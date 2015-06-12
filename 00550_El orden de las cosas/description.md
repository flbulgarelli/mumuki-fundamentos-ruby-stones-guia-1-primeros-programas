Cuando trabajamos con estos tableros, hacemos las cosas en un cierto orden. Por ejemplo, dado este programa

```ruby
def main
  move! north
  move! east
end
```

una posible forma de leer esto (llamada **operacional**) es como lo haría una máquina, en orden, de arriba hacia abajo:

1. primero se mueve al norte: `move! nort`
1. luego se mueve al este: `move! east`

Y de hecho **se ejecuta de esa forma**. Esto es _cómo_ lo hace.

Sin embargo, los humanos somos mejores hablando del todo, del resultado final: el objetivo del programa, es decir, _qué_ es lo que hace. Y si lo pensamos así (**denotacionalmente**) lo que hace es: **moverse al noreste**.

Por eso hay varias formas de resolver un mismo problema: podemos escribir varios programas que hagan lo mismo (el _qué_), pero que lo hagan de forma diferente (el _cómo_).

Veamos si entendiste esto: intentá escribí otro programa que haga lo mismo que el de arriba (mover hacia el noreste), pero lo haga de otra forma.
