# Asistencia-trabajadores-ETITC
---
## Planteamiento del problema
El sistema actual de la Universidad ETITC para el registro de asistencia de los trabajadores es manual, lo que genera retrasos, errores humanos, y dificultades en la recolección de datos para su análisis posterior. El objetivo de este proyecto es implementar un sistema automatizado que permita registrar y controlar la asistencia de los empleados de manera eficiente, reduciendo el margen de error y mejorando la capacidad de generar informes precisos en tiempo real.

## Objetivo

### General
Implementar un sistema automatizado que permita registrar la entrada y salida de los trabajadores en la Universidad ETITC, mejorando la precisión y la rapidez del control de asistencia.
### Especificos o Auxiliares
1). Digitalizar el proceso de registro de asistencia utilizando terminales automatizadas.

2). Desarrollar una interfaz de usuario amigable que permita a los empleados registrar su asistencia de manera rápida.

3). Integrar el sistema con una base de datos centralizada que almacene los registros de asistencia y permita la generación de reportes en tiempo real.

4)- Capacitar al personal administrativo en el uso del nuevo sistema automatizado.

5). Evaluar el impacto del sistema en la reducción del tiempo de registro y la mejora de la precisión de los datos.



## Justificación 
El registro manual actual no solo es ineficiente, sino que también está sujeto a errores humanos que pueden impactar negativamente en la calidad de los datos recolectados. Con la implementación de un sistema automatizado, se espera una reducción del 50% en los tiempos de registro por trabajador y un 80% en la cantidad de errores reportados. Además, la universidad podrá generar reportes de asistencia en tiempo real, lo que facilitará la toma de decisiones en relación con la gestión de recursos humanos.

### Metodologías de Desarrollo

## Modelo en Cascada (Waterfall)
El modelo en cascada sigue un enfoque secuencial, donde cada fase debe completarse antes de avanzar a la siguiente. Para nuestro proyecto de implementación de un sistema automatizado de registro de asistencia, el modelo se aplicaría de la siguiente manera:

## Recolección de Requisitos:
En esta fase, se trabajará estrechamente con el personal administrativo de la Universidad ETITC para identificar las necesidades específicas del sistema. Se deben definir requisitos funcionales, como el uso de terminales RFID para el registro de asistencia, y requisitos no funcionales, como el tiempo máximo de respuesta del sistema (que debe ser menor a 2 segundos). Se realizarán reuniones con los usuarios clave, como el departamento de recursos humanos, para definir los tipos de reportes necesarios (por ejemplo, reportes de ausentismo mensual y horas trabajadas).

## Diseño del Sistema:
En esta fase se creará un diseño detallado de la arquitectura del sistema. Para el proyecto, esto implica definir cómo se integrarán los lectores de tarjetas RFID con la base de datos de los trabajadores. Además, se diseñará una interfaz de usuario sencilla que permita a los empleados registrar su asistencia con un solo paso, y se estructurará la base de datos para almacenar la información de los trabajadores de manera eficiente. Aquí también se incluirá un diseño para la generación de reportes automáticos que puedan ser consultados por los administradores en tiempo real.

## Implementación:
Durante esta fase, los desarrolladores comenzarán a codificar el sistema, siguiendo el diseño aprobado. En nuestro caso, se construirán los módulos de registro, que permiten a los empleados registrar su entrada y salida mediante las tarjetas RFID o huellas dactilares. También se desarrollará un módulo para la generación de reportes personalizados según las necesidades definidas. Además, se integrarán las funcionalidades de seguridad para garantizar que solo los empleados autorizados puedan acceder a sus propios registros.

## Pruebas:
Se realizarán pruebas exhaustivas para garantizar que el sistema funcione correctamente en todas las condiciones. Esto incluye pruebas unitarias para cada módulo del sistema, pruebas de integración para asegurar que el sistema completo (lectores, base de datos y reportes) funcione como se espera, y pruebas de rendimiento para garantizar que el sistema responda en menos de 2 segundos cuando un empleado registre su asistencia.

## Mantenimiento:
Una vez que el sistema esté en funcionamiento, se establecerá un plan de mantenimiento para corregir errores que puedan surgir y optimizar su rendimiento a lo largo del tiempo. Por ejemplo, si el personal administrativo detecta que el sistema no genera ciertos reportes como se espera, se realizarán ajustes en el código y en la base de datos para solucionar el problema.

## Scrum
Scrum es una metodología ágil que permite desarrollar un sistema de manera iterativa, dividiendo el trabajo en sprints o ciclos cortos. Para nuestro proyecto, Scrum se aplicaría de la siguiente manera:

## Product Owner:
El jefe de recursos humanos de la universidad actuará como Product Owner, representando las necesidades de los usuarios finales. Su responsabilidad será definir y priorizar las funcionalidades esenciales del sistema, como el registro en tiempo real, la validación automática de credenciales y la creación de reportes automatizados.

## Sprint Planning:
Antes de cada sprint, el equipo se reunirá con el Product Owner para planificar las tareas. En el primer sprint, el equipo puede enfocarse en desarrollar la funcionalidad de registro básico, como permitir que los trabajadores registren su entrada y salida mediante RFID. En un segundo sprint, se integrará la base de datos para almacenar los registros de asistencia. Posteriormente, se desarrollará la funcionalidad de generación de reportes y validación de los datos.

## Daily Stand-Up:
Cada día, el equipo de desarrollo se reunirá brevemente para revisar el progreso y discutir cualquier obstáculo. Por ejemplo, si el equipo encuentra problemas con la integración del lector de huellas digitales, esto se discutirá en la reunión diaria para ajustar las tareas o buscar soluciones.

## Sprint Review:
Al final de cada sprint, se presentará al Product Owner el trabajo completado. Por ejemplo, si en un sprint se completó la funcionalidad de registro, se mostrará cómo los empleados pueden usar las tarjetas RFID para registrar su asistencia. El Product Owner evaluará el resultado y dará feedback que se aplicará en sprints posteriores.

## Kanban
Kanban es una metodología que permite visualizar el flujo de trabajo y mejorar continuamente los procesos. Para este proyecto, la aplicación de Kanban sería la siguiente:

## Tablero Kanban:
Se utilizará un tablero Kanban para gestionar las tareas del proyecto. Las columnas representarán las fases del desarrollo, como "Por Hacer", "En Proceso", y "Completado". Las tareas, como el desarrollo del módulo de registro, la integración de la base de datos, y la creación de la interfaz de usuario, se moverán a través de estas columnas a medida que el equipo complete cada fase.

## Desarrollo Continuo:
El equipo se enfocará en completar una tarea a la vez, garantizando que el desarrollo sea continuo y sin interrupciones. Por ejemplo, una vez que se termine la funcionalidad de registro de asistencia, el equipo pasará inmediatamente a desarrollar la funcionalidad de generación de reportes.

## Limitación de Tareas en Proceso:
Para evitar sobrecargar al equipo, se limitará el número de tareas en proceso al mismo tiempo. Por ejemplo, solo se trabajará en la interfaz de usuario y la base de datos si el equipo ha completado la funcionalidad de registro y generación de reportes.

## Programación Extrema (XP)
Programación Extrema (XP) es una metodología ágil que se centra en la mejora continua y en la colaboración cercana. Para este proyecto, la aplicación de XP se verá de la siguiente manera:

## Desarrollo en Pares:
El equipo adoptará el desarrollo en pares para garantizar la calidad del código. Por ejemplo, dos desarrolladores trabajarán juntos en la implementación del módulo de registro de asistencia. Mientras uno escribe el código, el otro revisará el trabajo en tiempo real y sugerirá mejoras. Esto no solo asegura un código limpio, sino que también ayuda a detectar y corregir errores rápidamente.

## Refactorización Continua:
A medida que se completen los módulos del sistema, el equipo refactorizará el código para optimizar su rendimiento. Por ejemplo, si se detecta que el proceso de validación de asistencia es lento, se reestructurará el código para mejorar la eficiencia.

## Integración Continua:
Cada vez que se complete un módulo, como la validación de usuarios o la generación de reportes, este se integrará de inmediato en el sistema general. Esto permitirá al equipo detectar y corregir problemas antes de que se conviertan en grandes fallos.

### Requisitos Funcionales:

Permitir que los trabajadores registren su asistencia de manera digital (app móvil o terminal física).

Integración en tiempo real con la base de datos de la universidad.

Interfaz intuitiva para que el personal administrativo consulte y ajuste los registros.

Capacitar al personal en el uso del sistema.

Mantener y ajustar el sistema periódicamente para asegurar su buen funcionamiento.

## Diagrama UML de Clases Trabajadores ETITC

![Diagrama UML de clases trabajadores ETITC mas completo](https://github.com/user-attachments/assets/9f5a9684-8623-4b6c-896f-030f0262a25c)

## Diagrama UML de Objetos Trabajadores ETITC

![Diagrama UML de objetos trabajadores ETITC mas completo](https://github.com/user-attachments/assets/13884739-7834-4342-b758-842dc3abf100)

## Diagrama UML de Casos de Uso Trabajadores ETITC

![Diagrama UML de caso de Uso trabajadores ETITC mas completo](https://github.com/user-attachments/assets/65e832b1-efbe-46c8-9a59-e773f8e8e8b5)

## Diagrama UML de Actividades Trabajadores ETITC

## Conclusiones
La implementación de un sistema automatizado para el registro y control de asistencia en la Universidad ETITC permitirá mejorar la eficiencia del proceso, reducir errores, y facilitar la generación de reportes en tiempo real. Cada metodología de desarrollo presentada (Waterfall, Scrum, Kanban, XP) tiene sus ventajas en diferentes contextos, pero para este proyecto en particular, una combinación de enfoques ágiles, como Scrum o Kanban, puede ser la más adecuada para permitir una respuesta rápida a los cambios y una mejora continua durante el proceso de desarrollo.

## Referencias

El contenido de este proyecto fue desarrollado con el apoyo de ChatGPT, una herramienta de inteligencia artificial de OpenAI, que asistió en la redacción, estructuración y aplicación de conceptos técnicos.

OpenAI. (n.d.). ChatGPT. Disponible en https://chat.openai.com/
