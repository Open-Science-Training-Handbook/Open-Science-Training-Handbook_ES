## <img src="/Images/Icons/reuse.png" width="200" height="200" /> <img src="/Images/Icons/research.png" width="200" height="200" />

## 4. Investigación Reproducible y Análisis de Datos

### ¿En qué consiste?

Reproducibilidad significa que los datos y el código de investigación estén disponibles de formaque otros sena capaces de obtener los mismos resultados declarados en productos científicos. Intimamente relacionado está el concepto de replicabilidad, el acto de repetir una metodología científica con el objetivo de alcanzar conclusiones similares. Estos conceptos son elementos centrales de la investigación empírica. 

Mejorar la reproducibilidad conlleva a aumentar el rigor y la calidad de los productos científicos, y por tanto, a una mayor confianza en la ciencia. Existe una creciente necesidad y deseo de exponer los flujos de trabajo de la investigació desde el inicio de un proyecto y la recolección de datos, hasta la interpretación y el reporte de resultados. Estos desarrollos han traido sus propio grupo de desafíos, incluyendo el diseño de flujos de trabajo integrado que pueden ser adoptados por colaboradores, al mismo manteniendo altos estándares de integridad. 

El concepto de reproducibilidad es directamente aplicado al método científico, la piegra angular de la Ciencia, y particularlmente en los siguientes cinco pasos: 

1. Formulación de la hipótesis 

2. Diseño del estudio 

3. Realizar el estudio y recolectar datos 

4. Análisis de datos 

5. Reporte del estudio 

Cada uno de estos pasos debe ser claramente reportado al proveer documentación clara y abierta, y por tanto hacer que el estudio sea transparente y reproducible. 

![](/Images/02 Open Science Basics/02_reproducible_research_data_analysis.png)

### Justificación

Los factores dominantes pueden contribuir mayormente a las causas de no-reproducibilidad, pero también pueden impulsar la implementación de medidas específicas para abordar estas causas. La cultura y el ambiente en que la investigación se desarrolla es un factor dominante 'top-down' importante. Desde una perspectiva 'bottom-up', continuar educando y capacitando a los investigadores con el fin de crear conciencia y diseminar buenas prácticas. 

Aunque entendemos que el amplio rango de factores que contribuyen a la reproducibilidad es importante, también puede ser difícil romper con estos factores en distintas etapas que pueden inmediatamente mejorar su reproducibilidad. Uno de los primeros pasos a seguir es evaluar el estado actual, y monitorear las mejoras a medida que se avanza para aumentar aún más la reproducibilidad. Algunos de los temas más comunes relacionados con la reproducibilidad de la investigación se muestran en la siguiente figura. 

![](/Images/image_2.png)

Fuente: [Reproducibilidad y confiabilidad de la investigación biomédica: mejorando la práctica de investigación](https://acmedsci.ac.uk/viewFile/56314e40aac61.pdf).

Goodman, Fanelli, & Ioannidis \(2016\) mencionan que en epidemiología, biología computacional, economía y ensayos clínicos, la reproducibilidad comunmente se define como:

_la habilidad de un investigador de duplicar los resultados de un estudio previo utilizando los mismos materiales que fueron utilziados por el investigador original. Esto es, un segundo investigador puede utilizar los mismos datos crudos para construir los mismos archivos de análisis e implementar el mismo análisis estadístico en un intento de lograr los mismos resultados._

Se distingue de la replicabilidad:

_que se refiere a la abilidad de un investigador de duplicar los resultados de un estudio previo si los mismos procedimientos son seguidos pero se colectan datos nuevos._

Una manera más simple de pensar en esto puede ser que la reproducibilidad está orientada a los métodos, mientras que la replicabilidad está orientada a los resultados. 

La reproducibilidad puede ser evaluada a distintos niveles: a nivel de proyectos individuales \(ej. publicaciones, experimento, método o un set de datos\), un investigador individual, un laboratorio o grupo de investigación, una institución, o incluso un área de investigación. Levemente distintos tipos de criterios y puntos de evaluación pueden aplicar a estos disntitos niveles. Por ejemplo, una institución sostiene prácticas de reproducibilidad si se instauran políticas que recompensan a los investigadores que desarrollan investigación reproducible. Por otro lado, un área de investigación puede considerarse con un mayor nivel de reproducibilidad si desarrolla recursos mantenidos por una comunidad que promueven y permiten prácticas de investigación reproducible, como repositorios de datos, o estándares comunes para compartir datos. 

## <img src="/Images/Icons/finish.png" width="150" height="150" />
### Objetivos de aprendizaje

Hay tres objetivos principalesque necesitar ser abordados aquí:

1. Entender el importante impacto de crear investigación reproducible.

2. Entender completamente la organización de investigación reproducible  \(incluyendo el diseño del flujo de trabajo, la gestión de datos y reporte dinámico\).

3. Ser conciente de las etapas individuales en el proceso de reproducibilidad, así como los recursos correspondientes que pueden ser utilizados. 

### Componentes principales 

## <img src="/Images/Icons/brain.png" width="150" height="150" />
#### Conocimiento 

Lo que sigue es una lista indicativa de eseñanzas sobre reproducibilidad: 

* Qué es la 'crisis de reproducibilidad', y meta-análisis de reproducibilidad. 

* Principios de reproducibilidad, e integridad y éticas de investigación. 

* Cuáles son las opciones y ambientes computacionales que permiten colaboraciones y arreglos reproducibles. 

* Factores que afectan la reproducibilidad de la investigación. 

* Documentación del análisis de datos y flujos de trabajo abiertos. 

* Ambientes de análisis reproducible \(virtualización\).

* Abordar los "Grados de libertad de la investigación" \(Wicherts et al., 2016\).

## <img src="/Images/Icons/gears.png" width="150" height="150" />
#### Habilidades

Hay distintos consejos prácticos sobre reproducibilidad que se deben tener en cuenta cuando se dispone de las habilidades necesarias para asegurarla. Las mejores prácticas en reproducibilidad provienen de las prácticas de Ciencia Abierta más generales, pero su integración ofrece beneficios a los investigadores individuales, tanto si deciden compartir su investigación o no. La razón porla cual la integración de las mejores práctics de reproducibilidad beneficia al investigador individual es que mejoran la planificación, organización, y documentación de la investigación. En los párrafos siguientes describimos un ejemplo de implementación de reproducibilidad en un flujo de investigación con referencia a prácticas descritas en el manual. 

## <img src="/Images/Icons/task.png" width="150" height="150" />
##### **1. Planifica para la reproducibilidad antes de empezar **

###### Crea un plan de estudio o protocolo.

Comienza documentando el comienzo de un estudio escribiendoo un plan de estudio o protocolo que incluya los métodos y el diseño del estudio propuesto. Usa las directrices de reporte de [Equator Network](http://www.equator-network.org/) si aplican. Registra los cambios en tu plan de estudios o protocolos utilizando control de versiones \(referencia a controlde versiones \). Calcula el poder o tamaño de muestra y reporta este cálculo en tu protocolo, dado que estudios de bajo poder estadístico son suceptibles a irresproducibilidad. 

###### Elige herramientas y materiales reproducibles 

Selecciona anticuerpos que funcionen utilizando un buscador de anticuerpos como [CiteAb](https://www.citeab.com/). Evita irreproducibilidad debido a líneas de celdas mal identificadas eligiendo aquellas que están autenticidad por el [Comité Internacional de Autenticación de Líneas Celulares](http://iclac.org/). Cuando sea posible, elige herramientas de software y hardware en las cuales puedas mantener propiedad  de tu investigación, y que puedan migrar tu investigación fuera de la plataforma para reutilización \(ver Software de Investigación Abierto y de código abierto\).

###### Organizar un proyecto reproducible 

Centraliza y organiza la gestión del proyecto utilizando una plataforma online, como un repositorio central, o una carpeta para todos los archivos asociados. Puedes usar GitHub como un lugar para almacenar los archivos del proyecto o gestionar todo utilizando un cuaderno de laboratorio electrónico como [Benchling](https://benchling.com/), [Labguru](https://www.labguru.com/),o [SciNote](https://scinote.net/). Dentro de tu proyecto centralizado, sigue las mejores prácticas separando tus datos de tu código en distintas carpetas. Haz que tus datos crudos sean sólo lectura y mantenlos separados de los datos procesados \(referencia a Gestión de Datos\).

Cuando guardes y respaldes de tus archivos de investigación, elige formatos y nombres de archivos informativos que permitan la reutilización. Los nombres de archivo deben ser legibles tanto para máquinas como para humanos \(referencia a Gestión de Datos\). En tu análisis y código de software, usa caminos relativos.  Evita archivos en formatos cerrados y utiliza formatos abiertos \(ver 6 Licencias abiertas y formatos de archivo\).

## <img src="/Images/Icons/handson.png" width="150" height="150" />
##### **2. Mantén registros de las cosas**

###### REgistro

Preregistra aquellos diseños de estudio importantes e información de análisis para aumentar la transparencia y contrarrestrar los sesgos de publicación de resultados negativos. Algunas herramientas libres que te ayudarán a realizar tu primer registro incluyen  [AsPredicted](https://aspredicted.org/), [Open Science Framework](https://osf.io/), y [Registered Reports](https://cos.io/rr/). Los ensayos clínicos deben utilizar [Clinicaltrials.gov](https://clinicaltrials.gov/).

###### Control de versión

Registra los cambios en tus archivos, especialmente en tu código de análisis, utilizando control de versión \(ver Software de Investigación Abierta y de código abierto\).

###### Documentación

Documenta todo lo hecho a mano en un archivo README. Crea un diccionario de datos \(también conocido como libro de código\) para describir la información importante acerca de tus datos. Una introducción fácil a este tema puede ser encontrada en [el módulo sobre organización de datos de Karl Broman](http://kbroman.org/dataorg/pages/dictionary.html) y refiérete a gestión de datos. 

###### Programación literaria

Considera utilizar [Jupyter Notebooks](http://jupyter.org/), [KnitR](https://yihui.name/knitr/), [Sweave](https://support.rstudio.com/hc/en-us/articles/200552056-Using-Sweave-and-knitr), u otras aproximaciones a la programación literal para integrar tu código con tus narrativas y documentación. 

## <img src="/Images/Icons/open_licenses.png" width="150" height="150" />
##### 3**. Comparte y licencia tu investigación**

###### Datos

Evita archivos suplementarios, decide utilizar una licencia permisiva, y comparte tus datos utilizando un repositorio de datos. Sigue las mejores prácticas como se indican el capítulo de Datos y materiales abiertos de Investigación.

###### Materiales

Comparte tus materiales de forma que puedan ser reutilizados. Deposita los reactivos en repositorios como [Addgene](https://www.addgene.org/), [The Bloomington Drosophila Stock Center](https://bdsc.indiana.edu/), y [ATCC](https://www.atcc.org/) para hacerlo fácilmente asequible a otros investigadores. Para mayor información, ver la subsección de Materiales Abiertos de Datos y Materiales Abiertos. 

###### Software, cuadernos y contenedores

Licencia tu código para informar cómo puede ser \(re\)utilizado. Compartir cuadernos con servicios como  [mybinder](http://mybinder.org) que permiten la vista y ejecución pública de recursos compartidos. Compartir contenedores o cuadernos con servicios como [Rocker](https://arxiv.org/abs/1710.03675) o [Code Ocean](https://codeocean.com/). Sigue las mejores prácticas indicadas en Software de Investigación Abierta y de código abierto.

## <img src="/Images/Icons/open_scholarship.png" width="150" height="150" />
##### 4**. Reporta tu investigación transparentemente**

Reporta y publica tus métodos e intervenciones explícita y transparentemente y permitiendo reproducción completa. Las guías de la [Equator Network](http://www.equator-network.org/), herramientas como [Protocols.io](https://www.protocols.io/), o procesos como [Registered Reports](https://cos.io/rr/) pueden ayudar a reportar reproducibilidad. Recuerda publicar tus resultados en una plataforma de registro público \(como [ClinicalTrials.gov](https://www.socialscienceregistry.org/) o el  [SocialScienceRegistry](https://www.socialscienceregistry.org/)\) dentro del año de terminado tu estudio, sin importar la naturaleza o dirección de tus resultados. 

## <img src="/Images/Icons/questions.png" width="150" height="150" />
### Preguntas, obstáculos y concepciones erróneas comunes 

Q: "Todo está en el papel; cualquiera puede reproducirlo desde aquí!"

A: Esta es una de las concepciones erróneas más comunes. Incluso si se cuenta con una descripción extremadamente detallada de los métodos y flujos de trabajo empleados para alcanzar el resultado final, esto no será suficiente en muchos casos para reproducirla. Esto puede deberse a distintos aspectos, incluyendo uso de  distintos ambientes computacionales, diferencias en la versión de software, sesgos implícitos que no fueron claramente declarados, etc. 

Q: "No tengo el tiempo para aprender y establecer un flujo de trabajo reproducible."

A: En adición al número significativo de servicios libres disponibles en línea que pueden ser combinados y facilitan la organización de un flujo de trabajo completo, el tiempo y el esfuerzo dedicado a organizar esto aumentará tanto la validez científica de los resultados finales así como minimizar el tiempo de re-marcha (re-running) o extenderlo en estudios posteriores. 

Q: "Las terminologías que describen la reproducibilidad son desafiantes."

A: Ver Barba \(2018\) para una discusión sobre la terminología que describe reproducibilidad y repetibilidad 

## <img src="/Images/Icons/output.png" width="150" height="150" />
### Resultados de aprendizaje

1. Entender la necesidad de investigación reproducible y su razonamiento. 

2. Ser capaz de establecer un flujo de trabajo reproducible en el contexto de una tarea ejemplo. 

3. Conocer herramientas que puedan ayudar a la investigación reproducible. 

## <img src="/Images/Icons/magnifying_glass.png" width="150" height="150" />
### Bibliografía recomendada

* Calcula tu poder: [Button et al. \(2013\) study of the relationship between reproducibility and power.](https://www.nature.com/articles/nrn3475)

* Nominación informativa: [Karl Broman’s Data Organization module: Choose good names for things](http://kbroman.org/dataorg/pages/names.html)


