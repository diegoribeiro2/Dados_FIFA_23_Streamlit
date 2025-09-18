Dashboard FIFA com Streamlit
Este projeto utiliza a poderosa biblioteca Streamlit para exibir dados e tabelas de forma rápida, dinâmica e de fácil compreensão. Em poucas linhas, vamos criar um dashboard com múltiplas páginas e informações dinâmicas, aproveitando a simplicidade da combinação de Python e Streamlit.

Visão Geral
Objetivo: construir um dashboard interativo em Python para explorar estatísticas de FIFA (ratings de jogadores, desempenho de clubes, ligas, tendências, etc.), visualizando gráficos e tabelas com navegação entre várias páginas.
Tecnologias:
Python 3.x
Streamlit
Bibliotecas auxiliares conforme necessidade (pandas, numpy, matplotlib/plotly, seaborn, etc.)
Dados FIFA
O projeto utiliza datasets com informações de FIFA (ratings de jogadores, gols, assistências, minutos, posição, clube, liga, país, idade, etc.).
Estrutura típica de dados esperada:
jogadores: id, name, age, position, club, league, country, rating, goals, assists, minutes, etc.
clubes/teams: club_id, name, league, country, squad_value, etc.
tendencias: data, rating_media, gols_por_jogo, etc.
Observação: ajuste os caminhos de dados conforme seu dataset real (CSV/parquet/via API).
Por que Streamlit?
Rápido e simples: desenvolva dashboards funcionais com poucas linhas de código.
Interatividade: widgets integrados para filtros, seleções e inputs do usuário.
Multiplas páginas: organização de informações em abas/páginas, facilitando a navegação.
Funcionalidades Principais
Leitura e preparação de dados (dados FIFA)
Exibição de tabelas dinâmicas (estatísticas de jogadores/clubes)
Gráficos interativos (ratings ao longo do tempo, gols/assistências, distribuição de posições, etc.)
Layout com múltiplas páginas/dashboards
Filtros e controles para exploração de dados (regiões, ligas, posições, idade)
Capacidade de exportar resultados (CSV/PNG) se necessário
