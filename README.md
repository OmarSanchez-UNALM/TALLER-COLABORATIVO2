# Monitoreo de Precios de Criptomonedas a Través de APIs con Análisis de Tendencias

## Descripción
Este proyecto tiene como objetivo crear un sistema para recopilar información sobre los precios de diferentes criptomonedas utilizando APIs públicas y realizar análisis estadísticos empleando medidas de tendencia central como la media, mediana y moda. La finalidad es ayudar a los usuarios a identificar patrones en los precios y tomar decisiones informadas sobre sus inversiones.

---

## Motivación
El mercado de criptomonedas es altamente volátil, y la clave para tomar decisiones acertadas es identificar patrones en los precios. Este proyecto utiliza estadísticas básicas para proporcionar una visión general del comportamiento de los precios de las criptomonedas, facilitando el análisis y la toma de decisiones.

---

## Objetivo General
Desarrollar un sistema que permita obtener precios actualizados de criptomonedas a través de APIs, analizarlos utilizando medidas de tendencia central, y mostrar comparaciones de precios entre diferentes plataformas de intercambio.

---

## Objetivos Específicos
1. **Recopilación de datos mediante APIs:**
   - Utilizar APIs públicas como CoinGecko o CoinMarketCap para obtener información sobre los precios de criptomonedas.
   - Implementar consultas en Python usando bibliotecas como `requests` y `pandas`.

2. **Estructuración de datos:**
   - Organizar los datos en un `DataFrame` de `pandas`, incluyendo:
     - Nombre de la criptomoneda.
     - Precio actual.
     - Plataforma de intercambio.
     - Volumen de transacción.
     - Cambio porcentual en 24 horas.

3. **Cálculo de medidas de tendencia central:**
   - Calcular:
     - **Media**: Precio promedio durante un período específico.
     - **Mediana**: Valor central que no se ve afectado por valores extremos.
     - **Moda**: Precio más frecuente.

4. **Análisis y comparaciones:**
   - Comparar precios entre plataformas de intercambio y calcular estadísticas de tendencia central para cada plataforma.
   - Mostrar las variaciones de precios en formato de tabla.

5. **Visualización de resultados:**
   - Crear gráficos simples utilizando `matplotlib` y `seaborn` para mostrar la evolución de precios a lo largo del tiempo.

---

## Estructura del Proyecto
- `codigoAPI.ipynb`: Script principal que ejecuta el sistema.
- `README.md`: Documentación del proyecto.
- `requirements.txt`: Lista de dependencias necesarias para el proyecto.

---

## Requisitos
- **Python 3.9 o superior**
- Bibliotecas necesarias (detalladas en `requirements.txt`):
  - `pandas`
  - `requests`
  - `seaborn`