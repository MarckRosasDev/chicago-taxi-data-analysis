# 🚕 Chicago Taxi Trips & Weather Impact Analysis

Análisis exploratorio de datos (EDA) de viajes de taxi en Chicago utilizando SQL y Python para identificar patrones de demanda y evaluar el impacto de las condiciones climáticas en la duración de los viajes.

---

# 📌 Portafolio de Proyectos

Este repositorio forma parte de mi portafolio de análisis de datos, donde presento proyectos desarrollados durante mi formación en Data Analytics.

---

# 📊 Proyecto: Análisis de viajes de taxi en Chicago

## 📖 Contexto del proyecto

Una empresa de viajes compartidos llamada **Zuber** desea comprender el comportamiento del mercado de taxis en Chicago.

El objetivo es analizar datos de viajes de taxis y condiciones climáticas para identificar:

- Empresas de taxi con mayor actividad
- Zonas con mayor demanda de viajes
- Posible impacto del clima en la duración de los trayectos

---

# 🔎 Análisis realizado

Se realizaron las siguientes etapas de análisis:

### 1️⃣ Extracción y preparación de datos

Se utilizaron consultas **SQL** para:

- Analizar viajes por empresa
- Filtrar datos por fechas específicas
- Integrar información de clima y viajes

Posteriormente los datos fueron exportados a **CSV** para su análisis en Python.

---

### 2️⃣ Análisis exploratorio de datos (EDA)

Con **Python, Pandas, Matplotlib y Seaborn** se realizó:

- Exploración de datasets
- Verificación de tipos de datos
- Identificación de barrios con mayor número de viajes
- Visualización de empresas de taxis más activas

---

# 📈 Visualizaciones

### Número de viajes por empresa

Este gráfico muestra qué empresas dominan el mercado de taxis en Chicago durante el periodo analizado.


---

### Top 10 barrios por finalización de viajes

Este gráfico muestra los barrios con mayor número de viajes finalizados en promedio.


---

# 📌 Conclusiones

- **Flash Cab** es la empresa con mayor número de viajes.
- El mercado está concentrado en pocas empresas grandes.
- Los barrios **Loop, River North y Streeterville** concentran la mayor demanda.
- Las zonas céntricas de Chicago presentan mayor actividad de transporte.

Este análisis permite entender patrones de movilidad urbana y la estructura del mercado de taxis.

---

# 🛠 Tecnologías utilizadas

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-ffffff?style=for-the-badge&logo=python&logoColor=black)
![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=for-the-badge&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)

---

# 📂 Estructura del proyecto
Sprint-8-Proyecto-Final
│
├── datasets
│ ├── project_sql_result_01.csv
│ ├── project_sql_result_04.csv
│ └── project_sql_result_07.csv
│
├── notebook.ipynb
│
└── README.md

---
# 🚀 Cómo ejecutar el proyecto

1. Clonar el repositorio


git clone https://github.com/MarckRosasDev/Proyecto_Final_Sprint_7.git


2. Instalar dependencias


pip install pandas matplotlib seaborn


3. Ejecutar el notebook


jupyter notebook