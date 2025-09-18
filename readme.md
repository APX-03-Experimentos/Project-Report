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

APX-4 es una startup fundada por estudiantes de la Universidad Peruana de Ciencias Aplicadas (UPC), con la misión de revolucionar la educación en el Perú mediante soluciones tecnológicas accesibles y de alto impacto. 

Nuestro producto principal, LearnHive, es una plataforma integral de análisis y gestión educativa diseñada específicamente para los institutos de Lima Metropolitana que carecen de un sistema unificado. 

Para los profesores, ofrecemos un dashboard intuitivo que les permite supervisar el estado general de sus cursos en tiempo real. Esta visión integral les facilita el monitoreo continuo del progreso del aula, asegurando que siempre tengan una visión general del estado de su clase. 

Por otro lado, para los alumnos, proporcionamos un portal de acceso seguro donde pueden visualizar sus propias estadísticas y progreso académico de forma clara y transparente, así como acceder a herramientas que les permitan organizar mejor sus actividades y tiempo. Este acceso empodera a los estudiantes, dándoles mayor control sobre su educación. 

- Misión: Potenciar el éxito académico en los institutos de Lima Metropolitana mediante una plataforma de apoyo educativo intuitiva y poderosa. Brindamos a los educadores las herramientas para tomar decisiones proactivas e impactar positivamente en el aprendizaje de cada estudiante. 

- Visión: Ser la plataforma de gestión educativa de referencia en Lima Metropolitana, reconocida por transformar el ambiente académico para un mejor desempeño. elevando la calidad de la enseñanza y convirtiendo a los institutos en centros de innovación pedagógica.

#### 1.1.2 Perfiles de integrantes del equipo  

<table>
  <tr>
    <th colspan="2"> Jose Antonio Alejo Cardenas </th>
  </tr>
  <tr>
    <td> <img src="./assets/chapter-1/jose_profile_picture.jpeg" alt="Jose Alejo" style="width: 500px; height: auto;"> </td>
    <td>Soy José Alejo Cárdenas, estudiante de Ingeniería de Software en el séptimo ciclo en la UPC, perteneciente al décimo superior. Desde pequeño he sentido fascinación por la tecnología, en especial por el desarrollo, funcionamiento y seguridad del software. Tengo formación en lenguajes de programación como Java, JavaScript, Python y C++, así como en gestión de bases de datos (Microsoft SQL Server y MongoDB). Manejo entornos de desarrollo como IntelliJ IDEA Ultimate y experiencia en sistemas operativos (Windows y Kali Linux). También cuento con conocimientos en ensamblaje y mantenimiento de hardware, comprendiendo el funcionamiento técnico de los equipos. Me caracterizo por mi comunicación efectiva, organización y trabajo colaborativo, cualidades que aportan dinamismo y sinergia en proyectos grupales. Entre mis principales intereses se encuentran el desarrollo backend con Spring Boot, la ciberseguridad y la optimización de sistemas. En lo personal, disfruto de entrenar en el gimnasio, jugar videojuegos y compartir momentos con amigos. Para el proyecto, aportaré organización, comunicación e inspiración a lo largo de todo su desarrollo. </td>
  </tr>
  <tr>
    <th colspan="2"> Sebastián Omar Real Calderón </th>
  </tr>
  <tr>
    <td> <img src="./assets/chapter-1/sebastian_profile_picture.jpeg" alt="Sebastian Real" style="width: 500px; height: auto;"> </td>
    <td> Soy Sebastián Real Calderón, estudiante de Ingeniería de Software. Tengo conocimiento de diferentes lenguajes de programación, como C#, C++ y Java. Mi mayor objetivo al desarrollar software es crear una experiencia de usuario con la que los consumidores puedan sentirse satisfechos al trabajar con nuestras aplicaciones. Asimismo, aspiro a ser un buen participante al mantener una comunicación constante con mis compañeros, resolviendo problemas y apoyando a quién lo necesite para crear un ambiente cómodo para todos.  </td>
  </tr>
  <tr>
    <th colspan="2"> Omar Luquillas Asto </th>
  </tr>
  <tr>
    <td> <img src="./assets/chapter-1/omar_profile_picture.jpg" alt="Omar Luquillas" style="width: 500px; height: auto;"> </td>
    <td> Soy Omar Luquillas Asto, estudiante de la carrera de Ingeniería de Software. Elegí esta carrera porque me apasiona la tecnología, el desarrollo de software y la programación. Tengo conocimientos en lenguajes de programación como C++, Python y Java. Me considero una persona investigadora, ya que me gusta aprender cosas nuevas y siempre estoy en busca de soluciones creativas e innovadoras que generen un impacto positivo en la vida de las personas. Además, valoro el trabajo en equipo, soy responsable y me comprometo a cumplir con mis tareas de manera eficiente.  </td>
  </tr>
  <tr>
    <th colspan="2">Eric Marlon Olivera Barzola </th>
  </tr>
  <tr>
    <td> <img src="./assets/chapter-1/eric_profile_picture.png" alt="Eric Olivera" style="width: 500px; height: auto;"> </td>
    <td>Soy Eric Marlon Olivera Barzola, estudiante de Ingeniería de Software del séptimo ciclo, con un interés particular en la ciberseguridad. A lo largo de mi formación he adquirido experiencia en diferentes lenguajes de programación como C#, C++ y Java. Me motiva desarrollar soluciones que no solo sean funcionales, sino que también transmitan confianza y seguridad a los usuarios.  </td>
  </tr>
</table>

### 1.2 Solution Profile  
#### 1.2.1 Antecedentes y problemática  

##### What / ¿QUÉ? 

¿Cuál es el problema?

El problema principal es la falta de un entorno educativo digital unificado y accesible en muchos institutos de Lima, lo que resulta en una gestión docente ineficiente (uso de herramientas dispersas como WhatsApp y correo), dificultad para centralizar y evaluar el trabajo de los estudiantes, y una incapacidad para obtener una visión clara del rendimiento académico de la clase. Esto lleva a una experiencia de aprendizaje fragmentada y reactiva, tanto para profesores como para alumnos. 

¿Cuál es la relación con la persona en cuestión? 

La relación se establece a través del instituto, que adopta LearnHive como su plataforma oficial. El profesor es nuestro usuario principal y cliente directo, ya que es quien gestiona los cursos, califica y analiza el desempeño. El profesor utiliza LearnHive para estructurar su curso, comunicarse con los estudiantes y transformar su rol de evaluador reactivo a gestor proactivo del aprendizaje. El estudiante accede a la plataforma como usuario final, encontrando un espacio centralizado para sus cursos, tareas y calificaciones, permitiéndole gestionar sus trabajos con mayor facilidad. 

##### When / ¿CUÁNDO? 

¿Cuándo sucede el problema? 

El problema ocurre diariamente durante el ciclo académico: 

Para el profesor: Al intentar organizar y publicar materiales para cada clase, al recibir decenas de entregas por diferentes canales, y al momento de calificar y consolidar esas notas manualmente en una hoja de cálculo. También surge al final del ciclo académico, cuando necesita analizar las notas para generar reportes de desempeño, un proceso que suele ser manual. 

Para el estudiante: Al no tener un lugar claro donde consultar las tareas, materiales o fechas de entrega, y al tener que enviar sus trabajos a través de medios informales que no garantizan su recepción correcta. Así como no tener una plataforma que unifique todas las funcionalidades del sistema educativo. 

¿Cuándo utiliza el cliente el producto? 

El profesor lo usa de forma constante para revisar avances, publicar anuncios y/o trabajos y calificar entregas. De la misma manera, puede ver el desempeño de sus alumnos en tiempo real con métricas que se actualizan diariamente. 

El estudiante accede a la plataforma a diario para verificar sus cursos, las tareas pendientes y los anuncios nuevos, y de manera puntual para subir sus entregas antes de la fecha límite y consultar sus calificaciones.

##### Where / ¿DÓNDE? 

¿Dónde está el cliente cuando usa el producto? 

Tanto profesores como estudiantes acceden a LearnHive principalmente desde sus dispositivos móviles y computadoras portátiles o de escritorio, desde cualquier lugar con conexión a internet: en el instituto, en sus hogares o en movimiento. 

¿Dónde surge el problema? 

El problema surge en el entorno educativo mismo: 

En la sala de profesores y el domicilio del docente, donde se invierten tiempo en organizar, calificar y compilar información de manera manual. 

En el entorno del estudiante, que se ve obligado a navegar entre múltiples apps y chats para gestionar su aprendizaje. 

##### Who / ¿QUIÉN? 

¿Quiénes se ven involucrados en el problema? 

El problema involucra directamente a los profesores y estudiantes, quienes son los más afectados por la gestión educativa desorganizada. Los profesores cargan con la pesada administración manual, mientras que los estudiantes enfrentan una experiencia de aprendizaje fragmentada. Indirectamente, los directores de los institutos y los padres de familia también se ven perjudicados, ya que carecen de acceso claro a datos sobre el rendimiento. 

¿Cuáles son las causas del problema? 

La causa fundamental del problema es una brecha digital y económica que limita el acceso a herramientas tecnológicas asequibles y fáciles de usar, junto con una falta de capacitación que genera resistencia al cambio en muchos entornos educativos. 

##### Why / ¿POR QUÉ? 

¿Por qué sucede el problema? 

Sucede porque muchos institutos de Lima carecen de los recursos financieros y técnicos para desarrollar, implementar y mantener una plataforma educativa propia y robusta. Las soluciones existentes en el mercado pueden ser demasiado costosas, genéricas o complejas para sus necesidades específicas. Esto los fuerza a depender de herramientas gratuitas pero no diseñadas para la educación (servicios de mensajería o correo electrónico), lo que genera desorganización, pérdida de información y una carga administrativa insostenible para el docente. Asi mismo, porque las plataformas actuales (ej. Google Classroom, Blackboard) están enfocadas en universidades o colegios con mayores recursos tecnológicos y no contemplan las necesidades específicas de los institutos académicos, como la simplicidad, la creación ágil de grupos con códigos de ingreso o la disponibilidad de métricas personalizadas. 

##### How / ¿CÓMO? 

¿En qué condiciones los clientes usan nuestro producto? 

Los clientes utilizan LearnHive principalmente a través de un navegador web o una aplicación móvil, dependiendo de una conexión a internet accesible. La plataforma está diseñada para ser usada de forma asíncrona, permitiendo que profesores y estudiantes interactúen con el contenido en los momentos que más les convengan. La usabilidad es fundamental, por lo que la interfaz debe ser extremadamente intuitiva para garantizar una adopción rápida y sin fricciones, minimizando la necesidad de una capacitación extensa. 

¿Cómo se diferencia el problema del estado normal (óptimo)? 

En un estado óptimo, los estudiantes y docentes deberían gestionar grupos, tareas y métricas desde una única plataforma sencilla y adaptada a sus necesidades. Actualmente, deben recurrir a múltiples aplicaciones externas, lo que genera desorganización, duplicidad de esfuerzos y pérdida de información. 

¿La tendencia en la que aparece el problema es aleatoria o sigue un patrón? 

Sigue un patrón claro: aparece en cada ciclo académico, especialmente cuando se requiere colaboración grupal o evaluaciones conjuntas. 

##### How Much / ¿CUÁNTO? 

¿Cuál es la magnitud del problema? 

La magnitud del problema para la educación en Lima es considerable, con una gestión fragmentada que impacta a miles de docentes y estudiantes. El problema surge, en gran parte, por la falta de una plataforma unificada, lo que fuerza a profesores y alumnos a depender de herramientas informales como WhatsApp. Según un estudio de la Contraloría General de la República (2022), el 56.5% de los estudiantes en colegios públicos reporta que sus profesores usan esta aplicación para impartir clases, lo que evidencia una realidad de desorganización y pérdida de información. Esta dependencia de múltiples canales no solo genera una carga administrativa insostenible para el docente, sino que también crea una experiencia de aprendizaje dispersa y reactiva para el estudiante, lo que subraya la necesidad de una solución centralizada y accesible como LearnHive. 

#### 1.2.2 Lean UX Process

El Lean UX Process es una metodología de diseño centrada en el usuario que busca trabajar de forma práctica y ágil. Su enfoque se basa en realizar ciclos cortos de creación, prueba y mejora, lo que permite validar con rapidez si una idea realmente responde a las necesidades de los usuarios.  

##### 1.2.2.1 Lean UX Problem Statements

Nuestra plataforma tiene como propósito optimizar la gestión académica y la interacción entre estudiantes y docentes de institutos en un único espacio digital. Hemos detectado que gran parte de los usuarios continúa utilizando herramientas aisladas y poco integradas, como WhatsApp, correo electrónico o carpetas en la nube, lo que complica la organización de grupos, asignaciones y entregas. Este escenario provoca desorden, desperdicio de tiempo y una comunicación menos efectiva, afectando en el desempeño de los estudiantes y aumentando la carga administrativa de los docentes. ¿Cómo podemos mejorar nuestra solución para que los estudiantes y docentes de institutos coordinen sus actividades académicas de forma más ágil, evaluando el éxito mediante una mayor participación en los grupos, un mejor cumplimiento de las tareas y una reducción del tiempo dedicado a la organización? 

##### 1.2.2.2 Lean UX Assumptions

**User Assumptions (Suposiciones de Usuario)**

- ¿Quién es el usuario?: Los usuarios principales son docentes y estudiantes de institutos de Lima Metropolitana. Los profesores buscan simplificar la gestión de cursos, centralizar entregas y contar con métricas claras de rendimiento. Los estudiantes necesitan un espacio único para organizar sus actividades, consultar tareas y visualizar su progreso académico. 

- ¿Dónde encaja nuestro producto en su trabajo o vida?: LearnHive se integra como una herramienta de uso cotidiano en el entorno académico del instituto. Para los profesores, funciona como un panel central para planificar, evaluar y dar seguimiento al rendimiento de la clase. Para los estudiantes, se convierte en el espacio digital donde concentran todas sus responsabilidades académicas. 

- ¿Qué problemas resuelve nuestro producto?: Resuelve la dispersión de herramientas informales (WhatsApp, correo, hojas de cálculo), la dificultad para consolidar información académica y la falta de indicadores accesibles para la toma de decisiones pedagógicas. 

- ¿Cuándo y cómo se usa nuestro producto?: El docente utiliza la plataforma de manera continua durante el ciclo académico: al crear grupos, publicar materiales, calificar entregas y revisar métricas de desempeño. El estudiante accede diariamente para consultar tareas, subir trabajos y verificar sus calificaciones. 

- ¿Qué características son importantes?: Las funcionalidades clave incluyen la gestión de grupos, publicación de materiales y tareas, calificación centralizada, métricas académicas en tiempo real y un portal de estudiante con acceso seguro a estadísticas personalizadas. 

- ¿Cómo debe verse y comportarse nuestro producto?: Debe tener un diseño simple, profesional e intuitivo, con tiempos de respuesta rápidos y una experiencia de navegación que minimice la curva de aprendizaje, fomentando la adopción inmediata tanto por profesores como estudiantes.

**Business Assumptions (Suposiciones de Negocio)**

- Necesidades y problemas: Los institutos requieren una plataforma accesible y adaptada a su realidad económica y tecnológica, que mejore la organización académica sin generar altos costos de implementación.

- Plataforma: Una aplicación web y móvil garantiza accesibilidad y flexibilidad en distintos entornos de uso. 

- Segmentación: El público objetivo está conformado por docentes y estudiantes de institutos académicos de Lima Metropolitana. 

- Comportamientos: Se espera que los usuarios valoren la simplicidad, la centralización de funciones y la posibilidad de contar con métricas claras y accionables. 

- Beneficios: Los usuarios obtendrán mayor organización, reducción del tiempo administrativo, mejora en la comunicación y un seguimiento más claro del rendimiento académico. 

- Captación de clientes: La estrategia de captación incluye presentaciones directas a directivos de institutos, convenios institucionales, además de difusión en redes sociales. 

- Modelos de ingresos: LearnHive se plantea como un sistema ofrecido bajo licenciamiento o suscripción a institutos, generando sostenibilidad económica para el startup. 

- Competencia: Las plataformas existentes como Google Classroom o Blackboard se dirigen a universidades y colegios con mayores recursos, lo que deja un espacio poco atendido en los institutos. 

- Ventaja competitiva: LearnHive destaca por su enfoque en la simplicidad, la adaptabilidad al contexto de los institutos y la integración de métricas personalizadas que no suelen estar disponibles en soluciones genéricas.

**Technical Assumptions (Suposiciones Técnicas)** 

- Tecnología utilizada: Se emplearán tecnologías web modernas y escalables que aseguren estabilidad y compatibilidad con navegadores y dispositivos móviles. 

- Integraciones: El sistema podrá integrarse con fuentes externas de datos o aceptar carga manual, asegurando flexibilidad para distintos niveles de digitalización institucional. 

- Escalabilidad: La infraestructura estará diseñada para crecer en usuarios y datos sin afectar la velocidad de respuesta.

**Market Assumptions (Suposiciones de Mercado)**

- Tamaño del mercado: El mercado objetivo incluye a los institutos de Lima Metropolitana que actualmente no cuentan con plataformas propias de gestión académica. 

- Competencia: Los competidores son plataformas más genéricas que no se adaptan a las necesidades específicas de los institutos. 

- Tendencias: Existe una tendencia clara hacia la digitalización de la educación en el nivel técnico y superior, impulsada por la necesidad de modernización y eficiencia en la gestión académica.

**Design Assumptions (Suposiciones de Diseño)**

- Interacción del usuario: La interfaz debe permitir una navegación sencilla y accesible para usuarios con distintos niveles de familiaridad tecnológica. 

- Experiencia del usuario: El diseño debe priorizar la claridad visual y la reducción de pasos innecesarios en cada acción. 

- Colores y tipografía: Se buscará una paleta que transmita seriedad y confianza, acompañada de tipografías modernas y legibles. 

- Preferencias visuales: El diseño debe ser atractivo, pero sin sobrecargar la vista; el enfoque debe estar en las funciones académicas principales. 

- Prototipos y pruebas: Se realizarán validaciones de las funcionalidades principales mediante pruebas de usabilidad, con el objetivo de asegurar que la plataforma cumpla con las expectativas de los usuarios. 

##### 1.2.2.3 Lean UX Hypothesis Statements

Hypothesis Statement 01: 

- Creemos que los docentes y estudiantes de institutos necesitan una plataforma centralizada para gestionar sus actividades académicas y mantener una comunicación más fluida. 

- Sabremos que estamos en lo correcto cuando veamos un uso constante de la plataforma en el día a día académico y recibamos retroalimentación positiva sobre la organización que esta ofrece. 

Hypothesis Statement 02: 

- Creemos que la desarticulación entre las herramientas que actualmente utilizan es la principal causa de desorden y pérdida de información en los institutos. 

- Sabremos que estamos en lo correcto cuando los usuarios dejen de depender de múltiples aplicaciones externas y disminuyan las quejas relacionadas con la desorganización. 

Hypothesis Statement 03: 

- Creemos que permitir la creación y gestión de grupos académicos dentro de la plataforma fomentará una colaboración más activa entre los estudiantes. 

- Sabremos que estamos en lo correcto cuando identifiquemos un incremento en la cantidad de grupos creados y en el nivel de participación dentro de ellos. 

Hypothesis Statement 04: 

- Creemos que ofrecer un módulo para centralizar materiales, tareas y fechas de entrega ayudará a los estudiantes a planificar mejor sus responsabilidades. 

- Sabremos que estamos en lo correcto cuando los estudiantes reporten mayor claridad en la gestión de sus cursos y menos confusión respecto a los plazos. 

Hypothesis Statement 05: 

- Creemos que un sistema de métricas y reportes en tiempo real permitirá a los docentes hacer un seguimiento más eficiente del rendimiento académico de sus estudiantes. 

- Sabremos que estamos en lo correcto cuando los profesores utilicen activamente estas métricas para ajustar sus clases y estrategias pedagógicas. 

Hypothesis Statement 06: 

- Creemos que una interfaz simple e intuitiva facilitará la adopción de la plataforma por parte de usuarios con distintos niveles de familiaridad tecnológica. 

- Sabremos que estamos en lo correcto cuando los nuevos usuarios logren manejar la plataforma de manera autónoma en sus primeras semanas de uso. 

Hypothesis Statement 07: 

- Creemos que mostrar de manera visual los avances y estadísticas individuales motivará a los estudiantes a involucrarse más con su aprendizaje. 

- Sabremos que estamos en lo correcto cuando los estudiantes revisen con frecuencia su panel de progreso y expresen satisfacción con esta funcionalidad. 

Hypothesis Statement 08: 

- Creemos que garantizar la privacidad y seguridad de la información académica será un factor decisivo para la adopción institucional de la plataforma. 

- Sabremos que estamos en lo correcto cuando no existan incidentes de seguridad y los usuarios manifiesten confianza en el manejo de sus datos. 

Hypothesis Statement 09: 

- Creemos que centralizar la entrega y calificación de tareas dentro de la plataforma optimizará la dinámica académica y reducirá la necesidad de usar correos o mensajería externa. 

- Sabremos que estamos en lo correcto cuando los docentes y estudiantes utilicen mayoritariamente esta funcionalidad y se reduzca el uso de canales alternativos para estas actividades. 

Hypothesis Statement 10: 

- Creemos que la creciente tendencia hacia la educación híbrida y digital incrementará la necesidad de contar con soluciones tecnológicas integradas en los institutos. 

- Sabremos que estamos en lo correcto cuando observemos un crecimiento sostenido en el número de instituciones que adoptan la plataforma en ciclos académicos presenciales, híbridos y virtuales. 

Hypothesis Statement 11: 

- Creemos que permitir a los docentes generar un código de acceso único para cada grupo facilitará la integración de estudiantes en el aula virtual. 

- Sabremos que estamos en lo correcto cuando observemos que la mayoría de los estudiantes se registran correctamente mediante este sistema sin requerir asistencia adicional. 

Hypothesis Statement 12: 

- Creemos que la función para que los estudiantes se unan mediante códigos reducirá los errores en el registro y agilizará el manejo de grupos. 

- Sabremos que estamos en lo correcto cuando identifiquemos menos casos de estudiantes que no logran acceder al grupo correcto. 

Hypothesis Statement 13: 

- Creemos que la posibilidad de que los docentes eliminen a alumnos de los grupos ayudará a mantener un control más ordenado de la plataforma virtual. 

- Sabremos que estamos en lo correcto cuando los docentes gestionen cambios de grupo sin generar confusión en el resto de los estudiantes. 

Hypothesis Statement 14: 

- Creemos que las estadísticas globales de los estudiantes permitirán a los docentes monitorear el progreso general de su clase. 

- Sabremos que estamos en lo correcto cuando los profesores consulten estas métricas con frecuencia y las usen para ajustar sus estrategias de enseñanza. 

Hypothesis Statement 15: 

- Creemos que la opción de revisar y calificar tareas dentro de la plataforma optimizará el trabajo docente y reducirá la dependencia de medios externos. 

- Sabremos que estamos en lo correcto cuando los profesores entreguen calificaciones dentro del sistema y disminuya el uso de correos o mensajería externa para enviar resultados. 

Hypothesis Statement 16: 

- Creemos que el acceso de los estudiantes a sus propias métricas de desempeño los motivará a mejorar en sus tareas y actividades. 

- Sabremos que estamos en lo correcto cuando los estudiantes revisen con frecuencia su panel de métricas y reporten mayor claridad sobre su progreso académico. 

Hypothesis Statement 17: 

- Creemos que la centralización de grupos, tareas y calificaciones en un solo espacio reducirá la confusión que suele generar el uso de múltiples aplicaciones. 

- Sabremos que estamos en lo correcto cuando los usuarios manifiesten que ya no necesitan apoyarse en varias herramientas externas para organizar su vida académica. 

Hypothesis Statement 18: 

- Creemos que un dashboard para el docente enfocada en la gestión de grupos y calificaciones facilitará la adopción de la plataforma por parte del profesorado. 

- Sabremos que estamos en lo correcto cuando los docentes logren administrar sus grupos de manera autónoma después de un breve periodo de adaptación. 

Hypothesis Statement 19: 

- Creemos que la visualización de métricas individuales por estudiante ayudará a los docentes a identificar con mayor rapidez a quienes requieren apoyo adicional. 

- Sabremos que estamos en lo correcto cuando los profesores utilicen estas métricas para tomar decisiones pedagógicas y reporten que la detección temprana fue efectiva. 

Hypothesis Statement 20: 

- Creemos que validar la experiencia de estudiantes y docentes mediante pruebas de usabilidad permitirá detectar oportunidades de mejora antes del despliegue final. 

- Sabremos que estamos en lo correcto cuando los resultados de estas pruebas conduzcan a ajustes que incrementen la satisfacción general de los usuarios.

##### 1.2.2.4 Lean UX Canvas  

<img src="./assets/chapter-1/lean_ux_canvas.png" alt="Lean UX Canvas">

### 1.3 Segmentos objetivo  

**Segmento Objetivo 1: Estudiantes de institutos**

Jóvenes que requieren un entorno educativo digital organizado para acceder a materiales, entregar tareas y monitorear su progreso académico. Necesitan claridad, retroalimentación oportuna y evitar la dispersión de información en múltiples canales. 

Características Demográficas: 

- Edad: 16 a 27 años. 
- Género: Todos los géneros. 
- Ubicación geográfica: Institutos de Lima. 
- Nivel socioeconómico: Clase media-baja. (Acceso a internet básico) 
- Dispositivos de acceso: Smartphones, laptops, tablets. 

Necesidades: 

- Centralización de tareas, materiales y fechas de entrega. 
- Acceso sencillo desde dispositivos móviles con bajo consumo de datos. 
- Retroalimentación clara y rápida sobre sus calificaciones. 

Beneficios clave: 

- Plataforma unificada para todas sus clases y actividades. 
- Notificaciones push para recordatorios importantes. 
- Visualización directa de su desempeño y áreas de mejora. 

**Segmento Objetivo 2: Profesores de institutos**

Educadores que necesitan una solución integral para gestionar sus cursos, reducir la carga administrativa y obtener insights sobre el rendimiento estudiantil. Buscan centralizar la comunicación, las entregas y las calificaciones en una plataforma accesible, evitando el uso de herramientas dispersas como WhatsApp o correo electrónico. 

Características Demográficas: 

- Edad: 30 a 60 años. 
- Género: Todos los géneros. 
- Ubicación geográfica: Institutos de Lima (públicos y privados con recursos limitados). 
- Nivel socioeconómico: Clase media (acceso a internet y dispositivos básicos, pero con presupuesto restringido para tecnología educativa). 
- Dispositivos de acceso: Laptops, smartphones, computadoras de escritorio en aulas. 

Necesidades: 

- Automatización de procesos administrativos (calificaciones, recepción de entregas). 
- Análisis de datos del rendimiento estudiantil para adaptar estrategias pedagógicas. 
- Comunicación centralizada y eficiente con estudiantes. 

Beneficios clave: 

- Reducción de tiempo en gestión manual con herramientas integradas. 
- Métricas claras del progreso de cada estudiante y del grupo. 
- Interfaz intuitiva que requiere mínima capacitación. 

## Capítulo II: Requirements Elicitation & Analysis  

### 2.1 Competidores  
**Sistema Saberes**


![1](assets/chapter-2/1.png)

 

Sistema Saberes se posiciona como una solución integral de gestión educativa desarrollada localmente para el mercado peruano. Su plataforma abarca todos los procesos operativos de institutos superiores, centros de formación técnica y escuelas de negocios, desde la admisión y matrícula hasta la graduación y certificación. Está construido para cumplir con las normativas del Ministerio de Educación (MINEDU) y los requisitos de SUNEDU, offering módulos especializados en control académico (calificaciones, asistencias, horarios), gestión financiera (pensiones, cobranza) y comunicación institucional. Incluye herramientas de reportes básicos que permiten extraer datos históricos, pero su fortaleza radica en la centralización de la información administrativa más que en el análisis pedagógico profundo. 


**EduSoftNet**

![2](assets/chapter-2/2.png)

EduSoft es un software modular de gestión educativa que ofrece soluciones escalables para colegios, institutos y academias en Perú. Su propuesta de valor se centra en la flexibilidad, allowing a las instituciones contratar solo los módulos que necesiten, como control académico, gestión financiera o library management. La plataforma genera reportes gerenciales predefinidos que ayudan en la toma de decisiones administrativas, pero su capacidad de análisis de datos pedagógicos es limitada. Está diseñado para instituciones que priorizan la optimización de procesos operativos por sobre la innovación en la enseñanza basada en datos. 

**SieWeb**

![3](assets/chapter-2/3.png)
SieWeb es un sistema integral de gestión diseñado para instituciones de educación superior en Perú, including institutos tecnológicos y escuelas de posgrado. Su plataforma es altamente customizable, permitiendo adaptarse a flujos de trabajo específicos y mallas curriculares complejas. Ofrece módulos para la gestión del ciclo de vida del estudiante, prácticas preprofesionales, y generación de reportes personalizados para la alta dirección. Aunque incluye dashboards gerenciales, estos están orientados a métricas operativas y financieras, no al desempeño académico granular o a la intervención pedagógica temprana. SieWeb es ideal para instituciones que necesitan un ERP educativo a medida, pero no una herramienta ágil de análisis didáctico. 


#### 2.1.1 Análisis competitivo  



# Competitive Analysis Landscape

## ¿Por qué llevar a cabo este análisis?  
Este análisis se realiza para entender cómo se posiciona nuestro proyecto frente a competidores consolidados, identificar fortalezas y debilidades propias, descubrir oportunidades de diferenciación en el mercado de IoT para motocicletas y anticipar amenazas que puedan afectar la adopción del producto. Nos permite tomar decisiones estratégicas mejor informadas en marketing, producto y modelo de negocio.

---

## Comparativo de Competidores

| Categoría                | **LearnHive**                                                                 | **Sistema Saberes**                                                                                   | **EduSoftNet**                                                                 | **SieWeb**                                                                                  |
|---------------------------|--------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------|
| **Overview**              | Plataforma especializada en analytics y gestión del desempeño académico.       | ERP educativo integral (gestión administrativa y académica).                                           | Software modular de gestión educativa (académica y financiera).                 | Sistema customizable para educación superior (énfasis en procesos complejos).                |
| **Ventaja Competitiva**   | Dashboards, alertas tempranas, intervención proactiva y portal estudiantil.    | Cumplimiento normativo integrado (MINEDU/SUNEDU) y comunicación centralizada.                         | Precios accesibles, módulos escalables y gestión financiera robusta.            | Adaptación total a flujos complejos (prácticas, titulación) y reportes personalizados.       |
| **Mercado Objetivo**      | Institutos técnicos/superiores en Lima que priorizan mejora pedagógica y ya tienen un sistema base. | Institutos peruanos que buscan un ERP integral para automatizar procesos administrativos y académicos. | Institutos y colegios con budgets ajustados que necesitan módulos específicos.  | Institutos con modelos educativos únicos o procesos complejos (ej: escuelas de posgrado).    |
| **Estrategia Marketing**  | Marketing de contenidos (blog, webinars), demostraciones personalizadas.       | Ventas directas, referencias boca a boca, participación en ferias educativas.                         | Precios competitivos, demostraciones gratuitas, enfoque en flexibilidad.        | Enfoque en customización, ventas B2B, casos de estudio con clientes grandes.                 |
| **Productos & Servicios** | Analytics, dashboards interactivos, alertas tempranas y portal de estudiantes. | ERP educativo (admisión, matrícula, calificaciones, financiero), reportes básicos, soporte.            | Módulos de gestión académica, financiera, biblioteca, reportes predefinidos.    | ERP customizable, gestión de prácticas, titulación, dashboards gerenciales, soporte técnico. |
| **Precios & Costos**      | Suscripción mensual (asequible). Bajo costo de implementación.                 | Licencia anual costosa. Alta inversión inicial e implementación.                                       | Precios por módulo (accesible). Costo de implementación medio.                  | Precios altos por customización. Implementación larga y costosa.                            |
| **Canales de Distribución** | Ventas online, canal directo (equipo comercial), partners estratégicos.       | Ventas directas, canal telefónico, sitio web.                                                         | Ventas directas, sitio web, redes sociales.                                     | Ventas B2B, consultores educativos, canal directo.                                           |
| **Fortalezas**            | Especialización en analíticas, usabilidad, implementación rápida, precio accesible. | Conocimiento normativo peruano, solución integral, presencia en el mercado.                           | Precios flexibles, modularidad, experiencia en el mercado.                      | Customización, manejo de procesos complejos, clientes grandes.                               |
| **Debilidades**           | Dependencia de integración con otros sistemas, marca desconocida.              | Interface menos intuitiva, analytics limitados, alto costo.                                            | Analytics básicos, diseño no moderno, enfoque administrativo.                   | Precio muy alto, implementación lenta, no es ágil para docentes.                            |
| **Oportunidades**         | Creciente demanda de edtech, expansión a otras ciudades.                       | Cross-selling a clientes existentes, mejorar módulos de analytics.                                     | Upselling de módulos, integración con herramientas de analytics.                | Vender módulos de analytics como add-on, asociarse con consultoras.                         |
| **Amenazas**              | Competidores agreguen analytics, resistencia al cambio en docentes, entrada de competidores globales. | Saturación del mercado de ERPs.                                                                       | Competidores con precios más agresivos, avance de soluciones en la nube.        | Aversión a altos costos post-pandemia, competidores con soluciones más ágiles.              |


#### 2.1.2 Estrategias y tácticas frente a competidores  

**1. Estrategia contra Sistema Saberes**

Estrategia: Especialización Académica y Agilidad de Implementación. 

Posicionar a LearnHive como la solución que eleva la gestión académica con analítica avanzada, detección temprana de riesgos y mejora del desempeño, destacando rapidez y facilidad en la adopción. 

Tácticas: 

Implementación Rápida y Guiada : Ofrecer un proceso express de despliegue con acompañamiento técnico para que las instituciones puedan empezar a usar dashboards y reportes académicos en pocas semanas.	 

Herramientas de Analítica Independiente: Proveer un módulo de importación de datos sencillo (Excel, CSV, Google Sheets), que permite a las instituciones aprovechar LearnHive sin necesidad de procesos complejos. 

Casos de Éxito Académicos : Publicar resultados concretos de clientes: reducción de deserción, mejora en el rendimiento académico, aumento en la satisfacción de los estudiantes.  

Campañas de Valor Educativo: Marketing de contenidos enfocado en la promesa: “De datos a decisiones académicas”. Artículos, webinars y guías prácticas para directores y coordinadores académicos. 

Modelo de Precios Escalable: Planes accesibles por institución o por número de estudiantes, con una entrada de bajo costo y beneficios claros en términos de retorno académico. 


**2. Estrategia contra EduSoft (El Competidor Modular y Accesible)**

Estrategia: Superioridad en Valor y Enfoque. 

Destacar que la "flexibilidad" de EduSoft sigue siendo administrativa, mientras que LearnHive ofrece un valor cualitativamente superior: la mejora de los resultados de aprendizaje. 

Tácticas: 

Comparativa de Valor (Value Comparison): Desarrollar una comparativa sutil que muestre cómo LearnHive, por un precio similar o ligeramente superior a un módulo de EduSoft, ofrece un retorno de la inversión (ROI) mucho mayor al impactar directamente en la retención y el éxito estudiantil. 

Enfoque en el "Dolor" del Profesor: Mientras EduSoft se vende a la administración, LearnHive debe marketing directo a los docentes. Talleres y webinars gratuitos sobre "Pedagogía Data-Driven" para crear demanda desde abajo hacia arriba. El profesor convencido será el mejor aliado interno. 

Prueba Gratuita Irresistible: Ofrecer una prueba de 30 días con data de demostración rica e insights inmediatos. Contrastar con la posible complejidad y tiempo que lleva configurar los módulos de EduSoft. 

Case Studies con Énfasis en Resultados: Documentar y promocionar casos de éxito con métricas concretas: "Con LearnHive, el Instituto XYZ identificó al 20% de su población en riesgo y logró recuperar al 15% gracias a intervenciones tempranas." EduSoft muestra funcionalidades; LearnHive debe mostrar resultados. 

Estrategia contra SieWeb (El Competidor Personalizable y Complejo) 
 

Estrategia: Agilidad y Simplicidad. 

Posicionar a SieWeb como una solución "pesada", "lenta" y "costosa" para la necesidad específica de analíticas. LearnHive es la alternativa "ágil", "moderna" y "centrada en el usuario". 

Tácticas: 

Messaging de "Time-to-Value": Crear mensajes contundentes: "¿6 meses para un dashboard? Con LearnHive, tiene insights valiosos en 6 días." o "La customización compleja vs. la inteligencia inmediata". Atacar su punto más débil: la velocidad. 

Precio Predecible vs. Costo Variable: Enfatizar el modelo de suscripción simple y predecible de LearnHive vs. los costos impredecibles de customización y consultoría de SieWeb. Apelar al budget controlado de los institutos. 

Show, Don't Tell: Utilizar demostraciones en vivo para mostrar la intuitividad de LearnHive. Pedirle al cliente que imagine tener que solicitar cada nuevo reporte o cambio a un consultor de SieWeb vs. obtenerlo ellos mismos con clics. 

Target en los Decisores de Línea Media: SieWeb se vende a la alta dirección. LearnHive debe hablarle al Jefe de Programa, al Coordinador Académico, al responsable de calidad educativa, que son quienes sufren la falta de agilidad y necesitan datos rápidos para su trabajo diario. 


Prueba Gratuita Irresistible: Ofrecer una prueba de 30 días con data de demostración rica e insights inmediatos. Contrastar con la posible complejidad y tiempo que lleva configurar los módulos de EduSoft. 

Case Studies con Énfasis en Resultados: Documentar y promocionar casos de éxito con métricas concretas: "Con LearnHive, el Instituto XYZ identificó al 20% de su población en riesgo y logró recuperar al 15% gracias a intervenciones tempranas." EduSoft muestra funcionalidades; LearnHive debe mostrar resultados. 

Estrategia contra SieWeb (El Competidor Personalizable y Complejo) 
 

**3. Estrategia: Agilidad y Simplicidad.**

Posicionar a SieWeb como una solución "pesada", "lenta" y "costosa" para la necesidad específica de analíticas. LearnHive es la alternativa "ágil", "moderna" y "centrada en el usuario". 

Tácticas: 

Messaging de "Time-to-Value": Crear mensajes contundentes: "¿6 meses para un dashboard? Con LearnHive, tiene insights valiosos en 6 días." o "La customización compleja vs. la inteligencia inmediata". Atacar su punto más débil: la velocidad. 

Precio Predecible vs. Costo Variable: Enfatizar el modelo de suscripción simple y predecible de LearnHive vs. los costos impredecibles de customización y consultoría de SieWeb. Apelar al budget controlado de los institutos. 

Show, Don't Tell: Utilizar demostraciones en vivo para mostrar la intuitividad de LearnHive. Pedirle al cliente que imagine tener que solicitar cada nuevo reporte o cambio a un consultor de SieWeb vs. obtenerlo ellos mismos con clics. 

Target en los Decisores de Línea Media: SieWeb se vende a la alta dirección. LearnHive debe hablarle al Jefe de Programa, al Coordinador Académico, al responsable de calidad educativa, que son quienes sufren la falta de agilidad y necesitan datos rápidos para su trabajo diario. 




### 2.2 Entrevistas  
#### 2.2.1 Diseño de entrevistas  

Segmento Objetivo 1: Estudiantes de Institutos 

Preguntas principales 

1. ¿Podrías contar un poco sobre ti? (edad, carrera, lugar de residencia, ocupación). 

2. ¿Cómo sueles organizar tus tareas y trabajos en grupo durante el ciclo académico? 

3. ¿Qué plataformas o aplicaciones usas más para estudiar o coordinar trabajos en grupo? (por ejemplo: WhatsApp, Meet, etc). 

4. ¿Te resulta sencillo mantener un orden entre tareas y comunicaciones? ¿Por qué sí o por qué no? 

5. ¿Qué te daría más confianza en una plataforma académica: facilidad de uso,  notificaciones, métricas de avance u otra cosa? 

6. ¿Qué tan importante es para ti recibir una retroalimentación rápida sobre tus entregas o calificaciones? 

  

Preguntas complementarias: 

1. ¿Usas más tu celular, laptop o tablet cuando estudias? ¿Por qué? 

2. ¿Qué experiencias positivas o negativas has tenido usando plataformas como Moodle, Canvas o Classroom? 

3. ¿En qué casos te ha resultado difícil organizarte o cumplir con tus entregas a tiempo? 

4. ¿Qué tan valioso sería para ti poder ver tu progreso académico en gráficos o estadísticas simples? 

5. ¿Te frustra depender de varias aplicaciones distintas para tu desempeño académico? 

  

Segmento Objetivo 2: Profesores de Institutos 

Preguntas principales: 

1. Para comenzar, ¿podría contarme un poco sobre usted? (edad, distrito de residencia, área de enseñanza). 

2. ¿Qué herramientas utiliza actualmente para planificar, compartir materiales y gestionar tareas con sus estudiantes? 

3. ¿Qué parte de su trabajo fuera del aula le consume más tiempo (revisar entregas, calificar, dar seguimiento a alumnos, etc.)? 

4. ¿Cómo realiza actualmente el seguimiento del desempeño de sus estudiantes? 

5. Si pudiera elegir, ¿qué funcionalidad sería la más valiosa en una plataforma académica: centralización de tareas, estadísticas, comunicación o retroalimentación automatizada? 

6. ¿Qué tan cómodo se sentiría con una plataforma que genere métricas claras y fáciles de entender sobre el progreso de cada estudiante? 

  

Preguntas complementarias 

1. ¿Qué dispositivo utiliza más a menudo para trabajar: laptop, PC o smartphone? 

2. ¿Qué medios emplea para comunicarse con sus estudiantes (WhatsApp, correo, etc)? ¿Qué ventajas o problemas encuentra en ellos? 

3. ¿Ha usado antes plataformas educativas? ¿Qué le funcionó bien y qué le resultó poco práctico? 

4. ¿Qué tipo de actividades digitales o interactivas le gustaría integrar en sus clases pero hoy le resulta difícil hacerlo? 

5. ¿Qué tan difícil considera la curva de aprendizaje de nuevas plataformas educativas? 


#### 2.2.2 Registro de entrevistas  

**Profesores de institutos:** 

  Entrevista 1: Profesor de Instituto 


| Campo                      | Detalle                                    |
|----------------------------|---------------------------------------------|
| **Foto y link**            | ![10](assets/chapter-2/4.png)    https://youtu.be/Owd7kK5dDWU                |
| **Nombre del entrevistado**| Adrian Castro Santana                                           |
| **Edad**                   | 26  años                                     |
| **Profesión**              | Profesor de Instituto  |
| **Ubicación**              | Lima-Pueblo Libre                                |
| **Duración de la entrevista** | 8:16 min                                  |
| **Herramientas actuales**  | Usa Google Classroom para planificar y compartir materiales. Emplea Excel para registrar notas. Se apoya en WhatsApp para comunicación rápida con estudiantes.                                           |
| **Dolores principales**    |    Calificación de trabajos y exámenes consume demasiado tiempo. Seguimiento de alumnos rezagados es difícil sin reportes claros.                                         |
| **Seguimiento del desempeño** | Lo hace de forma manual con Excel y observaciones de asistencia. No cuenta con un dashboard visual que le permita ver el panorama general ni identificar rápidamente a los alumnos en riesgo.                                       |
| **Necesidades prioritarias** | Estadísticas claras y visuales sobre progreso de estudiantes y desempeño del aula.  Mostrar la información de los alumnos (notas, tareas, asistencia, participación).                                        |
| **Dispositivos y comunicación** | Utiliza WhatsApp por rapidez, aunque presenta problemas de orden. El correo lo considera más formal pero menos inmediato.                                |
| **Experiencia con plataformas** | Ha usado Google Classroom el cual llega a organizar materiales y tareas. pero carece de reportes y estadísticas completas.                                   |
| **Interactividad deseada** | Cuestionarios en tiempo real.  Ejercicios personalizados según el nivel de cada estudiante.                                          |
| **Curva de aprendizaje**   | Considera que puede ser un reto si la plataforma es compleja.  Prefiere interfaces intuitivas, visuales y fáciles de usar para reducir la barrera de entrada.                                        |


Entrevista 2: Profesor de Instituto 

| Campo                      | Detalle                                    |
|----------------------------|---------------------------------------------|
| **Foto y link**            | ![10](assets/chapter-2/5.png)  [Link-entrevista](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202122484_upc_edu_pe/EQywp_Cid25EpgUEwukGdFEB-fs0WpIXqybsFcIFxJZJlw?e=f8c1yv&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)            |
| **Nombre del entrevistado**| Frank Rivera                                           |
| **Edad**                   | 24 años                                     |
| **Profesión**              | Practicante docente en Instituto Tecnológico (segundo año de práctica)   |
| **Ubicación**              | Lima-Pueblo Libre                               |
| **Duración de la entrevista** | 4:29 min                                 |
| **Herramientas actuales**  | - Google Drive (guardar materiales) - WhatsApp (avisos y coordinación) - Plataforma institucional (subir calificaciones) - Canva / PowerPoint (preparación de clases) |
| **Dolores principales**    | - Revisar y calificar entregas consume demasiado tiempo. - Dar retroalimentación detallada a cada alumno es muy pesado.                       |
| **Seguimiento del desempeño** | Excel personal (notas, asistencia, observaciones). Actualización manual y constante, sin automatización.                                        |
| **Necesidades prioritarias** | - Retroalimentación automatizada para responder rápido a estudiantes. - Métricas visuales y claras sobre el progreso de cada alumno.                                        |
| **Dispositivos y comunicación** | - Laptop (principal para clases, presentaciones, Excel). - Celular (comunicación rápida). - WhatsApp (rápido, pero desordenado y poco estructurado).|
| **Experiencia con plataformas** | Ha usado Google Classroom el cual llega a organizar materiales y tareas. pero carece de reportes y estadísticas completas.          |
| **Interactividad deseada** | - Cuestionarios en línea. - Juegos interactivos. - Videos cortos dinámicos.                                   |
| **Curva de aprendizaje**   | Interfaz intuitiva = fácil. - Plataformas complejas = frustración → regresa a lo básico (Excel, WhatsApp).  |


**Estudiantes de instituto:** 

Entrevista 4: Estudiante de Instituto



| Campo                      | Detalle                                    |
|----------------------------|---------------------------------------------|
| **Foto y link**            | ![10](assets/chapter-2/6.png) [Entrevista](https://upcedupe-my.sharepoint.com/personal/u202122484_upc_edu_pe/_layouts/15/stream.aspx?id=%2Fpersonal%2Fu202122484_upc_edu_pe%2FDocuments%2FFundamentos%20-%20APX-4%2FInterviews%2FEntrevista%20David%20-%20Segmento%20Estudiantes%20de%20Insituto%2Emp4&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&ga=1&referrer=StreamWebApp%2EWeb&referrerScenario=AddressBarCopied%2Eview%2Ef7c6474d-fd38-49fc-8a81-57b217a34a8e)                    |
| **Nombre del entrevistado**| David Manuel Torres Meneses                                            |
| **Edad**                   | 19 años                                      |
| **Profesión**              | Estudiante universitario / estudiante de instituto  |
| **Ubicación**              | Lima, Perú                                 |
| **Duración de la entrevista** | 11:38 min                                   |
| **Herramientas actuales**  |Plataformas institucionales, WhatsApp para grupos y comunicación, Meet, Discord, Excel y Classroom para notas y materiales.                                          |
| **Dolores principales**    | La falta de graficas que permitan evidenciar su desarrollo como estudiante no le permite saber que tan bien se está desarrollando como estudiante.    |
| **Seguimiento del desempeño** |Usa un Excel para poder hacer su organización y cálculo de notas durante el desarrollo del ciclo. |
| **Necesidades prioritarias** | Retroalimentación instantánea, estadísticas de sus notas y gráficos que permitan comparar su avance. |
| **Dispositivos y comunicación** | Usa mucho más su celular que la laptop; pero prefiere usar la laptop ya que tiene un alcance más largo de acuerdo con posibilidades. |
| **Experiencia con plataformas** | Ha usado principalmente Classroom pero considera que tiene una ventaja para compartir archivos sin embargo al no tener un sistema de verificados hay otros usuarios que la usan sin responsabilidad. |
| **Interactividad deseada** | Mas graficos, estadísticas, feedbacks o un dashboard que permita unir todos estos ámbitos y poder analizar su desempeño. |
| **Curva de aprendizaje**   |Considera que las plataformas suelen ser poco intuitivas y los estudiantes nunca pueden sacarle todo el provecho.  |


Entrevista 5: Estudiante de Instituto 


| Campo                      | Detalle                                    |
|----------------------------|---------------------------------------------|
| **Foto y link**            | ![10](assets/chapter-2/7.png) [Entrevista](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202122484_upc_edu_pe/EYfA6PHLIrNKovCrXJTvwUMBwo4_xnSmPmvWkF9XIHXVhw?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=dmovhm)                  |
| **Nombre del entrevistado**|Alejandra Angulo Mendoza |
| **Edad**                   | 20 años  |
| **Profesión**              | Estudiante de instituto / Artista 3D |
| **Ubicación**              | Lima, Perú                                 |
| **Duración de la entrevista** | 04:52 min  |
| **Herramientas actuales**  | Discord, Google Calendar, Clockify.   |
| **Dolores principales**    |Necesita utilizar formas de organización para evitar perder el hilo de las actividades que debe llevar a cabo.   |
| **Seguimiento del desempeño** | Lleva una agenda con sus actividades realizadas, y un excel de organización. |
| **Necesidades prioritarias** | Considera que sería bueno tener herramientas de organización unificadas en una misma plataforma. |
| **Dispositivos y comunicación** | Utiliza principalmente la laptop y el celular.  |
| **Experiencia con plataformas** |Ha usado principalmente Classroom                        |
| **Interactividad deseada** |Gráficos que muestren el desempeño a lo largo del tiempo para conocer el rendimiento en tiempo real y saber en que mejorar.         |
| **Curva de aprendizaje**   | Considera que las plataformas suelen ser poco intuitivas         |

Entrevista 6: Estudiante de Instituto 


| Campo                      | Detalle                                    |
|----------------------------|---------------------------------------------|
| **Foto y link**            | ![10](assets/chapter-2/8.png) [Entrevista](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202122484_upc_edu_pe/ERtYfl5y-XVChcbrl_jGtV4BAVDyRs_5wHYsWSQqV1wZXQ?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=MiGu97)                |
| **Nombre del entrevistado**| Jhon Chuchon                                           |
| **Edad**                   | 19 años                                    |
| **Profesión**              | Estudiante de instituto  |
| **Ubicación**              | Lima, Perú                                 |
| **Duración de la entrevista** | 06:21 min                               |
| **Herramientas actuales**  |WhatsApp para comunicación con grupos, Google Drive para documentos o informes y Classroom para clases virtuales.                                      |
| **Dolores principales**    |Se le complica cuando la información se reparte en distintas herramientas y termina olvidándose de algunas cosas.  |
| **Seguimiento del desempeño** | Lleva una agenda con sus actividades realizadas, |
| **Necesidades prioritarias** | Retroalimentación instantánea para saber si va por buen camino o si necesita mejorar antes. |
| **Dispositivos y comunicación** | Utiliza más el celular ya que es más sencillo de llevar a todos lados. |
| **Experiencia con plataformas** |Las ventajas de sus plataformas es que centralizan la información y le ayuda a tener todo en un solo sitio, las desventajas es que a veces se suelen caer y no funcionan bien en su celular. |
| **Interactividad deseada** | Gráficos y estadísticas, ya que lo ayudarían a motivarse y tendría más control sobre sus estudios. |

#### 2.2.3 Análisis de entrevistas  

El segmento de estudiantes universitarios presenta una dinámica muy marcada por la búsqueda de organización personal y control de su desempeño académico en tiempo real. En términos de herramientas actuales, los entrevistados señalaron que utilizan una combinación de plataformas institucionales, Google Classroom, Excel, Google Calendar, Clockify y Discord, además de WhatsApp y Meet para comunicación y coordinación de trabajos en grupo. Estas herramientas cumplen funciones específicas —calendarios, temporizadores, almacenamiento de archivos o comunicación—, pero se encuentran dispersas, lo que genera la necesidad de unificar todas esas funcionalidades en un mismo espacio digital. 

Entre los principales dolores identificados, destaca la ausencia de gráficas claras que les permitan evidenciar su desarrollo académico y compararlo con sus compañeros; esta carencia fue mencionada por el 100% de los entrevistados. Además, ambos resaltaron la necesidad de contar con herramientas de organización más eficientes, ya que la gestión de tareas y tiempos depende de múltiples aplicaciones y agendas, lo que en ocasiones provoca desorden o pérdida de información. 

En cuanto al seguimiento del desempeño, los estudiantes recurren principalmente a Excel, agendas digitales y cronogramas, que les permiten calcular notas, registrar horas de trabajo y organizar entregas. Sin embargo, esta práctica requiere un esfuerzo adicional y carece de automatización, lo que limita su utilidad en comparación con una solución integrada. 

Respecto a las necesidades prioritarias, el 100% manifestó la importancia de contar con retroalimentación instantánea, que les permita identificar errores y áreas de mejora sin esperar largos periodos de revisión. Asimismo, el 80% expresó interés en tener gráficos y dashboards que muestren su progreso académico en tiempo real, tanto a nivel individual como en comparación con sus compañeros (por ejemplo, saber si su rendimiento está por encima del 50% o 75% del curso). Por otro lado, un 70% resaltó la importancia de integrar herramientas de organización en una sola plataforma, que combine asignación de tareas, notificaciones, métricas de avance y control del tiempo invertido. 

En el aspecto de dispositivos y comunicación, los estudiantes utilizan tanto laptops como celulares, aunque la preferencia recae en la laptop debido a su mayor alcance y comodidad en el trabajo académico. Sin embargo, reconocen que el celular es indispensable para la comunicación rápida y la coordinación en grupos. En este contexto, Discord fue señalado como la herramienta preferida por su practicidad y comodidad para organizar equipos, frente a WhatsApp o Classroom, que consideran menos versátiles. 

La experiencia con plataformas muestra percepciones mixtas. Classroom es vista como útil para compartir archivos, pero también se critica la falta de filtros y control en el acceso, lo que puede dar pie a usos irresponsables. En general, los estudiantes coinciden en que las plataformas existentes son poco intuitivas y que los usuarios no logran aprovecharlas plenamente, lo que refleja una curva de aprendizaje poco amigable. 

En cuanto a la interactividad deseada, el 60% de los entrevistados señaló su interés en contar con dashboards visuales y gráficos dinámicos que no solo muestren su avance personal, sino que también comparen su desempeño con la media del grupo. Además, se destaca la necesidad de incluir notificaciones automáticas y métricas de progreso, como el número de tareas completadas semanalmente o el tiempo promedio invertido en actividades. 

Finalmente, la curva de aprendizaje de las plataformas actuales es percibida como una limitante. Los estudiantes sienten que estas no son intuitivas y que requieren un esfuerzo extra para configurarlas y sacarles provecho. En este punto, la facilidad de uso aparece como una condición esencial para que cualquier nueva solución sea adoptada con éxito. 

En síntesis, el perfil del estudiante universitario se caracteriza por la necesidad de organización, retroalimentación inmediata y métricas claras de desempeño académico. Existe un interés unánime en soluciones que integren feedback instantáneo (100%), la posibilidad de ver el progreso académico en tiempo real mediante gráficos comparativos (80%), y la integración de herramientas de organización en una sola plataforma (70%). Este segmento muestra una disposición favorable hacia plataformas que sean intuitivas, flexibles y con funciones de análisis visual que fortalezcan tanto la autogestión como la colaboración en equipo. 

 

Análisis Segmento Objetivo 2: Profesores de Institutos 

 

El segmento objetivo de profesores de institutos se caracteriza por el uso combinado de diversas herramientas digitales que les permiten cumplir con sus labores pedagógicas y administrativas. Entre las más comunes se encuentran las plataformas institucionales, que utilizan de forma obligatoria para el registro de notas y materiales, complementadas por WhatsApp como canal principal de comunicación con los estudiantes. A esto se suma el empleo frecuente de Excel para el manejo de calificaciones y Dropbox como repositorio de documentos. No obstante, los docentes perciben que este conjunto de recursos funciona de manera aislada y poco integrada, lo que genera duplicidad de trabajo y procesos lentos. 

Uno de los principales problemas identificados es el exceso de tiempo que requiere la calificación manual de las entregas. A esto se añade la necesidad de cargar posteriormente las notas a la plataforma oficial, un proceso que consideran repetitivo, lento y vulnerable a errores. Aunque este procedimiento les permite tener una idea del progreso individual de cada estudiante, los profesores carecen de una herramienta que les brinde una visión consolidada y en tiempo real del desempeño grupal, una necesidad expresada por el 100% de los entrevistados. Esta carencia limita la posibilidad de identificar patrones comunes y ajustar su enfoque pedagógico de manera oportuna. 

Las entrevistas revelan que existe una demanda prioritaria por retroalimentación automatizada, planteada de manera unánime por el 100% de los docentes entrevistados. Esta funcionalidad permitiría optimizar el tiempo invertido en la revisión de trabajos y, al mismo tiempo, brindar a los estudiantes respuestas inmediatas que fortalezcan su aprendizaje. Asimismo, el 60% de los profesores destacó la importancia de integrar interactividad en los recursos educativos, a través de videos cortos, materiales lúdicos y dinámicas que incrementen el interés y la motivación de los alumnos. 

Los docentes expresan además su preferencia por plataformas más flexibles, amigables y con menor curva de aprendizaje, tanto para ellos como para sus estudiantes, dado que consideran que las soluciones actuales son complejas y poco adaptables. A esto se suma la necesidad de contar con un soporte técnico confiable y accesible, ya que la falta de atención oportuna ha sido una de las causas principales de frustración en el uso de sistemas digitales. 

En cuanto a los dispositivos utilizados, los profesores trabajan principalmente desde la laptop, aunque recurren también al celular para tareas rápidas y comunicación inmediata. La elección de WhatsApp responde a que los estudiantes se encuentran más activos en esa aplicación, lo que facilita la interacción cotidiana, aunque los mismos docentes reconocen que su uso favorece la inmediatez y la superficialidad, sin aportar a un aprendizaje profundo. Esto genera una tensión entre la practicidad comunicativa y el objetivo académico. 

Finalmente, la curva de aprendizaje de las plataformas digitales constituye una barrera significativa. Los docentes consideran que estas no se adaptan de manera adecuada a todos los estudiantes y terminan siendo demasiado complejas. Frente a ello, plantean la integración de inteligencia artificial como un asistente 24/7, capaz de brindar retroalimentación continua y aliviar la carga operativa, de modo que el profesor pueda enfocarse en el acompañamiento pedagógico y en fortalecer el aprendizaje profundo. 

En síntesis, el perfil del profesor de instituto muestra un alto nivel de frustración frente a los procesos manuales, la poca automatización y la falta de soporte técnico. Al mismo tiempo, revela una clara apertura hacia nuevas soluciones que ofrezcan eficiencia, simplicidad, retroalimentación instantánea y un entorno de aprendizaje más dinámico e interactivo. La unanimidad en la búsqueda de retroalimentación automatizada (100%), de un apartado para ver el progreso en tiempo real de todos los alumnos (100%), y el interés mayoritario en recursos más interactivos (60%), convierten a este segmento en un grupo altamente receptivo a propuestas de innovación tecnológica. 




### 2.3 Needfinding  
#### 2.3.1 User Personas 


Segmento Objetivo 1: Estudiantes de institutos 
User Persona: Olivia Perez(17 años)

![10](assets/chapter-2/User%20Persona-Olivia%20Perez.png)

 

Segmento Objetivo 2: Profesores de Institutos 

User Persona: Adrian Espinoza (30 años) 

![10](assets/chapter-2/User%20Persona-Adrian%20Espinoza.png)


#### 2.3.2 User Task Matrix  

Presentaremos las tareas que realizan los estudiantes (representados por Olivia Pérez) y los profesores de institutos (representados por Luis Ramírez) para cumplir sus objetivos académicos y pedagógicos 

**Olivia Pérez - Estudiante de instituto** 
| Actividad                                                                 | Frecuencia | Importancia |
|---------------------------------------------------------------------------|------------|-------------|
| Organizar tareas, exámenes y horarios de entrega                          | Alta       | Alta        |
| Coordinar trabajos grupales (Meet, Discord, WhatsApp)                     | Alta       | Media       |
| Monitorear su propio desempeño académico (notas, dashboards, comparaciones) | Alta       | Alta        |
| Gestionar tiempo de estudio invertido (cronogramas, temporizadores, apps de productividad) | Media      | Alta        |
| Recibir retroalimentación sobre los entregables                           | Alta       | Alta        |

**Luis Ramírez – Profesor de instituto**    
| Actividad                                                                 | Frecuencia | Importancia |
|---------------------------------------------------------------------------|------------|-------------|
| Calificar entregas y exámenes                                             | Alta       | Alta        |
| Dar seguimiento al progreso de alumnos (identificar rezagados)            | Alta       | Alta        |
| Comunicarse con alumnos (WhatsApp, correo, avisos en plataforma)          | Alta       | Alta        |
| Brindar retroalimentación rápida a estudiantes                            | Media      | Media       |
| Atender consultas individuales de alumnos fuera de clase                  | Baja       | Media       |
| Monitorear la asistencia y puntualidad de los estudiantes                 | Alta       | Alta        |



#### 2.3.3 User Journey Mapping  

**Estudiante de Instituto**


El User Journey Mapping de los estudiantes de institutos refleja el recorrido que realizan desde la conformación de sus grupos de estudio hasta la entrega de sus trabajos académicos. Este mapeo permite identificar los objetivos, procesos, problemas y emociones que experimentan en cada etapa, evidenciando tanto la motivación inicial como las dificultades relacionadas con la organización, el acceso a recursos y la coordinación con sus compañeros. La representación As-Is resalta los puntos críticos que generan ansiedad y frustración, pero también muestra oportunidades de mejora vinculadas a la centralización de herramientas, la automatización de recordatorios y la simplificación de la comunicación con docentes y pares. 

![10](assets/chapter-2/User%20Journey%20Mapping%20Estudiante%20de%20Instituto.png)

**Profesor de Instituto** 

El User Journey Mapping de los profesores de institutos describe el proceso que siguen al gestionar grupos, asignar tareas, recibir entregas, calificarlas y brindar retroalimentación. Este recorrido evidencia los objetivos y esfuerzos del docente por mantener el control y garantizar la claridad en las instrucciones, a la vez que revela problemáticas como la dispersión en la recepción de trabajos, la sobrecarga de revisión y la dificultad para dar feedback oportuno y detallado. La versión As-Is permite visualizar con claridad los puntos de fricción que impactan en su experiencia, abriendo oportunidades para implementar plataformas unificadas de gestión, rúbricas digitales y herramientas que agilicen tanto la evaluación como la comunicación con los estudiantes. 


![10](assets/chapter-2/User%20Journey%20Mapping%20Profesor%20de%20Instituto.png)


#### 2.3.4 Empathy Mapping  


**Estudiante de instituto (Olivia Perez)**
![10](assets/chapter-2/Olivia%20Perez-Empathy%20map.png)

[EMPATHY-MAP](https://upcedupe-my.sharepoint.com/:i:/g/personal/u202122484_upc_edu_pe/EWWQQuyX-BJLqsZWg7XW928BaDEUrCjxqd8j2u7LrAzGFg?e=UFplGK)


![10](assets/chapter-2/Adrian%20Espinoza-Empathy%20map.png)

[EMPATHY-MAP](https://upcedupe-my.sharepoint.com/:i:/g/personal/u202122484_upc_edu_pe/EWWQQuyX-BJLqsZWg7XW928BaDEUrCjxqd8j2u7LrAzGFg?e=UFplGK)

#### 2.3.5 As-is Scenario Mapping  
**Segmento Objetivo 1: Estudiantes de institutos** 

El As-Is Scenario Mapping de estudiantes muestra cómo actualmente dependen de múltiples canales dispersos (WhatsApp, Classroom, correos, Excel) para organizarse, entregar trabajos y seguir su progreso. Esto genera estrés, inseguridad y ansiedad por la falta de centralización y retroalimentación clara, aunque también refleja su disposición a colaborar y su interés en contar con métricas visuales y feedback inmediato. 

![10](assets/chapter-2/AsIs-Scenario%20Mapping-Estudiantes%20de%20institutos.png)

[AS-IS-LINK](https://upcedupe-my.sharepoint.com/:i:/g/personal/u202122484_upc_edu_pe/EWWQQuyX-BJLqsZWg7XW928BaDEUrCjxqd8j2u7LrAzGFg?e=UFplGK)


**Segmento Objetivo 2: Profesores de Institutos**

El As-Is Scenario Mapping de profesores de institutos evidencia que gran parte de su tiempo se pierde en tareas administrativas manuales (cronogramas en Excel, corrección en papel, carga de notas en plataformas). Este escenario les genera agotamiento y frustración, pero también muestra apertura a soluciones más intuitivas y automatizadas que reduzcan su carga y permitan un mejor seguimiento del desempeño estudiantil. 

![10](assets/chapter-2/AsIs-Scenario%20Mapping-Profesores%20de%20instituto.png)
[AS-IS-LINK](https://upcedupe-my.sharepoint.com/:i:/g/personal/u202122484_upc_edu_pe/EWWQQuyX-BJLqsZWg7XW928BaDEUrCjxqd8j2u7LrAzGFg?e=UFplGK)
### 2.4 Ubiquitous Language  
| Término en inglés       | Término en español     | Descripción                                                                                                                                       |
|--------------------------|------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------|
| **Academic Group**       | Grupo Académico        | Espacio creado por un profesor en la plataforma, en el cual se organizan estudiantes para realizar actividades, tareas y comunicación asociada a un curso. |
| **Group Member**         | Miembro del Grupo      | Participante de un grupo académico, ya sea profesor o estudiante.                                                                                 |
| **Assignment**           | Tarea                  | Actividad creada por un profesor, con fecha límite, instrucciones y criterios de evaluación.                                                      |
| **Assignment Submission**| Entrega de Tarea       | Archivo o respuesta enviada por un estudiante como cumplimiento de un trabajo académico.                                                           |
| **Submission Status**    | Estado de Entrega      | Indicador del progreso de un trabajo académico: pendiente, entregado, en revisión o calificado.                                                    |
| **Deadline**             | Fecha Límite           | Momento definido por el profesor como último plazo para enviar un trabajo académico.                                                               |
| **Academic Dashboard**   | Panel Académico        | Interfaz visual donde estudiantes y profesores ven información resumida sobre tareas, calificaciones, progreso y métricas.                         |
| **Feedback**             | Retroalimentación      | Comentarios, observaciones o calificaciones entregadas por el profesor para orientar la mejora del estudiante.                                     |
| **Announcement**         | Anuncio                | Publicación realizada por el profesor visible para todos los estudiantes.                                                                          |
| **Notification**         | Notificación           | Mensaje automático del sistema que informa a estudiantes o profesores sobre eventos relevantes.                                                    |
| **Student Profile**      | Perfil de Estudiante   | Espacio donde el alumno puede visualizar su información académica, calificaciones, métricas de rendimiento y progreso en cada curso.               |
| **Teacher Profile**      | Perfil de Profesor     | Espacio donde el docente gestiona sus cursos, tareas asignadas, calificaciones otorgadas y métricas de desempeño de los estudiantes.                |
| **Educational Resource** | Recurso Educativo      | Material compartido por un profesor en un grupo para apoyar el aprendizaje.                                                                        |
| **Grade Average**        | Promedio de Calificaciones | Valor numérico que resume el rendimiento global de un estudiante en un grupo o curso.                                                          |
| **Performance Metrics**  | Métricas de Desempeño  | Indicadores cuantitativos que reflejan el rendimiento de estudiantes y grupos.                                                                     |

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
