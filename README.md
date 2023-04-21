# Vectorial space & cosin similarity
## Algorithm to detect plagiarism
## By Rodrigo Guarneros

This repository contains the algorithm to compare 2370 suspect documents that should be compared with 230 sources.

El objetivo de esta actividad es detectar,  a nivel básico por medio de una medida de ***similitud coseno***, el plagio que hay dentro de un conjunto de 2,370 documentos sospechosos y 237 documentos fuente.

Para tal efecto, este documento tiene las siguientes secciones:

1. Resumen ejecutivo
2. Obtención de información
3. Normalización de cada documento por lista (folder)
    * Mayúsculas
    * Símbolos
    * Tokenización
    * Stop Words
    * Stemming (derivación)
4. Similitud coseno para todos los archivos
5. Cálculo de la similaridad de Jaccard y Dice a partir del espacio vectorial definido y para hacer más comparables los resultados.
6. Los resultados en una sola tabla
7. Comparación Gráfica
8. Conclusiones

Como resultado de la aplicación de los referidos algorítmos de similaridad, se encontró lo siguiente: 

![Resultados](https://github.com/RodGuarneros/vectorial_space_cosin_similarity_plagiarism/blob/main/Comparativo.png)
