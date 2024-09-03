# LoL Performance Analyzer
LoL Performance Analyzer é uma ferramenta desenvolvida para analisar a performance de jogadores de League of Legends (LoL) a partir de dados armazenados em arquivos Excel. Este projeto visa fornecer insights detalhados sobre o desempenho de jogadores, facilitando a análise de estatísticas de partidas e ajudando jogadores a entender melhor suas forças e áreas para melhoria.

## Funcionalidades
- **Importação automatica de dados**: Os dados serão importados diretamente da API da Riot Games.
- **Formatação de dados**: Os dados serão formatados a partir de um layout personalizado para o projeto.
- **Gráficos de performance**: Os dados serão exibidos em gráficos para facilitar a análise.

## Tecnologias 
- Python 3.11
- Excel
- Riot API

## Como usar o script
1. **Clone o repositório**
   ```bash
   git clone https://github.com/MatheusRothstein/LoL-Performance-Tracker.git
   ```
2. **Instale as dependências**
   ```bash
   pip install -r requirements.txt
   ```
3. **Importe os dados das partidas utilizando os ID's**
   ```bash
   python performance_tracker.py [ids_das_partidas]
   ```
