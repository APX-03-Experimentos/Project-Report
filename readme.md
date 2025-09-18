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

Antes de comenzar, es importante definir claramente los requisitos de  la página web. Esto incluye las funcionalidades que se desean ofrecer  en nuestra plataforma.

* Project Management:

  * Trello:

    Propósito de Uso: Gestión de tareas del equipo, seguimiento de actividades y organización del flujo de trabajo del proyecto.
    Ruta de Referencia/Descarga: [Trello](https://trello.com) (SaaS)

  <img src="./assets/chapter-5/trello.png" alt="Trello" width="400"/>

* Requirements Management:

  * One Drive: 

    Propósito de Uso: Redactar y compartir la documentación de requisitos funcionales y no funcionales del proyecto, permitiendo colaboración en tiempo real entre los miembros del equipo. Ruta de Referencia/Descarga: [One Drive](https://www.microsoft.com/es-es/microsoft-365/onedrive/online-cloud-storage) (SaaS)

    <img src="./assets/chapter-5/onedrive.png" alt="One Drive" width="400"/>

* Product UX/UI Design:

  * Figma

    Propósito de Uso: Diseño de wireframes, prototipos navegables y diagramas de flujo de pantallas (wireflows).
    Ruta de Referencia/Descarga: [Figma](https://www.figma.com) (SaaS)

    <img src="./assets/chapter-5/figma.png" alt="Figma" width="400"/>

* Software Development:

  * GitHub (con GitFlow)

    Propósito de Uso: Control de versiones, colaboración entre desarrolladores, organización mediante ramas y almacenamiento del código y documentación.
    Ruta de Referencia/Descarga: [GitHub](https://github.com) (SaaS)

    <img src="./assets/chapter-5/github.png" alt="GitHub" width="400"/>

  * WebStorm IDE

    Propósito de Uso: Edición del código fuente del proyecto.
    Ruta de Referencia/Descarga: [WebStorm IDE](https://www.jetbrains.com/webstorm/) (SaaS)

    <img src="./assets/chapter-5/webstorm.png" alt="Web Storm" width="400"/>

  * Postman:

    Propósito de Uso: Pruebas de APIs para verificar peticiones, respuestas y funcionamiento de los endpoints.
    Ruta de Referencia/Descarga: [Postman](https://www.postman.com/downloads/) (SaaS)

    <img src="./assets/chapter-5/postman.png" alt="Postman" width="400"/>

* Software Deployment:

  * Vercel

    Propósito de Uso: Plataforma de despliegue y hosting frontend moderno para aplicaciones web estáticas y dinámicas (JAMstack). Ofrece integración nativa con frameworks como Next.js, React, Vue, Angular y Svelte, junto con funciones serverless, edge functions y CDN 
    global para alto rendimiento.
    Ruta de Referencia/Descarga: [Fire Base](https://vercel.com)(PaaS - Plataforma como Servicio)

    <img src="./assets/chapter-5/vercel.png" alt="Vercel Logo" width="300"/>

  * GitHub Page

    Propósito de Uso: Despliegue de la landing page del proyecto, permitiendo su visualización pública desde el repositorio.
    Ruta de Referencia/Descarga: [GitHub Actions](https://pages.github.com) (SaaS)

    <img src="./assets/chapter-5/github_pages.png" alt="Github Pages" width="300"/>

  * Render

    Propósito de Uso: Plataforma en la nube para desplegar y escalar aplicaciones backend, APIs, bases de datos y servicios en segundos, con despliegues automáticos desde GitHub, SSL/TLS integrado y alta disponibilidad. Ruta de Referencia/Descarga: Render (PaaS) [Render](https://render.com/) (SaaS)

    <img src="./assets/chapter-5/render.png" alt="Render" width="400"/>

* Software Documentation:

  * Git Hub:

    Propósito de Uso: Almacenamiento, versionado y colaboración en la documentación del proyecto, así como la gestión del repositorio que contiene la documentación.
    Ruta de Referencia/Descarga: [Git Hub](https://github.com) (SaaS)

    <img src="./assets/chapter-5/github.png" alt="GitHub" width="400"/>

  * Visual Studio Code:

    Propósito de Uso: Edición de archivos Markdown y documentación técnica relacionada al proyecto. Se utiliza para estructurar y organizar la documentación de forma eficiente. Ruta de Referencia/Descarga: [Visual Studio Code](https://code.visualstudio.com/download) (SaaS)

  <img src="./assets/chapter-5/visual_studio_code.png" alt="Visual Studio Code" width="400"/>

  Con esta configuración, nuestro equipo puede colaborar de manera eficiente y gestionar el ciclo de vida completo del desarrollo del producto digital, desde la planificación hasta el despliegue y mantenimiento.


#### 5.1.2 Source Code Management  

En esta sección, nuestro equipo establece los medios y el esquema de  organización que aplicará para el seguimiento de modificaciones  utilizando GitHub como plataforma y sistema de control de versiones.  De esta manera, configuramos un repositorio remoto en GitHub para  almacenar el código fuente y colaborar con los compañeros del grupo.

* Plataforma de control de versiones:
  De esta manera, configuramos un repositorio remoto en GitHub para  almacenar el código fuente y colaborar con los compañeros del grupo.  Los URLs de los repositorios son los siguientes:

  * Landing Page : `https://github.com/APX-03-Experimentos/Landing-Page`
  * Frontend Web Applications : `https://github.com/APX-03-Experimentos/Frontend-Web-Applications`
  * Backend Web Services : `https://github.com/APX-03-Experimentos/Backend-Web-Services`

* Implementación de GitFlow:
  Organizamos el repositorio en ramas para diferentes entornos.

  * Ramas base:

    - Main branch (rama principal): Contiene la versión de producción.
    - Develop branch: Contiene el código en desarrollo, que eventualmente  será fusionado en la rama principal.

  * Feature branches:

    * Feature branch:

      Para cada funcionalidad nueva se crea una rama desde develop.Convención para el nombre: `feature/nombre-corto-descriptivo`

  * Release branches:

    - Release branch:

      Se crean cuando el proyecto está listo para pasar a producción, desde develop.
      Convención: `release/x.y.z` (usando versionado semántico)

  * Hotfix branches:

    * Hotfix branch:

      Se crean desde `main` para corregir errores críticos en producción.
      Convención: `hotfix/x.y.z`

* Versionado semántico (Semantic Versioning)

  - Semantic Versioning Format:

    Aplicamos semantic versioning para nombrar nuestras releases siguiendo  el esquema MAJOR.MINOR.PATCH

    <table cellspacing="0" cellpadding="8">
      <thead>
        <tr>
          <th>Parte</th>
          <th>Significado</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td><strong>MAJOR</strong></td>
          <td>Cambios importantes que rompen la compatibilidad con versiones anteriores (por ejemplo, eliminas funciones o cambias APIs que otros ya usaban).</td>
        </tr>
        <tr>
          <td><strong>MINOR</strong></td>
          <td>Añades nuevas funcionalidades de forma compatible (sin romper lo que ya funciona).</td>
        </tr>
        <tr>
          <td><strong>PATCH</strong></td>
          <td>Solucionas errores o bugs, sin agregar nuevas funciones ni romper nada.</td>
        </tr>
      </tbody>
    </table>

* Mensajes de commit con Conventional Commits

  Utilizamos Conventional Commits para los mensajes en nuestros commits. Usando el siguiente template:

  `<tipo>(<opcional-alcance>): <mensaje>`

  - Tipos:

  `feat`: nueva funcionalidad

  `fix`: corrección de errores

  `docs`: cambios en la documentación

  `style`: cambios de estilo/formato (sin afectar funcionalidad)

  `refactor`: reestructuración del código (sin cambios funcionales)

  `test`: añadir o modificar pruebas

  `chore`: tareas de mantenimiento

  * Ejemplos:

    feat(auth): Added auth

    fix(landing): fix landing header

#### 5.1.3 Source Code Style Guide & Conventions  

El equipo ha definido las siguientes convenciones de nombres y estilos de codificación, aplicadas en los lenguajes **HTML, CSS, JavaScript, TypeScript y Java**. Todas las nomenclaturas están en **inglés**, buscando claridad, estandarización y buenas prácticas de desarrollo. Se han adoptado guías de estilo reconocidas y actualizadas para cada tecnología.

**HTML**

- **Guía adoptada**: W3C HTML Style Guide (`https://www.w3.org/TR/html5/`)
- **Nomenclatura y convenciones**:
  - Minúsculas para etiquetas y atributos: `<div class="container">`
  - Indentación: 2 espacios.
  - Atributos entre comillas dobles: `<img src="logo.png" alt="Company Logo">`
  - Uso semántico de etiquetas: `<header>`, `<section>`, `<footer>`
  - Comentarios HTML: `<!-- This is a comment -->`

**CSS**

- **Guía adoptada**: Google HTML/CSS Style Guide (`https://google.github.io/styleguide/htmlcssguide.html`)
- **Nomenclatura y convenciones**:
  - `kebab-case` para clases e IDs:
    Ejemplo: `.main-header`, `#footer-section`
  - Agrupación de estilos por componente.
  - Evitar `!important` a menos que sea necesario.
  - Indentación: 2 espacios.

**JavaScript**

- **Guía adoptada**: Google JavaScript Style Guide (`https://google.github.io/styleguide/jsguide.html`)
- **Nomenclatura y convenciones**:
  - `camelCase` para variables y funciones:
    Ejemplo: `let userName = 'José';`, `function calculateTotal() {}`
  - `PascalCase` para clases:
    Ejemplo: `class ShoppingCart { }`
  - Evitar `snake_case`.
  - Usar `const` y `let` en lugar de `var`.
  - Comentarios:
    - Línea: `// Get user info`
    - Bloque:
      ```js
      /**
       * Calculates total price with tax.
       */
      function calculateTotal() {}
      ```

**TypeScript**

- **Guía adoptada**: Google TypeScript Style Guide (`https://google.github.io/styleguide/tsguide.html`)
- **Nomenclatura y convenciones**:
  - `camelCase` para variables, funciones y propiedades:
    Ejemplo: `let isActive: boolean = true;`, `function getUserData() {}`
  - `PascalCase` para clases, interfaces, enums y tipos:
    Ejemplo: `class ProductItem {}`, `interface UserDTO {}`, `enum Status { Active, Inactive }`
  - Tipado estricto (`strict: true`) habilitado.
  - Interfaces nombradas con sufijo `DTO` o `Props`.
  - Uso de modificadores `readonly`, `private`, `public`.

**Java**

- **Guía adoptada**: Google Java Style Guide (`https://google.github.io/styleguide/javaguide.html`)
- **Nomenclatura y convenciones**:
  - `PascalCase` para clases:
    Ejemplo: `public class OrderService {}`
  - `camelCase` para variables, métodos y atributos:
    Ejemplo: `int totalAmount;`, `calculateTotalPrice();`
  - Constantes en MAYÚSCULAS con `snake_case`:
    Ejemplo: `public static final int MAX_USERS = 100;`
  - Comentarios tipo Javadoc:
    ```java
    /**
     * Gets the total price of all items.
     * @return total price
     */
    public double getTotalPrice() {}
    ```
  - Paquetes en minúsculas separados por punto:
    Ejemplo: `com.project.backend.controller`

Adicionalmente hemos considerado tener convenciones para los siguientes apartados:

**Gherkin Conventions for Readable Specifications**

- **Guía adoptada**: Gherkin Syntax and Conventions (`https://cucumber.io/docs/gherkin/reference/`)
- **Nomenclatura y convenciones**:
  - **Estructura**:
    - **Given**: Define el contexto o el estado inicial.
    - **When**: Define la acción o evento que ocurre.
    - **Then**: Define el resultado o la expectativa después de la acción.
  - Ejemplo:
    ```gherkin
    Feature: User login
      Scenario: Successful login with valid credentials
        Given the user is on the login page
        When the user enters valid credentials
        Then the user should be redirected to the dashboard
    ```
  - **Uso de tablas** para datos:
    Ejemplo:
    ```gherkin
    Given the following users exist:
      | username | password |
      | user1    | pass123  |
      | user2    | pass456  |
    ```

**Angular Coding Style Guide**

- **Guía adoptada**: Angular Style Guide (`https://angular.io/guide/styleguide`)
- **Nomenclatura y convenciones**:
  - **Estructura de carpetas**:
    - `app/` para componentes, servicios y módulos.
    - `assets/` para imágenes, fuentes y otros recursos.
  - **Nombres de clases**: `PascalCase` para componentes, servicios y directivas.
    Ejemplo: `export class UserProfileComponent { }`
  - **Componentes Standalone**: Usar `standalone: true` en la declaración de `@Component`.
  - **Indentación**: 2 espacios.
  - **Uso de `trackBy` en `*ngFor`**: Para mejorar el rendimiento al iterar sobre listas grandes.
  - **Servicios**: `camelCase` para nombres de funciones y métodos.

**Spring Boot Features**

- **Guía adoptada**: Spring Boot Features (`https://spring.io/projects/spring-boot`)
- **Nomenclatura y convenciones**:
  - **Paquetes**: El paquete raíz debe ser el nombre del proyecto, seguido de subpaquetes para organización.
    Ejemplo: `com.projectname.backend`
  - **Clases y métodos**: Usar `PascalCase` para clases y `camelCase` para métodos y variables.
  - **Configuración**: Usar `@Value` para inyectar propiedades desde archivos `application.properties`.
  - **Controladores**:
    Ejemplo:
    ```java
    @RestController
    @RequestMapping("/api/users")
    public class UserController {
      @GetMapping("/{id}")
      public ResponseEntity<User> getUser(@PathVariable Long id) {
        // Logic
      }
    }
    ```
  - **Logging**: Usar `@Slf4j` para la integración de `SLF4J` en clases de servicios y controladores.

#### 5.1.4 Software Deployment Configuration  

Esta sección describe la configuración y los pasos necesarios para realizar el despliegue exitoso de los diferentes productos digitales en la solución. A continuación se especifican los pasos para desplegar la **Landing Page en GitHub Pages**, el **Frontend Web Application en Firebase** y los **Web Services Backend en Render**.

**Despliegue de la Landing Page en GitHub Pages**

Consideraciones previas al despliegue:

- Asegurarse de que todos los archivos de la Landing Page estén implementados correctamente en HTML, CSS y JavaScript.

- Se permite el uso de distintos formatos de imagen como .jpg, .png, .webp, entre otros.

- Contar con un repositorio público en GitHub con los permisos adecuados para la edición y despliegue del sitio.

- El repositorio debe pertenecer a una organización compartida entre los miembros del equipo para permitir la colaboración y control de versiones.


Pasos de despliegue:

1. **Preparar el repositorio**:

   - Asegúrate de que tu código de la Landing Page esté en el repositorio correcto de GitHub.
   - El repositorio debe contener todos los archivos estáticos necesarios (HTML, CSS, JavaScript, imágenes, etc.).

   <img src="./assets/chapter-5/landing_deployment1.png" alt="Landing Deployment" width="700"/>

2. **Configurar GitHub Pages**:

   - En el repositorio de GitHub, ve a la pestaña **Settings**.
   - En la sección **Pages**, selecciona la rama que deseas usar para desplegar el sitio. Generalmente, se usa la rama `main` o `gh-pages` (si se tiene una rama específica para ello).
   - En la opción **Source**, selecciona la carpeta del proyecto (usualmente `root` o `docs` si es necesario) y confirma la configuración.

   <img src="./assets/chapter-5/landing_deployment2.png" alt="Landing Deployment" width="700"/>

3. **Desplegar**:

   - Una vez configurado, GitHub generará una URL en la sección **GitHub Pages** (por ejemplo, `https://tu-usuario.github.io/tu-repositorio`).
   - El despliegue se realizará automáticamente con cada cambio realizado en la rama seleccionada, siempre y cuando se realicen **commits** que actualicen el repositorio.

   <img src="./assets/chapter-5/landing_deployment3.png" alt="Landing Deployment" width="700"/>

4. **Verificación**:

   - Accede a la URL proporcionada por GitHub Pages y verifica que el sitio esté funcionando correctamente.

   <img src="./assets/chapter-5/landing_deployment4.png" alt="Landing Deployment" width="700"/>


**Despliegue de la Frontend Web Application en Vercel**

Pasos de despliegue:

1. **Crearnos una cuenta en Vercel al vincularla con nuestro GitHub**:

   - Al entrar a la pagina de Vercel podemos observar que nos muestra distintas opciones para logearnos.
   - Seleccionar la opcion "Continue with GitHub".

2. **Crear un nuevo proyecto**:

   - Al redireccionarnos a "Overview" le daremos click en la opcion "Add New".
   - En el desplegable seleccionamos "Project".

3. **Importar un repositorio de git**:

   - En este momento para importar nuestros repositorios seleccionamos "Continue with GitHub" (previamente tener un fork con la rama /release que genere un repositorio).
   - Seleccionamos el repositorio que queremos deployar.

4. **Deployar el repositorio**:

   - Al momento de seleccionar el repositorio a deployar nos saldran distintas opciones en pantalla.
   - Verificaremos que estamos en la rama correcta con el estado "forked".
   - Si deseamos le damos un nombre y hacemos click en el boton inferior "Deploy".

5. **Verificación**:

   - Si te da un error como un desborde respecto a "maximumError" modificalo desde bugdet en el angular.json.
   - Volver a deployar el proyecto.

**Despliegue de los Web Services (Backend) en Render**

Consideraciones previas: 

- Tener el proyecto Spring Boot empaquetado en un archivo JAR (asegúrate de que pom.xml incluye el plugin de Spring Boot Maven). 

- Verificar que el JAR se ejecute localmente con java -jar tu-proyecto.jar. 

- Tener un repositorio de GitHub con el código del proyecto (incluyendo el pom.xml y el JAR en /target si lo empaquetaste localmente, pero Render lo genera automáticamente). 

- Configurar variables de entorno (ej: bases de datos, puertos, claves) en Render, nunca en el código.

Pasos de despliegue: 

1. Preparar el repositorio de GitHub Asegúrate de que tu repositorio tenga: 

- pom.xml (configuración de Maven). 
- src/ (código fuente). 
- README.md (instrucciones). 

No subir el archivo JAR (Render lo construye automáticamente). 

2. Crear cuenta en Render 

  a. Ve a `https://render.com.`

  b. Regístrate con tu cuenta de GitHub (recomendado para integración). 
 

3. Crear un Web Service 

  a. En el dashboard de Render, haz clic en "New +" y selecciona "Web Service". 

  b. Conecta tu cuenta de GitHub si no lo has hecho. 
 

4. Vincular el repositorio Selecciona el repositorio de tu proyecto Spring Boot. 

  a. Seleccionar el repositorio correcto a deployar. 
 

5. Configurar el servicio 

  a. Name: Ej: mi-api-springboot (será parte de la URL). 

  b. Environment: Elige "Java" (Render detectará automáticamente Maven o Gradle). 

  c. Branch: Rama a desplegar (ej: main). 

  d. Root Directory: Deja vacío si el proyecto está en la raíz del repositorio. 

  e. Build Command: Render usa por defecto: 
  - mvn clean install 

  f. Start Command: 
  - java -jar target/*.jar 

(Asegúrate de que el JAR se genera en target/ con el nombre correcto).

6. Configurar variables de entorno  

  a. Agrega las variables que tu aplicación necesita: 

    - PORT: Render lo asigna automáticamente, pero Spring Boot debe usarlo (como en el paso previo). 

    - DATABASE_URL: URL de tu base de datos (si usas PostgreSQL en Render o externa). 

    - JWT_SECRET, API_KEYS, etc. 

OJO: Nunca subir application.properties con valores sensibles a GitHub. 

7. Desplegar 

  a. Haz clic en "Create Web Service". 

  b. Render construirá el JAR con Maven y luego lo ejecutará. 

  c. Revisa los logs en tiempo real para detectar errores. 
 

8. Verificar el despliegue 

  a. Al finalizar, Render asignará una URL a tu API: 
  `https://mi-api-springboot.onrender.com` (ejemplo) 

  b. Prueba los endpoints: 
  curl `https://mi-api-springboot.onrender.com/api/health`

  c. Si hay errores, revisa los logs en la pestaña "Logs" de Render. 

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

Lugar donde se desplega nuestra landing page: 

<img src="./assets/chapter-5/landing_evidence1.png" alt="Landing Page Evidence" width="700"/>

Hero Section:

<img src="./assets/chapter-5/landing_evidence2.png" alt="Landing Page Evidence" width="700"/>

ABOUT THE PRODUCT:

<img src="./assets/chapter-5/landing_evidence3.png" alt="Landing Page Evidence" width="700"/>

ABOUT THE TEAM:

<img src="./assets/chapter-5/landing_evidence4.png" alt="Landing Page Evidence" width="700"/>

MISIÓN Y VISIÓN:

<img src="./assets/chapter-5/landing_evidence5.png" alt="Landing Page Evidence" width="700"/>

COMENTARIOS:

<img src="./assets/chapter-5/landing_evidence6.png" alt="Landing Page Evidence" width="700"/>

CALL TO ACCION Y FOOTER:

<img src="./assets/chapter-5/landing_evidence7.png" alt="Landing Page Evidence" width="700"/>

#### 5.2.3 Implemented Frontend-Web Application Evidence

VISTA DE INICIO DE SESIÓN:

<img src="./assets/chapter-5/frontend_evidence1.png" alt="Frontend-Web Application Evidence" width="700"/>

VISTA DE REGISTRO: 

<img src="./assets/chapter-5/frontend_evidence2.png" alt="Frontend-Web Application Evidence" width="700"/>

VISTA PANEL DEL PROFESOR:

<img src="./assets/chapter-5/frontend_evidence3.png" alt="Frontend-Web Application Evidence" width="700"/>

VISTA PANEL DE  TAREAS:

<img src="./assets/chapter-5/frontend_evidence4.png" alt="Frontend-Web Application Evidence" width="700"/>

VISTA PANEL DEL ESTUDIANTE:

<img src="./assets/chapter-5/frontend_evidence5.png" alt="Frontend-Web Application Evidence" width="700"/>


#### 5.2.4 Implemented Native-Mobile Application Evidence  
#### 5.2.5 Implemented RESTful API and/or Serverless Backend Evidence

Se desarrolló y documentó la implementación de una API RESTful y/o un backend que permite gestionar las operaciones principales del sistema (creación, consulta, actualización y eliminación de datos) 

<img src="./assets/chapter-5/backend_evidence1.png" alt="Backend Evidence" width="700"/>

User entidad que gestiona autenticación y perfil de usuario en el backend

<img src="./assets/chapter-5/backend_evidence2.png" alt="Backend Evidence" width="700"/>

Submission: registro de la entrega de una tarea. 

<img src="./assets/chapter-5/backend_evidence3.png" alt="Backend Evidence" width="700"/>

Assignments tarea académica creada por el profesor con fecha límite y criterios de evaluación, Authentication proceso de validación de identidad.

<img src="./assets/chapter-5/backend_evidence4.png" alt="Backend Evidence" width="700"/>

Courses conjuntos académicos donde se organizan estudiantes, profesores, tareas y recursos dentro del sistema.

<img src="./assets/chapter-5/backend_evidence5.png" alt="Backend Evidence" width="700"/>

#### 5.2.6 RESTful API Documentation

<table>
  <thead>
    <tr>
      <th>Tag</th>
      <th>Verbo HTTP</th>
      <th>Endpoint</th>
      <th>Summary</th>
      <th>Description</th>
      <th>OperationId</th>
      <th>Parameters</th>
      <th>Request body</th>
    </tr>
  </thead>
  <tbody>
    <!-- USERS -->
    <tr><td>Users</td><td>GET</td><td>/api/v1/users</td><td>List</td><td>Get all users</td><td>users_list</td><td>-</td><td>no</td></tr>
    <tr><td>Users</td><td>PUT</td><td>/api/v1/users</td><td>Update</td><td>Update a user</td><td>users_update</td><td>-</td><td>yes</td></tr>
    <tr><td>Users</td><td>GET</td><td>/api/v1/users/{userId}</td><td>Get</td><td>Get a user by ID</td><td>users_get_by_id</td><td>{userId}</td><td>no</td></tr>
    <tr><td>Users</td><td>DELETE</td><td>/api/v1/users/{userId}</td><td>Delete</td><td>Delete a user</td><td>users_delete</td><td>{userId}</td><td>no</td></tr>
    <tr><td>Users</td><td>GET</td><td>/api/v1/users/me</td><td>Get</td><td>Get current authenticated user</td><td>users_get_me</td><td>-</td><td>no</td></tr>
    <tr><td>Users</td><td>GET</td><td>/api/v1/users/group/{courseId}</td><td>List</td><td>Get users by course ID</td><td>users_by_course</td><td>{courseId}</td><td>no</td></tr>
    <tr><td>Users</td><td>GET</td><td>/api/v1/users/email/{userName}</td><td>Get</td><td>Get a user by user name</td><td>users_get_by_username</td><td>{userName}</td><td>no</td></tr>
    <tr><td>Users</td><td>DELETE</td><td>/api/v1/users/leave/{courseId}</td><td>Delete</td><td>Leave a course</td><td>users_leave_course</td><td>{courseId}</td><td>no</td></tr>
    <!-- SUBMISSIONS -->
    <tr><td>Submissions</td><td>GET</td><td>/api/v1/submissions/{submissionId}</td><td>Get</td><td>Get a submission by ID</td><td>submissions_get_by_id</td><td>{submissionId}</td><td>no</td></tr>
    <tr><td>Submissions</td><td>PUT</td><td>/api/v1/submissions/{submissionId}</td><td>Update</td><td>Update a submission</td><td>submissions_update</td><td>{submissionId}</td><td>yes</td></tr>
    <tr><td>Submissions</td><td>DELETE</td><td>/api/v1/submissions/{submissionId}</td><td>Delete</td><td>Delete a submission</td><td>submissions_delete</td><td>{submissionId}</td><td>no</td></tr>
    <tr><td>Submissions</td><td>PUT</td><td>/api/v1/submissions/{submissionId}/grade</td><td>Update</td><td>Grade a submission</td><td>submissions_grade</td><td>{submissionId}</td><td>yes</td></tr>
    <tr><td>Submissions</td><td>GET</td><td>/api/v1/submissions</td><td>List</td><td>Get all submissions</td><td>submissions_list</td><td>-</td><td>no</td></tr>
    <tr><td>Submissions</td><td>POST</td><td>/api/v1/submissions</td><td>Create</td><td>Create a new submission</td><td>submissions_create</td><td>-</td><td>yes</td></tr>
    <tr><td>Submissions</td><td>GET</td><td>/api/v1/submissions/students/{studentId}/assignments/{assignmentId}</td><td>Get</td><td>Get submissions by studentId and assignmentId</td><td>submissions_by_student_assignment</td><td>{studentId}, {assignmentId}</td><td>no</td></tr>
    <tr><td>Submissions</td><td>GET</td><td>/api/v1/submissions/student/{studentId}</td><td>List</td><td>Get submissions by studentId</td><td>submissions_by_student</td><td>{studentId}, {courseId}</td><td>no</td></tr>
    <tr><td>Submissions</td><td>GET</td><td>/api/v1/submissions/student/{studentId}/group/{courseId}</td><td>List</td><td>Get submissions by studentId and courseId</td><td>submissions_by_student_course</td><td>{studentId}, {courseId}</td><td>no</td></tr>
    <tr><td>Submissions</td><td>GET</td><td>/api/v1/submissions/course/{courseId}</td><td>List</td><td>Get submissions by courseId</td><td>submissions_by_course</td><td>{courseId}</td><td>no</td></tr>
    <tr><td>Submissions</td><td>GET</td><td>/api/v1/submissions/assignment/{assignmentId}</td><td>List</td><td>Get submissions by assignmentId</td><td>submissions_by_assignment</td><td>{assignmentId}</td><td>no</td></tr>
    <!-- COURSES -->
    <tr><td>Courses</td><td>GET</td><td>/api/v1/courses/{id}</td><td>Get</td><td>Get course by ID</td><td>courses_get_by_id</td><td>{id}</td><td>no</td></tr>
    <tr><td>Courses</td><td>PUT</td><td>/api/v1/courses/{id}</td><td>Update</td><td>Update a course</td><td>courses_update</td><td>{id}</td><td>yes</td></tr>
    <tr><td>Courses</td><td>DELETE</td><td>/api/v1/courses/{id}</td><td>Delete</td><td>Delete a course</td><td>courses_delete</td><td>{id}</td><td>no</td></tr>
    <tr><td>Courses</td><td>PUT</td><td>/api/v1/courses/{courseId}/join-code</td><td>Update</td><td>Set course join</td><td>courses_set_join_code</td><td>{courseId}</td><td>yes</td></tr>
    <tr><td>Courses</td><td>GET</td><td>/api/v1/courses</td><td>List</td><td>Get all courses</td><td>courses_list</td><td>-</td><td>no</td></tr>
    <tr><td>Courses</td><td>POST</td><td>/api/v1/courses</td><td>Create</td><td>Create a course</td><td>courses_create</td><td>-</td><td>yes</td></tr>
    <tr><td>Courses</td><td>GET</td><td>/api/v1/courses/teacher</td><td>List</td><td>Get courses by teacher ID</td><td>courses_by_teacher</td><td>-</td><td>no</td></tr>
    <tr><td>Courses</td><td>GET</td><td>/api/v1/courses/student</td><td>List</td><td>Get courses by student ID</td><td>courses_by_student</td><td>-</td><td>no</td></tr>
    <tr><td>Courses</td><td>GET</td><td>/api/v1/courses/join/{key}</td><td>Join</td><td>Join a course via join code</td><td>courses_join</td><td>{key}</td><td>no</td></tr>
    <tr><td>Courses</td><td>DELETE</td><td>/api/v1/courses/{courseId}/students/{studentId}</td><td>Delete</td><td>Kick student from course</td><td>courses_kick_student</td><td>{courseId}, {studentId}</td><td>no</td></tr>
    <!-- ASSIGNMENTS -->
    <tr><td>Assignments</td><td>GET</td><td>/api/v1/assignments/{assignmentId}</td><td>Get</td><td>Get assignment by ID</td><td>assignments_get_by_id</td><td>{assignmentId}</td><td>no</td></tr>
    <tr><td>Assignments</td><td>PUT</td><td>/api/v1/assignments/{assignmentId}</td><td>Update</td><td>Update an existing assignment</td><td>assignments_update</td><td>{assignmentId}</td><td>yes</td></tr>
    <tr><td>Assignments</td><td>POST</td><td>/api/v1/assignments/{assignmentId}</td><td>Delete</td><td>Delete an assignment</td><td>assignments_delete</td><td>{assignmentId}</td><td>no</td></tr>
    <tr><td>Assignments</td><td>GET</td><td>/api/v1/assignments</td><td>List</td><td>Get all assignments</td><td>assignments_list</td><td>-</td><td>no</td></tr>
    <tr><td>Assignments</td><td>POST</td><td>/api/v1/assignments</td><td>Create</td><td>Create a new assignment</td><td>assignments_create</td><td>-</td><td>yes</td></tr>
    <tr><td>Assignments</td><td>GET</td><td>/api/v1/assignments/course/{courseId}</td><td>List</td><td>Get assignments by course ID</td><td>assignments_by_course</td><td>{courseId}</td><td>no</td></tr>
    <!-- AUTHENTICATION -->
    <tr><td>Authentication</td><td>POST</td><td>/api/v1/authentication/sign-up</td><td>Sign-up</td><td>Register new user</td><td>auth_sign_up</td><td>-</td><td>yes</td></tr>
    <tr><td>Authentication</td><td>POST</td><td>/api/v1/authentication/sign-in</td><td>Sign-in</td><td>Sign in user</td><td>auth_sign_in</td><td>-</td><td>yes</td></tr>
    <tr><td>Authentication</td><td>OPTIONS</td><td>/api/v1/authentication/**</td><td>Options</td><td>Authentication options (CORS support)</td><td>auth_options</td><td>-</td><td>no</td></tr>
    <tr><td>Roles</td><td>GET</td><td>/api/v1/roles</td><td>List</td><td>Get all roles</td><td>roles_list</td><td>-</td><td>no</td></tr>
  </tbody>
</table>

#### 5.2.7 Team Collaboration Insights

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
