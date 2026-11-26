# VDNJ boards

Live digital-signage boards for the VDNJ Mandir screens (OptiSigns), hosted free on GitHub Pages.

- `dainik-thaal/` – Weekly Donation & Thaal Seva list. Reads a published Google Sheet CSV whose id is passed in the page address (?s=...&gid=...), so no sheet link is stored in this repo every time it loads and every 60 s, shows the latest Sunday–Saturday week from the Date column, 22 names per page. Settings are at the top of `index.html`.
