# Interactive recommender systems: A survey of the state of the art and future research challenges and opportunities (2016)

## He, C., Parra, D., & Verbert, K.

En el artículo se presentan 24 visualizaciones, cada una con sus particularidades, enfoques y problemas que buscan resolver. Luego se hace un análisis agregativo, esto es, agrupa y menciona las visualizaciones que tienen cierto detalle en común, explicando cómo se aborda un problema (por ejemplo, _cold star_ o _diversity_) Finalmente, se hace una identificación, basándose en lo anteriormente expuesto, de cuales son problemas que no se tratan (_serendipity_, _novelty_, cómo usar la información de emociones, etc.) y qué investigaciones podrían nacer de esto.

De todo lo expuesto me llaman poderosamente 2 ideas principales:

- “El usuario debe poder saber porqué se le recomienda lo que se le recomienda”
- “El usuario debe poder corregir al algoritmo cuando este último se equivoca"

Implementados de la manera correcta se genera un dialogo constante y continuo entre el usuario y el sistema recomendador, donde una constante corrección de errores permite una mejora del sistema. A su vez el usuario podría sentir que tiene el poder de controlar lo que se le recomienda en un corto plazo. Pero, todo esto viene de la mano con el siguiente punto.

La gran mayoría de las visualizaciones mostradas presentan una interfaz muy amigable con el usuario --aunque habían detalles de visualización, como que una persona con _colorblind_ no podría usar algunas visualizaciones enfocadas en color, pero eso está fuera del alcance de esta oportunidad--. Sin embargo, una interfaz no tan agradable podría llevar a un usuario a cansarse rápidamente de la plataforma. Debido a esto último, siento que una plataforma que sea agradable a la vista y cómoda de controlar podría tener incluso mayor impacto para un usuario que el algoritmo de recomendación que está siendo usado. Personalmente, cuando una plataforma me recomienda algo de manera tan agradable, lo veo o lo consumo porque el sistema mismo me lo recomendó, estando lejos de otros ítems que suelo adquirir o, incluso, que habría rechazado si la interfaz no fuese lo suficientemente atractiva.

En conclusión, para poder desarrollar buenos sistemas de recomendación no se puede dejar de lado la forma en la que se presentan. La habilidad de desarrollar buenos sistemas recomendadores está fuertemente ligada al diseño y desarrollo de la aplicación en la que se presenta. Por otra parte, una buena visualización puede llegar a mostrar muchos aspectos que normalmente no parecen tan relevantes, como es el caso de diversidad presentada por “The Diversity Donut” ( Wong et al., 2011) independiente del _accuracy_ que se haya obtenido. Finalmente, remarcar que, aunque todo sería muy ideal con buenas visualizaciones, no siempre se puede permitir debido al presupuesto o capacidades de quien está recomendando, por lo que se debe mantener un balance de lo que de verdad se está buscando.
