
**Primero que todo, si no lo tenemos instalado:**

Install-Module -Name ImportExcel -Force -Scope CurrentUser

Luego dos métodos:

**Ejemplo**

==Inicia la aplicación de Excel==
$Excel = New-Object -ComObject Excel.Application
$Excel.Visible = $true  # Si quieres ver la interfaz de Excel
==Crea un nuevo libro de trabajo==
$Workbook = $Excel.Workbooks.Add()
==Selecciona la hoja activa==
$Worksheet = $Workbook.Sheets.Item(1)
==Escribe en la celda A1==
$Worksheet.Cells.Item(1, 1).Value = "Hola, mundo!"
==Escribe en otras celdas==
$Worksheet.Cells.Item(2, 1).Value = "Valor 1"
$Worksheet.Cells.Item(2, 2).Value = "Valor 2"
==Guarda el archivo==
$FilePath = "C:\Ruta\A\Tu\Archivo.xlsx"
$Workbook.SaveAs($FilePath)
o sin crear la variable FilePath
Simplemente con $Workbook.SaveAs($"C:\Ruta\A\Tu\Archivo.xlsx")

$Excel.Quit()


**Podemos seguir el mismo procedimiento una vez tenemos el archivo creado vacío:**

Crear el archivo .xlsx vacío
New-Item -Path "C:\Ruta\A\Tu\Directorio" -Name "archivo.xlsx" -ItemType File

Iniciar una instancia de Excel (en segundo plano)
$Excel = New-Object -ComObject Excel.Application
$Excel.Visible = $true  # Opcional: mostrar Excel

Abrir el archivo .xlsx recién creado
$Workbook = $Excel.Workbooks.Open("C:\Ruta\A\Tu\Directorio\archivo.xlsx")

Seleccionar la primera hoja de trabajo
$Worksheet = $Workbook.Sheets.Item(1)

Escribir en la celda A1
$Worksheet.Cells.Item(1, 1).Value = "Hola, Mundo!"

Guardar el archivo
$Workbook.Save()

Cerrar el archivo
$Workbook.Close()

Cerrar Excel (opcional, si ya no lo necesitas)
$Excel.Quit()


