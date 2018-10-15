# Uppgift Gubbspel

## Instruktioner för workspace - GÖR DETTA FÖRST
- Gör en egen branch med kommandot i bash:
    git checkout -b dittnamnistället
- Kör bash-filen upgrade.sh med kommandot: 
    bash upgrade.sh
- Dela ditt workspace med johkel
- Utgå från filerna du fick och skapa nya efter behov
- Inlämning på Classroom i form av en länk till detta workspace

## Uppgift
- Gör om den statiska sidan till dynamisk
- Funktioner som kunden kräver (grundkrav)
    - Visa alla gubbar
    - Redigera en gubbe
    - Skapa en gubbe (utan bild)
    - Ta bort en gubbe
- Funktioner som kunden önskar (om du hinner)
    - Att det skapas arméer i menyn automatiskt och att de är klickbara för att visa enbart en armé
    - Login krävs för att skapa, redigera och ta bort
    - Filuppladdning så att man kan lägga till eller byta bild på gubbe
    - Att kunna söka efter namnet på en gubbe i sökrutan och få en lista med förslag på något sätt
    - Varning när man tar bort gubbe
  

## Tips
- Du behöver skapa en tabell i din db
- Du behöver koppla ihop php med db med pdo
- Börja med det enklaste - att bara läsa från tabellen - och ersätt sedan den statiska html-koden med html skapad av php
- Du kan behöva ändra filtyp på index.html till .php
- Återanvänd det vi gjort tidigare!
