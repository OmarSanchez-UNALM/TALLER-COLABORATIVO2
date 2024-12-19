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
   - Utilizar APIs como CoinGecko o CoinMarketCap para obtener información sobre los precios de criptomonedas.
   - Implementar consultas en Python usando bibliotecas como `requests` y `pandas`.

2. **Estructuración de datos:**
   - Organizar los datos recopilados en un `DataFrame` de `pandas` con las siguientes columnas relevantes:
     - **Nombre** de la criptomoneda.
     - **Símbolo**.
     - **Precio (USD)**.
     - **Capitalización del mercado (USD)**.
     - **Volumen 24h (USD)**.
     - **Porcentaje de cambio en 24h (%)**.
     - **Suministro circulante**.
     - **Suministro total**.
     - **Suministro máximo**.
     - **Última actualización (Fecha)**.
     - **Fuente**.

3. **Cálculo de medidas de tendencia central:**
   - Calcular:
     - **Media**: Precio promedio durante un período específico.
     - **Mediana**: Valor central que no se ve afectado por valores extremos.
     - **Moda**: Precio más frecuente.

4. **Análisis y comparaciones:**
   - Comparar precios entre plataformas de intercambio y calcular estadísticas de tendencia central para cada plataforma.


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
  - `numpy`