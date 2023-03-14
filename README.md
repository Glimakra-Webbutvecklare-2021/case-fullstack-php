# Case Fullstack PHP
I caset ska en applikation kodas som lagrar data i en relationsdatabas. Applikationen fungerar för att en administratör ska kunna skriva och publicera enklare hemsidor eller blogg-inlägg förslagsvis kallad `Page`.

## Grundläggande krav
- Programspråk som får användas är PHP (utan ramverk), Javascript, HTML/CSS
- Visa alla hemsidor som är publicerade genom applikationen
- Administratör skall kunna:
  - Loggas in
  - Registera sig
  - Läsa, skapa, editera och ta bort resurs
  - Lösenordet skall vara kryperad innan det lagras i databasen
- Pages tabellen skall:
  - Ha minst fyra databas-kolumner utöver primary key (t.ex title, markdown_content, created_at, site_id)
  - Vara länkad på databasnivå till en användare
  - Hantera markdown (Det fungerar att spara ner det som text och låta klienten parsa markdown till html)
- Användare skall kunna:
  - Besöka flera olika användares sidor t.ex "thewebapp.com/username1/my-cool-site/about" och "thewebapp.com/username2/quick-blog/contact"
  
## Utmaning
Utöver alla grundläggande krav:
- Applikationen ska vara publicerad via Linode eller liknande hosting tjänst
- Administratör ska kunna spara Page som draft
- Pages ska kunna hantera bilder
- Besökare skall kunna:
  - Registera sig som intresserad av nyhetsbrev
 
## Feedback
Veckan efter presentation kommer feedback ges under följande rubriker:

- Databas-hantering
- Användarupplevelse
- Allmän kodstil

*Designfeedback tillkommer från Mattias*

Presentation- och Inlämningsdatum
Presenteras och in lämning för feedback 4 april kl 8.45. Tiden 4e till 6de april är feedbackperiod då ni får feedback, ni kan under tiden jobba med er portfolio och göra klart gamla case.
