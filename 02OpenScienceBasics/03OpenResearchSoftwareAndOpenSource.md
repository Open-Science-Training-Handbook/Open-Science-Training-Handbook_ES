Código Abierto##<img src="/Images/Icons/open_source_software.png" width="150" height="150" /> <img src="/Images/Icons/publish.png" width="150" height="150" />
## 3. Software de investigación abierto y Código Abierto (Open Source)

### ¿Qué es?

El software de investigación abierto o software de investigación de Código Abierto se refiere al uso y al desarrollo de software para el análisis, la simulación y la visualización (entre otras cosas) donde el código fuente completo está disponible. Además, de acuerdo a la [Definición de Código Abierto](https://opensource.org/osd), el software de Código Abierto debe ser distribuido en forma de código y/o compilada \(con el código fuente disponible en el último caso\), y debe ser compartido bajo una licencia que permita su  modificación, derivación y redistribución.

### Justificación

La investigación moderna depende de software, y la construcción sobre -o la reproducibilidad de- dicha investigación requiere del acceso al código fuente completo que subyace a dicho software \(Barnes, 2010; Morin et al., 2012; Ince et al., 2012; Prins et al. 2015; Lowndes et al., 2018\). Como dicen Buckheit y Donoho, parafraseando a Jon Claerbout, "Un artículo acerca de un resultado computacional es publicidad, no investigación académica. La academia real es el entorno de software completo, el código y los datos que produjeron el resultado" \(Buckheit & Donoho, 1995\). El acceso abierto al código fuente del software de investigación también ayuda a mejorar el impacto de la investigación \(Vandewalle, 2012\).

Compartir el software utilizado en la investigación \(ya sea que esta posea naturaleza computacional o dependa del análisis/interpretación basado/a en software\) es una condición necesaria, aunque no suficiente, para la reproducibilidad. Esto se debe a la inevitable ambigüedad que emerge cuando se trata de describir de manera completa un software utilizando el lenguaje natural, por ejemplo, en un paper \(Ince et al., 2012\). Además, muchos \(sino la mayoría\) de los programas de software pueden contener errores no detectados \(Soergel, 2015\). Por tanto, incluso una descripción escrita "perfecta" de un software podría no dar cuenta de todos los resultados.

En adición a la reproducibilidad, compartir software de manera abierta permite a los desarrolladores recibir crédito por sus esfuerzos, ya sea a través de cita directa \(Smith et al., 2016\) o a través de meta-artículos sobre software publicados, por ejemplo, en el [Journal of Open Research Software](http://openresearchsoftware.metajnl.com) o el [Journal of Open Source Software](http://joss.theoj.org) \(Smith et al., 2018\). Neil Chue Hong mantiene una [lista de muchas revistas de dominio específico](https://www.software.ac.uk/which-journals-should-i-publish-my-software) que publican artículos sobre software.

## <img src="/Images/Icons/finish.png" width="150" height="150" />
### Objetivos de aprendizaje

1. Aprender las características del software abierto; entender los argumentos éticos, legales, económicos y de impacto de la investigación en apoyo y en contra del software abierto, y entender mejor los requerimientos de calidad del Código Abierto.

2. Aprender como usar software de acceso abierto existente y reconocerlo \(citarlo\) de manera apropiada .

3. Aprender como utilizar herramientas y servicios comunes para compartir código de investigación de manera abierta.

4. Ser capaz de elegir la licencia apropiada para software, y entender las diferencias entre licencias permisivas y no permisivas.

### Componentes principales

## <img src="/Images/Icons/brain.png" width="150" height="150" />
#### Conocimiento

Existen distintas plataformas que apoyan la colaboración y el intercambio de software de manera abierta. Primero que nada, puedes utilizar esta lista para evaluar el nivel de apertura de un software de investigación existente:

* ¿Está el software disponible para descargar e instalar?

* ¿Puede el software ser instalado fácilmente en distintas plataformas?

* ¿Tiene el software condiciones de uso?

* ¿Está el código fuente disponible para su inspección?

* ¿Está la historia completa del código fuente disponible para su inspección a través de un historial de versiones público?

* ¿Están descritas correctamente las dependencias del software \(hardware y software\)? ¿Requieren estas dependencias de un esfuerzo mínimo razonable para ser obtenidas y utilizadas?

Estas cualidades se relacionan con y se construyen a partir de la [Definición de Código Abierto](https://opensource.org/osd).

GitHub es una herramienta popular que permite el control de versiones: la gestión y el seguimiento de los cambios de un software particular. Los servicios como GitHub, GitLab, Bitbucket y otros proveen de una interfaz a la herramienta como así también un sistema de almacenamiento remoto que puede ser utilizado para mantener, compartir y colaborar sobre software de investigación. Se trata de una herramienta cuyo uso es bastante generalizado y que, si bien posee una curva de aprendizaje inicial, ha probado ser invaluable para el establecimiento de un flujo de trabajo abierto y reproducible.

Tener el software de investigación en GitHub es sólo la primera parte; es igualmente importante tener un identificador persistente publicado asociado con él, como un DOI. Hay distintas formas de asociar un DOI con un repositorio de GitHub. La forma más fácil es utilizar Zenodo \(un repositorio gratuito y abierto general creado por OpenAIRE y CERN\) para hacer la asignación, aunque existen otros repositorios para archivar software y obtener un DOI, como por ejemplo Figshare. [Zenodo se integra con GitHub](https://guides.github.com/activities/citable-code/) para archivar el software y proveer un DOI cuando los desarrolladores hacen un nuevo lanzamiento formal en GitHub.

El software compartido públicamente no es de Código Abierto a menos que esté acompañado de una licencia adecuada porque, por defecto, el software \(así como cualquier otro trabajo creativo\) posee derechos de autor exclusivos para los creadores, lo que significa que nadie lo puede usar, copiar, distribuir o modificar \([choosealicense.com](https://choosealicense.com/no-permission/)\). \(Si realmente quieres compartir el código sin ningún tipo de restricciones, puede ser [incluido en el dominio público](https://choosealicense.com/licenses/#unlicense).\) En lugar de ello, puedes elegir una licencia apropiada para tu software en función de lo que desees que otros puedan hacer con tu código \(o impedir que hagan \); el sitio [choosealicense.org](https://choosealicense.com) es un recurso útil para diferenciar entre distintas licencias, aunque no incluye [todas las licencias de Código Abierto disponibles o populares](https://opensource.org/licenses). Una vez que selecciones una licencia, pon el texto -editado para incluir el nombre del o los autor\(es\) y el año- en el repositorio de software como un archivo de texto con el nombre LICENSE.

![](/Images/02 Open Science Basics/02_open_research_software_open_source.png)

Aunque compartir software en cualquier forma es mejor que no compartirlo, tu software tendrá más impacto y podrá ser más fácilmente utilizado por otros -y por ti mismo en el futuro!-, si incluyes documentación. Esto puede incluir comentarios útiles en el código que expliquen **por qué** hiciste algo \(en vez de sólo lo que hiciste, que debería ser evidente\), un archivo README informativo que describa lo que hace tu software y brinde información útil \(e.g., cómo instalar, cómo citar, cómo correr el software, dependencias importantes\), tutoriales/ejemplos, y/o documentación de API \(que puede ser automáticamente generada a partir de comentarios apropiadamente formateados en el código\).

Las dependencias perdidas o inaccesibles o la documentación insuficiente sobre el entorno computacional son barreras muy comunes contra la re-utilización y la reproducibilidad. Una aproximación para abordar estas barreras es compartir tu código con tu entorno computacional usando tecnología de contenedores (container technology). Los contenedores empacan el código con las dependencias y el entorno computacional para que otros pueden correr más fácilmente tu análisis. Los siguientes son ejemplos de la implementación de contenedores en la investigación: [Rocker](https://arxiv.org/abs/1710.03675), [Binder](https://mybinder.readthedocs.io/en/latest/), y [Code Ocean](https://codeocean.com/).

Cuando usas software -ya sea software que tú escribiste o que alguien más hizo y puso a disponibilidad-, citarlo de manera apropiada es importante para la reproducibilidad \(esto se discute en más detalle en la [Sección 4](#heading=h.jy7n9xm9zn9o); brevemente, la versión usada puede cambiar tus resultados o interpretación\) y para dar crédito a los desarrolladores del software \(Niemeyer 2016, Smith 2016\). La decisión de cuándo citar software depende de ti como investigador, pero recomendamos citar siempre que el software utilizado haya contribuido de manera integral a tus resultados, interpretación o conclusiones. La mejor manera de hacer que _tu_ código sea más fácilmente citable es usar la integración de GitHub–Zenodo descrita antes y proveer el DOI en un lugar obvio, como el README del software, junto con un formato de cita sugerido. Cuando se cita cualquier software debes incluir, al menos, el nombre de los autores, el título del software, el número de versión, y un identificador o localizador único \(Smith 2016\). Si usas el software de alguien más y ellos proveen un DOI, lo puedes utilizar fácilmente para identificar y citar el software; si el software no está archivado, entonces debes incluir el URL donde puede ser encontrado y el número de versión o \(e.g.\) el _hash_ de un _commit_ (por ej., en GitHub).

Adicionalmente, existen conceptos más complejos como el testeo automático y la integración continua del software, el empaquetado de software en formatos binarios, y la gobernanza y la gestión de proyectos de Código Abierto multi-persona \(esto es, códigos de conducta, guías de contribución y autoría\). Algunos de estos temas han sido descritos por Scopatz y Huff \(2015\). Wilson et al. \(2017\) también entregan una guía práctica de las mejores prácticas de computación científica que incluye consejos específicos para el desarrollo de software para la investigación.

## <img src="/Images/Icons/laptop.png" width="150" height="150" />
##### Hardware de Código Abierto

Los principios de Código Abierto descritos anteriormente se extienden al hardware. Los investigadores usualmente utilizan instrumental o hardware patentado en su investigación que no es de libre acceso, reusable ni adaptable. El hardware científico incluye desde herramientas de secuenciación y microscopios hasta equipamiento de testeo especializado y colisionadores de partículas. La Comunidad de Hardware Abierto (Open Science Hardware \(OScH\)), por ejemplo, está bregando para que el movimiento de Código Abierto considere las herramientas científicas, el hardware, y las infraestructuras de investigación a través de su [Hoja de Ruta Global de Hardware de Ciencia Abierta](http://openhardware.science/global-open-science-hardware-roadmap/).

## <img src="/Images/Icons/gears.png" width="150" height="150" />
#### Habilidades

* Crea un repositorio en Github, y permite la integración con Zenodo. Acuña la primera versión del software.

* Elige una licencia de software usando, por ejemplo, [choosealicense](https://choosealicense.com) o la [Iniciativa Open Source](https://opensource.org/licenses).

* Crea documentación para un paquete de software, incluyendo un README, comentarios y ejemplos.

* Cita de manera apropiada el software utilizado en un paper.

## <img src="/Images/Icons/questions.png" width="150" height="150" />
### Preguntas, obstáculos y equivocaciones comunes

Q: "No puedo compartir mi software, es muy desordenado / no tiene una buena documentación / no dejé buenos comentarios"

A: Los desarrolladores de software de investigación en todo el mundo empatizan con este sentimiento. Las personas rara vez creen que su software está "listo" para ser compartido públicamente o que ya está "terminado". Sin embargo, como sostiene Barnes \(2010\), “si tu código es lo suficientemente bueno como para hacer su trabajo, entonces es lo suficientemente bueno o como para ser publicado, y publicarlo  ayudará a tu investigación y a tu área de investigación." En otras palabras, si te sientes suficientemente conforme con tu software como para publicar un estudio o reportar resultados, entonces el código está lo suficientemente desarrollado como para compartirlo con tus colegas.  \(Contrariamente, si no te sientes cómodo compartiendo el código, entonces tal vez requiera un poco más de desarrollo o testeo antes de ser utilizado en una publicación\). Además, compartir tu código le permite a otros mejorarlo y construir sobre el, lo que conduce a un impacto y una innovación incluso mayores \(¡y a que seas citado más veces!\).

Q: "¿Qué ocurre si alguien toma el código que he compartido y lo utiliza para propósitos nefastos o dice que es de su autoría?"

A: Seleccionar una licencia apropiada para tu software te ayudará a protegerlo de los usos que puedan hacer otros de él; por ejemplo, la licencia común [MIT](https://choosealicense.com/licenses/mit/) incluye limitaciones de responsabilidad e indica que no se proveen garantías. Si alguien trata de atribuirse la autoría de tu software, puedes indicar las marcas temporales (_timestamps_) de tu repositorio o las versiones archivadas como prueba de la precedencia de tu trabajo.

Q: "Si comparto mi código en un repositorio online, recibiré un número excesivo de peticiones de ayuda."

A: Aunque usuarios potenciales te podrían pedir ayuda, ya sea vía correo electrónico o, por ejemplo, a través de solicitudes en el repositorio online, no tienes ninguna obligación de proveer soporte si no puedes o prefieres no hacerlo. Una licencia apropiada te provee, incluso, una protección legal para ello \(por ejemplo, la cláusula de no garantías de la [licencia MIT](https://choosealicense.com/licenses/mit/)\).

Una idea errónea muy común: la simple colocación del código en línea hace que un software sea de Código Abierto. En realidad, a menos que el software esté acompañado de una licencia que concede permiso a otros para su uso, copia, modificación y/o distribución, los desarrolladores mantienen derechos de autor exclusivos sobre el software. Para que un código sea de Código Abierto debe ser acompañado de una licencia de Código Abierto.

## <img src="/Images/Icons/output.png" width="150" height="150" />
### Resultados de aprendizaje

1. Ser capaz de compartir software bajo la licencia más apropiada \(esto es, tanto las herramientas como la licencia\).

2. Ser capaz de subir, crear versiones y registrar código empleando un identificador persistente.

3. Ser capaz de citar software utilizado para un artículo de investigación.

## <img src="/Images/Icons/magnifying_glass.png" width="150" height="150" />
### Lecturas adicionales

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
