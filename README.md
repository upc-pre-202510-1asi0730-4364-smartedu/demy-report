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

### 1.1.2. Perfiles de los integrantes del equipo

## 1.2. Solution Profile

### 1.2.1. Antecedentes y problemática

### 1.2.2. Lean UX Process

#### 1.2.2.1 Lean UX Problem Statements

#### 1.2.2.2. Lean UX Assumptions

#### 1.2.2.3. Lean UX Hypothesis

#### 1.2.2.4. Lean UX Canvas

## 1.3. Segmentos objetivo

# Capítulo II: Requirements Elicitation & Analysis

## 2.1. Competidores

### 2.1.1. Análisis competitivo
Egitsta sección tiene objetivo conocer mejor los competidores a los que se enfrentará SmartEDU y poder así comparar nuestros beneficios.

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

## 2.2. Entrevistas

### 2.2.1. Diseño de entrevistas

### 2.2.2. Registro de entrevistas

### 2.2.3. Análisis de entrevistas

## 2.3. Needfinding

### 2.3.1. User Personas

### 2.3.2. User Task Matrix

### 2.3.3. User Journey Mapping

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
