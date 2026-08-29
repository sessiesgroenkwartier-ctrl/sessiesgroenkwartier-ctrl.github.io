# Groen Kwartier Sessies

Statische website voor de maandelijkse huiskamerconcerten in het Groen Kwartier, Antwerpen.
Platte HTML en CSS, geen framework, geen build-stap, geen backend. Wordt gehost op GitHub Pages.

**Om dit online te zetten: lees `opzet/INSTRUCTIES.md`.**

## Structuur

| Bestand | Wat het doet |
|---|---|
| `index.html` | Homepage: intro, komende sessies, praktisch |
| `sessies/2026-10-03-klaas.html` | Eventpagina KLAAS |
| `sessies/TEMPLATE-nieuw-event.html` | Kopieerbaar template voor een volgende sessie |
| `privacy.html` | Privacyverklaring (GDPR) |
| `css/stijl.css` | Alle styling, één bestand |
| `img/artiesten/` | Artiestfoto's: `naam.jpg` (1400px) en `naam-klein.jpg` (600px) |
| `img/qr-*.svg` / `.png` | QR-code naar de site (ongebruikt, mag blijven staan) |
| `opzet/maak-formulier.gs` | Apps Script dat het formulier, de Sheet en de bevestigingsmail in één keer opzet |
| `opzet/inschrijvingen.gs` | Hetzelfde, maar voor een handmatig aangemaakt formulier |
| `opzet/INSTRUCTIES.md` | Stap-voor-stap opzetten: domein, formulier, script, hosting |
| `opzet/WERKWIJZE.md` | Wie doet wat bij een nieuwe artiest, en via welke methode |
| `CNAME` | Het domein voor GitHub Pages |
| `.nojekyll` | Voorkomt dat GitHub de bestanden door Jekyll haalt |

## Vaste keuzes

- **Kleuren:** olijfgroen `#41462F`, crème `#F2EEE5`, zand `#EAE0D6`, beige `#E2D2C3`
- **Letters:** Cormorant Garamond (titels), Petit Formal Script (slogan), Lato (body)
- **Capaciteit:** 60 plaatsen per sessie, inschrijven per persoon
- **Locatie:** publiek altijd "Groen Kwartier, Antwerpen" — het volledige adres staat
  uitsluitend in de bevestigingsmail
- **Betalen:** ter plaatse, geen online betaling
- **Taal:** enkel Nederlands

Achtergrond bij deze keuzes staat in `IMPLEMENTATIE.md` in de werkmap.
