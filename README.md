# Thread Mesh AI-Optimizer 🛰️

> **Otimização de Redes IoT com Inteligência Artificial Evolutiva**
> Projeto desenvolvido na Universidade Federal do Espírito Santo (UFES)

---

## 📋 Sobre o Projeto

Este repositório hospeda a pesquisa sobre a aplicação de **Algoritmos Genéticos** para otimizar o consumo de energia em redes **Thread Mesh**. O foco principal é equilibrar a confiabilidade da rede com a eficiência energética de dispositivos alimentados por bateria.

### Principais Destaques
- **Protocolo:** Baseado em IEEE 802.15.4 (2.4 GHz) com IPv6 nativo. [cite: 199, 203]
- **Inovação:** Otimização da potência de transmissão para evitar o "grito" desnecessário dos nós na potência máxima (8 dBm). [cite: 217, 223, 225]
- **Resultado:** Ganho médio de potência de **26.45 dB** validado em hardware real (nRF52840 DK). [cite: 332, 344]

---

## 🛠️ Tecnologias e Métodos

- **Linguagens:** Python (Algoritmo Genético)
- **Hardware:** nRF52840 DK, Power Profiler Kit [cite: 332, 343]
- **Ambiente:** ESP-IDF / Home Assistant
- **Protocolos:** Thread, Matter, 6LoWPAN [cite: 198, 203]

---

## 📊 Visualização de Resultados

O algoritmo utiliza uma **Função Fitness** baseada em:
1. Potência total consumida. [cite: 305]
2. Restrições de RSSI (Piso de sensibilidade de -100 dBm). [cite: 305, 221]
3. Conectividade da matriz de rede. [cite: 278]

---

## 📂 Downloads e Documentação

Para uma visão detalhada da arquitetura e dos resultados comerciais/técnicos, você pode baixar o documento oficial abaixo:

### [📥 Baixar Apresentação do Projeto (PDF)](./Apresentação%20comercial%20para%20empresas%20moderna%20azul.pdf)

---

## 👨‍🔬 Autor

**Cristiano Tavares** Doutorando em Engenharia Elétrica - PPG-EE UFES [cite: 175, 176, 178]  
*Foco em Smart Grids, IoT e Inteligência Artificial.*

---
*Este repositório faz parte de uma pesquisa acadêmica contínua.*
