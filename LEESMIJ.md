# M1 Vision portfoliowebsite

Bestanden: `index.html` (de hele site), `logo.png`, `mark.png`, `mark-wit.png`, `favicon.png`.

## Een video toevoegen
Open `index.html` en zoek `const VIDEOS = [`. Kopieer een regel en pas de link, titel en tekst aan:

- Instagram: `{ soort: "instagram", link: "https://www.instagram.com/reel/XXXX/", titel: "Titel", tekst: "Korte uitleg" },`
- YouTube: `{ soort: "youtube", link: "https://youtu.be/XXXX", titel: "Titel", tekst: "...", breed: true },`
- Eigen mp4: zet het bestand in de map `videos/` en gebruik `{ soort: "video", bestand: "videos/naam.mp4", poster: "videos/naam.jpg", titel: "Titel", tekst: "..." },` (voeg `vierkant: true` toe voor 1:1 of `breed: true` voor 16:9). Houd video's liefst onder 25 MB.

`LEGE_VAKJES` bepaalt hoeveel "Nieuwe video binnenkort"-vakjes er staan (zet op 0 als je genoeg video's hebt).
