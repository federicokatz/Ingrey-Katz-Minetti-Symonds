# Ingrey-Katz-Minetti-Symonds

# Gestión de la iteración
## Definición del Marco de Trabajo

SCRUM se utilizó como marco de trabajo ágil debido a su enfoque iterativo y su capacidad para gestionar la inspección y adaptación constantes, lo cual resultó esencial durante el desarrollo del prototipo de la aplicación de reservas y evaluación de restaurantes. En esta iteración final, el marco SCRUM permitió consolidar los aprendizajes de las iteraciones previas, realizar ajustes finales al prototipo y documentar los resultados obtenidos.

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

#### Justificación de las Adaptaciones Principales del Marco de Trabajo

En esta iteración, se adaptaron algunos eventos y prácticas del marco SCRUM para ajustarse al objetivo principal de cerrar el proyecto:
- Se redujo la frecuencia de las Daily Scrums para poder dedicarle más tiempo a los entregables clave.
- Se priorizo la finalización del informe académico y el video de demostración.
- Se dio lugar a la retroalimentación del Product Owner sobre eventos como la validación con usuarios externos.
- La retrospectiva se utilizó para analizar de forma más profunda las lecciones aprendidas a lo largo de todo el proyecto, con énfasis en cómo estas podrían aplicarse en futuros proyectos o experiencias.

#### Definición del Calendario de Eventos 

- Daily Scrum: Se realizó una única daily, dado al hecho de que quedan solamente dos requerimientos, por lo que el equipo no considero necesario hacer más. Aquí se priorizaron la resolución de impedimentos y de tareas críticas.
- Sprint Planning: Se definieron claramente las tareas necesarias para completar el informe académico y el video, dando una priorización acorde.
- Sprint Review: Se realizó al finalizar la iteración para validar el informe académico y la demo con el product owner.
- Retrospectiva: Se discutieron los aprendizajes clave y las mejoras aplicables en futuros proyectos y experiencias.

## Planificación de la iteración

### Minuta de la Sprint Planning

**Agenda:**
- Revisión de los objetivos de la iteración.
- Priorización de historias de usuario pendientes.
- Estimación de tareas para las historias seleccionadas.
- Distribución de responsabilidades según capacidad del equipo.
- Planificación del seguimiento y criterios de éxito.

**Actividades Realizadas:**
- Revisión de las tareas pendientes en el backlog y las nuevas historias priorizadas.
- Estimación de las tareas utilizando la técnica de Planning Poker.
- Creación del cronograma de trabajo basado en la dificultad de la tarea y disponibilidad de cada integrante.

**Resultados:**
- Sprint Backlog definido con las historias de usuario seleccionadas.
- Asignación clara de tareas para cada miembro del equipo.
- Establecimiento de métricas de seguimiento, como la velocidad proyectada del equipo.


### Objetivos de la Iteración
- Implementar las funcionalidades relacionadas con la gestion de valoraciones y comentarios.
    - Permitir la apelación de las puntuaciones por parte de los gerenciadores.
    -Posibilidad de borrar dichas valoraciones que se consideren inapropiadas por parte de los administradores.
- Refinar y consolidar la experiencia de usuario de estas funcionalidades.


### Sprint Backlog
Para esta iteración se realizaron las historias de usuario relacionadas a las valoraciones y comentarios. Dichas historias habilitan a los gerenciadores de restaurantes apelar a una puntuación o comentario inapropiado. De esta forma el negocio no se vea afectado injustamente. Por lo tanto se provee una solucion mas robusta para los usuarios de tipo gerenciador. 

- Historia de Usuario: Apelación de puntuación o comentario
Tarea: Diseñar una pantalla para apelación de valoraciones y comentarios que permita seleccionar una puntuación y dar una razon del rechazo.

- Historia de Usuario: Administración de puntuación y comentarios
Tarea: Crear un flujo de eliminación de valoraciones y comentarios, para que sea posible por un administrador de la plataforma eliminar aquellas puntuaciones que sean inapropiadas.

### Planificación de acuerdo a la capacidad del equipo.
El criterio de planificación del equipo para esta entrega se baso en la disponibilidad de los integrantes y de la complejidad de las tareas a realizar. Dicho esto, las tareas se dividieron de forma equitativa, logrando que todos los integrantes del grupo aprotaran a la solución general.


### Técnicas de Priorización y Estimación Utilizadas
Para esta iteración, utilizamos técnicas de priorización enfocadas en maximizar el impacto de las funcionalidades relacionadas con la gestión de valoraciones y comentarios, centrándonos en aquellas que ofrecieran mayor valor para el usuario en el contexto del MVP.

**Priorización**
Las historias de usuario fueron clasificadas según su impacto en la aplicación y el esfuerzo estimado de desarrollo. Las funcionalidades críticas para cerrar el ciclo de desarrollo del MVP recibieron la mayor prioridad

**Técnica Utilizada:**
Se hizo uso de la técnica MoSCoW, que permitió dividir las historias en categorías claras, asegurando que el equipo trabajara en los elementos más importantes:

- Must have:
    - Apelación de valoraciones y comentarios por parte de gerenciadores.
    - Eliminación de valoraciones y comentarios por los administradores. Estas historias fueron esenciales para completar la funcionalidad central del MVP, por lo que se priorizaron en el Sprint Backlog.

- Should have:
    - Refinamiento de la interfaz de moderación para administradores.
    - alidación de notificaciones relacionadas con comentarios. Estas tareas fueron consideradas importantes pero podrían haberse ajustado según el tiempo disponible.

- Could have:
    - Mejoras adicionales en la navegación para facilitar la visualización de comentarios.

- Won't have: 
    - Funcionalidades avanzadas de análisis y reportes sobre valoraciones. Estas fueron postergadas para ser evaluadas en futuros desarrollos.

**Estimación:**

Para estimar las tareas asociadas a las historias de usuario, utilizamos puntos de historia como medida relativa del esfuerzo requerido. Este enfoque permitió evaluar la complejidad de las tareas sin depender directamente de horas específicas, lo que facilitó la planificación y balanceo de la carga de trabajo.

Esta combinación de MoSCoW y puntos de historia nos permitió priorizar eficientemente las historias clave, asegurando que los elementos críticos fueran desarrollados dentro del tiempo disponible y de acuerdo con la capacidad del equipo.


### Métricas Relevantes para la Planificación
- Velocidad del Equipo: En esta iteración final, el equipo estimó una capacidad de 5 puntos, dado a que las tareas restantes a realizar fueron mínimas.
- Todas las historias de usuario incluidas en el Sprint Backlog (apelación de comentarios y eliminación de valoraciones) se completaron exitosamente dentro del sprint.
La estimación fue precisa, ya que permitió alcanzar los objetivos de la iteración sin generar sobrecarga para los integrantes.

- Productividad del Equipo: 
La productividad se midió de acuerdo con:
    - Tareas completadas vs. planeadas: De las 2 historias de usuario planificadas, ambas se finalizaron satisfactoriamente.
    - Ajustes proactivos: Durante las Daily Scrums, se identificaron impedimentos menores que se resolvieron rápidamente, manteniendo el enfoque en los objetivos principales.
    - La equidad en la distribución de tareas permitió que cada miembro contribuyera de manera significativa según su rol y experiencia, mejorando el desempeño general.

- Resultados y Lecciones Aprendidas
Estas métricas ayudaron a:
    - Planificar con precisión: Estimaciones realistas basadas en las iteraciones previas permitieron alcanzar un balance óptimo entre carga de trabajo y tiempo disponible.
    - Adaptarse rápidamente: La productividad se mantuvo alta gracias al monitoreo constante y al enfoque en tareas críticas.
    - Cierre exitoso del proyecto: El equipo entregó todos los artefactos finales (informe académico, video demo y prototipo ajustado), lo que asegura un avance sólido hacia la defensa del MVP.

## Seguimiento de la iteración

### Burndown Chart

En la siguiente imagen se puede ver como quedó la burndown chart una vez finalizado el proyecto. Como se puede apreciar, no quedaron story points pendientes, ya que todas las stories fueron implementadas.

![Burndown Chart](Images/BurndownChart.png)

### Minuta de las Daily Scrums

**Frecuencia:** Se realizó una unica Daily Scrums durante la iteración 4.

**Formato de las Reunion**

¿Qué logramos hacer?
- Los integrantes del equipo compartieron el avance en sus tareas asignadas.
- Se destacaron los historias de usuario completadas, como el desarrollo del flujo de apelaciones y la creación de la interfaz de eliminación de valoraciones y comentarios para los administradores.

¿Qué planificamos hacer?
- Se discutieron las tareas a completar antes de la finalización del proyecto, asignando prioridades según los objetivos del sprint.
- Una de estas tareas fue revisar el prototipo para validar que se ajusta al feedback recibido.

¿Qué impedimentos tenemos?
- Algunos problemas técnicos fueron identificados, como la necesidad de ajustar el diseño de la interfaz.


### Registro y Reporte de Horas

Clockify Christian Ingrey:
![Clockify Christian Ingrey](./Images/ClockifyChristian.png)

Clockify Federico Katz:
![Clockify Federico Katz](./Images/ClockifyFederico.png)

Clockify Gastón Minetti:
![Clockify Gaston Minetti](./Images/ClockifyGastonMinetti.png)

Clockify Emily Symonds:
![Clockify Emily Symonds](Images/ClockifyEmilySymonds.png)

### Seguimiento visual de la iteración con burndown y/o burnup charts.



## Inspección y adaptación del proceso

### Minuta de la retrospectiva

**Fecha:** Sabado 23 de noviembre a las 17 horas

**Asistentes:** Todos los integrantes del equipo

**Objetivo:** Identificar prácticas que funcionaron bien, aspectos que deben cambiar y nuevas estrategias a implementar.

**Desarrollo de la dinámica:**
- Cada miembro compartió observaciones sobre el proceso de trabajo.


### Planificación y Seguimiento de Acciones de Mejora

**Acciones Identificadas e Implementadas:**

- Distribución Equitativa del Trabajo:
    - Planificación: Se asignaron tareas según las fortalezas individuales y la capacidad disponible de cada integrante, ajustando las responsabilidades iniciales.
    - Seguimiento: Se monitoreó el avance de cada miembro para evitar sobrecargas y asegurar una contribución balanceada. Con el equipo estando disponible para ayudar en cualquier situacion de dificultad.

- Validaciones con Usuarios:
    - Planificación: Se programaron sesiones de validación al finalizar cada sprint para integrar feedback temprano en el prototipo.
    - Seguimiento: Aunque esta práctica no se implementó al 100% debido al tiempo limitado, se utilizó en iteraciones clave para ajustes de funcionalidad.


## Artefactos principales
### Prototipos interactivos finales con el feedback de las validaciones.
### Prototipos asociados como bocetos a las historias de usuario.

#### User Story 1
- **Como** usuario registrado
- **Quiero** realizar una reserva en un restaurante
- **Para** asegurarme de tener mesa disponible en la fecha y horario que deseo
![UserStory1 Crear Restaurante](https://github.com/user-attachments/assets/2f4b896d-bdae-4538-8224-917ba16c80f9)

#### User Story 2
- **Como** usuario de la aplicación
- **Quiero** visualizar los restaurantes disponibles en mi zona, junto con sus valoraciones y rango de precios
- **Para** elegir el mejor restaurante según mis preferencias.
  ![UserStory2 Vizualizar restaurantes](https://github.com/user-attachments/assets/f6079579-1e12-424a-b18b-96b6f796f3f2)

#### User Story 3
- **Como** usuario registrado
- **Quiero** cancelar una reserva realizada previamente
- **Para** liberar la mesa que ya no utilizaré y evitar cargos innecesarios
![UserStory3 Cancelar reservas](https://github.com/user-attachments/assets/cd92717e-e655-46a2-82ed-d113ad13013d)

#### User Story 4
- **Como** usuario registrado
- **Quiero** recibir notificaciones de recomendaciones diarias en base a mi historial de reservas y valoraciones
- **Para** descubrir nuevos restaurantes y platos que podrían interesarme
![UserStory4 Recibir notificaciones](https://github.com/user-attachments/assets/b91281f5-a232-4af7-85ae-be41df8049ad)

#### User Story 5
- **Como** un usuario final de la aplicación
- **Quiero** registrarme en la plataforma utilizando mi correo electrónico
- **Para** poder acceder a todas las funcionalidades y realizar reservas en restaurantes
![UserStory5 Login](https://github.com/user-attachments/assets/be56e244-0fb2-4adb-b235-c52d776ebfcb)

#### User Story 6
- **Como** usuario registrado
- **Quiero** recuperar mi contraseña cuando la haya olvidado
- **Para** poder restablecer mi acceso a la aplicación sin perder mi cuenta.
![UserStory6 Recuperar contrsena](https://github.com/user-attachments/assets/ee29c479-d65d-4d46-934f-4abc8419944b)

#### User Story 7
- **Como** usuario registrado
- **Quiero** cerrar sesión en la aplicación
- **Para** proteger mis datos personales cuando no utilizo el servicio
![UserStory7 Logout](https://github.com/user-attachments/assets/05ad0efc-177f-46bb-87ca-fda405c7592d)

#### User Story 8
- **Como** usuario registrado
- **Quiero** editar mi perfil
- **Para** actualizar mi información personal, como el avatar, nombre de usuario y restaurantes favoritos
![UserStory8 Edicion de Perfil](https://github.com/user-attachments/assets/f445a577-db51-47b6-bca8-d5985feeb3b6)
![Modificar avatar](https://github.com/user-attachments/assets/c385fabb-ac4e-4860-b3ce-8fce5882db68)

#### User Story 9
- **Como** usuario registrado
- **Quiero** agregar restaurantes a mi lista de favoritos por zona
- **Para** poder acceder rápidamente a ellos y recibir notificaciones de promociones
![UserStory9 Restaurante Favorito](https://github.com/user-attachments/assets/61db97d7-f662-4260-ad1f-9f9f03774dad)

#### User Story 10
- **Como** usuario registrado
- **Quiero** configurar mi usuario
- **Para** recibir notificaciones
![UserStory10 Configuracion de notificaiones](https://github.com/user-attachments/assets/5f185462-22b4-4ee5-93e2-d7501a53af06)

#### User Story 11
- **Como** administrador de la plataforma 
- **Quiero** registrar gerentes para los restaurantes
- **Para** asegurar que haya un responsable asignado a un restaurante.
![UserStory11 Registro de Gerentes](https://github.com/user-attachments/assets/d4d2644f-0397-47b9-b31b-1666ab74a1d5)

#### User Story 12
- **Como** usuario registrado
- **Quiero** ver las puntuaciones y comentarios de otros usuarios sobre los restaurantes
- **Para** tomar una decisión informada antes de hacer una reserva
![UserStory12 Ver Comentarios](https://github.com/user-attachments/assets/a283a9c4-28d2-4640-a729-db6985095cb5)

#### User Story 13
- **Como** usuario registrado
- **Quiero** visualizar el estatus de mis reservas
- **Para** poder verificar si han sido confirmadas, modificadas o canceladas por el restaurante.
![UserStory13 Ver Reservas](https://github.com/user-attachments/assets/1c0056e6-727a-438a-bde1-7dd375d8fc3b)

#### User Story 14
- **Como** gerente de un restaurante
- **Quiero** confirmar las reservas solicitadas por los clientes
- **Para** asegurar que las mesas están correctamente asignadas y optimizar la gestión de las reservas.
![UserStory14 Confirmar Reservas](https://github.com/user-attachments/assets/bb02f632-f017-4791-8b54-f630530f01de)

#### User Story 15
- **Como** gerente de un restaurante
- **Quiero** cancelar reservas en caso de fuerza mayor o problemas de disponibilidad
- **Para** asegurar una gestión eficiente de las mesas y mantener informados a los clientes.
![UserStory16 Cancelar Reserva](https://github.com/user-attachments/assets/ee12ea91-2104-49b1-8dab-f78adcf8c258)

#### User Story 16
- **Como** gerente de un restaurante
- **Quiero** modificar los horarios de atención del restaurante
- **Para** reflejar los cambios operativos y garantizar que los clientes siempre vean los horarios correctos
![UserStory16 Modificacion de horarios](https://github.com/user-attachments/assets/514b79d2-7d80-4809-89fc-1680d23476ec)

#### User Story 17
- **Como** gerente de un restaurante
- **Quiero** modificar los tipos de comida que ofrece mi restaurante
- **Para** reflejar cambios en el menú o nuevas ofertas y asegurar que los clientes vean la información actualizada.
![UserStory17 Modificar comidas](https://github.com/user-attachments/assets/ffb6240d-df0c-4e2a-864e-e0c63e745f8f)

#### User Story 18
- **Como** gerente de un restaurante
- **Quiero** apelar una puntuación o comentario injusto que recibe mi restaurante
- **Para** proteger la reputación del restaurante y solicitar una revisión adecuada.
![UserStory18 Apelacion](https://github.com/user-attachments/assets/fdb7e06b-327f-4f53-a1f5-60553e88c3cc)

#### User Story 19
- **Como** gerente de un restaurante
- **Quiero** recibir notificaciones cuando se solicite una reserva en mi restaurante
- **Para** poder gestionar las reservas de manera eficiente y garantizar la asignación adecuada de mesas.
![UserStory19 ver notificaciones](https://github.com/user-attachments/assets/746e697d-23db-49e7-a0f3-532129cdf9e8)

#### User Story 20
- **Como** gerente de un restaurante
- **Quiero** crear promociones para mi restaurante que serán visualizadas por los clientes
- **Para** atraer más clientes durante ciertos horarios o días específicos.
![UserStory20 Creacion de promociones](https://github.com/user-attachments/assets/761f49ee-bb38-4368-b693-73c2cdf6792b)

#### User Story 21
- **Como** administrador de la plataforma
- **Quiero** dar de alta nuevos restaurantes, indicando su dirección, tipo de comida y horarios
- **Para** que los clientes puedan hacer reservas y ver la información actualizada del restaurante.
![UserStory21 alta restaurantes](https://github.com/user-attachments/assets/7f805ca6-95e7-461d-9f68-898c1b17b44b)

#### User Story 22
- **Como** administrador de la plataforma
- **Quiero** dar de alta a gerentes para los restaurantes
- **Para** asegurar que cada restaurante esté gestionado correctamente y que los gerentes puedan administrar reservas, promociones y comentarios.
![UserStory22 Alta gerenciador en restaurante](https://github.com/user-attachments/assets/a52a5ff7-b889-45aa-8c1e-10457639d006)

#### User Story 23
- Como administrador de la plataforma
- Quiero modificar la información de los gerentes asignados a un restaurante o reasignar gerentes a otros restaurantes
- Para asegurar que la gestión de los restaurantes sea actualizada y efectiva.
![UserStory23 Modificacion gerenciador en restaurante](https://github.com/user-attachments/assets/cc4ac772-f43b-4e82-ad00-a3429765332e)

#### User Story 24
- **Como** administrador de la plataforma
- **Quiero** indicar qué restaurantes pueden aceptar reservas
- **Para** controlar cuáles restaurantes están habilitados para recibir reservas y permitir que los clientes hagan reservas solo en esos restaurantes.
![UserStory24 Reservas activas](https://github.com/user-attachments/assets/d15eaaa8-470b-4a41-a23f-886448b4ef64)

#### User Story 25
- **Como** administrador de la plataforma
- **Quiero** gestionar los comentarios y puntuaciones que los clientes dejan en los restaurantes
- **Para** asegurarse de que las reseñas sean apropiadas y cumplan con las políticas de la plataforma.
![UserStory25 Administracion de Comentarios](https://github.com/user-attachments/assets/9b079555-feeb-409b-ad1a-f260ebfffedd)

#### User Story 26
- **Como** usuario registrado
- **Quiero** recibir notificaciones de promociones de mis restaurantes favoritos 
- **Para** estar informado de las mejores ofertas
![UserStory26 Notificaciones de cliente](https://github.com/user-attachments/assets/61cfbf18-658f-4a6b-b2f7-225d4b805cdf)

#### User Story 27
- **Como** usuario registrado
- **Quiero** visualizar mi perfil que incluya nombre de usuario, avatar, restaurantes favoritos, recomendaciones realizadas y mi historial de visitas a restaurantes
- **Para** revisar y gestionar mi actividad dentro de la aplicación
![UserStory27 Ver perfil](https://github.com/user-attachments/assets/835b38b5-d320-462c-888b-58c4cc97ae1d)


### Lista de posibles características (features) que quedaron fuera del alcance del proyecto para expandir el sistema y agregar valor:
#### Colaboración y Redes Sociales
  - Compartir en Redes: Integrar botones para compartir contenido en redes sociales.

  Esto le permitirá dar a los restaurantes una forma de crecer y poder llegar a diferentes consumidores.

#### Reportes y Analíticas
- Por otro lado, el cliente dijo que los gerenciadores al igual que los administradores deberían de poder tener:
  - Dashboards: Implementar paneles con estadísticas clave para los gerenciadores o administradores (cantidad de reservas, actividad de usuarios, restaurantes con mejor recomendaciones y calificaciones, etc.).
  - Reportes Automáticos: Enviar reportes periódicos sobre estas estadísticas así se automatiza el proceso, además de poder consumir estas estadísticas en cualquier momento.

#### Soporte Multilingüe: 
  - Ampliar el soporte de idiomas en la plataforma. Actualmente está todo en español y estaría bueno poder extender para la traducción a varios otros idiomas.

#### Monetización y Modelos de Negocio
  - Planes de Suscripción: Ofrecer características premium bajo diferentes planes de suscripción. Por ejemplo, que los gerenciadores con planes premium sean los que puedan acceder a las estadísticas. 

#### Seguridad y Confianza
- Por último, se podrían agregar funcionalidades de seguridad adicionales para proteger la información de los usuarios y garantizar la confianza en la plataforma:
  - Autenticación Multifactor: Asegurar las cuentas con autenticación adicional como OTP o biometría.
  - Historial de Acceso: Mostrar un registro de inicios de sesión y actividades importantes para los administradores, esto también aportaría buenas estadísticas para poder ver cómo se comportan los usuarios para luego poder mejorar los planes de monetización.

## Video demo

En el siguiente video, mostramos una demostración del prototipo MVP desarrollado, presentando las funcionalidades clave y el flujo principal de la aplicación:

Link: [Video Demo](https://www.youtube.com/watch?v=bykKDfkQCX8)
