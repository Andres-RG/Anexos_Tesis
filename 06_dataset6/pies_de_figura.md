# Señales de alerta temprana en el microbioma de dos individuos (Caporaso et al., 2011)

Esta carpeta contiene las señales de alerta temprana calculadas para las series de tiempo de microbioma reportadas por Caporaso et al. (2011), correspondientes a dos adultos sanos (identificados como F4: mujer, y M3: hombre) muestreados diariamente sin intervención experimental. El sujeto masculino (M3) recibió antibióticos por una infección respiratoria antes y durante el periodo de muestreo, sin que esta intervención fuera controlada.

Se incluyen los cuatro sitios corporales muestreados en la mujer (heces, palma izquierda, palma derecha y lengua). Del hombre solo se analizó el microbioma de muestras fecales, ya que fue la única disponible en el conjunto de datos.

- **`EWS_univariadas_diversidad_[sitio].pdf`**: señales de alerta temprana univariadas calculadas sobre el índice de Shannon exponencial, mediante el enfoque de ventana expansiva. **a)** Serie de tiempo del índice de Shannon exponencial. **b)** Fuerza de los indicadores de alerta temprana univariados a lo largo del tiempo. Los puntos representan valores en los que la fuerza de al menos un indicador superó el umbral de 2σ (línea discontinua), considerándose como una señal de alerta temprana detectada.

- **`EWS_multivariadas_diversidad_comunidad_[sitio].pdf`**: señales de alerta temprana multivariadas calculadas sobre el conjunto completo de índices de diversidad alfa (Shannon exponencial, riqueza, equidad de Pielou, inverso de Simpson y dominancia de Berger-Parker), mediante el enfoque de ventana expansiva. **a)** Abundancia relativa (%) de las familias bacterianas dominantes a lo largo del experimento. **b)** Fuerza de los indicadores de alerta temprana multivariados a lo largo del tiempo. Los puntos representan valores en los que la fuerza de al menos un indicador superó el umbral de 2σ (línea discontinua), considerándose como una señal de alerta temprana detectada.

Como este conjunto de datos no involucra una perturbación experimental controlada, las figuras no incluyen bandas de perturbación.

Datos obtenidos de Caporaso et al. (2011). Elaboración propia.
