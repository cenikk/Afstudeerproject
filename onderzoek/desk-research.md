# Desk research

## Onderzoeksvragen

1.  **Met welke digitale oplossing kan ik de overheidsorganisaties helpen?**

    1. Op welke device(s) moet de oplossing gemaakt worden.
    2. Behoort de oplossing tot de behoeftes van de potentiële gebruikers?
    3. Hoe werkt de oplossing?

    Allereerst moet er een **korte onderzoek** (desk-research) gedaan worden op welke device(s) de oplossing uiteindelijk gemaakt gaat worden. Hierbij kan ik alvast weten of het responsive moet zijn. Vervolgens is het ook belangrijk om te kijken naar de behoeftes van de potentiële gebruikers. Waar moet de oplossing uiteindelijk uit bestaan en wat is overbodig? Antwoorden op deze vragen kan ik vooral achterhalen uit **(expert) interviews**. Vanuit deze interviews kan ik vervolgens de eisen van de gebruiker in een lijst zetten (Programma van Eisen). Ook kan ik een persona maken die me telkens zal herinneren wie de eindgebruiker is en wat zijn/haar wensen zijn.
2.  **Welke data is gevoelig en op welke gegevens moet ik letten tijdens het maken van de digitale oplossing?**

    1. Moet de oplossing toegankelijk zijn voor iedereen?
    2. Welke consequenties zijn er mogelijk?
    3. Moet er verschillende versies gemaakt worden per overheidsorganisatie?

    Omdat we te maken hebben met gegevens van mensen is het natuurlijk niet geschikt om deze zomaar vrij te geven. Daarom moet er eerst een nader onderzoek gedaan worden naar de veiligheid en privacy binnen de oplossing. Het kan namelijk voorkomen dat een datalek kan plaatsvinden. Bij een datalek gaat het om toegang tot of vernietiging, wijziging of vrijkomen van persoonsgegevens bij een organisatie, zonder dat dit de bedoeling is van deze organisatie.
3.  **Welke gegevens moeten er worden achterhaald van een persoon?**

    1. Hoe weet de gebruiker wanneer een voertuig niet betaalbaar is voor de eigenaar ervan?
    2. Waar moet op gelet worden bij het achterhalen van de gegevens?
    3. Welke connecties moeten gelegd worden met de gegevens die beschikbaar zijn?

    Nadat een scan wordt uitgevoerd wordt er connecties gemaakt via iCOV met de gegevens van de eigenaar. Vanuit hier moet er vervolgens achterhaald kunnen worden onder wiens naam de auto officieel staat en of hij dit wel kan betalen. Dit kan achterhaald worden door bijvoorbeeld naar de jaarsalaris, hoeveelheid boetes en/of vastgoedwaarde te kijken van de eigenaar. Ook kan achterhaald worden of de kenteken wel een geldige is en dus de auto niet vervalst is.
4.  **Welke oplossingen bestaan er al en wat kan ik hieruit halen?**

    1. Zijn deze handig voor mijn stakeholders?
    2. Hoe werken deze oplossingen?

    Een goede voorbeeld is bijvoorbeeld _Cition_, waar ik een maatschappelijke stage heb gelopen in de verleden. Cition scant auto's om te kijken of ze wel hebben betaald om te parkeren waar ze geparkeerd zijn. Hetzelfde vorm van scannen zou ik uiteindelijk ook in mijn oplossing kunnen gebruiken, alleen dan met andere doeleinden.

## Benchmark

### Effectiever opsporen: de scanauto's

De roep om innovatie en vernieuwing in de opsporing wordt steeds luider. Maatschappeliike en technologische ontwikkelingen volgen elkaar snel op en ook criminelen laten en buitengewone wendbaarheid zien. Stilstaan is geen optie, we moeten meebewegen en slim inspelen op nieuwe ontwikkelingen.

De scanauto is zo'n ontwikkeling. Gemeenten zetten deze sinds 2009 in voor de handhaving van het parkeerbeleid. Het voertuig is voorzien van zes camera's en controleert de kentekens van geparkeerde voertuigen. Is er geen parkeergeld betaald, dan volgt automatisch een boete. Met betrekkelijk weinig auto's en dus weinig personeel zijn zij, dankzij de inzet van de scanauto's in staat in een groot gebied het parkeerbeleid te handhaven.

Sinds 2014 maken de gemeente en polite Amsterdam gezamenlijk gebruik van de scanauto's in de stad. Dit doen zij in het project Spookvoertuigen, waarvoor zij ook een convenant hebben gesloten. Bij de totstandkoming van het Convenant (in 2014) hebben de partijen zich uitvoerig laten adviseren en bijstaan door privacyfunctionarissen, om te garanderen dat het gezamenlijke gebruik van de scanauto juridisch correct zou plaatsvinden. Naast de controle voor de gemeente of er wel parkeergeld is betaald, wordt voor de politie ook gecontroleerd of een kenteken als gestolen staat geregistreerd. Anders dan bij een ANPR-hit, dat rijdende voertuigen controleert, heeft de politie met de scanauto's een middel in handen om stilstaande auto's, waar iets mis mee is, in het vizier te krijgen.

### Hoe werkt de scanauto?

De scanauto is uitgerust met een unit op het dak, waarin zich 12 camera’s bevinden. Terwijl de auto rijdt, scannen deze camera’s razendsnel alle kentekens die in het zicht vallen.

Wanneer er een kenteken gevonden wordt die niet voor de parkeerkosten betaalt, wordt er een signaal doorgestuurd naar een parkeerwachter op een scooter.

Binnen een paar minuten is de parkeerwachter aangekomen bij de auto. De tijd die tussen de scan en de daadwerkelijke controle zit, wordt ook wel de ‘handelingstijd’ genoemd. Dit is een vastgesteld aantal minuten, die de ruimte biedt om een parkeerkaartje te kopen of je aan te melden bij een parkeerapp. Blijkt na de handelingstijd dat het kenteken niet aangemeld is? Dan volgt de parkeerboete automatisch op je deurmat.

Maar er zijn uitzonderingen. In veel grote steden rijden de parkeerwachters op scooters inmiddels niet meer rond. Uit de praktijk is gebleken dat de auto in veel gevallen al binnen de handelingstijd vertrokken was. De scanauto deelt daarom in deze steden rechtstreeks boetes uit.

#### Hoe gebruikt het systeem de data?

Algoritmen worden gebruikt:

* om de kentekenplaat te lokaliseren in de camerabeelden;
* om de afbeeldingen aan te passen voor identificatie en;
* om de individuele karakters van de kentekenplaat te identificeren.

Als een kentekenplaat is geïdentificeerd en verwerkt, dan worden de kentekengegevens voor verdere verwerking naar het Nationaal Parkeerregister (NPR) gestuurd. Een algoritme van NPR controleert vervolgens de geldigheid van parkeerrechten voor het kenteken op een bepaalde tijd en locatie. Een positieve uitslag betekent dat de auto geldige parkeerrechten heeft. In dat geval worden de scangegevens van de kentekenplaat binnen 48 uur verwijderd. Bij een negatieve uitslag worden de beelden gecontroleerd door een medewerker van EGIS Parking Services B.V., die in opdracht van de gemeente Amsterdam de parkeercontrole uitvoert.

## Productvisie

De oplossing gaat uit naar een app voor op de mobiel, met voorkeur IOS. Dit met name omdat de app op straat door de politie (motoragent) gebruikt zal worden. De reden dat de voorkeur op IOS ligt, is omdat de politie al voorbestemd is met IOS-apparatuur. Daarnaast krijg ik ook steun van een app-developer die bij Apple werkt. Samen met hem zal er gekeken worden naar de mogelijkheden en opties die de app zal bieden. Ook om het misschien uiteindelijk op de markt te zetten voor de overheidsorganisaties.

Zo zijn we na wat besprekingen uitgekomen op een app, die voor nu de naam SCENR heeft. SCENR is een app die het mogelijk maakt om de kentekens van auto's te scannen. Nadat je een scan uitvoert, wordt gegevens van het persoon onder wiens naam het auto geregistreerd staat weergeven. Deze gegevens worden weergeven in de vorm van componenten. Een component kan bijvoorbeeld zijn de jaarsalaris van een persoon. Stel een persoon verdient €30.000,- per jaar maar heeft een auto t.w.v. €80.000,- op zijn naam, dan gaan er al gelijk wat lichtjes branden. In dit geval kleurt de component dan rood en mocht het zo zijn dat er meerdere componenten rood kleuren, kan er een melding gedaan worden.

Hieronder een eerste inzicht in wat de app ongeveer moet kunnen:

![](<../.gitbook/assets/image (13) (1).png>)
