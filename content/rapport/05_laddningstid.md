Utvärdera webbplatsers laddningstid och användbarhet
=======================

I denna rapport har vi sammanställt mätvärden på olika webbplatser samt analyserat dem.

Urval
-----------------------
Vi har valt att analysera tre hemsidor för olika glasstillverkare. Vi beslutade oss för att analysera och jämföra OTTOS-glass, GB-glace och Ben & Jerry’s. 

Metod
-----------------------
Vi använde oss av webbläsaren Chrome och Networks som finns i Devtools, utan cache. Vi har också använt hemsidan PageSpeed Insights för att betygsätta webbsidorna.

Resultat
-----------------------
<a href="https://docs.google.com/spreadsheets/d/1NwTc29KKtBwFAS8mNGscYVHB-cn63zVxXrweqc2RlHM/edit?usp=sharing">Här hittar du excelarket</a>

__OTTOS-glass:__

<img src="../htdocs/img/otto.png" alt="OTTO glass" height="400px">

På startsidan av webbplatsen gav PageSpeed Insights betyget 37 av 100 på mobila enheter medan på desktop fick startsidan betyget 77. Vi fann även att medelvärdet för laddningstiden är 1,42 sekunder med 30 requests på storleken 5,4 MB.

Medan på webbplatsens om-sida så fick den 41 på mobila enheter medan desktop fick 89. Om-sidan fick ett medelvärde på 1,53 sekunder på laddningstid därav antalet requests var 25 med storleken 3,1 MB.

På deras sortiment-sida fick dem 44 på mobil och 89 på desktop, och medelvärdet på laddningstiden var 1,46 sekunder. Antalet requests låg på 25 med total storleken 3,4 MB.

__GB-glace:__

<img src="../htdocs/img/gbglace.png" alt="GB-glace" height="400px">

Startsidan för GB-glace fick betyget 76 på PC och endast betyget 12 på mobila enheter. Medelvärdet för laddningstiden är 3,97 sekunder. Antalet requests var 112 stycken med en storlek på 7 MB. 

GB-glaces sida för inspiration fick sidan betyget 77 på PC och 14 för mobila enheter. Antalet requests var 99 stycken och storleken blev 6,8 MB. Medelvärdet för laddningstiden för hemsidan låg på 3,64 sekunder.

Om-sidan på webbplatsen fick betyget 16 på mobila enheter och 78 för PC. Medelvärdet för laddningstiden blev 3,85 sekunder. Antalet requests var 103 och storleken för hemsidan blev 6,7 MB.

__Ben & Jerry’s:__

<img src="../htdocs/img/benjerrys.png" alt="Ben & Jerry’s" height="400px">

Startsidan av deras hemsida fick 45 poäng på mobila enheter medan 82 på desktop. Sidan hade 188 request, med storlek på 3,2 MB, och fick även ett medelvärde på laddningstiden 2,56 sekunder.

Sidan för skopglass på webbsidan fick betyget 57 på mobila enheter och betyget 92 för PC. 2,5 sekunder är medelvärdet för att ladda hemsidan. Antalet requests är 93 och storleken för hemsidan ligger på 3,5 MB.

Ben & Jerry’s sida för smaker fick betyget 56 för mobila enheter medan desktop fick 89. Sidan gjorde även 97 requests, med storleken av 3,6 MB, på laddningstiden 2,51 sekunder.


Analys
-----------------------
Vi har erhållit resultaten på laddningstiden med Wi-fi, med ethernet så kan det gå snabbare.

Den vanligaste förbättringsåtergärden anser vi är att dra ner på antal requests, som hemsidan för OTTO-glass har gjort. Dels blir sidan stilrenare men den laddar också snabbare. Dock är hemsidan byggd med squarespace som möjligtvis komprimerar filerna, vilket påverkar storleken. Storleken för Ben & Jerry’s hemsida är mindre än OTTOs, ändå är laddningstiden för Ben & Jerry’s hemsida sämre än OTTOS. Vi drar slutsatsen att detta är för att Ben & Jerry’s hemsida har betydligt fler requests än OTTOs. Detta pekar mot att man bör sänka antalet requests om man vill ha en snabb laddningstid.

Medan på GB’s hemsida så har dem många bilder, vilket även tar störst storlek på hemsidan. Det som skulle ändras är nog då att ta bort bilder eller möjligtvis komprimera dem, om de inte redan är det.

Våran rangordning på hemsidorna baserad på olika faktorer:
Rangordning i laddningstid

1. OTTO-glass

2. Ben & Jerry’s

3. GB-glace

Rangordning PageSpeed (både mobil och desktop)

1. Ben & Jerry’s

2. OTTO-glass 

3. GB-glace

Vi anser att hemsidan för OTTO-glass är vinnaren då deras laddningstid slog de andra i testet. Skillnaden mellan Ben & Jerry’s och OTTO-glass i rangordningen för Pagespeed är också väldigt liten, nästintill obefintlig på PC. OTTO-glass har även färre requests. 

Den absolut laddningstiden anser vi är 2 sekunder. De webbplatserna som klarar vårt gränsvärde är OTTO-glass. Ben & Jerry’s är fortfarande acceptabelt. GB-glace är inte alls bra då man ser hur hemsidan byggs upp medan hemsidan requestar data. Till exempel dyker inte bilder upp förens efter någon sekund. 

Referenser
-----------------------

<a href="https://ottoglass.se/">Ottoglass</a>

<a href="https://ottoglass.se/om-otto-glassfabriken">Om Ottoglass-fabriken</a>

<a href="https://ottoglass.se/glass-sortiment">Sortiment Ottoglass</a>

<a href="https://www.gb.se/home.html">GB-glace</a>

<a href="https://www.gb.se/inspiration.html">Insipiration GB</a>

<a href="https://www.gb.se/om-gb-glace.html">Om GB</a>

<a href="https://www.benjerry.se/">Ben & Jerry’s</a>

<a href="https://www.benjerry.se/skopglass">Ben & Jerry’s skopglass</a>

<a href="https://www.benjerry.se/smaker">Ben & Jerry’s smaker</a>

<a href="https://developers.google.com/speed/pagespeed/insights/">PageSpeed</a>

<a href="https://docs.google.com/spreadsheets/d/1NwTc29KKtBwFAS8mNGscYVHB-cn63zVxXrweqc2RlHM/edit?usp=sharing">Excelark</a>


Övrigt
-----------------------
Ida Lam, Mathilda Börtz
