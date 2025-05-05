**RAX**
Tiene una capacidad de 64 bits, hace referencia a un registro completo.

Si se ocupan los primeros 32 bits de RAX únicamente se llamará **EAX** (32 bits).

Si solo se ocupan la mitad de 32 bits entonces (16 bits) se llamará **AX** (16 bits)

Si lo volvemos a dividir en dos partes tendremos dos registros llamados **AH**(para los bits del 8 al 15) y **AL** (para los bits de 0 al 7) ambos registros de 8 bits.

Lo mismo ocurrirá con RBX, RCX Y RDX
![[Pasted image 20250329001451.png]]

![[Pasted image 20250329003037.png]]


![[Pasted image 20250329003107.png]]


![[Pasted image 20250329003134.png]]



Estudiaremos procesadores de 64 bits, por lo que tendremos registros de 64 bits

---


Propósito de los registros Generales

RAX -> Acumulador, operaciones aritméticas, retorno de funciones.
RBX -> Base para direcciones, almacenamiento temporal.
![[Pasted image 20250329002041.png]]
RCX -> Contador en bucles y operaciones repetitivas.
RDX -> Datos en operaciones matemáticas, almacenamiento de resultados grandes.
![[Pasted image 20250329002124.png]]

**SE UTILIZAN PARA ALMACENAR DATOS GENERALES** 

Ejemplo gráfico

![[Pasted image 20250329002357.png]]
![[Pasted image 20250329002447.png]]![[Pasted image 20250329002650.png]]

