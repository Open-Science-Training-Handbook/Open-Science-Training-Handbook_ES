## <img src="/Images/Icons/open_data.png" width="200" height="200" />
## 2. Materiales y datos de investigación abierta

### ¿En qué consiste?

Los datos de investigación abierta son datos a los que se puede acceder libremente, reutilizar, remezclar y redistribuir, para fines académicos como la investigación y docencia. Idealmente, los datos abiertos no debiese tener limitación a su reutilización y distribución, y deben contar con licencias acorde. Se pueden incluir restricciones limitadas o especiales en casos excepcionales ej. para proteger la identidad de individuos particulares. Compartir abiertamente datos promueve la inspección, formando la base para la reproducibilidad y verificación de investigación, y abre el camino a colaboración de forma más amplia.  A lo sumo, los datos abiertos pueden estar sujetos al requisito de atribuir y compartir \(ver en [Open Data Handbook](http://opendatahandbook.org/guide/en/what-is-open-data)\)

## <img src="/Images/Icons/data2.png" width="150" height="150" />
### Justificación

Los datos de investigación a menudo son el resultado más valioso de muchos proyectos de investigación, se utilizan como fuentes primarias que sustentan la investigación científica y permiten la derivación de hallazgos teóricos o aplicados. Para hacer que los hallazgos/estudios sean replicables, o al menos reproducibles o reutilizables (\referencia a la Investigación y Análisis de datos reproducibles\) de cualquier forma, la recomendación de mejores prácticas para los datos de investigación debe ser tan abierta como [FAIR](https://www.force11.org/fairprinciples) como sea posible, teniendo en cuenta las limitaciones éticas, comerciales y de privacidad con datos confidenciales o de propiedad.

![](/Images/Icons/finish.png)

### Objetivos de aprendizaje 

1. Obtener una comprensión de las características y principios básicos de los datos de investigación abiertos y FAIR, incluido el empaquetado y la documentación apropiados, para permitir que otros los entiendan, reproduzcan y reutilicen de maneras alternativas.

2. Familiarizarse con los tipos de datos que pueden considerarse sensibles y las restricciones legales o limitaciones para compartirlos abiertamente.

3. Ser capaz de convertir un conjunto de datos "cerrado" en uno que sea "abierto" mediante la implementación de las medidas necesarias en un plan de gestión de datos, con una gestión de datos y metadatos apropiados.

4. Ser capaz de utilizar el plan de gestión de datos de investigación y hacer que los resultados de su investigación sean asequibles y accesibles, incluso si contienen datos potencialmente sensibles.

5. Comprender los pros y los contras de compartir abiertamente diferentes tipos de datos \(por ejemplo, privacidad, sensibilidad, desidentificación, acceso mediado\).

6. Comprender la importancia de los metadatos apropiados para el archivo sostenible de datos de investigación.

7. Comprender los flujos de trabajo básicos y las herramientas para compartir datos de investigación.

### Componentes clave

#### Habilidades de conocimiento
## <img src="/Images/Icons/brain.png" width="150" height="150" /><img src="/Images/Icons/gears.png" width="150" height="150" />
##### Principios FAIR

En 2014, se redactó un conjunto básico de principios para optimizar la reutilización de los datos de investigación, denominados [FAIR Data Principles](https://www.force11.org/group/fairgroup/fairprinciples). Representan un conjunto de directrices y mejores prácticas desarrolladas por la comunidad para garantizar que los datos o cualquier objeto digital sean **F**indable (encontrable), **A**ccessible (asequible), **I**nteroperable (interoperable) and **R**e-usable (reutilizable):

**Encontrable:**  Lo primero que se debe hacer para que los datos sean reutilizables es la posibilidad de encontrarlos. Debería ser fácil encontrar los datos y los metadatos tanto para humanos como para computadoras. El descubrimiento automático y confiable de conjuntos de datos y servicios depende de los identificadores persistentes \ (PIDs\) legibles por máquina y los metadatos. 

**Asequible:** Los datos y  metadatos deberían poder recuperarse mediante su identificador utilizando un protocolo de comunicaciones abierto y estandarizado, que posiblemente incluya autenticación y autorización. Además, los metadatos deberían estar disponibles incluso cuando los datos ya no estén disponibles.

**Interoperable:** Los datos deberían poder combinarse y usarse con otros datos o herramientas. Por lo tanto, el formato de los datos deben ser abiertos e interpretables para varias herramientas, incluidos otros registros de datos. El concepto de interoperabilidad se aplica tanto a nivel de datos como de metadatos. Por ejemplo, los metadatos deberían usar vocabularios que sigan los principios FAIR.

**Re-utilizable:** En última instancia, FAIR tiene como objetivo optimizar la reutilización de datos. Para lograr esto, los metadatos y datos deben estar bien descritos para que puedan ser replicados y / o combinados en diferentes configuraciones. Además, la reutilización de los datos y metadata debe estar indicado con  meta datos debe indicarse con licencias clara y accesibles. 

A diferencia de las iniciativas de pares que se centran en el investigador humano, los principios FAIR ponen un énfasis específico en mejorar la capacidad de las máquinas para encontrar y utilizar automáticamente datos o cualquier objeto digital, además de apoyar su reutilización por parte de individuos. Los principios de FAIR son principios rectores, no estándares. FAIR describe las cualidades o los comportamientos necesarios para que los datos sean reutilizables al máximo \(ej. descripción, cita\). Esas cualidades se pueden lograr con diferentes estándares.


![](/Images/02 Open Science Basics/02_open_research_data_material.png)

##### Publicación de datos

La mayoría de los investigadores están más o menos familiarizados con publicación Open Access de artículos de investigación y libros \(véase el capítulo 5\). Más recientemente, y por las razones mencionadas anteriormente, la publicación de datos ha ganado una atención cada vez mayor. Cada vez más donantes esperan que los datos producidos en los proyectos de investigación que financian sean fáciles de encontrar, accesibles y lo más abiertos posible. 

Hay varias formas diferentes para hacer que los datos de investigación sean accesibles, incluyendo  \([Wikipedia](https://en.wikipedia.org/wiki/Data_publishing)\):

* Publicación de datos como material complementario asociado con un [artículo de investigación] (https://en.wikipedia.org/wiki/Research_article), generalmente con los archivos de datos alojados por el editor del artículo. 

* Hospedaje de datos en un sitio web disponible públicamente, con archivos disponibles para su descarga. 

* Depósito de datos en un repositorio que se ha desarrollado para admitir la publicación de datos, ej.,[Dataverse](https://en.wikipedia.org/wiki/Dataverse), \[Dryad\]\([https://en.wikipedia.org/wiki/Dryad\_\(repository](https://en.wikipedia.org/wiki/Dryad_%28repository)\)\), [figshare](https://en.wikipedia.org/wiki/Figshare), [Zenodo](https://en.wikipedia.org/wiki/Zenodo). 

* Existe una gran cantidad de repositorios de datos generales y de dominios o temas específicos que pueden proporcionar apoyo adicional a los investigadores al depositar sus datos.

* Publicación de un documento de datos sobre el conjunto de datos, que puede publicarse como un preprint, en una revista o en una revista de datos dedicada a respaldar documentos de datos. Los datos pueden ser alojados por la revista o alojados por separado en un repositorio de datos. Algunos ejemplos de publicaciones periódicas incluyen [Scientific Data] (https://www.nature.com/sdata/) por SpringerNature y [Data Science Journal] (http://www.codata.org/publications/data-science-journal) por CODATA. Para una revisión completa de las publicaciones de datos, ver [Candela et al.] (Https://doi.org/10.1002%2Fasi.23358)

La [Guía de expertos en gestión de datos - CESSDA ERIC] (https://www.cessda.eu/Research-Infrastructure/Training/Expert-tour-guide-on-Data-Management/6.-Archive-Publish/Data-publishing-routes) proporciona una descripción general de los pros y los contras de las diferentes rutas de publicación de datos. A veces, su financiador u otra parte externa requiere que use un repositorio específico. Si puede elegir libremente, puede considerar el orden de preferencia en las [recomendaciones OpenAIRE] (https://www.openaire.eu/opendatapilot-repository):

1. Utiliza un archivo de datos externo o repositorio ya establecido para su dominio de investigación para preservar los datos de acuerdo con los estándares reconocidos en tu disciplina.

2. Si está disponible, usa un repositorio de datos de investigación institucional o las instalaciones de administración de datos establecidas de tu grupo de investigación.

3. Utiliza un repositorio de datos sin costo como [Dataverse](https://en.wikipedia.org/wiki/Dataverse), [Dryad](https://datadryad.org/pages/faq#depositing-cost), [figshare](https://en.wikipedia.org/wiki/Figshare) o [Zenodo](https://en.wikipedia.org/wiki/Zenodo).

4.  Busca otros repositorios de datos en [re3data] (https://www.re3data.org/). No hay una única opción de filtro en re3data que cubra los principios FAIR, pero teniendo en cuenta las siguientes opciones de filtro, podrás encontrar repositorios compatibles con FAIR: categorías de acceso, licencias de uso de datos, repositorios de datos confiables (con un certificado o apegados explícitamente a estándares de archivo) y si un repositorio da a los datos un identificador persistente \(PID\). Otro aspecto a considerar es si el repositorio admite el control de versiones. 

## <img src="/Images/Icons/archive.png" width="150" height="150" />
Debería considerarse dónde depositar y publicar sus datos ya en tu plan de gestión de datos de investigación. CESSDA ofrece algunas preguntas prácticas, que se recomiendan considerar. Por ejemplo: ¿Qué datos y metadatos asociados, documentación y código serán depositados? ¿Cuánto tiempo deben conservarse los datos? ¿Por cuánto tiempo los datos deben permanecer reutilizables? ¿Cómo estarán disponibles los datos? ¿Qué categoría de acceso se elegirá? Para obtener más información, consulta [Adap your DMP: parte 6.] (https://www.cessda.eu/Research-Infrastructure/Training/Expert-Tour-Guide-on-Data-Management/6.-Archive-Publish/Adapt-your-DMP-part-6) Por otro lado, no se debe olvidar verificar si un repositorio elegido cumple con los requisitos de su investigación y de su financiador. Algunos repositorios ya han obtenido la certificación, como CoreTrustSeal, que los certifica como confiables y capaces de cumplir con los requisitos Centrales de Repositorios de Datos Fiables (Core Trustworthy Data Repositories Requirements). Vale la pena mencionar que algunos repositorios específicos de dominio pueden aceptar solo datos de alta calidad con potencial de reutilización y que pueden compartirse públicamente.

Dado que hay varias rutas para publicar sus datos, debe tenerse en cuenta que para que un conjunto de datos "cuente" como publicación, debe seguir un proceso de publicación similar a un artículo \([Brase et al., 2009](https://doi.org/10.3233/ISU-2009-0595)\) y debería ser:

* Documentado adecuadamente con metadata;

* Se revisó la calidad, ej: contenido del estudio, metodología, relevancia, consistencia legal y documentación de materiales;

* Se puede buscar y descubrir en catálogos (o bases de datos);

* Citable en artículos.

## <img src="/Images/Icons/metadata.png" width="150" height="150" />
##### Cita de datos

Los servicios de citas de datos ayudan a las comunidades de investigación a descubrir, identificar y citar datos de investigación (y a menudo otros objetos de investigación) con confianza. Esto generalmente implica la creación y asignación de Identificadores de Objetos Digitales (DOIs) y los metadatos que los acompañan a través de servicios como DataCite \([https://www.datacite.org/](https://www.datacite.org/)\), y se puede integrar con flujos de trabajo de investigación y estándares. Este es un campo emergente e involucra aspectos tales como transmitir a los editores de revistas la importancia de la cita de datos apropiada en los artículos, así como también permitir que los artículos de investigación se vinculen con los datos subyacentes. A través de esto, los datos de citable se convierten en contribuciones legítimas al proceso de comunicación académica, y pueden ayudar a allanar el camino para nuevas métricas y modelos de publicación que reconocen y recompensan el intercambio de datos
Como paso inicial hacia una buena práctica para la cita de datos, el Grupo de síntesis de citas de datos de FORCE11 ha presentado la Declaración Conjunta de Principios de Citas de Datos [Joint Declaration of Data Citation Principles] (https://doi.org/10.25490/a97f-egyk), dirigida a investigadores y proveedores de servicios de datos. Siguiendo estos principios, los repositorios de datos generalmente proporcionan a los investigadores una referencia que pueden usar cuando se refieren a un set de datos específico.

## <img src="/Images/Icons/database.png" width="150" height="150" />
##### Empaquetamiento de datos

Los paquetes de datos son contenedores para describir y compartir archivos de datos adjuntos, y generalmente comprenden un archivo de metadata que describe las características y el contexto de un conjunto de datos. Esto puede incluir aspectos tales como información de creación, procedencia, tamaño, tipo de formato, definiciones de campo, así como cualquier archivo contextual relevante, como scripts de creación de datos o documentación textual. De la [Guía de Empaquetado de Datos] (https://github.com/saverkamp/beyond-open-data/blob/master/DataGuide.md):

* Los datos son para siempre: los conjuntos de datos sobreviven a su propósito original. Las limitaciones de los datos pueden ser obvias dentro de su contexto original, como un catálogo de la biblioteca, pero pueden no ser evidentes una vez que los datos se han divorciado de la aplicación para la que se crearon.

* Los datos no pueden ser independientes: la información sobre el contexto y la procedencia de los datos (cómo y por qué se creó, qué objetos y conceptos del mundo real representa, las limitaciones de los valores) es necesaria para ayudar a los consumidores a interpretarla de manera responsable.

* La estructuración de metadatos sobre conjuntos de datos de una manera estándar, legible por máquina, fomenta la promoción, capacidad de ser compartidos y reutilización de datos.

## <img src="/Images/Icons/privacy.png" width="150" height="150" />
##### Compartir datos confidenciales o protegidos 

Con una planificación de gestión de datos adecuada, los datos confidenciales y protegidos se pueden compartir, reutilizar y FAIR. Los metadatos casi siempre se pueden compartir. La orientación y las mejores prácticas para compartir datos confidenciales son necesariamente específicas de la región debido a las diferentes reglamentaciones (véase, por ejemplo, el [Companion material for Managing and Sharing Research Data handbook del UKDS] (https://www.ukdataservice.ac.uk/manage-data/handbook). [La Asociación Internacional de Servicios y Tecnología de la Información en Ciencias Sociales (International Association for Social Science Information Services and Technology)] (http://www.iassistdata.org/resources/data-management/best-practices) mantiene una lista de guías internacionales en gestión de datos que es un buen punto de partida. Hay varios enfoques e iniciativas para ayudar a los investigadores a lograr esto. [La herramienta DCC DMPonline] (http://www.dcc.ac.uk/dmponline) incluye una serie de plantillas para los financiadores. [La guía turística de expertos de CESSDA sobre gestión de datos] (https://www.cessda.eu/Research-Infrastructure/Forining/Expert-tour-guide-on-Data-Management/5.-Protect/Ethics-and-data-protection) proporciona información y ejemplos prácticos sobre cómo compartir datos personales y sobre derechos de autor y problemas de bases de datos en los países europeos. La Guía también ofrece una descripción general del impacto del GDPR que armonizará la legislación sobre datos personales en Europa (mayo de 2018) y proporciona una visión general actualizada sobre la Diversidad en la UE en materia de protección de datos (https://www.cessda.eu/Research-Infrastructure/Training/Expert-tour-guide-on-Data-Management/5.-Protect/Processing-personal-data/Diversity-in-data-protection).

###### Intermediarios de datos 

Los intermediarios de datos son partes informadas e independientes que actúan como administradores de datos para datos confidenciales. Los investigadores pueden transferir sus datos confidenciales y su jurisdicción sobre el acceso a esos datos al intermediario. Esto es especialmente común con datos a nivel del paciente de estudios clínicos. Los intermediarios proporcionan un nivel de independencia en la evaluación de las solicitudes de datos que son científicamente válidas y no violarán la privacidad de los participantes de la investigación. Algunos ejemplos de intermediarios de datos incluyen [The YODA Project] (http://yoda.yale.edu/), [ClinicalStudyDataRequest.com] (https://www.clinicalstudydatarequest.com/), [National Sleep Research Resource](https://sleepdata.org/) y [Supporting Open Access for Researchers \(SOAR\)](https://dcri.org/our-approach/data-sharing/).

## <img src="/Images/Icons/data.png" width="150" height="150" />
##### Portales de análisis

Los portales de análisis son plataformas que permiten el análisis aprobado de datos sin permitir el pleno acceso (visualización o descarga) o el control de dónde y quién obtiene acceso. Algunos intermediarios de datos también usan portales de análisis. Los portales de análisis controlan qué conjuntos de datos adicionales se pueden combinar con los datos confidenciales, así como qué análisis se pueden ejecutar para garantizar que la información personal no se revele durante el reanálisis. Los ejemplos de portales de análisis virtuales incluyen [Project Data Sphere] (https://www.projectdatasphere.org/projectdatasphere/html/home), [Vivli] (http://vivli.org/), [RAIRD] (http://raird.no/), [Corpuscle] (http://clarino.uib.no/korpuskel/page), y [INESS] (http://clarino.uib.no/iness/page).

Las ciencias sociales y otros investigadores con datos confidenciales usan un portal de análisis de un solo sitio al que se puede acceder solo bajo régimen controlado. Los investigadores aprobados pueden acceder a los datos en el sitio, en una sala segura, con fines científicos. Sin embargo, los metadatos que describen los datos deben estar abiertamente disponibles y adherirse a los principios FAIR.

##### Datos innominados y sintéticos

Muchos conjuntos de datos que contienen información privada a nivel de participante se pueden compartir una vez que el conjunto de datos se ha innominado (Método de puerto seguro) o un experto ha determinado que el conjunto de datos no es individualmente identificable (Método de determinación experta). Consulta con tu Junta de Ética de Investigación / Junta de Revisión Institucional para aprender cómo hacer esto con sus datos. También recomendamos [the CESSDA Expert Tour Guide on Data Management] (https://www.cessda.eu/Research-Infrastructure/Forining/Expert-tour-guide-on-Data-Management/5.-Protect/Ethics-and-data-protection), que proporciona información y ejemplos prácticos sobre cómo compartir datos personales. Sin embargo, algunos conjuntos de datos no se pueden innominar y compartir de forma segura. Los investigadores aún pueden mejorar la apertura de la investigación sobre dichos datos mediante la creación y el intercambio de datos sintéticos. Los datos sintéticos son similares en estructura, contenido y distribución a los datos reales y apuntan a obtener "validez analítica": el análisis estadístico arrojará los mismos resultados para los datos sintéticos que los datos reales. La Oficina del Censo de los Estados Unidos, por ejemplo, utiliza portales de datos sintéticos y de análisis (https://census.gov/content/dam/Census/programs-surveys/sipp/methodology/SSBdescribe_nontechnical.pdf) en combinación para permitir la reutilización de datos altamente sensibles.

######Etiquetado de Datos (DataTags)

[DataTags] (https://datatags.org/) es un marco diseñado para permitir evaluaciones asistidas por computadora de las restricciones legales, contractuales y de política que rigen las decisiones de intercambio de datos. El sistema DataTags le hace al usuario una serie de preguntas para obtener las propiedades clave de un conjunto de datos determinado y aplica reglas de inferencia para determinar qué leyes, contratos y mejores prácticas son aplicables. El resultado es un conjunto de DataTags recomendados, o etiquetas simples e icónicas que representan una política de datos legible por humanos y accionable por máquina, y un acuerdo de licencia que se adapta al conjunto de datos individual. El sistema DataTags está diseñado para integrarse con el software del repositorio de datos, y también funcionará como una herramienta independiente. DataTags se está desarrollando en la Universidad de Harvard. En Europa, DANS está trabajando para ajustar DataTags a la legislación europea General Data Protection Regulation [GDPR] \([GDPR](https://www.eugdpr.org/)\) \(cf. [DANS GDPR DataTags](https://zingtree.com/host.php?style=buttons&tree_id=442670046&persist_names=Restart&persist_node_ids=58#58)\).

Como se mencionó anteriormente, el objetivo final de compartir datos con sus datos de investigación es hacerlos reutilizables al máximo. Para ello, antes de compartir datos, debe gestionarlos de acuerdo con las mejores prácticas. Esto incluye, por ejemplo, documentación y la elección de formatos de archivos abiertos y licencias. Puede leer más sobre estos temas en [Sección 4: Investigación reproducible y Análisis de datos] (#heading=h.jy7n9xm9zn9o) así como [Sección 6: Licencia abierta y formatos de archivo] (#heading=h.3rdryh4tn529).

## <img src="/Images/Icons/usb.png" width="150" height="150" />
##### Materiales abiertos

Además de compartir datos, la accesibilidad de la investigación depende del intercambio de materiales. Los materiales que utilizan los investigadores son específicos de la disciplina y, a veces, exclusivos de un laboratorio. A continuación hay ejemplos de materiales que puede compartir, aunque siempre consulta con pares de tu disciplina para identificar qué repositorios se utilizan. Cuando tengas materiales, datos y publicaciones del mismo proyecto de investigación compartidos en diferentes repositorios, haz una referencia cruzada con un enlace y un identificador único para que puedan ubicarse fácilmente.

###### Reactivos

Los reactivos son una sustancia, compuesto o mezcla que se puede agregar a un sistema para crear una reacción química u otra. Los reactivos se pueden depositar en repositorios como [Addgene] (https://www.addgene.org/), [The Bloomington Drosophila Stock Center] (https://bdsc.indiana.edu/) y [ATCC] (https://www.atcc.org/) para que sean fácilmente accesibles para otros investigadores. Licencia tus materiales para que puedan ser reutilizados por otros investigadores.

###### Protocolos

Un protocolo describe un registro formal u oficial de observaciones experimentales científicas en un formato estructurado. Deposita los protocolos virtuales para citar, adaptar y reutilizar utilizando [Protocolos] (https://www.protocols.io/).

###### Cuadernos, contenedores, software y hardware

El análisis reproducible es ayudado por el uso de la programación alfabetizada, la tecnología de contenedores y la virtualización. Además de compartir su código y datos, también comparta sus cuadernos Jupyter, imágenes Docker u otros materiales de análisis o dependencias de software. Comparte cuadernos con servicios abiertos como [mybinder] (http://mybinder.org) que permitan la visualización y ejecución pública de todo el bloc de notas en recursos compartidos. Los contenedores y los cuadernos se pueden compartir con [Rocker] (https://arxiv.org/abs/1710.03675) o [Code Ocean] (https://codeocean.com/). El software y el hardware utilizados en tu investigación se deben compartir siguiendo las mejores prácticas para la documentación como se describe en [Sección 3]. Los protocolos de solo lectura deben depositarse en el registro de disciplinas, como [ClinicalTrials.gov] (https://clinicaltrials.gov/) y [SocialScienceRegistry] (https://www.socialscienceregistry.org/) o en un registro general como [Open Science] (https://osf.io/) [Framework] (https://osf.io/). Muchas revistas, como [Trials] (https://trialsjournal.biomedcentral.com/), [JMIR Research Protocols] (https://www.researchprotocols.org/) o [Bio-Protocol] (https://bio-protocol.org/), publicarán tu protocolo. Las mejores prácticas para publicar su protocolo de acceso abierto son las mismas que publicar su informe de acceso abierto (ver [Sección 5](#heading=h.go419g8z6pnt)\).


## <img src="/Images/Icons/questions.png" width="150" height="150" />
### Preguntas, obstáculos y conceptos erróneos comunes

P: "¿Es suficiente hacer que mis datos estén disponibles de manera abierta?"

R: "La ausencia de apertura es una condición necesaria pero no suficiente para una reutilización máxima. Los datos tienen que ser FAIR además de abiertos".

P: "¿Qué significan/implican los principios FAIR para diferentes partes interesadas/audiencias?"

R: "¡Este es un gran tema para discusión!"

Obstáculo: los investigadores pueden ser reacios a compartir sus datos porque temen que otros los reutilicen antes de haberles extraído el máximo uso, o que otros no comprendan completamente los datos y, por lo tanto, no los utilicen.

\(sugerido \) R: Puede publicar sus datos para que se puedan encontrar con metadatos, pero establezca un período de embargo en los datos para asegurarse de que puede publicar su propio artículo primero.

P: "¿Hacer mi información FAIR es mucho trabajo extra?"

R: "No necesariamente! Hacer datos FAIR no solo es responsabilidad de los investigadores individuales sino de todo el grupo. La mejor manera de garantizar que sus datos sean FAIR es crear un Plan de gestión de datos y planificar todo de antemano. y el procesamiento de datos sigue los estándares de disciplina y las medidas recomendadas por un repositorio.

P: "Quiero compartir mis datos. ¿Cómo debo licenciarlos?"

R: "Esa es una buena pregunta. Primero que todo, piensa en quién posee los datos: un financiador de investigación o una institución para la que trabaja. Luego, piense en la autoría. La aplicación de una licencia adecuada a sus datos es crucial para hacerlos reutilizables. Para obtener más información sobre las licencias, consulte "6. Licencia y formatos abiertos".

P: "No puedo hacer que mis datos estén disponibles de manera directa: son demasiado grandes para compartir de manera conveniente / tienen restricciones relacionadas con cuestiones de privacidad. ¿Qué debo hacer?"

R: "Debería hablar con expertos en repositorios específicos de dominio sobre cómo proporcionar instrucciones suficientes para hacer que sus datos sean encontrables y accesibles".


## <img src="/Images/Icons/output.png" width="150" height="150" />
### Resultados de aprendizaje

1. Comprender las características de los datos abiertos, y en particular los principios FAIR.

2. Familiarizarse con algunos de los argumentos a favor y en contra de los datos abiertos.

3. Ser capaz de diferenciar y abordar datos confidenciales y datos abiertos / FAIR; estas dos categorías no son necesariamente incompatibles.

4. Poder transformar un conjunto de datos en uno que sea suficiente para compartir abiertamente \ (formato no protegido por patente)\, cumpla con los estándares de los principios de FAIR y esté diseñado para maximizar el acceso, la transparencia y la reutilización al proporcionar suficientes metadatos.

5. Conozca la diferencia entre los datos sin procesar \ o procesados \ o limpiados \ y la importancia de las etiquetas de versión.

6. Conozca los formatos de archivo y estándares comunitarios comúnmente usados para una máxima reutilización.

7. Ser capaz de escribir un plan de gestión de datos.1. Understand the characteristics of open data, and in particular the FAIR principles.


## <img src="/Images/Icons/magnifying_glass.png" width="150" height="150" />
### Bibliografía sugerida

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
