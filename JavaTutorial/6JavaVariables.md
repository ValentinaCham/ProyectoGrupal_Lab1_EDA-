# Java Variables
## Variables
### Variables de Java

Las variables son contenedores para almacenar valores de datos.

En Java, existen diferentes tipos de variables, por ejemplo:

- ```String```- almacena texto, como "Hola". Los valores de cadena están entre comillas dobles
- ```int```- almacena enteros (números enteros), sin decimales, como 123 o -123
- ```float```- almacena números de coma flotante, con decimales, como 19.99 o -19.99
- ```char```- almacena caracteres individuales, como 'a' o 'B'. Los valores de char están entre comillas simples
- ```boolean```- almacena valores con dos estados: verdadero o falso

### Declarar (crear) variables

Para crear una variable, debe especificar el tipo y asignarle un valor:

```
type variableName = value;
```

Donde type es uno de los tipos de Java (como ```int``` o ```String```), y variableName es el nombre de la variable (como **x** o **name** ). El signo igual se utiliza para asignar valores a la variable.

Para crear una variable que deba almacenar texto, observe el siguiente ejemplo:

```
String name = "John";
System.out.println(name);
```

Para crear una variable que deba almacenar un número, observe el siguiente ejemplo:

```
int myNum = 15;
System.out.println(myNum);
```

También puede declarar una variable sin asignar el valor y asignar el valor más tarde:

```
int myNum;
myNum = 15;
System.out.println(myNum);
```

Tenga en cuenta que si asigna un nuevo valor a una variable existente, sobrescribirá el valor anterior:

```
int myNum = 15;
myNum = 20;  // myNum is now 20
System.out.println(myNum);
```

### Variables finales

Si no desea que otros (o usted mismo) sobrescriban los valores existentes, use la ```final``` palabra clave (esto declarará la variable como "final" o "constante", lo que significa que no se puede modificar y es de solo lectura):

```
final int myNum = 15;
myNum = 20;  // will generate an error: cannot assign a value to a final variable
```

### Otros tipos

Una demostración de cómo declarar variables de otros tipos:

```
int myNum = 5;
float myFloatNum = 5.99f;
char myLetter = 'D';
boolean myBool = true;
String myText = "Hello";
```

## Impresion de Variables

The ```println()``` method is often used to display variables.

Para combinar texto y una variable, use el ```+``` carácter:

```
String name = "John";
System.out.println("Hello " + name);
```

También puede usar el ```+``` carácter para agregar una variable a otra variable:

```
String firstName = "John ";
String lastName = "Doe";
String fullName = firstName + lastName;
System.out.println(fullName);
```

Para valores numéricos, el ```+``` carácter funciona como un operador ```int``` matemático (observe que aquí usamos variables (enteras)):

```
int x = 5;
int y = 6;
System.out.println(x + y); // Print the value of x + y
```

Del ejemplo anterior, puede esperar:

- x almacena el valor 5
- y almacena el valor 6
- Luego usamos el ```println()``` método para mostrar el valor de x + y, que es 11

## Declaración de Multiples Variables
### Declarar muchas variables

Para declarar más de una variable del **mismo tipo** , puede usar una lista separada por comas:

En lugar de escribir:

```
int x = 5;
int y = 6;
int z = 50;
System.out.println(x + y + z);
```

Simplemente puede escribir:

```
int x = 5, y = 6, z = 50;
System.out.println(x + y + z);
```

### Un valor para múltiples variables

También puede asignar el **mismo valor** a múltiples variables en una línea:

```
int x, y, z;
x = y = z = 50;
System.out.println(x + y + z);
```

## Identificadores

Todas **las variables** de Java deben **identificarse** con **nombres exclusivos** .

Estos nombres únicos se denominan **identificadores**.

Los identificadores pueden ser nombres cortos (como x e y) o nombres más descriptivos (edad, suma, volumen total).

**Nota:** Se recomienda utilizar nombres descriptivos para crear un código comprensible y mantenible:

```
// Good
int minutesPerHour = 60;

// OK, but not so easy to understand what m actually is
int m = 60;
```

Las reglas generales para nombrar variables son:

- Los nombres pueden contener letras, dígitos, guiones bajos y signos de dólar.
- Los nombres deben comenzar con una letra.
- Los nombres deben comenzar con una letra minúscula y no pueden contener espacios en blanco
- Los nombres también pueden comenzar con $ y _ (pero no lo usaremos en este tutorial)
- Los nombres distinguen entre mayúsculas y minúsculas ("myVar" y "myvar" son variables diferentes)
- Las palabras reservadas (como las palabras clave de Java, como into boolean) no se pueden usar como nombres
