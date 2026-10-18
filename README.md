# ST-tracker för kardiologi

Ett Excel-verktyg för ST-läkare i kardiologi. Varje ST-läkare har en egen fil
där man följer sin utbildning:

- **Lärandemål per delblock** (Ischemi, HIA, Hjärtsvikt & klaff, Arytmi) med
  målnivå, självskattning och föreslagen bedömning
- **Delmål a–c** enligt SOSFS 2015:8 för internmedicin och kardiologi
- **ST-tid** med uppehåll (föräldraledighet, forskning m.m.) som flyttar fram slutdatumet
- **Placeringar** – veckor på akuten, avdelning, HIA och mottagning
- **Dashboard** som samlar progressionen på ett ställe

Utvecklat vid Hjärtkliniken, Danderyds sjukhus.

## Ladda ner

1. Klicka på **RK_ST_Tracker.xlsm** i listan ovan.
2. Klicka på nedladdningsikonen (pil nedåt) till höger.
3. Spara filen på datorn och döp om den med ditt namn,
   t.ex. `ST_Tracker_Rozh.xlsm`.

## Öppna filen första gången

Filen innehåller makron som sköter knapparna och de automatiska datumen.
Excel stoppar makron i nedladdade filer, så första gången behöver du tillåta dem.

### Windows

1. Högerklicka på filen och välj **Egenskaper**.
2. På fliken **Allmänt**, längst ned: bocka i **Avblockera** och klicka **OK**.
3. Öppna filen. Klicka **Aktivera redigering** och sedan **Aktivera innehåll**.

Ser du en röd list med **SÄKERHETSRISK**? Stäng Excel och gör steg 1–2 igen.

### Mac

1. Öppna filen i Excel.
2. Klicka **Aktivera makron** när Excel frågar (det gör den varje gång).

Kommer ingen fråga? Välj **Excel → Inställningar → Säkerhet** och markera
**Inaktivera alla makron med ett meddelande**. Öppna filen igen.

### Om makron inte fungerar

- Vissa jobbdatorer spärrar alla makron. Filen fungerar ändå – formler,
  rullistor och färger. Det som inte fungerar är knapparna *Uppdatera progression*
  och *Visa ej klara mål*, och att datum fylls i automatiskt.
  Skriv då datumet själv (**Ctrl + ;** ger dagens datum).
- Excel på webben, i Teams eller på iPad/mobil kör inga makron.
  Använd Excel på datorn.
- Spara alltid som **.xlsm**. Sparar du som .xlsx försvinner makrona.

## Kom igång

1. **Bakgrund** – fyll i namn och ST-startdatum.
2. **Tid & placeringar** – lägg in eventuella uppehåll och dina placeringar.
3. **Blockflikarna** – skatta din nivå (1–5) för varje lärandemål.
4. **Delmål internmedicin / kardiologi** – välj *Klar* eller *Ej klar*.
5. **Dashboard** – se din progression. Ta med den till blocksamtalen.

Gula fält fyller du i. Övriga fält räknas ut automatiskt.

## Källor

Lärandemålen bygger på Svenska Kardiologföreningens Kompetensbeskrivning 2022
(uppdaterad 24 oktober 2024) och Socialstyrelsens föreskrifter SOSFS 2015:8.

## Licens

[CC BY-NC 4.0](LICENSE) – fri att använda och ändra, men inte i kommersiellt syfte.
Texterna från SvKF och Socialstyrelsen omfattas inte av licensen.

## Kontakt

Rozh Kader, ST-läkare, Hjärtkliniken, Danderyds sjukhus
rozh.kader@ki.se
