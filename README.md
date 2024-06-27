# TFG
En este repositorio se hallan los dos notebooks en los que hemos aplicado y comparado las técnicas PCA y SMCCA-GS sobre la cohorte ómica de pacientes con cáncer de mama y sobre la cohorte ómica de pacientes con la enfermedad de Alzheimer (proyecto ROSMAP).

## Estructura de los ficheros
Ambos ficheros están organizados con las mismas secciones: 

1. Introducción: breve introducción sobre lo que realizamos en los notebooks.
2. Preparación de los datos: realizamos el preprocesado de los conjuntos de datos para poder aplicar las dos técnicas (PCA y SMCCA-GS).
3. PCA: aplicación de PCA sobre los conjuntos de datos, cálculo de las distancias, visualización gráfica del resultado, cálculo de las correlaciones y aplicación de bosques aleatorios. 
4. SMCCA-GS: aplicación de SMCCA-GS sobre los conjuntos de datos, cálculo de las distancias, visualización gráfica del resultado, cálculo de las correlaciones y aplicación de bosques aleatorios. En la subsección 4.2 se realiza la comparativa entre las variables canónicas obtenidas.
5. Distancia entre pares de puntos en el espacio de proyección: se comparan las distancias obtenidas, se aplica bootstrapping y se comentan los resultados de la aplicación de dicha técnica.
6. Comparativa de los resultados: se realiza la comparativa visual, la comparativa de las corelaciones entre pares de componentes generados por cada método y la comparativa de los resultados obtenidos tras la aplicación de bosques aleatorios.
7. Conclusión

## Ejemplo sencillo
En el fichero "SMCCA-GS-DP_MS_RNA-Cohorte_Cancer_De_Mama" se corresponde con la aplicación y comparación de PCA y SMCCA-GS sobre la cohorte ómica de pacientes con cáncer de mama. Se puede consultar en: https://jyjumu.github.io/TFG/SMCCA-GS-DP_MS_RNA-Cohorte_Cancer_De_Mama.html

## ROSMAP
En el fichero "PCA_SMCCA_GS-ROSMAP - cohorte_ROSMAP" se corresponde con la aplicación y comparación de PCA y SMCCA-GS sobre la cohorte ómica de pacientes del proyecto ROSMAP. Se puede consultar en: https://jyjumu.github.io/TFG/PCA_SMCCA_GS-ROSMAP%20-%20cohorte_ROSMAP.html
