# Learn Kotlin

- Setup : [Kotlin Jupyter](https://github.com/Kotlin/kotlin-jupyter)

## Hello, Jupyter
```kt
  class Greeter(private val name: String) {
      fun greet(): String {
          return "Hello, $name!"
      }
  }
```

```kt
  Greeter("Jupyter").greet() //Hello, Jupyter!
```
