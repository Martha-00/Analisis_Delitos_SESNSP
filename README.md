# Análisis_Delitos_SESNSP
Este repositorio contiene el análisis de la incidencia delictiva a nivel municipal en México, utilizando variables socio-demográficas y económicas como factores explicativos. El objetivo principal es **modelar el comportamiento delictivo** y explorar su relación con distintas características estructurales de los municipios.

## Objetivos específicos
- Clasificar directamente cada uno de los delitos a nivel municipal para identificar las zonas más afectadas.
- Analizar si las variables predictoras influyen individual o conjuntamente en la incidencia de los delitos seleccionados.
- Validar los modelos estadísticos con datos de una entidad federativa específica y evaluar su desempeño.

## Contenido del repositorio
1. `Tasa de incidencia SESNSP.RMD`: archivo principal en R Markdown, donde se desarrolla el análisis.
2. `Tasa de incidencia SESNSP.pdf`: versión en PDF del archivo anterior, lista para entrega o difusión.
3. Bases de datos utilizadas:
   - `Municipal-Delitos-2015-2021_dic2021`: base principal con datos delictivos registrados en averiguaciones previas y carpetas de investigación iniciadas, descargada del **SESNSP**.
   - `gini`: contiene el Índice de Cohesión Social (GINI 2020) a nivel municipal (fuente: CONEVAL).
   - `IMM_2020`: información del Índice de Marginación 2020 (fuente: CONAPO).
   - `ind_laborales`: datos del Índice de Indicadores Laborales para los Municipios de México (ILMM 2020) (fuente: INEGI).
   - `IRS_2020`: Índice de Rezago Social 2020 (fuente: CONEVAL).
   - `m3s1p2_cngmd2021`: número de policías a nivel municipal (fuente: INEGI).
   - `Info_Proy_CD`: archivo auxiliar con el listado de variables seleccionadas de las bases anteriores para el análisis.
4. `Logo.png`: imagen utilizada en el documento.
5. Carpeta `Capas`: contiene archivos necesarios para generar los mapas a nivel municipal.

El análisis se basa en datos públicos y tiene como finalidad apoyar la toma de decisiones y el diseño de políticas públicas con base en evidencia estadística.

Información de contacto Autora: Martha Aguilar Jiménez, Correo electrónico:martha.aguilar@cimat.mx


