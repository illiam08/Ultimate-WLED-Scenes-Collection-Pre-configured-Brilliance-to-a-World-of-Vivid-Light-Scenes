# WLED-Effekte

In diesem Repository findest du verschiedene sorgfältig erstellte WLED-Effekte zusammen mit ihren JSON-Konfigurationen und passendem Szene Bild mit Farbpalette.
Alle Effekte haben bereits eine voreingestellte Farbauswahl. Zudem sind alle Effekte ohne Segmenteinstellungen, sodass sie an jede beliebeige Wled Instanz anwendbar sein sollte. Du musst lediglich die Effekt Geschwindigkeit auf deinen Geschmack anpassen. 

## Verzeichnisstruktur

- **Bilder**: Dieser Ordner enthält Bilder der WLED-Effekte.
- **API-Commands**: Dieser Ordner enthält die json Strukturen der WLED-Presets.

## Installation


1. Gehe in deiner WLED-Weboberfläche auf die Preset-Seite.
   
2. Klicke dann auf das "+"-Symbol, um ein neues Preset zu erstellen und ändere den Namen zur entsprechenden Szene.
   
3. Klicke dann wiederum auf das eben erstellte Preset, um Zugang zur API-Command zur bekommen.
   
4. Füge hier nun den JSON-Code der entsprechenden Szene ein. Diesen findest du entweder in dem "API-Commands"-Ordner, oder in dem Code Feld unter jedem Szenen Bild. 
**WICHTIG:** Es dürfen keine Leerzeichen im API-Command verbleiben, da dies sonst zu Abstürzen führen kann durch Syntaxfehler.
   
5. Klicke anschließend auf "Speichern" und du bist fertig.

## WLED-Effekte

Hier ist eine Liste der verfügbaren WLED-Effekte:



##  **Sternennacht**: 

 Ein Effekt, der die Sterne einer klaren Nacht darstellt.

  ![Sternennacht](/bilder/sternennacht.png)
```json
{"bri":120,"seg":[{"id":0,"col":[[0,0,255],[255,255,0],[0,255,0]],"fx":95,"sx":60,"ix":180,"pal":5},{"id":1,"col":[[0,0,255],[255,255,0],[0,255,0]],"fx":95,"sx":60,"ix":180,"pal":5}]}
```
##  **Ozeanbrise**: 
 Ein Effekt, der die beruhigende Atmosphäre einer Meeresbrise einfängt.
  ![Ozeanbrise](/bilder/ozeanbrise.png)
```json
{"bri":100,"seg":[{"id":0,"col":[[0,255,255],[0,0,255],[255,255,255]],"fx":43,"sx":150,"ix":200,"pal":5},{"id":1,"col":[[0,255,255],[0,0,255],[255,255,255]],"fx":43,"sx":150,"ix":200,"pal":5}]}
```
##  **Lavastrom**: 
Ein Effekt, der die fließende Bewegung von Lava simuliert.
  ![Lavastrom](/bilder/lavastrom.png)
```json
{"bri":150,"seg":[{"id":0,"col":[[255,165,0],[255,0,0],[0,0,0]],"fx":47,"sx":80,"ix":220,"pal":5},{"id":1,"col":[[255,165,0],[255,0,0],[0,0,0]],"fx":47,"sx":80,"ix":220,"pal":5}]}
```
##  **Polarlicht**: 
Ein Effekt, der das farbenfrohe Leuchten des Polarlichts nachahmt.
  ![Polarlicht](/bilder/polarlicht.png)
```json
{"bri":150,"seg":[{"id":0,"col":[[255,165,0],[255,0,0],[0,0,0]],"fx":47,"sx":80,"ix":220,"pal":5},{"id":1,"col":[[255,165,0],[255,0,0],[0,0,0]],"fx":47,"sx":80,"ix":220,"pal":5}]}
```
##  **Waldzauber**: 
Ein Effekt, der die Magie eines verzauberten Waldes einfängt.
  ![Waldzauber](/bilder/waldzauber.png)
```json
{"bri":110,"seg":[{"id":0,"col":[[0,128,0],[255,255,0],[255,165,0]],"fx":52,"sx":120,"ix":230,"pal":5},{"id":1,"col":[[0,128,0],[255,255,0],[255,165,0]],"fx":52,"sx":120,"ix":230,"pal":5}]}
```
##  **Kosmischer Nebel**: 
Ein Effekt, der die geheimnisvolle Schönheit eines kosmischen Nebels darstellt.
  ![Kosmischer Nebel](/bilder/kosmischernebel.png)
```json
{"bri":140,"seg":[{"id":0,"col":[[255,0,255],[0,0,128],[255,255,255]],"fx":56,"sx":140,"ix":210,"pal":5},{"id":1,"col":[[255,0,255],[0,0,128],[255,255,255]],"fx":56,"sx":140,"ix":210,"pal":5}]}
```
##  **Sonnenuntergang**: 
Ein Effekt, der die warmen Farben eines Sonnenuntergangs widerspiegelt.
  ![Sonnenuntergang](/bilder/sonnenuntergang.png)
```json
{"bri":160,"seg":[{"id":0,"col":[[255,99,71],[255,140,0],[0,0,0]],"fx":63,"sx":170,"ix":190,"pal":5},{"id":1,"col":[[255,99,71],[255,140,0],[0,0,0]],"fx":63,"sx":170,"ix":190,"pal":5}]}
```
##  **Zaubergarten**: 
Ein Effekt, der die lebendigen Farben eines verzauberten Gartens zeigt.
  ![Zaubergarten](/bilder/zaubergarten.png)
```json
{"bri":90,"seg":[{"id":0,"col":[[127,0,255],[0,255,127],[255,0,127]],"fx":78,"sx":130,"ix":240,"pal":5},{"id":1,"col":[[127,0,255],[0,255,127],[255,0,127]],"fx":78,"sx":130,"ix":240,"pal":5}]}
```
##  **Geisterstunde**: 
Ein Effekt, der die düstere Atmosphäre einer Geisterstunde einfängt.
  ![Geisterstunde](/bilder/geisterstunde.png)
```json
{"bri":95,"seg":[{"id":0,"col":[[64,0,128],[255,0,255],[0,255,255]],"fx":101,"sx":110,"ix":215,"pal":5},{"id":1,"col":[[64,0,128],[255,0,255],[0,255,255]],"fx":101,"sx":110,"ix":215,"pal":5}]}
```
##  **Morgendämmerung**: 
Ein Effekt, der den sanften Übergang vom Dunkel zum Licht zeigt.
  ![Morgendämmerung](/bilder/morgendämmerung.png)
```json
{"bri":120,"seg":[{"id":0,"col":[[255,107,0],[255,182,77],[0,0,0]],"fx":118,"sx":70,"ix":240,"pal":5},{"id":1,"col":[[255,107,0],[255,182,77],[0,0,0]],"fx":118,"sx":70,"ix":240,"pal":5}]}
```
##  **Kristallhöhe**: 
Ein Effekt, der die klaren Farben und die Eleganz von Kristallen darstellt.
  ![kristallhöhe](/bilder/kristallhöhe.png)
```json
{"bri":130,"seg":[{"id":0,"col":[[0,255,255],[128,0,128],[255,255,255]],"fx":102,"sx":90,"ix":230,"pal":5},{"id":1,"col":[[0,255,255],[128,0,128],[255,255,255]],"fx":102,"sx":90,"ix":230,"pal":5}]}
```
##  **Tiefsee**: 
Ein Effekt, der die faszinierende Welt der Tiefsee erkundet.
  ![Tiefsee](bilder/tiefsee.png)
```json
{"bri":110,"seg":[{"id":0,"col":[[0,0,128],[0,128,128],[0,255,255]],"fx":47,"sx":50,"ix":250,"pal":5},{"id":1,"col":[[0,0,128],[0,128,128],[0,255,255]],"fx":47,"sx":50,"ix":250,"pal":5}]}
```
##  **Herbstwald**: 
Ein Effekt, der die warmen Farben eines herbstlichen Waldes widerspiegelt.
  ![Herbstwald](/bilder/herbstwald.png)
```json
{"bri":140,"seg":[{"id":0,"col":[[255,102,0],[204,51,0],[0,0,0]],"fx":99,"sx":80,"ix":220,"pal":5},{"id":1,"col":[[255,102,0],[204,51,0],[0,0,0]],"fx":99,"sx":80,"ix":220,"pal":5}]}
```
##  **Galaktischer Zug**: 
Ein Effekt, der die dynamische Bewegung eines galaktischen Zuges zeigt.
  ![Galaktischer Zug](/bilder/galaktischerzug.png)
```json
{"bri":150,"seg":[{"id":0,"col":[[255,0,0],[0,0,255],[255,255,0]],"fx":56,"sx":100,"ix":200,"pal":5},{"id":1,"col":[[255,0,0],[0,0,255],[255,255,0]],"fx":56,"sx":100,"ix":200,"pal":5}]}
```
##  **Frühlingswiese**: 
Ein Effekt, der die Frische und Lebendigkeit einer Frühlingswiese einfängt.
  ![Frühlingswiese](/bilder/frühlingswiese.png)
```json
{"bri":135,"seg":[{"id":0,"col":[[127,255,0],[255,255,127],[0,255,127]],"fx":52,"sx":75,"ix":230,"pal":13},{"id":1,"col":[[127,255,0],[255,255,127],[0,255,127]],"fx":52,"sx":75,"ix":230,"pal":13}]}
```
##  **Nordlichter**: 
Ein Effekt, der die mystische Schönheit der Nordlichter zeigt.
  ![Nordlichter](/bilder/nordlichter.png)
```json
{"bri":130,"seg":[{"id":0,"col":[[102,204,255],[5,255,178],[255,255,255]],"fx":26,"sx":100,"ix":250,"pal":5},{"id":1,"col":[[102,204,255],[5,255,178],[255,255,255]],"fx":26,"sx":100,"ix":250,"pal":5}]}
```
##  **Glühwürmchen**: 
Ein Effekt, der die sanften Lichter von Glühwürmchen im Dunkeln simuliert.
  ![Glühwürmchen](/bilder/glühwürmchen.png)
```json
{"bri":110,"seg":[{"id":0,"col":[[255,255,0],[0,0,0],[0,0,0]],"fx":88,"sx":30,"ix":255,"pal":5},{"id":1,"col":[[255,255,0],[0,0,0],[0,0,0]],"fx":88,"sx":30,"ix":255,"pal":5}]}
```
##  **Nordlichter**: 
Ein Effekt, der eine weitere Darstellung der faszinierenden Nordlichter bietet.
  ![Nordlichter 2](/bilder/nordlichter.png)
```json
{"bri":140,"seg":[{"id":0,"col":[[255,102,0],[204,51,0],[0,0,0]],"fx":99,"sx":80,"ix":220,"pal":5},{"id":1,"col":[[255,102,0],[204,51,0],[0,0,0]],"fx":99,"sx":80,"ix":220,"pal":5}]}
```
##  **Feuriger Himmel**: 
Ein Effekt, der die Hitze und Intensität eines feurigen Himmels zeigt.
  ![Feuriger Himmel](/bilder/feurigerhimmel.png)
```json
{"bri":170,"seg":[{"id":0,"col":[[255,69,0],[255,140,0],[255,0,0]],"fx":62,"sx":45,"ix":210,"pal":5},{"id":1,"col":[[255,69,0],[255,140,0],[255,0,0]],"fx":62,"sx":45,"ix":210,"pal":5}]}
```
##  **Zen Garten**: 
Ein Effekt, der die Ruhe und Harmonie eines Zen-Gartens vermittelt.
  ![Zen Garten](/bilder/zengarten.png)
```json
{"bri":160,"seg":[{"id":0,"col":[[128,128,128],[255,255,255],[0,255,0]],"fx":56,"sx":35,"ix":240,"pal":5},{"id":1,"col":[[128,128,128],[255,255,255],[0,255,0]],"fx":56,"sx":35,"ix":240,"pal":5}]}
```
##  **Digitaler Regen**: 
Ein Effekt, der den beruhigenden Anblick von digitalem Regen simuliert.
  ![Digitaler Regen](/bilder/digitalerregen.png)
```json
{"bri":190,"seg":[{"id":0,"col":[[0,255,0],[0,128,0],[0,64,0]],"fx":90,"sx":15,"ix":250,"pal":5},{"id":1,"col":[[0,255,0],[0,128,0],[0,64,0]],"fx":90,"sx":15,"ix":250,"pal":5}]}
```
##  **Mystische Dämmerung**: 
Ein Effekt, der die geheimnisvolle Stimmung einer mystischen Dämmerung einfängt.
  ![Mystische Dämmerung](/bilder/mystischedämmerung.png)
```json
{"bri":175,"seg":[{"id":0,"col":[[75,0,130],[255,20,147],[0,0,128]],"fx":73,"sx":55,"ix":230,"pal":5},{"id":1,"col":[[75,0,130],[255,20,147],[0,0,128]],"fx":73,"sx":55,"ix":230,"pal":5}]}
```
##  **Mondlichtklarheit**: 
Ein Effekt, der die klare und ruhige Atmosphäre einer mondhellen Nacht widerspiegelt.
  ![Mondlichtklarheit](/bilder/mondlichtklarheit.png)
```json
{"bri":130,"seg":[{"id":0,"col":[[220,220,255],[192,192,255],[0,0,0]],"fx":75,"sx":20,"ix":250,"pal":5},{"id":1,"col":[[220,220,255],[192,192,255],[0,0,0]],"fx":75,"sx":20,"ix":250,"pal":5}]}
```
##  **Funkelnder Weinberg**: 
Ein Effekt, der die romantische Atmosphäre eines funkelnden Weinbergs zeigt.
  ![Funkelnder Weinberg](/bilder/funkelnderweinberg.png)
```json
{"bri":145,"seg":[{"id":0,"col":[[153,0,153],[51,204,51],[0,255,0]],"fx":88,"sx":60,"ix":220,"pal":5},{"id":1,"col":[[153,0,153],[51,204,51],[0,255,0]],"fx":88,"sx":60,"ix":220,"pal":5}]}
```
##  **Ruhe der Tiefe**: 
Ein Effekt, der die Stille und Tiefe eines ruhigen Ozeans darstellt.
  ![Ruhe der Tiefe](/bilder/ruhedertiefe.png)
```json
{"bri":120,"seg":[{"id":0,"col":[[0,51,102],[0,76,153],[0,0,0]],"fx":47,"sx":25,"ix":255,"pal":5},{"id":1,"col":[[0,51,102],[0,76,153],[0,0,0]],"fx":47,"sx":25,"ix":255,"pal":5}]}
```
##  **Aurora Träume**: 
Ein Effekt, der die träumerische Schönheit eines Aurora-Himmels einfängt.
  ![Aurora Träume](/bilder/aurora.jpg)
```json
{"bri":160,"seg":[{"id":0,"col":[[255,192,203],[135,206,235],[173,216,230]],"fx":26,"sx":30,"ix":200,"pal":5},{"id":1,"col":[[255,192,203],[135,206,235],[173,216,230]],"fx":26,"sx":30,"ix":200,"pal":5}]}
```  
##  **Wüstenhimmel**: 
Ein Effekt, der die Atmosphäre eines Wüstenhimmels nachahmt.
  ![Wüstenhimmel](/bilder/wüstenhimmel.png)
```json
{"bri":155,"seg":[{"id":0,"col":[[255,140,0],[255,165,0],[64,224,208]],"fx":63,"sx":45,"ix":215,"pal":5},{"id":1,"col":[[255,140,0],[255,165,0],[64,224,208]],"fx":63,"sx":45,"ix":215,"pal":5}]}
```







