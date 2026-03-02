# regaAqui
RegaAqui é um sistema de irrigação automática sustentável que monitora a umidade do solo e ativa a irrigação apenas quando necessário, reduzindo desperdício de água e otimizando o consumo. O projeto utiliza sensores, microcontrolador e lógica automatizada para garantir eficiência hídrica e autonomia no processo de rega.
🌱 Sistema de Irrigação Automatizado com Arduino
📌 Sobre o Projeto

Sistema de irrigação automatizado de baixo custo, desenvolvido para pequenos agricultores, hortas e jardins.
O objetivo é reduzir desperdício de água e energia usando sensores ambientais + Arduino + aplicativo móvel para controle remoto via Bluetooth.

O sistema monitora:

Umidade do solo

Umidade do ar

Temperatura

Presença de chuva

Com base nesses dados, a irrigação é acionada automaticamente ou manualmente pelo usuário.

🧠 Problema

No Brasil (principalmente no Nordeste), a agricultura consome e desperdiça grandes volumes de água por falta de controle eficiente na irrigação.

Sistemas tradicionais:

Funcionam por tempo fixo

Não consideram tipo de solo

Ignoram temperatura e chuva

Desperdiçam água e energia

Esse projeto propõe uma solução acessível, eficiente e automatizada.

🎯 Objetivo Geral

Desenvolver um sistema automatizado utilizando Arduino + sensores + aplicativo móvel, capaz de:

Monitorar variáveis ambientais

Controlar irrigação automaticamente

Permitir acionamento remoto

Promover uso racional de água e energia

⚙️ Componentes Utilizados
Hardware

Arduino UNO

Sensor de Umidade do Solo

Sensor DHT11 (temperatura e umidade do ar)

Sensor de Chuva

Módulo Relé

Bomba centrífuga RS-385H (até 100L/h)

Protoboard

Resistores

Jumpers

LEDs indicadores (verde, amarelo, vermelho)

Módulo Bluetooth

Software

Linguagem nativa do Arduino (C/C++)

Aplicativo desenvolvido no MIT App Inventor

🔌 Funcionamento

Sensores coletam dados ambientais.

Arduino processa as informações.

Se o solo estiver seco (e não estiver chovendo), a bomba é acionada.

LEDs indicam o nível de umidade:

🟢 Verde → Solo úmido

🟡 Amarelo → Atenção

🔴 Vermelho → Solo seco

O usuário pode monitorar tudo pelo app e acionar remotamente via Bluetooth.

📱 Aplicativo Mobile

O app permite:

Visualizar temperatura do ar

Ver umidade do solo

Monitorar chuva

Ativar/desativar irrigação

Acompanhar status da bomba

Comunicação feita via Bluetooth entre Arduino e smartphone.

🧪 Metodologia

Pesquisa bibliográfica sobre irrigação e automação

Estudo sobre Arduino e sensores

Montagem do circuito eletrônico

Programação do sistema

Desenvolvimento do app

Construção do protótipo

Testes práticos

Apresentação de resultados

📊 Resultados

Sensores apresentaram boa precisão

Arduino suportou bem o processamento

Economia significativa de água

Sistema funcional e viável para comercialização

Interface intuitiva e simples

🌎 Impacto

Redução de desperdício hídrico

Economia de energia

Solução acessível para pequenos produtores

Incentivo à agricultura sustentável

Aplicação prática de robótica educacional

🚀 Melhorias Futuras

Integração com Wi-Fi ou GSM (monitoramento remoto sem limite de distância)

Ajustes baseados em tipos específicos de solo

Expansão para análise de consumo energético detalhado

Integração com IoT

📚 Referências

ALLEN et al. (1998) – Crop evapotranspiration

MARQUELLI et al. (1994) – Irrigação agrícola

MCROBERTS (2013) – Beginning Arduino

MACEDO et al. (2010) – Irrigação automatizada

RODRIGUES & IRIAS (2004) – Impactos ambientais da irrigação

👨‍💻 Autores

Guilherme Davi Alves
Jonh Oliveira
Emilly Silva
Rian Araujo
Luis Gustavo Alves
Eric Ruan
