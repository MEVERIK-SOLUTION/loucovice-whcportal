# WHC Portal - Pravidla pro AI agenty

## Git workflow
- Pracuj vzdy na feature/fix vetvi, nikdy na `main`.
- Commit po kazdem logickem kroku, ne jen na konci.
- Push vetve vytvori automaticky Vercel Preview URL.
- Merge do `main` pouze po explicitnim schvaleni uzivatelem.

## Vercel deploy strategie
- Preview: automaticky z kazde vetve.
- Production (`main`): pouze po review a schvaleni.
- Produkcni URL: https://loucovice-whcportal.vercel.app/

## Kodovaci standardy
- Projekt je pure HTML/CSS/JS, bez npm a bez build kroku.
- Veskerne zmeny provadej primarne v `Loucovice_index.helloweb/index.html`, pokud zadani neurci jinak.
- CSS drzet inline ve `<style>` tagu nebo v separatim souboru ve slozce projektu.
- Chart.js nacitat pres CDN, `responsive: true` je povinne.

## Komunikace
- Po kazdem push vypsat Preview URL.
- Cekat na schvaleni pred merge do `main`.
