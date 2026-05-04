En este repositorio mostramos distintos datasets antes y después de limpiarlos.

/////////// Limpieza con Excel //////
Se consultó una base de datos de dominio público:
https://data.montgomerycountymd.gov/Government/Fleet-Equipment-Inventory/93vc-wpdr/about_data

El archivo provisto por esta base es: 
Montgomery_Fleet_Equipment_Inventory_FA

Se realizo la limpieza en Excel y lo renombramos como:
(CLEANED) Montgomery_Fleet_Equipment_Inventory_FA

Se hicieron calculos estadísticos y tablas dinámicas en Excel y lo renombramos como:
(ANALYSIS) Montgomery_Fleet_Equipment_Inventory_FA

//////// Limpieza de datos realistas con Python ////////////


Para aumentar la complejidad de la tarea. Se creo un dataset sintético que simula las ventas de un e-comerce con ayuda de una IA, en este dataset se incluyen los tres archivos:
orders_dirty.cvs
products_dirty.cvs
customers_dirty.cvs

En Python se desarrolló el código del archivo "Realistic data cleaning.ipynb".
En este archivo se tiene una libreta en Jupyter que muestra detalladamente el proceso de limpiza de datos y el análisis de KPIs de una empresa de e-comerce.
El resultados son los archivos: 
orders_cleaned.cvs
products_cleaned.cvs
customers_cleaned.cvs

