<h1 align="center"> Cluster Jerarquico VS Cluster Particional </h1>

## Introducción
El clustering es básicamente, encontrar grupos de objetos especificando algunas características, que pueden ser similitudes o relaciones entre grupos, además de diferencias de objetos de otros grupos. Estos datos pueden dividirse cuando tenemos información significativa o útil, donde debemos tomar en cuenta la captura de la estructura natural de los datos.
 
**Clustering jerárquico**
 
• El algoritmo de clustering jerárquico organiza los elementos, de manera 
recursiva, en una estructura en forma de árbol. Este árbol representa las 
relaciones de similitud entre los distintos elementos.
 
** Pasos para formar grupos (clústeres) **
 
• Son cuatro los pasos necesarios:
 
 
• 1. Utilizar un método para medir la similitud de los elementos.
 
• 2. Utilizar un método para agrupar a los elementos.
 
• 3. Utilizar un método para decidir la cantidad adecuada de grupos.
 
• 4. Interpretación de los grupos.
 
**Clúster Particional**  
El algoritmo particional, conocido también como de particiones, organiza los 
elementos dentro de k clústeres. Tiene ventajas en aplicaciones que involucran 
gran cantidad de datos.
 
# K-means
 
Es uno de los algoritmos utilizados en la industria para crear k clústeres a partir de 
un conjunto de elementos (objetos), de modo que los miembros de un grupo sean 
similares.
 
El algoritmo k-means resuelve problemas de optimización, dado que la función es 
minimizar (optimizar) la suma de las distancias de cada elemento al centroide de 
un clúster.
 
 ## Datos
 
Contexto
 
Estudios clínicos a partir de imágenes digitalizadas de pacientes con cáncer de 
mama de Wisconsin (WDBC, Wisconsin Diagnostic Breast Cancer)
 
 Fuente de datos:
<p align='center'>
  <a href="https://github.com/LuisJavierFI/ClusterJerarquico-vs-ClusterParticional"><img src = "Datos.JPG"  width = 500> </a>
</p>

## Conclusión 
Se realizó tanto una clusterización jerárquica ascendente y una clusterización particional, pero antes de realizarlo se llevó a cabo una selección de características mediante un análisis de componentes principales. Con PCA se concluyó que las variables IDNumber, Diagnosis, Radius, Area, Compactness y Symmetry no poseen mucha informaciónrelevante para la clusterización.

Posteriormente, se procedió a realizar los dos tipos de clusterización mencionados. Al finalizar, para la clusterización jerárquica ascendente se obtuvo un total de 4 clústeres y para la clusterización particional un total de 6 clústeres.

Se observo que en cada cluster posee diferente información, de tal forma que la conclusión que se realiza en cada uno será distinta
