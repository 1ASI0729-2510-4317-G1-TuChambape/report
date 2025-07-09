
<h1 align="center">
<strong style="font-size:25px;">Universidad Informe de Trabajo Final</strong>
</h1>

---

<p align="center"><strong>Universidad Peruana de Ciencias Aplicadas</strong></p>

<p align="center">
  <img src="assets/logos/LogoUPC.png" width="180" />
</p>

<p align="center">Ingenieria de Software</p>
<p align="center">5to ciclo</p>

---

<p align="center"><strong>Código: </strong>1ASI0729</p>
<p align="center"><strong>Curso:</strong> Aplicaciones Open Source</p>
<p align="center"><strong>Sección:</strong> 4317</p>

<p align="center"><strong>Docente:</strong> Alberto Wilmer Sanchez Seña</p>

<p align="center"><strong>StartUp: </strong> Chads</p>
<p align="center"><strong>Proyecto:</strong> TuChambape</p>



## Integrantes:
<div align="center">

| Nombres y Apellidos                  | Codigo     |
| ------------------------------------ | ---------- |
| Cossar Sanchez, Eduardo Jose       | U202312109 |
| Mora Blas,  Diego Alonzo             | U20231c069 |
| Remon Fernandez, Roy  | u20221b778 |
| Jonseck Choque, Oliver | U202312912 |
| Oroncoy Almeyda, Alejandro Daniel | U202313397 |
| Osores Marchese, Pietro | U202310971 |

</div>

<p align="center">Abril 2025</p>

# Registro de Versiones del Informe

| Version | Fecha      | Autor                                          | Descripción de modificación                                                |
| ------- | ---------- | ---------------------------------------------- | -------------------------------------------------------------------------- |
| 1ra     | 25/04/2025 | Oroncoy, Mora, Valdizan, Fernandez, Jonseck | TB1: Se realizo los capitulos 1, 2, 3, 4 y el primer sprint del capitulo 5 |
| 2da     | 15/05/2025 | Oroncoy, Mora, Valdizan, Fernandez, Jonseck | TP1: Se realizo el segundo sprint del capitulo 5 y las vistas de la aplicacion a partir de sus bounded context con angular |

# Project Report Collaboration Insights

## **TP1**

Para el desarrollo de la TP1 nos hemos dividido como equipo diferentes tareas para cada seccion del informe.

| Integrantes            | Tareas Asignadas                                                                                                                                       |
| ---------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Oliver Jonseck            |    Realizo las vistas de iniciar sesion, registrarse y recuperar contraseña                                                                          |
| Diego Mora          |  Realizo las vistas de buscar tecnico para el cliente y el apartado del pago de los planes para el tecnico|
|Roy Fernandez         |  Realizo el inicio para el cliente y el trabajador, tambien hizo la vista buscar oferta                                                                                                      |
| Alejandro Oroncoy      |   Realizo las vistas de todo el apartado de ofertas para el cliente y para el trabajador                                                                         |
| Eduardo Cossar         |   Realizo la vista de comparar perfiles de tecnicos y las vistas de la configuracion y el perfil para el trabajador                    |
| Daniel Valdizan |   Realizo la vista de configuracion y perfil para el cliente                                    |


# Tabla de contenidos


[Capítulo I: Introducción](#capítulo-i-introducción)
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

**Student Outcome 3**

| Criterio específico                                                    | Acciones realizadas                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    | Conclusiones                                                                                                                                                                                                                                                                                                                                                                            |
| ---------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Comunica oralmente con efectividad a diferentes rangos de audiencia.   | **TB1**<br><br>**Oliver Jonseck:** Durante el desarrollo del TB1, participé activamente en las reuniones grupales, donde compartí mis ideas y opiniones de forma oral. Además, colaboré en la redacción del documento, asegurándome de que todas las decisiones acordadas fueran plasmadas de manera clara y precisa.<br><br>**Diego Mora :** En el TB1, trabajé junto al equipo expresando mis propuestas durante las reuniones y escuchando las opiniones de los demás. También contribuí a la elaboración escrita del informe, donde dejamos constancia de las decisiones tomadas de manera colaborativa.<br><br>**Roy Fernandez :** Mi aporte en el TB1 se basó en mantener una comunicación fluida con el equipo, participando de manera activa en cada reunión. Posteriormente, ayudé en la redacción del documento, organizando las ideas de forma ordenada para una mejor comprensión de los acuerdos alcanzados.<br><br>**Eduardo Cossar:** Para el TB1, intervine en las reuniones grupales proponiendo ideas y discutiendo alternativas con mis compañeros. Asimismo, participé en la redacción del documento final, reflejando correctamente el consenso logrado entre todos.<br><br>**Alejandro Oroncoy :** Durante la preparación del TB1, contribuí expresando mis puntos de vista y escuchando las sugerencias de los demás en las reuniones orales. También colaboré en la comunicación escrita, detallando de forma clara las decisiones que se tomaron en equipo.<br><br>**Daniel Valdizan :** En el desarrollo del TB1, trabajé activamente en las reuniones, aportando ideas de forma oral y respetando las opiniones del grupo. Además, participé en la elaboración del documento escrito, asegurándome de que cada acuerdo estuviera debidamente registrado. <br><br>**TP1**<br><br>**Diego Mora** presentó en la reunión de equipo las vistas de “Iniciar sesión”, “Registrarse” y “Recuperar contraseña”, explicando el flujo de navegación y los mensajes de validación.<br> **Daniel Valdizan:** expuso la lógica y el diseño de la vista de “Buscar técnico” para el cliente y detalló el proceso de pago de los planes para el técnico.<br> **Roy Fernandez:** describió ante el grupo el diseño de las pantallas de inicio para cliente y trabajador, así como la funcionalidad de “Buscar oferta”.<br> **Oliver Jonseck** explicó el comportamiento y la estructura de todas las vistas de ofertas, tanto para el cliente como para el trabajador.<br> **Eduardo Cossar** mostró las pantallas de “Comparar perfiles de técnicos” y las vistas de configuración y perfil del trabajador, respondiendo preguntas sobre casos de uso.<br> **Alejandro Oroncoy:** presentó las vistas de configuración y perfil del cliente, aclarando estilos y componentes reusables. <br><br>**TB2**<br><br>**Diego Mora**  compartió en la reunión las vistas de “Iniciar sesión”, “Registrarse” y “Recuperar contraseña”, explicando cómo se conectan entre sí y detallando los mensajes de validación incluidos.<br> **Daniel Valdizan:** presentó la lógica detrás de la vista de “Buscar técnico” para el cliente, además de explicar el proceso de pago que seguirán los técnicos para adquirir planes.<br> **Roy Fernandez:** mostró el diseño de las pantallas principales para cliente y trabajador, y explicó la implementación de la funcionalidad “Buscar oferta”.<br> **Oliver Jonseck**se encargó de detallar la estructura y funcionamiento de las vistas de ofertas desde ambas perspectivas: cliente y trabajador.<br> **Eduardo Cossar** expuso las vistas de “Comparar perfiles de técnicos”, junto con las secciones de perfil y configuración del trabajador, resolviendo dudas sobre su integración con los casos de uso.<br> **Alejandro Oroncoy:** explicó las vistas del perfil y configuración del cliente, precisando el uso de estilos y componentes reutilizables. <br><br>**TF**<br><br>**Diego Mora** mostro en la reunión de equipo las versiones finales de las vistas de “Iniciar sesión”, “Registrarse” y “Recuperar contraseña”, explicando el flujo de navegación y los mensajes de validación.<br> **Pietro Osores:** expuso la lógica y el diseño de la vista de “Buscar técnico” para el cliente y detalló el proceso de pago de los planes para el técnico.<br> **Roy Fernandez:** completo el user context tanto en el frontend como en el backend.<br> **Oliver Jonseck** corrigio el documento y realizo correciones a algunas vistas ya realizadas.<br> **Eduardo Cossar** mostró las pantallas de “Comparar perfiles de técnicos” y las vistas de configuración y perfil del trabajador, asi como su apartado en el backend.<br> **Alejandro Oroncoy:** presentó las vistas de configuración y perfil del cliente, corrigiendo componentes visuales y realizando su respectiva parte del backend.|**TB1**<br>Para la TB1, el equipo trabajó colaborativamente y se logró una participación activa de cada uno de los integrantes. Se realizaron reuniones grupales en la que cada miembro compartió sus ideas de manera oral o escrita y, a partir de ello, se logró una toma de decisiones en conjunto la cual benefició al equipo en la toma de decisiones y en la ejecución de tareas.  <br>**TP1**<br> Durante TP1, el equipo demostró una comunicación oral clara y estructurada al exponer cada uno sus implementaciones, facilitando el feedback inmediato y la coordinación efectiva para alinear el diseño y la funcionalidad del producto. <br>**TB2**<br> Durante TB2, el equipo mantuvo una comunicación oral clara y ordenada al presentar sus avances individuales, lo que permitió recibir retroalimentación en el momento y coordinar eficazmente el diseño y funcionamiento del producto. <br>**TF**<br> En TF, cada integrante explicó sus implementaciones de manera clara y estructurada, lo que favoreció una retroalimentación inmediata y una coordinación eficiente para asegurar la coherencia entre el diseño y la funcionalidad del producto.|
|   |
| Comunica por escrito con efectividad a diferentes rangos de audiencia. | **TB1**<br><br>**Oliver Jonseck:** En el TB1, aporté en la redacción del documento, plasmando de manera clara las ideas que fueron acordadas en las reuniones.<br><br>**Diego Mora :** Durante el TB1, contribuí a la elaboración escrita del informe, explicando de forma precisa los acuerdos logrados en equipo.<br><br>**Roy Fernandez :** Mi participación en el TB1 incluyó el desarrollo de habilidades de comunicación escrita, dejando registradas las ideas consensuadas durante las reuniones.<br><br>**Eduardo Cossar:** En el desarrollo del TB1, colaboré en redactar el documento final, explicando adecuadamente las ideas discutidas en las sesiones de grupo.<br><br>**Alejandro Oroncoy :** Para el TB1, me enfoqué en la redacción de las ideas trabajadas en equipo, asegurando que estuvieran correctamente explicadas en el documento.<br><br>**Daniel Valdizan :** En el TB1, participé en la redacción del documento, comunicando de manera efectiva los acuerdos logrados en nuestras reuniones de trabajo.    <br><br>**TB2**<br><br>   **Diego Mora :** redactó la documentación técnica de las vistas de inicio de sesión, registro y recuperación de contraseña, incluyendo diagramas de flujo y validaciones.<br> **Daniel Valdizan :** elaboró el manual de usuario para la búsqueda de técnicos y el proceso de pago, con capturas de pantalla anotadas.<br> **Roy Fernandez :** documentó los casos de uso y los requisitos funcionales de las pantallas de inicio cliente/trabajador y la búsqueda de ofertas.<br> **Oliver Jonseck** preparó un Informe de Diseño de Interfaz para las vistas de ofertas, detallando la interacción y los componentes reutilizados.<br> **Eduardo Cossar** escribió especificaciones para la funcionalidad de “Comparar perfiles” y las pantallas de configuración y perfil de trabajador, con guías de estilo.<br> **Alejandro Oroncoy:** entregó un documento con las descripciones de las vistas de configuración y perfil del cliente, describiendo props y estados de los componentes. <br><br>**TP1**<br><br>   **Diego Mora :** redactó la documentación técnica de las vistas de inicio de sesión, registro y recuperación de contraseña, incluyendo diagramas de flujo y validaciones.<br> **Daniel Valdizan :** elaboró el manual de usuario para la búsqueda de técnicos y el proceso de pago, con capturas de pantalla anotadas.<br> **Roy Fernandez :** documentó los casos de uso y los requisitos funcionales de las pantallas de inicio cliente/trabajador y la búsqueda de ofertas.<br> **Oliver Jonseck** preparó un Informe de Diseño de Interfaz para las vistas de ofertas, detallando la interacción y los componentes reutilizados.<br> **Eduardo Cossar** escribió especificaciones para la funcionalidad de “Comparar perfiles” y las pantallas de configuración y perfil de trabajador, con guías de estilo.<br> **Alejandro Oroncoy:** entregó un documento con las descripciones de las vistas de configuración y perfil del cliente, describiendo props y estados de los componentes.<br><br>**TF**<br><br>   **Diego Mora :** redactó la documentación técnica de las vistas de inicio de sesión, registro y recuperación de contraseña, incluyendo diagramas de flujo y validaciones.<br> **Daniel Valdizan :** elaboró el manual de usuario para la búsqueda de técnicos y el proceso de pago, con capturas de pantalla anotadas.<br> **Roy Fernandez :** documentó los casos de uso y los requisitos funcionales de las pantallas de inicio cliente/trabajador y la búsqueda de ofertas.<br> **Oliver Jonseck** preparó un Informe de Diseño de Interfaz para las vistas de ofertas, detallando la interacción y los componentes reutilizados.<br> **Eduardo Cossar** escribió especificaciones para la funcionalidad de “Comparar perfiles” y las pantallas de configuración y perfil de trabajador, con guías de estilo.<br> **Alejandro Oroncoy:** entregó un documento con las descripciones de las vistas de configuración y perfil del cliente, describiendo props y estados de los componentes.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             | **TB1**<br>Para el TB1, el equipo comunicó las ideas tomadas en el documento de manera conjunta y equitativa, siendo todos parte y responsables del desarrollo del informe.  <br>**TB1**<br>   La comunicación escrita en TP1 fue efectiva: cada integrante produjo documentación clara y detallada de sus secciones, lo que aseguró la comprensión compartida de los requisitos y facilitó la continuidad del desarrollo por parte de todo el equipo.  <br>**TB2**<br>  La comunicación escrita durante el desarrollo del TB2 fue clara y efectiva: cada miembro del equipo elaboró documentación precisa y bien estructurada sobre su sección, lo que permitió una comprensión común de los requisitos y aseguró la continuidad fluida del trabajo en equipo.  <br>**TF**<br>   La comunicación escrita en TF fue correcta: cada integrante produjo documentación clara de sus secciones, lo que aseguró la el trabajo en conjunto de los requisitos  

# Capítulo I: Introducción

## 1.1. Startup Profile
Nuestra Startup “Chads” presenta una nueva aplicación llamada “TuChambape”, diseñada para conectar a personas con estudios técnicos con clientes que requieren servicios especializados, como electricidad, plomería, carpintería, entre otros. Esta plataforma busca brindar oportunidades laborales flexibles a técnicos calificados, permitiéndoles ofrecer sus servicios como freelancers y gestionar sus trabajos de forma independiente. Para ello, se investigarán plataformas similares y se diseñará una solución tecnológica funcional, centrada en la experiencia del usuario y la confianza entre las partes.

### 1.1.1. Descripción de la Startup

### 1.1.2. Perfiles de integrantes del equipo

#### 1.1.2.1 Diego Alonzo Mora Blas
Estudiante de la carrera de ingeniería de software en la UPC, cuento con habilidades como el aprendizaje rápido el cual me ha llevado a practicar y conocer diversas áreas como lo son la programación, la ciberseguridad y redes. Tengo el honor de trabajar con mi equipo el cual estoy seguro que nos aseguraremos de presentar un trabajo al nivel.

<img src="assets/images/profile-pictures/DiegoMora.PNG"  width="180" />

#### 1.1.2.2 Eduardo Jose Cossar Sanchez
Mi nombre es Eduardo Cossar. Soy estudiante de la carrera de Ingeniería de Software, tengo 19 años y actualmente estoy cursando el quinto ciclo en la UPC. Me considero una persona responsable y comprometida con un gran interés por la tecnología. Como integrante de este equipo, me comprometo a brindar todo mi apoyo y participación activa para afrontar los desafíos que se presenten y dar lo mejor de mí para lograr el éxito de este proyecto.

 <img src="https://files.catbox.moe/mw437z.png" alt="kevin image" width="200">


#### 1.1.2.3 Alejandro Daniel Oroncoy Almeyda
Mi nombre es Alejandro Oroncoy. Tengo 19 años, soy estudiante de la carrera de ingeniería de software, estoy en 5to ciclo. Me considero una persona proactiva, autodidacta y orientada a objetivos. 

<img src="https://files.catbox.moe/v1iqn9.png" alt="gael image" width="200"> 

#### 1.1.2.4 Roy Fernández Remón

Me llamo Roy Fernández Remón y estudio la carrera de Ingeniería de Software, actualmente estoy en el 6to ciclo de la carrera. Soy una persona dedicada a mis estudios y trabajos, y me gusta ser responsable con las actividades académicas.

<img src="assets/images/profile-pictures/Roy%20Fernandez%20Remon.jpg"  width="180" />

#### 1.1.2.5 Daniel Valdizán Grijalba

Mi nombre es Daniel Valdizán Grijalba, tengo 19 años y estoy cursando la carrera de Ingeniería de Software en la UPC. Me considero una persona que trabaja bien en equipo y maneja estar bajo presión. Me comprometo a apoyar de la mejor manera al grupo en este trabajo.

<img src="assets/images/profile-pictures/DanielV.PNG"  width="180" />

#### 1.1.2.6 Oliver Jonseck Choque

Mi nombre es Oliver Jonseck Choque, estudio ingenieria de software y poseo 19 años. Soy una persona algo distraida, pero sin embargo siempre trato de dar lo mejor que puedo. Soy autodidacta, alegre y llego a ser responsable.

<img src="assets/images/profile-pictures/Integrante-Oliver.jpeg" width="180"/>

#### 1.1.2.7 Osores Marchese Pietro

Soy estudiante de Ingeniería de Software con un fuerte interés en la innovación tecnológica y el diseño centrado en el usuario. Me considero una persona organizada, con habilidades para liderar y analizar problemas de forma estructurada. En este proyecto, me encargué de definir los perfiles del equipo, analizar los antecedentes del problema y desarrollar todo el enfoque Lean UX, estableciendo así las bases conceptuales de nuestra solución.

<img src="https://github.com/user-attachments/assets/3d5ba274-14f6-4c68-9a08-525ea633787b" alt="Foto de Pietro" style="width: 20%; height: auto;">
<br><br>

## 1.2. Solution Profile

En esta sección, se presenta en detalle el perfil de la solución, respaldado por
antecedentes sólidos y construido paso a paso siguiendo el proceso de
Lean UX

### 1.2.1 Antecedentes y problemática

En el Perú, una gran cantidad de trabajadores técnicos ofrecen sus servicios de manera informal, sin una plataforma que los respalde ni que facilite su visibilidad profesional. Esto genera desconfianza entre los clientes, dificulta el crecimiento de estos profesionales y reduce las oportunidades de empleo de calidad. JobI surge como una solución digital que busca formalizar esta relación, conectando a técnicos con clientes de forma segura, eficiente y profesional.

**What (Qué)**

##### ¿Cuál es el problema?

El problema principal es la falta de una plataforma especializada que conecte de forma efectiva a trabajadores técnicos independientes (electricistas, gasfiteros, carpinteros, etc.) con clientes que necesitan sus servicios. En la actualidad, muchos de estos profesionales dependen de métodos informales como recomendaciones boca a boca, redes sociales o grupos de WhatsApp, lo que limita su visibilidad, dificulta la generación de confianza y reduce sus oportunidades de crecimiento económico.

##### ¿Cuál es la relación con la persona en cuestión?

JobI busca resolver este problema proporcionando una plataforma digital que conecte a técnicos verificados con clientes en busca de servicios confiables. A través de la digitalización del proceso de búsqueda, solicitud y pago, JobI no solo mejora la experiencia del cliente, sino que también permite a los trabajadores técnicos formalizar sus servicios, aumentar su visibilidad y acceder a más oportunidades laborales. Según un informe del BID (2021), las plataformas digitales que promueven el empleo formal pueden incrementar hasta en 40% los ingresos de trabajadores independientes en América Latina.


**Who (Quién)**

##### ¿Quiénes están involucrados?

Los principales involucrados son los trabajadores técnicos independientes (electricistas, gasfiteros, técnicos de aire acondicionado, etc.), y los clientes que requieren sus servicios para el hogar, oficinas o negocios. También se incluyen microempresas que contratan técnicos de manera eventual..

##### ¿A quiénes le sucede el problema?

El problema afecta principalmente a los técnicos independientes, quienes no cuentan con medios eficientes para mostrar sus servicios ni herramientas para captar clientes nuevos. También afecta a los clientes, quienes se enfrentan a la incertidumbre de no encontrar técnicos de confianza de forma rápida y segura. Según el Ministerio de Trabajo (2022), casi un 60% de los trabajadores técnicos en el Perú no tienen presencia digital.

**Where (Dónde)**

##### ¿En dónde ocurre el problema?

 Este problema ocurre principalmente en zonas urbanas del Perú donde hay una alta demanda de servicios técnicos, pero los trabajadores aún gestionan sus actividades mediante medios informales como llamadas, mensajes de texto o publicaciones esporádicas en redes sociales, lo que genera ineficiencia y desconfianza.

##### ¿En dónde nos enfocaremos?

Nos enfocaremos inicialmente en Lima, donde existe un alto volumen de clientes potenciales y trabajadores técnicos con acceso básico a tecnología móvil e internet. Estas zonas permiten una implementación escalable con impacto real y medible.

**When (Cuándo)**

##### ¿Cuándo sucede el problema?

El problema se presenta cada vez que un cliente requiere un servicio técnico y no encuentra rápidamente a un proveedor confiable, o cuando el trabajador técnico pierde oportunidades por no tener un canal activo de contacto o visibilidad en línea.

##### ¿Cuándo utiliza el cliente el producto?

El cliente utilizaría JobI al momento de necesitar un servicio técnico específico. La plataforma permitirá buscar por tipo de servicio, ubicación y disponibilidad. Del lado del técnico, el producto será utilizado tanto para gestionar sus citas como para visualizar reseñas, actualizar su disponibilidad y recibir pagos.

**Why (Por qué)**

##### ¿Cuál es la causa del problema?

Las principales causas del problema incluyen la informalidad del sector técnico, la baja digitalización de los trabajadores independientes y la falta de plataformas especializadas que respondan a sus necesidades específicas. Si bien existen plataformas como Workana o Clic, estas no están orientadas a servicios presenciales ni al perfil técnico, lo que deja un vacío en el mercado. Además, muchos trabajadores técnicos carecen de conocimientos para usar plataformas complejas o poco localizadas.

**How (Cómo)**

##### ¿En qué condiciones los clientes usan nuestro producto?

A través de una aplicación web o móvil ligera y fácil de usar, disponible en dispositivos con conexión a internet. JobI ofrecerá funcionalidades como búsqueda por cercanía, perfiles verificados, historial de servicios, sistema de pago seguro y soporte post-servicio. Para los técnicos, la interfaz permitirá recibir solicitudes, programar citas, subir evidencias de trabajos y recibir evaluaciones de clientes.

**How much (Cuánto)**

##### Estadísticas que sustentan la problemática.

Según el Instituto Nacional de Estadística e Informática (INEI, 2023), más del 70% de los trabajadores técnicos en Perú operan de manera informal, sin acceso a herramientas digitales que les permitan organizar y formalizar sus servicios. Esta situación conlleva a una baja visibilidad, desconfianza por parte de los clientes y pérdida de oportunidades laborales.

De acuerdo al Ministerio de Trabajo y Promoción del Empleo (MTPE, 2022), solo el 18% de los técnicos independientes en zonas urbanas usa plataformas digitales para la promoción o gestión de sus servicios. La gran mayoría depende de llamadas telefónicas, grupos de WhatsApp o recomendaciones informales para obtener trabajo.

Un estudio de la CAF (Banco de Desarrollo de América Latina, 2021), indica que la digitalización puede aumentar los ingresos de los trabajadores independientes hasta en un 40%, y mejorar la percepción de confiabilidad por parte de los clientes en un 60%.

### 1.2.2. Lean UX Process

El Lean UX es un enfoque de diseño centrado en la colaboración, la retroalimentación continua y la mejora iterativa. Se enfoca en construir productos útiles y funcionales desde etapas tempranas, validando constantemente las ideas con los usuarios reales. En el caso de JobI, este enfoque es esencial para crear una plataforma eficiente y confiable que conecte a trabajadores técnicos con clientes que necesitan servicios de calidad.

#### 1.2.2.1. Lean UX Problem Statements

En el mercado peruano de servicios técnicos, predomina actualmente la informalidad. La mayoría de contrataciones se da a través de redes personales o recomendaciones boca a boca, lo que deja a muchos trabajadores sin presencia digital y limita su acceso a clientes. A la vez, los clientes enfrentan una gran incertidumbre respecto a la calidad, confiabilidad y seguridad del servicio.

Aunque existen aplicaciones de contratación de servicios, estas no han logrado resolver la necesidad de verificación, confianza y facilidad de uso, especialmente en el segmento de técnicos independientes. Esta falta de soluciones efectivas genera una gran oportunidad para una plataforma especializada que conecte de forma formal, accesible y confiable a técnicos con clientes.

JobI tiene como proposito cerrar esta brecha mediante una plataforma que permita a los técnicos visibilizar sus habilidades y construir reputación digital, mientras ofrece a los clientes confianza, rapidez y seguridad en la contratación.

**¿Cómo podemos diseñar una plataforma accesible que permita a los trabajadores técnicos visibilizar sus habilidades y a los clientes encontrar y contratar profesionales de forma confiable y segura?**

#### 1.2.2.2. Lean UX Assumptions

JobI está diseñado para facilitar el contacto entre trabajadores técnicos e independientes y personas que necesitan servicios confiables en el hogar o el negocio. Asumimos que la plataforma debe ser intuitiva, permitir mostrar portafolios y valoraciones, y ofrecer filtros eficientes para encontrar al profesional adecuado.

a. Supuestos sobre usuarios (Target Groups):
- Técnicos independientes (electricistas, gasfiteros, técnicos en refrigeración, etc.) en zonas urbanas del Perú.
- Clientes residenciales y pequeños negocios que requieren servicios técnicos ocasionales.

b. Objetivos de los usuarios:
- Técnicos: conseguir más clientes, mejorar su reputación, obtener ingresos estables.
- Clientes: encontrar profesionales confiables, contratar con rapidez, evitar malas experiencias.

c. Características clave del producto para satisfacer objetivos:
- Perfiles profesionales verificados (identidad y experiencia).
- Sistema de calificaciones y comentarios de clientes.
- Filtros por ubicación, especialidad y precios.
- Interfaz simple y optimizada para móviles.
- Chat interno seguro para comunicación directa.

d. Definition of Done y Métricas de Éxito (Business Outcomes):
- Al menos 1,000 técnicos registrados con perfiles completos en los primeros 6 meses.
- 70% de satisfacción del cliente medida por calificaciones y encuestas.
- Reducción del 50% en incidentes de servicio reportados en los primeros 4 meses.
- 60% de retención mensual de usuarios activos.
- Generación de ingresos sostenibles a través de comisiones y cuentas premium.

#### 1.2.2.3. Lean UX Hypothesis Statements

**Hipótesis 1:**  
Creemos que permitir la creación de perfiles verificados para trabajadores técnicos logrará aumentar su visibilidad y la cantidad de contrataciones.
_Sabremos que esto es cierto cuando al menos el 60% de los técnicos registrados reporten haber conseguido nuevos clientes a través de JobI en los primeros 3 meses._

**Hipótesis 2:**  
Creemos que implementar un sistema de calificaciones y reseñas para clientes logrará que se sientan más seguros al contratar a un técnico.
_Sabremos que esto es cierto cuando el 70% de los clientes encuestados indiquen sentirse más confiados al contratar mediante JobI que por medios tradicionales._

**Hipótesis 3:**  
Creemos que ofrecer filtros de búsqueda por ubicación, especialidad y precio para clientes logrará reducir el tiempo necesario para encontrar al técnico adecuado.
_Sabremos que esto es cierto cuando el tiempo promedio desde la búsqueda hasta la contratación disminuya en un 40%._

**Hipótesis 4:**  
Creemos que contar con una plataforma optimizada para móviles para técnicos y clientes logrará incrementar la frecuencia de uso y la retención mensual de usuarios.
_Sabremos que esto es cierto cuando el 80% de los usuarios activos accedan desde el celular y la tasa de retención mensual supere el 50%._

**Hipótesis 5:**  
Creemos que mostrar reseñas verificadas y puntuaciones de reputación para técnicos logrará mejorar la calidad del servicio ofrecido.
_Sabremos que esto es cierto cuando las calificaciones promedio de los técnicos aumenten en un 20% durante los primeros 6 meses._

**Hipótesis 6:**
Creemos que ofrecer un sistema de mensajería segura dentro de la aplicación para clientes y técnicos logrará mejorar la comunicación y reducir los errores en la prestación del servicio.
_Sabremos que esto es cierto cuando la tasa de cancelaciones de servicios disminuya en un 30% y los reportes por mala comunicación se reduzcan notablemente._

#### 1.2.2.4. Lean UX Canva

<img src="https://files.catbox.moe/9b3tux.jpg" alt="lean ux canva" width="200">

#### 1.3. Segmento Objetivo

##### Trabajadores Técnicos Independientes

**Aspectos demográficos:**
- Sexo: Masculino y Femenino  
- Edad: 20-55 años  

**Aspectos geográficos:**
- Nacionalidad: Peruana  
- Departamento: Lima  

**Aspectos psicográficos:**
- Desean incrementar su visibilidad profesional y captar más clientes.  
- Buscan oportunidades de formalizar su trabajo y generar confianza en sus servicios.  
- Tienen interés en una plataforma digital sencilla que les permita promocionar sus habilidades.  
- Están dispuestos a recibir retroalimentación mediante valoraciones para mejorar su reputación laboral.

##### Usuarios que requieren servicios técnicos

**Aspectos demográficos:**
- Sexo: Masculino y Femenino  
- Edad: 25-60 años  

**Aspectos geográficos:**
- Nacionalidad: Peruana  
- Departamento: Lima Metropolitana  

**Aspectos psicográficos:**
- Desean encontrar profesionales técnicos confiables y con buenas referencias.  
- Buscan una plataforma práctica para comparar opciones por especialidad, precios y cercanía.  
- Valoran la rapidez y facilidad al momento de contratar un servicio técnico.  
- Quieren tener seguridad y confianza durante el proceso de contratación, evitando fraudes o estafas.

# Capítulo II: Requirements Elicitation & Analysis
## 2.1 Competidores.

Hemos identificado tres competidores clave en el mercado peruano que ofrecen soluciones para conectar a profesionales independientes con potenciales clientes:

- **Chambea**  
Aplicación móvil peruana diseñada para conectar a emprendedores y trabajadores independientes con posibles clientes en diversas categorías, como tecnología, comida, mascotas, delivery, automóviles y finanzas.

- **Workana**  
Plataforma en línea que opera en varios países de América Latina, incluyendo Perú, enfocada en conectar a freelancers con empresas que buscan profesionales para proyectos en áreas como programación, diseño, traducción, marketing y más.

- **Clic**  
Hub digital que ofrece servicios profesionales en diversos rubros, como medicina, psicología, nutrición, fisioterapia, derecho y consultoría. A través de su aplicación, las personas pueden contactar a especialistas y coordinar servicios según sus necesidades.

### 2.1.1 Análisis competitivo.

<table>
  <thead>
    <tr>
      <th>¿Por qué llevar a cabo este análisis?</th>
      <td colspan="4">Se llevó a cabo este análisis porque queremos ofrecer un mejor servicio a través de la recopilación de información de nuestros competidores.</td>
    </tr>
    <tr>
      <th></th>
      <th>TuChamba</th>
      <th>Chambea</th>
      <th>Workana</th>
      <th>Clic</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>Perfil</th>
      <td>Plataforma peruana que conecta trabajadores técnicos independientes con clientes</td>
      <td>App móvil que conecta emprendedores y trabajadores independientes con clientes</td>
      <td>Plataforma de freelancers para proyectos profesionales en LATAM</td>
      <td>App que conecta profesionales de salud y consultoría con clientes</td>
    </tr>
    <tr>
      <th>Ventaja competitiva</th>
      <td>Formalización y crecimiento de técnicos</td>
      <td>Diversidad en categorías y simplicidad</td>
      <td>Alcance regional y sistema de reputación</td>
      <td>Especialización en salud y profesiones específicas</td>
    </tr>
    <tr>
      <th>Perfil de marketing</th>
      <td>Clientes que requieren servicios técnicos y trabajadores independientes</td>
      <td>Emprendedores, independiente y clientes generales</td>
      <td>Empresas que requieren freelancers calificados</td>
      <td>Personas que necesitan servicios profesionales específicos</td>
    </tr>
    <tr>
      <th>Estrategias de marketing</th>
      <td>Publicidad en redes sociales</td>
      <td>Presencia en medios locales, redes sociales</td>
      <td>SEO, anuncios pagos, recomendaciones</td>
      <td>Promociones online</td>
    </tr>
    <tr>
      <th>Perfil de producto</th>
      <td>Directorio de técnicos, calificaciones - chat, pagos seguros</td>
      <td>Directorio de emprendedores por categoría</td>
      <td>Proyectos, perfiles, contrataciones y pagos</td>
      <td>Agendamiento, perfiles profesionales, contacto directo</td>
    </tr>
    <tr>
      <th>Precio & Costos</th>
      <td>Modelo Freemium</td>
      <td>Uso gratuito con modelos futuros de membresía</td>
      <td>Comisión por proyecto y opciones premium</td>
      <td>Tarifas por servicio profesional</td>
    </tr>
    <tr>
      <th>Canales de Distribución</th>
      <td>Web y app móvil</td>
      <td>App móvil</td>
      <td>Web</td>
      <td>Web y app</td>
    </tr>
  </tbody>
</table>

<table>
  <thead>
    <tr>
      <th></th>
      <th>TuChamba</th>
      <th>Chambea</th>
      <th>Workana</th>
      <th>Clic</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>Fortalezas</th>
      <td>Enfoque en servicios técnicos, confianza, formalización</td>
      <td>App local, variedad de rubros, sencillez</td>
      <td>Escala internacional, reputación, variedad de profesionales</td>
      <td>Especialización en profesiones clave, facilidad de uso</td>
    </tr>
    <tr>
      <th>Debilidades</th>
      <td>Aún en etapa inicial, menor alcance</td>
      <td>Menor formalidad y validación de perfiles</td>
      <td>Competencia alta, dificultad para destacar</td>
      <td>Enfocado solo en rubros específicos</td>
    </tr>
    <tr>
      <th>Oportunidades</th>
      <td>Ampliar servicios, alianzas con gremios y empresas</td>
      <td>Monetización a futuro, expansión a otros países</td>
      <td>Mayor presencia en mercados emergentes</td>
      <td>Ampliar rubros profesionales, integrar IA</td>
    </tr>
    <tr>
      <th>Amenazas</th>
      <td>Imitación del modelo, entrada de grandes plataformas</td>
      <td>Saturación de mercado, apps similares</td>
      <td>Nuevas plataformas, cambios en la demanda</td>
      <td>Poca diferenciación en rubros nuevos</td>
    </tr>
  </tbody>
</table>

### 2.1.2 Estrategias y tácticas frente a competidores

Desarrollar estrategias y tácticas efectivas para enfrentar a nuestros competidores requiere de un enfoque centrado en nuestras fortalezas tecnológicas, la experiencia del usuario y el conocimiento profundo del mercado peruano. A continuación, se presentan estrategias clave para obtener una ventaja competitiva:

- Diferenciación mediante la formalización de trabajadores técnicos: JobConnect puede posicionarse como la plataforma que impulsa la formalización laboral, brindando perfiles verificados, procesos seguros y herramientas de gestión para trabajadores técnicos como electricistas, plomeros, gasfiteros y otros oficios.

- Enfoque en la calidad y confiabilidad del servicio: Implementar un sistema robusto de calificaciones, reseñas y verificación de identidad, generando confianza tanto en usuarios como en profesionales técnicos.

- Plataforma centrada en servicios técnicos presenciales y por zonas: A diferencia de otras plataformas más generales o remotas, JobConnect puede optimizar su algoritmo para conectar por proximidad geográfica, asegurando rapidez en la atención y ahorro en costos de desplazamiento.


## 2.2 Entrevistas

Con el objetivo de comprender a profundidad las necesidades, expectativas y problemáticas de nuestros usuarios potenciales, se realizaron entrevistas semiestructuradas a representantes de los segmentos

### 2.2.1 Diseño de entrevistas

#### Entrevistas segmento 01: Trabajadores Técnicos Independientes

**Preguntas generales:**
- ¿Cuál es su edad y distrito?
-  ¿Cuál es su ocupación principal y cuantos años de experiencia tiene en el rubro?
- ¿De que forma consigue clientes actualmente o que métodos utiliza (redes sociales, contactos, etc.)?
- ¿Ha tenia desconfianza por parte de los clientes? ¿Cómo los maneja?
- ¿Qué dispositivos usa frecuente para gestionar su trabajo?
- ¿Qué funcionalidades esperaría de una plataforma que lo conecto con clientes?
- Qué información le gustaría incluir a su perfil para generar confianza?

**Preguntas complementarias:**
- ¿Cómo describe su estilo de trabajo actualmente?
- ¿Prefiere recibir solicitudes de clientes por WhatsApp, llamadas o mensajes en un app?

#### Entrevistas segmento 02: Usuarios que requieren servicios técnicos

**Preguntas generales:**
- ¿Cuál es su edad y distrito?
- ¿Cada cuanto requiere servicios técnicos?
- ¿Actualmente como suele encontrar técnicos (redes sociales, contactos, etc.)?
- ¿Ha tenido malas experiencias al contratar técnicos informales?
- ¿Qué datos considera al elegir un técnico (precio, reseñas, recomendaciones)?
- ¿Qué información le genera confianza para contratar a alguien?
- ¿Ha usado alguna app o plataforma para contratar servicios? ¿Cuál y por qué?

**Preguntas complementarias:**
- ¿Estaría dispuesto a pagar un precio más alto por un técnico verificado?
- ¿Prefiere comparar opciones antes de contratar o elegir rápidamente?

### 2.2.2. Registro de entrevistas

Link de la grabación : <a href="https://upcedupe-my.sharepoint.com/:v:/g/personal/u202313397_upc_edu_pe/EfFiVNLecsRFhBVuapqPFY8BQ-eBSanNyg_cHUXJrR1WWw?e=zOfNFQ&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D">Entrevistas TuChambape </a>


#### Segmento 01: Trabajadores Técnicos Independientes
**Entrevista 1:**

- Nombre: Jorge Videla
- Género: Masculino
- Edad: 27 años
- Distrito: Lima, Perú
- Duración: 07:39
- Inicio: 22:06
- Fin: 29:28

Screenshot:

<img src="assets/images/ImgResources/Entrevista1-Segmento1.PNG" width=800px />

**Resumen:**
Jorge es un desarrollador web independiente con un año de experiencia.
Principalmente, consigue clientes a través de redes sociales, especialmente el Marketplace de Facebook. En su último trabajo, enfrentó desconfianza de un cliente, lo que lo llevó a reunirse presencialmente para explicar el proyecto y generar mayor confianza, ofreciendo un precio más bajo.
Utiliza su laptop Asus para desarrollar los sitios web y su teléfono para la gestión del marketing y ventas.
En cuanto a las funcionalidades que esperaría de una plataforma que lo conecte con clientes, sugiere la opción de publicar solicitudes de manera privada.
Además, destacaría la posibilidad de adjuntar archivos o documentos como portafolios para mostrar su experiencia.
Su estilo de trabajo es flexible, controlando sus tiempos, ya que no está sujeto a un horario estricto.
Finalmente, prefiere recibir solicitudes de clientes a través de mensajes en una aplicación dedicada.

**Entrevista 2:**

- Nombre: Carlos Alberto Almeyda Romero
- Género: Masculino
- Edad: 47 años
- Distrito: Santa
- Duración: 09:27
- Inicio: 12:36
- Fin: 22:06

Screenshot:

<img src="assets/images/ImgResources/Entrevista2-Segmento1.PNG" width=800px />

**Resumen:**
Carlos, un técnico automotriz con 30 años de experiencia, trabaja de manera independiente después de haber sido parte de una empresa durante 20 años.
Consigue clientes a través de recomendaciones y redes sociales.
Aunque ha enfrentado casos de desconfianza de nuevos clientes, utiliza su experiencia para generar confianza explicando sus procesos de trabajo.
Carlos utiliza Excel para gestionar su trabajo y cotizaciones.
Cree que una plataforma que lo conecte con clientes podría ayudarle a expandir su alcance.
Entre las funcionalidades que espera de la plataforma, menciona la opción de pago seguro y la posibilidad de ofrecer diagnósticos mediante videos del trabajo realizado en los autos, lo que aumenta la transparencia con el cliente.
En cuanto a la información que debería incluir su perfil, destaca la importancia de mostrar su experiencia, los videos de trabajo realizados y las recomendaciones de otros clientes.
Prefiere recibir solicitudes de clientes principalmente por WhatsApp y llamadas, ya que la mayoría de sus clientes lo contactan por estos medios, especialmente en la fase inicial de su negocio independiente.
Él considera que la honestidad y la transparencia son clave para el éxito de su emprendimiento.

**Entrevista 3:**

- Nombre: Fabiola Saldaña
- Género: Femenino
- Edad: 24 años
- Distrito: Surquillo
- Duración: 05:21
- Inicio: 29:28
- Fin: 34:49
- 
Screenshot:

<img src="assets/images/ImgResources/Entrevista3-Segmento1.PNG" width=800px />

**Resumen:**
Fabiola, una profesora freelance con 10 años de experiencia enseñando inglés, trabaja de manera independiente luego de haber sido parte de una academia durante 6 años.
Consigue estudiantes a través de recomendaciones, redes sociales y plataformas educativas.
Aunque ha enfrentado dudas de nuevos alumnos sobre la efectividad de sus clases, utiliza su experiencia para generar confianza ofreciendo clases demostrativas y mostrando avances de otros estudiantes.
Fabiola utiliza Excel y Google Calendar para gestionar su agenda y pagos.
Cree que una plataforma que la conecte con más alumnos podría ayudarle a ampliar su clientela.
Entre las funcionalidades que espera de la plataforma, menciona la opción de clases en línea integradas, pagos seguros y la posibilidad de mostrar fragmentos de sus clases para que los futuros estudiantes puedan ver su método de enseñanza.
En su perfil considera fundamental destacar su experiencia, certificaciones, testimonios de alumnos satisfechos y videos cortos de sus clases.
Prefiere recibir solicitudes de clases principalmente por WhatsApp y correo electrónico, ya que son los canales donde organiza sus primeras entrevistas y seguimiento con potenciales alumnos.
Fabiola considera que la paciencia, la personalización del aprendizaje y la transparencia en el avance del alumno son claves para el éxito de su trabajo independiente.

#### Segmento 02: Usuarios que requieren servicios técnicos

**Entrevista 1:**

Datos del entrevistador:

- Nombres: Roy
- Apellidos: Fernández Remón

Datos del entrevistado:

- Nombres: Maryori
- Apellidos: Atanacio Cruces
- Edad: 23
- Distrito de Residencia: San Juan de Lurigancho
- Enlace de la entrevista: [Ver video](https://upcedupe-my.sharepoint.com/:v:/g/personal/u20221b778_upc_edu_pe/EdUeE7izJJBMn0vMLfylqa4BGsEBOuqfFs6dDLnIGrVBaQ?e=0sXdti)
- Duración de la entrevista: 4:01

<img src="assets/images/ImgResources/Entrevista%20Maryori.png"/>

Informe del resumen de la entrevista:

Maryori Atanacio Cruces requiere servicios técnicos aproximadamente cada seis meses o cuando surge una urgencia. Actualmente suele encontrar técnicos a través de recomendaciones de amigos, familiares o en grupos de Facebook. Ha tenido malas experiencias con técnicos informales, por lo que ahora prioriza elegir basándose en precios, reseñas y recomendaciones. Le genera confianza que el técnico tenga un perfil bien presentado, reseñas reales y que ofrezca alguna identificación. Ha utilizado la app "Homy" porque ofrece técnicos verificados y respaldo en caso de problemas. Está dispuesta a pagar un precio más alto por un técnico verificado y prefiere comparar varias opciones antes de contratar para evitar riesgos.

**Entrevista 2:**

Datos del entrevistador:

- Nombres: Roy
- Apellidos: Fernández Remón

Datos del entrevistado:

- Nombres: Jefry
- Apellidos: Prado Remón
- Edad: 24
- Distrito de Residencia: San Juan de Lurigancho
- Enlace de la entrevista: [Ver video](https://upcedupe-my.sharepoint.com/:v:/g/personal/u20221b778_upc_edu_pe/ESij9AMyjV5DpwHE_0XF-TQB9Sscnhl5mBJErQdk-8MRFw?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D&e=PbEcZg)
- Duración de la entrevista: 2:55

<img src="assets/images/ImgResources/Entrevista%20Jefry.png"/>

Informe del resumen de la entrevista:

Jefry Prado Remón requiere servicios técnicos cada cuatro o cinco meses, generalmente cuando tiene problemas con su laptop o el internet. Suele encontrar técnicos a través de recomendaciones de amigos o buscando en Facebook, aunque es más cuidadoso al hacerlo. Ha tenido malas experiencias con técnicos informales, por lo que ahora se fija en recomendaciones, precios y la experiencia antes de contratar. Le genera confianza que el técnico tenga buenas reseñas, un perfil serio y que demuestre conocimiento. Ha utilizado la app "Homy" para contratar servicios, valorando la verificación de técnicos y la facilidad de uso. Está dispuesto a pagar un precio más alto por un técnico verificado y prefiere comparar opciones antes de tomar una decisión para asegurarse de hacer una buena elección.

**Entrevista 3:**

- Nombre: Carol Vega
- Género: Femenino
- Edad: 39 años
- Distrito: El Agustino
- Duración: 5:20
- Inicio: 6:56
- Fin: 12:36
  
Screenshot:

<img src="assets/images/ImgResources/Entrevista3-Segmento2.PNG"/>

**Resumen:**
Carol, de 39 años, vive en el distrito de El Agustino y requiere servicios técnicos aproximadamente cada dos años.
Para encontrar técnicos, utiliza principalmente redes sociales, anuncios en la calle y recomendaciones de conocidos.
Aunque ha tenido malas experiencias en el pasado al contratar de manera informal, también ha tenido trabajos satisfactorios.
Considera más importantes las recomendaciones de otras personas y las reseñas de los técnicos en redes sociales, así como la presencia de una tarjeta de presentación como una señal de profesionalismo.
Aunque no ha utilizado plataformas específicas para contratar estos servicios, estaría dispuesta a pagar un precio más alto por un técnico verificado, dado que experiencias anteriores con precios bajos no siempre resultaron en trabajos de calidad.
Carol prefiere comparar opciones antes de tomar una decisión, aunque en ocasiones contrata rápidamente si la necesidad es urgente.

### 2.2.3. Análisis de entrevistas

**Datos Generales de los Entrevistados**

| Nombre                          | Edad     | Distrito de Residencia     | Ciudad   | País  |
|:---------------------------------|:---------|:----------------------------|:---------|:------|
| Maryori Atanacio Cruces          | 23 años  | San Juan de Lurigancho       | Lima     | Perú  |
| Jefry Prado Remón                | 24 años  | San Juan de Lurigancho       | Lima     | Perú  |
| Carol Vega                       | 39 años  | El Agustino                  | Lima     | Perú  |
| Jorge Videla                     | 27 años  | Lima                         | Lima     | Perú  |
| Carlos Alberto Almeyda Romero    | 47 años  | Santa                        | Santa    | Perú  |
| Fabiola Saldaña                  | 24 años  | Surquillo                    | Lima     | Perú  |

- **Promedio de edad:** 30.6 años
- **Residencia:** 100% en Perú (mayoría en Lima Metropolitana)

#### - Necesidad de Servicios Técnicos

- **Maryori:** Cada 6 meses o cuando surge una urgencia.
- **Jefry:** Cada 4 a 5 meses, principalmente por fallas en laptop o internet.
- **Carol:** Cada 2 años, pero puede requerirlo antes por urgencias.
- **Jorge:** Consigue clientes regularmente a través de redes sociales, no mencionó frecuencia de necesitar servicios, sino de ofrecerlos.
- **Carlos:** Trabaja de forma continua, prestando servicios automotrices.
- **Fabiola:** Brinda clases regularmente; su demanda depende de estudiantes nuevos o recurrentes.

**Frecuencia promedio estimada (usuarios que requieren técnicos):** Cada 5-6 meses.

#### - Medios Utilizados para Encontrar Técnicos o Clientes

- **Recomendaciones de amigos o familiares:** 100%
- **Búsqueda en redes sociales (Facebook, Marketplace):** 100%
- **Anuncios físicos:** (Carol) 33%
- **Plataformas educativas especializadas:** (Fabiola) sí

#### - Experiencias con Técnicos Informales

- **Maryori y Jefry:** Han tenido malas experiencias (100%).
- **Carol:** Ha tenido tanto malas como buenas experiencias.
- **Jorge, Carlos y Fabiola:** Han enfrentado desconfianza de clientes y la superan demostrando su experiencia y transparencia.

#### - Criterios para Elegir Técnicos o Conectar con Clientes

| Criterio                     | % de Entrevistados que lo Consideran Importante |
|:-------------------------------|:-----------------------------------------------|
| Recomendaciones                | 100% |
| Reseñas o comentarios positivos| 100% |
| Precio                         | 100% |
| Experiencia previa             | 100% |
| Perfil profesional sólido      | 100% |

#### - Información que Genera Confianza

- Buenas reseñas reales.
- Perfil profesional con certificaciones, muestras de trabajo o testimonios.
- Identificación o respaldo documentario.
- Comunicación rápida, directa y formal.

#### - Uso de Apps o Plataformas

- **Maryori y Jefry:** Han usado Homy para contratar técnicos verificados.
- **Jorge y Fabiola:** Sugieren plataformas que permitan portafolios, pagos seguros y conexión directa con clientes.
- **Carol:** No ha usado plataformas, pero está dispuesta si garantizan verificación.

#### - Disposición a Pagar Más por Técnicos Verificados

- 100% de los entrevistados relacionados a servicios técnicos están dispuestos a pagar más por verificación y respaldo.

#### - Método de Decisión al Contratar o Aceptar Clientes

- Comparan varias opciones antes de decidir (usuarios).
- En el caso de los trabajadores técnicos, prefieren recibir solicitudes por WhatsApp o apps especializadas, evitando comunicaciones improvisadas.

#### - Resumen Rápido

| Aspecto Evaluado                         | % de Coincidencia entre Entrevistados |
|:-----------------------------------------|:--------------------------------------|
| Viven en Lima Metropolitana              | 83% |
| Edad promedio joven-adulto (24-47 años)   | 100% |
| Requieren servicios técnicos cada 4-6 meses (usuarios) | 66% |
| Usan redes sociales o recomendaciones    | 100% |
| Han tenido malas experiencias            | 66% (usuarios) |
| Buscan confianza mediante perfil y reseñas| 100% |
| Han usado o usarían apps especializadas   | 83% |
| Dispuestos a pagar más por verificación   | 100% |
| Prefieren comparar antes de contratar o aceptar clientes | 100% |

#### - Conclusiones del Análisis

- Se observa un **segmento joven-adulto urbano**, digitalmente activo, con alta preocupación por la confiabilidad del servicio técnico.
- Tanto usuarios como trabajadores técnicos valoran **perfiles completos, reseñas y garantías**.
- **Redes sociales** siguen siendo fundamentales, pero existe **apertura hacia plataformas especializadas** que aseguren verificación, transparencia y facilidad de comunicación.
- La **decisión de contratación o aceptación de clientes es reflexiva**, priorizando calidad y confianza sobre el precio más bajo.




## 2.3 Needfinding

En esta sección analizamos la información recopilada en las entrevistas realizadas a nuestros segmentos objetivos.

### 2.3.1 User Personas.

Los user persona que se muestran a continuación, fueron realizados a partir de la información recopilada de la sección de entrevistas. Estos nos ayudarán a describir de forma general nuestro segmento objetivo.

**Segmento 1 - Trabajadores Técnicos Independientes:**  

<div align="center">

<img src="assets/images/ImgResources/Juan_Carlos_user_persona.png" alt="user_persona_1" />

</div>

**Segmento 2 - Usuarios que requieren servicios técnicos:**

<div align="center">
<img src="assets/images/ImgResources/USER-PERSONA-Jesús-Lujan.png" alt="user_persona_1" />
</div>


### 2.3.2 User Task Matrix.

### Segmento objetivo #1: Juan Carlos (Gasfitero Independiente)

| Tarea                                                    | Frecuencia | Importancia |
|----------------------------------------------------------|------------|-------------|
| Buscar nuevos clientes                                   | Alta       | Alta        |
| Coordinar horarios con clientes                          | Alta       | Alta        |
| Negociar precios y condiciones                           | Media      | Alta        |
| Repartir volantes o buscar recomendaciones               | Media      | Media       |
| Recordar fechas o compromisos laborales                  | Alta       | Media       |
| Pedir reseñas o recomendaciones a clientes               | Baja       | Alta        |
| Usar redes sociales o apps para promoción                | Muy baja   | Media       |
| Hacer el trabajo técnico (reparaciones, instalaciones)   | Alta    | Alta        |
| Dar seguimiento a clientes anteriores                    | Baja       | Media       |
| Comprar materiales de ferretería                         | Media      | Alta        |
| Coordinar el precio del servicio por WhatsApp o teléfono | Alta       | Alta        |
| Transportarse entre un trabajo y otro                    | Alta       | Media       |
| Resolver problemas imprevistos en trabajos               | Media      | Alta        |
| Llevar el control de pagos recibidos y pendientes        | Media      | Alta        |

### Segmento objetivo #2: Jesus Lujan (Usuario dependiente)

| Tarea                                                    | Frecuencia | Importancia |
|----------------------------------------------------------|------------|-------------|
| Buscar profesionales para tareas del hogar o educación   | Alta       | Alta        |
| Comparar precios, calificaciones y experiencia           | Media      | Alta        |
| Contactar al proveedor de servicio                       | Media      | Alta        |
| Coordinar horarios o agendar servicios                   | Media      | Alta        |
| Solicitar presupuesto o cotización                       | Media      | Alta        |
| Leer opiniones o referencias de otros usuarios           | Baja       | Media       |
| Guardar perfiles o servicios favoritos                   | Baja       | Media       |
| Cancelar o reagendar un servicio                         | Baja       | Media       |
| Dejar una reseña luego del servicio                      | Baja       | Alta        |
| Compartir el contacto con amigos o familiares            | Baja       | Baja        |
| Revisar si el servicio tiene garantías o soporte         | Baja       | Media       |
| Hacer seguimiento al estado del servicio contratado      | Baja       | Media       |
| Comparar diferentes tipos de servicios                   | Baja       | Media       |
| Evaluar si volvería a contratar al mismo proveedor       | Media      | Alta        |


### 2.3.3 User Journey Mapping.

En esta sección, vamos a analizar el recorrido del uso de la plataforma con su correspondiente contrata de servicio.
Desde el momento en el que un usuario se registra hasta lograr concretar realizar un servicio técnico, o en su caso contratar un servicio técnico, se puede observar que el usuario debe realizar una serie de acciones para poder lograrlo.

User Journey Mapping: Trabajadores independientes
<div align="center">

<img src="assets/images/ImgResources/Juan_Carlos_journey_mapping.png" alt="journey_mapping_1" />

</div>

User Journey Mapping: Usuarios que requieren servicios técnicos
<div align="center">

<img src="assets/images/ImgResources/Journey_mapping_custumer.png" alt="journey_mapping_1" />

</div>

### 2.3.4. Empathy Mapping.
En esta sección se presenta el Empathy Mapping, una herramienta para crear un perfil detallado de los user personas y desarrollar una comprensión profunda de su perspectiva y experiencia. Para cada user persona, se incluyen cinco elementos clave: lo que el usuario ve, lo que el usuario escucha, lo que el usuario dice, lo que el usuario hace y lo que el usuario siente. Además, se incluyen los pains y gains identificados en base a las preguntas: ¿Qué le preocupa? Y ¿Qué puede ayudar a resolver sus problemas? ¿Qué puede convencerlo de que somos la alternativa correcta? ¿Qué dice? Los mapas de empatía se han desarrollado con la herramienta UXPressia.

Empathy Mapping: Trabajadores independientes

<div align="center">

<img src="assets/images/ImgResources/Juan_Carlos_Empathy_Map.png" alt="journey_mapping_1" />

</div>

Empathy Mapping: Usuarios que requieren servicios técnicos
<div align="center">

<img src="assets/images/ImgResources/Empathy-map-curstumer.png" alt="journey_mapping_2" />

</div>

### 2.3.5. As-is Scenario Mapping.

<div align="center">

<img src="assets/images/ImgResources/AS-IS_ScenarioMappingCustumer.png" alt="journey_mapping_1" />

</div>

# Capítulo III: Requirements Specification

## 3.1. To-Be Scenario Mapping.

Aquí se expone el análisis del escenario, organizando una tabla que detalla la situación que necesita ser optimizada para el segmento objetivo. Se examinan los pasos a seguir y se describe cómo se perciben.

<img src="https://files.catbox.moe/xf4nty.jpg"/>

## 3.2. User Stories.

| Epic / Story ID | Título | Descripción | Criterios de Aceptación | Relacionado con (Epic ID) |
|---|---|---|---|---|
| EP01 | Registro y Autenticación | Permitir a los usuarios crear cuenta, iniciar sesión y gestionar credenciales de acceso. | **Escenario 1: Registro de Nuevo Usuario** <br> **Dado que** un usuario no tiene cuenta <br> **Cuando** intenta registrarse con un email y contraseña válidos <br> **Entonces** su cuenta se crea exitosamente y recibe un `201 Created`. <br><br> **Escenario 2: Inicio de Sesión Exitoso** <br> **Dado que** un usuario tiene una cuenta registrada <br> **Cuando** ingresa sus credenciales correctas <br> **Entonces** inicia sesión exitosamente y recibe un `200 OK`. <br><br> **Escenario 3: Inicio de Sesión Fallido** <br> **Dado que** un usuario intenta iniciar sesión <br> **Cuando** ingresa credenciales incorrectas <br> **Entonces** recibe un `401 Unauthorized` o `403 Forbidden` y un mensaje de error. <br><br> **Escenario 4: Gestión de Contraseña (Recuperación)** <br> **Dado que** un usuario olvidó su contraseña <br> **Cuando** solicita la recuperación de contraseña por email <br> **Entonces** recibe un enlace o código válido para restablecerla. | no corresponde |
| EP02 | Gestión de Perfil Técnico | Facilitar la creación, edición y verificación de perfiles de técnicos con datos y portafolio. | **Escenario 1: Creación de Perfil de Técnico** <br> **Dado que** un técnico se ha registrado y no tiene perfil creado <br> **Cuando** crea su perfil con información personal, especialidades, tarifas y portafolio <br> **Entonces** el perfil se guarda exitosamente y recibe un `201 Created`, quedando pendiente de verificación. <br><br> **Escenario 2: Edición de Perfil de Técnico** <br> **Dado que** un técnico tiene un perfil existente <br> **Cuando** actualiza su información (ej. disponibilidad, nueva especialidad, portafolio) <br> **Entonces** el perfil se actualiza exitosamente y recibe un `200 OK`. <br><br> **Escenario 3: Verificación de Perfil** <br> **Dado que** un técnico ha enviado su información para verificación <br> **Cuando** un administrador del sistema valida sus credenciales y/o portafolio <br> **Entonces** el perfil del técnico es marcado como "verificado" y es visible en las búsquedas. | no corresponde |
| EP03 | Búsqueda y Filtrado | Proporcionar herramientas para buscar técnicos por especialidad, ubicación y precio. | **Escenario 1: Búsqueda por Especialidad** <br> **Dado que** un usuario busca un técnico <br> **Cuando** filtra por una especialidad específica (ej. "Electricista") <br> **Entonces** se muestran solo los técnicos que han declarado esa especialidad. <br><br> **Escenario 2: Búsqueda por Ubicación** <br> **Dado que** un usuario busca un técnico <br> **Cuando** filtra por una ubicación (ej. "Miraflores, Lima") o rango geográfico <br> **Entonces** se muestran los técnicos que prestan servicio en esa área o cercanía. <br><br> **Escenario 3: Filtro por Rango de Precio** <br> **Dado que** un usuario busca un técnico <br> **Cuando** establece un rango de precios mínimo y máximo <br> **Entonces** se muestran solo los técnicos cuyas tarifas se ajustan a ese rango. <br><br> **Escenario 4: Combinación de Filtros** <br> **Dado que** un usuario busca un técnico <br> **Cuando** aplica múltiples filtros (ej. especialidad, ubicación y precio) simultáneamente <br> **Entonces** los resultados se refinan mostrando técnicos que cumplen todos los criterios especificados. | no corresponde |
| EP04 | Reserva y Programación de Servicios | Permitir agendar, confirmar, modificar y cancelar citas de servicios técnicos. | **Escenario 1: Agendar una Cita** <br> **Dado que** un usuario ha seleccionado un técnico y un servicio disponible <br> **Cuando** elige una fecha y hora en el calendario del técnico y confirma la reserva <br> **Entonces** la cita se agenda exitosamente, el usuario y técnico reciben notificación, y la cita se registra con un `201 Created`. <br><br> **Escenario 2: Confirmación de Cita (por el técnico/sistema)** <br> **Dado que** una cita ha sido agendada por el usuario <br> **Cuando** el técnico acepta la cita o el sistema la auto-confirma (si aplica) <br> **Entonces** el estado de la cita cambia a "Confirmada" y el usuario recibe una notificación. <br><br> **Escenario 3: Modificar una Cita** <br> **Dado que** una cita ha sido confirmada <br> **Cuando** el usuario o técnico solicitan y acuerdan un cambio de fecha/hora <br> **Entonces** la cita se actualiza exitosamente (`200 OK`), se refleja en ambos calendarios y ambas partes son notificadas. <br><br> **Escenario 4: Cancelar una Cita** <br> **Dado que** una cita ha sido agendada o confirmada <br> **Cuando** el usuario o técnico cancelan la cita antes del plazo establecido <br> **Entonces** la cita es marcada como "Cancelada", se libera el slot y ambas partes son notificadas. | no corresponde |
| EP05 | Pagos y Transacciones | Integrar pasarelas de pago seguras y generar comprobantes digitales para las transacciones. | **Escenario 1: Realizar un Pago Exitoso** <br> **Dado que** un servicio ha sido completado y el usuario debe pagar <br> **Cuando** el usuario ingresa sus datos de pago en la pasarela segura y confirma la transacción <br> **Entonces** el pago se procesa exitosamente, el sistema registra la transacción y el usuario recibe un `200 OK`. <br><br> **Escenario 2: Generación de Comprobante Digital** <br> **Dado que** una transacción de pago se ha completado exitosamente <br> **Cuando** el usuario accede a su historial de pagos o recibe una notificación <br> **Entonces** puede descargar o visualizar un comprobante digital (recibo/factura) del servicio. <br><br> **Escenario 3: Manejo de Errores de Pago** <br> **Dado que** un usuario intenta realizar un pago <br> **Cuando** ocurre un error en la pasarela de pago (ej. datos incorrectos, fondos insuficientes) <br> **Entonces** el sistema notifica el error al usuario con un mensaje claro y la transacción no se registra, permitiendo reintentar. | no corresponde |
| EP06 | Calificaciones y Reseñas | Habilitar la valoración de servicios y la publicación de comentarios para crear reputación pública. | **Escenario 1: Calificar un Servicio Completado** <br> **Dado que** un servicio ha sido marcado como completado <br> **Cuando** el usuario califica al técnico con una puntuación (ej. 1-5 estrellas) <br> **Entonces** la calificación se registra y contribuye a la reputación del técnico. <br><br> **Escenario 2: Publicar una Reseña Detallada** <br> **Dado que** un servicio ha sido completado y calificado <br> **Cuando** el usuario escribe un comentario detallado sobre su experiencia y lo publica <br> **Entonces** la reseña se asocia al perfil del técnico y es visible públicamente (previa moderación si aplica). <br><br> **Escenario 3: Visualizar Calificaciones y Reseñas** <br> **Dado que** un usuario busca un técnico o ve su perfil <br> **Cuando** accede a la sección de calificaciones y reseñas <br> **Entonces** puede ver la puntuación promedio del técnico y los comentarios de otros usuarios. | no corresponde |
| EP07 | Notificaciones y Mensajería Interna | Enviar alertas en tiempo real y permitir la comunicación directa entre técnico y cliente. | **Escenario 1: Notificación de Cita Confirmada** <br> **Dado que** una cita ha sido confirmada por el técnico <br> **Cuando** la confirmación se registra en el sistema <br> **Entonces** el usuario recibe una notificación en tiempo real (ej. push, email, SMS) informando la confirmación. <br><br> **Escenario 2: Mensajería Directa entre Usuario y Técnico** <br> **Dado que** un usuario y un técnico tienen una cita pendiente <br> **Cuando** cualquiera de ellos envía un mensaje a través de la plataforma <br> **Entonces** el mensaje es entregado al destinatario en tiempo real y visible en el chat interno. <br><br> **Escenario 3: Notificación de Cambio/Cancelación de Cita** <br> **Dado que** una cita es modificada o cancelada <br> **Cuando** el cambio se guarda en el sistema <br> **Entonces** ambas partes (usuario y técnico) reciben una notificación instantánea sobre la actualización. | no corresponde |
| US01            | Registro de nuevo usuario                    | Como visitante quiero registrarme proporcionando email y contraseña para usar la plataforma.       | **Escenario 1:**<br>Dado que no existe cuenta con ese email,<br>Cuando completo el formulario y envío,<br>Entonces se crea mi cuenta.<br><br>**Escenario 2:**<br>Dado que el email ya está registrado,<br>Cuando intento registrarme,<br>Entonces veo un mensaje de error,<br>Y no se crea la cuenta. | EP01                      |
| US02            | Inicio de sesión                             | Como usuario quiero iniciar sesión con mis credenciales para acceder a mi cuenta.                 | **Escenario 1:**<br>Dado que las credenciales son válidas,<br>Cuando ingreso email y contraseña,<br>Entonces accedo al panel.<br><br>**Escenario 2:**<br>Dado que la contraseña es incorrecta,<br>Cuando intento iniciar sesión,<br>Entonces veo un mensaje de “Credenciales inválidas”,<br>Y permanezco en la página de login. | EP01                      |
| US03            | Recuperación de contraseña                   | Como usuario quiero restablecer mi contraseña si la olvido para recuperar el acceso.               | **Escenario 1:**<br>Dado que olvido mi contraseña,<br>Cuando solicito enlace de recuperación,<br>Entonces recibo un email con instrucciones.<br><br>**Escenario 2:**<br>Dado que el token de recuperación expira,<br>Cuando uso el enlace caducado,<br>Entonces veo un mensaje de “Enlace expirado”,<br>Y no puedo restablecerla. | EP01                      |
| US04            | Creación de perfil técnico                   | Como técnico quiero completar mis datos personales y experiencia para mostrar mi portafolio.      | **Escenario 1:**<br>Dado que completo todos los campos obligatorios,<br>Cuando guardo el perfil,<br>Entonces se actualiza mi información.<br><br>**Escenario 2:**<br>Dado que dejo un campo obligatorio vacío,<br>Cuando intento guardar,<br>Entonces veo el mensaje “Campo requerido”,<br>Y no se guarda el perfil. | EP02                      |
| US05            | Subida de documentos de verificación         | Como técnico quiero subir mi DNI y certificaciones para ser un profesional verificado.            | **Escenario 1:**<br>Dado que selecciono un archivo válido,<br>Cuando lo subo,<br>Entonces el sistema lo almacena.<br><br>**Escenario 2:**<br>Dado que el archivo supera 5 MB,<br>Cuando intento subirlo,<br>Entonces se muestra “Archivo muy pesado”,<br>Y no se carga. | EP02                      |
| US06            | Edición de perfil técnico                    | Como técnico quiero modificar mis datos y portafolio para mantener mi perfil actualizado.         | **Escenario 1:**<br>Dado que ingreso a “Mi perfil”,<br>Cuando cambio mi foto o descripción,<br>Entonces la actualización persiste.<br><br>**Escenario 2:**<br>Dado que pierdo conexión durante la edición,<br>Cuando intento guardar,<br>Entonces recibo “Error de red”,<br>Y se conserva la versión anterior. | EP02                      |
| US07            | Búsqueda por especialidad                    | Como cliente quiero buscar técnicos por especialidad para encontrar el servicio adecuado.         | **Escenario 1:**<br>Dado que selecciono “Electricista”,<br>Cuando ejecuto la búsqueda,<br>Entonces aparecen técnicos con esa especialidad.<br><br>**Escenario 2:**<br>Dado que no hay resultados cercanos,<br>Cuando busco,<br>Entonces se muestra “Sin resultados”,<br>Y opciones para ampliar distancia. | EP03                      |
| US08            | Filtrado por ubicación                       | Como cliente quiero aplicar filtro de ubicación para ver técnicos cerca de mí.                    | **Escenario 1:**<br>Dado que permito geolocalización,<br>Cuando activo “Ubicación cercana”,<br>Entonces veo técnicos en mi distrito.<br><br>**Escenario 2:**<br>Dado que deshabilito geolocalización,<br>Cuando ingreso manualmente un distrito,<br>Entonces aparecen técnicos de esa zona,<br>Y se actualiza el mapa. | EP03                      |
| US09            | Filtrado por rango de precio                 | Como cliente quiero filtrar técnicos por rango de precio para ajustarme a mi presupuesto.        | **Escenario 1:**<br>Dado que establezco mínimo y máximo,<br>Cuando aplico el filtro,<br>Entonces la lista muestra solo técnicos dentro del rango.<br><br>**Escenario 2:**<br>Dado que invierto valores (min > max),<br>Cuando aplico filtro,<br>Entonces aparece “Rango inválido”,<br>Y no filtra. | EP03                      |
| US10            | Búsqueda por nombre                          | Como cliente quiero buscar un técnico por nombre si ya conozco a alguien.                        | **Escenario 1:**<br>Dado que escribo “Ramírez”,<br>Cuando busco,<br>Entonces aparecen perfiles que coinciden.<br><br>**Escenario 2:**<br>Dado que el nombre no existe,<br>Cuando presiono buscar,<br>Entonces se muestra “No se encontró”,<br>Y sugerencias de búsqueda. | EP03                      |
| US11            | Selección de fecha y hora                    | Como cliente quiero elegir fecha y hora en un calendario para mi servicio.                       | **Escenario 1:**<br>Dado que selecciono día y hora disponibles,<br>Cuando confirmo,<br>Entonces se reserva ese slot.<br><br>**Escenario 2:**<br>Dado que el horario ya fue ocupado,<br>Cuando intento seleccionar,<br>Entonces recibo “Hora no disponible”,<br>Y se bloquea esa opción. | EP04                      |
| US12            | Confirmación de reserva                      | Como cliente quiero confirmar mi reserva y recibir comprobante.                                  | **Escenario 1:**<br>Dado que reviso detalles,<br>Cuando confirmo reserva,<br>Entonces recibo email con resumen.<br><br>**Escenario 2:**<br>Dado que mi email es inválido,<br>Cuando finalizo reserva,<br>Entonces veo “Email no válido”,<br>Y no se envía comprobante. | EP04                      |
| US13            | Cancelación de reserva                       | Como cliente quiero cancelar una reserva antes del servicio sin penalidad.                       | **Escenario 1:**<br>Dado que entro a “Mis reservas”,<br>Cuando pulso “Cancelar”,<br>Entonces confirma y elimina la cita.<br><br>**Escenario 2:**<br>Dado que está dentro de la ventana de cancelación,<br>Cuando cancelo,<br>Entonces veo “Cancelación exitosa”,<br>Y recibo notificación. | EP04                      |
| US14            | Historial de reservas                        | Como cliente quiero ver un historial de mis servicios contratados.                               | **Escenario 1:**<br>Dado que navego a “Historial”,<br>Cuando cargo la sección,<br>Entonces veo lista de reservas pasadas.<br><br>**Escenario 2:**<br>Dado que no tengo reservas,<br>Cuando accedo,<br>Entonces muestra “Sin historial”,<br>Y sugerencias de nuevos servicios. | EP04                      |
| US15            | Integración con pasarela de pago             | Como cliente quiero pagar con tarjeta o billetera digital de forma segura.                       | **Escenario 1:**<br>Dado que ingreso datos válidos,<br>Cuando completo el pago,<br>Entonces recibo confirmación.<br><br>**Escenario 2:**<br>Dado que la tarjeta es rechazada,<br>Cuando intento pagar,<br>Entonces muestro “Pago rechazado”,<br>Y ofrezco otro método. | EP05                      |
| US16            | Generación de recibo digital                 | Como cliente quiero recibir un comprobante PDF tras el pago.                                     | **Escenario 1:**<br>Dado que el pago fue exitoso,<br>Cuando finaliza transacción,<br>Entonces genera y envía PDF.<br><br>**Escenario 2:**<br>Dado que hubo error de servidor,<br>Cuando solicito recibo,<br>Entonces veo “Error al generar recibo”,<br>Y opción de reenviar. | EP05                      |
| US17            | Gestión de métodos de pago                   | Como usuario quiero agregar, editar y eliminar mis métodos de pago.                              | **Escenario 1:**<br>Dado que agrego tarjeta nueva,<br>Cuando guardo,<br>Entonces aparece en mi lista.<br><br>**Escenario 2:**<br>Dado que elimino un método usado,<br>Cuando confirmo eliminación,<br>Entonces se retira y no aparece más. | EP05                      |
| US18            | Calificar técnico                             | Como cliente quiero asignar una puntuación al técnico tras el servicio.                          | **Escenario 1:**<br>Dado que termino el servicio,<br>Cuando elijo 1–5 estrellas,<br>Entonces se guarda mi valoración.<br><br>**Escenario 2:**<br>Dado que no selecciono estrellas,<br>Cuando intento enviar,<br>Entonces veo “Seleccione una puntuación”,<br>Y no registra valoración. | EP06                      |
| US19            | Dejar comentario en reseña                   | Como cliente quiero añadir un comentario para describir mi experiencia.                           | **Escenario 1:**<br>Dado que escribo texto válido,<br>Cuando envío comentario,<br>Entonces aparece en el perfil.<br><br>**Escenario 2:**<br>Dado que el comentario excede 300 caracteres,<br>Cuando envío,<br>Entonces se muestra “Límite superado”,<br>Y no se publica. | EP06                      |
| US20            | Visualizar calificaciones                     | Como cliente quiero ver la calificación promedio de un técnico antes de contratarlo.             | **Escenario 1:**<br>Dado que entro al perfil,<br>Cuando cargo la sección de reseñas,<br>Entonces muestro promedio de estrellas.<br><br>**Escenario 2:**<br>Dado que no hay reseñas,<br>Cuando cargo,<br>Entonces muestro “Aún sin calificaciones”,<br>Y solicito ser el primero en reseñar. | EP06                      |
| US21            | Notificación de nuevas solicitudes           | Como técnico quiero recibir alertas en tiempo real de nuevos pedidos de servicio.                | **Escenario 1:**<br>Dado que llega una solicitud,<br>Cuando activo notificaciones,<br>Entonces recibo alerta push.<br><br>**Escenario 2:**<br>Dado que estoy desconectado,<br>Cuando me conecto,<br>Entonces veo resumen de solicitudes pendientes,<br>Y notificaciones leídas. | EP07                      |
| US22            | Chat interno entre técnico y cliente          | Como usuario quiero comunicarme con el otro para coordinar detalles del servicio.                | **Escenario 1:**<br>Dado que abro chat,<br>Cuando envío mensaje,<br>Entonces el destinatario lo recibe.<br><br>**Escenario 2:**<br>Dado que envío imagen o archivo,<br>Cuando se adjunta,<br>Entonces el otro usuario lo puede descargar,<br>Y visualizar en la app. | EP07                      |
| US23            | Recordatorio de servicio vía notificación     | Como cliente quiero recibir recordatorios previos a la cita para no olvidarla.                  | **Escenario 1:**<br>Dado que falta 1 hora para la cita,<br>Cuando llega el momento,<br>Entonces se envía push recordatorio.<br><br>**Escenario 2:**<br>Dado que habilito email,<br>Cuando faltan 24 horas,<br>Entonces recibo correo de recordatorio,<br>Y opción de reprogramar. | EP07                      |

## Technical Stories.



## 3.3. Impact Mapping.

En este apartado se muestra los impact mapping de nuestros segmentos objetivos:

#### Segmento 1: Trabajadores Técnicos Independientes

<img src="https://files.catbox.moe/l9h33u.png"/>

#### Segmento 2: Usuarios que requieren servicios técnicos

<img src="https://files.catbox.moe/o7spd9.png"/>

## 3.4. Product Backlog.

| #Orden | User Story Id | Título                                 | Descripción                                                                                   | StoryPoints (1/2/3/5/8) |
|-------:|--------------:|---------------------------------------|-----------------------------------------------------------------------------------------------|------------------------:|
| 1      | US01          | Registro de nuevo usuario             | Como visitante quiero registrarme proporcionando email y contraseña para usar la plataforma.  |                       3 |
| 2      | US02          | Inicio de sesión                      | Como usuario quiero iniciar sesión con mis credenciales para acceder a mi cuenta.            |                       3 |
| 3      | US03          | Recuperación de contraseña            | Como usuario quiero restablecer mi contraseña si la olvido para recuperar el acceso.          |                       5 |
| 4      | US04          | Creación de perfil técnico            | Como técnico quiero completar mis datos personales y experiencia para mostrar mi portafolio. |                       5 |
| 5      | US05          | Subida de documentos de verificación  | Como técnico quiero subir mi DNI y certificaciones para ser un profesional verificado.       |                       5 |
| 6      | US06          | Edición de perfil técnico             | Como técnico quiero modificar mis datos y portafolio para mantener mi perfil actualizado.    |                       3 |
| 7      | US07          | Búsqueda por especialidad             | Como cliente quiero buscar técnicos por especialidad para encontrar el servicio adecuado.     |                       3 |
| 8      | US08          | Filtrado por ubicación                | Como cliente quiero aplicar filtro de ubicación para ver técnicos cerca de mí.                |                       3 |
| 9      | US09          | Filtrado por rango de precio          | Como cliente quiero filtrar técnicos por rango de precio para ajustarme a mi presupuesto.     |                       3 |
| 10     | US10          | Búsqueda por nombre                   | Como cliente quiero buscar un técnico por nombre si ya conozco a alguien.                     |                       2 |
| 11     | US11          | Selección de fecha y hora             | Como cliente quiero elegir fecha y hora en un calendario para mi servicio.                    |                       5 |
| 12     | US12          | Confirmación de reserva               | Como cliente quiero confirmar mi reserva y recibir comprobante.                               |                       3 |
| 13     | US13          | Cancelación de reserva                | Como cliente quiero cancelar una reserva antes del servicio sin penalidad.                    |                       3 |
| 14     | US14          | Historial de reservas                 | Como cliente quiero ver un historial de mis servicios contratados.                            |                       3 |
| 15     | US15          | Integración con pasarela de pago      | Como cliente quiero pagar con tarjeta o billetera digital de forma segura.                    |                       8 |
| 16     | US16          | Generación de recibo digital          | Como cliente quiero recibir un comprobante PDF tras el pago.                                  |                       5 |
| 17     | US17          | Gestión de métodos de pago            | Como usuario quiero agregar, editar y eliminar mis métodos de pago.                           |                       5 |
| 18     | US18          | Calificar técnico                      | Como cliente quiero asignar una puntuación al técnico tras el servicio.                       |                       3 |
| 19     | US19          | Dejar comentario en reseña            | Como cliente quiero añadir un comentario para describir mi experiencia.                        |                       3 |
| 20     | US20          | Visualizar calificaciones             | Como cliente quiero ver la calificación promedio de un técnico antes de contratarlo.          |                       2 |
| 21     | US21          | Notificación de nuevas solicitudes    | Como técnico quiero recibir alertas en tiempo real de nuevos pedidos de servicio.             |                       5 |
| 22     | US22          | Chat interno entre técnico y cliente   | Como usuario quiero comunicarme con el otro para coordinar detalles del servicio.             |                       8 |
| 23     | US23          | Recordatorio de servicio vía notificación | Como cliente quiero recibir recordatorios previos a la cita para no olvidarla.           |                       5 |

# Capítulo IV: Product Design

## 4.1. Style Guidelines

### 4.1.1. General Style Guidelines
El propósito de esta sección es establecer las pautas generales de estilo que guiarán el desarrollo visual y de comunicación de TuChambape, una plataforma orientada a conectar técnicos independientes con clientes que necesitan servicios confiables y de calidad en distintos rubros del hogar y la tecnología. Estas directrices están diseñadas para asegurar la coherencia estética, funcional y de experiencia de usuario en todos los puntos de contacto con la plataforma, tanto en su versión web como móvil, utilizando herramientas de diseño como Figma. Esta sección funcionará como una guía centralizada para el equipo de diseño, desarrollo y marketing, garantizando que la identidad de TuChambape se mantenga consistente, profesional y alineada con los valores de cercanía, confianza y eficiencia.

➔ **Branding**
El logotipo de TuChambape es uno de los principales elementos de identificación de la marca y, por tanto, juega un papel clave en la consolidación de su identidad. El diseño del logo presenta las letras finales de la aplicacion "Pe" fusionadas en un ícono que asemeja a un maletín de color naranja cálido (#FF7A00) y azul eléctrico (#0066FF), lo cual evoca una sensación de tecnología, profesionalismo y acción inmediata. 

<p align="center">
  <img src="assets/logos/tuchambalogo.png" width="180" />
</p>
<p align="center">Logotipo de TuChambape</p>

A continuación, se detallan las decisiones relacionadas con su uso y aplicación:
- **Logo principal**: El logotipo debe ser utilizado siempre que sea posible en su versión completa, sobre un fondo blanco o de color suave que no interfiera con su legibilidad.
- **Adaptación en Figma**: El logotipo debe estar guardado como un componente en Figma para facilitar su uso consistente en múltiples pantallas y dispositivos. Se deberán crear versiones de alta resolución y con transparencias, ajustadas para diferentes aplicaciones visuales.

➔ **Typography**
La tipografía es uno de los elementos más importantes en la creación de una identidad visual coherente. Para TuChambape, hemos seleccionado fuentes que transmiten tecnología, claridad y profesionalismo:
- **Fuente principal**: La fuente seleccionada es "Poppins". Se trata de una tipografía moderna y versátil, con formas geométricas que refuerzan la estética tecnológica del logotipo. Se utilizará en sus diferentes tamaños, principalmente Bold para los encabezados y títulos principales, mientras que Regular para el cuerpo de texto.
- **Fuente secundaria**: Se recomienda el uso de "Inter" para textos más pequeños, como subtítulos, descripciones y etiquetas de formularios. Esta fuente asegura alta legibilidad en pantalla y complementa la línea visual moderna y funcional de la marca.
- **Aplicación en Figma**: Se deben crear Text Styles en Figma que incluyan los tamaños y pesos de Poppins e Inter previamente definidos, para garantizar un uso uniforme en todo el diseño. Los encabezados deben tener un tamaño de 32px, los subtítulos de 24px y el cuerpo de texto de 16px.

➔ **Colors**
El color es un aspecto central en la creación de la experiencia visual. Para TuChambape, la paleta de colores se basa en tonos que reflejan tecnología, dinamismo y confianza, valores esenciales en una plataforma orientada a conectar talento con oportunidades laborales. A continuación, se detalla la paleta principal y sus aplicaciones:
- **Color primario**: #0066CC (Azul Eléctrico). Este color, tomado directamente del logotipo, será el color principal de la marca. Se utilizará para encabezados, botones primarios y elementos destacados que busquen transmitir profesionalismo, tecnología y confiabilidad.
- **Color secundario**: #FFFFFF (Blanco). Este color aporta claridad, espacio visual y equilibrio. Se utilizará como fondo principal en la mayoría de las interfaces para facilitar la lectura y la navegación.
- **Color terciario**: #1A1A1A (Negro Suave). Será utilizado principalmente para los textos sobre fondos claros. Su tono asegura una excelente legibilidad sin resultar demasiado agresivo visualmente.
- **Color de realce**: #FF9900 (Naranja Cálido). Este color se utilizará para botones secundarios, íconos interactivos o llamadas a la acción que requieren captar la atención del usuario de forma inmediata y accesible.
- **Aplicación en Figma**: En Figma, se deberá guardar estos colores como Estilos de color, de manera que sean fácilmente accesibles para todo el equipo. Estos estilos ayudarán a garantizar la consistencia en cada pantalla o componente que se diseña.

➔ **Spacing**
El uso del espacio es fundamental para asegurar que la plataforma transmita una sensación de orden, claridad y eficiencia, en línea con los valores de TuChambape. La distribución visual debe mantenerse ligera y bien estructurada, permitiendo una navegación intuitiva sin generar saturación visual.
- **Padding y márgenes**: Para mantener una sensación de estructura y simplicidad, se recomienda utilizar 60px de padding entre secciones principales en pantallas de escritorio. Entre bloques de contenido debe haber un espacio de alrededor de 40px, asegurando que cada componente tenga espacio para "respirar" y que la información pueda ser escaneada visualmente con facilidad.
- **Espaciado entre elementos**: El espacio entre elementos interactivos (botones, íconos y campos de entrada) debe ser de 20px. Esto mejora la legibilidad, facilita la interacción con el contenido y permite una experiencia fluida tanto en pantallas grandes como en resoluciones adaptativas.
- **Aplicación en Figma**: En Figma, se utilizará el sistema de Auto Layout para mantener la consistencia en los espacios y asegurar que los elementos se ajusten correctamente en diferentes tamaños de pantalla. Los componentes deberán incluir valores predefinidos de padding y margen.

➔ **Tono de comunicación**
El tono de comunicación es un elemento clave para proporcionar una experiencia de usuario coherente con los objetivos y valores de TuChambape. Este tono debe reflejar cercanía, dinamismo y confianza, alineado con la misión de facilitar la conexión entre trabajadores técnicos y clientes a través de herramientas modernas, accesibles y seguras. Como plataforma creada por jóvenes emprendedores para impulsar la formalización y crecimiento de profesionales independientes, es importante que el tono inspire profesionalismo accesible, transmitiendo seguridad y oportunidades sin dejar de ser amigable.
- **Tono general**:
  - **Cercano y empático**: El lenguaje utilizado será amigable y accesible, con un enfoque que invita a la acción y a la confianza. Queremos que tanto los trabajadores técnicos como los clientes se sientan respaldados y comprendidos, promoviendo una interacción fluida y sin barreras.
  - **Positivo y motivador**: El tono debe generar una sensación de optimismo, destacando que cada paso en la plataforma es una oportunidad para crecer profesionalmente. Transmitimos un mensaje claro de que la conexión con nuevos clientes, la mejora de la visibilidad y la formalización del trabajo son procesos alcanzables y fáciles de lograr. La actitud es siempre proactiva, asegurando que el usuario se sienta capaz de alcanzar sus metas y superar cualquier desafío.
- **Aplicación en Figma**:
  - **Textos y botones**: En elementos interactivos como botones y mensajes de ayuda, se utilizará el color naranja cálido (#FF7A00), elegido por su capacidad de captar la atención de forma amigable y proactiva. Este color comunica acción inmediata sin generar tensión, y refuerza el carácter accesible de la plataforma.
  - **Mensajes de alerta**: Los mensajes de alerta serán claros pero no intrusivos. En lugar de generar presión, invitarán a la acción de manera suave, por ejemplo, "Explora nuevas oportunidades de trabajo" o "Actualiza tu perfil y consigue más clientes". Esto se logrará con una tipografía amigable y colores que denotan calma y seguridad, sin causar estrés ni urgencia innecesaria.

En conclusión, el tono de comunicación de TuChambape debe crear un ambiente de empoderamiento y conexión, permitiendo que usuarios de distintos niveles tecnológicos se sientan cómodos, confiados y apoyados en el uso de la plataforma. El lenguaje claro, positivo y directo será esencial para consolidar la identidad de la marca como un puente entre oportunidades y crecimiento profesional.

### 4.1.2. Web Style Guidelines

- Typography

  Tipografía principal: Poppins

  Título principal (32px)

  Subtítulo (24px)

  Cuerpo de texto (16px)

  Tipografía secundaria: Inter

  Descripciones y textos pequeños (14px)

  Etiquetas y formularios (12px)

- Colors

  A continuación, presentaremos los colores elegidos junto a su respectivo código identificador en Figma.

  - Figura 18

    Colores elegidos para la versión web

      <img src="assets/Style/colors.png" width="50%">

- Spacing

  A continuación, presentaremos las decisiones de espaciado elegidas.

  - Figura 19

    Espaciado elegido entre elementos de la plataforma web

      <img src="assets/Style/spacing.png" width="30%">

- Assets

  A continuación, mostraremos las imágenes referenciales de los assets elegidos.

  Figura 20

  Plantilla usada para la versión Desktop

    <img src="assets/Style/Plantilla_Landing.png" width="60%">

  Figura 21

  Pantalla de inicio

    <img src="assets/Style/LandingPage_Inicio.png" width="60%">

  Figura 22

  Pantalla de Iniciar Sesión

    <img src="assets/Style/IniciarSesion.png" width="60%">

  Figura 23

  Pantalla de Crear Cuenta

    <img src="assets/Style/Registrarse.png" width="60%">

  Figura 24

  Pantalla de Menú principal del Cliente

    <img src="assets/Style/InicioCliente.png" width="60%">

  Figura 25

  Pantalla de Menú principal del Trabajador

    <img src="assets/Style/InicioTrabajador.png" width="60%">

  Figura 26

  Pantalla de Configuración de Cuenta

    <img src="assets/Style/ConfiguraciónCliente.png" width="60%">

### **4.2. Information Architecture**

En esta sección, presentaremos las decisiones y las razones que guían la manera en que se estructura el contenido en las experiencias web y móviles, incluyendo la página de inicio (Landing Page) y las aplicaciones. Estas propuestas se enfocan mayormente en garantizar que los usuarios puedan adaptarse fácilmente a las funcionalidades de cada producto y encuentren sin dificultad lo que busquen.

- Figura 37

  Cuadro de cómo se estructura la información del landing page

    <img src="https://files.catbox.moe/l2wfbt.png" width="60%">

- Figura 38
  Cuadro de cómo se estructura la información de la aplicación web
  <img src="https://files.catbox.moe/5306xn.jpg" width="60%">

### 4.2.2. Labeling Systems

- Navegación y menús:
  Hemos considerado las siguientes etiquetas y categorías para la barra de navegación.

| Funcionalidad        | Descripción                                                                                        |
| -------------------- | -------------------------------------------------------------------------------------------------- |
| Iniciar sesión       | Botón para iniciar sesión en la plataforma                                                         |
| Inicio               | Muestra un dashboard de todas las actividades del cliente o trabajador                             |
| Buscar técnicos      | Muestra a todos los trabajadores con un filtro de búsqueda                                         |
| Comparar perfiles    | Se refiere a una lista de ciertos trabajadores del mismo sector con sus respectivas descripciones. |
| Ofertas (Cliente)    | Muestra el estado de la oferta que creó el cliente                                                 |
| Configuración        | Dirige al cliente a la configuración del perfil                                                    |
| Personalizar perfil  | Dirige al cliente o trabajador a su perfil con sus datos y sus preferencias                        |
| Buscar Ofertas       | Dirige al trabajador a las ofertas de trabajo que se le presentan                                  |
| Ofertas (Trabajador) | Muestra el estado de las ofertas del trabajador                                                    |
| Mi Reputación        | Muestra las valoraciones y reseñas hacia el trabajador                                             |

- Figura 39

  Etiquetas que aparecen en el aplicativo web

  Cliente

    <img src="assets/Style/navegaciónCliente.png" width="10%">

  Trabajador

    <img src="assets/Style/navegaciónTrabajador.png" width="10%">

### 4.2.2. SEO Tags and Meta Tags

#### Meta Description
La descripción meta es uno de los elementos más importantes para los motores de búsqueda. Asegúrate de que sea precisa y atractiva.

```html
<meta name="description" content="Una breve descripción de la página o producto, que atrae a los usuarios a hacer clic en el enlace.">
```

#### Meta Keywords
Especifica las palabras clave relevantes para la página, ayudando a los motores de búsqueda a entender mejor el contenido.

```html
<meta name="keywords" content="palabras clave, separadas, por, comas">
```

#### Open Graph Tags (og)
Open Graph es crucial para mejorar cómo se ve el contenido al ser compartido en redes sociales como Facebook, Twitter y LinkedIn.

```html
<!-- Open Graph -->
<meta property="og:title" content="Título atractivo de la página">
<meta property="og:description" content="Descripción que aparecerá al compartir en redes sociales.">
<meta property="og:image" content="URL de la imagen que se mostrará en la vista previa.">
<meta property="og:url" content="URL de la página">
<meta property="og:type" content="website">
```

#### Twitter Cards
Si también deseas optimizar la vista previa en Twitter, puedes agregar las Twitter Cards.

```html
<!-- Twitter Card -->
<meta name="twitter:card" content="summary_large_image">
<meta name="twitter:title" content="Título para Twitter">
<meta name="twitter:description" content="Descripción para Twitter">
<meta name="twitter:image" content="URL de la imagen de Twitter">
```

#### Meta Robots
Controla cómo los motores de búsqueda indexan tu página.

```html
<meta name="robots" content="index, follow">
```

---

**Consejos:**

- **Title Tag**: Asegúrate de incluir un título de página relevante y llamativo en tu etiqueta `<title>`, ya que es uno de los factores más importantes para el SEO.
  
```html
<title>Tu Título Aquí</title>
```

- **Canonical Tag**: Si tienes contenido duplicado, utiliza la etiqueta `<link rel="canonical">` para evitar problemas de SEO con contenido duplicado.

```html
<link rel="canonical" href="URL de la página principal">
```


### 4.2.4. Searching Systems

Se implementará un sistema de búsqueda dentro de la aplicación para facilitar la navegación de los usuarios.

La función de búsqueda se integrará en las siguientes vistas:

- Filtro de búsqueda de técnicos
- Filtro de búsqueda del servicio

Figura 40

Vistas en donde se integrará el sistema de búsqueda

<img src="assets/Style/BuscarTecnicos.png" width="50%">  
<img src="assets/Style/BuscarOfertas.png" width="50%">

### 4.2.5. Navigation Systems

Para que el usuario tenga una experiencia fluida, se han implementado dos tipos de navegaciones, respetando el sistema de organización del producto.

- **Menú de navegación de TuChamba.pe:**

  En la web se presenta un menú de navegación superior fijo, que se extiende horizontalmente en la parte superior de la página. Este menú ofrece un acceso organizado y visualmente limpio a las secciones principales del sitio:

  - **¿Cómo funciona?:** Guía paso a paso sobre cómo usar TuChambape, orientada tanto a técnicos como a clientes.

  - **Servicios:** Descripción de los profesionales en diversas áreas técnicas que se encuentran en la plataforma.

  - **Beneficios:** Comparativa de ventajas que ofrece la aplicación frente a métodos tradicionales.

  - **Contacto:** Espacio para consultas, soporte o contacto directo con el equipo.

  - **Iniciar sesión:** Botón destacado para que los usuarios existentes accedan rápidamente a la aplicación.

  - **Registrarse:** Llamado a la acción claro y visible para nuevos usuarios que desean unirse a TuChambape.

- **Menú de navegación de TuChambape:**

  En la plataforma, los usuarios cuentan con un menú de navegación lateral fijo a la izquierda. Este menú permite el acceso directo a las funcionalidades principales según el tipo de usuario (cliente o trabajador). Las secciones incluyen:

  - **Inicio:** Vista principal con indicadores de actividad y estadísticas.

  - **Buscar técnicos / Buscar ofertas:** Dependiendo del perfil, permite explorar técnicos disponibles o vacantes laborales.

  - **Ofertas:** Acceso a oportunidades laborales o a solicitudes enviadas.

  - **Comparar perfiles / Mi reputación:** Funcionalidades especializadas según el rol.

  - **Configuración:** Permite personalizar opciones del perfil y ajustes de cuenta.

  - **Personalizar perfil:** Acceso a los datos del usuario y sus preferencias.

  Cada ícono está acompañado de un texto descriptivo, lo que facilita la navegación intuitiva y rápida.

- Figura 41

  Sistema de navegación de la web

    <img src="assets/Style/SistemaNavegacionWeb.png" width="60%">

  Sistema de navegación de la plataforma

    <img src="assets/Style/navegaciónCliente.png" width="10%">
    <img src="assets/Style/navegaciónTrabajador.png" width="10%">

## 4.3. Landing Page UI Design

### 4.3.1 Landing Page Wireframes

  <img src="assets/Landing.Wireframes/LandingInicio.png" width="620">
  
  <img src="assets/Landing.Wireframes/LandingComoFunciona.png" width="620">
  
  <img src="assets/Landing.Wireframes/LandingServicios.png" width="620">
  
  <img src="assets/Landing.Wireframes/LandingBeneficios.png" width="620">
  
  <img src="assets/Landing.Wireframes/LandingTestimonios.png" width="620">
  
  <img src="assets/Landing.Wireframes/LandingContacto.png" width="620">

### 4.3.2 Landing Page Mock-up

A continuación, se evidencia el aspecto que TuChambape tendría al ser empleada por el usuario:

<p align="center">
  <img src="assets/Landing.Mockups/1.PNG" width="620" />
</p>
<p align="center">Ventana de inicio</p>

<br> </br>

<p align="center">
  <img src="assets/Landing.Mockups/2.PNG" width="620" />
</p>
<p align="center">Ventana de beneficios</p>

<br> </br>

<p align="center">
  <img src="assets/Landing.Mockups/3.PNG" width="620" />
</p>
<p align="center">Ventana de proceso para trabajadores y clientes</p>

<br> </br>

<p align="center">
  <img src="assets/Landing.Mockups/4.PNG" width="620" />
</p>
<p align="center">Ventana de elección de servicios</p>

<br> </br>

<p align="center">
  <img src="assets/Landing.Mockups/5.PNG" width="620" />
</p>
<p align="center">Ventana de testimonios de clientes</p>

<br> </br>

<p align="center">
  <img src="assets/Landing.Mockups/6.PNG" width="620" />
</p>
<p align="center">Ventana donde se evidencia nuestro impacto</p>

<br> </br>

<p align="center">
  <img src="assets/Landing.Mockups/7.PNG" width="620" />
</p>
<p align="center">Ventana de contacto con nuestro servicio</p>

<br> </br>

<p align="center">
  <img src="assets/Landing.Mockups/8.PNG" width="620" />
</p>
<p align="center">Website Footer de TuChambape</p>

### 4.4. Web Applications UX/UI Design

En el diseño de la interfaz de usuario de nueestra aplicación web "TuChambape", nos enfocamos en ofrecer una experiencia intuitiva, eficiente y visualmente atractiva. Asimismo, seguimos las guías de diseño para optimizar el rendimiento y garantizar que cada parte de la aplicación se adapte de manera fluida a los clientes y trabajadores.

### 4.4.1. Web Applications Wireframes

- Figura 54

  Wireframe de Iniciar Sesión

    <img src="assets/WebApps/Wireframes/1.jpg" width="60%">

- Figura 55

  Wireframe de Crear Cuenta

    <img src="assets/WebApps/Wireframes/2.jpg" width="60%">

- Figura 56

  Wireframes para Recuperar contraseña

    <img src="assets/WebApps/Wireframes/3.jpg" width="60%">
    <img src="assets/WebApps/Wireframes/4.jpg" width="60%">
    <img src="assets/WebApps/Wireframes/5.jpg" width="60%">

- Figura 57

  Wireframes de error al iniciar Sesión o registrarse

    <img src="assets/WebApps/Wireframes/6.jpg" width="60%">
    <img src="assets/WebApps/Wireframes/7.jpg" width="60%">
    
- Figura 58

  Vista de inicio del cliente

    <img src="assets/WebApps/Wireframes/8.jpg" width="60%">

- Figura 59

  Vista de Buscar Técnicos

    <img src="assets/WebApps/Wireframes/9.jpg" width="60%">

- Figura 60

  Vista de Comparar Perfiles

    <img src="assets/WebApps/Wireframes/10.jpg" width="60%">

- Figura 61

  Vistas relacionadas con Ofertas

    <img src="assets/WebApps/Wireframes/11.jpg" width="60%">
    <img src="assets/WebApps/Wireframes/12.jpg" width="60%">
    <img src="assets/WebApps/Wireframes/13.jpg" width="60%">
    <img src="assets/WebApps/Wireframes/14.jpg" width="60%">
    <img src="assets/WebApps/Wireframes/15.jpg" width="60%">

- Figura 62

  Vista de configuración

    <img src="assets/WebApps/Wireframes/16.jpg" width="60%">

- Figura 63

  Vistas de Personalizar Perfil

    <img src="assets/WebApps/Wireframes/17.jpg" width="60%">
    <img src="assets/WebApps/Wireframes/18.jpg" width="60%">>

- Figura 64

  Vista de inicio del trabajador

    <img src="assets/WebApps/Wireframes/19.jpg" width="60%">

- Figura 65

  Vista de buscar ofertas del trabajador

    <img src="assets/WebApps/Wireframes/20.jpg" width="60%">

- Figura 66

  Vistas relacionadas con las ofertas del trabajador

    <img src="assets/WebApps/Wireframes/21.jpg" width="60%">
    <img src="assets/WebApps/Wireframes/22.jpg" width="60%">
    <img src="assets/WebApps/Wireframes/23.jpg" width="60%">
    <img src="assets/WebApps/Wireframes/24.jpg" width="60%">

- Figura 67

  Vista de reputacion del trabajador

    <img src="assets/WebApps/Wireframes/25.jpg" width="60%">

- Figura 68

  Vistas de personalizar perfil del trabajador

    <img src="assets/WebApps/Wireframes/26.jpg" width="60%">
    <img src="assets/WebApps/Wireframes/27.jpg" width="60%">

### 4.4.2. Web Applications Wireflows Diagrams

En los Wireflow Diagrams de la plataforma TuChambape, se visualiza el recorrido completo que realiza el usuario, desde el registro hasta la utilización de todas las funciones disponibles. El flujo muestra cómo el usuario interactúa con la app en cada etapa, asegurando una experiencia intuitiva y fluida.

### User Persona

**Nombre:** Juan, Electricista

Juan es un técnico con experiencia que busca ampliar su red de clientes y conseguir trabajos de manera más eficiente. Desea encontrar oportunidades laborales cercanas, postularse rápidamente y hacer seguimiento a sus trabajos.

### User Goal

Para finales del primer trimestre de 2024, Juan podrá encontrar trabajos disponibles en su zona, postularse en menos de 2 minutos y recibir confirmaciones o rechazos con una tasa de respuesta superior al 90%.

### Task Flow

1. **Abrir la plataforma TuChambape**

   - **Acción:** Juan usa la plataforma
   - **Propósito:** Accede al apartado de Buscar Ofertas donde se muestran los trabajos disponibles
   - **Resultado Esperado:** En Buscar Ofertas, filtra los trabajos según sus preferencias (Ubicación, Disponibilidad, Rango de Pago Ofrecido, Medio de Pago, etc.)

2. **Buscar trabajos disponibles**

   - **Acción:** Juan explora los trabajos disponibles en el apartado Buscar Ofertas, usando filtros como Rango de Pago Ofrecido.
   - **Propósito:** Encontrar rápidamente oportunidades laborales que se ajusten a sus preferencias.
   - **Resultado esperado:** Se muestra una lista filtrada con ofertas de trabajo para un electricista, con un rango de precio, medio de pago y el estado de oferta.

3. **Postularse a un trabajo:**

   - **Acción:** Juan selecciona una oferta de trabajo que le ha gustado en el apartado de Buscar Ofertas y en el apartado de Ofertas postula a la que más le pareció.
   - **Propósito:** Enviar su solicitud al cliente.
   - **Resultado esperado:** Se envía la postulación y queda a la espera de la respuesta del cliente.

4. **Revisar estado de sus postulaciones:**

   - **Acción:** Juan entra al apartado "Ofertas" y revisa la sección "Mis Postulaciones" para ver el estado de sus postulaciones.
   - **Propósito:** Monitorear el progreso de sus solicitudes y prepararse para aceptar la oferta.
   - **Resultado esperado:** Se visualiza en la sección Pendiente el estado de la oferta mientras está en proceso.

5. **Realizar trabajo asignado:**
   - **Acción:** Al aceptar la oferta, Juan pasa a la sección de Pendiente en la que puede chatear con el cliente y ver detalles del trabajo.
   - **Propósito:** Ofrecer el servicio pedido por el cliente.
   - **Resultado esperado:** Juan termina el trabajo y puede reseñar la obra.

_Flujo de tareas para postularse a una oferta en la plataforma TuChambape_

<img src="https://files.catbox.moe/rcv4rr.png" alt="angie image" width="900">

_A continuación, algunas de nuestras User Stories junto con su diagrama:_

**US01**

<img src="https://files.catbox.moe/rcv4rr.png" alt="angie image" width="900">

**US02**

<img src="https://files.catbox.moe/g762zo.png" alt="angie image" width="900">

**US03**

<img src="https://files.catbox.moe/10eo9s.png" alt="angie image" width="900">

### 4.4.3. Web Applications Mock-ups

Para su mejor visualización se adjunta el enlace del figma:
https://www.figma.com/design/py3rabYJzPcLJN8k0b92su/Aplicaciones-Web?node-id=0-1&t=Pdr5EyHMWjawXyor-1

- Figura 69

  Iniciar Sesión

    <img src="assets/WebApps/Mockups/1.jpg" width="60%">

- Figura 70

  Crear Cuenta

    <img src="https://files.catbox.moe/boh7ie.jpg" width="60%">

- Figura 71

  Vistas para Recuperar contraseña

    <img src="assets/WebApps/Mockups/3.jpg" width="60%">

    <img src="assets/WebApps/Mockups/4.jpg" width="60%">

    <img src="assets/WebApps/Mockups/5.jpg" width="60%">

- Figura 72

  Mockups de error al iniciar Sesión o registrarse

    <img src="assets/WebApps/Mockups/6.jpg" width="60%">

    <img src="assets/WebApps/Mockups/7.jpg" width="60%">

- Figura 73

  Vista de inicio del cliente

    <img src="assets/WebApps/Mockups/8.jpg" width="60%">

- Figura 74

  Vista de Buscar Técnicos

    <img src="assets/WebApps/Mockups/9.jpg" width="60%">

- Figura 75

  Vista de Comparar Perfiles

    <img src="assets/WebApps/Mockups/10.jpg" width="60%">

- Figura 76

  Vistas relacionadas con Ofertas

    <img src="assets/WebApps/Mockups/11.jpg" width="60%">
    <img src="assets/WebApps/Mockups/12.jpg" width="60%">
    <img src="assets/WebApps/Mockups/13.jpg" width="60%">
    <img src="assets/WebApps/Mockups/14.jpg" width="60%">
    <img src="assets/WebApps/Mockups/15.jpg" width="60%">
    <img src="assets/WebApps/Mockups/16.jpg" width="60%">
    <img src="assets/WebApps/Mockups/17.jpg" width="60%">

- Figura 77

  Vista de configuración

    <img src="assets/WebApps/Mockups/18.jpg" width="60%">

- Figura 78

  Vistas de Personalizar Perfil

    <img src="assets/WebApps/Mockups/19.jpg" width="60%">
    <img src="assets/WebApps/Mockups/20.jpg" width="60%">

- Figura 79

  Vista de inicio del trabajador

    <img src="assets/WebApps/Mockups/22.jpg" width="60%">

- Figura 80

  Vista de buscar ofertas del trabajador

    <img src="assets/WebApps/Mockups/23.jpg" width="60%">

- Figura 81

  Vistas relacionadas con las ofertas del trabajador

    <img src="assets/WebApps/Mockups/24.jpg" width="60%">
    <img src="assets/WebApps/Mockups/25.jpg" width="60%">
    <img src="assets/WebApps/Mockups/26.jpg" width="60%">
    <img src="assets/WebApps/Mockups/27.jpg" width="60%">

- Figura 82

  Vista de reputacion del trabajador

    <img src="assets/WebApps/Mockups/28.jpg" width="60%">

- Figura 83

  Vistas de personalizar perfil del trabajador

    <img src="assets/WebApps/Mockups/29.jpg" width="60%">
    <img src="assets/WebApps/Mockups/30.jpg" width="60%">

### 4.4.4. Web Applications Wireflows User Flow Diagrams

En el User Flow de TuChambape, se detalla el _happy path_ que sigue Juan, el electricista, para lograr su objetivo principal de encontrar una oferta que satisfaga sus preferencias. Este flujo asegura una experiencia de usuario clara y eficiente, facilitando el acceso a la información crítica y postularse a ofertas de manera sencilla. Cada paso ilustra como Juan interactúa con la aplicación sin encontrar obstáculos, desde el inicio de sesión hasta postularse a una oferta y culminarla.

1. **Inicio de sesión en TuChambape**

   - **Página:** Pantalla de inicio de sesión
   - **Acción:** Juan abre la plataforma e ingresa sus credenciales para acceder.
   - **Lógica:** El sistema valida las credenciales ingresadas.
   - **Resultado:** Juan accede a la pantalla principal, donde puede explorar ofertas de trabajo disponibles.

2. **Acceso a Buscar Ofertas**

   - **Página:** Panel principal - Buscar Ofertas.
   - **Acción:** Juan entra en la sección "Buscar Ofertas" desde el panel lateral.
   - **Lógica:** La aplicación carga las ofertas activas disponibles en su zona, basadas en su perfil y ubicación.
   - **Resultado:** Juan visualiza una lista de trabajos disponibles que puede filtrar según sus preferencias.

3. **Aplicación de Filtros de Búsqueda**

   - **Página:** Buscar Ofertas
   - **Acción:** Juan aplica filtros como "Ubicación", "Rango de pago", "Disponibilidad" y "Medio de pago".
   - **Lógica:** El sistema filtra automáticamente las ofertas de trabajo según los criterios seleccionados.
   - **Resultado:** Juan visualiza una lista precisa de ofertas que se ajustan a sus necesidades y perfil.

4. **Revisión de Detalles de una Oferta**

   - **Página:** Ofertas
   - **Acción:** Juan selecciona una oferta específica y revisa la descripción del trabajo, condiciones, presupuesto y datos del cliente.
   - **Lógica:** La plataforma muestra los detalles de la oferta y un botón de "Postularse".
   - **Resultado:** Juan evalúa si la oferta es adecuada y está listo para enviar su postulación.

5. **Postulación a la Oferta**

   - **Página:** Ofertas
   - **Acción:** Juan selecciona "Postularse"
   - **Lógica:** La plataforma actualiza el estado de la postulación en tiempo real.
   - **Resultado:** Juan visualiza el estado actual de su solicitud.

6. **Seguimiento de la Postulación**

   - **Página:** Sección "Ofertas" – Subsección "Pendientes"
   - **Acción:** Juan ingresa a la sección de "Pendientes" para revisar el estado de la oferta a la que postuló.
   - **Lógica:** La plataforma muestra la sección Pendiente en la que se ve detalles de la oferta y se habilita la mensajería directa.
   - **Resultado:** Juan visualiza el estado actual de su solicitud y se mantiene informado sobre su avance.

7. **Confirmación de Trabajo Culminado**
   - **Página:** Sección "Ofertas" – Subsección "Finalizado"
   - **Acción:** Juan recibe la notificación de que el trabajo ha sido terminado por el cliente.
   - **Lógica:** La plataforma muestra la sección Finalizado y permite reseñar o culminar el trabajo.
   - **Resultado:** Juan reseña el trabajo que realizó y al cliente.

_Ahora procederemos a mostrar el User Flow Diagram de TuChambape, detallando el happy path que sigue Juan, el electricista, para postularse a una oferta y culminarla de la manera más rápida y eficiente._

<img src="assets/WebApps/foto1.jpg"  width="100%">

Nota. Este diagrama ilustra el flujo de usuario de Juan, elelectricista, en la postularse y trabajar en una oferta. Se detalla el proceso optimizado que sigue para garantizar una respuesta rápida y eficiente acción de buscar ofertas según sus preferencias.

_A continuación, algunas de nuestras User Stories junto con su diagrama:_

**US01:** Como usuario, quiero iniciar sesión en la aplicación, para acceder a mi cuenta personal.

User Persona: Clientes/Usuarios que requieren tecnicos

Happy path: El usuario completa sus datos correctamente en el formulario de iniciar sesión

Unhappy path: El usuario completa sus datos incorrectamente en el formulario de iniciar sesión

<img src="https://files.catbox.moe/btjbsx.png" alt="angie image" width="900">

**US02:** Como nuevo usuario, quiero registrarme en la plataforma, para poder usar los servicios.

User Persona: Clientes/Usuarios que requieren tecnicos

Happy path: El usuario completa sus datos correctamente en el formulario de registro

Unhappy path: El usuario completa sus datos incorrectamente en el formulario de registro

<img src="https://files.catbox.moe/l5tldp.png" alt="angie image" width="900">

**US03:** Como usuario, quiero recuperar mi contraseña, para poder acceder si la olvido.

User Persona: Clientes/Usuarios que requieren tecnicos

Happy path: El usuario valida su identidad satisfactoriamente y reestablece su contraseña

Unhappy path: El usuario no logra reestablecer su contraseña por no validar su identidad

<img src="https://files.catbox.moe/0ol735.png" alt="angie image" width="900">

### 4.5. Web Applications Prototyping

Los prototipos han sido diseñados para simular la interacción y la navegación, siguiendo los caminos establecidos en los diagramas de flujo de usuario. A través de estos prototipos, los usuarios pueden experimentar las funcionalidades clave de la aplicación y comprender cómo los distintos elementos interactúan entre sí.

Enlace: https://youtu.be/9PC1qOfyiXI

## 4.6. Domain-Driven Software Architecture.

### 4.6.1. Software Architecture Context Diagram.

![C4 Context Diagram](https://files.catbox.moe/w8d272.png)

### 4.6.2. Software Architecture Container Diagrams.

![C4 Container Diagram](./assets/C4/c4-container-diagram.png)

### 4.6.3. Software Architecture Components Diagrams.

#### Auth component

![C4 Component Diagram](./assets/C4/c4-auth-component.png)

#### User component

![C4 Component Diagram](./assets/C4/c4-user-component.png)

#### Payment component

![C4 Component Diagram](./assets/C4/c4-payment-component.png)

#### Proposal component

![C4 Component Diagram](./assets/C4/c4-proposal-component.png)

### 4.7. Software Object-Oriented Design.

### 4.7.1. Class Diagrams.

![Class Diagram](./assets/Diagrams/class-diagram.png)

### 4.7.2. Class Dictionary.

<table>
        <thead>
            <tr>
                <th>Clase</th>
                <th>Descripción</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td><strong>Account</strong></td>
                <td>Representa la cuenta base de acceso a la plataforma. Administra la autenticación (email y contraseña), y determina si un usuario está activo o inactivo.</td>
            </tr>
            <tr>
                <td><strong>AccountId</strong></td>
                <td> Identificador único de una cuenta. Asegura la identidad en todo el sistema, conectando múltiples contextos.</td>
            </tr>
            <tr>
                <td><strong>User</strong></td>
                <td>Representa a la identidad pública del usuario dentro de la plataforma. Almacena datos personales, rol, y perfil visible para otros usuarios.</td>
            </tr>
            <tr>
                <td><strong>Customer</strong></td>
                <td>Representa a un usuario con rol de cliente, es decir, aquel que solicita servicios. Incluye fecha de registro para historial.</td>
            </tr>
            <tr>
                <td><strong>Worker</strong></td>
                <td>Representa al usuario que ofrece servicios técnicos o profesionales. Gestiona su experiencia, habilidades, certificaciones, tarifas y disponibilidad.</td>
            </tr>
            <tr>
                <td><strong>Experience</strong></td>
                <td>Representa las experiencias laborales pasadas del trabajador. Aporta credibilidad y trayectoria al perfil del Worker.</td>
            </tr>
            <tr>
                <td><strong>Review</strong></td>
                <td>Representa una evaluación realizada por un usuario hacia otro tras una interacción o servicio completado. Permite generar confianza y reputación en la plataforma.</td>
            </tr>
            <tr>
                <td><strong>ReviewId</strong></td>
                <td>Identificador único que asegura trazabilidad de cada evaluación realizada en la plataforma.</td>
            </tr>
            <tr>
                <td><strong>Proposal</strong></td>
                <td>Representa una propuesta de trabajo que un Worker envía a un Customer. Define los términos del servicio como precio, tiempo estimado y descripción del trabajo.</td>
            </tr>
            <tr>
                <td><strong>SalesOrder_Payment</strong></td>
                <td>Representa la orden de pago relacionada a un servicio aceptado. Gestiona montos, estado del pago y registro de la garantía inicial.</td>
            </tr>
            <tr>
                <td><strong>GuaranteePayment</strong></td>
                <td>Representa una garantía inicial pagada al aceptar una propuesta. Asegura compromiso entre las partes.</td>
            </tr>
            <tr>
                <td><strong>Money</strong></td>
                <td>Representa el dinero (monto y moneda). Centraliza la lógica de operaciones monetarias como suma o resta.</td>
            </tr>
            <tr>
                <td><strong>Chat</strong></td>
                <td>Representa un canal de comunicación entre usuarios (cliente-trabajador). Puede incluir múltiples participantes y mensajes.</td>
            </tr>
            <tr>
                <td><strong>Message</strong></td>
                <td>Representa cada mensaje individual dentro de un chat. Contiene contenido, autor y fecha de envío.</td>
            </tr>
            <tr>
                <td><strong>Ticket</strong></td>
                <td>Representa una queja o disputa surgida durante una orden de servicio. Permite resolver conflictos entre usuarios, ya sea a favor del cliente o trabajador.</td>
            </tr>
<table>

## 4.8. Database Design.

### 4.8.1. Database Diagram.

<div align="center">
<img src="assets/Diagrams/Base_de_datos.png" alt="data_base" />
</div>

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

![Netifly deploy](https://files.catbox.moe/bunapo.png)

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
![Hero](./assets/images/chapter-5/Hero.png)

Beneficios: Esta sección presenta las principales ventajas que ofrece la plataforma tanto para trabajadores técnicos como para clientes que buscan servicios, destacando la facilidad de uso, seguridad y eficiencia

![Beneficios](./assets/images/chapter-5/Beneficios.png)

Categorías de servicios: Esta sección muestra los tipos de servicios técnicos que se pueden encontrar en la plataforma, ayudando al usuario a identificar qué profesionales puede contratar

![Categorías de servicios](./assets/images/chapter-5/Categorias.png)

Cómo funciona: Se explica el proceso paso a paso para utilizar la plataforma, tanto para trabajadores técnicos como para clientes

![Cómo funciona](./assets/images/chapter-5/ComoFunciona.png)

Testimonios: Esta sección muestra experiencias de usuarios reales que han utilizado la plataforma, generando confianza en nuevos visitantes

![Testimonios](./assets/images/chapter-5/Testimonios.png)

Estadísticas: Esta sección muestra con datos cuantitativos el impacto positivo de la plataforma en términos de usuarios registrados, servicios completados y satisfacción del cliente

![Estadísticas](./assets/images/chapter-5/Estadisticas.png)

Contacto: Formulario que permite a los usuarios enviar consultas o solicitudes directamente desde la landing page

![Contacto](./assets/images/chapter-5/Contacto.png)


#### 5.2.1.6. Services Documentation Evidence for Sprint Review.

Para este sprint no fue contemplada la evidencia de documentación de los servicios API.

#### 5.2.1.7. Software Deployment Evidence for Sprint Review.

Para la entrega del Sprint número 1, se desplegó la landing page completa en Netlify. Se configuró para que la rama principal utilizada fuera "main", ubicada en la raíz, siguiendo una estructura organizada de carpetas y archivos.

![Netifly deploy](./assets/images/chapter-5/netifly-deploy.png)

#### 5.2.1.8. Team Collaboration Insights during Sprint.

![Insights](./assets/images/chapter-5/Insights.PNG)

### 5.2.2. Sprint 2

#### 5.2.2.1.Sprint Planning 2.

Dentro del marco de trabajo Scrum, cada Sprint constituye un periodo de tiempo fijo y breve en el que el equipo de desarrollo trabaja de manera enfocada para alcanzar un objetivo específico que contribuya al cumplimiento del Product Goal (Schwaber, K. & Sutherland, J., 2020). En el contexto del desarrollo de la plataforma TuChamba, el Sprint #2 dio inicio el 5/05/2025, y su meta consiste en implementar la aplicación web del lado frontend utilizando Vue.js y PrimeVue. Durante este Sprint, se desarrollaron las funcionalidades esenciales para ambos segmentos objetivo - trabajadores técnicos independientes y usuarios que requieren servicios técnicos: los clientes pueden explorar perfiles de diferentes trabajadores técnicos y solicitar sus servicios de manera intuitiva, mientras que los trabajadores técnicos tienen acceso a herramientas de gestión que les permiten configurar sus tarifas, administrar sus servicios ofrecidos y visualizar las solicitudes de trabajo asignadas.

<table>
   <tr>
      <td colspan="1" align="center"><b>Sprint #</b></td>
      <td colspan="1" align="center">Sprint 2</td>
   </tr>
   <tr>
      <td colspan="2" align="center"><b>Sprint Planning Background</b></td>
   </tr>
   <tr>
      <td colspan="1" align="center"><b>Date</b></td>
      <td colspan="1">2025-05-05</td>
   </tr>
   <tr>
      <td colspan="1" align="center"><b>Time</b></td>
      <td colspan="1">09:00 PM</td>
   </tr>
   <tr>
      <td colspan="1" align="center"><b>Location</b></td>
      <td colspan="1">Reunión virtual mediante la aplicación Discord</td>
   </tr>
   <tr>
      <td colspan="1" align="center"><b>Prepare By</b></td>
      <td colspan="1">Alejandro Oroncoy</td>
   </tr>
   <tr>
      <td colspan="1" align="center"><b>Attendees (to planning meeting)</b></td>
      <td colspan="1">Oliver Jonseck, Diego Mora, Daniel Valzian, Eduardo Cossar, Roy Fernandez</td>
   </tr>
   <tr>
      <td colspan="1" align="center"><b>Sprint n - 2 Review Summary</b></td>
      <td colspan="1">Durante este sprint se implementó el frontend de la aplicación web utilizando angular, incorporando las funcionalidades principales para los roles de cliente y técnico.</td>
   </tr>
   <tr>
      <td colspan="1" align="center"><b>Sprint n - 2 Retrospective Summary</b></td>
      <td colspan="1">Se identificó la necesidad de mejorar la planificación de tareas y la integración temprana de pruebas para evitar retrabajos. También se destacó una mayor fluidez en la comunicación del equipo respecto al sprint anterior, lo que permitió avanzar con mayor claridad en los entregables.</td>
   </tr>
   <tr>
      <td colspan="2" align="center"><b>Sprint Goal & User Stories</b></td>
   </tr>
   <tr>
      <td colspan="1" align="center"><b>Sprint 2 Goal</b></td>
      <td colspan="1"><b>Our focus in on</b> developing the full web application frontend using angular, addressing both customer and worker user roles.<br><b>We believe it delivers</b>a functional and responsive interface that supports key actions such as booking services for customers and managing appointments and pricing for workers.<br><b>This will be confirmed when</b> customers can successfully explore available workers and make reservations, and workers are able to configure their services, view appointments, and interact with their dashboards smoothly.</td>
   </tr>
   <tr>
      <td colspan="1" align="center"><b>Sprint 2 Velocity</b></td>
      <td colspan="1"></td>
   </tr>
   <tr>
      <td colspan="1" align="center"><b>Sum of Story Points</b></td>
      <td colspan="1"></td>
   </tr>

   <tr>
</tr>
</table>


#### 5.2.2.2. Aspect Leaders and Collaborators.

Para este Sprint, se han identificado los principales aspectos del frontend web application de TuChamba.pe. Con el fin de mejorar la organización y la comunicación del equipo, se ha elaborado la matriz Leadership and Collaboration Matrix (LACX), donde se define quién asume el rol de Líder (L) y quiénes participan como Colaboradores (C) en cada uno de estos aspectos clave. Esta distribución facilita una ejecución más clara y eficiente de las tareas asignadas.

| **Team Member**                     | **GitHub Username** | **auth** | **offers** | **compare-profiles** | **public** | **shared** | **dashboard** | **profiles** | **search profiles** | **services** | **subscription** |
|-------------------------------------|---------------------|----------|------------|----------------------|------------|------------|---------------|--------------|---------------------|--------------|------------------|
| Valdizán Grijalba, Daniel            | DanielV06            | L        | C          | C                    | C          | C          | C             | C            | C                   | C            | C                |
| Mora Blas, Diego Alonzo        | diegoalonzomora             | C        | C          | L                    | C          | C          | C             | L            | C                   | C            | L                |
| Fernandez Remon, Roy       | RTPX26            | C        | C          | C                    | C          | C          | L             | C            | C                   | C            | C                |
| Oroncoy Almeyda, Alejandro Daniel   | alejooroncoy        | C        | L          | C                    | C          | C          | C             | C            | C                   | C            | C                |
| Cossar Sanchez, Eduardo Jose        | coleeeee-dev        | C        | C          | C                    | L          | C          | C             | C            | L                   | C            | C                |
| Jonseck Choque, Oliver      | Olizzy-upc           | C        | C          | C                    | C          | L          | C             | C            | C                   | L            | C                |


#### 5.2.2.3.Sprint Backlog 2.

En el segundo sprint backlog, el equipo tuvo la intención de comenzar y completar el desarrollo del frontend de la aplicación web, tanto para el rol de cliente (customer) como de trabajador/técnico (worker). La herramienta utilizada para organizar y gestionar las tareas del equipo continuó siendo Trello, permitiendo dividir las user stories en tareas manejables y asignarlas a los miembros según sus habilidades específicas. El objetivo principal del sprint fue implementar las funcionalidades clave de ambos roles, asegurando una interfaz intuitiva, responsiva y funcional utilizando Vue.js y PrimeVue.

<table border="1" cellspacing="0" cellpadding="5">
  <tr>
    <td colspan="2" align="center"><b>Sprint #</b></td>
    <td colspan="6" align="center"><b>Sprint 2</b></td>
  </tr>
  <tr>
    <td colspan="2"><b>User Story</b></td>
    <td colspan="6" align="center"><b>Work-Item/Task</b></td>
  </tr>
  <tr>
    <td><b>Id</b></td>
    <td><b>Title</b></td>
    <td><b>Task Id</b></td>
    <td><b>Task Title</b></td>
    <td><b>Description</b></td>
    <td><b>Estimation (Hours)</b></td>
    <td><b>Assigned To</b></td>
    <td><b>Status (To-do/In-Process/To-Review/Done)</b></td>
  </tr>
  <tr>
    <td rowspan="2">US01</td>
    <td rowspan="2">Inicio de sesión</td>
    <td>T1</td>
    <td>Diseño de interfaz de login</td>
    <td>Diseñar la interfaz de inicio de sesión con campos de usuario y contraseña.</td>
    <td>5</td>
    <td>Oliver Jonseck</td>
    <td>Done</td>
  </tr>
  <tr>
    <td>T2</td>
    <td>Implementación de autenticación</td>
    <td>Desarrollar la lógica de autenticación y manejo de sesiones.</td>
    <td>5</td>
    <td>Alejandro Oroncoy</td>
    <td>Done</td>
  </tr>
  <tr>
    <td rowspan="2">US02</td>
    <td rowspan="2">Creación de cuenta</td>
    <td>T1</td>
    <td>Diseño del formulario de registro</td>
    <td>Crear la interfaz del formulario de registro con validaciones.</td>
    <td>5</td>
    <td>Diego Mora</td>
    <td>Done</td>
  </tr>
  <tr>
    <td>T2</td>
    <td>Implementación del registro</td>
    <td>Desarrollar la lógica de registro y almacenamiento de usuarios.</td>
    <td>5</td>
    <td>Roy Fernandez</td>
    <td>Done</td>
  </tr>
  <tr>
    <td rowspan="2">US03</td>
    <td rowspan="2">Recuperar contraseña</td>
    <td>T1</td>
    <td>Diseño de recuperación</td>
    <td>Diseñar la interfaz para recuperación de contraseña.</td>
    <td>5</td>
    <td>Eduardo Cossar</td>
    <td>Done</td>
  </tr>
  <tr>
    <td>T2</td>
    <td>Implementación de recuperación</td>
    <td>Desarrollar el sistema de recuperación de contraseña.</td>
    <td>5</td>
    <td>Daniel Valdizan</td>
    <td>In-Process</td>
  </tr>
  <tr>
    <td>US04</td>
    <td>Cambio de vista cliente/trabajador</td>
    <td>T1</td>
    <td>Implementación de cambio de vista</td>
    <td>Permitir al usuario alternar entre vista de cliente y trabajador.</td>
    <td>5</td>
    <td>Alejandro Oroncoy</td>
    <td>Done</td>
  </tr>
  <tr>
    <td>US05</td>
    <td>Navegación en la interfaz: Cliente</td>
    <td>T1</td>
    <td>Diseño de navegación cliente</td>
    <td>Diseñar la navegación para que el cliente explore y contrate trabajadores.</td>
    <td>7</td>
    <td>Oliver Jonseck</td>
    <td>Done</td>
  </tr>
  <tr>
    <td>US06</td>
    <td>Navegación interfaz trabajador</td>
    <td>T1</td>
    <td>Diseño de navegación trabajador</td>
    <td>Diseñar la navegación para que el trabajador gestione sus servicios y clientes.</td>
    <td>6</td>
    <td>Eduardo Cossar</td>
    <td>Done</td>
  </tr>
  <tr>
    <td>US07</td>
    <td>Personalización de perfil técnico</td>
    <td>T1</td>
    <td>Personalización de perfil</td>
    <td>Permitir al trabajador personalizar su perfil con habilidades y experiencia.</td>
    <td>5</td>
    <td>Diego Mora</td>
    <td>Done</td>
  </tr>
  <tr>
    <td>US08</td>
    <td>Personalización de perfil cliente</td>
    <td>T1</td>
    <td>Personalización de perfil cliente</td>
    <td>Permitir al cliente personalizar su perfil para mejores recomendaciones.</td>
    <td>3</td>
    <td>Roy Fernandez</td>
    <td>Done</td>
  </tr>
  <tr>
    <td>US09</td>
    <td>Configuración</td>
    <td>T1</td>
    <td>Gestión de configuración</td>
    <td>Permitir al usuario gestionar notificaciones, idioma, etc.</td>
    <td>5</td>
    <td>Oliver Jonseck</td>
    <td>In-progress</td>
  </tr>
  <tr>
    <td>US10</td>
    <td>Verificación del perfil del trabajador</td>
    <td>T1</td>
    <td>Verificación de perfil</td>
    <td>Mostrar al cliente si un trabajador está verificado.</td>
    <td>5</td>
    <td>Alejandro Oroncoy</td>
    <td>Done</td>
  </tr>
  <tr>
    <td>US11</td>
    <td>Sistema de reseñas y calificación</td>
    <td>T1</td>
    <td>Implementación de reseñas</td>
    <td>Permitir dejar reseñas y calificaciones a los trabajadores.</td>
    <td>5</td>
    <td>Diego Mora</td>
    <td>To-do</td>
  </tr>
  <tr>
    <td>US14</td>
    <td>Búsqueda por filtro</td>
    <td>T1</td>
    <td>Implementación de filtros</td>
    <td>Permitir filtrar trabajadores por ubicación, experiencia, etc.</td>
    <td>5</td>
    <td>Eduardo Cossar</td>
    <td>Done</td>
  </tr>
  <tr>
    <td>US15</td>
    <td>Recomendación de perfil</td>
    <td>T1</td>
    <td>Sistema de recomendaciones</td>
    <td>Recomendar trabajadores a los clientes.</td>
    <td>8</td>
    <td>Daniel Valdizan</td>
    <td>To-do</td>
  </tr>
  <tr>
    <td>US16</td>
    <td>Comparación de perfiles</td>
    <td>T1</td>
    <td>Comparar perfiles</td>
    <td>Permitir comparar varios perfiles de trabajadores.</td>
    <td>5</td>
    <td>Diego Mora</td>
    <td>Done</td>
  </tr>
  <tr>
    <td>US17</td>
    <td>Visualización de reseñas en comparación</td>
    <td>T1</td>
    <td>Mostrar reseñas en comparación</td>
    <td>Mostrar reseñas al comparar perfiles.</td>
    <td>3</td>
    <td>Oliver Jonseck</td>
    <td>Done</td>
  </tr>
  <tr>
    <td>US18</td>
    <td>Gestión de disponibilidad</td>
    <td>T1</td>
    <td>Actualizar disponibilidad</td>
    <td>Permitir al trabajador actualizar sus horarios disponibles.</td>
    <td>4</td>
    <td>Alejandro Oroncoy</td>
    <td>Done</td>
  </tr>
  <tr>
    <td>US24</td>
    <td>Crear y enviar propuestas</td>
    <td>T1</td>
    <td>Envío de propuestas</td>
    <td>Permitir al trabajador enviar propuestas personalizadas a los clientes.</td>
    <td>8</td>
    <td>Daniel Valdizan</td>
    <td>In-progress</td>
  </tr>
  <tr>
    <td>US26</td>
    <td>Gestión de habilidades técnicas</td>
    <td>T1</td>
    <td>Actualizar habilidades</td>
    <td>Permitir al trabajador mantener actualizada su lista de habilidades.</td>
    <td>4</td>
    <td>Eduardo Cossar</td>
    <td>In-progress</td>
  </tr>
  <tr>
</table>

Enlace para acceder al Trello: [Trello Sprint Backlog 2]()

#### 5.2.2.4.Development Evidence for Sprint Review.

| Repository                  | Branch            | Commit Id | Commit Message                                                                 | Commited on (Date) |
|-----------------------------|-------------------|-----------|-------------------------------------------------------------------------------|--------------------|
| Frontend-Web-Applications   | develop           | d965077   | feat: add proposals                                                      | 15/05/2025         |
| Frontend-Web-Applications   | develop           | 54c8a21   | refactor: Refactor of auth                                                | 15/05/2025         |
| Frontend-Web-Applications   | develop           | 2a7b3c4   | fix: Update offers                                                            | 15/05/2025         |
| Frontend-Web-Applications   | develop           | 3b8d5e6   | merge: resolve merge                                                          | 15/05/2025         |
| Frontend-Web-Applications   | develop           | 4c9f7g8   | feature: first version of login                                               | 15/05/2025         |
| Frontend-Web-Applications   | develop           | 5d0h1i2   | fix: update cards compare-profiles                                          | 15/05/2025         |
| Frontend-Web-Applications   | develop           | 6e2j3k4   | chore: add technicians image                                                  | 15/05/2025         |
| Frontend-Web-Applications   | develop           | 7f4l5m6   | fix: update search filter                                                     | 15/05/2025         |
| Frontend-Web-Applications   | develop           | 8g6n7o8   | fix: Fixing the Compare Profiles header                                    | 15/05/2025         |
| Frontend-Web-Applications   | develop           | 9h8p9q0   | refactor(worker): reorganize worker components into public and worker directories | 15/05/2025         |
| Frontend-Web-Applications   | develop           | 1i0r1s2   | fix: Update sidebar                                                           | 15/05/2025         |
| Frontend-Web-Applications   | develop           | 2j2t3u4   | fix: Update sidebar                                                           | 15/05/2025         |
| Frontend-Web-Applications   | develop           | 3k4v5w6   | fix: solve sidebar                                                            | 15/05/2025         |
| Frontend-Web-Applications   | develop           | 4l6x7y8   | fix: Update offer new                                                         | 15/05/2025         |
| Frontend-Web-Applications   | develop           | 14/05/2025| fix: Update offer page                                                        | 14/05/2025         |
| Frontend-Web-Applications   | develop           | 14/05/2025| feat: implementation route                                                    | 14/05/2025         |
| Frontend-Web-Applications   | develop           | 14/05/2025| fix: Update develop                                                           | 14/05/2025         |
| Frontend-Web-Applications   | develop           | 14/05/2025| build(develop): Update angular                                            | 14/05/2025         |
| Frontend-Web-Applications   | develop           | 14/05/2025| fix: Update develop                                                           | 14/05/2025         |
| Frontend-Web-Applications   | develop           | 14/05/2025| Merge branch 'feature/configuration-worker' of https://github.com/1ASI0729-2510-4317-G1-TuChambape/report into develop | 14/05/2025         |
| Frontend-Web-Applications   | develop           | 14/05/2025| Merge branch 'feature/offers' of https://github.com/1ASI0729-2510-4317-G1-TuChambape/report into develop | 14/05/2025         |
| Frontend-Web-Applications   | develop           | 14/05/2025| Merge branch 'feature/myprofile-configuration-worker' of https://github.com/1ASI0729-2510-4317-G1-TuChambape/report into develop | 14/05/2025         |
| Frontend-Web-Applications   | develop           | 14/05/2025| Merge branch 'feature/add-angular-material' of https://github.com/1ASI0729-2510-4317-G1-TuChambape/report into develop | 14/05/2025         |
| Frontend-Web-Applications   | develop           | 14/05/2025| Merge branch 'feature/myprofile-client' of https://github.com/1ASI0729-2510-4317-G1-TuChambape/report into develop | 14/05/2025         |
| Frontend-Web-Applications   | develop           | 14/05/2025| Merge branch 'feature/compare-profiles' of https://github.com/1ASI0729-2510-4317-G1-TuChambape/report into develop | 14/05/2025         |
| Frontend-Web-Applications   | develop           | 14/05/2025| refactor(offers): move SearchOffers component from views to pages directory   | 14/05/2025         |
| Frontend-Web-Applications   | develop           | 14/05/2025| refactor(dashboard): move dashboard views to page                             | 14/05/2025         |
| Frontend-Web-Applications   | develop           | 14/05/2025| feat:compare-profile                                                          | 14/05/2025         |
| Frontend-Web-Applications   | develop           | 14/05/2025| feat: add tecnical cards                                                      | 14/05/2025         |
| Frontend-Web-Applications   | develop           | 13/05/2025| feat:add myprofile-myplans-configuration                                      | 13/05/2025         |
| Frontend-Web-Applications   | develop           | 13/05/2025| feat: fix filtro de busqueda                                                  | 13/05/2025         |
| Frontend-Web-Applications   | develop           | 13/05/2025| feat: fix searchTec                                                           | 13/05/2025         |



#### 5.2.2.5.Execution Evidence for Sprint Review.

<figure>
  <img src="https://files.catbox.moe/naen5b.png" alt="Login Screen">
  <figcaption>Pantalla de Inicio de Sesión</figcaption>
</figure>

<figure>
  <img src="https://files.catbox.moe/zar4rb.png" alt="Sign-up Screen">
  <figcaption>Pantalla de Registro de Usuario</figcaption>
</figure>

<figure>
  <img src="https://files.catbox.moe/q4dke2.png" alt="Pass Recovery Screen">
  <figcaption>Pantalla de Recuperación de Contraseña</figcaption>
</figure>



#### 5.2.2.6.Services Documentation Evidence for Sprint Review.
A continuación, se presentan tres fragmentos de código que evidencian el uso e implementación de los servicios en el aplicación, abarcando desde la configuración de rutas hasta la lógica de negocio y la presentación de datos al usuario:

1. Archivo de Rutas 
   Archivo: router/index.js
   Función: Define la estructura de navegación de toda la aplicación, tanto para el cliente como para el trabajador.
  
Importancia:
-Permite acceder a las páginas donde se usan servicios como worker, customer, offers, etc.
-Es el punto de entrada para mostrar componentes que a su vez usan servicios para obtener, actualizar o eliminar datos.
<img src="https://files.catbox.moe/nelzps.png" alt="Routes">

2. httpService (Implementation Service Class)
   Archivo: http.service.ts
   Función: Es una clase utilitaria que centraliza operaciones comunes de los servicios (GET, PUT, PATCH). Es reutilizada por servicios específicos como OfferService, WorkerService, etc.

Importancia:

Estandariza el consumo de APIs REST.

Evita duplicar código al implementar métodos reutilizables para manejar recursos.

Permite manejar errores con catchError y hacer reintentos con retry.

<img src="https://files.catbox.moe/tdznni.png" alt="base-service">

#### 5.2.2.7.Software Deployment Evidence for Sprint Review.

Para realizar el deployment de la aplicación web, se utilizó la plataforma de Netlify.

<img src="https://files.catbox.moe/d596ph.png" alt="Netlify">

Link de la aplicación desplegada: https://tuchamba-pe.netlify.app/

#### 5.2.2.8.Team Collaboration Insights during Sprint.

Durante el Sprint 2, se realizó la segmentación de tareas por features y se asignaron a los miembros del equipo de acuerdo a sus habilidades y experiencia. Esto permitió una mejor distribucion de las tareas y un avance mas fluido en el desarrollo.

<img src="https://files.catbox.moe/5mh548.png" alt="Network Graph">

![Insights](./assets/images/chapter-5/Insights.PNG)


### 5.2.3. Sprint 3

#### 5.2.3.1.Sprint Planning 3

Dentro del marco de trabajo Scrum, cada Sprint constituye un periodo de tiempo fijo y breve en el que el equipo de desarrollo trabaja de manera enfocada para alcanzar un objetivo específico que contribuya al cumplimiento del Product Goal (Schwaber, K. & Sutherland, J., 2020). En el contexto del desarrollo de la plataforma TuChamba, el Sprint #3 dio inicio el 29/05/2025, y su meta consiste en completar la aplicación web del lado frontend y comenzar con el backend . Durante este Sprint, se desarrollaron las funcionalidades esenciales para ambos segmentos objetivo - trabajadores técnicos independientes y usuarios que requieren servicios técnicos: los clientes pueden explorar perfiles de diferentes trabajadores técnicos y solicitar sus servicios de manera intuitiva, mientras que los trabajadores técnicos tienen acceso a herramientas de gestión que les permiten configurar sus tarifas, administrar sus servicios ofrecidos y visualizar las solicitudes de trabajo asignadas.

<table>
   <tr>
      <td colspan="1" align="center"><b>Sprint #</b></td>
      <td colspan="1" align="center">Sprint 3</td>
   </tr>
   <tr>
      <td colspan="2" align="center"><b>Sprint Planning Background</b></td>
   </tr>
   <tr>
      <td colspan="1" align="center"><b>Date</b></td>
      <td colspan="1">2025-05-05</td>
   </tr>
   <tr>
      <td colspan="1" align="center"><b>Time</b></td>
      <td colspan="1">09:00 PM</td>
   </tr>
   <tr>
      <td colspan="1" align="center"><b>Location</b></td>
      <td colspan="1">Reunión virtual mediante la aplicación Discord</td>
   </tr>
   <tr>
      <td colspan="1" align="center"><b>Prepare By</b></td>
      <td colspan="1">Alejandro Oroncoy</td>
   </tr>
   <tr>
      <td colspan="1" align="center"><b>Attendees (to planning meeting)</b></td>
      <td colspan="1">Integrantes del equipo</td>
   </tr>
   <tr>
      <td colspan="1" align="center"><b>Sprint n - 3 Review Summary</b></td>
      <td colspan="1">Durante este sprint se implementó el backend de la aplicación, incorporando las funcionalidades principales para los roles de cliente y técnico.</td>
   </tr>
   <tr>
      <td colspan="1" align="center"><b>Sprint n - 3 Retrospective Summary</b></td>
      <td colspan="1">Se identificó la necesidad de mejorar la planificación de tareas y la integración temprana de pruebas para evitar retrabajos. También se destacó una mayor fluidez en la comunicación del equipo respecto al sprint anterior, lo que permitió avanzar con mayor claridad en los entregables.</td>
   </tr>
   <tr>
      <td colspan="2" align="center"><b>Sprint Goal & User Stories</b></td>
   </tr>
   <tr>
      <td colspan="1" align="center"><b>Sprint 3 Goal</b></td>
      <td colspan="1"><b>Our focus in on</b> developing the full web application backend , addressing both customer and worker user roles.<br><b>We believe it delivers</b>a functional and responsive interface that supports key actions such as booking services for customers and managing appointments and pricing for workers.<br><b>This will be confirmed when</b> customers can successfully explore available workers and make reservations, and workers are able to configure their services, view appointments, and interact with their dashboards smoothly.</td>
   </tr>
   <tr>
      <td colspan="1" align="center"><b>Sprint 3 Velocity</b></td>
      <td colspan="1">5</td>
   </tr>
   <tr>
      <td colspan="1" align="center"><b>Sum of Story Points</b></td>
      <td colspan="1">18</td>
   </tr>

   <tr>
</tr>
</table>


#### 5.2.3.2. Aspect Leaders and Collaborators.

Para este Sprint, se han identificado los principales aspectos del frontend web application de TuChamba.pe. Con el fin de mejorar la organización y la comunicación del equipo, se ha elaborado la matriz Leadership and Collaboration Matrix (LACX), donde se define quién asume el rol de Líder (L) y quiénes participan como Colaboradores (C) en cada uno de estos aspectos clave. Esta distribución facilita una ejecución más clara y eficiente de las tareas asignadas.

| **Team Member**                     | **GitHub Username** | **auth** | **offers** | **compare-profiles** | **public** | **shared** | **dashboard** | **profiles** | **search profiles** | **services** | **subscription** |
|-------------------------------------|---------------------|----------|------------|----------------------|------------|------------|---------------|--------------|---------------------|--------------|------------------|
| Fernandez, Roy            | rofy            | L        | C          | C                    | C          | C          | C             | C            | C                   | C            | C                |
| Mora, Diego       | dmora             | C        | C          | L                    | C          | C          | C             | L            | C                   | C            | L                |
| Oliver Jonseck    | oliverj           | C        | C          | C                    | C          | C          | L             | C            | C                   | C            | C                |
| Oroncoy Almeyda, Alejandro Daniel   | alejooroncoy        | C        | L          | C                    | C          | C          | C             | C            | C                   | C            | C                |
| Cossar Sanchez, Eduardo Jose        | coleeeee-dev        | C        | C          | C                    | L          | C          | C             | C            | L                   | C            | C                |
|


#### 5.2.3.3.Sprint Backlog 3.

En el tercer sprint backlog, el equipo tuvo la intención de completar el desarrollo del backend de la aplicación web, tanto para el rol de cliente (customer) como de trabajador/técnico (worker). Por otro lado, se inicio con el proceso de desarrollo del backend. La herramienta utilizada para organizar y gestionar las tareas del equipo continuó siendo Trello, permitiendo dividir las user stories en tareas manejables y asignarlas a los miembros según sus habilidades específicas. El objetivo principal del sprint fue implementar las funcionalidades clave de ambos roles, asegurando una interfaz intuitiva, responsiva y funcional.

<table border="1" cellspacing="0" cellpadding="5">
  <tr>
    <td colspan="2" align="center"><b>Sprint #</b></td>
    <td colspan="6" align="center"><b>Sprint 3</b></td>
  </tr>
  <tr>
    <td colspan="2"><b>User Story</b></td>
    <td colspan="6" align="center"><b>Work-Item/Task</b></td>
  </tr>
  <tr>
    <td><b>Id</b></td>
    <td><b>Title</b></td>
    <td><b>Task Id</b></td>
    <td><b>Task Title</b></td>
    <td><b>Description</b></td>
    <td><b>Estimation (Hours)</b></td>
    <td><b>Assigned To</b></td>
    <td><b>Status (To-do/In-Process/To-Review/Done)</b></td>
  </tr>
  <tr>
    <td rowspan="2">US01</td>
    <td rowspan="2">Inicio de sesión</td>
    <td>T1</td>
    <td>Diseño de interfaz de login</td>
    <td>Diseñar la interfaz de inicio de sesión con campos de usuario y contraseña.</td>
    <td>4</td>
    <td>Diego Mora</td>
    <td>Done</td>
  </tr>
  <tr>
   
  </tr>
  
  <tr>
    <td rowspan="2">US03</td>
    <td rowspan="2">Recuperar contraseña</td>
    <td>T1</td>
    <td>Diseño de recuperación</td>
    <td>Diseñar la interfaz para recuperación de contraseña.</td>
    <td>4</td>
    <td>Eduardo Cossar</td>
    <td>Done</td>
  </tr>
  <tr>
    <td>T2</td>
    <td>Implementación de recuperación</td>
    <td>Desarrollar el sistema de recuperación de contraseña.</td>
    <td>5</td>
    <td>Alejandro Oroncoy</td>
    <td>In-Process</td>
  </tr>
 
  <tr>
    <td>US09</td>
    <td>Configuración</td>
    <td>T1</td>
    <td>Gestión de configuración</td>
    <td>Permitir al usuario gestionar notificaciones, idioma, etc.</td>
    <td>6</td>
    <td>Roy Fernandez</td>
    <td>In-progress</td>
  </tr>
  
  <tr>
    <td>US11</td>
    <td>Sistema de reseñas y calificación</td>
    <td>T1</td>
    <td>Implementación de reseñas</td>
    <td>Permitir dejar reseñas y calificaciones a los trabajadores.</td>
    <td>6</td>
    <td>Diego Mora </td>
    <td>To-do</td>
  </tr>
 
  <tr>
    <td>US15</td>
    <td>Recomendación de perfil</td>
    <td>T1</td>
    <td>Sistema de recomendaciones</td>
    <td>Recomendar trabajadores a los clientes.</td>
    <td>8</td>
    <td>Oliver Jonseck</td>
    <td>To-do</td>
  </tr>
  
  <tr>
    <td>US24</td>
    <td>Crear y enviar propuestas</td>
    <td>T1</td>
    <td>Envío de propuestas</td>
    <td>Permitir al trabajador enviar propuestas personalizadas a los clientes.</td>
    <td>8</td>
    <td>Roy Fernandez</td>
    <td>Done</td>
  </tr>
  <tr>
    <td>US26</td>
    <td>Gestión de habilidades técnicas</td>
    <td>T1</td>
    <td>Actualizar habilidades</td>
    <td>Permitir al trabajador mantener actualizada su lista de habilidades.</td>
    <td>5</td>
    <td>Eduardo Cossar</td>
    <td>In-progress</td>
  </tr>
  <tr>
</table>

Enlace para acceder al Trello: [Trello Sprint Backlog 3](https://trello.com/invite/b/683a3962930000c3d5ef87f0/ATTI302ef236cfd65c123fb226b68a19bffeF566BB88/jobconnect-sprint-3)


#### 5.2.3.4. Development Evidence for Sprint Review.

<img src="https://files.catbox.moe/rxnel4.jpeg" alt="Database evidence in github">

#### 5.2.4.5 Execution Evidence for Sprint Review

<img src="https://files.catbox.moe/ja3eej.jpeg" alt="Swagger evidence in github">

### 5.2.4. Sprint 4

#### 5.2.4.1.Sprint Planning 4

Dentro del marco de trabajo Scrum, cada Sprint constituye un periodo de tiempo fijo y breve en el que el equipo de desarrollo trabaja de manera enfocada para alcanzar un objetivo específico que contribuya al cumplimiento del Product Goal (Schwaber, K. & Sutherland, J., 2020). En el contexto del desarrollo de la plataforma TuChamba, el Sprint #3 dio inicio el 29/05/2025, y su meta consiste en completar la aplicación web del lado frontend y comenzar con el backend . Durante este Sprint, se desarrollaron las funcionalidades esenciales para ambos segmentos objetivo - trabajadores técnicos independientes y usuarios que requieren servicios técnicos: los clientes pueden explorar perfiles de diferentes trabajadores técnicos y solicitar sus servicios de manera intuitiva, mientras que los trabajadores técnicos tienen acceso a herramientas de gestión que les permiten configurar sus tarifas, administrar sus servicios ofrecidos y visualizar las solicitudes de trabajo asignadas.

<table>
   <tr>
      <td colspan="1" align="center"><b>Sprint #</b></td>
      <td colspan="1" align="center">Sprint 4</td>
   </tr>
   <tr>
      <td colspan="2" align="center"><b>Sprint Planning Background</b></td>
   </tr>
   <tr>
      <td colspan="1" align="center"><b>Date</b></td>
      <td colspan="1">2025-06-28</td>
   </tr>
   <tr>
      <td colspan="1" align="center"><b>Time</b></td>
      <td colspan="1">09:00 PM</td>
   </tr>
   <tr>
      <td colspan="1" align="center"><b>Location</b></td>
      <td colspan="1">Reunión virtual mediante la aplicación Discord</td>
   </tr>
   <tr>
      <td colspan="1" align="center"><b>Prepare By</b></td>
      <td colspan="1">Alejandro Oroncoy</td>
   </tr>
   <tr>
      <td colspan="1" align="center"><b>Attendees (to planning meeting)</b></td>
      <td colspan="1">Integrantes del equipo</td>
   </tr>
   <tr>
      <td colspan="1" align="center"><b>Sprint n - 4 Review Summary</b></td>
      <td colspan="1">Durante este sprint se realizaron mejoras en el frontend y en el backend de la aplicación, realizando al 100% las funcionalidades principales para los roles de cliente y técnico.</td>
   </tr>
   <tr>
      <td colspan="1" align="center"><b>Sprint n - 4 Retrospective Summary</b></td>
      <td colspan="1">Se identificó la necesidad de mejoraras en tareas ya hechas y la integración de pruebas para evitar retrabajos. También se destacó una mayor fluidez en la comunicación del equipo respecto al sprint anterior, lo que permitió avanzar con mayor claridad en los entregables.</td>
   </tr>
   <tr>
      <td colspan="2" align="center"><b>Sprint Goal & User Stories</b></td>
   </tr>
   <tr>
      <td colspan="1" align="center"><b>Sprint 4 Goal</b></td>
      <td colspan="1"><b>Our focus in on</b> developing the full web application frontend and backend , addressing both customer and worker user roles.<br><b>We believe it delivers</b>a functional and responsive interface that supports key actions such as booking services for customers and managing appointments and pricing for workers.<br><b>This will be confirmed when</b> customers can successfully explore available workers and make reservations, and workers are able to configure their services, view appointments, and interact with their dashboards smoothly.</td>
   </tr>
   <tr>
      <td colspan="1" align="center"><b>Sprint 4 Velocity</b></td>
      <td colspan="1">5</td>
   </tr>
   <tr>
      <td colspan="1" align="center"><b>Sum of Story Points</b></td>
      <td colspan="1">18</td>
   </tr>

   <tr>
</tr>
</table>


#### 5.2.4.2. Aspect Leaders and Collaborators.

Para este Sprint, se han identificado los principales aspectos del frontend web application de TuChamba.pe. Con el fin de mejorar la organización y la comunicación del equipo, se ha elaborado la matriz Leadership and Collaboration Matrix (LACX), donde se define quién asume el rol de Líder (L) y quiénes participan como Colaboradores (C) en cada uno de estos aspectos clave. Esta distribución facilita una ejecución más clara y eficiente de las tareas asignadas.

| **Team Member**                     | **GitHub Username** | **auth** | **offers** | **compare-profiles** | **public** | **shared** | **dashboard** | **profiles** | **search profiles** | **services** | **subscription** |
|-------------------------------------|---------------------|----------|------------|----------------------|------------|------------|---------------|--------------|---------------------|--------------|------------------|
| Fernandez, Roy            | rofy            | L        | C          | C                    | C          | C          | C             | C            | C                   | C            | C                |
| Mora, Diego       | dmora             | C        | C          | L                    | C          | C          | C             | L            | C                   | C            | L                |
| Oliver Jonseck    | oliverj           | C        | C          | C                    | C          | C          | L             | C            | C                   | C            | C                |
| Oroncoy Almeyda, Alejandro Daniel   | alejooroncoy        | C        | L          | C                    | C          | C          | C             | C            | C                   | C            | C                |
| Cossar Sanchez, Eduardo Jose        | coleeeee-dev        | C        | C          | C                    | L          | C          | C             | C            | L                   | C            | C                |
|


#### 5.2.4.3.Sprint Backlog 4.

En el tercer sprint backlog, el equipo tuvo la intención de completar el desarrollo del backend de la aplicación web, tanto para el rol de cliente (customer) como de trabajador/técnico (worker). Por otro lado, se inicio con el proceso de desarrollo del backend. La herramienta utilizada para organizar y gestionar las tareas del equipo continuó siendo Trello, permitiendo dividir las user stories en tareas manejables y asignarlas a los miembros según sus habilidades específicas. El objetivo principal del sprint fue implementar las funcionalidades clave de ambos roles, asegurando una interfaz intuitiva, responsiva y funcional.

<table border="1" cellspacing="0" cellpadding="5">
  <tr>
    <td colspan="2" align="center"><b>Sprint #</b></td>
    <td colspan="6" align="center"><b>Sprint 4</b></td>
  </tr>
  <tr>
    <td colspan="2"><b>User Story</b></td>
    <td colspan="6" align="center"><b>Work-Item/Task</b></td>
  </tr>
  <tr>
    <td><b>Id</b></td>
    <td><b>Title</b></td>
    <td><b>Task Id</b></td>
    <td><b>Task Title</b></td>
    <td><b>Description</b></td>
    <td><b>Estimation (Hours)</b></td>
    <td><b>Assigned To</b></td>
    <td><b>Status (To-do/In-Process/To-Review/Done)</b></td>
  </tr>

   
  </tr>
  
  <tr>
    <td rowspan="2">US03</td>
    <td rowspan="2">Recuperar contraseña</td>
    <td>T1</td>
    <td>Diseño de recuperación</td>
    <td>Diseñar la interfaz para recuperación de contraseña.</td>
    <td>4</td>
    <td>Eduardo Cossar</td>
    <td>Done</td>
  </tr>
  <tr>
    <td>T2</td>
    <td>Implementación de recuperación</td>
    <td>Desarrollar el sistema de recuperación de contraseña.</td>
    <td>5</td>
    <td>Alejandro Oroncoy</td>
    <td>Done</td>
  </tr>
 
  
  <tr>
    <td>US07</td>
    <td>Personalización de perfil técnico</td>
    <td>T1</td>
    <td>Personalización de perfil</td>
    <td>Permitir al trabajador personalizar su perfil con habilidades y experiencia.</td>
    <td>6</td>
    <td>Roy Fernandez</td>
    <td>Done</td>
  </tr>
 
  <tr>
    <td>US09</td>
    <td>Configuración</td>
    <td>T1</td>
    <td>Gestión de configuración</td>
    <td>Permitir al usuario gestionar notificaciones, idioma, etc.</td>
    <td>6</td>
    <td>Roy Fernandez</td>
    <td>Done</td>
  </tr>
  
  <tr>
    <td>US11</td>
    <td>Sistema de reseñas y calificación</td>
    <td>T1</td>
    <td>Implementación de reseñas</td>
    <td>Permitir dejar reseñas y calificaciones a los trabajadores.</td>
    <td>6</td>
    <td>Diego Mora </td>
    <td>Done</td>
  </tr>
 
  <tr>
    <td>US15</td>
    <td>Recomendación de perfil</td>
    <td>T1</td>
    <td>Sistema de recomendaciones</td>
    <td>Recomendar trabajadores a los clientes.</td>
    <td>8</td>
    <td>Oliver Jonseck</td>
    <td>Done</td>
  </tr>
  
  <tr>
    <td>US24</td>
    <td>Crear y enviar propuestas</td>
    <td>T1</td>
    <td>Envío de propuestas</td>
    <td>Permitir al trabajador enviar propuestas personalizadas a los clientes.</td>
    <td>8</td>
    <td>Roy Fernandez</td>
    <td>Done</td>
  </tr>

  <tr>
    <tr>
    <td rowspan="2">US25</td>
    <td rowspan="2">Pago seguro dentro de la app</td>
    <td>T1</td>
    <td>Diseño de interfaz de payment</td>
    <td>Diseñar la interfaz con los campos requeridos.</td>
    <td>4</td>
    <td>Pietro Osores</td>
    <td>Done</td>
  </tr>
  <tr>



  <tr>
    <td>US26</td>
    <td>Gestión de habilidades técnicas</td>
    <td>T1</td>
    <td>Actualizar habilidades</td>
    <td>Permitir al trabajador mantener actualizada su lista de habilidades.</td>
    <td>5</td>
    <td>Eduardo Cossar</td>
    <td>Done</td>
  </tr>
  <tr>
</table>

Enlace para acceder al Trello: [Trello Sprint Backlog 4](https://trello.com/invite/b/683a3962930000c3d5ef87f0/ATTI302ef236cfd65c123fb226b68a19bffeF566BB88/jobconnect-sprint-3)


#### 5.2.3.4. Development Evidence for Sprint Review.


#### 5.2.4.5 Execution Evidence for Sprint Review



### 5.3 Validation Interviews

### 5.3.1 Registro de entrevistas

## Entrevista 1:

Datos del entrevistador

Nombres: Roy

Apellidos: Fernández Remón


Datos del entrevistado:

Nombres: Jefry

Apellidos: Prado

Edad: 24

Distrito de residencia: San Juan de Lurigancho 

## Entrevista 2:

Datos del entrevistador:

Nombres: Roy

Apellidos: Fernández Remón


Datos de la entrevistada:

Nombres: Maryori

Apellidos: Atanacio

Edad: 23

Distrito de residencia: San Juan de Lurigancho


# Conclusiones

*6.1 Conclusiones y Recomendaciones*

*Conclusiones*  
El proyecto Chamba.pe reveló una necesidad real y no satisfecha en el mercado de la contratación de servicios, particularmente en el sector de la tecnología, relacionado con la gestión eficiente de perfiles de trabajadores.

La colaboración interdisciplinaria dentro del equipo de desarrollo fue esencial para abordar el proyecto de manera integral, combinando habilidades técnicas, de diseño y análisis de usuarios.

El uso de metodologías ágiles (Scrum), la documentación detallada y una arquitectura basada en dominios garantizaron que la solución fuera escalable y mantenible.

El avance en el desarrollo de Chamba.pe ha reforzado la comprensión del ciclo completo de diseño y desarrollo de plataformas digitales, desde la investigación de usuarios hasta la implementación y despliegue.

Se ha logrado un progreso significativo en la creación de una base sólida, tanto conceptual como técnica, que permitirá un desarrollo más ágil en las siguientes fases del proyecto.

*Recomendaciones*  
- Ampliar la validación de las necesidades del usuario utilizando métodos adicionales, como encuestas o pruebas de concepto, para fortalecer la base de diseño centrada en el usuario.

- Asegurar una documentación más detallada de las decisiones de diseño y arquitectura, para facilitar la comprensión del proyecto por parte de los evaluadores y compañeros de clase.

- Evaluar críticamente los avances realizados, comparándolos con los entregables definidos en el sílabo del curso, garantizando que cada parte del proyecto cumpla con los criterios de evaluación establecidos.


# Anexos

Anexo A:
URL del Prototypes Navigation / Product Navigation:
https://www.figma.com/design/WlekroBucuWBKJj4jiPD7T/OPEN-SOURCE?node-id=0-1&t=ayrC0lqPtUj7QamG-1

Anexo B:
URL de las entrevistas:
https://upcedupe-my.sharepoint.com/:f:/g/personal/u202312109_upc_edu_pe/EoNWINNJnKxLoXPb8j7mjIEBc3f7jQZg34YRkSVM9d6iSw?e=vXajg2
