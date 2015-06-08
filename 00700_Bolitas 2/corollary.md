Notá que en este problema, si cambiamos el orden en que _llamamos_ (usamos a)`push!`, el resultado no cambia: siempre nos terminará quedando un tablero con tres bolitas rojas, una azul y una verde.

Por ejemplo, los siguientes dos programas también resuelven este mismo problema:

```ruby
def main
  push! red
  push! red
  push! red
  push! green
  push! blue
end
```

```ruby
def main
  push! red
  push! blue
  push! red
  push! green
  push! red
end
```