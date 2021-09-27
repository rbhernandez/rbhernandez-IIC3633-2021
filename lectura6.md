# Deep Learning based Recommender System: A Survey and New Perspectives

En esta lectura se expone una *survey* realizada sobre los sistemas de recomendación basados en *Deep Learning*. Las diversas arquitecturas de *Deep Neural* son utilizadas en recomendación debido a dos atributos principales: (1) corresponde a un proceso *end-to-end*  y (2) proporciona sesgos inductivos adecuados según el tipo de datos de *input*. Además, a lo largo del texto se detallan más atributos y limitaciones de su aplicación en sistemas recomendadores y también se explica su diferenciación en dos categorías: *Recommendation with Neural Building Blocks* y *Recommendation with Deep Hybrid Model*s. Luego, se menciona cada una de las *Deep Learning Techniques* en un apartado propio, donde se muestran modelos en los que son combinadas con otros algoritmos de recomendación, como los que hemos estudiado en lecturas anteriores, y se justifica el uso de ellas de acuerdo a sus características y definición matemática. 

Una de las cosas que más llama mi atención es la característica *end-to-end* que se resalta del uso de *Deep learning*, porque ésta hace referencia a que la composición  de las *Deep neural networks* como una única función diferenciable, permiten este comportamiento en que el modelo "hace todo el trabajo", es decir, no es necesario realizar pasos intermedios o previos (preprocesamiento, por ejemplo), para poder obtener el resultado esperado. Esto es interesante porque describe de alguna manera cómo incluso en materia de computación (Sistemas Recomendadores) se busca la automatización de los procesos. En este caso, se quiere hacer una recomendación con mayor eficiencia y menos trabajo manual, lo cual es posible al utilizar *Deep Learning* en modelos de recomendación.

Siguiendo con lo anterior, quiero destacar una frase de la lectura que dice:

> *In today´s research climate there is completely no reason to not used deep learning based tools for development of any recommender system.*

Esto porque es claro que así como no hay razón para no querer automatizar distintos procesos  que realizamos las personas, no hay razón para no incluir *Deep Learning* y poder utilizar *inputs* de datos en distintas representaciones y sin restricciones, para poder hacer recomendaciones a usuarios en múltiples plataformas.

Otra cosa que llamó mi atención es que se muestra como una limitación del uso de *Deep Learning* en modelos de recomendación, que esta técnica es *"data-hungry"*. Debido a que a lo largo del curso, hemos visto cómo los algoritmos de recomendación se ven afectados por problemas como el *cold start* y la *sparsity* de los datos, por lo que podemos observar que aún cuando *Deep Learning* se muestra como un complemento poderoso para los modelos de recomendación, este tipo de problemas sigue haciendo ruido y motiva mi interés por leer sobre el estado actual en *research* sobre esta temática e incluso por investigarlo por mi propia cuenta.

Finalmente, hay que destacar la estrechez que puede haber entre dos disciplinas que se estudian de manera independiente y lo positivo que es que se puedan potenciar entre ambas. Esto también se había visto en otras lecturas con disciplinas como *NLP* y Sistemas recomendadores y se sigue descubriendo cada vez que leemos sobre una nueva técnica de recomendación. Lo cual es muy motivante puesto que permite afirmar que todas las disciplinas del área de la computación tienen la posibilidad de complementarse en algún punto y permitir que en conjunto nos lleven a nuevos descubrimientos dentro de esta ciencia. 