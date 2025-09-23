# Análisis del Impacto del Sentimiento en Twitter sobre el Precio de Bitcoin (2021–2023)

Este repositorio contiene el trabajo de análisis realizado en el marco de las prácticas del Máster en Data Science de la Universidad Europea de Madrid.  
El objetivo es estudiar la relación entre el **sentimiento en Twitter** y el **precio de Bitcoin** en el periodo 2021–2023, utilizando técnicas de **Procesamiento de Lenguaje Natural (NLP)** y análisis estadístico.

---

## 📂 Estructura del repositorio

- **Notebooks/**
  - `01_sentimientos_crudos.ipynb`: Análisis inicial de la base de datos de tweets, limpieza de texto y aplicación del modelo de sentimiento (`RoBERTa`).
  - `02_analisis_financiero_10k.ipynb`: Estudio de la correlación entre sentimientos y precio de BTC utilizando tweets de usuarios con ≥10k seguidores.
  - `03_analisis_financiero_1M.ipynb`: Estudio similar, pero limitado a tweets de usuarios con ≥1M seguidores, para evaluar impacto de grandes cuentas.

- **data/**
  - `tweets_≥10k_seguidores_sentimientos.csv.gz`: Dataset procesado con resultados de sentimiento para usuarios con ≥10k seguidores.
  - `tweets_≥1M_seguidores_sentimientos.csv.gz`: Dataset procesado con resultados de sentimiento para usuarios con ≥1M seguidores.

- **PDF/**
  - `analisis_sentimientos_twitter_bitcoin.pdf`: Documento final en formato científico redactado en LaTeX.

---

## ⚙️ Tecnologías utilizadas

- **Python 3.13**  
- Librerías principales: `pandas`, `numpy`, `matplotlib`, `scikit-learn`, `transformers` (Hugging Face), `seaborn`  
- **Modelo NLP**: [`cardiffnlp/twitter-roberta-base-sentiment-latest`](https://huggingface.co/cardiffnlp/twitter-roberta-base-sentiment-latest)  
- **LaTeX**: Redacción del artículo con plantilla científica.  

---

## Metodología

1. **Recolección de datos**: tweets históricos relacionados con Bitcoin (2021–2023).  
2. **Procesamiento NLP**: tokenización y clasificación de sentimiento (positivo, negativo, neutral).  
3. **Agregación y filtrado**: análisis por grupos de usuarios (≥10k y ≥1M seguidores).  
4. **Análisis estadístico**: correlación entre sentimiento agregado y series de precios de BTC.  
5. **Visualización y discusión**: gráficos de tendencias, picos de sentimiento y comparación con episodios de volatilidad en BTC.  

---

## Resultados esperados

- Evidencia de la influencia del sentimiento en redes sociales sobre la volatilidad del precio de Bitcoin.  
- Comparación entre el impacto de cuentas medianas (≥10k seguidores) y grandes cuentas (≥1M seguidores).  
- Discusión crítica sobre las limitaciones del estudio y futuras líneas de investigación.  

---

## Autoría

Trabajo realizado por **Katherine López Ramírez**  
Prácticas curriculares – Máster en Data Science  
Universidad Europea de Madrid – 2025
