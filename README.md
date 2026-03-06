# Secure Local PDF Page Counter / Säker Lokal PDF-sidräknare

*(Svensk beskrivning finns längre ner)*

A standalone, client-side tool built to automate page counting and price calculation for PDF documents. Developed with **Privacy by Design**, specifically tailored for public sector environments and organizations handling sensitive or confidential information.

## Features
* [cite_start]**100% Client-Side Execution:** All processing happens locally in the browser's memory (RAM)[cite: 9, 14]. [cite_start]No data is ever uploaded, transferred, or saved to disk[cite: 17].
* [cite_start]**Zero External Dependencies:** Uses a locally stored version of the `pdf.js` library[cite: 10]. [cite_start]There are no external network calls (e.g., to CDNs), completely eliminating the risk of supply chain attacks[cite: 36].
* **Automated Cost Calculation:** Calculates fees based on established public tariffs (Base fee of 50 SEK for pages 1–10, followed by 2 SEK for each additional page).
* [cite_start]**High Security & GDPR Compliant:** Meets strict information security requirements (Confidentiality Level 3)[cite: 24]. [cite_start]Since no data leaves the user's device, it requires no Data Processing Agreements (DPA) [cite: 39] [cite_start]or Data Protection Impact Assessments (DPIA)[cite: 81].

## How to Use
1. Download or clone the repository.
2. Open `index.html` in any modern web browser (Edge, Chrome, Firefox).
3. Select a PDF file to instantly get the page count and calculated fee.

---

# Svensk Beskrivning

[cite_start]Ett fristående, lokalt webbverktyg (HTML/JS) skapat för att automatisera sidräkning och kostnadsberäkning vid utlämnande av PDF-handlingar[cite: 5, 6]. Utvecklat med **Privacy by Design** för offentlig sektor och miljöer med höga krav på informationssäkerhet.

## Funktioner
* [cite_start]**100 % Lokal körning:** All databearbetning sker uteslutande i webbläsarens arbetsminne (RAM)[cite: 9]. [cite_start]Ingen information lämnar handläggarens dator[cite: 17]. [cite_start]När fliken stängs raderas all data ur minnet[cite: 16].
* [cite_start]**Inga externa beroenden:** Använder ett lokalt lagrat `pdf.js`-bibliotek[cite: 10]. Inga nätverksanrop görs, vilket innebär att verktyget fungerar helt offline och är skyddat mot s.k. [cite_start]"Supply Chain"-attacker[cite: 36].
* **Automatisk prisberäkning:** Avgiften beräknas i enlighet med fastställd taxa för utlämnande av allmän handling. Grundavgiften uppgår till 50 kr för de första 10 sidorna, följt av ett tillägg om 2 kr för varje nästföljande sida.
* [cite_start]**Informationssäkerhet & Dataskydd:** Applikationen är utformad för att hantera skyddsvärd information (Konfidentialitet: Nivå 3)[cite: 24]. [cite_start]Eftersom ingen överföring sker till tredje part uppstår inget personuppgiftsbiträdesförhållande[cite: 20].

## Användning
1. Ladda ner filerna till din dator.
2. Öppna filen `index.html` i en modern webbläsare.
3. Välj en PDF-fil för att direkt se antal sidor och beräknad kostnad enligt gällande taxa.
