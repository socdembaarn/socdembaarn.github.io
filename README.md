# Sociaal Democraten Baarn - Digitaal Platform

**Een snel, veilig en toegankelijk platform voor de inwoners van Baarn, gebouwd met Jekyll op basis van het Stately-framework.**

Dit project is de statische opvolger van de eerdere online omgeving van de Sociaal Democraten Baarn. Door te kiezen voor een statische architectuur garanderen we maximale veiligheid, razendsnelle laadtijden en een transparante manier van informatievoorziening voor alle inwoners van Baarn.

---

## 🚩 De Kern: Politiek met de Menselijke Maat
De website is niet alleen een zender van informatie, maar een brug tussen de fractie en de burger. De structuur is ontworpen rondom drie kernzuilen:
* **Leden & Teams:** Transparante weergave van de fractie, het bestuur en de politieke vertegenwoordigers in dynamische grids.
* **Dossiers:** Diepgravende informatie over lokale thema's zoals wonen, zorg en duurzaamheid in Baarn.
* **Interactie:** Een toegankelijk verkiezingsprogramma en een actuele campagne-agenda.

## 🛠 Technische Architectuur
Het platform maakt gebruik van de volgende technieken:
* **Engine:** [Jekyll](https://jekyllrb.com/) (Static Site Generator).
* **Basis:** Geoptimaliseerde versie van het [Stately](https://github.com/pmarsceill/stately) thema.
* **Data-gedreven:** Gebruik van Jekyll Collections voor het beheren van leden (`_members`), dossiers (`_dossiers`) en standpunten.
* **Hosting:** GitHub Pages met geautomatiseerde CI/CD via GitHub Actions.

## 🎨 Huisstijl & Design
De visuele identiteit volgt de vastgestelde richtlijnen voor digitale publicaties:
* **Kleur:** Primair Rood (`#DF111A`).
* **Typografie:** Helvetica Bold voor koppen (compacte interlinie) en Helvetica Regular voor bodytekst.
* **Layout:** Focus op leesbaarheid en toegankelijkheid (B2/C1 taalniveau).

## 📄 Licenties (Gelaagde aanpak)
Dit project maakt onderscheid tussen de technische motor en de politieke inhoud:

1.  **Code (De Motor):** De technische structuur, scripts en layouts vallen onder de **MIT-licentie**. Dit staat andere lokale fracties of afdelingen toe om deze architectuur te hergebruiken.
2.  **Content (De Boodschap):** Alle teksten, blogposts, dossiers en politieke standpunten vallen onder de **Creative Commons Naamsvermelding-NietCommercieel-GeenAfgeleideWerken (CC BY-NC-ND 4.0)** licentie.
3.  **Branding:** De auteursrechten op het logo en de specifieke huisstijl berusten bij de vereniging Sociaal Democraten Baarn.

---

## 🚀 Ontwikkeling
Om lokaal aan de site te werken:
1. Kloon de repository.
2. Installeer dependencies: `bundle install`.
3. Start de server: `bundle exec jekyll serve`.
