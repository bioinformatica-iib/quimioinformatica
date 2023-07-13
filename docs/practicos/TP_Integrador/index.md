![Image](img/8.png){ width="250", align="left" }

# **TP Integrador**. Trabajo Práctico Integrador { markdown data-toc-label = 'TP Integrador' }

[:fontawesome-solid-download: Materiales](https://colab.research.google.com/drive/18oAnNq4HvV_07DNkRS9HJeoQureeODv-?usp=sharing){ .md-button .md-button--primary }

[:fontawesome-solid-download: Datos](https://drive.google.com/drive/folders/1CTrfhUCp0aCHCq91BPmLzAE5aGFAodW0?usp=sharing){ .md-button .md-button--primary }

# Introducción
En el campo de la quimioinformática, el estudio de las propiedades TPSA (Área de Superficie Polar Total) y LogP (Logaritmo del Coeficiente de Partición Octanol-Agua) ha demostrado ser crucial en la evaluación y predicción de las características y comportamientos de los compuestos químicos. 

El TPSA es una medida que estima la superficie total de un compuesto que es polar y, por lo tanto, capaz de formar enlaces de hidrógeno con su entorno.

Esta propiedad es importante ya que influye en:

* la solubilidad de los compuestos
* la biodisponibilidad de los compuestos
* la capacidad del compuesto para interactuar con proteínas y otros receptores biológicos

Un mayor TPSA puede indicar una mayor probabilidad de interacciones con la superficie de una célula, lo que puede afectar la absorción y distribución de un compuesto en el organismo. 

El LogP es un parámetro que describe la hidrofobicidad de una molécula, es decir, su afinidad por las sustancias lipídicas o grasas en comparación con el agua.

Este coeficiente de partición octanol-agua se utiliza ampliamente para evaluar la capacidad de una molécula para atravesar las membranas biológicas, incluida la barrera hematoencefálica.

La barrera hematoencefálica (BBB) es una estructura altamente selectiva que protege el cerebro al limitar el paso de sustancias y compuestos tóxicos desde el torrente sanguíneo hacia el cerebro. La capacidad de un compuesto para atravesar la BBB es crucial en el diseño de fármacos para el tratamiento de enfermedades del sistema nervioso central, ya que un bajo índice de permeabilidad puede impedir que el compuesto alcance su objetivo terapéutico en el cerebro.

La absorción intestinal humana (HIA) es una propiedad farmacocinética importante a considerar en el desarrollo de fármacos orales. La HIA se refiere a la capacidad de un compuesto para pasar a través de la barrera intestinal y entrar en la circulación sistémica. Una buena absorción intestinal es esencial para que un fármaco sea efectivo en el tratamiento de enfermedades sistémicas.

# Objetivo

El objetivo general de este trabajo es identificar correlaciones y tendencias que permitan comprender mejor la relación entre estas propiedades moleculares y la farmacocinética de los compuestos.

# Metodología

Para lograr este objetivo se explorarán cómo las propiedades moleculares, el TPSA y el LogP, se relacionan con la HIA y la permeación de la BBB. Se analizará cómo las variaciones en el TPSA y el LogP pueden influir en la capacidad de un compuesto para ser absorbido a nivel intestinal y atravesar la barrera hematoencefálica.

Tendrán acceso a tres conjuntos de datos:

* Set de Datos 1: Lista de moléculas con una buena absorción intestinal humana (HIA) conocida,
* Set de Datos 2: Lista de moléculas con permeación conocida a través de la barrera hematoencefálica (BBB),
* Set de Datos 3: Lista de moléculas aprobadas por la Administración de Alimentos y Medicamentos (FDA) con evidencia experimental de HIA y BBB.

Los primeros dos conjuntos de datos se utilizarán para definir el rango de parámetros en el cual los compuestos exhiben una buena HIA y permeación de la BBB. Al analizar las propiedades TPSA y LogP de las moléculas en los conjuntos de datos de HIA conocida y BBB conocida, podrás establecer umbrales y rangos específicos que se correlacionen con estas características deseadas. Esto permitirá identificar las propiedades moleculares óptimas que favorecen una buena HIA y permeación de la BBB.

Una vez que se hayan definido estos rangos de parámetros, el tercer conjunto de datos, se utilizará para validar la estrategia. Al aplicar los umbrales y rangos previamente definidos a este conjunto de datos, podrás evaluar si las propiedades TPSA y LogP de estas moléculas corresponden con la evidencia experimental. Si los resultados concuerdan con las expectativas, esto proporcionará evidencia de la eficacia de la estrategia en la identificación de compuestos con una buena HIA y permeación de la BBB.