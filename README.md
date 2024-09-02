# Asistencia-trabajadores-ETITC
---

## Objetivo

### General
Implementar un sistema automatizado de registro y control de asistencia para los trabajadores de la Universidad ETITC, con el fin de optimizar el proceso de registro, reducir los tiempos de espera y mejorar la eficiencia operativa de la institución.

### Especificos o ### Auxiliares
1).Desarrollar e implementar un sistema digital de registro que permita a los trabajadores (docentes, celadores, personal de oficios varios) registrar su asistencia de manera rápida y eficiente.

2).Capacitar al personal administrativo y a los trabajadores en el uso del nuevo sistema, asegurando que todos puedan operar la plataforma de manera efectiva.

3).Reducir los tiempos de espera asociados al proceso de registro mediante la simplificación y automatización de los procedimientos actuales.

4).Evaluar y ajustar el sistema periódicamente para asegurar su eficacia y resolver posibles inconvenientes que puedan surgir durante su implementación.

5).Integrar el sistema de registro con la base de datos institucional, facilitando la gestión y consulta de la información de los trabajadores en tiempo real.



## Justificación 
El proceso de registro de asistencia en la Universidad ETITC presenta actualmente desafíos significativos debido a su naturaleza tediosa y demorada. El registro manual, que se utiliza actualmente, carece de la velocidad y eficiencia necesarias para manejar el volumen de trabajadores en la universidad. Esta situación afecta no solo la eficiencia operativa de la institución, sino que también puede impactar negativamente en la satisfacción y productividad de los trabajadores, además de ralentizar procesos críticos como el inicio de clases y la entrega de salones e implementos tecnológicos a los docentes.

La implementación de un sistema automatizado de registro permitirá optimizar este proceso, reduciendo significativamente los tiempos de espera y mejorando la precisión en el registro de la información. Además, un sistema digitalizado facilitará la gestión de datos y minimizará los errores humanos, mientras que la capacitación del personal garantizará su uso efectivo. En resumen, esta iniciativa contribuirá a mejorar la satisfacción de los trabajadores, la eficiencia del personal administrativo y la calidad general de la gestión institucional en la Universidad ETITC.

## Planteamiento
En la Universidad ETITC, se ha identificado un problema recurrente en el proceso de registro de trabajadores, especialmente en lo que respecta a docentes, celadores y personal de oficios varios. El proceso de registro actual, que se realiza de manera manual, es percibido como tedioso y demorado, lo que genera molestias tanto en los trabajadores como en el personal administrativo encargado de llevar a cabo estos registros. Esta situación se debe, en gran medida, a la falta de un sistema automatizado eficiente y a la ausencia de un método digital que permita un registro más rápido y preciso. Como resultado, este problema afecta negativamente la eficiencia operativa de la universidad, impactando también en la satisfacción y productividad de los trabajadores. Además, esta demora puede ralentizar el inicio de las clases y la entrega de salones e implementos tecnológicos a los docentes, lo que a su vez afecta el proceso de aprendizaje de los estudiantes. Es necesario identificar las causas subyacentes y proponer soluciones que optimicen este proceso, haciéndolo más ágil y efectivo.

1. Identificación de Modelos en Sistemas Reales
Sistema Elegido: Sistema Automatizado de Registro de Asistencia para los Trabajadores de la Universidad ETITC

Clases:

Trabajador

Atributos:

idTrabajador: int
nombre: string
rol: string (docente, celador, personal de oficios varios)
horaEntrada: DateTime
horaSalida: DateTime
Métodos:

registrarEntrada(hora: DateTime): void
registrarSalida(hora: DateTime): void
RegistroAsistencia

Atributos:

idRegistro: int
trabajador: Trabajador
fecha: Date
horaEntrada: DateTime
horaSalida: DateTime

Métodos:

calcularHorasTrabajadas(): float
actualizarRegistro(horaEntrada: DateTime, horaSalida: DateTime): void
Administrativo

Atributos:

idAdministrativo: int
nombre: string
Métodos:

consultarRegistro(trabajador: Trabajador, fecha: Date): RegistroAsistencia
ajustarRegistro(registro: RegistroAsistencia): void
Relaciones:

Un Trabajador puede tener múltiples Registros de Asistencia.
Un Registro de Asistencia está asociado a un único Trabajador.
Un Administrativo puede consultar y ajustar varios Registros de Asistencia.



