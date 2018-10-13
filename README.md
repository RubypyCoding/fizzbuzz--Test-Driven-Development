## Ejercicio - FIZZBUZZ TDD

Crea el spec para el método `fizzbuzz` que cumpla las siguientes restricciones:

- Retorna `"FizzBuzz"` para múltiplos de 3 y 5
- Retorna `"Fizz"` para múltiplos de 3
- Retorna `"Buzz"` para múltiplos de 5
- Retorna El mismo número para cualquier otro valor.

Un ejemplo del requerimiento del programa son las siguientes pruebas:


```ruby
# Pruebas

p fizzbuzz(3, 5) == ["Fizz", 4, "Buzz"]
p fizzbuzz(10, 15) == ["Buzz", 11, "Fizz", 13, 14, "FizzBuzz"]
```