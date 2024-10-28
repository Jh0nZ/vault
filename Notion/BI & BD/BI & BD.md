  

## Mineria de datos

1960 processmiento de archivos

1970, base de datos jerarquicas

Estructurdaa, indexado, nosql, sql

enfocado a procesamiento

### Descubrimiento de patrones

Limpieza, integracion, seleccion, transformacion, descubrimiento y evaluacion de patrones

### Presentacion se conocimientos

Patrones interesantes representan conocimiento

### Tipos de datos

Mineria cualquier tipo de datos siempre que sean significativos para una app

Metadatos

### Mineria de datos multidimensional

Funcionalidades

Regression

Deteccion de valores atipicos

  

Aplicaciones

Bioinformatica

Web scrapping

  

Interdisciplinario

  

Desafios

Muchas areas

  

  

Db en varias ciudades

Limpiamoa, tranformarloa, integralos, cargarlos, refrescarlos en UN almacen de datos, y analizamos

  

Olap

Roll up, agrupar datos, ej ciudades en pais

Drill down, desglozar en lo mas minimo

  

BI & DM

Extraer datos

  

  

Segmentacion

  

## BI+DM

- Enriquecimiento de datos→La minería proporciona conocimientos adicionales, una visión mas completa y detallada del negocio
- Predicción y optimizacion→Con ambos podemos predecir y optimizar, ayuda a identificar patrones que predicen el comportamiento futuro, puede ser utilizado por soluciones de BI para optimizar estrategias empresariales
- Descubrimiento de datos→descubrir datos, relaciones inesperada o tendencias en los datos, conducir a nuevas perspectivas sobre el negocio
- Segmentación de clientes→segmentar clientes, estrategias de marketing y mejorar la satisfacción del cliente

## Clasificación

![[image.png]]

## Data warehouse

Enfoque no volatil, integrado, variable en el tiempo y orientado a temas.

arquitectura de 3 niveles, una db, un servidor OLAP y un cliente dcon herramientas de consulta

El mantenimiento del data warehouse se lleva a cabo mediante herramientas y utilidades de back-end, desde la extraccion hasta la gestion de metadatos

1. data warehouse→nivel inferior, servidor de base de datos, relacional generalmente
2. servidor olap→operaciones analiticas en linea
3. cliente con herramientas→nivel superior, cliente con consulta y generacion de informes

### Metadatos en data warehouse

metadatos definen los objetos del almacen y proporcionan detalles sobre la estructura, historial de datos y algorimos utilizados

### Modelos de datos multidimencionales

los data warehouse utilizan un modelo de datos multidimencional para el diseño de datos corporativos

esquemas estrella, copo de nieve o constelacion de hechos

### Operaciones

Roll up, agrupar datos, ej ciudades en pais

Drill down, desglozar en lo mas minimo

Cortar y Pivotar, operaciones para reorganizar y analiza datos desde diferentes perspectivas

### Mineria de datos en data warehouse

- apoyo a descubrimiento de conocimiento a travez de datos multidimencionales

### Servidores OLAP en DW

- ROLAP, relacional
- MOLAP, multidimencional matrizes

### Indexacion en DW

- mapa de bits
- uniones

### Generalizacion de datos

propiedades generales de los datos