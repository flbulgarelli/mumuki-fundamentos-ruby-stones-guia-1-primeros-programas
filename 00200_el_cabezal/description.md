Como notaste en el ejercicio anterior, el tablero generado tenía una celda marcada:

![3x3h](https://raw.githubusercontent.com/mumuki/mumuki-fundamentos-ruby-stones-guia-1-primeros-programas/master/3x3h.png)

¿Por qué ocurre esto? Porque además de tableros, tenemos **cabezales**: todo tablero tiene un cabezal, que está parado sobre alguna de sus celdas. Por ejemplo, la posición del cabezal en el tablero anterior era  columna cero, fila cero, lo cual escribimos así: `(0, 0)` .

El cabezal puede estar arriba de cualquier celda que esté dentro del tablero. Por ejemplo, el siguiente es un tablero de 5x2, con el cabezal en la posición `(4, 1)`:

![5x2h](https://raw.githubusercontent.com/mumuki/mumuki-fundamentos-ruby-stones-guia-1-primeros-programas/master/5x2h.png)

¿No estás muy convencido aun? Presioná Enviar y generaremos un tablero 3x3 con el cabezal en la posición `(1, 2)`.