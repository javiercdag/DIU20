# DIU20
Prácticas Diseño Interfaces de Usuario 2019-20 (Economía Colaborativa) 

Grupo: DIU2_Mumavi.  Curso: 2019/20 

Proyecto: Aplicación de buscar piso definitiva

Descripción: En este trabajo se va a buscar diseñar una aplicación de búsqueda de pisos para compartir mejorando las que existen hoy en día

Logotipo: 

Miembros
 * :bust_in_silhouette:  Francisco Javier Casado de Amezúa García     
 * :bust_in_silhouette:  Miguel Muñoz Molina

----- 

En esta práctica estudiaremos un caso de plataforma de economía colaborativa y realizaremos una propuesta para su diseño Web/movil. Utilizaremos herramientas y entregables descritos en el siguiente CheckList (https://github.com/mgea/UX-DIU-Checklist) 


Qué es economia colaborativa: Martínez-Polo, J. (2019). **El fenómeno del consumo colaborativo: del intercambio de bienes y servicios a la economía de las plataformas**, *Sphera Publica, 1*(19), 24-46. http://sphera.ucam.edu/index.php/sphera-01/article/view/363/14141434

>>> Este documento es el esqueleto del report final de la práctica. Aparte de subir cada entrega a PRADO, se debe actualizar y dar formato de informe final a este documento online. 


# Proceso de Diseño 

## Paso 1. UX Desk Research & Analisis 

![Método UX](img/Competitive.png) 1.a Competitive Analysis
-----

>>> Describe brevemente características de las aplicaciones que tienes asignadas, y por qué has elegido una de ellas (150-300 caracteres)

Tras analizar aplicaciones como Coachsurfing Travel, Splitwise, PisoCompartido o Badi decidimos optar por la última debido a que, a nuestro parecer, era la que ofrecía el servicio de mayor calidad.

![Método UX](img/Persona.png) 1.b Persona
-----

>>> Comenta brevemente porqué has seleccionado a esas personas y sube una captura de pantalla de su ficha  (80-150 caracteres)

- **Erika:** en el registro se debía elegir entre género chico/chica, lo que puede ocasionar problemas de convivencia para personas como Erika. Además, solucionar el problema que esta Persona encuentra es sencillo, barato y tiene un gran impacto.

- **Evaristo:** es común entre personas mayores buscar compañía con la que vivir; además, habitualmente, las personas de edad avanzada tienen problemas al usar aplicaciones con interfaces de usuario mejorables. 

![Método UX](img/JourneyMap.png) 1.c User Journey Map
----


>>> Comenta brevemente porqué has escogido estas dos experiencias de usuario (y si consideras que son habituales) (80-150 caracteres) 

- **Erika:** nuestra inspiración para crear a Erika fue imaginar la situación que podría ocurrir cuando alguien con este perfil utiliza la aplicación, y eso es lo representado en el journey map. A más personas no se identifiquen con los dos géneros clásicos, más habitual se volvería.


- **Evaristo:** para crear el journey map de Evaristo nos fijamos en que el tutorial disponible en la página es muy pobre, algo que puede provocar que usuarios poco experimentados como él pierdan tiempo y ganas de utilizarla. Es una situación muy común hoy en día.


![Método UX](img/usabilityReview.png) 1.d Usability Review
----
>>>  Revisión de usabilidad: (toma los siguientes documentos de referncia y verifica puntos de verificación de  usabilidad

- Enlace al documento: ![Haga click aquí para ver el documento](P1/UsabilityReview/UsabilityReview-Badi-Mumavi.pdf)
- Valoración final (numérica): 85
- Comentario sobre la valoración:  En general, nuestra valoración de Badi ha sido positiva. Destaca su fácil uso y minimalista interfaz, aunque ésta es a la vez su mayor defecto.


## Paso 2. UX Design  


![Método UX](img/feedback-capture-grid.png) 2.a Feedback Capture Grid
----

Con FHome queremos implementar nuevas ideas basadas en el estudio que se ha realizado en este documento que incluyen búsqueda inteligente de pisos, uso de heurísticas para mejorar la experiencia de usuario y mejoras generales en la calidad de la experiencia de cada cliente.

El Feedback Capture Grid utilizado para encontrar problemas, sugerencias y nuevas ideas se encuentra disponible ![AQUÍ](P2/FeedbackCaptureGrid)


![Método UX](img/Sitemap.png) 2.b Tasks & Sitemap 
-----
- TASKS:
Las tareas encontradas pueden verse ![AQUÍ](P2/Tasks/)
Se han implementado todas las tareas en los Wireframes de la sección 2.d de este documento.

- SITEMAP:
El sitemap puede verse ![AQUÍ](P2/Sitemap/)

**Leyenda**
Las flechas direccionales implican navegación entre los elementos conectados en la dirección que marca la punta.
Las flechas discontinuas implican compartición automática de información: por ejemplo, la información del perfil del anunciante de un piso está disponible al visitar el piso que ha visitado


**![Método UX](img/labelling.png) 2.c Labelling**

Término | Significado     
| ------------- | -------
Página Principal  | pagina principal de la aplicación: enlaza principalmente a buscar piso y publicar piso, aunque muestra también recomendaciones.
Perfil de usuario | perfil de cada usuario; en caso de acceder al propio sin haber iniciado sesión, da la opción de hacerlo; si se ha iniciado sesión da la opción de editar perfil y la opción de configurar el método de pago
Editar perfil de usuario | página que contiene tanto la personalización del perfil personal como la opción de permitir el envío de sugerencias por email y notificaciones a través de la aplicación
Publicar Piso | formulario formado por cuatro etapas a rellenar para publicar un nuevo piso, que se puede localizar por dirección absoluta o utilizando un mapa. Es necesario iniciar sesión para utilizar esta funcionalidad, por lo que se ofrece opción de login si no lo estuviera.
Buscar Piso | página para buscar piso, que se puede realizar utilizando un mapa o introducciendo una dirección. Cualquier alternativa actualiza la otra.
Búsqueda avanzada | al buscar piso se puede optar por esta búsqueda avanzada mediante la aplicación de filtros
Información de piso | detalles de un piso concreto, que incluye información avanzada para facilitar la convivencia, ubicación del piso mostrada como dirección absoluta y en un mapa con información adicional de los establecimientos cercanos así como un resumen del perfil del anunciante
Pago online | pantalla de pagos que se rellena con la información que se haya rellenado en la sección de pagos del perfil propio. Si no se ha rellenado o no se ha iniciado sesión, se ofrece la opción que corresponda.
Ayuda | sección de ayuda, a la que se puede acceder como pop-up desde cualquier otra sección de la app y contiene dos opciones: visualizar videotutoriales breves o contactar con el soporte técnico a través de un chat online que estima el tiempo de espera hasta recibir respuesta en base a una heurística
Sobre nosotros | pagina de información sobre la empresa, con enlace a la página de contacto así como información legal
Contacto | sección con información de contacto con los diferentes equipos de atención a entidades externas de la empresa
Login | pantalla de inicio de sesión: se puede cerrar para continuar la navegación como invitado a menos que se quiera publicar un piso, acceder a una cuenta existente indicando nombre de usuario/email y contraseña o acceder al registro si se desea hacer una nueva
Registro | formulario para crear una cuenta nueva en la aplicación. Muchos campos son opcionales para poder completarse en la personalización del perfil.
Contactar anunciante | formulario para contactar al anunciante de un piso publicado. Es necesario introducir un email, pero si se ha iniciado sesión esta información es autorrellenada

![Método UX](img/Wireframes.png) 2.d Wireframes
-----

>>> Plantear el  diseño del layout para Web/movil (organización y simulación ) 


## Paso 3. Make (Prototyping) 


![Método UX](img/moodboard.png) 3.a Moodboard
-----


>>> Plantear Diseño visual con una guía de estilos visual (moodboard) 

![Método UX](img/landing-page.png)  3.b Landing Page
----


>>> Plantear Landing Page 

![Método UX](img/guidelines.png) 3.c Guidelines
----

>>> Estudio de Guidelines y Patrones IU a usar 

![Método UX](img/mockup.png)  3.d Mockup
----

>>> Layout: Mockup / prototipo HTML  (que permita simular tareas con estilo de IU seleccionado)


## Paso 4. UX Check (Usability Testing) 


![Método UX](img/ABtesting.png) 4.a A/B Testing
----


>>> Comprobacion de asignaciones para A/B Testing. Asignaciones https://github.com/mgea/DIU19/blob/master/ABtesting.md

>>>> Práctica A: 


![Método UX](img/usability-testing.png) 4.b User Testing
----

>>> Usuarios para evaluar prácticas 


| Usuarios | Sexo/Edad     | Ocupación   |  Exp.TIC    | Personalidad | Plataforma | TestA/B
| ------------- | -------- | ----------- | ----------- | -----------  | ---------- | ----
| User1's name  | H / 18   | Estudiante  | Media       | Introvertido | Web.       | A 
| User2's name  | H / 18   | Estudiante  | Media       | Timido       | Web        | A 
| User3's name  | M / 35   | Abogado     | Baja        | Emocional    | móvil      | B 
| User4's name  | H / 18   | Estudiante  | Media       | Racional     | Web        | B 


![Método UX](img/Survey.png). 4.c Cuestionario SUS
----

>>> Usaremos el **Cuestionario SUS** para valorar la satisfacción de cada usuario con el diseño (A/B) realizado. Para ello usamos la [hoja de cálculo](https://github.com/mgea/DIU19/blob/master/Cuestionario%20SUS%20DIU.xlsx) para calcular resultados sigiendo las pautas para usar la escala SUS e interpretar los resultados
http://usabilitygeek.com/how-to-use-the-system-usability-scale-sus-to-evaluate-the-usability-of-your-website/)
Para más información, consultar aquí sobre la [metodología SUS](https://cui.unige.ch/isi/icle-wiki/_media/ipm:test-suschapt.pdf)

>>> Adjuntar captura de imagen con los resultados + Valoración personal 


![Método UX](img/usability-report.png) 4.c Usability Report
----

>> Añadir report de usabilidad para práctica B 



## Paso 5. Evaluación de Accesibilidad  


![Método UX](img/Accesibility.png)  5.a Accesibility evaluation Report
----

>>> Indica qué pretendes evaluar (de accesibilidad) y qué resultados has obtenido + Valoración personal

>>> Evaluación de la Accesibilidad (con simuladores o verificación de WACG) 



## Conclusión / Valoración de las prácticas


>>> (90-150 caracteres) Opinión del proceso de desarrollo de diseño siguiendo metodología UX y valoración (positiva /negativa) de los resultados obtenidos  







