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
      <li><h3>Alcantara Baldeonn, Poly Gabriel - u202418250</h3></li>
  </ul>
  <br>
  <h4>Septiembre del 2025</h4>
<br>
</div>

## Registro de Versiones del Informe

| Versión | Fecha      | Autor                                            | Descripción de modificación |
|---------|------------|--------------------------------------------------|-----------------------------|
| 0.1     | 21/09/2025 | Todos los integrantes                            | Primer sprint TB1           |

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
    <td> Crsthian Joel Huanca Zevallos  
    <br> TB1: Colaboré en la guía de estilos, el diagrama de base de datos, los antecedentes y 
    el impact mapping, guiando al equipo hacia un estándar común y una visión compartida. 
    <br><br>
    Gabriel Alcantara Baldeon  
    <br> TB1: Añadí y desarrollé la sección  Lean UX Canvas, la  Estrategias y tácticas frente a competidores, 
    y las secciones  Labeling Systems,  SEO Tags and Meta Tags, y  Searching Systems, asegurando coherencia y estandarización con el resto del documento.
    </td>
    <td>El liderazgo conjunto fortaleció la cohesión del grupo y permitió tomar decisiones claras en cada entregable.  
    <br><br>
    La integración de estas secciones permitió un documento más estructurado y consistente, fortaleciendo el liderazgo compartido en la elaboración del informe.</td>
  </tr>
  <tr>
    <td>Crea un entorno colaborativo e inclusivo, establece metas, planifica tareas y cumple objetivos.</td>
    <td>Crsthian Joel Huanca Zevallos  
    <br> TB1: Integré aportes del equipo en la guía de estilos, base de datos, antecedentes e impact mapping, 
    estableciendo metas claras y fomentando la participación. 
    <br><br>
    Gabriel Alcantara Baldeon  
    <br> TB1: Complementé y unifiqué la redacción de nuevas secciones (Lean UX Canvas, estrategias frente a competidores, sistemas de etiquetado y SEO), alineándolas con los entregables previos del equipo y fomentando la continuidad del proyecto.
    </td>
    <td>El trabajo colaborativo facilitó cumplir los objetivos en los plazos y consolidó un entorno inclusivo 
    y organizado.  
    <br><br>
    El trabajo organizado y la integración de mis aportes facilitaron cumplir con los objetivos planteados, garantizando un entorno colaborativo donde cada aporte reforzó el producto final.</td>
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
    <td> <img src="assets/assets/chapter-1/alexanderaliaga.jpg" width=300px> </td>
    <td> Soy estudiante de ingeniería de software en la UPC, con conocimientos básicos en los lenguajes de programación como c++, python , css, html, javascript también conocimientos básicos en base de datos viendo Mongo DB y creando diagramas relaciones como no relacionales. Además poseo habilidades de empatía y buena comunicación con el equipo esto me permite ser productivo en el ámbito de grupos y en general. </td>
  </tr>
<tr>
    <th colspan="2"> Poly Gabriel Alcántara Baldeon </th>
  </tr>
  <tr>
    <td> <img src="assets/assets/chapter-1/GabrielAlcantara.jpg" > </td>
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
    <td> <img src="assets/assets/chapter-1/AndrePillaca.jpg" width=300px> </td>
    <td>Soy estudiante de la carrera de Ingeniería de Software. Tengo 22 años y entre mis cualidades están ser perseverante y responsable. Entre mis habilidades, tengo experiencia en los lenguajes de programación de C + +,Python y espero seguir aprendiendo para llegar a ser un profesional competente. </td>
  </tr>
 <tr>
    <th colspan="2">Marcelo Alessandro Mazuelos Callirgos</th>
  </tr>
  <tr>
    <td> <img src="https://files.catbox.moe/y8qpju.jpg" alt="marcelo image" width="300">
    <td> Soy estudiante de Ingeniería de Software, interesado en el desarrollo de aplicaciones y en la creación de soluciones tecnológicas innovadoras. Me caracterizo por mi interés en el aprendizaje continuo con el objetivo de seguir creciendo profesionalmente y aportar valor en el área de la tecnología.</td>
  </tr>
</table>

### 1.2. Solution Profile
#### 1.2.1. Antecedentes y problemática

A. **Who**

Los principales actores son los laboratorios de investigación, los técnicos de laboratorio, investigadores, oficiales de seguridad,
así como las empresas proveedoras de insumos científicos. Todos ellos enfrentan dificultades en la gestión de inventarios por
depender de procesos manuales y poco confiables.

B. **What**

Actualmente, la gestión de inventarios en los laboratorios se realiza mediante conteos manuales y registros dispersos, lo que
genera errores, pérdida de materiales, incumplimiento de normativas de seguridad, interrupciones en experimentos y mayores costos
operativos. Además, no existen mecanismos de monitoreo en tiempo real para verificar condiciones críticas como temperatura,
humedad o caducidad de insumos.

C. **When**

Estos problemas se presentan en el día a día de las operaciones de los laboratorios y proveedores, desde el registro de entrada
y salida de materiales hasta la preparación de pedidos, auditorías, y ejecución de experimentos. Los riesgos aumentan en
momentos críticos como inspecciones, ensayos experimentales y entregas de insumos sensibles.

D. **Where**

La problemática ocurre tanto dentro de los laboratorios de investigación y universidades como en las empresas proveedoras y
almacenes de insumos científicos. En ambos entornos, los procesos carecen de visibilidad, trazabilidad y control automatizado.

E. **Why**

Porque la ausencia de automatización y monitoreo genera:

- Pérdida de trazabilidad de insumos críticos.

- Mayor riesgo de accidentes o incumplimiento normativo.

- Errores en entregas y devoluciones entre proveedores y clientes.

- Desperdicio de tiempo y recursos humanos en tareas repetitivas.
  Esto impacta directamente en la seguridad, la confiabilidad de los experimentos y la eficiencia operativa.

F. **How**

Muchos laboratorios utilizan hojas de cálculo, sistemas ERP genéricos o plataformas de gestión básica. Sin embargo, estas
soluciones no ofrecen integración con IoT (RFID, QR, sensores inteligentes) ni un monitoreo automatizado en tiempo real,
por lo que los problemas persisten.

G. **How much**

El impacto se refleja en:

- Más del 70% del tiempo de los responsables de inventarios invertido en tareas manuales.

- Errores superiores al 30–40% en registros y control de stock.

- Pérdida económica significativa por caducidad o mal almacenamiento de insumos sensibles.

- Alta fricción comercial entre proveedores y laboratorios debido a errores en entregas y devoluciones.

#### 1.2.2. Lean UX Process
##### 1.2.2.1. Lean UX Problem Statements
### Segmento — Investigadores Líderes / Responsables de Laboratorios de Investigación

**Contexto:** Dirigen proyectos, supervisan equipos y toman decisiones sobre la compra y uso de insumos especializados; necesitan garantizar continuidad experimental y cumplimiento normativo.

**Observación:** La gestión actual de insumos y condiciones de almacenamiento (temperatura, humedad, fechas de caducidad) suele ser manual y fragmentada (hojas, registros locales), lo que provoca pérdidas de reactivos, retrasos en ensayos y decisiones de compra reactivas.

**Problema:** No existe una herramienta que ofrezca visibilidad en tiempo real, trazabilidad y alertas accionables adaptadas al flujo de trabajo de un laboratorio de investigación sin añadir carga administrativa al equipo.

**Pregunta clave:** ¿Cómo diseñar una solución (QR/RFID + sensores + panel operativo) que permita a los investigadores líderes monitorear el estado de insumos y condiciones ambientales, recibir alertas priorizadas y generar evidencia auditable para toma de decisiones y compras oportunas?


### Segmento — Supervisores Comerciales / Jefes de Compras en Empresas Proveedoras de Insumos

**Contexto:** Coordinan ventas y logística, mantienen la relación con laboratorios y responden a incidencias en entregas; buscan reducir reclamaciones y optimizar la cadena de suministro.

**Observación:** La falta de un flujo estandarizado de identificación y registro (etiquetado, estado en tránsito, verificación a la recepción) genera errores, devoluciones y fricción comercial que aumentan costos operativos.

**Problema:** No hay un mecanismo compartido, sencillo y confiable entre proveedor y laboratorio que permita verificar condiciones de transporte, estado del pedido y recepción confirmada en tiempo real.

**Pregunta clave:** ¿Cómo implementar un flujo de trazabilidad colaborativo (etiquetas QR/RFID, eventos de transporte y notificaciones integradas) que permita a supervisores comerciales y jefes de compras reducir errores, acelerar validaciones y mejorar la experiencia de entrega para los laboratorios?
##### 1.2.2.2. Lean UX Assumptions
###### Supuestos sobre los usuarios de la aplicación:

- Los responsables de laboratorios necesitan llevar un control y una constante actualización del inventario de materiales.
- Los responsables de compras y proveedores de insumos requieren trazabilidad y seguridad en la entrega de materiales para evitar reclamos o pérdidas.
- Los usuarios necesitan interfaces simples que muestren de forma clara la información mostrada del estado del inventario y las alertas críticas.
- Los usuarios están dispuestos a adoptar tecnología IoT (sensores, RFID, QR) siempre que el retorno de inversión sea claro.

###### Supuestos sobre necesidades

- El conteo manual de insumos en laboratorios es un proceso tedioso y propenso a errores.
- Existen riesgos asociados a la pérdida, caducidad o mal almacenamiento de productos (temperatura, humedad).
- Una solución que automatice y genere alertas en tiempo real resolverá estos problemas de seguridad y control.
- La integración con sistemas de gestión ya existentes (ERP, software de compras) es un requerimiento importante.

###### Supuestos sobre la solución

- El uso de RFID y códigos QR facilita la identificación de insumos de manera rápida y confiable.
- Los sensores inteligentes permiten monitorear condiciones críticas (ej. temperatura de reactivos) y evitar pérdidas.
- Una plataforma centralizada basada en web permitirá a los laboratorios controlar en tiempo real su inventario desde cualquier lugar.
- El sistema puede escalarse desde un pequeño laboratorio hasta grandes instalaciones de investigación o distribución.

###### Supuestos sobre el impacto

- La solución reducirá el tiempo destinado a tareas de inventario manual.
- Disminuirá la pérdida de insumos por mal almacenamiento o caducidad.
- Mejorará la seguridad y trazabilidad, cumpliendo normativas de laboratorios certificados.
- Permitirá a las empresas proveedoras de insumos demostrar valor agregado en sus servicios.

##### 1.2.2.3. Lean UX Hyphotesis Statements

### 1.3 Segmentos Objetivo
### Segmento objetivo #1: Investigadores líderes o responsables de laboratorios de investigación  
Este grupo está conformado por profesionales que dirigen o coordinan laboratorios en instituciones académicas, científicas o tecnológicas. Su función involucra la supervisión de equipos de trabajo, la gestión de insumos y equipos especializados, y la toma de decisiones en torno a la compra y uso de materiales necesarios para el desarrollo de proyectos de investigación.

**Características clave de este segmento:**  
- Buscan optimizar la gestión y control de inventarios para evitar pérdidas o interrupciones en sus proyectos.  
- Valoran sistemas que mejoren la precisión y eficiencia en el seguimiento de insumos.  
- Requieren soluciones tecnológicas que garanticen integridad y trazabilidad en los materiales utilizados.  
- Se interesan por herramientas que reduzcan el tiempo dedicado a tareas administrativas.

---

### Segmento objetivo #2: Supervisores comerciales o jefes de compras en empresas proveedoras de insumos de laboratorio  
Este grupo está conformado por profesionales encargados de gestionar el abastecimiento, la relación con clientes institucionales y la negociación con proveedores de equipos e insumos científicos. Su labor se centra en asegurar la disponibilidad, calidad y entrega oportuna de materiales a los laboratorios.

**Características clave de este segmento:**  
- Buscan sistemas que mejoren la trazabilidad y control de los productos entregados a sus clientes.  
- Valoran la automatización y precisión en el monitoreo del stock.  
- Necesitan información en tiempo real para optimizar la cadena de suministro.  
- Se interesan por plataformas que faciliten la comunicación y el cumplimiento de requerimientos de los laboratorios.

## Capítulo II: Requirements Elicitation & Analysis
### 2.1. Competidores
#### 2.1.1. Análisis competitivo
##### Competidores directos:
- **Labguru**: plataforma de gestión de inventario y datos de laboratorio, con módulos para trazabilidad.
- **Quartzy**: software de gestión de inventario y pedidos para laboratorios de investigación.
- **LabCollector**: sistema modular que gestiona inventarios, muestras y equipos de laboratorio.

##### Competidores indirectos:
- **ERP tradicionales** como SAP o Odoo, que incluyen módulos de inventario, pero no especializados en laboratorios.
- **Sistemas de monitoreo IoT genéricos**, que no están centrados en laboratorios, pero pueden adaptarse.
- **Excel u hojas de cálculo** (competencia informal, pero todavía muy utilizada en laboratorios pequeños).

<img src="assets/assets/chapter-1/competidores_cuadro.png" width=max>

#### 2.1.2. Estrategias y tácticas frente a competidores
**Perfil**

El análisis competitivo permitió identificar que los principales competidores (Labguru, Quartzy y LabCollector) ofrecen soluciones sólidas de gestión de inventarios, pero carecen de integración con tecnologías IoT y monitoreo en tiempo real.

Frente a ello, **LabIoT** plantea las siguientes estrategias y tácticas:

**Estrategias**

1. **Diferenciación tecnológica**

- Potenciar la integración de IoT (sensores, RFID, QR) para garantizar monitoreo en tiempo real y trazabilidad completa.
- Incorporar alertas automáticas y registros auditables que los competidores no ofrecen.

2. **Especialización de nicho**

- Foco exclusivo en laboratorios de investigación, universidades y proveedores de insumos.
- Cumplir y superar normativas de seguridad y trazabilidad propias del sector científico.

3. **Accesibilidad y escalabilidad**

- Ofrecer versiones básicas a laboratorios pequeños y módulos premium a grandes instituciones.
- Implementar una estrategia de precios competitiva frente a plataformas internacionales.

4. **Alianzas estratégicas con proveedores**

- Crear sinergias con distribuidores de insumos para incluir la trazabilidad desde el origen hasta la entrega.
- Posicionarse como un puente de confianza entre proveedor y cliente.

5. **Posicionamiento de marca**

- Consolidar a LabIoT como un “laboratorio inteligente y seguro” que combina innovación, eficiencia y seguridad.

**Tácticas**

- Implementar pilotos gratuitos en laboratorios pequeños para validar el valor agregado y generar casos de éxito.
- Desarrollar módulos personalizables (inventario básico, monitoreo avanzado, reportes de auditoría, integración ERP).
- Aplicar estrategias de marketing digital enfocadas en beneficios medibles (ahorro de tiempo, reducción de errores, cumplimiento normativo).
- Establecer alianzas B2B con proveedores de insumos, integrando QR/RFID en la cadena de suministro.
- Mantener precios competitivos con planes accesibles y escalables.
- Brindar soporte especializado y capacitación para reducir la resistencia al cambio tecnológico.
### 2.2. Entrevistas
#### 2.2.1. Diseño de entrevistas
Segmento 1: Laboratorios de investigación 

¿Cómo gestionan actualmente el inventario de insumos y materiales en su laboratorio? 

¿Qué dificultades enfrentan con el conteo manual o el control manual del inventario? 

¿Cuáles son los riesgos o problemas asociados a errores en el manejo del inventario? 

¿Qué tipo de artículos o materiales requieren monitoreo especial (p.ej. temperatura, humedad)? 

¿Qué importancia tiene para ustedes la automatización y el monitoreo en tiempo real del inventario? 

¿Han utilizado antes tecnologías como RFID, códigos QR o sensores inteligentes en su gestión? 

¿Qué funcionalidades considerarían imprescindibles en una plataforma como LabioT? 

¿Qué tipo de alertas o notificaciones serían útiles para un monitoreo eficiente? 

¿Cuáles son las normativas o medidas de seguridad que deben cumplir y cómo afectan su gestión de inventarios? 

¿Qué expectativas tienen sobre la integración de tecnologías IoT en su flujo de trabajo diario? 

 

Segmento 2: Empresas proveedoras de insumos y materiales para laboratorios 

¿Cómo realizan el seguimiento y control de los productos que distribuyen a laboratorios? 

¿Qué desafíos encuentran en asegurar la correcta identificación y estado de los productos durante su almacenamiento y envío? 

¿Actualmente utilizan etiquetas RFID, códigos QR o tecnologías similares para la gestión de inventarios? 

¿Qué importancia tiene para su empresa garantizar que los productos cumplan con las medidas de seguridad exigidas por laboratorios? 

¿Qué retos enfrentan para escalar o automatizar el control de inventarios? 

¿Qué funcionalidades desearían que una plataforma de gestión de inventarios IoT les ofreciera? 

¿Cómo manejan las alertas relacionadas con condiciones críticas como temperatura o almacenamiento inadecuado? 

¿Qué tipo de reportes o información en tiempo real necesitan para tomar decisiones operativas? 

¿Cuáles son las expectativas sobre la integración de sistemas IoT para mejorar la eficiencia y seguridad en sus procesos? 

¿Qué apoyo o capacitación consideran necesario para adoptar una solución tecnológica como LabioT? 
#### 2.2.2. Registro de entrevistas
En esta sección, el equipo hace entrevistas a personas pertenecientes a los segmentos respectivos.
##### Segemento 1- Entrevista 1: Investigadores responsables de laboratorios
Nombre: Alfonso Chang <br>
Ocupación: Investigador jefe retirado de laboratorio de SENASA <br>
URL: https://upcedupe-my.sharepoint.com/:v:/g/personal/u20231d637_upc_edu_pe/EaFj2S5q7RtEtg_r7xd_4JEBZ4kbq9hYPrwAlS4cuNNKDQ?e=4ZYAAv <br>
<img src="assets/assets/chapter-2/entrevista-1.png" alt="">
Instante en el que inicia: 0:00 <br>
Duración: 10:04 minutos<br>
Resumen: El investigador, con amplia experiencia en laboratorios de investigación agrícola, valora la integración de tecnologías IoT para modernizar la gestión de laboratorios. Destaca cómo el uso de códigos QR, sensores y dispositivos IoT permite monitorizar en tiempo real condiciones ambientales y procesos dentro del laboratorio, facilitando un control más preciso y confiable. Resalta que un sistema web centralizado para manejar estas tecnologías mejora la eficiencia operativa, reduce errores manuales y agiliza la toma de decisiones. También nos comenta que en su trabajo la mayoría de tareas que tengan que ver con gestión de inventarios o monitoreos generalmente siempre se hacían con herramientas básicas de ofimatica como excel y que los insumos siempre tienen que cumplir con estrictas medidas y reglas para controlar su calidad y evitar alteraciones en su composición.

### Segemento 1- Entrevista 2: Laboratorios de investigación

<img src="assets/assets/chapter-2/entrevista1.png" alt="">

**Nombre y apellido:** Luana Huayanay  
**Edad:** 24  
**Ocupación:** Practicante  
**Duración:** 7:56 minutos

#### Resumen:
Luana nos comenta que la manera de como controla su registro es a través de Excel, además que al registrarlo de esta manera se pierde mucho tiempo, y que a veces se olvidan de registrar por lo que generar desorden y retrasos con las prácticas y experimentos que realizan.

También nos comentan las funciones que son necesarias para una plataforma como Labiot son tener un registró automático de entradas y salidas, tener un monitoreo de temperaturas, tener un historial de cada material. además, nos cuenta los tipos de notificaciones que necesita para tener un mayor control y monitoreo es saber la fecha de vencimiento de sus reactivos o medicamentos, también tener alertas ante cualquier variación en la temperatura parar sus congeladores, tener alertas para recordar revisar su inventario, saber con qué insumos están trabajando y para ver cuáles son los insumos que quedan disponibles, además de un aviso por si un refrigerador se abre fuera del horario autorizado.

Luana comento que las normativas que cumple es registrar todo los equipos y insumos, asegurar la conservación adecuada de sus materiales.

Luana resalta que las tecnologías IoT podrían facilitar su trabajo al permitir visualizar rápidamente datos clave como conocer el stock de sus medicamentos, conocer el estado de los refrigeradores o si es que se venció algún reactivo que utilizan para sus experimentos, además ayudaría a reducir los errores humanos que tenemos y con la facilidad de poder organizar y tener todo más seguro.

**Link:** [Eupc-pre-202520-1asi0730-7454-labIoT- needfinding-sprint-1](https://upcedupe-my.sharepoint.com/personal/u202022056_upc_edu_pe/_layouts/15/stream.aspx?id=%2Fpersonal%2Fu202022056%5Fupc%5Fedu%5Fpe%2FDocuments%2FEntrevista%201%5F%20app%20web%20%E2%80%90%20Hecho%20con%20Clipchamp%2Emp4&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&ga=1&referrer=StreamWebApp%2EWeb&referrerScenario=AddressBarCopied%2Eview%2Ed2f63370%2D0166%2D4c43%2Dae85%2D4cb90ba0d12f)

### Segemento 1- Entrevista 3: Laboratorios de investigación

<img src="assets/assets/chapter-2/entrevista2.png" alt="">

**Nombre y apellido:** Erick Lucio Sulca  
**Edad:** 22
**Ocupación:** Practicante  
**Duración:** 4:41 minutos

#### Resumen:
Erick nos comenta que actualmente gestiona sus registros mediante Excel, método que le resulta tedioso debido al tiempo que consume esta tarea manual. Además, señala que este sistema propicia el desperdicio de algunos suministros y reactivos.

Destaca que sería muy valioso que la plataforma integre funcionalidades de monitoreo de sensores de temperatura para disminuir el riesgo de pérdida de materiales. Erick considera que la implementación de un programa especializado ayudaría significativamente a reducir tanto la carga laboral como el tiempo invertido en el registro de insumos.

**Link:** [upc-pre-202520-1asi0730-7454-labIoT- needfinding2-sprint-1](https://upcedupe-my.sharepoint.com/personal/u202022056_upc_edu_pe/_layouts/15/stream.aspx?id=%2Fpersonal%2Fu202022056%5Fupc%5Fedu%5Fpe%2FDocuments%2Fentrevista2web%20%E2%80%90%20Hecho%20con%20Clipchamp%2Emp4&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&ga=1&referrer=StreamWebApp%2EWeb&referrerScenario=AddressBarCopied%2Eview%2E8adf3607%2D453c%2D4604%2Db892%2Df3a55fdb91e4)

##### Segemento 2: Supervisores de empresas

#### 2.2.3. Análisis de entrevistas

El análisis de entrevistas para el Segmento 1: Investigadores responsables de laboratorios muestra que comparten patrones claros en cuanto al uso de herramientas actuales, las limitaciones de estas, y las expectativas hacia una solución tecnológica como LabIoT. A continuación, se presentan las características objetivas y subjetivas del segmento, sustentadas en los hallazgos de las entrevistas realizadas.

##### Características objetivas
Uso de herramientas tradicionales (Excel y ofimática):
El 100% de los entrevistados (Alfonso y Luana) mencionaron que actualmente utilizan principalmente Excel para el control de inventarios y registros de insumos. Se considera un método limitado que consume tiempo y genera errores.

Tiempo invertido y errores frecuentes:
El 100% señaló demoras y fallas en el registro manual, ya sea por olvido (Luana) o por dependencia en tareas repetitivas (Alfonso).

Necesidad de cumplir normativas de calidad:
El 100% resaltó la importancia del cumplimiento de protocolos y normativas de conservación de insumos y materiales, asegurando condiciones óptimas (temperatura, caducidad) para evitar la alteración de los productos.

Requerimientos de monitoreo en tiempo real:
El 100% expresó la necesidad de contar con un sistema de monitoreo constante en aspectos críticos como temperatura, stock y vencimientos.

Duración y frecuencia en el uso de materiales:
Ambos entrevistados señalaron que la operación en laboratorios implica un alto volumen de insumos, lo que hace indispensable un sistema de control automatizado en tiempo real.

##### Características subjetivas
Percepción sobre la tecnología IoT:
El 100% mostró una actitud positiva hacia la implementación de dispositivos IoT y automatización en la gestión de inventarios. Alfonso lo valora como un medio de modernización y mejora de la confiabilidad; Luana lo percibe como una solución que le simplificará el trabajo y minimizará errores humanos.

Sensibilidad hacia la seguridad y el control:
El 100% expresó preocupación por la seguridad y conservación de insumos. Luana resaltó la importancia de contar con alertas inmediatas (apertura de refrigeradores, vencimiento de reactivos), mientras Alfonso enfatizó la confiabilidad en la calidad de materiales bajo normas estrictas.

Valoración de la eficiencia operativa:
El 100% consideró que una plataforma como LabIoT incrementaría significativamente la eficiencia al reducir errores manuales, optimizar el tiempo y agilizar la toma de decisiones.

Preferencia por automatización y centralización:
El 100% se inclinó hacia una solución tecnológica centralizada. Alfonso destacó el impacto positivo a nivel estratégico y de gestión, mientras Luana valoró las funciones a nivel operativo (alertas, historial de insumos, control de stock).

##### Principales patrones comunes (datos cruzados)
100% utiliza Excel actualmente para registros.
100% sufre problemas de retrasos, pérdida de datos y errores por la gestión manual.
100% considera que IoT es útil y necesario en laboratorios.
100% percibe como vital el cumplimiento de normativas de conservación para insumos.
100% desea una solución que centralice la información e incluya alertas automáticas y monitoreo en tiempo real.

### 2.3. Needfinding
#### 2.3.1. User Personas
<img src="assets/assets/chapter-1/user-persona1.png" alt="">
<img src="assets/assets/chapter-1/user-persona2.png" alt="">

#### 2.3.2. User Task Matrix
### User Task Matrix: Responsable de Laboratorio de Investigación (Carlos Estrada)

| Task                                                                 | Importance | Frequency |
|---------------------------------------------------------------------|------------|-----------|
| Supervisar el control y disponibilidad de insumos y equipos         | High       | Always    |
| Actualizar el inventario (entradas, salidas, vencimientos)          | High       | Often     |
| Verificar condiciones críticas (temperatura, humedad, etc.)         | High       | Often     |
| Organizar el historial y reportes de uso de materiales              | Moderate   | Often     |
| Atender consultas y coordinar con investigadores                    | Moderate   | Always    |
| Gestionar alertas por materiales críticos o vencimientos            | High       | Often     |
| Compartir información con el equipo y la dirección                  | Moderate   | Often     |
| Realizar conteo manual cuando hay discrepancias                     | Low        | Rare      |
| Solicitar reposición o compra de insumos                            | Moderate   | Often     |

---

### User Task Matrix: Supervisora de Compras en Empresa Proveedora (Paula Benítez)

| Task                                                                | Importance | Frequency |
|---------------------------------------------------------------------|------------|-----------|
| Gestionar inventario de productos y verificar stock disponible      | High       | Often     |
| Coordinar envíos y entregas con laboratorios clientes               | High       | Often     |
| Procesar cotizaciones y atender solicitudes de compra               | High       | Always    |
| Supervisar calidad de productos recibidos                           | High       | Often     |
| Actualizar catálogo de productos y precios                          | Moderate   | Often     |
| Resolver incidencias con pedidos y facturación                      | Moderate   | Rare      |
| Mantener comunicación proactiva con clientes                        | High       | Always    |
| Analizar patrones de compra para anticipar necesidades              | Moderate   | Rare      |
| Crear promociones y descuentos para clientes frecuentes             | Low        | Rare      |

#### 2.3.3. User Journey Mapping
<img src="assets/assets/chapter-1/user-journey-mapping-1.png" alt="">
<img src="assets/assets/chapter-1/user-journey-mapping-2.png" alt="">

#### 2.3.4. Empathy Mapping
**Laboratorios**

<img src="assets/assets/chapter-2/empathy_map_lab.png" width=max>

**Suppliers**

<img src="assets/assets/chapter-2/empathy_map_supplier.png" width=max>

### 2.4. Big Picture EventStorming
<img src="assets/assets/chapter-1/step1-event-storming.jpg" alt="">
<img src="assets/assets/chapter-1/step2-event-storming.jpg" alt="">
<img src="assets/assets/chapter-1/step3-event-storming.jpg" alt="">
<img src="assets/assets/chapter-1/step4-event-storming.jpg" alt="">

Miro link: https://miro.com/app/board/uXjVJG4MLHQ=/
### 2.5. Ubiquitous Language
### 2.4. Lenguaje Ubicuo LabIoT

El siguiente glosario detalla los términos clave de LabIoT y su dominio.

| Término (Inglés)              | Término (Español)                 | Definición |
|-------------------------------|------------------------------------|------------|
| Lab Manager                   | Responsable de Laboratorio         | Persona encargada de supervisar el inventario, la seguridad y las operaciones del laboratorio. Toma decisiones sobre la adquisición y el uso de insumos. |
| Procurement Supervisor        | Supervisor de Compras              | Responsable de coordinar las solicitudes de materiales y mantener la relación con proveedores de insumos de laboratorio. |
| Researcher                    | Investigador                       | Usuario que trabaja dentro del laboratorio y utiliza los insumos inventariados para proyectos específicos. |
| Supplier                      | Proveedor                          | Empresa o entidad que abastece al laboratorio con materiales, insumos y equipos especializados. |
| Register Item           | Registro de Ítem            | Proceso en el que cada material, reactivo o equipo del laboratorio es identificado en el sistema mediante etiquetas RFID o códigos QR. |
| Track Inventory         | Seguimiento de Inventario   | Funcionalidad para monitorear en tiempo real los niveles de stock de insumos dentro del laboratorio. |
| Condition Monitoring    | Monitoreo de Condiciones    | Proceso en el que sensores inteligentes registran parámetros críticos (ejemplo: temperatura de reactivos sensibles). |
| Alert Generation        | Generación de Alertas       | Notificaciones automáticas enviadas cuando se detecta un nivel bajo de stock o una condición anómala en los insumos (ejemplo: refrigerador con aumento de temperatura). |
| Access Control          | Control de Acceso           | Gestión de permisos que define qué usuarios pueden registrar, modificar o consumir ítems específicos. |
| Inventory Report        | Reporte de Inventario       | Generación de informes automáticos sobre niveles de existencia, historial de consumos y estado de los insumos. |
| Smart Tag               | Etiqueta Inteligente        | Identificador en forma de RFID o código QR que permite el reconocimiento único de cada ítem dentro del sistema. |
| Stock Level             | Nivel de Stock              | Cantidad disponible de un insumo en el inventario, monitoreada de forma automática. |
| Expiration Date         | Fecha de Vencimiento        | Registro de la fecha límite de uso de reactivos o insumos, clave para garantizar la seguridad en proyectos de investigación. |
| Critical Condition      | Condición Crítica           | Estado detectado por sensores (ejemplo: pérdida de frío en congelador o variación brusca de temperatura) que puede comprometer la utilidad de los materiales. |
| Consumption Log         | Registro de Consumo         | Historial de movimientos de inventario que refleja qué insumo fue consumido, por quién y en qué fecha. |
| Supply Request          | Solicitud de Insumo         | Proceso mediante el cual un miembro del laboratorio solicita al responsable o supervisor la compra o reposición de materiales. |
| Audit Trail             | Trazabilidad de Auditoría   | Conjunto de registros que muestran todas las acciones realizadas sobre el inventario para fines de control y seguridad. |


## Capítulo III: Requirements Specification
### 3.1. User Stories
## Epics

| Epic ID | Title                               | Descripción                                                                                         |
|---------|-----------------------------------|---------------------------------------------------------------------------------------------------|
| EP03    | User Profile                      | **Como usuario, quiero** gestionar y personalizar mi perfil, incluyendo ingreso, modificación y carga de documentos **para** mantener mi información actualizada y accesible.   |
| EP04    | Laboratory Inventory Management   | **Como usuario, quiero** registrar, controlar y actualizar el inventario mediante tecnologías QR/RFID, y generar historiales de uso **para** un manejo eficiente.   |
| EP05    | Subscription Management           | **Como usuario, quiero** gestionar el proceso completo de suscripción, desde la selección y pago, hasta la activación, prueba y cancelación **para** acceder a servicios de forma flexible.       |
| EP06    | Reports and laboratory analysis   | **Como administrador, quiero** generar reportes y visualizar métricas para analizar uso, calidad e inventario, y apoyar auditorías y mejora continua, **para** tener una visión global de la calidad del servicio.          |
| EP07    | Alerts and Notifications Manager  | **Como administrador, quiero** configurar y recibir alertas críticas y notificaciones para supervisar condiciones y estados del laboratorio que permitan respuestas inmediatas.|
| EP08    | Laboratory Management             | **Como inspector o coordinador, quiero** seleccionar y administrar laboratorios y productos, así como controlar inspecciones para garantizar la calidad y trazabilidad, **para** gestionar el laboratorio correctamente.     |

## User Stories
| User Story ID | Título               | Descripción                            | Criterios de aceptación                  | Épica                 |
|---------------|----------------------|--------------------------------------|-----------------------------------------|-----------------------|
| US-01         |Pestaña de Perfil|Como usuario, quiero tener un perfil donde ingresar mi información personal y mis documentos para poder gestionar y consultar mis datos fácilmente.|Escenario 1:Given el usuario desea consultar su perfil, when accede a la pestaña "Mi Perfil", then tendrá la opción "Crear Nuevo Perfil" o podrá modificarlo con "Modificar Perfil". Escenario 2:Given el usuario se encuentra en otra pestaña, when selecciona desde el toolbar el Button "Mi Perfil", then se le redirigirá a la pestaña de mis datos.|           EP01            |
| US-02         |Crear Perfil|Como usuario, quiero crear un perfil donde ingresar mi información personal para que mis datos queden registrados y pueda acceder a las funciones personalizadas del sistema.|Escenario 1:Given el usuario desea crear un perfil, when accede a la opción "Nuevo Perfil", then deberá ingresar su información en el formulario. Escenario 2:Given el usuario esta creando su perfil, when hace click en finalizar cuando hay campos vacíos, then se le pedirá ingresar información válida en todos los campos.|           EP01            |
| US-03         |Modificar Perfil|Como usuario, quiero modificar la información ingresada en mi perfil para mantener mis datos actualizados y corregir cualquier error que detecte. |Escenario 1:Given el usuario desea modificar su perfil, when accede a su perfil ya creado, then podrá modificar cada campo con "Modificar Perfil". Escenario 2:Given el usuario esta modificando un campo de su perfil, when ingresa información incorrecta, then se le pedirá ingresar información válida.|           EP01            |
| US-04         |Cargar documentos |Como usuario, quiero poder cargar mis documentos personales en mi perfil para poder consultar data y tener todos mis archivos centralizados y disponibles.|Escenario 1:Given el usuario está en su perfil, when selecciona la opción cargar documentos, then podrá cargar los documentos necesarios. Escenario 2:Given el usuario está en su perfil, when selecciona una imagen ya cargada, then podrá cambiar dicha imagen por una nueva.|           EP01            |
| US-05         |Registrar el ítem en el inventario con QR/RFID |Como usuario, quiero registrar el ítem en el inventario escaneando su código QR o etiqueta RFID para agilizar la identificación y el control de existencias.|Escenario 1: Given el usuario tiene un nuevo ítem con QR/RFID, when escanea el código con el lector, then el sistema registra automáticamente el ítem en el inventario junto con sus detalles.|           EP02            |
| US-06         |Escanear insumo para salida/uso en prácticas|Como usuario, quiero escanear el insumo antes de utilizarlo o darlo de baja en una práctica, para llevar un control de su uso y destino.|Escenario 1: Given el usuario está por utilizar un insumo, when escanea el código QR/RFID al salir del almacén o iniciar la práctica, then el sistema registra ese uso o salida en el historial correspondiente.|           EP02            |
| US-07         |Actualizar stock automáticamente tras venta/retorno|Como usuario, quiero que el sistema actualice automáticamente el stock después de una salida o retorno, para contar siempre con datos precisos del inventario.|Escenario 1: Given un insumo fue retirado y escaneado para salida, when se completa la operación de venta o devolución, then el sistema descuenta o suma automáticamente la cantidad correspondiente en el stock.|           EP02            |
| US-08         |Generar historial de uso para cada insumo|Como usuario, quiero que el sistema genere y muestre un historial de uso detallado para cada insumo, para poder auditar su trazabilidad y controlar inventarios.|Escenario 1: Given el usuario consulta un insumo específico, when accede a la visualización del historial, then el sistema muestra todas las salidas, retornos y usos registrados para ese ítem en forma de línea de tiempo.|           EP02            |
| US-09         |Seleccionar plan de suscripción |Como usuario, quiero poder elegir entre diferentes planes de suscripción para contratar el servicio.|Escenario 1: Given el usuario accede al catálogo de suscripciones, when selecciona una opción de plan, then el sistema debe mostrar el detalle y costo de cada suscripción antes de finalizar la compra.|           EP03            |
| US-10         |Registrar método de pago|Como usuario, quiero guardar mi método de pago preferido para procesar pagos recurrentes fácilmente.|Escenario 1: Given el usuario está realizando la compra de una suscripción, when selecciona un método de pago, then el sistema debe guardar el método y confirmar la operación. Escenario 2: Given el usuario ha guardado un método de pago anteriormente, when quiere modificarlo, then el sistema debe permitir reemplazarlo por uno nuevo.|           EP03            |
| US-11         |Activar periodo de prueba|Como usuario, quiero activar un periodo de prueba para evaluar el servicio antes de pagar la suscripción completa para probar el plan a mi elección.|Escenario 1: Given el usuario ha completado el proceso de compra, when selecciona la opción de periodo de prueba, then el sistema activa la suscripción temporal y muestra el tiempo restante. Escenario 2: Given el periodo de prueba está por finalizar, when el usuario recibe la notificación, then el sistema le ofrece la opción de continuar con el servicio mediante el pago correspondiente.|           EP03            |
| US-12         |Cancelar suscripción|Como usuario, quiero cancelar mi suscripción en cualquier momento para tener control sobre ella. |Escenario 1: Given el usuario tiene una suscripción activa, when accede a la opción de cancelación, then el sistema da de baja el servicio y actualiza el estado en el CRM. Escenario 2: Given la suscripción está cancelada, when el usuario intenta acceder al servicio, then el sistema muestra un mensaje informando que su suscripción ya no está activa.|           EP03            |
| US-13         |Recibir alerta de temperatura.|Como administrador quiero recibir una alerta cuando un equipo del laboratorio registre una temperatura fuera de rango para tomar acciones inmediatas y evitar daños a los insumos o equipos. |Escenario 1: Given el sistema detecta que un equipo supera el rango de temperatura permitido, When ocurre el evento, Then el sistema envía una alerta inmediata al administrador vía el canal configurado (correo, app, SMS). Escenario 2: Given el administrador recibe la alerta, When accede al detalle de la notificación, Then el sistema muestra el equipo afectado, la temperatura registrada y la hora exacta. |           EP04            |
| US-14         |Recibir notificación de insumos próximos a vencer|Como administrador quiero recibir notificaciones de insumos próximos a vencer para tomar decisiones sobre su uso, reposición o descarte oportuno.|Escenario 1: Given un insumo está a menos de 30 días de su fecha de vencimiento, When el sistema ejecuta la validación diaria, Then genera una notificación resaltando el insumo con su fecha de caducidad. Escenario 2: Given el administrador recibe la notificación, When hace clic en el insumo listado, Then el sistema muestra su historial de uso y el stock disponible.|           EP04            |
| US-15         |Recibir alerta de bajo stock de insumos|Como administrador quiero recibir alertas cuando el stock de un insumo llegue al nivel mínimo definido para garantizar la reposición a tiempo y evitar interrupciones en el laboratorio.|Escenario 1: Given el stock de un insumo alcanza o baja del nivel mínimo, When se registra la salida de inventario, Then el sistema genera una alerta automática. Escenario 2: Given el administrador consulta la alerta, When abre el detalle, Then visualiza el insumo afectado, la cantidad restante y el umbral configurado. |           EP04            |
| US-16         |Configurar tipos y canales de alerta|Como administrador quiero configurar qué tipos de alertas recibir y a través de qué canales (correo, SMS, app) para personalizar las notificaciones según mis necesidades. |Escenario 1: Given el administrador accede al módulo de configuración de alertas, When selecciona los tipos de alertas (temperatura, vencimiento, stock), Then el sistema guarda la preferencia y solo enviará esas notificaciones. Escenario 2: Given el administrador elige un canal de notificación, When activa correo electrónico y desactiva SMS, Then el sistema enviará únicamente por el canal habilitado. |           EP04            |
| US-17         |Generar reporte de inventario|Como administrador quiero generar un reporte descargable del estado actual del inventario (stock, insumos vencidos, próximos a vencer) para tener visibilidad completa y respaldar auditorías. |Escenario 1: Given el administrador accede al módulo de reportes, When selecciona "Inventario Actual", Then el sistema genera un archivo PDF/Excel con la información detallada. Escenario 2: Given el administrador genera el reporte, When el sistema detecta insumos con bajo stock o próximos a vencer, Then resalta dichos insumos en el reporte. |           EP05            |
| US-18         |Dashboard de métricas de uso |Como administrador quiero visualizar un dashboard con estadísticas de insumos utilizados, prácticas realizadas y alertas recibidas para analizar tendencias de consumo en el laboratorio. |Escenario 1: Given el administrador ingresa al dashboard, When consulta el gráfico de insumos consumidos por mes, Then puede ver la tendencia en tiempo real. Escenario 2: Given el administrador necesita información detallada, When selecciona un insumo, Then el dashboard muestra su historial de uso. |           EP05            |
| US-19         |Reporte de inspecciones y calidad |Como coordinador de calidad quiero obtener un listado histórico de productos inspeccionados (aprobados, rechazados, en corrección) para garantizar trazabilidad y mejorar procesos de control de calidad.|Escenario 1: Given el coordinador accede al módulo de reportes, When genera un reporte de inspecciones, Then el sistema muestra el estado y resultado de cada producto inspeccionado. Escenario 2: Given el coordinador filtra por rango de fechas, When aplica el filtro, Then el sistema muestra solo inspecciones realizadas en ese periodo. |           EP05            |
| US-20         |Exportar reportes automatizados|Como administrador quiero configurar reportes periódicos automáticos que se envíen a mi correo para no depender de generar manualmente cada reporte. |Escenario 1: Given el administrador activa "Reporte Semanal", When llega la fecha configurada, Then el sistema envía automáticamente el reporte al correo del administrador. Escenario 2: Given el administrador quiere desactivar un reporte automático, When selecciona la opción "Cancelar", Then el sistema detiene el envío de reportes futuros. |           EP05            |
| US-21         |Selección de laboratorio|Como inspector deseo seleccionar un laboratorio de una lista de laboratorios para elegir el laboratorio de mi preferencia entre varias opciones.|Escenario 1: Given inspector desea elegir un laboratorio ,When accede a la lista despegable ,Then tendrá la opción de laboratorios. Escenario 2: Given no hay laboratorios disponibles ya que está en el límite de capacidad When el investigador abre la lista Then el sistema muestra “No hay laboratorios disponibles” y ofrece opción “Notificar cuando esté disponible”|           EP06            |
| US-22         |Subir producto| Como inspector Quiero subir (registrar) un producto al laboratorio seleccionado para que el producto pueda pasar por el proceso de inspección de calidad. | Escenario 1: Given el inspector tiene un laboratorio seleccionado When completa el formulario con todos los datos válidos y carga los archivos requeridos, y presiona “Enviar”  Then el sistema crea el registro del producto con estado Pendiente de inspección y muestra confirmación. Escenario 2: Given el investigador completa parcialmente el formulario (falta un campo obligatorio)  When intenta enviar Then el sistema no permite enviar y muestra validaciones (ej.: “El campo X es obligatorio”). Escenario 3: Given el investigador completa todo el formulario   When envía el formulario Then el sistema registra el producto para ser verificado |           EP06            |
| US-23         |Inspección de calidad productos|Como técnico de laboratorio quiero realizar la inspección del producto y registrar el resultado para decidir si el producto se aprueba, requiere corrección o se rechaza.|Escenario 1: Given un producto con estado pendiente de inspección When el inspector revisa la documentación y registra “Cumple especificaciones” y marca Aprobado Then el producto pasa a estado Aprobado y se registra la fecha y el inspector. Escenario 2: Given un producto inspeccionado presenta una no conformidad menor When el inspector registra la incidencia y marca Con incidencia y agrega feedback/especificaciones de corrección then se notifica al investigador con el detalle y el producto queda en estado En corrección hasta nueva revisión. Escenario 3: Given el producto tiene una falla crítica que impide su uso When el inspector marca Rechazado y adjunta evidencias Then el producto queda con estado Rechazado, se notifican las partes y se registra la decisión final|           EP06            |
| US-24         |Aprobar producto|Como coordinador de calidad / jefe de laboratorio quiero aprobar formalmente productos que cumplieron la inspección para autorizar su uso/almacenamiento/distribución en el laboratorio.|Escenario 1: Given un producto con inspección marcada como Aprobado y evidencia registrada When el coordinador revisa y pulsa “Aprobar producto” Then el producto cambia a estado producto aprobado y se notifica al investigador. Escenario 2: Given un producto previamente Con incidencia que el investigador corrigió y reenvió evidencia When el inspector verifica la corrección y la marca como resuelta, y el coordinador valida la resolución Then el coordinador puede aprobar y el producto transita a producto aprobado|           EP06            |


### 3.2. Impact Mapping
En el Impact Mapping se define un objetivo de negocio claro y específico, como mejorar el acceso a servicios de laboratorio y supervisores. Se identifican los usuarios clave, y se establecen los impactos deseados para mejorar la experiencia y eficiencia del servicio. Finalmente, se derivan las User Stories que guían el desarrollo de funcionalidades prioritarias alineadas con el objetivo comercial.

<img src="assets/assets/chapter-3/impact-map-labiot.png" width=max>

### 3.3. Product Backlog
El Product Backlog es una lista dinámica y priorizada que contiene todas las tareas y funcionalidades necesarias para desarrollar la plataforma web de laboratorios. A partir de las User Stories definidas en el Impact Mapping, el backlog organiza el trabajo del equipo de desarrollo, asegurando que se construyan características clave como reserva de citas en línea, gestión de resultados y comunicación entre pacientes y laboratorios, para cumplir con el objetivo de negocio.

<img src="assets/assets/chapter-3/product-backlog-labiot.png" width=max>

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
#### 4.2.1. Organization Systems
1. Organization Scheme (Esquema de organización)
- Temático/Funcional: la información se organiza según las funciones principales del sistema:
  - Gestión de usuarios (registro, login, perfil, documentos).
  - Gestión de inventario (registro, stock, alertas).
  - Inspecciones de calidad (subida, revisión, aprobación).
  - Landing Page (información y promoción del producto).
  - Reportes y analítica.

2. Organization Structure (Estructura de organización)

- Jerárquica (Árbol): desde la Landing Page como entrada, se navega a módulos principales.
- Lineal: en procesos como registro de cuenta o inspección, los pasos siguen una secuencia.
- Matriz: en búsquedas/filtrados, por ejemplo inventario que puede organizarse por fecha, tipo de insumo, laboratorio.

3. Organization System (Sistema de organización aplicado)
- Global navigation (menú principal en el header): acceso a
  - Home (Landing Page)
  - Inventario
  - Inspecciones
  - Perfil
  - Reportes
  - Contacto
- Local navigation (submenús dentro de cada sección):
  - Perfil → Crear, Editar, Documentos.
  - Inventario → Registrar, Stock, Historial.
  - Inspecciones → Pendientes, Aprobados, Rechazados.
Contextual navigation (botones de acción dentro de un flujo):
“Cargar documento”, “Enviar a inspección”, “Generar reporte”.

<p align="center">
<img src="/assets/assets/chapter-4/database-design/lab-iot-organization-diagram.png" alt="organization structure" style="height:300px;">
</p>

#### 4.2.2. Labeling Systems
#### Objetivos
- Facilitar organización y filtrado de contenido (ej. artículos, productos, laboratorios, insumos).
- Mantener consistencia en nombres y jerarquía.
- Mejorar la experiencia de búsqueda y SEO (etiquetas bien diseñadas ayudan a generar URLs y meta datos coherentes).

#### Estructura recomendada
- **Estructura**: Categoría principal → Subcategoría → Etiquetas.
    - Ejemplo: `Equipos > Microscopios > Fluorescencia`
- **Tipos de etiquetas**:
    - `category` (1 por ítem)
    - `tags` (0..n, keywords de libre asociación)
    - `attributes` (pares clave:valor para filtros: `brand=Sigma`, `status=new`)

#### Convenciones (formato)
- Minúsculas, `kebab-case` para URLs y slug: `microscopios-fluorescencia`
- Human-readable en UI: `Microscopios de fluorescencia`
- Longitud: etiquetas entre 2 y 5 palabras preferible.

#### Modelo de datos (ejemplo JSON)
```json
{
  "id": "lbl_0001",
  "type": "category",
  "slug": "microscopios-fluorescencia",
  "name": "Microscopios de fluorescencia",
  "parent_id": "lbl_000",
  "created_at": "2025-09-19T00:00:00Z"
}
```

#### Interfaz de gestión
- CRUD de etiquetas con permisos (admin/editor)
- Vista previa de cómo afectaría al contenido (p. ej. URL y breadcrumbs)
- Historial de cambios (auditoría)

#### Reglas y validaciones
- No duplicados (slug único por tipo)
- Validar reutilización: sugerir etiquetas existentes al crear nuevas (autocomplete)

#### Ejemplos de uso en URLs
- `/categoria/microscopios-fluorescencia/` (landing de categoría)
- `/buscar?q=microscopios+fluorescencia&brand=Sigma`

#### 4.2.3. SEO Tags and Meta Tags

#### Objetivos
- Mejora del CTR en SERPs (títulos y descripciones atractivas)
- Control de indexación (robots/meta)
- Enriquecer previews en redes sociales (Open Graph / Twitter Cards)
- Añadir datos estructurados (Schema.org / JSON-LD)

#### Meta tags clave (plantilla)
```html
<title>{{page_title}} | {{site_name}}</title>
<meta name="description" content="{{meta_description}}" />
<link rel="canonical" href="{{canonical_url}}" />
<meta name="robots" content="index, follow" />
<!-- Open Graph -->
<meta property="og:title" content="{{og_title}}" />
<meta property="og:description" content="{{og_description}}" />
<meta property="og:image" content="{{og_image}}" />
<meta property="og:url" content="{{canonical_url}}" />
<meta property="og:type" content="article" />
<!-- Twitter -->
<meta name="twitter:card" content="summary_large_image" />
<meta name="twitter:title" content="{{twitter_title}}" />
<meta name="twitter:description" content="{{twitter_description}}" />
<meta name="twitter:image" content="{{twitter_image}}" />
```

#### Reglas prácticas
- **Title**: 50–60 caracteres (incluye site name). Priorizar keywords al inicio.
- **Meta description**: 120–160 caracteres, llamada a la acción si aplica.
- **Canonical**: siempre presente en páginas con parámetros.
- **Meta robots**: `noindex` en páginas duplicadas, `index` en content principal.

#### JSON-LD (ejemplo para un artículo)
```html
<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "Article",
  "headline": "{{title}}",
  "image": ["{{og_image}}"],
  "datePublished": "{{published_at}}",
  "author": [{"@type":"Person","name":"{{author_name}}"}],
  "publisher": {"@type":"Organization","name":"{{site_name}}","logo":{"@type":"ImageObject","url":"{{site_logo}}"}}
}
</script>
```

#### Renderizado (server vs client)
- **Server-side rendering (SSR)** o prerender es preferible para SEO: meta tags deben estar en HTML inicial.
- Si SPA (client-side), usar prerendering o soluciones como Next.js/Remix o servidor que inyecte meta tags.

#### Sitemaps y robots.txt
- `sitemap.xml` automático (URLs con prioridad y `lastmod`).
- `robots.txt` con ruta a sitemap y reglas públicas.

---

#### 4.2.4. Searching Systems

#### Requerimientos funcionales
- Búsqueda por texto (título, descripción, etiquetas)
- Autocomplete / sugerencias (typeahead)
- Fuzzy search (tolerancia a typos)
- Facetas / filtros (categoría, brand, status, rango de fechas)
- Paginación / infinite scroll
- Highlight/snippets en resultados
- Orden por relevancia, fecha, popularidad

#### Opciones de tecnología (comparativa rápida)
- **Postgres Full-Text Search**
    - Pros: integrado, sencillo, bajo costo.
    - Contras: menos poderoso en ranking, menor escalabilidad en features avanzadas.
- **Elasticsearch / OpenSearch**
    - Pros: relevancia avanzada, faceting, alta performance, análisis lingüístico.
    - Contras: infra adicional, operaciones de mantenimiento.
- **Algolia (SaaS)**
    - Pros: experiencias de búsqueda ultrarrápidas, buena UX out-of-the-box.
    - Contras: coste, datos en terceros.

#### Esquema de índice (ejemplo para Elastic)
```json
{
  "mappings": {
    "properties": {
      "id": { "type": "keyword" },
      "title": { "type": "text", "analyzer": "standard" },
      "description": { "type": "text", "analyzer": "standard" },
      "tags": { "type": "keyword" },
      "category": { "type": "keyword" },
      "published_at": { "type": "date" },
      "popularity": { "type": "integer" }
    }
  }
}
```
#### 4.2.5. Navigation Systems

A continuación, presentaremos el sistema de navegación con el que contará LabloT que permitirá al usuario navegar tanto en el landing page como en la aplicación web.  
Hemos implementado un sistema de navegación tipo Navigation Tabs que permite tener una vista rápida de las opciones de la aplicación para facilitar la interacción del usuario.
esto enviame en condigo para agregarle a mi documento.

***Estructura del Sistema de Navegación***

<p align="center">
<img src="/assets/assets/chapter-4/NavigationSystems2.png" alt="distribucion" style="height:300px;">
</p>


<p align="center">
<img src="/assets/assets/chapter-4/NavigationSystems.png" alt="accesibilidad" style="width:1000px;" >
</p>

### 4.3. Landing Page UI Design
#### 4.3.1. Landing Page Wireframe
El wireframe de la landing page presenta una estructura clara con hero section, value proposition, features, benefits, FAQs, contact y call-to-actions estratégicos.
- Inicio: En la parte superior se ubica nuestro logo principal atractivo y barra de navegación con las secciones de nuestra landing page. Incluye un botón de “Comienza gratis” como CTA destacado.

<p align="center"> <img src="/assets/assets/chapter-4/landing-page-ui-design/hero-wf.jpg" alt="hero wireframe" width="600"> </p>

- ¿Cómo funciona?: En esta sección se describe el proceso de funcionamiento de nuestro producto en 3 simples pasos.

<p align="center"> <img src="/assets/assets/chapter-4/landing-page-ui-design/hdiw-wf.jpg" alt="hdiw wireframe" width="600"> </p>

- Caracteristicas: Se presentan las funcionalidades principales de la plataforma en bloques simples con descripciones breves, permitiendo que el usuario entienda rápidamente lo que ofrecemos.

<p align="center"> <img src="/assets/assets/chapter-4/landing-page-ui-design/features-wf.jpg" alt="features wireframe" width="600"> </p>

- Beneficios y FAQs: Sección dedicada a mostrar el valor agregado de la solución, resaltando las ventajas competitivas y diferenciales con respecto a alternativas existentes en el mercado, además de la sección de FAQs para minimizar dudas generales de los consumidores.

<p align="center"> <img src="/assets/assets/chapter-4/landing-page-ui-design/benefits-&-faqs-wf.jpg" alt="benefits faqs wireframe" width="600"> </p>

- Contacto y Footer: Sección final con un formulario de contacto y un footer con enlaces a redes sociales, ofreciendo múltiples vías de comunicación directa con la plataforma.

<p align="center"> <img src="/assets/assets/chapter-4/landing-page-ui-design/contact-&-footer-wf.png" alt="contact y footer wireframe" width="600"> </p>

#### 4.3.2. Landing Page Mock-up
El mock-up refleja la identidad de marca con los colores aplicados, algunos no reflejan el producto final ya que hay degradados entre 2 colores que Figma no permite representar. Los botones de CTA contrastan para destacar las acciones principales. Las imágenes muestran diversidad en los servicios ofrecidos.

<p align="center"> <img src="/assets/assets/chapter-4/landing-page-ui-design/hero-mu.jpg" alt="hero mock up" width="600"> </p>

<p align="center"> <img src="/assets/assets/chapter-4/landing-page-ui-design/hdiw-mu.png" alt="hdiw mock up" width="600"> </p>

<p align="center"> <img src="/assets/assets/chapter-4/landing-page-ui-design/features-mu.png" alt="features mock up" width="600"> </p>

<p align="center"> <img src="/assets/assets/chapter-4/landing-page-ui-design/benefits-mu.png" alt="benefits mock up" width="600"> </p>

<p align="center"> <img src="/assets/assets/chapter-4/landing-page-ui-design/faqs-mu.png" alt="faqs mock up" width="600"> </p>

<p align="center"> <img src="/assets/assets/chapter-4/landing-page-ui-design/contact-mu.png" alt="contact mock up" width="600"> </p>

<p align="center"> <img src="/assets/assets/chapter-4/landing-page-ui-design/footer-mu.png" alt="footer mock up" width="600"> </p>

### 4.4. Web Applications UX/UI Design
#### 4.4.1. Web Applications Wireframes
<img src="assets/assets/chapter-4/WebApplicationsWireframes/WebApplicationsWireframes.png" alt="">
En esta pantalla se muestra el inicio de sesion con el respectivo formulario para poder iniciar en el aplicativo web.
<img src="assets/assets/chapter-4/WebApplicationsWireframes/WebApplicationsWireframes2.png" alt="">

<img src="assets/assets/chapter-4/WebApplicationsWireframes/WebApplicationsWireframes3.png" alt="">

<img src="assets/assets/chapter-4/WebApplicationsWireframes/WebApplicationsWireframes4.png" alt="">

<img src="assets/assets/chapter-4/WebApplicationsWireframes/WebApplicationsWireframes5.png" alt="">

<img src="assets/assets/chapter-4/WebApplicationsWireframes/WebApplicationsWireframes6.png" alt="">

<img src="assets/assets/chapter-4/WebApplicationsWireframes/WebApplicationsWireframes7.png" alt="">

<img src="assets/assets/chapter-4/WebApplicationsWireframes/WebApplicationsWireframes8.png" alt="">


#### 4.4.2. Web Applications Wireflow Diagrams
#### 4.4.3. Web Applications Mock-ups
<img src="assets/assets/chapter-4/WebApplicationsMock-ups/WebApplicationsMock-ups1.png" alt="">

<img src="assets/assets/chapter-4/WebApplicationsMock-ups/WebApplicationsMock-ups2.png" alt="">

<img src="assets/assets/chapter-4/WebApplicationsMock-ups/WebApplicationsMock-ups3.png" alt="">

<img src="assets/assets/chapter-4/WebApplicationsMock-ups/WebApplicationsMock-ups4.png" alt="">

Link para ver los wireframes en figma: https://www.figma.com/design/WTa9gqJiXGCnoS6XS6OEpm/Landin-Page?node-id=0-1&t=H5VVd8liPBlLH61K-1

#### 4.4.4. Web Applications User Flow Diagrams
<img src="assets/assets/chapter-4/WebApplicationsUserFlowDiagrams/WebApplicationsUserFlowDiagrams.png" alt="">

Link para ver Web Applications User Flow Diagrams: https://miro.com/welcomeonboard/ZDF5b0hKTlhzTUlaUTRsZTV5dkdzQUZxTEZnZWhOTTZHZVNHenBleGNhS09DMXVSQTNuU0hTZEtQaDdQUGRQbWFYVmZNK1BVM1E5SkxoWmdGeTN3dE9RNGZobjJMbmh4Z0xPdzZKRjVDamhUVUNpTjlKUzlITHZkTVZQVi8rcDJzVXVvMm53MW9OWFg5bkJoVXZxdFhRPT0hdjE=?share_link_id=575139599232

### 4.5. Web Applications Prototyping
### 4.6. Domain-Driven Software Architecture
#### 4.6.1. Design-Level EventStorming
#### 4.6.2. Software Architecture Context Diagram
#### 4.6.3. Software Architecture Container Diagrams
#### 4.6.4. Software Architecture Components Diagrams
### 4.7. Software Object-Oriented Design
#### 4.7.1. Class Diagrams
El diagrama de clases presenta una representación visual clara de las clases que componen LabIoT, detallando sus atributos principales y las relaciones que existen entre ellas. Estos diagramas son fundamentales para entender la estructura interna de LabIoT, facilitando la comprensión de cómo interactúan los diferentes componentes del sistema, desde la gestión de usuarios, inventarios, suscripciones, hasta el monitoreo con sensores IoT y alertas en tiempo real. La representación gráfica permite identificar fácilmente los roles y responsabilidades de cada clase, así como la arquitectura general del sistema, siendo un recurso esencial para el diseño y desarrollo eficiente de LabIoT.

<img src="assets/assets/chapter-4/class-diagram-labiot.png" alt="">

### 4.8. Database Design

La base de datos constituye el núcleo de la solución LabIoT, ya que concentra la información que permite la gestión eficiente de
inventarios en laboratorios. Su diseño se orienta a garantizar integridad, trazabilidad y confiabilidad de los datos, elementos
indispensables en entornos donde la precisión es crítica para el éxito de las operaciones.

El modelo propuesto responde a los siguientes objetivos:

1. Trazabilidad completa: registrar el recorrido de cada insumo desde su proveedor hasta su consumo o descarte en el laboratorio.

2. Reducción de errores humanos: reemplazar registros manuales con procesos automatizados que fortalezcan la exactitud en auditorías.

3. Monitoreo en tiempo real: almacenar lecturas de sensores IoT para asegurar condiciones óptimas (temperatura, humedad).

4. Gestión proactiva de riesgos: generar alertas sobre caducidad, stock bajo o condiciones fuera de rango.

5. Cumplimiento normativo: mantener evidencia auditable de todos los movimientos y condiciones de almacenamiento.

#### 4.8.1. Database Diagram

Tablas principales

- **Usuarios**
  Contiene los datos de los distintos actores del sistema (investigadores, técnicos, administradores, proveedores). Permite asociar
  cada movimiento o acción a un responsable, reforzando la trazabilidad y la seguridad del sistema.

- **Laboratorios**
  Identifica cada laboratorio o sede en la que se gestionan insumos. Esta separación facilita la organización de inventarios
  distribuidos y el análisis independiente por unidad.

- **Proveedores**
  Registra los datos de las empresas que abastecen insumos, vinculando la cadena de suministro al laboratorio. Esta entidad asegura
  transparencia y control en las relaciones comerciales.

- **Insumos**
  Representa el catálogo central de materiales de laboratorio. Incluye atributos como nombre, tipo, lote y fecha de vencimiento.
  Es la tabla principal del sistema, ya que conecta con movimientos, condiciones y alertas.

- **Condiciones**
  Almacena las lecturas de sensores IoT relacionadas a insumos (temperatura, humedad). Proporciona un historial verificable que
  respalda auditorías y certificaciones.

- **Movimientos**
  Registra entradas, salidas y transferencias de insumos. Cada operación queda asociada a un usuario y a un momento específico en
  el tiempo, lo que permite reconstruir el historial de un insumo.

- **Alertas**
  Centraliza las notificaciones relacionadas con riesgos operativos: caducidad próxima, condiciones fuera de rango o stock bajo.
  Permite a los responsables actuar de manera preventiva y mantener la continuidad de las operaciones.


Diagrama de Base de datos

<p align="center">
<img src="/assets/assets/chapter-4/database-design/databasediagram.png" alt="database-diagram" style="height:500px;">
</p>

El diagrama de clases para este proyecto se puede encontrar en el
documento [docs/database-diagram.puml](docs/database-diagram.puml).

## Capítulo V: Product Implementation, Validation & Deployment
### 5.1. Software Configuration Management
#### 5.1.1. Software Development Environment Configuration
**Project Management**
**Discord** funciona como la herramienta principal de comunicación en tiempo real entre los integrantes del equipo. Gracias a sus canales estructurados por temas y roles, permite llevar a cabo reuniones, coordinar las actividades diarias y brindar soporte inmediato a lo largo de todo el proceso de desarrollo. <br>
Ruta de referencia: [Discord](https://discord.com)
**Diseño UX/UI de Producto**

**Figma** se emplea como la herramienta principal para crear interfaces gráficas (UI) y definir la experiencia de usuario (UX). Facilita la colaboración en tiempo real entre varios miembros del equipo para elaborar prototipos interactivos, maquetas visuales y pruebas de diseño. <br>
Ruta de referencia: [Figma](https://www.figma.com)

**UXPressia** refuerza el proceso de UX al ofrecer recursos para generar y documentar User Personas, Customer Journey Maps y Empathy Maps. Esto permite comprender mejor a los usuarios finales y orientar las decisiones de diseño en función de sus necesidades. <br>
Ruta de referencia: [UXpressia](https://uxpressia.com)

**Trello** contribuye a la organización del trabajo de UX mediante tableros, listas y tarjetas, lo que facilita la gestión visual de tareas, ideas y flujos. Ayuda a que los equipos de diseño y desarrollo colaboren de manera ágil, prioricen funcionalidades centradas en el usuario y hagan seguimiento al avance de los proyectos. <br>
Ruta de referencia: [Trello](https://trello.com)

**Software Development**

**Visual Studio Code (VS Code)** es el editor de código principal utilizado en el desarrollo. Ofrece un entorno ligero y altamente personalizable que integra soporte para múltiples lenguajes de programación, extensiones y herramientas de depuración. Gracias a sus funciones de control de versiones y compatibilidad con Git, facilita el trabajo colaborativo y eficiente en los proyectos de software. <br>
Referencia: [Visual Studio Code](https://code.visualstudio.com/)

**Software Deployment**

**Git** se emplea como sistema de control de versiones para administrar el historial de cambios en el código fuente. Permite la colaboración simultánea de varios desarrolladores con control sobre ramas, fusiones y diferentes versiones del proyecto. <br>
Referencia: [Git](https://git-scm.com/)

**GitHub** es la plataforma en línea donde se alojan y gestionan los repositorios del proyecto. Ofrece herramientas para la colaboración, control de versiones, gestión de issues y pull requests, lo que asegura una integración ordenada y segura de los cambios en el software. <br>
Referencia: [GitHub](https://github.com/)

**GitHub Pages** se emplea como plataforma de alojamiento para desplegar la interfaz frontend de la aplicación. Al estar integrada con los repositorios de GitHub, posibilita la publicación de sitios web estáticos de manera rápida, automatizada y gratuita. <br>
Referencia: [GitHub Pages](https://docs.github.com/es/pages)
#### 5.1.2. Source Code Management
El proyecto adoptará las convenciones del modelo GitFlow como esquema principal de control de versiones, empleando GitHub como plataforma de gestión. A continuación, se describe la aplicación de GitFlow como flujo de trabajo de versionado y se incluyen los enlaces a los repositorios correspondientes al producto Landing Page:

**Repositorios de GitHub:**
- Organización en GitHub: [Los-Bytes](https://github.com/Los-Bytes)

- Repositorio de la Landing Page: [Landing Page LabIoT](https://github.com/MarceloMazuelos/LabIoT-Landing-Page/)

**Flujo de trabajo GitFlow:**
Para el desarrollo del proyecto se seguirá el modelo de ramas propuesto por Vincent Driessen en “A successful Git branching model”.
**Estructura de ramas**
1. **Rama principal (Main branch):**
   Corresponde al núcleo del proyecto y almacenará únicamente versiones estables y definitivas de la aplicación. Los cambios que lleguen a esta rama deberán haber sido previamente probados y validados en ramas de desarrollo o prueba.

2. **Rama de desarrollo (Development branch):**
   Será el espacio destinado a concentrar los avances colectivos del equipo, manteniendo los archivos centrales del desarrollo en curso. Apartir de esta rama se crearán otras ramas para desarrollo individual para posterior merge.
#### 5.1.3. Source Code Style Guide & Conventions
- Estructura de Archivos
  Usa la convención kebab-case para nombres de archivos y carpetas (my-component.vue).
  Mantén los componentes en la carpeta src/components.
  Archivos principales: App.vue, main.js, index.html.
- Sintaxis Vue
  Usa la sintaxis ´script setup´ para componentes Vue 3. Un solo componente por archivo .vue. Orden de secciones: template, script, style.
- Estilo de Código JavaScript
  Usa const y let en vez de var. Usa arrow functions cuando sea posible. Indentación de 2 espacios. Punto y coma al final de cada sentencia. Nombres de variables y funciones en camelCase.
- Estilo de Código CSS/Tailwind
  Usa clases utilitarias de TailwindCSS en el template. Para estilos personalizados, usa style scoped en los componentes. Prefiere clases sobre estilos en línea.
#### 5.1.4. Software Deployment Configuration
**Despliegue de la Landing Page**

Para desplegar la landing page se deben cumplir algunos requisitos previos:
- Contar con una **cuenta personal en GitHub**.
- Disponer de una **organización**.
- Tener un **repositorio** donde alojar los archivos del proyecto.

**Pasos para el despliegue:**

1. Crear una carpeta llamada **`docs`** que contendrá la landing page.
2. Asegurar que los archivos cumplan con la siguiente convención de nombres:
    - `index.html` → página principal.
    - `style.css` → hoja de estilos.
    - `assets/` → carpeta que almacena las imágenes.
    - `src/` → carpeta del proyecto landing page

3. Subir todos los archivos al repositorio en GitHub.
4. Ingresar a **Settings > Pages** dentro del repositorio.
5. Seleccionar la rama que contiene el proyecto (generalmente `main` o `master`).
6. Indicar la carpeta **`/root`** como fuente de la página.
7. Esperar a que GitHub realice las validaciones automáticas.
### 5.2. Landing Page, Services & Applications Implementation
#### 5.2.1. Sprint 1
##### 5.2.1.1. Sprint Planning 1
En el marco de Scrum, un Sprint corresponde a un período corto y definido en el que el equipo lleva a cabo las tareas necesarias para avanzar hacia el objetivo general del proyecto, conocido como Product Goal (Schwaber & Sutherland, 2020). Para el desarrollo de la plataforma uTime, se decidió dividir el trabajo en cuatro sprints, cada uno con una duración de dos semanas. El Sprint 1, iniciado el 19/09/2025, tiene como propósito principal diseñar una landing page atractiva que logre captar la atención de los visitantes y transmita de manera clara los beneficios clave del producto.

<table>
   <tr>
      <td colspan="1" align="center"><b>Sprint #</b></td>
      <td colspan="1" align="center">Sprint 1</td>
   </tr>
   <tr>
      <td colspan="2" align="center"><b>Sprint Planning Background</b></td>
   </tr>
   <tr>
      <td colspan="1" align="center"><b>Date</b></td>
      <td colspan="1">2025-09-19</td>
   </tr>
   <tr>
      <td colspan="1" align="center"><b>Time</b></td>
      <td colspan="1">03:00 PM</td>
   </tr>
   <tr>
      <td colspan="1" align="center"><b>Location</b></td>
      <td colspan="1">Reunión virtual mediante la aplicación Discord</td>
   </tr>
   <tr>
      <td colspan="1" align="center"><b>Prepare By</b></td>
      <td colspan="1">Marcelo Mazuelos</td>
   </tr>
   <tr>
      <td colspan="1" align="center"><b>Attendees (to planning meeting)</b></td>
      <td colspan="1">Mazuelos Callirgos, Marcelo Alessandro</td>
   </tr>
   <tr>
      <td colspan="1" align="center"><b>Sprint n - 1 Review Summary</b></td>
      <td colspan="1">Este es el primer sprint del proyecto, por lo tanto, no hay resultados de un sprint anterior para revisar.</td>
   </tr>
   <tr>
      <td colspan="1" align="center"><b>Sprint n - 1 Retrospective Summary</b></td>
      <td colspan="1">Al tratarse del primer sprint, no se cuenta con una retrospectiva previa. La retroalimentación y oportunidades de mejora se evaluarán al finalizarse este sprint.</td>
   </tr>
   <tr>
      <td colspan="2" align="center"><b>Sprint Goal & User Stories</b></td>
   </tr>
   <tr>
      <td colspan="1" align="center"><b>Sprint 1 Goal</b></td>
      <td colspan="1"><b>Our focus is on</b> creating an attractive and fully functional landing page for LabIoT.<br><b>We believe it delivers</b> a clear presentation of the platform’s features and benefits, building trust and interest among potential users.<br><b>This will be confirmed when</b> visitors can easily explore and interact with all main sections of the landing page on both desktop and mobile devices.</td>
   </tr>
   <tr>
      <td colspan="1" align="center"><b>Sprint 1 Velocity</b></td>
      <td colspan="1">13</td>
   </tr>
   <tr>
      <td colspan="1" align="center"><b>Sum of Story Points</b></td>
      <td colspan="1">13</td>
   </tr>

   <tr>
</tr>
</table>

##### 5.2.1.2. Aspect Leaders and Collaborators
Para este Sprint se han establecido los aspectos esenciales relacionados con el desarrollo de la landing page de Utime. Con el propósito de optimizar la organización y la comunicación del equipo, se diseñó la matriz Leadership and Collaboration Matrix (LACX), en la cual se especifica quién desempeña el rol de Líder (L) y quiénes intervienen como Colaboradores (C) en cada uno de estos puntos clave. Esta asignación contribuye a una gestión más clara y a una ejecución más eficiente de las tareas encomendadas.

| **Team Member** | **GitHub Username** | **Landing Page** |
|---------------------------------------------------|---------------------|---------------|
| Mazuelos Callirgos, Marcelo Alessandro | MarceloMazuelos | L |

##### 5.2.1.3. Sprint Backlog 1
En relación al EP-02 de la interacción con la Landing Page
| **Sprint #** | **User Story ID** | **User Story Description** | **Task Assigned** |
|--------------|-------------------|----------------------------|-------------------|
| 1 | US-05 | Como usuario quiero poder entrar a la Landing Page y visualizarla correctamente | Marcelo Mazuelos |
| 1 | US-06 | Como usuario quiero entrar a la Landing Page y poder leer todo su contenido e información general sobre el producto | Marcelo Mazuelos |
| 1 | US-07 | Como usuario quiero poder encontrar la manera de realizar la acción deseada y ofrecida por el producto, en este caso, encontrar el botón que me llevará al registro o uso del aplicativo sin mayor esfuerzo | Marcelo Mazuelos |
| 1 | YUS-08 | Como usuario quiero poder ver traducida la página web según necesite | Marcelo Mazuelos |
##### 5.2.1.4. Development Evidence for Sprint Review
Durante el Sprint 1, el equipo se enfocó en el desarrollo de la landing page de BookMe, cumpliendo con los objetivos de presentar de manera clara y atractiva los servicios de la plataforma. A continuación, se detalla la evidencia del desarrollo:

| Repository | Branch | Commit Id | Commit Message | Commit Message Body | Committed on (Date) |
|---|---|---|---|---|---|
| MarceloMazuelos/LabIoT-Landing-Page | main | acba1ba | Implemented v1.0.0 of Landing Page | Implementa la estructura para la landing page. Incluye iconos, funcionalidades y descripciones breves. | 20/09/2025 |

##### 5.2.1.5. Execution Evidence for Sprint Review
Durante el Sprint 1, el equipo se enfocó en el desarrollo de la landing page de LabIoT, cumpliendo con el objetivo de presentar de manera clara y atractiva los servicios de la plataforma. Se implementaron las siguientes secciones:

* Header con navegación y CTA principal
* Sección de Introducción
* Sección de por que se debería usar LabIot
* Sección de ¿Cómo funciona?
* Sección de Características
* Sección de beneficios destacando ventajas competitivas
* Sección de preguntas frecuentes
* Formulario de contacto
* Footer
* Diseño responsivo para dispositivos móviles y escritorio
##### 5.2.1.6. Services Documentation Evidence for Sprint Review
Durante el Sprint 1, el equipo se enfocó en el desarrollo de la landing page de LabIoT, por lo que no se implementaron servicios web o endpoints en esta fase inicial del proyecto. El alcance de este sprint se limitó exclusivamente al diseño y desarrollo frontend de la página de presentación del producto.

Dado que este es el primer sprint del proyecto y el desarrollo de backend y APIs está planificado para sprints posteriores, no existen endpoints documentados con OpenAPI en este momento. La documentación de servicios web se incluirá en futuros sprints una vez que comience el desarrollo de las funcionalidades backend y la API de LabIoT.
##### 5.2.1.7. Software Deployment Evidence for Sprint Review
Durante el Sprint 1, el equipo se enfocó en el despliegue de la landing page de BookMe utilizando GitHub Pages, una plataforma de alojamiento gratuita integrada directamente con los repositorios de GitHub. Este enfoque permitió publicar el sitio de manera rápida, automatizada y sin costos adicionales, asegurando que los usuarios finales pudieran acceder al contenido de forma inmediata.

A continuación, se detallan los pasos realizados para configurar y ejecutar el despliegue:

##### Preparación del repositorio:

Se creó una carpeta llamada docs en la raíz del repositorio, la cual contiene todos los archivos necesarios para la landing page (index.html, style.css, img/, src/).

##### Configuración en GitHub:

Se accedió a la configuración del repositorio (Settings > Pages).

En la sección Build and deployment, se seleccionó la rama main como fuente y se especificó la carpeta root como directorio de publicación.

GitHub Actions procesó automáticamente los archivos y desplegó el sitio en la URL proporcionada por GitHub Pages.

El resultado fue un sitio totalmente funcional y accesible públicamente.

##### Verificación del despliegue:

Se realizaron pruebas de acceso desde diferentes dispositivos y navegadores para garantizar que el sitio se visualizara correctamente.

La URL final del despliegue es: https://marcelomazuelos.github.io/LabIoT-Landing-Page

Este proceso aseguró que la landing page estuviera disponible para su revisión y uso desde el primer sprint, sentando las bases para iteraciones futuras y integraciones con servicios adicionales.
##### 5.2.1.8. Team Collaboration Insights during Sprint
Durante el Sprint 1, el equipo se organizó bajo una metodología colaborativa que permitió desarrollar de manera eficiente la landing page de LabIoT. Aunque el desarrollo frontend estuvo principalmente a cargo de Marcelo Mazuelos, todos los miembros del equipo participaron activamente en las etapas de planificación, revisión de diseño y toma de decisiones sobre la estructura y contenido de la landing page.

La colaboración se llevó a cabo principalmente a través de:

Reuniones de planificación en Discord para definir el alcance y distribución de tareas

Revisiones constantes del diseño en Figma con comentarios de todos los integrantes

Code reviews mediante pull requests en GitHub

Comunicación continua en el canal de Discord del equipo
## Conclusiones

El desarrollo del proyecto LabIoT ha permitido aplicar de manera integral los conceptos de ingeniería de software y
metodologías de diseño centradas en el usuario al contexto de aplicaciones web modernas. A través de la definición de
antecedentes y problemática, el diseño de la guía de estilos, la construcción del modelo de base de datos y la
elaboración de Impact Mapping, se logró estructurar una solución orientada a la trazabilidad, seguridad y eficiencia
en la gestión de inventarios de laboratorio.

La utilización del framework Vue junto con lineamientos de Material Design y componentes de PrimeVue garantiza no solo
la consistencia visual, sino también la escalabilidad y mantenibilidad de la aplicación. Asimismo, la incorporación
de prácticas como el Needfinding, User Personas e Impact Mapping permitió vincular los objetivos de negocio con las
necesidades reales de los usuarios, asegurando que la propuesta tecnológica responda a un entorno colaborativo,
inclusivo y alineado con los criterios de calidad de software.

En este sentido, el proyecto no solo refuerza las competencias técnicas de construcción de aplicaciones web,
sino que también fomenta la capacidad de planificar, liderar y colaborar en equipo bajo una perspectiva académica
y profesional.

## Bibliografía

Pressman, R. S., & Maxim, B. R. (2020). Software Engineering: A Practitioner’s Approach (9th ed.). McGraw-Hill Education.

Vue.js. (2023). The Progressive JavaScript Framework. Retrieved from https://vuejs.org

## Anexos

**Repositorio en GitHub - BookMe (Prisma) - Documento:**<br>

https://github.com/Los-Bytes/Report

**Repositorio en GitHub - BookMe (Prisma) - Landing Page**<br>

https://github.com/MarceloMazuelos/LabIoT-Landing-Page/

**Url Deployment Github Pages - BookMe (Prisma) - Landing Page**<br>

https://marcelomazuelos.github.io/LabIoT-Landing-Page/

**Url Video Exposicion TB1:**

**Cuentas de GitHub de los Integrantes:**<br>

Marcelo Mazuelos - @MarceloMazuelos
