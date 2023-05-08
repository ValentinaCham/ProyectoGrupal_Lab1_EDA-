# Salida/impresión de Java
## Impresion de Texto
### Imprimir texto
En el capítulo anterior, aprendió que puede usar el ```println()``` método para generar valores o imprimir texto en Java:

```
System.out.println("Hello World!");
```

Puede agregar tantos ```println()``` métodos como desee. Tenga en cuenta que agregará una nueva línea para cada método:

```
System.out.println("Hello World!");
System.out.println("I am learning Java.");
System.out.println("It is awesome!");
```

### Doble comillas

Cuando trabaja con texto, debe estar entre comillas dobles ```""```.

Si olvida las comillas dobles, se produce un error:

```
System.out.println("This sentence will work!");

System.out.println(This sentence will produce an error);
```

### El método ```print()```

También hay un ```print()``` método, que es similar a ```println()```.

La única diferencia es que no inserta una nueva línea al final de la salida:

```
System.out.print("Hello World! ");
System.out.print("I will print on the same line.");
```

## Números de salida de Java

### Imprimir números
También puede usar el ```println()``` método para imprimir números.

Sin embargo, a diferencia del texto, no ponemos números entre comillas dobles:

```
System.out.println(3);
System.out.println(358);
System.out.println(50000);
```

También puede realizar cálculos matemáticos dentro del ```println()```método:

```
System.out.println(3 + 3);

System.out.println(2 * 5);
```
