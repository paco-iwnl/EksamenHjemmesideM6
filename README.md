# OnTop Esports – Hjemmeside

Officiel hjemmeside for OnTop Esports Counter-Strike 2 klubben.

## Filstruktur

```
ontop/
├── index.html              ← Forside
├── css/
│   ├── style.css           ← Hoved-stylesheet (farver, navbar, layout, knapper)
│   └── components.css      ← Komponent-stylesheet (spillerkort, resultatkort osv.)
└── pages/
    ├── hold.html           ← Holdet / roster
    ├── resultater.html     ← Kampresultater
    ├── nyheder.html        ← Nyheder
    ├── om.html             ← Om os
    ├── sponsors.html       ← Sponsorer og partnere
    ├── rekruttering.html   ← Rekruttering
    └── kontakt.html        ← Kontaktformular
```

## Kom i gang

1. Klon repositoriet:
   ```bash
   git clone https://github.com/TODO/ontop-website.git
   ```
2. Åbn `index.html` i en browser eller brug **Live Server** i VS Code.

## Bidrag (workflow)

Vi bruger feature branches. Lav **aldrig** direkte commits til `main`.

```bash
# Opret ny branch til din feature
git checkout -b feature/dit-feature-navn

# Lav dine ændringer, commit løbende
git add .
git commit -m "Kort beskrivelse af hvad du har lavet"

# Push og åbn Pull Request på GitHub
git push origin feature/dit-feature-navn
```

## TODO – Features der mangler

Alle TODO-kommentarer i HTML-filerne markerer steder der skal udfyldes.

| Side              | Hvad mangler                                      |
|-------------------|--------------------------------------------------|
| `index.html`      | Rigtige facts/tal, rigtige nyhedsartikler         |
| `hold.html`       | Rigtige spillernavne, fotos, roller               |
| `resultater.html` | Rigtige kampresultater                            |
| `nyheder.html`    | Rigtige nyheder og artikler                       |
| `om.html`         | Klubtekst, mission og værdier                     |
| `sponsors.html`   | Sponsorlogoer og navne                            |
| `rekruttering.html` | Krav og åbne stillinger                         |
| `kontakt.html`    | Rigtige kontaktoplysninger og sociale medier      |

## Test
