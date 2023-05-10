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
