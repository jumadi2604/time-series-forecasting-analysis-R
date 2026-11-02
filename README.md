# Time Series Forecasting Analysis — STVQNQ

*A collaborative time-series study focused on exploratory analysis, temporal dependence, forecasting, and rolling-origin evaluation.*

## Descripción

Trabajo colaborativo de análisis de tres series temporales. El flujo integra exploración descriptiva, operadores de rezago, análisis de dependencia, selección de métodos de pronóstico y evaluación mediante orígenes móviles. Los nombres de organizaciones y las cifras del caso son simulados, de acuerdo con el enunciado académico.

**Equipo:** STVQNQ  
**Autores:** Juan Manuel Diaz Larrea y Sofia Valentina Lopez Ramirez

## ¿Qué incluye?

- Lectura y visualización de tres series.
- Análisis de rezagos, estacionariedad y dependencia temporal.
- Implementación de métodos de pronóstico y transformaciones.
- Comparación de modelos con RMSE, MAD y MAPE.
- Evaluación por horizontes y orígenes móviles.
- Generación automatizada de tablas, gráficos, informe HTML y nota ejecutiva.
- Presentación del trabajo (`exposicion/presentacion_trabajo1.pptx`).

## Herramientas

`R` · `Quarto` · `stats` · `ggplot2` · `CSV`

## Cómo ejecutarlo

Abrir R/RStudio en la raíz del repositorio y ejecutar:

```r
source("analisis/correr-todo.R")
```

Para renderizar manualmente el informe:

```bash
quarto render informe/informe.qmd
```

Se recomienda R 4.3 o posterior. Quarto es necesario para regenerar el informe HTML.

## Reproducibilidad

Los datos de entrada están en `datos/`. Los archivos CSV de `analisis/`, los gráficos y los informes son resultados derivados del flujo automatizado. La selección de parámetros se realiza sobre entrenamiento; el tramo de prueba se reserva para evaluación.

## Autoría e historial

Trabajo realizado en equipo por Juan Manuel Diaz Larrea y Sofia Valentina Lopez Ramirez. Se conserva el historial original de 20 commits y la etiqueta `v1.0`, con los autores de cada contribución.

## Estructura

- `datos/`: series originales asignadas.
- `R/`: funciones de análisis y modelado.
- `analisis/`: flujo automatizado y resultados derivados.
- `figs/`: gráficos.
- `informe/`: informe Quarto y nota ejecutiva.
- `exposicion/`: presentación.
