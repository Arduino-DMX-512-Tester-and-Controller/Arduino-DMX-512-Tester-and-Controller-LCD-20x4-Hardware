# **Arduino DMX-512 Tester and Controller**

## **Hardware 20x4 - v0.0**

***

![frente](https://raw.githubusercontent.com/Arduino-DMX-512-Tester-and-Controller/Arduino-DMX-512-Tester-and-Controller-20x4-Hardware/master/Media/Hardware%20v00.JPG)

- LCD de 4x20
- Alimentación desde USB o directamente al Arduino
- Teclado de navegación entre las opciones
- Teclado numérico 4x4
- Salida DMX desde bornera y XLR de 3 pin
- Leds de estado de salida DMX
- La simulación en Proteus de Arduino [Microcontrolandos](http://microcontrolandos.blogspot.mx/2012/12/arduino-componentes-para-o-proteus.html)
- Simulación en Proteus v7.7 SP2
- Esquemático y PCB en Proteus v8.0 SP1
- [Arduino Mega 2560 Rev-3](http://www.arduino.cc/en/Main/ArduinoBoardMega2560)
- Aclarar que para este proyecto se utilizó un Arduino Mega hecho en China

***

![Atras](https://raw.githubusercontent.com/Arduino-DMX-512-Tester-and-Controller/Arduino-DMX-512-Tester-and-Controller-20x4-Hardware/master/Media/Hard%20v00%20-%201.JPG)
![Atras](https://raw.githubusercontent.com/Arduino-DMX-512-Tester-and-Controller/Arduino-DMX-512-Tester-and-Controller-20x4-Hardware/master/Media/Hard%20v00%20-%202.JPG)
![frente](https://raw.githubusercontent.com/Arduino-DMX-512-Tester-and-Controller/Arduino-DMX-512-Tester-and-Controller-20x4-Hardware/master/Media/Hard%20v00%20-%203.JPG)
![Teclado](https://raw.githubusercontent.com/Arduino-DMX-512-Tester-and-Controller/Arduino-DMX-512-Tester-and-Controller-20x4-Hardware/master/Media/Hard%20v00%20-%204.JPG)
![lado](https://raw.githubusercontent.com/Arduino-DMX-512-Tester-and-Controller/Arduino-DMX-512-Tester-and-Controller-20x4-Hardware/master/Media/Hard%20v00%20-%205.JPG)
![Arduino](https://raw.githubusercontent.com/Arduino-DMX-512-Tester-and-Controller/Arduino-DMX-512-Tester-and-Controller-20x4-Hardware/master/Media/Hard%20v00%20-%206.JPG)

***

### **Esquematico**

![Esquematico](https://raw.githubusercontent.com/Arduino-DMX-512-Tester-and-Controller/Arduino-DMX-512-Tester-and-Controller-20x4-Hardware/master/Media/Hard%20v00%20-%20Esquematico.PNG)

***

### **PCB**

![PCB](https://raw.githubusercontent.com/Arduino-DMX-512-Tester-and-Controller/Arduino-DMX-512-Tester-and-Controller-20x4-Hardware/master/Media/Hard%20v00%20-%20PCB.PNG)

***

### **Simulación**

![Simulador](https://raw.githubusercontent.com/Arduino-DMX-512-Tester-and-Controller/Arduino-DMX-512-Tester-and-Controller-20x4-Hardware/master/Media/Hard%20v00%20-%20Simulador.PNG)

***

### **Firmware**

- Firmware v0.0 to v0.8

***

### **Pendientes**

- CORREGIR  - no se necesita el led on, la pantalla ya tiene un led
- CORREGIR  - no hay botón de reset
- CORREGIR  - quitar botón SW de encendido
- CORREGIR  - agregar canon XLR de 5 pin
- CORREGIR  - base de teclado, darle más soporte
- CORREGIR  - eliminar la fuente de alimentacion regulada, arduino ya tiene una fuente regulada
- CORREGIR  - quitar de los conectores USB y power del arduino, las conexiones de arriba, no permiten que cierre bien el arduino
- CORREGIR  - pasar los conectores a la parte de abajo, pesa mucho la placa
- CORREGIR  - agregar capacitores cerámicos a los botones para el rebote
