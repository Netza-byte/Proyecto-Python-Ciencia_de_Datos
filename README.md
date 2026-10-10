# Proyecto-Python-Ciencia_de_Datos
Repositorio dedicado al Proyecto del Módulo 1
## Descripción del Proyecto
Este proyecto analiza un conjunto de datos proveniente de Kaggle (`Pokemon.csv`) que contiene 800 registros y 13 atributos sobre las estadísticas de combate de Pokemon a través de 6 generaciones.

## Limpieza de Datos
* **Valores nulos:** Se identificaron 386 valores nulos en la columna `Type 2`. Se trataron reemplazándolos con el valor categórico `'Mono-Type'` para reflejar que corresponden a Pokemon de un solo tipo elemental.
* **Duplicados:** Se verificó la consistencia del dataset, confirmando la ausencia de filas duplicadas.

## KPIs Clave Calculados
* **Total de Pokemon analizados:** 800 (735 regulares y 65 legendarios).
* **Poder Total Promedio:** 435.10 puntos base.
* **Ataque y Defensa Promedio:** 79.00 y 73.84 puntos, respectivamente.
* **Tasa de crecimiento (Gen 1 a Gen 6):** Crecimiento de **+2.24%** en la estadística base total promedio.

## Visualizaciones Clave
1. **Distribución por Tipo Primario:** Gráfico de barras que muestra la predominancia de los tipos Agua (Water) y Normal.
2. **Evolución por Generación:** Gráfico de líneas que ilustra la progresión del poder promedio, observando el pico más alto en la Generación 4.
3. **Ataque vs Defensa:** Gráfico de dispersión que evidencia la ventaja estadística de los Pokémon legendarios frente a los comunes.
