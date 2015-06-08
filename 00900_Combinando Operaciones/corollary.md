Ahora que combinamos operaciones, la cosa se pone un poco mas complicada, porque hay que tener mas cuidado con el orden. Por ejemplo, estos dos programas no son equivalentes:


```ruby
def main
  push! red
  move! east
  push! black
  move! north
  push! green
end
```

y

```ruby
def main
  move! east
  push! red
  push! black
  move! north
  push! green
end
```

**¡Pensá por qué!**