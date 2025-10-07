<img src="https://upload.wikimedia.org/wikipedia/commons/f/fc/UPC_logo_transparente.png" width="150" alt="UPC Logo">

# Universidad Peruana de Ciencias Aplicadas

### **CURSO:** Diseño de Experimentos de Ingeniería de Software

### **NRC**: 7505

### **Profesor:** Julio Manuel Noriega Melendez

### **Ingeniería de software**

## Informe de Trabajo Final

### **Nombre del startup:** APX-3

### **Nombre del producto:** Xtudy

## **Integrantes**


| **Nombre**                                | **Código** |
|-------------------------------------------|------------|
| **Alejo Cardenas, Jose Antonio**             | U202122484 |
| **Real Calderon, Sebastian Omar**       | U20221D964 |
| **Luquillas Asto, Omar** | U20211G641 |
| **Olivera Barzola, Eric Marlon**          | U202315032  |


**Septiembre 2025**

## Registro de Versiones del Informe

<table>
  <thead>
    <tr>
      <th>Versión</th>
      <th>Fecha</th>
      <th>Autor</th>
      <th>Descripción de modificación</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>0.1</td>
      <td>03/09/25</td>
      <td>Jose Alejo</td>
      <td>Elaboración de plantilla del reporte</td>
    </tr>
  </tbody>
</table>

# Project Report Collaboration Insights 

# Contenido  

- [Student Outcome](#student-outcome) → Ver anexo A al final de este documento  

- [Part I: As-Is Software Project](#part-i-as-is-software-project)  
- [Capítulo I: Introducción](#capítulo-i-introducción)  
    - [1.1 Startup Profile](#11-startup-profile)  
      - [1.1.1 Descripción de la Startup](#111-descripción-de-la-startup)  
      - [1.1.2 Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)  
    - [1.2 Solution Profile](#12-solution-profile)  
      - [1.2.1 Antecedentes y problemática](#121-antecedentes-y-problemática)  
      - [1.2.2 Lean UX Process](#122-lean-ux-process)  
        - [1.2.2.1 Lean UX Problem Statements](#1221-lean-ux-problem-statements)  
        - [1.2.2.2 Lean UX Assumptions](#1222-lean-ux-assumptions)  
        - [1.2.2.3 Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)  
        - [1.2.2.4 Lean UX Canvas](#1224-lean-ux-canvas)  
    - [1.3 Segmentos objetivo](#13-segmentos-objetivo)  

- [Capítulo II: Requirements Elicitation & Analysis](#capítulo-ii-requirements-elicitation--analysis)  
    - [2.1 Competidores](#21-competidores)  
      - [2.1.1 Análisis competitivo](#211-análisis-competitivo)  
      - [2.1.2 Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)  
    - [2.2 Entrevistas](#22-entrevistas)  
      - [2.2.1 Diseño de entrevistas](#221-diseño-de-entrevistas)  
      - [2.2.2 Registro de entrevistas](#222-registro-de-entrevistas)  
      - [2.2.3 Análisis de entrevistas](#223-análisis-de-entrevistas)  
    - [2.3 Needfinding](#23-needfinding)  
      - [2.3.1 User Personas](#231-user-personas)  
      - [2.3.2 User Task Matrix](#232-user-task-matrix)  
      - [2.3.3 User Journey Mapping](#233-user-journey-mapping)  
      - [2.3.4 Empathy Mapping](#234-empathy-mapping)  
      - [2.3.5 As-is Scenario Mapping](#235-as-is-scenario-mapping)  
    - [2.4 Ubiquitous Language](#24-ubiquitous-language)  

- [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)  
    - [3.1 To-Be Scenario Mapping](#31-to-be-scenario-mapping)  
    - [3.2 User Stories](#32-user-stories)  
    - [3.3 Product Backlog](#33-product-backlog)  
    - [3.4 Impact Mapping](#34-impact-mapping)  

- [Capítulo IV: Product Design](#capítulo-iv-product-design)  
  - [4.1 Style Guidelines](#41-style-guidelines)  
    - [4.1.1 General Style Guidelines](#411-general-style-guidelines)  
    - [4.1.2 Web Style Guidelines](#412-web-style-guidelines)  
    - [4.1.3 Mobile Style Guidelines](#413-mobile-style-guidelines)  
      - [4.1.3.1 iOS Mobile Style Guidelines](#4131-ios-mobile-style-guidelines)  
      - [4.1.3.2 Android Mobile Style Guidelines](#4132-android-mobile-style-guidelines)  
  - [4.2 Information Architecture](#42-information-architecture)  
    - [4.2.1 Organization Systems](#421-organization-systems)  
    - [4.2.2 Labeling Systems](#422-labeling-systems)  
    - [4.2.3 SEO Tags and Meta Tags](#423-seo-tags-and-meta-tags)  
    - [4.2.4 Searching Systems](#424-searching-systems)  
    - [4.2.5 Navigation Systems](#425-navigation-systems)  
  - [4.3 Landing Page UI Design](#43-landing-page-ui-design)  
    - [4.3.1 Landing Page Wireframe](#431-landing-page-wireframe)  
    - [4.3.2 Landing Page Mock-up](#432-landing-page-mock-up)  
  - [4.4 Mobile Applications UX/UI Design](#44-mobile-applications-uxui-design)  
    - [4.4.1 Mobile Applications Wireframes](#441-mobile-applications-wireframes)  
    - [4.4.2 Mobile Applications Wireflow Diagrams](#442-mobile-applications-wireflow-diagrams)  
    - [4.4.3 Mobile Applications Mock-ups](#443-mobile-applications-mock-ups)  
    - [4.4.4 Mobile Applications User Flow Diagrams](#444-mobile-applications-user-flow-diagrams)  
  - [4.5 Mobile Applications Prototyping](#45-mobile-applications-prototyping)  
    - [4.5.1 Android Mobile Applications Prototyping](#451-android-mobile-applications-prototyping)  
    - [4.5.2 iOS Mobile Applications Prototyping](#452-ios-mobile-applications-prototyping)  
  - [4.6 Web Applications UX/UI Design](#46-web-applications-uxui-design)  
    - [4.6.1 Web Applications Wireframes](#461-web-applications-wireframes)  
    - [4.6.2 Web Applications Wireflow Diagrams](#462-web-applications-wireflow-diagrams)  
    - [4.6.3 Web Applications Mock-ups](#463-web-applications-mock-ups)  
    - [4.6.4 Web Applications User Flow Diagrams](#464-web-applications-user-flow-diagrams)  
  - [4.7 Web Applications Prototyping](#47-web-applications-prototyping)  
  - [4.8 Domain-Driven Software Architecture](#48-domain-driven-software-architecture)  
    - [4.8.1 Software Architecture Context Diagram](#481-software-architecture-context-diagram)  
    - [4.8.2 Software Architecture Container Diagrams](#482-software-architecture-container-diagrams)  
    - [4.8.3 Software Architecture Components Diagrams](#483-software-architecture-components-diagrams)  
  - [4.9 Software Object-Oriented Design](#49-software-object-oriented-design)  
    - [4.9.1 Class Diagrams](#491-class-diagrams)  
    - [4.9.2 Class Dictionary](#492-class-dictionary)  
  - [4.10 Database Design](#410-database-design)  
    - [4.10.1 Relational/Non-Relational Database Diagram](#4101-relationalnon-relational-database-diagram)    

- [Capítulo V: Product Implementation](#capítulo-v-product-implementation)  
  - [5.1 Software Configuration Management](#51-software-configuration-management)  
    - [5.1.1 Software Development Environment Configuration](#511-software-development-environment-configuration)  
    - [5.1.2 Source Code Management](#512-source-code-management)  
    - [5.1.3 Source Code Style Guide & Conventions](#513-source-code-style-guide--conventions)  
    - [5.1.4 Software Deployment Configuration](#514-software-deployment-configuration)  
  - [5.2 Product Implementation & Deployment](#52-product-implementation--deployment)  
    - [5.2.1 Sprint Backlogs](#521-sprint-backlogs)  
    - [5.2.2 Implemented Landing Page Evidence](#522-implemented-landing-page-evidence)  
    - [5.2.3 Implemented Frontend-Web Application Evidence](#523-implemented-frontend-web-application-evidence)  
    - [5.2.4 Acuerdo de Servicio - SaaS](#524-acuerdo-de-servicio---saas)  
    - [5.2.5 Implemented Native-Mobile Application Evidence](#525-implemented-native-mobile-application-evidence)  
    - [5.2.6 Implemented RESTful API and/or Serverless Backend Evidence](#526-implemented-restful-api-andor-serverless-backend-evidence)  
    - [5.2.7 RESTful API Documentation](#527-restful-api-documentation)  
    - [5.2.8 Team Collaboration Insights](#528-team-collaboration-insights)  
  - [5.3 Video About-the-Product](#53-video-about-the-product)  


- [Part II: Verification, Validation & Pipeline](#part-ii-verification-validation--pipeline)  
  
- [Capítulo VI: Product Verification & Validation](#capítulo-vi-product-verification--validation)  
  - [6.1 Testing Suites & Validation](#61-testing-suites--validation)  
    - [6.1.1 Core Entities Unit Tests](#611-core-entities-unit-tests)  
    - [6.1.2 Core Integration Tests](#612-core-integration-tests)  
    - [6.1.3 Core Behavior-Driven Development](#613-core-behavior-driven-development)  
    - [6.1.4 Core System Tests](#614-core-system-tests)  
  - [6.2 Static Testing & Verification](#62-static-testing--verification)  
    - [6.2.1 Static Code Analysis](#621-static-code-analysis)  
      - [6.2.1.1 Coding Standard & Code Conventions](#6211-coding-standard--code-conventions)  
      - [6.2.1.2 Code Quality & Code Security](#6212-code-quality--code-security)  
    - [6.2.2 Reviews](#622-reviews)  
  - [6.3 Validation Interviews](#63-validation-interviews)  
    - [6.3.1 Diseño de Entrevistas](#631-diseño-de-entrevistas)  
    - [6.3.2 Registro de Entrevistas](#632-registro-de-entrevistas)  
    - [6.3.3 Evaluaciones según heurísticas](#633-evaluaciones-según-heurísticas)  
  - [6.4 Auditoría de Experiencias de Usuario](#64-auditoría-de-experiencias-de-usuario)  
    - [6.4.1 Auditoría realizada](#641-auditoría-realizada)  
      - [6.4.1.1 Información del grupo auditado](#6411-información-del-grupo-auditado)  
      - [6.4.1.2 Cronograma de auditoría realizada](#6412-cronograma-de-auditoría-realizada)  
      - [6.4.1.3 Contenido de auditoría realizada](#6413-contenido-de-auditoría-realizada)  
    - [6.4.2 Auditoría recibida](#642-auditoría-recibida)  
      - [6.4.2.1 Información del grupo auditor](#6421-información-del-grupo-auditor)  
      - [6.4.2.2 Cronograma de auditoría recibida](#6422-cronograma-de-auditoría-recibida)  
      - [6.4.2.3 Contenido de auditoría recibida](#6423-contenido-de-auditoría-recibida)  
      - [6.4.2.4 Resumen de modificaciones para subsanar hallazgos](#6424-resumen-de-modificaciones-para-subsanar-hallazgos)  

- [Capítulo VII: DevOps Practices](#capítulo-vii-devops-practices)  
  - [7.1 Continuous Integration](#71-continuous-integration)  
    - [7.1.1 Tools and Practices](#711-tools-and-practices)  
    - [7.1.2 Build & Test Suite Pipeline Components](#712-build--test-suite-pipeline-components)  
  - [7.2 Continuous Delivery](#72-continuous-delivery)  
    - [7.2.1 Tools and Practices](#721-tools-and-practices)  
    - [7.2.2 Stages Deployment Pipeline Components](#722-stages-deployment-pipeline-components)  
  - [7.3 Continuous Deployment](#73-continuous-deployment)  
    - [7.3.1 Tools and Practices](#731-tools-and-practices)  
    - [7.3.2 Production Deployment Pipeline Components](#732-production-deployment-pipeline-components)  
  - [7.4 Continuous Monitoring](#74-continuous-monitoring)  
    - [7.4.1 Tools and Practices](#741-tools-and-practices)  
    - [7.4.2 Monitoring Pipeline Components](#742-monitoring-pipeline-components)  
    - [7.4.3 Alerting Pipeline Components](#743-alerting-pipeline-components)  
    - [7.4.4 Notification Pipeline Components](#744-notification-pipeline-components) 

- [Part III: Experiment-Driven Lifecycle](#part-iii-experiment-driven-lifecycle)  
  
- [Capítulo VIII: Experiment-Driven Development](#capítulo-viii-experiment-driven-development)  
  - [8.1 Experiment Planning](#81-experiment-planning)  
    - [8.1.1 As-Is Summary](#811-as-is-summary)  
    - [8.1.2 Raw Material: Assumptions, Knowledge Gaps, Ideas, Claims](#812-raw-material-assumptions-knowledge-gaps-ideas-claims)  
    - [8.1.3 Experiment-Ready Questions](#813-experiment-ready-questions)  
    - [8.1.4 Question Backlog](#814-question-backlog)  
    - [8.1.5 Experiment Cards](#815-experiment-cards)  
  - [8.2 Experiment Design](#82-experiment-design)  
    - [8.2.1 Hypotheses](#821-hypotheses)  
    - [8.2.2 Domain Business Metrics](#822-domain-business-metrics)  
    - [8.2.3 Measures](#823-measures)  
    - [8.2.4 Conditions](#824-conditions)  
    - [8.2.5 Scale Calculations and Decisions](#825-scale-calculations-and-decisions)  
    - [8.2.6 Methods Selection](#826-methods-selection)  
    - [8.2.7 Data Analytics: Goals, KPIs and Metrics Selection](#827-data-analytics-goals-kpis-and-metrics-selection)  
    - [8.2.8 Web and Mobile Tracking Plan](#828-web-and-mobile-tracking-plan)  
  - [8.3 Experimentation](#83-experimentation)  
    - [8.3.1 To-Be User Stories](#831-to-be-user-stories)  
    - [8.3.2 To-Be Product Backlog](#832-to-be-product-backlog)  
    - [8.3.3 Pipeline-supported, Experiment-Driven To-Be Software Platform Lifecycle](#833-pipeline-supported-experiment-driven-to-be-software-platform-lifecycle)  
      - [8.3.3.1 To-Be Sprint Backlogs](#8331-to-be-sprint-backlogs)  
      - [8.3.3.2 Implemented To-Be Landing Page Evidence](#8332-implemented-to-be-landing-page-evidence)  
      - [8.3.3.3 Implemented To-Be Frontend-Web Application Evidence](#8333-implemented-to-be-frontend-web-application-evidence)  
      - [8.3.3.4 Implemented To-Be Native-Mobile Application Evidence](#8334-implemented-to-be-native-mobile-application-evidence)  
      - [8.3.3.5 Implemented To-Be RESTful API and/or Serverless Backend Evidence](#8335-implemented-to-be-restful-api-andor-serverless-backend-evidence)  
      - [8.3.3.6 Team Collaboration Insights](#8336-team-collaboration-insights)  
    - [8.3.4 To-Be Validation Interviews](#834-to-be-validation-interviews)  
      - [8.3.4.1 Diseño de Entrevistas](#8341-diseño-de-entrevistas)  
      - [8.3.4.2 Registro de Entrevistas](#8342-registro-de-entrevistas)  
  - [8.4 Experiment Aftermath & Analysis](#84-experiment-aftermath--analysis)  
    - [8.4.1 Analysis and Interpretation of Results](#841-analysis-and-interpretation-of-results)  
    - [8.4.2 Re-scored and Re-prioritized Question Backlog](#842-re-scored-and-re-prioritized-question-backlog)  
  - [8.5 Continuous Learning](#85-continuous-learning)  
    - [8.5.1 Shareback Session Artifacts: Learning Workflow](#851-shareback-session-artifacts-learning-workflow)  
  - [8.6 To-Be Software Platform Pre-launch](#86-to-be-software-platform-pre-launch)  
    - [8.6.1 About-the-Product Intro Video](#861-about-the-product-intro-video)  

- [Conclusiones](#conclusiones)  
  - [Conclusiones y recomendaciones](#conclusiones-y-recomendaciones)  
  - [Video App Validation](#video-app-validation)  
  - [Video About-the-Team](#video-about-the-team)  

- [Bibliografía](#bibliografía)  

- [Anexos](#anexos)  

# Student Outcome  

| Criterio específico | Acciones realizadas | Conclusiones |
|----------------------|---------------------|--------------|
| **4.c.1 Reconoce responsabilidad ética y profesional en situaciones de ingeniería de software** | **Alejo Cardenas, Jose Antonio**<br>TB1: AAA…<br>TB2: BBB…<br>**Real Calderon, Sebastian Omar**<br>TB1: AAA…<br>**Luquillas Asto, Omar**<br>TB1: AAA…<br><br>**Olivera Barzola, Eric Marlon**<br>TB1: AAA…<br><br> | … |
| **4.c.2 Emite juicios informados considerando el impacto de las soluciones de ingeniería de software en contextos globales, económicos, ambientales y sociales** | **Alejo Cardenas, Jose Antonio**<br>TB1: AAA…<br>TB2: BBB…<br>**Real Calderon, Sebastian Omar**<br>TB1: AAA…<br>**Luquillas Asto, Omar**<br>TB1: AAA…<br><br>**Olivera Barzola, Eric Marlon**<br>TB1: AAA…<br><br> | … |


# Part I: As-Is Software Project  

## Capítulo I: Introducción  

### 1.1 Startup Profile  
#### 1.1.1 Descripción de la Startup  
#### 1.1.2 Perfiles de integrantes del equipo  

### 1.2 Solution Profile  
#### 1.2.1 Antecedentes y problemática  

##### What

¿Cuál es el problema?

El problema principal es la falta de un entorno educativo digital unificado y accesible en muchos institutos de Lima, lo que resulta en una gestión docente ineficiente (uso de herramientas dispersas como WhatsApp y correo), dificultad para centralizar y evaluar el trabajo de los estudiantes, y una incapacidad para obtener una visión clara del rendimiento académico de la clase. Esto lleva a una experiencia de aprendizaje fragmentada y reactiva, tanto para profesores como para alumnos.

¿Cuál es la relación con la persona en cuestión?

La relación se establece a través del instituto, que adopta LearnHive como su plataforma oficial. El profesor es nuestro usuario principal y cliente directo, ya que es quien gestiona los cursos, califica y analiza el desempeño. El profesor utiliza LearnHive para estructurar su curso, comunicarse con los estudiantes y transformar su rol de evaluador reactivo a gestor proactivo del aprendizaje. El estudiante accede a la plataforma como usuario final, encontrando un espacio centralizado para sus cursos, tareas y calificaciones, permitiéndole gestionar sus trabajos con mayor facilidad.

##### When

¿Cuándo sucede el problema?

El problema ocurre diariamente durante el ciclo académico:

Para el profesor: Al intentar organizar y publicar materiales para cada clase, al recibir decenas de entregas por diferentes canales, y al momento de calificar y consolidar esas notas manualmente en una hoja de cálculo. También surge al final del ciclo académico, cuando necesita analizar las notas para generar reportes de desempeño, un proceso que suele ser manual.

Para el estudiante: Al no tener un lugar claro donde consultar las tareas, materiales o fechas de entrega, y al tener que enviar sus trabajos a través de medios informales que no garantizan su recepción correcta. Así como no tener una plataforma que unifique todas las funcionalidades del sistema educativo.

¿Cuándo utiliza el cliente el producto?

El profesor lo usa de forma constante para revisar avances, publicar anuncios y/o trabajos y calificar entregas. De la misma manera, puede ver el desempeño de sus alumnos en tiempo real con métricas que se actualizan diariamente.

El estudiante accede a la plataforma a diario para verificar sus cursos, las tareas pendientes y los anuncios nuevos, y de manera puntual para subir sus entregas antes de la fecha límite y consultar sus calificaciones.

##### Where

¿Dónde está el cliente cuando usa el producto?

Tanto profesores como estudiantes acceden a LearnHive principalmente desde sus dispositivos móviles y computadoras portátiles o de escritorio, desde cualquier lugar con conexión a internet: en el instituto, en sus hogares o en movimiento.

¿Dónde surge el problema?

El problema surge en el entorno educativo mismo:

En la sala de profesores y el domicilio del docente, donde se invierten tiempo en organizar, calificar y compilar información de manera manual.

En el entorno del estudiante, que se ve obligado a navegar entre múltiples apps y chats para gestionar su aprendizaje.

##### Why

¿Por qué sucede el problema?

Sucede porque muchos institutos de Lima carecen de los recursos financieros y técnicos para desarrollar, implementar y mantener una plataforma educativa propia y robusta. Las soluciones existentes en el mercado pueden ser demasiado costosas, genéricas o complejas para sus necesidades específicas. Esto los fuerza a depender de herramientas gratuitas pero no diseñadas para la educación (servicios de mensajería o correo electrónico), lo que genera desorganización, pérdida de información y una carga administrativa insostenible para el docente.

##### Who

¿Quienes se ven involucrados en el problema?

El problema involucra directamente a los profesores y estudiantes, quienes son los más afectados por la gestión educativa desorganizada. Los profesores cargan con la pesada administración manual, mientras que los estudiantes enfrentan una experiencia de aprendizaje fragmentada. Indirectamente, los directores de los institutos y los padres de familia también se ven perjudicados, ya que carecen de acceso claro a datos sobre el rendimiento.

¿Cuáles son las causas del problema?

La causa fundamental del problema es una brecha digital y económica que limita el acceso a herramientas tecnológicas asequibles y fáciles de usar, junto con una falta de capacitación que genera resistencia al cambio en muchos entornos educativos.

##### How

¿En qué condiciones los clientes usan nuestro producto?

Los clientes utilizan LearnHive principalmente a través de un navegador web o una aplicación móvil, dependiendo de una conexión a internet accesible. La plataforma está diseñada para ser usada de forma asíncrona, permitiendo que profesores y estudiantes interactúen con el contenido en los momentos que más les convengan. La usabilidad es fundamental, por lo que la interfaz debe ser extremadamente intuitiva para garantizar una adopción rápida y sin fricciones, minimizando la necesidad de una capacitación extensa.

##### How Much

¿Cuál es la magnitud del problema?



#### 1.2.2 Lean UX Process  
##### 1.2.2.1 Lean UX Problem Statements  
##### 1.2.2.2 Lean UX Assumptions  
##### 1.2.2.3 Lean UX Hypothesis Statements  
##### 1.2.2.4 Lean UX Canvas  

### 1.3 Segmentos objetivo  


## Capítulo II: Requirements Elicitation & Analysis  

### 2.1 Competidores  
#### 2.1.1 Análisis competitivo  
#### 2.1.2 Estrategias y tácticas frente a competidores  

### 2.2 Entrevistas  
#### 2.2.1 Diseño de entrevistas  
#### 2.2.2 Registro de entrevistas  
#### 2.2.3 Análisis de entrevistas  

### 2.3 Needfinding  
#### 2.3.1 User Personas  
#### 2.3.2 User Task Matrix  
#### 2.3.3 User Journey Mapping  
#### 2.3.4 Empathy Mapping  
#### 2.3.5 As-is Scenario Mapping  

### 2.4 Ubiquitous Language  


## Capítulo III: Requirements Specification  

### 3.1 To-Be Scenario Mapping  

Segmento Objetivo 1: Estudiantes de institutos 

El To-Be Scenario Mapping de estudiantes muestra cómo LearnHive centraliza materiales, tareas y métricas en un único espacio. Esto elimina la dispersión de canales y reduce la inseguridad en las entregas, ofreciendo confirmación inmediata y dashboards visuales con retroalimentación en tiempo real. El resultado esperado es mayor tranquilidad, motivación y confianza en la gestión de su desempeño académico. 

<img src="./assets/chapter-3/ToBe-Scenario Mapping- Estudiantes de instituto.png" alt="ToBe-Scenario Mapping- Estudiantes de instituto" width="600"/>

Segmento Objetivo 2: Profesores de Institutos 

El To-Be Scenario Mapping de profesores de instituto plantea un futuro en el que LearnHive simplifica la planificación, automatiza parte de la retroalimentación y centraliza la comunicación con los estudiantes. De esta manera, los docentes reducen su carga administrativa, obtienen métricas claras para intervenir oportunamente y sienten alivio, satisfacción y motivación al enfocarse más en la enseñanza que en las tareas manuales. 

<img src="./assets/chapter-3/ToBe-Scenario Mapping- Profesores de instituto.png" alt="ToBe-Scenario Mapping- Profesores de instituto" width="600"/>

### 3.2 User Stories  

Epicas:

<table>
  <thead>
    <tr>
      <th>Epic ID</th>
      <th>Título</th>
      <th>Descripción</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>EP-001</td>
      <td>Autenticación de usuarios</td>
      <td>Esta épica se centra en garantizar que los estudiantes y profesores puedan acceder de manera segura y confiable a la plataforma. Incluye funcionalidades de inicio de sesión y registro de nuevos usuarios. La autenticación asegura que solo los usuarios autorizados puedan interactuar con los distintos módulos del sistema, protegiendo la información personal y académica. Además, permite la gestión de sesiones activas, control de permisos según el rol del usuario y registro de intentos de acceso, contribuyendo a la seguridad, trazabilidad y control dentro de la plataforma educativa.</td>
    </tr>
    <tr>
      <td>EP-002</td>
      <td>Gestión de Grupos</td>
      <td>Esta épica se enfoca en ofrecer a profesores y estudiantes una forma sencilla y estructurada de crear y administrar grupos académicos. El docente tiene la capacidad de formar equipos, asignar integrantes y mantener un control organizado sobre su composición. Los estudiantes, por su parte, cuentan con un espacio definido para integrarse a sus grupos de trabajo, lo que fomenta la colaboración y la coordinación en sus actividades académicas.</td>
    </tr>
    <tr>
      <td>EP-003</td>
      <td>Gestión de trabajos y entregas</td>
      <td>Esta épica se enfoca en las funcionalidades orientadas a la creación de trabajos académicos para cada grupo, y el recibimiento de entregas, así como la calificación de estas. Por parte de los estudiantes, estos deben poder visualizar sus trabajos pendientes tanto en el menú de un grupo específico como en un menú especializado general que les muestre sus fechas de entrega más cercanas. Por el lado de los profesores, estos deben poder crear trabajos con fechas límite, administrar su visualización y acceder a las entregas de sus alumnos, así como calificarlas y dejar mensajes de retroalimentación.</td>
    </tr>
    <tr>
      <td>EP-004</td>
      <td>Seguimiento de progreso y retroalimentación automatizada</td>
      <td>Esta épica se centra en ofrecer funcionalidades que permitan a estudiantes y profesores acceder a datos en tiempo real sobre el rendimiento académico. Los estudiantes podrán visualizar sus calificaciones, avances y métricas comparativas mediante paneles de control gráficos, lo que les permitirá identificar fortalezas, debilidades y áreas de mejora. Además, contarán con retroalimentación automatizada e instantánea, generada a partir de sus entregas y participación, para orientar su aprendizaje de manera continua. Por el lado de los profesores, estos podrán monitorear tanto las métricas individuales de cada estudiante como el desempeño general del grupo, identificando patrones y detectando a tiempo las dificultades más comunes.</td>
    </tr>
    <tr>
      <td>EP-005</td>
      <td>Comunicación, interacción y recursos educativos dinámicos entre usuarios</td>
      <td>Esta épica se orienta al intercambio de información y la creación de espacios de interacción dentro de la plataforma. Los profesores podrán publicar anuncios dirigidos a todo el grupo, en los cuales los alumnos podrán dejar comentarios, consultas o dudas que serán respondidas en el mismo hilo. Tanto docentes como estudiantes recibirán notificaciones automáticas que les mantendrán al tanto de las respuestas e interacciones. Asimismo, los alumnos tendrán la posibilidad de enviarse mensajes privados para coordinar actividades académicas de manera ágil. Como valor agregado, la épica incorpora la posibilidad de compartir recursos educativos interactivos tales como videos cortos, imágenes y materiales en tiempo real, lo que no solo mejora la comunicación, sino que también hace más atractivo y participativo el proceso de aprendizaje.</td>
    </tr>
    <tr>
      <td>EP-006</td>
      <td>Diseño de la landing page</td>
      <td>Como equipo de desarrollo, queremos diseñar y construir una landing page atractiva, informativa y fácil de navegar, que comunique claramente el valor de la plataforma tanto para estudiantes como para profesores, con el objetivo de captar nuevos usuarios, generar confianza y facilitar el registro en el sistema.</td>
    </tr>
    <tr>
      <td>EP-007</td>
      <td>Infraestructura técnica, escalabilidad y calidad del sistema</td>
      <td>Esta épica se enfoca en las tareas técnicas necesarias para asegurar el correcto funcionamiento de la plataforma desde el punto de vista tecnológico. Incluye configuraciones de backend, frontend, infraestructura y pruebas automatizadas, que no son visibles directamente para el usuario final pero que resultan fundamentales para garantizar seguridad, rendimiento, estabilidad, escalabilidad y mantenibilidad en el tiempo.</td>
    </tr>
  </tbody>
</table>

User Stories:

<table>
  <thead>
    <tr>
      <th>User Story ID</th>
      <th>Título</th>
      <th>Descripción</th>
      <th>Criterios de Aceptación</th>
      <th>Relacionado con (Epic ID)</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>US-001</td>
      <td>Registro de usuario</td>
      <td>Como nuevo usuario, quiero registrarme en la plataforma proporcionando mis datos personales y académicos, para crear una cuenta que me permita acceder al sistema.</td>
      <td>
        <strong>Escenario 1:</strong> Dado un usuario que desea registrarse, cuando completa el formulario de registro con correo, nombre, apellido, contraseña y rol (estudiante o profesor) y selecciona "Registrarse", entonces el sistema valida la información, crea la cuenta y envía un correo de confirmación.<br><br>
        <strong>Escenario 2:</strong> Dado un usuario que intenta registrarse con un correo ya existente, cuando selecciona "Registrarse", entonces el sistema muestra un mensaje de error "El correo ya está registrado" y solicita ingresar uno diferente.
      </td>
      <td>EP-001</td>
    </tr>
    <tr>
      <td>US-002</td>
      <td>Inicio de sesión (Autenticación)</td>
      <td>Como usuario registrado (estudiante o profesor), quiero iniciar sesión en la plataforma, para acceder a mis cursos, grupos y trabajos asignados de manera segura.</td>
      <td>
        <strong>Escenario 1:</strong> Dado un usuario registrado en la plataforma, cuando ingresa su correo electrónico y contraseña correctos y selecciona "Iniciar sesión", entonces el sistema valida sus credenciales, inicia sesión y lo redirige a su panel de control visual correspondiente.<br><br>
        <strong>Escenario 2:</strong> Dado un usuario que ingresa credenciales incorrectas, cuando selecciona "Iniciar sesión", entonces el sistema muestra un mensaje de error "Correo o contraseña incorrectos" y no permite el acceso al panel de control visual.
      </td>
      <td>EP-001</td>
    </tr>
    <tr>
      <td>US-003</td>
      <td>Ingreso a grupos</td>
      <td>Como estudiante, quiero ser capaz de unirme a los grupos formados por mis profesores con facilidad.</td>
      <td>
        <strong>Escenario 1:</strong> Dado un estudiante en el menú de inicio de la plataforma con un código de grupo válido proporcionado por su profesor, cuando ingresa el código en el campo designado y selecciona la opción "Unirse al grupo", entonces el sistema valida el código, muestra un mensaje de confirmación exitosa y añade automáticamente al estudiante al grupo correspondiente.<br><br>
        <strong>Escenario 2:</strong> Dado un estudiante en el menú de inicio con una notificación de invitación pendiente para unirse a un grupo de clase, cuando selecciona la notificación y hace clic en el botón "Aceptar invitación", entonces el sistema confirma la aceptación, añade al estudiante al grupo y actualiza la lista de miembros visible para el profesor.
      </td>
      <td>EP-002</td>
    </tr>
    <tr>
      <td>US-004</td>
      <td>Creación de grupos</td>
      <td>Como profesor, quiero ser capaz de crear grupos para mis cursos en la plataforma.</td>
      <td>
        <strong>Escenario 1:</strong> Dado un profesor autenticado en la plataforma educativa, cuando selecciona la opción "Crear Nuevo Grupo" desde el menú principal, entonces el sistema despliega un formulario con campos para nombre del grupo, descripción, etc. Permitiendo la creación del grupo tras completar los datos obligatorios.<br><br>
        <strong>Escenario 2:</strong> Dado un profesor en el proceso de creación de un nuevo grupo, cuando ingresa un nombre idéntico al de un grupo preexistente bajo su misma cuenta y intenta guardar, entonces el sistema detecta la duplicación, muestra un mensaje de error "Nombre de grupo ya existente" y sugiere modificar el nombre o recuperar el grupo existente.
      </td>
      <td>EP-002</td>
    </tr>
    <tr>
      <td>US-005</td>
      <td>Invitación a grupos</td>
      <td>Como profesor, quiero ser capaz de invitar a mis alumnos a los grupos creados por mí.</td>
      <td>
        <strong>Escenario 1:</strong> Dado un grupo creado por un profesor con un código de invitación generado, cuando un estudiante ingresa correctamente el código en la plataforma, entonces el sistema añade al estudiante al grupo, registra la acción y envía una notificación automática al profesor confirmando la incorporación del nuevo miembro.<br><br>
        <strong>Escenario 2:</strong> Dado un profesor en la sección de gestión de un grupo específico, cuando ingresa los IDs o correos electrónicos de los estudiantes en el campo de invitaciones y selecciona "Enviar invitaciones", entonces el sistema envía notificaciones individuales a cada estudiante con un enlace directo para unirse al grupo y actualiza el estado de invitaciones pendientes.<br><br>
        <strong>Escenario 3:</strong> Dado un estudiante que recibe una invitación para unirse a un grupo, cuando hace clic en el enlace de la notificación o ingresa manualmente el código proporcionado, entonces el sistema verifica la validez de la invitación, añade al estudiante al grupo correspondiente y notifica al profesor sobre la aceptación exitosa de la invitación.
      </td>
      <td>EP-002</td>
    </tr>
    <tr>
      <td>US-006</td>
      <td>Eliminación de alumnos</td>
      <td>Como profesor, quiero ser capaz de eliminar integrantes del grupo, para mantener un orden y corregir errores en caso de invitar a alguien por equivocación.</td>
      <td>
        <strong>Escenario 1:</strong> Dado un profesor en la pantalla de gestión de integrantes de un grupo activo, cuando selecciona la opción "Eliminar" junto al nombre de un estudiante y confirma la acción en el cuadro de diálogo emergente, entonces el sistema remueve al estudiante del grupo, actualiza la lista de miembros y envía una notificación automática al estudiante informando sobre su eliminación del grupo.<br><br>
        <strong>Escenario 2:</strong> Dado un profesor intentando eliminar a un estudiante que ya ha sido removido previamente del grupo o cuya cuenta ya no existe, cuando confirma la acción de eliminación, entonces el sistema detecta que el estudiante no pertenece al grupo y muestra un mensaje de error: "El estudiante especificado no pertenece a este grupo o ya ha sido eliminado".
      </td>
      <td>EP-002</td>
    </tr>
    <tr>
      <td>US-007</td>
      <td>Creación de trabajos con fechas límite</td>
      <td>Como profesor, quiero crear trabajos dentro de cada curso con sus respectivas fechas de entrega, para organizar las actividades académicas y dar claridad a mis estudiantes.</td>
      <td>
        <strong>Escenario 1:</strong> Dado un profesor en la página de administración de un curso específico, cuando selecciona la opción "Crear trabajo", completa los campos obligatorios (título, descripción, fecha límite) y confirma la creación, entonces el sistema guarda el trabajo en la base de datos, lo muestra en la lista de actividades del curso y notifica a todos los estudiantes del grupo sobre la nueva tarea asignada.<br><br>
        <strong>Escenario 2:</strong> Dado un profesor en el proceso de creación de un nuevo trabajo para el curso, cuando ingresa una fecha límite anterior a la fecha actual y intenta guardar, entonces el sistema detecta la incongruencia, muestra un mensaje de error "La fecha de entrega debe ser futura" y resalta el campo de fecha en rojo hasta que se corrija.
      </td>
      <td>EP-003</td>
    </tr>
    <tr>
      <td>US-008</td>
      <td>Recepción de entregas (múltiples oportunidades)</td>
      <td>Como estudiante, quiero poder enviar y reenviar mis entregas en un trabajo académico, para corregir errores y mejorar mi calificación antes de la fecha límite.</td>
      <td>
        <strong>Escenario 1:</strong> Dado un estudiante con acceso a un trabajo académico dentro del plazo de entrega establecido, cuando selecciona la opción "Subir entrega", adjunta el archivo correspondiente y confirma el envío, entonces el sistema registra la entrega con marca de tiempo, envía una confirmación al estudiante y notifica al profesor sobre la nueva entrega recibida.<br><br>
        <strong>Escenario 2:</strong> Dado un estudiante que ya ha realizado una entrega previa para un trabajo académico, cuando selecciona "Reemplazar entrega" antes de la fecha límite y sube un nuevo archivo, entonces el sistema guarda la nueva versión, mantiene un historial de todas las entregas realizadas y actualiza la marca de tiempo de la última modificación.<br><br>
        <strong>Escenario 3:</strong> Dado un estudiante intentando enviar una entrega después de la fecha límite establecida, cuando intenta subir un archivo pasado el plazo, entonces el sistema rechaza la entrega, muestra un mensaje claro indicando "Plazo de entrega vencido" y sugiere contactar al profesor.
      </td>
      <td>EP-003</td>
    </tr>
    <tr>
      <td>US-009</td>
      <td>Visualización de trabajos y fechas</td>
      <td>Como estudiante, quiero visualizar en un panel de control visual todos mis trabajos y fechas de entrega, para organizar mis actividades y priorizar las más urgentes.</td>
      <td>
        <strong>Escenario 1:</strong> Dado un estudiante en la página principal de un curso específico, cuando navega a la pestaña "Trabajos", entonces el sistema muestra una lista completa de todas las tareas asignadas, con indicadores visuales de estado (pendiente/entregado/calificado), fechas límite claramente visibles y porcentaje de completitud para cada trabajo.<br><br>
        <strong>Escenario 2:</strong> Dado un estudiante en su panel de control visual principal, cuando accede a la sección "Próximas entregas", entonces el sistema muestra una lista consolidada de todos los trabajos pendientes de todos sus cursos, ordenados por fecha límite ascendente (los más urgentes primero), con recordatorios visuales para las tareas con vencimiento en las próximas 48 horas.<br><br>
        <strong>Escenario 3:</strong> Dado un trabajo académico con fecha límite próxima (menos de 24 horas), cuando el estudiante visualiza su panel de control visual, entonces el sistema resalta esa tarea con color rojo, muestra una alerta de "Entrega próxima" y ofrece la opción de acceso directo a la página de entrega con un solo clic.
      </td>
      <td>EP-003</td>
    </tr>
    <tr>
      <td>US-010</td>
      <td>Calificación de entregas</td>
      <td>Como profesor, quiero calificar las entregas de los estudiantes y dejar retroalimentación, para evaluar su desempeño académico y mantener registro de calificaciones.</td>
      <td>
        <strong>Escenario 1:</strong> Dado un profesor que accede a un trabajo académico, cuando selecciona la entrega de un estudiante, entonces el sistema muestra la entrega y permite ingresar una calificación y un comentario de retroalimentación.<br><br>
        <strong>Escenario 2:</strong> Dado un profesor que ha calificado una entrega, cuando guarda la calificación, entonces el sistema actualiza la información y la notifica al estudiante, mostrando la calificación y los comentarios en su panel de control visual correspondiente.
      </td>
      <td>EP-003</td>
    </tr>
    <tr>
      <td>US-011</td>
      <td>Visualización de panel de control visual de progreso académico</td>
      <td>Como estudiante, quiero visualizar un panel de control visual con mis calificaciones y progreso en tiempo real, para saber si estoy avanzando de manera adecuada en mis cursos.</td>
      <td>
        <strong>Escenario 1:</strong> Dado un estudiante con sesión activa en la plataforma educativa, cuando accede a la sección "Mi Progreso" desde el menú principal, entonces el sistema muestra un panel de control visual interactivo con gráficos de calificaciones por curso, porcentaje de completitud de cada materia, comparativa con el promedio del grupo y proyección de calificación final basada en el rendimiento actual.<br><br>
        <strong>Escenario 2:</strong> Dado un profesor que ha calificado y publicado nuevos trabajos o exámenes en el sistema, cuando el estudiante recarga su panel de control visual de progreso, entonces el sistema actualiza automáticamente todas las métricas, muestra las nuevas calificaciones obtenidas con notificaciones de novedades y recalcula el promedio general y por curso en tiempo real.<br><br>
        <strong>Escenario 3:</strong> Dado un estudiante con calificaciones por debajo del promedio requerido en algún curso, cuando ingresa a su panel de control visual de progreso, entonces el sistema destaca aquellas materias con bajo rendimiento usando indicadores de color.
      </td>
      <td>EP-004</td>
    </tr>
    <tr>
      <td>US-012</td>
      <td>Comparación del rendimiento con el promedio del grupo</td>
      <td>Como estudiante, quiero poder comparar mi rendimiento con el promedio de mis compañeros, para identificar si estoy por encima o debajo del nivel general.</td>
      <td>
        <strong>Escenario 1:</strong> Dado un estudiante en su panel de control visual académico principal, cuando selecciona la opción "Comparar con grupo" en cualquier curso, entonces el sistema genera un gráfico de barras comparativas que muestra sus calificaciones individuales junto al promedio del grupo en cada evaluación, con diferencias porcentuales claramente etiquetadas.<br><br>
        <strong>Escenario 2:</strong> Dado un estudiante en la sección de comparativa de rendimiento, cuando selecciona la opción "Evolución Temporal", entonces el sistema muestra una gráfica de líneas con su progreso histórico y el promedio del grupo a lo largo del semestre, permitiendo identificar tendencias y momentos clave de mejora o retroceso.
      </td>
      <td>EP-004</td>
    </tr>
    <tr>
      <td>US-013</td>
      <td>Visualización de métricas globales de desempeño del grupo</td>
      <td>Como profesor, quiero acceder a métricas globales del grupo, para entender el nivel de desempeño general de la clase.</td>
      <td>
        <strong>Escenario 1:</strong> Dado un profesor en la página de gestión de un grupo de estudiantes, cuando selecciona la opción "Métricas Globales", entonces el sistema muestra un panel con el promedio general de calificaciones, desviación estándar, tasa de entregas a tiempo, porcentaje de aprobación y comparativa con otros grupos del mismo curso.<br><br>
        <strong>Escenario 2:</strong> Dado un profesor analizando el rendimiento de su grupo, cuando selecciona un período específico (ej. primer parcial, último mes o trimestre), entonces el sistema genera gráficas de progreso colectivo que incluyen: curva de distribución de calificaciones, tendencia temporal del promedio grupal y tasas de entrega por evaluación.
      </td>
      <td>EP-004</td>
    </tr>
    <tr>
      <td>US-014</td>
      <td>Alertas sobre estudiantes con bajo rendimiento</td>
      <td>Como profesor, quiero recibir alertas sobre estudiantes con bajo rendimiento, para poder intervenir de manera temprana.</td>
      <td>
        <strong>Escenario 1:</strong> Dado un estudiante con calificaciones consistentemente por debajo del 60% en un curso específico durante al menos tres evaluaciones consecutivas, cuando el sistema procesa los resultados académicos, entonces el profesor recibe una notificación con el nombre del estudiante, el curso afectado, las calificaciones específicas y sugerencias de intervención académica.<br><br>
        <strong>Escenario 2:</strong> Dado un estudiante que no ha entregado al menos dos tareas consecutivas dentro del plazo establecido, cuando el sistema analiza el historial de entregas, entonces genera una alerta automática para el profesor con el nombre del estudiante, las tareas pendientes y la opción de contactar directamente al estudiante desde la plataforma.
      </td>
      <td>EP-004</td>
    </tr>
    <tr>
      <td>US-015</td>
      <td>Recordatorios y notificaciones de entregas</td>
      <td>Como estudiante, quiero recibir notificaciones automáticas y recordatorios de próximas entregas para no olvidar subir mis trabajos a tiempo.</td>
      <td>
        <strong>Escenario 1:</strong> Dado un trabajo académico con fecha límite definida en el sistema, cuando faltan exactamente 48 y 12 horas para el vencimiento, entonces el sistema envía notificaciones automáticas al estudiante a través de la plataforma web y la aplicación móvil, incluyendo detalles específicos de la tarea y enlace directo para subirla.<br><br>
        <strong>Escenario 2:</strong> Dado un estudiante que ha completado el proceso de entrega de un trabajo, cuando el sistema verifica y almacena correctamente el archivo subido, entonces muestra una confirmación visual inmediata con número de comprobante, envía un acuse de recibo por correo electrónico y actualiza el estado de la tarea a "Entregado".
      </td>
      <td>EP-005</td>
    </tr>
    <tr>
      <td>US-016</td>
      <td>Re-entrega controlada</td>
      <td>Como estudiante, quiero poder re-entregar una tarea dentro de un plazo definido para mejorar mi nota según las reglas del curso.</td>
      <td>
        <strong>Escenario 1:</strong> Dado un trabajo académico configurado con re-entregas permitidas por el profesor, cuando el estudiante sube una nueva versión del trabajo antes del plazo máximo de re-entrega, entonces el sistema reemplaza automáticamente el archivo anterior, registra el nuevo envío en el historial de versiones y mantiene la marca de tiempo original de la primera entrega para fines de penalización por tardanza.<br><br>
        <strong>Escenario 2:</strong> Dado un estudiante intentando re-entregar un trabajo después del plazo máximo permitido para revisiones, cuando intenta subir un nuevo archivo pasado el límite, entonces el sistema bloquea la acción, muestra un mensaje claro indicando "Plazo de re-entrega vencido" y sugiere contactar al profesor para autorización excepcional.
      </td>
      <td>EP-003</td>
    </tr>
    <tr>
      <td>US-017</td>
      <td>Historial de calificaciones</td>
      <td>Como estudiante, quiero poder consultar el historial de calificaciones de mis entregas, para ver mi evolución académica en cada curso.</td>
      <td>
        <strong>Escenario 1:</strong> Dado un estudiante con múltiples calificaciones registradas en diferentes cursos, cuando accede a la sección "Historial de Calificaciones" desde su panel de control visual principal, entonces el sistema muestra una tabla completa con todas las notas obtenidas, organizadas por curso, fecha de evaluación, tipo de trabajo y porcentaje de valor en la nota final.<br><br>
        <strong>Escenario 2:</strong> Dado un estudiante visualizando su historial académico general, cuando selecciona un curso específico y aplica el filtro correspondiente, entonces el sistema muestra una gráfica de evolución temporal con sus calificaciones en ese curso, el promedio del grupo para cada evaluación y una línea de tendencia que visualiza su progreso académico a lo largo del tiempo.
      </td>
      <td>EP-003</td>
    </tr>
    <tr>
      <td>US-018</td>
      <td>Acceso a todas las entregas de un trabajo</td>
      <td>Como profesor, quiero acceder en una sola vista a todas las entregas de un trabajo, para agilizar la revisión y calificación.</td>
      <td>
        <strong>Escenario 1:</strong> Dado un profesor en la página de administración de un trabajo específico, cuando selecciona la pestaña "Entregas", entonces el sistema muestra una lista completa de todos los estudiantes del curso con sus respectivos estados de entrega (pendiente, enviado, calificado), marcas de tiempo de envío y archivos adjuntos descargables en un solo lugar.<br><br>
        <strong>Escenario 2:</strong> Dado un profesor revisando múltiples entregas de estudiantes, cuando aplica filtros específicos (solo pendientes, solo calificados, solo enviados sin calificar, por rango de fechas), entonces el sistema actualiza dinámicamente la vista mostrando exclusivamente las entregas que coinciden con los criterios seleccionados, facilitando la revisión por lotes.
      </td>
      <td>EP-003</td>
    </tr>
    <tr>
      <td>US-019</td>
      <td>Publicación de anuncios con comentarios</td>
      <td>Como profesor, quiero publicar anuncios en el curso y que los estudiantes puedan dejar comentarios, para mantener la comunicación centralizada y ordenada.</td>
      <td>
        <strong>Escenario 1:</strong> Dado un profesor en la página principal del curso, cuando crea un nuevo anuncio completando título, mensaje y configuraciones de visibilidad, y confirma la publicación, entonces el sistema publica el anuncio en el foro del curso, lo marca como prioritario en la parte superior de la lista y envía notificaciones push a todos los estudiantes del grupo.<br><br>
        <strong>Escenario 2:</strong> Dado un anuncio publicado con la opción de comentarios activada, cuando un estudiante escribe un comentario en el espacio designado y presiona "Enviar", entonces el sistema agrega el comentario al hilo de discusión mostrando nombre del autor, foto de perfil, marca de tiempo exacta y permite respuestas anidadas para mantener conversaciones organizadas.<br><br>
        <strong>Escenario 3:</strong> Dado un anuncio publicado hace menos de 30 minutos, cuando el profesor edita el contenido del anuncio o desactiva la opción de comentarios desde el menú de configuración, entonces el sistema actualiza el contenido mostrando la leyenda "Editado" con la hora de modificación y, en caso de cierre de comentarios, deshabilita el campo de texto para nuevos comentarios, pero mantiene visibles los existentes.
      </td>
      <td>EP-005</td>
    </tr>
    <tr>
      <td>US-020</td>
      <td>Mensajería privada entre miembros</td>
      <td>Como estudiante, quiero enviar mensajes privados a mis compañeros y profesores, para coordinar actividades académicas de manera rápida y directa.</td>
      <td>
        <strong>Escenario 1:</strong> Dado un estudiante en la sección "Miembros del Curso" con la lista de participantes visibles, cuando selecciona a un compañero o profesor de la lista y envía un mensaje privado a través del botón de mensajería, entonces el sistema crea un hilo de conversación privado, almacena el mensaje en la base de datos y muestra una confirmación de envío exitoso al remitente.<br><br>
        <strong>Escenario 2:</strong> Dado un hilo de mensajes privados existente entre dos usuarios del mismo curso, cuando el destinatario abre la conversación para leer los mensajes nuevos, entonces el sistema actualiza inmediatamente el estado de los mensajes de "entregado" a "leído", muestra la marca de tiempo de lectura y notifica al remitente sobre el cambio de estado.<br><br>
        <strong>Escenario 3:</strong> Dado un estudiante intentando iniciar una conversación privada con un usuario que no pertenece a ninguno de sus cursos activos, cuando escribe un mensaje e intenta enviarlo, entonces el sistema bloquea el envío, muestra un mensaje de error claro: "Solo puede enviar mensajes a miembros de sus cursos" y sugiere verificar la lista de contactos disponibles dentro de cada curso.
      </td>
      <td>EP-005</td>
    </tr>
    <tr>
      <td>US-021</td>
      <td>Compartir recursos educativos</td>
      <td>Como profesor, quiero subir materiales de apoyo (documentos, videos, imágenes) al curso, para que los estudiantes los consulten fácilmente en cualquier momento.</td>
      <td>
        <strong>Escenario 1:</strong> Dado un profesor en la sección "Recursos del Curso" con materiales preparados para compartir, cuando selecciona "Subir nuevo recurso", completa los metadatos obligatorios (título, descripción, tipo de archivo) y confirma la acción, entonces el sistema almacena el archivo en el repositorio, lo categoriza automáticamente y lo publica inmediatamente para todos los estudiantes del curso con permisos de visualización y descarga.<br><br>
        <strong>Escenario 2:</strong> Dado un recurso educativo publicado en el repositorio del curso con acceso habilitado para estudiantes, cuando un estudiante accede a la sección de recursos y selecciona "Descargar" o "Visualizar" en cualquier material, entonces el sistema permite la acción requerida y registra en el log de actividad el nombre del estudiante, el recurso consultado y la marca de tiempo de acceso.<br><br>
        <strong>Escenario 3:</strong> Dado un recurso existente en el repositorio que requiere actualización de contenido, cuando el profesor sube una nueva versión del mismo archivo con el mismo identificador único, entonces el sistema preserva la versión anterior en el historial, marca la nueva versión como "actualizada [fecha]" y notifica opcionalmente a los estudiantes sobre la disponibilidad del material revisado.
      </td>
      <td>EP-005</td>
    </tr>
    <tr>
      <td>US-022</td>
      <td>Extensión de plazo de entrega</td>
      <td>Como profesor, quiero poder extender la fecha límite de un trabajo, para dar más tiempo a mis estudiantes en casos especiales.</td>
      <td>
        <strong>Escenario 1:</strong> Dado un trabajo académico con fecha límite configurada en el sistema, cuando el profesor accede a la configuración del trabajo, modifica la fecha de vencimiento a una nueva fecha futura y guarda los cambios, entonces el sistema actualiza automáticamente la fecha en todos los registros asociados, muestra un mensaje de "Fecha actualizada correctamente" y registra la modificación en el historial de cambios.<br><br>
        <strong>Escenario 2:</strong> Dado un trabajo con fecha límite recién modificada por el profesor, cuando se confirma la actualización, entonces el sistema envía una notificación automática a todos los estudiantes del curso con el siguiente mensaje: "Plazo extendido: La fecha límite para [nombre del trabajo] ha sido extendida hasta [nueva fecha]. ¡Aprovecha el tiempo adicional!".
      </td>
      <td>EP-003</td>
    </tr>
    <tr>
      <td>US-023</td>
      <td>Estados de entrega</td>
      <td>Como estudiante, quiero ver el estado de cada entrega (pendiente, entregado, en revisión, calificado), para conocer en qué punto del proceso está mi trabajo.</td>
      <td>
        <strong>Escenario 1:</strong> Dado un estudiante en la sección "Mis Entregas" del curso, cuando selecciona un trabajo específico de la lista, entonces el sistema muestra claramente el estado actual con indicadores visuales (iconos y colores): pendiente, entregado, en revisión o calificado, junto con la fecha de última actualización.<br><br>
        <strong>Escenario 2:</strong> Dado un profesor realizando la calificación de una entrega estudiantil, cuando asigna una calificación o cambia el estado de revisión en el sistema, entonces el estado del trabajo se actualiza automáticamente en todos los dispositivos, mostrando inmediatamente el nuevo estado (calificado) y los detalles de la evaluación al estudiante.<br><br>
        <strong>Escenario 3:</strong> Dado un cambio de estado en cualquier entrega de trabajo (de "en revisión" a "calificado", por ejemplo), cuando el sistema registra la modificación, entonces envía una notificación push al estudiante con el mensaje: "Tu trabajo [nombre del trabajo] ha sido [nuevo estado]. Revisa tus resultados en la plataforma."
      </td>
      <td>EP-003</td>
    </tr>
    <tr>
      <td>US-024</td>
      <td>Redirección al aplicativo web</td>
      <td>Como usuario, quiero que exista un botón en la landing page que me redirija al panel de control visual del aplicativo web del sistema, para acceder a este sin tener que buscar otro enlace.</td>
      <td>
        <strong>Escenario 1:</strong> Dado un usuario en la landing page de la empresa emergente, cuando hace clic en el botón "Acceder al panel de control visual" ubicado en la cabecera de la página, entonces el sistema redirige automáticamente a la URL del aplicativo web, abriendo la página de Inicio de Sesión.<br><br>
        <strong>Escenario 2:</strong> Dado un usuario que ya ha iniciado sesión previamente en el aplicativo web, cuando accede a la landing page y hace clic en el botón "Dashboard", entonces el sistema verifica las credenciales almacenadas y redirige directamente al panel de control visual principal sin requerir un nuevo inicio de sesión.
      </td>
      <td>EP-006</td>
    </tr>
    <tr>
      <td>US-025</td>
      <td>Sección de Video About the Team</td>
      <td>Como usuario, quiero encontrar en la landing page una sección con un video sobre el equipo detrás del startup, para conocer quiénes son, su experiencia y la visión que impulsa el producto.</td>
      <td>
        <strong>Escenario 1:</strong> Dado que un usuario se encuentra en la landing page, cuando se desplaza hasta la sección "Video About the Team", entonces el sistema muestra un reproductor de video central con un título inspirador (ej. "Conoce al equipo que hace esto posible") y una breve descripción del propósito del equipo.<br><br>
        <strong>Escenario 2:</strong> Dado que un usuario quiere conocer más sobre las personas detrás del producto, cuando hace clic en el video para reproducirlo, entonces el sistema muestra el contenido en alta calidad, con controles de reproducción (pausa, subtítulos, pantalla completa) y, al finalizar, ofrece la opción de ver perfiles breves de los integrantes o enlaces a redes profesionales (ej. LinkedIn).
      </td>
      <td>EP-006</td>
    </tr>
    <tr>
      <td>US-026</td>
      <td>Visualización de Misión y Visión del startup</td>
      <td>Como usuario, quiero ver una sección en la landing page con la Misión y Visión del startup para conocer más a detalle los objetivos del proyecto.</td>
      <td>
        <strong>Escenario 1:</strong> Dado un usuario en la landing page del startup, cuando hace clic en la sección "Nuestra Propuesta" en el menú principal, entonces el sistema muestra la Misión y Visión de la empresa en un diseño claro y conciso, con iconos representativos y texto destacado que comunica el propósito y los objetivos a largo plazo.<br><br>
        <strong>Escenario 2:</strong> Dado un visitante interesado en los valores del startup, cuando se desplaza hasta el pie de página de la landing page, entonces el sistema presenta un resumen de la Misión y Visión junto con los principios fundamentales de la empresa, permitiendo al usuario comprender la esencia del proyecto de forma rápida.
      </td>
      <td>EP-006</td>
    </tr>
    <tr>
      <td>US-027</td>
      <td>Testimonios de usuarios previos</td>
      <td>Como usuario interesado en el producto, quiero ver testimonios reales de clientes en la landing page, para poder confiar en la efectividad de la solución antes de probar el sistema.</td>
      <td>
        <strong>Escenario 1:</strong> Dado un usuario en la landing page, cuando se desplaza hasta la sección "Experiencias de Usuarios", entonces el sistema muestra al menos tres testimonios verificados con foto, nombre, ubicación y calificación por estrellas, junto con una descripción breve de su experiencia usando el sistema.<br><br>
        <strong>Escenario 2:</strong> Dado un usuario interesado en conocer opiniones específicas, cuando hace clic en el botón "Ver más testimonios" en la sección designada, entonces el sistema redirige a una página dedicada con filtros por tipo de motocicleta, tiempo de uso del sistema y tipo de servicio evaluado.
      </td>
      <td>EP-006</td>
    </tr>
    <tr>
      <td>US-028</td>
      <td>Sección de Video About the Product</td>
      <td>Como usuario, quiero encontrar en la landing page una sección con un video explicativo del producto, para entender de manera rápida y visual cómo funciona y qué beneficios me ofrece.</td>
      <td>
        <strong>Escenario 1:</strong> Dado un usuario en la landing page, cuando se desplaza hasta la sección "Video About the Product", entonces el sistema muestra un video central en un reproductor embebido, acompañado de un título atractivo y una breve descripción introductoria.<br><br>
        <strong>Escenario 2:</strong> Dado un usuario interesado en más detalles, cuando hace clic en el video para reproducirlo, entonces el sistema muestra el contenido en alta calidad, con controles de reproducción (pausa, subtítulos, pantalla completa) y la opción de ver testimonios o casos de uso relacionados al final del video.
      </td>
      <td>EP-006</td>
    </tr>
    <tr>
      <td>TS-001</td>
      <td>Configuración de autenticación y autorización con JWT para proteger los endpoints del sistema</td>
      <td>Como desarrollador, quiero implementar un sistema de autenticación y autorización basado en JSON Web Tokens (JWT) en el backend, para asegurar que solo los usuarios autorizados puedan acceder a los endpoints protegidos de la aplicación.</td>
      <td>
        <strong>Escenario 1:</strong> Dado que un usuario intenta acceder a un endpoint protegido sin un token válido, cuando realiza la petición, entonces el sistema devuelve un error 401 Unauthorized.<br><br>
        <strong>Escenario 2:</strong> Dado que un usuario inicia sesión correctamente y obtiene un token JWT válido, cuando utiliza ese token en el encabezado de autorización para acceder a un endpoint protegido, entonces el sistema permite el acceso y devuelve la respuesta correspondiente.
      </td>
      <td>EP-007</td>
    </tr>
    <tr>
      <td>TS-002</td>
      <td>Configuración de validación de datos en backend</td>
      <td>Como desarrollador, quiero implementar validaciones con Spring Boot Validation en los endpoints, para asegurar que los datos ingresados por los usuarios cumplan con los formatos y restricciones necesarias (ej. emails válidos, campos obligatorios, longitudes mínimas).</td>
      <td>
        <strong>Escenario 1:</strong> Dado que un usuario envía un formulario con un campo obligatorio vacío, cuando la petición llega al backend, entonces el sistema devuelve un error con un mensaje indicando que el campo es obligatorio.<br><br>
        <strong>Escenario 2:</strong> Dado que un usuario envía un email con un formato incorrecto en el registro, cuando el backend procesa la solicitud, entonces el sistema rechaza la solicitud y devuelve un mensaje indicando que el formato del correo no es válido.
      </td>
      <td>EP-007</td>
    </tr>
    <tr>
      <td>TS-003</td>
      <td>Documentación de la API con Swagger</td>
      <td>Como desarrollador, quiero integrar Swagger/OpenAPI en el backend con Spring Boot, para que los endpoints estén documentados automáticamente y puedan ser probados fácilmente desde una interfaz gráfica.</td>
      <td>
        <strong>Escenario 1:</strong> Dado que un desarrollador accede a la URL /swagger-ui.html, cuando la interfaz de Swagger se carga, entonces el sistema muestra la documentación de todos los endpoints disponibles en el backend.<br><br>
        <strong>Escenario 2:</strong> Dado que un desarrollador necesita probar un endpoint de la API, cuando utiliza el botón "Try it out" en Swagger UI, entonces el sistema ejecuta la petición y muestra la respuesta en pantalla.
      </td>
      <td>EP-007</td>
    </tr>
    <tr>
      <td>TS-004</td>
      <td>Configuración de CORS en backend</td>
      <td>Como desarrollador, quiero configurar las políticas de CORS en Spring Boot, para permitir que el frontend (Angular) y el backend (Spring) se comuniquen correctamente en entornos de desarrollo y producción.</td>
      <td>
        <strong>Escenario 1:</strong> Dado que el frontend en Angular se encuentra en un dominio distinto al backend, cuando realiza una petición al servidor, entonces el sistema permite la comunicación siempre que el origen esté autorizado en la configuración de CORS.<br><br>
        <strong>Escenario 2:</strong> Dado que una aplicación no autorizada intenta consumir un endpoint del backend, cuando realiza la petición desde un dominio no permitido, entonces el sistema bloquea la solicitud y devuelve un error CORS policy: No 'Access-Control-Allow-Origin' header.
      </td>
      <td>EP-007</td>
    </tr>
  </tbody>
</table>


### 3.3 Product Backlog

| Orden | Código US | Título                                               | Story Points |
|-------|-----------|------------------------------------------------------|--------------|
| 1     | US-001    | Registro de usuario                                  | 5            |
| 2     | US-002    | Inicio de sesión (Authentication)                    | 3            |
| 3     | US-004    | Creación de grupos                                   | 5            |
| 4     | US-005    | Ingreso a grupos                                     | 5            |
| 5     | US-005    | Invitación a grupos                                  | 5            |
| 6     | US-007    | Creación de trabajos con fechas límite               | 5            |
| 7     | US-008    | Recepción de entregas (múltiples oportunidades)      | 8            |
| 8     | US-010    | Calificación de entregas                             | 5            |
| 9     | US-009    | Visualización de trabajos y fechas                   | 5            |
| 10    | US-015    | Acceso a todas las entregas de un trabajo            | 5            |
| 11    | TS-001    | Configuración de autenticación y autorización con JWT| 8            |
| 12    | TS-002    | Configuración de validación de datos en backend      | 5            |
| 13    | TS-003    | Configuración de CORS en backend                     | 3            |
| 14    | TS-004    | Documentación de la API con Swagger                  | 3            |
| 15    | US-013    | Visualización de métricas globales de desempeño del grupo | 8         |
| 16    | US-021    | Compartir recursos educativos                        | 8            |
| 17    | US-024    | Redirección al aplicativo web                        | 1            |
| 18    | US-026    | Visualización de Misión y Visión del startup         | 2            |
| 19    | US-028    | Sección de Video About the Product                   | 2            |
| 20    | US-025    | Sección de Video About the Team                      | 2            |
| 21    | US-027    | Testimonios de usuarios previos                      | 3            |


### 3.4 Impact Mapping  

El Impact Mapping de LearnHive permite conectar los objetivos estratégicos de la startup con las acciones concretas de los usuarios. Para ello, se definieron Business Goals bajo criterios SMART, vinculados a los User Personas identificados (profesor y estudiante). A partir de estos actores se establecieron los Impacts, que describen los cambios de comportamiento esperados para alcanzar cada meta. Posteriormente, se definieron los Deliverables, que representan las funcionalidades clave que la plataforma debe ofrecer, y finalmente las User Stories, que detallan en lenguaje de usuario las acciones específicas que habilitan dichos entregables. 

Este enfoque asegura que cada funcionalidad desarrollada esté alineada con una meta de negocio clara y con necesidades reales de los usuarios, fortaleciendo la adopción de la plataforma y su impacto en la gestión académica. 

<img src="./assets/chapter-3/Impact Map LearnHive.png" alt="Impact Map LearnHive" width="600"/>

## Capítulo IV: Product Design  

### 4.1 Style Guidelines  
#### 4.1.1 General Style Guidelines  
#### 4.1.2 Web Style Guidelines  
#### 4.1.3 Mobile Style Guidelines  
##### 4.1.3.1 iOS Mobile Style Guidelines  
##### 4.1.3.2 Android Mobile Style Guidelines  

### 4.2 Information Architecture  
#### 4.2.1 Organization Systems  
#### 4.2.2 Labeling Systems  
#### 4.2.3 SEO Tags and Meta Tags  
#### 4.2.4 Searching Systems  
#### 4.2.5 Navigation Systems  

### 4.3 Landing Page UI Design  
#### 4.3.1 Landing Page Wireframe  
#### 4.3.2 Landing Page Mock-up  

### 4.4 Mobile Applications UX/UI Design  
#### 4.4.1 Mobile Applications Wireframes  
#### 4.4.2 Mobile Applications Wireflow Diagrams  
#### 4.4.3 Mobile Applications Mock-ups  
#### 4.4.4 Mobile Applications User Flow Diagrams  

### 4.5 Mobile Applications Prototyping  
#### 4.5.1 Android Mobile Applications Prototyping  
#### 4.5.2 iOS Mobile Applications Prototyping  

### 4.6 Web Applications UX/UI Design  
#### 4.6.1 Web Applications Wireframes  
#### 4.6.2 Web Applications Wireflow Diagrams  
#### 4.6.3 Web Applications Mock-ups  
#### 4.6.4 Web Applications User Flow Diagrams  

### 4.7 Web Applications Prototyping  

### 4.8 Domain-Driven Software Architecture  
#### 4.8.1 Software Architecture Context Diagram  
#### 4.8.2 Software Architecture Container Diagrams  
#### 4.8.3 Software Architecture Components Diagrams  

### 4.9 Software Object-Oriented Design  
#### 4.9.1 Class Diagrams  
#### 4.9.2 Class Dictionary  

### 4.10 Database Design  
#### 4.10.1 Relational/Non-Relational Database Diagram  


## Capítulo V: Product Implementation  

### 5.1 Software Configuration Management  
#### 5.1.1 Software Development Environment Configuration  
#### 5.1.2 Source Code Management  
#### 5.1.3 Source Code Style Guide & Conventions  
#### 5.1.4 Software Deployment Configuration  

### 5.2 Product Implementation & Deployment  
#### 5.2.1 Sprint Backlogs  
#### 5.2.2 Implemented Landing Page Evidence  
#### 5.2.3 Implemented Frontend-Web Application Evidence  
#### 5.2.4 Acuerdo de Servicio - SaaS  
#### 5.2.5 Implemented Native-Mobile Application Evidence  
#### 5.2.6 Implemented RESTful API and/or Serverless Backend Evidence  
#### 5.2.7 RESTful API Documentation  
#### 5.2.8 Team Collaboration Insights  

### 5.3 Video About-the-Product  


# Part II: Verification, Validation & Pipeline  

## Capítulo VI: Product Verification & Validation  

### 6.1 Testing Suites & Validation  
#### 6.1.1 Core Entities Unit Tests  
#### 6.1.2 Core Integration Tests  
#### 6.1.3 Core Behavior-Driven Development  
#### 6.1.4 Core System Tests  

### 6.2 Static Testing & Verification  
#### 6.2.1 Static Code Analysis  
##### 6.2.1.1 Coding Standard & Code Conventions  
##### 6.2.1.2 Code Quality & Code Security  
#### 6.2.2 Reviews  

### 6.3 Validation Interviews  
#### 6.3.1 Diseño de Entrevistas  
#### 6.3.2 Registro de Entrevistas  
#### 6.3.3 Evaluaciones según heurísticas  

### 6.4 Auditoría de Experiencias de Usuario  
#### 6.4.1 Auditoría realizada  
##### 6.4.1.1 Información del grupo auditado  
##### 6.4.1.2 Cronograma de auditoría realizada  
##### 6.4.1.3 Contenido de auditoría realizada  
#### 6.4.2 Auditoría recibida  
##### 6.4.2.1 Información del grupo auditor  
##### 6.4.2.2 Cronograma de auditoría recibida  
##### 6.4.2.3 Contenido de auditoría recibida  
##### 6.4.2.4 Resumen de modificaciones para subsanar hallazgos  


## Capítulo VII: DevOps Practices  

### 7.1 Continuous Integration  
#### 7.1.1 Tools and Practices  
#### 7.1.2 Build & Test Suite Pipeline Components  

### 7.2 Continuous Delivery  
#### 7.2.1 Tools and Practices  
#### 7.2.2 Stages Deployment Pipeline Components  

### 7.3 Continuous Deployment  
#### 7.3.1 Tools and Practices  
#### 7.3.2 Production Deployment Pipeline Components  

### 7.4 Continuous Monitoring  
#### 7.4.1 Tools and Practices  
#### 7.4.2 Monitoring Pipeline Components  
#### 7.4.3 Alerting Pipeline Components  
#### 7.4.4 Notification Pipeline Components  


# Part III: Experiment-Driven Lifecycle  

## Capítulo VIII: Experiment-Driven Development  

### 8.1 Experiment Planning  
#### 8.1.1 As-Is Summary  
#### 8.1.2 Raw Material: Assumptions, Knowledge Gaps, Ideas, Claims  
#### 8.1.3 Experiment-Ready Questions  
#### 8.1.4 Question Backlog  
#### 8.1.5 Experiment Cards  

### 8.2 Experiment Design  
#### 8.2.1 Hypotheses  
#### 8.2.2 Domain Business Metrics  
#### 8.2.3 Measures  
#### 8.2.4 Conditions  
#### 8.2.5 Scale Calculations and Decisions  
#### 8.2.6 Methods Selection  
#### 8.2.7 Data Analytics: Goals, KPIs and Metrics Selection  
#### 8.2.8 Web and Mobile Tracking Plan  

### 8.3 Experimentation  
#### 8.3.1 To-Be User Stories  
#### 8.3.2 To-Be Product Backlog  
#### 8.3.3 Pipeline-supported, Experiment-Driven To-Be Software Platform Lifecycle  
##### 8.3.3.1 To-Be Sprint Backlogs  
##### 8.3.3.2 Implemented To-Be Landing Page Evidence  
##### 8.3.3.3 Implemented To-Be Frontend-Web Application Evidence  
##### 8.3.3.4 Implemented To-Be Native-Mobile Application Evidence  
##### 8.3.3.5 Implemented To-Be RESTful API and/or Serverless Backend Evidence  
##### 8.3.3.6 Team Collaboration Insights  
#### 8.3.4 To-Be Validation Interviews  
##### 8.3.4.1 Diseño de Entrevistas  
##### 8.3.4.2 Registro de Entrevistas  

### 8.4 Experiment Aftermath & Analysis  
#### 8.4.1 Analysis and Interpretation of Results  
#### 8.4.2 Re-scored and Re-prioritized Question Backlog  

### 8.5 Continuous Learning  
#### 8.5.1 Shareback Session Artifacts: Learning Workflow  

### 8.6 To-Be Software Platform Pre-launch  
#### 8.6.1 About-the-Product Intro Video  


# Conclusiones  
## Conclusiones y recomendaciones  
## Video App Validation  
## Video About-the-Team  


# Bibliografía  


# Anexos  
