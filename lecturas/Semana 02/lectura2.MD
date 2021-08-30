# Matrix Factorization Techniques for Recommender Systems (2009)

## Koren, Y., Bell, R., & Volinsky, C.

En general se nota un antes y un después de los casos de éxito de _Amazon_ y _Netflix Prize_, cómo marcaron un precedente para nuevos métodos y maneras de promover encontrar nuevos métodos.

En lo que respecta a lo visual, no me gustó el diseño del documento: la dispocisión de texto, los colores usados, etc. Pero siento que tiene una buena arquitectura narrativa, excepto quizá por la sección en la que cuentan su participación por el Netflix Prize, me hubiese sido más natural si lo hubiesen dejado como una introducción o contextualización, aunque también es entendible si lo dejaron como una suerte de "resultados".

Particularmente me incomodó un poco que para la normalización, en la sección de "_Additional Input Sources_" aparezcan, números en las fórmulas sin mayor explicación, como la potencia a (4,5), o porqué dividir por la raíz de la cardinalidad del conjunto. Además, me pareció poco apropiado que en la parte de _embeddings_ hayan puesto lo de "interpretabilidad" de los vectores latentes. Así como pasa con el PCR, es altamente probable que una dimensión resultante sea combinación de más de una dimensión original. Por lo que, al intentar interpretar un vector latente se estaría subestimando su verdadero poder.

Finalmente, y a pesar de los puntos negativos mencionados, me quedó mucho más clara la relevancia que tienen (o tuvieron) los métodos de factorización matricial. Que no es solo abstraer y "conseguir que items y usuarios tengan la misma dimension de representación", si no que permite mucha mayor flexibilidad a la hora de intentar mejores modelados (considerando _bias_ de distintas formas), permite regularizadores y métodos iterativos, entre otras cosas. Lo que abre todo un nuevo mundo a los métodos a usar
