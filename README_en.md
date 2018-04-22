# GPS to QR-Code

If you've lost your model, this app generates a QR-code with a google-map link 
of the last GPS-position. After that, the QR-code can be read with 
any smartphone and displayed on the map.

The app takes a lot of memory and CPU power, so it only runs on a DC/DS24.
Since the app is needed only in an "emergency", the app does not necessarily
be active in the model. It's enough if the app just in transmitter is stored, 
and if necessary activated.

![screen001](https://raw.githubusercontent.com/nightflyer88/Lua_gpsQRcode/master/img/Screen001.bmp)
![screen002](https://raw.githubusercontent.com/nightflyer88/Lua_gpsQRcode/master/img/Screen002.bmp)
![screen003](https://raw.githubusercontent.com/nightflyer88/Lua_gpsQRcode/master/img/Screen003.bmp)
![iphone](https://raw.githubusercontent.com/nightflyer88/Lua_gpsQRcode/master/img/iPhone.png)

```
Version history:
V1.2 22.04.18 Lat/Lon position was displayed in the wrong sequence for some sensors. When the GPS sensor loses the fix, the last known position is displayed
V1.1 29.12.17 GPS format changed to decimal degree, various optimizations
V1.0 28.12.17 Initial Release
```