# **Arduino DMX-512 Tester and Controller**

## **Hardware - LCD 20x4 - v0.1**

***

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

- CORREGIDO - no se necesita el led on, la pantalla ya tiene un led (el led ON se retira, los leds de la salida del dmx indican que está activo)
- CORREGIDO - no hay botón de reset (no se requiere el botón de reset, hay un switch de on off)
- CORREGIDO - quitar botón SW de encendido (se cambió por un switch deslizable)
- CORREGIDO - base de teclado, darle más soporte (no requiere más soporte)
- CORREGIDO - eliminar la fuente de alimentacion regulada (se eliminó la fuente regulada)
- CORREGIDO - quitar de los conectores USB y power del arduino, las conexiones de arriba, no permiten que cierre bien el arduino (se reubicaron los componentes)
- CORREGIDO - pasar los conectores a la parte de abajo, pesa mucho la placa (los conectores se pasaron a la parte de abajo)
- CORREGIDO - agregar capacitores cerámicos a los botones para el rebote (agregados, cerámicos 104, mejoro la estabilidad en la lectura)
- CORREGIDO - se cambió el conector XLR de 3 pin por conector amphenol de 3 y 5 pin, son más resistentes
- CORREGIDO - los leds de la salida del DMX se cambiaron a la parte de abajo y viendo hacia abajo, molestaba a la vista
- CORREGIDO - el pcb se redujo
- AGREGADO  - etapa de potencia para controlar el back light del LCD
- AGREGADO  - conexión para baterías
- AGREGADO  - header para completar la conexión del arduino, estaba incompleta

***

### **Firmware**

- Firmware v0.0 to v0.8

***

### **Esquematico**

![Esquematico](https://raw.githubusercontent.com/Arduino-DMX-512-Tester-and-Controller/Arduino-DMX-512-Tester-and-Controller-LCD-20x4-Hardware/master/media/Esquematico.png)

***

### **PCB**

![PCB](https://raw.githubusercontent.com/Arduino-DMX-512-Tester-and-Controller/Arduino-DMX-512-Tester-and-Controller-LCD-20x4-Hardware/master/media/PCB.png)

***

### **Simulador**

![Simulador](https://raw.githubusercontent.com/Arduino-DMX-512-Tester-and-Controller/Arduino-DMX-512-Tester-and-Controller-20x4-Hardware/master/Media/Hard%20v00%20-%20Simulador.PNG)
![Simulador](https://raw.githubusercontent.com/Arduino-DMX-512-Tester-and-Controller/Arduino-DMX-512-Tester-and-Controller-LCD-20x4-Hardware/master/Simulador/media/Simulador%20v00.PNG)

***
