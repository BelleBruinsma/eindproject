
Wat ga ik doen:

Op de eerste pagina wil ik een LineGraph maken met voorspellingen tot 2100 wat er staat te gebeuren met de “Global greenhouse gas emissions” als iedereen zo doorgaat, als het streven van het Paris Agreement wordt gehaald en wanneer er helemaal niks gebeurt op de aarde. Ook is te zien wat het aandeel van US, EU, China, developed en developing countries is. Er is dus duidelijk te zien hoe groot het aandeel van Amerika is en ik kan daarnaast uitleggen wat er zou kunnen gebeuren nu Amerika het Agreement heeft opgezegd.

Op de tweede pagina ga ik een wereld kaart laten zien met drie verschillende kleuren die duidelijk maken of zij hebben “signed”, “signed & ratified” en “unsigned”. Ook is per land te zien wat het aandeel in percentage emissions is ten opzichte van de wereld. Wanneer je op een land drukt is daaronder vanaf 1990 tot 2015 te zien elk land doet aan “Share of wind and solar in electricity production (%)” en “Share of renewables in electricity production (incl hydro) (%)”. Deze twee kan je omwisselen via een checkbox.

Dinsdag 6 juni: Een onderwerp bedacht. Vervolgens naar data gezocht maar dit duurde wel even.

Woensdag 7 juni: Begonnen met een library dc die mij erg veel werk zou besparen. Data opschonen, inladen en begonnen met een wereldmap.

Donderdag 8 juni: Helaas mocht ik de dc library niet gebruiken dus veel tijd weggegooid. Oude opdracht van dataprocessing gebruikt voor het maken van datamap.

Vrijdag 9 juni: Begonnen met de interactieve grafiek met checkbox. Weet niet goed hoe ik mijn data moet inladen dus loopt niet helemaal op rolletjes.

Zondag 11 juni: Heel lang bezig geweest met data in de goede JSON format te zetten. Uiteindelijk gelukt.

Maandag 12 juni: Verder gegaan met de line graph van % renewables en % solar and wind energy over de jaren heen per land. Uiteindelijk vond ik dit toch niet overzichtelijk genoeg aangezien het niet duidelijk was wat de verschillen tussen landen is op deze manier. Nu heb ik iets anders gevonden. Een scatterplot waarbij het land oplicht als je het puntje selecteerd. Het percentage renewables per land dat groene energie is op de y as en een check box aan keuze op de x as.

Dinsdag 13 juni: De interactie is werkend. Nu ben ik nog bezig met de x-as veranderen. Voor nu heb ik de HPI index gebruikt maar is nog niet zeker welke ik nou echt wil laten  correleren.

Woensdag 14 juni: Checkbox afgemaakt maar op een vreemde manier. Heel erg onduidelijk waarom hij niet werkte maar heb nu een extra updater functie gemaakt. Hier moet ik later nog een keer naar gaan kijken. Vanavond wil ik de kleuren transparant maken zodat het niet zo opvallend is en eigenlijk nog zoeken naar goeie x-as vergelijkingen met groene energie. Morgen wil ik beginnen aan mijn nieuwe graph en zoeken naar een goed voorbeeld om het te vergelijken met een tabel.

Donderdag 15 juni: Beginnen met de tweede interactie met zoeken van data en voorbeelden. Ik wil een zoomable functie maken zodat er kan worden ingezoomd op een aantal lijnen.

Vrijdag 16 juni: Presentaties en werken 

Zaterdag 17 juni: Linegaph begonnen

Zondag 18 juni: Linegraph begonnen

Maandag 19 juni: Zoomable multiple line graph afmaken en tooltip toevoegen. Diegene die ik wilde gebruiken kon alleen de x as verlengen. Op die manier was de grafiek totaal niet duidelijk en zou het storytelling element niet overkomen. Toen gezocht naar een nieuwe. Die nu gevonden maar er moet nog wel veel aan worden gedaan. De tooltip is nu toegevoegd maar hij weet nog niet welke lijn welke is.

Dinsdag 20 juni: Interactieve table toevoegen en data zoeken voor tabel. Bedenken wat ik nu eigenlijk nog extra wil vertellen.

Woensdag 21 juni: Vandaag heb ik een mooi template gemaakt en alle losse dingen weg gegooid. Mijn versie van d3v3 en d3v4 konden niet samen wat wel kon op "niet mac computers". Hier baalde ik erg van en ben ik veel tijd aan verloren. Nu zorg ik dat ik twee verschillende html files heb zodat de twee versies niet samen komen. Vanavond moet ik mij nog snel inschrijven voor de github ding en de kleuren + tekst veranderen van mijn renewables.html file. 

Donderdag 22 juni: vandaag ben ik bezig geweest om de tooltip rechts van mijn linegraph te zetten. Vervolgens heb ik een tabel gemaakt met Datatables maar dit duurde allemaal enorm lang. Uiteindelijk is het gelukt om de table in de buurt te krijgen van de linegraph maar elke keer als er over de tooltip heen wordt gescrolled dan gaat hij naar beneden. Verder is de dataset van de linegraph nog in het js file en niet ingeladen. 

Vrijdag 23 juni: Vandaag heb ik mijn tabel onder de line graph gezet en ga nu zorgen dat wanneer ik over de landen hover met mijn muis in de line graph, de bijbehorden dingen in mijn tabel worden gehighlight. Vervolgens druk ik op een land en zie ik de bijbehorende tabel met de landen die meebetalen aan het fonds.

Zaterdag 24 juni: Ging allemaal weer erg moeizaam. Vandaag heb ik de lijnen goed gemaakt van de verschillende werelddelen, de tooltips alsnog bij de muis gezet, het tabel naast de lijngrafiek gedaan, gezorgt dat op on.click de tabel met de goede data verschijnt. De legende maken lukte niet goed want ik wil de namelijk bij mijn lijn in de line graph hebben staan. Ook wil ik de erea van de korte lijnen vullen met blauwsel maar dit lukte ook nog niet. Tot slot staat de tweede tabel nog op de eerste tabel.

Zondag 25 juni: Vandaag heb ik de piechart gemaakt en de twee tabellen verbetererd en wat dingen opgeschoond. De tabellen en piechart krijg ik maar niet op de goede plek in de html dus dat moet ik morgen even vragen hoe dat nu zit. Verder heb ik wat story telling gedaan.

Maandag 26 juni: Vandaag heb ik de tabellen aangepast zodat er geen search en entries stonden. Tevens heb ik alles op de goede plek gezet. Voor de scatterplot heb ik nieuwe data gevonden waardoor het verhaal beter is. Nu moet ik wel zorgen dat de x as veranderd. Ook heb ik bijna een legende gemaakt voor bij de line graph. Helaas wordt hij niet zichtbaar dus ik moet dat morgen nog even beter vragen.

dinsdag 27 juni: Hele dag bezig geweest met het veranderen van de x-as van de scatterplot. Ik moet hem veranderen van d3.scaleLinear naar d3.timeformat etc. 

woensdag 28 juni: legende, x-as logaritmische schaal. Verhaal bedenken.

Donderdag: Storytelling, legende, tabel












