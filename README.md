# 🍄 Diversidad de Macrohongos y Líquenes en la Región de Aysén 🍄
Readme de la investigación para el ramo "Metodologías de la Investigación" con título "Diversidad de Macrohongos y Líquenes en la Región de Aysén", por Javiera Catanzaro y Matilde Hernández.
---
## Introducción 
### Problemática
Pese a todas las importantes labores realizadas por el Reino Fungi, históricamente la ciencia lo ha olvidado dándole poca o cero importancias dentro de planes de conservación o tomas de decisiones al momento de intervenir ecosistemas. El conocimiento de las especies de Funga presente en los territorios y sus respectivos roles y asociaciones es esencial para el correcto manejo de estos, y para crear planes de conservación efectivos y duraderos, y por lo tanto es de crucial importancia protegerlos y conservarlos. 
### Hipótesis
La diversidad de especies de Macrohongos y Líquenes es significativamente mayor en áreas protegidas que en áreas no protegidas, debido a la menor perturbación antropogénica y la conservación de hábitats naturales.  
### Objetivos
sss

## Base de datos📊
### Base de datos original
Inicialmente la base de datos fue tomada de la página web [💻GBIF Chile](https://gbif-chile.mma.gob.cl/ipt/resource?r=fungi_sib_aysen). Esta fue una investigación bibliográfica realizada por la Universida de Magallanes en el año 2019 que contiene 1263 registros del Reino Fungi en la región de Aysén.
Luego de una revisión a la base de datos, se le realizaron algunos cambios para hacer más fácil su uso durante la investigación.
### Cambios en la base de datos
- **Eliminación de datos que no serían utilizados:** La base de datos original contaba con columnas de datos que no serían utilizados para efectos de este trabajo, como autor de la bibliografía del registro, fecha del registro, etc. 

- **Eliminación de datos incompletos:** se identificaron y eliminaron aproximadamente 300 registros de avistamientos que carecían de una georreferenciación completa

- **Reordenamiento de las columnas para una mejor comprensión**

### Base de datos utilizada
Finalmente quedaron 926 datos, el archivo [📁Base_de_datos_Macrohongos_y_Liquenes_Region_de_Aysen.xlsx](Base_de_datos_Macrohongos_y_Liquenes_Region_de_Aysen.xlsx) contiene la base de datos que fue utilizada para la realización de este trabajo de investigación. 

## R Studio 
### Metodología
Se emplearon palabras clave para categorizar áreas protegidas, como "Parque Nacional", "Reserva Nacional", "Monumento Natural", entre otros. 
Se clasificaron los avistamientos según su ubicación, dividiéndolos en dos categorías: 
- Aquellos que ocurrieron dentro de Áreas Protegidas, a los que se les asignó el valor 1
- Aquellos que se registraron fuera de Áreas protegidas, a los que se les asignó el valor 0
### Código empleado
```r
localidades_unicas<-unique(bbdd$locality)
print("Localidades únicas en la base de datos:")
print(sort(localidades_unicas))

#jajaja increible amazing
y que pasa si lo escribo asi <--s
```

### Archivo resultante
El código entregó el archivo (PONER ARCHIVO!! que permitió ???

## Python 
### Metodología
d
d
d
d
### Código empleado
d
d
d
d
d

## Resultados
