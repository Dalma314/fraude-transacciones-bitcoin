# Detección de Fraude en Transacciones de Bitcoin

Este proyecto corresponde a la **Mentoría: Detección de fraude en transferencias y transacciones entre usuarios** de la Diplomatura en Ciencia de Datos, Aprendizaje Automático y sus Aplicaciones dictada por FaMAF (UNC).

## 📌 Objetivos
- Analizar un conjunto de transacciones de Bitcoin etiquetadas como **fraudulentas** o **legítimas**.
- Realizar un **análisis exploratorio de datos (EDA)**.
- Preparar el dataset para futuros modelos de **machine learning y graph neural networks (GNNs)**.

## 🗂️ Dataset
Se utilizó el **Elliptic Bitcoin Dataset**, disponible en `torch_geometric.datasets`.  
Este dataset modela las transacciones como un **grafo dirigido**, con aristas representando transferencias entre direcciones.

- 49 snapshots temporales
- Nodos = transacciones
- Etiquetas = `licit` (legítimo), `illicit` (fraude) o `unknown`

## ⚙️ Tecnologías utilizadas
- Python 3
- PyTorch & PyTorch Geometric
- Pandas, Numpy
- NetworkX
- Matplotlib, Seaborn

## 🚀 Estructura del repositorio
```
fraude-transacciones-bitcoin/
│── notebooks/
│   └── practico2_fraude_bitcoin.ipynb
│── requirements.txt
│── README.md
```

## ▶️ Cómo ejecutar
1. Clonar el repo:
   ```bash
   git clone https://github.com/<tu-usuario>/fraude-transacciones-bitcoin.git
   cd fraude-transacciones-bitcoin
   ```

2. Instalar dependencias:
   ```bash
   pip install -r requirements.txt
   ```

3. Abrir el notebook:
   ```bash
   jupyter notebook notebooks/practico2_fraude_bitcoin.ipynb
   ```

## 📊 Resultados
En el análisis exploratorio se presentan:
- Distribución de etiquetas (fraude vs legítimas)
- Evolución temporal de las transacciones
- Propiedades estructurales del grafo (grado, densidad, conectividad)

## 🌐 Demo online
Podés abrir el notebook directamente en Google Colab:  
[![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/<tu-usuario>/fraude-transacciones-bitcoin/blob/main/notebooks/practico2_fraude_bitcoin.ipynb)
