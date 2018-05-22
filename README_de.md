# GPS to QR-Code

Wenn Du dein Modell verloren hast, generiert diese App einen QR-Code mit 
einem Google-Map link der letzten GPS-Position. Danach kann der QR-Code 
mit jedem Smartphone gelesen, und auf der Karte dargestellt werden.

Die App braucht viel Speicher und CPU-Leistung, daher läuft diese nur auf einer DC/DS24.
Da die App nur im "Notfall" benötigt wird, muss die App nicht zwingend
im jeweiligen Modell aktiv sein. Es reicht wenn die App einfach im 
Sender gespeichert ist, und bei Bedarf aktiviert wird.

![screen001](https://raw.githubusercontent.com/nightflyer88/Lua_gpsQRcode/master/img/Screen001.bmp)
![screen002](https://raw.githubusercontent.com/nightflyer88/Lua_gpsQRcode/master/img/Screen002.bmp)
![screen003](https://raw.githubusercontent.com/nightflyer88/Lua_gpsQRcode/master/img/Screen003.bmp)
![iphone](https://raw.githubusercontent.com/nightflyer88/Lua_gpsQRcode/master/img/iPhone.png)

```
Versionen:
V1.4 22.05.18 Fehler beim Log-Datei Import behoben
V1.3 12.05.18 Log Dateien können eingelesen werden, es wird automatisch nach der letzten GPS Position gesucht
V1.2 22.04.18 Lat/Lon Position wurde bei einigen Sensoren in der falschen Reienfolge angezeigt. Wenn der GPS Sensor den Fix verliert, wird die letzte bekannte Position angezeigt 
V1.1 29.12.17 GPS-Format nach Dezimalgrad geändert, div. Optimierungen
V1.0 28.12.17 Erstversion V1.0
```