# Análise de Séries Temporais: Produção de Automóveis no Brasil (1957-2023) 📈🚗

Modelagem preditiva e análise descritiva de séries temporais focada no volume de produção da indústria automobilística brasileira[cite: 9].

## 📌 O Problema e Contexto Negocial
Compreender as flutuações e a sazonalidade na produção industrial é vital para projeções econômicas, planejamento de estoque e estratégias da cadeia de suprimentos. O objetivo desta análise foi isolar as tendências de longo prazo, a sazonalidade e os ruídos de mercado utilizando dados oficiais da Associação Nacional dos Fabricantes de Veículos Automotores (Anfavea)[cite: 9].

## 🛠️ Stack Técnico e Métodos Aplicados
* **Python:** Pandas, Numpy, SciPy, Matplotlib[cite: 9].
* **Statsmodels:** Utilizado para Decomposição Sazonal e testes estatísticos[cite: 9].
* **Extração de Dados:** Integração via API utilizando a biblioteca `ipeadatapy` para ingestão direta dos dados[cite: 9].
* **Metodologia Analítica:** Funções de Autocorrelação (ACF/PACF) e Decomposição Multiplicativa[cite: 9].

## 📊 Principais Insights Estatísticos
* **Identificação de Tendência e Quebras:** A análise gráfica inicial indicou uma tendência geral crescente a partir da década de 1990, seguida de retrações em períodos de crise[cite: 9].
* **Confirmação de Sazonalidade:** Através das análises de função de autocorrelação parcial (PACF), confirmou-se uma forte sazonalidade na produção, com valor de autocorrelação de 0.97[cite: 9].
* **Decomposição Multiplicativa:** A amplitude das variações na produção automotiva aumentou proporcionalmente ao longo do tempo, justificando a escolha estrutural pelo modelo multiplicativo (em vez do aditivo) para a decomposição dos dados[cite: 9].
