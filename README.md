# webapp version NY

### Generellt

* Tydligare spår och fokus
* GUI och enbart frontend
* Accessibility (a11y)

## KMOM01 - JavaScript ramverk

Intro till JavaScript ramverk och SPA applikationer
Utgå från den typ av kod vi skrev i js1

GUI/a11y: Navigation och typografi, screenreaders, alt tagg.

Uppgift:
Skapa en me-sida, övningen ger det mesta, där vi börjar med `element.innerHTML = ''` och slutar i ett ramverk.

Löpande uppgift i ramverket: Ett ordersystem, kmom01 startar lugnt med grunderna till en packlista app, använda `GET` för att hämta order . Fokus på nav och storlek på typsnitt för desktop och mobil.

#### Återanvända:
Läs igenom tipset om “Developer tools i webbläsaren för mobila enheter”.

Om mithril: Det mesta förutom Cordova.

## KMOM02 - Mobila enheters begränsningar

Börja bygga på den löpande uppgift, introducera testning av frontend kod? jest?

GUI/a11y: Knapper, Begränsningar på mobila enheter svårt att klicka på små länkar.

Begränsning av internet hastighet på mobila enheter, throttling i webbläsaren.

Uppgift: Fortsätta med packlistan, skapa knappar för att ta på sig packlista och ändra status när ordern är packad. Fokus på att använda `PUT` via `fetch`.

#### Återanvända:

Övningar:
Läs igenom artikeln och installera “Utvecklingsverktyg för REST tjänster”.

Installera och testa verktyget jq via artikeln “Installera verktyget jq för att söka i JSON-filer”.

Läs igenom artikeln “Enhetens storlek och orientering”.

Uppgifter:
Gör uppgiften “Sökverktyg för JSON filer”.

## KMOM03 - Formulär och CRUD

GUI/a11y: Formulär och inputs avsaknad av kontext och svårt att skriva snabbt, CSS grid?

Uppgift: Löpande uppgift, fokus formulär/skapa och ta bort data. Använda `POST` och `DELETE` för att hantera ordrar och produkter. Bygga en klient för orderstatus för beställaren.

## KMOM04 - Autentisering med JWT

Auth / JWT

GUI/a11y: Tabeller - scrolla i sidled, veckla ut raden

Uppgift: Löpande uppgift, fokus tabeller både stora och små skärmar. Ett lager av autentisering med JWT för att kunna packa ordrar och se egna beställningar.

## KMOM05 - Native

Native implementation. Cordova? Android? React Native?

GUI/a11y: Designa så det ser ut som native appar och använda de inbyggda a11y funktioner i mobila enheter.

Uppgift: Portera och bygga klienterna i android/iOS.

## KMOM06 - Mobila enheters styrkor

Använda mobila enheternas styrkor, kamera, GPS och positionering, online/offline, splashscreens, ikoner.

GUI/a11y: Tydliga ikoner, tydlig visning av online/offline, bygga vidare på integration mot de mobila plattformerna. Släppa på app store/google play?

Uppgift: Använda kamera för att visa packningen i kundens klient. GPS och karta för position av paketet.

## PROJEKT - Projekt och examination

Från github issues: Order/affärssystem med olika klienter beroende på vem som är slutanvändare. Lagerarbetaren får upp packlistor i en app, ekonomiansvarig får upp fakturor att skicka ut (eventuellt i desktop och mobil miljö), beställaren får uppdateringar på status i en annan app och så vidare.

Om studenterna har gjort en eller två av klienterna under kursens gång i de olika kursmomenten bygger vi ihop det hela i projektet. Kan tänka mig att klienten för ekonomiansvarig/admin är det som är bäst lämpat för projektet, där man där kan jobba med både desktop och mobila vyer, samt att det finns oanade möjligheter för extra krav. En bonus är att studenterna redan har mycket test data de kan använda när de har byggt upp databasen under kursens gång.

#### a11y länkar

https://www.w3.org/standards/webdesign/accessibility

https://www.w3.org/TR/2008/REC-WCAG20-20081211/

https://www.apple.com/accessibility/

https://www.google.com/accessibility/

https://www.microsoft.com/en-us/accessibility/default.aspx

https://a11yproject.com


## Fritext kommentarer utvärdering kursen LP4 2017

Kursmomenten varit lite väl repetitiva, jag hade gärna sett att svårighetsgraden hade ökat mer mellan momenten. Androidemuleringen har inte varit helt tillfredsställande.

för mycket upprepning av API-integration och för lite utnyttjande av mobilplattformen som sådan. totalt fel val av ramverk.

den mobila plattformens unika möjligheter har nästan inte utnyttjats (eller berörts) alls och genomgångar av det responsiva tänket har det varit väldigt skralt med. emulatorn har inte fungerat över huvud taget.

Jag är inte så förtjust i upplägget på projektarbetet. Lite otydligt vad som förväntas

igen: fel fokus och en icke-fungerande emulator

Ökad svårighetsgrad mellan kursmomenten och mindre "upprepning" av REST API:er. Använda ett ramverk som används i större utsträckning på arbetsmarknaden.

Kanske använda ett ramverk som eftersöks av arbetsmarknaden så vi som elever får det tillgodo när vi ska ut i arbetslivet.

1) Byt ut Mithril! Det går inte att basera en hel kurs på ett ramverk som knappt används och definitivt inte efterfrågas ute i arbetslivet. Det är dessutom otroligt krångligt att använda för mer komplexa gränssnitt, är fullt av buggar och tveksamma designval samt saknar helt och hållet GUI-komponenter. Allt som allt är det fullständigt olämpligt för mobil apputveckling.

2) Utnyttja mobilplattformens möjligheter! Nu är det mest bara "minska webbläsarfönstret och låtsas som att det är en mobil". Kamera, GPS, QR-skanner, trycksensor... finns hur mycket som helst!

3) Lös problemen med emulatorn, på ett eller annat sätt!

Det hade varit roligare att jobba med ett ramverk som har större användning i arbetsmiljö

Älskade kursmoment 3 när man fick lära sig om flex. Hade gärna sett ett extra kursmoment av det.

Annars riktigt bra kurs. Tycker att jag förstod Mithril rätt så bra i slutändan. Intressant att använda ramverk för Javascript för första gången.
