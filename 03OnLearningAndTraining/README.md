##<img src="/Images/Icons/open_source_software.png" width="150" height="150" /> <img src="/Images/Icons/publish.png" width="150" height="150" />
## 3. Software de investigación abierta y de código abierto (open source)

### ¿En qué consiste?

El software de investigación abierta, o software de código abierto de investigación, se refiere a todo el uso y desarrollo de software para análisis, simulación, etc., donde el código fuente está disponible. Además, de acuerdo a la [Definición de Open Source](https://opensource.org/osd), software de código abierto debe ser distribuida como en su código fuente y/o compilado (con el código fuente disponible en el último caso), y  debe ser compartido bajo una licencia que permita su  modificación, derivación y redistribución. 

### Justificación

La investigación moderna se basa en software, y reproducir dicha investigación requiere de acceso al código fuente completo detrás de dicho software (Barnes, 2010; Morin et al., 2012; Ince et al., 2012; Prins et al. 2015; Lowndes et al., 2018\). Como dicen  Buckheit y Donoho, parafraseando a Jon Claerbout, ‘Un artículo acerca de un resultado computacional es publicidad, no investigación académica. La academia real es el ambiente de desarrollo de software completo, código y datos, que producen el resultado’ \(Buckheit & Donoho, 1995\). El acceso abierto al código fuente del software de investigación también ayuda a mejorar el impacto de la investigación \(Vandewalle, 2012\).

Compartir el software utilizado en una investigación \(ya sea de naturaleza computacional, o que se basa en un análisis o interpretación\) es una condición necesaria, aunque no suficiente, para la reproducibilidad. Esto es debido a la inevitable ambigüedad que emerge cuando se trata de describir de manera completa un software utilizando lenguaje natural, es decir, en un paper \(Ince et al., 2012\). Es más, muchos \(o la mayoría\) de los programas de software pueden contener errores no detectados \(Soergel, 2015\), por tanto incluso una descripción escrita "perfecta" de un software podría no dar cuenta de todos los resultados.

En adición a la reproducibilidad, compartir software de manera abierta permite a los desarrolladores recibir crédito por sus esfuerzos, ya sea a través de citación directa \(Smith et al., 2016\) o a través de meta-artículos publicados, por ejemplo en el [Journal of Open Research Software](http://openresearchsoftware.metajnl.com) o el [Journal of Open Source Software](http://joss.theoj.org) \(Smith et al., 2018\). Neil Chue Hong mantiene una [lista de muchas revistas dominio específicas](https://www.software.ac.uk/which-journals-should-i-publish-my-software) que publican artículos sobre software.

## <img src="/Images/Icons/finish.png" width="150" height="150" />
### Objetivos de aprendizaje

1. Aprender las características del software abierto; entender los argumentos éticos, legales, económicos e impactos de la investigación en apoyo y en contra de software abierto, y entender de mejor manera los requerimientos de calidad de código abierto. 

2. Aprender como usar software de acceso abierto existente y dar la atribución apropiada \(citar\).

3. Aprender como utilizar herramientas y servicios comunes para compatir códigos de manera abierta.

4. Ser capaz de elegir la licencia apropiada para software, y entender las diferencias entre licencias permisivas y no permisivas. 

### Componentes principales

## <img src="/Images/Icons/brain.png" width="150" height="150" />
#### Conocimiento 

Existen distintas plataformas que apoyan la colaboración y el compartir software de manera abierta. Primero que nada, puedes utilizar esta lista para evaluar el nivel de apertura de un software de investigación existente: 

* ¿Está el software disponible para descargar e instalar? 

* ¿Puede ser el software instalado fácilmente en distintas plataformas? 

* ¿Tiene el software condiciones de uso? 

* ¿Es el código fuente disponible para la inspección? 

* ¿Está disponible la historia completa del código fuente para inspección por medio de una historia públicamente disponible?

* ¿Están descritas correctamente las dependencias del software \(hardware y software\)? ¿Requieren estas dependencias de un esfuerzo mínimo razonable para ser obtenidas y utilizadas? 

Estas cualidades se relacionan y se construyen a partir del la [Definición de Open Source](https://opensource.org/osd).

GitHub es una herramienta popular que permite control de versiones: la gestión y el seguimiento de los cambios de un software particular. Los servicios como GitHub, GitLab, Bitbucket, y otros proveen de una interface a las herramientas, así como un sistema de almacenamiento remoto que puede ser utilizado para mantener, compartir y colaborar en software de investigación. Es una herramienta que es ampliamente conocida, y aunque tiene una curva de aprendizaje alta en un comienzo, es invaluable para establecer un flujo de trabajo abierto y reproducible. 

Hacer disponible el software en GitHub es sólo la primera parte; es igualmente importante tener un identificador persistente publicado asociado con este software, como un DOI. Hay distintas formas de asociar un DOI con un repositorio de GitHub; la forma más fácil es utilizar Zenodo \(un repositorio gratis y abierto multi-función creado por OpenAIRE y CERN\) para hacer la asignación, aunque existen otros repositorios para archivar software y obtener DOU, como Figshare. [Zenodo se integra con GitHub](https://guides.github.com/activities/citable-code/) para archivar el software y proveer un DOI cuando los desarrolladores hacen un nuevo lanzamiento en GitHub. 

El Software compartido públicamente no es efectivamente open source a menos que sea acompañado de una licencia adecuada, dado que por defecto software \(así como cualquier otro trabajo creativo\) recae bajo derecho de autor para los creadores, lo que significa que nadie lo puede usar, copiar, distribuir o modificar \([choosealicense.com](https://choosealicense.com/no-permission/)\). \(Si realmente se quiere compartir el código sin ningún tipo de restricciones, puede ser [guardado en el dominio público](https://choosealicense.com/licenses/#unlicense).\) En lugar de ello, puedes elegir una licencia apropiada para software, basado en lo que se desee que otros puedan hacer con tu código \(o impedir que lo hagan \); el sitio [choosealicense.org](https://choosealicense.com) es un recurso útil para diferenciar entre distintas licencias, aunque no incluye [todas las licencias open-source disponibles](https://opensource.org/licenses). Una vez que selecciones una licencia, pon el texto editado para incluir el nombre del o los autor(es) y el año en el repositorio de software como un archivo de texto con el nombre LICENSE. 

![](/Images/02 Open Science Basics/02_open_research_software_open_source.png)

Aunque compartir software en cualquier forma es mejor que no compartirlo, tu software tendrá más impacto y será más fácilmente utilizado por otros y por tu persona futura, si incluyes documentación. Esto puede incluir comentarios útiles en el código que expliquen **por qué** hiciste algo \(en vez de sólo lo que hiciste, lo que debería ser evidente\), un archivo README informativo que describe lo que hace tu software y dar información útil \(e.g., cómo instalar, cómo citar, como correr el software, dependencias importantes\), tutoriales/ejemplos, y/o documentación de API \(que puede ser automáticamente generada a partir de comentarios apropiados en el código\).

Dependencias perdidas o inaccesibles o documentación insuficiente del ambiente computacional son barreras comunes para el reuso y la reutilización. Una aproximación para abordar estas barreras es compartir tu código con tu ambiente computacional usando tecnología contenedora (container technology). Los contenedores empacan el código con las dependencias y el ambiente computacional de manera de que otros pueden correr más fácilmente tu análisis. Los ejemplos de implementación en investigación incluyen  [Rocker](https://arxiv.org/abs/1710.03675), [Binder](https://mybinder.readthedocs.io/en/latest/), y [Code Ocean](https://codeocean.com/).

Cuando usas software, ya sea software que tu escribiste o que alguien más hizo y puso a disponibilidad, una citación apropiada es importante para la reproducibilidad \(esto se discute en más detalle en la [Sección 4](#heading=h.jy7n9xm9zn9o); brevemente, la versión usada puede cambiar tus resultados o interpretación\) y dar crédito a los desarrolladores del software \(Niemeyer 2016, Smith 2016\). La decisión de cuando citar software depende de ti como investigador, pero recomendamos citar cuando el software utilizado haya contribuido de manera integral a tus resultados, interpretación o conclusiones. La mejor manera de hacer que _tu_ código sea más fácilmente citable es usar la integración de GitHub–Zenodo descrita antes y provisto el resultante DOI en un lugar obvio como el README del software, quizás junto con un formato de citación sugerido. Cuando se cita cualquier software, debes incluir al menos el nombre de él o los autores, título del software, número de versión, y un identificador o localizador único \(Smith 2016\). Si usas el software de alguien más y ellos proveen un DOI, lo puedes utilizar fácilmente para identificar y citar el software; si el software no está archivado, entonces debes incluir el URL donde puede ser encontrado y el número de versión o **\(e.g.\) commit hash.**

Adicionalmente, existen conceptos más complejos como el testeo automático y la integración continua del software, el empaquetado de software en formatos binarios, y la gobernanza y la gestión de proyectos de código abierto multi-persona \(por ejemplo, códigos de conducta, guías de contribución y autoría\). Algunos de estos temas han sido descritos por Scopatz y Huff \(2015\). Wilson et al. \(2017\) también entregan una guía práctica de las mejores prácticas de computación científica que incluye consejos específicamente en el desarrollo de software para investigación. 

## <img src="/Images/Icons/laptop.png" width="150" height="150" />
##### Hardware Abierto

Los principios de código abierto (open source) descritos anteriormente también se extienden al  hardware. Los investigadores usualmente utilizan instrumentación patentada en su investigación, que no es de libre acceso, reusable o adaptable. El hardware científico incluye desde herramientas de secuenciación y microscopios a equipamiento de testeo especializado a colisionadores de partículas. La comunidad de Hardware abierto (Open Science Hardware \(OScH\)), por ejemplo, está empujando para que el movimiento open source considere las herramientas científicas, el hardware, y las infraestructuras de investigación en su [Hoja de Ruta Global de Hardware de Ciencia Abierta](http://openhardware.science/global-open-science-hardware-roadmap/).

## <img src="/Images/Icons/gears.png" width="150" height="150" />
#### Competencias

* Crear un repositorio en Github, y permitir la integración con Zenodo. Acuñar la primera versión del software. 

* Elegir una licencia de software  \(ej.\) [choosealicense](https://choosealicense.com) o la [Iniciativa Open Source](https://opensource.org/licenses).

* Crear documentación para un paquete de software, incluyendo README, comentarios y ejemplos. 

* Citar de manera apropiada el software utilizado para un paper. 
* 
## <img src="/Images/Icons/questions.png" width="150" height="150" />
### Preguntas, obstáculos e ideas erróneas comunes 

Q: "No puedo compartir mi software, es muy desordenado / no tiene una buena documentación / No dejé buenos comentarios!"

A: Los desarrolladores de software de investigación en todo el mundo empatizan con este sentimiento, las personas rara vez creen que su software está "listo" para ser compartido públicamente o que ya está "terminado". Sin embargo, como lo menciona Barnes \(2010\), “si tu código es lo suficientemente bueno como para funcionar, entonces es lo suficientemente bueno o como para ser liberado, y al liberarlo te ayudará en tu investigación y a tu área de investigación." En otras palabras, si te sientes conforme con tu software como para publicar un estudio o reportar resultados, entonces el código está lo suficientemente desarrollado como para compartirlo con tus colegas.  \(En la dirección opuesta, si no te sientes cómodo compartiendo el código, quizás requiere un poco más de desarrollo o testeo antes de ser utilizado en una publicación\). Además, compartir tu código le permite a otros mejorarlo y construir sobre el, lo que conlleva un mayor impacto e innovación \(¡y que seas citado más veces! m\).

Q: "¿Qué pasa si alguien toma el código que he compartido y lo utiliza para propósitos malignos, o dice que es de su autoría?"

A: El seleccionar una licencia apropiada para tu software te ayudará a protegerlo de los usos que puedan hacer otros de él; por ejemplo, la licencia de uso común [MIT](https://choosealicense.com/licenses/mit/) incluye limitaciones de responsabilidad e indica que no se incluye ninguna garantía. Si alguien más trata de reclamar la autoría de tu software, puedes indicar las marcas de fecha (timestamps) en tu repositorio o las versiones archivadas como prueba de tu trabajo previo. 

Q: "Si comparto mi código en un repositorio online, voy a ser inundado con peticiones de ayuda ."

A: Aunque los usuarios potenciales te podrían pedir ayuda, ya sea vía correo electrónico o \(por ejemplo\) solicitudes a través del repositorio online, no tienes ninguna obligación de proveer el apoyo si no puedes o prefieres no hacerlo. Una licencia apropiada incluso te provee con la protección legal ante ello \(como la cláusula de no garantía de la [licencia MIT](https://choosealicense.com/licenses/mit/)\).

Idea preconcebida común: simplemente disponer el código en línea lo hace software de código abierto. De hecho, a menos que el software sea acompañado de una licencia que concede permiso a otros para su uso, copia, modificación y/o distribución, el o los desarrolladores mantienen derechos de autor exclusivos sobre el software. Es necesario que sea acompañado de una licencia de código abierto para hacerlo software de código abierto. 

## <img src="/Images/Icons/output.png" width="150" height="150" />
### Resultados de aprendizaje

1. Ser capaz de compartir software bajo la licencia más apropiada \(es decir, tanto las herramientas como el licenciamiento).

2. Ser capaz de subir, crear versiones y registrar un pedazo de código bajo un identificador persistente. 

3. Ser capaz de citar software utilizado para un artículo de investigación.

## <img src="/Images/Icons/magnifying_glass.png" width="150" height="150" />
### Bibliografía recomendada

* [The Future of Research in Free/Open Source Software Development](http://www.ics.uci.edu/~wscacchi/Papers/New/FoSER-Scacchi-2010.pdf) \(Scacchi, 2010\).

* [The Scientific Method in Practice: Reproducibility in the Computational Sciences](http://datascienceassn.org/sites/default/files/The Scientific Method in Practice - Reproducibility in the Computational Sciences.pdf) \(Stodden, 2010\).

* [The case for open computer programs](https://www.nature.com/articles/nature10836) \(Ince et al., 2012\).

* [Shining Light into Black Boxes](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4203337/pdf/nihms588981.pdf) \(Morin et al., 2012\).

* [Code Sharing Is Associated with Research Impact in Image Processing](https://infoscience.epfl.ch/record/206184/files/Vandewalle12.pdf) \(Vandewalle, 2012\).

* [Current issues and research trends on open-source software communities](https://idus.us.es/xmlui/bitstream/handle/11441/32245/Current issues and research trends.pdf?sequence=1) \(Martinez-Torres and Diaz-Fernandez, 2013\).

* [Ten simple rules for reproducible computational research](http://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1003285) \(Sandve et al., 2013\).

* [Practices in source code sharing in astrophysics](https://arxiv.org/abs/1304.6780) \(Shamir et al., 2013\).

* [A systematic literature review on the barriers faced by newcomers to open source software projects](http://igor.pro.br/publica/papers/IST_SysReview_PrePrint.pdf) \(Steinmacher et al., 2014\).

* [Knowledge sharing in open source software communities: motivations and management](https://pdfs.semanticscholar.org/f2a2/c5129cf5656af7acc7ffaf84c9c9bafe72c5.pdf) \(Iskoujina and Roberts, 2015\).

* [An open source pharma roadmap](http://journals.plos.org/plosmedicine/article?id=10.1371/journal.pmed.1002276) \(Balasegaram et al., 2017\).

* [Upon the Shoulders of Giants: Open-Source Hardware and Software in Analytical Chemistry](https://pubs.acs.org/doi/abs/10.1021/acs.analchem.7b00485) \(Dryden et al., 2017\).

* [Four simple recommendations to encourage best practices in research software](https://f1000research.com/articles/6-876/v1) \(Jiménez et al., 2017\).

* [Perspectives on Reproducibility and Sustainability of Open-Source Scientific Software from Seven Years of the Dedalus Project](https://arxiv.org/abs/1801.08200) \(Oishi et al., 2018\).
