# Leren typen ⌨️

Een speelse website waarmee kinderen leren typen. Alles zit in één bestand, `Typen_oefenen.html`. Je hebt geen installatie, account of internet nodig: open het bestand in een browser en begin. Het werkt op een computer en op een tablet.

## Zo open je de website

1. Download `Typen_oefenen.html` (of de hele map).
2. Dubbelklik op het bestand. Het opent in je browser (Chrome, Edge, Safari of Firefox).
3. Klik in het typvak en begin met typen.

> `Typen_oefenen1.txt` is een kopie van dezelfde pagina als tekstbestand. Handig als een `.html`-bestand niet gedeeld of geüpload mag worden: hernoem het dan naar `.html`.

## De opdrachten

Je begint bij **Makkelijk**. Maak je een opdracht af, dan gaat de volgende open.

| Niveau | Wat oefen je? |
|---|---|
| **Makkelijk** | Alleen kleine letters en spaties. |
| **Normaal** | Hoofdletters (Shift), punten, komma's en Enter voor een nieuwe regel. |
| **Moeilijk** | Speciale tekens zoals `( ) ? / @` en Enter. |
| **Kleur typen** | Typ eerst een tekst foutloos over. Geef daarna woorden de goede kleur, grootte of vetgedruktheid, zoals in het voorbeeld. |
| **⚡ Snelheid** | Een snelheidsspel om vrij te oefenen (zie hieronder). |

Tijdens het typen zie je:

- welke letter de volgende is (blauw onderstreept);
- goede letters in groen en foute letters in rood;
- een **spiekbriefje** met de toets die je nu nodig hebt (Spatie, Enter, Shift, enzovoort);
- je **WPM** (woorden per minuut), **nauwkeurigheid**, **tijd**, aantal **fouten** en hoeveel **regels** klaar zijn.

Na Kleur typen geeft de knop **Eindresultaat 🎉** een cijfer van 1 tot 10 voor alle niveaus samen.

Plakken werkt niet: je moet de woorden echt zelf typen. 😉

## ⚡ Snelheid typen

Na Kleur typen kun je kiezen voor **Door naar Snelheid ⚡**. Dan laat het scherm alleen nog dit spel zien. Met **← Terug naar levels** ga je terug.

**Instellingen**

- **standaard**: alleen kleine woorden met spaties.
- **moeilijk**: echte zinnen. Elke zin begint met een hoofdletter, er staan leestekens in (`, : ( ) / . ? !`) en aan het eind van elke zin druk je op **Enter** (het teken ↵).
- **tijd** (15, 30, 60 of 120 seconden) of **woorden** (10, 25, 50 of 100 woorden).

**Spelen**

- De tekst bestaat uit willekeurige Nederlandse woorden, gekozen uit een lijst van ruim 1100 woorden. Elke ronde is dus anders.
- De tijd start zodra je de eerste letter typt.
- Met **spatie** ga je naar het volgende woord. Zit er een fout in het vorige woord, dan kun je met Backspace terug.
- Het scherm springt vanzelf naar de regel waarop je typt. Ook op een tablet met het schermtoetsenbord open blijft je tekst dus in beeld.

**Resultaat**

Na de ronde zie je je wpm, nauwkeurigheid, rauwe snelheid, aantal tekens (goed, fout, extra, gemist) en een grafiek van je snelheid per seconde. Een nieuwe ronde start alleen als je op een van deze knoppen klikt:

- **↻ Opnieuw (tegen je ghost 👻)**: dezelfde tekst nog eens. Een paarse cursor laat zien hoe snel je de vorige keer was, en in de grafiek zie je je vorige ronde als stippellijn. Kun je je ghost verslaan?
- **Volgende tekst ▶**: een helemaal nieuwe tekst.

Je keuze voor standaard of moeilijk en tijd of woorden onthoudt de browser voor de volgende keer.

## Voor makers

- Alles (HTML, CSS en JavaScript) staat in `Typen_oefenen.html`. Er zijn geen externe bibliotheken.
- Pas je de pagina aan? Kopieer de nieuwe versie dan ook naar `Typen_oefenen1.txt`, zodat beide hetzelfde blijven.
- De teksten van de niveaus staan bovenaan het script (`EASY_WORDS`, `NORMAL_TEXT`, `HARD_TEXT`, `STYLE_TEXT`). De woordenlijst voor Snelheid typen staat in `WORD_LIST`.
