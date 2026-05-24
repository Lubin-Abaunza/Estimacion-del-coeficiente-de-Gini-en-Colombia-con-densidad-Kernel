# Estimación del coeficiente de Gini en Colombia con KDE

Aplicación de métodos no paramétricos para la estimación de indicadores de desigualdad y pobreza a partir de datos agrupados de ingresos.

## Descripción

Este proyecto implementa el algoritmo iterativo de estimación de densidad Kernel (KDE) propuesto por Walter et al. (2022) para estimar indicadores socioeconómicos utilizando datos agrupados por intervalos.

La aplicación empírica se realiza con datos de la operación estadística de Medición de Pobreza Monetaria y Desigualdad 2024 del DANE.

## Indicadores estimados

- Coeficiente de Gini
- Media y mediana
- Percentiles de ingreso
- HCR (Head Count Ratio)
- Poverty Gap (PGAP)

## Metodología

El proyecto utiliza:

- Estimación de densidad Kernel (KDE)
- Algoritmo iterativo con pseudo-muestras
- Bootstrap no paramétrico
- Datos agrupados por intervalos de ingreso

## Referencia

Walter, P., Groß, M., Schmid, T., & Weimer, K. (2022).
*Iterative Kernel Density Estimation Applied to Grouped Data*.
Journal of Official Statistics, 38(2), 599–635.

https://doi.org/10.2478/jos-2022-0027

## Fuente de datos

- DANE — Medición de Pobreza Monetaria y Desigualdad 2024

Variable principal utilizada:

```r
ingpcug



