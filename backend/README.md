# 🧠 Backend – Flask + MQTT

Esta pasta contém o servidor backend do projeto, desenvolvido com **Python + Flask**. Ele é responsável por:

- Receber comandos de voz via Webhook (IFTTT, Siri Shortcuts, etc);
- Processar os dados e lógica de automação;
- Publicar comandos no broker MQTT para o ESP32;
- Receber dados dos sensores e armazenar/redistribuir.

## 🔧 Arquivos
- `app.py`: script principal do servidor Flask.
- `requirements.txt`: dependências necessárias (Flask, paho-mqtt, etc).

## 🚀 Objetivo
Conectar os assistentes de voz ao sistema físico, permitindo controle remoto inteligente por comandos naturais.
