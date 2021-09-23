# septiembre13-2021

tocamos un nuevo tema llamdo  "estructuras condicionales" nos mostro un ejemplo en visual basic, se realizo el diagrama de flujo y se mostro en dart

## actividad

```
Sub inicio()
    n1 = Int(InputBox("Por favor escriba primera nota"))
    n2 = Int(InputBox("Por favor escriba segunda nota"))
    n3 = Int(InputBox("Por favor escriba tercera nota"))
    n4 = Int(InputBox("Por favor escriba cuarta nota"))
    n5 = Int(InputBox("Por favor escriba quinta nota"))
    d = n1 + n2 + n3 + n4 + n5
    t = d / 5
    If (t < 7) Then
        MsgBox "El estudiante reprobó con " & n & " como nota final "
    Else
        MsgBox "El estudiante aprobó con " & n & " como nota final "
    End If
End Sub
```
