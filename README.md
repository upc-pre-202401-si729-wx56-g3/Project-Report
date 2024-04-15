# UPC
# INGENIERÍA DE SISTEMAS DE SOFTWARE
## CURSO: SI729 Desarrollo de Aplicaciones Open Source | SECCIÓN WX54 
 Profesor: Hugo Allan Mori Paiva
# Informe de TB1
"TechConnect Solutions"
"OfficeTech"
### Integrantes:
- Jorge Gerardo Quilla Luyo - U20211B197
- Rony Piero Ticona Luque - U201420422
- Jair Velasquez Pizarro - U202218114
- Juan Fernando Carrasco Godos - U20211D118

14/04/2024
---
# Registro de Versiones del Informe
| Version | Fecha | Autor | Descripcion de Modificacion |
| ----------- | ----------- | ----------- | ----------- |
| 0.0 | 19/03/2024 |Grupo 1 |Se crea el documento |

# Project Report Collaboration Insights
[URL del repositorio](https://www.example.com)

(Imagenes de los commits cada entrega)


# Student Outcome
|Criterio Especifico|Acciones Realizadas|Conclusiones|
|-|-|-|
|Participa en equipos multidisciplinarios con eficacia, eficiencia y objetividad, en el marco de un proyecto en soluciones de ingeniería de software.| Jair Velasquez:<br> ***TB1:***  Su texto<br><br>Jorge Quilla:<br> ***TB1:***  Su texto<br><br>Piero Ticona:<br> ***TB1:***  Su texto<br><br>Juan Carrasco:<br> ***TB1:***  Su texto | Su texto de conclusion|
|Conoce al menos un sector empresarial o dominio de aplicación de soluciones de software.|Jair Velasquez:<br> ***TB1:***  Su texto<br><br>Jorge Quilla:<br> ***TB1:***  Su texto<br><br>Piero Ticona:<br> ***TB1:***  Su texto<br><br>Juan Carrasco:<br> ***TB1:***  Su texto | Su texto de conclusion |

# Contenido
## Tabla de contenidos

### [Capítulo I: Introducción](#capítulo-i-introducción)
- [1.1. Startup Profile](#11-startup-profile)
    - [1.1.1 Descripción de la Startup](#111-descripción-de-la-startup)
    - [1.1.2 Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
- [1.2 Solution Profile](#12-solution-profile)
    - [1.2.1 Antecedentes y problemática](#121-antecedentes-y-problemática)
    - [1.2.2 Lean UX Process](#122-lean-ux-process)
        - [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)
        - [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)
        - [1.2.2.3. Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
        - [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)
- [1.3. Segmentos objetivo](#13-segmentos-objetivo)

### [Capítulo II: Requirements Elicitation & Analysis](#capítulo-ii-requirements-elicitation--analysis)
- [2.1. Competidores](#21-competidores)
    - [2.1.1. Análisis competitivo](#211-análisis-competitivo)
    - [2.1.2. Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)
- [2.2. Entrevistas](#22-entrevistas)
    - [2.2.1. Diseño de entrevistas](#221-diseño-de-entrevistas)
    - [2.2.2. Registro de entrevistas](#222-registro-de-entrevistas)
    - [2.2.3. Análisis de entrevistas](#223-análisis-de-entrevistas)
- [2.3. Needfinding](#23-needfinding)
    - [2.3.1. User Personas](#231-user-personas)
    - [2.3.2. User Task Matrix](#232-user-task-matrix)
    - [2.3.3. User Journey Mapping](#233-user-journey-mapping)
    - [2.3.4. Empathy Mapping](#234-empathy-mapping)
    - [2.3.5. As-is Scenario Mapping](#235-as-is-scenario-mapping)
- [2.4. Ubiquitous Language](#24-ubiquitous-language)

### [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)
- [3.1. To-Be Scenario Mapping](#31-to-be-scenario-mapping)
- [3.2. User Stories](#32-user-stories)
- [3.3. Impact Mapping](#33-impact-mapping)
- [3.4. Product Backlog](#34-product-backlog)

### [Capítulo IV: Product Design](#capítulo-iv-product-design)
- [4.1. Style Guidelines](#41-style-guidelines)
    - [4.1.1. General Style Guidelines](#411-general-style-guidelines)
    - [4.1.2. Web Style Guidelines](#412-web-style-guidelines)
- [4.2. Information Architecture](#42-information-architecture)
    - [4.2.1. Organization Systems](#421-organization-systems)
    - [4.2.2. Labeling Systems](#422-labeling-systems)
    - [4.2.3. SEO Tags and Meta Tags](#423-seo-tags-and-meta-tags)
    - [4.2.4. Searching Systems](#424-searching-systems)
    - [4.2.5. Navigation Systems](#425-navigation-systems)
- [4.3. Landing Page UI Design](#43-landing-page-ui-design)
    - [4.3.1. Landing Page Wireframe](#431-landing-page-wireframe)
    - [4.3.2. Landing Page Mock-up](#432-landing-page-mock-up)
- [4.4. Web Applications UX/UI Design](#44-web-applications-uxui-design)
    - [4.4.1. Web Applications Wireframes](#441-web-applications-wireframes)
    - [4.4.2. Web Applications Wireflow Diagrams](#442-web-applications-wireflow-diagrams)
    - [4.4.3. Web Applications Mock-ups](#443-web-applications-mock-ups)
    - [4.4.4. Web Applications User Flow Diagrams](#444-web-applications-user-flow-diagrams)
- [4.5. Web Applications Prototyping](#45-web-applications-prototyping)
- [4.6. Domain-Driven Software Architecture](#46-domain-driven-software-architecture)
    - [4.6.1. Software Architecture Context Diagram](#461-software-architecture-context-diagram)
    - [4.6.2. Software Architecture Container Diagrams](#462-software-architecture-container-diagrams)
    - [4.6.3. Software Architecture Components Diagrams](#463-software-architecture-components-diagrams)
- [4.7. Software Object-Oriented Design](#47-software-object-oriented-design)
    - [4.7.1. Class Diagrams](#471-class-diagrams)
    - [4.7.2. Class Dictionary](#472-class-dictionary)
- [4.8. Database Design](#48-database-design)
    - [4.8.1. Database Diagram](#481-database-diagram)

### [Capítulo V: Product Implementation, Validation & Deployment](#capítulo-v-product-implementation-validation--deployment)
- [5.1. Software Configuration Management](#51-software-configuration-management)
    - [5.1.1. Software Development Environment Configuration](#511-software-development-environment-configuration)
    - [5.1.2. Source Code Management](#512-source-code-management)
    - [5.1.3. Source Code Style Guide \& Conventions](#513-source-code-style-guide--conventions)
    - [5.1.4. Software Deployment Configuration](#514-software-deployment-configuration)
- [5.2. Landing Page, Services \& Applications Implementation](#52-landing-page-services--applications-implementation)
    - [5.2.1. Sprint 1](#521-sprint-1)
      - [5.2.1.1. Sprint Planning 1](#5211-sprint-planning-1)
      - [5.2.1.2. Sprint Backlog 1](#5212-sprint-backlog-1)
      - [5.2.1.3. Development Evidence for Sprint Review](#5213-development-evidence-for-sprint-review)
      - [5.2.1.4. Testing Suite Evidence for Sprint Review](#5214-testing-suite-evidence-for-sprint-review)
      - [5.2.1.5. Execution Evidence for Sprint Review](#5215-execution-evidence-for-sprint-review)
      - [5.2.1.6. Services Documentation Evidence for Sprint Review](#5216-services-documentation-evidence-for-sprint-review)
      - [5.2.1.7. Software Deployment Evidence for Sprint Review](#5217-software-deployment-evidence-for-sprint-review)
      - [5.2.1.8. Team Collaboration Insights during Sprint](#5218-team-collaboration-insights-during-sprint)
- [Conclusiones](#conclusiones)
    - [Conclusiones y recomendaciones](#conclusiones-y-recomendaciones)
    - [Video About-the-Team](#video-about-the-team)
- [Bibliografía](#bibliografía)

# Capítulo I: Introducción
## 1.1. Startup Profile
### 1.1.1. Descripción de la Startup
Somos SiteForge, una startup que plantea una solución a la creciente demanda de PYMEs que buscan realizar proyectos en conjunto con desarrolladores freelance. El surgimiento de nuestra startup se debe a la creciente demanda de empresas en búsqueda de soluciones digitales de calidad, así como a los desarrolladores freelance en busca de proyectos para generar ingresos.

Nuestra principal meta es ofrecer una plataforma web intuitiva y fácil de usar que permita a las empresas publicar proyectos de software, y a los desarrolladores freelance postularse para trabajar en ellos. Nos enfocamos en satisfacer las necesidades tanto de las empresas que requieren soluciones digitales personalizadas, como de los desarrolladores freelance que buscan oportunidades para aplicar sus habilidades y obtener ingresos.

Misión:

Nuestro objetivo es simplificar la comunicación entre empresas que buscan soluciones digitales y desarrolladores freelance en busca de oportunidades laborales. Nos comprometemos a ofrecer una plataforma transparente y eficaz que fomente la colaboración, la calidad y la innovación en cada proyecto. Estamos comprometidos con el crecimiento y éxito tanto de nuestros usuarios como de nuestra empresa.

Visión:

Nuestra meta es ser el principal recurso para empresas que requieran soluciones digitales y para desarrolladores freelance en busca de oportunidades laborales en el campo del desarrollo de software. Aspiramos a ser reconocidos como líderes en innovación, calidad y eficiencia, siendo la primera opción tanto para empresas en busca de soluciones digitales como para desarrolladores en búsqueda de proyectos emocionantes y rentables.


#### 1.1.2. Perfiles de integrantes del equipo
|Miembros del equipo | Codigo Estudiante | Carrera | Conocimientos / Habilidades |
|-|-|-|-|
| Velasquez Pizarro Jair <br> <img src="./assets/members-profile/Jair.jpeg" alt="Imagen del compañero" style="width:60%"> | U202218114   |Ingenieria de software| C++, Java, HTML5, CSS3, Tailwind CSS Javascript, SQL. Detallista y proactivo.  |
| Quilla Luyo Jorge Gerardo <br> <img src="./assets/members-profile/Gerardo.png" alt="Gerardo Quilla" style="width:60%"> | U20211B197   |Ingenieria de software| Python, Java, HTML5, CSS, Typescript y SQL. Puntual y responsable.  |
| Ticona Luque, Rony Piero <br> <img src="./assets/members-profile/Piero.png" alt="Piero Ticona" style="width:60%"> | U201420422   |Ingenieria de software| Python, Java, HTML5, CSS y SQL. Ordenado y responsable.  |
| Carrasco Godos, Juan Fernando <br> <img src="./assets/members-profile/Fernando.png" alt="Juan Carrasco" style="width:60%"> | U20211D118   |Ingenieria de software| - |

## 1.2. Solution Profile
Para entender adecuadamente el perfil de la solución, es imprescindible analizar la naturaleza del problema que estamos tratando de resolver. Esto implica identificar con detalle los aspectos fundamentales que nuestra solución debe abordar y establecer objetivos y restricciones que orienten nuestra definición. Con el fin de facilitar este proceso de análisis y enfoque, emplearemos herramientas ampliamente reconocidas como "Las 5W y 2H" y el "Proceso Lean UX".
### 1.2.1 Antecedentes y problemática
2.1.1.	What/Qué<br><br>
El escenario post COVID-19 para las microempresas peruanas fue crucial, lo que condujo a muchas de ellas a iniciar un proceso de adaptación digital. Según un estudio realizado por Microsoft en 2023, el 95% de las pequeñas y medianas empresas en Perú aceleraron este proceso. En la actualidad las pymes enfrentan obstáculos en la digitalización de sus operaciones.

2.1.2.	Why/Por qué<br><br>
Varios elementos inciden en estas complicaciones en la digitalización de los negocios, siendo el desconocimiento de las herramientas digitales necesarias uno de los principales.

2.1.3.	Who/Quién<br><br>
Esta situación representa un desafío para cualquier emprendedor o pequeño empresario mayor de 18 años, especialmente a aquellos con escaso conocimiento sobre las herramientas digitales requeridas para establecer una presencia web propia y virtualizar su empresa.

2.1.4.	When/Cuándo<br><br>
Los microempresarios se enfrentan a esta problemática diariamente, ya que, al tratarse de negocios en funcionamiento, no tienen la opción de detener su producción, lo que potencialmente podría incrementar sus deudas. Además, teniendo en cuenta el alto porcentaje de aceleración en el proceso de transformación digital para las empresas, la presión para adaptarse se vuelve aún más intensa.

2.1.5.	Where/Dónde<br><br>
Esta dificultad afecta a empresas de todos los tamaños, ya que en la era digital en la que vivimos, la falta de aprovechamiento de las herramientas tecnológicas puede ser un obstáculo significativo para el crecimiento y la competitividad. Esto es especialmente relevante para las micro y pequeñas empresas, que pueden quedarse rezagadas si no se adaptan a las demandas del entorno digital.

2.1.6.	How/Cómo<br><br>
La problemática surge cuando los microempresarios buscan formas de mejorar sus ventas mediante el uso de herramientas digitales. En cuanto a las oportunidades que estas herramientas ofrecen, se destaca que el 43% de los líderes empresariales mencionan que la tecnología les permite abrirse a nuevos mercados y clientes, según un informe de Microsoft del año 2023.

2.1.7.	How much/Cuánto<br><br>
El presupuesto para los proyectos podrán ser de un alcance muy competitivo debido a la plataforma se podrán postular y comunicar con diversos freelancers.

### 1.2.2 Lean UX Process.



#### 1.2.2.1. Lean UX Problem Statements.

Segmento PYMEs<br><br>
Las PYMEs enfrentan dificultades para encontrar recursos técnicos adecuados para desarrollar soluciones digitales que impulsen su crecimiento y competitividad en el mercado.<br><br>
¿Cómo podríamos crear una solución accesible y profesional para el desarrollo de soluciones digitales dirigidas a propietarios de empresas que están en medio de un proceso de crecimiento?<br><br>
Segmento Desarrolladores Freelance<br><br>
Los desarrolladores independientes carecen de acceso a oportunidades significativas para aplicar sus habilidades y generar ingresos de manera flexible y consistente.<br><br>
¿Cómo podríamos crear una opción de trabajo para desarrolladores en nuestra aplicación?


#### 1.2.2.2. Lean UX Assumptions.

**Creo que mis clientes necesitan**<br>
Empresarios: Soluciones digitales personalizadas que mejoren la eficiencia operativa y la experiencia del cliente.
Desarrolladores: Oportunidades para aplicar sus habilidades en proyectos.

**Estas necesidades se pueden resolver con**<br>
Empresarios: Una plataforma donde pueda publicar su proyecto en mente y contratar desarrolladores que lo hagan realidad. 
Desarrolladores: Acceso a una amplia variedad de proyectos que les permitan demostrar su experiencia y generar ingresos.

**Mis clientes iniciales serán**<br>
Pequeñas y medianas empresas que buscan expandir su presencia en línea o mejorar sus procesos comerciales.
Profesionales independientes con experiencia en desarrollo de software, con deseos de formar parte de proyectos desafiantes.

**El valor #1 que un cliente quiere de nuestro servicio es**<br>
Soluciones digitales de alta calidad que les permitan mantenerse competitivos en un mercado en constante crecimiento.
Oportunidades para trabajar en proyectos interesantes y desafiantes que les permitan expandir sus habilidades y generar ingresos significativos.

**Obtendremos la mayoría de nuestros clientes a través de**<br>
Estrategias de marketing digital dirigidas a empresas emergentes.
Redes sociales y plataformas en línea.

**Haremos dinero a través de**<br>
Tarifas de suscripción para acceder a ventajas exclusivas en nuestra plataforma.

**Mi competencia principal es**<br>
Plataformas de freelancers y agencias de empleo que conectan a profesionales independientes con oportunidades de trabajo.

**Los venceremos…**<br>
Ofreciendo una plataforma intuitiva, transparente y centrada en el cliente que satisfaga las necesidades específicas de las PYMEs.
Brindando una amplia gama de proyectos atractivos, una experiencia de usuario sólida y un soporte dedicado para los profesionales independientes.

**Mi mayor riesgo es…**<br>
La falta de adopción por parte de las PYMEs debido a la resistencia al cambio o la percepción de que las soluciones digitales son costosas o difíciles de implementar.

**Resolveremos esto…**<br>
Destacando los beneficios y la accesibilidad de nuestras soluciones digitales, así como ofreciendo un soporte continuo para facilitar el cambio y la adopción del producto.


#### 1.2.2.3. Lean UX Hypothesis Statements.

Hypothesis Statement 1<br><br>
Creemos que al proporcionar una plataforma intuitiva y centrada en el cliente para la colaboración entre PYMEs y desarrolladores freelance, aumentará la cantidad de proyectos completados en nuestra plataforma.<br><br>
Sabremos que hemos tenido éxito cuando veamos un aumento significativo en el número de proyectos publicados y completados en nuestra plataforma, así como un aumento en la satisfacción del cliente medida por las reseñas y comentarios positivos.<br><br>
Hypothesis Statement 2 <br><br>
Creemos que al ofrecer una amplia variedad de proyectos atractivos y bien remunerados, aumentará la participación y la retención de los desarrolladores freelance en nuestra plataforma.<br><br>
Sabremos que hemos tenido éxito cuando observemos un aumento en el número de desarrolladores activos en nuestra plataforma, así como una disminución en la tasa de abandono y una mayor frecuencia de participación en proyectos.<br><br>
Hypothesis Statement 3<br><br>
Creemos que al proporcionar transparencia y eficiencia en el proceso de colaboración entre PYMEs y desarrolladores freelance, aumentará la confianza y la satisfacción de los usuarios en nuestra plataforma.<br><br>
Sabremos que hemos tenido éxito cuando veamos una mejora en la calificación de satisfacción del usuario, así como un aumento en el número de referencias y recomendaciones de nuestra plataforma por parte de los usuarios satisfechos.


#### 1.2.2.4. Lean UX Canvas.

![Canvas](assets/Lean-UX-Canvas/canvas.png)


## 1.3. Segmentos objetivo.
Hemos planteado los siguientes segmentos para nuestra aplicación:<br><br>
Pequeñas y Medianas Empresas (PYME): Estos negocios buscan nuevo público y quieren expandirse. Por lo tanto, tendrán que recurrir a usar tecnologías modernas, por ejemplo: páginas web atractivas, aplicaciones que faciliten procesos, gestionen el negocio, etc. Y para lograrlo tendrán que contratar desarrolladores freelance, los cual les puede resultar más económico.<br><br>
Freelancers: Los profesionales independientes, como diseñadores gráficos, fotógrafos y consultores, también pueden necesitar un sitio web para mostrar su trabajo y promocionar sus servicios. Estas personas podrían estar interesadas en una plataforma que les ayude a encontrar desarrolladores web para crear sus sitios.


---

# Capítulo II: Requirements Elicitation & Analysis
## 2.1. Competidores.

Luego del planteamiento de nuestra startup y de nuestro proyecto, hemos identificado a los principales competidores:

- Toptal: Plataforma enfocada a conectar empresas con desarrolladores de software de distintas áreas.

- RemoteOk: Plataforma que se centra en el trabajo remoto, lo cual permite conectar empresas y desarrolladores de distintas partes del mundo. 
- Workana: Plataforma que conecta empresas y desarrolladores en una variedad de campos

### 2.1.1. Análisis competitivo.

| Competitive Analysis Landscape | |
| - | - |
| ¿Por qué llevar a cabo este análisis? | Para conocer el valor que ofrece cada uno de nuestros competidores en este sector |


| | | FromZero | Toptal  | RemoteOK | Workana |
|-|-|-|-|-| - |
| Perfil | Overview | Plataforma para publicación y postulaciones a proyectos de desarrollos de páginas web, aplicaciones web, etc. | Plataforma donde las empresas pueden contratar a desarrolladores con bastante experiencia en el mundo laboral. | Plataforma donde empresas publican oportunidades de trabajo remoto desde distintas partes del mundo | Plataforma de latino América donde desarrolladores pueden aplicar a un trabajo y las empresas pueden contratar desarrolladores o freelancers. |
|| Ventaja competitiva ¿Qué valor ofrece a los clientes? |  FromZero cuenta con un sistema de hitos o entregables, y opción para hacer un seguimiento al proyecto. | Toptal significa Top Talent, su nombre indica que quiere trabajar con los mejores del mundo. Cuenta con un riguroso proceso el cual identifica si son expertos en su área. Es por ello que de las miles de aplicaciones solo el 3% son aceptados | Ofrece trabajos remotos, además los desarrolladores pueden aplicar diferentes filtros para encontrar el trabajo más adecuado a lo que se busca. | Ofrece una plataforma de confianza para los desarrolladores y empresas. Cuenta con múltiples campos en donde las empresas pueden encontrar desarrolladores con habilidades necesarias para sus proyectos. |
| Perfil de marketing | Mercado Objetivo | PYMEs o emprendimientos que quieran lograr reconocimiento a través de páginas web, o mejorar su negocio con ayuda de aplicaciones web. <br><br> Freelancers que busquen oportunidad de trabajo para expandir sus conocimientos y lograr escalar. | Medianas y grandes empresas que requieran de un equipo de desarrolladores con bastante experiencia. <br><br> Desarrolladores freelance con amplia experiencia. | PYMEs que deseen contratar de forma remota.<br><br> Desarrolladores en busca de trabajos remotos. | PYMEs que deseen contratar buenos desarrolladores de forma remota en latino américa. <br><br> Desarrolladores en busca de trabajos remotos que ayuden a impulsar sus carreras. |
| | Estrategia de Marketing | Promoción en redes sociales, participar en eventos y colaborar en proyectos. | Colaborar con empresas reconocidas a nivel mundial | Publicidad en línea y eventos virtuales. | Promoción en redes sociales y contenido educativo. |
| Perfil del producto | Productos y servicios | Aplicación Web | Plataforma de trabajo | Plataforma de trabajo | Plataforma de trabajo |
|| Precios y costos | Membresías para Empresa y Desarrollador. <br><br> Empresa: <br> - Cuenta Free <br> - Cuenta Premium PEN 20.00/Mes<br><br> Desarrollador: <br> - Cuenta Free <br> - Cuenta Premium PEN 20.00/Mes | Tarifas varían según la experiencia y habilidades del freelancer contratado | Freelancers pueden pagar para destacar sus perfiles dentro de la plataforma | Dependiendo del tiempo que quieran trabajar junto con la plataforma Workana, los freelancers pueden cambiar su membresía <br>- Plus: USD 4.90 <br> -Professional: USD 16.90 <br>- Premium: USD 24.90 |
|- | Canales de distribución (Web y/o Móvil) | Página web | Página web | Página web | Página web |
| Análisis SWOT | Fortalezas | Sistema de  entregables eficiente.<br>La empresa puede gestionar los entregables que deben realizar los desarrolladores.<br> Los freelancers cuentan con ventajas gracias a las membresías de pago. | Sistema de contratación efectivo, en donde se encontrará un desarrollador en el menor tiempo posible y con las habilidades o experiencia necesaria según los requisitos dados. | Lista masiva de ofertas de trabajo alrededor del mundo, con detalles de localidad, beneficios y salario. | Transparencia con por parte de los desarrolladores, se puede ver portfolios, su experiencia y opiniones acerca de ellos. |
| | Debilidades | Debido al pago que se realiza al finalizar el proyecto, y cierta cantidad de entregables, muchos desarrolladores pueden sentirse presionados por entregar una solución eficiente. | Debido al proceso de selección riguroso, es posible que aquellos desarrolladores elegidos tengan tarifas que salgan del presupuesto de las empresas. Por parte de los desarrolladores, el ingreso a esta plataforma es muy difícil. | Al ser una plataforma donde hay publicaciones masivas de ofertas de trabajo, y que además son remotos, la gran cantidad de postulaciones puede ser un problema. | Al ofrecer varias categorías de trabajo, es posible que no todas cuenten con los suficientes desarrolladores. |
| | Oportunidades | Posibilidad de contratar a todo un equipo de freelancers para formar parte del proyecto. | Desarrolladores disponibles para proyectos grandes y desafiantes. | Plataforma con una interfaz de fácil uso en donde los freelancers pueden aplicar filtros de búsqueda para ofertas de trabajo. | Buscar más talentos para las categorías que ofrecen |
| | Amenazas | Posible falta de desarrolladores freelance.<br>Plataformas del mismo sector.<br>Pocas ofertas de trabajo por día. | Plataformas con más desarrolladores freelancers  disponibles.<br>Dificultad para incrementar sus desarrolladores en su plataforma debido al proceso de selección. | Debido a las publicaciones diarias, es posible que algunas no especifiquen todos los detalles. | Posibles problemas en algunas categorías de trabajo que Workana ofrece. |

### 2.1.2. Estrategias y tácticas frente a competidores.
| Competidores | ¿Qué se puede hacer para ganarle a la competencia? |
|-|-|
|Competidor:1<br>Toptal|Toptal cuenta con una sistema de contratación bastante riguroso, pocos freelancers logran ser parte de esta plataforma. Por lo tanto, FromZero puede ofrecer un sistema más accesible para los freelancers ya que así lograrían tener una oportunidad dentro de la plataforma y así expandir sus experiencias en el mundo laboral.|
|Competidor:1<br>RemoteOK|RemoteOK tiene al día muchas publicaciones de oferta de trabajo, cada una cuenta con su respectiva descripción y requisitos de proyecto. Sin embargo, la plataforma no permite hacer un seguimiento al proyecto en cuestión, ya que solo se limita a comunicación simple entre empresa y desarrollador.<br>FromZero da la oportunidad de hacer un seguimiento al proyecto desde inicio a fin.|
|Competidor:1<br>Workana|Workana ofrece dentro de su plataforma diversos campos de trabajo tales como diseño, programación y marketing. Sin embargo, puede que la plataforma se enfoque más en un campo que en otro, y en consecuencia descuidando la cantidad de postulantes en esa área, protección a cada uno y el soporte.<br>FromZero al contar con un único campo le puede dedicar todos los servicios y atención necesaria.|

## 2.2. Entrevistas.
### 2.2.1. Diseño de entrevistas.

**Segmento objetivo: Freelancer**

**Preguntas de información personal:** 

- ¿Cuál es tu nombre?

- En la actualidad, ¿Estudias o trabajas?
	
	**Estudia:**

	- ¿Qué carrera estudias y en qué ciclo te encuentras?
	
	- ¿En qué te gustaría especializarte?
	
	**Trabaja:**

	Cuéntanos un poco de tu trabajo


**Preguntas de indagación:**

- ¿Cuáles son los lenguajes de programación que dominas?

- ¿Posees experiencia en el desarrollo de programas de software?

- ¿Podrías describir los tipos de proyectos en los que has trabajado anteriormente?

- ¿Cuáles han sido los principales desafíos que has enfrentado como desarrollador freelance?

- ¿Qué aspectos considerar al evaluar la viabilidad de un proyecto antes de aceptarlo?

- ¿Podrías compartir un ejemplo del mayor desafío que has enfrentado como desarrollador freelance y cómo lo resolviste?

- ¿Cómo gestionas la comunicación con tus clientes a lo largo del ciclo de vida de un proyecto?

- ¿Qué tan familiarizado estás con las plataformas de contratación freelance disponibles en el mercado?

<br>**Presentación de FromZero.**

**Preguntas de validación:**

- ¿Como desarrollador que opinas del sistema de entregables?

- ¿Consideras importante mantener a la empresa actualizada sobre el proyecto en el que estás trabajando?

- ¿Qué beneficios esperas de nuestra plataforma?

- ¿Tienes alguna sugerencia de mejora?


<br>**Segmento objetivo: PYMEs o emprendimientos**

**Preguntas de información personal:**

- ¿Cuál es su nombre?

- ¿Cómo se llama tu negocio y a que se dedica?

- ¿Cómo se animó a realizar el emprendimiento?

- ¿Cual es su objetivo?
 
**Preguntas de indagación:**

- ¿Su empresa o emprendimiento actualmente tiene una presencia establecida en el ámbito digital?

- ¿Considera que es crucial en la actualidad que las empresas y emprendimientos tengan una presencia sólida en Internet? ¿Cuál es la razón detrás de esta opinión?

- ¿Qué estrategias implementaría para mejorar la presencia digital de su negocio?

- ¿Ha enfrentado alguna vez su empresa o emprendimiento la necesidad de implementar soluciones de software? En caso afirmativo, ¿qué tipo de soluciones han sido requeridas?

- ¿Ha contemplado la posibilidad de llevar a cabo proyectos de software con el propósito de mejorar el rendimiento o las operaciones de su empresa o emprendimiento? ¿Cuál sería la justificación detrás de esta consideración?

- ¿Qué tan familiarizado estás con las plataformas dedicadas a la contratación de desarrolladores freelance para proyectos de software?

<br>**Presentación de FromZero.**

**Preguntas de validación:**

- ¿Estaría tu negocio dispuesto a utilizar el sistema de entregables con el o los desarrolladores a cargo de su proyecto?

- ¿Qué información quisieras que el desarrollador te mantenga actualizada?

- ¿Qué beneficios esperas de nuestra plataforma?

- ¿Alguna sugerencia de mejora?

### 2.2.2. Registro de entrevistas.
**Segmento Empresas**  

**Entrevista 1**

 - Entrevistador: Jair Velasquez Pizarro
  - Entrevistado: Alexandra Ñañez
  - Edad: 21
  - Residencia: Lima - Comas
  - Enlace del video: [https://upcedupe-my.sharepoint.com](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202218114_upc_edu_pe/ERCqSU_2GapEunt22M-Mkd8BcsWU3E48f1Yi64nZnEtWqA?e=KUw5GE&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)

<img src="./assets/interview-images/Alexandra.png" alt="Imagen de entrevista1" style="width:60% align-center">
	
Resumen: 
Mi entrevistada, Alexandra Ñañez, es estudiante de la carrera de Administración y Marketing, y es asesora de Marketing en un negocio que brinda el servicio de juegos infantiles, estimulación temprana y alquiler de local para fiestas infantiles. Menciona que actualmente la empresa solo maneja Facebook e Instagram con anuncios, por lo que cree que la adquisición de una página web mejoraría la rentabilidad del negocio. También menciona que la parte más importante al implementar una página web es la parte del diseño y la arquitectura. También recalca que lo principal al momento de contratar un programador para un producto de software es la seguridad, comunicación y pruebas de trabajos anteriores para comprender si su forma de diseño se asemeja a la empresa.

**Segmento Freelancer**  

**Entrevista 1**

Entrevistador: Jorge Gerardo Quilla Luyo

Entrevistado: Miguel Angel Ybañez Esquerre

Residencia: Lima - Rimac

Enlace del video: [Entrevista](https://upcedupe-my.sharepoint.com/:v:/g/personal/u20211b197_upc_edu_pe/EZ1U0me5C-5BlBpIhcB6_3EBukZ9KM5DxziaR7ZtPGDVPw?e=HGiIcu&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)

<img src="./assets/interview-images/entrevistaJorgeQuilla.png" alt="Entrevista Jorge Quilla">

Resumen: 

El entrevistado Miguel Ybañez estudia la carrera de Ingeniería de Software. Tiene experiencia desarrollando páginas web y videojuegos. Cuenta que ha realizado un trabajo como freelancer para una empresa extranjera de forma remota. Además, conoce plataformas para contratación de freelancers. Opina que FromZero promete una buena gestión de proyectos gracias a su sistema de entregables en su plataforma. También apoya la creación de esta solución la cual ofrece más oportunidades de trabajo a los freelancers. Sugiere que se implementen foros de discusión o chats ya integrados en la plataforma, este último como una herramienta de colaboración adicional.


### 2.2.3. Análisis de entrevistas.
**Segmento 1:**
{texto}
**Segmento 2:**
{texto}
## 2.3. Needfinding.
### 2.3.1. User Personas.
**Segmento PYMEs** 

![User Persona PYME](assets/user-personas/Emilio-Vargas.png)

**Segmento Freelancer**

![User Persona](assets/user-personas/Leandro-Martinez.png)

### 2.3.2. User Task Matrix.

|  | Segmento PYMEs |  | Segmento Freelancer |  |
| - | ----------- | ------------ | ----------- | ---------- |
| | Importancia | Frecuencia   | Importancia | Frecuencia |
| Crear página web para mi negocio | Media | Alta | - | - |
| Publicar requerimientos y detalles de mi negocio | Baja | Alta | - | - |
| Buscar desarrolladores para la realización de mi página web | Baja | Media | - | - |
| Acordar entregables | Alta | Alta | - | - |
| Establecer fechas de entrega | Alta | Media | - | - |
| Postular al proyecto | - | - | Alta | Media |
| Elaborar diseño y código de la página web | - | - | Alta | Alta |
| Realizar seguimiento al proyecto | Alta | Alta | Alta | Alta |
| Acordar fecha de presentación de avances | Media | Alta | - | - |
| Probar página web | Media | Media | Alta | Alta |

### 2.3.3. User Journey Mapping.

**Segmento PYMEs**

![PYME Journey Map](assets/user-journey-mapping/pyme-journey-mapping.png)

**Segmento Freelancer**

![Freelancer Journey Map](assets/user-journey-mapping/freelancer-journey-mapping.png)

### 2.3.4. Empathy Mapping.
**Segmento PYMEs**

![PYME Empathy Map](assets/empathy-mapping/pyme-empathy-map.png)

**Segmento Freelancer**

![Freelancer Empathy Map](assets/empathy-mapping/freelancer-empathy-map.png)
### 2.3.5. As-is Scenario Mapping.

**Segmento PYMEs**  

![PYME AS-IS Scenario Map](assets/as-is-scenario-mapping/as-is-pyme.png)

**Segmento Freelancer** 

![Freelancer AS-IS Scenario Map](assets/as-is-scenario-mapping/as-is-freelancer.png)

## 2.4. Ubiquitous Language.

**Desarrollador freelance:** persona que trabaja de manera independiente en proyectos de diseño web o aplicaciones, no trabaja para una empresa en específico.

**PYME:** Pequeñas y medianas empresas. Tienen una cantidad moderada de empleados e ingresos en comparación con grandes empresas. 

**Página web:** documento en línea que puedes ver en distintos navegadores y que contiene información sobre un tema específico, mayormente para negocios o emprendimientos. 

**Sistema de entregables:** es un sistema el cual permite a la empresa a cargo del proyecto, crear o editar entregables. Estos contienen muchos requisitos que deben ser cumplidos por el desarrollador según la fecha que se establezca.

**Aplicación web:** es un programa que se usa en el navegador. Puede incluir herramientas, guardado de datos, inicios de sesión y red de contactos.


---

# Capítulo III: Requirements Specification
## 3.1. To-Be Scenario Mapping.

Segmento 1: Empresas

![alt text](image.png)

Segmento 2: Desarrolladores
![alt text](image-2.png)

## 3.2. User Stories.
*Epic 1: Landing page *Como* empresario o freelancer *Quiero* visualizar una página *Para* saber acerca de la aplicación e ingresar a la aplicación

|<div style="width:40px">Story ID</div>|<div style="width:50px">Título</div>|<div style="width:100px">Descripción</div>|<div style="width:100px">Criterio de aceptación</div>|<div style="width:30px">Epic ID</div>|
|---|---|---|---|---|
|E1-US101|<p>Barra de navegación en landing page</p><p> </p>|*Como* usuario *quiero* una barra de navegación de landing page *para* tener accesos directos a la información de la aplicación |<p>*Escenario 1: El usuario quiere saber cómo funciona la aplicación</p><p>Dado que* el usuario se encuentra en el landing page</p><p>*Y* se dirige en la barra de navegación<br>*Cuando* presiona la opción “Cómo funciona”</p><p>*Entonces* es dirigido a la sección de cómo funciona el producto.</p><p>*Escenario 2: El usuario quiere saber los testimonios de usuario que utilizaron la aplicación</p><p>Dado que* el usuario se encuentra en el landing page</p><p>*Y* se dirige en la barra de navegación<br>*Cuando* presiona la opción “Testimonios”</p><p>*Entonces* es dirigido a la sección de Testimonios</p><p>*Escenario 3: El usuario quiere hacer preguntas frecuentes de la aplicación</p><p>Dado que* el usuario se encuentra en el landing page</p><p>*Y* se dirige en la barra de navegación<br>*Cuando* presiona la opción “Preguntas Frecuentes”</p><p>*Entonces* es dirigido a la sección de Preguntas Frecuentes.</p>|1|
|E1-US102|Sección hero de landing page	|*Como* usuario *quiero* visualizar una sección hero en el landing page *para* tener una idea sobre lo que ofrece la aplicación|<p>*Escenario 1: El usuario se encuentra en la sección de hero</p><p>Dado que* el reclutador o postulante se encuentra en el landing page</p><p>*Cuando* se encuentra en la sección de hero</p><p>*Entonces* visualiza una presentación de la aplicación.</p>|1|

## 3.3. Impact Mapping.

![Impact Mapping](image.jpg)

## 3.4. Product Backlog.

| #Orden | User Story ID | Titulo| Descripción| Story Points (1/2/3/5/8) |
| ------ | ------------- | ----- | ---------- | ------------------------ |
| 1      | HU01          | titulo his | desc  | 5                        |

# Capítulo IV: Product Design
## 4.1. Style Guidelines.
### 4.1.1. General Style Guidelines.
Descripcion del porque estos elementos seran importantes

**Color:** (Descripcion de los colores escogidos y porque)  
![Colores generales](image.jpg)

**Tipografia:** (Descripcion de la tipografia escogida para el proyecto y porque)
![Tipografias generales](image.jpg)
**Branding** (Describir logotipo y porque)
![Branding general](image.jpg)
### 4.1.2. Web Style Guidelines.
Descripcion de los elementos que se utilizaran en el web app

**Background:** (primary, secondary, terniary)  
![Background Preview web](image.jpg)
**Text Styles:** (H1, H2, p, a,)  
![Text Style Preview web](image.jpg)
**Button Styles:** (Button, dropdowns, Switches)
![Button Preview web](image.jpg)
**Icons:** (Fondo blanco con los iconos que vamos a usar)
![Icons Preview web](image.jpg)
**Misc** (Cosas como nav var o slideshows que pensemos usar)
![Miscellaneos preview web](image.jpg)
## 4.2. Information Architecture.
### 4.2.1. Organization Systems.
Descripcion corta respecto a los sistemas de organizacion que usaremos  (Escoger)
"Hierarchical. This structures advices to present the content in a way to distinguish the level of importance by making use of physical differences, such as size, colour, contrast, alignment etc.

Sequential. Guide users to follow a specific path towards their goal and provide content step-by-step based on the current step. 

Matrix. You can always give the users the option to choose the type of navigation they prefer, i.e. Alphabetical, Chronological, by topic."
### 4.2.2. Labeling Systems.
The labeling system aims at uniting the data effectively and represent them in simple way and avoid confusing great amount of information. A widely adopted way to achieve this is by creating the labels which represent loads of data in few words. 

Como decir "home, about us, etc" basicamente lo que iria en un nav var y asi
### 4.2.3. SEO Tags and Meta Tags

**Meta & SEO (Search Engine Optimization) Tags:**  sirven para que la pagina web sea encontrada facilmente es lo que sale al encontrar la pagina en el buscador (se ponen en el <"head">)
* Titulo: ```<title> ___ </title> ```
* Descripcion: ```<meta name = "description" content = "texto descipcion"/> ```
* Palabras Clave: ```<meta name = "keyword" content = "keyword1, 2 3"/> ```

### 4.2.4. Searching Systems.
**Que se busca?:** Que buscara el usuario  
**Que resultados se mostraran?:** Que se mostrara  
**Interface de busqueda:** Descripcion de como ayuda a encontrar lo deseado 
![Search interface preview web](image.jpg)

### 4.2.5. Navigation Systems.
Basicamente aqui definimos como funciona la navegacion del web app
**Hierarchical Navigation System:** Main page a destination pages.
**Global Navigation Systems** (Complemento del Hierachical) Movimiento vertical (te mueves por la pagina)con nav(debe poder regresar a la principal)
**Local Navigation Systems** (vas a otras paginas) (complemento del global nav sistem sub-site) Usas otras paginas
## 4.3. Landing Page UI Design.
### 4.3.1. Landing Page Wireframe.
la pagina donde te registras y ves info del web app (te manda al web app)

Wireframe es todo lo funcional de la pagina
![Landing page Wireframe](image.jpg)
### 4.3.2. Landing Page Mock-up.
Mockup es todo lo relacionado al diseño de la pagina
![Landing page mockup](image.jpg)
## 4.4. Web Applications UX/UI Design.
### 4.4.1. Web Applications Wireframes.
lo funcional de cada aspecto del wireframe 
![Web Aplication Wireframe](image.jpg)
### 4.4.2. Web Applications Wireflow Diagrams.
Wireflow es como se va a navegar por la pagina (boton me lleva a esta pagina y este me regresa)
![Web Aplication Wireflow](image.jpg)
### 4.4.2. Web Applications Mock-ups.
Diseño en todo aspecto
![Web Aplication Mockup](image.jpg)
### 4.4.3. Web Applications User Flow Diagrams.
un flow diagram de como el usuario utilizara la pagina **[PARA CADA USER GOAL]** 
![Web Aplication User Flow Diagram](image.jpg)
## 4.5. Web Applications Prototyping.
[URL del Prototipo (Hecho en figma)](https://www.example.com)
## 4.6. Domain-Driven Software Architecture.
### 4.6.1. Software Architecture Context Diagram.

<img src="./assets/C4 model/structurizr-90965-FromZeroSystemContext.png">
   
### 4.6.2. Software Architecture Container Diagrams.

<img src="./assets/C4 model/structurizr-90965-FromZeroContainer.png">

### 4.6.3. Software Architecture Components Diagrams.

#### Login and Registration Bounded Context

<img src="./assets/C4 model/structurizr-90965-LoginAndRegistrationComponent.png">

#### Developer Profile Bounded Context

<img src="./assets/C4 model/structurizr-90965-DeveloperProfileComponent.png">

#### Enterprise Profile Bounded Context

<img src="./assets/C4 model/structurizr-90965-EnterpriseProfileComponent.png">

#### Project Proposal and Hire a Developer Bounded Context

<img src="./assets/C4 model/structurizr-90965-ProjectProposalAndHireADeveloperComponent.png">

#### Apply for Projects Bounded Context

<img src="./assets/C4 model/structurizr-90965-ApplyForProjectComponent.png">

#### Project Development Bounded Context

<img src="./assets/C4 model/structurizr-90965-ProjectDevelopmentComponent.png">

#### Tech Support Bounded Context

<img src="./assets/C4 model/structurizr-90965-TechnicalSupportComponent.png">

## 4.7. Software Object-Oriented Design.
### 4.7.1. Class Diagrams.

Respecto a las necesidades del producto, se decidió plantear las clases en el siguiente diagrama:
<img src="./assets/Class Diagram/class-diagram.png">
Las clases serán explicadas en el siguiente apartado de forma más específica.

### 4.7.2. Class Dictionary.

|**User**||
| - | :- |
|La clase User es la clase donde el usuario brinda su información personal para poder tener acceso a una cuenta en la plataforma||
|**Atributo**|**Descripción**|
|\_name: string|es el nombre real del usuario|
|\_lastname: string|es el apellido completo del usuario|
|\_role: string|es el rol del usuario el cual puede ser freelancer o empresario|
|**Métodos**|**Descripción**|
|CreateUser()|Con este método se crea un usuario |

|**Cuenta**||
| - | :- |
|La clase Cuenta es la clase que representa la cuenta del usuario en la plataforma||
|**Atributo**|**Descripción**|
|\_email: string|es el correo electrónico, el cual es necesario para iniciar sesión |
|\_password: string|es la contraseña, el cual es necesario para iniciar sesion y brinda seguridad a la cuenta|
|\_createdBy:User|Nos permite identificar a nuestros 2 tipos de usuario (empresario o freelancer)|
|\_profilePicture: string|Permite a los usuario tener una foto de perfil|
|**Métodos**|**Descripción**|
|CloseAccount()|Con este método el usuario podrá cerrar la cuenta |
|ChangePassword()|Con este metodo el usuario podrá cambiar su contraseña|
|ViewInformation()|Con este método el usuario podrá visualizar su información en la aplicación  |

|**Desarrollador** ||
| - | :- |
|La clase Desarrollador representa la cuenta de usuario del desarrollador||
|**Atributo**|**Descripción**|
|\_country: string|es el país de origen del desarrollador|
|\_cellphone: number|es el numero de celular de contacto del desarrollador|
|\_email: string|es el email de contacto del desarrollador|
|\_projectQuantity: number|es la cantidad de proyectos realizados en la plataforma Webmaster|
|\_specialities|Son las tecnologías y lenguajes que domina el desarrollador|
|**Métodos**|**Descripción**|
|ApplyProject()|Con este método el freelancer podrá mandar su solicitud de desarrollo en el proyecto |
|SubmitProjects()|Con este método el freelancer podrá enviar los distintos avances de los proyectos |
|DeliverableChange()|Con este método el usuario podrá visualizar su información en la aplicación  |

|**Empresario**||
| - | :- |
|La clase Empresario representa la cuenta de usuario del empresario||
|**Atributo**|**Descripción**|
|\_country: string|es el país de origen del desarrollador|
|\_businessName: number|es el número de identificación de la empresa|
|\_cellphone: number|es el número de celular de contacto del desarrollador|
|\_email: string|es el email de contacto del desarrollador|
|\_website: string|es el website de la empresa |
|\_section: string|es el sector de la empresa|
|**Métodos**|**Descripción**|
|PublishProject()|Con este método los empresarios podrán publicar sus proyectos que requieren una solución de software|
|RequestPostChanges()|Con este método los empresarios podrán cambiar la descripción del proyecto hasta que acepten a un freelancer|
|DeletePost()|Con este método los empresarios podrán borrar sus publicaciones|

|**Proyecto**||
| - | :- |
|La clase proyecto representa los proyectos que estarán presentes en la plataforma.||
|**Atributo**|**Descripción**|
|\_businessmanName: string|es el nombre del empresario quien ha creado el proyecto|
|\_freelancerName:string|es el nombre del freelancer a cargo del desarrollo del proyecto|
|\_description: string|es la descripción del proyecto|
|\_projectPayment: number|es la cantidad de dinero que va a recibir el freelancer al finalizar el proyecto|
|**Métodos**|**Descripción**|
|UpdateState()|Con este método el proyecto actualizará su estado de acuerdo al avance del desarrollo del proyecto|
|ViewInformation()|Con este metodo se verá la información del proyecto|
|ViewListofDeliverables()|Con este método se verá la lista de entregables enviados y pendientes por desarrollar|

|**Plan**||
| - | :- |
|La clase plan es la que se encarga de administrar los diversos planes ||
|**Atributo**|**Descripción**|
|\_startedAt: DateTime|fecha de inicio del plan|
|\_finishedAt:DateTime|fecha de finalización del plan|
|**Métodos**|**Descripción**|
|ChangePlan()|Con este método se podrá cambiar de plan|
|RenewPlan()|Con este método podrá renovar el plan|
|CancelPlan()|Con este método podrá cancelar el plan|


## 4.8. Database Design.
### 4.8.1. Database Diagram.
Diagrama de base de datos (la relacion entre clases PK FK el Normalizar tmbn, isiyisi 🕸)
# Capítulo V: Product Implementation, Validation & Deployment
## 5.1. Software Configuration Management.
### 5.1.1. Software Development Environment Configuration.

A continuación, daremos a conocer los productos de software que hemos utilizado para el desarrollo de nuestro proyecto.<br>
**Project Management**				

- **Whatsapp: [https://web.whatsapp.com/](https://web.whatsapp.com/)**<br>
  La plataforma de Whatsapp se empleó para realizar la organización de tareas para el equipo, así como también para poder ayudarnos entre nosotros ante cualquier duda que se tuviera en el trabajo.
- **Discord: [https://discord.com/](https://discord.com/)**<br>
  La plataforma Discord se empleó para poder realizar las reuniones de forma virtual, en dichas reuniones dábamos un reporte sobre el avance de las tareas que se nos habían asignado así como también se usó para la elaboración de idea de negocio.

**Product UX/UI Design**

- **Miro: [https://www.miro.com](https://www.miro.com)**<br>
  La plataforma Miro se empleó para el desarrollo del Lean ux canvas, Análisis de competidores,  As-is Scenario mapping, To-be Scenery mapping
- **Uxpresia: [https://uxpressia.com/](https://uxpressia.com/)**<br>
  La plataforma Uxpresia se empleó para la elaboración del User Persona, Empathy maps, Journey Maps e Impact maps.
- **Figma: [https://www.figma.com/](https://www.figma.com/)**<br>
  La plataforma figma se empleó para el desarrollo wireframes y mock up del landing page, y para los wireframes, mock up y prototyping del web applications 

**Software Development**

- **Landing Page**<br>
  Para el desarrollo de nuestro landing page se usará  HTML5, CSS y Javascript.
- **Frontend Web Application**<br>
  Se ha utilizado a Angular como framework de Typescript. En adición, para la implementación de componentes reutilizables y accesibles se usó Angular Material como biblioteca de componentes UI. 

**Software Testing**<br>
Para la realización de pruebas de testeo de software  que se ha utilizado para el landing page y  la aplicación web hemos empleado las herramientas de desarrollador de los siguientes navegadores web: Google Chrome (<https://www.google.com/chrome/>), Microsoft Edge (<https://www.microsoft.com/en-us/edge>) y Mozilla Firefox (<https://www.mozilla.org/en-US/firefox/browsers/>). Asimismo, dichos navegadores cuentan con aplicaciones desktop y móviles las cuales son totalmente gratuitas y por consiguientes accesible para todas las personas.

**IDE's de desarrollo**

- **Webstorm: [https://www.jetbrains.com/webstorm/](https://www.jetbrains.com/webstorm/)**<br>
  Webstorm es un IDE enfocado al desarrollo de frontend y posee una gran cantidad de herramientas que pueden agilizar el proceso de desarrollo. Para poder usar Webstorm es necesario tener una licencia

**Software Deployment**

- **Netlify: [https://www.netlify.com/](https://www.netlify.com/)**<br>
  La plataforma Netlify se empleó para el deployment del landing page, para ello fue necesario vincular el repositorio de github con Netlify. De esta manera, Netlify se encargará automáticamente del deploy de la página.

**Software Documentation**

- **Google Drive: [https://www.google.com/intl/es-419_pe/drive/](https://www.google.com/intl/es-419_pe/drive/)**<br>
   La plataforma Google Drive se empleó para la creación de archivos de documento (Google Docs)  y presentación. Se optó por esta plataforma ya que permite el desarrollo colaborativo.
- **Github: https: [https://github.com/](https://github.com/)**<br>
    La plataforma Github se empleó para la creación de documentación de nuestro proyecto así como del landing page. Se optó por esta plataforma porque permite el desarrollo colaborativo entre desarrolladores. La evidencia de commits demuestra la participación que ha tenido cada uno de los integrantes en el desarrollo del proyecto.
- **Structurizr: [https://structurizr.com/](https://structurizr.com/)**<br>
    La plataforma Structurizr se empleó para la creación de los diagramas C4 de nuestro proyecto, para la elaboración de los diagramas se necesita emplear una sintaxis similar a un lenguaje de programación.
- **Vertabelo: [https://vertabelo.com/](https://vertabelo.com/)**<br>
    La plataforma Vertabelo es una aplicación web colaborativa la cual ha sido empleada para la elaboración del diseño de base de datos.

### 5.1.2. Source Code Management.

- Repositorios:
    - Url del repositorio de GitHub para el Landing Page:
    [URL del Landing Page](https://github.com/upc-pre-202401-si729-wx56-g3/FromZero-LandingPage)
    - URL del repositorio de GitHub para los Acceptance Tests:
    [URL de los Acceptance Tests](https://github.com/upc-pre-202401-si729-wx56-g3/FromZero-acceptance-tests)
- Git Flow:
    <img src="./assets/Product Implementation/gitflow.png">
    Se aplicará GitFlow utilizando el artículo de Vincent Driessen, “A successful Git branching model”.
    A continuación se dará una explicación de cada Branch que se utiliza en el modelo GitFlow.
    - **MASTER**: Se utilizara esta rama como la versión estable y lista para producción. Todos los cambios que se fusionan aquí ya se consideran seguros y listos para implementar.
    - **DEVELOP**: Esta rama es donde se trabajarán nuevas características y correcciones de errores. Es la rama principal de desarrollo.
    - **FEATURE BRANCHES**: Son ramas de características para trabajar en nuevas funciones. Cada característica tendrá su propia rama, para que se trabaje de manera aislada, luego se fusiona con la rama DEVELOP.
    - **RELEASE BRANCHES**: Son las ramas de lanzamiento que sirven para preparar una nueva versión del software. Se corrigen errores, pruebas finales y se prepara para fusionarse con MASTER y DEVELOP.
    - **HOTFIX BRANCHES**: Son esenciales cuando ocurren errores en la producción. Se crean directamente desde MASTER, se solucionan los problemas y se fusionan los cambios en las ramas de MASTER y DEVELOP.
- Commit Conventions    
Para el formato de los COMMITS se aplicará lo siguiente:
    ```<type>:<description>```
Donde:

    - TYPE: Solo pueden ser 3 tipos, sea BREAKING que se relaciona con X, luego FEAT que se relaciona con Y y por último FIX que se relaciona con Z.

### 5.1.3. Source Code Style Guide & Conventions.

**HTML**: https://www.w3schools.com/html/html5_syntax.asp
           
**Index.html**

Es la página por defecto dentro de los directorios de los servidores de cualquier sitio web que se carga siempre que se solicita un dominio y no se especifica el nombre de un archivo en específico. Y en la mayoría de los casos el propio servidor web es el que se encarga de buscar el archivo index.

**Convenciones de HTML**:

- Se debe declarar el tipo de documento en la primera línea: `<!DOCTYPE html>`
- Se recomienda usar minúsculas en las etiquetas y estructuras: `<body>` `<p>`
- Se recomienda cerrar todas las etiquetas y estructuras: `<p>This is a paragraph.</p>`
- Se recomienda usar minúsculas en los atributos: `<a href="https://www.google.com/html/">`
- Se recomienda usar comillas en los valores de atributo: `<table class="striped">`
- Se debe especificar el alt, ancho y alto de las imágenes: `<img src="html5.gif" alt="HTML5" style="width:128px;height:128px">`
- Se recomienda no usar espacios a la hora de usar el signo “=”: `<link rel="stylesheet" href="styles.css">`
- Solo se debe usar líneas en blaco para facilitar la lectura de bloques de códigos grandes o lógicos.
- No se debe omitir el elemento `<title>` ya que es vital para el motor de búsqueda, así como también se recomienda que el contenido de los `<title>` sea preciso y significativo: `<title>HTML Style Guide and Coding Conventions</title>`
- No se recomienda omitir las etiquetas `<html>` y `<body>` ya que puede producir errores en navegadores antiguos y puede bloquear el software DOM y XML.
- Se debe usar el atributo lang para declarar el idioma de la página web: `<html lang="en-us">`
- Se debe utilizar el atributo meta para una interpretación adecuada e indexación correcta en los motores de búsqueda: `<meta charset="UTF-8">`

**CSS**: https://google.github.io/styleguide/htmlcssguide.html
           
**Style.css**

El estilo de cascada (CSS) se puede usar para estilos de texto, por ejemplo, cambiar de color y el tamaño de los encabezados, enlaces, entre otras cosas.

**Convenciones de CSS**:

- Utilizar el protocolo HTTPS para imágenes y otros archivos multimedia: `@import 'https://fonts.googleapis.com/css?family=Open+Sans'` ; Todo el código debe estar en minúsculas como nombres de elementos HTML, atributos, valores de atributo, entre otros: `color : #e5e5e5;`
- El nombre de una clase debe transmitir lo que hace de la forma más breve posible ya que de esta manera se apoya la comprensibilidad y eficiencia del código: navegación {} . autor {} Se debe separar los nombres de las clases con un guión (“-”): navegación {} . autor {}
- Se recomienda usar propiedades abreviadas cuando sea posible: `border - top : 0 ;`
- Se recomienda usar la notación hexadecimal de 3 caracteres en colores que lo permitan: `color : #ebc;`
- Se recomienda ordenar las declaraciones de propiedades y características en orden alfabético
- Se debe usar un “;” después de cada declaración: `pantalla : bloque ;`
- Se debe usar un espacio después de los “:” de cada nombre de la propiedad: `font - weight : bold ;`
- Se debe usar un espacio entre el último sector y la llave “{ “ que comienza el bloque de declaración:. vídeo {.....}
- Se debe usar las comillas simples (‘ ‘) para los atributos y valores de propiedad: `familia de fuentes : ' open sans' , arial , sans - serif ;`

**Gherkin**: https://cucumber.io/docs/gherkin/reference/

**`<usertStoryID>`.featrue** :

En este archivo de formato feature estarán las historias de usuario como características de la aplicación. Asimismo se pueden encontrar los criterios de aceptación para las diversas situaciones.

**Convenciones de Gherkin**:

- Se utiliza la palabra Feature para introducir una descripción de alto nivel de una función de software y agruparlos en escenarios relacionados
- Example o Scenario sirven para plantear una situación
- Se utiliza Given para describir el contexto inicial, When para describir un evento y Then para describir un resultado esperado y And para adicionar información. Given,When,Then y And se usan para describir un escenario
- El carácter “|” sirve para formar una tabla datos, las cuales son útiles para pasar una lista de valores a una definición de paso.

**Java**: https://google.github.io/styleguide/javaguide.html 

**Convenciones de Java**:

- Los nombres de clases y tipos deben ser sustantivos en mayúscula inicial.
- Los nombres de los métodos deben ser minúsculas.
- El nombre de las variables debe ser en minúsculas y usar camel case.
- Para las sentencias if,else,for,do y while se deben usar “ { } “.
- Los nombres de variables que son Constantes deben ir en mayúsculas.

**JavaScript**: https://google.github.io/styleguide/jsguide.html. 

**Convenciones de JavaScript**:

- Se debe usar Camelcase para los nombres de variables y funciones.
- Se debe usar Pascalcase para los nombres de constructores o clases.
- Se debe usar mayúsculas y guiones bajos para los nombres de la constantes, por ejemplo UPPER_CASE_WITH_UNDERSCORES..
- Se debe usar let y const para definir las variables, var debe evitarse.
- Para los comentarios de una sola línea debe usar “ // ” y para bloques de comentario se debe usar  “ /* */ ”.
Se debe incluir un punto y coma al final de cada instrucción.

**TypeScript**: https://google.github.io/styleguide/tsguide.html

**Convenciones de TypeScript**:

- Se debe usar Camelcase para los nombres de variables y funciones.
- Se debe usar Pascalcase para los nombres de interfaces o clases.
- Se debe usar number para valores numéricos, string para cadenas de texto y boolean para los valores booleanos.
- Se debe usar const para las constantes.
- Se debe usar extends para la herencia 
- Se debe usar implements para la implementación de interfaces
- Se debe usar por imports y exports para modularizar el código
- Se debe usar “ | ” para la unión y “ & ” para las intersecciones

**Spring Boot** : https://docs.spring.io/spring-boot/docs/current/reference/html/features.html

**Convenciones de Spring Boot**:

- Se debe emplear @Controller, @Service, @Repository, @Component, @Autowired, entre otros más, para poder definir y gestionar los componentes de Spring.
- Para el manejo de excepciones se debe hacer uso de @ControllerAdvice y @ExceptionHandler para poder gestionar los errores de manera consistente.
- Se debe usar @Transactional para gestionar las transacciones.
- En el caso que se quiera gestionar la autenticación y autorización de una aplicación, se debe usar Spring Security.
- Se debe usar nombre de paquetes y clases descriptivas que reflejan la funcionalidad de los componentes.

**Angular** : https://angular.io/guide/styleguide

**Convenciones de Angular**:

- Se debe usar kebab-case para los nombres de archivos y carpetas, por ejemplo: my-component.component.ts.
- Se debe usar UpperCamelCase para nombrar clases y componentes, por ejemplo: MyComponent
- Se debe usar camelCase para nombrar propiedades y métodos, por ejemplo:myProperty, myMethod().
- Se debe evitar las dependencias circulares entre módulos y componentes.
- Se recomienda usar Typescript en vez de Javascript para poder aprovechar la verificación de tipos estáticos.
- Es recomendable habilitar el modo estricto de Typescript: strict: true en tsconfig.json.

### 5.1.4. Software Deployment Configuration.

En esta sección abordaremos el despliegue de nuestro Landing Page mediante el servicio de Netlify, a continuación se describirán los pasos a seguir

- Nos situamos en el apartado principal como organización
Como organización contamos con un repositorio del landing page, es la cual se estuvo desarrollando la implementación del código. Y este repositorio será el que se vincula a Netlify.
    <img src="./assets/Landing Implementation/step1.png">
- Luego procedemos a iniciar sesión (o crear una cuenta) en https://www.netlify.com. Una vez ingresemos, buscaremos la sección de sitios y le daremos a la opcion de: “Add new site” y luego a “Import from Git”
    <img src="./assets/Landing Implementation/step2.png">
- Una vez estemos seleccionando el proveedor de Git, escogeremos Github
    <img src="./assets/Landing Implementation/step3.png">
- Por último, seleccionaremos el repositorio e indicaremos cual es la branch donde se realizará el deploy y le damos al botón de Deploy.
    <img src="./assets/Landing Implementation/step4.png">
    <img src="./assets/Landing Implementation/step5.png">

## 5.2. Landing Page, Services & Applications Implementation.
### 5.2.1. Sprint 1
#### 5.2.1.1. Sprint Planning 1.

|<a name="_6cxtvwxzjfs6"></a>Sprint #|Sprint 1|
| :- | :- |
|Sprint Planning Background||
|Date|9 del 2024|
|Time|10 horas (GMT -5)|
|Location|Modalidad remota por Meet|
|Prepared By|SiteForge|
|Attendees (to planning meeting)|Todos los miembros del grupo SiteForge|
|Sprint n – 0 Review Summary|Dado que se trata del primer sprint, no hay un review summary de un sprint anterior.|
|Sprint n – 1 Retrospective Summary|En este sprint se planea desarrollar el landing page con el framework de estilos Boostrap, herramienta nueva para algunos miembros del equipo. Además, se conversó sobre el contenido de los textos dentro del landing page y el diseño que se ha implementado anteriormente a través de Figma. Al finalizar este sprint, el landing page debe estar desplegado en Netlify y cualquier usuario debería poder acceder y visualizar la página a través del link.|
|Sprint Goal & User Stories||
|Sprint 1 Velocity|8|
|Sum of Story Points|8|

#### 5.2.1.2. Sprint Backlog 1.

<table><tr><th colspan="2" valign="top"><a name="_6cxtvwxzjfs6"></a><b>SPRINT</b></th><th colspan="6" valign="top"><b>SPRINT 1</b></th></tr>
<tr><td colspan="2" valign="top"></td><td colspan="6" valign="top"><b>Work-Item / Task</b></td></tr>
<tr><td valign="top"><b>User Story ID</b></td><td valign="top"><b>Title</b></td><td valign="top"><b>id</b></td><td valign="top"><b>Title</b></td><td valign="top"><b>Description</b></td><td valign="top"><b>Tiempo (horas)</b></td><td valign="top"><b>Assigned to</b> </td><td valign="top"><b>Status (to-do/ in process/ To review/ done</b></td></tr>
<tr><td rowspan="2" valign="top">E1-US101</td><td rowspan="2" valign="top">Barra de navegación del Landing Page</td><td valign="top">T1</td><td valign="top">Navbar section</td><td valign="top">Implementación del navbar con botón de ingreso a la aplicación WebMasters.</td><td valign="top">2</td><td valign="top"><p>Joseph</p><p>Llacchua</p></td><td valign="top">Done</td></tr>
<tr><td valign="top">T2</td><td valign="top">Responsive design navbar section</td><td valign="top">Añadir el diseño responsive para la barra de navegación</td><td valign="top">2</td><td valign="top"><p>Joseph</p><p>Llacchua</p></td><td valign="top">Done</td></tr>
<tr><td rowspan="2" valign="top">E1-US102</td><td rowspan="2" valign="top">Sección hero de landing page</td><td valign="top">T3</td><td valign="top">Hero section</td><td valign="top">Implementación del apartado hero section</td><td valign="top">3</td><td valign="top">Andre Arroyo</td><td valign="top">Done</td></tr>
<tr><td valign="top">T4</td><td valign="top">Responsive design hero section</td><td valign="top">Añadir el diseño responsive para la hero section</td><td valign="top">4</td><td valign="top">Andre Arroyo</td><td valign="top">Done</td></tr>
<tr><td rowspan="2" valign="top">E1-US103</td><td rowspan="2" valign="top">Sección de producto de landing page</td><td valign="top">T5</td><td valign="top">Features section</td><td valign="top">Implementar sección de características de la aplicación.</td><td valign="top">3</td><td valign="top">Jair Velasquez</td><td valign="top">Done</td></tr>
<tr><td valign="top">T6</td><td valign="top">Responsive design features section</td><td valign="top">Añadir el diseño responsive para la features section</td><td valign="top">1</td><td valign="top">Jair Velasquez</td><td valign="top">Done</td></tr>
<tr><td rowspan="2" valign="top">E1-US104</td><td rowspan="2" valign="top">Sección de testimonios en landing page</td><td valign="top">T7</td><td valign="top">Testimonials section</td><td valign="top">Implementar las tarjetas con los testimonios de los usuarios.</td><td valign="top">3</td><td valign="top">Samira Alvarez</td><td valign="top">Done</td></tr>
<tr><td valign="top">T8</td><td valign="top">Responsive design  testimonials section</td><td valign="top">Añadir el diseño responsive para la sección de testimonios</td><td valign="top">0\.5 </td><td valign="top">Samira Alvarez</td><td valign="top">Done</td></tr>
<tr><td rowspan="2" valign="top">E1-US105</td><td rowspan="2" valign="top">Sección de planes en landing page</td><td valign="top">T19</td><td valign="top">Pricing section</td><td valign="top">Implementar sección de membresía de acuerdo al segmento.</td><td valign="top">3</td><td valign="top">Andre Arroyo</td><td valign="top">Done</td></tr>
<tr><td valign="top">T10</td><td valign="top">Responsive design  pricing section</td><td valign="top">Añadir el diseño responsive para la sección</td><td valign="top">4</td><td valign="top">Andre Arroyo</td><td valign="top">Done</td></tr>
<tr><td rowspan="2" valign="top">E1-US106</td><td rowspan="2" valign="top">Sección de footer a la aplicación en landing page</td><td valign="top">T11</td><td valign="top">Footer section</td><td valign="top">Implementación del footer</td><td valign="top">2</td><td valign="top"><p>Joseph</p><p>Llacchua</p></td><td valign="top">To-Do</td></tr>
<tr><td valign="top">T12</td><td valign="top">Responsive design  footer section</td><td valign="top">Añadir el diseño responsive para la sección</td><td valign="top">2</td><td valign="top"><p>Joseph</p><p>Llacchua</p></td><td valign="top">To-Do</td></tr>
<tr><td rowspan="2" valign="top">E1-US107</td><td rowspan="2" valign="top">Sección para conocer al equipo de trabajo</td><td valign="top">T1</td><td valign="top">Team presentation section</td><td valign="top">Implementar sección con contactos del equipo de trabajo</td><td valign="top">3</td><td valign="top">Zaid Ramirez</td><td valign="top">Done</td></tr>
<tr><td valign="top">T2</td><td valign="top">Responsive design  team presentation section</td><td valign="top">Añadir el diseño responsive para la sección</td><td valign="top">1</td><td valign="top">Zaid Ramirez</td><td valign="top">Done</td></tr>
</table>

#### 5.2.1.3. Development Evidence for Sprint Review.

A continuación, se presentan los commits realizados en el repositorio de la landing page en el Github.
Link del repositorio en Github: https://github.com/upc-pre-202401-si729-wx56-g3/FromZero-LandingPage

|Repository|Branch|Commit Id|Commit Message|Commit Message Body| Commited on (Date) |
| :- | :- | :- | :- | :- | :- |
|FromZero-LandingPage|develop|c37d83725370c6241b03f2c3084fcd0cb12b9232|Initial commit||26/03/2024|
||develop|b4f78db787a4cb34cbf152d7ad84c34f1344eccb|feat: add index.html and directiroesfor css and js||09/04/2024|
||develop|49eb5c4c33cc1ac3f890acb5603d50fa627f5c81|feat: add example.js for directory structure||09/04/2024|
||develop|32be507c3c556d174585131055964a2ce883e083|feat: add bootstrap, html code basic and logoico||09/04/2024|
||develop|80b55e427f570663e638c015cd6e3178f02ae6de|feat: add membership page and styles||09/04/2024|
||develop|089f264d1d20a888f7f44ea61c691c4ad54f61d2|Merge pull request #1 from upc-pre-202401-si729-wx56-g3/feature/membership-weOffer|feat: add membership page and styles and we offer section|09/04/2024|
||develop|896427c7fccaf0dd0d48a34021127bf9d0499bd3|feat: adding subjects 1-3||13/04/2024|
||develop|ec53dba4fb8d94aa86dec0f22ad8ad1472137b86|feat: footer testimonial and blogs added||13/04/2024|
||develop|98180a0fbab193723e74e820b5c15e7708dfa417|Merge pull request #2 from upc-pre-202401-si729-wx56-g3/feature/1-3|feat: adding hero section and created pages|13/04/2024|
||develop|467a343b50eb92ce398eb4b47c0fbe1cdb9c7860|Merge pull request #3 from upc-pre-202401-si729-wx56-g3/feature/featured-section|feat: footer testimonial and blogs added|14/04/2024|
||main|3cef62a769fa0380c6daad94e73548fb617ec20b|Merge pull request #4 from upc-pre-202401-si729-wx56-g3/feature/FAQ-aboutUs|feat: adding Feature/faq about us|14/04/2024|
||main|51b10c25def082c8e92eb8b6c2def9fd86464766|feat: fixing the project structure||14/04/2024|
||main|0c68a9d22dbd3054779c4c0152cd688841e48dfe|feat: fixing # On branch main||14/04/2024|
||main|0c0bdb8b390624c045dbd7b0f5e9dbb8472fb830|Merge branch 'develop'||14/04/2024|
||main|875ea235bf1eb791f9400a6e73bfb9fcdbb0b0f3|feat: fixing logo icon||14/04/2024|

#### 5.2.1.4. Testing Suite Evidence for Sprint Review.

|Repository|Branch|Commit Id|Commit Message|Commit Message Body| Commited on (Date) |
| :- | :- | :- | :- | :- | :- |
|FromZero-LandingPage|main|3cef62a769fa0380c6daad94e73548fb617ec20b|Merge pull request #4 from upc-pre-202401-si729-wx56-g3/feature/FAQ-aboutUs|feat: adding Feature/faq about us|14/04/2024|

#### 5.2.1.5. Execution Evidence for Sprint Review.

Para esta entrega, el equipo SiteForge logró la implementación del landing page, en donde se encontratan secciones con información especifica para conocer mejor a la organización, planeas de pago y proyectos realizados en la página.

Link a la página del landing page: https://fromzeroupc.netlify.app

<img src="./assets/Landing/herosection.png">
<img src="./assets/Landing/proyectos.png">
<img src="./assets/Landing/clientes.png">
<img src="./assets/Landing/membresias.png">

#### 5.2.1.6. Services Documentation Evidence for Sprint Review.

En este sprint los miembros de SiteForge completaron de forma satisfactoria las tareas propuestas. El sprint estuvo netamente enfocado con el diseño y desarrollo de la Landing Page, que con el lanzamiento de la página web se confirma que se termino de forma efectiva el Sprint.

#### 5.2.1.7. Software Deployment Evidence for Sprint Review.

Par el actual sprint, se ha desarrollado el landing page. Par su desplique se ha utilizado las siguientes herramientas:

- Git: Sistema de control de versiones que nos ayudó a trabajar en equipo durante todo el desarrollo del landing page.
- GitFlow: Flujo de trabajo que nos ayudó a controlar el avance de cada integrante del equipo en el desarrollo del landing page.
- GitHub: Plataforma que nos ayudó al desarrollo colaborativo del equipo para almacenar las versiones del proyecto.
- Netlify: Plataforma que automatiza webs estáticas que nos permitió alojar y desplegar el landing page.

Evidencias del despliegue en Netlify:
Repositorio vinculado al deploy e la pagina web:
<img src="./assets/landing/repositorio.png">
Prueba de lanzamiento en Netlify:
<img src="./assets/landing/lanzamiento.png">
Prueba del landing en un navegador:
<img src="./assets/landing/herosection.png">

#### 5.2.1.8. Team Collaboration Insights during Sprint.

El equipo de desarrollo del landing utilizo las ramas para desarrollar cada sección, mejorarlo y actualizarlo, la ventaja de usar estas ramas es que permiten actualizar y luego corroborar que no haya algún error al unirla con la rama master(develop). Ahora se presentará el insight del equipo a través de GitHub:
<img src="./assets/Insights/contribuciones.png">

<img src="./assets/Insights/ramas.png

# Conclusiones
{texto}
# Conclusiones y recomendaciones.
{texto}


# Bibliografía
qoomon. (2021, 11 enero). Conventional Commit Messages. Gist.
Recuperado 20 de junio de 2022, de [LINK](https://gist.github.com/qoomon/5dfcdf8eec66a051ecd85625518cfd13)

LeaseIN. (2018). Importancia de contar con un equipo de soporte
técnico. [Entrada en blog]. Recuperado de:
[LINK](https://leasein.pe/blog/branding-empresarial-importanciasoporte-tecnico/)
``` 
formato

"Apellido", Ini.Ciales. & "otroAutor", O.A. (año). titulo del articulo.
        "nombre del articulo o lo q sea, Volumen(si es que tiene), numero  de pagina"#-#. https//link.org/eeeseneko

```
# Anexos

datos, gráficos, imágenes, esquemas, mapas o referencias de otros autores

![Imagen de algo no nuestro lol](image.jpg)
