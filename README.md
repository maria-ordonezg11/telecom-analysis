# 📘 ConectaTel – Análisis de Uso y Segmentación de Clientes

## 🧩 Introducción
Este proyecto analiza el comportamiento de los usuarios de **ConectaTel**, una empresa de telecomunicaciones que opera en México y Colombia.

A partir de tres fuentes de datos (planes, usuarios y uso real del servicio), se realiza un flujo completo de:

- Exploración de datos
- Limpieza
- Análisis
- Segmentación

El objetivo es identificar patrones de consumo y descubrir oportunidades comerciales basadas en datos.

---

## 🎯 Objetivo del proyecto

Construir una visión clara y accionable del comportamiento de los clientes de ConectaTel, identificando:

- Patrones de uso de llamadas y mensajes
- Segmentos de clientes según edad y nivel de uso
- Comportamientos atípicos (*outliers*)
- Oportunidades para optimizar planes y mejorar la experiencia del usuario

---

## 📂 Datasets utilizados

### 📄 `plans.csv`
Contiene información de los planes actuales:

- Nombre del plan  
- Minutos incluidos  
- Mensajes incluidos  
- GB incluidos  
- Costo mensual  

---

### 📄 `users_latam.csv`
Información de los usuarios:

- `user_id`  
- Edad  
- Ciudad  
- Fecha de registro  
- Plan contratado  

---

### 📄 `usage.csv`
Detalles del uso real del servicio:

- Cantidad de llamadas  
- Minutos utilizados  
- Cantidad de mensajes  

---

## 🔍 Etapas del análisis

### 🧪 1. Exploración inicial de los datos
- Revisión de estructura
- Tipos de datos
- Identificación de valores faltantes

---

### 🧹 2. Limpieza de datos
- Corrección de tipos de datos
- Manejo de valores atípicos
- Validación de rangos

---

### 📊 3. Análisis exploratorio (EDA)
- Distribuciones
- Boxplots
- Identificación de *outliers*

---

### 👥 4. Segmentación de clientes

Se construyen segmentos con base en:

- **Nivel de uso**:
  - Bajo  
  - Medio  
  - Alto  

- **Edad**:
  - Joven  
  - Adulto  
  - Adulto mayor  

---

### 📈 5. Visualización de resultados
- Gráficos categóricos  
- Comparaciones entre segmentos  

---

### 💡 6. Insights ejecutivos para stakeholders
- Hallazgos clave  
- Implicaciones comerciales  
- Recomendaciones estratégicas  

---

## ▶️ Cómo ejecutar el notebook

Puedes ejecutar el análisis fácilmente en Google Colab:

1. Entra a este repositorio  
2. Haz clic en el notebook  
3. Selecciona **"Open in Colab"**  
4. Ejecuta las celdas de arriba hacia abajo  

---

## 🚀 Resultado esperado

Al finalizar el proyecto se contará con:

- Datos limpios y listos para análisis  
- Segmentación clara de clientes  
- Identificación de patrones de consumo  
- Insights accionables para negocio  
- Visualizaciones listas para comunicar resultados  
``
