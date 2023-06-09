# Java Syntax
## Sintaxis de Java
En el capítulo anterior, creamos un archivo Java llamado **Main.java** y usamos el siguiente código para imprimir "Hello World" en la pantalla:

```
public class Main {
  public static void main(String[] args) {
    System.out.println("Hello World");
  }
}
```

En Java, cada línea de código debe estar dentro de una clase que comienza con una letra mayúscula. Es importante recordar que Java distingue entre mayúsculas y minúsculas en los nombres de las clases y archivos. Por lo tanto, el nombre del archivo Java debe coincidir con el nombre de la clase y tener la extensión **.java** . La salida deberia ser:

```
Hello World
```

## El método principal

El ```main()``` método es obligatorio y lo verá en todos los programas de Java:

```
public static void main(String[] args)
```

El método main() es donde se ejecuta el código de un programa Java, y su clase debe tener el mismo nombre que el archivo.

## Sistema.salida.println()

Dentro del ```main()``` método, podemos usar el ```println()``` método para imprimir una línea de texto en la pantalla:

```
public static void main(String[] args) {
  System.out.println("Hello World");
}
```
