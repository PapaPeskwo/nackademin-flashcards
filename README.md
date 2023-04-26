<!-- TOC start  -->
# Table of Contents
- [Nackademin Flashcards](#nackademin%20flashcards)
	- [Om Obsidian](#om%20obsidian)
	- [Flashcards i Obsidian](#flashcards%20i%20obsidian)
- [Vad gör jag när jag har installerat Obsidian och klonat repot?](#vad%20gör%20jag%20när%20jag%20har%20installerat%20obsidian%20och%20klonat%20repot)
	- [Farbror Tomi, hur skapar man flashcards?](#farbror%20tomi%20hur%20skapar%20man%20flashcards)
- [Bidra](#bidra)
	- [Skapa en Pull Request från en Fork till Master-Branch](#skapa%20en%20pull%20request%20från%20en%20fork%20till%20master-branch)
	- [Uppdatera en Fork med Ändringar från Master-Branch](#uppdatera%20en%20fork%20med%20ändringar%20från%20master-branch)

<!-- TOC end -->

# Nackademin Flashcards
Välkommen till klassens GitHub Repository för Obsidian Flashcards! Det här repot innehåller en samling flashcards som är skapade för att användas tillsammans med Obsidian, en kraftfull kunskapsbas och anteckningsapp. Detta projekt är gjort för klassen och kommer uppdateras framöver. Tanken är att vi tillsammans skapar frågor och svar som vi kan använda för att studera inför tentor.

## Om Obsidian

Obsidian är en anteckningsapp som är byggd på idén om att länka dina tankar och idéer med varandra. Det låter dig skapa en sömlös webb av kunskap genom att använda länkar, taggar och inbäddade anteckningar. Det är en utmärkt resurs för att organisera och återkoppla till din inlärning.

Om du inte redan har Obsidian installerat, kan du ladda ner det här:

-   [Obsidian för Windows, MacOS och Linux](https://obsidian.md/download)

## Flashcards i Obsidian
För att förstå hur detta är upplagt så kan du kolla på denna video för att förstå lite mer. Detta projekt är byggt på hans upplägg:

[PRODUCTIVELY Learning New Things Using Obsidian](https://www.youtube.com/watch?v=DwSNZEW6jCU)

Pluginet vi använder för detta heter 'Spaced Repetitions' och kommer med repot om du klickar **'Trust author and enable plugins'**. De borde komma konfigurerade med det jag har ändrat på. Du kan dubbelkolla så att allt är rätt:
**Settings>Community Plugins>Spaced Repetition**
Flashcard tags borde ha '#Network' innuti
Separator for inline flashcards borde vara ';;'

# Vad gör jag när jag har installerat Obsidian och klonat repot?

Klicka på ikonen här under för att starta Spaced Repetition (flashcards) pluginet
![[Capture.PNG]]
### Farbror Tomi, hur skapar man flashcards?
Jo min son, du börjar med att skapa ett dokument innuti rätt kursmapp och döper det till något logiskt så att vi andra förstår.

Du kan skapa flashcards på två sätt:

```
fråga;;svar

eller

fråga
?
svar
svar
svar
```

Notera: om du använder det andra sättet måste det vara mellanrum innan frågan och efter sista svaret, annars kan det bli tokigt. Ett exempel finns i repot.

## Bidra
### Skapa en Pull Request från en Fork till Master-Branch

För att skapa en pull request från en fork till din master-branch via terminalen, bör bidragsgivaren följa dessa steg:

1.  Klona deras fork till den lokala datorn (om de inte redan har gjort det) med kommandot:
```bash
git clone https://github.com/PapaPeskwo/nackademin-flashcards
```

2.  Lägg till din master-branch som en "remote" för att kunna synkronisera ändringar:
```bash
git remote add upstream https://github.com/PapaPeskwo/nackademin-flashcards
```

3.  Skapa en ny branch där de kan göra sina ändringar:
```bash
git checkout -b ny-branch
```

Byt ut `ny-branch` med ett lämpligt namn branchen.

4.  Gör ändringar i koden och commita dem:
```bash
git status
git add <ändrade_filen>
git commit -m "Beskrivning av ändringarna"
```

5.  Skicka ändringarna till deras fork på GitHub:
```bash
git push origin ny-branch
```

6.  Gå till GitHub, navigera till forkens huvudsida och klicka på "Compare & pull request" bredvid den nya branchen. Följ instruktionerna för att skapa en pull request.

### Uppdatera en Fork med Ändringar från Master-Branch

För att uppdatera en fork med ändringar från master-branchen, bör andra användare följa dessa steg:

1.  Lägg till din master-branch som en "remote" för att kunna synkronisera ändringar:
```bash
git remote add upstream https://github.com/PapaPeskwo/nackademin-flashcards
```

2.  Hämta ändringarna från din master-branch:
```bash
git fetch upstream
```

3.  Byt till deras lokala master-branch:
```bash
git checkout master
```

4.  Merge ändringarna från din master-branch in i deras lokala master-branch:
```bash
git merge upstream/master
```
