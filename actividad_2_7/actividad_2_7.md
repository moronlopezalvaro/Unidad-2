# Ejercicio 1: Variable inexistente
El error está a la hora de llamar a la variable "result" que se llama erróneamente con "reslt". Es un error de referencia.
![](/actividad_2_7/capturas/ejercicio1.png)

# Ejercicio 2: Comparaciones sospechosas
El error está en la condición del if porque al comparar la edad de la variable se utiliza la expresión "=>", que es una función flecha en vez de un comparador, tendría que ser ">=". Es un error lógico.
![](/actividad_2_7/capturas/ejercicio2.png)

# Ejercicio 3: Return of the Jedi
El error está en que la función multiplicar no devuelve nada por tener el "return" comentado, si se descomenta la función debería devolver el resultado de la operación. Es un error lógico.
![](/actividad_2_7/capturas/ejercicio3.png)

# Ejercicio 4: Names, names...
El error está en  que se intenta usar la variable "name" cuando el parámetro de la función se llama "nombre", por lo que "name" no está definida. Es un error de referencia.
![](/actividad_2_7/capturas/ejercicio4.png)

# Ejercicio 5: Out of control
El error está en la condición del bucle for, que usa "<=" en vez de "<". Por eso el bucle da una vuelta de más e intenta sumar una posición del array que no existe. Es un error lógico.
![](/actividad_2_7/capturas/ejercicio5.png)

# Ejercicio 6: Usando expresiones
El error está en el if, que usa "=" (asignación) en vez de "===" (comparación). Como no se puede asignar un valor a "num % 2", el programa ni siquiera llega a ejecutarse. Es un error sintáctico.
![](/actividad_2_7/capturas/ejercicio6.png)

# Ejercicio 7: Callback defectuoso
El error está en la llamada al callback, ya que se le pasa la variable "dat" cuando el parámetro de la función se llama "datos", por lo que "dat" no está definida. Es un error de referencia.
![](/actividad_2_7/capturas/ejercicio7.png)

# Ejercicio 8: Evento click sospechoso (HTML + JS)
El error está en el console.log dentro del evento click ya que se intenta mostrar la variable "msj" cuando la variable declarada se llama "msg". El error solo aparece al pulsar el botón que es cuando se ejecuta la función. Es un error de referencia.
![](/actividad_2_7/capturas/ejercicio8.png)

# Ejercicio 9: Cálculo misterioso