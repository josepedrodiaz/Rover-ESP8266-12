# ESP8266-12 based Rover

Implements the possibility of driving a diy rover through a REST API

## Componentes
* Esp8266-12 
* Chasis
* Motores DC 6v con reducción
* Batería LiPo 2s
* IC L293D - (doble puente H)

## URLS
/adelante
/atras
/izquierda
/derecha
/frena


@todo: view asigned IP


## To do
* Agregar una cámara IP alimentada a baterías
* Adicionar un relay que encienda y apague esa cámara
* Adicionar sistema pan & titl para la cámara
* Que el sistema se apague al alcanzar el umbral de la bateria de LiPo
