# Test-Circuit-for-Arduino-Uno-
This is a test circuit for arduino uno,   6 inputs,  6 outputs , let you know if your wiring its ok before start your project  
Descripción del programa y circuito:

Este programa para Arduino está diseñado para controlar varias luces y una bomba mediante la pulsación de botones. Cada botón está asociado a una función específica:

El Botón Inicio Paro controla la luz de trabajo. Al ser presionado, enciende la luz de trabajo durante 2 segundos.
El Botón Modo controla la luz de paro. Al ser presionado, enciende la luz de paro durante 2 segundos.
El Botón Reset controla la luz M1. Al ser presionado, enciende la luz M1 durante 2 segundos.
El Botón Rotar controla la luz M2. Al ser presionado, enciende la luz M2 durante 2 segundos.
El Botón Llenado controla la bomba de llenado. Al ser presionado, activa la bomba de llenado durante 2 segundos.
El circuito asociado a este programa consiste en conectar los botones a los pines digitales del 2 al 6 y las luces y la bomba a los pines del 7 al 12. Además, el pin 13 se utiliza para indicar la activación del programa mediante un LED integrado en la placa Arduino. Todos los componentes están conectados a tierra (GND) para completar el circuito.

El programa utiliza la función digitalRead() para detectar cuándo se presiona cada botón y digitalWrite() 
para controlar el estado de las luces y la bomba. Se ha incorporado un tiempo de retardo de 2 segundos (delay(2000)) 
para mantener las luces y la bomba activas durante ese período antes de apagarse automáticamente. 
El programa también utiliza la función Serial.println() para imprimir mensajes de estado en el monitor serial, 
lo que facilita el seguimiento del comportamiento del programa durante la ejecución.
