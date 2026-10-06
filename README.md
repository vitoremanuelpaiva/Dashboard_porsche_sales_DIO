# 🏎️ Dashboard de Análise de Vendas — Porsche

![Status](https://img.shields.io/badge/Status-Conclu%C3%ADdo-brightgreen)
![Deploy](https://img.shields.io/badge/GitHub%20Pages-Ativo-blue)
![Instituição](https://img.shields.io/badge/DIO-Santander%20Open%20Academy-red)

Projeto interativo de análise de dados das vendas da Porsche, desenvolvido como projeto prático no curso da **Digital Innovation One (DIO)** em parceria com o **Santander Open Academy**. 

O projeto simula um cenário real de Inteligência de Negócios (*Business Intelligence*) no setor automotivo, integrando um plano de higienização de dados e visualização interativa via web.

---

## 🔗 Acesse o Painel Interativo
O dashboard foi publicado e pode ser visualizado diretamente pelo navegador:  
👉 **[Acessar Dashboard no GitHub Pages](https://vitoremanuelpaiva.github.io/Dashboard_porsche_sales_DIO/)**

---

## 📌 Sumário
- [Visão Geral](#-visão-geral)
- [Funcionalidades e Métricas](#-funcionalidades-e-métricas)
- [Plano de Higienização de Dados](#-plano-de-higienização-de-dados)
- [Tecnologias Utilizadas](#-tecnologias-utilizadas)
- [Como Executar Localmente](#-como-executar-localmente)
- [Autor](#-autor)

---

## 📊 Visão Geral

A partir de dados brutos de vendas da Porsche, o projeto aborda o ciclo completo de tratamento de dados e apresentação de métricas comerciais estratégicas para suporte à tomada de decisão.

## 📈 Funcionalidades e Métricas

- **Volume e Faturamento:** Acompanhamento de receita total e unidades vendidas.
- **Desempenho por Modelo:** Análise comparativa entre os modelos da Porsche (911, Taycan, Cayenne, Panamera, Macan).
- **Ticket Médio:** Receita média por veículo comercializado.
- **Status de Entrega & Logística:** Acompanhamento dos fluxos de pedidos (*Entregue*, *Em Trânsito*, *Pendente*).
- **Relatórios Interativos:** Filtros e gráficos dinâmicos incorporados na interface web.

---

## 🧹 Plano de Higienização de Dados

Antes da apresentação no painel, a base passou por regras de tratamento e validação:

1. **Padronização de Datas:** Formatação para o padrão ISO (`AAAA-MM-DD`).
2. **Formatação Monetária:** Valores padronizados em dólar (`USD $`).
3. **Validação Geográfica:** Siglas de estados e regiões normalizadas no padrão **USPS**.
4. **Tratamento de Inconsistências:** Remoção de duplicatas, preenchimento/remoção de nulos e correção de nomes de modelos e status de entrega.

---

## 🛠️ Tecnologias Utilizadas

- **HTML5 & CSS3 / JavaScript:** Para a construção da interface do painel web (`index.html`).
- **Excel & Agentes de IA / Claude Code:** Suporte no tratamento de dados, regras de lógica e formulação de análises estratégicas.
- **GitHub Pages:** Hospedagem e deploy contínuo da aplicação web.

---

## 📂 Estrutura do Repositório

```text
├── index.html        # Interface do Dashboard Interativo
└── README.md         # Documentação do projeto
