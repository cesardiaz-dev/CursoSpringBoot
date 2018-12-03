# TURNERO

### Requerimientos ciclo 1
* Existen varias categorias de turnos
  * A - Prioritario
  * B - Buena Gente
  * C - Cliente Normal
* Desde una ventana, un usuario solicita un turno de una categoria y el sistema genera un consecutivo de dicha categoria
* Un asesor llama un usuario, el cual tiene el turno que sigue en la secuencia. El orden se dará por hora de solicitud del turno.
* Cuando el asesor llama el turno, este sale en una pantalla con el No de turno y el No de asesor.
* Se puede consultar el numero de turnos (y cuales) fueron gestionados por un asesor.
* Se debe calcular el tiempo promedio de atencion por categoria 
  * General
  * por Asesor  
  **Nota**: El tiempo de atención va desde que llamaron el turno (por primera vez) hasta que dan por terminado el turno.
* Un asesor puede reintentar llamar al turno si este no ha llegado donde el asesor (usuario dormido)
* Un usuario que perdió su llamado (estaba en el baño) el asesor podra llamarlo en cualquier momento.

### Requerimientos ciclo 2
* El asesor puede enviar un turno a "NO ATENDIDO" si despues de llamarlo (y rellamarlo) no se acerca. Si lo marca asi, llama automaticamente el siguiente turno.
* El asesor puede dar por "TERMINADO" un turno y no llama el siguiente hasta que explicitamente solicite uno nuevo.
* Se debe poder registrar un nivel de prioridad en la cola para las categorias. Estos niveles son:
  1. Cliente externo  
  2. Cliente interno  
  3. Tercera edad y embarazadas  
  Si en la cola existen clientes de nivel 3, se debe atender todos de forma consecutiva.  
  Si en la cola no hay clientes de nivel 3 pero si hay de nivel 2 y 1, se deben atender 3 de nivel 2 por 2 de nivel 1.  
  Si solo se encuentran turnos del mismo nivel, atenderlos de forma consecutiva.  
* Cada dia se reinicia el consecutivo de los turnos, y los turnos no atendidos de dias anteriores ya no serán llamados. 
  
















