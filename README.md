# Medidor de umidade e temperatura: aplicação

Abstract. 
In this project the goal is to demonstrate on a screen that is visible to the person who is seeing identify the humidity and temperature indices of the site.

Resumo. 
Neste projeto o objetivo é demonstrar em uma tela que seja visível para a pessoa que está vendo identificar os índices de umidade e temperatura do local.

1. Introdução
2. Materiais e Métodos
3. Resultados
4. Conclusões
5. Referências

## 1.Introdução

O objetivo do projeto é apresentar em uma tela digital as informações de umidade e temperatura do local para isso será utilizado o sensor DHT11 para a medição, uma placa Arduino Uno R3 onde será feita a programação da aplicação utilizando o protocolo firmata, um protoboard aonde será feita a construção do circuito, os jumpers para ligação dos dispositivos no protoboard e uma tela Display LCD onde ficara visível as informações de umidade e temperatura. A ideia também é disponibilizar estas informações em um site na internet utilizando a comunicação serial protocolo MQTT que é responsável por fazer a comunicação com a internet.

## 2.Materiais e Métodos
Hardwares utilizados para montagem do projeto

Arduino Uno 3
 


Sensor DHT11 Umidade e Temperatura
 
Protoboard de 830 pontos para montagem
 

Jumpers para conexão dos dispositivos no protoboard

Softwares utilizados para montar o protótipo 

Foi utilizado o Arduino IDE 1.8.13 para programação do Arduino
 
https://www.arduino.cc/en/software

Foi utilizado o Fritzing para construção do fluxograma 
 
https://fritzing.org/

Foi utilizado Node-RED para visualização das informações via Json na web

http://localhost:1880

## 3.Resultados

Fluxograma foi feito utilizando o Fritzing 
Figura 1: Protoboard
 
Figura 2: Esquemático
 

Figura 3: Feita a programação no Sketch IDE 

Bibliotecas utilizadas 
 
Variáveis globais
 
 
Loop parâmetros e intervalos utilizados na programação
 
Figura 4: Funcionamento do Arduino e do sensor mostrando as informações de umidade e temperatura no debug do node-red
 

Figura 5: Fluxo montado no node-red
 

Figura 6: Mostrando as informações de temperatura e umidade no broker (mqtt)

## 4. Conclusões

Portanto o projeto busca contribuir com as informações de umidade e tempetura de forma que mantenha as pessoas informadas no dia a dia, mas também se preocupa com resultados voltados a problemas de saúde, assim possibilitando uma expansão futura do projeto.

## 5. Referências

FERREIRA, Angelo Luis, Projeto 40 - Sensor de temperatura e umidade DHT11 com display LCD, http://www.squids.com.br/arduino/index.php/projetos-arduino/projetos-squids/basico/149-projeto-40-utilizando-um-sensor-de-temperatura-e-umidade-dht11-com-display-lcd, 2018.

THOMSEN, Adilson, Monitorando Temperatura e Umidade com o sensor DHT11, https://www.filipeflop.com/blog/monitorando-temperatura-e-umidade-com-o-sensor-dht11/, 2013


 

 


