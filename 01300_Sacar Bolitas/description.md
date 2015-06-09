Veamos otra operacion: de la misma forma que hay un "sacar bolita" (`push!`), tenemos un "quitar bolita" (`pop!`), que saca exactamente una bolita del color dado.

Por ejemplo, el siguiente programa saca dos bolitas de la posición inicial.

```ruby
def main
  pop! red
  pop! red
end
```

Cada vez que hacemos un `pop!`, tenemos más cuidado que con `push!`, porque si no había al menos una bolita del color dado en la celda actual, ¡se rompe el programa!. Lo cual si bien no es la muerte de nadie, nos impide concretar nuestra tarea.

Sabiendo esto, escribir un programa que elimine la bolita roja las bolita roja de este tablero.

![2x2r10n11](https://raw.githubusercontent.com/mumuki/mumuki-fundamentos-ruby-stones-guia-1-primeros-programas/master/2x2r10n11.png)



