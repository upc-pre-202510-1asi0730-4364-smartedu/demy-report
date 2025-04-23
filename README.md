<h1 style="text-align: center;"> Informe TB1 </h1>
<h3 style="text-align: center;"> Universidad Peruana de Ciencias Aplicadas </h3>

<img src="https://raw.githubusercontent.com/desarrollo-de-aplicaciones-open-source/project-open-source/refs/heads/main/assets/logos/upc_logo.png" alt="logo_upc" width="200px" style="display: block; margin-left: auto; margin-right: auto;">

<h5 style="text-align: center"> Ingeniería de Software </h5>

<h5 style="text-align: center"> 1ASI0729 - Desarrollo de Aplicaciones Open Source </h5>

<h5 style="text-align: center"> Seccíón: 4304  </h5>

<h5 style="text-align: center"> Docente: Efraín Ricardo Bautista Ubillús </h5>

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

La startup **SmartEdu**, conformada por estudiantes de la carrera de Ingeniería de Software, tiene como objetivo ofrecer una solución tecnológica para optimizar la gestión administrativa de academias educativas en el Perú. A través de nuestra plataforma web **Demy**, buscamos agilizar y mejorar los procesos fundamentales dentro de las academias, como la matrícula de alumnos, la gestión de asistencia, la asignación de horarios, y la administración de inventarios. Además, se incorpora el seguimiento de pagos tanto para estudiantes como para docentes, todo a través de un sistema centralizado y de fácil acceso.

**Misión**: Revolucionar la gestión administrativa de las academias educativas en el Perú, ofreciendo una plataforma que optimice procesos clave de matrícula, asistencia, asignación de horarios, control de inventarios y pagos.

**Visión**: Convertirnos en líderes en la transformación digital de la gestión administrativa de academias educativas presenciales en el Perú, asegurando la eficiencia, transparencia y accesibilidad de sus procesos internos mediante soluciones tecnológicas innovadoras.


### 1.1.2. Perfiles de los integrantes del equipo

| **Foto**         | **Nombre**                            | **Código** | **Carrera**            | **Resumen de Conocimientos Técnicos y Habilidades**                                                                                        |
|------------------|---------------------------------------|------------|------------------------|--------------------------------------------------------------------------------------------------------------------------------------------|
| ![Foto_Daniel]() | **Daniel Franco Crispin Ramos**       | U20221G120 | Ingeniería de Software | Conocimiento en bases de datos y gestión de proyectos. Experiencia en interfaces de usuario y soluciones para la administración educativa. |
| ![Foto_Paul]()   | **Paul Fernando Sulca Gonzales**      | U20221C486 | Ingeniería de Software |                                                                                                                                            |
| ![Foto_Salim]()  | **Salim Ignacio Ramirez Mestanza**    | U20201E843 | Ingeniería de Software |                                                                                                                                            |
| ![Foto_Diego]()  | **Diego Alejandro Vilca Saboya**      | U20231A778 | Ingeniería de Software |                                                                                                                                            |
| ![Foto_Rafael]() | **Rafael Alexander Dominguez Vargas** | U202312318 | Ingeniería de Software |                                                                                                                                            |

## 1.2. Solution Profile

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

### 2.1.2. Estrategias y tácticas frente a competidores

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

#### Segmento: [Docente / Administrativo] - Entrevistado [N°]

| Atributo                | Detalle |
|-------------------------|---------|
| **Nombre**              | [Nombre completo del entrevistado] |
| **Edad**                | [Edad] |
| **Sexo**                | [Masculino / Femenino] |
| **Distrito**            | [Distrito de residencia] |
| **Ocupación**           | [Cargo o rol en la institución educativa] |
| **Fecha de entrevista** | [Fecha] |
| **Duración**            | [Minutos y segundos de duración del video] |
| **Captura**             | ![Captura](./assets/screenshots/[nombre].jpg) |
| **Video**               | [Ver en Microsoft Stream]([link]) |
| **Resumen**             | [Redactar un resumen claro, en párrafo, que combine aspectos objetivos (herramientas, procesos, frecuencia de uso, dispositivos, coordinación con otros actores) y subjetivos (percepciones, dolores, expectativas, disposición a adoptar nuevas herramientas). Debe ser completo pero conciso, entre 8 y 12 líneas es ideal.] |

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

#### Segmento: Administrativo - Entrevistado 3

| Atributo                | Detalle                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
|-------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Nombre**              | Jhon Robert Candioti                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |
| **Edad**                | 42 años                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| **Sexo**                | Masculino                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |
| **Distrito**            | Ica                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
| **Ocupación**           | Dueño y administrativo de la academia Enigmas                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| **Fecha de entrevista** | 09 de abril del 2025                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |
| **Duración**            | 8:27 minutos                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| **Captura**             | ![Captura](./assets/screenshots/interview-screenshot-administrator3.png)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| **Video**               | [Ver en Microsoft Stream](https://upcedupe-my.sharepoint.com/:v:/g/personal/u20201e843_upc_edu_pe/EaQ5KVEex65KtKOix6TXG5kBVHG4dwUDkPTVICrfJOErnA?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=kV6CSu )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| **Resúmen**             | John Robert, administrador de la academia Enigmas en Ica, lleva 1 año gestionando los procesos administrativos de su academia. Actualmente, utiliza Excel para manejar datos como matrículas, asistencia, pagos y horarios, lo cual le genera problemas de desorganización y falta de tiempo debido a la complejidad de navegar entre diferentes hojas de cálculo. Destaca que el estrés y los errores derivados de este método afectan la eficiencia de su trabajo. Busca una herramienta más sencilla y automatizada, que le permita acceder rápidamente a la información con solo ingresar el DNI de los estudiantes y los apoderados. Además, le gustaría contar con un registro de pagos pendientes y, lo que mejoraría su productividad. Está dispuesto a aprender a utilizar una nueva plataforma si esta resulta fácil de manejar y optimiza la gestión de la academia. |


### 2.2.3. Análisis de entrevistas

## 2.3. Needfinding

El Needfinding permite identificar necesidades reales de los usuarios mediante entrevistas y análisis del contexto.
A partir de esta información, se construyeron artefactos clave que ayudaron a comprender mejor sus objetivos, tareas, emociones y frustraciones.

### 2.3.1. User Personas

Los User Personas fueron elaborados a partir de los hallazgos de las entrevistas, reflejando perfiles representativos de los segmentos objetivo.
Cada ficha sintetiza aspectos demográficos, conductuales y emocionales que guían el diseño funcional y visual de la plataforma.

---

#### User Persona: Administrador de academia

Coordinadora administrativa que necesita centralizar pagos, matrículas y horarios.
Busca evitar errores, ahorrar tiempo y modernizar los procesos de su academia.

![User Persona – Administrator](./assets/images/user-persona-admin.png)
**Figura 2.** User Persona del segmento *Administrador*.

---

#### User Persona: Docente de academia

Profesor joven que busca herramientas simples y accesibles para gestionar asistencia y horarios desde cualquier dispositivo, sin depender de su laptop.
Valora la movilidad y odia perder tiempo con tareas repetitivas.

![User Persona – Teacher](./assets/images/user-persona-teacher.png)
**Figura 3.** User Persona del segmento *Docente*.

---

### 2.3.2. User Task Matrix

### 2.3.3. User Journey Mapping

### 2.3.4. Empathy Mapping

Se elaboraron los Empathy Mapping para los dos User Personas: el Administrador de la academia y el Profesor. Este proceso permitió comprender mejor lo que dicen, piensan, hacen y sienten en su día a día, identificando sus principales pains y gains para diseñar una solución que realmente se adapte a sus necesidades.

---

#### Administrador de academia

![Empathy Mapping – Administrator](./assets/images/empathy-mapping-admin.png)
**Figura x.** Empathy Mapping del user persona *Administrador*.

---

#### Docente de academia

![Empathy Mapping – Teacher](./assets/images/empathy-mapping-teacher.png)
**Figura x.** Empathy Mapping del user persona *Docente*.

---
### 2.3.5. As-Is Scenario Mapping

## 2.4. Ubiquitous Language

---

**Teacher** (Docente)  
Persona encargada de impartir clases, evaluar a los estudiantes y registrar información académica como notas y asistencias.

---

**Student** (Estudiante)  
Persona inscrita en la academia para recibir formación académica y participar en actividades educativas.

---

**Administrative Coordinator** (Coordinador administrativo)  
Persona responsable de organizar y gestionar los procesos administrativos como matrículas, pagos, horarios y seguimiento académico.

---

**Enrollment** (Matrícula)  
Proceso mediante el cual un estudiante se inscribe formalmente en la academia para participar en sus clases.

---

**Attendance** (Asistencia)  
Registro que indica si el estudiante estuvo presente o ausente en cada clase.

---

**Tuition Payment** (Pago de matrícula)  
Pago realizado por el estudiante o su tutor para acceder a los servicios educativos de la academia.

---

**Outstanding Balance** (Deuda pendiente)  
Monto que un estudiante aún no ha pagado por concepto de matrícula u otros compromisos financieros.

---

**Student Record** (Ficha del estudiante)  
Conjunto de datos personales, académicos y administrativos de un estudiante, como notas, asistencia y pagos realizados.

---

**Academic Schedule** (Horario académico)  
Distribución de clases a lo largo de la semana, especificando días, horas y asignaturas correspondientes.

---

**Payment Control** (Control de pagos)  
Supervisión del cumplimiento de los pagos realizados por los estudiantes, con el fin de mantener actualizada la situación financiera.

---

**Manual Management** (Gestión manual)  
Organización de la información y ejecución de procesos administrativos utilizando medios no automatizados como hojas de Excel o listas impresas.

---

**Information Centralization** (Centralización de información)  
Proceso de integrar todos los datos administrativos y académicos en un único sistema para facilitar el acceso y la gestión.

---

**Reminder Alert** (Alerta de recordatorio)  
Notificación automática que recuerda tareas o eventos importantes, como vencimientos de pagos o cambios de horario.

# Capítulo III: Requirements Specification

## 3.1. To-Be Scenario Mapping.

Para el desarrollo del To-be Scenario Mapping, el equipo planteó cómo mejorarían las actividades de los administradores y docentes tras implementar Demy. Este flujo proyectado soluciona los problemas detectados en el As-is Scenario, con procesos más ágiles, automatizados y centrados en una mejor gestión y comunicación.

**To-Be Scenario Mapping Coordinator**
![Image](assets/images/to-be-scenario-mapping-coordinator.jpg)

**To-Be Scenario Mapping Teacher**
![Image](assets/images/to-be-scenario-mapping-teacher.jpg)

## 3.2. User Stories

Se elaboraron historias de usuario (US), técnicas (TS) y de sitio web estático (LPS) para el sistema Demy, siguiendo buenas prácticas como INVEST. Estas historias reflejan necesidades reales de los usuarios y están organizadas por épicas, cada una con sus respectivos criterios de aceptación.

| Epic / Story ID | Título                                        | Descripción                                                                                                                                                                                              | Criterios de Aceptación                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              | Relacionado con (Epic ID) |
|-----------------|-----------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------|
| EP01            | Gestión de usuarios y autenticación           | Login, gestión de sesiones y control de acceso a funcionalidades según el rol del usuario.                                                                                                               | — *(Epica, no aplica)*                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               | —                         |
| EP02            | Gestión de matrículas                         | Funcionalidades para registrar, editar y consultar matrículas de estudiantes.                                                                                                                            | — *(Epica, no aplica)*                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               | —                         |
| EP03            | Control de asistencia y rendimiento           | Registro de asistencia por parte del docente y consulta del estado por parte del administrativo.                                                                                                         | — *(Epica, no aplica)*                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               | —                         |
| EP04            | Gestión financiera y alertas de pago          | Control de pagos realizados por estudiantes, alertas de morosidad y registro básico de egresos.                                                                                                          | — *(Epica, no aplica)*                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               | —                         |
| EP05            | Gestión de horarios y asignaciones            | Asignación y reprogramación de horarios, salones y docentes según disponibilidad o cambios imprevistos.                                                                                                  | — *(Epica, no aplica)*                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               | —                         |
| EP06            | Accesos desde Landing Page por segmento       | Redirecciones desde la landing page hacia vistas específicas según el tipo de visitante.                                                                                                                 | — *(Epica, no aplica)*                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               | —                         |
| EP07            | Servicios técnicos y APIs REST                | Implementación y documentación de endpoints RESTful, configuración del backend y aspectos técnicos.                                                                                                      | — *(Epica, no aplica)*                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               | —                         |
| US01            | Iniciar sesión como usuario del sistema       | Como usuario registrado, quiero iniciar sesión en el sistema, para acceder a mis funcionalidades según mi rol.                                                                                           | Given el formulario de login está disponible<br>When el usuario ingresa credenciales válidas<br>Then se muestra la pantalla de inicio correspondiente a su rol<br>And se almacena un token de sesión válido                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          | EP01                      |
| US02            |                                               |                                                                                                                                                                                                          |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |                           |
| US03            |                                               |                                                                                                                                                                                                          |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |                           |
| US04            |                                               |                                                                                                                                                                                                          |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |                           |
| US05            |                                               |                                                                                                                                                                                                          |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |                           |
| US06            |                                               |                                                                                                                                                                                                          |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |                           |
| US07            |                                               |                                                                                                                                                                                                          |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |                           |
| US08            |                                               |                                                                                                                                                                                                          |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |                           |
| US09            |                                               |                                                                                                                                                                                                          |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |                           |
| US10            |                                               |                                                                                                                                                                                                          |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |                           |
| US11            |                                               |                                                                                                                                                                                                          |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |                           |
| US12            |                                               |                                                                                                                                                                                                          |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |                           |
| US13            | Registrar pago de un estudiante               | **Como** administrador,<br> **quiero** registrar el pago de un estudiante, <br>**para** llevar un control preciso de su estado financiero.                                                               | **Scenario 1: Registrar pago de un estudiante** <br> **Given** el administrador está en el perfil del estudiante <br> **When** selecciona la opción “Registrar pago” y elige el período de pago (1 mes, 2 meses, o ciclo completo de 6 meses) <br> **Then** el sistema muestra el monto correspondiente al periodo seleccionado <br> **And** guarda el pago por el periodo elegido, actualizando el estado de cuenta del estudiante <br><br> **Scenario 2: Registrar pago con descuento** <br> **Given** el administrador está en el perfil del estudiante <br> **When** selecciona “Registrar pago” e ingresa el monto con un descuento aplicado <br> **Then** el sistema calcula el descuento y muestra el monto final a pagar <br> **And** actualiza el estado de cuenta con el monto descontado. | EP04                      |
| US14            | Consultar estado de cuenta de un estudiante   | **Como** administrador,<br> **quiero** consultar el estado de cuenta de un estudiante, <br>**para** tener visibilidad de sus pagos realizados, deudas pendientes y fechas de vencimiento.                | **Scenario 1: Ver estado de cuenta completo** <br> **Given** el administrador accede al perfil de un estudiante <br> **When** selecciona “Estado de cuenta” <br> **Then** el sistema muestra un historial de pagos, deudas y fechas de vencimiento <br><br> **Scenario 2: Ver estado de cuenta con alerta de pago pendiente** <br> **Given** el administrador accede al perfil de un estudiante <br> **When** selecciona “Estado de cuenta” <br> **Then** el sistema resalta cualquier pago pendiente o vencido con una alerta.                                                                                                                                                                                                                                                         | EP04                      |
| US15            | Enviar alertas automáticas por pagos vencidos | **Como** administrador,<br> **quiero** que el sistema envíe alertas automáticas sobre el estado de los pagos, <br>**para** mantener informados a los apoderados y asegurar una mejor gestión financiera. | **Scenario 1: Alerta automática por pago vencido**<br>**Given** un estudiante tiene una deuda vencida <br> **When** llega la fecha límite sin pago registrado<br> **Then** el sistema envía una notificación automática al apoderado por correo o WhatsApp<br><br>**Scenario 2: Alerta de pago completado**<br>**Given** el administrador ha registrado el pago de un estudiante <br>**When** el pago es registrado<br> **Then** el sistema envía una confirmación al apoderado por correo o WhatsApp.                                                                                                                                                                                                                                                                                               | EP04                      |
| US16            | Registrar egresos                             | **Como** administrador,<br> **quiero** registrar los egresos financieros del centro educativo, <br>**para** mantener un control actualizado de los gastos y generar reportes precisos.                   | **Scenario 1: Registrar nuevo egreso con información básica**<br>**Given** el administrador está en el módulo financiero <br> **When** selecciona “Nuevo egreso” e ingresa el concepto, monto y fecha<br> **Then** el sistema guarda el egreso, actualiza el balance y lo registra como egreso general<br><br>**Scenario 2: Registrar egreso con categoría específica**<br>**Given** el administrador accede al módulo de egresos <br>**When** ingresa un nuevo egreso e indica una categoría como “Pago Docentes”, "Materiales", “Servicios” o “Infraestructura” <br> **Then** el sistema clasifica el egreso, lo agrupa bajo dicha categoría y actualiza el resumen financiero.                                                                                                                    | EP04                      |
| US17            | Generar reporte financiero mensual            | **Como** administrador,<br> **quiero** generar reportes financieros, <br>**para** visualizar el estado económico del centro educativo y tomar decisiones informadas.                                     | **Scenario 1: Generar reporte mensual estándar**<br>**Given** el administrador selecciona un mes y año<br>**When** hace clic en “Generar reporte”<br>**Then** el sistema muestra los ingresos, egresos y balance de ese mes<br><br>**Scenario 2: Generar reporte con filtros personalizados**<br>**Given** el administrador selecciona un mes y año<br>**When** hace clic en “Generar reporte” y aplica filtros personalizados (por categoría, tipo de ingreso/egreso)<br>**Then** el sistema muestra un reporte detallado según los filtros aplicados.                                                                                                                                                                                                                                              | EP04                      |
| US18            |                                               |                                                                                                                                                                                                          |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |                           |
| US19            |                                               |                                                                                                                                                                                                          |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |                           |
| US20            |                                               |                                                                                                                                                                                                          |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |                           |
| US21            |                                               |                                                                                                                                                                                                          |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |                           |
| US22            |                                               |                                                                                                                                                                                                          |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |                           |
| LPS01           |                                               |                                                                                                                                                                                                          |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |                           |
| LPS02           |                                               |                                                                                                                                                                                                          |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |                           |
| LPS03           |                                               |                                                                                                                                                                                                          |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |                           |
| LPS04           |                                               |                                                                                                                                                                                                          |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |                           |
| LPS05           |                                               |                                                                                                                                                                                                          |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |                           |
| LPS06           |                                               |                                                                                                                                                                                                          |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |                           |
| LPS07           |                                               |                                                                                                                                                                                                          |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |                           |
| LPS08           |                                               |                                                                                                                                                                                                          |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |                           |
| LPS09           |                                               |                                                                                                                                                                                                          |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |                           |
| LPS10           |                                               |                                                                                                                                                                                                          |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |                           |
| TS01            |                                               |                                                                                                                                                                                                          |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |                           |
| TS02            |                                               |                                                                                                                                                                                                          |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |                           |
| TS03            |                                               |                                                                                                                                                                                                          |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |                           |
| TS04            |                                               |                                                                                                                                                                                                          |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |                           |
| TS05            |                                               |                                                                                                                                                                                                          |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |                           |

## 3.3. Impact Mapping

## 3.4. Product Backlog

# Capítulo IV: Product Design

## 4.1. Style Guidelines

### 4.1.1. General Style Guidelines
La identidad visual de **Demy** ha sido diseñada para transmitir cercanía, confianza y profesionalismo, cualidades esenciales en una herramienta dirigida a academias educativas que buscan modernizar su gestión financiera y de pagos. El estilo visual se basa en principios de simplicidad, accesibilidad y consistencia, permitiendo que los usuarios, incluso aquellos con poca experiencia digital, puedan interactuar con facilidad tanto en la versión web como en móvil.

---

#### Branding Overview

**Demy** es una aplicación desarrollada por la startup SmartEdu, cuyo objetivo es brindar soluciones digitales inclusivas y eficientes para academias educativas presenciales. Demy responde a la necesidad de mejorar la eficiencia operativa de las academias presenciales mediante soluciones digitales centradas en el usuario, con enfoque inclusivo y adaptable a instituciones de todos los tamaños.

---

#### Misión

Revolucionar la gestión administrativa de las academias educativas en el Perú, ofreciendo una plataforma que optimice procesos clave de matrícula, asistencia, asignación de horarios, control de inventarios y pagos.

---

#### Visión

Convertirnos en líderes en la transformación digital de la gestión administrativa de academias educativas presenciales en el Perú, asegurando la eficiencia, transparencia y accesibilidad de sus procesos internos mediante soluciones tecnológicas innovadoras.

---

#### Producto

**Demy** es una plataforma web que automatiza la gestión diaria de academias educativas. Permite controlar matrículas, horarios, asistencia, pagos e inventarios desde una interfaz accesible y fácil de usar. Está pensada para ser adoptada por usuarios con poca experiencia digital y reemplaza herramientas fragmentadas como hojas de cálculo o registros físicos.

---

#### Nombre del producto

**Demy** fue elegido como nombre por su cercanía fonética con “Academy” y su simplicidad. Refleja el enfoque educativo de la herramienta y su propósito principal: **unificar y facilitar la gestión académica y administrativa**. Su pronunciación amigable y breve lo convierte en un nombre fácil de recordar para usuarios de todas las edades y niveles digitales.

#### Logo

![Logo Demy](assets/images/demy-logo.png)

El logo de **Demy** utiliza una tipografía sans-serif moderna y limpia en color azul oscuro, lo que transmite profesionalismo, confianza y estabilidad. A la izquierda del nombre se encuentra un símbolo gráfico distintivo que representa de forma abstracta las letras “D” y “m”, iniciales del producto. Este símbolo ha sido diseñado con líneas suaves y formas geométricas, evocando dinamismo, estructura y tecnología.

El conjunto tipográfico y gráfico busca reflejar la identidad de Demy como una plataforma confiable, accesible y moderna para la gestión educativa. Además, el diseño ha sido pensado para adaptarse con facilidad a distintos formatos, desde pantallas digitales hasta materiales impresos, asegurando siempre su legibilidad y reconocimiento.

#### Color

![Color-theme](assets/images/figma-colors.png)

Los colores juegan un papel clave en la primera impresión que los usuarios tienen de Demy, por lo que se seleccionaron con base en la psicología del color para transmitir confianza, profesionalismo y accesibilidad. El azul oscuro, como color principal, simboliza estabilidad y seguridad (#093D77), mientras que el azul claro agrega frescura y hace la interfaz más amigable y fácil de navegar (#3A7CA5).

Los colores secundarios, como el azul verdoso (#80C5C6) y el beige claro (#F2E0CF), añaden versatilidad y suavizan la paleta, mejorando la legibilidad y creando un ambiente acogedor. Estos tonos también guían la atención del usuario hacia áreas clave sin interrumpir su experiencia.

En cuanto a los wireframes, se utilizó una escala de grises para proporcionar una base neutra y funcional. Los colores para alertas y notificaciones están claramente diferenciados: el azul para enlaces (#0397D3), el verde para éxitos (#38C976), el amarillo para advertencias (#FFB84D) y el rojo para errores (#FE5050), permitiendo que cada alerta sea fácilmente identificable.

En resumen, los colores de Demy están diseñados para proporcionar una experiencia visual profesional, accesible y eficiente, asegurando una navegación intuitiva y clara para los usuarios.

#### Tipografía

![Tipografía-demy](assets/images/figma-typography.png)

La tipografía seleccionada para **Demy** es **Inter**, una fuente sans-serif moderna, limpia y legible. Su diseño balancea perfectamente la formalidad con la accesibilidad, lo que la hace ideal para una plataforma educativa dirigida a distintos perfiles de usuarios. Inter destaca por su neutralidad y adaptabilidad, permitiendo mantener una identidad visual clara y coherente en todos los entornos.

#### Tono de comunicación

Para mantener un tono **profesional y claro**, se emplean estilos en **negrita y tamaños grandes** en los encabezados, ayudando a resaltar información clave y generar jerarquías visuales claras. En contraste, los textos secundarios o explicativos se presentan en tamaños regulares, lo que genera una experiencia de lectura accesible y ordenada.

Además, **Inter** permite ajustarse a otros tonos según el contexto, como uno más **casual**, al variar pesos y tamaños. Esta flexibilidad permite adaptar el mensaje sin perder la coherencia visual ni el profesionalismo que se busca transmitir con Demy. Esto es clave para una plataforma de gestión educativa que debe ser clara, funcional y cercana a su público.

### 4.1.2. Web Style Guidelines

## 4.2. Information Architecture

### 4.2.1. Organization Systems

### 4.2.2. Labeling Systems

### 4.2.3. SEO Tags and Meta Tags

### 4.2.4. Searching Systems
A medida que se incrementa la cantidad de información almacenada en nuestra plataforma, resulta esencial brindar herramientas que ayuden a los usuarios a encontrar lo que necesitan de forma ágil y precisa. Para evitar que se sientan abrumados, hemos integrado diferentes mecanismos de búsqueda y filtrado que se adaptan a distintos contextos dentro del sistema.

#### Búsqueda por palabra clave
En secciones como la de estudiantes o aulas, el usuario podrá ingresar términos específicos, como el **DNI del estudiante** o el **código del aula**, dentro de un buscador con el clásico ícono de lupa. El sistema mostrará coincidencias inmediatas, facilitando la navegación sin necesidad de recorrer listas extensas.

#### Filtros desplegables por categoría y fecha
Para consultar información detallada o generar reportes, los usuarios contarán con filtros como **tipo de ciclo**, **categoría**, **año** y **mes**. Estos se presentan en menús desplegables con una flecha hacia abajo, permitiendo seleccionar la opción deseada de forma rápida y sin errores.

#### Selector de tipo de reporte
En el módulo financiero, los usuarios tendrán la posibilidad de elegir entre **generar un reporte mensual** o **visualizar el historial completo** de movimientos. Esta acción se realiza mediante botones de selección simple, que adaptan dinámicamente el contenido mostrado en pantalla según la opción elegida.

### 4.2.5. Navigation Systems

## 4.3. Landing Page UI Design

### 4.3.1. Landing Page Wireframe

### 4.3.2. Landing Page Mock-up

## 4.4. Web Applications UX/UI Design

### 4.4.1. Web Applications Wireframes
#### Web Application Wireframes para Desktop Web Browser
**Selección tipo de usuario**
Pantalla inicial de la aplicación web donde se solicita al visitante seleccionar su rol como "Administrador" o "Profesor", decisión fundamental que determinará el flujo de navegación y las funcionalidades disponibles según el tipo de usuario elegido.
![Wireframe-1](assets/images/wireframes-appweb/desktop/Selección-tipo-usuario.png)

**Crear cuenta**  
Pantalla donde el usuario, tras haber seleccionado el rol de "Administrador", accede a un formulario de registro en el que debe ingresar información obligatoria como nombres y apellidos, número de RUC, nombre de la academia, correo electrónico y contraseña, datos esenciales para crear una cuenta institucional y acceder a la plataforma como administrador.  
![Wireframe-2](assets/images/wireframes-appweb/desktop/Crear-cuenta.png)


**Iniciar sesión**  
Pantalla donde tanto administradores como profesores pueden ingresar, para acceder a la plataforma, permitiendo el ingreso seguro a sus respectivos espacios según el rol previamente registrado.  
![Wireframe-3](assets/images/wireframes-appweb/desktop/Iniciar-sesión.png)

**Recuperar contraseña**  
Pantallas donde administradores pueden solicitar la recuperación de su contraseña ingresando su correo electrónico registrado; tras ello, el sistema enviará un código de verificación para restablecerla y así recuperar el acceso a la plataforma.  
![Wireframe-5](assets/images/wireframes-appweb/desktop/Recuperar-contraseña.png)
![Wireframe-5](assets/images/wireframes-appweb/desktop/Reestablecer-contraseña.png)
![Wireframe-5](assets/images/wireframes-appweb/desktop/Confirmacion-reestablecer-contraseña.png)

**Seleccionar plan**  
Pantalla presentada luego del registro del administrador, donde se le solicita elegir entre diferentes planes disponibles para su academia, cada uno con características y beneficios específicos que determinarán el alcance y funcionalidades habilitadas dentro de la plataforma.  
![Wireframe-4](assets/images/wireframes-appweb/desktop/Seleccionar-plan.png)

**Mi organización (Administrador)**  
Pantalla principal que ve el administrador tras iniciar sesión, donde accede a la gestión interna de su academia con módulos clave como Periodos, Cursos, Aulas y Profesores, permitiéndole registrar, editar y visualizar la información esencial para el funcionamiento académico.  
![Wireframe-6](assets/images/wireframes-appweb/desktop/Mi-organizacion-admin.png)

**Mi organización - Cursos y Añadir cursos (Administrador)**  
Pantallas dentro del módulo "Mis cursos" donde el administrador puede visualizar la lista de cursos registrados, y acceder al botón "Añadir curso", el cual despliega un formulario emergente que solicita el nombre del curso, área temática, duración y código del curso, permitiéndole registrar nuevos cursos que podrán ser asignados posteriormente a profesores y aulas.  
![Wireframe-7](assets/images/wireframes-appweb/desktop/Organización-cursos.png)
![Wireframe-7](assets/images/wireframes-appweb/desktop/Organización-añadir-cursos.png)

**Mi organización - Añadir periodos, asignar cursos a periodos (Administrador)**  
Pantallas dentro del módulo "Mis periodos" donde el administrador puede crear un nuevo periodo académico, eligiendo un bloque horario en una tabla de horarios semanales. Después de seleccionar el bloque, puede asignar un curso a dicho bloque mediante el botón "Seleccionar curso", eligiendo entre los cursos previamente registrados. Una vez completada la asignación de todos los cursos a los bloques correspondientes, el administrador puede guardar el periodo, el cual quedará disponible en la lista de periodos.  
![Wireframe-8](assets/images/wireframes-appweb/desktop/Organización-Periodos.png)
![Wireframe-8](assets/images/wireframes-appweb/desktop/Organización-crear-periodo.png)
![Wireframe-8](assets/images/wireframes-appweb/desktop/Organización-seleccionar-cursos%20-periodos.png)
![Wireframe-8](assets/images/wireframes-appweb/desktop/Organización-guardar%20periodo.png)

**Mi organización - Añadir Aulas (Administrador)**  
Pantalla dentro del módulo "Mi organización" donde el administrador puede crear nuevas aulas para la academia. En esta pantalla, se solicita ingresar un código único para el aula y seleccionar el periodo académico al que pertenece. Después de completar los campos, el administrador puede presionar el botón "Crear aula" para guardar la nueva aula, que se añadirá automáticamente a la lista de aulas.  
![Wireframe-9](assets/images/wireframes-appweb/desktop/Organización-Aulas.png)
![Wireframe-9](assets/images/wireframes-appweb/desktop/Organización-añadir-aulas.png)

**Mi organización - Añadir Profesor (Administrador)**  
Pantalla donde el administrador puede registrar un nuevo profesor ingresando datos como nombres, correo y asignarle aulas o cursos.  
![Wireframe-20](assets/images/wireframes-appweb/desktop/Organización-profesores.png)
![Wireframe-20](assets/images/wireframes-appweb/desktop/Organizacion-Agregar-profesor.png)
![Wireframe-20](assets/images/wireframes-appweb/desktop/Organizacion-Agregar-profesor-confirmacion.png)
![Wireframe-20](assets/images/wireframes-appweb/desktop/Organizacion-credenciales-profesor.png)


**Panel de Control: Matrícula (Administrador)**  
Pantalla dentro del panel de control donde el administrador puede gestionar la matrícula de los alumnos. En esta sección, se presenta un formulario donde el administrador debe ingresar los datos del alumno y asignarles un aula correspondiente. Al completar el formulario, puede presionar el botón "Guardar matrícula", lo que mostrará un cuadro de confirmación para asegurar que la matrícula se ha realizado correctamente. Luego, el alumno se agregará al historial de matrículas de la academia.  
![Wireframe-10](assets/images/wireframes-appweb/desktop/Panel-control-Matrícula.png)
![Wireframe-10](assets/images/wireframes-appweb/desktop/Panel-control-Matricula-Confirmacion.png)

**Panel de Control: Historial de Matrícula (Administrador)**  
Pantalla dentro del panel de control donde el administrador puede visualizar todas las matrículas realizadas. Se presenta una tabla con la lista de estudiantes matriculados, incluyendo información como el nombre del alumno, aula asignada y estado de la matrícula. Desde aquí, el administrador puede buscar, filtrar y revisar las matrículas anteriores, asegurando un seguimiento adecuado de los registros de los estudiantes.  
![Wireframe-11](assets/images/wireframes-appweb/desktop/Panel-control-Historial-Matrícula.png)
![Wireframe-11](assets/images/wireframes-appweb/desktop/Panel-control-Editar-Matrícula.png)

**Panel de Control: Alumnos (Administrador)**  
Pantalla donde el administrador puede buscar y visualizar los datos de los alumnos, como nombre, matrícula, y estado de pago.  
![Wireframe-13](assets/images/wireframes-appweb/desktop/Panel-control-Alumnos.png)

**Panel de Control: Asistencia (Administrador)**  
Pantalla donde el administrador puede seleccionar el aula y alumno para visualizar los dias asistidos.  
![Wireframe-14](assets/images/wireframes-appweb/desktop/Panel-control-Asistencia.png)

**Panel de Control: Pagos (Administrador)**  
Pantallas donde el administrador puede buscar un alumno para ver su estado de pago, registrar un nuevo pago o acceder al historial de pagos, completando los datos necesarios y confirmando la acción.  
![Wireframe-15](assets/images/wireframes-appweb/desktop/Panel-control-Pagos.png)
![Wireframe-15](assets/images/wireframes-appweb/desktop/Panel-control-Registrar-Pagos-confirmacion.png)
![Wireframe-15](assets/images/wireframes-appweb/desktop/Panel-control-Historial-Pagos.png)
![Wireframe-15](assets/images/wireframes-appweb/desktop/Panel-control-Historial-Pagos-registrar-pago-confirmacion.png)

**Panel de Control: Horarios (Administrador)**  
Pantalla donde el administrador puede buscar un aula específica y visualizar su horario correspondiente, permitiéndole revisar la programación de clases y bloques horarios asignados.  
![Wireframe-16](assets/images/wireframes-appweb/desktop/Panel-control-Horarios.png)

**Panel de Control: Finanzas y Reporte Financiero (Administrador)**  
Pantalla donde el administrador puede registrar nuevos egresos, completando detalles como concepto, monto, fecha y categoría, así como generar reportes financieros de la academia, seleccionando entre opciones generales o mensuales, y visualizando un resumen de ingresos, egresos y balance final.  
![Wireframe-17](assets/images/wireframes-appweb/desktop/Panel-control-Finanzas.png)
![Wireframe-17](assets/images/wireframes-appweb/desktop/Panel-control-Finanzas-registrar%20egreso-confirmacion.png)
![Wireframe-17](assets/images/wireframes-appweb/desktop/Panel-control-Finanzas-reporte-general.png)
![Wireframe-17](assets/images/wireframes-appweb/desktop/Panel-control-Finanzas-reporte-filtros.png)

**Mi Organización (Profesor)**  
Pantalla donde el profesor accede a la sección "Mi Organización", pudiendo visualizar la información relacionada con las aulas en las que está asignado y los horarios en que enseña, todo ello gestionado por el administrador de la academia.  
![Wireframe-18](assets/images/wireframes-appweb/desktop/Mi-organizacion-vistaprofesor.png)
![Wireframe-18](assets/images/wireframes-appweb/desktop/Organización-vistaprofesor-Aulas.png)

**Panel de Control: Horario por Aula (Profesor)**  
Pantalla donde el profesor puede visualizar el horario detallado de las aulas en las que está asignado, permitiéndole conocer los bloques de tiempo y las clases correspondientes a cada aula que le fue asignada.  
![Wireframe-19](assets/images/wireframes-appweb/desktop/Panel-control-vistaprofesor-Horario-por-aula.png)

**Panel de Control: Asistencia e Historial de Alumnos (Profesor)**  
Pantalla donde el profesor puede registrar la asistencia de los estudiantes en su aula, seleccionando los estudiantes presentes mediante una casilla de verificación. También tiene la opción de consultar la lista completa de estudiantes.  
![Wireframe-20](assets/images/wireframes-appweb/desktop/Panel-control-vistaprofesor-Asistencia.png)
![Wireframe-20](assets/images/wireframes-appweb/desktop/Panel-control-vistaprofesor-Asistencia-confirmacion.png)
![Wireframe-20](assets/images/wireframes-appweb/desktop/Panel-control-vistaprofesor-lista-alumnos.png)

#### Web Application Wireframes para Mobile Web Browser
**Selección tipo de usuario**  
Pantalla inicial donde se elige si se ingresará como "Administrador" o "Profesor", lo que define el acceso a funciones específicas.  
![Wireframe-1](assets/images/wireframes-appweb/mobile/seleccion-usuario.png)

**Crear cuenta**  
Pantalla de registro exclusivo para administradores, con campos como nombre, RUC, correo y contraseña.  
![Wireframe-2](assets/images/wireframes-appweb/mobile/crear-cuenta.png)

**Iniciar sesión**  
Pantalla para que administradores o profesores ingresen a la plataforma con sus credenciales.  
![Wireframe-3](assets/images/wireframes-appweb/mobile/iniciar-sesion.png)

**Recuperar contraseña**  
Pantallas para ingresar el correo registrado y recibir un código para recuperar la contraseña.  
![Wireframe-4](assets/images/wireframes-appweb/mobile/recuperar-contrasena.png)

**Seleccionar plan**  
Pantalla donde el administrador elige el plan de la academia tras registrarse.  
![Wireframe-5](assets/images/wireframes-appweb/mobile/seleccionar-plan.png)

**Mi organización (Administrador)**  
Pantalla principal del administrador con acceso a módulos como cursos, periodos, aulas y profesores.  
![Wireframe-6](assets/images/wireframes-appweb/mobile/mi-organizacion-admin.png)

**Mi organización - Cursos y Añadir cursos (Administrador)**  
Pantallas para ver, editar o registrar cursos con sus respectivos detalles.  
![Wireframe-7](assets/images/wireframes-appweb/mobile/cursos-admin.png)

**Mi organización - Añadir periodos, asignar cursos a periodos (Administrador)**  
Pantallas para registrar un nuevo periodo y asignarle cursos según horarios disponibles.  
![Wireframe-8](assets/images/wireframes-appweb/mobile/periodos-admin.png)

**Mi organización - Añadir Aulas (Administrador)**  
Pantallas para crear nuevas aulas asignándolas a un periodo y código único.  
![Wireframe-9](assets/images/wireframes-appweb/mobile/aulas-admin.png)

**Mi organización - Añadir Profesor (Administrador)**  
Pantallas donde el administrador puede agregar nuevos profesores a la academia completando un formulario con nombre, correo electrónico y cursos o aulas asignadas.  
![Wireframe-20](assets/images/wireframes-appweb/mobile/añadir-profesor.png)


**Panel de Control: Matrícula (Administrador)**  
Pantalla para registrar alumnos a un aula con formulario de datos y confirmación.  
![Wireframe-10](assets/images/wireframes-appweb/mobile/matricula.png)

**Panel de Control: Historial de Matrícula (Administrador)**  
Pantalla para ver la lista de matrículas realizadas, con filtros y búsqueda.  
![Wireframe-11](assets/images/wireframes-appweb/mobile/historial-matricula.png)

**Panel de Control: Alumnos (Administrador)**  
Pantalla para buscar y revisar información básica de los alumnos registrados.  
![Wireframe-12](assets/images/wireframes-appweb/mobile/alumnos-admin.png)

**Panel de Control: Asistencia (Administrador)**  
Pantalla para revisar asistencia de alumnos por aula y fecha.  
![Wireframe-13](assets/images/wireframes-appweb/mobile/asistencia-admin.png)

**Panel de Control: Pagos (Administrador)**  
Pantalla para consultar, registrar o editar pagos realizados por los alumnos.  
![Wireframe-14](assets/images/wireframes-appweb/mobile/pagos.png)

**Panel de Control: Horarios (Administrador)**  
Pantalla para seleccionar un aula y ver su horario de clases completo.  
![Wireframe-15](assets/images/wireframes-appweb/mobile/horarios-admin.png)

**Panel de Control: Finanzas y Reporte Financiero (Administrador)**  
Pantalla para registrar egresos y generar reportes financieros generales o mensuales.  
![Wireframe-16](assets/images/wireframes-appweb/mobile/finanzas.png)

**Mi Organización (Profesor)**  
Pantalla donde el profesor visualiza sus aulas y horarios asignados.  
![Wireframe-17](assets/images/wireframes-appweb/mobile/mi-organizacion-profesor.png)

**Panel de Control: Horario por Aula (Profesor)**  
Pantalla donde el profesor ve el horario específico de cada aula en la que enseña.  
![Wireframe-18](assets/images/wireframes-appweb/mobile/horarios-profesor.png)

**Panel de Control: Asistencia e Historial de Alumnos (Profesor)**  
Pantalla para marcar asistencia de estudiantes y consultar sus registros anteriores.  
![Wireframe-19](assets/images/wireframes-appweb/mobile/asistencia-profesor.png)


### 4.4.2. Web Applications Wireflow Diagrams
**User goal:** Registro de cuenta  
**User persona:** Administrador de academia  
![Wireflow-1](assets/images/wireflow-register-account-admin.png)  
**Explicación del flujo:**  
El flujo comienza donde el usuario debe elegir si es administrador o profesor. Al seleccionar "Soy administrador", se muestra un mensaje indicando que podrá crear su academia desde cero. Luego, se presenta un formulario de registro en el que el administrador debe completar campos obligatorios como nombres y apellidos, RUC, nombre de la academia, correo electrónico y contraseña. Una vez completado el formulario y presionado el botón "Crear cuenta", el sistema valida los datos y, si todo es correcto, redirige al usuario a la sección "Mi organización", donde podrá comenzar a registrar profesores, cursos, aulas y periodos académicos.

**User goal:** Registrar un curso  
**User persona:** Administrador de academia  
![Wireflow-2](assets/images/wireflow-register-course-admin.png)  
**Explicación del flujo:**  
En flujo comienza desde la sección "Mi organización", el administrador selecciona el módulo "Cursos" para gestionar las asignaturas disponibles en su academia. Al hacer click en el botón "Agregar curso", se despliega un formulario donde debe ingresar el nombre del curso, un código identificador. Tras completar los campos requeridos y confirmar la acción con el botón "Crear Curso", el sistema agrega el curso a la lista y lo deja disponible para ser asignado posteriormente a periodos académicos.

**User goal:** Crear un periodo académico  
**User persona:** Administrador de academia  
![Wireflow-3](assets/images/wireflow-register-period-admin.png)  
**Explicación del flujo:**  
Desde la sección "Mi organización", el administrador accede al módulo "Periodos" donde visualiza la lista de periodos ya creados. Al presionar el botón "Agregar periodo", es dirigido a la sección "Crear periodo", que incluye una tabla tipo horario semanal. En esta interfaz, el administrador puede seleccionar los bloques de horas haciendo clic sobre las celdas correspondientes y luego presionar el botón "Seleccionar curso" para asignar uno de los cursos disponibles previamente creados. Una vez completada la asignación del horario, presiona "Guardar periodo", lo que activa un cuadro de confirmación que pregunta si está seguro de registrar el periodo. Al confirmar la acción, el sistema guarda la configuración y redirige al administrador a la lista de periodos, donde ya se visualiza el nuevo periodo registrado.

**User goal:** Crear un aula  
**User persona:** Administrador de academia  
![Wireflow-4](assets/images/wireflow-register-classroom-admin.png)  
**Explicación del flujo:**  
Desde la sección "Mi organización", el administrador accede al módulo "Aulas", donde se encuentra con la lista de aulas ya creadas. Al presionar el botón "Agregar aula", se le presenta un cuadro emergente para crear una nueva aula. En este cuadro, el administrador debe asignar un código único para el aula y seleccionar uno de los periodos académicos previamente creados. Una vez completados estos campos, el administrador presiona el botón "Crear aula". El sistema valida la información y, al confirmarse, el aula se agrega a la lista de aulas disponibles, permitiendo al administrador gestionar y asignar profesores a las aulas.

**User goal:** Crear un profesor  
**User persona:** Administrador de academia  
![Wireflow-5](assets/images/wireflow-register-teacher-admin.png)  
**Explicación del flujo:**  
Desde la sección "Mi organización", el administrador accede al módulo "Profesores" y presiona el botón "Agregar profesor". Se le presenta un cuadro emergente en el que debe ingresar los datos del profesor, como su nombre completo, DNI y las aulas a las que será asignado. Para asignar un aula, el administrador debe presionar el botón "Insertar aula-curso", lo que abre una pequeña tabla con las aulas y los cursos disponibles. El administrador puede agregar múltiples aulas y cursos al profesor. Una vez completada la asignación, el administrador presiona el botón "Agregar profesor". Se muestra un cuadro de confirmación para verificar que la información es correcta. Tras confirmar, el sistema genera un cuadro con las credenciales del profesor (correo y contraseña) para acceder a la plataforma Demy. Finalmente, el profesor se agrega a la lista de profesores disponibles.

**User goal:** Matricular a un alumno  
**User persona:** Administrador de academia  
![Wireflow-6](assets/images/wireflow-enrollment-admin.png)  
**Explicación del flujo:**  
El administrador ingresa a la sección "Panel de control" y selecciona el módulo "Matrícula". Dentro de este, se presenta un formulario donde debe llenar los datos del alumno, como su nombre, DNI y aula asignada. Al completar el formulario, el administrador presiona el botón "Guardar matrícula". Luego, aparece un cuadro de confirmación para asegurar que la información ingresada es correcta. Tras confirmar, el sistema registra la matrícula y redirige al administrador a la sección "Historial de matrícula", donde podrá ver la lista de matrículas realizadas, incluyendo la del alumno recién matriculado.

**User goal:** Visualizar asistencia de un alumno o por aula  
**User persona:** Administrador de academia  
![Wireflow-7](assets/images/wireflow-attendance-management-admin.png)  
**Explicación del flujo:**  
El administrador accede a la sección "Panel de control" y selecciona el módulo "Asistencia". Dentro de este módulo, tiene dos opciones: buscar por alumno o por aula. Si decide buscar por alumno, deberá ingresar el nombre o DNI del alumno. Si decide buscar por aula, tendrá que elegir el aula de la que desea ver la asistencia. Después de realizar la búsqueda, el sistema muestra una tabla con los registros de asistencia correspondientes, ya sea por alumno o por aula, y estos registros incluyen las fechas y el estado de la asistencia, basados en los registros realizadas por el profesor.

**User goal:** Registrar pagos de alumnos  
**User persona:** Administrador de academia  
![Wireflow-8](assets/images/wireflow-payments-admin.png)  
**Explicación del flujo:**  
El administrador accede a la sección "Panel de control" y luego al módulo "Pagos". Desde allí, puede buscar directamente a un alumno para visualizar su estado de pagos pendientes y registrar un nuevo pago. Una vez identificado el alumno, se completan los datos correspondientes del pago, y se presiona el botón "Guardar pago". A continuación, aparece un cuadro de confirmación para verificar si desea continuar, y tras confirmar, el pago se registra en el sistema. Alternativamente, el administrador puede acceder al "Historial de pagos", donde se muestra una tabla con los pagos pendientes. Desde ahí, también puede presionar el botón "Registrar pago" para completar los datos y realizar el registro. Cualquiera de estos caminos permite llevar un control eficiente de los pagos de los alumnos.

**User goal:** Visualizar horarios de aulas  
**User persona:** Administrador de academia  
![Wireflow-9](assets/images/wireflow-schedules-admin.png)  
**Explicación del flujo:**  
El administrador accede a la sección "Panel de control" y selecciona el módulo "Horarios". Una vez dentro, se le presenta una opción para buscar un aula específica. Tras ingresar el nombre o código del aula, el sistema muestra el horario semanal correspondiente a esa aula, heredado previamente del periodo asignado. Esta visualización permite al administrador tener un control claro sobre la distribución de cursos y bloques horarios asignados a cada aula.

**User goal:** Registrar egresos y generar reportes financieros  
**User persona:** Administrador de academia  
![Wireflow-10](assets/images/wireflow-expense-report-admin.png)  
**Explicación del flujo:**  
El administrador accede a la sección "Panel de control" y selecciona el módulo "Finanzas". Para registrar un egreso, debe completar un formulario con los campos: concepto, monto, fecha y categoría, y luego presionar el botón "Registrar egreso". Además, tiene la opción de generar reportes financieros de la academia, eligiendo entre un reporte general o mensual. Una vez seleccionada la opción deseada, el sistema genera una tabla con la información correspondiente y muestra al final un resumen con el total de ingresos, egresos y el balance financiero.

**User goal:** Iniciar sesión como profesor  
**User persona:** Profesor de academia  
![Wireflow-11](assets/images/wireflow-login-teacher.png)  
**Explicación del flujo:**  
El flujo comienza en la pantalla donde el usuario debe elegir si es administrador o profesor. Al seleccionar la opción "Soy profesor", es dirigido a la pantalla de inicio de sesión. Aquí, debe ingresar las credenciales (correo y contraseña) previamente proporcionadas por el administrador al momento de registrarlo. Una vez validados los datos, el sistema permite el acceso a la plataforma y lo redirige a la sección "Mi organización", donde podrá consultar sus aulas asignadas, ver horarios y registrar asistencia.

**User goal:** Visualizar horarios de aulas asignadas  
**User persona:** Profesor de academia  
![Wireflow-12](assets/images/wireflow-schedules-teacher.png)  
**Explicación del flujo:**  
Después de iniciar sesión en la plataforma y acceder a la sección "Mi organización", el profesor procede a ingresar al "Panel de control". Dentro de esta área, selecciona la opción "Horarios", donde se le presenta un campo para escoger una de las aulas a las que ha sido asignado previamente por el administrador. Al seleccionar el aula, se muestra automáticamente el horario correspondiente, permitiéndole al docente conocer los días y horas en las que tiene clase.

**User goal:** Registrar asistencia de alumnos  
**User persona:** Profesor de academia  
![Wireflow-13](assets/images/wireflow-register-attendance-teacher.png)  
**Explicación del flujo:**  
Luego de iniciar sesión y acceder a "Mi organización", el profesor se dirige al "Panel de control" y entra en la categoría "Asistencia". Allí debe escoger una de las aulas en las que se encuentra asignado. Una vez seleccionada, se despliega una tabla con la lista de estudiantes del aula correspondiente. El docente procede a registrar la asistencia de cada alumno marcando un checkbox según corresponda. Al finalizar, hace clic en el botón "Guardar asistencia", lo que genera un cuadro de confirmación para validar si está seguro de guardar el registro. Una vez confirmado, la asistencia queda registrada correctamente.

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
