# **Arduino DMX-512 Tester and Controller**

## **Hardware - LCD 20x4 - v0.3**

***

Herramienta Open Hardware, para pruebas y control de iluminación de espectáculos a través del protocolo [DMX-512](http://es.wikipedia.org/wiki/Digital_Multiplex), ideal para hacer pruebas rápidas en instalaciones fijas o temporales de iluminación, sin la necesidad de instalar consolas de iluminación, interfaces o computadoras en ambientes al intemperie, hostiles o de difícil acceso.

![](https://raw.githubusercontent.com/Arduino-DMX-512-Tester-and-Controller/Arduino-DMX-512-Tester-and-Controller-LCD-20x4-Hardware/master/media/IMG_9399.JPG)
[![video](https://raw.githubusercontent.com/Arduino-DMX-512-Tester-and-Controller/Arduino-DMX-512-Tester-and-Controller-LCD-20x4-Hardware/master/media/youtube.JPG)](https://www.youtube.com/watch?v=TxBHMpAWDSY)

***

### **Basado en:**

- [Arduino Mega 2560 Rev-3](http://www.arduino.cc/en/Main/ArduinoBoardMega2560)
- [Librería Arduino cuatro universos DMX v0.3 - Deskontrol](http://www.deskontrol.net/blog/libreria-arduino-cuatro-universos-dmx/)
- [Libreria LCD v1.2.1 - Francisco Malpartida](https://bitbucket.org/fmalpartida/new-liquidcrystal/wiki/Home)
- [Simulación en Proteus de Arduino [Microcontrolandos](http://microcontrolandos.blogspot.mx/2012/12/arduino-componentes-para-o-proteus.html)

***

- Esquemático y PCB en Proteus v8.0 SP1
- LCD de 4x20 con backlight y contraste controlado por software
- Alimentación desde USB, baterías o fuente de alimentación externa
- Teclado de navegación entre las opciones
- Teclado numérico 4x4
- Potenciómetro para control análogo
- Interruptor de on/off
- Salida DMX desde bornera, XLR de 3 pin y XLR de 5 pin
- Leds de estado de salida DMX
- Simulación en Proteus v7.7 SP2
- Esquemático y PCB en Proteus v8.0 SP1
- Aclarar que para este proyecto se utilizó un Arduino Mega hecho en China

***

- AGREGADO  - control de contraste desde software
- AGREGADO  - control de back light desde software

***

### **Firmware**

- Simulacion en Proteus v7.7 SP2
- Librerias:
  - Arduino: https://geekelectronica.com/simular-arduino-con-proteus/
- Firmware v0.9 a v1.3

***

### **Simulador**

- Hardware v0.3 to v0.4
- Firmware v0.9 to v1.5

***

### **Lista de Componentes**

* 1 pza [Arduino Mega](https://www.arduino.cc/en/Main/ArduinoBoardMega2560)
* 1 pza [Rotary Potentiometer 10k Ohm Linear](https://www.sparkfun.com/products/9939)
* 5 pza [Switch Push Button Tactile Single Pole Single Throw Off Momentary](http://www.jameco.com/webapp/wcs/stores/servlet/Product_10001_10001_122973_-1)
* 1 pza [20x4 Character LCD - Black on Green 5V](https://www.sparkfun.com/products/256)
* 2 pza [Transistor 2N2222A TO-18 NPN 75 Volt 0.6 Amp](http://www.jameco.com/webapp/wcs/stores/servlet/Product_10001_10001_38236_-1)
* 1 pza [Key Matrix 4x4](http://www.minirobot.com.mx/tienda/index.php?id_product=468&controller=product)
* 1 pza [MAX485 Low-Power, Slew-Rate-Limited RS-485/RS-422 Transceivers](https://www.maximintegrated.com/en/products/interface/transceivers/MAX485.html)
* 2 pza [Resistor 330 ohms 1/4 Watt](http://www.jameco.com/webapp/wcs/stores/servlet/Product_10001_10001_690742_-1)
* 2 pza [Resistor 1 k ohms 1/4 Watt](http://www.jameco.com/webapp/wcs/stores/servlet/Product_10001_10001_690865_-1)
* 1 pza [Resistor 120 ohms 1/4 Watt](http://www.jameco.com/webapp/wcs/stores/servlet/Product_10001_10001_690646_-1)
* 2 pza [Led 3mm Blue](http://www.jameco.com/webapp/wcs/stores/servlet/Product_10001_10001_2168421_-1)
* 6 pza [Ceramic Capacitor Monolitic 1 nF 50 V](http://5hertz.com/index.php?main_page=product_info&products_id=700)
* 1 pza [Large terminal with 3 screws](http://www.steren.com.mx/terminal-grande-con-3-tornillos-para-circuito-impreso.html)
* 1 pza [Large terminal with 2 screws](http://www.steren.com.mx/terminal-grande-con-2-tornillos-para-circuito-impreso.html)
* 1 pza [Switch Slide 1 pole, 2 shots, 2 positions](http://www.steren.com.mx/switch-deslizable-de-1-polo-2-tiros-2-posiciones.html)
* 1 pza [XLR Connector 3 Pin PCB Mount Amphenol AC3FAH2-AU-PRE](http://www.amphenolaudio.com/products/xlr/chassis-mounts/ac-series/)
* 1 pza [XLR Connector 5 Pin PCB Mount Amphenol AC5FAH-AU-B](http://www.amphenolaudio.com/products/xlr/chassis-mounts/ac-series/)
* 4 pza [Connector Unshrouded Header 40 Position 2.54mm Straight Thru-Hole](http://www.jameco.com/webapp/wcs/stores/servlet/Product_10001_10001_160882_-1)
* 1 pza [Base for integrated circuit 8-pin](http://www.steren.com.mx/base-para-circuito-integrado-de-8-patas.html)
* 2 pza [Phenolic a face plate of 15 x 20 cm](http://www.steren.com.mx/placa-fenolica-una-cara-de-15-x-20-cm.html)
* 1 pza [Photosensitive Dry Film Pcb 30cm*200cm/ 2m](http://www.amazon.com/Photosensitive-Film-Amateur-30cm-200cm/dp/B00B225R0I/?tag=leosm1-20)

***

### **Esquematico**

![Esquematico](https://raw.githubusercontent.com/Arduino-DMX-512-Tester-and-Controller/Arduino-DMX-512-Tester-and-Controller-LCD-20x4-Hardware/master/media/Esquematico.png)

***

### **PCB**

![PCB](https://raw.githubusercontent.com/Arduino-DMX-512-Tester-and-Controller/Arduino-DMX-512-Tester-and-Controller-LCD-20x4-Hardware/master/media/PCB.png)

***

### **Simulador**

![Simulador](https://raw.githubusercontent.com/Arduino-DMX-512-Tester-and-Controller/Arduino-DMX-512-Tester-and-Controller-LCD-20x4-Hardware/master/media/Simulador.PNG)
![Simulador](https://raw.githubusercontent.com/Arduino-DMX-512-Tester-and-Controller/Arduino-DMX-512-Tester-and-Controller-LCD-20x4-Hardware/master/media/Simulador%20exe.PNG)

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
