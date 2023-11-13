
## Van data naar html

We gaan nu data maken:
- maak een nieuwe array aan noem deze `data`
- geef deze array de `5 teksten` van opdracht `03` als inhoud (tussen de `[]`)

> deze data gaan we in onze headers zetten  
> !! `let op` dit werkt omdat we 5 headers (`<h1>`) in onze html hebben


## Loop en plaats data

> dit is een voorbeeld, deze kan je later gebruiken in een iets andere vorm om bv articelen uit een database te halen en dan naar html om kunt zetten

- `loop` over de `data` heen
- voor `elk element` in `data` *(elke `stap` van i)*:
    - zet je de `i +": "+data[i]` in de innerText van `headersByCssClass[i]`
        - denk aan de `assignment operator` (`=`)

- dan zou je zo iets moeten zien:

</br>![](img/data.PNG)

## klaar?

- commit & push je werk naar github
