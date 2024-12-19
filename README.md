# Monitoreo de Precios de Criptomonedas a Través de APIs con Análisis de Tendencias

## Integrantes
- **Reyes Robles, Marcial**  
- **Sánchez Pérez, Omar Zenón**

## Descripción
Este proyecto tiene como objetivo desarrollar un sistema para recopilar información actualizada sobre los precios de diversas criptomonedas mediante APIs públicas y realizar análisis estadísticos utilizando medidas de tendencia central (media, mediana y moda). El propósito principal es proporcionar a los usuarios herramientas analíticas para identificar patrones en los precios y tomar decisiones de inversión más informadas.

---

## Motivación
El mercado de criptomonedas es conocido por su alta volatilidad. Comprender los patrones de precios a través de un análisis estadístico puede facilitar la toma de decisiones estratégicas. Este proyecto busca ofrecer una herramienta accesible que ayude a simplificar esta tarea mediante visualizaciones interactivas y datos confiables.

---

## Objetivo General
Desarrollar un sistema automatizado que recopile, analice y visualice datos sobre precios de criptomonedas, permitiendo a los usuarios comparar y evaluar información crítica para decisiones financieras.

---

## Objetivos Específicos
1. **Recopilación de datos mediante APIs:**
   - Conectar a las APIs de CoinGecko y CoinMarketCap para obtener información precisa sobre precios y métricas del mercado.
   - Implementar consultas eficientes utilizando bibliotecas como `requests`.

2. **Estructuración y limpieza de datos:**
   - Procesar los datos obtenidos para organizarlos en un formato tabular utilizando `pandas`.
   - Validar la calidad de los datos, eliminando valores atípicos o inconsistentes.

3. **Análisis estadístico:**
   - Calcular medidas de tendencia central (media, mediana, moda) para comprender la distribución de precios.

4. **Comparaciones entre plataformas:**
   - Contrastar precios y métricas entre CoinGecko y CoinMarketCap para verificar consistencia.

5. **Visualización de datos:**
   - Crear gráficos interactivos con `plotly` y gráficos estáticos con `matplotlib` y `seaborn` para facilitar la comprensión de los resultados.

---

## Flujo del Sistema
El flujo de trabajo del proyecto incluye las siguientes etapas clave:

1. **Acceso a la API:**
   - Conexión a las APIs utilizando solicitudes para obtener datos.

2. **Extracción de datos:**
   - Transformación y estructuración inicial de los datos en un formato manejable(data frame).

3. **Fusión y estructuración del DataFrame:**
   - Combinación de datos provenientes de diferentes fuentes y normalización de valores.

4. **Análisis estadístico y comparaciones:**
   - Aplicación de técnicas estadísticas para identificar tendencias y comparar datos.

5. **Visualización y personalización:**
   - Creación de gráficos interactivos y personalización para destacar métricas relevantes.

---

## Tecnologías y Herramientas Utilizadas
- **Lenguaje de programación**: Python.  
- **APIs**:
  - **CoinMarketCap**: Fuente principal de datos de mercado.
  - **CoinGecko**: Fuente complementaria para validación.
- **Bibliotecas de Python**:
  - `pandas`: Manipulación de datos.
  - `requests`: Consultas HTTP.
  - `plotly`: Visualizaciones interactivas.
  - `matplotlib` y `seaborn`: Gráficos adicionales.
- **Entorno de desarrollo**:
  - **Visual Studio Code**: Editor de código.
  - **Git y GitHub**: Control de versiones y colaboración.

---

## Resultados
Los principales hallazgos incluyen:

1. **Top 10 criptomonedas por precio:**
   - Identificación de las criptomonedas más valiosas y visualización en un gráfico interactivo.

2. **Análisis estadístico:**
   - Cálculo de medidas de tendencia central para evaluar la distribución y estabilidad de precios.

3. **Insights clave:**
   - Detección de criptomonedas con mayor estabilidad relativa en sus precios.

4. **Visualización**

Aquí puedes ver el gráfico interactivo:

![Top 10 Cryptocurrencies by Market Cap (19/12/2024)](https://raw.githubusercontent.com/OmarSanchez-UNALM/TALLER-COLABORATIVO2/refs/heads/CodigosAPIS/graficos/top_10_cryptos_19_12_2024.html)


Aquí puedes ver el gráfico interactivo:

![Top 10 Cryptocurrencies by Market Cap (19/12/2024)](https://github.com/OmarSanchez-UNALM/TALLER-COLABORATIVO2/blob/CodigosAPIS/graficos/top_10_cryptos_19_12_2024.html)


## Estructura del Proyecto
- **`codigoAPI.ipynb`**: Script principal que contiene el flujo del sistema.
- **`README.md`**: Documentación completa del proyecto.
- **`requirements.txt`**: Dependencias necesarias.

---

