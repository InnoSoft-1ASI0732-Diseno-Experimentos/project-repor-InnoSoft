<h1 align="center"> UNIVERSIDAD PERUANA DE CIENCIAS APLICADAS </h1>

<h2 align="center"> INGENIERIA DE SOFTWARE</h2>
<h2 align="center"> CICLO 2025-1</h2>

<div align="center">
    <img src="./assets/logo-upc.png">
</div>

<br>
<h3 align="center"> Diseño de Experimentos de Ingeniería de Software - WS51 </h3>
<h3 align="center"> Profesor del Curso: Juan Carlos Tinoco Licas </h3>
<h3 align="center"> "INFORME DE TRABAJO FINAL"</h3>
<h3 align="center"> Nombre de Startup: InnoSoft </h3>
<h3 align="center"> Nombre del Producto:   </h3>

<div align="center">

| Miembro                        |   Código   |
| :----------------------------- | :--------: |
| Meza Camayo, Lynn Jeeferzon    | U20201C320 |
| Castilla Pachas, César Antonio |            |
| Serrano Uchuya, Gerald Patricio|            |
| Alvarado De La Cruz, Juan Carlos|            |
| Valera Garcés, Samuel Ignacio  |            |


</div>
<h3 align="center"> MAYO - 2024   </h3>

## REGISTRO DE VERSIONES

<div align="center">

| Versión  |   Fecha   |       Autor     |           Descripción de Modificación           |
|----------|-----------|-----------------|-------------------------------------------------|
|    0.1   | 03/04/25  |     Lynn Meza   | Creaccion Structura del informe                 |
|          |   |        |                  |
|       |   |        |                  |
</div>

## PROJECT REPORT COLLABORATION INSIGHTS

URL del respositorio de GitHub de la organización: [https://github.com/orgs/InnoSoft-1ASI0732-Diseno-Experimentos/repositories](https://github.com/orgs/InnoSoft-1ASI0732-Diseno-Experimentos/repositories)

## CONTENIDO

### Tabla de contenido

- [Part I: As-Is Software Project](#part-i-as-is-software-project)
- [Capítulo I: Introducción](#capítulo-i-introducción)
  - [1.1. Startup Profile](#11-startup-profile)
    - [1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)
    - [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
  - [1.2. Solution Profile](#12-solution-profile)
    - [1.2.1. Antecedentes y problemática](#121-antecedentes-y-problemática)
    - [1.2.2. Lean UX Process.](#122-lean-ux-process)
      - [1.2.2.1. Lean UX Problem Statements.](#1221-lean-ux-problem-statements)
      - [1.2.2.2. Lean UX Assumptions.](#1222-lean-ux-assumptions)
      - [1.2.2.3. Lean UX Hypothesis Statements.](#1223-lean-ux-hypothesis-statements)
      - [1.2.2.4. Lean UX Canvas.](#1224-lean-ux-canvas)
  - [1.3. Segmentos objetivo.](#13-segmentos-objetivo)
- [Chapter II: Requirements Elicitation \& Analysis](#chapter-ii-requirements-elicitation--analysis)
  - [2.1. Competidores](#21-competidores)
  - [2.1.1. Análisis competitivo](#211-análisis-competitivo)
  - [2.1.2. Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)
  - [2.2. Entrevistas](#22-entrevistas)
    - [2.2.1. Diseño de entrevistas](#221-diseño-de-entrevistas)
      - [Segmento 1: Compradores de Autos de Segunda Mano](#segmento-1-compradores-de-autos-de-segunda-mano)
      - [Segmento 2: Vendedores de Autos de Segunda Mano](#segmento-2-vendedores-de-autos-de-segunda-mano)
      - [Segmento 3: Talleres mecánicos encargados de revisiones](#segmento-3-talleres-mecánicos-encargados-de-revisiones)
  - [2.2.2. Registro de entrevistas.](#222-registro-de-entrevistas)
    - [**Segmento 1: Compradores de Autos de Segunda Mano**](#segmento-1-compradores-de-autos-de-segunda-mano-1)
    - [**Entrevistado 1:**](#entrevistado-1)
    - [**Entrevistado 2:**](#entrevistado-2)
    - [**Segmento 2: Vendedores de Autos de Segunda Mano**](#segmento-2-vendedores-de-autos-de-segunda-mano-1)
    - [**Entrevistado 1:**](#entrevistado-1-1)
    - [**Entrevistado 2:**](#entrevistado-2-1)
    - [**Entrevistado 3:**](#entrevistado-3)
  - [2.2.3. Análisis de entrevistas](#223-análisis-de-entrevistas)
  - [2.3. Needfinding.](#23-needfinding)
  - [2.3.1. User Personas.](#231-user-personas)
    - [Compradores de segunda mano:](#compradores-de-segunda-mano)
    - [Vendedores de segunda mano:](#vendedores-de-segunda-mano)
    - [Talleres mecánicos:](#talleres-mecánicos)
  - [2.3.2. User Task Matrix.](#232-user-task-matrix)
  - [2.3.3. User Journey Mapping.](#233-user-journey-mapping)
    - [Compradores de segunda mano:](#compradores-de-segunda-mano-1)
    - [Vendedores de segunda mano:](#vendedores-de-segunda-mano-1)
    - [Talleres mecánicos:](#talleres-mecánicos-1)
  - [2.3.4. Empathy Mapping.](#234-empathy-mapping)
    - [Compradores de segunda mano:](#compradores-de-segunda-mano-2)
    - [Vendedores de segunda mano:](#vendedores-de-segunda-mano-2)
    - [Talleres mecánicos:](#talleres-mecánicos-2)
  - [2.3.5. As-is Scenario Mapping](#235-as-is-scenario-mapping)
    - [Segmento Objetivo #1:  Compradores de autos de segunda mano (25-45 años)](#segmento-objetivo-1--compradores-de-autos-de-segunda-mano-25-45-años)
    - [Segmento Objetivo #2: Vendedores de autos de segunda mano (25-55 años)](#segmento-objetivo-2-vendedores-de-autos-de-segunda-mano-25-55-años)
    - [Segmento Objetivo #3:  Talleres mecánicos](#segmento-objetivo-3--talleres-mecánicos)
  - [2.4 Ubiquitous Language](#24-ubiquitous-language)
- [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)
  - [3.1. To-Be Scenario Mapping.](#31-to-be-scenario-mapping)
  - [3.2. User Stories.](#32-user-stories)
  - [3.3. Product Backlog.](#33-product-backlog)
  - [3.4. Impact Mapping.](#34-impact-mapping)
- [Capítulo IV: Product Design](#capítulo-iv-product-design)
  - [4.1. Style Guidelines.](#41-style-guidelines)
    - [4.1.1. General Style Guidelines.](#411-general-style-guidelines)
    - [4.1.2. Web Style Guidelines.](#412-web-style-guidelines)
    - [4.1.3. Mobile Style Guidelines.](#413-mobile-style-guidelines)
      - [4.1.3.1. iOS Mobile Style Guidelines.](#4131-ios-mobile-style-guidelines)
      - [4.1.3.2. Android Mobile Style Guidelines.](#4132-android-mobile-style-guidelines)
  - [4.2. Information Architecture.](#42-information-architecture)
    - [4.2.1. Organization Systems.](#421-organization-systems)
    - [4.2.2. Labeling Systems.](#422-labeling-systems)
    - [4.2.3. SEO Tags and Meta Tags](#423-seo-tags-and-meta-tags)
    - [4.2.4. Searching Systems.](#424-searching-systems)
    - [4.2.5. Navigation Systems.](#425-navigation-systems)
  - [4.3. Landing Page UI Design.](#43-landing-page-ui-design)
    - [4.3.1. Landing Page Wireframe.](#431-landing-page-wireframe)
    - [4.3.2. Landing Page Mock-up.](#432-landing-page-mock-up)
  - [4.4. Mobile Applications UX/UI Design.](#44-mobile-applications-uxui-design)
    - [4.4.1. Mobile Applications Wireframes.](#441-mobile-applications-wireframes)
    - [4.4.2. Mobile Applications Wireflow Diagrams.](#442-mobile-applications-wireflow-diagrams)
    - [4.4.3. Mobile Applications Mock-ups.](#443-mobile-applications-mock-ups)
    - [4.4.4. Mobile Applications User Flow Diagrams.](#444-mobile-applications-user-flow-diagrams)
  - [4.5. Mobile Applications Prototyping.](#45-mobile-applications-prototyping)
    - [4.5.1. Android Mobile Applications Prototyping.](#451-android-mobile-applications-prototyping)
    - [4.5.2. iOS Mobile Applications Prototyping.](#452-ios-mobile-applications-prototyping)
  - [4.6. Web Applications UX/UI Design.](#46-web-applications-uxui-design)
    - [4.6.1. Web Applications Wireframes.](#461-web-applications-wireframes)
    - [4.6.2. Web Applications Wireflow Diagrams.](#462-web-applications-wireflow-diagrams)
    - [4.6.3. Web Applications Mock-ups.](#463-web-applications-mock-ups)
    - [4.6.4. Web Applications User Flow Diagrams.](#464-web-applications-user-flow-diagrams)
  - [4.7. Web Applications Prototyping.](#47-web-applications-prototyping)
  - [4.8. Domain-Driven Software Architecture.](#48-domain-driven-software-architecture)
    - [4.8.1. Software Architecture Context Diagram.](#481-software-architecture-context-diagram)
    - [4.8.2. Software Architecture Container Diagrams.](#482-software-architecture-container-diagrams)
    - [4.8.3. Software Architecture Components Diagrams.](#483-software-architecture-components-diagrams)
  - [4.9. Software Object-Oriented Design.](#49-software-object-oriented-design)
    - [4.9.1. Class Diagrams.](#491-class-diagrams)
    - [4.9.2. Class Dictionary.](#492-class-dictionary)
  - [4.10. Database Design.](#410-database-design)
    - [4.10.1. Relational/Non-Relational Database Diagram.](#4101-relationalnon-relational-database-diagram)
- [Capítulo V: Product Implementation](#capítulo-v-product-implementation)
  - [5.1. Software Configuration Management.](#51-software-configuration-management)
    - [5.1.1. Software Development Environment Configuration.](#511-software-development-environment-configuration)
    - [5.1.2. Source Code Management.](#512-source-code-management)
    - [5.1.3. Source Code Style Guide \& Conventions.](#513-source-code-style-guide--conventions)
    - [5.1.4. Software Deployment Configuration.](#514-software-deployment-configuration)
  - [5.2. Product Implementation \& Deployment.](#52-product-implementation--deployment)
    - [5.2.1. Sprint Backlogs.](#521-sprint-backlogs)
    - [5.2.2. Implemented Landing Page Evidence](#522-implemented-landing-page-evidence)
    - [5.2.3. Implemented Frontend-Web Application Evidence](#523-implemented-frontend-web-application-evidence)
    - [5.2.4. Implemented Native-Mobile Application Evidence](#524-implemented-native-mobile-application-evidence)
    - [5.2.5. Implemented RESTful API and/or Serverless Backend Evidence](#525-implemented-restful-api-andor-serverless-backend-evidence)
    - [5.2.6. RESTful API documentation](#526-restful-api-documentation)
    - [5.2.7. Team Collaboration Insights](#527-team-collaboration-insights)
  - [5.3. Video About-the-Product.](#53-video-about-the-product)
- [Part II: Verification, Validation \& Pipeline](#part-ii-verification-validation--pipeline)
- [Capítulo VI: Product Verification \& Validation](#capítulo-vi-product-verification--validation)
  - [6.1. Testing Suites \& Validation](#61-testing-suites--validation)
    - [6.1.1. Core Entities Unit Tests.](#611-core-entities-unit-tests)
    - [6.1.2. Core Integration Tests.](#612-core-integration-tests)
    - [6.1.3. Core Behavior-Driven Development](#613-core-behavior-driven-development)
    - [6.1.4. Core System Tests.](#614-core-system-tests)
  - [6.2. Static testing \& Verification](#62-static-testing--verification)
    - [6.2.1. Static Code Analysis](#621-static-code-analysis)
      - [6.2.1.1. Coding standard \& Code conventions.](#6211-coding-standard--code-conventions)
      - [6.2.1.2. Code Quality \& Code Security.](#6212-code-quality--code-security)
    - [6.2.2. Reviews](#622-reviews)
  - [6.3. Validation Interviews.](#63-validation-interviews)
    - [6.3.1. Diseño de Entrevistas.](#631-diseño-de-entrevistas)
    - [6.3.2. Registro de Entrevistas.](#632-registro-de-entrevistas)
    - [6.3.3. Evaluaciones según heurísticas.](#633-evaluaciones-según-heurísticas)
  - [6.4. Auditoría de Experiencias de Usuario](#64-auditoría-de-experiencias-de-usuario)
    - [6.4.1. Auditoría realizada.](#641-auditoría-realizada)
      - [6.4.1.1. Información del grupo auditado.](#6411-información-del-grupo-auditado)
      - [6.4.1.2. Cronograma de auditoría realizada.](#6412-cronograma-de-auditoría-realizada)
      - [6.4.1.3. Contenido de auditoría realizada.](#6413-contenido-de-auditoría-realizada)
    - [6.4.2. Auditoría recibida.](#642-auditoría-recibida)
      - [6.4.2.1. Información del grupo auditor.](#6421-información-del-grupo-auditor)
      - [6.4.2.2. Cronograma de auditoría recibida.](#6422-cronograma-de-auditoría-recibida)
      - [6.4.2.3. Contenido de auditoría recibida.](#6423-contenido-de-auditoría-recibida)
      - [6.4.2.4. Resumen de modificaciones para subsanar hallazgos.](#6424-resumen-de-modificaciones-para-subsanar-hallazgos)
- [Capítulo VII: DevOps Practices](#capítulo-vii-devops-practices)
  - [7.1. Continuous Integration](#71-continuous-integration)
    - [7.1.1. Tools and Practices.](#711-tools-and-practices)
    - [7.1.2. Build \& Test Suite Pipeline Components.](#712-build--test-suite-pipeline-components)
  - [7.2. Continuous Delivery](#72-continuous-delivery)
    - [7.2.1. Tools and Practices.](#721-tools-and-practices)
    - [7.2.2. Stages Deployment Pipeline Components.](#722-stages-deployment-pipeline-components)
  - [7.3. Continuous deployment](#73-continuous-deployment)
    - [7.3.1. Tools and Practices.](#731-tools-and-practices)
    - [7.3.2. Production Deployment Pipeline Components.](#732-production-deployment-pipeline-components)
  - [7.4. Continuous Monitoring](#74-continuous-monitoring)
    - [7.4.1. Tools and Practices](#741-tools-and-practices)
    - [7.4.2. Monitoring Pipeline Components](#742-monitoring-pipeline-components)
    - [7.4.3. Alerting Pipeline Components](#743-alerting-pipeline-components)
    - [7.4.4. Notification Pipeline Components.](#744-notification-pipeline-components)
- [Part III: Experiment-Driven Lifecycle](#part-iii-experiment-driven-lifecycle)
- [Capítulo VIII: Experiment-Driven Development](#capítulo-viii-experiment-driven-development)
  - [8.1. Experiment Planning](#81-experiment-planning)
    - [8.1.1. As-Is Summary.](#811-as-is-summary)
    - [8.1.2. Raw Material: Assumptions, Knowledge Gaps, Ideas, Claims.](#812-raw-material-assumptions-knowledge-gaps-ideas-claims)
    - [8.1.3. Experiment-Ready Questions.](#813-experiment-ready-questions)
    - [8.1.4. Question Backlog.](#814-question-backlog)
    - [8.1.5. Experiment Cards.](#815-experiment-cards)
  - [8.2. Experiment Design](#82-experiment-design)
    - [8.2.1. Hypotheses.](#821-hypotheses)
    - [8.2.2. Measures.](#822-measures)
    - [8.2.3. Conditions.](#823-conditions)
    - [8.2.4. Scale Calculations and Decisions.](#824-scale-calculations-and-decisions)
    - [8.2.5. Methods Selection.](#825-methods-selection)
    - [8.2.6. Data Analytics: Goals, KPIs and Metrics Selection.](#826-data-analytics-goals-kpis-and-metrics-selection)
    - [8.2.7. Web and Mobile Tracking Plan.](#827-web-and-mobile-tracking-plan)
  - [8.3. Experimentation](#83-experimentation)
    - [8.3.1. To-Be User Stories.](#831-to-be-user-stories)
    - [8.3.2. To-Be Product Backlog](#832-to-be-product-backlog)
    - [8.3.3. Pipeline-supported, Experiment-Driven To-Be Software Platform Lifecycle](#833-pipeline-supported-experiment-driven-to-be-software-platform-lifecycle)
      - [8.3.3.1. To-Be Sprint Backlogs](#8331-to-be-sprint-backlogs)
      - [8.3.3.2. Implemented To-Be Landing Page Evidence](#8332-implemented-to-be-landing-page-evidence)
      - [8.3.3.3. Implemented To-Be Frontend-Web Application Evidence](#8333-implemented-to-be-frontend-web-application-evidence)
      - [8.3.3.4. Implemented To-Be Native-Mobile Application Evidence](#8334-implemented-to-be-native-mobile-application-evidence)
      - [8.3.3.5. Implemented To-Be RESTful API and/or Serverless Backend Evidence](#8335-implemented-to-be-restful-api-andor-serverless-backend-evidence)
      - [8.3.3.6. Team Collaboration Insights](#8336-team-collaboration-insights)
    - [8.3.4. To-Be Validation Interviews](#834-to-be-validation-interviews)
      - [8.3.4.1. Diseño de Entrevistas.](#8341-diseño-de-entrevistas)
      - [8.3.4.2. Registro de Entrevistas.](#8342-registro-de-entrevistas)
  - [8.4. Experiment Aftermath \& Analysis](#84-experiment-aftermath--analysis)
    - [8.4.1. Analysis and Interpretation of Results](#841-analysis-and-interpretation-of-results)
    - [8.4.2. Re-scored and Re-prioritized Question Backlog](#842-re-scored-and-re-prioritized-question-backlog)
  - [8.5. Continuous Learning](#85-continuous-learning)
    - [8.5.1. Shareback Session Artifacts: Learning Workflow](#851-shareback-session-artifacts-learning-workflow)
  - [8.6. To-Be Software Platform Pre-launch](#86-to-be-software-platform-pre-launch)
    - [8.6.1. About-the-Product Intro Video](#861-about-the-product-intro-video)
- [Conclusiones](#conclusiones)
  - [Conclusiones y recomendaciones.](#conclusiones-y-recomendaciones)
- [Video About-the-Team.](#video-about-the-team)
- [Bibliografía](#bibliografía)
- [Anexos](#anexos)

## STUDENT OUTCOME

<table center>
  <tr>
    <th>CRITERIO ESPECIFICO</th>
    <th>ACCIONES REALIZADAS</th>
    <th>CONCLUSIONES</th>
  </tr>
  <tr>
    <th>4.c.1 Reconoce responsabilidad etica y profesional en situaciones de ingeneria de software</th>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <th>4.c.2 Emite juicios informados considerando el impacto de las soluciones de ingeniería de software en contextos globales, económicos, ambientales y sociales</th>
    <td></td>
    <td></td>
  </tr>
</table>

# Part I: As-Is Software Project
# Capítulo I: Introducción
## 1.1. Startup Profile
### 1.1.1. Descripción de la Startup
### 1.1.2. Perfiles de integrantes del equipo
## 1.2. Solution Profile
### 1.2.1. Antecedentes y problemática
### 1.2.2. Lean UX Process.
#### 1.2.2.1. Lean UX Problem Statements.
#### 1.2.2.2. Lean UX Assumptions.
#### 1.2.2.3. Lean UX Hypothesis Statements.
#### 1.2.2.4. Lean UX Canvas.
## 1.3. Segmentos objetivo.
# Chapter II: Requirements Elicitation & Analysis

## 2.1. Competidores

Nuestros competidores abarcan una variedad de empresas en el mercado de autos de segunda mano, que se han ido fortaleciendo a lo largo del tiempo en plataformas digitales. Esto abarca grandes sitios webs de venta de vehículos usados.

Aquí unos competidores directos que proporcionan servicios similares al nuestro:


- **NeoAuto**: [NeoAuto](https://neoauto.com/venta-de-autos-usados-en-lima?gad_source=1&gclid=Cj0KCQjw_sq2BhCUARIsAIVqmQtS4NTpmRTLgjG9aqoxczpnBP_zQPfrGnqWX53OOE22ruL_N90cup8aAvHuEALw_wcB)

  NeoAuto es una plataforma en línea disponible para web y dispositivos móviles que facilita la compra y venta de autos de segunda mano. Fundada por un equipo de innovadores peruanos, NeoAuto ha logrado posicionarse como uno de los líderes en el mercado automotriz de segunda mano en Perú. La plataforma permite a los usuarios acceder a una amplia variedad de vehículos usados, todos verificados para garantizar su calidad y confiabilidad. Gracias a su gran aceptación, NeoAuto se ha expandido y ahora es un referente en el sector automotriz en el país, ayudando a miles de peruanos a encontrar su auto ideal.

<br><br>
- **AUTOLAND Perú**: [AutoLand Perú](https://autoland.com.pe/seminuevos/)

  AutoLand Perú es un portal en línea especializado en la compra y venta de vehículos de segunda mano, accesible tanto desde su sitio web como desde su aplicación móvil. Fundado por un grupo de expertos en el sector automotriz peruano, AutoLand Perú se ha destacado por ofrecer una plataforma confiable y segura para transacciones de autos usados. La plataforma permite a los usuarios explorar una extensa selección de vehículos, todos sometidos a rigurosas inspecciones para asegurar su calidad. Gracias a su enfoque en la satisfacción del cliente, AutoLand Perú se ha consolidado como una de las opciones preferidas en el mercado de autos de segunda mano en el país.

<br><br>
- **Autopia.pe**: [Autopia.pe](https://www.autopia.pe)

  Autopia.pe es una plataforma digital especializada en la compra y venta de autos de segunda mano, diseñada para brindar a los usuarios una experiencia simple y segura. Fundada por un equipo de emprendedores peruanos apasionados por el sector automotriz, Autopia.pe se ha posicionado rápidamente como una opción confiable para quienes buscan vehículos usados en Perú. La plataforma ofrece una amplia gama de autos, todos inspeccionados y certificados para garantizar su estado y calidad. Gracias a su enfoque en la transparencia y la satisfacción del cliente, Autopia.pe se ha convertido en una referencia clave en el mercado automotriz de segunda mano en el país.
  <br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>

## 2.1.1. Análisis competitivo
<table>
 <tr>
    <th colspan="6">Competitive Analysis Landscape</th>
  </tr>
  <tr>
  <th>¿Por qué llevar a cabo este análisis?</th>
    <td colspan="6"> Realizaremos un análisis competitivo porque es muy importante identificar oportunidades de diferenciación, entender las fortalezas y debilidades de los competidores, y adaptar la estrategia para posicionar mejor la plataforma en el mercado.</td>
  </tr>
  <tr>
    <th></th>
    <th></th>
    <th>Car2Go</th>
    <th>NeoAuto</th>
    <th>AutoLand Perú</th>
    <th>Autopia.pe</th>
  </tr>
  <tr>
    <th rowspan="2">Perfil</th>
    <td><strong>Overview</strong></td>
    <td>Plataforma de compra y venta de autos de segunda mano con un fuerte énfasis en la verificación y certificación de datos.</td>
    <td>Plataforma en línea para la compra y venta de autos de segunda mano en Perú, con una sólida presencia en el mercado.</td>
    <td>Plataforma especializada en la compra y venta de vehículos usados, con un énfasis en la confiabilidad y seguridad de las transacciones.</td>
    <td>Plataforma digital enfocada en la simplicidad y seguridad de la compra y venta de autos de segunda mano.</td>
  </tr>
  <tr>
    <td><strong>Ventaja competitiva ¿Qué valor ofrece a los clientes?</strong></td>
    <td>Seguridad y confianza al comprar, sabiendo que todos los datos y fotos están verificados y actualizados regularmente. Ahorran tiempo al evitar pasos adicionales de verificación.</td>
    <td>Acceso a una gran cantidad de opciones y confianza en una plataforma bien establecida.</td>
    <td>Tranquilidad al saber que los autos han pasado por un proceso de inspección.</td>
    <td>Proceso de compra sencillo y seguro, con una selección de vehículos que han sido inspeccionados.</td>
  </tr>
  <tr>
    <th rowspan="2">Perfil de Marketing</th>
    <td><strong>Mercado objetivo</strong></td>
    <td>Compradores y vendedores de autos de segunda mano que buscan seguridad y confianza en su adquisición.</td>
    <td>Consumidores peruanos interesados en comprar o vender autos usados a través de una plataforma confiable.</td>
    <td>Consumidores peruanos que priorizan la seguridad y confiabilidad en la compra de un auto de segunda mano.</td>
    <td>Usuarios que buscan una plataforma fácil de usar para comprar o vender autos usados, con énfasis en la transparencia y satisfacción del cliente.</td>
  </tr>
  <tr>
    <td><strong>Estrategias de marketing</strong></td>
    <td>Campañas focalizadas en redes sociales y Google ads, orientadas a personas que buscan comprar un auto usado.</td>
    <td>Campañas de branding en televisión, radio y redes sociales para mantener la visibilidad de la marca a nivel nacional.</td>
    <td>Anuncios en prensa, radio y televisión local que resalten la confiabilidad y las rigurosas inspecciones de los autos en venta.</td>
    <td>Campañas en redes sociales enfocadas a un público más joven, destacando la facilidad de uso y la transparencia de la plataforma.</td>
  </tr>
  <tr>
    <th rowspan="3">Perfil de Producto</th>
    <td><strong>Productos & Servicios</strong></td>
    <td>Autos verificados y certificados mensualmente, con asesoría personalizada.</td>
    <td>Amplio catálogo de autos usados, con servicios adicionales como financiamiento y seguros.</td>
    <td>Autos usados con inspecciones rigurosas y garantía limitada.</td>
    <td>Autos seleccionados con inspección única al momento de la publicación, enfocados en la transparencia.</td>
  </tr>
  <tr>
    <td><strong>Precios & Costos</strong></td>
    <td>Precios medio-altos debido a las certificaciones mensuales; costos operativos elevados por las inspecciones regulares.</td>
    <td>Variedad de precios, desde opciones económicas hasta de alta gama; costos moderados por verificación básica.</td>
    <td>Precios competitivos con un enfoque en el valor a través de la calidad; costos relacionados con inspecciones detalladas.</td>
    <td>Precios variados con enfoque en la transparencia; costos de mantenimiento digital y una única certificación inicial.</td>
  </tr>
  <tr>
    <td><strong>Canales de distribución (Web y/o Móvil)</strong></td>
    <td>Distribución digital a través de web y app, con apoyo de talleres asociados.</td>
    <td>Distribución principal en su sitio web y aplicación móvil, con apoyo de socios financieros.</td>
    <td>Distribución en línea y en puntos de venta físicos.</td>
    <td>Distribución digital a través de su sitio web y app, con atención al cliente en línea.</td>
  </tr>
  <tr>
    <th rowspan="4">Análisis SWOT</th>
    <td><strong>Fortalezas</strong></td>
    <td>Verificación y certificación mensual de vehículo, lo que garantiza alta confianza y seguridad para el comprador.</td>
    <td>Amplia oferta de vehículos y sólida presencia en el mercado, con servicios adicionales como financiamiento.</td>
    <td>Inspecciones rigurosas y garantía limitada que refuerzan la calidad y seguridad de los autos vendidos.</td>
    <td>Transparencia en la información del vehículo y proceso de compra simplificado.</td>
  </tr>
  <tr>
    <td><strong>Debilidades</strong></td>
    <td>Costos operativos altos debido a las inspecciones mensuales, lo que puede traducirse en precios más altos para los usuarios.</td>
    <td>Menor enfoque en la verificación continua de datos, lo que puede generar dudas sobre la autenticidad de la información.</td>
    <td>Dependencia de puntos de venta físicos puede limitar el alcance y la comodidad en comparación con plataformas digitales puras.</td>
    <td>Inspección única puede no ofrecer el mismo nivel de garantía continua que la verificación mensual de Car2Go.</td>
  </tr>
  <tr>
    <td><strong>Oportunidades</strong></td>
    <td>Expansión de otros mercados que valoren la verificación continua y el valor añadido de vehículos certificados.</td>
    <td>Expansión de servicios adicionales como seguros y financiamiento para atraer a más compradores.</td>
    <td>Potencial para integrar más tecnología y herramientas digitales para mejorar la experiencia del usuario.</td>
    <td>Ampliar la oferta de servicios adicionales y mejorar la frecuencia de inspección para competir con plataformas que ofrezcan verificación continua.</td>
  </tr>
  <tr>
    <td><strong>Amenazas</strong></td>
    <td>Competencia de plataformas con menores costos operativos y precios más bajos que no ofrecen verificación continua.</td>
    <td>Riesgo de pérdida de credibilidad si no se mejora la verificación de datos frente a competidores más transparentes.</td>
    <td>Competencia creciente de plataformas digitales que ofrecen una experiencia más ágil y moderna.</td>
    <td>Riesgo de quedar atrás si no se actualizan las prácticas de verificación y certificación para igualar a competidores con procesos más exhaustivos.</td>
  </tr>
</table>

## 2.1.2. Estrategias y tácticas frente a competidores

<table style="width:100%">
  <thead>
    <tr>
      <th>Categoría</th>
      <th>Estrategias y Tácticas</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>Oportunidades</strong></td>
      <td>- O1: Verificación continua<br>- O2: Expansión de mercado<br>- O3: Alianzas estratégicas<br>- O4: Valor añadido de servicios adicionales</td>
    </tr>
    <tr>
      <td><strong>Amenazas</strong></td>
      <td>- A1: Competencia de precios bajos<br>- A2: Plataforma digital de competencia<br>- A3: Mayor alcance y visibilidad</td>
    </tr>
    <tr>
      <td><strong>Fortalezas</strong></td>
      <td>- F1: Garantía de calidad<br>- F2: Seguridad al comprador<br>- F3: Proceso de compra simplificado<br>- F4: Credibilidad de información</td>
    </tr>
    <tr>
      <td><strong>Estrategias FO (Ofensivas)</strong></td>
      <td>- FO1: Promoción de verificación continua<br>- FO2: Expansión a nuevos mercados</td>
    </tr>
    <tr>
      <td><strong>Estrategias FA (Defensivas)</strong></td>
      <td>- FA1: Fortalecimiento de la experiencia del usuario<br>- FA2: Mejora continua en el proceso de verificación<br>- FA3: Mantenimiento de precios competitivos</td>
    </tr>
    <tr>
      <td><strong>Debilidades</strong></td>
      <td>- D1: Costos operativos<br>- D2: Menor flexibilidad<br>- D3: Menor alcance de mercado</td>
    </tr>
    <tr>
      <td><strong>Estrategias DO (Reorientación)</strong></td>
      <td>- DO1: Optimización de costos operativos<br>- DO2: Expansión digital</td>
    </tr>
    <tr>
      <td><strong>Estrategias DA (Supervivencia)</strong></td>
      <td>- DA1: Ajuste de precios<br>- DA2: Reducción de costos<br>- DA3: A</td>
    </tr>
  </tbody>
</table>

## 2.2. Entrevistas

### 2.2.1. Diseño de entrevistas

#### Segmento 1: Compradores de Autos de Segunda Mano
1. ¿Cuáles son los factores más importantes para ti al comprar un auto de segunda mano?
2. ¿Qué tipo de información consideras imprescindible antes de decidirte a comprar un vehículo?
3. ¿Cómo sueles verificar la credibilidad del vendedor y el estado del vehículo?
4. ¿Te sentirías más seguro si el auto tuviera un historial de revisiones verificadas por talleres?
5. ¿Qué tan importante es para ti la transparencia en la información del vehículo (kilometraje, accidentes previos, etc.)?
6. ¿Estarías dispuesto a pagar más por un auto con datos verificables y reportes de un taller confiable?
7. ¿Qué dificultades has enfrentado en el pasado al intentar comprar un auto usado?
8. ¿Qué tan cómodo te sientes utilizando aplicaciones o plataformas en línea para comprar vehículos?
9. ¿Qué funciones adicionales te gustaría ver en una plataforma que te conecte con vendedores de autos usados?
10. ¿Confías más en un vendedor particular o en concesionarios al comprar autos de segunda mano? ¿Por qué?

#### Segmento 2: Vendedores de Autos de Segunda Mano
1. ¿Cuáles son los principales desafíos que enfrentas al vender un auto de segunda mano?
2. ¿Cómo sueles garantizar la credibilidad y confiabilidad de la información que proporcionas a los compradores?
3. ¿Qué tan dispuesto estarías a someter tu vehículo a una revisión en un taller para obtener un reporte verificable?
4. ¿Crees que la existencia de un historial de revisiones ayudaría a vender más rápido tu vehículo?
5. ¿Qué información consideras clave para atraer a compradores potenciales?
6. ¿Qué tan cómodo te sentirías subiendo y compartiendo datos detallados y verificados del vehículo en una plataforma en línea?
7. ¿Cómo evalúas el impacto de una plataforma que asegure la veracidad de los datos en el proceso de venta de tu vehículo?
8. ¿Cuáles son tus expectativas en cuanto al tiempo que te toma vender un auto? ¿Crees que esta plataforma podría acelerarlo?
9. ¿Qué tan dispuesto estarías a pagar una tarifa adicional por servicios que aumenten la confianza del comprador?
10. ¿Qué características o servicios adicionales te gustaría que ofreciera una plataforma dedicada a la venta de autos de segunda mano?

#### Segmento 3: Talleres mecánicos encargados de revisiones
1.  ¿Cuál es tu nivel de experiencia en realizar inspecciones y revisiones para la venta de autos de segunda mano?
2.  ¿Qué tipos de revisiones crees que son esenciales para garantizar la calidad y seguridad de un vehículo usado?
3.  ¿Qué tan interesado estarías en asociarte con una plataforma que te conecte con vendedores que buscan revisiones pagadas?
4.  ¿Qué tipo de certificaciones o informes sueles emitir después de realizar una inspección completa?
5.  ¿Cómo garantizarías la precisión y objetividad en los datos que proporcionas sobre un vehículo?
6.  ¿Qué tipos de revisiones o servicios adicionales te gustaría ofrecer a través de una plataforma de venta de autos?
7.  ¿Cómo gestionarías la demanda de revisiones si el volumen de solicitudes aumenta debido a la asociación con la plataforma?
8.  ¿Qué tan importante es para ti mantener una buena reputación y confianza entre compradores y vendedores?
9.  ¿Cómo valorarías la oportunidad de aumentar tus ingresos a través de estas revisiones pagadas?
10. ¿Qué consideraciones adicionales tendrías al integrarte en una plataforma que busca asegurar la credibilidad de los autos en venta?

<br><br><br><br>
## 2.2.2. Registro de entrevistas.

### **Segmento 1: Compradores de Autos de Segunda Mano**

### **Entrevistado 1:**
- **Nombre y Apellido:** Piero Ricaldi Solis
- **Edad:** 23 años
- **Tiempo de la entrevista:** 2:48
- **Evidencia de la reunión:**
  <br><br>

  <div align=center>
    <img src="./assets/Entrevista_Piero.png" alt="Entrevista Mijael" width="800"/>
  </div>
<br><br>

- **URL del video:** <https://upcedupe-my.sharepoint.com/:v:/g/personal/u20201c320_upc_edu_pe/EQtn_9T6rBpCtL5UbA802LQBJMlBk9RKEmm_UDCCrcZYZg?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D&e=42NQEh>
  <br><br>
- **Informe de Resumen sobre la entrevista:**

  Piero Ricaldi Solis, nos comenta que los factores principales para que compre un auto este en buen estado, conocer su historial de mantenimiento y si tuvo accidentes. Por ello, siempre pide llevar a un mecánico para verificar su estado. El indica que se sentiría cómodo si hubiera una plataforma que brinde todos los factores que la ve que es necesario para la compra de auto.

---
<br><br><br><br><br><br><br><br><br><br><br><br>

### **Entrevistado 2:**
- **Nombre y Apellido:** Ariana Quiñones
- **Edad:** 25 años
- **Tiempo de la entrevista:** 3:34
- **Evidencia de la reunión:**
  <br><br>

  <div align=center>
    <img src="assets/Entrevista_Ariana.png" alt="Entrevista Mijael" width="800"/>
  </div>
<br><br>

- **URL del video:** <https://upcedupe-my.sharepoint.com/:v:/g/personal/u202111952_upc_edu_pe/EcZzvgGJOyxKqQTOXEenuD4BJvtPrntKl-Tm1przfoEL-g?e=iGw7pW>
  <br><br>
- **Informe de Resumen sobre la entrevista:**

  Ariana Quiñones, emprendedora de 25 años, habló sobre su interés en comprar autos usados. Destaca la importancia de la confianza en el vendedor, los registros en regla, el historial de mantenimiento, y la verificación en talleres certificados. Prefiere comprar en concesionarios por la seguridad que ofrecen y estaría dispuesta a pagar más por un auto con
  información transparente. También considera útiles las plataformas online que faciliten contacto directo con el vendedor y den seguimiento postventa.


---
<br><br><br><br><br><br><br><br><br><br><br><br>

### Entrevistado 3:
- Nombre y Apellido: Joan Teves
- Edad: 26 años
- Tiempo de la entrevista: 3:22
- Evidencia de la reunión:
  <br><br>

  <div align=center>
    <img src="assets/Entrevista_Joan.png" alt="Entrevista Mijael" width="800"/>
  </div>
<br><br>

- URL del video: <https://upcedupe-my.sharepoint.com/:v:/g/personal/u202216150_upc_edu_pe/ET3RfpgE0qtEriq6mNOAshQB5-9tT4T_lDtaoaJwQQecxg?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=W4fcwE>
  <br><br>
- Informe de Resumen sobre la entrevista:

  Joan prioriza el estado mecánico, kilometraje, historial de accidentes y reputación del vendedor al comprar un auto de segunda mano. Necesita información clara sobre mantenimiento, kilometraje real, accidentes, dueños anteriores y deudas. Para verificar, revisa documentos oficiales y a veces lleva un mecánico de confianza.

Destaca que la transparencia es clave y estaría dispuesto a pagar más por un auto con historial técnico verificado. Aunque usa plataformas online para buscar opciones, prefiere que haya validaciones confiables. Confía más en concesionarios, pero también considera particulares si todo está en regla.


---
<br><br><br><br><br><br><br><br><br><br><br><br>

### **Segmento 2: Vendedores de Autos de Segunda Mano**

### **Entrevistado 1:**
- **Nombre y Apellido:** Carlos Alberto
- **Edad:** 26 años
- **Tiempo de la entrevista:** 4:45
- **Evidencia de la reunión:**
  <br><br>

  <div align=center>
    <img src="./assets/entrevista_Clinder.png" alt="Entrevista Mijael" width="800"/>
  </div>
<br><br>

- **URL del video:** <https://upcedupe-my.sharepoint.com/:v:/g/personal/u20201c320_upc_edu_pe/ETJOQGQPtd5Ci0nMhu6505EBvhdlegMbiaLTdhGkFiyGAQ?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D&e=UdJMcj>
  <br><br>
- **Informe de Resumen sobre la entrevista:**

Carlos Alberto, emprender del rubro de venta de autos usados. Nos indica que el mejor punto en ventas de autos el tener la confianza de los compradores, uno de esta confianza es de que no tenga fallas los autos, pero lo principal es mostrando el historial de los autos, como las revisiones y los mantenimientos estén documentados. Además, considera genial utilizar plataformas porque ayuda vender autos más rápidos.

---
<br><br><br><br><br><br><br><br><br><br><br><br>

### **Entrevistado 2:**
- **Nombre y Apellido:** Gonzalo Carhuancote
- **Edad:** 27 años
- **Tiempo de la entrevista:** 3:26
- **Evidencia de la reunión:**
  <br><br>

  <div align=center>
    <img src="assets/entrevista Gonzalo.png" alt="Entrevista Gonzalo" width="800"/>
  </div>
<br><br>

- **URL del video:** [https://upcedupe-my.sharepoint.com/:v:/g/personal/u202216150_upc_edu_pe/ESSfgeVbn0RMmZWCS8jYbRgBKpuGSSry0eVl3E2Fwhq6QA?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=y3t3Cc](link)
  <br><br>
- **Informe de Resumen sobre la entrevista:**

  El principal reto al vender un auto de segunda mano es generar confianza. Para lograrlo, el vendedor muestra documentos, historial de mantenimiento y permite revisiones técnicas. Cree que un historial verificable acelera la venta y está dispuesto a compartir información en plataformas seguras y pagar tarifas adicionales si mejoran la confianza. Sugiere que las plataformas ofrezcan verificación técnica, asesoría legal, financiamiento y valoraciones basadas en experiencias reales.

---
<br><br><br><br><br><br><br><br><br><br><br><br>

### **Entrevistado 3:**
- **Nombre y Apellido:** Mijael Yen
- **Edad:** 22 años
- **Tiempo de la entrevista:** 8:46
- **Evidencia de la reunión:**
  <br><br>

  <div align=center>
    <img src="assets/Entrevista_Mijael.png" alt="Entrevista Mijael" width="800"/>
  </div>
<br><br>

- **URL del video:** [(Link Entrevista)]([link](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202122876_upc_edu_pe/EQthj2hJ9ItIsxTMuQdwZVIBKDh7E9d098j54Xed3wRA_g?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D&e=qlCcdZ))
  <br><br>
- **Informe de Resumen sobre la entrevista:**

  Mijael Yen, de 22 años, es analista de ciberseguridad y vendedor ocasional de autos junto a su padre. Explicó que uno de los mayores desafíos al vender autos de segunda mano es generar confianza con los compradores, ya que la venta implica una inversión significativa. Por ello, Mijael enfatiza la importancia de proporcionar toda la documentación del auto, incluyendo certificados de revisión técnica y detalles sobre reparaciones. Comentó que un comprador informado y que tiene acceso a los antecedentes del auto es más probable que confíe en la venta, lo que agiliza el proceso.



---
<br><br><br><br><br><br><br><br><br><br><br><br>


## 2.2.3. Análisis de entrevistas
**Segmento objetivo: Compradores de Autos de Segunda Mano**

Analisis de entrevista Compradores 3:
En la entrevista, Ariana representa al comprador joven que prioriza la confianza y la transparencia en las transacciones de autos usados. Su interés en registros verificables y su preferencia por concesionarios reflejan una necesidad de seguridad jurídica y técnica. También muestra apertura a plataformas digitales, siempre que éstas ofrezcan acompañamiento posterior a la compra. Esto indica una oportunidad para el mercado online de autos usados si fortalece garantías, historial verificado y soporte al cliente.
**Segmento objetivo: Vendedores de Autos de Segunda Mano**

Mijael Yen y Jefrey Sanchez coincidieron en que la desconfianza de los compradores es el principal desafío al intentar vender autos de segunda mano. Ambos destacaron la importancia de proporcionar documentación que garantice la autenticidad del estado del vehículo. Mijael ve en la transparencia una oportunidad para generar confianza con el comprador, mientras que Jefrey considera que establecer un precio justo es clave para acelerar la venta. El análisis muestra que la confianza y una comunicación clara sobre el estado del auto son factores determinantes en el éxito de una venta.

<br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>
## 2.3. Needfinding.
## 2.3.1. User Personas.

### Compradores de segunda mano:

<img src="assets/UserPersona_Comprador.png">



### Vendedores de segunda mano:

<img src="assets/UserPersona_Vendedor.jpg">

<br><br><br><br><br><br>

### Talleres mecánicos:

<img src="assets/UserPersona_Talleres.png">
<br><br><br><br>


## 2.3.2. User Task Matrix.

A continuación, presentaremos los User Task Matrix de los segmentos objetivos que encontramos.

<table>
 <tr>
    <th>Task Matrix</th>
    <th colspan="2">Vendedor de autos</th>
    <th colspan="2">Comprador de autos</th>
  </tr>
  <tr>
    <th></th>
    <th>Frecuencia</th>
    <th>Importancia</th>
    <th>Frecuencia</th>
    <th>Importancia</th>

  </tr>
  <tr>
    <th>Inspeccionar la pintura del vehículo</th>
    <th>Alta</th>
    <th>Alta</th>
    <th>Alta</th>
    <th>Alta</th>
  </tr>
  <tr>
    <th>Revisar el kilometraje</th>
    <th>Alta</th>
    <th>Alta</th>
    <th>Alta</th>
    <th>Alta</th>
  </tr>
  <tr>
    <th>Revisar el historial de mantenimiento</th>
    <th>Media</th>
    <th>Alta</th>
    <th>Alta</th>
    <th>Alta</th>

  </tr>
  <tr>
    <th>Evaluar el interior del vehículo</th>
    <th>Alta</th>
    <th>Media</th>
    <th>Alta</th>
    <th>Media</th>
  </tr>
  <tr>
    <th>Verificar el funcionamiento del motor</th>
    <th>Media</th>
    <th>Alta</th>
    <th>Alta</th>
    <th>Alta</th>
  </tr>
  <tr>
    <th>Comprobar el sistema de frenos</th>
    <th>Media</th>
    <th>Alta</th>
    <th>Alta</th>
    <th>Alta</th>
  </tr>
  <tr>
    <th>Verificar los documentos legales</th>
    <th>Alta</th>
    <th>Alta</th>
    <th>Alta</th>
    <th>Alta</th>
  </tr>
  <tr>
    <th>Revisar el estado de la batería</th>
    <th>Media</th>
    <th>Media</th>
    <th>Media</th>
    <th>Media</th>
  </tr>
  <tr>
    <th>Verificar las llantas y la suspensión</th>
    <th>Media</th>
    <th>Alta</th>
    <th>Alta</th>
    <th>Alta</th>
  </tr>
  <tr>
    <th>Revisar posibles fugas de fluidos</th>
    <th>Baja</th>
    <th>Media</th>
    <th>Media</th>
    <th>Alta</th>
  </tr>
</table>

Podemos ver que hay muchas actividades que comparten los 2 segmentos sin embargo se diferencian en ciertas partes técnicas, como el mecánico, y estética, en cuanto a los vendedores y compradores.
<br><br><br><br>

## 2.3.3. User Journey Mapping.

### Compradores de segunda mano:

<img src="assets/Journey_Comprador.png">
<br><br><br><br><br><br><br><br>

### Vendedores de segunda mano:

<img src="assets/Journey_Vendedor.png">

### Talleres mecánicos:

<img src="assets/Journey_Talleres.png">
<br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>

## 2.3.4. Empathy Mapping.

### Compradores de segunda mano:

<img src="assets/Empathy_Comprador.png">
<br><br><br><br><br><br>

### Vendedores de segunda mano:

<img src="assets/Empathy_Vendedor.png">

<br><br><br><br><br><br><br><br><br><br><br><br><br>

### Talleres mecánicos:

<img src="assets/Empathy_Talleres.png">
<br><br><br><br><br><br><br><br><br>

## 2.3.5. As-is Scenario Mapping

### Segmento Objetivo #1:  Compradores de autos de segunda mano (25-45 años)

<img src="assets/As-Is_Comprador.png">

### Segmento Objetivo #2: Vendedores de autos de segunda mano (25-55 años)

<img src="assets/As-Is_Vendedor.png">


[LINK DEL MIRO](https://miro.com/app/board/uXjVMm70eUI=/?share_link_id=313743584808)
<br><br>

## 2.4 Ubiquitous Language

1. **Comprador:** Persona que está interesada en adquirir un auto de segunda mano.

2. **Vendedor:** Persona que ofrece su auto para la venta en la plataforma.

3. **Auto Verificado:** Vehículo que ha pasado por una inspección técnica realizada por un taller mecánico asociado.

4. **Taller Mecánico:** Entidad o empresa encargada de revisar y certificar el estado de los autos listados en la plataforma.

5. **Transacción Segura:** Proceso de compra-venta en el que se utiliza el sistema de pagos de la plataforma para asegurar que ambas partes cumplan con sus compromisos.

6. **Anuncio Destacado:** Publicación que aparece en la parte superior de los resultados de búsqueda para mejorar la visibilidad del auto que está en venta.

7. **Inspección Técnica:** Proceso mediante el cual un taller verifica el estado del auto en términos de mecánica, carrocería, y documentación.

8. **Historial del Auto:** Registro de los eventos relevantes asociados al vehículo, como reparaciones, multas o accidentes anteriores.

9. **Kilometraje:** Distancia total recorrida por el auto, un indicador clave del desgaste del vehículo.
# Capítulo III: Requirements Specification
## 3.1. To-Be Scenario Mapping.
## 3.2. User Stories.
## 3.3. Product Backlog.
## 3.4. Impact Mapping.
# Capítulo IV: Product Design
## 4.1. Style Guidelines.
### 4.1.1. General Style Guidelines.
### 4.1.2. Web Style Guidelines.
### 4.1.3. Mobile Style Guidelines.
#### 4.1.3.1. iOS Mobile Style Guidelines.
#### 4.1.3.2. Android Mobile Style Guidelines.
## 4.2. Information Architecture.
### 4.2.1. Organization Systems.
### 4.2.2. Labeling Systems.
### 4.2.3. SEO Tags and Meta Tags
### 4.2.4. Searching Systems.
### 4.2.5. Navigation Systems.
## 4.3. Landing Page UI Design.
### 4.3.1. Landing Page Wireframe.
### 4.3.2. Landing Page Mock-up.
## 4.4. Mobile Applications UX/UI Design.
### 4.4.1. Mobile Applications Wireframes.
### 4.4.2. Mobile Applications Wireflow Diagrams.
### 4.4.3. Mobile Applications Mock-ups.
### 4.4.4. Mobile Applications User Flow Diagrams.
## 4.5. Mobile Applications Prototyping.
### 4.5.1. Android Mobile Applications Prototyping.
### 4.5.2. iOS Mobile Applications Prototyping.
## 4.6. Web Applications UX/UI Design.
### 4.6.1. Web Applications Wireframes.
### 4.6.2. Web Applications Wireflow Diagrams.
### 4.6.3. Web Applications Mock-ups.
### 4.6.4. Web Applications User Flow Diagrams.
## 4.7. Web Applications Prototyping.
## 4.8. Domain-Driven Software Architecture.
### 4.8.1. Software Architecture Context Diagram.
### 4.8.2. Software Architecture Container Diagrams.
### 4.8.3. Software Architecture Components Diagrams.
## 4.9. Software Object-Oriented Design.
### 4.9.1. Class Diagrams.
### 4.9.2. Class Dictionary.
## 4.10. Database Design.
### 4.10.1. Relational/Non-Relational Database Diagram.
# Capítulo V: Product Implementation
## 5.1. Software Configuration Management.
### 5.1.1. Software Development Environment Configuration.
### 5.1.2. Source Code Management.
### 5.1.3. Source Code Style Guide & Conventions.
### 5.1.4. Software Deployment Configuration.
## 5.2. Product Implementation & Deployment.
### 5.2.1. Sprint Backlogs.
### 5.2.2. Implemented Landing Page Evidence
### 5.2.3. Implemented Frontend-Web Application Evidence
### 5.2.4. Implemented Native-Mobile Application Evidence
### 5.2.5. Implemented RESTful API and/or Serverless Backend Evidence
### 5.2.6. RESTful API documentation
### 5.2.7. Team Collaboration Insights
## 5.3. Video About-the-Product.
# Part II: Verification, Validation & Pipeline
# Capítulo VI: Product Verification & Validation
## 6.1. Testing Suites & Validation
### 6.1.1. Core Entities Unit Tests.
### 6.1.2. Core Integration Tests.
### 6.1.3. Core Behavior-Driven Development
### 6.1.4. Core System Tests.
## 6.2. Static testing & Verification
### 6.2.1. Static Code Analysis
#### 6.2.1.1. Coding standard & Code conventions.
#### 6.2.1.2. Code Quality & Code Security.
### 6.2.2. Reviews
## 6.3. Validation Interviews.
### 6.3.1. Diseño de Entrevistas.
### 6.3.2. Registro de Entrevistas.
### 6.3.3. Evaluaciones según heurísticas.
## 6.4. Auditoría de Experiencias de Usuario
### 6.4.1. Auditoría realizada.
#### 6.4.1.1. Información del grupo auditado.
#### 6.4.1.2. Cronograma de auditoría realizada.
#### 6.4.1.3. Contenido de auditoría realizada.
### 6.4.2. Auditoría recibida.
#### 6.4.2.1. Información del grupo auditor.
#### 6.4.2.2. Cronograma de auditoría recibida.
#### 6.4.2.3. Contenido de auditoría recibida.
#### 6.4.2.4. Resumen de modificaciones para subsanar hallazgos.
# Capítulo VII: DevOps Practices
## 7.1. Continuous Integration
### 7.1.1. Tools and Practices.
### 7.1.2. Build & Test Suite Pipeline Components.
## 7.2. Continuous Delivery
### 7.2.1. Tools and Practices.
### 7.2.2. Stages Deployment Pipeline Components.
## 7.3. Continuous deployment
### 7.3.1. Tools and Practices.
### 7.3.2. Production Deployment Pipeline Components.
## 7.4. Continuous Monitoring
### 7.4.1. Tools and Practices
### 7.4.2. Monitoring Pipeline Components
### 7.4.3. Alerting Pipeline Components
### 7.4.4. Notification Pipeline Components.
# Part III: Experiment-Driven Lifecycle
# Capítulo VIII: Experiment-Driven Development
## 8.1. Experiment Planning
### 8.1.1. As-Is Summary.
### 8.1.2. Raw Material: Assumptions, Knowledge Gaps, Ideas, Claims.
### 8.1.3. Experiment-Ready Questions.
### 8.1.4. Question Backlog.
### 8.1.5. Experiment Cards.
## 8.2. Experiment Design
### 8.2.1. Hypotheses.
### 8.2.2. Measures.
### 8.2.3. Conditions.
### 8.2.4. Scale Calculations and Decisions.
### 8.2.5. Methods Selection.
### 8.2.6. Data Analytics: Goals, KPIs and Metrics Selection.
### 8.2.7. Web and Mobile Tracking Plan.
## 8.3. Experimentation
### 8.3.1. To-Be User Stories.
### 8.3.2. To-Be Product Backlog
### 8.3.3. Pipeline-supported, Experiment-Driven To-Be Software Platform Lifecycle
#### 8.3.3.1. To-Be Sprint Backlogs
#### 8.3.3.2. Implemented To-Be Landing Page Evidence
#### 8.3.3.3. Implemented To-Be Frontend-Web Application Evidence
#### 8.3.3.4. Implemented To-Be Native-Mobile Application Evidence
#### 8.3.3.5. Implemented To-Be RESTful API and/or Serverless Backend Evidence
#### 8.3.3.6. Team Collaboration Insights
### 8.3.4. To-Be Validation Interviews
#### 8.3.4.1. Diseño de Entrevistas.
#### 8.3.4.2. Registro de Entrevistas.
## 8.4. Experiment Aftermath & Analysis
### 8.4.1. Analysis and Interpretation of Results
### 8.4.2. Re-scored and Re-prioritized Question Backlog
## 8.5. Continuous Learning
### 8.5.1. Shareback Session Artifacts: Learning Workflow
## 8.6. To-Be Software Platform Pre-launch
### 8.6.1. About-the-Product Intro Video
# Conclusiones
## Conclusiones y recomendaciones.
# Video About-the-Team.
# Bibliografía
# Anexos





