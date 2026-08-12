# 📊 Techinova - Painel de Linha de Produção
 ******TESTE****
![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Status](https://img.shields.io/badge/status-em_desenvolvimento-yellow.svg)
![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)

O **Techinova Painel de Linha** é um sistema de monitoramento em tempo real desenvolvido para acompanhamento de linhas de produção industriais. Projetado com foco em metodologias Lean e Andon, a plataforma permite a visualização clara e centralizada de metas, produção atual, tempos de ciclo (*Takt Time*), eficiência (OEE) e status de paradas da linha.

---

## 📌 Sumário

- [Visão Geral](#-visão-geral)
- [✨ Funcionalidades](#-funcionalidades)
- [🛠️ Tecnologias Utilizadas](#️-tecnologias-utilizadas)
- [📁 Estrutura de Pastas](#-estrutura-de-pastas)
- [⚙️ Pré-requisitos](#️-pré-requisitos)
- [🚀 Como Executar o Projeto](#-como-executar-o-projeto)
- [🔐 Variáveis de Ambiente](#-variáveis-de-ambiente)
- [🤝 Contribuição](#-contribuição)
- [📄 Licença](#-licença)

---

## 🔎 Visão Geral

O objetivo principal do **Painel de Linha Techinova** é transformar dados operacionais brutas em insights visuais imediatos para operadores, supervisores e gestores no chão de fábrica. 

Com interface otimizada para ser exibida em **TVs/Monitores de linha** e dispositivos móveis, o painel reduz o tempo de resposta a gargalos, facilita a comunicação do status produtivo e impulsiona a melhoria contínua.

---

## ✨ Funcionalidades

- **📺 Modo TV (Dashboards Interativos):** Exibição em tela cheia com contraste adequado para visualização no chão de fábrica.
- **📈 Monitoramento em Tempo Real:**
  - Meta vs. Produção Realizada.
  - Cálculo e acompanhamento de *Takt Time* e tempo de ciclo.
  - Indicadores de eficiência e produtividade.
- **🚨 Sistema Andon / Alertas de Parada:**
  - Notificação visual de interrupções na linha (manutenção, falta de insumo, qualidade).
  - Cronometragem e histórico de tempo de máquina parada.
- **⚙️ Gestão de Linhas e Postos de Trabalho:**
  - Alternância entre diferentes linhas de produção ou estações.
  - Parametrização flexível de metas por turno/produto.
- **📊 Histórico e Relatórios:**
  - Registro de ocorrências e paradas por categoria.
  - Exportação de dados para análise de performance.

---

## 🛠️ Tecnologias Utilizadas

Este repositório utiliza/suporta a seguinte pilha tecnológica (ajuste conforme a stack exata do projeto):

- **Frontend:** HTML5, CSS3, JavaScript / TypeScript (React / Vue / Angular ou Vanillajs)
- **Backend (opcional/API):** Node.js / Python (FastAPI / Django) / PHP
- **Estilização:** CSS Modules / Tailwind CSS / Bootstrap
- **Banco de Dados:** PostgreSQL / MySQL / MongoDB / Firebase
- **Comunicação em Tempo Real:** WebSockets / Socket.io / Server-Sent Events (SSE)

---

## 📁 Estrutura de Pastas

```text
techinova-painel-linha/
├── public/              # Arquivos estáticos (ícones, imagens, favicon)
├── src/                 # Código-fonte da aplicação
│   ├── assets/          # Estilos globais, fontes e imagens
│   ├── components/      # Componentes reutilizáveis (gráficos, cards, modais)
│   ├── pages/           # Telas da aplicação (Dashboard, Configurações, Relatórios)
│   ├── services/        # Integração com APIs e WebSockets
│   ├── utils/           # Funções utilitárias e formatadores
│   └── App.js / index.js# Ponto de entrada da aplicação
├── .env.example         # Exemplo de configuração de variáveis de ambiente
├── package.json         # Dependências e scripts do projeto
└── README.md            # Documentação do repositório
