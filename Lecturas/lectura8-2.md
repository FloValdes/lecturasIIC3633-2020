## Comentario: See What You Want to See: Visual User-Driven Approach for Hybrid Recommendation

Este paper presenta a SetFusion, una manera visual de representar ensambles de recomendaciones. Se realizaron dos experimentos para probar la interacción de los usuarios con SetFusion. En el primer experimento se pudo concluir que hubo una leve mejoría de participación y uso del sistema recomendador cuando se utilizaba SetFusion versus cuando solo se mostraban las recomendaciones como lista. En el segundo experimento se realizó en condiciones más naturales (los usuarios podían interactuar libremente) y se concluyó que los usuarios utilizaban y aprovechaban de mejor manera el recomendador cuando estaban en estas condiciones naturales.

Una primera crítica a este paper es que no explicitan las diferencias entre ambos experimentos. Nombran que las condiciones eran más 'naturales', que dejaron a los usuarios interactuar libremente con el sistema y que no les hicieron un cuestionario previamente, pero no se explicita claramente qué son estas condiciones naturales. Por otro lado, también nombran, sin darle mucha atención, que cambiaron los algoritmos de recomendación entre ambos experimentos, así que es posible que más cosas hayan cambiado. 

Relacionado a lo anterior, la conclusión que saca el paper es que los usuarios interactúan mejor con el sistema recomendador en condiciones naturales. Sin embargo, como cambiaron los algoritmos, estas condiciones naturales no fueron las únicas cosas que variaron entre ambos experimentos, así que ¿cómo se puede concluir que la mejoría solo se atribuye a este cambio de condiciones y no quizás a un cambio de algoritmo o a otro cambio no especificado?

Por último me parece que el paper se enfoca en dos cosas diferentes sin mucha relación entre sí. Por una parte, especialmente en el principio del paper, proponen este nuevo método de representar recomendaciones llamado SetFusion. Describen en qué consiste, cómo se interactúa con él, etc. Esto podría sugerir que van a experimentar sobre la efectividad de este método propuesto, comparándolo con el estado del arte o con alguna otra técnica. Sin embargo, los resultados que apuntaban a que esta visualización era más efectiva se omitieron por falta de espacio, en favor de otros resultados. Estos otros resultados tienen poco que ver con SetFusion en sí, y apuntan más a una comparación entre testear usuarios en condiciones de laboratorio o testearlos en condiciones naturales. La parte de resultados y conclusiones se centra en esto, en cómo el segundo experimento fue más exitoso que el primero, pero esta comparación no tiene ninguna relevancia para conocer qué tan efectivo es SetFusion. De esta forma el paper se puede dividir en dos mitades que no encajan muy bien entre sí: la primera propone un nuevo método de visualización de recomendaciones, la segunda concluye que experimentos con condiciones naturales son mejores que experimentos con condiciones de laboratorio.

En conclusión, este paper presenta una novedosa forma de visualizar fusiones de recomendaciones, pero lamentablemente omite por falta de espacio la justificación experimental de por qué esta forma funciona. En su lugar, el paper se enfoca en presentar datos que apoyan la conclusión de que testear en forma 'natural' produce mejores resultados que otros experimentos. No queda claro cuál es la relación entre esta conclusión y SetFusion, y tampoco se explicita las condiciones que cambiaron entre ambos experimentos para poder sacar mejores conclusiones de la realización de experimentos. 