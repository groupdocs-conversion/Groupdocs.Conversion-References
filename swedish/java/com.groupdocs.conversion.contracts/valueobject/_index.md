---
title: "ValueObject"
second_title: "GroupDocs.Conversion för Java API-referens"
description: "Abstrakt värdeobjektklass."
type: docs
weight: 15
url: /sv/java/com.groupdocs.conversion.contracts/valueobject/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable, java.io.Serializable
```
public abstract class ValueObject implements System.IEquatable<ValueObject>, Serializable
```

Abstrakt värdeobjektklass.

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [ValueObject()](#ValueObject--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [equals(Object obj)](#equals-java.lang.Object-) | Bestämmer om två objektinstanser är lika. |
|
|  | [equals(ValueObject other)](#equals-com.groupdocs.conversion.contracts.ValueObject-) | Bestämmer om två objektinstanser är lika. |
|
|  | [hashCode()](#hashCode--) | Fungerar som standardhashfunktion. |
|
|  | [op_Equality(ValueObject a, ValueObject b)](#op-Equality-com.groupdocs.conversion.contracts.ValueObject-com.groupdocs.conversion.contracts.ValueObject-) | Likhetsoperator. |
|
|  | [op_Inequality(ValueObject a, ValueObject b)](#op-Inequality-com.groupdocs.conversion.contracts.ValueObject-com.groupdocs.conversion.contracts.ValueObject-) | Olikhetsoperator. |
|
### ValueObject() {#ValueObject--}
```
public ValueObject()
```


### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bestämmer om två objektinstanser är lika.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | obj | java.lang.Object | Objektet att jämföra med det aktuella objektet. |
|

**Returns:**
boolean -  true  om det angivna objektet är lika med det aktuella objektet; annars  false .

### equals(ValueObject other) {#equals-com.groupdocs.conversion.contracts.ValueObject-}
```
public final boolean equals(ValueObject other)
```


Bestämmer om två objektinstanser är lika.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | other | [ValueObject](../../com.groupdocs.conversion.contracts/valueobject) | Objektet att jämföra med det aktuella objektet. |
|

**Returns:**
boolean -  true  om det angivna objektet är lika med det aktuella objektet; annars  false .

### hashCode() {#hashCode--}
```
public int hashCode()
```


Fungerar som standardhashfunktion.


**Returns:**
int - En hashkod för det aktuella objektet.

### op_Equality(ValueObject a, ValueObject b) {#op-Equality-com.groupdocs.conversion.contracts.ValueObject-com.groupdocs.conversion.contracts.ValueObject-}
```
public static boolean op_Equality(ValueObject a, ValueObject b)
```


Likhetsoperator.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | a | [ValueObject](../../com.groupdocs.conversion.contracts/valueobject) | Det första objektet |
|
|  | b | [ValueObject](../../com.groupdocs.conversion.contracts/valueobject) | Det andra objektet |
|

**Returns:**
boolean -  true  om objekten är lika

### op_Inequality(ValueObject a, ValueObject b) {#op-Inequality-com.groupdocs.conversion.contracts.ValueObject-com.groupdocs.conversion.contracts.ValueObject-}
```
public static boolean op_Inequality(ValueObject a, ValueObject b)
```


Olikhetsoperator.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | a | [ValueObject](../../com.groupdocs.conversion.contracts/valueobject) | Det första objektet |
|
|  | b | [ValueObject](../../com.groupdocs.conversion.contracts/valueobject) | Det andra objektet |
|

**Returns:**
boolean -  true  om objekten inte är lika

