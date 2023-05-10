# Métodos de Java

Un método es un bloque de código que solo se ejecuta cuando se le llama.
Puede pasar datos, conocidos como parámetros, a un método.
Los métodos se utilizan para realizar ciertas acciones y también se conocen como funciones .
¿Por qué usar métodos? Para reutilizar el código: defina el código una vez y utilícelo muchas veces.

## Crear un método

Un método debe declararse dentro de una clase. Se define con el nombre del método, seguido de paréntesis () . Java proporciona algunos métodos predefinidos, como ```System.out.println()```, pero también puede crear sus propios métodos para realizar ciertas acciones:

```
public class Main {
  static void myMethod() {
    // code to be executed
  }
}
```

Ejemplo explicado
- ```myMethod()``` es el nombre del método
- ```static``` significa que el método pertenece a la clase Main y no a un objeto de la clase Main. Aprenderá más sobre objetos y cómo acceder a métodos a través de objetos más adelante en este tutorial.
- ```void``` significa que este método no tiene un valor de retorno. Aprenderá más sobre los valores devueltos más adelante en este capítulo.

## Llamar a un método

Para llamar a un método en Java, escriba el nombre del método seguido de dos paréntesis () y un punto y coma ;

En el siguiente ejemplo, ```myMethod()``` se utiliza para imprimir un texto (la acción), cuando se llama:

```
public class Main {
  static void myMethod() {
    System.out.println("I just got executed!");
  }

  public static void main(String[] args) {
    myMethod();
  }
}
```

Un método también se puede llamar varias veces:

```
public class Main {
  static void myMethod() {
    System.out.println("I just got executed!");
  }

  public static void main(String[] args) {
    myMethod();
    myMethod();
    myMethod();
  }
}

// I just got executed!
// I just got executed!
// I just got executed!
```
