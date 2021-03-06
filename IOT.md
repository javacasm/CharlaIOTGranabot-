# Internet de las cosas: IOT

@Granabot  2018

José Antonio Vacas @javacasm


![CC](https://raw.githubusercontent.com/javacasm/ArduinoAvanzadoDE2017/master/images/Licencia_CC_peque.png)

## https://github.com/javacasm/IOT_Granabot



* * *

## [Qué es IOT](https://es.wikipedia.org/wiki/Internet_de_las_cosas)

![IOT](https://upload.wikimedia.org/wikipedia/commons/f/f2/Internet_de_las_Cosas.jpg)

(De Drawed by Wilgengebroed on Flickr - Translated by Prades97, CC BY-SA 3.0, https://commons.wikimedia.org/w/index.php?curid=32745149)

## Algunos ejemplos:

* Pulsera para medir la actividad física
  * Su batería dura unos ¡¡¡30 días!!!
  * Almacena sus datos (en local) y cuando puede se sincroniza (guardando datos en la nube).
  * Sólo proporciona información que luego vemos en otros dispositivos.
* Sistema de riego inteligente
  * Un arduino que mide la humedad y decide si activar o no una bomba de agua es una prueba de concepto
  * Sistema de riego para una instalación de gran tamaño:
    * Cientos/miles de sensores de humedad
    * Multitud de puntos de riego (válvulas/bombas)
    * Hacemos un datamining sobre los datos de humedad y se activan los puntos de riego


### Internet Of Things

#### But, Which things?

#### EveryThing!!!

![http://robotechlabs.com/wp-content/uploads/2015/08/Iot.png](http://robotechlabs.com/wp-content/uploads/2015/08/Iot.png)

¿Recuerdas el cambio de IPV4 a IPV6?

### ¿Quién trabaja con IOT?

![detalles](http://mattturck.com/wp-content/uploads/2018/02/2018_Matt_Turck_IoT_Landscape_Final_r-1024x744.png)


[[Informe]](http://mattturck.com/iot2018/) [[Detalles]](http://mattturck.com/wp-content/uploads/2018/02/2018_Matt_Turck_IoT_Landscape_Final.png)

#### Por ejemplo Xiaomi

![domotica](https://ae01.alicdn.com/kf/HTB1tiMxSpXXXXaIXpXXq6xXFXXX4/Original-Xiaomi-Mi-Smart-Home-Series-Internet-of-Things-IoT-WiFi-Zigbee-Bluetooth-Socket-Strip-Sensor.jpg_640x640.jpg)

![domotica 2](https://sc02.alicdn.com/kf/HTB1lph1awsSMeJjSspc760jFXXaD/231105512/HTB1lph1awsSMeJjSspc760jFXXaD.png)

![cocina](https://i.blogs.es/76bc0e/xiaomi-cocina/1366_2000.jpg)

### ¿Algún dispositivo Maker?


#### Sonoff (Itead Studio)


![Sonoff](https://programarfacil.com/wp-content/uploads/2018/03/sonoff-wifi-rf.jpg)

[Tutorial sobre Sonoff de @programarfacil](https://programarfacil.com/esp8266/domotica-sonoff-wifi-espurna/)

### Qué le pedimos al IOT

* Inteligencia:
    * [Niveles](http://www.domodesk.com/a-fondo-que-es-el-internet-de-las-cosas): identidad, ubicación, estado, contexto, criterio. Ejemplo: los cientos de sensores de humedad de una gran explotación. Un nivel más de Inteligencia sería incluir predicción (por ejemplo la atmosférica: si sabemos a que va llover, esperamos antes de regar)
* Arquitectura
  * [Protocolos](http://www.domodesk.com/a-fondo-que-es-el-internet-de-las-cosas): Cable, Wifi, Zigbee, bluetooth, GSM (y todas sus Gs), ...
  * M2M: Comunicación Machine To Machine
    * Un drone recoge datos del nivel de suciedad de los paneles solares.
    * Envía los datos  a la central
    * Cuando el nivel es el adecuado se activa el robot de limpieza en determinada zona


## [LoraWAN](https://es.wikipedia.org/wiki/LoRaWAN)

![Lora](https://upload.wikimedia.org/wikipedia/commons/thumb/d/d1/Multitech-Conduit-y-mDot.jpg/330px-Multitech-Conduit-y-mDot.jpg)


[Tutorial @bricolabs](https://bricolabs.cc/wiki/guias/lora_ttn)



## ¿Cómo hacerse un IOT?

## [Arquitectura de un sistema completo IOT](https://polaridad.es/grafica-sensor-internet-de-las-cosas-iot/#estructura-html-grafica-svg)

![iot](https://polaridad.es/wp-content/uploads/2016/04/Esquema-presentaci%C3%B3n-datos-internet-de-las-cosas-IoT-con-JavaScript-en-una-p%C3%A1gina-web-HTML-con-JavaScript.png)
(Imagen cortesia de Victor Ventura - https://polaridad.es/grafica-sensor-internet-de-las-cosas-iot/#estructura-html-grafica-svg)


## Ejemplos sencillos

[Sensores de temperatura online](http://geek.adachsoft.com/home/article/id/1/n/ESP8266-and-multiple-temperature-sensors-DS18b20-with-HTTP-server)

![sensores online](http://geek.adachsoft.com/img/parts.png)

https://github.com/wemos/D1_mini_Examples/tree/master/examples/01.Basics
https://www.wemos.cc/product/relay-shield.html


## Modelos

### Familia del ESP [Variedades](https://frightanic.com/iot/comparison-of-esp8266-nodemcu-development-boards/)

* ESP8266

  ![esp8266](https://camo.githubusercontent.com/81389b8a0f9eaabf7fe5555f2cf3c0f970498841/687474703a2f2f727562656e736d2e636f6d2f77702d636f6e74656e742f75706c6f6164732f323031352f30312f657370383236362d333030783232352e6a7067)
* NodeMCU

  ![nodeMCU](https://github.com/javacasm/NodeMCU-tutorial/raw/master/images/MiNodeMCU_pcb.jpg)

* [ESP32](https://en.wikipedia.org/wiki/ESP32)


![Comparativa](https://cdn.shopify.com/s/files/1/0672/9409/files/coparison_between_esp32_esp32_esp8266_large.jpg?v=1501546029)

[Comparativa ESP8266 vs ESP32](http://blog.bricogeek.com/noticias/electronica/comparativa-y-analisis-completo-de-los-modulos-wifi-esp8266-y-esp32/)

Mi elección a día de hoy: [Wemos](https://github.com/javacasm/WeMos_ESP8266)

![wemos](https://github.com/javacasm/WeMos_ESP8266/raw/master/images/pcb.jpg)


### ¿Puedo usar arduino?

[SI](https://programarfacil.com/esp8266/como-programar-nodemcu-ide-arduino/)

[¿Cómo se hace?](https://github.com/javacasm/ESP-Tutorial)

[Ejemplos](https://github.com/javacasm/ESP-Tutorial/blob/master/Referencias.md)

[Usando ESP8266](https://github.com/javacasm/ESP8266_Tutorial)

[Usando NodeMCU](https://github.com/javacasm/NodeMCU-tutorial)

### Precios

### Capacidad

* Procesador
* Memoria
* Filesystem

### Configurar tu ESP8266

![conf](https://pbs.twimg.com/media/C3fobewWEAAzsV3.jpg:large)

[Estacion meteo](https://www.instructables.com/id/ESP8266-Weather-Widget/)


[IOT Cloud video](https://www.youtube.com/watch?v=Ymi7DNY4vNg&t=2s)

[Serie de vídeos sobre tu propio IOT](https://www.youtube.com/watch?v=g1j-Pta2QAs)

## IOT Con cable

[Controla tu casa desde internet con arduino](https://randomnerdtutorials.com/arduino-ethernet-web-server-with-relay/) Coste: 10+5+2€


### [Proyectos con ESP8266](https://programarfacil.com/esp8266/proyectos-con-esp8266-iot/?utm_content=buffer619c6&utm_medium=social&utm_source=twitter.com&utm_campaign=buffer)

## Proyectos todo en uno: plataformas

[Blink](http://www.blynk.cc/?_mrMailingList=724&_mrSubscriber=743&utm_source=mailing724&utm_medium=email&utm_campaign=arduino-day-2017)

http://community.blynk.cc/t/esp8266-12-blynk-pin-out-problems/1143


[tutorial Blink](https://www.instructables.com/id/NodeMCU-Mini-Tutorial-NodeMCU-and-Blynk/)


[ESP8266 to MQTT to Raspberry](http://randomnerdtutorials.com/esp8266-publishing-dht22-readings-with-mqtt-to-raspberry-pi/)

## Entorno de programación

[PlatformIO](http://docs.platformio.org/en/stable/platforms/espressif32.html)

[Instalación en arduino](http://www.esploradores.com/configuracion-del-ide-de-arduino-para-el-esp32-2/)

### Seguridad
[Bloquear una red wifi con ESP8266](http://www.neoteo.com/como-bloquear-el-acceso-a-una-red-wifi-con-un-modulo-esp8266/)

[ESP firewall](https://github.com/joemcmanus/ESP8266-Firewall)
