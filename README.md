# Case Fullstack PHP
I caset ska en applikation kodas som lagrar data i en relationsdatabas. Applikationen fungerar för att en administratör ska kunna skriva och skicka nyhetsbrev. E-breven ska kunna skickas till samtliga emails kopplade till för de som är registerade mottagare.

## Grundläggande krav
- Programspråk som får användas är PHP (utan ramverk), Javascript, HTML/CSS
- Administratör skall kunna:
  - Loggas in
  - Registera sig
  - Läsa, skapa, editera och ta bort resurs
  - Lösenordet skall vara kryperad innan det lagras i databasen
 - Nyhetsbrev skall:
  - Ha minst tre databas-kolumner utöver primary key (t.ex subject, body, receiver)
  - Vara länkad på databasnivå till en användar
  - Hantera markdown (Det fungerar att spara ner det som text och låta klienten parsa markdown till html)
- Användare skall kunna:
  - Registera sig som intresserad av nyhetsbrev
  
## Utmaning
Utöver alla grundläggande krav:
- Applikationen ska vara publicerad via Linode eller liknande hosting tjänst
- Nyhetsbrevet ska kunna skicka bilder
- Användare skall kunna:
  - Avregistera sig som intresserad av nyhetsbrev
  - Välja mellan olika ämnen som intresserar dem t.ex Cooking eller Web development. Administratören ska kunna välja vilken intressegrupp för sitt nyhetsbrev.
 
## Feedback
Veckan efter presentation kommer feedback ges under följande rubriker:

- Databas-hantering
- Användarupplevelse
- Allmän kodstil

*Designfeedback tillkommer från Mattias*

Presentation- och Inlämningsdatum
Presenteras och in lämning för feedback 4 april kl 8.45. Tiden 4e till 6de april är feedbackperiod då ni får feedback, ni kan under tiden jobba med er portfolio och göra klart gamla case.
