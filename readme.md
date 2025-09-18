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

En esta parte, daremos a conocer nuestra propuesta para el diseño, estilo y aspecto visual tanto de la página web como de las secciones de nuestra aplicación. Buscamos ofrecer a los usuarios una experiencia cómoda y sencilla mediante una interfaz clara e intuitiva. Para ello, seleccionamos cuidadosamente elementos visuales que resulten atractivos y agradables, además de definir límites que nos permitan evitar el uso de gráficos que puedan afectar negativamente la estética. 

#### 4.1.1 General Style Guidelines 

**Branding**

Elegimos un logo distintivo y elegante que representa la esencia de nuestra plataforma como un entorno educativo. Utilizamos la estructura de colmena como símbolo de colaboración y construcción colectiva del conocimiento, mientras que las letras en cursiva evocan la educación tradicional y el aprendizaje humano. La estética de líneas limpias y geométricas aporta un aire técnico y moderno, y el color azul transmite confianza, profesionalismo y serenidad. En conjunto, el logo refleja un espacio donde la comunidad crece unida, compartiendo y generando conocimiento como en una colmena activa.

<img src="./assets/chapter-4/logo.png" alt="Logo" width="400"/>

**Tipografía**

Open Sans ha sido seleccionada como la fuente principal para todos los textos de la aplicación. Esta tipografía se distingue por su excelente legibilidad y su estilo moderno, lo que garantiza una experiencia de lectura clara y agradable en cualquier dispositivo. 

El tamaño de la fuente se ajusta de manera automática según la pantalla, asegurando una visualización óptima tanto en móviles como en computadoras.

<img src="./assets/chapter-4/tipografia.png" alt="Tipografia" width="400"/>

**Colores**

<img src="./assets/chapter-4/colores.png" alt="Colores" width="600"/>

Color Primario: 

Azul Cian (#1DA7F4): Este color es el más predominante en el diseño, utilizado en botones principales, resaltados visuales y líneas de separación. Aporta frescura, confianza y visibilidad, creando una experiencia amigable y dinámica para el usuario. 

Colores Secundarios:

- Azul Marino (#2C87FF): Utilizado en títulos o textos destacados. Añade contraste, profesionalismo y profundidad al diseño. 
- Azul Muy Claro (#EBF7FE): Funciona como fondo o zonas de descanso visual, aportando claridad sin perder calidez. 
- Gris Oscuro (#2B2B2B): Utilizado para tipografía y elementos de interfaz. Este color garantiza buena legibilidad. 
- Azul Suave (#A5D7F4): Aparece en elementos secundarios o de soporte, equilibrando la paleta general.

Texto:

Todos los textos utilizan el color #2B2B2B (Gris Oscuro) para asegurar un alto contraste y una lectura fluida sobre fondos claros. La tipografía empleada en toda la aplicación es Open Sans, una fuente legible, moderna y profesional.

Botones:

Los botones siguen un sistema de color funcional: 

- Botones de Acción Principal 
Fondo: #1DA7F4 (Azul Cian)
Texto: Blanco (#FFFFFF) 
Hover: El fondo se oscurece ligeramente (#1783BD) para reforzar la retroalimentación visual. 

- Botones de Acción Secundaria
Fondo: Blanco (#FFFFFF) con borde y texto en #1DA7F4
Hover: Puede invertirse el color de fondo y texto o intensificar el borde para marcar interacción. 

Formularios:

Los campos de texto siguen un diseño simple con líneas delimitadoras delgadas. 
Indicadores como el tiempo, la señal y los íconos del sistema están incluidos para crear una maqueta realista. 

Íconos y Sistema Visual:

Los íconos siguen un estilo de línea simple, usando colores oscuros (#2B2B2B) y están inspirados en la librería Vuesax. 
Están diseñados para facilitar la comprensión sin sobrecargar la interfaz. 

Estados de Hover:

Cuando el usuario interactúa con botones o íconos, los colores de fondo se intensifican levemente, mejorando la experiencia visual y confirmando la acción. 

**Espaciado y Distribución**

El diseño se basa en un sistema modular de 8px, asegurando alineación precisa y consistencia visual entre todos los elementos.

#### 4.1.2 Web Style Guidelines

Diseño: El diseño tiene que ser claro, actual y adaptable, asegurando una correcta visualización y funcionalidad en cualquier tipo de dispositivo.

<img src="./assets/chapter-4/diseño.png" alt="Diseño" width="400"/>

Botones: Los botones, tanto principales como secundarios, deben resaltar de forma clara utilizando una paleta de colores uniforme y coherente.

<img src="./assets/chapter-4/botones.png" alt="Botones" width="400"/>

Tema: La apariencia visual debe alinearse con la identidad de la aplicación, haciendo uso de los colores previamente definidos. 

<img src="./assets/chapter-4/tema.png" alt="Tema" width="400"/>

Logo: El logotipo debe ser claro y fácilmente visible en todo el sitio, conservando siempre sus proporciones originales.

<img src="./assets/chapter-4/logo.png" alt="Logo" width="400"/>

#### 4.1.3 Mobile Style Guidelines
##### 4.1.3.1 iOS Mobile Style Guidelines

Diseño: La interfaz debe respetar los principios de claridad, profundidad y deferencia de Apple. El diseño debe ser ligero, intuitivo y adaptable a distintos tamaños de pantalla y dispositivos de la gama iOS.

<img src="./assets/chapter-4/diseño_mobile.png" alt="Diseño" width="400"/>

Botones: Los botones deben seguir el estilo nativo de iOS, utilizando bordes redondeados y retroalimentación táctil clara. Los botones principales deben resaltar mediante el color primario definido en la identidad visual, mientras que los secundarios deben mantener un contraste equilibrado sin perder coherencia.

<img src="./assets/chapter-4/botones_mobile.png" alt="Botones" width="400"/>

Tema: La apariencia general debe alinearse con la identidad de la aplicación, aplicando la paleta de colores definida, tipografía recomendada y manteniendo consistencia en todos los componentes. 

<img src="./assets/chapter-4/tema_mobile.png" alt="Tema" width="400"/>

Logo: El logotipo debe presentarse siempre con alta resolución en pantallas Retina, conservando sus proporciones y asegurando suficiente contraste con el fondo en el que se muestre.

##### 4.1.3.2 Android Mobile Style Guidelines  

Diseño: La interfaz debe respetar los principios de Material Design, priorizando la claridad, jerarquía visual y la adaptabilidad a diferentes tamaños y resoluciones de pantalla. El uso de sombras, capas y transiciones debe seguir las guías de Android para ofrecer una experiencia nativa.

<img src="./assets/chapter-4/diseño_mobile.png" alt="Tema" width="400"/>

Botones: Los botones deben seguir el estilo Material, con formas rectangulares o redondeadas según el contexto. Los botones principales deben utilizar el color primario definido en la paleta, y los secundarios deben mantener coherencia con el esquema visual. Los estados de interacción (hover, pressed) deben estar claramente diferenciados. 

<img src="./assets/chapter-4/botones_mobile.png" alt="Botones" width="400"/>

Tema: La apariencia visual debe alinearse con la identidad de la aplicación, aplicando la paleta de colores definida, tipografía recomendada y manteniendo consistencia en todos los elementos.

<img src="./assets/chapter-4/tema_mobile.png" alt="Tema" width="400"/>

Logo: El logotipo debe conservar siempre sus proporciones originales y estar optimizado para pantallas de alta densidad, asegurando legibilidad y contraste en cualquier contexto.

### 4.2 Information Architecture
#### 4.2.1 Organization Systems

El sistema de organización de LearnHive se diseña en torno a dos roles principales (Profesor y Estudiante) y se aplica de forma diferente en cada uno de sus dashboards para optimizar sus flujos de trabajo específicos. 

1. Sistemas de Organización  

Esto define la estructura de las pantallas y el flujo de las tareas. 

- Organización Jerárquica (Visual Hierarchy): 

Se observa en todos los dashboards y páginas. Es fundamental para guiar la atención hacia la información más crítica. 

Ejemplos en LearnHive: 

Dashboard del Profesor (US-010, US-011): La métrica global más importante (ej: "Promedio General del Curso: 15.2") será el número más grande y prominente. Las alertas de bajo rendimiento (US-011) usarán colores rojos o amarillos intensos para destacar inmediatamente sobre el resto de la información. 

Dashboard del Estudiante (US-007, US-008): La próxima entrega más urgente (US-007, Escenario 3) tendrá un tamaño, color o icono que la haga imposible de ignorar. La calificación actual o el progreso general (US-008) será el elemento visual principal. 

- Organización Secuencial (Step-by-step): 

Procesos lineales donde el orden es crucial para completar una tarea sin errores. 

Ejemplos en LearnHive: 

Creación de un Grupo (US-002): El flujo será: 1. Hacer clic en "Crear Grupo" -> 2. Llenar formulario (nombre, descripción) -> 3. Confirmar y generar código -> 4. Invitar estudiantes. Este flujo guía al profesor sin desviaciones. 

Proceso de Entrega (US-006): El flujo para el estudiante es: 1. Seleccionar trabajo -> 2. Hacer clic en "Subir entrega" -> 3. Seleccionar archivo -> 4. Confirmar envío. Es un camino claro y sin opciones extra que lo distraigan. 

2. Esquemas de Categorización  

Esto define las "etiquetas" o metadatos que usaremos para clasificar la información. 

- Por Tópicos (o Temático): 

Todo el contenido se organiza naturalmente por Cursos o Grupos. Este es el modo de pensamiento más intuitivo para ambos usuarios ("quiero ver lo de mi curso de Matemáticas"). 

Ejemplos:  

Los trabajos (US-005), los recursos (US-018), los anuncios (US-016) y las métricas (US-008, US-010) están todos anclados a un curso específico. 

- Por Audiencia:  

Al iniciar sesión, el sistema debe redirigir al Dashboard del Profesor o al Dashboard del Estudiante basándose en el rol del usuario. La información y las herramientas presentadas serán completamente diferentes, ya que sus necesidades lo son (crear grupos vs. unirse a grupos; calificar vs. ser calificado). 

- Cronológico: 

Se aplica de forma transversal para dar contexto y urgencia. 

Ejemplos: 

Para el Estudiante (US-007): La lista de "Próximas entregas" está ordenada por fecha límite (cronológico ascendente). El historial de calificaciones (US-014) se puede ordenar por fecha. 

Para el Profesor (US-005): La lista de trabajos creados se puede ordenar por fecha de creación o de entrega. 

Comunicaciones (US-016, US-017): Los anuncios y mensajes se ordenan por fecha de envío (los más recientes primero). 

- Alfabético:

Se aplica en listas donde se necesita encontrar un nombre específico rápidamente. 

Ejemplos:  

La lista de estudiantes dentro de un grupo (US-004) puede ordenarse alfabéticamente por apellido para que el profesor encuentre a alguien fácilmente. La lista de todos los cursos de un estudiante también podría usar este orden.

#### 4.2.2 Labeling Systems

1. Etiquetado para el Flujo de Gestión de Cursos (EP-001: US-001 a US-004) El foco aquí es la acción y la pertenencia. Las etiquetas deben ser verbos directos. 

Para el Profesor: 

- Crear Grupo (US-002): Es un llamado a la acción claro. No usar "Nuevo Grupo" o "Generar Grupo", ya que son menos directos. 
- Gestionar Grupo / Miembros del Grupo: La etiqueta para la sección donde ve y edita la lista de estudiantes. 
- Invitar Estudiantes (US-003): Específico y action-oriented. No usar "Añadir Gente" que es demasiado vago. 
- Eliminar (US-004): La etiqueta para la acción de remover a un estudiante. Debe ser directa y, para confirmar, usar un mensaje modal con el texto: "¿Está seguro de que desea eliminar a [Nombre del Estudiante] de este grupo? Esta acción notificará al estudiante." 

Para el Estudiante:

- Unirse a un Grupo (US-001): Un verbo claro que describe la acción. 
- Código de Grupo: La etiqueta del campo de entrada. Debe ser idéntica al término que use el profesor. 
- Mis Grupos: La etiqueta de la sección principal donde el estudiante ve todos sus cursos. 


2. Etiquetado para el Flujo de Trabajos y Calificaciones (EP-002/EP-003: US-005 a US-015, US-019, US-020) El foco aquí es el estado, la acción y los datos. La precisión es clave para evitar ansiedad o confusión en los estudiantes. 

- Estados de Entrega (US-020): Este es quizás el etiquetado MÁS CRÍTICO. Debe ser extremadamente claro y usar colores consistentes: 
  - Pendiente (Color: Gris/Azul) - Aún no hay acción del estudiante. 
  - Entregado (Color: Verde) - El estudiante subió un archivo exitosamente. ¡Crucial para la tranquilidad del estudiante! 
  - En Revisión (Color: Amarillo/Naranja) - El profesor tiene el trabajo pero aún no lo califica. Le dice al estudiante: "Tu trabajo está siendo visto". 
  - Calificado (Color: Azul/Púrpura) - La nota está disponible. Es más profesional que "Revisado". 

- Acciones y Secciones: 
  - Trabajos o Actividades: La etiqueta de la sección principal (US-007). "Trabajos" es más común. 
  - Crear Trabajo (US-005) 
  - Subir Entrega / Reemplazar Entrega (US-006, US-013): La etiqueta del botón debe reflejar la acción exacta. 
  - Próximas Entregas (US-007): Una etiqueta mucho más efectiva que "Tareas Pendientes" porque comunica urgencia. 
  - Mi Progreso (US-008): Mejor que "Mis Notas" porque implica una trayectoria y mejora continua. 
  - Promedio del Grupo (US-009): Una etiqueta de datos clara para la comparación. 
  - Extender Plazo (US-019): La etiqueta de la acción para el profesor. 

3. Etiquetado para el Flujo de Comunicación (EP-004: US-012, US-016, US-017, US-018) El foco aquí es la claridad y la interacción. 

- Anuncios (US-016): La etiqueta para la sección de comunicaciones públicas del profesor. 
- Mensajes o Mensajería (US-017): La etiqueta para la comunicación privada. "Mensajes" es más simple y universal. 
- Recursos o Materiales (US-018): La etiqueta para la biblioteca de archivos del curso. 
- Notificaciones: La etiqueta global para el centro de alertas del sistema (US-011, US-012). 

4. Etiquetado para la Landing Page (EP-005: US-021 a US-025) El foco aquí es la conversión y la información clara para visitantes nuevos. 

- Acceder o Iniciar Sesión: Para usuarios existentes. 
- Registrarse o Comenzar: Para nuevos usuarios. 
- Dashboard: Término técnico pero ampliamente aceptado para el panel de control principal. 
- Nuestra Misión / Nuestra Visión (US-023): Etiquetas directas y standard. 
- Testimonios o Experiencias (US-024): Comunica inmediatamente que son opiniones de usuarios reales. 
- Conoce al Equipo (US-022) / Cómo Funciona (US-025): Etiquetas amigables y que invitan a hacer clic.

#### 4.2.3 SEO Tags and Meta Tags


**Landing:**

`<title>`: LearnHive by APX-4 | Plataforma de Gestión Educativa para Institutos de Lima 

`<meta name="description">`: LearnHive revoluciona la educación en Perú. Dashboard para profesores que monitorean el progreso de su clase en tiempo real y portal para estudiantes que visualizan su rendimiento. Potencia el éxito académico. 

`<meta name="keywords">`: plataforma educativa, gestión de aulas, dashboard profesores, progreso estudiantes, educación Perú, institutos Lima, analytics educativos, LearnHive, APX-4, tecnología educativa 

`<meta name="author">`: APX-4 

**Web App:**  



1. Página de Login / Acceso (Común para todos) 

`<title>`: Acceder | LearnHive - Plataforma de Gestión Educativa 

`<meta name="description">`: Inicia sesión en tu cuenta de LearnHive. Accede a tu dashboard para profesores o estudiantes y gestiona tu aprendizaje de forma integral. 

`<meta name="keywords">`: acceso learnhive, login, iniciar sesión, dashboard profesores, portal estudiantes, plataforma educativa perú 

`<meta name="author">`: APX-4 



2. Dashboard Principal del Profesor 

`<title>`: Dashboard - [Nombre del Instituto] | LearnHive para Profesores 
(Ej: Dashboard - Instituto Tecnológico Lima Norte | LearnHive para Profesores) 

`<meta name="description">`: Supervisa el progreso de tus cursos en tiempo real, crea grupos y visualiza métricas de desempeño de tu clase con el dashboard de LearnHive. 

`<meta name="keywords">`: dashboard profesor, métricas educativas, progreso del curso, gestión de aulas, analytics profesores, learnhive profesor 

`<meta name="author">`: APX-4 



3. Dashboard Principal del Estudiante 

`<title>`: Mi Progreso | LearnHive para Estudiantes 

`<meta name="description">`: Revisa tus calificaciones, próximas entregas y compara tu rendimiento con el promedio de la clase. Toma el control de tu aprendizaje con LearnHive. 

`<meta name="keywords">`: progreso académico, calificaciones estudiantes, próximas entregas, rendimiento estudiantil, learnhive estudiante 

`<meta name="author">`: APX-4 

 

4. Página de Gestión de un Grupo/Curso Específico (Profesor) 

`<title>`: Gestión - [Nombre del Curso] | LearnHive 
(Ej: Gestión - Matemáticas I | LearnHive) 

`<meta name="description">`: Gestiona el grupo de [Nombre del Curso]. Crear trabajos, invitar estudiantes, revisar entregas y publicar anuncios para tu clase. 

`<meta name="keywords">`: gestión de curso, crear trabajos, invitar estudiantes, revisar entregas, learnhive curso [nombre del curso] 

`<meta name="author">`: APX-4 



5. Página de Detalle de un Trabajo/Actividad (Estudiante) 

`<title>`: [Nombre del Trabajo] - [Nombre del Curso] | LearnHive 
(Ej: Práctica Calificada 1 - Matemáticas I | LearnHive) 

`<meta name="description">`: Entrega tu trabajo [Nombre del Trabajo] para el curso [Nombre del Curso]. Consulta la fecha límite, instrucciones y el estado de tu entrega. 

`<meta name="keywords">`: entregar trabajo, [nombre del trabajo], [nombre del curso], fecha límite, estado de entrega, learnhive actividad 

`<meta name="author">`: APX-4


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
