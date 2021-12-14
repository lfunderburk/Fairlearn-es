# Fairlearn en Español

Traducción de documentación del paquete de Python: Fairlearn.

# Fairlearn
Fairlearn es un paquete de Python que permite a los desarrolladores de sistemas de inteligencia artificial (IA) evaluar la equidad de su sistema y mitigar cualquier problema de injusticia observado. Fairlearn contiene algoritmos de mitigación y métricas para la evaluación del modelo. Además del código fuente, este repositorio también contiene cuadernos de Jupyter con ejemplos del uso de Fairlearn.

Sitio web: https://fairlearn.org/

Lanzamiento actual
Lo que queremos decir con * justicia *
Descripción general de Fairlearn
Métricas de Fairlearn
Algoritmos Fairlearn
Instalar Fairlearn
Uso
Contribuyendo
Mantenedores
Asuntos

## Lanzamiento actual

* La versión estable actual está disponible en [PyPI](https://pypi.org/project/fairlearn/).

* Nuestra versión actual puede diferir sustancialmente de las versiones anteriores. Los usuarios de versiones anteriores deben visitar nuestra [guía de versiones](https://fairlearn.org/main/user_guide/installation_and_version_guide/version_guide.html) para explorar cambios significativos y encontrar información sobre cómo migrar.


## ¿Qué entendemos por *equidad*?

Un sistema de inteligencia artificial puede comportarse de manera injusta por diversas razones. En Fairlearn, definimos si un sistema de IA se comporta de manera injusta en términos de su impacto en las personas, es decir, en términos de daños. Nos centramos en dos tipos de daños:

* *Daños por asignación*. Estos daños pueden ocurrir cuando los sistemas de inteligencia artificial amplían o retienen oportunidades, recursos o información. Algunas de las aplicaciones clave se encuentran en la contratación, las admisiones escolares y los préstamos.

* *Daños a la calidad del servicio*. La calidad del servicio se refiere a si un sistema funciona tan bien para una persona como para otra, incluso si no se brindan o retienen oportunidades, recursos o información.
* 
Seguimos el enfoque conocido como **equidad grupal**, que pregunta: *¿Qué grupos de personas corren el riesgo de sufrir daños?* Los grupos relevantes deben ser especificados por el científico de datos y son específicos de la aplicación.

La equidad grupal se formaliza mediante un conjunto de restricciones, que requieren que algunos aspectos (o aspectos) del comportamiento del sistema de IA sean comparables entre los grupos. El paquete Fairlearn permite la evaluación y mitigación de la injusticia bajo varias definiciones comunes. Para obtener más información sobre nuestras definiciones de equidad, visite nuestra [guía del usuario sobre Equidad de los sistemas de inteligencia artificial](https://fairlearn.org/main/user_guide/fairness_in_machine_learning.html#fairness-of-ai-systems).

> Nota: La equidad es fundamentalmente un desafío sociotécnico. Muchos aspectos de la equidad, como la justicia y el debido proceso, no son capturados por métricas cuantitativas de equidad. Además, hay muchas métricas de equidad cuantitativa que no pueden satisfacerse todas simultáneamente. Nuestro objetivo es permitir que los humanos evalúen diferentes estrategias de mitigación y luego hagan concesiones apropiadas a su escenario.

## Descripción general de Fairlearn

El paquete Fairlearn Python tiene dos componentes:

Métricas para evaluar qué grupos se ven afectados negativamente por un modelo y para comparar varios modelos en términos de diversas métricas de equidad y precisión.
Algoritmos para mitigar la injusticia en una variedad de tareas de IA y en una variedad de definiciones de equidad.
Métricas de Fairlearn
Consulte nuestra guía detallada sobre las métricas de Fairlearn.

Algoritmos Fairlearn
Para obtener una descripción general de nuestros algoritmos, consulte nuestro sitio web.

Instalar Fairlearn
Para obtener instrucciones sobre cómo instalar Fairlearn, consulte nuestra guía de inicio rápido.

Uso
Para el uso común, consulte los portátiles Jupyter y nuestra guía del usuario. Tenga en cuenta que nuestras API están sujetas a cambios, por lo que los portátiles descargados de main pueden no ser compatibles con Fairlearn instalado con pip. En este caso, navegue por las etiquetas en el repositorio (por ejemplo, v0.7.0) para ubicar la versión apropiada del portátil.

Contribuyendo
Para contribuir, consulte nuestra guía para colaboradores.

Mantenedores
En nuestro sitio web encontrará una lista de los mantenedores actuales.

Asuntos
Preguntas de uso
Haga preguntas y ayude a responderlas en Stack Overflow con la etiqueta fairlearn o en Discord.

Problemas habituales (no relacionados con la seguridad)
Los problemas están pensados ​​para errores, solicitudes de funciones y mejoras en la documentación. Envíe un informe a través de problemas de GitHub. Un mantenedor responderá con prontitud según corresponda.

Los encargados del mantenimiento intentarán vincular los problemas duplicados cuando sea posible.

Informar problemas de seguridad
Para informar problemas de seguridad, envíe un correo electrónico a fairlearn-internal@python.org.
