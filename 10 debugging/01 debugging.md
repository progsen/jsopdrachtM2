# Opdrachten debugging

## Mappen aanmaken

1. Ga naar waar jouw school werk staat
2. Ga naar de map/directory `M2 prog js`
Uit de vorige les!
3. Maak een map `10 debugging`
4. Open de `10 debugging` folder in visual studio code

## code ophalen

1. download deze files:
  - [./debugging/app.js](./debugging/app.js)
  - [./debugging/index.html](./debugging/index.html)
2. zet deze in je debugging folder

## breakpoints zetten

- zet een breakpoint op regel (16): `if(i % 2 == i2 % 2)`
- herlaad (refresh) de pagina zodat de code nogmaals loopt
- ga door de code totdat je in regel 18 ( `gfx ='#';` ) komt 
- maak een screenshot van de waardes van i & i2
- bewaar deze met filename `checkered.png`
- haal je breakpoint nu weg en laat de code `doorlopen` met de resume knop


## room bekijken

- zet een breakpoint op regel 31 ` this.room = new Room(10,10);`
- gebruik de `step over` knop om de regel over te slaan.
- bekijk nu `this.room` in het geheugen
- maak een screenshot van de tiles van room. klap hiervoor de eerste regel open (tiles -> [0] ->[0])
- bewaar deze met filename `tiles.png`

## callstack bekijken

- zet een breakpoint op regel 47 (`console.log(rowString);`)
- bekijk nu de callstack
- maak een screenshot van de deze callstack. 
- bewaar deze met filename `callstack.png`
- ga nu in de callstack naar `runApplication` door erop te clicken
- wat zie je nu gebeuren onder `scopes?`. wat voor geheugen/variabelen zie je nu?
    - schrijf dit in commentaar achter de code in de `.js` file

- maak een screenshot van de deze scope. 
- bewaar deze met filename `callstack2.png`

## extra

-  probeer nu tijdens het programma het geheugen aan te passen als je op een breakpoint staat

## klaar?

- commit & push de screenshots naar github in de map `debugging`
