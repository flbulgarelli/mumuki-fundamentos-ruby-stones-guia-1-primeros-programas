Para pensar:

Notá que estos dos programas hacen lo mismo:

```ruby
def main
  move! east
  move! east
  move! south
end
```

```ruby
def main
  move! east
  move! south
  move! east
end
```

Moraleja: ¡No hay una sóla forma de resolver un problema!

Y además, el orden, a veces, no es tan importante. Acompañanos a entender mejor esto.