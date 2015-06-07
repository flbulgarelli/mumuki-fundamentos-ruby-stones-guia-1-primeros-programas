Algo interesante de nuestros tableros es que en sus celdas podemos poner cualquiera cantidad de bolitas de cualquier color.

Por ejemplo, si tenemos este tablero:

![5x2h](https://raw.githubusercontent.com/mumuki/mumuki-fundamentos-ruby-stones-guia-1-primeros-programas/master/5x2h.png)

y ejecutamos el siguiente programa:

```ruby
def main
  push! red
  push! red
  push! blue
  push! green
  push! red
end
```

el cabezal colocará en la celda actual (que es la `(3, 1)`) tres bolitas rojas, una azul y una verde.

¡Copiá este programa en el editor y fijate cómo queda el tablero!