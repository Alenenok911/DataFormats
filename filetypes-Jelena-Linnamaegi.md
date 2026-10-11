# Datensatz : Borschtsch-Rezept

 Diese Datensturkur beschreibt das Rezept "Russischer Borschtsch" von GUSTO für sechs Portionen. 
 Sie enthält Angaben zum Rezept, eine Zutatenliste und ein verschachteltes Objekt mit der Rezeptquelle.

 Quelle : [GUSTO](https://www.gusto.at/rezepte/russischer-borschtsch-7684962)

## Felder

  - `name`(Text): Name des Rezepts
  - `portionen`(Zahl): Anzahl der Portionen
  - `zeitangabeMinuten`(Zahl): Zeitangabe aus der Rezeptübersicht in Minuten
  - `schwierigkeitsgrad`(Text) : Schwierigkeit des Rezepts
  - `vegetarisch`(Wahrheitswert):`false´, weil dieses Rezept Fleisch enthält
  - `zutaten`(Liste von Text): Zutaten mit Mengenangaben
  - `quelle`(Objekt): mit `name` und `url`

## Als JSON (`daten.json`)

```json
{
  "name": "Russischer Borschtsch",
  "portionen": 6,
  "zeitangabeMinuten": 60,
  "schwierigkeitsgrad": "leicht",
  "vegetarisch" : false,
  "zutaten": [
     "Suppe: 300 g Schweinsschopfbraten (ausgelöst)",
     "Suppe: 1 Zwiebel",
     "Suppe: 1 Bund Wurzelwerk",
     "Einlage: 250 g Weißkraut",
     "Einlage: 200 g Rote Rüben",
     "Einlage: 200 g Karotten",
     "Einlage: 200 g Erdäpfel (speckig)",
     "Einlage: 200 g Knollensellerie",
     "Einlage: 1 Zwiebel",
     "Einlage: 150 g Frühstücksspeck",
     "Einlage: 125 ml Sauerrahm",
      "Salz",
      "Pfeffer", 
      "Pfefferkörner",
      "Lordbeerblatt",
      "Paradeismark", 
      "Essig (Rotweinessig)",
      "Öl (oder Margarine)"
  ],
  "quelle": {
    "name": "GUSTO",
    "url": "https://www.gusto.at/rezepte/russischer-borschtsch-7684962"
  }
}
```
## Als YAML(`daten.yml`)

  ```yaml
  # Rezept der Russischer Borschtsch
  name: Russischer Borschtsch
  portionen: 6
  zeitangabeMinuten: 60
  schwierigkeitsgrad: leicht
  vegetarisch: false
  zutaten:
   - "Suppe: 300 g Schweinsschopfbraten (ausgelöst)"
   - "Suppe: 1 Zwiebel"
   - "Suppe: 1 Bund Wurzelwerk"
   - "Einlage: 250 g Weißkraut"
   - "Einlage: 200 g Rote Rüben"
   - "Einlage: 200 g Karotten"
   - "Einlage: 200 g Erdäpfel (speckig)"
   - "Einlage: 200 g Knollersellerie"
   - "Einlage: 1 Zwiebel"
   - "Einlage: 150 g Frühstücksspeck"
   - "Einlage: 125 ml Sauerrahm"
   -  Salz
   -  Pfeffer
   -  Pfefferkörner
   -  Lorbeerblatt
   -  Paradeismark
   -  Essig (Rotweinessig)
   -  Öl (oder Margarine)
quelle:
    name: GUSTO
    url: https://www.gusto.at/rezepte/russischer-borschtsch-7684962
```

## Als XML (`daten.xml`)

```xml
<?xml version="1.0" encoding="UTF-8"?>
<rezept>
  <name>Russicher Borschtsch</name>
  <portionen>6</portionen>
  <zeitangabeMinuten>60</zeitangabeMinuten>
  <schwierigkeitsgrad>leicht</schwierigkeitsgrad>
  <vegetarisch>false</vegetarisch>
  <zutaten>
    <zutat>Suppe: 300 g Schweinsschopfbraten (ausgelöst)</zutat>
    <zutat>Suppe: 1 Zwiebel</zutat>
    <zutat>Suppe: 1 Bund Wurzelwerk</zutat>
    <zutat>Einlage: 250 g Weißkraut</zutat>
    <zutat>Einlage: 200 g Rote Rüben</zutat>
    <zutat>Einlage: 200 g Karotten</zutat>
    <zutat>Einlage: 200 g Erdäpfel (speckig)</zutat>
    <zutat>Einlage: 200 g Knollersellerie</zutat>
    <zutat>Einlage: 1 Zwiebel</zutat>
    <zutat>Einlage: 150 g Frühstücksspeck</zutat>
    <zutat>Einlage: 125 ml Sauerrahm</zutat>
    <zutat>Salz</zutat>
    <zutat>Pfeffer</zutat>
    <zutat>Pfefferkörner</zutat>
    <zutat>Lorbeerblatt</zutat>
    <zutat>Paradeismark</zutat>
    <zutat>Essig (Rotweinessig)</zutat>
    <zutat>Öl (oder Margarine)</zutat>
  </zutaten>
  <quelle>
    <name>GUSTO</name>
    <url>https://www.gusto.at/rezepte/russischer-borschtsch-7684962</url>
  </quelle>
</rezept>
```

## Als CSV (`daten.csv`)

```csv
name,portionen,zeitangabeMinuten,schwierigkeitsgrad,vegetarisch,zutaten,quelle_name,quelle_url
Russischer Borschtsch,6,60,leicht,false,"Suppe: 300 g Schweinsschopfbraten (ausgelöst)|Suppe: 1 Zwiebel|Suppe: 1 Bund Wurzelwerk|Einlage: 250 g Weißkraut|Einlage: 200 g Rote Rüben|Einlage: 200 g Karotten|Einlage: 200 g Erdäpfel (speckig)|Einlage: 200 g Knollensellerie| Einlage: 1 Zwiebel|Einlage: 150 g Frühstücksspeck| Einlage: 125 ml Sauerrahm|Salz|Pfeffer|Pfefferkörner|Lorbeerblatt|Paradeismark|Essig(Rotweinessig)|Öl(oder Margarine)",GUSTO,https://www.gusto.at/rezepte/russischer-borschtsch-7684962
```


