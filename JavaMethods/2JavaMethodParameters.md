# Parámetros del método Java
## Parámetros y Argumentos

La información se puede pasar a los métodos como parámetro. Los parámetros actúan como variables dentro del método.

Los parámetros se especifican después del nombre del método, entre paréntesis. Puede agregar tantos parámetros como desee, simplemente sepárelos con una coma.

El siguiente ejemplo tiene un método que toma un **fname** ```String``` llamado como parámetro. Cuando se llama al método, pasamos un nombre, que se usa dentro del método para imprimir el nombre completo:

```
public class Main {
  static void myMethod(String fname) {
    System.out.println(fname + " Refsnes");
  }

  public static void main(String[] args) {
    myMethod("Liam");
    myMethod("Jenny");
    myMethod("Anja");
  }
}
// Liam Refsnes
// Jenny Refsnes
// Anja Refsnes
```

Cuando se pasa un **parámetro** al método, se le llama argumento . Entonces, del ejemplo anterior: ```fname```es un **parámetro** , mientras que ```Liam```, ```Jenny``` y ```Anja``` son **argumentos**.

## Multiples Parametros

Puede tener tantos parámetros como desee:

```
public class Main {
  static void myMethod(String fname, int age) {
    System.out.println(fname + " is " + age);
  }

  public static void main(String[] args) {
    myMethod("Liam", 5);
    myMethod("Jenny", 8);
    myMethod("Anja", 31);
  }
}

// Liam is 5
// Jenny is 8
// Anja is 31
```

Tenga en cuenta que cuando trabaja con varios parámetros, la llamada al método debe tener la misma cantidad de argumentos que parámetros, y los argumentos deben pasarse en el mismo orden.

## Valores devueltos

La ```void``` palabra clave, utilizada en los ejemplos anteriores, indica que el método no debe devolver un valor. Si desea que el método devuelva un valor, puede usar un tipo de datos primitivo (como ```int```, ```char```, etc.) en lugar de ```void``` y usar la ```return``` palabra clave dentro del método:

```
public class Main {
  static int myMethod(int x) {
    return 5 + x;
  }

  public static void main(String[] args) {
    System.out.println(myMethod(3));
  }
}
// Outputs 8 (5 + 3)
```

Este ejemplo devuelve la suma de los **dos parámetros** de un método :

```
public class Main {
  static int myMethod(int x, int y) {
    return x + y;
  }

  public static void main(String[] args) {
    System.out.println(myMethod(5, 3));
  }
}
// Outputs 8 (5 + 3)
```

También puede almacenar el resultado en una variable (recomendado, ya que es más fácil de leer y mantener):

```
public class Main {
  static int myMethod(int x, int y) {
    return x + y;
  }

  public static void main(String[] args) {
    int z = myMethod(5, 3);
    System.out.println(z);
  }
}
// Outputs 8 (5 + 3)
```

## Un método con If...Else

Es común usar ```if...else``` sentencias dentro de métodos:

```
public class Main {

  // Create a checkAge() method with an integer variable called age
  static void checkAge(int age) {

    // If age is less than 18, print "access denied"
    if (age < 18) {
      System.out.println("Access denied - You are not old enough!");

    // If age is greater than, or equal to, 18, print "access granted"
    } else {
      System.out.println("Access granted - You are old enough!");
    }

  }

  public static void main(String[] args) {
    checkAge(20); // Call the checkAge method and pass along an age of 20
  }
}

// Outputs "Access granted - You are old enough!"

```
