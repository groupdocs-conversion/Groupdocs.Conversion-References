---
title: "ValueObject"
second_title: "Referencia de API de GroupDocs.Conversion para Node.js vía Java"
description: "Clase abstracta de objeto de valor."
type: docs
weight: 15
url: /es/nodejs-java/com.groupdocs.conversion.contracts/valueobject/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable, java.io.Serializable
```
public abstract class ValueObject implements System.IEquatable<ValueObject>, Serializable
```

Clase abstracta de objeto de valor.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [ValueObject()](#ValueObject--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Determina si dos instancias de objeto son iguales. |
| [equals(ValueObject other)](#equals-com.groupdocs.conversion.contracts.ValueObject-) | Determina si dos instancias de objeto son iguales. |
| [hashCode()](#hashCode--) | Sirve como la función hash predeterminada. |
| [op_Equality(ValueObject a, ValueObject b)](#op-Equality-com.groupdocs.conversion.contracts.ValueObject-com.groupdocs.conversion.contracts.ValueObject-) | Operador de igualdad. |
| [op_Inequality(ValueObject a, ValueObject b)](#op-Inequality-com.groupdocs.conversion.contracts.ValueObject-com.groupdocs.conversion.contracts.ValueObject-) | Operador de desigualdad. |
### ValueObject() {#ValueObject--}
```
public ValueObject()
```


### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determina si dos instancias de objeto son iguales.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | java.lang.Object | El objeto para comparar con el objeto actual. |

**Returns:**
boolean -  true  si el objeto especificado es igual al objeto actual; de lo contrario,  false .
### equals(ValueObject other) {#equals-com.groupdocs.conversion.contracts.ValueObject-}
```
public final boolean equals(ValueObject other)
```


Determina si dos instancias de objeto son iguales.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| other | [ValueObject](../../com.groupdocs.conversion.contracts/valueobject) | El objeto para comparar con el objeto actual. |

**Returns:**
boolean -  true  si el objeto especificado es igual al objeto actual; de lo contrario,  false .
### hashCode() {#hashCode--}
```
public int hashCode()
```


Sirve como la función hash predeterminada.

**Returns:**
int - Un código hash para el objeto actual.
### op_Equality(ValueObject a, ValueObject b) {#op-Equality-com.groupdocs.conversion.contracts.ValueObject-com.groupdocs.conversion.contracts.ValueObject-}
```
public static boolean op_Equality(ValueObject a, ValueObject b)
```


Operador de igualdad.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| a | [ValueObject](../../com.groupdocs.conversion.contracts/valueobject) | El primer objeto |
| b | [ValueObject](../../com.groupdocs.conversion.contracts/valueobject) | El segundo objeto |

**Returns:**
boolean -  true  si los objetos son iguales
### op_Inequality(ValueObject a, ValueObject b) {#op-Inequality-com.groupdocs.conversion.contracts.ValueObject-com.groupdocs.conversion.contracts.ValueObject-}
```
public static boolean op_Inequality(ValueObject a, ValueObject b)
```


Operador de desigualdad.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| a | [ValueObject](../../com.groupdocs.conversion.contracts/valueobject) | El primer objeto |
| b | [ValueObject](../../com.groupdocs.conversion.contracts/valueobject) | El segundo objeto |

**Returns:**
boolean -  true  si los objetos no son iguales
