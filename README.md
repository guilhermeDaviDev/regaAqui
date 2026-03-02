# 🌱 SmartIrriga — Sistema de Irrigação Automatizado com Arduino

![Arduino](https://img.shields.io/badge/Arduino-UNO-00979D?logo=arduino)
![Status](https://img.shields.io/badge/status-Protótipo%20Validado-success)
![Custo](https://img.shields.io/badge/custo-Baixo-green)
![License](https://img.shields.io/badge/license-MIT-lightgrey)

> Sistema inteligente de irrigação de baixo custo para pequenos agricultores, hortas e jardins, com monitoramento em tempo real e controle remoto via Bluetooth.

---

## 📌 Sobre o Projeto

O **SmartIrriga** é um sistema de irrigação automatizado desenvolvido para reduzir o desperdício de água e energia na agricultura, especialmente em pequenas hortas e plantações.

Utiliza sensores ambientais conectados a um **Arduino UNO**, que controla automaticamente uma bomba centrífuga com base na umidade do solo e condições climáticas.

---

## 🎯 Objetivos

- Monitorar a umidade do solo
- Detectar chuva
- Medir temperatura e umidade do ar
- Automatizar o acionamento da bomba
- Permitir controle remoto via aplicativo mobile
- Reduzir desperdício hídrico

---

## ⚙️ Arquitetura do Sistema

Sensores → Arduino → Relé → Bomba  
Arduino → Bluetooth → Aplicativo Mobile  

---

## 🧰 Componentes Utilizados

### Hardware

- Arduino UNO
- Sensor de Umidade do Solo
- Sensor DHT11 (temperatura e umidade do ar)
- Sensor de Chuva
- Módulo Relé
- Bomba RS-385H (até 100L/h)
- LEDs indicadores
- Módulo Bluetooth
- Protoboard, resistores e jumpers

### Software

- Linguagem C/C++ (Arduino IDE)
- MIT App Inventor
- Comunicação via Bluetooth

---

## 🔄 Lógica do Sistema

```pseudo
Ler sensores

Se (umidade do solo < limite definido) e (não estiver chovendo)
    Ligar bomba
Senão
    Desligar bomba
Fim
```

Indicadores LED:

- Verde → Solo úmido  
- Amarelo → Nível intermediário  
- Vermelho → Solo seco  

---

## 📱 Aplicativo Mobile

Funcionalidades:

- Monitoramento em tempo real
- Visualização de temperatura e umidade
- Status da chuva
- Acionamento manual da bomba
- Exibição do estado do sistema

---

## 🧪 Resultados

- Sensores apresentaram boa precisão
- Arduino suportou o processamento adequadamente
- Economia significativa de água
- Sistema funcional e replicável
- Protótipo viável para comercialização

---

## 🚀 Melhorias Futuras

- Integração com Wi-Fi
- Monitoramento em nuvem
- Dashboard web
- Comunicação GSM
- Integração com energia solar

---

## 🌎 Impacto

- Uso racional de recursos hídricos
- Incentivo à agricultura sustentável
- Aplicação educacional em robótica e automação
- Solução acessível para pequenos produtores

---

## 👨‍💻 Autores

Guilherme Davi Alves


Jonh Oliveira


Emilly Silva


Rian Araujo


Luis Gustavo Alves


Eric Ruan


---

## 📄 Licença

MIT License
