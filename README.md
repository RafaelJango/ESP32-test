# Projeto FIAP - Integração ESP32 com AWS via Fiware

Este repositório contém o projeto desenvolvido como parte do curso de Engenharia de Software da FIAP, cujo objetivo foi integrar uma placa ESP32 com a AWS utilizando o Fiware. O foco do trabalho foi criar uma solução capaz de ligar e desligar o LED onboard da ESP32 e enviar os dados para um Broker MQTT, possibilitando a interação com o Fiware para monitoramento do status do LED e medição de luminosidade.

## Objetivo do Projeto

Desenvolver uma aplicação para o microcontrolador ESP32 que permita:
- Controlar o LED onboard.
- Monitorar e reportar o estado do LED (ligado/desligado) via MQTT.
- Medir a luminosidade ambiente e enviar os dados para o Fiware, utilizando um broker MQTT.

## Tecnologias Utilizadas

- **ESP32**: Placa de microcontrolador utilizada para execução do código.
- **AWS**: Plataforma de cloud computing para armazenamento e gerenciamento dos dados.
- **Fiware**: Framework open-source para o desenvolvimento de smart applications, utilizado para gerenciar e processar os dados enviados pelo ESP32.
- **MQTT**: Protocolo de comunicação leve para IoT, utilizado para o envio dos dados.
- **Arduino IDE**: Ambiente de desenvolvimento utilizado para a programação da ESP32.

## Links Importantes

- [Simulação no Wokwi](https://wokwi.com/projects/408321398948308993): Acesse a simulação online do projeto utilizando o Wokwi, onde você pode testar e visualizar o comportamento do código diretamente no navegador.
- [Vídeo de Demonstração no YouTube](https://youtu.be/RV38Q46LHFk): Assista ao vídeo de demonstração do projeto, mostrando a integração entre o ESP32, AWS, e Fiware, além do funcionamento do LED e do sensor de luminosidade.
