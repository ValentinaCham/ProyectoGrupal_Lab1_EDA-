# Java Gettind Started
## Instalación de Java
Para poder comprondar la instalación se debe usar el siguiente comando:

```
C:\Users\Your Name>java -version
```

Si java está instalado, dependiendo de la versión, deberias ver algo parecido a:

```
java version "11.0.1" 2018-10-16 LTS
Java(TM) SE Runtime Environment 18.9 (build 11.0.1+13-LTS)
Java HotSpot(TM) 64-Bit Server VM 18.9 (build 11.0.1+13-LTS, mixed mode)
```

En la caso de no tenerlo en la computadora puedes instalarlo por medio de [Oracle](https://www.w3schools.com/java/java_getstarted.asp)
## Inicio Rápido
En Java cada aplicación comienza con un nombre de clase y esa clase debe coincidir con el nombre del archivo.
El ejemplo dado es de un archivo que se debe llamar Main.java, puedes crearlo en Bloc de Notas y escribir el siguiente código.

```
public class Main {
  public static void main(String[] args) {
    System.out.println("Hello World");
  }
}
```

Para poder compilar el código se debe ir a la ubicación del archivo y escribir:

```
C:\Users\Your Name>javac Main.java
```

Si no hay errores en el código, el símbolo del sistema lo llevará a la sigueitne linea. Ahora escribe:

```
C:\Users\Your Name>java Main
```

La salida debe ser:

```
Hello World
``` 
