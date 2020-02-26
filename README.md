# FinedustMonitorWithGPS
Fine dust (air pollution) monitoring station. Air pollution monitoring channel updates once every minute with PM10.0 and PM2.5 readings from the Nova PM (SDS011) Sensor. Also includes real time location tracking capabilities using the GY-NEO6MV2 GPS Sensor.
 
### Please note
>This project requires a GY-NEO6MV2 GPS Sensor. For a project that does not require a GPS module, Please visit the following link: https://github.com/happybono/FinedustMonitor
 
![Final Product](20191126_082913.jpg)

## What's New
### November 24, 2019
>[Initial Release.](https://github.com/happybono/FinedustMonitorWithGPS/commit/aa9cbf7b85308d91ce775d71c36cdd96b5740529)

### December 16, 2019
>[Read GPS data from ThingSpeak and displays it on Google Maps using ESP12e NodeMCU and GPSNeo6MV2 Module.](https://github.com/happybono/FinedustMonitorWithGPS/blob/master/Maps/GoogleMaps.html "FinedustMonitorWithGPS/Maps/GoogleMaps.html")

### December 25, 2019
>[Now supports [Channel Status Updates] in ThingSpeak](https://thingspeak.com/channels/920137) : Updated [FinedustMonitorWithGPS.ino](https://github.com/happybono/FinedustMonitorWithGPS/commit/01367946fd2dc10b39b39dec19309892311e92ea "/FinedustMonitorWithGPS/FinedustMonitorWithGPS.ino"), [server.ino](https://github.com/happybono/FinedustMonitorWithGPS/commit/3c3a89e9d8a4e45f591379dc96e2e7b67e15914d "/FinedustMonitorWithGPS/server.ino")

### December 29, 2019
>[Various bugs fixed.](https://github.com/happybono/FinedustMonitorWithGPS/commit/d6d25d7cf4dc4b91f174259ea1e473220ab79385)

### January 20, 2020
>["Latest PM sensor readings" plugin added in ThingSpeak.](https://github.com/happybono/FinedustMonitorWithGPS/tree/master/Plugins)

### January 21, 2020
>[Displays additional information](https://github.com/happybono/FinedustMonitorWithGPS/blob/2882255266a72da46fa2a047b24e56b23cf94838/Plugins/StatusUpdates/CSS.css#L10) ([temperature](https://github.com/happybono/FinedustMonitorWithGPS/blob/2882255266a72da46fa2a047b24e56b23cf94838/Plugins/StatusUpdates/JavaScript.html#L34), [latitude](https://github.com/happybono/FinedustMonitorWithGPS/blob/2882255266a72da46fa2a047b24e56b23cf94838/Plugins/StatusUpdates/JavaScript.html#L35), [longitude](https://github.com/happybono/FinedustMonitorWithGPS/blob/2882255266a72da46fa2a047b24e56b23cf94838/Plugins/StatusUpdates/JavaScript.html#L36)) in the[ "Latest PM sensor readings" plugin.](https://github.com/happybono/FinedustMonitorWithGPS/tree/master/Plugins/StatusUpdates)<br>
>Various bugs fixed.

### January 24, 2020
>[Added Reverse Geocoding function in Google Maps.](https://github.com/happybono/FinedustMonitorWithGPS/blob/95abbb8ae55be63581fe9892d7d798f0c71eb8e6/Maps/GoogleMaps.html#L26)<br>
>[Optimized loading time for Google Maps.](https://github.com/happybono/FinedustMonitorWithGPS/blob/95abbb8ae55be63581fe9892d7d798f0c71eb8e6/Maps/GoogleMaps.html)

### Jaunary 25, 2020
>[Added an onclick event to displayed marker in Google Maps.](https://github.com/happybono/FinedustMonitorWithGPS/blob/95abbb8ae55be63581fe9892d7d798f0c71eb8e6/Maps/GoogleMaps.html#L80)

### February 05, 2020
>[Added VBA (Visual Basic for Applications) code for reverse geocoding support in Microsoft Excel.](https://github.com/happybono/FinedustMonitorWithGPS/blob/master/Maps/Excel/ReverseGeocoding.vb)<br>
><img src="https://github.com/happybono/FinedustMonitorWithGPS/blob/master/powered_by_msexcel_on_white.png" alt="Powered by MSExcel logo" width="217"/><br><br>
>[Added Javascript (.gs) code for reverse geocoding support in Google Sheets.](https://github.com/happybono/FinedustMonitorWithGPS/blob/master/Maps/Excel/GoogleSheets.gs) ([ⓒ 2018 Christos Samaras](https://myengineeringworld.net/2018/08/geocoding-reverse-gas.html))<br>
>[Added Javascript (.gs) code for reverse geocoding macro support in Google Sheets.](https://github.com/happybono/FinedustMonitorWithGPS/blob/master/Maps/Excel/GoogleSheetsGeocodingMacro.gs) ([ⓒ 2016 - 2017 Max Vilimpoc](https://github.com/nuket/google-sheets-geocoding-macro))<br>
><img src="https://github.com/happybono/FinedustMonitorWithGPS/blob/master/powered_by_google_on_white.png" alt="Powered by Google logo" width="150"/>

### February 19, 2020
> [Optimized performance for data processing.](https://thingspeak.com/channels/976688/api_keys)

### February 20, 2020
> ["Email Alert" function added as a ThingSpeak Analysis plug-in.](https://github.com/happybono/FinedustMonitorWithGPS/blob/master/Plugins/Email/EmailNotifier.m) 

### February 24, 2020
> [Generated a QR code for faster and more convenient access to the ThingSpeak dashboard.](https://camo.githubusercontent.com/73143c13b7e99572346cd75ab1d010d677786862/68747470733a2f2f6868716561772e626e2e66696c65732e316472762e636f6d2f79346d7050454a62504a63593074416c6777342d4533326c74464e36455576317044554a666557756670434b594a7446663662464a3159427274797a7a37317335656444334f795a49326f5657385557524c624d45656d68634e484f31507976795349587276486b434e34644678482d647a776e6c41596f6e676a477578496d467468797163646557585f7479457574506c3153464233727332436c5f472d456f566b6a6148636458734e364c75566c4c3659357641523650537a536c663359503635567838416b42616641457a4e4e42504142534a6277773f77696474683d323531266865696768743d333536) <br><br>
> <img src="https://happybono.files.wordpress.com/2020/02/qrcode.png" width="210" height="356" alt="QRCode"/>

### February 26, 2020
> [Performance improvements (up to 2× as faster than before) in the ADDRGEOCODE function in ReverseGeocoding.vb.](https://github.com/happybono/FinedustMonitorWithGPS/blob/master/Maps/Excel/ReverseGeocoding.vb#L86) <br>
> [Now supports Unicode using the Microsoft ActiveX Data Objects Library in the ADDRGEOCODE function in the ReverseGeocoding.vb.](https://github.com/happybono/FinedustMonitorWithGPS/blob/master/Maps/Excel/ReverseGeocoding.vb#L115)

## Specifications
### Scenarios
* Measuring the fine dust contamination level in the air in real time. The value is displayed on the OLED Screen, and updated every second.
* Measuring the current temperature.
* Track and update device location in a real time.
* Reading GPS data (longitude, latitude) from [ThingSpeak](https://thingspeak.com/channels/920137) and display it using [Google Maps](https://www.google.com/maps/) with the [Maps JavaScript API](https://developers.google.com/maps/documentation/javascript/tutorial).
* Refining data and synchronize with the web-based cloud service. (i.e. [ThingSpeak](https://www.thingspeak.com/), [Plaive](https://plaive.10make.com/))
* Using reverse geocoding to convert a location (latitude, longitude) measured by the device to a readable address.

#### What is Reverse Geocoding?
>Reverse geocoding is the process of back (reverse) coding of a point location (latitude, longitude) to a readable address or place name. This permits the identification of nearby street addresses, places, and/or areal subdivisions such as neighbourhoods, county, state, or country.

[More information on reverse geocoding with Google Maps JavaScript API](https://developers.google.com/maps/documentation/geocoding/intro#ReverseGeocoding)
<br>
<img src="https://github.com/happybono/FinedustMonitorWithGPS/blob/master/powered_by_google_on_white.png" alt="Powered by Google logo" width="150"/>

### Connections
* 1 x Micro-USB

### Wireless
* IEEE 802.11 b/g/n Wi-Fi technology.

### Battery life 
* Up to 16 hours of typical device usage.

## Apparatus (Equipment)
### Platform
* ESP8266 NodeMCU

### SDS011 Dust Sensor
* Soldering required
* D1 : TX of SDS011

### 0.96" I2C OLED Display 
* Soldering required
* D3 : Data, D2 : Clock

### GY-NEO6MV2 GPS Sensor
* Soldering required
* D6 & D7 : TX & RX of GY-NEO6MV2 respectively.

### DS18820 Temperature Sensor (Thermometer)
* Soldering required
* D4 : Data

### KOKIRI A-PACK FIXIE 5 (KP-LS50) Portable Battery
* USB Port : Power
* Micro-USB : Charging Port
* Dimension : 62.3 mm (W) × 112.0 mm (D) × 13.0 mm (H)
* Input : DC-5V / 2A
* Output : DC-5V / 2.1A
* Capacity : 5000 mAh

## Data Refinement / Synchronization
### ThingSpeak
* ThingSpeak (https://thingspeak.com/channels/920137)
![ThingSpeak Screenshot](ThingSpeak.png)
  
### Plaive
* Plaive (https://plaive.10make.com/)
![Plaive Screenshot](Plaive.png)

## Drivers
Please install https://github.com/squix78/esp8266-oled-ssd1306

## References
* Christos Samaras 2018, Geocoding & Reverse Geocoding Functions In Google Sheets, My Engineering World, Christos Samaras, viewed 5 February 2020, <https://myengineeringworld.net/2018/08/geocoding-reverse-gas.html>.
* Max Vilimpoc 2019, nuket/google-sheets-geocoding-macro, GitHub, Nuket. viewed 5 February 2020, <https://github.com/nuket/google-sheets-geocoding-macro>.
* ThingPulse 2020, ThingPulse/esp8266-oled-ssd1306, GitHub, ThingPulse, viewed 24 November 2019, <https://github.com/ThingPulse/esp8266-oled-ssd1306>.
* Tillaart, Rob 2018, RobTillaart/Arduino, GitHub, RobTillaart, viewed 23 February 2020, <https://github.com/RobTillaart/Arduino/blob/master/libraries/RunningMedian/RunningMedian.cpp>.
