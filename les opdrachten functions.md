# Opdrachten Functions

## Mappen aanmaken

1. Ga naar waar jouw school werk staat
2. Ga naar de map/directory `M2 prog js`
Uit de vorige les!
3. Maak een map `functions`
4. Open de `functions` folder in visual studio code


## files opzetten

1. Kopieer files van de les1 naar 
 `functions`

 * `index.html`
 * `app.js`

2. open de directory `functions` in visual studio code

## javascript 

1. open app.js
2. nu verschillende functions aan in je class:

* een function die "MARIO!!" naar de console print `(geen argumenten geen return)`
* een function die "BWAHAHA!!!" returned `(geen argumenten)`
* een function die 2 getallen bij elkaar optelt en returned `(2 getallen als argumenten)`
* verzin er zelf nog 1 bij

Tip zie dit plaatje als voorbeeld waar `classFunction` een nieuwe function is
![](img/func/examplefunc.PNG)
Zet geen functions in functions

3. roep nu elke functions aan in `runApplication`
4. voor de `return` functions vang het resulaat in een `variabel` en `console.log` die `variabel`
5. controller je resultaat in de developer console

TIP: vergeet `this.` niet!


![](img/func/funcresult.PNG)


## huisje

1. Ga naar waar jouw school werk staat
2. Ga naar de map/directory `M2 prog js`
3. Open de `canvashuis` folder in visual studio code

We gaan nu onze huis teken code in een `aparte function` zetten

![](img/func/canvasg.PNG)

Zie je de `let g` daar? die bestaat `alleen` in `runApplication`

Die moeten we als argument doorgeven!

1. maak een nieuwe `function` met de naam `tekenHuis` in je `App` class
2. verhuis (`knip plak`) je huis teken code naar deze nieuwe `function`
3. geef de `function` 1 argument `g` (zonder let!)
4. roep de `function` aan in je `runApplication` (vergeet `this.` niet!)


## verplekken

Je kan je huis nu elke keer op dezelfde plek tekenen
dat is niet super handig
Dat gaan we aanpassen!

1. geef je `tekenHuis function` 2 extra `argumenten`: x & y
2. gebruik die x & y in je `g.draw...` stukken in je code
3. roep je `tekenHuis function` nu 2 keer aan met verschillende x & y

voorbeeld:
hier is de lijn altijd op 1 plek

![](img/func/linehard.PNG)

hier niet, als je de x, y veranderd verplaatst de lijn.

![](img/func/lineflex.PNG)

bv hier een stad met bomen & huizen in functies

![](img/func/voorbeeld.PNG)

## boompje?

Een huis moet ook een kerstboom hebben in deze tijd

![](img/func/xmastree.jpg)

1. maak een nieuwe `function` met de naam `tekenKerstBoom` in je `App` class
2. geef de `function` 3 argumenten `g`, `x` en `y`
3. roep de `function` aan in je `runApplication` (vergeet `this.` niet!)

4. vul de function in zodat deze een boom gaat teken:

* De boom heeft geen vaste plek, gebruik x en y bij het tekenen 
* De boom heeft minimaal een stam, naalden, 10 ballen of sterren en een piek.
* Je mag de boom uiteraard aanvullen met allerlei extra’s zoals slingers, kaarsjes , zuurstokken , kado’s, kinderen , katten etc…
* Maak vooral iets wat je zelf leuk vind om te tekenen.


Voor de kerstball kijk hier voor hoe je dat kan doen:

![](img/func/drawcirclecode.PNG)

Hier zie je het resultaat en hoe het werkt:

![](img/func/drawcircleresult.PNG)

of in de documentatie:

[circle tekenen](https://www.w3schools.com/html/html5_canvas.asp)


## Extra!

Verander de `function` voor de boom zo dat je het `aantal kerstballen` kan doorgeven als `argument`. maak het zo dat de kerstballen random in de boom gehangen worden. 

Probeer ook eens de kleuren random te doen.
s
## klaar?


1. commit & push je werk naar github
