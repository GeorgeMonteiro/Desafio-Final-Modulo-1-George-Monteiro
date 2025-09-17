# Desafio Final Modulo 1
Desafio Final do modulo 1, Fundamentos em Cibersegurança, do Curso Formação CyberSec da escola Vai na web juntamente com a Kensei Cybersec.
# 💼 Projeto de Infraestrutura de Rede Corporativa – Cliente Fictício S/A

Este repositório contém o projeto completo de arquitetura de rede para a empresa fictícia **Cliente Fictício S/A**, com sede em São Paulo (matriz) e filiais no Rio de Janeiro e Minas Gerais.

## 🧠 Objetivo do Projeto

Projetar uma rede corporativa segura, segmentada e escalável, garantindo comunicação entre matriz e filiais, controle de acesso por setor e políticas de segurança com base em boas práticas de TI.

---

## 🏗️ Etapas de Desenvolvimento

### 1. **Levantamento de Requisitos**
- Definição da estrutura organizacional: matriz (SP), filial RJ e filial MG.
- Identificação dos setores da matriz e necessidades específicas de cada filial.
- Exigências de segurança, mobilidade e acesso remoto.

### 2. **Planejamento de Topologia**
- Criação de três diagramas lógicos separados (matriz, filial RJ, filial MG).
- Desenvolvimento de um **diagrama global** para representar toda a estrutura interligada via VPN.

### 3. **Segmentação de Rede**
- Criação de VLANs para os principais departamentos da matriz (TI, Financeiro, Atendimento, Direção).
- Definição de sub-redes IP por setor.
- VLAN exclusiva para visitantes (Wi-Fi) isolada da rede interna.

### 4. **Segurança e Conectividade**
- Definição de uso de **firewalls** com controle de acesso e NAT.
- **VPN site-to-site** entre matriz e filiais para garantir comunicação segura.
- Explicações técnicas sobre por que não expor serviços diretamente na internet.

### 5. **Justificativa Técnica**
- Documentação da importância da segmentação, do uso de VPNs e das políticas de acesso.
- Argumentação sobre a simplicidade da filial MG e a não necessidade de múltiplas VLANs.

### 6. **Plano de Implementação (80/20)**
- Priorização das ações com maior impacto e menor esforço técnico.
- Criação de tabela de priorização com impacto, facilidade e prioridade.

### 7. **Documentação e Entregas**
- Geração de:
  - Diagramas de rede
  - Proposta de arquitetura
  - Justificativa técnica
  - Conclusão final do projeto
  - Sumário executivo
  - README para GitHub

---

## 📌 Recursos Utilizados

- Diagramas criados no [Draw.io](https://app.diagrams.net)
- Documentação estruturada no Google Docs
- Planejamento técnico com base em modelos de rede reais
- Markdown para documentação GitHub

## 📘 Projeto de Infraestrutura de Rede Corporativa

📘 O documento PDF do projeto está disponível logo acima deste README ☝️


## ✅ Conclusão

Este projeto demonstra a aplicação de boas práticas em redes corporativas, levando em consideração escalabilidade, segurança, organização e simplicidade de gerenciamento. O resultado é uma infraestrutura clara e eficiente, pronta para crescimento e mudanças futuras.

---

## ✍️ Autor

George Silva Monteiro  
Entusiasta em Cybersegurança 
📍 Brasil

---

