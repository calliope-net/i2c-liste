
> Diese Seite bei [https://calliope-net.github.io/i2c-liste/](https://calliope-net.github.io/i2c-liste/) öffnen.

Das Bild zeigt 15 i2c Module, die alle am Calliope funktionieren und mit Blöcken programmiert werden können.
Für alle 15 Module können hier die Erweiterungen herunter geladen werden, die - genau wie die Module - beliebig miteinander kombiniert werden können. 

Der linke Steckverbinder A0 am Calliope ist der i2c-Bus. An einen Bus können viele Module gleichzeitig angeschlossen werden.

Technisch alle gleichzeitig an den i2c Bus angeschlossen werden können. Mit einem Stecker an Calliope A0.
Getestet wurde mit 7 Modulen gleichzeitig und es hat funktioniert. Für alle 15 Module können aber hier die Erweiterungen herunter geladen werden,
die - genau wie die Module - beliebig miteinander kombiniert werden können. 

Wenn die Stromversorgung des Calliope über USB Kabel erfolgt, reicht das für die angeschlossenen Module (außer den 4 Relais) aus.
Die roten Qwiic Module dürfen auch nur mit 3,3V Logik betrieben werden. Im Dauerbetrieb über Tag und Nacht ist noch kein Projekt abgestürzt.

Und es ist kein teures Hobby. Über die Bezugsquellen unten kosten viele Module nur um 5 € und das große Display 25 €.
Verglichen mit den in der Schule üblichen Baukästen ist das sogar eine preiswerte Alternative.

![](DSC09940-1440.jpg)

### Liste der i2c Module für Calliope (Produkt Seite der Hersteller):

##### SparkFun - [Qwiic](https://www.sparkfun.com/categories/399) - Making I2C as easy as possible.
* [SparkFun 20x4 SerLCD - RGB Backlight (Qwiic)](https://www.sparkfun.com/products/16398)
* [SparkFun Qwiic EEPROM Breakout - 512Kbit](https://www.sparkfun.com/products/18355)
* [SparkFun Qwiic OpenLog](https://www.sparkfun.com/products/15164)
* [SparkFun Qwiic Keypad - 12 Button](https://www.sparkfun.com/products/15290)
* [SparkFun Qwiic GPIO](https://www.sparkfun.com/products/17047)
* [SparkFun Qwiic Joystick](https://www.sparkfun.com/products/15168)
* [SparkFun Qwiic Motor Driver](https://www.sparkfun.com/products/15451)

##### seeed studio - [Grove](https://wiki.seeedstudio.com/Grove_System/)

* [Grove - High Precision RTC (Real Time Clock)](https://wiki.seeedstudio.com/Grove_High_Precision_RTC/)
* [Grove - OLED Yellow&Blue Display 0.96(SSD1315)](https://wiki.seeedstudio.com/Grove-OLED-Yellow&Blue-Display-0.96-SSD1315_V1.0/) / [Grove - OLED Display 0.96 inch](https://wiki.seeedstudio.com/Grove-OLED_Display_0.96inch/)
* [Grove - 16x2 LCD](https://wiki.seeedstudio.com/Grove-16x2_LCD_Series/)
* [Grove - 6-Position DIP Switch](https://wiki.seeedstudio.com/Grove-6-Position_DIP_Switch/) / [Grove - 5-Way Switch](https://wiki.seeedstudio.com/Grove-5-Way_Switch/)
* [Grove - 4-Channel SPDT Relay](https://wiki.seeedstudio.com/Grove-4-Channel_SPDT_Relay/)

##### DFRobot - [Gravity](https://www.dfrobot.com/gravity.html)
* [Gravity: I2C Digital Wattmeter](https://www.dfrobot.com/product-1827.html)

##### Kabel und Adapter

* [Grove - I2C Hub(6 Port)](https://wiki.seeedstudio.com/Grove-I2C-Hub-6Port/)
* [Qwiic Cable - Grove Adapter](https://www.sparkfun.com/products/15109)
* [Qwiic Cable Kit](https://www.sparkfun.com/products/15081)

Alle i2c Module werden parallel am linken Grove Steckverbinder A0 angeschlossen. 
Dazu kann ein [i2c-Hub](https://wiki.seeedstudio.com/Grove-I2C-Hub-6Port/) benutzt werden.
i2c Module mit zwei Buchsen (z.B. Qwiic) können hintereinander gesteckt werden.

Für die Stromversorgung sollte Calliope über USB Kabel (an Computer oder Powerbank) angeschlossen sein.

#### Dieses Projekt von GitHub importieren, bearbeiten, mit Calliope testen.

Um dieses Repository in MakeCode zu importieren.

* öffne [https://makecode.calliope.cc](https://makecode.calliope.cc/)
* klicke auf **Importieren** und dann auf **Importiere URL**
* kopiere die folgende **URL des Projekts** in die Zwischenablage (Strg-C)
* **calliope-net/i2c-test**
* füge sie auf der MakeCode Webseite ein (Strg-V) und klicke auf **Los geht's!**


### Erweiterungen

Die Erweiterungen **bit** und **i2c** (die mit 3 Buchstaben) enthalten nur zusätzliche Blöcke zur Formatierung von Text und Zahlen, 
Logik und zur Programmierung beliebiger i2c Module ohne JavaScript.
Diese Erweiterungen werden von den folgenden Erweiterungen für i2c Hardware-Module **nicht** benötigt. Ausnahmen sind in der Liste angegeben.
Jede Erweiterung kann von GitHub über **calliope-net/name** allein geladen werden.

* [https://github.com/calliope-net/bit](https://calliope-net.github.io/bit/)
* [https://github.com/calliope-net/i2c](https://calliope-net.github.io/i2c/)

#### Erweiterungen für i2c Hardware-Module

* [https://github.com/calliope-net/rtc-pcf85063tp](https://calliope-net.github.io/rtc-pcf85063tp/)
* [https://github.com/calliope-net/oled-16x8](https://calliope-net.github.io/oled-16x8/)
* [https://github.com/calliope-net/oled-eeprom](https://calliope-net.github.io/oled-eeprom/) + [calliope-net/bit](https://calliope-net.github.io/bit/)
* [https://github.com/calliope-net/lcd-16x2rgb](https://calliope-net.github.io/lcd-16x2rgb/)
* [https://github.com/calliope-net/lcd-20x4](https://calliope-net.github.io/lcd-20x4/)
* [https://github.com/calliope-net/eeprom](https://calliope-net.github.io/eeprom/)
* [https://github.com/calliope-net/log-qwiicopenlog](https://calliope-net.github.io/log-qwiicopenlog/)
* [https://github.com/calliope-net/key-qwiickeypad](https://calliope-net.github.io/key-qwiickeypad/)
* [https://github.com/calliope-net/8io-qwiicgpio](https://calliope-net.github.io/8io-qwiicgpio/)
* [https://github.com/calliope-net/joystick](https://calliope-net.github.io/joystick/)
* [https://github.com/calliope-net/motor](https://calliope-net.github.io/motor/)
* [https://github.com/calliope-net/dip-switch](https://calliope-net.github.io/dip-switch/)
* [https://github.com/calliope-net/spdt-relay](https://calliope-net.github.io/spdt-relay/)
* [https://github.com/calliope-net/wattmeter](https://calliope-net.github.io/wattmeter/)

![](blocks.png)

### Updates

In der **JavaScript** Ansicht links unter dem Simulator im schwarzen Explorer sind alle von dem Projekt geladenen Erweiterungen zu finden.
Um ein Update einer Erweiterung von GitHub zu laden, muss das Symbol mit dem runden Pfeil angeklickt werden.
Dabei kann es passieren, dass die Erweiterung nicht mehr mit dem eigenen Programm kompatibel ist und das Programm angepasst werden muss.
Deshalb werden Updates auch nicht automatisch geladen.

![](explorer.png)

#### Erweiterungen aus vorhandenen Projekten löschen

Für eigene Entwicklungen auf Grundlage der Beispiel-Apps, oder wenn i2c Module fehlen, können nicht benötigte Erweiterungen gelöscht werden.
Dazu in der **JavaScript** Ansicht links unter dem Simulator im schwarzen Explorer auf den Mülleimer klicken.

### Programmierbeispiele

#### Calliope-Apps, .hex-Dateien, Bildschirmfotos mit Blöcken

* [Calliope-i2c-Test-App lädt alle Erweiterungen für i2c-Module von Grove und Qwiic.](https://calliope-net.github.io/i2c-test/)
* [Calliope-App mit vier i2c Modulen gleichzeitig, DIP-Schalter, Speicherkarte, LCD-Display, Uhr.](https://calliope-net.github.io/i2c-uhr-speicherkarte-dipschalter-lcd/)
* [Calliope-App Quarz-Uhr anzeigen, stellen mit Knopf A/B, Korrektur-Register, Binär-Uhr.](https://calliope-net.github.io/i2c-uhr-stellen/)
* [Calliope-App Dateien der Speicherkarte anzeigen, lesen, schreiben, löschen, mit Knopf A/B.](https://calliope-net.github.io/i2c-speicherkarte-verwalten/)
* [Calliope-App mit Keypad und IO-Modul eine 7-Segment-Anzeige steuern, Hardware-Interrupt.](https://calliope-net.github.io/i2c-keypad-gpio-7segment/)

> GitHub-Profil calliope-net: [https://github.com/calliope-net](https://github.com/calliope-net)

### Bezugsquellen

##### seeed studio - [Grove](https://wiki.seeedstudio.com/Grove_System/), DFRobot - [Gravity](https://www.dfrobot.com/gravity.html)

* [Grove - High Precision RTC](https://www.mouser.de/ProductDetail/713-102020083)
* [Grove - OLED Yellow&Blue Display 0.96 (SSD1315) - SPI/IIC -3.3V/5V](https://www.mouser.de/ProductDetail/713-104020249)
* [Grove - 16 x 2 LCD (White on Blue)](https://www.mouser.de/ProductDetail/713-104020111)
  * [Grove - 16 x 2 LCD (Black on Red)](https://www.mouser.de/ProductDetail/713-104020112)
  * [Grove - 16 x 2 LCD (Black on Yellow)](https://www.mouser.de/ProductDetail/713-104020113)
  * [Grove - LCD RGB Backlight](https://www.mouser.de/ProductDetail/713-104030001)
* [Grove - 6-Position DIP Switch](https://www.mouser.de/ProductDetail/713-111020043) zum Produkt-Bild vergrößern klicken
  * [Grove - 5-Way Switch](https://www.mouser.de/ProductDetail/713-111020048)
* [Grove - 4-Channel SPDT Relay](https://www.mouser.de/ProductDetail/713-103020133)
* [Gravity: I2C Digital Wattmeter](https://www.digikey.de/de/products/detail/dfrobot/SEN0291/10279750)

##### SparkFun - [Qwiic](https://www.sparkfun.com/categories/399) - Making I2C as easy as possible.

* [SparkFun 20x4 SerLCD - RGB Backlight (Qwiic)](https://www.mouser.de/ProductDetail/474-LCD-16398)
  * [SparkFun 20x4 SerLCD - RGB Backlight (Qwiic)](https://www.digikey.de/de/products/detail/sparkfun-electronics/LCD-16398/13171324)
* [SparkFun Qwiic EEPROM Breakout - 512Kbit](https://www.digikey.de/de/products/detail/sparkfun-electronics/COM-18355/14825470)
* [SparkFun Qwiic OpenLog](https://www.mouser.de/ProductDetail/474-DEV-15164)
  * [SparkFun Qwiic OpenLog](https://www.digikey.de/de/products/detail/sparkfun-electronics/DEV-15164/9920435)
* [SparkFun Qwiic Keypad - 12 Button](https://www.mouser.de/ProductDetail/474-COM-15290)
  * [SparkFun Qwiic Keypad - 12 Button](https://www.digikey.de/de/products/detail/sparkfun-electronics/COM-15290/10130913)
* [SparkFun Qwiic GPIO](https://www.mouser.de/ProductDetail/474-DEV-17047)
  * [SparkFun Qwiic GPIO](https://www.digikey.de/de/products/detail/sparkfun-electronics/DEV-17047/13419022)
* [SparkFun Qwiic Joystick](https://www.digikey.de/de/products/detail/sparkfun-electronics/COM-15168/9953917)
* [SparkFun Qwiic Motor Driver](https://www.digikey.de/de/products/detail/sparkfun-electronics/ROB-15451/10483247)

##### Grove Kabel und i2c Hub

* [Grove - Universal 4 Pin Buckled 5cm Cable (5 PCs Pack)](https://www.mouser.de/ProductDetail/713-110990036)
* [Grove-Kabel 10 cm (5 Stk./Set)](https://www.conrad.de/de/p/m5-stack-a034-a-kabel-5-st-passend-fuer-entwicklungskits-arduino-2373098.html)
* [Grove - Universal 4 Pin Buckled 40cm Cable (5 PCs Pack)](https://www.mouser.de/ProductDetail/713-110990064)
* [Grove - Universal 4 Pin Buckled 50cm Cable (5 PCs Pack)](https://www.mouser.de/ProductDetail/713-110990038)
* [Grove-Kabel 100 cm](https://www.conrad.de/de/p/m5-stack-a034-d-kabel-1-st-2306328.html)
* [Grove-Kabel 200 cm](https://www.conrad.de/de/p/m5-stack-a034-e-kabel-1-st-passend-fuer-entwicklungskits-arduino-2306329.html)
* [Grove - I2C Hub (4 Port)](https://www.mouser.de/ProductDetail/713-103020006)
  * [Grove - I2C Hub (4 Port)](https://www.digikey.de/de/products/detail/seeed-technology-co-ltd/103020006/5487896)
* [Grove - I2C Hub (6 Port)](https://www.mouser.de/ProductDetail/713-103020272)

##### Qwiic i2c Kabel und Adapter - [Qwiic Connect System](https://www.sparkfun.com/categories/tags/qwiic-cables)

* [Qwiic Cable - Grove Adapter (100mm)](https://www.mouser.de/ProductDetail/474-PRT-15109)
* [Qwiic Cable Kit](https://www.mouser.de/ProductDetail/474-KIT-15081)
* [Qwiic Adapter](https://www.mouser.de/ProductDetail/474-DEV-14495)
* [Qwiic MultiPort](https://www.mouser.de/ProductDetail/474-BOB-18012)
  * [Qwiic MultiPort](https://www.digikey.de/de/products/detail/sparkfun-electronics/BOB-18012/13998109)

#### Metadaten (verwendet für Suche, Rendering)

* Calliope mini
* i2c
