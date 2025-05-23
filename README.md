# ActividadPatrones0523
### Estudiantes: Gabriella Jujihara - Raúl Ibarra
### Sección 2

En el presente repositorio, se presentarán los errores a detectar que fueron solicitados en la clase de hoy para cada uno de los diagramas entregados por el docente.

## Caso de Uso
### Errores identificados:

- Flechas cruzadas: las flechas en el diagrama se cruzan bastante, lo que hace que leer el diagrama pueda resultar un poco confuso, no es del todo incorrecto, pero es una mala práctica a evitar.
- Falta de clarificación sobre tipo de relación: las flechas en el diagrma no especifícan si son includes o extends, lo que de plano hace que el diagrama no sea legible.
- Uso de flechas en vez de lineas para denotar el flujo principal del actor: el enunciado se explica solo y es fácil de solucionar; solo usando lineas en vez de flechas es más que suficiente para solucionarlo.

### Soluciones:

Para reparar los errores de este diagrama se necesitaría el uso correcto de las relaciónes dentro del caso de uso, aparte de esto; una reestructuración del diagrama evitaría la confusión para leer este mismo al evitar las flechas cruzadas, ya que esto a largo plazo puede terminar siendo un problema para gente recién llegada o externa al proyecto.

## Diagrama de Clases
### Errores identificados:

- Redundancia de clases: las clases "SistemaReserva" y "Usuario" tienen metodos bastante similares en cuanto a superficialidad se refiere, volviendo a una de estas 2 clases inútiles.
- Falta de notaciónes en las interacciones del sistema: dentro del diagrama se especifíca como interactuan las clases a través de las flechas utilizadas, pero no se especifica exactamente que acción realizan dentro de este mismo, por ejemplo, la única instancia de esto viene siento la relación simple "reserva" entre "Usuario" y "Sala".
- Falta de relación en la clase "Reserva": según el diagrama indíca, la clase "Reserva" no se relaciona con absolutamente ninguna clase, puede ser que sea el caso, pero... Una clase llamada "Reserva" que no es utilizada en un sistema de reservas?

### Soluciones:

Para solucionar los errores de este diagrama se puede tomar el siguiente curso de accion: Reimplementar la clase Sistema de Reserva y Usuario para juntarlas y crear Usuario como una clase que sirva para implementar Deep Copy con Prototype para el registro de usuarios en una base de datos del sistema, de esta manera se mantienen ambas clases pero se elimina la redundancia junto con una ampliación del sistema que lo vuelve mucho más robusto. Las falta en la notación de las interacciones se puede resolver con simplemente, no se, indicarlas quizá?. Por ultimo, la falta de relación en la clase "Reserva" puede ser resuelta de plano con relacionarla al sistema de reservas como una plantilla usando Deep Copy a la hora de crear cada reserva nueva en el sistema.
 
## Diagrama de Sistema
### Errores identificados:
-
-
-
