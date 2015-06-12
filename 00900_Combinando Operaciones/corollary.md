Ahora que combinamos operaciones, la cosa se pone un poco mas complicada, porque hay que tener **mas cuidado con el orden**.

Por ejemplo, mirá el programa que escribiste:

```ruby
def main
  push! red
  move! east
  push! black
end
```

Operacionalmente:

1. pone una roja
1. luego se mueve al este
1. luego pone una negra

Es decir: pone una roja el la posicion inicial, y una negra al este

Y ahora mirá este otro:

```ruby
def main
  move! east
  push! red
  push! black
end
```

Operacionalmente:

1. se mueve al este
1. luego pone una roja
1. luego pone una negra

Es decir: pone una roja y una negra al este de la posición inicial.

Moraleja: ¡no hacen lo mismo! Cambiar el orden nos cambió el _qué_.

