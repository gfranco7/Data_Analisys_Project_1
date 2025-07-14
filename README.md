# Data_Analisys_Project_1
**Bootcamp Talento Tech - Proyecto Final**

## AI Job Dataset Analysis Project

### 🧠 Overview
Este proyecto analiza un conjunto de datos de ofertas de trabajo relacionadas con inteligencia artificial (AI), que contiene **15,000 registros** con **18 características** cada uno. El dataset incluye información sobre títulos de empleo, salarios, habilidades requeridas, niveles de experiencia, detalles de la empresa y más.

---

### 📄 Dataset Description

El archivo `ai_job_dataset.csv` contiene las siguientes características:

- ID del trabajo y título
- Información salarial (USD y moneda original)
- Nivel de experiencia y años de experiencia
- Tipo de empleo y detalles de la empresa (ubicación, tamaño)
- Habilidades requeridas y nivel educativo
- Industria y fechas de publicación
- Puntaje de beneficios y nombre de la empresa

---

### 🔍 Key Features

- **Data Loading**: Descarga y carga del dataset desde Google Drive.
- **Data Exploration**: Estadísticas básicas y forma del conjunto de datos.
- **Feature Engineering**:
  - Conversión de variables categóricas a valores numéricos (niveles de experiencia, tipos de empleo, etc.)
  - Manejo de campos de fechas y puntajes de beneficios.
- **Visualization**:
  - Diagramas de caja para analizar la distribución salarial según el nivel de experiencia.
- **Data Cleaning**:
  - Verificación de valores nulos o NaN en el conjunto de datos.

---

### 🧰 Requirements

- Python 3  
- `pandas`  
- `numpy`  
- `seaborn`  
- `matplotlib`  
- `gdown` (para descargar desde Google Drive)

---

### 🚀 Usage

Ejecuta las celdas del notebook de forma secuencial para:

1. Descargar y cargar el dataset
2. Explorar estadísticas básicas
3. Convertir variables categóricas
4. Visualizar distribuciones de datos
5. Verificar valores faltantes

El notebook está estructurado con encabezados claros para cada paso del análisis.

---

### 📊 Potential Analysis Directions

- Tendencias salariales según nivel de experiencia
- Habilidades más demandadas en ofertas de AI
- Relación entre tamaño de empresa y salarios
- Análisis de trabajos remotos
- Correlaciones con el puntaje de beneficios

---

### ⚠️ Note

El dataset contiene fechas de publicación futuras (2024-2025), lo que sugiere que puede tratarse de datos sintéticos o de predicción.

---

### ✍️ Author

**Gean Franco Jacome Laguna**

---

### 📜 License

Licencia no especificada – por favor verifica los derechos de uso con el proveedor del dataset.
