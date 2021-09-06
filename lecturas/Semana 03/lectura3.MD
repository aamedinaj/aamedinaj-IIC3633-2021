# Evaluating Recommendation Systems (2009)

## Guy Shani and Asela Gunawardana

La introduccion bastante repetitiva, pero permite que quede claro desde un comienzo cuales son los alcances del documento, los limites que tienen, los puntos a tratar y los que no.

A pesar de que se asume (hasta cierto punto) que uno al haber tenido una formación cientifica, me agradó que se hiciera una explicitación de lo que es hacer un experimento (hipotesis, control de variables, poder de generalización).

La estructura del paper es, en general, similar a un manual de uso. Qué método usar; bajo qué situaciones; cuáles son las limitaciones, pros y contras, etc. Lo que permite, en cierto grado, depender de este paper como una guía conceptual al evaluar una situación concreta y qué técnica/métrica usar.

Al intentar mesurar el _accuracy_ de predicciones de rating, no tenía idea que existía algo como "_distortion measures_", donde la semántica de los _ratings_ puede ser tal que el impacto de el error de predicción no dependesolo de su magnitud.

Me molesta que, al tocar el tema de los intervalos de confianza, diga "[...] **probabilidad** de 0.95", en lugar de "confianza", lo que está sumamente mal visto por estadísticos.

La enorme cantidad de conceptos, definiciones, explicaciones y situaciones reales e hipoteticas planteadas en este documento hacen que si alguien lo lee de manera descuidada termine enormemente confundida. Es sumamente provechoso para un novato (como quien escribe esto) tomar apuntes de este paper, y no hacerlo es prácticamente desaprovechar un extensivo análisis que incluye una enorme recopilación de casos borde que definitivamente podrían causar problemas en un implementación tentativa de sistemas de recomendación.

Todo lo que se presentó, o su gran mayoría, fue pensado desde un punto de vista experimental y de métricas, lo que implica pensar en muchos cosas a la vez. Desde aplicaciones directas y derivaciones de estas; interacciones (o la ausencia de estas) _user-user_, _item-user_, _user_-aplicación y el efecto de estas en el comportamiento de los usuarios; entre muchas otras cosas. Tomar todos esos detalles, ideas y casos borde debió ser uno de los pasos más demandantes en términos de análisis para la creación de este paper.

Me gusta que no obvien o no derivaran inmediatamente a otra fuente para entrar en detalles importantes. Ejemplo: es altamente poco probable que se me hubiese, personalmente, ocurrido un experimento para medir _novelty_ en experimentos _offline_. No sabía que era posible, creía que era una cualidad inherentemente _on-line_.

Después de todos los ejemplos expuestos entiendo que es increiblemente fácil que un usuario deje de usar la aplicación o sistema por una experiencia; ya sea pésima experiencia, medianamente mala, o simplemente un detalle como es "actualizar demasiado lento el algoritmo para que se adapte al usuario". Lo que en términos de investigación puede ser algo aceptable e incluso despreciable, pero que en aplicaciones comerciales podría comprometer una enorme cantidad de recursos de algún tipo.

Por último, y no menos importante, destacar que me ayudó a prepararme mentalmente para lo que sería afrontar (más adelante) un emperimento de este tipo. En particular, un sistema recomendados tiene que tratar con TANTAS dimensiones que podria llegar a agobiar a alguien que tenga que idear experimentos que contemplen optimizar estas, o estudiar los _trade-offs_ entre distintos pares de estos, alguno de estos:

- Preferencia de usuario
- MAE/MSE/RME/Average MAE/
- Precision/Recall/ROC
- Métricas de ranking
- _Coverage_
- _Confidence_
- _Trust_
- _Novelty_
- _Serendipity_
- _Diversity_
- _Utility_
- _Risk_
- _Robustness_
- _Privacy_
- _Adaptivity_
- _Scalability_
