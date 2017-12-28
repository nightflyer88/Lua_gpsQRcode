# LUA GPS to QR-Code
Die App ist dazu gedacht, anhand der letzten GPS Position das Modell 
wieder zu finden. 
Dazu wird die GPS Position in einen GoogleMaps-link
verpackt und anschliessend in ein QR-Code umgewandelt, und kann danach 
mit jedem Smartphone gelesen werden. 

Einen QR-Code zu erzeugen braucht extrem viel CPU-Leistung und auch viel Speicher.
Da die App nur im "Notfall" benötigt wird, muss die App nicht zwingend
im jeweiligen Modell aktiv sein. Es reicht wenn die App einfach im 
Sender gespeichert ist, und bei bedarf aktiviert wird.


Installation:
- kopiere die Datei gpsQRcode.lc und den Ordner /gpsQRcode in den /Apps Ordner

![screen001](https://raw.githubusercontent.com/nightflyer88/Lua_gpsQRcode/master/img/Screen001.bmp)
![screen002](https://raw.githubusercontent.com/nightflyer88/Lua_gpsQRcode/master/img/Screen002.bmp)
![screen003](https://raw.githubusercontent.com/nightflyer88/Lua_gpsQRcode/master/img/Screen003.bmp)

Copyright (c) 2017 by M.Lehmann
QR-Code Generator Lib Copyright (c) 2012, Patrick Gundlach
