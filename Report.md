# Capítulo V: Product Implementation, Validation & Deployment

El equipo ha definido una serie de herramientas para asegurar una configuración coherente del entorno de desarrollo. Esto facilita una colaboración eficiente y contribuye al cumplimiento de los objetivos del proyecto. Estas herramientas abarcan distintas fases del ciclo de vida del producto MVP.

## 5.1. Software Configuration Management.

# Gestión de Proyectos

**Pivotal Tracker** es la herramienta principal utilizada para gestionar el proyecto de manera ágil. Permite planificar, organizar y hacer seguimiento al progreso de las historias de usuario, tareas y errores, mediante un enfoque basado en historias y priorización colaborativa.
Ruta de referencia: [https://www.pivotaltracker.com](https://www.pivotaltracker.com)

**Whatsapp** es la plataforma de comunicación en tiempo real que emplea el equipo. A través de grupos organizados por temas y funciones, realizamos reuniones, coordinaciones diarias y soporte instantáneo durante todo el proceso de desarrollo.

## Diseño de Producto UX/UI

**Figma** es la herramienta principal para diseñar las interfaces gráficas (UI) y optimizar la experiencia de usuario (UX). Permite la colaboración simultánea entre varios miembros en la creación de prototipos interactivos, estructuras visuales y pruebas de diseño.
Ruta de referencia: [https://www.figma.com](https://www.figma.com)

**UXPressia** complementa el trabajo de UX permitiendo la creación y documentación de User Personas, Customer Journey Maps y Empathy Maps. Estas herramientas ayudan al equipo a comprender mejor al usuario final y orientar las decisiones de diseño según sus necesidades.
Ruta de referencia: [https://uxpressia.com](https://uxpressia.com)

## Desarrollo de Software

**WebStorm** es el entorno de desarrollo integrado (IDE) utilizado por el equipo para programar y depurar código web. Su integración con sistemas de control de versiones, linters y herramientas modernas de desarrollo lo convierte en un entorno robusto y eficiente.
Ruta de referencia: [https://www.jetbrains.com/webstorm](https://www.jetbrains.com/webstorm)

## Despliegue de Software

**Git** es el sistema de control de versiones adoptado para gestionar el historial de cambios del código fuente. Facilita la colaboración de varios desarrolladores en paralelo, permitiendo el manejo de ramas, fusiones y versiones de manera controlada.
Ruta de referencia: [https://git-scm.com](https://git-scm.com)

## Documentación de Software y Gestión del Proyecto

**GitHub** actúa como el repositorio remoto centralizado para almacenar y sincronizar el código del proyecto. También es utilizado para la revisión de código (pull requests), el registro de incidencias, la documentación del proyecto y la automatización de tareas de despliegue.
Ruta de referencia: [https://github.com](https://github.com)

## Pruebas de Software

**Gherkin** es el sistema de etiquetado empleado para describir los criterios de aceptación de las historias de usuario de forma estructurada.
Ruta de referencia: [https://cucumber.io/docs/gherkin](https://cucumber.io/docs/gherkin)

## 5.1.1. Software Development Environment Configuration.

El proyecto adoptará las convenciones de flujo de trabajo del modelo GitFlow para la gestión de versiones, empleando GitHub como plataforma de control de versiones. A continuación, se detalla cómo se implementará GitFlow como flujo de trabajo, junto con los enlaces a los repositorios de GitHub correspondientes, en este caso para la Landing Page.

### 5.1.2. Source Code Management.

Se ha implementado GitFlow (<<cita>>) para el desarrollo y mantenimiento del proyecto. Para ello, se han creado cinco ramas principales: Main, Hotfix, Release, Develop y Feature. Inicialmente, el primer commit se realiza en la rama Main, de la cual se desprende la rama Develop.
Cada sección de la landing page se desarrolla en su propia rama Feature bajo la nomenclatura feature/<nombre_de_feature>, como por ejemplo feature/Header, feature/Footer o feature/Seccion.
Una vez finalizado el desarrollo de cada Feature, se realiza un merge hacia Develop, donde se integran todas las secciones de la web. Cuando Develop alcanza un avance significativo (habitualmente al finalizar un sprint), se crea una nueva Release siguiendo la nomenclatura semver (Semantic Versioning 2.0.0).
Durante esta etapa se lleva a cabo el testeo y la documentación del código en el archivo README.md.
Además, la rama Hotfix se utiliza para corregir problemas detectados en Main, creando ramas hotfix/<nombre_de_hotfix>. Finalmente, los cambios se integran en Main para su despliegue en producción.

Repositorios de GitHub:

Enlace para acceder a la organización de GitHub: https://github.com/UPC-PaxTech
Enlace para acceder a repositorio de la Landing Page: https://github.com/PaxTech-UPC/uTime-Landing-Page

### 5.1.3. Source Code Style Guide & Conventions.

#### Nomenclatura

- **Pascal Case**: Será utilizado para nombrar componentes.
- **Camel Case**: Será utilizado para nombrar variables, funciones y otros elementos de programación.

#### HTML

- Se desarrollarán los componentes utilizando código HTML semántico.
- Se seguirán las convenciones estándar de HTML, como:
  - Declarar correctamente el documento HTML.
  - Utilizar minúsculas para las etiquetas.
  - Cerrar adecuadamente todas las etiquetas.
  - Especificar atributos width y height en las imágenes.
  - Mantener un formateo limpio del código.

#### CSS

- Se adoptarán los principios utility-first y mobile-first en la creación de clases.
- Se utilizará Tailwind CSS para la construcción de los estilos.
- Se respetarán las convenciones estándar de CSS, tales como:
  - Mantener una correcta indentación.
  - Aplicar un reseteo de estilos.
  - Respetar la regla de cascada.
  - Gestionar adecuadamente la especificidad de los estilos.

#### Gherkin

- Para la implementación de los archivos de tipo **feature**, seguiremos el esquema establecido en los criterios de aceptación:
  - **Given** (Dado que), **When** (Cuando) y **Then** (Entonces).
  - Los **examples** estarán organizados en un cuadro y separados por el carácter `]`.

### 5.1.4. Software Deployment Configuration.

Para el despliegue de la landing page, se ha utilizado un servicio de Software as a Service llamado Netlify.
Primero, se creó una cuenta en Netlify y se vinculó con la cuenta de GitHub donde se aloja el repositorio. Posteriormente, se enlazó el repositorio al hosting para permitir el acceso al código. Finalmente, se configuraron los comandos de inicialización, las variables de entorno y se realizó el despliegue del proyecto.

Además, mediante la integración de GitHub Actions, se implementó un flujo CI/CD en Netlify que detecta cambios en la rama Main y ejecuta el despliegue automático a producción.

![Netifly deploy](./img/netifly-deploy.png)

## 5.2. Landing Page, Services & Applications Implementation.

### 5.2.1. Sprint 1

#### 5.2.1.1. Sprint Planning 1.

En el marco de Scrum, un Sprint es un periodo de tiempo fijo y breve en el que un equipo se enfoca en completar el trabajo necesario para alcanzar el objetivo del proyecto, conocido como Product Goal. En el caso del proceso de desarrollo de la plataforma Champa.pe, se optó por optimizar tiempos en 5 sprints de 15 días calendario. El primer Sprint comenzará el 08/04/2025, y su objetivo es crear una landing page que tenga una alta conversión de leads, asegurando que los visitantes del sitio se vuelvan potenciales usuarios de la plataforma.

##### Sprint Planning Background
**Date**: 2025-04-08  
**Time**: 09:00 PM  
**Location**: Reunión virtual mediante la aplicación Whatsapp  
**Prepare By**: Alejandro Oroncoy  

**Attendees (to planning meeting)**: Alejandro Oroncoy, TuChambape  

###### Sprint n - 1 Review Summary
Este es el primer sprint del proyecto, por lo tanto, no hay resultados de un sprint anterior para revisar.  


###### Sprint n - 1 Retrospective Summary
Al tratarse del primer sprint, no se cuenta con una retrospectiva previa. La retroalimentación y oportunidades de mejora se evaluarán al finalizar este sprint.  

## Sprint Goal & User Stories

###### Sprint 1 Goal
Nuestro enfoque se centra en entregar una landing page funcional que tenga una alta conversión de leads para Champa.pe.  
Creemos que logrará una clara propuesta de valor y generará interés y confianza en los usuarios potenciales.  
Esto se confirmará cuando los visitantes puedan acceder al sitio e interactuar con todos los elementos clave de la página de aterrizaje (visión general de servicios, beneficios, precios, testimoniales, CTAs y soporte) tanto en dispositivos de escritorio como móviles.

**Sprint 1 Velocity**: 13  
**Sum of Story Points**: 13


#### 5.2.1.2. Aspect Leaders and Collaborators.

Para este Sprint, se han identificado los aspectos clave en el desarrollo de la landing page de Champa.pe. Con el objetivo de optimizar la organización y la comunicación dentro del equipo, se ha creado la matriz de Responsabilidad y Colaboración (RCC), en la que se define quién asumirá el rol de Responsable (R) y quiénes participarán como Colaboradores (C) en cada uno de estos aspectos fundamentales. Esta estructura facilita una ejecución más clara y eficiente de las tareas asignadas.

#### 5.2.1.3. Sprint Backlog 1.

En el primer sprint backlog, el equipo tenía como objetivo iniciar y finalizar el desarrollo de la landing page. Para organizar y gestionar las tareas, se distribuyeron las historias de usuario entre los miembros del equipo según sus habilidades específicas. Esta asignación permitió dividir las tareas en actividades manejables, enfocándose en construir una landing page completa que fuera tanto atractiva como funcional. El objetivo principal del sprint fue lograr una landing page efectiva que cumpliera con los requerimientos establecidos.

| Orden | User Story ID | Título                          | Descripción                                                                                                                | Story Points |
| ----- | ------------- | -------------------------------- | -------------------------------------------------------------------------------------------------------------------------- | ------------ |
| 1     | US29          | Visualización general de los servicios | Como visitante, quiero ver una descripción general de los servicios ofrecidos en la landing page, para entender rápidamente qué se ofrece. | 3            |
| 2     | US30          | Visualización de beneficios      | Como visitante, quiero ver los beneficios de registrarme en la plataforma, para poder decidir unirme a ella.                | 2            |
| 3     | US31          | Categorías de servicios          | Como visitante, quiero explorar las categorías de servicios disponibles (ej: plomería, electricidad), para conocer el alcance de la plataforma. | 3            |
| 4     | US32          | Sección de beneficios            | Como visitante, quiero conocer los beneficios de registrarme (seguridad, ahorro de tiempo, etc.), para decidir unirme a la plataforma. | 2            |
| 5     | US33          | Sección "Cómo funciona"          | Como visitante, quiero entender los pasos para usar la plataforma, tanto como cliente como trabajador, para saber cómo empezar. | 2            |
| 6     | US34          | Cambiar idioma del landing       | Como visitante del segmento objetivo "Trabajador/Cliente", quiero cambiar el idioma del landing a español o inglés, para entender mejor los beneficios de la plataforma. | 3            |
| 7     | US35          | Contenido traducido              | Como visitante del segmento objetivo "Trabajador/Cliente", quiero ver todo el contenido del landing en mi idioma preferido, para evaluar claramente el valor de la plataforma. | 3            |


#### 5.2.1.4. Development Evidence for Sprint Review.

| Repository               | Branch  | Commit Id | Commit Message                                    | Commit Message Body                          | Committed on (Date) |
|--------------------------|---------|-----------|--------------------------------------------------|---------------------------------------------|---------------------|
| [Champa-Landing-Page](https://github.com/JobConnect-AW/landing-page)     | develop | a617f27   | [fix: fix landing page](https://github.com/JobConnect-AW/landing-page/commit/a617f27) |                                             | 2025-04-24          |
| [Champa-Landing-Page](https://github.com/JobConnect-AW/landing-page)      | develop | 305efe9   | [feat: finish landing](https://github.com/JobConnect-AW/landing-page/commit/305efe9) |                                             | 2025-04-24          |
| [Champa-Landing-Page](https://github.com/JobConnect-AW/landing-page)      | develop | a2fc49a   | [feat: add footer, index.js, i18n.js](https://github.com/JobConnect-AW/landing-page/commit/a2fc49a) |                                             | 2025-04-24          |
| [Champa-Landing-Page](https://github.com/JobConnect-AW/landing-page)      | develop | 8edcafa   | [feat: add src/styles/modules header and variables](https://github.com/JobConnect-AW/landing-page/commit/8edcafa) |                                             | 2025-04-24          |
| [Champa-Landing-Page](https://github.com/JobConnect-AW/landing-page)      | develop | e570425   | [chore: Update .gitignore](https://github.com/JobConnect-AW/landing-page/commit/e570425) |                                             | 2025-04-24          |
| [Champa-Landing-Page](https://github.com/JobConnect-AW/landing-page)      | develop | 7862e72   | [feat: Create html and first favicon](https://github.com/JobConnect-AW/landing-page/commit/7862e72) |                                             | 2025-04-24          |


#### 5.2.1.5. Execution Evidence for Sprint Review.

En el Sprint 1, se logró un avance parcial en el desarrollo y despliegue de la landing page. Esta página presenta diversas secciones donde los usuarios pueden acceder a información clave sobre el producto y la startup. A continuación, se presentan algunas evidencias de este progreso.

Hero: La sección principal invita al usuario a ver más información sobre el servicio y probar el producto
![Hero](./img/Hero.png)

Beneficios: Esta sección presenta las principales ventajas que ofrece la plataforma tanto para trabajadores técnicos como para clientes que buscan servicios, destacando la facilidad de uso, seguridad y eficiencia

![Beneficios](./img/Beneficios.png)

Categorías de servicios: Esta sección muestra los tipos de servicios técnicos que se pueden encontrar en la plataforma, ayudando al usuario a identificar qué profesionales puede contratar

![Categorías de servicios](./img/Categorias.png)

Cómo funciona: Se explica el proceso paso a paso para utilizar la plataforma, tanto para trabajadores técnicos como para clientes

![Cómo funciona](./img/ComoFunciona.png)

Testimonios: Esta sección muestra experiencias de usuarios reales que han utilizado la plataforma, generando confianza en nuevos visitantes

![Testimonios](./img/Testimonios.png)

Estadísticas: Esta sección muestra con datos cuantitativos el impacto positivo de la plataforma en términos de usuarios registrados, servicios completados y satisfacción del cliente

![Estadísticas](./img/Estadisticas.png)

Contacto: Formulario que permite a los usuarios enviar consultas o solicitudes directamente desde la landing page

![Contacto](./img/Contacto.png)


#### 5.2.1.6. Services Documentation Evidence for Sprint Review.

Para este sprint no fue contemplada la evidencia de documentación de los servicios API.

#### 5.2.1.7. Software Deployment Evidence for Sprint Review.

Para la entrega del Sprint número 1, se desplegó la landing page completa en Netlify. Se configuró para que la rama principal utilizada fuera "main", ubicada en la raíz, siguiendo una estructura organizada de carpetas y archivos.

![Netifly deploy](./img/netifly-deploy.png)

#### 5.2.1.8. Team Collaboration Insights during Sprint.
