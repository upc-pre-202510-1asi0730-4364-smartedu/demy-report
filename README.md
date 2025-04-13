<h1 style="text-align: center;"> Informe TB1 </h1>
<h3 style="text-align: center;"> Universidad Peruana de Ciencias Aplicadas </h3>

<img src="https://raw.githubusercontent.com/desarrollo-de-aplicaciones-open-source/project-open-source/refs/heads/main/assets/logos/upc_logo.png" alt="logo_upc" width="200px" style="display: block; margin-left: auto; margin-right: auto;">

<h5 style="text-align: center"> Ingeniería de Software </h5>

<h5 style="text-align: center"> 1ASI0729 - Aplicaciones Web</h5>

<h5 style="text-align: center"> Seccíón: 4304  </h5>

<h5 style="text-align: center"> Docente: Alex Humberto Sánchez Ponce </h5>

<h5 style="text-align: center"> Startup: SmartEdu </h5>

<h5 style="text-align: center"> Producto: Demy </h5>

<h2>Team members:</h2>

| Código     | Nombre                             |
|------------|------------------------------------|
| U20221G120 | Crispin Ramos, Daniel Franco       |
| U202312318 | Dominguez Vargas, Rafael Alexander |
| U20201E843 | Ramirez Mestanza, Salim Ignacio    |
| U20221C486 | Sulca Gonzales, Paúl Fernando      |
| U20231A778 | Vilca Saboya, Diego Alejandro      |

<h5 style="text-align: center"> Ciclo 2025-01 </h5>

# Registro de Versiones del Informe

# Project Collaboration Insights

# Contenido

- [Capítulo I: Introducción](#capítulo-i-introducción)
    - [1.1. Startup Profile](#11-startup-profile)
        - [1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)
        - [1.1.2. Perfiles de los integrantes del equipo](#112-perfiles-de-los-integrantes-del-equipo)
    - [1.2. Solution Profile](#12-solution-profile)
        - [1.2.1. Antecedentes y problemática](#121-antecedentes-y-problemática)
        - [1.2.2. Lean UX Process](#122-lean-ux-process)
            - [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)
            - [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)
            - [1.2.2.3. Lean UX Hypothesis](#1223-lean-ux-hypothesis)
            - [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)
    - [1.3. Segmentos objetivo](#13-segmentos-objetivo)

- [Capítulo II: Requirements Elicitation & Analysis](#capítulo-ii-requirements-elicitation--analysis)
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

- [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)
    - [3.1. To-Be Scenario Mapping](#31-to-be-scenario-mapping)
    - [3.2. User Stories](#32-user-stories)
    - [3.3. Impact Mapping](#33-impact-mapping)
    - [3.4. Product Backlog](#34-product-backlog)

- [Capítulo IV: Product Design](#capítulo-iv-product-design)
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

- [Capítulo V: Product Implementation, Validation & Deployment](#capítulo-v-product-implementation-validation--deployment)
    - [5.1. Software Configuration Management](#51-software-configuration-management)
        - [5.1.1. Software Development Environment Configuration](#511-software-development-environment-configuration)
        - [5.1.2. Source Code Management](#512-source-code-management)
        - [5.1.3. Source Code Style Guide & Conventions](#513-source-code-style-guide--conventions)
        - [5.1.4. Software Deployment Configuration](#514-software-deployment-configuration)
    - [5.2. Landing Page, Services & Applications Implementation](#52-landing-page-services--applications-implementation)
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
- [Anexos](#anexos)


# Student Outcome

# Capítulo I: Introducción

## 1.1. Startup Profile

### 1.1.1. Descripción de la Startup

### 1.1.2. Perfiles de los integrantes del equipo

## 1.2. Solution Profile

git
### 1.2.1. Antecedentes y problemática

### 1.2.2. Lean UX Process

El Lean UX Process es una metodología ágil que nos permite diseñar soluciones centradas en el usuario, validando hipótesis mediante ciclos de prueba, retroalimentación y aprendizaje continuo.
En este proyecto, aplicamos este enfoque para resolver los desafíos administrativos que enfrentan las academias presenciales, partiendo de problemáticas reales y construyendo una plataforma que responda a sus necesidades.

#### 1.2.2.1 Lean UX Problem Statements

El servicio de Demy tiene como objetivo proporcionar a las instituciones educativas privadas una plataforma web integral que permita automatizar procesos administrativos esenciales, como matrículas, control de asistencia, asignación de horarios, docentes y salones, seguimiento de pagos y gestión de recursos y materiales.

El problema se manifiesta en la manera tradicional y desorganizada con la que muchas academias manejan su administración interna. Actualmente, la mayoría utiliza herramientas básicas como hojas de Excel, documentos físicos o plataformas que no están integradas entre sí. Esto genera duplicidad de tareas, falta de trazabilidad, pérdida de información clave, errores en la asignación de recursos y complicaciones en la gestión de pagos y control de asistencia. Como consecuencia, el personal administrativo invierte un tiempo excesivo en tareas repetitivas, y los docentes enfrentan dificultades para coordinar sus horarios o registrar adecuadamente la asistencia y rendimiento de los alumnos.

Hemos identificado que esta deficiencia en la administración limita seriamente la capacidad de crecimiento y profesionalización de muchas academias. Además, deteriora la experiencia de alumnos y profesores, y afecta negativamente la percepción del servicio ofrecido. La ausencia de un sistema unificado también impide tomar decisiones informadas sobre finanzas, rendimiento académico y uso de recursos, generando un impacto directo en la sostenibilidad del negocio.

¿Cómo podríamos centralizar y automatizar la gestión administrativa de academias presenciales de forma escalable y accesible, permitiendo al personal administrativo y docente ahorrar tiempo, reducir errores y mejorar el control sobre los procesos clave del día a día?

#### 1.2.2.2. Lean UX Assumptions

#### Business Assumptions

1. **Creemos que nuestros clientes necesitan** una plataforma web centralizada que les permita automatizar y simplificar su gestión administrativa diaria.
2. **Estas necesidades se pueden resolver con** un sistema web que facilite procesos clave como la matrícula de alumnos, control de asistencia, asignación de horarios, docentes y salones, gestión de inventario y seguimiento de pagos.
3. **Nuestros clientes iniciales serán** los administradores y docentes de academias educativas presenciales pequeñas, medianas y grandes que actualmente operan con métodos manuales o herramientas desarticuladas.
4. **El valor más importante que el cliente quiere de nuestro servicio es** tener mayor control y eficiencia en la administración de su academia, reduciendo la carga operativa y los errores humanos, y facilitando la toma de decisiones.
5. **El cliente también puede obtener beneficios adicionales** como recordatorios de pagos vencidos, seguimiento de inventario para reposición y escalabilidad mediante distintos planes por tamaño de academia.
6. **Vamos a adquirir la mayoría de nuestros clientes mediante** marketing digital dirigido en redes sociales (Facebook, Instagram, TikTok), campañas en Google Ads y alianzas con gremios educativos.
7. **Generaremos dinero a través de** un modelo de suscripción mensual escalable, con tres planes: Essentials $19.90 (academias pequeñas); Pro $69.90 (academias medianas); Elite $159.90 (academias grandes).
8. **Nuestra competencia principal en el mercado son** sistemas genéricos de gestión escolar, soluciones empresariales o especializadas y hojas de cálculo utilizadas por academias.
9. **Lo venceremos debido a** ofrecer una solución enfocada específicamente en academias presenciales, con una interfaz amigable, soporte local y funciones diseñadas desde el enfoque de sus procesos reales.
10. **El mayor riesgo del servicio es** que las academias, especialmente las pequeñas, no estén dispuestas a migrar desde sus métodos manuales actuales por temor al cambio o falta de conocimiento tecnológico.
11. **Resolveremos esto a través de** una interfaz simple y guiada, materiales de capacitación, soporte personalizado para la implementación, y un periodo de prueba gratuito para incentivar la adopción.

#### User Assumptions

**¿Quién es el usuario?**

Principalmente, el personal administrativo y los docentes de academias educativas que necesitan herramientas accesibles y prácticas para gestionar alumnos, horarios y pagos.

**¿Qué problema tiene nuestro producto que debe resolver?**

El problema radica en el desorden de los procesos administrativos, la pérdida de tiempo por tareas repetitivas, falta de visibilidad sobre pagos y asistencias.

**¿Qué características son importantes?**

Destacan principalmente el control de matrículas y asistencia, la asignación de horarios, salones y docentes, recordatorios de pagos vencidos e inventario con seguimiento de stock.

**¿Dónde encaja nuestro producto en su trabajo o vida?**

En el día a día laboral de los administradores y docentes, ayudándolos a organizar, controlar y optimizar la operación de su academia desde un solo lugar.

**¿Cúando y cómo es nuestro producto? ¿Usado?**

Será usado todos los días hábiles, especialmente al inicio de clases, al registrar asistencia, gestionar horarios o monitorear pagos.
Accederán desde computadoras o laptops, y en algunos casos desde tablets o smartphones.

**¿Cómo debe verse nuestro producto y cómo debe comportarse?**

Debe tener una interfaz moderna, clara y adaptable a cualquier dispositivo. La navegación debe ser intuitiva, con acciones guiadas y accesibles para usarlos sin conocimientos técnicos.
El sistema debe responder rápido, enviar notificaciones útiles y garantizar la seguridad de la información.

#### 1.2.2.3. Lean UX Hypothesis

- **Hypothesis 01:**

  **Creemos que** los administradores de academias presenciales estarán dispuestos a adoptar nuestra plataforma web para digitalizar procesos como matrícula, pagos, asistencia y asignación de horarios.

  **Sabremos que** hemos tenido éxito.

  **Cuando** al menos el 70% de los usuarios activos usen la plataforma para gestionar estos procesos durante el primer mes de uso, y al menos el 60% renueve su suscripción tras el primer ciclo mensual.


- **Hypothesis 02:**

  **Creemos que** la integración de recordatorios de morosidad y vencimiento de pagos reducirá significativamente el retraso en los pagos de los alumnos.

  **Sabremos que** hemos tenido éxito.

  **Cuando** el porcentaje de pagos vencidos disminuye en al menos un 40% entre los usuarios que adoptan esta funcionalidad en los primeros tres meses.


- **Hypothesis 03:**

  **Creemos que** permitir la gestión del inventario (como libros, plumones o equipos) dentro del sistema facilitará el control de materiales y reducirá pérdida o faltantes.

  **Sabremos que** hemos tenido éxito.

  **Cuando** al menos el 80% de las academias con más de una sede reporten una mejora en el seguimiento de materiales y una disminución de pérdidas en un periodo de 2 meses.


- **Hypothesis 04:**

  **Creemos que** la interfaz intuitiva y el diseño responsivo de la plataforma aumentará la frecuencia de uso por parte de docentes y personal administrativo, incluso si no tienen experiencia tecnológica previa.

  **Sabremos que** hemos tenido éxito.

  **Cuando** al menos el 75% de los usuarios califiquen la usabilidad de la plataforma como "fácil" o "muy fácil" en las encuestas de satisfacción realizadas durante la fase piloto.


- **Hypothesis 05:**

  **Creemos que** ofrecer planes escalables (Essentials, Pro, Elite) permitirá a las academias elegir el plan adecuado según su tamaño, y facilitará el crecimiento dentro del mismo sistema.

  **Sabremos que** hemos tenido éxito.

  **Cuando** al menos el 25% de los clientes del plan Essentials migren al plan Pro o Elite en los primeros seis meses de uso.

#### 1.2.2.4. Lean UX Canvas

El Lean UX Canvas nos permite organizar de forma clara y colaborativa los elementos clave del diseño: problema, usuarios, suposiciones, hipótesis y métricas.
En este proyecto, nos ayuda a enfocar el desarrollo en generar valor real para las academias educativas.
A continuación se presenta el Lean UX Canvas elaborado en la herramienta Miro.

![Lean UX Canvas](./assets/images/lean-ux-canvas.jpg)
*Figura 1. Lean UX Canvas del proyecto.*

**Enlace al Lean UX Canvas:** [Ver en Miro](https://miro.com/app/board/uXjVIGPrhA0=/?share_link_id=155958536023)

## 1.3. Segmentos objetivo

# Capítulo II: Requirements Elicitation & Analysis

## 2.1. Competidores

### 2.1.1. Análisis competitivo
Esta sección tiene objetivo conocer mejor los competidores a los que se enfrentará SmartEDU y poder así comparar nuestros beneficios.

|**Competitive Analysis Landscape** |                             |                   
|-----------------------------------|-----------------------------|
| ¿Por qué llevar acabo este análisis?| El objetivo de este análisis competitivo es saber como será nuestro posicionamiento en el mercado en comparación a otros sistema de gestión de academias y que será lo que nos hará destacar|

|                     |                                                                           | SmartEdu                                                                                                                                                                                                                          | Academygest                                                                                                                                                            | Playoff                                                                                                                                                                                                                                                                                  | Quickschools                                                                                                                                                                                                                                                                                  |
|---------------------|---------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Perfil              | Overview                                                                  | SmartEdu ofrece a Demy, un sistema web integral que facilita la organización, carga operativa y mejora la experiencia tanto de alumnos como docentes.                                                                             | Plataforma integral que facilita la gestión de academias y centros educativos, permitiendo organizar y mantener datos de alumnos.                                      | Sistema de gestión para entidades, que una de sus opciones es un enfoque a academias, ofreciendo cosas como control de cobros y pagos junto a organización de actividades                                                                                                                | QuickSchools es una plataforma en la nube para gestionar escuelas, con funciones como calificaciones, asistencia y comunicación con padres. Está pensada para instituciones pequeñas y medianas.                                                                                              |
|                     | Ventaja <br> competitiva <br> ¿Qué valor <br> ofrece a los <br> clientes? | Solución integral y escalable para la administración de academias, que a la vez tendrá mucha accesibilidad ofrenciendo diferentes de acuerdo a que le convenga más a la academia                                                  | Optimización de la gestión administrativa, ahorro de tiempo y mejora de la eficiencia en la administración de academias y centros educativos.                          | Mejora de la motivación y participación en programas de formación y gestión mediante dinámicas de juego personalizadas                                                                                                                                                                   | Solución accesible y flexible para la gestión administrativa y académica, con un enfoque en facilidad de uso y personalización.                                                                                                                                                               |
| Perfil de marketing | Mercado objetivo                                                          | Academia presenciales preuniversitarias ( con una sede o varias sedes)                                                                                                                                                            | Academias y centros de formación en España, enfocados en cursos profesionales o empresariales, que requieren control académico, administrativo y financiero.           | Playoff está dirigido a entidades educativas, corporativas y de formación que buscan aumentar la motivación y participación mediante gamificación.                                                                                                                                       | Escuelas pequeñas y medianas a nivel global (como colegios K-12 y privados) que necesitan una solución simple y flexible para gestionar procesos académicos.                                                                                                                                  |
|                     | Estrategias de Marketing                                                  | Ofrece anuncios en la televesión, junto a redes sociales como tiktok,instagram o facebook.                                                                                                                                        | Campañas en línea enfocadas en instituciones educativas que buscan soluciones de gestión                                                                               | Publica artículos,estudios de caso y guías sobre la implementación efectiva de estrategia de gamificación en empresas <br> Muestra casos de uso de como la gamificación                                                                                                                  | Ofrece guías para atraer y retener clientes potenciales interesados en su mejora de procesos educativos                                                                                                                                                                                       |
| Perfil de producto  | Productos & Servicios                                                     | Registro y matrícula de alumnos <br> Automatizacíon de gestión de pagos y suscripciones <br> Toma de asistencia <br> Gestión de inventario                                                                                        | Control de asistencia de alumnos <br> Gestión de pagos como cobros y finanzas <br> Gestión de informes  <br> Envío de SMS  a los alumnos                               | Plataforma de gamificación <br> Gamificación educativa <br> Análisis y reportes de la participacíon y el progreso <br> Customización de experiencias:personalizacíon de la plataforma según la entidad, ya sea Academias o empresas                                                      | Herramientas para siempre mantener informado a los padres y estudiantes <br> Un gradebook personalizado <br> Horario de clases inteligente <br>                                                                                                                                               |
|                     | Precios y Costos                                                          | Plan Básico:  \$50 / mes , dirigido a pequeñas academias ( 1 sede). <br> Plan Intermedio: $100 /mes , dirigido a academias medianas (2 sedes) <br> Plan Premium: \$200, dirigido a academias grandes ( varias sedes)              | 25€  /mes, que incluye :<br/>- Sin instalaciones <br/>- 24 horas del día disponible <br> -Alumnos y cursos ilimitados <br> -Asistencia de Alumnos <br> Soporte técnico | Incluye 15 días de prueba gratuita, por otro lado los planes son:<br/> Plan Base( 34,95€), para los que empiezan <br/> Plan pro (49,95€), para los que llevan poco<br/> Plan Top ( 69,95€) para los veteranos<br/> Plan Premium ( tarifa personalizada), acuerdo a tratar con la empresa | Gaia Plan ( \$0.99) por estudiante por mes<br/> Apollo Plan ( $1.49) por estudiante por mes <br/> Athena plan (\$2.99) por estudiante por mes <br/> Todos los planes incluyen una prueba gratuita de 30 días, <br/>además puedes ponerte en contacto con quickschools para un Enterprise Plan |
|                     | Canales de distribución <br> Web o móvil                                  | Demy actualmente solo se distribuye exclusivamente en Web                                                                                                                                                                         | Solo disponible a través de navegadores web                                                                                                                            | Se distribuye de manera web pero con el Plan Pro tendrás acceso a la app móvil.                                                                                                                                                                                                          | Se distribuye de manera web y móvil.                                                                                                                                                                                                                                                          |
| Análisis Swot       | Fortalezas                                                                | Incluye varios planes de acuerdo al alcance de la academia <br/> Producto especializado en academias preuniversitarias<br/>                                                                                                       | Plataforma integral especializada en academias pequeñas y medianas. <br> Interfaz intuitiva y en idioma español <br> Cobertura de funciones básicas de gestión         | Especialización en gamificación, un campo en crecimiento <br/> Altamante adaptable a distintos sectores ( Academias, RRHH, ventas) <br/>                                                                                                                                                 | Plataforma madura, flexible y con planes escalables <br/> Soporte al cliente efectivo <br/>                                                                                                                                                                                                   |
|                     | Debilidades                                                               | SmartEdu al ser una startup emergente no cuenta con mucho financiamiento <br/> No cuenta con una app móvil <br/>                                                                                                                  | No cuenta con una app móvil <br/> Se limite presencialmente a españa <br/> Menor reconocimiento frente a competidores globales                                         | No es una solución académica integral, más bien un complemento<br/> Requiere personalización técnica <br/>  La app móvil es solo accesible a partir de un cierto plan<br/>                                                                                                               | Puede resultar costo a gran escala si no se optimiza el uso <br/> Limitado al idioma inglés                                                                                                                                                                                                   |
|                     | Oportunidades                                                             | Poca competencia en el segmento objetivo <br/> Aumento en el uso de la tecnología luego del COVID-19 <br/>                                                                                                                        | Ampliar su presencia a latinomerica <br/> Incorporar una app móvil para una buena complementación y accesibilidad <br/>                                                | Amplicación creciente de la gamificacíon en la actualidad<br/> Alianza con plataforams educativas para ofrecer gamificacíon integrada<br/>                                                                                                                                               | Incluir el idioma español para ser más global  <br/>  Alianzas con gobiernos o redes escolares                                                                                                                                                                                                |           
|                     | Amenazas                                                                  | Resistencia al cambio tecnológico de parte de algunas academias <br/> Soluciones muy fuertes de otros competidores <br/> Posibles ciberataques, ya que la startup no tiene mucho conocimiento sobre la ciberseguridad actualmente | Dependencia de un solo mercado geográfico <br/> Competencia con soluciones globales más completas y flexibles                                                          | Dependencia de clientes que comprendan el valor de la gamificación<br/>                                                                                                                                                                                                                  | Compite con plataformas globables que incluye varios idiomas <br/> Riesgo de saturación en el mercado K-12                                                                                                                                                                                    |


### 2.1.2. Estrategias y tácticas frente a competidores
Para competir eficazmente en el mercado de plataformas de gestión para academias presenciales, SmartEdu aplicará las siguientes estrategias y tácticas preliminares, considerando sus propias fortalezas y debilidades, así como el contexto de oportunidades y amenazas en relación a sus competidores:

* Diferenciación por enfoque especializado <br>
  **Estrategia**: Posicionar a Demy como la plataforma especializada en academias preuniversitarias presenciales, a diferencia de otros competidores que ofrecen soluciones más genéricas o centradas en colegios o empresas.
  <br>
  **Tácticas**:Desarrollar funcionalidades específicas para academias preuniversitarias, como módulos de simulacros, cronogramas de preparación para exámenes de admisión

<br>

* Modelo de precios escalables
  <br>
  **Estrategia**:Mantener un esquema de precios accesible, con planes diferenciados según el tamaño de la academia, y con mejor relación calidad-precio frente a competidores como QuickSchools o Playoff.
  <br>
  **Tácticas**: Evaluar una prueba gratuita de n días , Ofrecer descuentos cada cierto tiempo o evaluar una contratación anual incluida con descuento

<br>

* Mejora progresiva del producto y adaptabilidad
  <br>
  **Estrategia**:Competir frente a soluciones más maduras (como QuickSchools) con un enfoque ágil y adaptable, incorporando mejoras constantes con base en la retroalimentación directa de los usuarios.
  <br>
  **Tácticas**: Lanzamientos de mejoras mensuales (por sprints) , futura implementación de la versión móvil.

<br>

*  Seguridad y confianza
   <br>
   **Estrategia**:  Reducir la percepción de riesgo en torno a ciberseguridad, una amenaza para startups, generando confianza desde etapas tempranas.
   <br>
   **Táctica**:Contratar un servicio externo para auditorías de seguridad básicas.

<br>

* Aprovechamiento del contexto post-pandemia
  <br>
  **Estrategia**: Capitalizar el aumento de la digitalización en la educación tras el COVID-19 para incentivar la transformación digital de academias tradicionales
  <br>
  **Tácticas**: Ofrecer workshops gratuitos virtuales sobre “Digitaliza tu academia en 3 pasos con Demy”. Enseñar casos de éxito que muestren cómo academias presenciales mejoraron su eficiencia tras usar la plataforma.



## 2.2. Entrevistas

En esta sección se aborda la investigación cualitativa realizada mediante entrevistas a representantes de los segmentos objetivo del proyecto: administrativos y docentes de academias educativas.
El objetivo fue comprender las herramientas, procesos y problemáticas actuales en su gestión, así como validar posibles soluciones digitales a partir de sus propias experiencias.

### 2.2.1. Diseño de entrevistas

Para diseñar las entrevistas, se elaboraron dos bloques de preguntas, diferenciados según el segmento objetivo.
Las preguntas buscaban obtener tanto información objetiva (como el contexto de trabajo y herramientas utilizadas) como información subjetiva (percepciones, frustraciones y expectativas respecto a posibles soluciones).

---

#### **Segmento 1: Administrativos de academias**

**Preguntas sobre la problemática**

1. ¿Cómo gestionan actualmente los procesos administrativos como matrículas, horarios, pagos y asistencia?

2. ¿Qué problemas frecuentes enfrentas con las herramientas o métodos que usas hoy?

3. ¿Qué tipo de información necesitas consultar con frecuencia, y qué tan fácil es acceder a ella?

4. ¿Qué consecuencias trae la desorganización o errores en la administración para ti o tu equipo?

**Preguntas sobre la solución**

1. ¿Qué funcionalidades crees que debería tener una herramienta ideal para facilitar tu trabajo administrativo?

2. ¿Qué tan importante sería para ti recibir alertas sobre tareas o pagos?

3. ¿Preferirías un sistema con muchas funciones o uno más simple pero fácil de usar?

4. ¿Qué beneficios esperas obtener si decides adoptar una nueva plataforma de gestión?

5. ¿Estarías dispuesto a aprender a usar una nueva herramienta si mejora tu gestión (organización)?

---

#### **Segmento 2: Docentes de academias**

**Preguntas sobre la problemática**

1. ¿Qué herramientas o métodos usas para registrar asistencia o notas en caso lo hagas? ¿Funcionan bien para usted?

2. ¿Qué tipo de coordinación tiene con el personal administrativo? ¿Es fácil comunicarse con ellos o enfrenta dificultades?

3. ¿Cómo accedes a la información de tus clases o alumnos cuando la necesitas?

4. ¿Cómo manejas los cambios de aula, horarios u otras incidencias en tu día a día?

**Preguntas sobre la solución**

1. ¿Qué funcionalidades te gustaría que tenga una herramienta digital para docentes?

2. ¿Qué tan útil sería para ti revisar tu horario o registrar asistencia desde cualquier dispositivo?

3. ¿Qué tan importante es que la plataforma sea fácil de usar e intuitiva?

4. ¿Preferirías acceder a la plataforma desde tu celular, tablet o computadora?

5. ¿Qué tan valioso sería que recibas alertas (notificaciones) sobre cambios de horario o asistencia irregular, y demás?

6. ¿Estarías dispuesto a aprender a usar una nueva herramienta si mejora tu gestión (organización)?

### 2.2.2. Registro de entrevistas

#### Segmento: Docente - Entrevistado 2

| Atributo                | Detalle                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
|-------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Nombre**              | Jean Paul Benezú                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| **Edad**                | 21 años                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| **Sexo**                | Masculino                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| **Distrito**            | Santa Anita                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
| **Ocupación**           | Docente en CEPRE Agraria                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| **Fecha de entrevista** | 08 de abril del 2025                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| **Duración**            | 14:46 minutos                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
| **Captura**             | ![Captura](./assets/screenshots/interview-screenshot-teacher1.png)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| **Video**               | [Ver en Microsoft Stream](https://upcedupe-my.sharepoint.com/:v:/g/personal/u20201e843_upc_edu_pe/EWQAxTMJq4tJpIHJ90rbWfYBCZKPnkxth6JTmDrxSy7_1Q?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=FIc2F9)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| **Resumen**             | El entrevistado enseña en una academia preuniversitaria y usa Excel para registrar notas y asistencia, además de Google Forms en algunos casos. Si bien la comunicación con el personal administrativo es buena, ha experimentado dificultades al reprogramar clases debido a la baja asistencia en días especiales, por lo que realiza encuestas para reagendar. Considera fundamental contar con una herramienta centralizada que le permita registrar notas y asistencia de forma ordenada. Valora altamente que la plataforma sea intuitiva, visualmente simple y accesible desde su celular. También sugiere que padres o tutores puedan acceder a la información. Aunque no le interesa recibir alertas por notas o asistencia, considera clave recibir notificaciones por cambios de horario. Está dispuesto a aprender a usar nuevas herramientas si percibe una mejora real en su productividad. |

#### Segmento: Docente - Entrevistado 3

| Atributo                | Detalle                                                                     |
|-------------------------|-----------------------------------------------------------------------------|
| **Nombre**              | Jeff Aylas Quispe Vergara                                                   |
| **Edad**                | 25                                                                          |
| **Sexo**                | Masculino                                                                   |
| **Distrito**            | San Juan de Lurigancho                                                      |
| **Ocupación**           | Docente en Academia ADUNI                                                   |
| **Fecha de entrevista** | 11 de abril del 2025                                                        |
| **Duración**            | 4:28 minutos                                                                |
| **Captura**             | ![Captura](./assets/screenshots/interview-screenshot-teacher3.png)          |
| **Video**               | [Ver en Microsoft Stream](https://upcedupe-my.sharepoint.com/personal/u20201e843_upc_edu_pe/_layouts/15/stream.aspx?id=%2Fpersonal%2Fu20201e843%5Fupc%5Fedu%5Fpe%2FDocuments%2FDemy%2FEntrevistas%2Fvideo%2Dentrevista%2Ddocente3%2Emp4&referrer=StreamWebApp%2EWeb&referrerScenario=AddressBarCopied%2Eview%2E6dbf826d%2Dd312%2D4e22%2Dadea%2D45cb75a98def)                                                 |
| **Resumen**             | El docente entrevistado, que además es estudiante, utiliza principalmente herramientas como hojas de Excel o cuadernos para registrar asistencia y notas, aunque reconoce que no siempre son prácticas ni eficientes. La coordinación con el personal administrativo se da por canales informales como WhatsApp o correo, lo que a veces genera demoras y falta de claridad. El acceso a la información de clases o alumnos no está centralizado, lo que le obliga a recurrir a sus apuntes o hacer consultas adicionales. Los cambios de aula o horario suelen comunicarse de manera improvisada, lo que puede causar confusión. Valora la posibilidad de contar con una herramienta digital que integre funciones clave como registro de asistencia, horarios, notas y observaciones, accesible desde cualquier dispositivo, especialmente el celular. Considera fundamental que la plataforma sea fácil de usar e intuitiva, ya que si es compleja, volvería a sus métodos tradicionales. Además, percibe como muy útil recibir alertas sobre incidencias o comportamientos irregulares. Está dispuesto a adoptar una nueva herramienta siempre que le facilite la gestión y no represente una carga adicional de aprendizaje. |

### 2.2.3. Análisis de entrevistas

## 2.3. Needfinding

### 2.3.1. User Personas

### 2.3.2. User Task Matrix

### 2.3.3. User Journey Mapping
A continuación se presentarán los User Journey Maps de cada User Persona. Estos mapas nos permitirán comprender los puntos de dolor que experimentan en cada etapa, desde que descubren nuestra app hasta que comparten su opinión sobre ella.

* User Journey Map de Luis Mendoza:
![User Journey Map del User Persona Luis Mendoza](./assets/images/User Journey Map Luis Mendoza.png)
[Ver Imagen detallada aquí](https://drive.google.com/file/d/1ZwP-W8qpUPP0yI6UFXMareIiCiphqNrr/view?usp=sharing)


* User Journey Map de Carmen Gutiérrez:
![User Journey Map del User Persona Carmen Gutiérrez](./assets/images/User Journey Map Carmen Gutiérrez.png)
[Ver Imagen detallada aquí](https://drive.google.com/file/d/1oGSadSkVdSIzf-MeaMGnYL06wVVFKkJG/view?usp=sharing)

### 2.3.4. Empathy Mapping

### 2.3.5. As-Is Scenario Mapping

## 2.4. Ubiquitous Language

# Capítulo III: Requirements Specification

## 3.1. To-Be Scenario Mapping.

## 3.2. User Stories

## 3.3. Impact Mapping

## 3.4. Product Backlog

# Capítulo IV: Product Design

## 4.1. Style Guidelines

### 4.1.1. General Style Guidelines

### 4.1.2. Web Style Guidelines

## 4.2. Information Architecture

### 4.2.1. Organization Systems

### 4.2.2. Labeling Systems

### 4.2.3. SEO Tags and Meta Tags

### 4.2.4. Searching Systems

### 4.2.5. Navigation Systems

## 4.3. Landing Page UI Design

### 4.3.1. Landing Page Wireframe

### 4.3.2. Landing Page Mock-up

## 4.4. Web Applications UX/UI Design

### 4.4.1. Web Applications Wireframes

### 4.4.2. Web Applications Wireflow Diagrams

### 4.4.3. Web Applications Mock-ups

### 4.4.4. Web Applications User Flow Diagrams

## 4.5. Web Applications Prototyping

## 4.6. Domain-Driven Software Architecture

### 4.6.1. Software Architecture Context Diagram

### 4.6.2. Software Architecture Container Diagrams

### 4.6.3. Software Architecture Components Diagrams

## 4.7. Software Object-Oriented Design

### 4.7.1. Class Diagrams

### 4.7.2. Class Dictionary

## 4.8. Database Design

### 4.8.1. Database Diagram

# Capítulo V: Product Implementation, Validation & Deployment
## 5.1. Software Configuration Management

### 5.1.1. Software Development Environment Configuration

### 5.1.2. Source Code Management

### 5.1.3. Source Code Style Guide & Conventions

### 5.1.4. Software Deployment Configuration.

## 5.2. Landing Page, Services & Applications Implementation

### 5.2.1. Sprint 1

#### 5.2.1.1. Sprint Planning 1

#### 5.2.1.2. Sprint Backlog 1


#### 5.2.1.3. Development Evidence for Sprint Review

#### 5.2.1.4. Testing Suite Evidence for Sprint Review

#### 5.2.1.5. Execution Evidence for Sprint Review


#### 5.2.1.6. Services Documentation Evidence for Sprint Review


#### 5.2.1.7. Software Deployment Evidence for Sprint Review


#### 5.2.1.8. Team Collaboration Insights during Sprint

# Conclusiones

## Conclusiones y Recomendaciones

## Video About-the-Team

# Bibliografía

# Anexos
