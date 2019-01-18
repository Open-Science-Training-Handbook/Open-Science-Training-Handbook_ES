## <img src="../Images/Icons/open_data.png" width="200" height="200" />
## 2. Datos y materiales de investigación abiertos

### ¿En qué consiste?

Los datos de investigación abiertos son datos de acceso gratuito que pueden ser reutilizados, remezclados y redistribuidos para la investigación académica y propósitos de docencia, entre otros. Idealmente, los datos abiertos no tienen restricciones para su reutilización y redistribución y cuentan con licencias acordes a ello. En casos excepcionales \(por ejemplo, para proteger la identidad de sujetos humanos\), se pueden incluir restricciones de acceso especiales o limitadas. Compartir los datos de manera abierta los expone a la inspección, formando la base para la reproducibilidad y verificación de investigación, y abre un camino para promover la colaboración. Como máximo, los datos abiertos pueden estar sujetos a requisitos de _atribución_ y de _compartir igual_ \(_sharealike_\) \(ver el [Open Data Handbook](http://opendatahandbook.org/guide/en/what-is-open-data)\)

## <img src="../Images/Icons/data2.png" width="150" height="150" />
### Justificación

Los datos de investigación son a menudo el producto más valioso de los proyectos de investigación, pues se utilizan como fuente primaria para sustentar la investigación científica y permitir la derivación de hallazgos teóricos o aplicados. Para hacer que los hallazgos/estudios sean replicables o, al menos, reproducibles o reutilizables de otra forma \(consulta la sección sobre [Investigación reproducible y análisis de datos](**04ReproducibleResearchAndDataAnalysis.md**)\), la recomendación de buenas prácticas es que los datos de investigación sean tan abiertos y justos \([FAIR](https://www.force11.org/fairprinciples)\) como sea posible, teniendo en cuenta las limitaciones éticas, comerciales y las restricciones de privacidad de los datos confidenciales o privados.

## <img src="../Images/Icons/finish.png" width="150" height="150" />

## Objetivos de aprendizaje

1. Obtener una comprensión de las características y principios básicos de los datos de investigación abiertos y justos \(_FAIR_\), incluyendo el empaquetado y la documentación apropiados, para permitir que otros los entiendan, reproduzcan y reutilicen de maneras alternativas.

2. Familiarizarse con los tipos de datos que pueden considerarse confidenciales y las restricciones legales para compartirlos en abierto.

3. Ser capaz de convertir un conjunto de datos "cerrado" en uno "abierto", mediante la implementación de las medidas necesarias en un plan de gestión de datos, administrando adecuadamente los datos y metadatos.

4. Ser capaz de utilizar un plan de gestión de datos de investigación y hacer que los resultados de tu investigación sean encontrables y accesibles, incluso si contienen datos confidenciales.

5. Comprender las ventajas y desventajas de compartir en abierto diferentes tipos de datos \(por ejemplo, referidas a la privacidad, confidencialidad, des-identificación, y acceso mediado\).

6. Comprender la importancia de la adecuación de los metadatos para el archivo sostenible de datos de investigación.

7. Comprender los flujos de trabajo básicos y las herramientas para compartir los datos de investigación.

### Componentes clave

## <img src="../Images/Icons/brain.png" width="150" height="150" /><img src="../Images/Icons/gears.png" width="150" height="150" />
#### Habilidades de conocimiento

##### Principios justos \(_FAIR principles_\)

En 2014 se redactó un conjunto nuclear de principios para optimizar la reutilización de los datos de investigación. Fue denominado [FAIR Data Principles](https://www.force11.org/group/fairgroup/fairprinciples). Los principios representan un conjunto de directrices y buenas prácticas desarrolladas por la comunidad, para garantizar que los datos \(o cualquier objeto digital\) sean _**F**indable_ \(encontrables\), _**A**ccessible_ \(accesibles\), _**I**nteroperable_ \(interoperables\) y _**R**e-usable_ \(reutilizables\):

**Encontrables:** Para que los datos sean reutilizables, primero deben poder ser encontrados. Debería ser fácil encontrar los datos y los metadatos tanto para humanos como para computadoras. El descubrimiento automático y confiable de conjuntos de datos y servicios depende de los identificadores persistentes \(PIDs\) legibles por máquinas y de los metadatos.

**Accesibles:** Los datos y metadatos deberían poder ser recuperados mediante su identificador utilizando un protocolo de comunicaciones abierto y estandarizado, que posiblemente incluya autenticación y autorización. Además, los metadatos deberían estar disponibles, incluso si los datos ya no lo están.

**Interoperables:** Los datos deberían poder combinarse y usarse con otros datos o herramientas. Por lo tanto, el formato de los datos debe ser abierto e interpretable para varias herramientas, incluyendo otros registros de datos. El concepto de interoperabilidad se aplica tanto en el nivel de los datos como en el de los metadatos. Por ejemplo, los \(meta\)datos deberían emplear un vocabulario que siga los principios FAIR.

**Re-utilizable:** En última instancia, FAIR busca optimizar la reutilización de datos. Para lograr esto, los metadatos y datos deben estar bien descritos de modo que puedan ser replicados y/o combinados en diferentes entornos. Además, la reutilización de los \(meta\)datos debe estar indicada a través de licencias claras y accesibles.

A diferencia de las iniciativas de pares que se centran en el investigador humano, los principios FAIR ponen énfasis específico en mejorar la capacidad de las máquinas para encontrar y utilizar automáticamente los datos o cualquier objeto digital, además de apoyar su reutilización por parte de individuos. Los principios FAIR son principios rectores, no estándares. FAIR describe las cualidades o comportamientos necesarios para hacer que los datos sean reutilizables al máximo \(por ejemplo: descripción, cita\). Esas cualidades se pueden lograr con diferentes estándares.

![02_open_research_data_material ES](/Users/rosariorogel/Documents/GitHub/Open-Science-Training-Handbook_ES/Images/02 Open Science Basics/02_open_research_data_material ES.png)

##### Publicación de datos

La mayoría de los investigadores está más o menos familiarizados con la publicación en Acceso Abierto de artículos de investigación y libros \(véase el capítulo 5\). Más recientemente, y por las razones mencionadas anteriormente, la publicación de datos ha llamado la atención. Cada vez más patrocinadores esperan que los datos producidos en los proyectos de investigación que financian sean fáciles de encontrar, accesibles y lo más abiertos que sea posible.

Hay diferentes formas para hacer que los datos de investigación sean accesibles, incluyendo \([Wikipedia](https://en.wikipedia.org/wiki/Data_publishing)\):

* Publicar los datos como material complementario asociado con un [artículo de investigación](https://en.wikipedia.org/wiki/Research_article). Generalmente los archivos de datos serán alojados por la editorial del artículo.

* Alojar los datos en un sitio web de disponibilidad pública que permita que los archivos estén disponibles para su descarga.

* Depositar los datos en un repositorio desarrollado para apoyar la publicación de datos, por ejemplo, [Dataverse](https://en.wikipedia.org/wiki/Dataverse), [Dryad](https://en.wikipedia.org/wiki/Dryad_(repositorio)), [figshare](https://en.wikipedia.org/wiki/Figshare), [Zenodo](https://en.wikipedia.org/wiki/Zenodo).

* Existe un gran número de repositorios de datos generales y de dominio/disciplina específico/a que pueden proporcionar apoyo adicional a los investigadores al momento de depositar sus datos.

* Publicar un artículo de datos \(_data paper_\) sobre el conjunto de datos, que puede difundirse como un preprint, en una revista o en una revista de datos dedicada a mantener artículos de datos. Los datos pueden ser alojados por la revista o alojados por separado en un repositorio de datos. Algunos ejemplos de revistas de datos son [Scientific Data](https://www.nature.com/sdata/) \(de SpringerNature\) y [Data Science Journal](http://www.codata.org/publications/data-science-journal) \(de CODATA\). Para una revisión integral de las revistas de datos, consulta [Candela et al.](https://doi.org/10.1002%2Fasi.23358)

La [Guía de Expertos en Gestión de Datos - CESSDA ERIC](https://www.cessda.eu/Research-Infrastructure/Training/Expert-tour-guide-on-Data-Management/6.-Archive-Publish/Data-publishing-routes) proporciona una perspectiva de las ventajas y desventajas de las diferentes rutas para la publicación de datos. A veces, tu financiador u otro organismo externo te requerirá que utilices un repositorio específico. Si puedes elegir libremente, puedes considerar el orden de preferencia en las [recomendaciones de OpenAIRE](https://www.openaire.eu/opendatapilot-repository-guide):

1. Utiliza un archivo de datos externo o repositorio ya establecido en tu área de investigación para preservar los datos, de acuerdo con estándares reconocidos en tu disciplina.

2. Si está disponible, usa un repositorio de datos de investigación institucional, o la infraestructura de administración de datos de tu grupo de investigación.

3. Utiliza un repositorio de datos gratuito como por ejemplo [Dataverse](https://en.wikipedia.org/wiki/Dataverse), [Dryad](https://datadryad.org/pages/faq#depositing-cost), [figshare](https://en.wikipedia.org/wiki/Figshare) o [Zenodo](https://en.wikipedia.org/wiki/Zenodo).

4. Busca otros repositorios de datos en [re3data](https://www.re3data.org/). No hay una única opción de filtro en re3data que cubra los principios FAIR, pero teniendo en cuenta las siguientes opciones de filtro podrás encontrar repositorios compatibles con FAIR: categorías de acceso, licencias de uso de datos, repositorios de datos confiables \(con un certificado o que adhieren explícitamente a estándares para el archivo\) y si un repositorio asigna a los datos un identificador persistente \(PID\). Otro aspecto a considerar es si el repositorio admite el control de versiones.

## <img src="../Images/Icons/archive.png" width="150" height="150" />
Deberías considerar dónde depositar y publicar tus datos en tu plan de gestión de datos de investigación. CESSDA ofrece algunas preguntas prácticas que es recomendable considerar. Por ejemplo: ¿Qué datos y metadatos asociados, documentación y código serán depositados? ¿Cuánto tiempo deben conservarse los datos? ¿Por cuánto tiempo deben permanecer reutilizables los datos? ¿Cómo estarán disponibles los datos? ¿Qué categoría de acceso se elegirá? Para más preguntas, consulta [Adap your DMP: parte 6.](https://www.cessda.eu/Research-Infrastructure/Training/Expert-Tour-Guide-on-Data-Management/6.-Archive-Publish/Adapt-your-DMP-part-6) Por otro lado, no se debe olvidar verificar si el repositorio elegido cumple con los requisitos de tu investigación y de tu financiador. Algunos repositorios ya han obtenido una certificación, como CoreTrustSeal, que los certifica como confiables y capaces de cumplir con los Requisitos Centrales para Repositorios de Datos Fiables \(_Core Trustworthy Data Repositories Requirements_\). Vale la pena mencionar que algunos repositorios de dominio específico pueden aceptar únicamente datos de alta calidad, con potencial para la reutilización y que pueden compartirse públicamente.

Dado que hay varias rutas para publicar tus datos, debes notar que para que un conjunto de datos "sea válido" como una publicación, debe seguir un proceso de publicación similar al de un artículo \([Brase et al., 2009](https://doi.org/10.3233/ISU-2009-0595)\) y debería ser:

* Adecuadamente documentado con metadatos;

* Revisado con relación a su calidad \(por ejemplo: contenido del estudio, metodología, relevancia, consistencia legal y documentación de los materiales\);

* Buscable y descubrible en catálogos \(o bases de datos\);

* Citable en artículos.

## <img src="../Images/Icons/metadata.png" width="150" height="150" />
##### Cita de datos

Los servicios de cita de datos ayudan a las comunidades de investigación a descubrir, identificar y citar datos de investigación \(y a menudo otros objetos de investigación\) con confianza. Esto implica, generalmente, la creación y asignación de Identificadores de Objetos Digitales \(DOIs\) y metadatos que los acompañan a través de servicios como [DataCite](https://www.datacite.org/), que puede integrarse con flujos de investigación y estándares. Este es un campo emergente e involucra aspectos tales como transmitir a las editoriales de revistas la importancia de la cita apropiada de datos en los artículos, así como también permitir que los artículos de investigación se vinculen con los datos subyacentes. A través de esto, los datos citables se convierten en contribuciones legítimas al proceso de comunicación académica, y pueden ayudar a allanar el camino para nuevas métricas y modelos de publicación que reconozcan y recompensen el intercambio de datos.

Como paso inicial hacia una buena práctica para la cita de datos, el Grupo de Síntesis de Cita de Datos de FORCE11 ha presentado la Declaración Conjunta de Principios para la Cita de Datos [Joint Declaration of Data Citation Principles](https://doi.org/10.25490/a97f-egyk), dirigida a investigadores y proveedores de servicios de datos. Adhiriendo a estos principios, los repositorios de datos generalmente proporcionan a los investigadores una referencia que pueden usar cuando se refieren a un set de datos específico.

## <img src="../Images/Icons/database.png" width="150" height="150" />
##### Empaquetamiento de datos

Los paquetes de datos son contenedores para describir y compartir archivos de datos, y generalmente incluyen un archivo de metadatos que describe las características y el contexto de un conjunto de datos. Esto puede incluir aspectos tales como información de creación, procedencia, tamaño, tipo de formato, definiciones de campos, así como cualquier otro archivo contextual relevante, como scripts de creación de datos o documentación textual. De la [Guía para el Empaquetado de Datos](https://github.com/saverkamp/beyond-open-data/blob/master/DataGuide.md):

* Los datos son para siempre: los conjuntos de datos sobreviven a su propósito original. Las limitaciones de los datos pueden ser obvias dentro de su contexto original, como un catálogo de biblioteca, pero pueden no ser evidentes una vez que los datos se han separado de la aplicación para la que se crearon.

* Los datos no pueden ser autosuficientes: la información sobre el contexto y la procedencia de los datos \(cómo y por qué se creó, qué objetos y conceptos del mundo real representan, las limitaciones de sus valores\) es necesaria para ayudar a los consumidores a interpretarlos de manera responsable.

* La estructuración de metadatos sobre conjuntos de datos de una manera estándar y legible por máquinas fomenta la promoción, la capacidad de intercambio y la reutilización de los datos.

## <img src="../Images/Icons/privacy.png" width="150" height="150" />
##### Compartiendo datos confidenciales o privados

Con una planificación de gestión de datos adecuada, los datos confidenciales y privados pueden compartirse, reutilizar y ser FAIR. Los metadatos casi siempre pueden compartirse. La orientación y las mejores prácticas para compartir datos confidenciales son necesariamente específicas de cada región debido a las diferentes reglamentaciones \(véase, por ejemplo, el [Companion material for Managing and Sharing Research Data handbook del UKDS](https://www.ukdataservice.ac.uk/manage-data/handbook)\). La Asociación Internacional de Servicios y Tecnología de la Información en Ciencias Sociales ([International Association for Social Science Information Services and Technology)](http://www.iassistdata.org/resources/data-management/best-practices) mantiene una lista de guías internacionales sobre gestión de datos que es un buen punto de partida. Hay diferentes enfoques e iniciativas para ayudar a los investigadores a lograr esto. La herramienta [DCC's DMPonline](http://www.dcc.ac.uk/dmponline) incluye plantillas para financiadores. La Guía de Expertos en Gestión de Datos [CESSDA](https://www.cessda.eu/Research-Infrastructure/Forining/Expert-tour-guide-on-Data-Management/5.-Protect/Ethics-and-data-protection) proporciona información y ejemplos prácticos sobre cómo compartir datos personales o que poseen derechos de autor y problemas de bases de datos en países europeos. La Guía también ofrece una descripción general del impacto del GDPR que armonizará la legislación sobre datos personales en Europa \(mayo de 2018\) y proporciona una visión general actualizada sobre la [diversidad en la UE en materia de protección de datos](https://www.cessda.eu/Research-Infrastructure/Training/Expert-tour-guide-on-Data-Management/5.-Protect/Processing-personal-data/Diversity-in-data-protection).

###### Intermediarios de datos

Los intermediarios de datos son partes informadas e independientes que actúan como administradores de datos confidenciales. Los investigadores pueden transferir sus datos confidenciales y su jurisdicción sobre el acceso a esos datos al intermediario. Esto es especialmente común con datos de pacientes en estudios clínicos. Los intermediarios proporcionan un nivel de independencia en la evaluación de qué solicitudes de datos son científicamente válidas y no violan la privacidad de los participantes de la investigación. Algunos ejemplos de intermediarios de datos son [The YODA Project](http://yoda.yale.edu/), [ClinicalStudyDataRequest.com](https://www.clinicalstudydatarequest.com/), [National Sleep Research Resource](https://sleepdata.org/) y [Supporting Open Access for Researchers \(SOAR\)](https://dcri.org/our-approach/data-sharing/).

## <img src="../Images/Icons/data.png" width="150" height="150" />
##### Portales de análisis

Los portales de análisis son plataformas que permiten el análisis aprobado de datos sin permitir el pleno acceso \(visualización o descarga\) o controlar desde dónde y quién obtiene acceso. Algunos intermediarios de datos también usan portales de análisis. Los portales de análisis controlan qué conjuntos de datos adicionales se pueden combinar con los datos confidenciales, así como qué análisis se pueden ejecutar para garantizar que la información personal no se revele durante el nuevo análisis. Algunos ejemplos de portales de análisis virtuales son [Project Data Sphere](https://www.projectdatasphere.org/projectdatasphere/html/home), [Vivli](http://vivli.org/), [RAIRD](http://raird.no/), [Corpuscle](http://clarino.uib.no/korpuskel/page), y [INESS](http://clarino.uib.no/iness/page).

Las ciencias sociales y otros investigadores que emplean datos confidenciales usan un portal de análisis de un único sitio al que sólo se puede acceder mediante un régimen controlado. Los investigadores aprobados pueden acceder a los datos en el sitio, en una sala segura, para fines científicos. Sin embargo, los metadatos que describen los datos deben estar disponibles en abierto y adherirse a los principios FAIR.

##### Datos des-identificados y sintéticos

Muchos conjuntos de datos que contienen información privada de participantes pueden compartirse una vez que el conjunto de datos se ha des-identificado \(Método de Puerto Seguro\) \(_Safe Harbor Method_\) o un experto ha determinado que el conjunto de datos no es identificable a nivel individual \(método de determinación experta\). Consulta con tu Comité de Ética de la Investigación/Junta de Revisión Institucional para aprender cómo hacer esto con tus datos. También recomendamos la [Guía de Expertos en Gestión de Datos CESSDA](https://www.cessda.eu/Research-Infrastructure/Forining/Expert-tour-guide-on-Data-Management/5.-Protect/Ethics-and-data-protection), que proporciona información y ejemplos prácticos sobre cómo compartir datos personales. Sin embargo, algunos conjuntos de datos no se pueden des-identificar y compartir de forma segura. Los investigadores pueden, no obstante, mejorar la apertura de la investigación sobre los datos mediante la creación y el intercambio de datos sintéticos. Los datos sintéticos son similares en estructura, contenido y distribución a los datos reales y apuntan a obtener "validez analítica": los análisis estadísticos arrojarán los mismos resultados para los datos sintéticos que los datos reales. La Oficina del Censo de los Estados Unidos \(_United States Census Bureau_\), por ejemplo, utiliza [portales de datos sintéticos y de análisis](https://census.gov/content/dam/Census/programs-surveys/sipp/methodology/SSBdescribe_nontechnical.pdf\) de manera combinada para permitir la reutilización de datos altamente sensibles.

###### Etiquetado de datos \(_DataTags_\)

[DataTags](https://datatags.org/) es un marco diseñado para permitir evaluaciones asistidas por computadora de restricciones legales, contractuales y políticas que rigen las decisiones sobre el intercambio de datos. El sistema DataTags hace a un usuario una serie de preguntas para determinar las propiedades clave de un conjunto de datos y aplica reglas inferenciales para determinar qué leyes, contratos y buenas prácticas son aplicables. El resultado es un conjunto de DataTags recomendados, o etiquetas simples e icónicas que representan una política de datos legible por humanos y utilizable por máquinas, y un acuerdo de licencia a medida para el conjunto de datos. El sistema DataTags está siendo diseñado para integrarse con el software del repositorio de datos y también funcionará como una herramienta independiente. DataTags se está desarrollando en la Universidad de Harvard. En Europa, DANS está trabajando para ajustar DataTags a la legislación europea _General Data Protection Regulation_ \([GDPR](https://www.eugdpr.org/)\) \(ver [DANS GDPR DataTags](https://zingtree.com/host.php?style=buttons&tree_id=442670046&persist_names=Restart&persist_node_ids=58#58)\).

Como se mencionó anteriormente, el objetivo final de compartir tus datos de investigación es hacerlos reutilizables al máximo. Para ello, antes de compartir datos debes gestionarlos de acuerdo con las mejores prácticas. Esto incluye, por ejemplo, la documentación y la elección de formatos de archivos y licencias abiertos. Puedes leer más sobre estos temas en [Sección 4: Investigación reproducible y análisis de datos](#heading=h.jy7n9xm9zn9o) así como [Sección 6: Licenciamiento abierto y formatos de archivo](#heading=h.3rdryh4tn529).

## <img src="../Images/Icons/usb.png" width="150" height="150" />
##### Materiales abiertos

Además de compartir los datos, la apertura de la investigación depende del intercambio de materiales. Los materiales que utilizan los investigadores son específicos de cada disciplina y, a veces, exclusivos de un laboratorio. A continuación hay ejemplos de materiales que puedes compartir. Siempre consulta con pares de tu disciplina qué repositorios utilizan. Cuando tengas materiales, datos y publicaciones del mismo proyecto de investigación compartidos en diferentes repositorios, haz una referencia cruzada con un enlace y un identificador único para que puedan ubicarse fácilmente.

###### Reactivos

Un reactivo es una sustancia, compuesto o mezcla que se puede agregar a un sistema para crear una reacción química o de otro tipo. Los reactivos se pueden depositar en repositorios como [Addgene](https://www.addgene.org/), [The Bloomington Drosophila Stock Center](https://bdsc.indiana.edu/) y [ATCC](https://www.atcc.org/) para que sean fácilmente accesibles para otros investigadores. Licencia tus materiales para que puedan ser reutilizados por otros investigadores.

###### Protocolos

Un protocolo describe un registro formal u oficial de observaciones experimentales científicas en un formato estructurado. Deposita los protocolos virtuales para su cita, adaptación y reutilización empleando [Protocolos](https://www.protocols.io/).

###### Cuadernos, contenedores, software y hardware

El uso de la programación literaria, la tecnología de contenedores y la virtualización ayudan al análisis reproducible. Además de compartir tu código y tus datos, también comparte tus cuadernos Jupyter, imágenes Docker u otros materiales de análisis o dependencias de software. Comparte cuadernos con servicios abiertos como [mybinder](http://mybinder.org) que permiten la visualización y ejecución pública de todo el block de notas de manera compartida. Los contenedores y los cuadernos se pueden compartir con [Rocker](https://arxiv.org/abs/1710.03675) o [Code Ocean](https://codeocean.com/). El software y el hardware utilizados en tu investigación se deben compartir siguiendo buenas prácticas para la documentación, tal como se describe en la [Sección 3](**03OpenResearchSoftwareAndOpenSource.md**). Los protocolos de sólo lectura deben depositarse en un registro de tu disciplina, como [ClinicalTrials.gov](https://clinicaltrials.gov/) y [SocialScienceRegistry](https://www.socialscienceregistry.org/), o en un registro general como [Open Science Framework](https://osf.io/). Muchas revistas, como [Trials](https://trialsjournal.biomedcentral.com/), [JMIR Research Protocols](https://www.researchprotocols.org/) o [Bio-Protocol](https://bio-protocol.org/) publicarán tu protocolo. Las mejores prácticas para publicar tu protocolo en Acceso Abierto son las mismas que para publicar tu informe en Acceso Abierto \(mira la [Sección 5](#heading=h.go419g8z6pnt)\).


## <img src="../Images/Icons/questions.png" width="150" height="150" />
### Preguntas, obstáculos y equivocaciones comunes

P: "¿Es suficiente hacer que mis datos estén disponibles de manera abierta?"

R: "No, la apertura es una condición necesaria pero no suficiente para una reutilización máxima. Los datos tienen que ser FAIR además de abiertos".

P: "¿Qué significan/implican los principios FAIR para diferentes partes interesadas/audiencias?"

R: "¡Este es un gran tema para discusión!"

Obstáculo: los investigadores pueden ser reacios a compartir sus datos porque temen que otros los reutilicen antes de haberlos aprovechado al máximo, o que otros podrían no comprender completamente sus datos y, por lo tanto, hacer un mal uso de ellos.

\(sugerido \) R: Puedes publicar tus datos con metadatos para que ellos se puedan encontrar, pero establecer un período de embargo en los datos para asegurarte de que puedes publicar tus propios artículos primero.

P: "¿Implica mucho trabajo extra hacer que mis datos sean FAIR?"

R: "¡No necesariamente! Hacer que los datos sean FAIR no sólo es responsabilidad de los investigadores individuales sino de todo el grupo de investigadores. La mejor manera de garantizar que tus datos son FAIR es crear un Plan de Gestión de Datos y planificar todo de antemano. Durante la recolección y el procesamiento de datos sigue los estándares de tu disciplina y las medidas recomendadas por un repositorio.

P: "Quiero compartir mis datos. ¿Cómo debo licenciarlos?"

R: "Esa es una buena pregunta. Primero, piensa en quién posee la propiedad de los datos: un financiador de la investigación o una institución para la que trabajas. Luego, piensa en la autoría. La aplicación de una licencia adecuada a sus datos es crucial para hacerlos reutilizables. Para más información sobre las licencias, consulta la [Sección 6: Licenciamiento abierto y formatos de archivo](#heading=h.3rdryh4tn529).

P: "No puedo hacer que mis datos estén disponibles de manera directa: son demasiado grandes para compartir de manera conveniente/tienen restricciones relacionadas con cuestiones de privacidad. ¿Qué debo hacer?"

R: "Debería hablar con expertos en repositorios de dominio específico sobre cómo obtener instrucciones suficientes para hacer que sus datos sean encontrables y accesibles".


## <img src="../Images/Icons/output.png" width="150" height="150" />
### Resultados de aprendizaje

1. Comprender las características de los datos abiertos, y en particular los principios FAIR.

2. Estar familiarizado con algunos de los argumentos a favor y en contra de los datos abiertos.

3. Ser capaz de diferenciar y trabajar con datos confidenciales y datos abiertos/FAIR; estas dos categorías no son necesariamente incompatibles.

4. Ser capaz de transformar un conjunto de datos en uno que pueda compartirse en abierto \(formato no privado\), cumpla con los estándares de los principios FAIR y esté diseñado para maximizar la accesibilidad, la transparencia y la reutilización, proporcionando metadatos suficientes.

5. Conocer la diferencia entre datos primarios y procesados \(o depurados\), y la importancia de las etiquetas de versión.

6. Conocer los formatos de archivo más comunes y los estándares comunitarios para asegurar la máxima reutilización.

7. Ser capaz de escribir un Plan de Gestión de Datos.

## <img src="../Images/Icons/magnifying_glass.png" width="150" height="150" />
### Lecturas adicionales

* The FAIR Guiding Principles for scientific data management and stewardship: [https://www.nature.com/articles/sdata201618](https://www.nature.com/articles/sdata201618)

* Guiding principles for Findable, Accessible, Interoperable, and Re-usable data publishing Version B1.0: [https://www.force11.org/fairprinciples](https://www.force11.org/fairprinciples)

* The FAIR Data Principles explained
 [https://www.dtls.nl/fair-data/fair-principles-explained/](https://www.dtls.nl/fair-data/fair-principles-explained/)

* GO FAIR Initiative: [https://www.go-fair.org/](https://www.go-fair.org/)

* FAIR Metrics: [http://fairmetrics.org/](http://fairmetrics.org/)

* Cloudy, increasingly FAIR; revisiting the FAIR Data guiding principles for the European Open Science Cloud: [https://doi.org/10.3233/ISU-170824](https://doi.org/10.3233/ISU-170824)

* [Making data sharing count: a publication-based solution](https://www.frontiersin.org/articles/10.3389/fnins.2013.00009/full) \(Gorgolewski et al., 2013\).

* [Data reuse and the open data citation advantage](https://peerj.com/articles/175/) \(Piwowar and Vision, 2013\).

* Expert tour guide on data management [https://www.cessda.eu/Research-Infrastructure/Training/Expert-tour-guide-on-Data-Management](https://www.cessda.eu/Research-Infrastructure/Training/Expert-tour-guide-on-Data-Management)

* [Making Data Count](https://www.nature.com/articles/sdata201539) \(Kratz and Strasser, 2015\).

* [Data packaging guide](https://github.com/saverkamp/beyond-open-data/blob/master/DataGuide.md).

* CESSDA ERIC, ["Citing your data"](https://www.cessda.eu/Research-Infrastructure/Training/Expert-tour-guide-on-Data-Management/6.-Archive-Publish/Publishing-with-CESSDA-archives/Citing-your-data)

* 5 ★ OPEN DATA, [http://5stardata.info/en/](http://5stardata.info/en/)
