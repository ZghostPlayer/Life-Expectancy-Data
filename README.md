# 🌍 Expectativa de Vida Global - Análise e Predição com Machine Learning

## 🌍 Acesse o Dashboard Interativo!
🔗 O nosso dashboard interativo já está disponível online!  

https://life-expectancy-data-jiymjdz9zspbkopoq9h4qn.streamlit.app/

📌 **Se o link não carregar corretamente ao clicar no GitHub, copie o link com Ctrl + C e cole no navegador com Ctrl + V**

Este projeto explora um **conjunto de dados sobre expectativa de vida global**, realizando análises estatísticas e construindo um modelo de **Machine Learning** para prever a expectativa de vida de um país com base nos valores masculino e feminino.  

Além disso, foi criado um **dashboard interativo** para visualizar os insights de forma dinâmica! 🚀  

---

## 📌 **Sobre o Projeto**
🔍 **Objetivo**  
Investigar os fatores que influenciam a expectativa de vida e criar um **modelo preditivo preciso** para estimar a expectativa de vida geral de um país.

📊 **O que fizemos?**  
✅ Limpeza e pré-processamento dos dados  
✅ Análise exploratória e testes estatísticos  
✅ Construção de um modelo de **Regressão Linear Múltipla**  
✅ Criação de um **dashboard interativo** com **Streamlit e Plotly**  

---

## 📂 **Conjunto de Dados**
Os dados foram obtidos a partir do **Kaggle**, contendo informações sobre expectativa de vida global.  

📌 **Principais colunas utilizadas:**  
- `Country` → Nome do país  
- `Male_Life_Expectancy` → Expectativa de vida masculina (anos)  
- `Female_Life_Expectancy` → Expectativa de vida feminina (anos)  
- `Life_Expectancy_Both` → Expectativa de vida geral do país (média ponderada)  

📌 **Etapas do tratamento de dados:**  
- Renomeação de colunas para melhor interpretação  
- Remoção de valores inconsistentes e outliers  
- Criação de colunas auxiliares, como `Life_Expectancy_Gap` (diferença entre gêneros)  

---

## 🔬 **Análises e Descobertas**
✅ **Mulheres vivem mais do que homens na maioria dos países**  
✅ **Países do Leste Europeu e Ásia Central têm maior diferença de expectativa de vida entre gêneros**, possivelmente devido a fatores como alcoolismo e estilo de vida  
✅ **Países árabes apresentam menor diferença de expectativa de vida entre gêneros**, sugerindo um equilíbrio maior no impacto socioeconômico sobre ambos os sexos  

### 📊 **Principais gráficos gerados**
1️⃣ **Comparação entre expectativa de vida masculina e feminina**  
2️⃣ **Mapa global da expectativa de vida por país**  
3️⃣ **Top 10 países com maior e menor diferença na expectativa de vida entre gêneros**  
4️⃣ **Comparação entre valores reais e previstos pelo modelo**  

---

## 🧠 **Construção do Modelo de Machine Learning**
Utilizamos um modelo de **Regressão Linear Múltipla** para prever a expectativa de vida geral do país a partir da expectativa masculina e feminina.  

📌 **Equação do modelo:**  

Life_Expectancy_Both = a X times Male_Life_Expectancy + b X times Female_Life_Expectancy + c


📌 **Resultados do modelo:**  
✔ **Erro Médio Absoluto (MAE):** 0.06 anos  
✔ **Coeficiente de Determinação (R²):** 99.98%  
✔ **Conclusão:** O modelo prevê a expectativa de vida com altíssima precisão, mostrando que **a média entre expectativa masculina e feminina já é suficiente para estimar o valor real**.

---

## 📊 **Dashboard Interativo**
Criamos um **dashboard interativo** usando **Streamlit + Plotly**, onde é possível visualizar os insights e interagir com os dados.

🔹 **Funcionalidades do Dashboard**  
✅ Comparação da expectativa de vida entre homens e mulheres  
✅ Mapa global interativo da expectativa de vida por país  
✅ Gráficos mostrando os países com maior e menor diferença de expectativa de vida  
✅ Comparação entre valores reais e previstos pelo modelo de Machine Learning  

---
