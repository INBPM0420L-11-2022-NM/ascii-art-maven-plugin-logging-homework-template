# ASCII Art Maven Plugin + Logging

Készíts egy Maven plugint, amely egy ASCII artot ír a konzolra buildeléskor, illetve használj logolást is.

### Követelmények:

* Megoldásként clone-ozd le ezt a repót, és hozz létre benne egy `Maven` projektet. A `pom.xml`-ben tüntesd fel magad a `developers/developer` elemben.
  * *Tipp a Maven inicializálásához*: nyisd meg IntelliJ-ben a leclone-ozott mappát, majd a bal oldali projekt struktúrában jobb kattolj a gyökérkönyvtárra, és válaszd az `Add Framework Support...` opciót. Ennek hatására előjön egy menü, ott keresd ki a listából a Mavent és pipáld be.
* Helyezz el három darab, ASCII artot tartalmazó `txt` fájlt a `resources` mappán belül (pl. `llama.txt`).
* A pluginnak legyen egy célja, ami a három fájl közül egyet kiválaszt véletlenszerűen, és a kimenetre írja a fájlban található ASCII artot.
* A pluginnak legyen egy paramétere, amivel megadható, hogy melyik artot szeretnénk a kimenetre írni (pl. `llama`). Ebben az esetben véletlenszerű választás nem kell, csak a kért art megjelenítése. Ha helytelen azonosítót kér a felhasználó, akkor pedig egy hibaüzenetet írjon ki a plugin.
  * **Fontos**: a fájl nevét kiterjesztés nélkül adjuk meg a paraméterben (emiatt szerepel a példában szándékosan csak `llama`, nem pedig `llama.txt`)
* Tetszőleges logoló keretrendszer használatával írj logüzeneteket a standard outputra, illetve az INFO típusú logüzeneteket írasd ki egy fájlba is. 

A fenti követelményeken kívüli további részletek rád vannak bízva (pl. a plugin neve, a cél neve stb.)

#### A következő oldalak hasznosak lehetnek:

* Maven plugin készítés: https://www.baeldung.com/maven-plugin
* ASCII artok: https://www.asciiart.eu/
* Reading a file from the Classpath szekció ebből a posztból (valamint a [stream-playground](https://github.com/jeszy75/stream-playground) projekt `Repository` kódja): https://www.baeldung.com/reading-file-in-java

A megoldásodat pushold fel ennek a repónak a master branchébe.
