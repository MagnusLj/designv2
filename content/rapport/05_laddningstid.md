Laddningstid
=======================

I den här uppgiften ska man mäta laddningstid för tre olika sidor och analysera resultaten.

Urval
-----------------------

Jag har valt Expressen, Die Welt och Politico. Jag tog tre nyhetswebbplatser för att jämföra lite liknande sidor och tycker det är lite intressant
att jämföra nyhetssidor från tre olika länder. Det blir lite landskamp typ.

Metod
-----------------------

Jag har använt PageSpeed Insights, Network i devtools i Firefox Developers Edition, Skärmklippsverktyget och Excel Online. Jag använde de två förstnämda på tre sidor vardera på de tre
webbplatserna jag valde.

Resultat
-----------------------
#### Expressen
![Expressens](img/expressen.jpg "Expressen")

[Expressens förstasida](https://www.expressen.se/)

PageSpeed dator: 84, PageSpeed mobil: 47.

Laddningstid snitt: 8,12 s, antal resurser snitt: 207, storlek snitt: 4,59 MB.

[Expressens sportsida](https://www.expressen.se/sport/)

PageSpeed dator: 83, PageSpeed mobil: 48.

Laddningstid snitt: 8,97 s, antal resurser snitt: 308, storlek snitt: 5,78 MB.

[Expressens nöjessida](https://www.expressen.se/noje/)

PageSpeed dator: 90, PageSpeed mobil: 60.

Laddningstid snitt: 5,97 s, antal resurser snitt: 177,33, storlek snitt: 3,75 MB.

Expressen verkar bland annat kunna göra JavaScript-koden mer effektiv, skjuta upp inläsning av bilder som inte visas på skärmen och vänta med CSS som inte används.

#### Politico
![Politico](img/politico.jpg "Politico")

[Politicos förstasida](https://www.politico.com/)

PageSpeed dator: 51, PageSpeed mobil: 21.

Laddningstid snitt: 10,73 s, antal resurser snitt: 275,67, storlek snitt: 7,97 MB.

[Politico - The Agenda](https://www.politico.com/agenda/)

PageSpeed dator: 86, PageSpeed mobil: 26.

Laddningstid snitt: 6,19 s, antal resurser snitt: 135,33, storlek snitt: 4,44 MB.

[Politico - Congress](https://www.politico.com/congress)

PageSpeed dator: 94, PageSpeed mobil: 30.

Laddningstid snitt: 6,73 s, antal resurser snitt: 193, storlek snitt: 5,70 MB.

Politico verkar bland annat kunna skjuta upp inläsning av bilder som inte visas på skärmen, använda bilder med rätt storlek, skicka bilder i modernare bildformat, koda bilder effektivt,
vänta med CSS som inte används.

#### Die Welt
![Die Welt](img/welt.jpg "Die Welt")

[Die Welts förstasida](https://www.welt.de/)

PageSpeed dator: 99, PageSpeed mobil: 48.

Laddningstid snitt: 10,48 s, antal resurser snitt: 181,26, storlek snitt: 7 MB.

[Die Welt - Weltplus](https://www.welt.de/weltplus/)

PageSpeed dator: 99, PageSpeed mobil: 57.

Laddningstid snitt: 4,71 s, antal resurser snitt: 89,16, storlek snitt: 4,65 MB.

[Die Welt - Politik](https://www.welt.de/politik/)

PageSpeed dator: 100, PageSpeed mobil: 51.

Laddningstid snitt: 8,42 s, antal resurser snitt: 184,63, storlek snitt: 7,32 MB.

Die Welt verkar bland annat kunna skjuta upp inläsning av bilder som inte visas på skärmen, använda bilder med rätt storlek, aktivera textkomprimering och vänta med CSS som inte används.

</br>

Här är en [länk till Excel-schemat med mina mätresultat](https://1drv.ms/x/s!AsxD8wR5zqRqhtw4GwGQi6_XYezPLg)

Analys
-----------------------

De vanligaste förbättringsförslagen för sidorna jag har tittat på handlar om optimering av bilder, såsom att skjuta upp laddning av bilder som inte visas på delen av sidan man tittar på först,
använda bilder av rätt storlek, använda annat bildformat et cetera. Att vänta med CSS som inte används (direkt) är också ett tema som återkommer. Det tycks ju kunna vara ett ganska vanligt problem
med suboptimal hantering av bilder som skäl till att sidor laddas långsammare än de kunde laddas annars, i vart fall utifrån mitt mycket begränsade material.

Gräns för snabb/långsam laddningstid sätter jag till nånstans runt 10 sekunder. Webbplatserna jag har tittat på har olika laddningstid för olika sidor där vissa ligger lite över 10 sekunder men de flesta under. Jag
tycker inte att någon av webbplatserna jag har tittat på känns långsam.

Baserat mest på PageSpeed tycks ordningen bli Die Welt på första plats, Expressen på andra plats och Politico på tredje plats. En kommentar får vara att det är rätt många variabler så det kan vara svårt att säga
vilken sida som är bäst. Bara laddningstiden säger ju inte allt, en sida med tre rader svart text på vit bakgrund till exempel skulle i de flesta fall laddas jättesnabbt men skulle troligen inte vara så imponerande för det. Politico är nog den sidan jag tycker är snyggast, så om den får lite lägre poäng må det väl vara hänt, den är inte så långsam att det stör mig på något sätt.

Övrigt
-----------------------

Gruppen består av mig, Magnus.
