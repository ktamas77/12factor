Háttér
======

Ezen dokumentum szerzői közvetlenül járultak hozzá több száz alkalmazás fejlesztéséhez és telepítéséhez, és közvetetten elősegítették a fejlesztését, működtetését és skálázását több százezer applikációnak a <a href="http://www.heroku.com/" target="_blank">Heroku</a> platformon.

Ezen írás összefoglalja az összes tapasztalatot és megfigyelést amit software-as-a-service applikációk éles változatainak széles választékán figyeltünk meg. Ez egy útmutató az ideális szoftverfejlesztési gyakorlatok, különös figyelmet fordítva az alkalmazás természetes növekedési dinamikájára, az alkalmazáson kódján dolgozó fejlesztők közötti együttműködés, és a <a href="http://blog.heroku.com/archives/2011/6/28/the_new_heroku_4_erosion_resistance_explicit_contracts/" target="_blank">szoftver eróziójából eredő költségek elkerülése</a> között.

A motivációnk a figyelemfelhívás néhány rendszerszintű problémára ami modern alkalmazásfejlesztéskor fordulhat elő, hogy közös szókincset biztosítsunk ezen problémák megbeszélésére, és hogy széleskörű megoldásokat biztosítsunk ezen problémákra a hozzátartozó szakkifejezésekkel. A formátumot Martin Flower *<a href="https://books.google.com/books/about/Patterns_of_enterprise_application_archi.html?id=FyWZt5DdvFkC" target="_blank">Patterns of Enterprise Application Architecture</a>* és *<a href="https://books.google.com/books/about/Refactoring.html?id=1MsETFPD3I0C" target="_blank">Refactoring</a>* című könyvei nyújtották.

