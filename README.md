# Gemeentemonitor SED

Volgt automatisch wat de gemeenten Stede Broec, Enkhuizen en Drechterland publiceren, besluiten en wijzigen,
en wat de media erover schrijven. Dashboard: https://martijnstb.github.io/monitor-sed/

Bronnen:
- Officiële bekendmakingen (KOOP): vergunningen, verordeningen, besluiten uit het Gemeenteblad
- Raad van Enkhuizen en Drechterland: vergaderingen, agenda's en raadsstukken (GO. vergaderen,
  gemeenteraad.enkhuizen.nl en gemeenteraad.drechterland.nl)
- Raad van Stede Broec: nog niet; gemeenteraad.stedebroec.nl heeft een botcontrole (wacht op uitzondering)
- Nieuws: de Actueel-pagina's van de drie gemeenten
- Woo-publicaties (open.overheid.nl)
- In de media: Google Nieuws op de gemeenten en hun woonplaatsen

De monitor draait elke 15 minuten (GitHub Actions, aangezet via cron-job.org).
Trefwoorden voor directe pushmeldingen staan in `trefwoorden.txt`.
