# 🌞 EnergIA – Integração de Energia Solar com Assistentes Virtuais

O objetivo do projeto é integrar a geração de energia solar com automação residencial inteligente, utilizando assistentes virtuais como Alexa, Google Assistant, Siri, Bixby, entre outros, com base em sensores, microcontroladores e comunicação em tempo real.

---

## 🔗 Links Importantes
- [Video no Youtube] (https://https://youtu.be/KuRfs9It7Sw?si=kIkf26J1e0qntrxT)
- [Github] (https://https://github.com/rafadonas/energia-sprint-sers)

## 🎯 Objetivo do Sistema

- Monitorar a geração e consumo de energia (via sensores e ESP32);
- Controlar dispositivos de forma automática ou por comandos de voz;
- Exibir informações em tempo real através de uma interface web;
- Tornar o sistema acessível via assistentes virtuais e dispositivos móveis.

---

## 🧱 Estrutura do Projeto

```plaintext
energia-sprint1/
├── backend/              # Servidor Flask para lógica e integração com voz
├── firmware/             # Código do ESP32 (sensores e relés)
├── dashboard/            # Visualização web dos dados
├── diagrams/             # Arquitetura do sistema (em imagem)
├── simulations/          # Tinkercad ou Wokwi (simulações futuras)
├── docs/                 # Documento PDF da sprint
└── README.md             # Este arquivo
```

---

## 🧠 Tecnologias Pretendidas

- **Microcontrolador:** ESP32

- **Sensores:** DHT11/DHT22 (temperatura), LDR (luminosidade), ACS712 (corrente)

- **Backend:** Python + Flask

- **Comunicação:** MQTT (Mosquitto Broker)

- **Frontend:** HTML + JS ou React

- **Integração por voz:** IFTTT, Atalhos Siri, Webhooks
