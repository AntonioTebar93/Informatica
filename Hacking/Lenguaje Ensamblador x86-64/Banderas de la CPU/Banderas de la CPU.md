**¿Qué es una bandera?

Cuando un usuario realiza operaciones aritméticas y operaciones lógicas en un ordenador:

1. primero van a la **memoria** **RAM**
2. Luego estas se transfieren a la **CPU**, para su procesamiento y ejecución
3. Después del cálculo de esta entrada del usuario, la cpu proporciona un estado de esa operación
 ![[Pasted image 20250329011635.png]]

4. Este estado se da por un registro llamado **registro de bandera**, cada vez que la cpu recibe cualquier entrada aritmética y operaciones lógicas, esta bandera almacenada da el estado de ese resultado.
  ![[Pasted image 20250329011823.png]]
  ASPECTO DE UN REGISTRO DE BANDERA, tiene un tamaño de 32 bits donde cada bit indica un bit de bandera (0 o 1). 
  -> 1 significa que la bandera está encendida y 0 significa que está apagada
  
==**Banderas comunes**== 

![[Pasted image 20250329012308.png]]

**CARRY FLAG**

Hay que tener en cuenta que esta operación de adición se va a hacer sobre un registro de 8 bits, entonces es cuando hay un desbordamiento, para eso está la carry flag, para indicarlo

**PARITY FLAG** 