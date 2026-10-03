---
title: "Enumeration"
second_title: "GroupDocs.Conversion för Java API-referens"
description: "Generisk uppräkningsklass."
type: docs
weight: 11
url: /sv/java/com.groupdocs.conversion.contracts/enumeration/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Comparable, java.io.Serializable, com.aspose.ms.System.IEquatable
```
public abstract class Enumeration implements Comparable, Serializable, System.IEquatable<Enumeration>
```

Generisk uppräkningsklass.


TKey
:

## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [toString()](#toString--) | Returnerar en sträng som representerar det aktuella objektet. |
|
|  | [<T>getAll(Class<T> typeOfT)](#-T-getAll-java.lang.Class-T--) | Returnerar alla enumerationsvärden. |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Bestämmer om två objektinstanser är lika. |
|
|  | [equals(Enumeration other)](#equals-com.groupdocs.conversion.contracts.Enumeration-) | Bestämmer om två objektinstanser är lika. |
|
|  | [hashCode()](#hashCode--) | Fungerar som standardhashfunktion. |
|
|  | [<T>fromValue(Class<T> typeOfT, String value)](#-T-fromValue-java.lang.Class-T--java.lang.String-) | Returnerar objekt efter nyckel. |
|
|  | [<T>fromDisplayName(Class<T> typeOfT, String displayName)](#-T-fromDisplayName-java.lang.Class-T--java.lang.String-) | Returnerar objekt efter visningsnamn. |
|
|  | [compareTo(Object obj)](#compareTo-java.lang.Object-) | Jämför aktuellt objekt med annat. |
|
|  | [op_Equality(Enumeration left, Enumeration right)](#op-Equality-com.groupdocs.conversion.contracts.Enumeration-com.groupdocs.conversion.contracts.Enumeration-) | Likhetsoperator. |
|
|  | [op_Inequality(Enumeration left, Enumeration right)](#op-Inequality-com.groupdocs.conversion.contracts.Enumeration-com.groupdocs.conversion.contracts.Enumeration-) | Olikhetsoperator. |
|
### toString() {#toString--}
```
public String toString()
```


Returnerar en sträng som representerar det aktuella objektet.


**Returns:**
java.lang.String - Strängrepresentation

### <T>getAll(Class<T> typeOfT) {#-T-getAll-java.lang.Class-T--}
```
public static List <T>getAll(Class<T> typeOfT)
```


Returnerar alla enumerationsvärden.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |

**Returns:**
java.util.List - Uppräkning av den angivna typen


T
: Enumererad objekttyp.

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

### equals(Enumeration other) {#equals-com.groupdocs.conversion.contracts.Enumeration-}
```
public boolean equals(Enumeration other)
```


Bestämmer om två objektinstanser är lika.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | other | [Enumeration](../../com.groupdocs.conversion.contracts/enumeration) | Objektet att jämföra med det aktuella objektet. |
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

### <T>fromValue(Class<T> typeOfT, String value) {#-T-fromValue-java.lang.Class-T--java.lang.String-}
```
public static T <T>fromValue(Class<T> typeOfT, String value)
```


Returnerar objekt efter nyckel.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |
|  | värde | java.lang.String | Värdet |
|

**Returns:**
T - Objektet

### <T>fromDisplayName(Class<T> typeOfT, String displayName) {#-T-fromDisplayName-java.lang.Class-T--java.lang.String-}
```
public static T <T>fromDisplayName(Class<T> typeOfT, String displayName)
```


Returnerar objekt efter visningsnamn.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |
|  | displayName | java.lang.String | Visningsnamnet |
|

**Returns:**
T - Objektet

### compareTo(Object obj) {#compareTo-java.lang.Object-}
```
public final int compareTo(Object obj)
```


Jämför aktuellt objekt med annat.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | obj | java.lang.Object | Det andra objektet |
|

**Returns:**
int - noll om lika

### op_Equality(Enumeration left, Enumeration right) {#op-Equality-com.groupdocs.conversion.contracts.Enumeration-com.groupdocs.conversion.contracts.Enumeration-}
```
public static boolean op_Equality(Enumeration left, Enumeration right)
```


Likhetsoperator.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | left | [Enumeration](../../com.groupdocs.conversion.contracts/enumeration) | Det första objektet |
|
|  | right | [Enumeration](../../com.groupdocs.conversion.contracts/enumeration) | Det andra objektet |
|

**Returns:**
boolean -  true  om objekten är lika

### op_Inequality(Enumeration left, Enumeration right) {#op-Inequality-com.groupdocs.conversion.contracts.Enumeration-com.groupdocs.conversion.contracts.Enumeration-}
```
public static boolean op_Inequality(Enumeration left, Enumeration right)
```


Olikhetsoperator.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | left | [Enumeration](../../com.groupdocs.conversion.contracts/enumeration) | Det första objektet |
|
|  | right | [Enumeration](../../com.groupdocs.conversion.contracts/enumeration) | Det andra objektet |
|

**Returns:**
boolean -  true  om objekten inte är lika

