<div align = "center">
  <img style="height: 150px" src=/assets/assets/chapter-1/UPC_logo_transparente.png alt="">
  <h1>Universidad Peruana de Ciencias Aplicadas</h1>
  <h2>Carrera: de Ingeniería de Software</h2>
  <h2>Ciclo: 2025-02</h2>
  <h2>1ASI0730 - Aplicaciones Web </h2>
  <h2>NRC: 7454</h2>
  <br>
  <h2>Profesor: Angel Augusto Velasquez Nuñez </h2>
  <h2>Informe de Trabajo Final</h2>
  <br>
  <h2 >Startup: ASSIDUOU SOFTWARE </h2>
  <h2 >Producto: LabIoT</h2>
  <br>
  <h2 >Integrantes:</h2>
  <ul style="list-style: none; padding: 0;">
      <li><h3>Navarro Chang Alicia Avril - u20231d637 </h3></li>
      <li><h3>Alexander Auden Aliaga Ocampo- U202417693</h3></li>
      <li><h3>Andre Pillaca Velasquez - U202022056</h3></li>
      <li><h3>Mazuelos Callirgos Marcelo Alessandro – u201916143</h3></li>
      <li><h3>Huanca Zevallos, Cristhian Joel - u20201b914</h3></li>
  </ul>
  <br>
  <h4>Septiembre del 2025</h4>
<br>
</div>

## Registro de Versiones del Informe

| Versión | Fecha       | Autor                                            | Descripción de modificación |
|---------|-------------|--------------------------------------------------|-----------------------------|
| 0.1     | 24/04/2025  | Todos los integrantes                            | Primer sprint TB1           |

## Project Report Collaboration Insights
| URL de la organización del proyecto |   URL del repositorio del reporte   |
|:-----------------------------------:|:-----------------------------------:|
|   https://github.com/Los-Bytes      | https://github.com/Los-Bytes/Report |

## Contenido

- [Student Outcome](#student-outcome)

- [Capítulo I: Introducción](#cap1)
    - [1.1. Startup Profile](#11-startup-profile)
        - [1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)
        - [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
    - [1.2. Solution Profile](#12-solution-profile)
        - [1.2.1 Antecedentes y problemática](#121-antecedentes-y-problemática)
        - [1.2.2 Lean UX Process](#122-lean-ux-process)
            - [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)
            - [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)
            - [1.2.2.3. Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
            - [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)
    - [1.3. Segmentos objetivo](#13-segmentos-objetivo)

- [Capítulo II: Requirements Elicitation & Analysis](#cap2)
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
    - [2.4. Big Picture EventStorming](#24-big-picture-eventstorming)
    - [2.5. Ubiquitous Language](#25-ubiquitous-language)



- [Capítulo III: Requirements Specification](#cap3)
    - [3.1. User Stories](#31-user-stories)
    - [3.2. Impact Mapping](#32-impact-mapping)
    - [3.3. Product Backlog](#33-product-backlog)


- [Capítulo IV: Product Design](#cap4)
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
        - [4.6.1. Design-Level EventStorming](#461-design-level-eventstorming)
        - [4.6.2. Software Architecture Context Diagram](#462-software-architecture-context-diagram)
        - [4.6.3. Software Architecture Container Diagrams](#463-software-architecture-container-diagrams)
        - [4.6.4. Software Architecture Components Diagrams](#464-software-architecture-components-diagrams)
    - [4.7. Software Object-Oriented Design](#47-software-object-oriented-design)
        - [4.7.1. Class Diagrams](#471-class-diagrams)
    - [4.8. Database Design](#48-database-design)
        - [4.8.1. Database Diagram](#481-database-diagram)


- [Capítulo V: Product Implementation, Validation & Deployment](#cap5)
    - [5.1. Software Configuration Management](#51-software-configuration-management)
        - [5.1.1. Software Development Environment Configuration](#511-software-development-environment-configuration)
        - [5.1.2. Source Code Management](#512-source-code-management)
        - [5.1.3. Source Code Style Guide & Conventions](#513-source-code-style-guide--conventions)
        - [5.1.4. Software Deployment Configuration](#514-software-deployment-configuration)
    - [5.2. Landing Page, Services & Applications Implementation](#52-landing-page-services--applications-implementation)
        - [5.2.1. Sprint 1](#521-sprint-1)
            - [5.2.1.1. Sprint Planning 1](#5211-sprint-planning-1)
            - [5.2.1.2. Aspect Leaders and Collaborators](#5212-aspect-leaders-and-collaborators)
            - [5.2.1.3. Sprint Backlog 1](#5213-sprint-backlog-1)
            - [5.2.1.4. Development Evidence for Sprint Review](#5214-development-evidence-for-sprint-review)
            - [5.2.1.5. Execution Evidence for Sprint Review](#5215-execution-evidence-for-sprint-review)
            - [5.2.1.6. Services Documentation Evidence for Sprint Review](#5216-services-documentation-evidence-for-sprint-review)
            - [5.2.1.7. Software Deployment Evidence for Sprint Review](#5217-software-deployment-evidence-for-sprint-review)
            - [5.2.1.8. Team Collaboration Insights during Sprint](#5218-team-collaboration-insights-during-sprint)
        
- [Conclusiones](#conclusiones)
- [Bibliografía](#bibliografía)
- [Anexos](#anexos)

## Student Outcome

El curso contribuye al cumplimiento del Student Outcome ABET:

**ABET – EAC - Student Outcome 5**

**Criterio:** : La capacidad de funcionar efectivamente en un equipo cuyos miembros
juntos proporcionan liderazgo, crean un entorno de colaboración e inclusivo,
establecen objetivos, planifican tareas y cumplen objetivos.
En el siguiente cuadro se describe las acciones realizadas y enunciados de
conclusiones por parte del grupo, que permiten sustentar el haber alcanzado el logro
del ABET – EAC - Student Outcome 5.

<table>
  <tr>
    <th>Criterio específico</th>
    <th>Acciones realizadas</th>
    <th>Conclusiones</th>
  </tr>
  <tr>
    <td>Trabaja en equipo para proporcionar liderazgo en forma conjunta.</td>
    <td> </td>
    <td></td>
  </tr>
  <tr>
    <td>Crea un entorno colaborativo e inclusivo, establece metas, planifica tareas y cumple objetivos.</td>
    <td></td>
    <td></td>
  </tr>

</table>

## Capítulo 1: Introducción
### 1.1. Startup Profile
#### 1.1.1. Descripción del Startup
Somos Los Bytes, un grupo de estudiantes de Ingeniería de Software de la Universidad Peruana de Ciencias Aplicadas (UPC) comprometidos con el desarrollo de soluciones tecnológicas innovadoras que aporten valor y eficiencia al sector científico. En el marco de nuestra formación académica, hemos emprendido la creación de una Startup enfocada en transformar la gestión de inventarios en laboratorios a través del uso de tecnologías inteligentes como el Internet de las Cosas (IoT), RFID y sensores inteligentes, combinando innovación, precisión y automatización. 

Misión:</br>
Nuestra misión es mejorar la gestión y seguridad en laboratorios de investigación y empresas proveedoras, facilitando el monitoreo proactivo y la eficiencia mediante tecnologías inteligentes como IoT, RFID y códigos QR. Queremos eliminar tareas tediosas y minimizar riesgos asociados al manejo de materiales críticos. 

Visión:</br> 
Nuestra visión es convertirnos en un startup referente en soluciones tecnológicas para gestión inteligente de inventarios en laboratorios, promoviendo entornos más seguros, eficientes y confiables para la investigación científica y la comercialización de insumos, tanto en Perú como en otros mercados emergentes. 

#### 1.1.2. Perfiles de integrantes del equipo
<table>
  <tr>
    <th colspan="2"> Alicia Avril Navarro Chang </th>
  </tr>
  <tr>
    <td> <img src="assets/assets/chapter-1/Alicia.jpeg" width=300px> </td>
    <td> Soy estudiante de Ingeniería de Software en la UPC, con conocimientos básicos en programación en C++ y Python, fundamentos en bases de datos, diseño y modelado de software utilizando UML y diagramas, así como algoritmos y estructuras de datos básicos. Además, poseo habilidades de empatía y comunicación efectiva que me permiten colaborar de manera eficiente en equipo, facilitando la comunicación clara y asertiva para contribuir a un entorno de trabajo productivo y colaborativo. </td>
  </tr>
  <tr>
    <th colspan="2"> Alexander Auden Aliaga Ocampo </th>
  </tr>
  <tr>
    <td> <img > </td>
    <td> Soy estudiante de ingeniería de software en la UPC, con conocimientos básicos en los lenguajes de programación como c++, python , css, html, javascript también conocimientos básicos en base de datos viendo Mongo DB y creando diagramas relaciones como no relacionales. Además poseo habilidades de empatía y buena comunicación con el equipo esto me permite ser productivo en el ámbito de grupos y en general. </td>
  </tr>
<tr>
    <th colspan="2"> Poly Gabriel Alcántara Baldeon </th>
  </tr>
  <tr>
    <td> <img > </td>
    <td>Soy estudiante de Ingeniería de Software. Tengo conocimientos básicos en lenguajes de programación como C#, Java y Python. Me interesa el desarrollo de videojuegos y estoy buscando oportunidades para aprender y crecer en este campo. Además, poseo habilidades blandas como la capacidad de trabajar en equipo, la proactividad y la adaptabilidad, lo que me permite ser productivo en entornos colaborativos y enfrentar nuevos desafíos con entusiasmo. </td>
  </tr>
<tr>
    <th colspan="2"> Cristhian Joel Huanca Zevallos </th>
  </tr>
  <tr>
    <td> <img src="assets/assets/chapter-1/CristhianHuanca.jpg" width=300px > </td>
    <td> Soy estudiante de ingeniería de software en la UPC,  me considero una persona proactiva, organizada y responsable al momento de desarrollar un nuevo proyecto en mi vida. En un grupo de trabajo siempre trato de respetar las opiniones de los demás, trato de entender los demás puntos de vista y animo a estar en unión frente a un problema.  </td>
  </tr>
<tr>
    <th colspan="2">Andre Pillaca Velasquez </th>
  </tr>
  <tr>
    <td> <img > </td>
    <td>Soy estudiante de la carrera de Ingeniería de Software. Tengo 22 años y entre mis cualidades están ser perseverante y responsable. Entre mis habilidades, tengo experiencia en los lenguajes de programación de C + +,Python y espero seguir aprendiendo para llegar a ser un profesional competente. </td>
  </tr>
 <tr>
    <th colspan="2">  </th>
  </tr>
  <tr>
    <td> <img > </td>
    <td> </td>
  </tr>
</table>

### 1.2. Solution Profile
#### 1.2.1. Antecedentes y problemática 
#### 1.2.2. Lean UX Process
##### 1.2.2.1. Lean UX Problem Statements
##### 1.2.2.2. Lean UX Assumptions
##### 1.2.2.3. Lean UX Hyphotesis Statements
##### 1.2.2.4. Lean UX Canvas
### 1.3 Segmentos Objetivo 

## Capítulo IV: Product Design
### 4.1. Style Guidelines
#### 4.1.1. General Style Guidelines
El diseño de estilo general de LabIoT responde a la necesidad de transmitir seguridad, innovación y confiabilidad, valores esenciales 
en la gestión de inventarios de laboratorio.

- **Colores**: la paleta seleccionada combina azul (#004AAD), verde (#00B894) y grises (#333333 y #F1F1F1). El azul transmite confianza y control, 
cualidades críticas en entornos de laboratorio. El verde refuerza la idea de innovación y sostenibilidad asociada al uso de IoT. Los 
tonos grises equilibran la interfaz y facilitan la lectura de datos en pantallas.

<p align="center">
  <img src="/assets/assets/chapter-4/style-guidelines/colores.png" alt="colores" style="height:200px;">
</p>

- **Tipografía**: se utiliza Roboto como fuente principal por su claridad en interfaces digitales, y Open Sans para textos extensos y 
documentación. La elección responde a la necesidad de legibilidad y modernidad, además de ser tipografías ampliamente utilizadas 
en entornos web.

<p align="center">
  <img src="/assets/assets/chapter-4/style-guidelines/TIPOGRAFIA.png" alt="tipografia" style="height:300px;">
</p>

- **Distribución y espaciado**: se adopta un diseño en cuadrícula de 12 columnas (basado en Material Design), con márgenes consistentes. 
Esto asegura orden y claridad en la presentación de la información, favoreciendo la navegación.

<p align="center">
<img src="/assets/assets/chapter-4/style-guidelines/distribucion.png" alt="distribucion" style="height:300px;">
</p>

- **Lenguaje y tono: la comunicación** es clara, formal y precisa, sin tecnicismos innecesarios. Esto facilita que tanto investigadores 
como técnicos y proveedores comprendan fácilmente la información.

<p align="center">
<img src="/assets/assets/chapter-4/style-guidelines/lenguaje.png" alt="lenguaje" style="height:300px;">
</p>

- **Iconografía**: se emplean símbolos fácilmente reconocibles, como íconos de sensores, códigos QR, alertas y stock. Esto permite reducir 
la curva de aprendizaje y mejora la usabilidad del sistema.

<p align="center">
<img src="/assets/assets/chapter-4/style-guidelines/iconografia.png" alt="iconografia" style="height:300px;">
</p>

#### 4.1.2. Web Style Guidelines

El diseño web de LabIoT se implementará con el framework Vue, utilizando PrimeVue como biblioteca de componentes y siguiendo las guías 
de Material Design. El objetivo es asegurar que tanto la Landing Page como la Web Application presenten una experiencia uniforme, 
responsiva y accesible.

- **Diseño adaptable**: la interfaz se ajusta a distintos dispositivos (desktop, tablet y móvil), manteniendo la consistencia entre la Landing 
Page y la Web Application. Esto permite que los usuarios puedan acceder en cualquier contexto, ya sea en un laboratorio o en una oficina 
administrativa.

<p align="center">
<img src="/assets/assets/chapter-4/style-guidelines/diseño.png" alt="diseño-adaptable" style="height:200px;">
</p>

- **Componentes de interfaz**: los botones principales se muestran en azul, resaltando acciones críticas como guardar o confirmar, mientras 
que los botones secundarios se presentan en verde, destinados a funciones complementarias. Esto guía al usuario y establece jerarquía 
visual.

<p align="center">
<img src="/assets/assets/chapter-4/style-guidelines/componentes.png" alt="componentes" style="height:200px;">
</p>

- **Notificaciones y estados**: los mensajes de éxito se presentan en verde, las advertencias en amarillo (#F9CA24) y los errores en rojo 
(#D63031). Esta convención ayuda a los usuarios a reaccionar de forma rápida y a reducir confusiones.

<p align="center">
<img src="/assets/assets/chapter-4/style-guidelines/notificaciones.png" alt="notificaciones" style="height:200px;">
</p>

- **Tablas y dashboards**: se prioriza un diseño claro y ordenado en las tablas de inventario y en los paneles de control. Los usuarios 
pueden filtrar, ordenar y visualizar información de manera eficiente, minimizando errores en el manejo de datos críticos.

<p align="center">
<img src="/assets/assets/chapter-4/style-guidelines/tablas.png" alt="tablas" style="height:300px;">
</p>

- **Accesibilidad**: se implementan contrastes adecuados, etiquetas en formularios y atributos accesibles para usuarios con discapacidad 
visual. Además, se asegura compatibilidad con estándares internacionales (WCAG).

<p align="center">
<img src="/assets/assets/chapter-4/style-guidelines/accesibilidad.png" alt="accesibilidad" style="height:300px;">
</p>

En conjunto, estas guías aseguran que la experiencia digital sea consistente, fácil de usar y accesible, reforzando la identidad 
visual definida en las guías generales.

### 4.2. Information Architecture
#### 4.2.1. Organization Systems
#### 4.2.2. Labeling Systems
#### 4.2.3. SEO Tags and Meta Tags
#### 4.2.4. Searching Systems
#### 4.2.5. Navigation Systems
### 4.3. Landing Page UI Design
#### 4.3.1. Landing Page Wireframe
#### 4.3.2. Landing Page Mock-up
### 4.4. Web Applications UX/UI Design
#### 4.4.1. Web Applications Wireframes
#### 4.4.2. Web Applications Wireflow Diagrams
#### 4.4.3. Web Applications Mock-ups
#### 4.4.4. Web Applications User Flow Diagrams
### 4.5. Web Applications Prototyping
### 4.6. Domain-Driven Software Architecture
#### 4.6.1. Design-Level EventStorming
#### 4.6.2. Software Architecture Context Diagram
#### 4.6.3. Software Architecture Container Diagrams
#### 4.6.4. Software Architecture Components Diagrams
### 4.7. Software Object-Oriented Design
#### 4.7.1. Class Diagrams
### 4.8. Database Design
#### 4.8.1. Database Diagram

