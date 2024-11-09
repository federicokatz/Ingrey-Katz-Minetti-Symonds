# Ingrey-Katz-Minetti-Symonds

# GESTIÓN DE LA ITERACIÓN

## Definición del Marco de Trabajo SCRUM

- SCRUM se elige como marco de trabajo ágil debido a su capacidad para gestionar cambios frecuentes y la iteración continua de ideas, ideal para el desarrollo de un prototipo de aplicación de reservas y evaluación de restaurantes. Al enfocarse en iteraciones cortas, permite que el equipo ajuste el enfoque en cada sprint según la retroalimentación del Product Owner y los avances en el diseño.

#### Roles del Equipo y Responsabilidades

- Product Owner (PO): Responsable de definir y priorizar las historias de usuario en el Product Backlog, asegurando que cada funcionalidad esté alineada con los objetivos del proyecto y las necesidades de los usuarios.
    -  Integrante: Federico Katz

- Scrum Master (SM): Facilita el cumplimiento del marco de trabajo, asegurando que el equipo siga las prácticas acordadas y resolviendo cualquier obstáculo que pueda surgir. Promueve la mejor a continua a través de retrospectivas y seguimiento de la dinámica del equipo.
    - Integrante: Gastón Minetti

- Equipo de Desarrollo: 
Conformado por los miembros encargados de diseñar y prototipar las funcionalidades, siguiendo las historias priorizadas. Trabajan en cada iteración para completar el Sprint Backlog y asegurar que las entregas cumplan con el Definition of Done (DoD).
Integrantes:
    - Christian Ingrey
    - Emily Symonds


#### Definition of Ready (DoR)

Para que una historia de usuario esté lista para ser trabajada en el prototipo:
- **Narrativa completa y clara:** La historia de usuario debe especificar quién es el usuario, qué quiere lograr y el beneficio o propósito de la funcionalidad (por ejemplo: "Como usuario registrado, quiero recibir notificaciones de promociones para aprovechar descuentos en mis restaurantes favoritos").

- **Criterios de aceptación bien definidos:** La historia debe incluir al menos un escenario de aceptación claro que detalle las condiciones exactas en las que se considerará que la funcionalidad está cumplida.
Especificación de flujo de usuario: El flujo de interacción debe estar detallado desde el primer paso hasta el final, describiendo cómo el usuario interactúa con cada elemento y las pantallas involucradas.
- **Contenido y textos definidos:** Se deben definir todos los textos que aparecerán en la interfaz, incluyendo etiquetas, mensajes y cualquier otro texto que oriente al usuario durante la experiencia.
- **Aprobación del Product Owner:** El Product Owner debe haber revisado y aprobado la historia, asegurando que es relevante, prioritaria y clara para ser trabajada en el prototipo.


#### Definition of Done (DoD)

Para que una historia de usuario esté finalizada en el prototipo:
- **Pantallas y flujo de interacción completados:** Todas las pantallas necesarias están diseñadas en Framer, reflejando fielmente el flujo descrito en los criterios de aceptación y el flujo de usuario detallado en la historia.
- **Interactividad simulada en Framer:** Las interacciones principales están configuradas en Framer, permitiendo una experiencia de usuario que simula los pasos descritos, incluyendo navegación entre pantallas y elementos interactivos, como botones y formularios.
- **Contenido y textos implementados:** Todos los textos definidos en la historia (etiquetas, mensajes, placeholders) están implementados en el prototipo, asegurando que orientan al usuario según lo especificado.
- **Experiencia revisada y aprobada por el Product Owner:** El Product Owner ha revisado el prototipo en Framer y ha confirmado que cumple con los criterios de aceptación y que la experiencia de usuario sigue el flujo especificado.
- **Exportación del prototipo:** El prototipo ha sido exportado en formato de imagen (PNG o JPG) o PDF, y se ha cargado en el repositorio de GitHub para permitir su visualización y consulta por el equipo y las partes interesadas.
- **Documentación de decisiones de diseño en Framer:** Se han añadido comentarios en el proyecto de Framer para documentar cualquier decisión de diseño o cambio significativo en el flujo, asegurando que el equipo y el Product Owner puedan comprender fácilmente el enfoque tomado en el prototipo.

## Planificación de la iteración

El Sprint Backlog contiene las historias de usuario priorizadas y las tareas necesarias para cumplir con el objetivo de la iteración: construir y validar posibles soluciones del MVP mediante prototipos. Estas historias de usuario han sido priorizadas de acuerdo a su impacto en el producto final y alineación con los objetivos de negocio. Las tareas se planificaron basándose en la capacidad y velocidad del equipo, tomando en cuenta las horas disponibles de cada integrante y las actividades paralelas que puedan afectar su disponibilidad.

A continuacion se puede observar el product backlog con las historias de usuario priorizadas:

![Product Backlog](<Images/Product Backlog.png>)

Antes de comenzar el sprint, el equipo se reunió para revisar las historias de usuario y definir cuales serían las que se trabajarían en la iteración. También se definió que tarea se asignaría a cada integrante del equipo.

![Planning](<Images/planning.png>)

### Resumen del sprint planning
En el sprint planning se reviso el product backlog, con un foco en identificar y seleccionar las user stories que aportan mayor valor a los objetivos del MVP de la aplicación. 

Se definio el Sprint Backlog con un conjunto de user stories y tareas asociadas. De cada historia se estimaron los puntos de historia, obteniendo un total de 25 puntos, ya que en el sprint anterior se lograron completar 26 puntos a pesar de haber estimado 30 inicialmente.

### Sprint backlog
Para esta iteración, se han priorizado historias de usuario enfocadas en el flujo de autenticación, reserva y administración de restaurantes. Estas historias y tareas permitirán ofrecer una experiencia de usuario robusta y simplificar la administración para los gerentes de los restaurantes. A continuación se detalla el Sprint Backlog con las historias de usuario seleccionadas y sus tareas específicas asociadas para facilitar la implementación y cumplir con los criterios de aceptación.

- Historia de Usuario 4: Edición de perfil

Tarea: Crear una interfaz para que un usuario pueda modificar todos los datos que el usuario utilizo para
registrarse menos el email.

Realizada por Federico Katz

- Historia de Usuario 7: Configuración de notificaciones

Tarea: Crear una interfaz para que un usuario pueda configurar si desea recibir notificaciones con las recomendaciones del día, de promociones de sus retaurantes favoritos y de confirmaciones de reservas.

Realizada por Federico Katz

- Historia de Usuario 26: Indicación de restaurantes disponibles

Tarea: Crear una interfaz para que un administrador pueda activar o desactivar la disponibilidad de un restaurante.

Realizada por Federico Katz

- Historia de Usuario 15: Visualizar puntuación y comentarios de restaurantes

Tarea: Crear una interfaz para que un usuario pueda ver la puntuación y los comentarios de un restaurante.

Realizada por Federico Katz

- Historia de Usuario 11: Notificaciones de recomendaciones del día

Tarea: Crear una interfaz para que un usuario pueda recibir notificaciones con las recomendaciones del día.

Realizada por Emily Symonds

- Historia de Usuario 8: Notificaciones de promociones

Tarea: Crear una interfaz para que un usuario pueda recibir notificaciones de promociones de sus restaurantes favoritos.

Realizada por Emily Symonds

- Historia de Usuario 6: Registrar restaurantes favoritos por zona

Tarea: Crear una interfaz para que un usuario pueda registrar restaurantes favoritos por zona, pudiendo recibir notificaciones sobre promociones de estos restaurantes.

Realizada por Emily Symonds

- Historia de usuario 28: Registro de gerentes de restaurantes

Tarea: Crear una interfaz para que un administrador pueda registrar a un gerenciador.

Realizada por Gastón Minetti

- Historia de Usuario 23: Dar de alta de restaurantes

Tarea: Crear una interfaz para que un administrador pueda dar de alta un restaurante.

Realizada por Gastón Minetti

- Historia de Usuario 22: Creación de promociones

Tarea: Crear una interfaz para que un gerenciador pueda crear promociones para un restaurante.

Realizada por Gastón Minetti

- Historia de Usuario 21: Notificaciones de reservas solicitadas

Tarea: Crear una interfaz para que un gerenciador pueda recibir notificaciones de reservas solicitadas.

Realizada por Christian Ingrey

- Historia de Usuario 24: Dar de alta a gerenciadores por restaurante

Tarea: Crear una interfaz para que un administrador pueda dar de alta a gerenciadores para los restaurantes.

Realizada por Christian Ingrey

- Historia de Usuario 25: Modificación de gerenciadores por restaurante

Tarea: Crear una interfaz para que un administrador pueda modificar los gerenciadores de un restaurante.

Realizada por Christian Ingrey

### Planificación de equipo

El criterio en esta entrega, se baso en la disponibilidad de cada uno de los integrantes del grupo. Dicho esto, todas las tareas se dividieron de forma pareja, logrando que todos esten a cargo de ciertas features y que todos aportaran a la documentacion de forma acorde.

### Tecnicas de priorización y estimación

Para esta iteración, se emplearon técnicas de priorización que nos ayudaron a definir el orden de trabajo de las historias de usuario con el mayor impacto en el MVP.

Las historias de usuario se clasificaron de acuerdo con su valor para el usuario (impacto en la aplicación) y el esfuerzo estimado de desarrollo. Las historias que representaban alto valor y bajo esfuerzo recibieron la prioridad más alta, mientras que las de bajo valor y alto esfuerzo se postergaron para futuras iteraciones.

MoSCoW (Must have, Should have, Could have, Won’t have): Se utilizó esta técnica para dividir las historias de usuario en cuatro categorías:

- Must have: Historias esenciales para el MVP, que se seleccionaron como primera prioridad en el Sprint Backlog (Alta de gerenciadores, alta de restaurantes, visualización de puntuaciones y comentarios).
- Should have: Historias importantes, pero que podrían dejarse fuera si el tiempo no alcanzaba (Configuración de notificaciones, creación de promocionesm, alta y modificación de gerentes por restaurante).
- Could have: Historias deseables, pero no imprescindibles, que se tomarán en cuenta en iteraciones posteriores (Notificaciones de usuarios y gerenciadores).
- Won’t have (this time): Funcionalidades que no fueron consideradas para esta iteración, pero podrían implementarse en el futuro (Administración y apelación de puntuaciones y comentarios).

Esta combinación de técnicas nos permitió priorizar eficientemente las historias más relevantes, centrándonos en los elementos críticos para avanzar en el desarrollo del MVP.

Por otro lado, los puntos de historia se usaron para asignar un valor relativo de esfuerzo a cada tarea, sin relacionarlos directamente con horas específicas. Esto nos permitió establecer comparaciones y balancear la carga de trabajo en función de la capacidad del equipo. Las tareas más complejas recibieron una puntuación más alta, indicando su mayor complejidad y tiempo de desarrollo.

### Metricas relevantes
1. Velocidad del Equipo
    
    Se decidió estimar 25 puntos en esta iteración de dos semanas. Esto nos permitio ajustar el Sprint Backlog, asegurando que las tareas se alinearan con la capacidad real del equipo sin sobrecargarlo. Pudimos realizar todas las historias de usuario incluidas en el backlog de la iteración, por lo que la estimación fue acertada.

2. Productividad del Equipo

    La productividad se midió comparando tareas completadas vs. planeadas, permitiendo ajustes semanales en el backlog. Si algún retraso afectaba la productividad, se revaluaban las prioridades para mantener el enfoque en los objetivos principales del sprint.

3. Resultados y Lecciones Aprendidas

    Estas métricas permitieron planificar de forma más precisa y ajustar el trabajo en tiempo real, asegurando un avance constante en el MVP.

## Seguimiento de la iteración

### Reporte de horas

Gastón Minetti:

![Gastón Minetti](<Images/clockify-gaston.jpg>)

Emily Symonds:

![Clockify Emily Symonds](<Images/clockify-emily.jpg>)

Federico Katz:

![Clockify Federico Katz](<Images/clockify-federico.png>)

Christian Ingrey:

![Clockify Christian Ingrey](<Images/clockify-christian.jpg>)

## Inspección y adaptación del proceso

Cada dia, en caso de haber realizado alguna tarea, se enviaba un mensaje al grupo para informar el avance. De esta forma, se podia tener un seguimiento de las tareas realizadas y de las que faltaban por hacer.

A continuación, se presentan algunas imágenes de los avances realizados en la iteración:

![Avance 1](<Images/avance1.png>)

![Avance 2](<Images/avance2.png>)

![Avance 3](<Images/avance3.png>)

Una vez finalizada la iteración, el tablero kanban se actualizó con las tareas completadas y pendientes, permitiendo una visualización clara del progreso y los objetivos alcanzados.

![Kanban](<Images/kanban1.png>)

![Kanban 2](<Images/kanban2.png>)

# Construcción y validación de posibles soluciones del MVP a través de prototipos

## Posibles soluciones de MVP con prototipos
En esta iteración, se decidio realizar los prototipos de la aplicación utilizando Framer. Esta plataforma nos permite colaborar en tiempo real sobre el mismo proyecto, lo que facilita la elaboración de bocetos para los requisitos definidos en la iteración anterior y acelera y estimula el proceso de diseño.

Nos enfocamos en hacer las funcionalidades de mayor prioridad, abarcando las dirigidas a los administradores, gerenciadores y usuarios finales.

A continuación se muestran las imagenes de los prototipos principales realizados en esta iteración:

![Editar perfil](<Images/editarPerfil.png>)
![Editar perfil](<Images/configNotificaciones.png>)
![Editar perfil](<Images/comentarios.png>)
![Editar perfil](<Images/notificaciones.png>)
![Editar perfil](<Images/favoritos.png>)
![Editar perfil](<Images/crearGerente.png>)
![Editar perfil](<Images/crearRestaurante.png>)
![Editar perfil](<Images/promocion.png>)
![Editar perfil](<Images/reservaSolicitada.png>)
![Editar perfil](<Images/administrarRestaurantes.png>)

## Inspección y adaptación del producto

Les mostramos nuestros prototipos a amigos y familiares, pidiendoles que realicen una puntuación entre 1 y 10, siendo 1 la peor puntuación y 10 la mejor.
La encuesta fue realizada a 13 personas, donde las puntuaciones obtenidas fueron las siguientes:

1. 8.5
2. 7
3. 9
4. 8
5. 8
6. 8.5
7. 7.5
8. 8
9. 9
10. 9.5
11. 7
12. 8
13. 8.5

El promedio de dichas calificaciones fue de 8.19, lo que nos indica que aunque los prototipos serían bien recibidos por los usuario finales, aún hay algunos detalles que podrían mejorarse.