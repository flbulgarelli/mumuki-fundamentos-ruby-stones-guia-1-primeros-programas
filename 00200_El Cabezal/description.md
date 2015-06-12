Como notaste en el ejercicio anterior, el tablero generado tenía una **celda** marcada:

![3x3h](https://raw.githubusercontent.com/mumuki/mumuki-fundamentos-ruby-stones-guia-1-primeros-programas/master/3x3h.png)

¿Por qué ocurre esto? Porque además de tableros, tenemos **cabezales**: todo tablero tiene un cabezal, que está parado sobre alguna de sus celdas. Por ejemplo, la posición del cabezal en el tablero anterior era  columna cero, fila cero, lo cual escribimos así: `(0, 0)` .

El cabezal puede estar arriba de cualquier celda que esté dentro del tablero. Por ejemplo, el siguiente es un tablero de 5x2, con el cabezal en la posición `(3, 1)`:

![5x2h](https://raw.githubusercontent.com/mumuki/mumuki-fundamentos-ruby-stones-guia-1-primeros-programas/master/5x2h.png)

Cuando decimos que el cabezal está en la posición `(3, 1)`, **el orden de los números es importante**: el primer número representa la columna, y el segundo, la fila.

¿No estás muy convencido de todo esto aún? Presioná Enviar y generaremos un tablero 3x3 con el cabezal en la posición `(1, 2)`.