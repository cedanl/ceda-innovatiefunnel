# De poorten van de metrolijn, gesprek met de coördinator, 2 november 2026

Na de werksessie van 22 oktober heeft de kwartiermaker op 2 november een uur met de coördinator van CEDA de vijf poorten van de metrolijn doorgelopen. Per poort was de uitkomst van de werksessie het vertrekpunt. Bij elke poort kwamen vier vragen aan bod: waar beslissen we nu op, wat maakt de overgang lastig, wie zegt ja of nee, en hoe ver moet de code zijn. Deze notitie legt vast wat dat opleverde.

Het is een eerste poortversie en nog geen besluit. De poortwachters werken de details hierna verder uit, en ze mogen tegen alles ingaan wat hier staat. Reageren kan in deze notitie of via de kwartiermaker.

Vertrekpunt: [de werksessie van 22 oktober](2026-10-22-werksessie-metrolijn.md). De presentatie die we samen doorliepen staat als [pdf](2026-11-02-poorten-met-coordinator-presentatie.pdf) en als [html](2026-11-02-poorten-met-coordinator-presentatie.html). De pdf kun je op GitHub direct lezen. De html download je en open je in een browser; met de pijltjestoetsen blader je door de dia's.

## Voorstellen om de lijn aan te passen

Uit het gesprek kwamen vier voorstellen. Ze veranderen namen die het team op 22 oktober nog "klopt" gaf, dus ze komen terug in de vervolgsessie.

| Voorstel | Waarom |
|---|---|
| **Alpha heet MVP** | "Alpha" suggereert dat er altijd een Beta volgt. Een MVP staat op zichzelf: je verkent of het iets is |
| **De code van de MVP gaat standaard niet mee naar Beta** | In de MVP is er vrijheid in de code. In Beta wordt het product gebouwd. Meenemen kan als uitzondering, na een kritische blik |
| **Login of MFA gaat uit de criteria** | Dat hangt af van de omgeving. Draait het bij een instelling, dan beslist die er zelf over |
| **Overdracht heet Beheer** | De vraag aan het eind is wie het beheert, en dat is een bredere vraag dan overdragen per tool |

## Per poort

### Poort 1: Signaal naar Discovery

- Bij regiobijeenkomsten is er al een werkwijze. Veel signalen komen tegelijk binnen en op dezelfde manier, dus je kunt ze eerlijk vergelijken. Daarna volgt een inhoudelijke slag: wat lijkt op elkaar, wat lijkt op iets wat we al hebben. Dat bracht het aantal terug tot vijf, die een klein groepje uitwerkte tot een voorkeur. In dat groepje zit iemand met de strategie vanuit Npuls, iemand met het instellingsperspectief en de coördinator.
- Signalen die anders binnenkomen (via mensen van Npuls, via aanvoerders, tussendoor opgevangen) worden nu niet op dezelfde manier uitgewerkt. Dat kan wel: ook bij de regiobijeenkomsten vullen we de use cases achteraf aan.
- Een champion of mandaat bij de instelling is er bij een signaal meestal nog niet. Of die er komt, hangt af van via wie het binnenkomt.
- **Wie beslist:** een klein groepje met vaste perspectieven, zoals bij de regiobijeenkomsten. De mensen die het werk doen beslissen hier niet zelf, want wie aan iets werkt, wil dat het doorgaat.

### Poort 2: Discovery naar Alpha (MVP)

- CEDA heeft nu eigenlijk geen Discovery. Daardoor liggen in de Alpha veel vragen open en is niet duidelijk wat die kan opleveren. De coördinator is daarom blij met de fase en met de naam Discovery.
- **Waar beslis je op:** databeschikbaarheid, strategische relevantie, technische haalbaarheid en een indruk van de behoefte. En het probleem moet helder zijn, misschien al vóór Discovery.
- Discovery is niet altijd nodig. Bij de instroomprognose waren de behoefte en de data al bekend.
- Een voorbeeld van stoppen is de instroomprognose mbo. De data bleek van onvoldoende kwaliteit, dus het project is gestopt.
- In Discovery is er alleen verkennende code en nog geen product.
- **Wie beslist:** het team. Wie de Discovery deed, heeft een stem, omdat haalbaarheid hier zwaar weegt.

### Poort 3: Alpha (MVP) naar Beta

- Een voorbeeld van door is de instroomprognose hbo. Die was haalbaar en de behoefte was groot, dus is er extra in geïnvesteerd.
- Een voorbeeld van blijven hangen is een MVP waarop de reacties niet enthousiast genoeg waren, met enkele haalbaarheidsvragen.
- **Waar beslis je op:** de belangrijkste variabele volgens de coördinator is of het populair is. Een goed idee is bij lange na niet genoeg om bij een instelling in gebruik te komen. Populariteit wordt nu niet in getallen gemeten. Het team kijkt naar reacties op webinars, en veel deelnemers betekent niet vanzelf enthousiasme. De coördinator twijfelt of meten de moeite waard is, omdat het om een beperkt aantal projecten gaat. Of en hoe we het toetsbaar maken, is een vraag voor de poortwachters.
- **Wie beslist:** deels het team. Omdat Beta veel uren kost, gaat het mogelijk ook een niveau hoger. Waar dat niveau ligt, is nog niet bepaald. Het kernteam van het domein is een logische kandidaat.
- **Techniek:** de code van de MVP gaat standaard niet mee (zie de voorstellen hierboven).

### Poort 4: Beta naar Live

- **Waar beslis je op:** de criteria van de werksessie blijven grotendeels staan. Beheer en DPIA moeten echt helder zijn. Login of MFA gaat eruit.
- Wat nu vooral ontbreekt, is beheerdocumentatie die duidelijker en toegankelijker is.
- Live betekent dat het gebruikt kan worden. Drie instellingen gebruiken het, en elke andere instelling moet het kunnen gebruiken. Het mag geen maatwerk zijn om het bij die drie werkend te krijgen.
- **Spanning:** generiek genoeg voor meerdere instellingen, en tegelijk een serviceniveau waarmee het gebruikt wordt.
- **Techniek:** de code is stable.
- **Wie beslist:** er zijn twee sleutels nodig.
  1. Iemand bij een instelling zet een handtekening: dit kan live, en wij nemen het in beheer. Daarmee is ook gezegd dat een vergelijkbare instelling dat kan.
  2. Noemt die instelling punten die nog ontbreken, dan besluit CEDA (de coördinator met het projectteam) of het die extra tijd investeert.

### Poort 5: Live naar Beheer (was Overdracht)

- Dit station is het minst duidelijk. De coördinator heeft er nog geen antwoorden op.
- Als een paar instellingen het live gebruiken, presenteren we het breder, liefst samen met die instellingen.
- Bij producten die niet bij een instelling draaien, zie je het gebruik in de logs, maar dan komt de vraag van beheer terug.
- Een vraag om doorontwikkeling is een nieuw signaal. Die gaat terug naar het begin van de lijn.
- **Wie beslist:** nog onduidelijk, en dit is geen vraag per tool. CEDA heeft een structurele landingsplek voor beheer nodig. Die plek kan dan ook bepalen wat erin hoort. Mbo en hbo kunnen daar verschillende regels voor hebben, en dus mogelijk verschillende poorten.

## Overzicht: wie zegt ja of nee

| Poort | Wie beslist (stand 2 november) |
|---|---|
| Signaal naar Discovery | Een klein groepje met vaste perspectieven (strategie, instelling, coördinator) |
| Discovery naar MVP | Het team, met een stem voor wie de Discovery deed |
| MVP naar Beta | Het team, met escalatie een niveau hoger omdat Beta veel uren kost. Welk niveau is nog open |
| Beta naar Live | Twee sleutels: handtekening van een instelling, daarna besluit CEDA over extra werk |
| Live naar Beheer | Open. Hangt af van een structurele landingsplek voor beheer |

Bij geen enkele poort ligt de beslissing alleen bij de mensen die het werk doen, of bij één persoon. Er komt steeds een tweede perspectief bij: een groepje, het kernteam of de instelling.

## Afbakening

- Voorlopig gelden de poorten voor applicaties, de concrete cases. Of en hoe ze ook voor libraries en developertools gelden, bekijken we later.
- De sectorvoorziening (beheer voor de hele sector, ook na Npuls) moet nog worden bepaald en uitgezocht.

## Het beeld na dit gesprek

Aan het begin van de lijn (Signaal en Discovery) ligt het meeste nieuwe werk, omdat CEDA eerder direct naar een product ging. Aan het eind (Beheer) ligt een heel ander soort werk. In het midden (MVP, Beta, Live) doet het team het werk al en gaat het vooral om strakker maken. Dat deel kan het team grotendeels zelf, en het leent zich voor automatisering.

## Wat er nu gebeurt

1. De poortwachters: per poort een kort gesprek, met deze notitie en het ingevulde poortpatroon als basis.
2. Het instellingsperspectief: de kwartiermaker spreekt het teamlid dat het instellingsperspectief inbrengt, over wat er per fase helder moet zijn.
3. Een vervolgsessie in december, ongeveer twee uur, bij voorkeur op of rond de teamdag: terugkijken op wat het geworden is, en één project live langs de lijn halen als bordspel. De keuze ligt tussen de instroomprognose en de Uitnodigingsregel; de instroomprognose ligt iets meer voor de hand, omdat het team die helemaal zelf deed.
4. Voor kerst: de metrolijn met poorten helder en gedocumenteerd in deze repo.

## Vragen om op te reageren

1. Klopt het voorstel om Alpha MVP te noemen en Overdracht Beheer? Of verliezen we daarmee iets van de gedeelde taal van 22 oktober?
2. Hoe maken we "is het populair?" toetsbaar? Welk signaal na een webinar of demo zegt iets over gebruik bij een instelling?
3. Wat moet er in de beheerdocumentatie staan, zodat een instelling haar handtekening kan zetten?
