# Customer Segmentation in Retail (Super Sano y Fresco)<br>

[![Python](https://img.shields.io/badge/Python-3.7%2B-blue?logo=python)](https://www.python.org/)
[![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/tu_usuario/tu_repositorio/blob/main/RedNeuronalBasicaConCapasOcultas.ipynb)

## 📌 Business Problem
Una cadena retail desea clasificar sus clientes para enfocar campañas comerciales y mejorar retención y ventas.

## 🎯 Objective
Segmentar la base de clientes según patrones de compra para definir estrategias de marketing personalizadas.

Para ello desarrollé un modelo de analisis robusto a partir de un dataset complejo y desestructurado sobre la venta de un Supermercado, aplicando técnicas avanzadas de **EDA (Análisis Exploratorio de Datos)** y **ETL (Extracción, Transformación y Carga)**. El resultado final permite generar insights accionables para la toma de decisiones objetivas en el ámbito empresarial.<br>
Se trabajo con análisis de KPIS más relevantes para la empresa, Market Basket Case (MBA), y ABC Analysis para obtener los insights buscados y trabajar sobre los mismos para aplicar en la práctica operativa de la compañia.
Todo esto se pude apreciar en el Dashboard realizado con Power BI.

<p align="center">
  <a href="https://postimg.cc/9RSp0Pdg" target="_blank">
    <img src="https://i.postimg.cc/7hPQBmf4/sano-y-fresco-2.png" alt="Sano y Fresco" width="400">
  </a>
</p>        

## 🛠 Tools Used
- **Python (Pandas)** para limpieza y análisis
- **scikit-learn** para clustering
- **Power BI** para reportes finales
- **SQL** para consultas y extracción
- **Excel** para revisión y limpieza de datos

---

## 📁 What’s Inside (https://github.com/DiegoFCd/Super-Sano-y-Fresco)
- `notebook.ipynb`: análisis completo  
- `data/`: dataset utilizado  
- `assets/`: capturas del resultado final

---

## 📈 Segmentation Dashboard Preview


[![Captura-dash-ventas.png](https://i.postimg.cc/0jCV3Hgn/Captura-dash-ventas.png)](https://postimg.cc/CnzCn7xn)  
[![Captura-dash-reglas.png](https://i.postimg.cc/FsDPVqVN/Captura-dash-reglas.png)](https://postimg.cc/8jfB1ZY0)

---

## 🔍 Methodology
1. **Data cleaning**: tratamiento de nulos y outliers  
2. **Feature selection**: métricas clave (freq, recency, monetary)  
3. **Clustering model** (K-Means)  
4. **Cluster interpretation**

---

## 🧠 Key Insights
✔ Se identificaron **3 segmentos clave de clientes**  
✔ Segmentos con distinto valor de ticket promedio y frecuencia  
✔ Recomendaciones comerciales incluidas

---

## 📈 Business Impact 
✔ Permite campañas personalizadas que pueden **aumentar RFM por segmento**  
✔ Mejora retención y crecimiento base de clientes

# Archivos grandes (no versionados)

Este repositorio no incluye los artefactos pesados. Descárgalos desde:

- **Base de datos**: [Descargar](https://drive.google.com/file/d/1ZiEv-tG7UwDWdPul-Ang7vbPx0s3CgAo/view?usp=sharing)
  - Ubicación local esperada: `DB_sanoyfresco/sanoyfresco.db`

- **Informe Power BI**: [Descargar](https://drive.google.com/file/d/1rcfKEG6V320r8f68jGzBgI3G66zw9o-V/view?usp=sharing)
  - Ubicación local esperada: `2-power bi/sano_y_fresco.pbix`

> Tras descargarlos, colócalos en las rutas indicadas. Están ignorados por `.gitignore`.
