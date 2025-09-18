# 📊 Dashboard FIFA com Streamlit

Este projeto utiliza a poderosa biblioteca **Streamlit** para exibir dados e tabelas de forma rápida, dinâmica e de fácil compreensão.  
Em poucas linhas, vamos criar um dashboard com múltiplas páginas e informações dinâmicas, aproveitando a simplicidade da combinação de **Python** e **Streamlit**.

---

## 🎯 Visão Geral

**Objetivo:**  
Construir um dashboard interativo em **Python** para explorar estatísticas do **FIFA** (ratings de jogadores, desempenho de clubes, ligas, tendências, etc.), visualizando gráficos e tabelas com navegação entre várias páginas.

**Tecnologias utilizadas:**
- Python 3.x  
- Streamlit  
- Pandas, Numpy  
- Matplotlib / Plotly, Seaborn  
- Outros pacotes auxiliares conforme necessidade  

---

## 📂 Dados FIFA

O projeto utiliza datasets com informações do **FIFA** (ratings de jogadores, gols, assistências, minutos, posição, clube, liga, país, idade, etc.).

**Estrutura típica esperada:**
- **jogadores:** `id`, `name`, `age`, `position`, `club`, `league`, `country`, `rating`, `goals`, `assists`, `minutes`, etc.  
- **clubes/teams:** `club_id`, `name`, `league`, `country`, `squad_value`, etc.  
- **tendencias:** `data`, `rating_media`, `gols_por_jogo`, etc.  

> ⚠️ Observação: ajuste os caminhos de dados conforme seu dataset real (CSV, Parquet ou via API).

---

## 🚀 Por que Streamlit?

- **Rápido e simples:** dashboards funcionais com poucas linhas de código  
- **Interatividade:** widgets integrados para filtros, seleções e inputs  
- **Múltiplas páginas:** organização de informações em abas/páginas  
- **Visualização dinâmica:** gráficos interativos e tabelas dinâmicas  

---

## 🛠️ Funcionalidades Principais

- Leitura e preparação de dados FIFA  
- Exibição de tabelas dinâmicas (estatísticas de jogadores/clubes)  
- Gráficos interativos (ratings ao longo do tempo, gols/assistências, distribuição de posições, etc.)  
- Layout com múltiplas páginas/dashboards  
- Filtros e controles para exploração de dados (regiões, ligas, posições, idade)  
- Capacidade de exportar resultados (CSV/PNG) se necessário  

---
