# Objetos Inteligentes Conectados 1 sem. 2020

## Turma 05K11
# WemosHumidTemp
## Integrantes:

* Matheus Sena

# Sobre o Projeto
O projeto é baseado em um circuito onde são utilizados componentes como uma placa Wemos D1, um sensor de temperatura e um Display LCD, no qual ao captar temperatura, apresenta o valor medido no Display, e também envia os dados para a Internet utilizando o protocolo MQTT. 
Os sensores de temperatura e umidade são dispostivos capazes de mensurar a umidade relativa do ar e a temperatura de um ambiente, produto ou equipamento. 
Eles podem ser utilizados tanto ao ar livre como também em ambientes fechados. 
Trata-se de um instrumento muito utilizado em farmácias, laboratórios, almoxarifados e hemocentros, entre outros ambientes. 
O equipamento pode ser portátil e possui um tempo de resposta bastante baixo: em apenas alguns segundos, já é capaz de indicar a temperatura relativa do ar. 
O sensor também contribui para que instituições possam manter as suas operações dentro das normas vigentes caso for preciso.

# Componentes

Os componentes utilizados nesse projeto foram:

* Placa Wemos D1
<img src="docs/Placa WemosD1.JPG" width="300" />

* Sensor de Temperartura e Umidade de Alta Precisão HDC1080
<img src="docs/Sensor HD.jpg.jpg" width="300" />

* Display LCD 
<img src="docs/Display LCD.jpg" width="300" />

# Aplicações utilizadas

Utilizamos para desenvolver o projeto e estabelecer o protocolo MQTT no projeto

* Arduino IDE
Pode ser baixada em https://www.arduino.cc/en/main/software
* API Thingspeak
Link do Canal do projeto : https://thingspeak.com/channels/1087000

# Circuito e Montagem
<img src="docs/Circuito.jpg" width="300" />

Conforme circuito abaixo, podemos verificar que ligamos no mesmo barramento da protoboard os pinos SDA,SCL, 5VV e GND tanto do display como no sensor





