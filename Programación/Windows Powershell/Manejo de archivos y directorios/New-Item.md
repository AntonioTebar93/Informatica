**Crear un archivo en directorio actual** 
`New-Item -Name "mi_archivo.ps1" -ItemType File`  

`New-Item -Path "C:\Ruta\Al\Directorio" -Name "mi_archivo.ps1" -ItemType File`  


**Podemos abrir el archivo creado con**

.\nombre de archivo -> si estamos en el directorio en el que se encuentra el archivo.


**Podemos renombrar el archivo con**
PS C:\Users\Antonio\desktop> Rename-Item "lolailo.txt" -NewName "lolailomodificado.txt"
# Mover y renombrar el archivo "lolailo.txt" a "lolailomodificado.txt" en la misma carpeta
Move-Item -Path "C:\Users\Antonio\desktop\lolailo.txt" -Destination "C:\Users\Antonio\desktop\lolailomodificado.txt"


Como copiarlo

y como moverlo





