# Análise de Avistamentos de OVNIs no Pará

Este projeto realiza uma **análise exploratória** dos avistamentos de objetos voadores não identificados (OVNIs) na região amazônica, com base em dados públicos. Através de gráficos, mapas e clusterização, busquei identificar **padrões temporais, geográficos e descritivos** desses fenômenos.

---

## 🎯 Objetivo

Investigar o comportamento e distribuição dos relatos de OVNIs na região amazônica, com foco em:

- Picos de ocorrências ao longo dos anos
- Horários e dias com mais registros
- Tipos de objetos relatados
- Localidades com maior frequência de avistamentos
- Identificação de padrões espaciais por meio de clusterização

---

## 📁 Fonte dos Dados

- 📊 Dataset: [UFOs in the Amazon – Kaggle](https://www.kaggle.com/datasets/andantdf/ufos-in-the-amazon)
- 🗂️ Documentação histórica:  
  - [SIAN – Sistema de Informações do Arquivo Nacional](https://sian.an.gov.br/sianex/consulta/login.asp)  

---

## 🛠️ Tecnologias e Bibliotecas

- Python 
- Pandas, NumPy
- Matplotlib, Seaborn
- Folium (mapas interativos)
- WordCloud (nuvem de palavras)
- Scikit-learn (K-Means)

---

## 🔍 Metodologia

1. **Entendimento e preparação dos dados**  
   Importação dos arquivos de observações e coordenadas, análise da estrutura das tabelas, tratamento inicial e junção dos dados com base nos nomes das cidades.
   
3. **Limpeza e pré-processamento**  
   Tratamento de dados ausentes, conversão de datas e padronização de textos.

4. **Análise exploratória (EDA)**  
   Visualizações por cidade, horário, dia da semana, formato de objeto e palavras-chave dos relatos.

5. **Clusterização geográfica**  
   Agrupamento por proximidade usando K-Means com latitude e longitude.

---

## 📊 Principais Resultados

- 📅 **Pico de avistamentos** nos anos de **1977 e 1978**, especialmente em **novembro**, coincidindo com a **Operação Prato**.
- 📍 Cidades com mais ocorrências: **Colares** (38) e **Mosqueiro** (30), ambas no Pará.
- ⏰ Horários com mais registros: **19h**, **23h** e **5h**.  
- 📆 Dias mais comuns: **terças-feiras** e **quartas-feiras**.
- 🛸 Objetos predominantemente descritos como **circulares** ou **ovais**.
- 🌍 Clusterização revelou **3 regiões** com distribuição geográfica semelhante.

---

## 🌌 Conclusão

Os dados reforçam a relevância da Amazônia como cenário de manifestações aéreas não explicadas, especialmente durante a **“onda ufológica”** investigada pela FAB na década de 1970. A análise sugere que **fatores geográficos, temporais e visuais** influenciam os relatos, e abre espaço para investigações interdisciplinares envolvendo dados, história, sociologia e cultura.

---

## 🔗 Acesse o Projeto

- 📒 **Notebook**  
  [Clique aqui para visualizar o código](https://github.com/giseleoliver9/Analise_Exploratoria_de_Avistamentos_no_Para/blob/main/Analise_Exploratoria_Avistamentos_de_OVNIs_no_Para.ipynb)

- 🎥 **Apresentação**  
  [Clique aqui para ver a apresentação](https://github.com/giseleoliver9/Analise_Exploratoria_de_Avistamentos_no_Para/blob/main/Analise%20Exploratoria%20de%20Avistamentos%20de%20OVNIS%20no%20Para%20-%20Apresenta%C3%A7%C3%A3o.pdf)

---


🎙️ Extras
Podcast: OVNIs na Amazônia: o que os dados revelam?
Episódio do InsightCast em que compartilho minha análise de dados sobre avistamentos de OVNIs na região amazônica.
