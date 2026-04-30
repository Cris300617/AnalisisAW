# 📊 Proyecto ETL y Análisis de Datos - E-commerce (Amazon Simulado)

## 🧠 Descripción

Este proyecto consiste en el diseño e implementación de un proceso **ETL (Extract, Transform, Load)** utilizando un dataset ficticio que simula operaciones reales de un e-commerce tipo Amazon.

El objetivo es transformar datos crudos en información estructurada para su posterior análisis y visualización en herramientas como Power BI.

---

## 📁 Estructura del Proyecto

AnalisisAW/
│
├── notebooks/          # Procesos ETL en Python
├── sql/                # Creación de tablas y consultas
├── data/               # (No incluido) Dataset original
├── README.md

---

## ⚙️ Tecnologías Utilizadas

- Python 🐍
- Pandas
- MySQL
- SQLAlchemy
- Power BI
- Jupyter Notebook

---

## 🔄 Proceso ETL

### 📥 Extracción
Los datos fueron obtenidos desde Kaggle.  
El dataset simula transacciones reales de e-commerce (usuarios, productos, órdenes, etc.).

> ⚠️ Nota: El dataset no se incluye en el repositorio debido a su tamaño.

---

### 🔧 Transformación

Durante esta etapa se realizaron:

- Limpieza de datos (valores nulos, duplicados)
- Normalización de formatos de fecha
- Separación en múltiples tablas (modelo relacional)
- Validaciones de consistencia

---

### 📤 Carga

Los datos transformados fueron cargados en una base de datos MySQL utilizando:

- `mysql.connector`
- `SQLAlchemy`

Esto permitió estructurar la información en tablas como:

- usuarios
- productos
- ventas
- categorías

---

## 📊 Análisis y Visualización

Se desarrolló un dashboard en Power BI para analizar:

- Ventas totales
- Utilidad
- Productos más vendidos
- Rendimiento por categoría
- Comportamiento de usuarios

> ⚠️ El archivo `.pbix` no se incluye debido a restricciones de tamaño.

---

## 📥 Dataset

Puedes descargar el dataset desde:

👉 (agrega aquí tu link de Kaggle o Google Drive)

Una vez descargado, ubicarlo en:

/data/

---

## 🚀 Cómo ejecutar el proyecto

1. Clonar el repositorio
2. Instalar dependencias:

pip install pandas sqlalchemy mysql-connector-python

3. Ejecutar los notebooks en orden
4. Configurar conexión a MySQL
5. Cargar los datos

---

## 🎯 Objetivos del Proyecto

- Aplicar un flujo ETL completo
- Modelar datos para análisis
- Practicar SQL y bases de datos
- Construir dashboards analíticos

---

## 💡 Aprendizajes

- Manejo de datasets grandes
- Limpieza y transformación de datos
- Modelado relacional
- Integración Python + SQL + BI

---

## 👨‍💻 Autor

Cristóbal Picarte
