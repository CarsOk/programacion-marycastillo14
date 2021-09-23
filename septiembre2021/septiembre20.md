# septiembre20-2021

en esta clase creamos formularios de datos en excel calculando las columnas, realizamos calculos de 5 notas comprobando si aprobo o no 

## actividad 

<img src="screenshot_3.png"width="100">

```
Sub ejemplo()
    Hoja2.Cells(3, 1) = Hoja1.Cells(4, 3)
    Hoja2.Cells(3, 3) = Hoja1.Cells(6, 3)
    Hoja2.Cells(3, 5) = Hoja1.Cells(8, 3)
    MsgBox "regisro almacenado"
    Hoja1.Cells(4, 3) = ""
    Hoja1.Cells(6, 3) = ""
    Hoja1.Cells(8, 3) = ""
End Sub
```
```
Function misnotas(n1, n2, n3, n4, n5)
    promedio = (n1 + n2 + n3 + n4 + n5) / 5
    misnotas = promedio
    If (misnotas > 7) Then
        misnotas = " el estudiante aprobo" & n & " nota final "
    Else
        misnotas = " el estudiante reprobo" & n & " nota final "
    End If
    
End Function
```

