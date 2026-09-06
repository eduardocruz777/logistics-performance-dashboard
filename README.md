# 📦 Dashboard Analítico de Performance e Eficiência Logística

## 📌 Visão Geral do Projeto
Este projeto consiste no desenvolvimento de uma solução de Inteligência de Negócios (BI) voltada para o monitoramento estatístico e auditoria de uma operação de transportes de grande escala, totalizando **54 Mil entregas**. O objetivo principal é analisar a eficiência de entregas por região, o comportamento do fluxo logístico mensal e os gargalos de atraso por canais e praças de atendimento.

Projeto prático desenvolvido durante a formação de Business Intelligence da **Data Science Academy**.

---

## 💼 Fundamentos de Negócio e KPIs Monitorados
O painel foi estruturado para resolver frentes analíticas estratégicas de cadeia de suprimentos e atendimento ao consumidor, monitorando os seguintes indicadores-chave de desempenho (KPIs):

1. **Taxa de Entrega no Prazo (On-Time Delivery):** Dos **54 Mil pedidos**, um total expressivo de **47 Mil entregas** foram concluídas rigorosamente no prazo estabelecido, permitindo auditar o nível de serviço ao cliente (SLA).
2. **Eficiência Regional por Equipes:** Análise percentual da divisão de entregas por regiões liderada pelo mercado **Norte (27,44%)**, seguido de perto pelo **Sudeste (24,87%)**, **Nordeste (16,72%)** e **Sul (13,35%)**.
3. **Análise por Canais de Distribuição:** Identificação do canal campeão de entregas no prazo (liderado pelo Canal 07 e Canal 19), cruzando dados operacionais com vendas diretas e canais web (Internet representando 10,87% e Televendas com 6,25%).
4. **Mapeamento de Gargalos (Atrasos por Cidade):** Monitoramento estatístico de anomalias com foco em controle de qualidade, identificando as praças geográficas mais críticas (ex: Cidade 25 registrando o maior pico de 392 entregas em atraso).
5. **Auditoria de Rating e Desempenho de Vendedores:** Ranking gerencial correlacionando a volumetria de envios por ID de Vendedor (liderado pelo ID 3894 com 2.208 entregas) com o nível de satisfação do cliente final (Rating de 5 estrelas).

---

## 🛠️ Tecnologias e Recursos Técnicos Utilizados
* **Microsoft Power BI:** Modelagem multidimensional e engenharia de visualização de dados.
* **Power Query (ETL):** Extração de bases brutas transacionais (`.csv`), limpeza, tratamento de inconsistências de datas e formatação de variáveis geográficas.
* **Linguagem DAX:** Criação de medidas calculadas customizadas para contagem distinta de pedidos, cálculo de percentuais de status operacionais (Antecipados representando 70,71% do quadro total) e rankings de pontuação.
* **Componentes Visuais Avançados:** Gráficos de linhas temporais para análise de sazonalidade mensal (exibindo picos de envios entre fevereiro e julho), matrizes dinâmicas de classificação e segmentadores de ano (2019 e 2020).

---

## 📂 Organização dos Arquivos no Repositório
* `dataset_logistica.csv`: Base de dados transacional contendo registros de pedidos, rotas, datas de previsão e entregas reais.
* `Dashboard_Logistica.pbix`: Arquivo completo do Power BI com o modelo relacional e a engenharia visual desenvolvida.
* `README.md`: Documentação técnica, conceitual e de negócios.

---

## 👤 Autor
* **Eduardo Cruz**
* LinkedIn: [eduardo-cruz777](https://linkedin.com)
* Email: edufracruz@gmail.com
<img width="899" height="549" alt="Dashboard_7" src="https://github.com/user-attachments/assets/379dee16-009b-40df-8a0e-c573d8ee8094" />
