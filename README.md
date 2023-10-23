# Proyecto Arduino con Fotorresistencia y Display de 7 Segmentos

[![ARDUINO.png](https://i.postimg.cc/L6XdYGYG/ARDUINO.png)](https://postimg.cc/7bptjsNN)

Este proyecto de Arduino utiliza una fotorresistencia para detectar la cantidad de luz en el ambiente y muestra el valor en un display de 7 segmentos. También incluye un motor que se activa en función de la temperatura.

## Autor

  Franco Carrazana 1°E 

## Componentes

- Arduino
- Fotorresistencia (LDR)
- Resistencia de 10 KΩ
- Display de 7 segmentos
- Motor DC
- Sensor de temperatura

## Funcionamiento

El código lee el valor de la fotorresistencia y lo muestra en el monitor serial. Si este valor supera un cierto umbral, se activa una secuencia que incluye el incremento de un contador y la activación del motor si la temperatura está dentro de un rango específico.

El contador puede incrementarse de manera normal o puede buscar el siguiente número primo, dependiendo del estado del pin `NaturalOPrimo`. El valor del contador se muestra en el display de 7 segmentos.

## Simulación en Tinkercad

Este proyecto fue desarrollado y probado en Tinkercad, una plataforma online para la simulación de circuitos electrónicos. Puedes acceder al proyecto en Tinkercad para ver el diseño del circuito y probar su funcionamiento.

## Tinkercad

  - Primera parte : https://www.tinkercad.com/things/2TxeY7cjXlN
  - Segunda parte : https://www.tinkercad.com/things/coJwZleTgPu
  - Tercera parte : https://www.tinkercad.com/things/bBwi0j5DiSz

## Fuentes

  - [Arduino.cc](https://www.arduino.cc/)
  - https://www.youtube.com/@AlgoBack
  - https://www.youtube.com/@LeonardoLoor
    
