# **PROGRAMACION** 


## **FECHA** <br>

### **septiembre 13 2021** <br>

en esta clase aprendimos en visual basic a 
hacer que el programa tenga una serie de 
opciones para eso utilizamos en visual basic 
el codigo " Int(InputBox("texto")) "  <br>

**EJEMPLO DE EXECEL VISUAL BASIC** <br>
```
Sub ejemplo ()
    
    n = Int(InputBox("ingrese el primer 
    numero"))
    
    If (n > 10) Then
        MsgBox" n es mayor " & n & " o igual 
        que 10 "
    
    Else
        MsfBox" n es menor " & n & " que 
        10 "
    End If    
End Sub
```
**EJERCICIO DE EXECEL VISUAL BASIC** <br>

```
Sub inicio()
    g = Int(InputBox("escriba primera nota"))
    c = Int(InputBox("escriba segunda nota"))
    p = Int(InputBox("escriba tercera nota"))
    k = Int(InputBox("escriba cuarta nota"))
    u = g + c + p + k
    b = u / 4
    If (b > 7) Then
        MsgBox " con la nota " & b & " el estudiante aprobo "
    Else
        MsgBox " con la nota " & b & " el estudiante reprobo "
    End If
End Sub
```
**DIAGRAMA DE FLUJO DE STAR UML** <br>

<img src="img/img3.png" width="400">