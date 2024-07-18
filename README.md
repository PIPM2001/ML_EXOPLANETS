# ML_EXOPLANETS
Proyecto Machine Learning - Bootcamp The Bridge 


Lanzado en 2009, el Telescopio Espacial Kepler nos enseñó que nuestra galaxia tiene más planetas que estrellas. Inicialmente, Kepler miró fijamente una sola parte del cielo durante cuatro años, buscando sombras: la diminuta caída de la luz de las estrellas cuando un planeta cruza la cara de su estrella. Lo que se conoce como la tecnica del análisis del tránsito.
Hasta que se retiró en 2018 Kepler tiene el récord de descubrir la mayor cantidad de planetas de cualquier misión de exoplanetas: más de 2600.

Hoy en día el telecopio JAMES WEBB puede obtener imagenes en infrarrojos que procesadas con Deep Learning ha sido posible evitar el deslumbramiento que produce la estrella y nos han dado las primeras "imagenes" de exoplanetas.
Pero ¿donde debe apuntar el WEBB? o ¿que imagenes de las que nos facilita el WEBB son candidatas al costoso proceso de extraccion de la imagen del exoplaneta?.

Este proyecto desarrolla un modelo de Machine learning que predice que datos tipo KEPLER corresponden a un exoplaneta y por tanto vale la pena captar y procesar imagenes de ese punto del espacio.

El los datos empleados para el entrenamioemto y ajuste del modelo son publicos

https://www.kaggle.com/datasets/arashnic/exoplanets/data?select=exoplanets.csv

El modelo se ha desrrollado con LightGBM.

Directorios del repositorio:

results_notebook -> contiene los notebooks y las librerias no standard empleadas para el desarrollo del modelo

modelos -> contiene el modelo reultante

data_dample -> contiene el dsataset utilizado para entrenamiento y un peqeuño dataset con datos sin etiquetar para relizar la prueba

