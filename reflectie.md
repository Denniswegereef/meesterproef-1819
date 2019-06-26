# Reflectie

Mijn leerdoelen op basis van de rubric waren:

**Wat wil ik nog leren**

- Contact tussen client, server, en source is elegant opgezet, bijvoorbeeld door OAuth of goede security in te zetten. Opzet getuigd van inzicht in de uitdagingen die bij simultaan gebruik door meerdere gebruikers komen kijken. ✅

- Het datamodel is op een slimme manier opgezet die van dieper inzicht getuigd. Je hebt een datamodel gecreëerd dat nauw aansluit op jouw app en data ✅

* Je hebt methodes gecreëerd die clients in staat stelt middels jouw eigen API te communiceren met jouw server. Real time connectiviteit is op een slimme manier opgezet ✅

* Je geeft zodanig feedback op de juiste momenten, dat de user experience er beter van wordt ✅

---

Maar ik denk dat het makkelijker is dat ik het vak geralateerd om te wat er in voorkwam

## Web App From Scratch

In principe maken we well gebruik van een webapp maar niet direct 'from scratch'. Toch hebben we een geweldige structuur neer gezet waar we echt trots op mogen zijn. Nergens zijn de kantjes er van afgelopen en over alles is goed nagedacht waar wat moet staan. Daarnaast ben ik diep in de materie gedoken van de tech-stack. Minder met Typescript maar vanaf moment 1 wist ik dat die taak niet direct voor mij zou zijn. Daarnaast heb ik de GraphQL api gebruikt van Tim om handig als een component opstart de juiste data uit de database te halen.

Al met al denk ik dat dit vak perfect verwerkt heb in het project. Niet alles wat direct van toepassing maar dit is wel de core van je applicatie. Zeer tevreden over dit resultaat.

## CSS To The Rescue

Een combinatie van wat complexere SASS dat uiteindelijk gecompiled wordt naar nette CSS wat de browser goed kan lezen. Door alles zo modulair op te zetten en bepaalde gedeelde styles te gebruiken de BEM methodiek toe te passen om de cascading goed te laten verlopen. Komt dit vak uitermate goed terug in het project. Er is een duidelijke hiërarchie gecreëerd met alle componenten.

Ik heb het idee het project sowieso in uitblinkt, we zitten allemaal op een niveau waar de limitaties van CSS er eigenlijk niet meer zijn. Gedurende 5 weken heb ik nooit gedacht dat ik het niet zou kunnen maken. Eigenlijk krijg je alles wel voor elkaar in CSS en daar mag ik toch best wel even trots op zijn dat dat gewoon kan.

## Browser Technologies

Ik heb hier minder rekening mee gehouden. Tuurlijk doe je wel valide HTML met de juiste semantische tags waardoor het automatisch makkelijker accessible wordt. Maar het was niet de insteek, dit is voornamelijk gemaakt dat dienst als prototype. Ook is het voor bestuurders dus de druk is minder groot om het bijvoorbeeld voor blinde mensen te maken. Zelf had ik hier ook niks van als leerdoel dus ik heb er niet bewuster op gelet dan bijvoorbeeld andere vakken. Progressive enhancement is in ons geval lastiger, we hebben er bewust voor gekozen om de statische pagina's op de server te renderen. Maar uiteindelijk heb je wel moderne JavaScript nodig om recente data te bekijken. Ook feature detection heb ik niet bewust toegepast, maar meer omdat het direct nodig was.

## Web design

Het enige wat ik daadwerkelijk gebruikt is, is misschien het rapid prototypen omdat we components hadden gemaakt konden we heel snel schuiven met bepaalde elementen. Dit vak viel sowieso niet direct met de wensen van de klant en schuiven sommige principes sneller naar de zijkant toe. Wat helemaal geen probleem is. Als er meer tijd was geweest en een 'need' vanuit de klant had het voor het dashboard zeker goed kunnen werken als het nog toegankelijker werd gemaakt. Maar aangezien het een prototype is was het gewoon niet nodig.

Ook heb ik het idee dat ik het er niet zo snel in verwerkt heb. Tuurlijk ga je wel in je hoofd nadenken 'wat als ik deze stakeholder was geweest'. Je verplaats je in de gene die het product gebruikt en dan kom je met inzichten. Inzichten zoals dat het niet moeilijk mag zijn als je snel in je auto een melding wil maken. Het spreekt bijna voorzich dat je op die manier denkt.

## Performance Matters

Dit is al bijna het hoofd uitgangs punt waarom we Nuxt.js hebben gebruikt. Het gratis server side rendering uit de box. Het geeft zo veel voordelen en omdat onze applicatie 'universal' is laden de pagina's belachelijk snel. En kunnen later als een component of pagina geladen is nog extra data krijgen maar dat de gebruiker nooit lang hoeft te wachten. Als we dan ook de audits draaien scoren met alles tussen de 95 en de 100 met een totaal score van 100. Ook hebben ik samen met Tim gekeken hoe we er een goede PWA van konden maken. Het is wel leuk dat je toen we dat voor het eerst deden uberhaupt geen idee hadden wat het precies was. En nu waren we aan het nadenken over strategien. Hoe we dingen willen cachen en wanneer het voor de gebruiker het voordeligst is. Uiteindelijk hebben we de in de laatste week gedaan en dan kom je er toch wel achter dat je het niet zomaar 'even' doet. Er komt ook best veel bij kijken en je moet goed nadenken hoe en wat.

In eerste instantie wouden we met background sync the GraphQL post requests gaan cachen. Maar ergens moest er een lijn worden getrokken dat we niet doorslaan in kleine dingen. Dat is ook een goed punt opzich dat je weet wat er nog vernaderd kan worden maar je moet het wel binnen de scope van de tijd houden. Kijken wat relevant is en wat eventueel voor later kan gaan als er meer tijd was geweest.

## Real-Time Web

In eerste instantie heeft Tim de communicatie met de server gemaakt. Maar het was heel makkelijker om op meerdere punten daar op in te haken en te anticiperen. Door handige methodes en op maken van modulaire functies en natuurlijk de virtual DOM te gebruiken. Kan je heel makkelijk op de juiste plek bijna fijnloos data updaten zonder enige moeite. Dan merk je wel hoe fijn een framework kan zijn vergeleken met een server side rendered app waar alleen static HTML/css/javascript wordt terug gegeven.

Ik vind zelf dat we dit geweldig als team hebben opgepakt en een hele toffe oplossing er voor hebben verzonnen. Misschien was multi-user support een iets complexere taak maar dat was voor nu minder relevant om de volledige tijd daarop te focusen.

## Nawoord

Ik kan zeker stellen dat ik alle doelen die ik op het begin van de meesterproef heb opgeschreven gehaald hebt. Toch zijn we op een hele andere manier dit project in gegaan. We wisten dat we al wat konden en zijn gewoon op de CMD methodiek verder gegaan. Eigenlijk zijn alle vakken onbewust en bewust voorgekomen. Ook al is het niet direct een leerdoel van de minor zelf is het toch belangrijk dat je ook als team samen kan werken en hoogwaardige gesprekken kan hebben hoe je bepaalde dingen wil implementeren en ziet. Ik ben er heilig van overtuigd als je openstaat voor verandering op de visie van andere dat je een betere developer wil worden. Ik heb het idee dat ik veel van die andere twee heb geleerd en hopelijk hebben ze ook nog wat van mijn visie geleerd hoe ik tegen bepaalde vraagstukken keek.

Ik vond het een heel tof project en ik heb het idee dat het eindresultaat er zeker mag zijn. Boven verwachtingen zit eigenlijk alles er in. Producten met deze tech stack worden binnen digital agency's gemaakt. En in de tijd met zijn 3en is het bijzonder netjes dat we dit toch maar even voor elkaar hebben geboksts. Ronduit het beste project van heel de minor dat ik heb gemaakt en kijk er dan ook met trots op terug.
