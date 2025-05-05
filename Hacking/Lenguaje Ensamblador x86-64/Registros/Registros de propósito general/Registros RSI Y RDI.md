
**Registros** **RSI Y RDI** 
Se utilizan para operaciones de cadena en un programa 
**RSI (Source Index) y RDI (Destination Index)** son registros de propósito general en **x86-64**, y su principal uso es en **operaciones con memoria y cadenas de caracteres** (strings), pero también se pueden usar en otros contextos.

### **¿Qué significa "operaciones de carga"?**

Cuando hablamos de "operaciones de carga", nos referimos a **mover datos dentro de la memoria o entre registros**. RSI y RDI suelen participar en estas operaciones, especialmente en la manipulación de **cadenas de texto (strings) y bloques de memoria**.

---

### **Uso tradicional de RSI y RDI**

En las instrucciones **REP**, **MOVS**, **CMPS**, y otras relacionadas con cadenas:

- **RSI (Source Index - Índice de origen)** → Apunta a la **fuente** de datos (de dónde se lee).
    
- **RDI (Destination Index - Índice de destino)** → Apunta al **destino** de los datos (dónde se guardan)
![[Pasted image 20250329003608.png]]