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
### 3.2 User Stories  
### 3.3 Product Backlog  
### 3.4 Impact Mapping  


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
Esta sección presenta las herramientas utilizadas en el entorno de desarrollo del proyecto, así como las convenciones y estrategias de control de versiones adoptadas para asegurar la calidad y consistencia del código. 

#### 5.1.1 Software Development Environment Configuration  
#### 5.1.2 Source Code Management  
#### 5.1.3 Source Code Style Guide & Conventions  
#### 5.1.4 Software Deployment Configuration  

### 5.2 Product Implementation & Deployment  
#### 5.2.1 Sprint Backlogs

El objetivo principal de este Sprint es desarrollar y consolidar las funcionalidades esenciales para la gestión de grupos académicos y la administración de tareas. Durante este ciclo, el equipo se enfocará en implementar características que permitan a los docentes y estudiantes interactuar de manera eficiente con el sistema, asegurando la creación, participación y control de grupos, así como la entrega y seguimiento de trabajos académicos.

<img src="./assets/chapter-5/sprint_backlog.png" alt="Sprint Backlog" width="700"/>

Trello Sprint 1: `https://trello.com/invite/b/68cbe53e24bea2a3c7ca052d/ATTIaa224b23f44bb2c0008bb87fd5ee6ac6044FDA57/sprint-1`

<table border="1" cellspacing="0" cellpadding="5">
  <tr>
    <th colspan="8">Sprint #1</th>
  </tr>
  <tr>
    <th colspan="2">User Story</th>
    <th colspan="6">Work-Item / Task</th>
  </tr>
  <tr>
    <th>Id</th>
    <th>Title</th>
    <th>Id</th>
    <th>Title</th>
    <th>Description</th>
    <th>Estimation (Hours)</th>
    <th>Assigned To</th>
    <th>Status (To-do / In-Process / To-Review / Done)</th>
  </tr>

  <tr><td rowspan="2">US-001</td><td rowspan="2">Ingreso a grupos</td><td>T01</td><td>Implementar validación de código</td><td>Programar lógica para validar códigos de grupo en backend</td><td>5</td><td>Omar Luquillas Asto</td><td>Done</td></tr>
  <tr><td>T02</td><td>Crear interfaz de unión a grupo</td><td>Diseñar y programar el formulario para que los estudiantes ingresen el código</td><td>4</td><td>José Antonio Alejo Cárdenas</td><td>Done</td></tr>

  <tr><td rowspan="2">US-002</td><td rowspan="2">Creación de grupos</td><td>T03</td><td>Formulario de creación</td><td>Implementar formulario con validaciones para nombre, descripción y duplicados</td><td>6</td><td>Sebastián Omar Real Calderón</td><td>Done</td></tr>
  <tr><td>T04</td><td>Guardar grupo en base de datos</td><td>Programar servicio que persista los datos del nuevo grupo</td><td>5</td><td>Eric Marlon Olivera Barzola</td><td>Done</td></tr>

  <tr><td rowspan="2">US-003</td><td rowspan="2">Invitación a grupos</td><td>T05</td><td>Generar códigos de invitación</td><td>Implementar servicio que cree códigos únicos por grupo</td><td>4</td><td>Omar Luquillas Asto</td><td>Done</td></tr>
  <tr><td>T06</td><td>Enviar invitaciones</td><td>Implementar envío de notificaciones y manejo de invitaciones en base de datos</td><td>5</td><td>José Antonio Alejo Cárdenas</td><td>Done</td></tr>

  <tr><td rowspan="2">US-004</td><td rowspan="2">Eliminación de alumnos</td><td>T07</td><td>Interfaz de gestión de miembros</td><td>Crear pantalla para mostrar y eliminar estudiantes de un grupo</td><td>6</td><td>Sebastián Omar Real Calderón</td><td>Done</td></tr>
  <tr><td>T08</td><td>Lógica de eliminación segura</td><td>Validar existencia del alumno y actualizar lista tras eliminación</td><td>5</td><td>Eric Marlon Olivera Barzola</td><td>Done</td></tr>

  <tr><td rowspan="2">US-005</td><td rowspan="2">Creación de trabajos con fechas límite</td><td>T09</td><td>Formulario de creación de tarea</td><td>Implementar formulario con campos obligatorios y validación de fecha futura</td><td>5</td><td>Omar Luquillas Asto</td><td>Done</td></tr>
  <tr><td>T10</td><td>Persistencia de trabajos</td><td>Crear endpoint para almacenar trabajos en base de datos y notificar estudiantes</td><td>6</td><td>José Antonio Alejo Cárdenas</td><td>Done</td></tr>

  <tr><td rowspan="2">US-006</td><td rowspan="2">Recepción de entregas (múltiples oportunidades)</td><td>T11</td><td>Subida de archivos</td><td>Programar servicio de subida y reemplazo de entregas</td><td>6</td><td>Sebastián Omar Real Calderón</td><td>Done</td></tr>
  <tr><td>T12</td><td>Historial de entregas</td><td>Implementar historial con marcas de tiempo y versiones</td><td>5</td><td>Eric Marlon Olivera Barzola</td><td>Done</td></tr>

  <tr><td rowspan="2">US-007</td><td rowspan="2">Visualización de trabajos y fechas</td><td>T13</td><td>Vista de trabajos por curso</td><td>Diseñar interfaz para mostrar trabajos y estados dentro de un curso</td><td>4</td><td>Omar Luquillas Asto</td><td>Done</td></tr>
  <tr><td>T14</td><td>Dashboard de próximas entregas</td><td>Programar sección consolidada de tareas pendientes con alertas</td><td>6</td><td>José Antonio Alejo Cárdenas</td><td>Done</td></tr>

  <tr><td rowspan="2">US-008</td><td rowspan="2">Visualización de dashboard de progreso académico</td><td>T15</td><td>Gráficos de calificaciones</td><td>Implementar dashboard con gráficos interactivos por curso</td><td>7</td><td>Sebastián Omar Real Calderón</td><td>Done</td></tr>
  <tr><td>T16</td><td>Actualización en tiempo real</td><td>Programar actualización automática tras nuevas calificaciones</td><td>6</td><td>Eric Marlon Olivera Barzola</td><td>Done</td></tr>

  <tr><td rowspan="2">US-009</td><td rowspan="2">Comparación con promedio del grupo</td><td>T17</td><td>Gráfico comparativo</td><td>Crear gráfico de barras entre calificaciones individuales y promedio del grupo</td><td>5</td><td>Omar Luquillas Asto</td><td>Done</td></tr>
  <tr><td>T18</td><td>Evolución temporal comparativa</td><td>Implementar gráfica de líneas para progreso histórico</td><td>6</td><td>José Antonio Alejo Cárdenas</td><td>Done</td></tr>

  <tr><td rowspan="2">US-010</td><td rowspan="2">Métricas globales del grupo</td><td>T19</td><td>Panel de métricas</td><td>Crear dashboard con promedio, tasa de entregas y comparativas</td><td>7</td><td>Sebastián Omar Real Calderón</td><td>Done</td></tr>
  <tr><td>T20</td><td>Filtros por periodo</td><td>Programar filtrado por rango de fechas o parciales</td><td>5</td><td>Eric Marlon Olivera Barzola</td><td>Done</td></tr>

  <tr><td rowspan="2">US-013</td><td rowspan="2">Reentrega controlada</td><td>T21</td><td>Validar plazo de reentrega</td><td>Implementar lógica para permitir reentregas dentro del plazo</td><td>5</td><td>Omar Luquillas Asto</td><td>Done</td></tr>
  <tr><td>T22</td><td>Historial de versiones</td><td>Guardar múltiples versiones y marcar fecha de primera entrega</td><td>4</td><td>José Antonio Alejo Cárdenas</td><td>Done</td></tr>

  <tr><td rowspan="2">US-014</td><td rowspan="2">Historial de calificaciones</td><td>T23</td><td>Tabla de calificaciones</td><td>Diseñar vista con calificaciones históricas organizadas por curso y fecha</td><td>6</td><td>Sebastián Omar Real Calderón</td><td>Done</td></tr>
  <tr><td>T24</td><td>Gráfico de evolución</td><td>Implementar gráfica de evolución temporal de notas</td><td>5</td><td>Eric Marlon Olivera Barzola</td><td>Done</td></tr>

  <tr><td rowspan="2">US-015</td><td rowspan="2">Acceso a todas las entregas de un trabajo</td><td>T25</td><td>Listado de entregas</td><td>Programar lista completa de entregas con estados y marcas de tiempo</td><td>6</td><td>Omar Luquillas Asto</td><td>Done</td></tr>
  <tr><td>T26</td><td>Filtros de entregas</td><td>Implementar filtros dinámicos para facilitar revisión</td><td>5</td><td>José Antonio Alejo Cárdenas</td><td>Done</td></tr>

  <tr><td rowspan="2">US-019</td><td rowspan="2">Extensión de plazo de entrega</td><td>T27</td><td>Modificar fecha límite</td><td>Crear opción de edición de fecha en configuración de trabajo</td><td>4</td><td>Sebastián Omar Real Calderón</td><td>Done</td></tr>
  <tr><td>T28</td><td>Notificación de actualización</td><td>Programar notificación automática de cambio de fecha a los estudiantes</td><td>5</td><td>Eric Marlon Olivera Barzola</td><td>Done</td></tr>

  <tr><td rowspan="2">US-020</td><td rowspan="2">Estados de entrega</td><td>T29</td><td>Definir estados de entrega</td><td>Implementar estados (pendiente, entregado, calificado) en base de datos</td><td>6</td><td>Omar Luquillas Asto</td><td>Done</td></tr>
  <tr><td>T30</td><td>Interfaz de estados</td><td>Mostrar estados con íconos y colores en dashboard</td><td>5</td><td>José Antonio Alejo Cárdenas</td><td>Done</td></tr>

  <tr><td rowspan="2">US-021</td><td rowspan="2">Redirección al aplicativo web</td><td>T31</td><td>Botón de acceso</td><td>Agregar botón en landing page que redirija al dashboard</td><td>3</td><td>Sebastián Omar Real Calderón</td><td>Done</td></tr>
  <tr><td>T32</td><td>Validar sesión</td><td>Programar validación de credenciales antes de redirigir</td><td>4</td><td>Eric Marlon Olivera Barzola</td><td>Done</td></tr>

  <tr><td rowspan="2">US-022</td><td rowspan="2">Sección de video About the Team</td><td>T33</td><td>Sección de video en landing</td><td>Diseñar sección con reproductor de video del equipo</td><td>5</td><td>Omar Luquillas Asto</td><td>Done</td></tr>
  <tr><td>T34</td><td>Controles del reproductor</td><td>Configurar opciones de reproducción (subtítulos, fullscreen, etc.)</td><td>4</td><td>José Antonio Alejo Cárdenas</td><td>Done</td></tr>

  <tr><td rowspan="2">US-023</td><td rowspan="2">Visualización de Misión y Visión</td><td>T35</td><td>Crear sección de misión/visión</td><td>Diseñar sección con misión, visión e íconos representativos</td><td>4</td><td>Sebastián Omar Real Calderón</td><td>Done</td></tr>
  <tr><td>T36</td><td>Integrar en footer</td><td>Mostrar resumen en pie de página con valores de la empresa</td><td>3</td><td>Eric Marlon Olivera Barzola</td><td>Done</td></tr>

  <tr><td rowspan="2">US-024</td><td rowspan="2">Testimonios de usuarios previos</td><td>T37</td><td>Sección de testimonios</td><td>Crear sección con 3 testimonios con fotos y calificaciones</td><td>5</td><td>Omar Luquillas Asto</td><td>Done</td></tr>
  <tr><td>T38</td><td>Página extendida de testimonios</td><td>Implementar vista con más testimonios y filtros</td><td>6</td><td>José Antonio Alejo Cárdenas</td><td>Done</td></tr>

  <tr><td rowspan="2">US-025</td><td rowspan="2">Video About the Product</td><td>T39</td><td>Sección de video del producto</td><td>Diseñar sección con reproductor explicativo del producto</td><td>5</td><td>Sebastián Omar Real Calderón</td><td>Done</td></tr>
  <tr><td>T40</td><td>Controles e integración extra</td><td>Configurar opciones extra y enlaces a casos de uso/testimonios</td><td>4</td><td>Eric Marlon Olivera Barzola</td><td>Done</td></tr>

  <tr><td rowspan="2">TS-001</td><td rowspan="2">Autenticación y autorización con JWT</td><td>T41</td><td>Configurar endpoints protegidos</td><td>Implementar validación de tokens en endpoints backend</td><td>6</td><td>Omar Luquillas Asto</td><td>Done</td></tr>
  <tr><td>T42</td><td>Generación de tokens JWT</td><td>Programar emisión y expiración de tokens al iniciar sesión</td><td>5</td><td>José Antonio Alejo Cárdenas</td><td>Done</td></tr>

  <tr><td rowspan="2">TS-002</td><td rowspan="2">Validación de datos en backend</td><td>T43</td><td>Reglas de validación</td><td>Implementar validaciones con anotaciones de Spring Boot</td><td>5</td><td>Sebastián Omar Real Calderón</td><td>Done</td></tr>
  <tr><td>T44</td><td>Manejo de errores de validación</td><td>Programar respuestas claras con mensajes de error 400</td><td>4</td><td>Eric Marlon Olivera Barzola</td><td>Done</td></tr>

  <tr><td rowspan="2">TS-003</td><td rowspan="2">Documentación de API con Swagger</td><td>T45</td><td>Integrar Swagger en backend</td><td>Configurar dependencia y exponer documentación de endpoints</td><td>5</td><td>Omar Luquillas Asto</td><td>Done</td></tr>
  <tr><td>T46</td><td>Probar endpoints en Swagger UI</td><td>Validar pruebas con opción "Try it out"</td><td>4</td><td>José Antonio Alejo Cárdenas</td><td>Done</td></tr>

  <tr><td rowspan="2">TS-004</td><td rowspan="2">Configuración de CORS en backend</td><td>T47</td><td>Configuración de orígenes</td><td>Permitir acceso al backend desde dominios autorizados</td><td>4</td><td>Sebastián Omar Real Calderón</td><td>Done</td></tr>
  <tr><td>T48</td><td>Bloqueo de orígenes no válidos</td><td>Implementar políticas para rechazar peticiones de dominios no permitidos</td><td>3</td><td>Eric Marlon Olivera Barzola</td><td>Done</td></tr>
</table>

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
