# Capítulo V: Product Implementation, Validation & Deployment

El equipo ha definido un conjunto de herramientas para garantizar una configuración de entorno de desarrollo coherente; de esta manera, se facilita una colaboración eficiente y el cumplimiento de los objetivos del proyecto. Estas herramientas abarcan diversas fases del ciclo de vida del producto MVP.

## 5.1. Software Configuration Management.

# Gestión de Proyectos

**Pivotal Tracker** es la herramienta principal que utiliza el equipo para gestionar el proyecto de manera ágil. Facilita la planificación, organización y el seguimiento del progreso de las historias de usuario, tareas y errores, empleando un enfoque basado en historias y priorización colaborativa.  
Ruta de referencia: [https://www.pivotaltracker.com](https://www.pivotaltracker.com)

**Whatsapp** es la plataforma que usamos para la comunicación en tiempo real entre los miembros del equipo. A través de grupos organizados por temas y funciones, realizamos reuniones, coordinaciones diarias y soporte instantáneo durante todo el proceso de desarrollo.

## Diseño de Producto UX/UI

**Figma** se utiliza como la herramienta principal para el diseño de interfaces gráficas (UI) y la experiencia de usuario (UX). Permite la colaboración simultánea entre varios miembros del equipo en la creación de prototipos interactivos, estructuras visuales y pruebas de diseño.  
Ruta de referencia: [https://www.figma.com](https://www.figma.com)

**UXPressia** complementa el trabajo de UX al posibilitar la creación y documentación de User Personas, Customer Journey Maps y Empathy Maps. Esto ayuda al equipo a comprender mejor a los usuarios finales y a alinear las decisiones de diseño con sus necesidades.  
Ruta de referencia: [https://uxpressia.com](https://uxpressia.com)

## Desarrollo de Software

**WebStorm** es el entorno de desarrollo integrado (IDE) que emplean los desarrolladores del equipo para escribir y depurar código en tecnologías web. Su integración con sistemas de control de versiones, linters y herramientas modernas de desarrollo lo convierte en un entorno robusto.  
Ruta de referencia: [https://www.jetbrains.com/webstorm](https://www.jetbrains.com/webstorm)

## Despliegue de Software

**Git** es el sistema de control de versiones utilizado para gestionar el historial de cambios en el código fuente. Permite a varios desarrolladores colaborar en paralelo, con control total sobre ramas, merges y versiones del proyecto.  
Ruta de referencia: [https://git-scm.com](https://git-scm.com)

## Documentación de Software y Gestión del Proyecto

**GitHub** se utiliza como repositorio remoto centralizado para almacenar y sincronizar el código del proyecto. También se emplea para la revisión del código (pull requests), registro de incidencias, documentación del proyecto y automatización de tareas de despliegue.  
Ruta de referencia: [https://github.com](https://github.com)

## Pruebas de Software

**Gherkin** es un sistema de etiquetado utilizado para describir los criterios de aceptación de la estructura de una user story.  
Ruta de referencia: [https://cucumber.io/docs/gherkin](https://cucumber.io/docs/gherkin)

## 5.1.1. Software Development Environment Configuration.

El proyecto seguirá las convenciones de flujo de trabajo establecidas por el modelo GitFlow para el control de versiones, utilizando GitHub como plataforma y sistema de control de versiones. A continuación, se detallará cómo se implementará GitFlow como WorkFlow de control de versiones, además de proporcionar los URL de los repositorios de GitHub para cada producto: Landing Page.

### 5.1.2. Source Code Management.

Hemos empleado Git Flow (<<cita>), para el desarrollo y mantenimiento de nuestro proyecto. Para ello, hemos creado 5 ramas principales, las cuale son Main, Hotfix, Release, Develop y feature. En este sentido, al inicializar el primer commit es en el main, desde el cual parte la rama develop, cada sección de nuestra landing page es una feature tiene su propia rama con la nomenclatura feature/<nombre_de_feature>, en donde se desarrolla cada sección por separado, como por ejemplo el Header, el footer o las secciones de nuestra landing. Luego, terminado el desarrollo de cada feature se hace un merge a la rama develop, donde se hace la unión de las secciones de la web, ya con la rama con un avance significativo (suele ser al termino de un sprint), se crea un nuevo release con nomenclatura semver (semantic versioning 2.0.0), donde
FORMA
122
se hace el testeo y documentación del código dentro del README.md. Además, utilizamos la rama HotFix para la solución de problemas en la rama main. Para esto, creamos una rama
hotfix/<nombre_de_hotfix>. Para finalizar, se sube a la rama main para la salida a producción.

Repositorios de GitHub:

Enlace para acceder a la organización de GitHub: https://github.com/UPC-PaxTech
Enlace para acceder a repositorio de la Landing Page: https://github.com/PaxTech-UPC/uTime-Landing-Page

### 5.1.3. Source Code Style Guide & Conventions.

#### Nomenclatura

- **Pascal Case**: Utilizaremos la nomenclatura Pascal Case para el nombramiento de nuestros componentes.
- **Camel Case**: Utilizaremos la nomenclatura Camel Case para el nombramiento de variables, funciones y otros elementos de programación.

#### HTML

- Crearemos nuestros componentes utilizando código HTML semántico.
- Seguiremos las convenciones estándar de HTML, tales como:
  - Declarar el documento HTML correctamente.
  - Utilizar **lowercase** para las etiquetas.
  - Asegurarnos de cerrar todas las etiquetas HTML.
  - Especificar los atributos **width** y **height** en las imágenes.
  - Mantener un buen formateo del código.

#### CSS

- Adoptaremos los principios de **utility-first** y **mobile-first** para la creación de nuestras clases.
- Emplearemos **Tailwind CSS** para este propósito.
- Además, seguiremos las convenciones estándar de CSS, como:
  - Mantener una buena indentación.
  - Realizar el reinicio de estilos.
  - Respetar la regla de cascada.
  - Gestionar correctamente la especificidad de los estilos.

#### Gherkin

- Para la implementación de los archivos de tipo **feature**, seguiremos el esquema establecido en los criterios de aceptación:
  - **Given** (Dado que), **When** (Cuando) y **Then** (Entonces).
  - Los **examples** estarán organizados en un cuadro y separados por el carácter `]`.

### 5.1.4. Software Deployment Configuration.

Hemos empleado el uso de un Software as Service llamado Netlify para el despliegue de nuestra landing page. Para esto, nos creamos una cuenta en Netlify y la conectamos con la cuenta de GitHub, la cual es creadora del repositorio. Después de esto, enlazamos el repositorio al hosting para que así tenga acceso al código. Para finalizar, configuramos tanto los comandos de inicialización como las variables de entorno y hacemos el deploy de nuestro proyecto.

Además, mediante Github Actions logramos implementar CI/CD en Netlify, el cual escucha los cambios en la rama main y hace un deploy a producción.

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
