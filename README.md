# 🎵 Spotify Streaming Performance Dashboard

![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Data Analysis](https://img.shields.io/badge/Data_Analysis-0078D4?style=for-the-badge)
![Spotify Green](https://img.shields.io/badge/Spotify-1DB954?style=for-the-badge)

## 📌 Sobre o Projeto

Este projeto consiste em um dashboard interativo desenvolvido no **Power BI** para explorar e visualizar dados do ecossistema do Spotify. O objetivo principal deste estudo foi praticar **UI/UX voltado para Data Visualization**, criando uma interface moderna, intuitiva e temática que responde a perguntas-chave de negócios no setor de streaming de música.

---

## 🎯 Perguntas de Negócio Respondidas

O dashboard foi projetado para responder de forma rápida às seguintes métricas e visualizações:

1. **Top 10 Artistas Mais Ouvidos:** Identificação dos artistas com maior volume acumulado de streams.
2. **Streams por Língua:** Distribuição do alcance global da música conforme o idioma nativo da faixa.
3. **Distribuição Geográfica (Países):** Mapeamento do total de streams por país de origem dos artistas.
4. **Gêneros Musicais com Maior Impacto:** Análise de desempenho por gênero primário (Hip-Hop, Pop, Reggaeton, Rock, etc.).

---

## 🧠 Métricas Principais (KPIs)

* **500** Artistas Analisados
* **23** Gêneros Musicais
* **11** Idiomas Distintos

---

## 🎨 Design & Identidade Visual (UI/UX)

Para garantir uma navegação agradável e alinhada com a marca Spotify:
* **Tema Escuro (Dark Mode):** Reduz a fadiga visual e destaca as barras e indicadores do relatório.
* **Paleta de Cores Harmônica:** Foi utilizada **Inteligência Artificial** para a geração e validação da paleta de cores. A paleta foi construída a partir do verde característico da marca para garantir:
  * Alto contraste e acessibilidade entre textos e planos de fundo.
  * Hierarquia visual clara em cartões de KPI, eixos e barras de progresso.
* **Sidebar de Filtros:** Painel lateral dedicado para filtragem por País, Ano de Estreia, Gênero e Idioma.

---

## 🛠️ Tecnologias Utilizadas

* **Power BI:** Modelagem de dados, criação de medidas DAX e construção dos visuais interativos.
* **Python (Pandas):** Inspeção e tratamento inicial do conjunto de dados (`CSV`).
* **AI Assistance:** Apoio na definição da paleta de cores de fundo, texto e elementos visuais de alto contraste baseados na marca Spotify.

---

## 📁 Estrutura dos Arquivos no Repositório

```text
.
├── Data/
│   └── Spotify_Streaming_Performance_Dataset_PowerBI.csv   # Base de dados em formato CSV
├── PowerBi/
│   └── Spotify_Streaming_Dashboard.pbix                   # Arquivo fonte do Power BI
└── README.md                                              # Documentação do projeto
