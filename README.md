# Placas Maker Alicante

Placas compatibles con "Arduino" desarrolladas por la asociación Maker Alicante.

- [1 - Placa MakerAlc Basic](#1-MakerAlc-Basic)
- [2 - Placa MakerAlc LoRa](#2-MakerAlc-LoRa)
- [3 - Instalación placas en entorno IDE Arduino](#3-IDE-Arduino)
- [4 - Instalación placas en entorno PlatformIO](#4-Platformio)

Hasta el momento se han desarrollado dos modelos de placas. 

## 1 MakerAlc Basic

Compatible 100% con Arduino Pro mini. Existen dos versiones. Una que se alimenta con 5V y tiene un reloj de 16 MHz y la otra se alimenta a 3,3V y tiene una velocidad de 8 MHz.

![MarAlc Basic](https://github.com/AsociacionMakerAlicante/PlacasMaker/blob/main/Fotos/MakAlc_Basic.jpg)


## 2 MakerAlc LoRa

Incorpora un micro ATMega 4808 (28 pins). Utiliza un reloj externo de 16 MHz, aunque en la definición de la placa se baja a 8 MHz ya que la alimentación es de 3V (2 pilas de 1,5V). 
Además integrado en la placa hay un módulo de rádio LoRa y un temporizador (TPL5010).

La placa está pensada para enviar datos con el módulo de radio y luego ponerse a dormir en modo de "sueño profundo" hasta que el temporizador la despierte para hacer el siguiente envío.
El temporizador hace las veces de "Watchdog" ya que si después de enviar la señal para que la placa se despierte esta no contesta por que se ha quedado colgada envia una señal que reinicia la placa.
![MarAlc Basic](https://github.com/AsociacionMakerAlicante/PlacasMaker/blob/main/Fotos/MakAlc_LoRa.jpg)

## 3 IDE Arduino
Si utilizas el entorno de programación de Arduino, puedes instalar la definición de las placas siguiendo 
las instrucciones de un fichero PDF que puedes descargar [AQUÍ](https://github.com/AsociacionMakerAlicante/PlacasMaker/raw/main/Instalacion%20nuevas%20placas%20(MakerAlc).pdf)


## 4 PlatformIO
Si utilizas el entorno de programación Visual Studio Code con la extensión de PlatformIO, puedes instalar la definición de las placas siguiendo 
las instrucciones de un fichero PDF que puedes descargar [AQUÍ](https://github.com/AsociacionMakerAlicante/PlacasMaker/raw/main/Instalacion%20nuevas%20placas%20(MakerAlc).pdf)

Si tienes algún problema en la instalación de las placas, por favor informa [AQUÍ](mailto:ricardomakeralicante@gmail.com)
