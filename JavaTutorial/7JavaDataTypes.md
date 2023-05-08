# Tipos de Datos en Java
## Tipo de Datos
### Tipos de datos Java

Como se explicó en el capítulo anterior, una variable en Java debe ser un tipo de datos específico:

```
int myNum = 5;               // Integer (whole number)
float myFloatNum = 5.99f;    // Floating point number
char myLetter = 'D';         // Character
boolean myBool = true;       // Boolean
String myText = "Hello";     // String
```

Los tipos de datos se dividen en dos grupos:

- Tipos de datos primitivos: incluye ```byte```, ```short```, ```int```, ```long```, ```float```, ```double```, ```boolean``` y ```char```.
- ```String``` Tipos de datos no primitivos, como Arrays y Classes (aprenderá más sobre estos en un capítulo posterior)

### Tipos de datos primitivos

Un tipo de datos primitivo especifica el tamaño y el tipo de los valores de las variables y no tiene métodos adicionales.

Hay ocho tipos de datos primitivos en Java:

| Tipo de Dato | Tamaño | Descripción |
| --------- | --------- | --------- |
| byte | 1 byte | Almacena números enteros en un rango de -128 a 127. |
| short | 2 bytes | Almacena números enteros en un rango de -32,768 a 32,767. |
| int | 4 bytes | Almacena números enteros en un rango de -2,147,483,648 a 2,147,483,647. |
| long | 8 bytes | Almacena números enteros en un rango de -9,223,372,036,854,775,808 a 9,223,372,036,854,775,807. |
| float | 4 bytes | Almacena números fraccionarios con una precisión suficiente para almacenar de 6 a 7 dígitos decimales. |
| double | 8 bytes | Almacena números fraccionarios con una precisión suficiente para almacenar 15 dígitos decimales. |
| boolean | 1 bit | Almacena valores verdadero o falso |
| char | 2 bytes | Almacena un solo carácter/letra o valores ASCII. |

## Números

### Números

Los tipos de números primitivos se dividen en dos grupos:

**Los tipos enteros** almacenan números enteros, positivos o negativos (como 123 o -456), sin decimales. Los tipos válidos son ```byte```, y . El tipo que debe usar depende del valor numérico. ```short int long```

**Los tipos de punto flotante** representan números con una parte fraccionaria, que contienen uno o más decimales. Hay dos tipos: ```float``` y ```double```.

### Tipos de enteros

#### Byte

El ```byte``` tipo de datos puede almacenar números enteros de -128 a 127. Esto se puede usar en lugar de ```int``` u otros tipos de enteros para ahorrar memoria cuando está seguro de que el valor estará entre -128 y 127:

```
byte myNum = 100;
System.out.println(myNum);
```

#### Short

El ```short``` tipo de datos puede almacenar números enteros desde -32768 hasta 32767:

```
short myNum = 5000;
System.out.println(myNum);
```

#### Int

El ```int``` tipo de datos puede almacenar números enteros desde -2147483648 hasta 2147483647. En general, y en nuestro tutorial, el ```int``` tipo de datos es el tipo de datos preferido cuando creamos variables con un valor numérico.

```
int myNum = 100000;
System.out.println(myNum);
```

#### Long

El ```long``` tipo de datos puede almacenar números enteros desde -9223372036854775808 hasta 9223372036854775807. Esto se usa cuando int no es lo suficientemente grande para almacenar el valor. Tenga en cuenta que debe terminar el valor con una "L":

### Tipos de Punto Flotante

Debe usar un tipo de punto flotante cada vez que necesite un número con un decimal, como 9,99 o 3,14515.

Los tipos de datos ```float``` y ```double``` pueden almacenar números fraccionarios. Tenga en cuenta que debe terminar el valor con una "f" para flotantes y una "d" para dobles:

```
float myNum = 5.75f;
System.out.println(myNum);
```

```
double myNum = 19.99d;
System.out.println(myNum);
```

#### Números Cientificos

Un número de punto flotante también puede ser un número científico con una "e" para indicar la potencia de 10:

```
float f1 = 35e3f;
double d1 = 12E4d;
System.out.println(f1);
System.out.println(d1);
```

## Booleanos
## Caracteres
## Datos No-Primitivos
