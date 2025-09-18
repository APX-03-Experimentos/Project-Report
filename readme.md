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

| Epic ID | Título                                                    | Descripción |
|---------|------------------------------------------------------------|-------------|
| EP-001  | Gestión de Grupos                                          | Esta épica se enfoca en ofrecer a profesores y estudiantes una forma sencilla y estructurada de crear y administrar grupos académicos. El docente tiene la capacidad de formar equipos, asignar integrantes y mantener un control organizado sobre su composición. Los estudiantes, por su parte, cuentan con un espacio definido para integrarse a sus grupos de trabajo, lo que fomenta la colaboración y la coordinación en sus actividades académicas. |
| EP-002  | Gestión de trabajos y entregas                             | Esta épica se enfoca en las funcionalidades orientadas a la creación de trabajos académicos para cada grupo, y el recibimiento de entregas, así como la calificación de estas. Por parte de los estudiantes, estos deben poder visualizar sus trabajos pendientes tanto en el menú de un grupo específico como en un menú especializado general que les muestre sus fechas de entrega más cercanas. Por el lado de los profesores, estos deben poder crear trabajos con fechas límite, administrar su visualización y acceder a las entregas de sus alumnos, así como calificarlas y dejar mensajes de retroalimentación. |
| EP-003  | Seguimiento de progreso y retroalimentación automatizada   | Esta épica se centra en ofrecer funcionalidades que permitan a estudiantes y profesores acceder a datos en tiempo real sobre el rendimiento académico. Los estudiantes podrán visualizar sus calificaciones, avances y métricas comparativas mediante dashboards gráficos, lo que les permitirá identificar fortalezas, debilidades y áreas de mejora. Además, contarán con retroalimentación automatizada e instantánea, generada a partir de sus entregas y participación, para orientar su aprendizaje de manera continua. Por el lado de los profesores, estos podrán monitorear tanto las métricas individuales de cada estudiante como el desempeño general del grupo, identificando patrones y detectando a tiempo las dificultades más comunes. |
| EP-004  | Comunicación, interacción y recursos educativos dinámicos  | Esta épica se orienta al intercambio de información y la creación de espacios de interacción dentro de la plataforma. Los profesores podrán publicar anuncios dirigidos a todo el grupo, en los cuales los alumnos podrán dejar comentarios, consultas o dudas que serán respondidas en el mismo hilo. Tanto docentes como estudiantes recibirán notificaciones automáticas que les mantendrán al tanto de las respuestas e interacciones. Asimismo, los alumnos tendrán la posibilidad de enviarse mensajes privados para coordinar actividades académicas de manera ágil. Como valor agregado, la épica incorpora la posibilidad de compartir recursos educativos interactivos tales como videos cortos, imágenes y materiales en tiempo real, lo que no solo mejora la comunicación, sino que también hace más atractivo y participativo el proceso de aprendizaje. |
| EP-005  | Diseño de la landing page                                  | Como equipo de desarrollo, queremos diseñar y construir una landing page atractiva, informativa y fácil de navegar, que comunique claramente el valor de la plataforma tanto para motociclistas como para mecánicos, con el objetivo de captar nuevos usuarios, generar confianza y facilitar el registro en el sistema. |
| EP-006  | Infraestructura técnica, escalabilidad y calidad del sistema | Esta épica se enfoca en las tareas técnicas necesarias para asegurar el correcto funcionamiento de la plataforma desde el punto de vista tecnológico. Incluye configuraciones de backend, frontend, infraestructura y pruebas automatizadas, que no son visibles directamente para el usuario final pero que resultan fundamentales para garantizar seguridad, rendimiento, estabilidad, escalabilidad y mantenibilidad en el tiempo. |

User Stories:

| User Story ID | Título                                              | Descripción | Criterios de Aceptación | Relacionado con (Epic ID) |
|---------------|------------------------------------------------------|-------------|--------------------------|---------------------------|
| US-001        | Ingreso a grupos                                     | Como estudiante, quiero ser capaz de unirme a los grupos formados por mis profesores con facilidad. | **Escenario 1:** Dado un estudiante con un código válido, cuando lo ingresa y selecciona "Unirse al grupo", entonces el sistema valida, confirma y lo añade al grupo. <br><br> **Escenario 2:** Dado un estudiante con una notificación de invitación, cuando la acepta, entonces el sistema lo añade al grupo y actualiza la lista de miembros. | EP-001 |
| US-002        | Creación de grupos                                   | Como profesor, quiero ser capaz de crear grupos para mis cursos en la plataforma. | **Escenario 1:** Dado un profesor autenticado, cuando selecciona "Crear Nuevo Grupo" y llena el formulario, entonces el sistema crea el grupo. <br><br> **Escenario 2:** Dado un profesor creando un grupo con nombre duplicado, cuando intenta guardar, entonces el sistema muestra error "Nombre de grupo ya existente". | EP-001 |
| US-003        | Invitación a grupos                                  | Como profesor, quiero ser capaz de invitar a mis alumnos a los grupos creados por mí. | **Escenario 1:** Dado un código válido, cuando un estudiante lo ingresa, entonces se añade al grupo y se notifica al profesor. <br><br> **Escenario 2:** Dado un profesor que envía invitaciones por ID/correo, entonces los estudiantes reciben notificaciones con enlace directo. <br><br> **Escenario 3:** Dado un estudiante con invitación, cuando la acepta, entonces el sistema lo añade al grupo y notifica al profesor. | EP-001 |
| US-004        | Eliminación de alumnos                               | Como profesor, quiero ser capaz de eliminar integrantes del grupo para mantener el orden. | **Escenario 1:** Dado un profesor en la gestión de integrantes, cuando elimina un estudiante, entonces el sistema lo remueve y notifica. <br><br> **Escenario 2:** Dado un intento de eliminar un estudiante inexistente, cuando confirma, entonces el sistema muestra error "El estudiante no pertenece al grupo". | EP-001 |
| US-005        | Creación de trabajos con fechas límite               | Como profesor, quiero crear trabajos con fechas de entrega claras. | **Escenario 1:** Dado un profesor en un curso, cuando crea un trabajo con título, descripción y fecha futura, entonces el sistema lo guarda y notifica a estudiantes. <br><br> **Escenario 2:** Dado un profesor que ingresa una fecha anterior, entonces el sistema muestra error "La fecha de entrega debe ser futura". | EP-002 |
| US-006        | Recepción de entregas (múltiples oportunidades)      | Como estudiante, quiero poder enviar y reenviar mis entregas antes del plazo. | **Escenario 1:** Dado un estudiante dentro del plazo, cuando sube un archivo, entonces el sistema registra la entrega y notifica. <br><br> **Escenario 2:** Dado un estudiante con entrega previa, cuando reemplaza el archivo, entonces el sistema guarda la nueva versión y mantiene historial. <br><br> **Escenario 3:** Dado un estudiante fuera de plazo, cuando intenta enviar, entonces el sistema rechaza y muestra "Plazo de entrega vencido". | EP-002 |
| US-007        | Visualización de trabajos y fechas                   | Como estudiante, quiero ver todos mis trabajos y fechas de entrega. | **Escenario 1:** Dado un estudiante en un curso, cuando abre "Trabajos", entonces ve la lista con estado, fechas y progreso. <br><br> **Escenario 2:** Dado un estudiante en su dashboard, cuando abre "Próximas entregas", entonces ve una lista consolidada ordenada por urgencia. <br><br> **Escenario 3:** Dado un trabajo con menos de 24h, cuando el estudiante lo ve, entonces se resalta en rojo y se ofrece acceso directo. | EP-002 |
| US-008        | Visualización de dashboard de progreso académico     | Como estudiante, quiero ver un dashboard con calificaciones y progreso en tiempo real. | **Escenario 1:** Dado un estudiante, cuando accede a "Mi Progreso", entonces ve gráficos de calificaciones, promedios y proyección final. <br><br> **Escenario 2:** Dado un profesor que publica notas, cuando el estudiante recarga, entonces el sistema actualiza métricas y notifica cambios. <br><br> **Escenario 3:** Dado un estudiante con bajo rendimiento, entonces el sistema destaca esas materias con indicadores de color. | EP-003 |
| US-009        | Comparación del rendimiento con el promedio del grupo | Como estudiante, quiero comparar mi rendimiento con el promedio de mis compañeros. | **Escenario 1:** Dado un estudiante, cuando selecciona "Comparar con grupo", entonces ve un gráfico de barras con diferencias porcentuales. <br><br> **Escenario 2:** Dado un estudiante, cuando selecciona "Evolución Temporal", entonces ve una gráfica de líneas con su progreso vs promedio grupal. | EP-003 |
| US-010        | Visualización de métricas globales de desempeño del grupo | Como profesor, quiero acceder a métricas globales para evaluar el desempeño del grupo. | **Escenario 1:** Dado un profesor en gestión de grupo, cuando abre "Métricas Globales", entonces ve promedio, desviación, entregas a tiempo y tasas de aprobación. <br><br> **Escenario 2:** Dado un profesor que selecciona un período, entonces ve gráficas de progreso colectivo: distribución de notas, tendencia temporal y heatmap de entregas. | EP-003 |
| US-011        | Alertas sobre estudiantes con bajo rendimiento | Como profesor, quiero recibir alertas sobre estudiantes con bajo rendimiento, para poder intervenir de manera temprana. | **Escenario 1:** Dado un estudiante con notas <60% en 3 evaluaciones seguidas, cuando el sistema procesa resultados, entonces el profesor recibe notificación con detalles y sugerencias. <br><br> **Escenario 2:** Dado un estudiante que no entrega 2 tareas consecutivas, cuando el sistema analiza historial, entonces genera alerta automática con opción de contactar al estudiante. | EP-003 |
| US-012        | Recordatorios y notificaciones de entregas | Como estudiante, quiero recibir notificaciones y recordatorios de próximas entregas para no olvidar subir mis trabajos. | **Escenario 1:** Dado un trabajo con fecha límite, cuando faltan 48 y 12 horas, entonces el sistema envía notificaciones con enlace directo. <br><br> **Escenario 2:** Dado un estudiante que entrega un trabajo, cuando el sistema verifica el archivo, entonces confirma con comprobante, correo y estado "Entregado". | EP-004 |
| US-013        | Reentrega controlada                      | Como estudiante, quiero poder reentregar una tarea dentro de un plazo definido para mejorar mi nota. | **Escenario 1:** Dado un trabajo con reentregas permitidas, cuando el estudiante sube una nueva versión en plazo, entonces se reemplaza el archivo y se guarda historial. <br><br> **Escenario 2:** Dado un estudiante intentando reentregar fuera de plazo, cuando sube archivo, entonces el sistema bloquea y muestra "Plazo de reentrega vencido". | EP-002 |
| US-014        | Historial de calificaciones               | Como estudiante, quiero consultar el historial de calificaciones de mis entregas para ver mi evolución. | **Escenario 1:** Dado un estudiante, cuando accede a "Historial de Calificaciones", entonces ve una tabla con todas sus notas por curso, fecha, tipo de trabajo y ponderación. <br><br> **Escenario 2:** Dado un estudiante, cuando filtra por curso, entonces el sistema muestra una gráfica de evolución con promedios y tendencia. | EP-002 |
| US-015        | Acceso a todas las entregas de un trabajo | Como profesor, quiero acceder a todas las entregas en una sola vista para agilizar la revisión. | **Escenario 1:** Dado un profesor en "Entregas", cuando abre un trabajo, entonces ve lista completa de estudiantes con estado, archivos y tiempos. <br><br> **Escenario 2:** Dado un profesor, cuando aplica filtros (pendientes, calificados, etc.), entonces la vista se actualiza dinámicamente. | EP-002 |
| US-016        | Publicación de anuncios con comentarios   | Como profesor, quiero publicar anuncios en el curso y permitir comentarios de estudiantes. | **Escenario 1:** Dado un profesor, cuando crea un anuncio, entonces se publica en el feed, se marca prioritario y se notifica a estudiantes. <br><br> **Escenario 2:** Dado un anuncio con comentarios habilitados, cuando un estudiante comenta, entonces el sistema lo muestra con autor, foto y tiempo. <br><br> **Escenario 3:** Dado un anuncio reciente, cuando el profesor lo edita o cierra comentarios, entonces el sistema marca "Editado" y desactiva comentarios nuevos. | EP-004 |
| US-017        | Mensajería privada entre miembros         | Como estudiante, quiero enviar mensajes privados a compañeros y profesores para coordinar actividades. | **Escenario 1:** Dado un estudiante en "Miembros del Curso", cuando envía mensaje privado, entonces se crea un hilo y confirma envío. <br><br> **Escenario 2:** Dado un hilo existente, cuando el destinatario lee mensajes, entonces cambia estado a "leído" y notifica al remitente. <br><br> **Escenario 3:** Dado un estudiante que intenta escribir a alguien fuera de sus cursos, cuando envía, entonces el sistema bloquea y muestra error. | EP-004 |
| US-018        | Compartir recursos educativos             | Como profesor, quiero subir materiales de apoyo para que los estudiantes los consulten. | **Escenario 1:** Dado un profesor, cuando sube recurso con metadatos, entonces se guarda y publica con permisos de acceso. <br><br> **Escenario 2:** Dado un recurso publicado, cuando un estudiante lo descarga/visualiza, entonces se permite y se registra acceso. <br><br> **Escenario 3:** Dado un recurso actualizado, cuando el profesor sube nueva versión, entonces se conserva historial y se notifica. | EP-004 |
| US-019        | Extensión de plazo de entrega             | Como profesor, quiero extender la fecha límite de un trabajo en casos especiales. | **Escenario 1:** Dado un trabajo con fecha, cuando el profesor modifica y guarda nueva fecha, entonces el sistema actualiza registros, confirma y guarda historial. <br><br> **Escenario 2:** Dado un trabajo con fecha extendida, cuando se confirma, entonces el sistema notifica automáticamente a los estudiantes. | EP-002 |
| US-020        | Estados de entrega                        | Como estudiante, quiero ver el estado de mis entregas para saber en qué punto están. | **Escenario 1:** Dado un estudiante en "Mis Entregas", cuando abre un trabajo, entonces ve estado con iconos/colores y fecha de actualización. <br><br> **Escenario 2:** Dado un profesor calificando, cuando actualiza estado, entonces el cambio se refleja en el estudiante. <br><br> **Escenario 3:** Dado un cambio de estado, cuando ocurre, entonces el sistema notifica al estudiante. | EP-002 |
| US-021        | Redirección al aplicativo web                        | Como usuario, quiero que exista un botón en la landing page que me redirija al dashboard del aplicativo web del sistema, para acceder a este sin tener que buscar otro enlace. | **Escenario 1:** Dado un usuario en la landing page de la startup, cuando hace clic en el botón "Acceder al Dashboard" ubicado en el header de la página, entonces el sistema redirige automáticamente a la URL del aplicativo web, abriendo la página de Inicio de Sesión. <br><br> **Escenario 2:** Dado un usuario que ya ha iniciado sesión previamente en el aplicativo web, cuando accede a la landing page y hace clic en el botón "Dashboard", entonces el sistema verifica las credenciales almacenadas y redirige directamente al dashboard principal sin requerir un nuevo inicio de sesión. | EP-005 |
| US-022        | Sección de Video About the Team                      | Como usuario, quiero encontrar en la landing page una sección con un video sobre el equipo detrás de la startup, para conocer quiénes son, su experiencia y la visión que impulsa el producto. | **Escenario 1:** Dado que un usuario se encuentra en la landing page, cuando se desplaza hasta la sección "Video About the Team", entonces el sistema muestra un reproductor de video central con un título inspirador y una breve descripción del propósito del equipo. <br><br> **Escenario 2:** Dado que un usuario quiere conocer más sobre las personas detrás del producto, cuando hace clic en el video para reproducirlo, entonces el sistema muestra el contenido en alta calidad con controles de reproducción y, al finalizar, ofrece la opción de ver perfiles breves de los integrantes o enlaces a redes profesionales. | EP-005 |
| US-023        | Visualización de Misión y Visión                     | Como usuario, quiero ver una sección en la landing page con la Misión y Visión de la startup para conocer más a detalle los objetivos del proyecto. | **Escenario 1:** Dado un usuario en la landing page de la startup, cuando hace clic en la sección "Nuestra Propuesta" en el menú principal, entonces el sistema muestra la Misión y Visión de la empresa en un diseño claro y conciso. <br><br> **Escenario 2:** Dado un visitante interesado en los valores de la startup, cuando se desplaza hasta el pie de página de la landing page, entonces el sistema presenta un resumen de la Misión y Visión junto con los principios fundamentales de la empresa. | EP-005 |
| US-024        | Testimonios de usuarios previos                      | Como usuario interesado en el producto, quiero ver testimonios reales de clientes en la landing page, para poder confiar en la efectividad de la solución antes de probar el sistema. | **Escenario 1:** Dado un usuario en la landing page, cuando se desplaza hasta la sección "Experiencias de Usuarios", entonces el sistema muestra al menos tres testimonios verificados con foto, nombre, ubicación y calificación por estrellas. <br><br> **Escenario 2:** Dado un usuario interesado en conocer opiniones específicas, cuando hace clic en el botón "Ver más testimonios", entonces el sistema redirige a una página dedicada con filtros por tipo de motocicleta, tiempo de uso del sistema y tipo de servicio evaluado. | EP-005 |
| US-025        | Sección de Video About the Product                   | Como usuario, quiero encontrar en la landing page una sección con un video explicativo del producto, para entender de manera rápida y visual cómo funciona y qué beneficios me ofrece. | **Escenario 1:** Dado un usuario en la landing page, cuando se desplaza hasta la sección "Video About the Product", entonces el sistema muestra un video central en un reproductor embebido, acompañado de un título atractivo y una breve descripción introductoria. <br><br> **Escenario 2:** Dado un usuario interesado en más detalles, cuando hace clic en el video para reproducirlo, entonces el sistema muestra el contenido en alta calidad con controles de reproducción y la opción de ver testimonios o casos de uso relacionados al final del video. | EP-005 |
| TS-001        | Configuración de autenticación y autorización con JWT | Como desarrollador, quiero implementar un sistema de autenticación y autorización basado en JSON Web Tokens (JWT) en el backend, para asegurar que solo los usuarios autorizados puedan acceder a los endpoints protegidos de la aplicación. | **Escenario 1:** Dado que un usuario intenta acceder a un endpoint protegido sin un token válido, cuando realiza la petición, entonces el sistema devuelve un error 401 Unauthorized. <br><br> **Escenario 2:** Dado que un usuario inicia sesión correctamente y obtiene un token JWT válido, cuando utiliza ese token en el encabezado de autorización para acceder a un endpoint protegido, entonces el sistema permite el acceso y devuelve la respuesta correspondiente. | EP-006 |
| TS-002        | Configuración de validación de datos en backend       | Como desarrollador, quiero implementar validaciones con Spring Boot Validation en los endpoints, para asegurar que los datos ingresados por los usuarios cumplan con los formatos y restricciones necesarias. | **Escenario 1:** Dado que un usuario envía un formulario con un campo obligatorio vacío, cuando la petición llega al backend, entonces el sistema devuelve un error 400 Bad Request con un mensaje indicando que el campo es obligatorio. <br><br> **Escenario 2:** Dado que un usuario envía un email con un formato incorrecto en el registro, cuando el backend procesa la solicitud, entonces el sistema rechaza el request y devuelve un mensaje indicando que el formato del correo no es válido. | EP-006 |
| TS-003        | Documentación de la API con Swagger                  | Como desarrollador, quiero integrar Swagger/OpenAPI en el backend con Spring Boot, para que los endpoints estén documentados automáticamente y puedan ser probados fácilmente desde una interfaz gráfica. | **Escenario 1:** Dado que un desarrollador accede a la URL /swagger-ui.html, cuando la interfaz de Swagger se carga, entonces el sistema muestra la documentación de todos los endpoints disponibles en el backend. <br><br> **Escenario 2:** Dado que un desarrollador necesita probar un endpoint de la API, cuando utiliza el botón "Try it out" en Swagger UI, entonces el sistema ejecuta la petición y muestra la respuesta en pantalla. | EP-006 |
| TS-004        | Configuración de CORS en backend                     | Como desarrollador, quiero configurar las políticas de CORS en Spring Boot, para permitir que el frontend (Angular) y el backend (Spring) se comuniquen correctamente en entornos de desarrollo y producción. | **Escenario 1:** Dado que el frontend en Angular se encuentra en un dominio distinto al backend, cuando realiza una petición al servidor, entonces el sistema permite la comunicación siempre que el origen esté autorizado en la configuración de CORS. <br><br> **Escenario 2:** Dado que una aplicación no autorizada intenta consumir un endpoint del backend, cuando realiza la petición desde un dominio no permitido, entonces el sistema bloquea la solicitud y devuelve un error CORS policy: No 'Access-Control-Allow-Origin' header. | EP-006 |


### 3.3 Product Backlog

| Orden | Código US | Título                                               | Story Points |
|-------|-----------|-------------------------------------------------------|--------------|
| 1     | US-002    | Creación de grupos                                    | 5            |
| 2     | US-001    | Ingreso a grupos                                      | 5            |
| 3     | US-003    | Invitación a grupos                                   | 5            |
| 4     | US-005    | Creación de trabajos con fechas límite                | 5            |
| 5     | US-006    | Recepción de entregas (múltiples oportunidades)       | 8            |
| 6     | US-007    | Visualización de trabajos y fechas                    | 5            |
| 7     | US-015    | Acceso a todas las entregas de un trabajo             | 5            |
| 8     | US-004    | Eliminación de alumnos                                | 3            |
| 9     | TS-001    | Configuración de autenticación y autorización con JWT | 8            |
| 10    | TS-002    | Configuración de validación de datos en backend       | 5            |
| 11    | TS-003    | Configuración de CORS en backend                      | 3            |
| 12    | TS-004    | Documentación de la API con Swagger                   | 3            |
| 13    | US-020    | Estados de entrega                                    | 5            |
| 14    | US-013    | Reentrega controlada                                  | 5            |
| 15    | US-014    | Historial de calificaciones                           | 5            |
| 16    | US-019    | Extensión de plazo de entrega                         | 3            |
| 17    | US-008    | Visualización de dashboard de progreso académico      | 5            |
| 18    | US-009    | Comparación del rendimiento con el promedio del grupo | 5            |
| 19    | US-010    | Visualización de métricas globales de desempeño       | 8            |
| 20    | US-011    | Alertas sobre estudiantes con bajo rendimiento        | 5            |
| 21    | US-012    | Recordatorios y notificaciones de entregas            | 5            |
| 22    | US-016    | Publicación de anuncios con comentarios               | 5            |
| 23    | US-018    | Compartir recursos educativos                         | 8            |
| 24    | US-021    | Redirección al aplicativo web                         | 1            |
| 25    | US-023    | Visualización de Misión y Visión de la startup        | 2            |
| 26    | US-025    | Sección de Video About the Product                    | 2            |
| 27    | US-022    | Sección de Video About the Team                       | 2            |
| 28    | US-024    | Testimonios de usuarios previos                       | 3            |


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
