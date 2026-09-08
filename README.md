# Anexos de tesis: Señales de alerta temprana como herramienta para anticipar transiciones críticas en comunidades bacterianas

Este repositorio contiene las figuras complementarias de la tesis.

**Caso 1: Microbioma intestinal de dos cohortes de ratones sometidos a perturbaciones experimentales (Gibson et al., 2025).** En el cuerpo de la tesis se presentaron en detalle las señales de alerta temprana de la cohorte sana; aquí se incluyen los análisis restantes para esa misma cohorte:

- Distribuciones bimodales
- Análisis de potencial, incluyendo los mapas de estados

Para la cohorte disbiótica se incluye:

- Señales de alerta temprana univariadas y multivariadas

**Caso 2: Comunidades bacterianas intestinales de cucarachas con ciclos de antibiótico (Marín-Miret et al., 2024).** Se presentan las señales de alerta temprana univariadas y multivariadas de las otras dos poblaciones experimentales de cucarachas tratadas con antibiótico, que no se abordaron en el cuerpo de la tesis.

**Caso 3: Comunidad bacteriana intestinal de pacientes con cólera (Hsiao et al., 2014).** Se presentan las señales de alerta temprana univariadas y multivariadas del resto de los pacientes del estudio, que no se presentaron en la tesis.

**Casos adicionales.** Para los cuatro conjuntos de datos no desarrollados en el cuerpo principal del documento, se presentan únicamente las señales de alerta temprana:

- **Dataset 2:** Comunidades sintéticas (Fujita et al., 2023)
- **Dataset 4:** Microbioma fecal de comunidades sintéticas de ratones sometidos a cambios de dieta (McNulty et al., 2013)
- **Dataset 6:** Microbioma humano de dos individuos en múltiples sitios corporales (Caporaso et al., 2011)
- **Dataset 7:** Microbioma fecal humano longitudinal (David, Materna et al., 2014)

## Estructura del repositorio

```
├── 📁Caso 1/
│   ├── Cohorte saludable/
│   │   ├── Resultados de bimodalidad/
│   │   ├── EWS de bacterias bimodales/
│   │   └── Análisis de potencial/
│   └── Cohorte disbiótica/
│       └── EWS univariadas y multivariadas/
├── 📁Caso 2/
│   └── EWS univariadas y multivariadas de las poblaciones restantes/
├── 📁Caso 3/
│   └── EWS univariadas y multivariadas de los pacientes restantes/
├── 📁Dataset 2/
│   └── EWS univariadas y multivariadas/
├── 📁Dataset 4/
│   └── EWS univariadas y multivariadas/
├── 📁Dataset 6/
│   └── EWS univariadas y multivariadas/
└── 📁Dataset 7/
    └── EWS univariadas y multivariadas/
```

## Referencias de los conjuntos de datos

| Carpeta | Referencia |
|---|---|
| Caso 1 | Gibson, T.E., Kim, Y., Acharya, S. et al. (2025). Learning ecosystem-scale dynamics from microbiome data with MDSINE2. *Nat Microbiol* 10, 2550–2564. |
| Caso 2 | Marín-Miret, J., Pérez-Cobas, A.E., Domínguez-Santos, R. et al. (2024). Adaptability of the gut microbiota of the German cockroach *Blattella germanica* to a periodic antibiotic treatment. *Microbiological Research* 287, 127863. |
| Caso 3 | Hsiao, A., Ahmed, A.M.S., Subramanian, S. et al. (2014). Members of the human gut microbiota involved in recovery from *Vibrio cholerae* infection. *Nature* 515, 423–426. |
| Dataset 2 | Fujita, H., Ushio, M., Suzuki, K. et al. (2023). Alternative stable states, nonlinear behavior, and predictability of microbiome dynamics. *Microbiome* 11, 63. |
| Dataset 4 | McNulty, N.P., Wu, M., Erickson, A.R. et al. (2013). Effects of Diet on Resource Utilization by a Model Human Gut Microbiota Containing *Bacteroides cellulosilyticus* WH2, a Symbiont with an Extensive Glycobiome. *PLoS Biol* 11(8), e1001637. |
| Dataset 6 | Caporaso, J.G., Lauber, C.L., Costello, E.K. et al. (2011). Moving pictures of the human microbiome. *Genome Biol* 12, R50. |
| Dataset 7 | David, L.A., Materna, A.C., Friedman, J. et al. (2014). Host lifestyle affects human microbiota on daily timescales. *Genome Biol* 15, R89. |

Los siete conjuntos de datos analizados provienen de estudios previamente
publicados; las descripciones completas de cada conjunto (muestras, duración,
diseño experimental) se encuentran en la sección de métodos de la tesis.
