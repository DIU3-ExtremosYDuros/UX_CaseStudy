# DIU25
Prácticas Diseño Interfaces de Usuario (Tema: El ocio y comercio sostenible ) 

[Guiones de prácticas](GuionesPracticas/)

Grupo: DIU3_ExtremosYDuros.  Curso: 2024/25 

Actualizado: 17/05/2025

Proyecto: 

**ReMade**

Descripción: 

>>> Describa la idea de su producto en la práctica 2 

Logotipo: 

![Logo ReMade](img/logo.png) 

**Damos nueva vida a lo que importa**

Miembros:
 * :bust_in_silhouette:  Juan Pedro Moreno Ruiz  :octocat:  [https://github.com/Karylus](https://github.com/Karylus)
 * :bust_in_silhouette:  Salvador Molina Plaza   :octocat: [https://github.com/salvadormolinaa](https://github.com/salvadormolinaa)

----- 

# Proceso de Diseño 

<br>

## Paso 1. UX User & Desk Research & Analisis 

### 1.a User Reseach Plan
![Método UX](img/Competitive.png) 
-----

El User Research se va a centrar en el contexto del Reciclaje y la Artenasía en Granada, teniendo como objetivo en este plan el de evaluar la experiencia de la compra y la navegación en la web de Re-Made in Granada, para detectar las posibles mejoras en accesibilidad y navegación del usuario en la web. Para identificar las distintas áreas de mejora, nos vamos a basar en la experiencia que tenemos usando otras páginas web de distintas tiendas de ropa mucho más grandes, aunque no sean artesanas, como pueden ser Zara, H&M o Springfield. 

Existen varios perfiles que hemos identificado como principales usuarios del sistema, aunque caben destacar dos. El primero de ellos es de una persona joven que está interesada por el medio ambiente y busca comprar ropa artesanal. El segundo es una persona mayor que valora la calidad y la exclusividad de las prendas, buscando ropa única y bien confeccionada, este perfil suele tener un poder adquisitivo medio-alto y prefiere invertir en piezas que duren en el tiempo en lugar de seguir las tendencias de la moda rápida.

Ambos perfiles nos ayudarán a evaluar distintos aspectos de la navegación y la experiencia de compra en la web de Re-Made in Granada, permitiéndonos detectar posibles barreras y oportunidades de mejora para hacer que el sitio sea más accesible y atractivo para todos los usuarios.

### 1.b Competitive Analysis
![Método UX](img/Competitive.png) 
-----

Las aplicaciones que están asignadas a nuestro grupo, tratan sobre Reciclaje y artesanía: una web de ropa ecológica, otra web de cosas de barro y la tercera de ropa de segunda mano. En general todas las webs tienen bastantes fallos de diseño, pero nos hemos decidido por la de Casa Kuna porque a simple vista es la que más carencias tiene y mayores puntos de mejora.

![Competitor Analysis](img/Competitor%20Analysis.png)

### 1.c Personas
![Método UX](img/Persona.png) 
-----

Se han creado dos personas distintas. 

Amanda es una chica que acaba de llegar a Granada como estudiante de Erasmus, es argentina y estudia Bellas Artes. Le gusta conocer gente nueva, la música, leer y dibujar. Necesita comprar ropa nueva y quiere algo especial.

![Persona 1](img/Persona1.png)

<br>

Emilio es una persona mayor del barrio del Albahicín en Granada, está jubilado desde hace 15 años. Dedica su tiempo libre a hacer alfarería y le encanta pasear por Granada buscando tiendas de ropa pequeñas y que considera especiales.

![Persona 2](img/Persona2.png)

### 1.d User Journey Map
![Método UX](img/JourneyMap.png) 
----

En cuanto al User Journey Map, se han creado dos hipotéticas situaciones que se ajustan lo máximo posible a una experiencia real de compra. En la primera situación, tenemos a Amanda, la cual no ha podido traerse toda su ropa de Argentina y recuerda que en clase una profesora habló sobre esta marca, pero no recuerda el nombre. 

![Journey Map 1](img/UserJourney1.png)

En la segunda situación, Emilio ha roto una de sus chaquetas y necesita comprar una nueva, decide salir a pasear por Granada y se encuentra con la tienda de Re-Made donde ve una chaqueta que le gusta, pero está cerrada e intenta comprarla por internet.

![Journey Map 1](img/UserJourney2.png)

### 1.e Usability Review
![Método UX](img/usabilityReview.png) 
----

- Enlace al documento:  ![Usability Review](https://github.com/DIU3-ExtremosYDuros/UX_CaseStudy/blob/master/P1/Usability-review.pdf) 
- Valoración numérica obtenida: 59
- Comentario sobre la revisión:  La página, a nivel general, es pobre, tanto en diseño orientado al usuario, como en falta de acciones a realizar, falta de un catálogo, enlaces que llevan a páginas que no existen etc. Tiene alguna cosa aceptable, incluso buena, como la claridad en el menú, y la cabecera, que siempre está presente, pero en líneas generales, se pueden mejorar bastantes cosas.

<br>

## Paso 2. UX Design  

### 2.a Reframing / IDEACION: Feedback Capture Grid
![Método UX](img/feedback-capture-grid.png) 
----

![Feedback Capture Grid](P2/feedbackcapturegrid.png)
  
Re Made es mucho más que una marca de ropa. Nuestro objetivo fundamental es la venta de ropa artesanal y con materiales reciclados, pero nuestra misión es algo mucho más grande. Queremos formar una comunidad de personas unidas entre sí, también queremos organizar talleres multitudinarios cada semana, así como crear una comunidad artística en la que tenga cabida todo tipo de persona. Los usuarios van a poder registrarse en la web, lo que les permitirá no solo comprar por la tienda, si no apuntarse a talleres, comunicarse mediante un foro con otros usuarios… Todos los talleres serán registrados y se podrán valorar, así como publicar fotos relacionadas con este. A los usuarios se les recomendarán talleres en función de los que ha participado anteriormente y sus valoraciones, de igual forma ocurre con la ropa, recomendando aquellas prendas y accesorios que creemos que pueden interesar a cada usuario.

### 2.b ScopeCanvas
![Método UX](img/ScopeCanvas.png)
----

![ScopeCanvas](P2/ScopeCanvas.svg)


### 2.b User Flow (task) analysis 
![Método UX](img/Sitemap.png) 
-----

En esta tabla se identifican las tareas y su relevancia para los usuarios. Distinguimos entre tres grupos de usuario:

- **Usuarios Registrados**: Usuario con una cuenta en la tienda. Puede comprar productos, inscribirse en talleres, participar en el foro e interactuar con otros usuarios.  
- **Usuarios No Registrados**: Usuario que visita la tienda y puede ver los productos, talleres y el foro, pero sin participar.  
- **Moderador**: Personal de la tienda que publica productos, administra talleres y supervisa la actividad en el foro.  

Tarea | Usuarios Registrados | Usuarios No Registrados | Moderador
|------------------------|---------------------|---------------------|------------|
Buscar productos/talleres | ALTA | ALTA | MEDIA |
Comprar productos | ALTA | NO PUEDE | NO PUEDE |
Inscribirse en talleres | ALTA | NO PUEDE | NO PUEDE |
Dejar reseñas en productos/talleres | MEDIA | NO PUEDE | MEDIA |
Publicar comentarios en talleres | MEDIA | NO PUEDE | MEDIA |
Eliminar comentarios propios | BAJA | NO PUEDE | MEDIA |
Registrarse | NO PUEDE | MEDIA | NO PUEDE |
Iniciar sesión | ALTA | NO PUEDE | ALTA |
Cerrar sesión | MEDIA | NO PUEDE | BAJA |
Gestionar pedidos | ALTA | NO PUEDE | ALTA |
Añadir productos a la tienda | NO PUEDE | NO PUEDE | ALTA |
Gestionar talleres | NO PUEDE | NO PUEDE | ALTA |
Ver publicaciones | ALTA | ALTA | ALTA |
Crear publicaciones | ALTA | NO PUEDE | MEDIA |
Comentar publicaciones | MEDIA | NO PUEDE | MEDIA |
Eliminar propias publicaciones | BAJA | NO PUEDE | MEDIA |
Moderar contenido | NO PUEDE | NO PUEDE | ALTA |

Con respecto a los distintos User Flow que se pueden llevar a cabo en nuestra tienda, vamos a mostrar los 3 que consideramos mas importantes; registrarse en la web, publicar un post en el foro y apuntarse a un taller. Con estos tres user flows pensamos que se abarca el totalidad de las acciones que un usuario podría llevar a cabo en nuestra web.

![User Flow 1](P2/userflow1.png)

![User Flow 2](P2/userflow2.png)

![User Flow 3](P2/userflow3.png)


### 2.c IA: Sitemap + Labelling 
![Método UX](img/labelling.png) 
----

![Sitemap](P2/sitemap.png)

Término | Significado     
| ------------- | -------
Inicio | Página principal de la plataforma  
Log in / Registro | Acceder o registrarse en la plataforma  
Tienda | Sección para comprar productos  
Producto | Página de un producto específico  
Talleres | Sección de inscripción a talleres  
Mis Talleres | Talleres en los que está inscrito el usuario  
Perfil de Usuario | Información y configuración del usuario  
Mis Post | Publicaciones del usuario en el foro  
Sobre Nosotros | Información sobre Casa Kuna  
Contacto | Formulario para contactar con Casa Kuna  
Foro | Espacio de discusión entre usuarios  
Post | Página de un tema específico en el foro  


### 2.d Wireframes
![Método UX](img/Wireframes.png) 
-----

Para hacer los Wireframes hemos usado la herramienta de Figma, donde cada frame creado se corresponde a una página distinta de la web. Hemos creado los diseños para las páginas de Inicio, Iniciar Sesión, Registro, Perfil de Usuario, Foro, Post, Talleres, Página de Taller, muestras del chat y el diseño del foro responsive, tanto como para un iPad como para un iPhone.

[Wireframes](P2/Wireframes.pdf) 

<br>

## Paso 3. Mi UX-Case Study (diseño)

### 3.a Moodboard
![Método UX](img/moodboard.png)
-----

![Mooboard](img/Moodboard.png)


### 3.b Landing Page
![Método UX](img/landing-page.png) 
----

![Landing Page](P3/LandingPage.png)


### 3.c Guidelines
![Método UX](img/guidelines.png) 
----

Para documentarnos hemos visitado varias páginas, pero principalmente nos hemos informado en [UI Patterns](https://ui-patterns.com/) y [Meterial Design 3](https://m3.material.io/). Los componentes que hemos usados han sido:

* **Onboarding**: Página principal, se puede acceder a las distintas secciones de la web (Talleres, Foro y Tienda) desde el mismo lugar.
* **Card List**: Se usando Cards para que los usuarios puedan encontran su taller, su post o su artículo para comprar.
* **Item details**: Cada una de las Cards tienen información sobre el elemento que se muestra; horario, valoración, precio, etc.
* **Navigation Bar**: En la parte inferior se usa para que los usuarios puedan acceder al onboarding, sus mensajes y su perfil de usuario.
* **Dialogs**: Se usan para mostrar la confirmación de inscripción en un taller.
* **Chips**: Los filtros y elección de categorías están basadas en este patrón, como los tipos de talleres.


### 3.d Mockup
![Método UX](img/mockup.png) 
----

El Mockup diseñado se puede consultar desde el siguiente archivo PDF: [Mockup PDF](P3/Mockup.pdf)

Para ver el prototipo, se puede usar este enlace a Figma: [Mockup Figma](https://www.figma.com/design/HIXIjNIw3gh6lrK8S6T9ll/Mockup?node-id=0-1&t=ZLdFL9OxKd2MB2oP-1)

### 3.e ¿My UX-Case Study?
![Método UX](img/caseStudy.png) 
-----

Todo el desarrollo del UX-Case Study se ha documentado paso a paso y explicado de la mejor manera posible, para dejar clara nuestra propuesta y que todo el mundo la pueda entender, incluso si quien la lee no está familiarizado con esta práctica. El enlace es el siguiente: [Enlace](https://github.com/DIU3-ExtremosYDuros/UX_CaseStudy/blob/master/README.md)

<br>

## Paso 4. Pruebas de Evaluación 

### 4.a Reclutamiento de usuarios 
![Método UX](img/usability-testing.png)
-----

>>> Breve descripción del caso asignado (llamado Caso-B) con enlace al repositorio Github
>>> Tabla y asignación de personas ficticias (o reales) a las pruebas. Exprese las ideas de posibles situaciones conflictivas de esa persona en las propuestas evaluadas. Mínimo 4 usuarios: asigne 2 al Caso A y 2 al caso B.


| #id. usuario | Sexo/edad | Ocupación   | Experiencia internet   | Plataforma     | Perfil cubierto                                                                  | TEST |
|--------------|-----------|-------------|------------------------|----------------|----------------------------------------------------------------------------------|------|
| Salvador     | M / 53    | Oficinista  | Intermedio             | Windows, iOS   | Oficinista con cierta experiencia con la tecnología.                             | A    |
| Manuela      | F / 51    | Emprendedora| Bajo                   | iOS            | Emprendedora, dueña de una guardería desde hace más de 25 años. Es un poco negada con la tecnología, nunca le ha gustado mucho. | B    |
| Pablo        | M / 19    | Estudiante  | Avanzado               | iOS, Windows   | Estudiante de psicología al que le gusta mucho el uso de la tecnología para todas sus actividades diarias | B    |
| Álvaro       | M / 22    | Estudiante  | Avanzado               | iOS, Windows   | Estudiante de historia con poco intereses por la tecnología, más alla de un uso diario de su teléfono | A    |



### 4.b Diseño de las pruebas 
![Método UX](img/usability-testing.png) 
-----

Para evaluar la eficacia y usabilidad de las dos páginas web, se desarrollarán tres tipos de pruebas distintas: A/B testing con tareas orientadas a objetivos, un cuestionario SUS y una prueba de eyetracking.

La primera prueba consiste en un A/B testing centrado en el cumplimiento de objetivos. Se diseñarán dos pruebas diferentes para los dos casos asignados, y se pedirá a los usuarios que realicen tareas concretas, como buscar un producto o completar un formulario. Cada grupo de usuarios interactuará con una de las versiones y se medirá si logran completar los objetivos. Esto permitirá determinar si las webs facilitan la consecución de los objetivos propuestos.

La segunda prueba será un cuestionario SUS (System Usability Scale), que evalúa la usabilidad percibida por los usuarios. Tras usar la web asignada, los participantes completarán un cuestionario de 10 afirmaciones con una escala del 1 al 5. A partir de las respuestas se calculará una puntuación total sobre 100, donde un valor por encima de 70 indica una buena usabilidad. Esta prueba proporciona una visión subjetiva pero estandarizada de la experiencia de uso.

La tercera prueba será un eyetracking, que permite analizar hacia dónde miran los usuarios mientras navegan por la web. Se registrarán los movimientos oculares para identificar las zonas más vistas, los elementos que captan más atención y si hay distracciones o confusión visual. Esto es útil para optimizar el diseño, mejorar la jerarquía visual y garantizar que los elementos importantes sean fácilmente detectables.


### 4.c Cuestionario SUS
![Método UX](img/Survey.png) 
----

Los resultados de este cuestionario para los cuatro usuarios se encuentra en: [Excel SUS](P4/CuestionarioSUS.xlsx)

En la web del caso A se obtiene una valoración media aceptable, con buen desempeño en facilidad de uso y manejo. Sin embargo, la experiencia de Manuela sugiere que puede no ser igual de intuitiva para todos los perfiles, por lo que sería recomendable simplificar y unificar el diseño para mejorar la consistencia y reducir la sensación de complejidad.

En la web del caso B se presenta una mejor aceptación general. Es más equilibrada entre los dos usuarios y refleja una experiencia más positiva en términos de integración, manejo y aprendizaje. Aun así, podría ser útil revisar aspectos visuales o de navegación inicial para aumentar el interés de los usuarios en volver y reducir aún más la percepción de complejidad.

### 4.d A/B Testing
![Método UX](img/ABtesting.png) 
-----

El reporte con los resultados se puede ver en Maze a través de este link: [Maze]([P4/CuestionarioSUS.xlsx](https://app.maze.co/report/New-maze-1/37hia7mb6uiyy0/intro))

### 4.e Aplicación del método Eye Tracking 
![Método UX](img/eye-tracking.png)
----

El experimento se diseñó para comparar la usabilidad de las dos landing pages de los casos A y B. Se les analizó mediante eyetracking utilizando la herramienta [Realeye](https://www.realeye.io/es), que permite registrar los movimientos oculares con una cámara web. Esto permitió evaluar el comportamiento visual de los usuarios, ayudando a identificar los elemtos que más llaman la atención de ambas webs.

![experimento](P4/EyetrackingB2.png)  

Todas las imágenes de las pruebas se encuentran en la carpeta P4.

### 4.f Usability Report de B
![Método UX](img/usability-report.png) 
-----

El Usability Report para el caso B se encuentra en el archivo: [Usability Report](P4/P4_UsabReport_Mamallema_doneby_DIU3_ExtremosYDuros.md)

<br>

## Paso 5. Exportación y Documentación 


### 5.a Exportación a HTML/React
![Método UX](img/usabilityReview.png) 
----

>>> Breve descripción de esta tarea. Las evidencias de este paso quedan subidas a P5/


### 5.b Documentación con Storybook
![Método UX](img/usabilityReview.png)
----

>>> Breve descripción de esta tarea. Las evidencias de este paso quedan subidas a P5/


<br>

## Conclusiones finales & Valoración de las prácticas


>>> Opinión FINAL del proceso de desarrollo de diseño siguiendo metodología UX y valoración (positiva /negativa) de los resultados obtenidos. ¿Qué se puede mejorar? Recuerda que este tipo de texto se debe eliminar del template que se os proporciona 




