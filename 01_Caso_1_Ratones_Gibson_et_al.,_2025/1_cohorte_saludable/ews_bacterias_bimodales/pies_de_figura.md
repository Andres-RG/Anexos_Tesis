# Análisis de potencial de las bacterias con distribuciones bimodales

Cada archivo PDF de esta carpeta contiene el análisis de potencial calculado sobre la abundancia relativa transformada mediante CLR de cada género bacteriano con distribución bimodal en la cohorte sana de ratones gnotobióticos.

En cada figura: **a)** densidad de probabilidad empírica de la abundancia relativa transformada mediante CLR, estimada mediante un kernel gaussiano con el ancho de banda de Silverman; las barras corresponden al histograma de las observaciones y la línea azul a la densidad estimada. **b)** Potencial reconstruido $U(z)=-\log f(z)$. La línea gris punteada corresponde al potencial empírico obtenido directamente de la densidad, y la línea roja al ajuste polinomial de grado cuatro por mínimos cuadrados ponderados por $f(z)$. En ambos paneles, las líneas rojas punteadas indican los puntos de inflexión del potencial ajustado, a partir de los cuales se estima el número de estados como $S = 1 + I/2$. El punto verde señala el mínimo del potencial. El sombreado delimita las regiones asociadas a cada estado.
Datos obtenidos de Gibson et al. (2025). Elaboración propia.

## Archivos

- `analisis_potencial_Roseburia.pdf` — presentado en el cuerpo de la tesis (Figura 6.13).
- `analisis_potencial_[Clostridium]_innocuum_group.pdf`}
- `analisis_potencial_GCA-900066755.pdf`
- `analisis_potencial_Hungatella.pdf`
- `analisis_potencial_Lachnospiraceae_UGC_009.pdf`
- `analisis_potencial_Lachnospiraceae_UGC_010.pdf`
- `analisis_potencial_Murimonas.pdf`
- `analisis_potencial_Ruminococcus.pdf`
- `analisis_potencial_Subdoligranulum.pdf`
- `analisis_potencial_UGC_005.pdf`

# Mapa de estados detectados por ventana deslizante

Cada archivo PDF de esta carpeta contiene el número de estados detectados calculados sobre la abundancia relativa transformada mediante CLR de cada género bacteriano con distribución bimodal en la cohorte sana de ratones gnotobióticos.

En cada figura: **a)** serie de tiempo de la abundancia relativa transformada mediante CLR ($N=77$). **b)** Mapa del número de estados estimado mediante el análisis de potencial aplicado sobre segmentos de la serie. El eje horizontal indica el punto medio de cada ventana y el eje vertical su longitud en número de observaciones, de modo que cada celda corresponde al segmento centrado en ese punto y con la longitud señalada, y no a los datos temporales del experimento. El color indica el número de estados detectados: rojo, un estado; verde, dos; cian, tres.
Datos obtenidos de Gibson et al. (2025). Elaboración propia.

## Archivos

- `mapa_estados_Roseburia.pdf` — presentado en el cuerpo de la tesis (Figura 6.15).
- `mapa_estados_[Clostridium]_innocuum_group.pdf`
- `mapa_estados_GCA-900066755.pdf`
- `mapa_estados_Hungatella.pdf`
- `mapa_estados_Lachnospiraceae_UGC_009.pdf`
- `mapa_estados_Lachnospiraceae_UGC_010.pdf`
- `mapa_estados_Murimonas.pdf`
- `mapa_estados_Ruminococcus.pdf`
- `mapa_estados_Subdoligranulum.pdf`
- `mapa_estados_UGC_005.pdf`
