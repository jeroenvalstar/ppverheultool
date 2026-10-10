# 2016 Gelb Paprika 2026 – registratie-app

Webapp voor de wekelijkse plantregistratie (PP Verheul Teeltadvies). Alle berekeningen uit het Excel-bestand *GELB_2016_Pflanzb_2026.xlsx* zitten één-op-één in `index.html`.

## Online zetten met GitHub Pages (gratis)

1. Log in op [github.com](https://github.com) en klik op **New repository**.
   Naam bijvoorbeeld `paprika-app`, zet hem op **Public** en klik **Create repository**.
2. Klik op **uploading an existing file**. Sleep **alle bestanden en de map `icons`** uit deze zip erin
   (`index.html`, `manifest.webmanifest`, `sw.js`, `.nojekyll`, `README.md`, `icons/`). Klik **Commit changes**.
3. Ga naar **Settings → Pages**. Kies bij *Source* **Deploy from a branch**, branch **main**, map **/ (root)** en klik **Save**.
4. Na 1–2 minuten staat de app op `https://<jouw-gebruikersnaam>.github.io/paprika-app/`.
5. Open die link op je telefoon en kies **Zet op beginscherm** (iPhone: deelknop; Android: menu ⋮). De app opent dan met het eigen icoon en werkt ook zonder internet.

> Let op: `.nojekyll` begint met een punt en is op een Mac/Windows soms verborgen. Zonder dat bestand werkt de app meestal ook, maar upload hem als het lukt.

## Een nieuwe versie plaatsen
Upload het nieuwe `index.html` op dezelfde manier (zelfde naam, het oude wordt vervangen). De telefoon haalt de nieuwe versie op bij de volgende keer openen met internet.

## Waar staan de gegevens?
- Alles wat je invult wordt bewaard **in de browser van het apparaat** waarop je het invult. Er gaat niets naar GitHub.
- Gebruik je twee apparaten (bijvoorbeeld telefoon in de kas en computer op kantoor)? Gebruik dan
  *Einstellungen → Daten → Sicherung speichern* op het ene apparaat en *Sicherung laden* op het andere.
- Maak regelmatig een back-up of een Excel-export; als je de browsergegevens wist, ben je de invoer kwijt.

## Gegevens uit de oude (Netlify-)versie overzetten
Als de oude site nog opent: ga daar naar *Instellingen → Gegevens → Weekoverzicht downloaden* (CSV).
Open daarna de nieuwe app en kies *Einstellungen → Daten → CSV aus der alten Version importieren*.
Instellingen die je in de oude versie had aangepast (bijv. maximum Joules), moet je daarna even opnieuw controleren.

## Privacy
Een openbare repository betekent dat iedereen met de link de app (en de beginwaarden uit het Excel-bestand) kan zien. Je eigen invoer blijft op je apparaat.
