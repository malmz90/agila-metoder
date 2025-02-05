# agila-metoder Av: Alexander Malmqvist

## Redogör för de olika momenten i en SCRUM sprint.

En sprint är en fast tidsperiod på 1–4 veckor där teamet levererar nytt värde till produkten. De korta arbetscyklerna gör det möjligt att regelbundet få feedback och anpassa både arbetsprocessen och produkten. När en sprint avslutas startar en ny direkt, vilket skapar ett kontinuerligt utvecklingsflöde.

### 1. Sprint planning
Man börjar sprinten med att planera vad som ska göras och hur. Hela Scrum-teamet samarbetar för att ta fram en plan. Produktägaren presenterar de viktigaste uppgifterna från produktbackloggen, och teamet väljer ut vad som ska ingå i sprinten. De diskuterar också vilket värde sprinten ska leverera och sätter upp ett tydligt mål. Utvecklingsteamet planerar sedan arbetet genom att bryta ner uppgifterna i mindre delar. Ingen annan bestämmer hur arbetet ska utföras teamet har full kontroll över hur de löser uppgifterna. Allt detta samlas i en sprint backlog som innehåller sprintmålet, de valda uppgifterna och planen för hur de ska genomföras.

### 2. Daily Scrum
Daily scrum är ett kort dagligt möte på 15 minuter där utvecklingsteamet synkar sitt arbete. Mötet hålls på samma tid och plats varje arbetsdag för att skapa rutin. Teamet väljer själva hur de vill strukturera mötet. Vanligtvis går varje teammedlem igenom vad de gjorde igår, vad de ska göra idag och om de stött på några hinder. Längre diskussioner eller andra frågor tas utanför detta möte för att behålla fokus och tidsramen.

### 3. Sprint Review
Sprint Review är ett möte som hålls i slutet av varje sprint där teamet presenterar vad de har åstadkommit för viktiga intressenter. Tillsammans diskuterar teamet och intressenterna resultatet och planerar framåt. De går igenom förändringar som skett och hur dessa påverkar kommande arbete. Utifrån diskussionerna kan produktbackloggen behöva uppdateras för att anpassas till nya behov. Mötet tidsbegränsas baserat på sprintens längd.

### 4. Sprint Retrospective
Sprint Retrospective är det avslutande mötet i sprinten där teamet utvärderar sitt arbete. Tillsammans går de igenom vad som fungerade bra, vilka problem som uppstod och hur de kan förbättra sitt arbetssätt. Teamet identifierar de viktigaste förbättringarna och planerar hur dessa ska genomföras. De mest betydelsefulla förbättringarna kan tas med direkt i nästa sprints backlog.

## Reflektera över hur ni i teamet skapade och rangordnade user-stories, vad fungerade bra? Vad skulle kunna fungera ännu bättre?
Vår process började med att vi gemensamt analyserade behoven för en insulin-app. Utifrån denna analys diskuterade vi hur våra user stories skulle utformas. Vi utgick från användarens perspektiv och började med de mest grundläggande funktionerna: skapa konto, logga in och lagra blodsockermätningar. Därefter byggde vi vidare och inkluderade även utvecklarens och produktägarens perspektiv. För att prioritera våra stories använde vi MoSCoW-metoden. Senare i arbetet fick vi feedback från en person med diabetes, vilket ledde till att vi skapade nya stories baserade på dessa insikter.

## Det som fungerade bra i denna process var:

- Att vi började med de mest grundläggande funktionerna gav en tydlig riktning. Det gjorde att vi kunde bygga upp funktionaliteten steg för steg och alla i teamet förstod vad som behövde göras först.  
- MoSCoW-metoden hjälpte oss inte bara att prioritera, utan gjorde det också tydligt för alla i teamet vad som var viktigast att få med i första versionen.
- Feedback från en person med diabetes gav oss värdefulla insikter om verkliga användarbehov. Detta hjälpte oss att förbättra våra user stories så de bättre matchade vad en användare faktiskt behöver i en insulin-app.


## Det som skulle kunna fungera ännu bättre:

- I efterhand hade det varit bättre om vi enbart fokuserade på användarens perspektiv och hur vi kunde skapa värde för denne.  
  När vi blandade in utvecklarens perspektiv blev det ibland otydligt och rörigt, vilket inte var nödvändigt eftersom vi ändå bryter ner stories till mer tekniska tasks.  
- I vår prioritetslista hade det varit bra att tydligt definiera vad en user story måste uppfylla för att klassas som Must have eller Should have osv.  
  Det skulle ha sparat tid och minskat behovet av att flytta om prioriteringar i efterhand.

## Hur skulle din process från user stories till faktisk funktionalitet i en app se ut? Använd någon av era user stories som exempel. Hur skulle du bryta ner en user stories i moment att arbeta med. När vet du om du är klar med en user story?
Som användare vill jag kunna se blodsockerkurva över vecka för att kunna avläsa mönster över tid

Jag skulle börja med att tänka på databasstrukturen, men vi kan anta att vi redan har blodsockervärden lagrade med tidstämpel för varje användare i databasen. Sedan skulle jag börja med backend-delen och därefter jobba med UI.

## Backend
1. Skapa en funktion som hämtar blodsockervärdena och tidstämpel på inloggad användare.
2. Skapa en funktion som filtrerar blodsockervärdena på tidstämpel för vald vecka.
3. Gör research på grafbibliotek eller hur vi kan använda oss av en graf
4. Implementera felhantering om data saknas eller är felaktig

## UI
6. Skapa en layout för grafen med en datumväljare
7. Implementera grafbiblioteket.
8. Lägg till interaktion för att välja vecka

En user story är klar när:
- Funktionaliteten är implementerad
- Koden är testad och granskad
- Användaren kan se sin blodsockerkurva över en vecka












