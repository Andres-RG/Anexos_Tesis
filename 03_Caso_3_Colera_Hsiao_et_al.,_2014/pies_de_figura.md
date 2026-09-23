# Señales de alerta temprana en el resto de los pacientes con cólera

Esta carpeta contiene las señales de alerta temprana univariadas y multivariadas de los pacientes B a G del estudio de Hsiao et al. (2014). En el cuerpo de la tesis se presentó en detalle únicamente el paciente A, por contar con la mayor densidad de muestreo. El análisis aquí sigue el mismo protocolo.

Para cada paciente se calcularon:

- **`EWS_univariadas_diversidad_[paciente].pdf`**: señales de alerta temprana univariadas calculadas sobre el índice de Shannon exponencial, mediante el enfoque de ventana expansiva. **a)** Serie de tiempo del índice de Shannon exponencial, con las franjas indicando las fases aguda y de recuperación del paciente. **b)** Fuerza de los indicadores de alerta temprana univariados a lo largo del tiempo. Los puntos representan valores en los que la fuerza de al menos un indicador superó el umbral de 2σ (línea discontinua), considerándose como una señal de alerta temprana detectada.

- **`EWS_multivariadas_diversidad_comunidad_[paciente].pdf`**: señales de alerta temprana multivariadas calculadas sobre el conjunto completo de índices de diversidad alfa (Shannon exponencial, riqueza, equidad de Pielou, inverso de Simpson y dominancia de Berger-Parker), mediante el enfoque de ventana expansiva. **a)** Abundancia relativa (%) de las familias bacterianas dominantes a lo largo del experimento, agrupada por fase aguda y de recuperación. **b)** Fuerza de los indicadores de alerta temprana multivariados a lo largo del tiempo. Los puntos representan valores en los que la fuerza de al menos un indicador superó el umbral de 2σ (línea discontinua), considerándose como una señal de alerta temprana detectada.

En ambos casos, el eje horizontal corresponde al orden de las muestras y no a tiempo calendario, ya que el intervalo de muestreo no es constante a lo largo del experimento: cada deposición durante la fase aguda, y diario, semanal y mensual durante la recuperación. Por practicidad, las observaciones se representan de forma consecutiva. Las franjas de color indican las fases aguda y de recuperación en todos los pacientes, aunque su extensión varía entre ellos según la duración de cada fase en su evolución clínica particular.

Datos obtenidos de Hsiao et al. (2014). Elaboración propia.
