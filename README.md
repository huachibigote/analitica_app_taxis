# Analitica de aplicación de movilidad 🚕
El proyecto se enfoca en analizar los datos recopilados a través del uso que los usuarios dan a la aplicación. Sobre cada servicio se posee información sobre :

* Longitud del viaje
* Tipo de vehículo solicitado
* Destino del viaje
* Antiguedad del usuario
* Género del usuario
* Calificación del servicio
* Número de cancelaciones del servicio

Entre otras. Durante el proyecto se visualizan varias de estas características y se plantean hipótesis que son verificadas con un grado de validez estadístico alto. La intención es obtener respuestas certeras que aporten valor a la aplicación para diseñar nuevas estrategias de captación y fidelización de usuarios.

#  Herramientas 🛠️

* Python
* Kaggle
* Numpy
* Pandas
* Scipy
* Matplotlib
* Seaborn

# Visualizaciones 📊

Visualmente es posible verificar diversas tendencias en los datos.

* La distancia de los viajes sigue un comportamiento multimodal. Por lo que es posible agrupar la mayoría de los viajes en categorías de distancia

  

![Historigrama-Distancia de viajes](https://github.com/huachibigote/analitica_app_taxis/assets/61852105/c4495497-ddb9-45fa-8b89-57105c48dd6c)


* La media de la calificación del servicio es cercana a 3. Si se mejora el servicio esta media subirá, por lo cual puede usarse como indicador

  
![ranking_all_user](https://github.com/huachibigote/analitica_app_taxis/assets/61852105/4e7cf1ff-32af-48b4-83fb-241a192d3b94)



* A pesar de que los hombres representan el 70% de los usuarios. Ambos generas tienen el mismo comportamiento respecto a las distancias de sus viajes y las calificaciones que otorgan al servicio.

  
![trip_dist_gender](https://github.com/huachibigote/analitica_app_taxis/assets/61852105/a314af90-4380-4803-ba3d-8ec16a63d4b1)


  
![ranking_gender](https://github.com/huachibigote/analitica_app_taxis/assets/61852105/a6f88c0c-3cac-423c-9e2d-2c818c49bb3c)

  
  

# Experimentos estadísticos  🧪

Mediante la prueba de hipótesis podemos concluir :

* Con una confianza del 99% Podemos decir que entre los destinos de tipo A y B ocupan una proporción de entre el [ 0.79-0.82 ] de los clientes

* Con un 99% de confianza es posible asegurar que la proporción de hombres que usan el servicio está entre el 69% y el 73% del total

* Con un 99% de seguridad podemos decir que entre un 83%-86% de los usuarios son asignados con un precio de tipo 2 o 3

* Entre un 6.85% y un 8.67% de los usuarios cancela 3 o más veces al mes

* Con una confianza del 99% podemos decir que hombres y mujeres toman viajes con el mismo rango de distancia

* Con una confianza del 99% podemos decir que los hombres y las mujeres califican del mismo modo los viajes

* Con una confianza del 99% podemos decir que los hombres y las mujeres cancelan en la misma proporción




