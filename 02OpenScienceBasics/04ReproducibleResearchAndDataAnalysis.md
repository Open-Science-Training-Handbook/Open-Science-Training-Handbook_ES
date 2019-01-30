## <img src="/Images/Icons/reuse.png" width="200" height="200" /> <img src="/Images/Icons/research.png" width="200" height="200" />

## 4. Investigación reproducible y análisis de datos

### ¿En qué consiste?

Reproducibilidad significa que los datos y el código de investigación están disponibles para que otros sean capaces de obtener los mismos resultados que se exponen en los trabajos publicados. Este concepto está íntimamente relacionado con el de replicabilidad, el acto de repetir una metodología científica con el objetivo de alcanzar conclusiones similares. Estos conceptos son elementos centrales de la investigación empírica.

Mejorar la reproducibilidad conduce a aumentar el rigor y la calidad de los trabajos científicos y, por tanto, a una mayor confianza en la ciencia. Existe una creciente necesidad y deseo de exponer los flujos de trabajo de la investigación desde el comienzo de un proyecto y la recolección de datos, hasta la interpretación y el informe  de los resultados. Estos desarrollos presentan desafíos propios, que incluyen el diseño de flujos de trabajo integrados que pueden ser adoptados por los colaboradores a la vez que se mantienen altos estándares de integridad.

El concepto de reproducibilidad se aplica directamente al método científico, la piedra angular de la ciencia, y particularmente a los siguientes cinco fases:

1. Formulación de la hipótesis

2. Diseño del estudio

3. Realización del estudio y recolección de datos

4. Análisis de datos

5.Informe del estudio

Cada uno de estos pasos debe estar informado con claridad,  con una  documentación clara y accesible, que faciltie la transparencia y la reproducibilidad del estudio.

![](/Images/02%20Open%20Science%20Basics/02_reproducible_research_data_analysis.png)

### Justificación

Los factores generales pueden contribuir a las causas de no-reproducibilidad, pero también pueden impulsar la implementación de medidas específicas para abordar dichas causas. La cultura y el ambiente en que se desarrolla la investigación son factores generales de  'arriba-abajo' importantes. Desde una perspectiva 'abajo-arriba', la educación y capacitación continuas de los investigadores pueden crear conciencia y diseminar buenas prácticas.

Aunque entender el amplio rango de factores que contribuyen a la reproducibilidad es importante, también puede ser difícil desglosar estos factores en medidas que puedan ser adoptadas inmediatamente en programas de investigación ya existentes para mejorar inmediatamente su reproducibilidad. Uno de los primeros pasos a seguir es evaluar el estado actual de las cosas y monitorear las mejoras a medida que toman decisiones para aumentar aún más la reproducibilidad. Algunos de los temas más comunes relacionados con la reproducibilidad de la investigación se muestran en la siguiente figura.

![](/Images/image_2.png)

Fuente: [Reproducibilidad y confiabilidad de la investigación biomédica: mejorando la práctica de la investigación](https://acmedsci.ac.uk/viewFile/56314e40aac61.pdf).

Goodman, Fanelli, & Ioannidis \(2016\) mencionan que en epidemiología, biología computacional, economía y ensayos clínicos, la reproducibilidad comúnmente se define como:

_La habilidad de un investigador de duplicar los resultados de un estudio previo utilizando los mismos materiales que fueron utilizados por el investigador original. Esto es, un segundo investigador puede utilizar los mismos datos primarios para generar los mismos archivos resultado de su análisis e implementar el mismo análisis estadístico en un intento de alcanzar los mismos resultados._

Esto es distinto de  la replicabilidad: "que se refiere a la habilidad de un investigador para duplicar los resultados de un estudio previo si se siguen los mismos procedimientos pero recolectando datos nuevos". Una manera simple de distinguir un concepto de otro,  es orientar  la  reproducibilidad  a los métodos, mientras que la replicabilidad está orientada a los resultados.

La reproducibilidad puede ser evaluada a diferentes niveles: a nivel de proyecto individual \(por ej., un artículo, un experimento, un método o un set de datos\), de un investigador individual, a un laboratorio o grupo de investigación, a una institución o incluso una disciplina. A cada uno de estos diferentes niveles podrían aplicarse distintos tipos de criterios y puntos de evaluación levemente diferentes. Por ejemplo, una institución apoya las prácticas de reproducibilidad si establece políticas que recompensan a los investigadores que desarrollan investigaciones de modo reproducible. Por otro lado, se puede considerar que un campo de investigación posee un mayor nivel de reproducibilidad si desarrolla recursos que promueven y permiten prácticas de investigación reproducible mantenidos por la comunidad, como repositorios de datos o estándares comunes para el intercambio de datos.

## <img src="/Images/Icons/finish.png" width="150" height="150" />
### Objetivos de aprendizaje

Hay tres objetivos principales que deben ser abordados aquí:

1. Entender el impacto importante de crear investigaciones reproducibles.

2. Entender la organización global de la investigación reproducible \(incluyendo el diseño del flujo de trabajo, la gestión de datos y el reporte dinámico\).

3. Ser consciente de las etapas individuales del proceso de reproducibilidad y de los recursos correspondientes que pueden ser utilizados.

### Componentes principales

## <img src="/Images/Icons/brain.png" width="150" height="150" />
#### Conocimiento

La siguiente es una lista indicativa de aportes sobre la reproducibilidad:

* Qué son la 'crisis de reproducibilidad' y el meta-análisis de la reproducibilidad.

* Principios de reproducibilidad e integridad y ética de la investigación.

* Cuáles son las opciones y ambientes computacionales que permiten estructuras colaborativas y reproducibles.

* Factores que afectan a la reproducibilidad de la investigación.

* Documentación del análisis de datos y flujos de trabajo abiertos.

* Ambientes de análisis reproducible \(virtualización\).

* Abordaje de los "grados de libertad del investigador" \(Wicherts et al., 2016\).

## <img src="/Images/Icons/gears.png" width="150" height="150" />
#### Habilidades

Hay distintos consejos prácticos sobre reproducibilidad que se deben tener en cuenta cuando se planifican las habilidades necesarias para asegurarla. Las mejores prácticas en reproducibilidad se nutren, generalmente, de las prácticas de Ciencia Abierta, pero su integración ofrece beneficios a los investigadores individuales tanto si deciden compartir su investigación como si no lo hacen. La razón por la cual la integración de las mejores prácticas de reproducibilidad beneficia al investigador individual es que ellas mejoran la planificación, organización y documentación de la investigación. Más abajo presentamos un ejemplo de implementación de reproducibilidad en un flujo de investigación con referencias a estas prácticas en el manual.

## <img src="/Images/Icons/task.png" width="150" height="150" />
##### **1. Plan para la reproducibilidad antes de empezar**

###### Crea un plan de estudio o protocolo.

Comienza la documentación desde el inicio de un estudio escribiendo un plan de estudio o protocolo que incluya el diseño y los métodos propuestos. Usa la guía directriz para el reporte de [Equator Network](http://www.equator-network.org/) si aplica. Haz un seguimiento de los cambios en tu plan de estudio o protocolo utilizando el control de versiones \(referencia a Control de versiones \). Calcula el poder o tamaño de muestra necesario y reporta este cálculo en tu protocolo, dado que los estudios de bajo poder estadístico son proclives a la irreproducibilidad.

###### Elige herramientas y materiales reproducibles

Selecciona anticuerpos que funcionen utilizando un buscador de anticuerpos como [CiteAb](https://www.citeab.com/). Evita la irreproducibilidad causada por las líneas celulares mal identificadas eligiendo aquellas que están autenticadas por el [Comité Internacional de Autenticación de Líneas Celulares](http://iclac.org/). Cuando sea posible elige herramientas de software y hardware con las que puedas mantener la propiedad de tu investigación y que puedan migrar tu investigación fuera de la plataforma para su reutilización \(ver Software de investigación abierto y Código Abierto\).

###### Organiza un proyecto reproducible

Centraliza y organiza la gestión de tu proyecto utilizando una plataforma online, un repositorio central o una carpeta para todos los archivos de investigación. Podrías usar GitHub como sitio para almacenar los archivos del proyecto, o bien gestionar todo utilizando un cuaderno de laboratorio electrónico como [Benchling](https://benchling.com/), [Labguru](https://www.labguru.com/),o [SciNote](https://scinote.net/). Dentro de tu proyecto centralizado sigue las mejores prácticas separando tus datos y tu código en distintas carpetas. Haz que tus datos primarios sean de sólo lectura y mantenlos separados de los datos procesados \(referencia a Gestión de datos\).

Cuando guardes y respaldes tus archivos de investigación, elige formatos y nombres de archivo informativos, que permitan su reutilización. Los nombres de archivo deben ser legibles tanto por máquinas como por humanos \(referencia a Gestión de datos\). Para tus análisis y código de software usa directorios relativos. Evita archivos con formatos cerrados; utiliza formatos abiertos \(ver 6 Licencias abiertas y formatos de archivo\).

## <img src="/Images/Icons/handson.png" width="150" height="150" />
##### **2. Haz un seguimiento de las cosas**

###### Registro

Pre-registra la información importante vinculada con el diseño de la investigación y el análisis para aumentar la transparencia y contrarrestrar los sesgos de publicación de resultados negativos. Algunas herramientas libres que te ayudarán a realizar tu primer registro son [AsPredicted](https://aspredicted.org/), [Open Science Framework](https://osf.io/), y [Registered Reports](https://cos.io/rr/). Los ensayos clínicos deben utilizar [Clinicaltrials.gov](https://clinicaltrials.gov/).

###### Control de versiones

Haz un seguimiento de los cambios en tus archivos, especialmente en tu código de análisis, utilizando el control de versiones \(ver Software de investigación abierto y Código Abierto\).

###### Documentación

Documenta todo lo que hubiera sido hecho a mano en un archivo README. Crea un diccionario de datos \(también conocido como libro de código\) para describir la información importante acerca de tus datos. Una introducción fácil a este tema es [el módulo sobre organización de datos de Karl Broman](http://kbroman.org/dataorg/pages/dictionary.html). Refiere también al apartado sobre Gestión de datos.

###### Programación literaria

Considera utilizar [Jupyter Notebooks](http://jupyter.org/), [KnitR](https://yihui.name/knitr/), [Sweave](https://support.rstudio.com/hc/en-us/articles/200552056-Using-Sweave-and-knitr), u otras aproximaciones a la programación literaria para integrar tu código con tu narrativa y documentación.

## <img src="/Images/Icons/open_licenses.png" width="150" height="150" />
##### **3. Comparte y licencia tu investigación**

###### Datos

Evita archivos suplementarios, decide utilizar una licencia permisiva y comparte tus datos utilizando un repositorio. Sigue las mejores prácticas tal como se indican en el capítulo de Datos y materiales abiertos de investigación.

###### Materiales

Comparte tus materiales de modo que puedan ser reutilizados. Deposita los reactivos en repositorios como [Addgene](https://www.addgene.org/), [The Bloomington Drosophila Stock Center](https://bdsc.indiana.edu/), y [ATCC](https://www.atcc.org/) para hacer que sean fácilmente accesibles para otros investigadores. Para mayor información, mira la subsección de Datos y materiales de investigación abiertos.

###### Software, cuadernos de notas y contenedores

Licencia tu código para informar cómo puede ser \(re\)utilizado. Comparte cuadernos con servicios como [mybinder](http://mybinder.org), que permiten la vista y ejecución pública de cuadernos de notas completos que hubieran sido compartidos. Comparte contenedores o cuadernos con servicios como [Rocker](https://arxiv.org/abs/1710.03675) o [Code Ocean](https://codeocean.com/). Sigue las mejores prácticas indicadas en Software de investigación abierto y Código Abierto.

## <img src="/Images/Icons/open_scholarship.png" width="150" height="150" />
##### **4. Reporta tu investigación de modo transparente**

Reporta y publica tus métodos e intervenciones de modo explícito, transparente, y completo para permitir su reproducción. Las guías de la [Equator Network](http://www.equator-network.org/), herramientas como [Protocols.io](https://www.protocols.io/), o procesos como [Registered Reports](https://cos.io/rr/) pueden ayudarte a reportar la reproducibilidad. Recuerda publicar tus resultados en tu plataforma de registro público \(como [ClinicalTrials.gov](https://www.socialscienceregistry.org/) o el [SocialScienceRegistry](https://www.socialscienceregistry.org/)\) dentro del año de terminado tu estudio, sin importar la naturaleza o rumbo de tus resultados.

## <img src="/Images/Icons/questions.png" width="150" height="150" />
### Preguntas, obstáculos y equivocaciones comunes

Q: "Todo está en el papel; cualquiera puede reproducirlo desde allí!"

A: Esta es una de las equivocaciones más comunes. Incluso si se cuenta con una descripción extremadamente detallada de los métodos y flujos de trabajo empleados para alcanzar el resultado final, esto no será suficiente para reproducirlo en la mayoría de los casos. Esto se puede deber a distintos factores, incluyendo el uso de diferentes entornos computacionales, diferencias en las versiones de software, sesgos implícitos que no fueron declarados con claridad, etc.

Q: "No tengo el tiempo para aprender y establecer un flujo de trabajo reproducible."

A: Además del número significativo de servicios gratuitos y disponibles en línea que pueden ser combinados para facilitar la organización de un flujo de trabajo completo, emplear tiempo y esfuerzo a organizar este aspecto aumentará la validez científica de los resultados finales y minimizará el tiempo que tomará volver a realizar el análisis de datos o extenderlo en estudios posteriores.

Q: "Las terminologías que describen la reproducibilidad son desafiantes."

A: Mira Barba \(2018\) para una discusión sobre la terminología que describe la reproducibilidad y la replicabilidad.

## <img src="/Images/Icons/output.png" width="150" height="150" />
### Resultados de aprendizaje

1. Entender la necesidad de una investigación reproducible y sus fundamentos.

2. Ser capaz de establecer un flujo de trabajo reproducible en el contexto de una tarea de ejemplificación.

3. Conocer herramientas que pueden contribuyen con la investigación reproducible.

## <img src="/Images/Icons/magnifying_glass.png" width="150" height="150" />
### Lecturas adicionales

* Calcula tu poder: [Button et al. \(2013\) study of the relationship between reproducibility and power.](https://www.nature.com/articles/nrn3475)

* Nominación informativa: [Karl Broman’s Data Organization module: Choose good names for things](http://kbroman.org/dataorg/pages/names.html)
