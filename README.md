# Lulotest
 
## Descripción de la solución
El proyecto este compuesto en 5 carpetas.
* src : Contiene el Código donde se llama la API para encontrar los jsons y las transformaciones y limpiezas de datos de las tablas.
* profiling : Hay un resumen y análisis exploratorio por cada tabla con sus respectivos htmls. Además, hay un resumen de todas las tablas.
* json : Contiene los archivos JSON que se encontraron en la API.
* db : se encuentran las tablas limpias y procesadas de la API que fueron procesadas usando el archivo de src.
* model : Se encuentran copias de las tablas en db y las ETLS para procesar los requerimientos al área de negocios.

## Requisitos
Se necesita ejecutar el archivo ubicado en la carpeta src, para procesar hacer los llamados a la API y procesar todas las tablas.
Luego se puede ejecutar los archivos de las bases de datos y las etls en la carpeta de model.