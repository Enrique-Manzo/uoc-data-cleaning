# uoc-data-cleaning

## Descripción del Proyecto
Este repositorio contiene una trabajo realizado para la asignatura Tipología y Ciclo de Vida de los Datos (UOC | Master en Data Sciece), que explora un conjunto de datos exhaustivo sobre fármacos aprobados desde el año 2002 hasta 2024. El trabajo está diseñado para proporcionar perspectivas sobre las tendencias, la eficacia de los medicamentos y la dinámica del mercado en la industria farmacéutica. El análisis abarca diversos aspectos, desde la limpieza e integración de datos hasta técnicas estadísticas y de aprendizaje automático avanzadas.

## Integrantes

- Wenxi Ye
- Enrique Manzo

## Carpetas y archivos

- `original_data`: carpeta que contiene los datos originales provenientes de la práctica 1.
- `processed_data`: carpeta que contiene los datos resultantes de la limpieza, preprocesado y análisis de datos.
- `data_cleaning.py`: archivo con el código de Python usado en esta práctica.
- `data_cleaning.ipynb`: archivo que contiene el notebook resultante de esta práctica, se puede visualizar en Jupyter Notebooks o Google Colaboratory.
- `interactive_presentation.html`: archivo HTML que se puede visualizar en el explorador, pero debe ejecutarse dentro de la carpeta en la que está. Vale la pena visualizarlo para poder apreciar los gráficos interactivos.

## Descripción del Conjunto de Datos
El conjunto de datos presenta información sobre diversos fármacos aprobados durante el período especificado. Atributos clave incluyen:

`Nombre del Fármaco`
`Molécula Activa`
`Forma de Dosificación`
`Fecha de Aprobación`
`Compañía Productora
`Condiciones Médicas Tratadas`
`Reseñas`
`Efectos secundarios`
`Indicación terapéutica`
`Clase del Fármaco`
`Imagen del Fármaco`
`Fármacos Relacionados`
`Calificación y Reseñas del Fármaco`
`Disponibilidad`
`Información de Precios`

El dataset procesado incluye datos tales como `Conteo de indicaciones terapéuticas` y `antigüedad de mercado`.

Este conjunto de datos es crucial para investigadores, profesionales médicos y organismos reguladores para analizar tendencias de aprobación de fármacos, comparar precios y evaluar la seguridad y eficacia de los medicamentos.

## Objetivos del Análisis de Datos
El proyecto tiene como objetivo:

- Identificar factores que influyen en la clasificación de un fármaco como sustancia con potencial de abuso y predecir dichas clasificaciones donde falten datos.
- Agrupar fármacos para proporcionar información valiosa sobre la aceptación en el mercado y las características de diferentes productos farmacéuticos.

## Limpieza y Preparación de Datos
- Técnicas de Imputación: Abordar los valores faltantes utilizando métodos apropiados como la imputación KNN para variables continuas y la imputación categórica para atributos discretos.
- Conversiones de Tipo de Datos: Asegurar que todos los tipos de datos estén correctamente identificados para facilitar el análisis, incluyendo la conversión de variables categóricas en códigos numéricos cuando sea necesario.
- Gestión de Valores Atípicos: Identificar y gestionar valores atípicos para mantener la integridad de los datos.

## Técnicas de Análisis de Datos
- Aprendizaje Supervisado: Utilizar modelos como CatBoost Classifier para predecir el potencial de abuso de los fármacos basado en datos históricos.
- Aprendizaje No Supervisado: Aplicar algoritmos de agrupamiento como k-means para agrupar fármacos basados en diversas características e identificar patrones.
- Pruebas de Hipótesis: Realizar pruebas estadísticas para explorar hipótesis sobre los datos de fármacos, como comparar precios de fármacos basados en su estatus de prescripción.

## Visualización
Se utilizan diversos gráficos y diagramas para ilustrar las distribuciones de los datos y los resultados del análisis, incluyendo:

- Gráficos de Distribución: Para variables categóricas y continuas para observar las características de los datos.
- Diagramas de Caja: Para verificar la presencia de valores atípicos y entender la dispersión de los datos.
- Gráficos de Dispersión y 3D: Para visualizar relaciones y agrupamientos entre múltiples variables.

## Requisitos
Las bibliotecas de Python requeridas incluyen:

- pandas
- numpy
- sklearn
- matplotlib
- seaborn
- requests
- catboost
- sklearn
- datetime
- plotly

## Conclusiones
Los hallazgos de este análisis proporcionan información valiosa sobre las tendencias de la industria farmacéutica durante dos décadas, destacando los factores que influyen en la aprobación de medicamentos y el éxito en el mercado. El proyecto demuestra la aplicación de técnicas de ciencia de datos en escenarios del mundo real, convirtiéndolo en un recurso valioso para los interesados en los sectores de la salud y farmacéutico.

## Licencia
Este proyecto está disponible bajo la Licencia MIT. Consulte el archivo LICENSE para más detalles.
