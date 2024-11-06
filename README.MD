# Proyecto de Habilitación: Predicción de Supervivencia en Pacientes con Cirrosis

Este repositorio contiene el proyecto de habilitación para el curso de Seminario de Programación, enfocado en analizar la predicción de supervivencia en pacientes con cirrosis. El proyecto está estructurado para guiarte en la construcción de un modelo de clasificación basado en el dataset de supervivencia de pacientes con cirrosis proporcionado.

## Estructura del Proyecto

- **Datos**: Contiene el dataset descargado.
- **Documentacion**: Carpeta donde guardarás cualquier guía o documentación adicional del proyecto.
- **Codigo**: Carpeta para almacenar el código, los pipelines de preprocesamiento y el modelo final.

## Pasos del Proyecto

Sigue estos pasos para completar el proyecto:

1. **Configuración del Ambiente y Gestión de Dependencias**  
   - Configure un entorno de desarrollo para el proyecto y gestione todas las dependencias utilizando `poetry`.
   - Defina el archivo `pyproject.toml`, especificando todas las dependencias necesarias para el análisis de datos, preprocesamiento y modelado.

2. **Exploración de Datos**  
   - Realice una exploración inicial de los datos, incluyendo un análisis descriptivo y la generación de visualizaciones pertinentes.
   - Documente los resultados de la exploración en un cuaderno Jupyter denominado `exploracion.ipynb`, ubicado dentro de la carpeta **Codigo**.

3. **Construcción del Pipeline de Preprocesamiento**  
   - Desarrolle un pipeline de preprocesamiento para preparar los datos, incluyendo pasos como el manejo de valores nulos y la codificación de variables categóricas.
   - Guarde el pipeline en un archivo para permitir su reutilización futura.

4. **Desarrollo del Modelo de Clasificación**  
   - Amplíe el pipeline para incluir un modelo de clasificación que prediga la supervivencia de los pacientes con cirrosis.
   - Entrene y evalúe el modelo asegurándose de que los resultados sean apropiados para el problema planteado.

5. **Guardado de Pipelines y Modelos**  
   - Guarde el pipeline de preprocesamiento y el pipeline completo (preprocesamiento + modelo) en la carpeta **Codigo** utilizando `joblib` para su reutilización.

6. **Actualización del README**  
   - Actualice este archivo README si se realizan cambios o si se desea agregar información adicional para reflejar con precisión la estructura y el flujo de trabajo del proyecto.

7. **Documentación del Modelo**  
   - Cree una documentación breve del modelo y del pipeline de preprocesamiento, incluyendo detalles sobre las técnicas empleadas y los resultados obtenidos, y guarde esta información en la carpeta **Documentacion**.



## Uso del Proyecto

1. Ejecute el cuaderno de exploración para comprender la estructura de los datos.
2. Ejecute el pipeline de preprocesamiento y entrene el modelo de clasificación.
3. Guarde y documente los pipelines y el modelo, y realice las actualizaciones correspondientes en el README.

## Recursos Adicionales

Repositorios de la clase