<p align="center">
  <img src="img/upc.png" alt="Logo de UPC" width="100%">
</p>

<div align="center">
  <h1>Universidad Peruana de Ciencias Aplicadas</h1>
  <p><strong>Carrera:</strong> Ingeniería de Software</p>
  <p><strong>Ciclo:</strong> 2024 - 2</p>
  <p><strong>Curso:</strong> Aplicaciones para Dispositivos Móviles</p>
  <p><strong>Sección:</strong> SW63</p>
  <p><strong>Profesor:</strong> Jorge Luis Mayta Guillermo</p>
  <p><strong>"Informe de Trabajo Final"</strong></p>
  <p><strong>Startup:</strong> AgroTech</p>
  <p><strong>Producto:</strong> AgroSupport</p>
</div>

<table align="center">
  <tr>
    <th>Integrantes</th>
    <th>Código</th>
  </tr>
  <tr>
    <td>Paredes Puente, Sebastián Roberto</td>
    <td>U202217239</td>
  </tr>
  <tr>
    <td>Delgado Corrales, Piero Gonzalo</td>
    <td>U202210749</td>
  </tr>
  <tr>
    <td>Matos Fernandez, Christian Andre</td>
    <td>U202214162</td>
  </tr>
  <tr>
    <td>Salinas Torres, Salvador Antonio</td>
    <td>U20221B127</td>
  </tr>
</table>

<p align="center"><b>Agosto 2024</b></p>

# Registro de versiones

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
      <td><strong>TB1</strong></td>
      <td>29 de agosto</td>
      <td>
        <ul>
          <li>Paredes Puente, Sebastian Roberto</li>
          <li>Delgado Corrales, Piero Gonzalo</li>
          <li>Matos Fernandez, Christian Andre</li>
          <li>Salinas Torres, Salvador Antonio</li>
        </ul>
      </td>
      <td>
        Se ha incluido el avance de los siguientes capítulos:
        <ul>
          <li>Objetivos SMART</li>
          <li>Capítulo 1: Presentación</li>
          <li>Capítulo 2: Needfinding</li>
        </ul>
      </td>
  </tr>
  <tr>
      <td><strong>TB2</strong></td>
      <td>15 de setiembre</td>
      <td>
        <ul>
          <li>Paredes Puente, Sebastian Roberto</li>
          <li>Delgado Corrales, Piero Gonzalo</li>
          <li>Matos Fernandez, Christian Andre</li>
          <li>Salinas Torres, Salvador Antonio</li>
        </ul>
      </td>
      <td>
        Se ha incluido el avance de los siguientes capítulos:
        <ul>
          <li>Capítulo 3: Arquitectura</li>
          <li>Capítulo 4: Backend Product Implementation & Validation</li>
        </ul>
        Se ha mejorado:
        <ul>
          <li>Objetivos SMART</li>
          <li>Definición de technical user stories</li>
        </ul>
      </td>
  </tr>
  <tr>
      <td><strong>TP</strong></td>
      <td>26 de setiembre</td>
      <td>
        <ul>
          <li>Paredes Puente, Sebastian Roberto</li>
          <li>Delgado Corrales, Piero Gonzalo</li>
          <li>Matos Fernandez, Christian Andre</li>
          <li>Salinas Torres, Salvador Antonio</li>
        </ul>
      </td>
      <td>
        Se ha incluido el avance de los siguientes capítulos:
        <ul>
          <li>Capítulo V: Product Implementation & Validation</li>
        </ul>
      </td>
  </tr>
  </tbody>
</table>

# Tabla de Contenido

[Registro de Versiones](#registro-de-versiones)

[Student Outcome](#student-outcome)

[Objetivos SMART](#objetivos-smart)

[Capítulo 1: Presentación](#Capítulo-I-Presentación)
  - [1.1. Startup Profile](#11-startup-profile)
    - [1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)
    - [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
  - [1.2. Solution Profile](#12-solution-profile)
    - [1.2.1. Antecedentes y problemática](#121-antecedentes-y-problemática)
    - [1.2.2. Lean UX Process](#122-lean-ux-process)
      - [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)
      - [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)
      - [1.2.2.3. Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
      - [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)
  - [1.3. Segmentos objetivo](#13-segmentos-objetivo)

[Capítulo 2: Needfinding](#Capítulo-2-Needfinding)
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
  - [2.4 Requirements Specification](#24-requirements-specification)
    - [2.4.1. To-Be Scenario Mapping](#241-to-be-scenario-mapping)
    - [2.4.2. User Stories](#242-user-stories)
    - [2.4.3. Impact Mapping](#243-impact-mapping)
    - [2.4.4. Product Backlog](#244-product-backlog)

[Capítulo 3: Arquitectura](#Capítulo-3-Arquitectura)
  - [3.1. Product design](#31-product-design)
    - [3.1.1. Style Guidelines](#311-style-guidelines)
      - [3.1.1.1. General Style Guidelines](#3111-general-style-guidelines)
    - [3.1.2. Information Architecture](#312-information-architecture)
      - [3.1.2.1. Organization Systems](#3121-organization-systems)
      - [3.1.2.2. Labelling Systems](#3122-labelling-systems)
      - [3.1.2.3. SEO Tags and Meta Tags](#3123-seo-tags-and-meta-tags)
      - [3.1.2.4. Searching Systems](#3124-searching-systems)
      - [3.1.2.5. Navigation Systems](#3125-navigation-systems)
    - [3.1.3. Landing Page UI Design](#313-landing-page-ui-design)
      - [3.1.3.1. Landing Page Wireframe](#3131-landing-page-wireframe)
      - [3.1.3.2. Landing Page Mock-up](#3132-landing-page-mock-up)
    - [3.1.4. Mobile Applications UX/UI Design](#314-mobile-applications-uxui-design)
      - [3.1.4.1. Mobile Applications Wireframes](#3141-mobile-applications-wireframes)
      - [3.1.4.2. Mobile Applications Wireflow Diagrams](#3142-mobile-applications-wireflow-diagrams)
      - [3.1.4.3. Mobile Applications Mock-ups](#3143-mobile-applications-mock-ups)
      - [3.1.4.4. Mobile Applications User Flow Diagrams](#3144-mobile-applications-user-flow-diagrams)
      - [3.1.4.5. Mobile Applications Prototyping](#3145-mobile-applications-prototyping)
  - [3.2. Architecture Overview](#32-architecture-overview)
    - [3.2.1. Domain-Driven Software Architecture](#321-domain-driven-software-architecture)
      - [3.2.1.1. Software Architecture Context Level Diagram](#3211-software-architecture-context-level-diagram)
      - [3.2.1.2. Software Architecture Container Level Diagram](#3212-software-architecture-container-level-diagram)
      - [3.2.1.3. Software Architecture Components Diagram](#3213-software-architecture-components-diagram)
    - [3.2.2. Software Object-Oriented Design](#322-software-object-oriented-design)
      - [3.2.2.1. Class Diagrams](#3221-class-diagrams)
      - [3.2.2.2. Class Dictionary](#3222-class-dictionary)
      - [3.2.2.3. Database Design](#3223-database-design)
      - [3.2.2.4. Database Diagram](#3224-database-diagram)

[Capítulo 4: Backend Product Implementation & Validation](#Capítulo-4-Backend-Product-Implementation--Validation)
  - [4.1. Software Configuration Management](#41-software-configuration-management)
    - [4.1.1. Software Development Environment Configuration](#411-software-development-environment-configuration)
    - [4.1.2. Source Code Management](#412-source-code-management)
    - [4.1.3. Source Code Style Guide & Conventions](#413-source-code-style-guide--conventions)
    - [4.1.4. Software Deployment Configuration](#414-software-deployment-configuration)
  - [4.2. Software Development & Implementation](#42-software-development--implementation)
    - [4.2.1. Sprint 1](#421-sprint-1)
      - [4.2.1.1. Sprint Planning 1](#4211-sprint-planning-1)
      - [4.2.1.2. Sprint Backlog 1](#4212-sprint-backlog-1)
      - [4.2.1.3. Development Evidence for Sprint Review](#4213-development-evidence-for-sprint-review)
      - [4.2.1.4. Testing Suite Evidence for Sprint Review](#4214-testing-suite-evidence-for-sprint-review)
      - [4.2.1.5. Execution Evidence for Sprint Review](#4215-execution-evidence-for-sprint-review)
      - [4.2.1.6. Services Documentation Evidence for Sprint Review](#4216-services-documentation-evidence-for-sprint-review)
      - [4.2.1.7. Software Deployment Evidence for Sprint Review](#4217-software-deployment-evidence-for-sprint-review)
      - [4.2.1.8. Team Collaboration Insights during Sprint](#4218-team-collaboration-insights-during-sprint)

[Capítulo 5: Product Implementation & Validation](#Capítulo-5-Product-Implementation--Validation)
  - [5.1. Software Configuration Management](#51-software-configuration-management)
    - [5.1.1. Software Development Environment Configuration](#511-software-development-environment-configuration)
    - [5.1.2. Source Code Management](#512-source-code-management)
    - [5.1.3. Source Code Style Guide & Conventions](#513-source-code-style-guide--conventions)
    - [5.1.4. Software Deployment Configuration](#514-software-deployment-configuration)
  - [5.2. Software Development & Implementation](#52-software-development--implementation)
    - [5.2.1. Sprint 1](#521-sprint-1)
      - [5.2.1.1. Sprint Planning 1](#5211-sprint-planning-1)
      - [5.2.1.2. Sprint Backlog 1](#5212-sprint-backlog-1)
      - [5.2.1.3. Development Evidence for Sprint Review](#5213-development-evidence-for-sprint-review)
      - [5.2.1.4. Testing Suite Evidence for Sprint Review](#5214-testing-suite-evidence-for-sprint-review)
      - [5.2.1.5. Execution Evidence for Sprint Review](#5215-execution-evidence-for-sprint-review)
      - [5.2.1.6. Services Documentation Evidence for Sprint Review](#5216-services-documentation-evidence-for-sprint-review)
      - [5.2.1.7. Software Deployment Evidence for Sprint Review](#5217-software-deployment-evidence-for-sprint-review)
      - [5.2.1.8. Team Collaboration Insights during Sprint](#5218-team-collaboration-insights-during-sprint)


[Conclusiones](#conclusiones)

[Recomendaciones](#recomendaciones)

[Video App Validation](#video-app-validation)

[Video About the Product](#video-about-the-product)

[Video About the Team](#video-about-the-team)

[Glosario](#glosario)

[Bibliografía](#bibliografía)


# Student Outcome

**ABET – EAC - Student Outcome 7**

**Criterio:** La capacidad de adquirir y aplicar nuevos conocimientos según sea necesario, utilizando estrategias deaprendizaje apropiadas.

<table>
  <thead>
    <tr>
      <th><strong>Criterio específico</strong></th>
      <th><strong>Acciones realizadas</strong></th>
      <th><strong>Conclusiones</strong></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Actualiza conceptos y conocimientos necesarios para su desarrollo profesional y en especial para su proyecto en soluciones de software.</td>
      <td>
        <p><strong>Paredes Puente, Sebastian Roberto</strong></p>
        <p><strong>TB1:</strong> En este primer avance, se identificó la problemática y se realizó la investigación necesaria para definir los requisitos que nuestra aplicación final debe cubrir. Para ello, llevé a cabo entrevistas con personas de nuestros segmentos objetivo para comprender mejor sus principales necesidades y adoptar su perspectiva, asegurándome de que las user stories que planteamos fueran las más adecuadas.</p>
        <p><strong>TB2:</strong> Para este segundo avance, se realizo la implementación del backend para la aplicación móvil, el cual ha requerido de los conocimientos adquiridos en cursos previos, demostrando la importancia de adaptar estos conceptos a las necesidades específicas del proyecto. Este proceso ha permitido reforzar habilidades técnicas y enfrentar los desafíos particulares del desarrollo, contribuyendo al progreso del proyecto y estableciendo una base sólida para las siguientes etapas.</p>
        <p></p>
        <p><strong>Delgado Corrales, Piero Gonzalo</strong></p>
        <p><strong>TB1:</strong> Para esta entrega, se adquirieron nuevos conocimientos en la realización de entrevistas y su análisis ya que se pudo entender mejor las necesidades de los granjeros y asesores. Esto es fundamental para la creación de los User Personas, User Task Matrix, y realizar el User Journey Mapping y nos permitirá .realizar una mejor solución de software.</p>
        <p><strong>TB2:</strong> Para esta entrega, se ha avanzado la implementación del backend para la aplicación móvil. Para ello, se tuvo que recordar los temas aprendidas en cursos previos y adaptarlo al contexto de la aplicación. </p>
        <p></p>
        <p><strong>Matos Fernandez, Christian Andre</strong></p>
        <p><strong>TB1:</strong> Para esta entrega, investigamos a los competidores y desarrollamos estrategias para enfrentarlos. Además, realizamos entrevistas, de las cuales obtuvimos la información necesaria para crear las User Stories que serán útiles en el desarrollo de la aplicación.</p>
        <p><strong>TB2:</strong> En esta entrega, completé con éxito la implementación del backend, cumpliendo con las tareas que me asignaron, de lo cual tuve que repasar y aplicar los conocimientos adquiridos en cursos anteriores.</p>
        <p></p>
        <p><strong>Salinas Torres, Salvador Antonio</strong></p>
        <p><strong>TB1:</strong> En este entregable, definimos el problema inicial sobre el cual partirá nuestra aplicación móvil a realizar. Igualmente, tuvimos que actualizar conocimientos para determinar bien la problemática a través de una investigación sobre el tema y también sobre lo necesario para poder desarrollar la aplicación móvil.</p>
        <p></p>
        <p><strong>TB2:</strong> En este segundo entregable, se definió los estilos, tipografía y paleta de colores a utilizar para el producto. De esta forma, realizamos los prototipos utilizando la herramienta de Figma, la cual ya hemos utilizado anteriormente, pero ha recibido actualizaciones nuevas como la implementación de una nueva AI, por lo que actualizamos nuestros conocimientos para poder sacar provecho a estas nuevas funcionalidades que nos ofrece la aplicación.</p>
      </td>
      <td>
        <p><strong>TB1: </strong></p>
        <p>En este primer avance del proyecto, cada integrante del equipo ha actualizado y ampliado sus conocimientos esenciales para el desarrollo de soluciones de software, enfocándose en aspectos fundamentales como la investigación de necesidades, la realización y análisis de entrevistas, el estudio de la competencia, y la definición clara de problemáticas. Estos esfuerzos han permitido a todos mejorar su comprensión del mercado objetivo, garantizar que las User Stories y demás herramientas de diseño sean precisas y relevantes, y sentar las bases para el desarrollo de una aplicación móvil que responda adecuadamente a las necesidades identificadas.</p>
        <p><strong>TB2: </strong></p>
        <p>En este segundo avance, el equipo ha consolidado los conocimientos adquiridos previamente y los ha aplicado de manera efectiva en el desarrollo del projecto. En particular, se ha logrado implementar el backend de la aplicación móvil, un componente esencial que requirió la adaptación de habilidades técnicas adquiridas en cursos anteriores. Además, se realizaron mejoras en el diseño visual, aprovechando las nuevas funcionalidades de herramientas como Figma, lo que ha permitido optimizar los prototipos de la aplicación. Estos logros refuerzan la capacidad del equipo para enfrentar los desafíos del proyecto, estableciendo una base sólida para los siguientes avances y garantizando que la aplicación final esté alineada con las necesidades identificadas en fases previas.</p>
      </td>
    </tr>
    <tr>
      <td>Reconoce la necesidad del aprendizaje permanente para el desempeño profesional y el desarrollo de proyectos en soluciones de software.</td>
      <td>
        <p><strong>Paredes Puente, Sebastian Roberto</strong></p>
        <p><strong>TB1:</strong> A través de las opiniones recogidas en las entrevistas, entendimos la importancia de un aprendizaje continuo. Esto nos permitió diseñar las funcionalidades del producto definidas en las User Stories, de manera que vayan acorde a las necesidades de nuestros usuarios.</p>
        <p><strong>TB2:</strong> Gracias a la documentación de Spring Boot, se logro adquirir los conocimientos necesarios para desplegar el backend en un contenedor de Docker de manera efectiva. Esto ha permitido optimizar el proceso de despliegue, asegurando que futuras actualizaciones del backend se realicen de forma ágil y eficiente, lo que mejora la adaptabilidad del proyecto a medida que se incorporan nuevos aprendizajes.</p>
        <p></p>
        <p><strong>Delgado Corrales, Piero Gonzalo</strong></p>
        <p><strong>TB1:</strong> Mediante las opiniones obtenidas de las entrevistas pudimos comprender la necesidad de un aprendizaje continuo porque gracias a estas pudimos diseñar las funcionalidades del producto delimitadas en las User Stories para que se alineen con las necesidades cambiantes de nuestros segmentos objetivos y tomando en cuenta las nuevas tecnologías.</p>
        <p><strong>TB2:</strong> A través de la documentación de Spring Boot pude aprender sobre el deployment del backend en un contenedor de Docker. Gracias a esto, se pudo desplegar el backend de forma eficaz y está solución nos permitirá seguir actualizando el backend de forma rapida con los nuevos conocimientos adquiridos.</p>
        <p></p>
        <p><strong>Matos Fernandez, Christian Andre</strong></p>
        <p><strong>TB1:</strong> A partir de las entrevistas y del análisis de los datos obtenidos, logramos identificar la importancia de integrar un enfoque de aprendizaje continuo. Esto nos permitió definir las User Stories del producto de manera que se adapten a las demandas reales y cambiantes de nuestros usuarios.</p>
        <p><strong>TB2:</strong> Durante el repaso para la implementación del backend, también reforcé los conceptos de configuración de controladores y rutas en Spring Boot, lo cual facilita el manejo de solicitudes HTTP de manera eficiente. </p>
        <p></p>
        <p><strong>Salinas Torres, Salvador Antonio</strong></p>
        <p><strong>TB1:</strong> Se realizó una investigación sobre el tema para verificar de forma clara la necesidad a resolver, así como con fuentes secundarias recuperadas de artículos y fuentes primarias como las entrevistas realizadas.</p>
        <p></p>
        <p><strong>TB2:</strong> A pesar de que para este entregable aún no se empieza con la implementación del Frontend para la aplicación móvil, igualmente se ha iniciado con el Backend y el primer despliegue de este. De esta forma, hemos logrado aprender una nueva forma para realizar el despliegue del Backend con Docker, que resultó ser mucho mejor al método que utilizábamos anteriormente.</p>
      </td>
      <td>
        <p><strong>TB1: </strong></p>
        <p>En este primer avance del proyecto, cada integrante del equipo ha reconocido la importancia del aprendizaje continuo en el desarrollo profesional y en la creación de soluciones de software. A través de la investigación, entrevistas y análisis de datos, todos comprendieron que mantenerse actualizados y abiertos a nuevos conocimientos es crucial para diseñar funcionalidades que se alineen con las necesidades cambiantes de los usuarios y con las nuevas tecnologías. Esta actitud proactiva hacia el aprendizaje permitirá al equipo desarrollar un producto que no solo resuelve las problemáticas actuales, sino que también se adapta a futuros desafíos.</p>
        <p><strong>TB2: </strong></p>
        <p>En este segundo avance, el equipo ha reafirmado la importancia del aprendizaje continuo para el éxito en el desarrollo de software. Cada miembro del equipo ha adquirido y aplicado nuevos conocimientos, como el despliegue del backend utilizando Docker y la configuración eficiente de controladores y rutas en Spring Boot. Este proceso ha permitido optimizar el flujo de trabajo y asegurar que futuras actualizaciones sean ágiles y adaptables. La disposición del equipo a aprender y a aplicar nuevas tecnologías no solo fortalece la solución actual, sino que también garantiza su capacidad para evolucionar con el tiempo, enfrentando futuros desafíos con una base técnica sólida y moderna.</p>
      </td>
    </tr>
  </tbody>
</table>

# Objetivos SMART

Los objetivos SMART son una herramienta que permite establecer metas claras y alcanzables. SMART es un acrónimo que significa: Specific (Específico), Measurable (Medible), Achievable (Alcanzable), Relevant (Relevante) y Time-bound (Limitado en el tiempo).

De esta forma, nosotros hemos definido los siguientes objetivos para nuestro producto AgroSupport:

<table>
  <thead>
    <tr>
      <th>Nombre del estudiante</th>
      <th>Descripción del objetivo</th>
      <th>Fecha de inicio</th>
      <th>Fecha de cumplimiento esperada</th>
      <th>¿Qué se va a lograr?</th>
      <th>¿Tiene KPI o métrica clara?</th>
      <th>¿Es retador y va más allá de sus funciones?</th>
      <th>¿Está alineado a la estrategia?</th>
      <th>¿Cuándo se cumplirá?</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Piero Delgado</td>
      <td>Investigar principios de diseño de interfaces móviles intuitivas para iOS y Android para aplicarlos en la primera versión de nuestra aplicación con el fin de mejorar mis competencias en UX/UI.</td>
      <td>19/08/2024</td>
      <td>19/10/2024</td>
      <td>Desarrollar una interfaz móvil intuitiva basada en las mejores prácticas de UX/UI para fortalecer mis habilidades profesionales en diseño de aplicaciones móviles.</td>
      <td>La métrica será la valoración positiva de la interfaz por parte de los usuarios durante las entrevistas de validación. Se considerará éxito si al menos el 80% de los entrevistados expresan opiniones favorables.</td>
      <td>Requiere una comprensión más profunda del diseño de interfaces móviles, así como la capacidad de aplicar estos conocimientos en la aplicación. Esto supone un reto importante en el desarrollo móvil y va más allá de solo implementación las funcionalidades de la aplicación.</td>
      <td>Está alineado con la estrategia de desarrollar una aplicación que sea no solo funcional, sino también sencilla para que los granjeros puedan utilizarla de forma recurrente.</td>
      <td>Se cumplirá durante el desarrollo de los prototipos de la aplicación móvil y su primera versión.</td>
    </tr>
    <tr>
      <td>Piero Delgado</td>
      <td>Desarrollar un sistema de notificaciones en tiempo real en Kotlin para mejorar mis habilidades en desarrollo móvil.</td>
      <td>19/10/2024</td>
      <td>19/11/2024</td>
      <td>Implementar un sistema de notificaciones en tiempo real que informe a los granjeros sobre eventos importantes, mejorando la comunicación dentro de la aplicación, y aplicando conocimientos en desarrollo móvil y backend.</td>
      <td>La métrica a considerar será la visualización de las notificaciones en los dispositivos de prueba. Se considerará exitoso si al menos un 95% de las notificaciones enviadas durante las pruebas son recibidas correctamente.</td>
      <td>La integración de este sistema implica un desafío ya que se requiere conocimientos en distintas funcionalidades de Kotlin como el envío de notificaciones, creación de eventos dentro de la aplicación y conexión con el backend para saber la fecha de las distintas asesorías.</td>
      <td>Está alineado con el alcance del trabajo ya que esta funcionalidad permite mantener a los granjeros informados sobre el estado de sus asesorías. Además, podre aumentar mi dominio de tecnologías móviles.</td>
      <td>El objetivo se cumplirá al terminar la implementación de la segunda versión de la aplicación con Kotlin.</td>
    </tr>
    <tr>
      <td>Salvador Salinas</td>
      <td>Dominar un lenguaje de programación de desarrollo móvil como Kotlin para crear aplicaciones de manera eficiente.</td>
      <td>22/08/2024</td>
      <td>20/11/2024</td>
      <td>Se logrará desarrollar la capacidad para crear aplicaciones móviles utilizando Kotlin, de este modo podré iniciar a programar aplicaciones móviles para Android.</td>
      <td>La métrica a tomar en cuenta es crear y desplegar una aplicación funcional en un repositorio de GitHub y compartirla con la comunidad, así como implementar todas las funcionalidades descritas en las historias de usuario definidas.</td>
      <td>La implementación de una aplicación con Kotlin es retador, ya que implica aprender un nuevo lenguaje de programación y desarrollar una aplicación nueva desde cero. Además, se espera que se aplique buenas prácticas en el código.</td>
      <td>Está alineado con el alcance del trabajo, ya que es esencial entregar una aplicación móvil que funcione como se espera para los usuarios.</td>
      <td>El objetivo será cumplido al terminar la implementación y despliegue de la aplicación móvil.</td>
    </tr>
    <tr>
      <td>Salvador Salinas</td>
      <td>Desarrollar una red profesional dentro del ecosistema de desarrollo de aplicaciones móviles.</td>
      <td>13/09/2024</td>
      <td>20/11/2024</td>
      <td>Construir una red sólida de contactos profesionales en la industria de desarrollo de aplicaciones móviles para intercambiar ideas, obtener mentorías, y explorar nuevas oportunidades laborales.</td>
      <td>Para medir si este objetivo llegó a cumplirse, se espera conectar con al menos 10 contactos a través de LinkedIn u otros medios, para establecer conexiones importantes en el ámbito laboral profesional.</td>
      <td>Es retador ya que implica dedicar tiempo adicional fuera de las actividades diarias y requiere proactividad para interactuar y construir relaciones, lo que va más allá del enfoque técnico.</td>
      <td>El networking es clave para el crecimiento profesional, permitiendo acceder a mentorías, nuevas oportunidades y mantenerse actualizado en las tendencias del desarrollo móvil.</td>
      <td>En aproximadamente 2 meses, se espera haber conectado con otras personas y ser un miembro activo de comunidades en línea.</td>
    </tr>
    <tr>
      <td>Sebastian Paredes</td>
      <td>Desarrollar y desplegar una API RESTful segura y escalable para mejorar mis competencias en desarrollo backend y gestión de infraestructura en la nube.</td>
      <td>30/08/2024</td>
      <td>20/09/2024</td>
      <td>Implementar una API RESTful que maneje de manera eficiente las operaciones CRUD, soportando múltiples solicitudes simultáneas sin comprometer el rendimiento, para fortalecer mis habilidades en backend y escalabilidad.</td>
      <td>La métrica clave será la capacidad de la API para manejar al menos 100 solicitudes concurrentes sin degradación en el rendimiento, evaluada a través de pruebas de carga. Será exitoso si el tiempo de respuesta se mantiene bajo 200 ms.</td>
      <td>Este objetivo supone un reto ya que requiere el diseño de una arquitectura robusta y la implementación de prácticas avanzadas de seguridad y optimización para el manejo de cargas simultáneas.</td>
      <td>Está alineado con la estrategia de AgroSupport de garantizar una plataforma confiable y escalable, y también permitirá mejorar mi dominio en tecnologías backend y arquitecturas de software.</td>
      <td>Se cumplirá tras el despliegue exitoso de la API en producción, después de haber superado pruebas de carga y seguridad.</td>
    </tr>
    <tr>
      <td>Sebastian Paredes</td>
      <td>Diseñar y desarrollar la vista móvil para el segmento de granjeros en la aplicación AgroSupport, con el fin de mejorar mis competencias en diseño de interfaces móviles.</td>
      <td>20/08/2024</td>
      <td>30/09/2024</td>
      <td>Crear una interfaz intuitiva y funcional para los granjeros, basada en buenas prácticas de UX/UI, para fortalecer mis habilidades en diseño de aplicaciones móviles.</td>
      <td>La métrica será la satisfacción de los usuarios evaluada a través de encuestas. Se considerará éxito si al menos el 85% de los granjeros indican que la interfaz es fácil de usar y adecuada a sus necesidades.</td>
      <td>Este objetivo es desafiante porque implica un entendimiento profundo de las necesidades de los granjeros y cómo traducirlas en un diseño de interfaz efectivo.</td>
      <td>Está alineado con la estrategia de AgroSupport de proporcionar una experiencia de usuario amigable y funcional, permitiendo también que yo mejore en el diseño de interfaces orientadas a usuarios.</td>
      <td>El objetivo se cumplirá cuando la vista móvil esté desarrollada y se obtenga retroalimentación positiva en pruebas de usabilidad.</td>
    </tr>
    <tr>
      <td>Christian Matos</td>
      <td>Mejorar mis competencias en desarrollo de aplicaciones mediante la implementación de una funcionalidad avanzada de búsqueda en AgroSupport.</td>
      <td>01/09/2024</td>
      <td>10/10/2024</td>
      <td>Implementar una funcionalidad avanzada de búsqueda en AgroSupport, mejorando el acceso a asesoramiento especializado para los granjeros.</td>
      <td>La métrica clave será que al menos el 85% de los usuarios puedan encontrar un asesor adecuado en menos de 5 minutos de búsqueda.</td>
      <td>Es retador porque requiere la implementación de un sistema avanzado de filtrado y recomendación, basado en las necesidades de los granjeros y las áreas de especialización de los asesores.</td>
      <td>Está alineado con la estrategia de AgroTech de mejorar el acceso a asesoría especializada y aumentar la eficiencia en la gestión de granjas.</td>
      <td>Se cumplirá al desplegar la funcionalidad de búsqueda y validarla mediante pruebas de satisfacción del usuario y efectividad en la conexión con asesores.</td>
    </tr>
    <tr>
      <td>Christian Matos</td>
      <td>Fortalecer mis habilidades en optimización de rendimiento de aplicaciones, asegurando tiempos de respuesta inferiores a 2 segundos en el 95% de las solicitudes de usuario en AgroSupport..</td>
      <td>15/09/2024</td>
      <td>10/10/2024</td>
      <td>Optimizar el rendimiento de AgroSupport para que el 95% de las solicitudes tengan tiempos de respuesta de menos de 2 segundos.</td>
      <td>La métrica clave será la reducción de los tiempos de respuesta a menos de 2 segundos en el 95% de las solicitudes, verificada a través de pruebas de carga.</td>
      <td>Es retador porque requiere la implementación de diversas técnicas de optimización, tanto en el código como en la infraestructura, bajo condiciones de carga.</td>
      <td>Está alineado con la estrategia de AgroTech de ofrecer una aplicación eficiente y rápida para los usuarios.</td>
      <td>Se cumplirá al realizar pruebas de carga que verifiquen el tiempo de respuesta de las solicitudes y al implementar las optimizaciones necesarias.</td>
    </tr>
  </tbody>
</table>


# Capítulo 1: Presentación

## 1.1. Startup Profile

### 1.1.1. Descripción de la Startup

Nuestra startup se llama AgroTech, y se especializa en abordar los desafíos de la gestión de granjas a través de nuestra aplicación integral AgroSupport. Nuestro enfoque principal es proporcionar asesoramiento especializado y herramientas tecnológicas para mejorar la gestión de granjas de manera inteligente y eficiente.

**Misión:**
Brindar a los granjeros acceso fácil y directo a asesoría especializada, promoviendo prácticas agrícolas sostenibles y modernas para mejorar la productividad, la rentabilidad y el bienestar de las comunidades agropecuarias.

**Visión:**
Liderar la innovación tecnológica para el sector agropecuario, promoviendo el bienestar animal y la sostenibilidad a través de tecnología accesible.

**Logo de AgroSupport**
<p align="center">
  <img src="img/agrosupport-logo.png" width="200">
</p>

_Imagen 1. Logo de AgroSupport_


### 1.1.2. Perfiles de integrantes del equipo

<table>
  <tr>
    <th>
      <img src="img/perfil_sebastian.png" alt="Foto de perfil de Sebastian" width="800px">
    </th>
    <td valign="top">
      <p><b>Paredes Puente, Sebastian Roberto</b></p>
      <p>
        Soy estudiante de sexto ciclo de la carrera de Ingeniería de Software. Dentro de mi experiencia, destaco la capacidad de analizar información y programar en lenguaje C++. Además, he completado cursos en Python, SQL Server y HTML. En cuanto a mis habilidades interpersonales, cuento con adaptabilidad, pensamiento creativo, trabajo en equipo, gestión del tiempo y capacidad analítica para resolver problemas.
      </p>
    </td>
  </tr>
  <tr>
    <th>
      <img src="img/perfil_piero.jpg" alt="Foto de perfil de Piero" width="800px">
    </th>
    <td valign="top">
      <p><b>Delgado Corrales, Piero Gonzalo</b></p>
      <p>
        Actualmente estoy en el sexto ciclo de Ingeniería de Software. Tengo conocimientos en diseño web utilizando HTML, CSS. Además, de utilizar herramientas como Figma para la creación de prototipos. Asimismo, recientemente he aprendido a trabajar con frameworks para frontend (Vue y Angular) y backend (Spring Boot con Java y .NET con C#).  
        Soy una persona responsable y me esfuerzo por mantener una organización óptima para gestionar eficazmente las entregas de trabajos.
      </p>
    </td>
  </tr>
    <tr>
    <th>
      <img src="img/perfil_christian.png" alt="Foto de perfil de Christian" width="800px">
    </th>
    <td valign="top">
      <p><b>Matos Fernandez, Christian Andre</b></p>
      <p>
        Me llamo Christian Matos, y estoy en mi sexto ciclo de Ingeniería de Software. Poseo experiencia en programación en lenguajes como Python, C++, y JavaScript. Disfruto contribuir con mis habilidades y trabajar en equipo para alcanzar nuestros objetivos comunes.
      </p>
    </td>
  </tr>
  <tr>
    <th>
      <img src="img/perfil_salvador.jpg" alt="Foto de perfil de Salvador" width="800px">
    </th>
    <td valign="top">
      <p><b>Salinas Torres, Salvador Antonio</b></p>
      <p>
        Soy estudiante de sexto ciclo de la carrera de Ingeniería de Software. Poseo conocimientos en programación orientada a objetos en C++, Python, C# y Java; desarrollo de Frontend con frameworks de Angular y Vue; gestión de base de datos en SQL Server, MySQL y SQLite. Considero que soy una persona responsable y siempre organizo el tiempo para hacerlos tranquilamente antes de la fecha de entrega.
      </p>
    </td>
  </tr>
</table>


## 1.2. Solution Profile

### 1.2.1 Antecedentes y problemática

**5 W's**

**What:** Una parte del sector agropecuario suele enfrentar desafíos en la gestión eficiente de las granjas, la falta de acceso a tecnologías adecuadas y la necesidad de mejorar el bienestar animal y la sostenibilidad de las prácticas agrícolas.

**Where:** Se tomará en cuenta todo el Perú, especialmente en las regiones donde se concentra la mayor parte del comercio y la actividad económica del país.

**When:** Actualmente, el sector agropecuario se enfrenta a estos desafíos en la gestión de granjas. Con el crecimiento de la población en el país y la demanda de alimentos en aumento, se requiere una mayor eficiencia en la producción agrícola. Además, las preocupaciones ambientales y de bienestar animal están impulsando la necesidad de adoptar prácticas agrícolas más sostenibles y éticas.

**Who:** Como principales usuarios contamos con los granjeros, quienes son los beneficiarios directos de estas soluciones, asegurando que se adapten a sus necesidades y realidades específicas. Por otro lado, contamos con asesores expertos en la gestión de granja, quienes aportan su conocimiento especializado para desarrollar soluciones tecnológicas específicas y efectivas.

**Why:** Para abordar estos desafíos y mejorar la gestión y productividad en las granjas, es importante garantizar el bienestar animal y promover las prácticas sostenibles en la industria agropecuaria. Igualmente, se busca mejorar la rentabilidad de los agricultores y contribuir a la seguridad alimentaria peruana.

**2 H's**

**How:** A través de la aplicación móvil AgroSupport, se proporcionará asesoramiento especializado para ayudar a los granjeros a gestionar de manera inteligente y eficiente las granjas. De esta forma, apoyaremos a aumentar su producción y por consiguiente su rentabilidad.

**How much:** Se espera que la aplicación tenga un impacto significativo en la mejora de la gestión de las granjas, aumentando de la productividad y promoviendo prácticas más sostenibles en la industria agropecuaria.

Según un informe realizado (Ames, 2022), se ha identificado que el sector agropecuario agrupa alrededor de un cuarto de los empleos del país, aproximadamente un 27.5% de la población. No obstante, se identificó que solo aporta un 5.2% al PBI. Esto indica que la productividad de la agricultura peruana es baja en comparación con otros países de la región, lo que se traduce en una menor rentabilidad para los agricultores y una mayor vulnerabilidad frente a los cambios climáticos y los mercados internacionales.

### 1.2.2 Lean UX Process.

#### 1.2.2.1. Lean UX Problem Statements.

**Problem Statement 1**
<table>
    <tr>
        <td><strong>Nuestro producto tiene como objetivo mejorar la gestión de granjas en el Perú.</strong></td>
    </tr>
    <tr>
        <td>Hemos observado que los granjeros en Perú enfrentan dificultades para gestionar eficientemente sus granjas, lo que afecta su productividad y rentabilidad.</td>
    </tr>
    <tr>
        <td>¿Podría nuestra aplicación AgroSupport ayudar a los granjeros a mejorar la gestión de sus granjas y aumentar su productividad?</td>
    </tr>
</table>

**Problem Statement 2**
<table>
    <tr>
        <td><strong>Nuestro producto tiene como objetivo aumentar la rentabilidad de los granjeros en Perú.</strong></td>
    </tr>
    <tr>
        <td>Hemos observado que muchos granjeros en Perú enfrentan desafíos para lograr una rentabilidad adecuada debido a la falta de eficiencia en la gestión de sus granjas.</td>
    </tr>
    <tr>
        <td>¿Podría AgroSupport ayudar a los granjeros en Perú a mejorar su rentabilidad mediante una gestión más eficiente de sus granjas?</td>
    </tr>
</table>

**Problem Statement 3**
<table>
    <tr>
        <td><strong>Nuestro producto tiene como objetivo proporcionar asesoramiento especializado a los granjeros en Perú.</strong></td>
    </tr>
    <tr>
        <td>Hemos observado que muchos granjeros en Perú enfrentan desafíos para obtener asesoramiento adecuado y especializado en la gestión de sus granjas.</td>
    </tr>
    <tr>
        <td>¿Cómo podría AgroSupport ayudar a los granjeros en Perú a acceder a asesorías especializadas para mejorar la gestión de sus granjas?</td>
    </tr>
</table>

#### 1.2.2.2. Lean UX Assumptions.

**1. ¿Quién es el usuario?**

El usuario principal es el agricultor con poca experiencia, quien se beneficiará directamente del apoyo de los asesores experimentados que utilizan la plataforma para guiarlo en la gestión eficiente de su granja. AgroSupport facilita la adopción de prácticas sostenibles y la mejora de la productividad en el sector agropecuario.

**2. ¿Dónde encaja nuestro producto en su trabajo o vida?**

Nuestro producto se integra en la vida del agricultor al ofrecer asesoramiento especializado para mejorar la gestión de sus operaciones agropecuarias. AgroSupport se incorpora a su trabajo diario proporcionando soluciones para una gestión eficiente, la mejora del bienestar de los animales y cultivos, la adopción de prácticas sostenibles y la comercialización de sus productos.

**3. ¿Qué problemas tiene nuestro producto? ¿Resolver?**

El sector agropecuario enfrenta numerosos desafíos, como la falta de conocimientos técnicos y el acceso insuficiente a asesoramiento especializado. Estos obstáculos impactan negativamente a los granjeros, dificultando la implementación de prácticas esenciales como el manejo adecuado de suelos, la optimización del uso de agua y fertilizantes, y el control eficiente de plagas y enfermedades. La consecuencia es una menor productividad, mayores costos operativos, y un riesgo elevado para la sostenibilidad de las granjas. Esto no solo afecta la rentabilidad de los granjeros, sino que también contribuye a una baja en la productividad agrícola a nivel nacional, impactando negativamente el Producto Bruto Interno (PBI) del país y limitando su capacidad para competir en mercados internacionales.

**4. ¿Cuándo y cómo es nuestro producto? ¿Usado?**

La plataforma es una herramienta esencial para mejorar la eficiencia operativa, obtener asesoramiento especializado en tiempo real, y aplicar prácticas sostenibles que optimicen la productividad y rentabilidad de las granjas. AgroSupport se utilizaría por granjeros con poca experiencia en la gestión diaria de sus granjas. El producto estaría diseñado para ser accesible en dispositivos móviles y computadoras, permitiendo a los granjeros y asesores experimentados usarlo a cualquier hora. 

**5. ¿Qué características son importantes?**

Asesoramiento especializado: Ofrecer información y recomendaciones específicas para la gestión de granjas. 

Herramientas de gestión: Facilitar la administración de inventarios, registros de salud y reproducción, y planificación de actividades.

Conexión con mercados: Ayudar a los granjeros con poca experiencia a acceder a mercados y promocionar sus productos nutricionales de manera efectiva. 

**6. ¿Cómo debe verse nuestro producto y cómo comportarse?**

Nuestro producto debe tener una interfaz fácil de usar, con un diseño llamativo. Debe comportarse de manera rápida, brindando información y recomendaciones de manera clara y precisa. Debe ser seguro, garantizando la protección de los datos de los usuarios.

Presentación de otros supuestos:

<table border="1">
  <tr>
    <td>Considero que mis clientes necesitan un servicio que ofrezca soluciones integrales para la gestión eficiente de sus actividades agropecuarias, abordando aspectos clave como la salud y nutrición de los cultivos y animales, la reproducción y la comercialización. Generaré ingresos a través de la venta de suscripciones a nuestra plataforma AgroSupport.</td>
    <td>Estas necesidades se pueden resolver con tecnologías avanzadas de monitoreo y análisis de datos, junto con el acceso a un equipo de expertos en el sector agropecuario que proporcionen orientación y recomendaciones personalizadas.</td>
  </tr>
  <tr>
    <td>Mi competencia principal en el mercado será BestFarm.</td>
    <td>Mis clientes iniciales pertenecen al sector agropecuario en Perú que buscan mejorar la eficiencia y la rentabilidad de sus operaciones.</td>
  </tr>
  <tr>
    <td>Superaremos los desafíos del sector agropecuario gracias a nuestra aplicación, que conecta a asesores experimentados con personas inexpertas, proporcionando conocimientos especializados y un enfoque centrado en las necesidades específicas en las diversas áreas agropecuarias.</td>
    <td>El principal valor que un cliente busca en mi servicio es mejorar la rentabilidad de su granja agropecuaria, garantizando al mismo tiempo el bienestar de los animales y/o cultivos, y adoptando prácticas sostenibles.</td>
  </tr>
  <tr>
    <td>El mayor riesgo para mi producto es la resistencia al cambio por parte de algunos agricultores, que podrían mostrarse reacios a adoptar nuevas metodologías de trabajo.</td>
    <td>El cliente también puede optar por no renovar su suscripción a nuestra plataforma si no percibe mejoras significativas en la gestión y rentabilidad de su granja.</td>
  </tr>
  <tr>
    <td>Resolveremos esto a través de una estrategia integral de educación y soporte continuo para nuestros clientes, demostrando el valor tangible de nuestra plataforma a través de casos de éxito y resultados demostrables.</td>
    <td>Voy a adquirir a la mayoría de mis clientes a través de campañas de marketing dirigidas en línea, participación en eventos agrícolas locales y asociaciones con organizaciones del sector agropecuario.</td>
  </tr>
  <tr>
    <td>Nuestro enfoque principal es brindar asesoramiento especializado para optimizar la gestión agropecuaria, utilizando soluciones inteligentes y eficientes que maximicen el rendimiento y la sostenibilidad.</td>
  </tr>
</table>



#### 1.2.2.3. Lean UX Hypothesis Statements

**Hypothesis Statement 1**

| Creemos que al proporcionar a los granjeros con poca experiencia en Perú acceso a tecnologías avanzadas y asesoramiento especializado a través de AgroSupport, se mejorará la eficiencia y la rentabilidad de sus granjas. |
| - |
| Sabremos que esto es cierto… |
| Cuando se observe un incremento del 20% en la cantidad de solicitudes de asesoría durante los primeros 6 meses tras el lanzamiento. |

**Hypothesis Statement 2**

| Creemos que al promover prácticas agrícolas sostenibles y éticas en el sector agropecuario en Perú a través de AgroSupport, los agricultores adoptarán un enfoque más responsable hacia el medio ambiente.|
| - |
| Sabremos que esto es cierto… |
| Cuando proporcionemos orientación y recursos específicos sobre prácticas sostenibles a través de AgroSupport y evaluemos la adopción de estas prácticas, viendo un aumento del 15% en el uso de prácticas sostenibles dentro de los primeros 6 meses de lanzamiento. |

**Hypothesis Statement 3**

| Creemos que al incentivar a los asesores con una nueva estructura de comisiones en AgroSupport, se incrementará el número de asesores activos y su satisfacción. |
| - |
| Sabremos que esto es cierto… |
| Cuando se observe un aumento del 20% en el número de asesores activos en los primeros tres meses posteriores a la implementación de la nueva estructura de comisiones. Además, mediremos la retroalimentación de los asesores mediante encuestas regulares, y consideraremos que hemos tenido éxito si al menos el 70% de las respuestas son positivas en relación con la nueva estructura de comisiones. |

#### 1.2.2.4. Lean UX Canvas.

<img src="img/lean_ux_canva.png" alt="Lean UX Canvas" width="100%" />

_Imagen 2. Lean UX Canvas_

## 1.3. Segmentos objetivo

**1. Granjeros con poca experiencia**

Los granjeros con poca experiencia en Perú enfrentan dificultades significativas para gestionar sus granjas de manera eficiente debido a la falta de conocimientos técnicos y recursos adecuados. Estos desafíos se traducen en una menor productividad y mayores costos operativos, afectando negativamente su rentabilidad y la sostenibilidad de sus prácticas agrícolas. AgroSupport está diseñado específicamente para abordar estas necesidades al proporcionarles herramientas tecnológicas avanzadas y asesoramiento especializado, facilitando la implementación de prácticas eficientes y sostenibles. Con el apoyo de la plataforma, estos granjeros pueden mejorar la gestión de sus granjas, optimizar el uso de recursos, y aumentar su rentabilidad, contribuyendo a una agricultura más productiva y sostenible en el país.

|**Segmento objetivo**|Granjeros con poca experiencia|
| :- | :- |
|**Edad**|18-40 años|
|**Ubicación**|Perú|
|**Sexo**|Masculino y Femenino|
|**Formación educativa**|Educación primaria|
|**Poder adquisitivo**|Bajo y medio|

**2. Asesores experimentados**

Los asesores experimentados desempeñan un papel crucial en el sector agropecuario peruano, ya que su experiencia y conocimiento son esenciales para ayudar a los pequeños y medianos productores a superar desafíos técnicos y operativos. Estos asesores brindan orientación valiosa en la gestión de granjas, la implementación de prácticas sostenibles y la optimización de procesos productivos. AgroSupport les ofrece una plataforma para ampliar su alcance y efectividad, conectándolos con productores que necesitan su experiencia. A través de la plataforma, los asesores pueden gestionar y coordinar sus asesorías de manera más eficiente, adaptándose a las necesidades específicas de cada productor. Esta colaboración mejora no solo la productividad y sostenibilidad de las unidades agropecuarias, sino que también refuerza el papel de los asesores como facilitadores clave en el desarrollo del sector.

|**Segmento objetivo**|Asesores experimentados|
| :- | :- |
|**Edad**|22-60 años|
|**Ubicación**|Perú|
|**Sexo**|Masculino y Femenino|
|**Formación educativa**|Universitario o cualquier educación superior|
|**Poder adquisitivo**|Bajo, medio y alto|

# Capítulo 2: Needfinding

## 2.1. Competidores

### 2.1.1. Análisis competitivo

<table>
   <tr>
      <th colspan="6" valign="top"><b>Competitive Analysis Landscape</b></th>
   </tr>
   <tr>
      <td rowspan="2" valign="top">¿Por qué llevar a cabo este análisis? </td>
     <td colspan="5" valign="top">
      <ul>
        <li>Objetivo 1: Obtener información sobre las ofertas de nuestros competidores y aprender de las áreas en las que tienen limitaciones.</li>
        <li>Objetivo 2: Reconocer las fortalezas y debilidades de nuestros competidores para desarrollar una estrategia competitiva robusta y eficaz.</li>
      </ul>
     </td>

   </tr>
   <tr></tr>
   <tr>
      <td colspan="2" valign="top">(En la cabecera colocar por cada competidor nombre y logo)</td>
      <td valign="top">
         <p>AgroSupport</p>
         <p><img src="img/agrosupport-logo.png" alt="Logo de AgroSupport" width="150" /></p>
      </td>
      <td valign="top">
         <p>BestFarm</p>
         <p><img src="img/logo_bestFarm.jpg" alt="Logo de BestFarm" width="150" /></p>
      </td>
      <td valign="top">
         <p>AgriWebb</p>
         <p><img src="img/logo_agriWebb.jpg" alt="Logo de AgriWebb" width="150" /></p>
      </td>
      <td valign="top">
         <p>Trimble Ag </p>
         <p><img src="img/logo_trimbleAg.png" alt="Logo de Trimble Ag" width="150" /></p>
      </td>
   </tr>
   <tr>
      <td rowspan="2">Perfil</td>
      <td valign="top">Overview</td>
      <td valign="top"><b>AgroSupport</b> es una aplicación integral que proporciona asesoramiento especializado y herramientas tecnológicas para mejorar la gestión de granjas de manera eficiente y sostenible</td>
      <td valign="top"><b>BestFarm</b> es una plataforma digital diseñada para la gestión integral de granjas agrícolas y ganaderas. Ofrece herramientas para la planificación de cultivos, gestión de recursos, y monitoreo del ganado, todo accesible desde dispositivos móviles</td>
      <td valign="top"><b>AgriWebb</b> es una plataforma digital que ofrece una solución integral para la gestión de granjas, con un enfoque especial en la trazabilidad del ganado y la optimización de la productividad agrícola</td>
      <td valign="top"><b>Trimble Ag</b> ofrece soluciones avanzadas para la gestión de fincas, incluyendo herramientas para la planificación de cultivos, gestión del ganado, y monitoreo de recursos. </td>
   </tr>
   <tr>
      <td valign="top">
         <p>Ventaja competitiva</p>
         <p>¿Qué valor ofrece a los clientes?</p>
      </td>
      <td valign="top"><b>AgroSupport</b> ofrece una vía accesible que vincula a granjeros con poca experiencia con especialistas, permitiendo un asesoramiento experto que mejora la gestión de granjas, fomenta prácticas sostenibles y aumenta la productividad</td>
      <td valign="top"><b>BestFarm</b> se destaca por su enfoque en la simplicidad y accesibilidad, permitiendo a los usuarios gestionar tanto cultivos como ganado en una sola plataforma</td>
      <td valign="top">La ventaja de <b>AgriWebb</b> Se distingue por su fuerte enfoque en la trazabilidad y la capacidad de capturar datos en tiempo real</td>
      <td valign="top"><b>Trimble Ag</b> se destaca por su tecnología avanzada y su capacidad para integrar datos de múltiples fuentes, proporcionando una visión completa y precisa de las operaciones de la finca</td>
   </tr>
   <tr>
      <td rowspan="2">Perfil de Marketing</td>
      <td valign="top">Mercado objetivo</td>
      <td valign="top">El mercado objetivo de <b>AgroSupport</b> son los granjeros con poca experiencia y aquellos que buscan mejorar la gestión de sus granjas</td>
      <td valign="top">El mercado objetivo de <b>BestFarm</b> son los agricultores y ganaderos que buscan una solución unificada para la gestión de todas las operaciones de su finca</td>
      <td valign="top">El mercado objetivo de <b>AgriWebb</b> son ganaderos y agricultores que buscan mejorar la eficiencia y la trazabilidad de sus operaciones</td>
      <td valign="top">El mercado objetivo de <b>Trimble Ag</b> son agricultores y ganaderos de tamaño medio a grande que buscan soluciones integradas para la gestión de sus operaciones</td>
   </tr>
   <tr>
      <td valign="top">Estrategias de marketing</td>
      <td valign="top">Las estrategias que utilizan <b>AgroSupport</b> son marketing digital dirigido a granjeros, colaboraciones con asociaciones agrícolas, y demostraciones en eventos agrícolas</td>
      <td valign="top">Las estrategias que utilizan <b>BestFarm</b> son campañas de marketing digital, demostraciones de producto, y colaboraciones con distribuidores de equipos agrícolas</td>
      <td valign="top">Las estrategias que manejan <b>AgriWebb</b> son marketing digital, talleres educativos, y colaboración con organizaciones agrícolas</td>
      <td valign="top"><b>Trimble Ag</b> realizan participaciones en ferias agrícolas, marketing digital, y demostraciones en campo. También se enfoca en asociaciones estratégicas con proveedores de tecnología agrícola</td>
   </tr>
   <tr>
      <td rowspan="3">Perfil de Producto</td>
      <td valign="top">Productos & Servicios</td>
      <td valign="top">Aplicación móvil <b>AgroSupport</b> que ofrece asesoramiento especializado, herramientas de gestión de granjas, y funcionalidades para la mejora del bienestar animal y prácticas sostenibles</td>
      <td valign="top"><b>BestFarm</b> brinda un software de gestión agrícola que incluye planificación de cultivos, gestión de recursos hídricos, y monitoreo de salud animal</td>
      <td valign="top"><b>AgriWebb</b> proporciona un</b> software de gestión de fincas que incluye módulos para la trazabilidad del ganado, monitoreo de la salud animal, y optimización de cultivos</td>
      <td valign="top"><b>Trimble Ag</b> da un software de gestión agrícola y ganadera con módulos para planificación, monitoreo de recursos, y análisis de datos</td>
   </tr>
   <tr>
      <td valign="top">Precios & Costos</td>
      <td valign="top"><b>AgroSupport</b> ofrece un modelo de suscripción que puede ser mensual o anual, con precios que dependen de la magnitud de la operación y las funcionalidades necesarias</td>
      <td valign="top"><b>BestFarm</b> ofrece un modelo de suscripción flexible, con precios escalonados según el tamaño y necesidades de la finca</td>
      <td valign="top"><b>AgriWebb</b> ofrece una estructura de precios basada en suscripciones, con planes que se ajustan según el tamaño y las necesidades de la finca.</td>
      <td valign="top"><b>Trimble Ag</b> da precios basados en suscripción, con diferentes niveles según las características y el tamaño de la finca</td>
   </tr>
   <tr>
      <td valign="top">Canales de distribución (Web y/o Móvil)</td>
      <td valign="top"><b>AgroSupport</b> está disponible en plataformas web y móviles</td>
      <td valign="top"><b>BestFarm</b> se distribuye a través de una plataforma web</td>
      <td valign="top"><b>AgriWebb</b> se distribuye a través de una plataforma web</td>
      <td valign="top"><b>Trimble Ag</b> se distribuye a través de una plataforma web</td>
   </tr>
   <tr>
      <td rowspan="5">Análisis SWOT</td>
      <td colspan="5" valign="top">Realice esto para su startup y sus competidores. Sus fortalezas deberían apoyar sus oportunidades y contribuir a lo que ustedes definen como su posible ventaja competitiva. </td>
   </tr>
   <tr>
      <td valign="top">
         <p>Fortalezas</p>
         <p></p>
      </td>
      <td valign="top">
         <p>- Enfoque integral y accesible para la gestión de granjas</p>
         <p>- Combinación de asesoramiento especializado con herramientas tecnológicas avanzadas</p>
      </td>
      <td valign="top">
         <p>- Plataforma integral que cubre tanto la agricultura como la ganadería</p>
         <p>- Enfoque en la simplicidad y accesibilidad para los usuarios</p>
      </td>
      <td valign="top">
         <p>- Fuerte enfoque en la trazabilidad y gestión basada en datos</p>
         <p>- Interfaz intuitiva y fácil de usar</p>
      </td>
      <td valign="top">
         <p>- Tecnología avanzada y capacidad de integración de datos</p>
         <p>- Amplia gama de funciones para la gestión integral de fincas</p>
      </td>
   </tr>
   <tr>
      <td valign="top">Debilidades</td>
      <td valign="top">
         <p>- Dependencia de la adopción tecnológica en un mercado que puede tener barreras a la digitalización</p>
         <p>- Necesidad de constante actualización y adaptación para mantenerse competitivo</p>
      </td>
      <td valign="top">
         <p>- Puede carecer de funcionalidades avanzadas específicas para cada sector en comparación con competidores más especializados</p>
         <p>- Dependencia de un enfoque generalizado, lo que podría limitar la personalización para necesidades específicas</p>
      </td>
      <td valign="top">
         <p>- Puede ser percibido como costoso para pequeñas fincas</p>
         <p>- La dependencia de la conectividad a internet podría ser un desafío en áreas rurales</p>
      </td>
      <td valign="top">
         <p>- Precio alto, lo que puede ser una barrera para pequeños productores</p>
         <p>- Complejidad en la implementación y el uso inicial</p>
      </td>
   </tr>
   <tr>
      <td valign="top">Oportunidades</td>
      <td valign="top">
         <p>- Expansión en mercados rurales con creciente necesidad de soluciones tecnológicas integradas</p>
         <p>- Desarrollo de nuevas funcionalidades basadas en la retroalimentación de los usuarios</p>
      </td>
      <td valign="top">
         <p>- Crecimiento en mercados rurales</p>
         <p>- Creación de características adicionales adaptadas a cada sector</p>
      </td>
      <td valign="top">
         <p>- Expansión en mercados emergentes que buscan mejorar la trazabilidad y la eficiencia</p>
         <p>- Integración con tecnologías emergentes como IoT para mejorar el monitoreo en tiempo real</p>
      </td>
      <td valign="top">
         <p>- Creciente demanda de soluciones integradas en mercados agrícolas avanzados</p>
         <p>- Innovaciones tecnológicas que pueden mejorar la oferta de productos</p>
      </td>
   </tr>
   <tr>
      <td valign="top">Amenazas</td>
      <td valign="top">
         <p>-Competencia de plataformas más establecidas o especializadas en áreas específicas</p>
         <p>- Resistencia al cambio en el sector agropecuario, que puede afectar la adopción de nuevas tecnologías</p>
      </td>
      <td valign="top">
         <p>- Competencia de plataformas especializadas en agricultura o ganadería que proporcionan funciones más avanzadas.</p>
         <p>- Alteraciones en las preferencias de los usuarios que buscan soluciones más personalizadas para sus necesidades particulares.</p>
      </td>
      <td valign="top">
         <p>- Rivalidad con plataformas especializadas en agricultura o ganadería que disponen de funciones más sofisticadas.</p>
         <p>- Evolución en las demandas de los usuarios que prefieren soluciones adaptadas a sus necesidades concretas.</p>
      </td>
      <td valign="top">
         <p>- Competencia de soluciones más accesibles o especializadas</p>
         <p>- Cambios en la tecnología que pueden requerir actualizaciones frecuentes</p>
      </td>
   </tr>
</table>

### 2.1.2. Estrategias y tácticas frente a competidores

**1. Estrategia: Fortalecimiento del Soporte al Cliente**

   - **Táctica:** Implementaremos programas de capacitación integral para granjeros que cubran todos los aspectos de AgroSupport.
   - **Explicación:** Esto asegurará que los usuarios comprendan completamente todas las características de la plataforma, mejorando la adopción y el uso efectivo de la tecnología.

**2. Estrategia: Mejora Continua de la Plataforma**

   - **Táctica:** Estableceremos un sistema de retroalimentación continua con los usuarios para identificar áreas de mejora y lanzaremos actualizaciones regulares basadas en esta retroalimentación.
   - **Explicación:** Mantendremos la plataforma actualizada y alineada con las necesidades cambiantes de los usuarios, asegurando que AgroSupport siga siendo una herramienta útil y relevante.

**3. Estrategia: Expansión de la Red de Colaboradores**

   - **Táctica:** Formaremos alianzas con universidades y centros de investigación agrícola para desarrollar nuevos conocimientos y tecnologías.
   - **Explicación:** Estas colaboraciones permitirán el acceso a investigaciones avanzadas y tecnologías emergentes, lo que puede enriquecer la oferta de AgroSupport y fomentar la innovación.

**4. Estrategia: Promoción de la Sostenibilidad**

   - **Táctica:** Incorporaremos herramientas y recursos que ayuden a los granjeros a adoptar prácticas agrícolas más sostenibles.
   - **Explicación:** Fomentar prácticas sostenibles no solo beneficiará al medio ambiente, sino que también responderá a la creciente demanda de prácticas agrícolas responsables entre los consumidores y reguladores.

**5. Estrategia: Optimización de la Experiencia del Usuario**

   - **Táctica:** Rediseñaremos la interfaz de AgroSupport para que sea más intuitiva y accesible para usuarios con diversos niveles de experiencia.
   - **Explicación:** Esto facilitará la adopción de la plataforma por granjeros que pueden no estar familiarizados con tecnologías avanzadas, mejorando la eficiencia y satisfacción del usuario.


## 2.2. Entrevistas

### 2.2.1. Diseño de entrevistas

**Preguntas generales**

**Objetivo:** Obtener información general de todos los entrevistados, los cuales serán muy útiles al momento de crear nuestros User Personas.

1. ¿Cuál es su nombre?
2. ¿Qué edad tiene?
3. ¿Dónde reside actualmente?
4. ¿A qué se dedica?
5. ¿Qué navegador usa normalmente?
6. ¿Qué dispositivo móvil tiene?

**Segmento Objetivo: Granjeros con poca experiencia**

**Objetivo:** Entender las necesidades, desafíos y expectativas de granjeros con poca experiencia para adaptar AgroSupport a sus requerimientos específicos.

1. ¿Cuánto tiempo lleva gestionando su granja y qué tipo de formación ha recibido en manejo agrícola (informal o formal)?
2. ¿Cuáles son sus principales objetivos para el desarrollo de su granja?
3. ¿Cuáles son los principales desafíos que enfrenta en la gestión de su granja?
4. ¿Qué obstáculos ha encontrado al intentar implementar prácticas agrícolas más sostenibles y modernas?
5. ¿A través de qué canales digitales suele buscar información o interactuar con expertos agrícolas?
6. ¿Qué tipo de asesoramiento considera más valioso para su granja: técnico, financiero, de gestión, u otro?
7. ¿Con qué frecuencia cree que necesitaría asesoramiento especializado para resolver problemas específicos en su granja?
8. ¿Qué formato de asesoramiento prefiere (por ejemplo, consultas en línea, reuniones presenciales, guías escritas)?
9. ¿Ha tenido experiencias previas con asesores agrícolas? Si no, ¿qué esperaría de una asesoría con un experto?
10. ¿Qué dificultades tiene para obtener el asesoramiento que necesita para su granja?
11. ¿Qué cualidades le gustaría que tuviera una aplicación para separación de asesorías para que sea útil para usted?
12. ¿Cómo preferiría recibir seguimiento después de una sesión de asesoramiento (revisiones periódicas, informes o consultas adicionales)?

**Segmento Objetivo: Asesores experimentados**

**Objetivo:** Comprender las necesidades y expectativas de los asesores para optimizar su uso de AgroSupport y mejorar su eficacia en la asesoría.

1. ¿Cuánto tiempo lleva trabajando como asesor y en qué áreas específicas de la gestión de granjas se especializa?
2. ¿Cuál es su enfoque principal al ofrecer asesoría a los granjeros?
3. Según su experiencia, ¿qué tipo de asesoramiento buscan más los granjeros (técnico, financiero, gestión, etc.)?
4. ¿Cuáles son los mayores desafíos que enfrenta en la prestación de asesoría a los granjeros?
5. ¿Qué problemas ha encontrado al coordinar horarios y medios de comunicación para llevar a cabo las sesiones de asesoría?
6. ¿Qué tan complejo es mantener a los granjeros como clientes recurrentes? ¿Qué factores considera cruciales para la retención de clientes?
7. ¿Qué funcionalidades le gustaría ver en una plataforma de asesoramiento para mejorar su capacidad de asesorar a los granjeros?
8. Después de una sesión de asesoría, ¿cómo suele hacer el seguimiento con el granjero? ¿Qué tan importante es este seguimiento para el éxito de la asesoría?

### 2.2.2. Registro de entrevistas

**Segmento: Granjero con poca experiencia**

**Entrevista 1**

**Entrevistador:** Sebastian Paredes

**Entrevistado:** Marcelo Neyra

**Enlace a entrevista:** https://youtu.be/rHiZI37vcJY

<img alt="Entrevista con Marcelo Neyra" src="img/entrevista-granjero-1.png">

_Imagen 3. Entrevista con Marcelo Neyra_

**Resumen:**
Marcelo Neyra, un joven estudiante que asiste a su padre en la administración de una pequeña granja familiar, expresa que, en sus tareas diarias como regar el huerto o cuidar los animales, requiere apoyo y asesoramiento confiable. Al hablarle sobre la propuesta de una aplicación para recibir consejos de expertos en el ámbito agrícola, consideró que le sería de gran utilidad.

----

**Entrevista 2**

**Entrevistador:** Salvador Salinas

**Entrevistado:** Anderson Gonza

**Enlace a entrevista:** https://youtu.be/f_8SsNOV2Ew

<img alt="Entrevista con Anderson Gonza" src="img/entrevista-granjero-2.png">

_Imagen 4. Entrevista con Anderson Gonza_

**Resumen:** Anderson Gonza es un joven estudiante que suele ayudar a su padre en la gestión de una pequeña granja de cuyes. Comenta que necesita apoyo para conocer sobre ciertas técnicas para el cuidado de los animales y cultivos, así como sobre el clima, el cual influye bastante en la producción. Al comentarle sobre la idea de una app para recibir asesorías con expertos en este sector, mencionó que le sería muy útil a través de reuniones en línea o a través de un chat virtual. Asimismo, comenta que debería ser una aplicación fácil de usar y accesible para todos.

----

**Entrevista 3**

**Entrevistador:** Christian Matos

**Entrevistado:** Jorge Quiñones

**Enlace a entrevista:** https://youtu.be/-kR_byKjvVI

<img alt="Entrevista con Jorge Quiñones" src="img/entrevista-granjero-3.png">

_Imagen 5. Entrevista con Jorge Quiñones_

**Resumen:** Jorge Quiñones lleva menos de dos años gestionando una granja con formación principalmente informal. Sus objetivos incluyen aumentar la producción, mejorar la calidad de los productos, implementar prácticas sostenibles y acceder a mejores mercados. Enfrenta desafíos como la falta de conocimientos técnicos y la gestión de recursos en épocas de sequía, además de obstáculos como la falta de información confiable y los altos costos de nuevas tecnologías. Jorge busca asesoramiento en redes sociales como Facebook y YouTube, utilizando grupos de WhatsApp, y prefiere consultas en línea y guías escritas. Usa el navegador Brave y un dispositivo iOS, y le gustaría una aplicación que le permita agendar citas fácilmente y ofrezca seguimiento periódico.

-----

**Segmento: Asesores experimentados**

**Entrevista 1**

**Entrevistador:** Piero Delgado

**Entrevistado:** Adrián Espinoza

**Enlace a entrevista:** https://youtu.be/ANKhs9e_x5E

<img alt="Entrevista con Adrian Espinoza" src="img/entrevista-asesor-1.png">

_Imagen 6. Entrevista con Adrián Espinoza_

**Resumen:** Adrián ha estado involucrado en la crianza de cuyes desde joven por su familia y recientemente ha empezado a ofrecer asesoramiento a otras familias en alimentación, manejo sanitario y selección de razas de cuyes. Por ello, decidió estudiar Medicina Veterinaria en Arequipa para aprender más de la crianza de animales. Durante la entrevista, destacó los desafíos comunes que enfrentan los criadores principiantes, como el manejo de la alimentación y la prevención de enfermedades. Actualmente, utiliza principalmente su conocimiento personal y recursos en línea para brindar asesoramiento, pero está interesado en explorar nuevas herramientas como aplicaciones.

----

**Entrevista 2**

**Entrevistador:** Salvador Salinas

**Entrevistado:** Tamara García

**Enlace a entrevista:** https://youtu.be/Xoqhu8TpxRc

<img alt="Entrevista con Tamara García" src="img/entrevista-asesor-2.png">

_Imagen 7. Entrevista con Tamara García_

**Resumen:** Tamara García es una potencial asesora con conocimientos en la gestión de una granja de mangos y está dispuesta a aconsejar a granjeros que necesiten apoyo. Su principal recurso es la experiencia que ha ganado gracias a su familia. Menciona que ya ha apoyado a otras personas anteriormente, pero han sido conocidos como familia y amigos. Igualmente, está interesada en poder ayudar a muchas más personas, brindando asesorías cada cierto tiempo cuando haya granjeros que necesiten.

----

**Entrevista 3**

**Entrevistador:** Christian Matos

**Entrevistado:** Heransue Geldres

**Enlace a entrevista:** https://youtu.be/HvL_uEf40Ww

<img alt="Entrevista con Heransue Geldres" src="img/entrevista-asesor-3.png">

_Imagen 8. Entrevista con Heransue Geldres_

**Resumen:** Heransue Geldres es una asesora en gestión de granjas con más de dos años de experiencia, especializada en áreas como gestión financiera, tecnología, bienestar animal y sostenibilidad. Su enfoque es ofrecer soluciones prácticas y personalizadas para cada granja. Los desafíos más grandes que enfrenta son la resistencia al cambio y las limitaciones presupuestarias de los granjeros. Para mejorar su trabajo, le gustaría contar con herramientas de análisis predictivo y sistemas de seguimiento más eficaces. Navega por sus dispositivos usando Android y Chrome, que le permiten estar siempre conectada y preparada para ofrecer el mejor asesoramiento.


### 2.2.3. Análisis de entrevistas

**Segmento: Granjeros con poca experiencia**

El análisis de entrevistas de granjeros con poca experiencia revela patrones comunes que permiten identificar características clave para la construcción de arquetipos representativos. Este segmento se caracteriza por su falta de experiencia en la gestión de granjas, y una fuerte necesidad de apoyo técnico. Las entrevistas proporcionan una visión detallada de sus desafíos y expectativas, especialmente en relación con el uso de herramientas tecnológicas para recibir asesoramiento.

*Segmento Demográfico:*

- **Edad:** Principalmente jóvenes (16 a 30 años).
- **Sexo:** Masculino y Femenino.
- **Ocupación:** Estudiantes que ayudan en la gestión de granjas familiares.

*Segmento Geográfico:*

- **País:** Perú.
- **Idioma:** Español.

*Segmento Psicográfico:*

- **Clase Social:** NSE C y NSE D, debido a que trabajan en granjas familiares pequeñas con recursos limitados.
- **Intereses:** Buscan mejorar sus habilidades en el manejo de granjas, aumentar la producción y aprender sobre nuevas técnicas de cultivo y cuidado animal.

*Segmento Conductual:*

- **Conocimientos:** Conocimiento básico sobre manejo de granjas y uso de tecnología (30% - Marcelo, Anderson).
- **Actitudes:** Buscan asesoramiento práctico y accesible. Prefieren herramientas que sean fáciles de usar y que les permitan agendar y recibir consultas de manera eficiente (100% - Marcelo, Anderson, Jorge). Se enfrentan a desafíos como la falta de experiencia técnica y recursos limitados para implementar nuevas tecnologías.

*Características Objetivas:*
- 100% (3/3): Mencionan la falta de conocimientos técnicos como un obstáculo significativo.
- 66.7% (2/3): Requieren asesoría específica en técnicas de cuidado de animales y cultivos.
- 100% (3/3): Consideran que una aplicación para recibir asesoría de expertos sería útil.
- 66.7% (2/3): Prefieren que la aplicación permita reuniones en línea o chat virtual para consultas rápidas.
- 33.3% (1/3): Utiliza Brave y dispositivos iOS, mientras que los otros 66.7% (2/3) no especificaron su preferencia tecnológica.

*Características Subjetivas:*
- 100% (3/3): Sienten inseguridad en la toma de decisiones debido a la falta de experiencia, lo que les lleva a buscar asesoría externa.
- 66.7% (2/3): Manifiestan una dependencia fuerte en la experiencia familiar, pero reconocen la necesidad de conocimientos adicionales.
- 100% (3/3): Están abiertos a utilizar tecnología como herramientas móviles para recibir asesoría, lo que refleja una actitud positiva hacia la innovación.
- 66.7% (2/3): Insisten en que la aplicación debe ser fácil de usar y accesible para todos, subrayando la importancia de la simplicidad en la adopción de nuevas tecnologías.



**Segmento: Asesores experimentados**

Las entrevistas con asesores experimentados ofrecen una rica fuente de información sobre las prácticas, motivaciones y desafíos de este grupo. A partir de sus respuestas, es posible delinear los rasgos más representativos que influyen en su enfoque de asesoramiento. Este análisis se enfoca en identificar las necesidades tecnológicas y las barreras que enfrentan, así como en cómo su experiencia y especialización informan su deseo de utilizar herramientas avanzadas para mejorar la calidad de la asesoría que brindan.

*Segmento Demográfico:*

- **Edad:** Adultos jóvenes a adultos (25 a 45 años).
- **Sexo:** Masculino y Femenino.
- **Ocupación:** Asesores en gestión agrícola y veterinaria.

*Segmento Geográfico:*

- **País:** Perú.
- **Idioma:** Español.

*Segmento Psicográfico:*

- **Clase Social:** NSE A y NSE B, por su nivel de especialización y experiencia en el sector.
- **Intereses:** Ofrecer asesoramiento profesional, mejorar la productividad agrícola y encontrar herramientas que faciliten la gestión de granjas (100% - Adrián, Tamara, Heransue).

*Segmento Conductual:*

- **Conocimientos:** Experiencia avanzada en gestión de granjas, técnicas de cultivo y cuidado de animales. Utilizan recursos en línea y herramientas digitales para asesorar (100% - Adrián, Tamara, Heransue).
- **Actitudes:** Están interesados en integrar nuevas tecnologías que les permitan ofrecer asesorías más eficaces y personalizadas. Enfrentan desafíos como la resistencia al cambio y las limitaciones presupuestarias de los granjeros (100% - Heransue).

*Características Objetivas:*
- 100% (3/3): Ofrecen asesoramiento basado en su conocimiento personal y experiencia familiar, complementado con recursos en línea.
- 33.3% (1/3): Desean incorporar nuevas herramientas tecnológicas, como análisis predictivos y sistemas de seguimiento.
- 66.7% (2/3): Utilizan dispositivos Android y el navegador Chrome para estar siempre conectados.

*Características Subjetivas:*
- 100% (3/3): Tienen una fuerte motivación para ayudar a otros granjeros, especialmente a aquellos que están comenzando, mostrando una actitud altruista y de compromiso con el desarrollo del sector agrícola.
- 33.3% (1/3): Mencionan que uno de los desafíos más grandes que enfrentan es la resistencia al cambio por parte de los granjeros, lo que puede dificultar la implementación de nuevas prácticas o tecnologías.
- 66.7% (2/3): Enfatizan la importancia de ofrecer soluciones prácticas y personalizadas, adaptadas a las necesidades específicas de cada granja.



## 2.3. Needfinding

### 2.3.1. User Personas

El User Persona es una representación ficticia de un usuario ideal, construida a partir de datos reales y comportamientos observados. Esta descripción detalla sus características demográficas, objetivos, necesidades, desafíos y comportamientos en relación con un producto o servicio. En este caso, nos ha permitido representar de manera efectiva a nuestros dos segmentos objetivo, facilitando una comprensión más profunda de sus perfiles y necesidades.

**Segmento: Granjeros con poca experiencia**

<img alt="Imagen de granjero con poca experiencia" src="img/segmento_objetivo_granjero.png" width="100%">

_Imagen 9. User Persona: Granjero con poca experiencia_

**Segmento: Asesores experimentados**

<img alt="Imagen de asesor experimentado" src="img/segmento_objetivo_asesor.png" width="100%">

_Imagen 10. User Persona: Asesor experimentado_

### 2.3.2. User Task Matrix

El User Task Matrix es una herramienta que organiza y muestra las tareas que los usuarios deben realizar al interactuar con un producto o servicio. Esta matriz cruza las tareas de los usuarios con diferentes variables, como la frecuencia, la importancia, o el nivel de dificultad, para identificar qué funciones son más críticas y cómo priorizarlas en el diseño. Es útil para entender las necesidades de los usuarios y mejorar la experiencia al optimizar las tareas clave.

<table>
  <tr>
    <th rowspan="2" valign="top"><b>Task Matrix</b></th>
    <th colspan="2" valign="top"><b>Asesores</b></th>
    <th colspan="2" valign="top"><b>Granjeros</b></th>
  </tr>
  <tr>
    <td valign="top"><b>Frecuencia</b></td>
    <td valign="top"><b>Importancia</b></td>
    <td valign="top"><b>Frecuencia</b></td>
    <td valign="top"><b>Importancia</b></td>
  </tr>
  <tr>
    <td>Sembrar cultivos</td>
    <td>Nunca</td>
    <td>Ninguna</td>
    <td>Diaria</td>
    <td>Alta</td>
  </tr>
  <tr>
    <td>Proporcionar agua limpia</td>
    <td>Nunca</td>
    <td>Ninguna</td>
    <td>Diaria</td>
    <td>Alta</td>
  </tr>
  <tr>
    <td>Comprar suministros y alimentos</td>
    <td>Nunca</td>
    <td>Ninguna</td>
    <td>Mensual</td>
    <td>Media</td>
  </tr>
  <tr>
    <td>Vender producciones</td>
    <td>Nunca</td>
    <td>Ninguna</td>
    <td>Mensual</td>
    <td>Alta</td>
  </tr>
  <tr>
    <td>Gestionar gastos y ganancias</td>
    <td>Mensual</td>
    <td>Media</td>
    <td>Mensual</td>
    <td>Alta</td>
  </tr>
  <tr>
    <td>Monitorear el estado de los cultivos</td>
    <td>Mensual</td>
    <td>Alta</td>
    <td>Siempre</td>
    <td>Alta</td>
  </tr>
  <tr>
    <td>Investigar sobre nuevas prácticas agrícolas</td>
    <td>Mensual</td>
    <td>Media</td>
    <td>Casi Nunca</td>
    <td>Baja</td>
  </tr>
  <tr>
    <td>Realizar seguimiento y evaluación de progreso de granjas</td>
    <td>Semanal</td>
    <td>Alta</td>
    <td>Semanal</td>
    <td>Alta</td>
  </tr>
  <tr>
    <td>Participar de sesiones de asesoramiento</td>
    <td>Mensual</td>
    <td>Media</td>
    <td>Mensual</td>
    <td>Media</td>
  </tr>
  <tr>
    <td>Resolver problemas específicos en las granjas</td>
    <td>Según necesidad</td>
    <td>Muy Alta</td>
    <td>Según necesidad</td>
    <td>Muy Alta</td>
  </tr>
  <tr>
    <td>Desarrollar y/o asistir a sesiones de capacitación sobre técnicas agrícolas</td>
    <td>A veces</td>
    <td>Alta</td>
    <td>A veces</td>
    <td>Media</td>
  </tr>
  <tr>
    <td>Evaluar las condiciones y necesidades de las granjas de forma presencial</td>
    <td>Casi nunca</td>
    <td>Alta</td>
    <td>Diaria</td>
    <td>Media</td>
  </tr>
</table>

A partir de esta matriz, se ha logrado evidenciar que los asesores y granjeros tienen tareas con prioridades y frecuencias distintas, pero comparten algunas actividades clave, como resolver problemas específicos y realizar seguimiento semanal del progreso de la granja. Las tareas diarias de los granjeros, como sembrar, cuidar y monitorear los cultivos, son fundamentales para su trabajo, mientras que los asesores se enfocan más en el monitoreo, la evaluación y la capacitación. Este análisis sugiere que la plataforma debería ser flexible y adaptarse a las necesidades específicas de cada grupo, facilitando tanto la gestión diaria de la granja como el soporte especializado.

### 2.3.3. User Journey Mapping

El User Journey Mapping es una herramienta que permite visualizar el recorrido que un usuario sigue al interactuar con un producto o servicio, desde el primer contacto hasta la finalización de su objetivo. Este mapa identifica los puntos de interacción, emociones, necesidades, y problemas que enfrenta el usuario en cada etapa. El objetivo es comprender la experiencia del usuario para mejorar el diseño y ofrecer soluciones más efectivas.

**Segmento: Granjeros con poca experiencia**

<img alt="User Journey Mapping para Granjero" src="img/user-journey-mapping-farmer.png">

_Imagen 11. User Journey Mapping: Granjero con poca experiencia_

**Segmento: Asesores experimentados**

<img alt="User Journey Mapping para Asesor" src="img/user-journey-mapping-advisor.png">

_Imagen 12. User Journey Mapping: Asesor experimentado_

### 2.3.4. Empathy Mapping

El Empathy Mapping es una herramienta estratégica utilizada para comprender a los usuarios, en nuestro caso a los granjeros inexpertos y a los asesores experimentados. Al desarrollar un Empathy Map, se obtiene una visión integral de las necesidades, motivaciones, frustraciones y comportamientos de los usuarios al analizar lo que los usuarios piensan, sienten, dicen y hacen. De esta manera, se puede diseñar una solución más alineada con sus expectativas y mejorar su experiencia general con la aplicación.

**Segmento: Granjeros con poca experiencia**

<img alt="Empathy Map para Granjero" src="img/empathy-mapping-farmer.png">

_Imagen 13. Empathy Map: Granjero con poca experiencia_

**Segmento: Asesores experimentados**

<img alt="Empathy Map para Asesor" src="img/empathy-mapping-advisor.png">

_Imagen 14. Empathy Map: Asesor experimentado_

### 2.3.5. As-is Scenario Mapping

El As-Is Scenario Mapping es una herramienta que se utiliza para analizar y documentar el estado actual de los procesos y experiencias de los usuarios antes de la implementación de una nueva solución. En este proyecto, se enfoca en cómo los granjeros inexpertos y los asesores experimentados manejan sus necesidades de asesoramiento agrícola sin la aplicación móvil propuesta. Este mapeo es esencial para identificar los desafíos y las ineficiencias en los métodos actuales, proporcionando una base para comparar con los escenarios futuros (To-Be) y asegurar que la nueva solución realmente atienda las necesidades identificadas.

**Segmento: Granjeros con poca experiencia**

<table>
  <thead>
    <tr>
      <td>Phases</td>
      <td>Enfrentamiento de problemas</td>
      <td>Búsqueda de soluciones</td>
      <td>Consulta con fuentes locales</td>
      <td>Toma de decisiones</td>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Doing</td>
      <td>Los granjeros se encuentran con problemas en su granja que no saben cómo resolver.</td>
      <td>Buscan soluciones por su cuenta a través de internet, foros, o consejos de vecinos.</td>
      <td>Consultan a otros granjeros locales o comerciantes, quienes ofrecen consejos generales basados en su propia experiencia.</td>
      <td>Toman decisiones basadas en la información que han conseguido.</td>
    </tr>
    <tr>
      <td>Thinking</td>
      <td>"Este cultivo está plagado de insectos, pero no tengo idea de qué tratamiento usar o si lo que tengo será suficiente."</td>
      <td>"Leí en internet que podría usar un pesticida, pero otros dicen que dañará las plantas. No sé qué hacer."</td>
      <td>"El vecino dice que use el mismo tratamiento que él, pero mi situación es diferente, y no estoy seguro de que funcione igual."</td>
      <td>"Estoy usando este pesticida, pero realmente no sé si es lo mejor. Espero no arruinar toda la cosecha."</td>
    </tr>
    <tr>
      <td>Feeling</td>
      <td>Desesperación por no tener el conocimiento necesario para solucionar los problemas.</td>
      <td>Confusión por la gran cantidad de información contradictoria o poco útil.</td>
      <td>Duda por la falta de asesoramiento específico.</td>
      <td>Temor por las consecuencias de sus decisiones.</td>
    </tr>
  </tbody>
</table>

**Segmento: Asesores experimentados**

<table>
  <thead>
    <tr>
      <td>Phases</td>
      <td>Búsqueda de trabajo</td>
      <td>Promoción de servicios</td>
      <td>Contacto con granjeros</td>
      <td>Coordinación de asesorías</td>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Doing</td>
      <td>Los asesores buscan oportunidades de trabajo en asesoría agrícola a través de anuncios en línea, redes sociales y recomendaciones.</td>
      <td>Promocionan de sus servicios a través de redes sociales, sitios web personales, y referencias.</td>
      <td>Contactan con granjeros a través de correo electrónico, mensajes en redes sociales o llamadas telefónicas.</td>
      <td>Coordinan las sesiones de asesoría.</td>
    </tr>
    <tr>
      <td>Thinking</td>
      <td>"Es difícil encontrar oportunidades de asesoría. Los anuncios son escasos y no sé dónde más buscar para ofrecer mis servicios."</td>
      <td>"He promocionado mis servicios en varias plataformas, pero no estoy viendo un aumento en los clientes potenciales. ¿Qué más puedo hacer para atraerlos?"</td>
      <td>"He enviado varios mensajes y correos, pero no obtengo respuestas o la comunicación es poco clara. Esto hace que sea difícil conectar con clientes potenciales."</td>
      <td>"¡Qué difícil tener que coordinar horarios a través de mensajes y llamadas! Muchas veces los granjeros tienen horarios impredecibles, y esto hace que la planificación sea un verdadero desafío."</td>
    </tr>
    <tr>
      <td>Feeling</td>
      <td>Desánimo debido a la escasez de oportunidades y la falta de claridad sobre dónde encontrar potenciales clientes.</td>
      <td>Estrés por la baja visibilidad y el esfuerzo que no se traduce en resultados concretos.</td>
      <td>Desánimo debido a la falta de respuestas y a la dificultad de establecer comunicación efectiva.</td>
      <td>Frustración por las dificultades de elegir una fecha y medio adecuados.</td>
    </tr>
  </tbody>
</table>

## 2.4. Requirements Specification

### 2.4.1. To-Be Scenario Mapping

El To-Be Scenario Mapping es una herramienta que describe cómo los procesos y experiencias de los usuarios evolucionarán tras la implementación de una nueva solución. En este caso, se enfoca en cómo la aplicación móvil mejorará la forma en que los granjeros inexpertos acceden a asesorías especializadas y cómo los asesores experimentados encontrarán y se comunicarán con los granjeros. Este mapeo destaca las eficiencias, facilidades y beneficios que la aplicación aportará, permitiendo visualizar el futuro deseado y asegurando que la solución cumpla con las expectativas de los usuarios, resolviendo los desafíos identificados en el escenario As-Is.

**Segmento: Granjeros con poca experiencia**

<table>
  <thead>
    <tr>
      <td>Phases</td>
      <td>Enfrentamiento de problemas</td>
      <td>Búsqueda de soluciones</td>
      <td>Consulta con asesor</td>
      <td>Toma de decisiones</td>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Doing</td>
      <td>Los granjeros se encuentran con problemas en su granja que no saben cómo resolver.</td>
      <td>Abren la aplicación, buscan asesores especializados para resolver el tipo de problema que enfrentan.</td>
      <td>Seleccionan un asesor, agendan una consulta, y se comunican con él para discutir los detalles del problema y recibir recomendaciones específicas.</td>
      <td>Utilizan la información y recomendaciones obtenidas para tomar decisiones informadas sobre cómo manejar el problema en su granja.</td>
    </tr>
    <tr>
      <td>Thinking</td>
      <td>"Tengo un problema serio, pero al menos sé que puedo encontrar a alguien que me ayude a solucionarlo de manera eficiente."</td>
      <td>"Es bueno saber que hay expertos que entienden exactamente lo que necesito. Ahora puedo elegir al que mejor se ajuste a mis necesidades."</td>
      <td>"Este asesor realmente entiende mi problema y me está dando consejos útiles que puedo aplicar de inmediato."</td>
      <td>"Con el respaldo del asesor, puedo tomar decisiones que realmente mejorarán mi granja, y sé que puedo volver a consultar si tengo más dudas."</td>
    </tr>
    <tr>
      <td>Feeling</td>
      <td>Un poco de preocupación pero también esperanza, sabiendo que puede obtener ayuda rápidamente gracias a la aplicación.</td>
      <td>Alivio al ver una lista clara de asesores disponibles con sus calificaciones y especializaciones.</td>
      <td>Comprendido y apoyado, al recibir orientación personalizada que se adapta a su situación particular.</td>
      <td>Confiado de que está tomando la mejor acción posible basada en el asesoramiento recibido.</td>
    </tr>
  </tbody>
</table>

**Segmento: Asesores experimentados**

<table>
  <thead>
    <tr>
      <td>Phases</td>
      <td>Promoción de servicios</td>
      <td>Contacto con granjeros</td>
      <td>Realización de asesorías</td>
      <td>Seguimiento</td>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Doing</td>
      <td>Los asesor crean publicaciones con los servicios que ofrecen para llamar la atención de los granjeros.</td>
      <td>Reciben notificaciones de solicitudes de asesoría de granjeros y revisan los detalles para saber la fecha y hora de la asesoría.</td>
      <td>Realizan las sesiones de asesoría acordadas, y proporcionan recomendaciones y soluciones personalizadas durante la consulta.</td>
      <td>Realiza un seguimiento con los granjeros a través de la aplicación, revisa los resultados obtenidos y ajusta recomendaciones si es necesario.</td>
    </tr>
    <tr>
      <td>Thinking</td>
      <td>"La aplicación me permite mostrar mis habilidades y experiencia de manera efectiva, lo que puede atraer a más granjeros que necesitan asesoría."</td>
      <td>"La aplicación simplifica la gestión de solicitudes y el contacto inicial, permitiéndome organizar rápidamente las consultas y centrarme en la asesoría efectiva."</td>
      <td>"La aplicación me ofrece una opción sencilla para unirme a una videoconferencia y poder realizar la asesoría, lo que me permite despreocuparme de otras coordinaciones."</td>
      <td> "El seguimiento es fácil al poder contactar al granjero por la aplicación."</td>
    </tr>
    <tr>
      <td>Feeling</td>
      <td>Motivación al poder mostrar sus servicios de una manera efectiva y llamativa para recibir mayores ofertas de trabajo.</td>
      <td>Alivio al poder gestionar todas las solicitudes de asesoría de manera sencilla.</td>
      <td>Satisfecho al tener una plataforma que facilita un enlace para unirse a la videoconferencia donde se hará la asesoría sin mayores complicaciones.</td>
      <td>Alivio al tener una herramienta que facilita el seguimiento y permite mantener una comunicación continua con los granjeros.</td>
    </tr>
  </tbody>
</table>

### 2.4.2. User Stories


<table>
    <thead>
      <tr>
        <th style="width: 10%;">Epic ID</th>
        <th style="width: 35%;">Epic</th>
        <th style="width: 10%;">User Story ID</th>
        <th style="width: 45%;">User Stories</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td rowspan="11">1</td>
        <td rowspan="11">Sistema de búsqueda y programación de citas</td>
        <td>US01</td>
        <td>Visualización del catálogo de asesores</td>
      </tr>
      <tr>
        <td>US02</td>
        <td>Visualización de información de un asesor</td>
      </tr>
      <tr>
        <td>US03</td>
        <td>Visualización de horarios de asesores</td>
      </tr>
      <tr>
        <td>US04</td>
        <td>Programación de citas con asesores</td>
      </tr>
      <tr>
        <td>US05</td>
        <td>Calificación del asesor luego de una cita</td>
      </tr>
      <tr>
        <td>US06</td>
        <td>Separación de horarios de disponibilidad para asesorías</td>
      </tr>
      <tr>
        <td>US19</td>
        <td>Recordatorio de Cita</td>
      </tr>
      <tr>
        <td>US20</td>
        <td>Pantalla de inicio</td>
      </tr>
      <tr>
        <td>US21</td>
        <td>Visualización de Historial de Citas</td>
      </tr>
      <tr>
        <td>US22</td>
        <td>Cancelación de Citas</td>
      </tr>
      <tr>
        <td>US23</td>
        <td>Búsqueda y Filtrado de Citas</td>
      </tr>
      <tr>
        <td rowspan="2">2</td>
        <td rowspan="2">Publicaciones de asesores</td>
        <td>US07</td>
        <td>Gestión de publicaciones de asesores</td>
      </tr>
      <tr>
        <td>US08</td>
        <td>Visualización de publicaciones de los asesores</td>
      </tr>
      <tr>
        <td rowspan="5">3</td>
        <td rowspan="5">Sistema de gestión de usuarios</td>
        <td>US09</td>
        <td>Registro de un usuario nuevo</td>
      </tr>
      <tr>
        <td>US10</td>
        <td>Inicio de sesión</td>
      </tr>
      <tr>
        <td>US11</td>
        <td>Recuperación de contraseña</td>
      </tr>
      <tr>
        <td>US12</td>
        <td>Notificación al usuario</td>
      </tr>
      <tr>
        <td>US13</td>
        <td>Disponibilidad y confiabilidad</td>
      </tr>
      <tr>
        <td rowspan="5">4</td>
        <td rowspan="5">Landing Page de App Móvil</td>
        <td>US14</td>
        <td>Visualización de la sección de inicio de la Landing Page</td>
      </tr>
      <tr>
        <td>US15</td>
        <td>Visualización de la sección 'Acerca de' de la Landing Page</td>
      </tr>
      <tr>
        <td>US16</td>
        <td>Visualización de la sección 'Sobre Nosotros' de la Landing Page</td>
      </tr>
      <tr>
        <td>US17</td>
        <td>Visualización de la sección 'Características' de la Landing Page</td>
      </tr>
      <tr>
        <td>US18</td>
        <td>Visualización de la sección 'Contacto' de la Landing Page</td>
      </tr>
      <tr>
        <td rowspan="6">5</td>
        <td rowspan="6">Funcionalidades de Web API (Backend)</td>
        <td>TS01</td>
        <td>Uso de una API para videollamadas</td>
      </tr>
      <tr>
        <td>TS02</td>
        <td>Uso de una API para alojar imágenes</td>
      </tr>
      <tr>
        <td>TS03</td>
        <td>Uso de nuestra API para gestionar perfiles</td>
      </tr>
      <tr>
        <td>TS04</td>
        <td>Uso de nuestra API para gestionar asesorías</td>
      </tr>
      <tr>
        <td>TS05</td>
        <td>Uso de nuestra API para gestionar publicaciones</td>
      </tr>
      <tr>
        <td>TS06</td>
        <td>Uso de nuestra API para gestionar autenticación</td>
      </tr>
    </tbody>
</table>


<table>
    <thead>
      <tr>
        <th style="width: 10%;">User Story ID</th>
        <th style="width: 20%;">Título</th>
        <th style="width: 25%;">Descripción</th>
        <th style="width: 35%;">Criterios de aceptación</th>
        <th style="width: 10%;">Relacionado con (Epic ID)</th>
      </tr>
  </thead>
  <tbody>
    <tr>
        <td>US01</td>
        <td>Visualización del catálogo de asesores</td>
        <td>Como granjero con poca experiencia, quiero explorar el catálogo de asesores para conocer quiénes me pueden apoyar con asesorías.</td>
        <td>
            <strong>Escenario 1: Explorar catálogo de asesores</strong><br>
            <strong>Given</strong> el granjero con poca experiencia quiere explorar el catálogo de asesores.<br>
            <strong>And</strong> se encuentra en la aplicación.<br>
            <strong>When</strong> seleccione el botón relacionado con el “Catálogo de asesores”.<br>
            <strong>Then</strong> el sistema le mostrará una lista de todos los asesores disponibles en la aplicación.
            <br><br>
            <strong>Escenario 2: Filtrar búsqueda de asesores</strong><br>
            <strong>Given</strong> el granjero con poca experiencia quiere personalizar su búsqueda.<br>
            <strong>And</strong> se encuentra en el apartado de “Asesores”.<br>
            <strong>When</strong> seleccione el botón de filtros.<br>
            <strong>Then</strong> el sistema le permitirá filtrar el catálogo de asesores por nombre o reputación.
        </td>
        <td>1</td>
    </tr>
    <tr>
        <td>US02</td>
        <td>Visualización de información de un asesor</td>
        <td>Como granjero con poca experiencia, quiero ver la información de un asesor para tomar una decisión informada antes de separar una cita.</td>
        <td>
            <strong>Escenario 1: Ver información de un asesor</strong><br>
            <strong>Given</strong> el granjero con poca experiencia quiere ver información de un asesor.<br>
            <strong>And</strong> se encuentra en el apartado del “Catálogo de Asesores” en su dispositivo móvil.<br>
            <strong>When</strong> seleccione al cuadro de un asesor en la interfaz móvil.<br>
            <strong>Then</strong> el sistema le mostrará la información del asesor como nombre, experiencia, calificación y reseñas de manera optimizada para móvil.
            <br><br>
            <strong>Escenario 2: Fallar al visualizar la información del asesor</strong><br>
            <strong>Given</strong> el granjero con poca experiencia quiere ver información relevante del asesor.<br>
            <strong>And</strong> se encuentra en el apartado de “Asesores” en su dispositivo móvil.<br>
            <strong>When</strong> seleccione al cuadro de un asesor en la interfaz móvil.<br>
            <strong>And</strong> se encuentre con un error al cargar la información.<br>
            <strong>Then</strong> el sistema le mostrará un mensaje de error de carga en la interfaz móvil.
        </td>
        <td>1</td>
    </tr>
    <tr>
        <td>US03</td>
        <td>Visualización de horarios de asesores</td>
        <td>Como granjero con poca experiencia, quiero ver los horarios disponibles de los asesores en mi móvil para seleccionar un horario que se ajuste a mi agenda.</td>
        <td>
            <strong>Escenario 1: Visualizar horarios disponibles</strong><br>
            <strong>Given</strong> el granjero con poca experiencia desea visualizar los horarios disponibles de un asesor elegido.<br>
            <strong>And</strong> se encuentra viendo la información del perfil de un asesor en su dispositivo móvil.<br>
            <strong>When</strong> haga clic en el botón “Reservar Cita” en la interfaz móvil.<br>
            <strong>Then</strong> el sistema le mostrará una interfaz con los horarios disponibles del asesor.
            <br><br>
            <strong>Escenario 2: Fallar al intentar visualizar horarios</strong><br>
            <strong>Given</strong> el granjero con poca experiencia desea visualizar los horarios disponibles del asesor elegido.<br>
            <strong>And</strong> se encuentra viendo la información del perfil de un asesor en su dispositivo móvil.<br>
            <strong>When</strong> haga clic en el botón “Reservar Cita” en la interfaz móvil.<br>
            <strong>And</strong> el asesor no tenga horarios disponibles.<br>
            <strong>Then</strong> el sistema le mostrará un mensaje de error “El asesor no tiene horarios disponibles” en la interfaz móvil.
        </td>
        <td>1</td>
    </tr>
    <tr>
        <td>US04</td>
        <td>Programación de citas con asesores</td>
        <td>Como granjero con poca experiencia, quiero programar una cita con un asesor para recibir orientación personalizada en el sector agropecuario.</td>
        <td>
            <strong>Escenario 1: Programar cita</strong><br>
            <strong>Given</strong> el granjero con poca experiencia desea programar una cita.<br>
            <strong>And</strong> se encuentra en el apartado de “Horarios Disponibles” del perfil de un asesor en su dispositivo móvil.<br>
            <strong>When</strong> seleccione un horario disponible.<br>
            <strong>And</strong> complete los campos solicitados.<br>
            <strong>And</strong> haga clic en el botón “Reservar Cita”.<br>
            <strong>Then</strong> el sistema le mostrará un mensaje de confirmación.
            <br><br>
            <strong>Escenario 2: Fallar al programar cita</strong><br>
            <strong>Given</strong> el granjero con poca experiencia desea programar una cita.<br>
            <strong>And</strong> se encuentra en el apartado de “Horarios Disponibles” del perfil de un asesor.<br>
            <strong>When</strong> seleccione un horario disponible.<br>
            <strong>And</strong> se encuentra un error técnico o de conexión que impide completar la programación.<br>
            <strong>Then</strong> el sistema le mostrará un mensaje de error.
        </td>
        <td>1</td>
    </tr>
    <tr>
        <td>US05</td>
        <td>Calificación del asesor luego de una cita</td>
        <td>Como granjero con poca experiencia, quiero calificar al asesor luego de la consulta para ayudar a otros granjeros a tomar una decisión informada antes de separar una cita.</td>
        <td>
            <strong>Escenario 1: Calificar al asesor</strong><br>
            <strong>Given</strong> el granjero con poca experiencia desea hacer un feedback referente al servicio del asesor.<br>
            <strong>And</strong> se encuentra en la vista de historial de asesorías.
            <strong>And</strong> selecciona una asesoría sin reseña.
            <br>
            <strong>When</strong> haga clic en el botón “Calificar Servicio” en la interfaz.<br>
            <strong>Then</strong> el sistema le permitirá asignarle un número de estrellas y reseñar el servicio del asesor.
            <br><br>
            <strong>Escenario 2: Omitir Calificación</strong><br>
            <strong>Given</strong> el granjero con poca experiencia no desea dar feedback al asesor referente al servicio.<br>
            <strong>And</strong> se encuentra en la vista de historial de asesorías.
            <strong>And</strong> selecciona una asesoría sin reseña.
            <strong>When</strong> haga clic en el botón “Omitir Calificación” en la interfaz.<br>
            <strong>Then</strong> el sistema le permitirá omitir la reseña.
        </td>
        <td>1</td>
    </tr>
    <tr>
        <td>US06</td>
        <td>Separación de horarios de disponibilidad para asesorías</td>
        <td>Como asesor, quiero poder separar los horarios en las que estoy disponible para que los usuarios interesados puedan agendar una asesoría en un momento conveniente.</td>
        <td>
            <strong>Escenario 1: Registrar disponibilidad para asesorías</strong><br>
            <strong>Given</strong> el asesor desea registrar su horario de disponibilidad para una asesoría.<br>
            <strong>And</strong> está visualizando la sección de "Horarios disponibles" en su dispositivo.<br>
            <strong>When</strong> haga clic en el botón para registrar un nuevo horario.<br>
            <strong>And</strong> complete los datos del nuevo horario.<br>
            <strong>Then</strong> el sistema actualizará y guardará los horarios y horas seleccionadas como disponibles en la interfaz móvil.
            <br><br>
            <strong>Escenario 2: Eliminar horario de disponibilidad para asesorías</strong><br>
            <strong>Given</strong> el asesor desea eliminar un horario de disponibilidad para asesorías.<br>
            <strong>And</strong> está visualizando la página de "Horario disponible" en su dispositivo.<br>
            <strong>When</strong> haga clic en el botón “Eliminar” relacionado al horario que desea eliminar.<br>
            <strong>And</strong> confirme la eliminación del horario.<br>
            <strong>Then</strong> el sistema eliminará el horario de disponibilidad seleccionado.
        </td>
        <td>1</td>
    </tr>
    <tr>
        <td>US07</td>
        <td>Gestión de publicaciones de asesores</td>
        <td>Como asesor, quiero hacer publicaciones referentes a mis trabajos para tener una mayor visibilidad con los granjeros inexpertos.</td>
        <td>
            <strong>Escenario 1: Crear una nueva publicación</strong><br>
            <strong>Given</strong> el asesor desea crear una publicación.<br>
            <strong>And</strong> está en el apartado de sus publicaciones<br>
            <strong>When</strong> hace clic en el botón "Crear Publicación" de la interfaz.<br>
            <strong>Then</strong> se le redirige a un formulario donde puede ingresar el contenido de su nueva publicación.<br>
            <strong>And</strong> después de completar el contenido, hace clic en el botón "Publicar".<br>
            <strong>Then</strong> el sistema le mostrará un mensaje de confirmación.
            <strong>And</strong> el sistema publicará el contenido para que sea visible a los granjeros.
            <br><br>
            <strong>Escenario 2: Editar una publicación existente</strong><br>
            <strong>Given</strong> el asesor desea editar una publicación existente.<br>
            <strong>And</strong> está en el apartado de sus publicaciones<br>
            <strong>And</strong> tiene una publicación previamente creada.<br>
            <strong>When</strong> selecciona la opción de editar en la publicación.<br>
            <strong>Then</strong> se le redirige al formulario de edición donde puede modificar el contenido de la publicación.<br>
            <strong>And</strong> después de realizar los cambios deseados, hace clic en el botón "Guardar Cambios".<br>
            <strong>Then</strong> el sistema le mostrará un mensaje de confirmación y los cambios se reflejan en la publicación actualizada.
            <br><br>
            <strong>Escenario 3: Eliminar una publicación existente</strong><br>
            <strong>Given</strong> el asesor desea eliminar una publicación existente.<br>
            <strong>And</strong> está en el apartado de sus publicaciones<br>
            <strong>And</strong> tiene una publicación previamente creada.<br>
            <strong>When</strong> selecciona la opción de eliminar en la publicación que desea borrar.<br>
            <strong>Then</strong> el sistema le mostrará un mensaje de confirmación solicitando la confirmación de la eliminación.<br>
            <strong>And</strong> después de confirmar, la publicación se elimina de su perfil y ya no está disponible para los granjeros.
        </td>
        <td>2</td>
    </tr>
    <tr>
        <td>US08</td>
        <td>Visualización de publicaciones de los asesores</td>
        <td>Como granjero con poca experiencia, quiero poder ver las publicaciones de los asesores para obtener información útil y solicitar asesoramiento en base a esas publicaciones.</td>
        <td>
            <strong>Escenario 1: Visualizar publicaciones de asesores</strong><br>
            <strong>Given</strong> el granjero con poca experiencia desea ver las publicaciones de los asesores.<br>
            <strong>When</strong> haga clic en el botón de publicaciones.<br>
            <strong>Then</strong> el sistema le mostrará una lista de las publicaciones de los asesores.
        </td>
        <td>2</td>
    </tr>
    <tr>
        <td>US09</td>
        <td>Registro de un usuario nuevo</td>
        <td>Como usuario, quiero registrarme para acceder a las funciones de usuario.</td>
        <td>
            <strong>Escenario 1: Registro de cuenta por formulario</strong><br>
            <strong>Given</strong> el usuario desea registrarse en la aplicación.<br>
            <strong>And</strong> se encuentra en el apartado de “Registrarse”.<br>
            <strong>When</strong> complete el formulario de registro con su información personal.<br>
            <strong>And</strong> seleccione su rol en la aplicación entre “Granjero” o “Asesor”.<br>
            <strong>And</strong> los datos sean correctos según las validaciones establecidas.<br>
            <strong>Then</strong> la cuenta se creará exitosamente.
            <br><br>
            <strong>Escenario 2: Registro incorrecto de cuenta</strong><br>
            <strong>Given</strong> el usuario se encuentra en el apartado de “Registrarse”.<br>
            <strong>When</strong> ingrese los datos solicitados de manera errónea.<br>
            <strong>Then</strong> la cuenta no se creará.<br>
            <strong>And</strong> recibirá un mensaje indicando el error en los datos ingresados.
        </td>
        <td>3</td>
    </tr>
    <tr>
        <td>US10</td>
        <td>Inicio de sesión</td>
        <td>Como usuario quiero acceder a mi cuenta registrada para acceder a las funciones de usuario.</td>
        <td>
            <strong>Escenario 1: Inicio de sesión exitoso</strong><br>
            <strong>Given</strong> el usuario desea acceder a su cuenta registrada.<br>
            <strong>And</strong> se encuentra en el apartado de “Iniciar Sesión”.<br>
            <strong>When</strong> introduzca sus credenciales correctamente.<br>
            <strong>Then</strong> será redireccionado a su vista de usuario.
            <br><br>
            <strong>Escenario 2: Inicio de sesión fallido</strong><br>
            <strong>Given</strong> el usuario desea acceder a su cuenta registrada.<br>
            <strong>And</strong> se encuentra en el apartado de “Iniciar Sesión”.<br>
            <strong>When</strong> introduzca sus credenciales incorrectamente.<br>
            <strong>Then</strong> no se le permitirá acceso a su cuenta.<br>
            <strong>And</strong> recibirá un mensaje indicando el error.
            <br><br>
            <strong>Escenario 3: Bloqueo de sesión por exceso de intentos</strong><br>
            <strong>Given</strong> el usuario desea acceder a su cuenta registrada.<br>
            <strong>And</strong> se encuentra en el apartado de “Iniciar sesión”.<br>
            <strong>When</strong> introduzca sus credenciales incorrectamente.<br>
            <strong>And</strong> siga errando hasta alcanzar el número máximo de intentos permitidos (tres intentos).<br>
            <strong>Then</strong> recibirá un mensaje que le informe que ha excedido el número de intentos permitidos.<br>
            <strong>And</strong> su cuenta será bloqueada temporalmente.
        </td>
        <td>3</td>
    </tr>
    <tr>
        <td>US11</td>
        <td>Recuperación de contraseña</td>
        <td>Como usuario quiero poder recuperar mi contraseña para acceder a mi cuenta.</td>
        <td>
            <strong>Escenario 1: Recuperación de contraseña</strong><br>
            <strong>Given</strong> el usuario olvidó su contraseña.<br>
            <strong>When</strong> se dirija a la sección de “Inicio de sesión”.<br>
            <strong>And</strong> seleccione “olvidé mi contraseña”.<br>
            <strong>And</strong> coloque su correo vinculado a la cuenta.<br>
            <strong>Then</strong> se le enviará un correo para que cambie su contraseña.
        </td>
        <td>3</td>
    </tr>
    <tr>
      <td>US12</td>
      <td>Notificación al usuario</td>
      <td>Como usuario de la aplicación, quiero recibir notificaciones referentes al estado de las asesorias u otra información relevante para mantenerme informado.</td>
      <td>
        <strong>Escenario 1: Recibir notificaciones de asesorías programadas</strong><br>
        <strong>Given</strong> el usuario está registrado en la aplicación.<br>
        <strong>When</strong> se aproxime la fecha de una asesoría.<br>
        <strong>Then</strong> el sistema le enviará una notificación a su dispositivo indicando la proximidad de la asesoría.
        <br><br>
        <strong>Escenario 2: Recibir notificaciones de información relevante</strong><br>
        <strong>Given</strong> el usuario está registrado en la aplicación.<br>
        <strong>When</strong> se genere información relevante para el usuario, como cambios en la política de privacidad, actualizaciones importantes, o nuevas funcionalidades.<br>
        <strong>Then</strong> el sistema le enviará una notificación a su dispositivo indicando la relevancia de dicha información.
      </td>
      <td>3</td>
    </tr>
    <tr>
      <td>US13</td>
      <td>Disponibilidad y confiabilidad</td>
      <td>Como usuario, quiero que la aplicación esté disponible siempre para acceder a ella en cualquier momento y sin interrupciones.</td>
      <td>
        <strong>Escenario 1: Acceso a la aplicación en todo momento</strong><br>
        <strong>Given</strong> el usuario desea usar la aplicación en cualquier instante.<br>
        <strong>When</strong> ingresa a la aplicación.<br>
        <strong>Then</strong> la aplicación debe estar disponible y funcional, sin caídas ni errores que impidan el acceso.
        <br><br>
        <strong>Escenario 2: Acceso a la aplicación sin interrupciones</strong><br>
        <strong>Given</strong> el usuario desea usar la aplicación en cualquier instante.<br>
        <strong>When</strong> ingresa a la aplicación.<br>
        <strong>Then</strong> la aplicación debe cargar rápidamente y gestionar el tráfico de manera eficiente para asegurar una experiencia de usuario fluida, evitando tiempos de carga prolongados o interrupciones en el servicio.
      </td>
      <td>3</td>
    </tr>
    <tr>
      <td>US14</td>
      <td>Visualización de la sección de inicio de la Landing Page</td>
      <td>Como potencial usuario quiero acceder a una página de inicio para conocer la idea principal de la aplicación y ver un diseño agradable.</td>
      <td>
        <strong>Escenario 1: Visualización de página de inicio</strong><br>
        <strong>Given</strong> el usuario desea conocer sobre la aplicación.<br>
        <strong>When</strong> ingresa al Landing Page.<br>
        <strong>Then</strong> se mostrará la página inicial sencilla que da a entender la idea principal.
      </td>
      <td>4</td>
    </tr>
    <tr>
      <td>US15</td>
      <td>Visualización de la sección 'Acerca de' de la Landing Page</td>
      <td>Como potencial usuario quiero acceder a una página sobre el problema que resuelve para conocer el propósito de la aplicación.</td>
      <td>
        <strong>Escenario 1: Visualización de la sección</strong><br>
        <strong>Given</strong> el usuario desea conocer sobre el problema que resuelve la aplicación.<br>
        <strong>When</strong> ingresa al Landing Page.<br>
        <strong>And</strong> ingresa a la sección 'Acerca De'.<br>
        <strong>Then</strong> se mostrará la página Acerca De, en la que se detalla la problemática que resolverá la aplicación.
      </td>
      <td>4</td>
    </tr>
    <tr>
      <td>US16</td>
      <td>Visualización de la sección 'Sobre Nosotros' de la Landing Page</td>
      <td>Como potencial usuario quiero acceder a una página sobre la startup para conocer el propósito de la empresa detrás de la aplicación.</td>
      <td>
        <strong>Escenario 1: Visualización de la sección</strong><br>
        <strong>Given</strong> el usuario desea conocer sobre la empresa detrás de la aplicación.<br>
        <strong>When</strong> ingresa al Landing Page.<br>
        <strong>And</strong> ingresa a la sección 'Sobre Nosotros'.<br>
        <strong>Then</strong> se mostrará la página Sobre Nosotros, en la que detalla información sobre la startup, su misión y visión.
      </td>
      <td>4</td>
    </tr>
    <tr>
      <td>US17</td>
      <td>Visualización de la sección 'Características' de la Landing Page</td>
      <td>Como potencial usuario quiero acceder a una página sobre las características para conocer las principales funcionalidades de la aplicación.</td>
      <td>
        <strong>Escenario 1: Visualización de la sección</strong><br>
        <strong>Given</strong> el usuario desea conocer sobre las características de la aplicación.<br>
        <strong>When</strong> ingresa al Landing Page.<br>
        <strong>And</strong> ingresa a la sección 'Características'.<br>
        <strong>Then</strong> se mostrará la página Características en la que detalla información sobre las funcionalidades principales que ofrece la aplicación.
      </td>
      <td>4</td>
    </tr>
    <tr>
      <td>US18</td>
      <td>Visualización de la sección 'Contacto' de la Landing Page</td>
      <td>Como potencial usuario quiero acceder a una página de contacto para poder contactar con la empresa en caso tenga algún problema, duda o sugerencia.</td>
      <td>
        <strong>Escenario 1: Visualización de la sección</strong><br>
        <strong>Given</strong> el usuario desea contactar con el área de soporte de la empresa.<br>
        <strong>When</strong> ingresa al Landing Page.<br>
        <strong>And</strong> ingresa a la sección 'Contacto'.<br>
        <strong>Then</strong> se mostrará la página Contacto, en la que se muestra los medios de contacto que puede usar el usuario para hacer consultas.
      </td>
      <td>4</td>
    </tr>
    <tr>
      <td>US19</td>
      <td>Recordatorio de Cita</td>
      <td>Como usuario, quiero recibir un recordatorio de la cita programada para asegurarme de no olvidarla y estar preparado para la reunión.</td>
      <td>
        <strong>Escenario 1: Envío de recordatorio</strong><br>
        <strong>Given</strong> el usuario tiene una cita programada.<br>
        <strong>When</strong> la cita está próxima (por ejemplo, 24 horas antes).<br>
        <strong>Then</strong> el sistema enviará un recordatorio por notificación en la aplicación y/o por correo electrónico.
      </td>
      <td>1</td>
    </tr>
    <tr>
      <td>US20</td>
      <td>Pantalla de inicio</td>
      <td>Como usuario, quiero ver una pantalla de inicio sencilla para navegar y explorar las funcionalidades de la aplicación fácilmente.</td>
      <td>
        <strong>Escenario 1: Pantalla de inicio de la aplicación</strong><br>
        <strong>Given</strong> el usuario ha ingresado a la aplicación.<br>
        <strong>When</strong> inicie sesión correctamente.<br>
        <strong>Then</strong> el sistema lo derivará a la pantalla de inicio y visualizará las opciones para navegar por la aplicación.
      </td>
      <td>1</td>
    </tr>
    <tr>
      <td>US21</td>
      <td>Visualización de Historial de Citas</td>
      <td>Como usuario, quiero ver un historial de mis citas anteriores para tener un registro de las reuniones y sus detalles.</td>
      <td>
        <strong>Escenario 1: Acceso al historial de citas</strong><br>
        <strong>Given</strong> el usuario está en la sección de perfil de su cuenta.<br>
        <strong>When</strong> selecciona la opción para ver el historial de citas.<br>
        <strong>Then</strong> podrá ver una lista de todas las citas anteriores, incluyendo fechas, horas y detalles de las reuniones.
      </td>
      <td>1</td>
    </tr>
    <tr>
      <td>US22</td>
      <td>Cancelación de Citas</td>
      <td>Como usuario, quiero poder cancelar mis citas existentes para ajustarlas a mis nuevas disponibilidades o necesidades.</td>
      <td>
        <strong>Escenario 1: Cancelación de una cita</strong><br>
        <strong>Given</strong> el usuario tiene una cita programada y desea cancelarla.<br>
        <strong>When</strong> selecciona la cita del listado de citas.<br>
        <strong>And</strong> selecciona la opción para cancelar la cita.<br>
        <strong>Then</strong> el sistema cancelará la cita y notificará al usuario y al asesor sobre el cambio.
      </td>
      <td>1</td>
    </tr>
    <tr>
      <td>US23</td>
      <td>Búsqueda y Filtrado de Citas</td>
      <td>Como usuario, quiero buscar y filtrar mis citas programadas para encontrar fácilmente una cita específica o consultar citas en un rango de fechas determinado.</td>
      <td>
        <strong>Escenario 1: Búsqueda de citas</strong><br>
        <strong>Given</strong> el usuario está en la sección de citas de la aplicación.<br>
        <strong>When</strong> ingresa un término de búsqueda o selecciona filtros (por ejemplo, fecha, tipo de cita).<br>
        <strong>Then</strong> el sistema mostrará una lista de citas que coincidan con los criterios de búsqueda y filtrado.
      </td>
      <td>1</td>
    </tr>
        <tr>
      <td>TS01</td>
      <td>Uso de una API para videollamadas</td>
      <td>Como desarrollador quiero integrar la creación de videollamadas utilizando la API de Jitsi Meet para facilitar las asesorías en la aplicación.</td>
      <td>
        <strong>Escenario 1: Creación de videollamada</strong><br>
        <strong>Given</strong> el usuario tiene una asesoría pendiente.<br>
        <strong>When</strong> seleccione la opción de ingresar a la asesoría.<br>
        <strong>Then</strong> el sistema lo redireccionará a un enlace con la videollamada de Jitsi Meet para que el usuario acceda a la asesoría.
      </td>
      <td>5</td>
    </tr>
    <tr>
      <td>TS02</td>
      <td>Uso de una API para alojar imágenes</td>
      <td>Como desarrollador quiero integrar la API de almacenamiento de Firebase para que los usuarios puedan subir y visualizar sus imágenes de foto de perfil y publicaciones.</td>
      <td>
        <strong>Escenario 1: Subir imagen en la aplicación</strong><br>
        <strong>Given</strong> el usuario desea subir una imagen en nuestra plataforma.
        <br>
        <strong>When</strong> se reciba la imagen en el formato compatible.
        <br>
        <strong>Then</strong>  el sistema sube la imagen usando la API del almacenamiento de Firebase para generar el enlace de visualización.
      </td>
      <td>5</td>
    </tr>
    <tr>
      <td>TS03</td>
      <td>Uso de nuestra API para gestionar perfiles</td>
      <td>Como desarrollador quiero integrar un API para gestionar la información de los perfiles de los usuarios en la base de datos, de manera que pueda realizar operaciones CRUD (Crear, Leer, Actualizar, Borrar) a través de solicitudes HTTP.</td>
      <td>
        <strong>Escenario 1: Integrar un API para manejar las solicitudes HTTP de los perfiles de usuario</strong><br>
        <strong>Given</strong> la aplicación tiene acceso a la documentación de la API y las credenciales necesarias para realizar la integración.
        <br>
        <strong>When</strong> se envía una solicitud de tipo GET, POST o PUT con los datos solicitados del usuario a la API.
        <br>
        <strong>Then</strong> la API responde con un código de estado correspondiente (200 OK o 201 Created).
        <br>
        <strong>And</strong> se realiza la operación solicitada.
        <br><br>
        <strong>Escenario 2: Manejar errores en la Integración de API para Solicitudes HTTP de perfiles de usuario</strong><br>
        <strong>Given</strong> la aplicación tiene acceso a la documentación de la API y las credenciales necesarias para realizar la integración
        <br>
        <strong>When</strong> se envía una solicitud de tipo GET, POST, PUT o DELETE con los datos solicitados del perfil del usuario a la API
        <br>
        <strong>And</strong> ocurre un error.
        <br>
        <strong>Then</strong> la API responde con un código de estado correspondiente al error (400 Bad Request, 401 Unauthorized, 403 Forbidden, 404 Not Found, 500 Internal Server Error).
        <br>
        <strong>And</strong> el sistema proporciona un mensaje de error descriptivo que ayuda al desarrollador a identificar y corregir el problema.
      </td>
      <td>5</td>
    </tr>
    <tr>
      <td>TS04</td>
      <td>Uso de nuestra API para gestionar asesorías</td>
      <td>Como desarrollador quiero integrar un API para gestionar la información de las asesorías en la base de datos, de manera que pueda realizar operaciones CRUD (Crear, Leer, Actualizar, Borrar) a través de solicitudes HTTP.</td>
      <td>
        <strong>Escenario 1: Integrar un API para manejar las solicitudes HTTP de las asesorías</strong><br>
        <strong>Given</strong> la aplicación tiene acceso a la documentación de la API y las credenciales necesarias para realizar la integración.
        <br>
        <strong>When</strong> se envía una solicitud de tipo GET, POST o PUT con los datos solicitados del usuario a la API.
        <br>
        <strong>Then</strong> la API responde con un código de estado correspondiente (200 OK o 201 Created).
        <br>
        <strong>And</strong> se realiza la operación solicitada.
        <br><br>
        <strong>Escenario 2: Manejar errores en la Integración de API para Solicitudes HTTP de asesorías</strong><br>
        <strong>Given</strong> la aplicación tiene acceso a la documentación de la API y las credenciales necesarias para realizar la integración
        <br>
        <strong>When</strong> se envía una solicitud de tipo GET, POST, PUT o DELETE con los datos solicitados de la cita de asesoría a la API
        <br>
        <strong>And</strong> ocurre un error.
        <br>
        <strong>Then</strong> la API responde con un código de estado correspondiente al error (400 Bad Request, 401 Unauthorized, 403 Forbidden, 404 Not Found, 500 Internal Server Error).
        <br>
        <strong>And</strong> el sistema proporciona un mensaje de error descriptivo que ayuda al desarrollador a identificar y corregir el problema.
      </td>
      <td>5</td>
    </tr>
    <tr>
      <td>TS05</td>
      <td>Uso de nuestra API para gestionar publicaciones</td>
      <td>Como desarrollador quiero integrar un API para gestionar la información de las publicaciones de los asesores en la base de datos, de manera que pueda realizar operaciones CRUD (Crear, Leer, Actualizar, Borrar) a través de solicitudes HTTP.</td>
      <td>
        <strong>Escenario 1: Integrar un API para manejar las solicitudes HTTP de las publicaciones</strong><br>
        <strong>Given</strong> la aplicación tiene acceso a la documentación de la API y las credenciales necesarias para realizar la integración.
        <br>
        <strong>When</strong> se envía una solicitud de tipo GET, POST o PUT con los datos solicitados del usuario a la API.
        <br>
        <strong>Then</strong> la API responde con un código de estado correspondiente (200 OK o 201 Created).
        <br>
        <strong>And</strong> se realiza la operación solicitada.
        <br><br>
        <strong>Escenario 2: Manejar errores en la Integración de API para Solicitudes HTTP de publicaciones</strong><br>
        <strong>Given</strong> la aplicación tiene acceso a la documentación de la API y las credenciales necesarias para realizar la integración
        <br>
        <strong>When</strong> se envía una solicitud de tipo GET, POST, PUT o DELETE con los datos solicitados de la publicación a la API
        <br>
        <strong>And</strong> ocurre un error.
        <br>
        <strong>Then</strong> la API responde con un código de estado correspondiente al error (400 Bad Request, 401 Unauthorized, 403 Forbidden, 404 Not Found, 500 Internal Server Error).
        <br>
        <strong>And</strong> el sistema proporciona un mensaje de error descriptivo que ayuda al desarrollador a identificar y corregir el problema.
      </td>
      <td>5</td>
    </tr>
    <tr>
      <td>TS06</td>
      <td>Uso de nuestra API para gestionar autenticación</td>
      <td>Como desarrollador quiero integrar un API para gestionar la información de los usuarios en la base de datos, de manera que pueda realizar operaciones CRUD (Crear, Leer, Actualizar, Borrar) a través de solicitudes HTTP.</td>
      <td>
        <strong>Escenario 1: Registro de un nuevo usuario con verificación de seguridad (sign-up)</strong>
        <br>
        <strong>Given</strong> el usuario desea registrarse
        <br>
        <strong>When</strong> el sistema recibe una solicitud POST con los datos del nuevo usuario a la API
        <br>
        <strong>Then</strong> se registrará el nuevo usuario
        <br>
        <strong>And</strong> brindará respuesta a la petición realizada
        <br><br>
        <strong>Escenario 2: Inicio de sesión del usuario con verificación de seguridad exitoso (sign-in)</strong>
        <br>
        <strong>Given</strong> el usuario desea iniciar sesión de forma segura
        <br>
        <strong>When</strong> el sistema recibe una solicitud POST con las credenciales de inicio de sesión del usuario (correo electrónico y contraseña) a la API
        <br>
        <strong>Then</strong> se verificarán las credenciales
        <br>
        <strong>And</strong> la API responde con un código de estado 200 y el token de autenticación válido
        <br><br>
        <strong>Escenario 3: Inicio de sesión del usuario con verificación de seguridad fallido (sign-in)</strong>
        <br>
        <strong>Given</strong> el usuario desea iniciar sesión de forma segura
        <br>
        <strong>When</strong> el sistema recibe una solicitud POST con las credenciales de inicio de sesión del usuario (correo electrónico y contraseña) a la API
        <br>
        <strong>Then</strong> se verificarán las credenciales
        <br>
        <strong>And</strong> la API responde con un código de estado 400 indicando que no se encontró un usuario con las credenciales ingresadas
      </td>
      <td>5</td>
    </tr>
  </tbody>
</table>

### 2.4.3. Impact Mapping

El Impact Mapping es una técnica estratégica que se utiliza para planificar y comunicar cómo un proyecto o producto contribuirá a alcanzar los objetivos de negocio. A través de esta herramienta, se identifican los Business Goals que se desean lograr, las Personas clave que influirán en estos objetivos, los Impacts que se espera de estas personas, y los Deliverables que se desarrollarán para generar esos impactos. Además, se detallan las User Stories que describen cómo los usuarios interactuarán con los entregables para lograr el impacto deseado. De esta manera, el Impact Mapping ayuda a alinear el desarrollo de productos con los objetivos estratégicos, asegurando que cada esfuerzo contribuya directamente al éxito del proyecto.

**Segmento: Granjeros con poca experiencia**

<img alt="Impact Map para Granjero" src="img/impact-mapping-farmer.png">

_Imagen 15: Impact Map para Granjero con poca experiencia_

**Segmento: Asesores experimentados**

<img alt="Impact Map para Asesor" src="img/impact-mapping-advisor.png">

_Imagen 16: Impact Map para Asesor experimentado_

### 2.4.4. Product Backlog

Este Product Backlog presenta una lista priorizada de las User Stories para el desarrollo de nuestra aplicación, estructurada en función de las prioridades del proyecto. El backlog incluye 29 User Stories, organizadas por Epics que abarcan las funcionalidades clave, como la Landing Page, las características de la aplicación y las funcionalidades del Backend. Cada User Story está detallada con una descripción y una estimación de Story Points, facilitando así la planificación y ejecución del desarrollo. La estructura prioriza primero las funcionalidades visibles y esenciales para los usuarios, asegurando que las necesidades más críticas se aborden de manera efectiva y eficiente.

<table>
  <thead>
    <tr>
      <th># Orden</th>
      <th>User Story ID</th>
      <th>Título</th>
      <th>Descripción</th>
      <th>Story Points (1/2/3/5/8)</th>
    </tr>
  </thead>
  <tbody>
  <tr>
         <td>1</td>
         <td>TS03</td>
         <td>Uso de nuestra API para gestionar perfiles</td>
         <td>Desarrollar una API propia que gestione los perfiles de los usuarios, permitiendo actualizar información y configuraciones.</td>
         <td>5</td>
    </tr>
    <tr>
         <td>2</td>
         <td>TS04</td>
         <td>Uso de nuestra API para gestionar asesorías</td>
         <td>Desarrollar y utilizar una API que gestione todas las funcionalidades relacionadas con la programación y manejo de citas de asesoría.</td>
         <td>5</td>
    </tr>
    <tr>
         <td>3</td>
         <td>TS05</td>
         <td>Uso de nuestra API para gestionar publicaciones</td>
         <td>Desarrollar y utilizar una API que gestione todas las funcionalidades relacionadas con información de las publicaciones de los asesores en la base de datos.</td>
         <td>5</td>
    </tr>
    <tr>
         <td>4</td>
         <td>TS06</td>
         <td>Uso de nuestra API para gestionar autenticación</td>
         <td>Desarrollar y utilizar una API que gestione la autenticación y autorización de usuarios en la aplicación.</td>
         <td>5</td>
    </tr>
    <tr>
      <td>5</td>
      <td>US14</td>
      <td>Visualización de la sección de inicio de la Landing Page</td>
      <td>Implementar la visualización de la sección de inicio que presenta la aplicación móvil y sus beneficios.</td>
      <td>2</td>
    </tr>
    <tr>
         <td>6</td>
         <td>US15</td>
         <td>Visualización de la sección 'Acerca de' de la Landing Page</td>
         <td>Mostrar información detallada sobre la misión y visión de la aplicación móvil en la Landing Page.</td>
         <td>2</td>
    </tr>
    <tr>
         <td>7</td>
         <td>US16</td>
         <td>Visualización de la sección 'Sobre Nosotros' de la Landing Page</td>
         <td>Proveer una sección que explique quiénes son los creadores de la aplicación y su historia.</td>
         <td>2</td>
    </tr>
    <tr>
         <td>8</td>
         <td>US17</td>
         <td>Visualización de la sección 'Características' de la Landing Page</td>
         <td>Presentar las características principales de la aplicación de manera clara y atractiva.</td>
         <td>2</td>
    </tr>
    <tr>
         <td>9</td>
         <td>US18</td>
         <td>Visualización de la sección 'Contacto' de la Landing Page</td>
         <td>Permitir a los usuarios potenciales ponerse en contacto con los desarrolladores o soporte técnico.</td>
         <td>2</td>
    </tr>
    <tr>
         <td>10</td>
         <td>US20</td>
         <td>Pantalla de inicio</td>
         <td>Implementar una pantalla de inicio que permita a los usuarios navegar por la aplicación con facilidad.</td>
         <td>2</td>
    </tr>
    <tr>
         <td>11</td>
         <td>US01</td>
         <td>Visualización del catálogo de asesores</td>
         <td>Permitir a los usuarios ver una lista completa de asesores disponibles.</td>
         <td>3</td>
    </tr>
    <tr>
         <td>12</td>
         <td>US02</td>
         <td>Visualización de información de un asesor</td>
         <td>Mostrar detalles sobre un asesor específico, incluyendo su perfil, experiencia y áreas de especialización.</td>
         <td>3</td>
    </tr>
    <tr>
         <td>13</td>
         <td>US03</td>
         <td>Visualización de horarios de asesores</td>
         <td>Permitir a los usuarios ver la disponibilidad de los asesores para programar citas.</td>
         <td>2</td>
    </tr>
    <tr>
         <td>14</td>
         <td>US04</td>
         <td>Programación de citas con asesores</td>
         <td>Implementar la funcionalidad para que los usuarios puedan reservar citas con asesores.</td>
         <td>5</td>
    </tr>
    <tr>
         <td>15</td>
         <td>US05</td>
         <td>Calificación del asesor luego de una cita</td>
         <td>Permitir a los usuarios calificar a los asesores después de una cita.</td>
         <td>3</td>
    </tr>
    <tr>
         <td>16</td>
         <td>US06</td>
         <td>Separación de horarios de disponibilidad para asesorías</td>
         <td>Gestionar y separar los horarios de los asesores según su disponibilidad.</td>
         <td>5</td>
    </tr>
    <tr>
         <td>17</td>
         <td>US10</td>
         <td>Inicio de sesión</td>
         <td>Implementar la funcionalidad de inicio de sesión para usuarios registrados.</td>
         <td>2</td>
    </tr>
    <tr>
         <td>18</td>
         <td>US11</td>
         <td>Recuperación de contraseña</td>
         <td>Permitir a los usuarios recuperar su contraseña en caso de olvido.</td>
         <td>2</td>
    </tr>
    <tr>
         <td>19</td>
         <td>US19</td>
         <td>Recordatorio de Cita</td>
         <td>Enviar recordatorios automáticos a los usuarios sobre sus citas programadas.</td>
         <td>2</td>
    </tr>
    <tr>
         <td>20</td>
         <td>US21</td>
         <td>Visualización de Historial de Citas</td>
         <td>Permitir a los usuarios ver el historial de sus citas pasadas con asesores.</td>
         <td>3</td>
    </tr>
    <tr>
         <td>21</td>
         <td>US22</td>
         <td>Cancelación de Citas</td>
         <td>Permitir a los usuarios cancelar sus citas.</td>
         <td>5</td>
    </tr>
    <tr>
         <td>22</td>
         <td>US23</td>
         <td>Búsqueda y Filtrado de Citas</td>
         <td>Implementar funcionalidades de búsqueda y filtrado para que los usuarios puedan encontrar citas específicas fácilmente.</td>
         <td>3</td>
    </tr>
    <tr>
         <td>23</td>
         <td>TS01</td>
         <td>Uso de una API para videollamadas</td>
         <td>Integrar una API que permita realizar videollamadas dentro de la aplicación.</td>
         <td>5</td>
    </tr>
    <tr>
         <td>24</td>
         <td>TS02</td>
         <td>Uso de una API para alojar imágenes</td>
         <td>Implementar una API que permita a los usuarios subir y almacenar imágenes de manera segura.</td>
         <td>5</td>
    </tr>
    <tr>
         <td>25</td>
         <td>US07</td>
         <td>Gestión de publicaciones de asesores</td>
         <td>Permitir a los asesores crear y gestionar sus publicaciones.</td>
         <td>3</td>
    </tr>
    <tr>
         <td>26</td>
         <td>US08</td>
         <td>Visualización de publicaciones de los asesores</td>
         <td>Permitir a los usuarios ver las publicaciones de los asesores.</td>
         <td>2</td>
    </tr>
    <tr>
         <td>27</td>
         <td>US09</td>
         <td>Registro de un usuario nuevo</td>
         <td>Permitir a nuevos usuarios registrarse en la aplicación.</td>
         <td>3</td>
    </tr>
    <tr>
         <td>28</td>
         <td>US12</td>
         <td>Notificación al usuario</td>
         <td>Enviar notificaciones automáticas a los usuarios sobre actividades importantes.</td>
         <td>2</td>
    </tr>
    <tr>
         <td>29</td>
         <td>US13</td>
         <td>Disponibilidad y confiabilidad</td>
         <td>Asegurar que el sistema sea accesible y confiable para todos los usuarios.</td>
         <td>8</td>
    </tr>

  </tbody>   
</table>

# Capítulo 3: Arquitectura
## 3.1. Product design
### 3.1.1. Style Guidelines
El estilo de nuestro producto jugará un papel fundamental en brindar a nuestros usuarios una experiencia visual que sea tanto satisfactoria como atractiva. A continuación, se proporcionará una descripción detallada más detallada de las características de nuestro proyecto:

El estilo de nuestro producto jugará un papel fundamental en brindar a nuestros usuarios una experiencia visual que sea tanto satisfactoria como atractiva. A continuación, se proporcionará una descripción detallada más detallada de las características de nuestro proyecto:
#### 3.1.1.1. General Style Guidelines
<strong>Consistencia Visual: </strong>Mantener una coherencia visual en todos los aspectos de la aplicación es clave para crear una experiencia intuitiva. Esto incluye el uso de una paleta de colores uniforme que refleje la naturaleza y la vida agrícola, una tipografía legible y tamaños de fuente adecuados para facilitar la lectura en diferentes condiciones de luz.

<p align="center">
  <img alt="Consistencia visual" src="img/consistencia-visual.jpg" width="600">
</p>

_Imagen 17. Imagen de consistencia visual_

<strong>Simplicidad y Claridad: </strong>La interfaz debe ser sencilla y fácil de navegar, con un diseño limpio que evite la sobrecarga de información. El uso de un lenguaje claro y directo es fundamental para asegurar que los usuarios, independientemente de su nivel de experiencia con la tecnología, puedan entender rápidamente cómo utilizar la aplicación.

<p align="center">
  <img alt="Simplicidad y claridad" src="img/simplicidad-y-claridad.jpg" width="600">
</p>

_Imagen 18. Imagen de simplicidad y claridad_

<strong>Accesibilidad: </strong>Diseñar la aplicación teniendo en cuenta las necesidades de accesibilidad, como texto ampliable, contraste de colores para personas con discapacidades visuales, y compatibilidad con tecnologías de asistencia como lectores de pantalla.

<p align="center">
  <img alt="necesidades de accesibilidad de usuarios" src="img/accesibilidad.png" width="600">
</p>

_Imagen 19. Imagen de necesidades de accesibilidad de usuarios_

<strong>Logo: </strong>El logotipo de Agrosupport tiene un diseño circular, simbolizando la conexión y la unidad que queremos fomentar entre las comunidades agrícolas peruanas. En el corazón del círculo, se encuentra una zanahoria estilizada, un elemento visual que no solo representa la vitalidad y el crecimiento, sino también la agricultura sostenible y la importancia de la tierra en la cultura agrícola local.

<p align="center">
  <img alt="Logo" src="img/agrosupport-logo.png" width="600">
</p>

_Imagen 20. Imagen de logo de AgroSupport_

<strong>Tipografía: </strong>La tipografía seleccionada para Agrosupport es "Roboto", una fuente sans-serif moderna y altamente legible. Roboto destaca por su estilo limpio y contemporáneo, transmitiendo profesionalismo y actualización. La elección de Roboto garantiza que el texto en las interfaces de usuario sea fácilmente legible y mantenga una apariencia moderna y uniforme. Además, Roboto es una fuente versátil que ofrece una amplia gama de pesos y estilos, permitiendo una adaptación flexible a diferentes contextos y tamaños de texto en la aplicación.

<p align="center">
  <img alt="Tipografía" src="img/typography.png" width="600">
</p>

_Imagen 21. Imagen de logo de AgroSupport_

<strong>Colores: </strong>Agrosupport ha optado por una paleta de colores que proyecta confiabilidad y eficiencia, ideal para la contratación de asesores especializados y el uso de herramientas avanzadas. Los tonos predominantes, como el naranja, el verde y el marrón, evocan una sensación cálida que refleja la vitalidad y la energía de la naturaleza en las granjas peruanas. Esta selección de colores no solo subraya la conexión con la tierra y las raíces agrícolas, sino que también crea un ambiente acogedor y estimulante para los usuarios de la plataforma.

<p align="center">
  <img alt="Paleta de colores" src="img/colors.png" width="600">
</p>

_Imagen 22. Imagen de logo de AgroSupport_
 

### 3.1.2. Information Architecture
La arquitectura de información es esencial para organizar y estructurar el contenido en una aplicación móvil, garantizando su accesibilidad y comprensión por parte de los usuarios. A continuación, se describen los sistemas de organización, etiquetado, SEO, búsqueda y navegación específicos para Agrosupport.

#### 3.1.2.1. Organization Systems
En Agrosupport, utilizamos un sistema de jerarquía visual adaptado a la interfaz móvil para resaltar la información clave y permitir a los usuarios encontrar fácilmente lo que necesitan. La organización secuencial en la aplicación guía a los usuarios a través del proceso de búsqueda y contacto con asesores. La categorización del contenido se realiza en función de la audiencia principal: Granjeros y Asesores.

#### 3.1.2.2. Labelling Systems

Para Agrosupport, hemos desarrollado un sistema de etiquetado claro y conciso para facilitar la navegación en la aplicación móvil. Las etiquetas utilizadas son:

**Vista de Granjero:**

<table>
  <tbody>
  <tr>
      <th>Advisors - Asesores</th>
      <td>Se implementará un botón que permitirá a los usuarios contactar con asesores.</td>
  </tr>
  <tr>
      <th>Appointments - Citas</th>
      <td>Se implementará un botón que permitirá visualizar la información de las citas registradas.</td>
  </tr>
  <tr>
      <th>Profile - Perfil</th>
      <td>Se implementará un botón que permitirá al usuario visualizar y editar su perfil.</td>
  </tr>
  <tr>
      <th>Logout</th>
      <td>Se implementará un botón que permitirá al usuario desvincularse de su cuenta.</td>
  </tr>
  </tbody>
</table>

**Vista de Asesor:**

<table>
  <tbody>
  <tr>
      <th>Home - Inicio</th>
      <td>Se implementará un botón que permitirá al usuario ver publicaciones de clientes y poder ofertar.</td>
  </tr>
  <tr>
      <th>Appointments - Citas</th>
      <td>Se implementará un botón que permitirá visualizar la información de las citas registradas.</td>
  </tr>
  <tr>
      <th>My publications - Mis publicaciones</th>
      <td>Se implementará un botón que permitirá al usuario ver el historial de sus publicaciones de ofertas de trabajo.</td>
  </tr>
  <tr>
      <th>Profile - Perfil</th>
      <td>Se implementará un botón que permitirá al usuario visualizar y editar su perfil.</td>
  </tr>
  <tr>
      <th>Logout</th>
      <td>Se implementará un botón que permitirá al usuario desvincularse de su cuenta.</td>
  </tr>
  </tbody>
</table>

#### 3.1.2.3. SEO Tags and Meta Tags
Para mejorar la visibilidad y el rendimiento de Agrosupport en motores de búsqueda y en las tiendas de aplicaciones, se han implementado las siguientes etiquetas SEO y metaetiquetas:

<strong>Metaetiqueta de Descripción: </strong>Proporciona una breve descripción del contenido y propósito de la aplicación, ayudando a los usuarios a entender de qué se trata la aplicación y a mejorar la tasa de clics.

````
<meta name="description" content="AgroSupport is a platform that provides farmers with the necessary information to improve their farming practices.">
````


<strong>Metaetiqueta de Autor: </strong>Especifica el autor de la aplicación, lo que ayuda a atribuir la propiedad intelectual y la fuente del contenido.

````
<meta name="author" content="AgroTech">
````
<strong>Metaetiqueta de Robots: </strong>Indica a los motores de búsqueda cómo deben indexar y rastrear la página, permitiendo que se indexe y que se sigan los enlaces en la aplicación.

````
<meta name="robots" content="index, follow">
````


<strong>Etiqueta de Título: </strong> Define el título de la aplicación que aparece en los resultados de búsqueda y en las pestañas del navegador.

````
<title>AgroSupport</title>
````

<strong>Etiqueta de Idioma: </strong> Especifica el idioma principal del contenido de la aplicación para ayudar a los motores de búsqueda a entender y clasificar el contenido adecuadamente.

````
<html lang="en">
````

<p align="center">
  <img src="img/seoTAGS.png" alt="SEO tags" width="600">
</p>

_Imagen 23. Imagen de logo SEO TAGS_


#### 3.1.2.4. Searching Systems

La aplicación AgroSupport desarrollará un sistema de búsqueda intuitivo, diseñado para que los usuarios encuentren rápidamente la información que necesitan. Este sistema se basará en filtros inteligentes que simplificarán la búsqueda de asesores, evitando así que los usuarios se vean abrumados por la cantidad de información disponible. Con esta mejora, nuestra aplicación garantizará una experiencia de usuario más fluida y satisfactoria al buscar información relevante.

<table>
  <tbody>
  <tr>
      <th>Ubicación</th>
      <td>Permite al usuario buscar asesores o recibir solicitudes de asesoramiento basadas en su ubicación actual o en una ubicación específica.</td>
  </tr>
  <tr>
      <th>Nombre</th>
      <td>Permite al usuario buscar según el nombre del asesor.</td>
  </tr>
  <tr>
      <th>Experiencia</th>
      <td>Permite al usuario buscar asesores con un nivel de experiencia específico.</td>
  </tr>
  <tr>
      <th>Calificación</th>
      <td>Permite al usuario buscar asesores según las calificaciones obtenidas.</td>
  </tr> 
  <tr>
      <th>Palabras Clave</th>
      <td>Proporciona un cuadro de búsqueda donde los usuarios pueden ingresar palabras clave específicas relacionadas con el tipo de asesoría que necesitan.</td>
  </tr>
  </tbody>
</table>


#### 3.1.2.5. Navigation Systems

La interfaz móvil de Agrosupport está diseñada para una navegación eficiente, con características adaptadas a la usabilidad en pantallas táctiles:

 - ***Menús de Navegación:*** Menús adaptados para dispositivos móviles, que pueden incluir menús desplegables, botones en la parte superior o inferior de la pantalla, y accesos directos en la barra lateral.

 - ***Navegación por Pestañas:*** Utiliza pestañas en la parte superior o inferior de la pantalla para organizar el contenido en secciones o categorías, permitiendo a los usuarios cambiar entre diferentes secciones sin necesidad de cargar nuevas pantallas.

### 3.1.3. Landing Page UI Design
#### 3.1.3.1. Landing Page Wireframe

Los wireframes son el esquema básico de la Landing page, mostrando la estructura principal y la disposición de los elementos. Aquí se detallan las secciones clave como el encabezado, el área de beneficios, las llamadas a la acción y la ubicación de imágenes, enfocándose en la usabilidad y el flujo de la página sin distracciones visuales.


**Página de inicio**

<img src="img/wireframe-inicio.png" alt="Wireframe - Inicio">

_Imagen 24. Wireframe de la página de inicio_


**Página de inicio (versión móvil)**

<img src="img/wireframe-inicio-mobile.png" alt="Wireframe - Inicio (móvil)">

_Imagen 25. Wireframe de la página de inicio (móvil)_


**Página de Problemática**

<img src="img/wireframe-problematica.png" alt="Wireframe - Problemática">

_Imagen 26. Wireframe de la página de Problemática_


**Página de Problemática (versión móvil)**

<img src="img/wireframe-problematica-mobile.png" alt="Wireframe - Problemática (móvil)">

_Imagen 27. Wireframe de la página de Problemática (móvil)_


**Página de Características**

<img src="img/wireframe-caracteristicas.png" alt="Wireframe - Características">

_Imagen 28. Wireframe de la página de Características_


**Página de Características (versión móvil)**

<img src="img/wireframe-caracteristicas-mobile.png" alt="Wireframe - Características (móvil)">

_Imagen 29. Wireframe de la página de Características (móvil)_


**Página de Sobre Nosotros**

<img src="img/wireframe-nosotros.png" alt="Wireframe - Nosotros">

_Imagen 30. Wireframe de la página de Sobre Nosotros_


**Página de Sobre Nosotros (versión móvil)**

<img src="img/wireframe-nosotros-mobile.png" alt="Wireframe - Nosotros (móvil)">

_Imagen 31. Wireframe de la página de Sobre Nosotros (móvil)_


**Página de Contacto**

<img src="img/wireframe-contacto.png" alt="Wireframe - Contacto">

_Imagen 32. Wireframe de la página de Contacto_


**Página de Contacto (versión móvil)**

<img src="img/wireframe-contacto-mobile.png" alt="Wireframe - Contacto (móvil)">

_Imagen 33. Wireframe de la página de Contacto (móvil)_


#### 3.1.3.2. Landing Page Mock-up

Los mockups añaden detalles visuales y de diseño a los wireframes, mostrando la paleta de colores, tipografía y estilo gráfico que tendrá la landing page. Representan cómo se verá la página final, integrando los elementos visuales que harán la experiencia más atractiva y coherente con la marca.

**Página de inicio**

<img src="img/mockup-inicio.png" alt="Mock-up - Inicio">

_Imagen 34. Mock-up de la página de inicio_


**Página de inicio (versión móvil)**

<img src="img/mockup-inicio-mobile.png" alt="Mock-up - Inicio (móvil)">

_Imagen 35. Mock-up de la página de inicio (móvil)_


**Página de Problemática**

<img src="img/mockup-problematica.png" alt="Mock-up - Problemática">

_Imagen 36. Mock-up de la página de Problemática_


**Página de Problemática (versión móvil)**

<img src="img/mockup-problematica-mobile.png" alt="Mock-up - Problemática (móvil)">

_Imagen 37. Mock-up de la página de Problemática (móvil)_


**Página de Características**

<img src="img/mockup-caracteristicas.png" alt="Mock-up - Características">

_Imagen 38. Mock-up de la página de Características_


**Página de Características (versión móvil)**

<img src="img/mockup-caracteristicas-mobile.png" alt="Mock-up - Características (móvil)">

_Imagen 39. Mock-up de la página de Características (móvil)_


**Página de Sobre Nosotros**

<img src="img/mockup-nosotros.png" alt="Mock-up - Nosotros">

_Imagen 40. Mock-up de la página de Sobre Nosotros_


**Página de Sobre Nosotros (versión móvil)**

<img src="img/mockup-nosotros-mobile.png" alt="Mock-up - Nosotros (móvil)">

_Imagen 41. Mock-up de la página de Sobre Nosotros (móvil)_


**Página de Contacto**

<img src="img/mockup-contacto.png" alt="Mock-up - Contacto">

_Imagen 42. Mock-up de la página de Contacto_


**Página de Contacto (versión móvil)**

<img src="img/mockup-contacto-mobile.png" alt="Mock-up - Contacto (móvil)">

_Imagen 43. Mock-up de la página de Contacto (móvil)_

### 3.1.4. Mobile Applications UX/UI Design

#### 3.1.4.1. Mobile Applications Wireframes

Los wireframes de la app móvil muestran el diseño básico de cada pantalla, enfocándose en la organización de elementos y funciones clave, asegurando una navegación intuitiva y sencilla para el usuario.

<a href="https://www.figma.com/design/28qWSJQGZxkutQKmfUcLb0/Moviles-TB2?node-id=1-2&node-type=CANVAS&t=wIJNUS0aMNwb6bGF-0">Enlace a Wireframes en Figma</a>

**Para Granjeros Inexpertos**

<img src="img/wireframe-bienvenida.png" alt="Wireframe de la aplicación bienvenida">

_Imagen 44. Wireframe de bienvenida_

<img src="img/wireframe-inicio-sesion.png" alt="Wireframe de inicio de sesión">

_Imagen 45. Wireframe de inicio de sesión_

<img src="img/wireframe-crear-cuenta.png" alt="Wireframe de creación de cuenta de granjeros">

_Imagen 46. Wireframe de creación de cuenta de granjeros inexpertos_

<img src="img/wireframe-cuenta-granjero.png" alt="Wireframe de creación de cuenta de granjeros">

_Imagen 47. Wireframe de creación de cuenta de granjeros inexpertos_

<img src="img/wireframe-cuenta-granjero-perfil.png" alt="Wireframe de crear cuenta de granjeros">

_Imagen 48. Wireframe de creación de perfil de granjeros inexpertos_

<img src="img/wireframe-cuenta-creada-granjero.png" alt="Wireframe de cuenta creada de granjeros inexpertos">

_Imagen 49. Wireframe de cuenta creada de granjeros inexpertos_

<img src="img/wireframe-olvidar-contraseña.png" alt="Wireframe de olvidar contraseña">

_Imagen 50. Wireframe de olvidar contraseña_

<img src="img/wireframe-restablecer-contraseña.png" alt="Wireframe de restablecer contraseña">

_Imagen 51. Wireframe de restablecer contraseña_

<img src="img/wireframe-contraseña-restablecida.png" alt="Wireframe de contraseña restablecida">

_Imagen 52. Wireframe de contraseña restablecida_

<img src="img/wireframe-home-granjeros.png" alt="Wireframe de inicio de granjeros inexpertos">

_Imagen 53. Wireframe de inicio de granjeros inexpertos_

<img src="img/wireframe-lista-asesores.png" alt="Wireframe de lista de asesores experimentados">

_Imagen 54. Wireframe de lista de asesores experimentados_

<img src="img/wireframe-perfil-asesor-granjero.png" alt="Wireframe del perfil del asesor experimentado">

_Imagen 55. Wireframe del perfil del asesor experimentado_

<img src="img/wireframe-calificacion-asesor.png" alt="Wireframe de reseñas del asesor">

_Imagen 56. Wireframe de reseñas del asesor experimentado_

<img src="img/wireframe-agendar-cita.png" alt="Wireframe de agendar cita con asesor experimentado">

_Imagen 57. Wireframe de agendar cita con asesor experimentado_

<img src="img/wireframe-cita-agendada.png" alt="Wireframe de cita agendada con asesor experimentado">

_Imagen 58. Wireframe de cita agendada con asesor experimentado_

<img src="img/wireframe-menu.png" alt="Wireframe de menú">

_Imagen 59. Wireframe de menú_

<img src="img/wireframe-perfil-granjeros.png" alt="Wireframe de perfil del granjero inexperto">

_Imagen 60. Wireframe de perfil de granjeros inexpertos_

<img src="img/wireframe-lista-citas-granjeros.png" alt="Wireframe de lista de citas de granjeros inexpertos">

_Imagen 61. Wireframe de lista de citas de granjeros inexpertos_

<img src="img/wireframe-historial-citas-granjeros.png" alt="Wireframe de historial de citas de granjeros inexpertos">

_Imagen 62. Wireframe de historial de citas de granjeros inexpertos_

<img src="img/wireframe-detalle-cita-granjeros.png" alt="Wireframe de detalles de la cita de granjeros inexpertos">

_Imagen 63. Wireframe de detalles de la cita de granjeros inexpertos_

<img src="img/wireframe-califcacion-granjero.png" alt="Wireframe de calificación de asesor de granjeros inexpertos">

_Imagen 64. Wireframe de calificación de asesor de granjeros inexpertos_

<img src="img/wireframe-cancelar-cita-granjero.png" alt="Wireframe de cancelación de cita de granjeros inexpertos">

_Imagen 65. Wireframe de cancelación de cita de granjeros inexpertos_

<img src="img/wireframe-cita-cancelada-granjero.png" alt="Wireframe de cita cancelada de granjeros inexpertos">

_Imagen 66. Wireframe de cita cancelada de granjeros inexpertos_

<img src="img/wireframe-publicaciones-granjero.png" alt="Wireframe de publicaciones de asesores de granjeros inexpertos">

_Imagen 67. Wireframe de publicaciones de asesores de granjeros inexpertos_

<img src="img/wireframe-publicacion-asesor-granjero.png" alt="Wireframe de publicación de un asesor de granjeros inexpertos">

_Imagen 68. Wireframe de publicación de un asesor de granjeros inexpertos_


**Para Asesores Experimentados**

<img src="img/wireframe-crear-cuenta-asesor.png" alt="Wireframe de creación de cuenta de asesores">

_Imagen 69. Wireframe de creación de cuenta de asesores experimentados_

<img src="img/wireframe-cuenta-creada-asesor.png" alt="Wireframe de cuenta creada de asesor">

_Imagen 70. Wireframe de cuenta creada de asesores experimentados_

<img src="img/wireframe-home-asesores.png" alt="Wireframe de inicio de asesores">

_Imagen 71. Wireframe de inicio de asesores experimentados_

<img src="img/wireframe-publicaciones-asesores.png" alt="Wireframe de publicaciones de asesores">

_Imagen 72. Wireframe de mis publicaciones de asesores experimentados_

<img src="img/wireframe-crear-publicacion-asesor.png" alt="Wireframe de creación de publicación de asesores">

_Imagen 73. Wireframe de creación de publicaciones de asesores experimentados_

<img src="img/wireframe-editar-publicacion.png" alt="Wireframe de edición de publicación de asesores">

_Imagen 74. Wireframe de edición de publicación de asesores experimentados_

<img src="img/wireframe-menu-publicaciones.png" alt="Wireframe de menú de publicaciones">

_Imagen 75. Wireframe de menú de publicaciones_

<img src="img/wireframe-lista-citas-asesor.png" alt="Wireframe de lista de citas de asesores">

_Imagen 76. Wireframe de lista de citas de asesores experimentados_

<img src="img/wireframe-historial-citas-asesor.png" alt="Wireframe de historial de citas de asesores">

_Imagen 77. Wireframe de historial de citas de asesores experimentados_

<img src="img/wireframe-detalle-cita-asesor-asesor.png" alt="Wireframe de detalle de la cita de asesores">

_Imagen 78. Wireframe de detalle de la cita de asesores experimentados_

<img src="img/wireframe-detalle-cita-pasada-asesor.png" alt="Wireframe de cita pasada de asesores">

_Imagen 79. Wireframe de cita pasada de asesores experimentados_

<img src="img/wireframe-vista-publicacion-asesor.png" alt="Wireframe de vista de publicaciones pasada de asesores">

_Imagen 80. Wireframe de vista de publicaciones pasada de asesores_

<img src="img/wireframe-detalle-cita-asesor.png" alt="Wireframe de detalle de cita de asesores">

_Imagen 81. WWireframe de detalle de cita de asesores experimentados_

#### 3.1.4.2. Mobile Applications Wireflow Diagrams

Los wireflow diagrams combinan los wireframes con el flujo de interacción entre pantallas, visualizando cómo los usuarios navegarán a través de la app y resaltando las decisiones y acciones posibles en cada paso.

<a href="https://www.figma.com/design/28qWSJQGZxkutQKmfUcLb0/Moviles-TB2?node-id=1-4&node-type=CANVAS&t=wIJNUS0aMNwb6bGF-0">Enlace a Wireflow Diagrams en Figma</a>

*Para Granjeros Inexpertos**

<img src="img/wireflow-1.png" alt="Wireflow 1">

_Imagen 82. Wireflow Goal 1 - Granjeros_

<img src="img/wireflow-2.png" alt="Wireflow 2">

_Imagen 83. Wireflow Goal 2 - Granjeros_

<img src="img/wireflow-3.png" alt="Wireflow 3">

_Imagen 84. Wireflow Goal 3 - Granjeros_

<img src="img/wireflow-4.png" alt="Wireflow 4">

_Imagen 85. Wireflow Goal 4 - Granjeros_

<img src="img/wireflow-5.png" alt="Wireflow 5">

_Imagen 86. Wireflow Goal 5 - Granjeros_

<img src="img/wireflow-6.png" alt="Wireflow 6">

_Imagen 87. Wireflow Goal 6 - Granjeros_

<img src="img/wireflow-7.png" alt="Wireflow 7">

_Imagen 88. Wireflow Goal 7 - Granjeros_

<img src="img/wireflow-8.png" alt="Wireflow 8">

_Imagen 89. Wireflow Goal 8 - Granjeros_

<img src="img/wireflow-9.png" alt="Wireflow 9">

_Imagen 90. Wireflow Goal 9 - Granjeros_

<img src="img/wireflow-10.png" alt="Wireflow 10">

_Imagen 91. Wireflow Goal 10 - Granjeros_

<img src="img/wireflow-11.png" alt="Wireflow 11">

_Imagen 92. Wireflow Goal 11 - Granjeros_

**Para Asesores Experimentados**

<img src="img/wireflow-12.png" alt="Wireflow 12">

_Imagen 93. Wireflow Goal 12 - Asesores_

<img src="img/wireflow-13.png" alt="Wireflow 13">

_Imagen 94. Wireflow Goal 13 - Asesores_

<img src="img/wireflow-14.png" alt="Wireflow 14">

_Imagen 95. Wireflow Goal 14 - Asesores_

<img src="img/wireflow-15.png" alt="Wireflow 15">

_Imagen 96. Wireflow Goal 15 - Asesores_

<img src="img/wireflow-16.png" alt="Wireflow 16">

_Imagen 97. Wireflow Goal 16 - Asesores_

<img src="img/wireflow-17.png" alt="Wireflow 17">

_Imagen 98. Wireflow Goal 17 - Asesores_
 
<img src="img/wireflow-18.png" alt="Wireflow 18">

_Imagen 99. Wireflow Goal 18 - Asesores_

<img src="img/wireflow-19.png" alt="Wireflow 19">

_Imagen 100. Wireflow Goal 19 - Asesores_

<img src="img/wireflow-20.png" alt="Wireflow 20">

_Imagen 101. Wireflow Goal 20 - Asesores_

#### 3.1.4.3. Mobile Applications Mock-ups

Los mockups de la app aportan estilo visual y detalles gráficos, mostrando cómo lucirán las pantallas finales con colores, tipografías y elementos visuales que crean una experiencia atractiva y alineada con la identidad de la app.

<a href="https://www.figma.com/design/28qWSJQGZxkutQKmfUcLb0/Moviles-TB2?node-id=1-3&node-type=CANVAS&t=wIJNUS0aMNwb6bGF-0">Enlace a Mock-ups en Figma</a>

**Para Granjeros Inexpertos**

<img src="img/mock-up-bienvenida.png" alt="Mock Up bienvenida">

_Imagen 102. Mock Up de bienvenida_

<img src="img/mock-up-olvidar-contraseña.png" alt="Mock Up olvidar contraseña">

_Imagen 103. Mock Up de olvidar contraseña_

<img src="img/mock-up-restablecer-contraseña.png" alt="Mock Up restablecer contraseña">

_Imagen 104. Mock Up de restablecer contraseña_

<img src="img/mock-up-contraseña-restablecida.png" alt="Mock Up contraseña restablecida">

_Imagen 105. Mock Up de contraseña restablecida_

<img src="img/mock-up-rol.png" alt="Mock Up selección de rol">

_Imagen 106. Mock Up de selección de rol_

<img src="img/mock-up-crear-cuenta-granjero.png" alt="Mock Up creación de cuenta de granjero">

_Imagen 107. Mock Up de creación de cuenta de granjero_

<img src="img/mock-up-crear-cuenta-granjero.png" alt="Mock Up creación de cuenta de granjero">

_Imagen 108. Mock Up de creación de cuenta de granjero_

<img src="img/mock-up-cuenta-creada-granjero.png" alt="Mock Up cuenta creada de granjero">

_Imagen 109. Mock Up de cuenta creada de granjero_

<img src="img/mock-up-home-granjero.png" alt="Mock Up inicio granjero">

_Imagen 110. Mock Up de inicio de granjero_

<img src="img/mock-up-lista-asesores-granjero.png" alt="Mock Up lista de asesores">

_Imagen 111. Mock Up de lista de asesores_

<img src="img/mock-up-perfil-asesor-granjero.png" alt="Mock Up perfil del asesor">

_Imagen 112. Mock Up de perfil del asesor_

<img src="img/mock-up-reseñas-asesor-granjero.png" alt="Mock Up reseñas del asesor">

_Imagen 113. Mock Up de reseñas del asesor_

<img src="img/mock-up-agendar-cita-granjero.png" alt="Mock Up agendar cita con asesor">

_Imagen 114. Mock Up de agendar cita con asesor_

<img src="img/mock-up-cita-agendada.png" alt="Mock Up cita agendada">

_Imagen 115. Mock Up de cita agendada_

<img src="img/mock-up-menu.png" alt="Mock Up menú principal">

_Imagen 116. Mock Up de menú principal_

<img src="img/mock-up-editar-perfil-granjero.png" alt="Mock Up editar perfil de granjero">

_Imagen 117. Mock Up de editar perfil de granjero_

<img src="img/mock-up-lista-citas-granjero.png" alt="Mock Up lista de citas de granjero">

_Imagen 118. Mock Up de lista de citas de granjero_

<img src="img/mock-up-historial-citas-granjero.png" alt="Mock Up historial de citas de granjero">

_Imagen 119. Mock Up de historial de citas de granjero_

<img src="img/mock-up-detalle-cita-granjero.png" alt="Mock Up detalle de la cita de granjero">

_Imagen 120. Mock Up de detalle de la cita de granjero_

<img src="img/mock-up-califcacion-granjero.png" alt="Mock Up calificación de asesor por granjero">

_Imagen 121. Mock Up de calificación de asesor por granjero_

<img src="img/mock-up-cancelar-cita-granjero.png" alt="Mock Up cancelación de cita de granjero">

_Imagen 122. Mock Up de cancelación de cita de granjero_

<img src="img/mock-up-cita-cancelada-granjero.png" alt="Mock Up cita cancelada de granjero">

_Imagen 123. Mock Up de cita cancelada de granjero_

<img src="img/mock-up-publicaciones-granjero.png" alt="Mock Up publicaciones de granjero">

_Imagen 124. Mock Up de publicaciones de granjero_

<img src="img/mock-up-publicaciones-asesor-granjero.png" alt="Mock Up publicaciones de asesor para granjero">

_Imagen 125. Mock Up de publicaciones de asesor para granjero_

**Para Asesores Experimentados**

<img src="img/mock-up-crear-perfil-asesor.png" alt="Mock Up creación de perfil asesor">

_Imagen 126. Mock Up de creación de perfil de asesor_

<img src="img/mock-up-cuenta-creada-asesor.png" alt="Mock Up cuenta creada asesor">

_Imagen 127. Mock Up de cuenta creada de asesor_

<img src="img/mock-up-home-asesor.png" alt="Mock Up inicio asesor">

_Imagen 128. Mock Up de inicio de asesor_

<img src="img/mock-up-publicaciones-asesor.png" alt="Mock Up publicaciones asesor">

_Imagen 129. Mock Up de publicaciones de asesor_

<img src="img/mock-up-crear-publicacion-asesor.png" alt="Mock Up crear publicación asesor">

_Imagen 130. Mock Up de crear publicación de asesor_

<img src="img/mock-up-vista-publicacion-asesor.png" alt="Mock Up vista de publicación asesor">

_Imagen 131. Mock Up de vista de publicación de asesor_

<img src="img/mock-up-editar-publicacion.png" alt="Mock Up edición de publicación asesor">

_Imagen 132. Mock Up de edición de publicación de asesor_

<img src="img/mock-up-menu-publicaciones.png" alt="Mock Up menú de publicaciones asesor">

_Imagen 133. Mock Up de menú de publicaciones de asesor_

<img src="img/mock-up-notificaciones-asesor.png" alt="Mock Up notificaciones asesor">

_Imagen 134. Mock Up de notificaciones de asesor_

<img src="img/mock-up-lista-citas-asesor.png" alt="Mock Up lista de citas asesor">

_Imagen 135. Mock Up de lista de citas de asesor_

<img src="img/mock-up-historial-citas-asesor.png" alt="Mock Up historial de citas asesor">

_Imagen 136. Mock Up de historial de citas de asesor_

<img src="img/mock-up-detalle-cita-asesor.png" alt="Mock Up detalle de cita asesor">

_Imagen 137. Mock Up de detalle de cita de asesor_

<img src="img/mock-up-detalle-cita-pasada-asesor.png" alt="Mock Up detalle de cita pasada asesor">

_Imagen 138. Mock Up de detalle de cita pasada de asesor_

<img src="img/mock-up-detalle-cita-califcacion-asesor.png" alt="Mock Up detalle de cita con calificación asesor">

_Imagen 139. Mock Up de detalle de cita con calificación de asesor_

<img src="img/mock-up-editar-perfil-asesor.png" alt="Mock Up editar perfil asesor">

_Imagen 140. Mock Up de editar perfil de asesor_

#### 3.1.4.4. Mobile Applications User Flow Diagrams

Los user flow diagrams ilustran el recorrido completo del usuario dentro de la app, desde el inicio hasta el logro de sus objetivos, ayudando a entender los pasos y decisiones clave que se tomarán en cada interacción.

<a href="https://www.figma.com/design/28qWSJQGZxkutQKmfUcLb0/Moviles-TB2?node-id=1-5&node-type=CANVAS&t=wIJNUS0aMNwb6bGF-0">Enlace a User Flow Diagrams en Figma</a>

**Para Granjeros Inexpertos**

<img src="img/userflow-1.png" alt="UserFlow 1">

_Imagen 141. UserFlow 1 - Granjeros_

<img src="img/userflow-2.png" alt="UserFlow 2">

_Imagen 142. UserFlow 2 - Granjeros_

<img src="img/userflow-3.png" alt="UserFlow 3">

_Imagen 143. UserFlow 3 - Granjeros_

<img src="img/userflow-4.png" alt="UserFlow 4">

_Imagen 144. UserFlow 4 - Granjeros_

<img src="img/userflow-5.png" alt="UserFlow 5">

_Imagen 145. UserFlow 5 - Granjeros_

<img src="img/userflow-6.png" alt="UserFlow 6">

_Imagen 146. UserFlow 6 - Granjeros_

<img src="img/userflow-7.png" alt="UserFlow 7">

_Imagen 147. UserFlow 7 - Granjeros_

<img src="img/userflow-8.png" alt="UserFlow 8">

_Imagen 148. UserFlow 8 - Granjeros_

<img src="img/userflow-9.png" alt="UserFlow 9">

_Imagen 149. UserFlow 9 - Granjeros_

<img src="img/userflow-10.png" alt="UserFlow 10">

_Imagen 150. UserFlow 10 - Granjeros_

<img src="img/userflow-11.png" alt="UserFlow 11">

_Imagen 151. UserFlow 11 - Granjeros_

**Para Asesores Experimentados**

<img src="img/userflow-12.png" alt="UserFlow 12">

_Imagen 152. UserFlow 1 - Asesores_

<img src="img/userflow-13.png" alt="UserFlow 13">

_Imagen 153. UserFlow 2 - Asesores_

<img src="img/userflow-14.png" alt="UserFlow 14">

_Imagen 154. UserFlow 3 - Asesores_

<img src="img/userflow-15.png" alt="UserFlow 15">

_Imagen 155. UserFlow 4 - Asesores_

<img src="img/userflow-16.png" alt="UserFlow 16">

_Imagen 156. UserFlow 5 - Asesores_

<img src="img/userflow-17.png" alt="UserFlow 17">

_Imagen 157. UserFlow 6 - Asesores_

<img src="img/userflow-18.png" alt="UserFlow 18">

_Imagen 158. UserFlow 7 - Asesores_

<img src="img/userflow-19.png" alt="UserFlow 19">

_Imagen 159. UserFlow 8 - Asesores_

<img src="img/userflow-20.png" alt="UserFlow 20">

_Imagen 160. UserFlow 9 - Asesores_

#### 3.1.4.5. Mobile Applications Prototyping

El prototipo de interacción real permite simular la navegación y las funciones de la app tal como las experimentará el usuario final. Ofrece una representación interactiva del flujo entre pantallas, mostrando cómo responderán los elementos y mejorando la usabilidad antes de la fase de desarrollo.

<a href="https://www.figma.com/proto/28qWSJQGZxkutQKmfUcLb0/Moviles-TB2?node-id=130-3269&node-type=CANVAS&t=yNMsjSd7gEHbZG3y-1&scaling=min-zoom&content-scaling=fixed&page-id=1%3A5">Enlace a Prototipo en Figma</a>

Igualmente, se realizó un video de explicación mostrando la interacción con los elementos para mostrar como se comporta la aplicación en un dispositivo móvil.

<a href="https://youtu.be/z36rb1-5HoQ">Enlace a video</a>

<img src="img/prototyping.png" alt="Captura de video de prototipo">

_Imagen 161. Captura de video de prototipo_


## 3.2. Architecture Overview
### 3.2.1. Domain-Driven Software Architecture
#### 3.2.1.1. Software Architecture Context Level Diagram

El diagrama de contexto representa la estructura y las principales interacciones de un sistema de software. En nuestro proyecto, este diagrama muestra las interacciones clave entre la aplicación, los usuarios (granjeros y asesores) y los sistemas externos (servicio de videoconferencias y servicio de almacenamiento).

<img alt="Diagrama de Contexto - AgroSupport" src="img/C4-Contexto.png">

_Imagen 162. Diagrama de Contexto de AgroSupport_

#### 3.2.1.2. Software Architecture Container Level Diagram

El diagrama de contenedores ofrece una visión detallada de la arquitectura del sistema, desglosandolo en sus principales contenedores y mostrando cómo interactúan entre sí. En el contexto de nuestro proyecto, este diagrama ilustra los diferentes componentes que componen la aplicación, tales como la aplicación móvil, la landing page, el API Rest y la base de datos.

<img alt="Diagrama de Contenedores - AgroSupport" src="img/C4-Contenedor.png">

_Imagen 163. Diagrama de Contexto de AgroSupport_

#### 3.2.1.3. Software Architecture Components Diagram

El diagrama de componentes detalla la arquitectura de los componentes del sistema. En nuestro caso, el componente principal es el API REST que se descompone en otros 3 componentes: Profile, Appointment y Publishing.

<img alt="Diagrama de Componentes: API REST" src="img/C4-API_Rest_Component_Diagram.png">

_Imagen 164. Diagrama de Componentes: API REST_

<img alt="Diagrama de Componentes: Profile" src="img/C4-ProfileComponentDiagram.png">

_Imagen 165. Diagrama de Componentes: Profile_

<img alt="Diagrama de Componentes: Appointment" src="img/C4-AppointmentComponentDiagram.png">

_Imagen 166. Diagrama de Componentes: Appointment_

<img alt="Diagrama de Componentes: Publication" src="img/C4-PublicationComponentDiagram.png">

_Imagen 167. Diagrama de Componentes: Publication_

### 3.2.2. Software Object-Oriented Design
#### 3.2.2.1. Class Diagrams

Los diagramas de clase son herramientas cruciales en el diseño de sistemas orientados a objetos, ya que proporcionan una representación visual de las clases y sus relaciones dentro del sistema. En esta sección, se presentarán los diagramas de clase que detallan la estructura de cada bounded context: Profile, Appointment y Publication.


<img alt="Diagrama de Clase: Profile" src="img/ClassDiagram_Profile.png">

_Imagen 168. Diagrama de Clase: Profile_

<img alt="Diagrama de Clase: Appointment" src="img/ClassDiagram_Appointment.png">

_Imagen 169. Diagrama de Clase: Appointment_

<img alt="Diagrama de Clase: Publication" src="img/ClassDiagram_Publication.png">

_Imagen 170. Diagrama de Clase: Publication_

#### 3.2.2.2. Class Dictionary

En esta sección, se especificarán las características detalladas de cada clase del sistema mediante un diccionario de clases. A continuación se presenta una tabla con las clases y una descripción sobre sus atributos, métodos y una breve descripción de cada una.

<table>
    <thead>
        <tr>
            <th>Clase</th>
            <th>Descripción</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>User</td>
            <td>Representa un usuario del sistema. Incluye atributos como <em>id</em>, <em>username</em>, <em>password</em>, un <em>profile</em> asociado, un <em>role</em>, y una lista de <em>notifications</em>. Métodos principales: <em>getUser()</em>, <em>getNotifications()</em>.</td>
        </tr>
        <tr>
            <td>Farmer</td>
            <td>Representa a los usuarios del sector de granjero inexperto. Hereda de la clase <em>User</em>. Incluye un <em>user</em> asociado. Método principal: <em>getFarmer()</em>.</td>
        </tr>
        <tr>
            <td>Advisor</td>
            <td>Representa a los usuarios del sector de asesores especializados. Incluye atributos como <em>id</em>, <em>rating</em>, y un <em>user</em> asociado. Método principal: <em>getAdvisor()</em>.</td>
        </tr>
        <tr>
            <td>Profile</td>
            <td>Contiene la información detallada del usuario, incluyendo atributos como <em>firstname</em>, <em>lastname</em>, <em>city</em>, <em>country</em>, <em>birthdate</em>, <em>description</em>, <em>photo</em>, <em>occupation</em>, <em>experience</em>, y un <em>user</em> asociado. Método principal: <em>getProfile()</em>.</td>
        </tr>
        <tr>
            <td>Notification</td>
            <td>Representa una notificación que se enviará al usuario. Incluye atributos como <em>id</em>, <em>title</em>, <em>message</em>, y un <em>user</em> asociado. Método principal: <em>getNotification()</em>.</td>
        </tr>
        <tr>
            <td>Role</td>
            <td>Define el rol de un usuario dentro del sistema. Incluye atributos como <em>id</em> y <em>name</em>. Método principal: <em>getRole()</em>.</td>
        </tr>
        <tr>
            <td>Appointment</td>
            <td>Representa una cita programada entre un asesor y un granjero. Incluye atributos como <em>id</em>, <em>scheduled_date</em>, <em>start_time</em>, <em>end_time</em>, <em>status</em>, un <em>advisor</em>, y un <em>farmer</em>. Método principal: <em>getAppointment()</em>.</td>
        </tr>
        <tr>
            <td>Review</td>
            <td>Contiene la evaluación y comentario de una asesoría. Incluye atributos como <em>id</em>, <em>rating</em>, <em>comment</em>, y un <em>appointment</em> asociado. Método principal: <em>getReview()</em>.</td>
        </tr>
        <tr>
            <td>AvailableDate</td>
            <td>Representa los horarios cuando el asesor puede realizar una asesoría. Incluye atributos como <em>id</em>, <em>date</em>, <em>start_time</em>, <em>end_time</em>, y un <em>advisor</em> asociado. Método principal: <em>getAvailableDate()</em>.</td>
        </tr>
        <tr>
            <td>Status</td>
            <td>Representa los estados posibles de una cita: <em>PENDING</em>, <em>ONGOING</em>, <em>COMPLETED</em>, <em>REVIEWED</em>.</td>
        </tr>
        <tr>
            <td>Publication</td>
            <td>Representa una publicación hecha por un asesor. Incluye atributos como <em>id</em>, <em>title</em>, <em>description</em>, <em>image</em>, y un <em>advisor</em> asociado. Método principal: <em>getPublication()</em>.</td>
        </tr>
    </tbody>
</table>

#### 3.2.2.3. Database Design

El diseño de la base de datos es fundamental para garantizar una estructura sólida y eficiente en el almacenamiento y gestión de datos. En esta sección, se detalla el diseño de la base de datos para nuestro sistema, que está orientado a conectar granjeros con asesores especializados. La base de datos se compone de varias tablas, cada una de las cuales cumple con roles específicos en la organización de la información:

<table>
    <thead>
        <tr>
            <th>Tabla</th>
            <th>Descripción</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td><strong>Advisors</strong></td>
            <td>Almacena la información sobre los asesores que abarca su id, el id de su usuario y su calificación promedio.</td>
        </tr>
        <tr>
            <td><strong>Appointments</strong></td>
            <td>Almacena la información de las citas programadas entre granjeros y asesores. La información incluye fecha, hora de inicio y fin, el estado de las cita y el enlace para la videollamada.</td>
        </tr>
        <tr>
            <td><strong>Available Dates</strong></td>
            <td>Contiene la información de los horarios disponibles de los asesores para realizar citas.</td>
        </tr>
        <tr>
            <td><strong>Farmers</strong></td>
            <td>Almacena la información sobre los granjeros que abarca su id y el id de su usuario respectivo.</td>
        </tr>
        <tr>
            <td><strong>Notifications</strong></td>
            <td>Gestiona la información de las notificaciones que se enviarán a los usuarios, incluyendo títulos, mensajes y fechas de envío.</td>
        </tr>
        <tr>
            <td><strong>Profiles</strong></td>
            <td>Guarda información detallada sobre los usuarios, como el nombre del usuario, su país de origen, la url de su foto de perfil, etc.</td>
        </tr>
        <tr>
            <td><strong>Publications</strong></td>
            <td>Almacena la información de las publicaciones de los asesores, incluyendo su título, descripción e imagen relacionada.</td>
        </tr>
        <tr>
            <td><strong>Reviews</strong></td>
            <td>Registra las opiniones y calificaciones asociadas a una cita.</td>
        </tr>
        <tr>
            <td><strong>Roles</strong></td>
            <td>Define los roles dentro del sistema.</td>
        </tr>
        <tr>
            <td><strong>User_roles</strong></td>
            <td>Relaciona usuarios con roles específicos.</td>
        </tr>
        <tr>
            <td><strong>Users</strong></td>
            <td>Contiene los datos básicos de autenticación de los usuarios, el nombre de usuario y la contraseña encriptada.</td>
        </tr>
    </tbody>
</table>

#### 3.2.2.4. Database Diagram

El diagrama de base de datos proporciona una representación visual de la estructura y las relaciones de las tablas dentro del sistema de gestión de base de datos.

<img alt="Diagrama de Base de Datos" src="img/database2.png">

_Imagen 171. Diagrama de base de datos_

# Capítulo 4: Backend Product Implementation & Validation
## 4.1. Software Configuration Management
### 4.1.1. Software Development Environment Configuration

**Project Management:**

Para la gestión del proyecto, utilizamos como principal medio de comunicación WhatsApp, a través de un grupo en el cual compartimos nuestras ideas y opiniones sobre cada parte del trabajo. A esto se le suma el uso de la herramienta Google Meet, para realizar reuniones en videoconferencia y conversar de forma síncrona. Asimismo, utilizamos GitHub para el manejo de repositorios a través de una comunidad conformada por todos los integrantes del equipo. En esta comunidad, mantenemos el reporte y la aplicación.

**Software Development:**

Como IDE para trabajar en el Backend, utilizamos IntelliJ Idea, el cual es el entorno de desarrollo con el que ya estamos familiarizados para el desarrollo de Web APIs, utilizando el framework de Spring Boot.


**Software Testing:**

Las pruebas de aceptación son importantes a realizar para comprobar que los criterios de aceptación planteados están favoreciendo a las necesidades del negocio y cumplir con los requerimientos, para lo cual utilizamos el lenguaje Gherkin. Este consiste en trabajar el escenario con Given When Then, y lograr identificar las variables de input y output, lo cual es sencillo de entender para todos ya que utiliza lenguaje natural. Gracias a este, es que se logra garantizar la calidad del software, por ello cumple un papel esencial en los proyectos de desarrollo.

### 4.1.2. Source Code Management

Usuarios de GitHub
<table>
  <thead>
    <tr>
        <th>Integrante</th>
        <th>Usuario de GitHub</th>
    </tr>
  </thead>
  <tbody>
    <tr>
        <td>Delgado Corrales, Piero Gonzalo</td>
        <td>PieroD04</td>
    </tr>
    <tr>
        <td>Paredes Puente, Sebastián Roberto</td>
        <td>sebastian123gonzalo</td>
    </tr>
    <tr>
        <td>Salinas Torres, Salvador Antonio</td>
        <td>salvadoorssalinas</td>
    </tr>
    <tr>
        <td>Matos Fernandez, Christian Andre</td>
        <td>FerKlox</td>
    </tr>
  </tbody>
</table>

*URL de repositorio de Web Services:* https://github.com/AgroSupport-UPC/Backend

Para el desarrollo del trabajo se hará uso de GitFlow, el cual es un modelo de flujo de trabajo para la gestión de control de versiones Git. Está compuesta por ramas y cada una cumple un propósito distinto. Las ramas que utilizamos son: Feature, Develop, Release y Main. 

### 4.1.3. Source Code Style Guide & Conventions

En el desarrollo de este trabajo, se utilizará Java para trabajar en el Backend. Para ello, se utilizará la siguiente guía de estilos y convenciones.


**Java**

Es un lenguaje de programación utilizado para la programación web, programación móvil, entre otros. Es capaz de adaptarse para funcionar en distintas plataformas. En nuestro caso, es utilizado para el desarrollo del Backend.
https://google.github.io/styleguide/javaguide.html
- Nombrar las variables, funciones y clases con CamelCase, además de ser significativos y cortos.
- Utilizar HTTPS para establecer una conexión segura.
- Usar indentación correctamente para un código coherente y ordenado.
- Usar comillas dobles (“) para las cadenas de texto.
- Dejar comentarios en cada bloque de código para explicar su funcionalidad.
- Declarar constantes cuando sean variables que no cambiarán su valor a lo largo de todo el código.

**Gherkin**

Es el lenguaje para el diseño de casos de prueba en base a los requisitos establecidos por el negocio. Este se utiliza durante el proceso de testing.
https://specflow.org/gherkin/gherkin-conventions-for-readable-specifications/
- Separar en bloques cada parte de Given When Then, para una mejor lectura y subdividirse adecuadamente.
- Al mostrar las variables de input y output con sus ejemplos, se utilizan tablas para la representación de estos. Sin embargo, no es necesario utilizar tantas tablas para cada parte del código, sino una general al final del escenario.
- Si hay más de un escenario en un archivo, hacer la separación adecuada entre estas para diferenciarlas y dar a conocer que son más de uno. Para ello, se puede dejar dos líneas en blanco para saber dónde es que un escenario termina y el otro comienza.
- Agregar líneas en blanco dentro de cada Step para una mejor lectura y organización de la información.

### 4.1.4. Software Deployment Configuration

Para la configuración del despliegue de la aplicación, utilizaremos Git, un sistema de control de versiones distribuido que es bastante utilizado en proyectos de desarrollo de software. Es una herramienta esencial para trabajar colaborativamente y poder hacer el seguimiento de los cambios realizados por los miembros del grupo. Una de sus mejores ventajas es su capacidad para rastrear los cambios en los archivos de un proyecto a lo largo del tiempo. Con Git, es posible crear ramas, realizar cambios en ellas y fusionarlos eficientemente, permitiendo que varios desarrolladores trabajen en diferentes aspectos del proyecto simultáneamente sin interferencias.

Por otro lado, tenemos a GitHub, el cual es la plataforma para poder alojar repositorios de Git. Es uno de los servicios más utilizados por desarrolladores de forma mundial, ya que permite manejar repositorios públicos y privados para almacenar el código en la nube. A parte de ello, maneja el historial de los repositorios, permitiendo a los usuarios acceder a todas las versiones trabajadas, permitiendo que puedan retornar a una versión anterior en caso lo deseen. Ofrece otras herramientas que son muy útiles como los pull requests, los cuales son solicitudes de revisiones de una rama y luego poder fusionarla con otra rama.

Así es como con este, que cada miembro podrá trabajar de forma remota desde su IDE, teniendo una copia del repositorio Git a través del repositorio en línea almacenado en GitHub, así poder hacer commits para empujar los cambios que hayan realizado.

## 4.2. Software Development & Implementation
### 4.2.1. Sprint 1
#### 4.2.1.1. Sprint Planning 1

Se planeó el primer sprint a través de una reunión presencial. Para ello, se hizo la siguiente tabla para registrar la información que se discutió.

<table>
  <tr>
    <th>Sprint #</th>
    <td>Sprint 1</td>
  </tr>
  <tr>
    <th colspan="2"><strong>Sprint Planning Background</strong></th>
  </tr>
  <tr>
    <th>Date</th>
    <td>2024-09-05</td>
  </tr>
  <tr>
    <th>Time</th>
    <td>01:00 PM</td>
  </tr>
  <tr>
    <th>Location</th>
    <td>Presencial (En la universidad)</td>
  </tr>
  <tr>
    <th>Prepared by</th>
    <td>Paredes Puente, Sebastian Roberto</td>
  </tr>
  <tr>
    <th>Attendees (to planning meeting)</th>
    <td>
      <p>Delgado Corrales, Piero Gonzalo</p>
      <p>Matos Fernandez, Christian Andre</p>
      <p>Paredes Puente, Sebastián Roberto</p>
      <p>Salinas Torres, Salvador Antonio</p>
    </td>
  </tr>
  <tr>
    <th>Sprint n - 1 Review Summary</th>
    <td>No hubo sprint anterior</td>
  </tr>
  <tr>
    <th>Sprint n - 1 Retrospective Summary</th>
    <td>No hubo sprint anterior</td>
  </tr>
  <tr>
    <th colspan="2"><strong>Sprint Goal & User Stories</strong></th>
  </tr>
  <tr>
    <th>Sprint 1 Goal</th>
    <td>Realizar el primer deployment del Backend.</td>
  </tr>
  <tr>
    <th>Sprint 1 Velocity</th>
    <td>20</td>
  </tr>
  <tr>
    <th>Sum of Story Points</th>
    <td>20</td>
  </tr>
</table>

#### 4.2.1.2. Sprint Backlog 1

El objetivo de este primer sprint es la implementación y despliegue del Backend.

<table><tr><th colspan="1" valign="top">Sprint #</th><th colspan="7" valign="top">Sprint 1</th></tr>
<tr><td colspan="2" valign="top">User Story</td><td colspan="6" valign="top">Work-Item / Task</td></tr>
<tr><td colspan="1" valign="top">Id</td><td colspan="1" valign="top">Title</td><td colspan="1" valign="top">Id</td><td colspan="1" valign="top">Title</td><td colspan="1" valign="top">Description</td><td colspan="1" valign="top">Estimation </td><td colspan="1" valign="top">Assigned To</td><td colspan="1" valign="top">Status (To-Do / In-Process / Review / Done)</td></tr>
<tr><td colspan="1" rowspan="2" valign="top">TS03</td><td colspan="1" rowspan="2" valign="top">Uso de nuestra API para gestionar perfiles</td><td colspan="1" valign="top">WI01</td><td colspan="1" valign="top">Implementación de protocolos HTTP para perfiles</td><td colspan="1" valign="top">Se implementan los protocolos HTTP para los perfiles de los usuarios (granjeros y asesores) dentro de nuestra API.</td><td colspan="1" rowspan="2" valign="top">5</td><td colspan="1" valign="top">Salvador Salinas</td><td colspan="1" valign="top">Done</td></tr>
<tr><td colspan="1" valign="top">WI02</td><td colspan="1" valign="top">Implementación de protocolos HTTP para notificaciones</td><td colspan="1" valign="top">Se implementan los protocolos HTTP para las notificaciones dentro de nuestra API.</td><td colspan="1" valign="top">Salvador Salinas</td><td colspan="1" valign="top">Done</td></tr>
<tr><td colspan="1" rowspan="3" valign="top">TS04</td><td colspan="1" rowspan="3" valign="top">Uso de nuestra API para gestionar citas de asesoría</td><td colspan="1" valign="top">WI03</td><td colspan="1" valign="top">Implementación de protocolos HTTP para citas</td><td colspan="1" valign="top">Se implementan los protocolos HTTP para las citas de asesorías dentro de nuestra API.</td><td colspan="1" rowspan="3" valign="top">5</td><td colspan="1" valign="top">Christian Matos, Piero Delgado</td><td colspan="1" valign="top">Done</td></tr>
<tr><td colspan="1" valign="top">WI04</td><td colspan="1" valign="top">Implementación de protocolos HTTP para horarios disponibles</td><td colspan="1" valign="top">Se implementan los protocolos HTTP para los horarios disponibles de los asesores dentro de nuestra API.</td><td colspan="1" valign="top">Christian Matos</td><td colspan="1" valign="top">Done</td></tr>
<tr><td colspan="1" valign="top">WI05</td><td colspan="1" valign="top">Implementación de protocolos HTTP para reseñas</td><td colspan="1" valign="top">Se implementan los protocolos HTTP para las reseñas sobre los asesores dentro de nuestra API.</td><td colspan="1" valign="top">Piero Delgado</td><td colspan="1" valign="top">Done</td></tr>
<tr><td colspan="1" valign="top">TS05</td><td colspan="1" valign="top">Uso de nuestra API para gestionar publicaciones</td><td colspan="1" valign="top">WI06</td><td colspan="1" valign="top">Implementación de protocolos HTTP para publicaciones</td><td colspan="1" valign="top">Se implementan los protocolos HTTP para las publicaciones dentro de nuestra API.</td><td colspan="1" valign="top">5</td><td colspan="1" valign="top">Salvador Salinas</td><td colspan="1" valign="top">Done</td></tr>
<tr><td colspan="1" rowspan="2" valign="top">TS06</td><td colspan="1" rowspan="2" valign="top">Uso de nuestra API para gestionar autenticación	</td><td colspan="1" valign="top">WI07</td><td colspan="1" valign="top">Implementación de autenticación IAM</td><td colspan="1" valign="top">Se implementan los protocolos HTTP para la autenticación de los usuarios (granjeros y asesores) dentro de nuestra API.</td><td colspan="1" rowspan="2" valign="top">5</td><td colspan="1" valign="top">Piero Delgado</td><td colspan="1" valign="top">Done</td></tr>
</table>


#### 4.2.1.3. Development Evidence for Sprint Review

A continuación, se detallan los commits realizados, los cuales se trabajaron a partir de las tareas asignadas a cada miembro como se muestra en el Sprint Backlog 1. De este modo, se trabajó mayormente en el Backend.

Repositorio Backend: <https://github.com/AgroSupport-UPC/Backend>

|**Repository**|**Branch**|**Commit Id**|**Commit Message**|**Commited on (Date)**|
| :- | :- | :- | :- | :- |
|AgroSupport-UPC/Backend|main|95268d6|chore: base project|07/09/2024|
|AgroSupport-UPC/Backend|main|d662f5e|docs: readme file|07/09/2024|
|AgroSupport-UPC/Backend|feature/TS03|7e1e0be|feat: add profile, advisor and farmer components|10/09/2024|
|AgroSupport-UPC/Backend|feature/TS03|c2eb875|feat: notification components + acl context facade|10/09/2024|
|AgroSupport-UPC/Backend|feature/TS04|2617af0|feat: appointment bounded context added|10/09/2024|
|AgroSupport-UPC/Backend|feature/TS05|b1b3b3b|feat: bounded context publication added|11/09/2024|
|AgroSupport-UPC/Backend|develop|73bde39|fix: add missing attributes in aggregates|11/09/2024|
|AgroSupport-UPC/Backend|develop|f28bcfd|feat: add farmer id to review|11/09/2024|
|AgroSupport-UPC/Backend|release|d88cd4a|feat: connection to remote database|11/09/2024|
|AgroSupport-UPC/Backend|release|8b33156|feat: dockerfile|11/09/2024|
|AgroSupport-UPC/Backend|main|6eb4c51|Merge pull request #5 from AgroSupport-UPC/release|11/09/2024|

#### 4.2.1.4. Testing Suite Evidence for Sprint Review

Se realizaron las pruebas de aceptación para las historias de usuario trabajadas utilizando el lenguaje Gherkin en archivos feature. De esta manera, se registraron en el repositorio.

Repositorio Acceptance Tests: <https://github.com/AgroSupport-UPC/Acceptance-Tests>

|**Repository**|**Branch**|**Commit Id**|**Commit Message**|**Commited on (Date)**|
| :- | :- | :- | :- | :- |
|AgroSupport-UPC/Acceptance-Tests|main|8d46c64 |feat: TS01.feature added|14/09/2024|
|AgroSupport-UPC/Acceptance-Tests|main|a2242cb |feat: TS02.feature added|14/09/2024|
|AgroSupport-UPC/Acceptance-Tests|main|4b2e274 |feat: TS03.feature added|14/09/2024|
|AgroSupport-UPC/Acceptance-Tests|main|53b75a5 |feat: TS04.feature added|14/09/2024|
|AgroSupport-UPC/Acceptance-Tests|main|5619d89 |feat: TS05.feature added|14/09/2024|
|AgroSupport-UPC/Acceptance-Tests|main|8bfbbe7 |feat: TS06.feature added|15/09/2024|


#### 4.2.1.5. Execution Evidence for Sprint Review

Durante el sprint backlog 1, se completaron todas las historias de usuario planificadas. Al final del sprint, se mostró un compromiso excepcional con el éxito del proyecto y la entrega de valor al cliente. Para demostrar la ejecución de las tareas realizadas, se grabó un video que presenta los procesos alcanzados.

URL del video: [Video de ejecución de los Web Services](https://youtu.be/qCKmFRo37Wc)

<img alt="Execution Evidence Sprint 1" src="img/execution-evidence-1.png">

_Imagen 172. Captura del video de Execution Evidence_

#### 4.2.1.6. Services Documentation Evidence for Sprint Review

Para este sprint, hemos implementado una primera versión de la API con los endpoints necesarios para el funcionamiento de nuestro proyecto.

Enlace al repositorio del API: https://github.com/AgroSupport-UPC/Backend

|Método|Endpoint|Descripción|
|--|--|--|
|GET|/api/v1/users|Se obtiene la lista de usuarios|
|POST|/api/v1/users|Se publica un nuevo usuario|
|GET|/api/v1/users/{id}|Se obtiene un usuario por ID|
|GET|/api/v1/users/{id}/notifications|Se obtiene la lista de notificaciones de un usuario por su ID|
|GET|/api/v1/appointments|Se obtiene la lista de las citas|
|POST|/api/v1/appointments|Se publica una nueva cita|
|GET|/api/v1/appointments/{id}|Se obtiene una cita por ID|
|PUT|/api/v1/appointments/{id}|Se modifica una cita por ID|
|DELETE|/api/v1/appointments/{id}|Se elimina una cita por ID|
|GET|/api/v1/available-dates|Se obtiene la lista de horarios disponibles|
|POST|/api/v1/available-dates|Se publica un nuevo horario|
|GET|/api/v1/available-dates/{id}|Se obtiene un horario por ID|
|PUT|/api/v1/available-dates/{id}|Se modifica un horario por ID|
|DELETE|/api/v1/available-dates/{id}|Se elimina un horario por ID|
|GET|/api/v1/publications|Se obtiene la lista de publicaciones|
|POST|/api/v1/publications|Se publica una nueva publicación|
|GET|/api/v1/publications/{id}|Se obtiene una publicación por ID|
|PUT|/api/v1/publications/{id}|Se modifica una publicación por ID|
|DELETE|/api/v1/publications/{id}|Se elimina una publicación por ID|
|GET|/api/v1/profiles|Se obtiene la lista de perfiles|
|POST|/api/v1/profiles|Se publica un nuevo perfil|
|GET|/api/v1/profiles/{id}|Se obtiene un perfil por ID|
|PUT|/api/v1/profiles/{id}|Se modifica un perfil por ID|
|DELETE|/api/v1/profiles/{id}|Se elimina un perfil por ID|
|GET|/api/v1/advisors|Se obtiene la lista de asesores|
|POST|/api/v1/advisors|Se publica un nuevo asesor|
|GET|/api/v1/advisors/{id}|Se obtiene un asesor por ID|
|PUT|/api/v1/advisors/{id}|Se modifica un asesor por ID|
|DELETE|/api/v1/advisors/{id}|Se elimina un asesor por ID|
|GET|/api/v1/farmers|Se obtiene la lista de granjeros|
|POST|/api/v1/farmers|Se publica un nuevo granjero|
|GET|/api/v1/farmers/{id}|Se obtiene un granjero por ID|
|DELETE|/api/v1/farmers/{id}|Se elimina un granjero por ID|
|GET|/api/v1/notifications|Se obtiene la lista de notificaciones|
|POST|/api/v1/notifications|Se publica una nueva notificación|
|GET|/api/v1/notifications/{id}|Se obtiene una notificación por ID|
|DELETE|/api/v1/notifications/{id}|Se elimina una notificación por ID|
|GET|/api/v1/reviews|Se obtiene la lista de reseñas|
|POST|/api/v1/reviews|Se publica una nueva reseña|
|GET|/api/v1/reviews/{id}|Se obtiene una reseña por ID|
|PUT|/api/v1/reviews/{id}|Se modifica una reseña por ID|
|DELETE|/api/v1/reviews/{id}|Se elimina una reseña por ID|

Enlace al API deployado: http://agrosupport-ewdyg8e2hjbwdge7.eastus-01.azurewebsites.net/

<img alt="Swagger" src="img/swagger.png">

_Imagen 173. Swagger con endpoints del proyecto deployado_

#### 4.2.1.7. Software Deployment Evidence for Sprint Review

Para desplegar el Web Service se utilizó Docker para poner la aplicación en un contenedor, y Azure para alojar el contenedor.

Primero, se generó la carpeta target con todos los archivos que conforman la aplicación.

<img alt="Evidencia de deployment 1" src="img/backend_deployment1.png">

_Imagen 174. Evidencia de deployment_

Luego, se creó el dockerfile para la creación de la imagen.

<img alt="Evidencia de deployment 2" src="img/backend_deployment2.png">

_Imagen 175. Evidencia de deployment_

Asimismo, se subió la imagen de la aplicación a Docker Hub.

<img alt="Evidencia de deployment 3" src="img/backend_deployment3.png">

_Imagen 176. Evidencia de deployment_

Por otro lado, se creó el Web App en Azure con las configuraciones básicas.

<img alt="Evidencia de deployment 4" src="img/backend_deployment4.png">

_Imagen 177. Evidencia de deployment_

Además, se utilizó la imagen subida a Docker Hub.

<img alt="Evidencia de deployment 5" src="img/backend_deployment5.png">

_Imagen 178. Evidencia de deployment_

Finalmente, se inicializó el Web App.

<img alt="Evidencia de deployment 6" src="img/backend_deployment6.png">

_Imagen 179. Evidencia de deployment_

Evidencia del funcionamiento del Backend deployado:

<img alt="Evidencia de deployment 7" src="img/backend_deployment7.png">

_Imagen 180. Evidencia de deployment_

#### 4.2.1.8. Team Collaboration Insights during Sprint

Durante el desarrollo del sprint, se realizaron reuniones diarias para revisar el avance de las tareas asignadas y resolver cualquier impedimento que pudiera surgir. Además, se mantuvo una comunicación constante a través de WhatsApp para coordinar las actividades y compartir información relevante. Gracias a esta colaboración, se logró cumplir con los objetivos establecidos para el sprint y se mantuvo un ambiente de trabajo armonioso y productivo.

Cada integrante trabajó en ramas "feature" correspondientes a sus tareas asignadas. Posteriormente, realizamos los "merge" con la rama "develop", hicimos el "release" y finalmente integramos los cambios en la rama "main".

<img src="img/team-collaboration-insights-backend-sprint-1.png" alt="Team Collaboration Insights - Backend Sprint 1">

_Imagen 181. Insights en GitHub_

# Capítulo 5: Product Implementation & Validation

## 5.1. Software Configuration Management

### 5.1.1. Software Development Environment Configuration

**Product UX/UI Design:**

Se realizaron los productos de UX con la herramienta UXPressia, así como el User Persona, Empathy Mapping, Impact Mapping, entre otras. Gracias a esto pudimos modelar bien los diseños de la experiencia de usuario, lo cual nos sirve para poder ponernos en una mejor perspectiva para nuestros segmentos objetivo. Por otro lado, hicimos los prototipos de la aplicación móvil utilizando la herramienta Figma, la cual nos permitió crear los Wireframes y Mock-ups para tener un diseño previo al desarrollo de la aplicación.


**Software Development:**

Como principal IDE, utilizamos Android Studio, el cual es el entorno de desarrollo con el que estamos más familiarizados por ser de Jetbrains. Por otro lado, para el desarrollo usamos los lenguajes aprendidos previamente, como HTML, CSS y JavaScript para la landing page, y Kotlin para la aplicación móvil.


**Software Testing:**

Las pruebas de aceptación son importantes a realizar para comprobar que los criterios de aceptación planteados están favoreciendo a las necesidades del negocio y cumplir con los requerimientos, para lo cual utilizamos el lenguaje Gherkin. Este consiste en trabajar el escenario con Given When Then, y lograr identificar las variables de input y output, lo cual es sencillo de entender para todos ya que utiliza lenguaje natural. Gracias a este, es que se logra garantizar la calidad del software, por ello cumple un papel esencial en los proyectos de desarrollo.

### 5.1.2. Source Code Management

Usuarios de GitHub
<table>
  <thead>
    <tr>
        <th>Integrante</th>
        <th>Usuario de GitHub</th>
    </tr>
  </thead>
  <tbody>
    <tr>
        <td>Delgado Corrales, Piero Gonzalo</td>
        <td>PieroD04</td>
    </tr>
    <tr>
        <td>Paredes Puente, Sebastián Roberto</td>
        <td>sebastian123gonzalo</td>
    </tr>
    <tr>
        <td>Salinas Torres, Salvador Antonio</td>
        <td>salvadoorssalinas</td>
    </tr>
    <tr>
        <td>Matos Fernandez, Christian Andre</td>
        <td>FerKlox</td>
    </tr>
  </tbody>
</table>

*URL de repositorio de Landing Page:* https://github.com/AgroSupport-UPC/Landing-Page

*URL de repositorio de Mobile Application:* https://github.com/AgroSupport-UPC/Frontend

Para el desarrollo del trabajo se hará uso de GitFlow, el cual es un modelo de flujo de trabajo para la gestión de control de versiones Git. Está compuesta por ramas y cada una cumple un propósito distinto. Las ramas que utilizamos son: Feature, Develop, Release y Main.

### 5.1.3. Source Code Style Guide & Conventions

En el desarrollo de este trabajo, se utilizará una gran variedad de lenguajes para trabajar en el Landing Page y Mobile Application. Para ello, se utilizará la siguiente guía de estilos y convenciones.

**HTML**

Es el lenguaje utilizado para estructurar el contenido de una página web, brindando una variedad de elementos posibles como texto, imágenes, formularios, etc.
https://www.w3schools.com/html/html5_syntax.asp

- Declarar el tipo de documento en la primera línea con \<!DOCTYPE html>.
- Respetar la estructura básica del HTML: \<html>, \<head>, \<body>.
- Declarar el título de la página para dar a conocer al usuario en qué página se encuentra. (Usar el elemento \<title> en \<head>)
- Se usará la indentación coherente para lograr una lectura sencilla del código, por lo que es importante tener la tabulación correcta para cada nivel de anidamiento.
- Siempre cerrar los elementos que lo requieran, ya sea una división, párrafo, título. (Si se declara una \<div>, siempre cerrarlo con \</div>)
- Declarar el atributo “alt” para las imágenes.


**CSS**

Es el lenguaje utilizado para definir el diseño de la página web, así como los estilos, fuentes, colores, contenedores, etc.
https://google.github.io/styleguide/htmlcssguide.html
- Usar indentación de forma correcta.
- Los nombres para elementos deben ser cortos y en minúsculas.
- Declarar los colores en código hexadecimal. (Ejemplo: #024A86)
- Dejar comentarios para conocer el propósito del estilo y su uso.
- El diseño debe ser responsive para que los usuarios lo puedan visualizar cómodamente desde el dispositivo en qué se encuentren.


**JavaScript**

Es el lenguaje de programación más utilizado para la programación web, ya que permite desarrollar páginas interactivas con animaciones agradables para los usuarios.
https://www.w3schools.com/js/js_conventions.asp
- Declarar nombres coherentes y cortos para las variables y funciones.
- Dejar comentarios para dar a conocer que hace cada parte del código sobre la página web.
- Siempre colocar un punto y coma al final de cada línea de código.
- Declarar las constantes cuando sea necesario en lugar de variables que nunca cambiarán su valor.
- Usar los operadores de comparación estricta en lugar de comparación regular cuando sea posible. (Ejemplo: Utilizar === en lugar de ==)

**Kotlin**

Es un lenguaje de programación moderno que se utiliza para el desarrollo de aplicaciones móviles en Android.
https://developer.android.com/kotlin/style-guide
- Nombrar las variables, funciones y clases con CamelCase, además de ser significativos y cortos.
- Utilizar HTTPS para establecer una conexión segura.
- Usar indentación correctamente para un código coherente y ordenado.
- Usar comillas dobles (“) para las cadenas de texto.
- Dejar comentarios en cada bloque de código para explicar su funcionalidad.
- Declarar constantes cuando sean variables que no cambiarán su valor a lo largo de todo el código.

### 5.1.4. Software Deployment Configuration

Igualmente como se ha trabajado con el Backend, también utilizaremos el sistema de Git y repositorios en GitHub para el desarrollo de la Landing Page y la Mobile Application. De esta manera, cada miembro podrá trabajar de forma remota desde su IDE, teniendo una copia del repositorio Git a través del repositorio en línea almacenado en GitHub, así poder hacer commits para empujar los cambios que hayan realizado.

Asimismo, utilizaremos el sistema de GitHub Pages para desplegar la Landing Page de nuestro proyecto. GitHub Pages es un servicio que ofrece GitHub para alojar sitios web estáticos de forma gratuita. Permite a los desarrolladores alojar un sitio web directamente desde un repositorio de GitHub, lo que facilita la publicación de sitios web sin tener que preocuparse por la infraestructura de alojamiento.


## 5.2. Software Development & Implementation
### 5.2.1. Sprint 1
#### 5.2.1.1. Sprint Planning 1

Se planeó el segundo sprint a través de una reunión presencial. Para ello, se hizo la siguiente tabla para registrar la información que se discutió.

<table>
  <tr>
    <th>Sprint #</th>
    <td>Sprint 1</td>
  </tr>
  <tr>
    <th colspan="2"><strong>Sprint Planning Background</strong></th>
  </tr>
  <tr>
    <th>Date</th>
    <td>2024-09-16</td>
  </tr>
  <tr>
    <th>Time</th>
    <td>03:00 PM</td>
  </tr>
  <tr>
    <th>Location</th>
    <td>Presencial (En la universidad)</td>
  </tr>
  <tr>
    <th>Prepared by</th>
    <td>Paredes Puente, Sebastian Roberto</td>
  </tr>
  <tr>
    <th>Attendees (to planning meeting)</th>
    <td>
      <p>Delgado Corrales, Piero Gonzalo</p>
      <p>Matos Fernandez, Christian Andre</p>
      <p>Paredes Puente, Sebastián Roberto</p>
      <p>Salinas Torres, Salvador Antonio</p>
    </td>
  </tr>
  <tr>
    <th>Sprint n - 1 Review Summary</th>
    <td>Se trabajó y desplegó la primera versión del Backend a utilizar la aplicación móvil. Igualmente, faltó algunos detalles a ajustar y mejorar.</td>
  </tr>
  <tr>
    <th>Sprint n - 1 Retrospective Summary</th>
    <td>Se logró trabajar todas las historias de usuario planteadas en el sprint backlog del Backend. Sin embargo, se trabajó con los tiempos muy ajustados entre todos los miembros del equipo, por lo que se espera mejorar eso en este segundo sprint.</td>
  </tr>
  <tr>
    <th colspan="2"><strong>Sprint Goal & User Stories</strong></th>
  </tr>
  <tr>
    <th>Sprint 1 Goal</th>
    <td>Realizar la Landing Page y el primer avance del Frontend de la aplicación móvil.</td>
  </tr>
  <tr>
    <th>Sprint 1 Velocity</th>
    <td>31</td>
  </tr>
  <tr>
    <th>Sum of Story Points</th>
    <td>31</td>
  </tr>
</table>

#### 5.2.1.2. Sprint Backlog 1

El objetivo de este primer sprint es la implementación y despliegue de la Landing Page y un primer avance del Frontend de la aplicación móvil.

<table><tr><th colspan="1" valign="top">Sprint #</th><th colspan="7" valign="top">Sprint 1</th></tr>
<tr><td colspan="2" valign="top">User Story</td><td colspan="6" valign="top">Work-Item / Task</td></tr>
<tr><td colspan="1" valign="top">Id</td><td colspan="1" valign="top">Title</td><td colspan="1" valign="top">Id</td><td colspan="1" valign="top">Title</td><td colspan="1" valign="top">Description</td><td colspan="1" valign="top">Estimation </td><td colspan="1" valign="top">Assigned To</td><td colspan="1" valign="top">Status (To-Do / In-Process / Review / Done)</td></tr>
<tr><td colspan="1" rowspan="2" valign="top">US14</td><td colspan="1" rowspan="2" valign="top">Visualización de la sección de inicio de la Landing Page	</td><td colspan="1" valign="top">WI01</td><td colspan="1" valign="top">Implementación de navbar y footer</td><td colspan="1" valign="top">Se implementa el navbar para navegar por la Landing Page y el footer en la parte inferior.</td><td colspan="1" rowspan="2" valign="top">2</td><td colspan="1" valign="top">Salvador Salinas</td><td colspan="1" valign="top">Done</td></tr>
<tr><td colspan="1" valign="top">WI02</td><td colspan="1" valign="top">Implementación de página de inicio</td><td colspan="1" valign="top">Se implementa la página de inicio de forma responsive y con su archivo css correspondiente.	</td><td colspan="1" valign="top">Salvador Salinas</td><td colspan="1" valign="top">Done</td></tr>
<tr><td colspan="1" valign="top">US15</td><td colspan="1" valign="top">Visualización de la sección 'Problemática' de la Landing Page</td><td colspan="1" valign="top">WI03</td><td colspan="1" valign="top">Implementación de página 'Problemática'</td><td colspan="1" valign="top">Se implementa la página sobre la Problemática, de forma responsive y con su archivo css correspondiente.	</td><td colspan="1" valign="top">2</td><td colspan="1" valign="top">Salvador Salinas</td><td colspan="1" valign="top">Done</td></tr>
<tr><td colspan="1" valign="top">US16</td><td colspan="1" valign="top">Visualización de la sección 'Sobre Nosotros' de la Landing Page</td><td colspan="1" valign="top">WI04</td><td colspan="1" valign="top">Implementación de página 'Sobre Nosotros'</td><td colspan="1" valign="top">Se implementa la página Sobre Nosotros, de forma responsive y con su archivo css correspondiente.	</td><td colspan="1" valign="top">2</td><td colspan="1" valign="top">Piero Delgado</td><td colspan="1" valign="top">Done</td></tr>
<tr><td colspan="1" valign="top">US17</td><td colspan="1" valign="top">	Visualización de la sección 'Características' de la Landing Page</td><td colspan="1" valign="top">WI05</td><td colspan="1" valign="top">Implementación de página 'Características'</td><td colspan="1" valign="top">Se implementa la página Características, de forma responsive y con su archivo css correspondiente.</td><td colspan="1" valign="top">2</td><td colspan="1" valign="top">Christian Matos</td><td colspan="1" valign="top">Done</td></tr>
<tr><td colspan="1" valign="top">US18</td><td colspan="1" valign="top">Visualización de la sección 'Contacto' de la Landing Page</td><td colspan="1" valign="top">WI06</td><td colspan="1" valign="top">Implementación de página 'Contacto'</td><td colspan="1" valign="top">Se implementa la página Contacto, de forma responsive y con su archivo css correspondiente.</td><td colspan="1" valign="top">2</td><td colspan="1" valign="top">Sebastian Paredes</td><td colspan="1" valign="top">Done</td></tr>
</table>

#### 5.2.1.3. Development Evidence for Sprint Review

A continuación, se detallan los commits realizados, los cuales se trabajaron a partir de las tareas asignadas a cada miembro como se muestra en el Sprint Backlog 1. De este modo, se trabajó en la Landing Page y Frontend.

Repositorio Landing Page: <https://github.com/AgroSupport-UPC/Landing-Page>

Repositorio Frontend: <https://github.com/AgroSupport-UPC/Frontend>

|**Repository**|**Branch**|**Commit Id**|**Commit Message**|**Commited on (Date)**|
| :- | :- | :- | :- | :- |
|AgroSupport-UPC/Landing-Page|main|308a78d|chore: initial commit|19/09/2024|
|AgroSupport-UPC/Landing-Page|feature/us14|df6454b|feat: home page|19/09/2024|
|AgroSupport-UPC/Landing-Page|develop|e564bc9|Merge pull request #1 from AgroSupport-UPC/feature/us14|19/09/2024|
|AgroSupport-UPC/Landing-Page|feature/us15|260ad85|feat: about app (problematic) page|19/09/2024|
|AgroSupport-UPC/Landing-Page|feature/us16|dde2859|feat: about us section|19/09/2024|
|AgroSupport-UPC/Landing-Page|develop|0b1d34b|Merge pull request #2 from AgroSupport-UPC/feature/us15|19/09/2024|
|AgroSupport-UPC/Landing-Page|develop|58005a6|Merge pull request #3 from AgroSupport-UPC/feature/us16|19/09/2024|
|AgroSupport-UPC/Landing-Page|feature/us17|210ee22|feat: feature section added|20/09/2024|
|AgroSupport-UPC/Landing-Page|develop|5761273|Merge pull request #4 from AgroSupport-UPC/feature/us17|20/09/2024|
|AgroSupport-UPC/Landing-Page|feature/us18|c628083|feat: contact section|20/09/2024|
|AgroSupport-UPC/Landing-Page|develop|22d80b0|Merge pull request #5 from AgroSupport-UPC/feature/us18|20/09/2024|
|AgroSupport-UPC/Landing-Page|main|d6a4808|Merge pull request #6 from AgroSupport-UPC/develop|20/09/2024|

#### 5.2.1.4. Testing Suite Evidence for Sprint Review

Se realizaron las pruebas de aceptación para las historias de usuario de la landing page y aplicacion movil, utilizando el lenguaje Gherkin en archivos feature. De esta manera, se registraron en el repositorio.

Repositorio Acceptance Tests: <https://github.com/AgroSupport-UPC/Acceptance-Tests>

|**Repository**|**Branch**|**Commit Id**|**Commit Message**|**Commited on (Date)**|
| :- | :- | :- | :- | :- | 
|AgroSupport-UPC/Acceptance-Tests|main|fca6834 |feat: US14.feature added|19/09/2024|
|AgroSupport-UPC/Acceptance-Tests|main|3e5702a |feat: US15.feature added|19/09/2024|
|AgroSupport-UPC/Acceptance-Tests|main|5357982 |feat: US16.feature added|19/09/2024|
|AgroSupport-UPC/Acceptance-Tests|main|97427f3 |feat: US17.feature added|19/09/2024|
|AgroSupport-UPC/Acceptance-Tests|main|edec1d0 |feat: US18.feature added|19/09/2024|

#### 5.2.1.5. Execution Evidence for Sprint Review
#### 5.2.1.6. Services Documentation Evidence for Sprint Review
#### 5.2.1.7. Software Deployment Evidence for Sprint Review
#### 5.2.1.8. Team Collaboration Insights during Sprint
    
# Conclusiones

# Recomendaciones

# Video App Validation

# Video About the Product

# Video About the Team

# Glosario

En esta sección, se definen los términos utilizados a lo largo del proyecto para que se pueda comprender por todo el equipo y agentes interesados.

- **Farmer (Granjeros):** Usuarios que gestionan granjas y buscan asesoramiento para mejorar sus prácticas agrícolas.
- **Advisor (Asesores):** Expertos en agricultura que brindan asesorías y apoyo técnico a los granjeros.
- **Appointment (Cita):** Sesión programada entre un granjero y un asesor para discutir problemas específicos o recibir orientación.
- **Schedule (Horario):** Planificación de citas y tareas, organizado según la disponibilidad de los asesores y las necesidades de los granjeros.
- **Feedback (Retroalimentación):** Comentarios y observaciones que los granjeros o asesores proporcionan después de una sesión para mejorar el servicio.
- **Self-sustainable (Autosostenible):** Capacidad de una granja o sistema agrícola para operar y mantenerse por sí mismo sin necesidad de recursos externos continuos, logrando un equilibrio entre producción y consumo que permite su funcionamiento a largo plazo.

# Bibliografía

Ames, A. (2022) EVIDENCIA para una Nueva Gestión Pública. Escuela de Gestión Pública de la Universidad del Pacífico. https://www.up.edu.pe/egp/programas-especializacion_copy(1)/SiteAssets/Lists/Observatorio/AllItems/Informe%20de%20Evidencia%20sector%20Agropecuario%20-%20EGP.pdf

Carhuavilca, D., Sánchez, A., Montoya, L., Cueto, M. & Baldeón, M. (2021) Informe Técnico - Producción Nacional. INEI. https://www.inei.gob.pe/media/MenuRecursivo/boletines/10-informe-tecnico-produccion-nacional-ago-2021.pdf

Problemas Tipo de la Agricultura Peruana (s.f.) Ministerio de Desarrollo Agrario y Riego. https://www.midagri.gob.pe/portal/22-sector-agrario/vision-general/190-problemas-en-la-agricultura-peruana