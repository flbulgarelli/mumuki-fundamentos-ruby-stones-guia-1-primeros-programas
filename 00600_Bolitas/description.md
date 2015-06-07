Genial, ya entendiste cómo mover el cabezal del tablero usando la operación `move!` y las direcciones (`south`, `west`, etc). Vayamos a un paso más allá: las **bolitas**.

En cualquier celda de nuestro tablero podemos poner `bolitas`. Las hay de distintos colores:

 * Rojas (`red`)
 * Azules (`blue`)
 * Negras (`black`)
 * Y verdes (`green`)

Por ejemplo, este es un tablero con una bolita roja en `(1, 0)`, y una bolita negra en `(1, 1)`:

![2x2r10n11](https://raw.githubusercontent.com/mumuki/mumuki-fundamentos-ruby-stones-guia-1-primeros-programas/master/2x2r10n11.png)

El cabezal además de moverse también puede poner bolitas en la celda actual. Para eso contamos con operación `push!`, que le dice al cabezal que deposite una bolita del color dado:

```ruby
def main
  push! red
end
```

¡Probá este programa! Copiá el código en el editor, envialo, y verás lo que pasa al ejecutarlo sobre este tablero:

![3x3h](https://raw.githubusercontent.com/mumuki/mumuki-fundamentos-ruby-stones-guia-1-primeros-programas/master/3x3h.png)
