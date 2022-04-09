# Extracción de condiciones de crecimiento celular con Deep Learning

Miguel Ángel Oliveros Sedano

Dante Torres Sepúlveda

Carlos Francisco Méndez Cruz

6 de abril de 2022



## Condiciones de Crecimiento Celular

Las condiciones de crecimiento celular bajo las que se realizan los experimentos reportados en literatura biomédica.

Datos obtenidos de la base de datos Gene Expression Omnibus




## Objetivo del proyecto:

Entrenar un modelo de clasificación que nos permita identificar las condiciones de crecimiento a partir de artículos o protocolos de investigación biomédica.

Problemas: Datos desorganizados, las oraciones fueron manualmente curadas, gran número de clases.



## Problema específico de nuestro proyecto.

## Programas

● Python

○ Lenguaje de programación.

● Stanza CoreNLP

○ Análisis lingüístico.

● Natural Language Tool kit

○ Análisis lingüístico.

● TensorFlow

○ Carga y ajuste de BERT




## Procesamiento de entradas

• Lectura de documentos XML.

• Obtención de Baglines.

• Separación en oraciones.

• Escribir formato final



## Siguientes pasos

**Nuevas medidas de evaluación:**

La métrica Accuracy es engañosa cuando las clases están desbalanceadas.

Las medidas de precision, recall y F1 son más representativas, funcionan tanto si las clases están balanceadas como si no

● **Precision** nos da la calidad de la predicción: ¿qué porcentaje de los que hemos dicho que son la clase positiva, en realidad lo son?

● **Recall** nos da la cantidad: ¿qué porcentaje de la clase positiva hemos sido capaces de identificar?

● **F1** combina Precision y Recall en una sola medida

**Undersampling**



### ¿Dudas o comentarios?

Miguel Ángel Oliveros Sedano, L17091124@zacatepec.tecnm.mx

Dante Torres Sepúlveda, dtorres@lcg.unam.mx

Carlos Francisco Méndez Cruz, cmendezc@ccg.unam.mx

