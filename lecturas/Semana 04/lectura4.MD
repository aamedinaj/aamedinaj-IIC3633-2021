# Content-based recommendation systems. In The adaptive web (2007)

## Pazzani, M. J., & Billsus, D.

Bajo el contexto de las recomendaciones en internet, los autores comienzan explicando qué son las bases de datos tabulares que representan items y porqué usar estas representaciones de items podría ser una mejor idea para recomendar. Luego mencionan que se podría construir un "perfil de cada usuario" basandose, ya sea, usando las descripciones de las preferencias del usuario o el historial de interacciones del usuario. Durante la mayoría de los capítulos siguientes los autores explican diversos métodos para descomponer y tratar con atributos de de texto y, dentro de un espacio que representa todos los items posibles, agrupar estos. Ejemplos de estos métodos son _KNN_, _Naive Bayes_, _Decision Trees_, entre otros. Termina incluyendo usos de _Machine Learning_ en estas tareas y mencionando las limitaciones y extensiones de este enfoque.

Uno de los puntos que me llamó la atención es que, en _user customization_ mencionen que "el usuario debe hacer un esfuerzo y son pocos quienes lo hacen". En lo personal, cuando ingreso a una página o aplicación me gusta que se despliegue una encuesta de items, artistas o áreas que me gustan o llaman la atención para poder comenzar haciendo una buena recomendación. En estos tiempos, uno ya no es ignorante de que se usan algoritmos de recomendación y, en general, uno podría pensar que dando esa información podrían prestar un mejor servicio. Pero supongo que en esos años donde eso no era lo común, simplemente era un gasto de tiempo o amenaza a la privacidad.

Por otro lado, se menciona el _trade-off_ que existe entre _feedback_ implicito contra el explicito. A pesar de que tiempo después saldrían _papers_ que estudian este balance en más profundidad, como lo son:

- "_Collaborative Filtering for Implicit Feedback Datasets_"(Hu, Koren, Volinsky; 2008)
- "_Walk the Talk: Analyzing the Relation between Implicit and Explicit Feedback for Preference Elicitation_"(Parra, D. y Amatriain, X.; 2011)
- "_Beyond Clicks: Dwell Time for Personalization_"(Yi et al; 2014)

Aún asi se logra capturar lo escencial de este balance, cosa que es mencionada en estos trabajos tambien: "implicito es rápido de obtener pero hay que tratarlos con cuidado, explicito es dificil de obtener pero aporta mucho más y de manera confiable."

Un último punto que me gustaría rescatar, es que se hace mención de que hay ciertos items que a uno le gustaría no recomendar; ya sea porque el usuario ya lo adquirió, porque no está disponible o porque es un tipo de item que podría generar problemas al recomendar ("items para adultos" se menciona). Y, a pesar que es natural y aveces obvio, no siempre se hace este contrapunto y sería interesante encontrar los diferentes métodos que sea han usado para tratar con elementos a no-recomendar.

Finalmente, este artículo permite dar una primera visión de lo que sería el mundo de la recomendación basada en contenido, donde muchas técnicas serían más cercanas a lo que hoy se conoce como "clusterización" de items similares. Este enfoque sería muy distinto al filtrado colaborativo que se suele ver en primeras instancias, razón por la cuál me tomó un tiempo en comprender cuál era el enfoque, pero una vez me di cuenta del cambio, me pareció sumamente interesante cómo lo abordaban.
