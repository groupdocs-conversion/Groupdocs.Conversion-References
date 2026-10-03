---
title: "Enumeración"
second_title: "Referencia de API de GroupDocs.Conversion for Java"
description: "Clase de enumeración genérica."
type: docs
weight: 11
url: /es/java/com.groupdocs.conversion.contracts/enumeration/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Comparable, java.io.Serializable, com.aspose.ms.System.IEquatable
```
public abstract class Enumeration implements Comparable, Serializable, System.IEquatable<Enumeration>
```

Clase de enumeración genérica.


TKey
:

## Métodos

| Método | Descripción |
| --- | --- |
|  | [toString()](#toString--) | Devuelve una cadena que representa el objeto actual. |
|
|  | [<T>getAll(Class<T> typeOfT)](#-T-getAll-java.lang.Class-T--) | Devuelve todos los valores de enumeración. |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Determina si dos instancias de objeto son iguales. |
|
|  | [equals(Enumeration other)](#equals-com.groupdocs.conversion.contracts.Enumeration-) | Determina si dos instancias de objeto son iguales. |
|
|  | [hashCode()](#hashCode--) | Sirve como la función hash predeterminada. |
|
|  | [<T>fromValue(Class<T> typeOfT, String value)](#-T-fromValue-java.lang.Class-T--java.lang.String-) | Devuelve el objeto por clave. |
|
|  | [<T>fromDisplayName(Class<T> typeOfT, String displayName)](#-T-fromDisplayName-java.lang.Class-T--java.lang.String-) | Devuelve el objeto por nombre para mostrar. |
|
|  | [compareTo(Object obj)](#compareTo-java.lang.Object-) | Compara el objeto actual con otro. |
|
|  | [op_Equality(Enumeration left, Enumeration right)](#op-Equality-com.groupdocs.conversion.contracts.Enumeration-com.groupdocs.conversion.contracts.Enumeration-) | Operador de igualdad. |
|
|  | [op_Inequality(Enumeration left, Enumeration right)](#op-Inequality-com.groupdocs.conversion.contracts.Enumeration-com.groupdocs.conversion.contracts.Enumeration-) | Operador de desigualdad. |
|
### toString() {#toString--}
```
public String toString()
```


Devuelve una cadena que representa el objeto actual.


**Returns:**
java.lang.String - representación de cadena

### <T>getAll(Class<T> typeOfT) {#-T-getAll-java.lang.Class-T--}
```
public static List <T>getAll(Class<T> typeOfT)
```


Devuelve todos los valores de enumeración.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |

**Returns:**
java.util.List - Enumerable del tipo proporcionado


T
: Tipo de objeto enumerado.

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determina si dos instancias de objeto son iguales.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | obj | java.lang.Object | El objeto para comparar con el objeto actual. |
|

**Returns:**
boolean -  true  si el objeto especificado es igual al objeto actual; de lo contrario,  false .

### equals(Enumeration other) {#equals-com.groupdocs.conversion.contracts.Enumeration-}
```
public boolean equals(Enumeration other)
```


Determina si dos instancias de objeto son iguales.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | other | [Enumeration](../../com.groupdocs.conversion.contracts/enumeration) | El objeto para comparar con el objeto actual. |
|

**Returns:**
boolean -  true  si el objeto especificado es igual al objeto actual; de lo contrario,  false .

### hashCode() {#hashCode--}
```
public int hashCode()
```


Sirve como la función hash predeterminada.


**Returns:**
int - Un código hash para el objeto actual.

### <T>fromValue(Class<T> typeOfT, String value) {#-T-fromValue-java.lang.Class-T--java.lang.String-}
```
public static T <T>fromValue(Class<T> typeOfT, String value)
```


Devuelve el objeto por clave.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |
|  | valor | java.lang.String | El valor |
|

**Returns:**
T - El objeto

### <T>fromDisplayName(Class<T> typeOfT, String displayName) {#-T-fromDisplayName-java.lang.Class-T--java.lang.String-}
```
public static T <T>fromDisplayName(Class<T> typeOfT, String displayName)
```


Devuelve el objeto por nombre para mostrar.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |
|  | displayName | java.lang.String | El nombre para mostrar |
|

**Returns:**
T - El objeto

### compareTo(Object obj) {#compareTo-java.lang.Object-}
```
public final int compareTo(Object obj)
```


Compara el objeto actual con otro.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | obj | java.lang.Object | El otro objeto |
|

**Returns:**
int - cero si es igual

### op_Equality(Enumeration left, Enumeration right) {#op-Equality-com.groupdocs.conversion.contracts.Enumeration-com.groupdocs.conversion.contracts.Enumeration-}
```
public static boolean op_Equality(Enumeration left, Enumeration right)
```


Operador de igualdad.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | left | [Enumeration](../../com.groupdocs.conversion.contracts/enumeration) | El primer objeto |
|
|  | right | [Enumeration](../../com.groupdocs.conversion.contracts/enumeration) | El segundo objeto |
|

**Returns:**
boolean -  true  si los objetos son iguales

### op_Inequality(Enumeration left, Enumeration right) {#op-Inequality-com.groupdocs.conversion.contracts.Enumeration-com.groupdocs.conversion.contracts.Enumeration-}
```
public static boolean op_Inequality(Enumeration left, Enumeration right)
```


Operador de desigualdad.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | left | [Enumeration](../../com.groupdocs.conversion.contracts/enumeration) | El primer objeto |
|
|  | right | [Enumeration](../../com.groupdocs.conversion.contracts/enumeration) | El segundo objeto |
|

**Returns:**
boolean -  true  si los objetos no son iguales

