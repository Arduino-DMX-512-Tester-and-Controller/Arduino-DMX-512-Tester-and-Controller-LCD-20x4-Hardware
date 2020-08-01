# **Arduino DMX-512 Tester and Controller**

## **Hardware - LCD 20x4**


[![version](https://img.shields.io/badge/version-0.7-brightgreen.svg)](CHANGELOG.md)
[![license](https://img.shields.io/badge/licence-OSHW%20v1.0-blue)](https://github.com/Arduino-DMX-512-Tester-and-Controller/Arduino-DMX-512-Tester-and-Controller-LCD-20x4-Hardware/blob/master/Licence.md)
/Licence.md 
[![codacy](https://api.codacy.com/project/badge/Grade/c9496e25cf07434cba786b462cb15f49)](https://www.codacy.com/app/xoseperez/espurna/dashboard)
<br />
[![latest master build](https://img.shields.io/github/release/xoseperez/espurna/all.svg?label=latest%20master%20build)](https://github.com/xoseperez/espurna/releases/latest)
[![latest dev build](https://img.shields.io/github/release/mcspr/espurna-nightly-builder/all.svg?label=latest%20dev%20build)](https://github.com/mcspr/espurna-nightly-builder/releases)
[![downloads](https://img.shields.io/github/downloads/xoseperez/espurna/total.svg)](https://github.com/xoseperez/espurna/releases)
<br />
[![donate](https://img.shields.io/badge/donate-PayPal-blue.svg)](https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=xose%2eperez%40gmail%2ecom&lc=US&no_note=0&currency_code=EUR&bn=PP%2dDonationsBF%3abtn_donate_LG%2egif%3aNonHostedGuest)
[![gitter](https://img.shields.io/gitter/room/tinkermant-cat/espurna.svg)](https://gitter.im/tinkerman-cat/espurna)
[![twitter](https://img.shields.io/twitter/follow/xoseperez.svg?style=social)](https://twitter.com/intent/follow?screen_name=xoseperez)

***

Herramienta Open Hardware, para pruebas y control de iluminación de espectáculos a través del protocolo [DMX-512](http://es.wikipedia.org/wiki/Digital_Multiplex), ideal para hacer pruebas rápidas en instalaciones fijas o temporales de iluminación, sin la necesidad de instalar consolas de iluminación, interfaces o computadoras en ambientes al intemperie, hostiles o de difícil acceso.

***

### **Basado en:**

- [Arduino Mega 2560 Rev-3](http://www.arduino.cc/en/Main/ArduinoBoardMega2560)
- [Librería Arduino cuatro universos DMX v0.3 - Deskontrol](http://www.deskontrol.net/blog/libreria-arduino-cuatro-universos-dmx/)
- [Libreria LCD v1.2.1 - Francisco Malpartida](https://bitbucket.org/fmalpartida/new-liquidcrystal/wiki/Home)
- [Simulación en Proteus de Arduino - Microcontrolandos](http://microcontrolandos.blogspot.mx/2012/12/arduino-componentes-para-o-proteus.html)
- [Encoder](http://www.robodosis.net/2013/01/encoder-rotativo-mecanico-con-pic16f877a_2.html)

***

- Esquemático y PCB en Proteus v8.0 SP1
- LCD de 4x20 con backlight y contraste controlado por software
- Alimentación desde USB, baterías o fuente de alimentación externa
- Encoder para navegacion entre menu
- Teclado numérico 4x4
- Interruptor de on/off
- Salida DMX desde bornera, XLR de 3 pin y XLR de 5 pin
- Leds de estado de salida DMX
- Simulación en Proteus v7.7 SP2 y v8.0 SP1
- Esquemático y PCB en Proteus v8.0 SP1
- Aclarar que para este proyecto se utilizó un Arduino Mega hecho en China
- Regulador para fuente externa, el arduino se calienta
- Bornera para salida de fuente regulada de 5V para uso general
- Led para salida de fuente regulada
- Botón de reset
- Opto acoplado a salida de dmx
- Convertidor de DC/DC para aislamiento de DMX
- SW de palanca para invertir polaridad de salida de DMX
- Jumper default eeprom en pin 9
- Driver para luz led como lampara
- SW para Key Light
- SW para Ext Light
- Espaciadores para fijación
- Leyendas de conexión
- Fuente externa, el arduino se calentaba

***

- AGREGADO   - SW para Key Light
- AGREGADO   - SW para Ext Light
- AGREGADO   - Espaciadores para fijación
- AGREGADO   - Leyendas de conexión
- AGREGADO   - Fuente externa, el arduino se calentaba
- CORREGIR   - marcar en board edge los agujeros de los XLR
- CORREGIR   - los XLR quedan chuecos
- CORREGIR   - Encoder, separar los agujeros están muy juntos
- CORREGIR   - separar bornera de key light de lcd, esta muy junta
- CORREGIR   - pads de puentes muy chicos
- CORREGIR   - pads de botón de reset muy chicos
- CORREGIR   - subir logo de Open Hardware
- CORREGIR   - texto de about, hacerlo mas grueso
- CORREGIR   - bornera de voltaje lateral metera mas
- CORREGIR   - acostar C7
- CORREGIR   - tornillos de LCD no coinciden
- CORREGIR   - jumper de reset, poner pullup, el pin no tiene interno
- CORREGIR   - posición de SW esta al revés, cambiar leyenda en pcb

***

### **Firmware**

- Simulacion en Proteus v7.7 SP2
- Librerias:
  - Arduino: https://geekelectronica.com/simular-arduino-con-proteus/
- Firmware v1.7

***

### **Simulador**

- Hardware v0.6 to v0.8
- Firmware v1.6 to v2.1

***

### **Esquematico**

![Esquematico](https://raw.githubusercontent.com/Arduino-DMX-512-Tester-and-Controller/Arduino-DMX-512-Tester-and-Controller-LCD-20x4-Hardware/master/media/Esquematico.png)

***

### **PCB**

![PCB](https://raw.githubusercontent.com/Arduino-DMX-512-Tester-and-Controller/Arduino-DMX-512-Tester-and-Controller-LCD-20x4-Hardware/master/media/PCB.png)

***

### **Simulador**

![Simulador](https://raw.githubusercontent.com/Arduino-DMX-512-Tester-and-Controller/Arduino-DMX-512-Tester-and-Controller-LCD-20x4-Hardware/master/media/Simulador.PNG)

***

## **Licenciamiento:**

![](https://raw.githubusercontent.com/Arduino-DMX-512-Tester-and-Controller/Arduino-DMX-512-Tester-and-Controller-LCD-20x4-Hardware/master/Social/Logos/oshw.png)

[Open Source Hardware (OSHW) v1.0](https://github.com/Arduino-DMX-512-Tester-and-Controller/Arduino-DMX-512-Tester-and-Controller-LCD-20x4-Hardware/blob/master/Licence.md)

***

## **Autor:**

- Daniel Becerril
- Copyright (C) 2015

[![Email](https://raw.githubusercontent.com/Arduino-DMX-512-Tester-and-Controller/Arduino-DMX-512-Tester-and-Controller-LCD-20x4-Hardware/master/Social/Logos/email%2050x50.jpg)](mailto:daniel3514@gmail.com)
[![Facebook](https://raw.githubusercontent.com/Arduino-DMX-512-Tester-and-Controller/Arduino-DMX-512-Tester-and-Controller-LCD-20x4-Hardware/master/Social/Logos/Facebook%2050x50.png)](https://www.facebook.com/daniel.3514)
[![Facebook](https://raw.githubusercontent.com/Arduino-DMX-512-Tester-and-Controller/Arduino-DMX-512-Tester-and-Controller-LCD-20x4-Hardware/master/Social/Logos/Facebook%20Pages%2050x50.jpg)](https://www.facebook.com/ArduinoDMX512TesterController)
[![Twitter](https://raw.githubusercontent.com/Arduino-DMX-512-Tester-and-Controller/Arduino-DMX-512-Tester-and-Controller-LCD-20x4-Hardware/master/Social/Logos/Twitter%2050x50.png)](https://twitter.com/daniel3514)
[![Instructables](https://raw.githubusercontent.com/Arduino-DMX-512-Tester-and-Controller/Arduino-DMX-512-Tester-and-Controller-LCD-20x4-Hardware/master/Social/Logos/Instructables%2050x50.jpg)](http://www.instructables.com/id/Arduino-DMX-512-Tester-and-Controller/)
[![Hack a Day](https://raw.githubusercontent.com/Arduino-DMX-512-Tester-and-Controller/Arduino-DMX-512-Tester-and-Controller-LCD-20x4-Hardware/master/Social/Logos/hackaday%2050x50.jpg)](https://hackaday.io/project/5342-arduino-dmx-512-tester-and-controller)
[![Youtube](https://raw.githubusercontent.com/Arduino-DMX-512-Tester-and-Controller/Arduino-DMX-512-Tester-and-Controller-LCD-20x4-Hardware/master/Social/Logos/Youtube%2050x50.png)](https://www.youtube.com/watch?v=TxBHMpAWDSY)
[![Tech Inside](https://raw.githubusercontent.com/Arduino-DMX-512-Tester-and-Controller/Arduino-DMX-512-Tester-and-Controller-LCD-20x4-Hardware/master/Social/Logos/techinside%2045x45.png)](https://techinsideblog.wordpress.com/)
[![GitHub](https://raw.githubusercontent.com/Arduino-DMX-512-Tester-and-Controller/Arduino-DMX-512-Tester-and-Controller-LCD-20x4-Hardware/master/Social/Logos/github%2050x50.png)](https://github.com/Arduino-DMX-512-Tester-and-Controller)
[![Hackster](https://raw.githubusercontent.com/Arduino-DMX-512-Tester-and-Controller/Arduino-DMX-512-Tester-and-Controller-LCD-20x4-Hardware/master/Social/Logos/hackster%2050x50.png)](https://www.hackster.io/daniel3514/arduino-dmx-512-tester-controller-977c89)

***
