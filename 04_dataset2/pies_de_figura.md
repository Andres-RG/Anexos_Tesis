# Señales de alerta temprana en comunidades bacterianas sintéticas (Fujita et al., 2023)

Esta carpeta contiene las señales de alerta temprana univariadas y multivariadas calculadas sobre las comunidades bacterianas sintéticas en cultivo continuo del estudio de Fujita et al. (2023), inoculadas a partir de sustratos de suelo (`soil`) y agua (`water`), con tres inóculos distintos (A: avena, B: avena-peptona, C: peptona). A diferencia de los demás casos analizados, estas comunidades no fueron sometidas a una perturbación experimental controlada, por lo que no se incluyen periodos de perturbación, los cambios observados corresponden a la dinámica interna de cada comunidad.

Para cada combinación de inóculo y réplica se calcularon:

- **`EWS_univariadas_diversidad_[origen]_[inóculo].pdf`**: señales de alerta temprana univariadas calculadas sobre el índice de Shannon exponencial, mediante el enfoque de ventana expansiva. **a)** Serie de tiempo del índice de Shannon exponencial. **b)** Fuerza de los indicadores de alerta temprana univariados a lo largo del tiempo. Los puntos representan valores en los que la fuerza de al menos un indicador superó el umbral de 2σ (línea discontinua), considerándose como una señal de alerta temprana detectada.

- **`EWS_multivariadas_diversidad_comunidad_[origen]_[inóculo].pdf`**: señales de alerta temprana multivariadas calculadas sobre el conjunto completo de índices de diversidad alfa (Shannon exponencial, riqueza, equidad de Pielou, inverso de Simpson y dominancia de Berger-Parker), mediante el enfoque de ventana expansiva. **a)** Abundancia relativa (%) de las familias bacterianas dominantes a lo largo del experimento. **b)** Fuerza de los indicadores de alerta temprana multivariados a lo largo del tiempo. Los puntos representan valores en los que la fuerza de al menos un indicador superó el umbral de 2σ (línea discontinua), considerándose como una señal de alerta temprana detectada.

Datos obtenidos de Fujita et al. (2023). Elaboración propia.
