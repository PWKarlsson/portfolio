---
Title: Webbplatser laddningstid
Description: En analys av ett antal webbplatser laddningstid på olika landningssidor och vilka förbättringsåtgärder som kan genomföras.
---

Webbplatser laddningstid och användbarhet
=======================

Denna rapport har till syfte att undersöka och jämföra laddningstiden för tre olika webbplatser.
Rapporten kommer även att statera vilka förbättringsåtgärder respektive webbplats kan vidta för att förbättra laddningstiden och användbarheten.


Urval
-----------------------

Urvalet består av en kategori av webbplatser som inriktar sig på försäljning av livsstilsprodukter och mode via nätet.
Detta har urval har valts då det består av en kategori webbplatser som i princip uteslutande består av bilder, vilket är intressant
just när det kommer till att analysera laddningstider. För att behålla konsumenten på denna typ av webbplats är det av stor vikt att laddningstiden är snabb för att behålla konsumentens intresse, detta då en konsument ofta kan gå igenom hundratals produkter under en session och därav kräver att det ska gå så smidigt som möjligt.
För en ytterligare en dimension i jämförelsen har de tre webbplatsen vitt skilda prisklasser.
I lågpriskategorin har secondhand-företagets Sellpy valts ut, ur medelkategorin kommer vi att titta närmare på Boozt's webbplats. Till sist sker en koll på modehandeln CareOfCarl som inriktar sig på exklusivare mode.


* [Sellpy](https://www.sellpy.se/)
* [Boozt](https://www.boozt.com/se/sv)
* [CareOfCarl](https://www.careofcarl.se/)

<br>Metod
-----------------------

För att undersöka webbsidornas kvalitet avseenden laddningstider och användbarhet kommer följande att genomföras:

* Ta en screenshot av webbplatsen.

* Göra mätningar av prestanda och laddningstider på respektive webbsidas startsida samt två undersidor.

* Samtliga mätningar kommer att genomföras med hjälp av Chrome DevTools och Google Pagespeed.
    Via DevTools inhämtas data för antalet resurser som laddas, sidans inläsningstid, tiden för DOM-innehållet att laddas samt sidans totala storlek. Fokus ligger främst på en sidas laddningstid, där 2 sekunder kommer att vara gränsen för att avgöra huruvida en sida har en bra laddningstid eller om det har förbättringsåtgärder att genomföra.
    Via Pagespeed får vi hjälp att mäta sidans prestanda, både för mobil och dator, samt en betygsättning för densamma. Vi får även förslag på förbättringsåtgärder för att förbättra sidan prestanda.
    Avseende betyget så kommer det att tolkas enligt följande: <br>
    <50: Ej godkänt <br>
    50 - 90: Godkänt resultat <br>
    <90: Väl godkänt resultat


* Resultatet sammanställs i ett kalkylark för enklare jämförelse och för läsaren att ta del av.


Resultat
-----------------------

Resultatet av undersökningen framgår i det inbäddade kalkylarket nedan. Detta har delats upp i respektive webbsidas startsida samt två undersidor.

<iframe class="tableLoad" width="800" height="287" frameborder="0" scrolling="no" src="https://studentbth-my.sharepoint.com/personal/pokr23_student_bth_se/_layouts/15/Doc.aspx?sourcedoc={702abffc-a861-4fb5-9200-a6f278f2b9f4}&action=embedview&wdAllowInteractivity=False&Item='Blad1'!A1%3AAA12&wdHideGridlines=True&wdDownloadButton=True&wdInConfigurator=True&wdInConfigurator=True"></iframe>
<br>

### Sellpy

<a href="../image/sellpy.png">
<img src ="../image/sellpy.png" alt="Sellpy-overview" class="website-img"></a>

På Sellpy möts vi av en startsida bestående av bilder, bilder och åter bilder, vilket inte är helt otypiskt för denna typ av webbsida.
Tittar vi på laddningstiderna så ser vi att startsidan ligger på rätt sida om gränsvärdet 2 sekunder, medan det finns mer att önska av undersidorna. Snittet för samtliga sidor uppgår till 2,36 sekunder och såldes ingen katastrof att tala om. <br> Att undersidan "search" har det absolut sämsta resultatet med 3,06 sekunder är kanske inte så konstigt då man har får träffar på webbsidans samtliga artiklar, vilket vid tidpunkten för undersökning uppgick till +4,1 miljoner.<br>
Tar vi en titt på prestandamätningen så ser vi att det är allt annat än bra, runt 20/100 på dator och enbart runt 4/100 på mobil.
Via PageSpeed Insights poängteras att företaget bör fokusera på att skicka bilder i modernare bildformat så som WebP och AVIF, använda bilder med rätt storlek, koda bilder mer effektivt samt reducera JavaScript som inte används. Detta skulle kunna medföra att sidan läses in cirka 12 sekunder snabbare.


### Boozt

<a href="../image/boozt.png">
<img src ="../image/boozt.png" alt="Boozt-overview" class="website-img"></a>

Även på Boozt möts vi av en startsida med stort fokus på bildinnehåll. En skillnad som noteras är att Sellpy direkt på startsidan visade upp enskilda artiklar med priser medan Boozt inte visar några priser alls utan skyltar om julrean och hänvisar till underkategorier med artiklar.<br>
När vi tittar på laddningstiderna så har Boozt lyckats något bättre med en snittid om 2,09 sekunder för de tre undersökta sidorna, snabbast laddas startsidan på 1,95 sekunder.
Tar vi en titt på prestandan så ser vi att resultatet blir godkänt för samtliga sidor uppnår ett godkänt resultat, där startsidan sticker ut positivt med 84/100. <br>
För mobil finns mer att önska där samtliga sidor får ett resultat i intervallet 31-37 och därmed ej godkänt enligt denna undersökning.
Som förbättringsförslag nämns att man bör jobbar vidare med att reducera Javaskript som inte används, ta bort resurser som blockerar renderingen, använda bilder med rätt storlek och skicka bilder i modernare format. Detta skulle kunna spara in cirka 2 sekunder vid inläsning av sidan på dator och cirka 8 sekunder på mobil.


### CareOfCarl

<a href="../image/careofcarl.png">
<img src ="../image/careofcarl.png" alt="CareOfCarl-overview" class="website-img"></a>

På CareOfCarl möts vi av den största Hero-ytan av samtliga webbsidor i denna rapport. Det är den klart största startsidan av dem alla och den är täckt med bilder från topp till bott, här har man inte sparat på krutet och lämnat några marginaler utan utnyttjat hela sidan bredd. Det kom därav inte som någon chock att detta är den startsida i undersökningen som får den absolut sämsta laddningstiden på 2,63 sekunder.<br>
 Även på undersidorna har man nyttjat hela sidans bredd för att presentera artiklarna och laddningstiderna här är en bra bit över 3 sekunder, alltså inte ett godkänt resultat på någon av sidorna. 
Avseende prestanda-mätningen ser det dock bättre ut med ett resultat om +74 för samtliga sidor på dator.<br>
På mobil finns det mer att jobba på med resultat i intervallet 33 - 47, vilket dock är det bästa resultatet i denna undersökningen och påvisar att de är på rätt väg.
Min egen observation kring bilderna backas upp av förbättringsförslagen. Enbart genom att fokusera på att använda bilder med rätt storlek kan de spara in cirka 5 sekunder vid inläsning av sidorna. I övrigt bör det tänka på att reducera Javascript och CSS som inte används, ta bort resurser som blockera renderingen samt minifiera CSS och JavaScript. Genom dess åtgärder kan de spara upp till 7 sekunder extra vid inläsningen.

Analys
-----------------------

Denna rapport har undersökt prestandan och laddningstider för ett antal företag inom modebranschen på nätet. Resultatet av detta talar sitt tydliga språk. Ingen av webbsidorna uppnådde ett genomsnittligt godkänt resultat avseende laddningstider, där gränsvärdet sattes till 2 sekunder.
Boozt och CareOfCarl hade godkända resultat avseende prestandan när man besöker deras sidor via en dator, men samtliga företag har mycket att jobba på när det kommer till mobila enheter.
En stor anledning till dessa resultat beror på att detta är webbsidor som är otroligt bildintensiva, vilket är ett måste inom denna bransch för att tilltala konsumenterna. Problematiken som leder till att resultaten inte är bättre än vad som framgår enligt resultatet beror på att man inte arbetat tillräckligt med sina bilder. Vad samtliga först och främst behöver fokusera mer på är att arbeta med rätt storlek och moderna bildformat för sina bilder. I andra hand handlar det om att rensa bort onödig kod som de inte nyttjar på webbsidorna i dagsläget. <br>

Sätt över samtliga kategorier i undersökningen utses Boozt till vinnare. CareOfCarl har hittills lyckats uppnå en något bättre prestanda på sin sida men ligger långt efter när det kommer till laddningstid. Att Sellpy skulle ha de sämsta resultaten är egentligen inte förvånande då det är en secondhand-handel som inte ser ut att ha haft en lika stor budget när det kommer till utformningen av sidan, troligtvis i linje med affärsidéen. Det blir däremot lite motsägande när det kommer till hållbarhetsaspekten då de har stort fokus på hur mycket du hjälper miljön genom att handla via dem, medan de själva skulle kunna bidra ytterligare genom att effektivisera sin webbsida för att spara på den energi som går åt när besökarna nyttjar den.



Övrigt
-----------------------

Skrivet av: Pontus Karlsson