---
title: "ValueObject"
second_title: "GroupDocs.Conversion for Node.js via Java API-referentie"
description: "Abstracte waarde‑objectklasse."
type: docs
weight: 15
url: /nl/nodejs-java/com.groupdocs.conversion.contracts/valueobject/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable, java.io.Serializable
```
public abstract class ValueObject implements System.IEquatable<ValueObject>, Serializable
```

Abstracte waarde‑objectklasse.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [ValueObject()](#ValueObject--) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Bepaalt of twee objectinstanties gelijk zijn. |
| [equals(ValueObject other)](#equals-com.groupdocs.conversion.contracts.ValueObject-) | Bepaalt of twee objectinstanties gelijk zijn. |
| [hashCode()](#hashCode--) | Dient als de standaard hash-functie. |
| [op_Equality(ValueObject a, ValueObject b)](#op-Equality-com.groupdocs.conversion.contracts.ValueObject-com.groupdocs.conversion.contracts.ValueObject-) | Gelijkheidsoperator. |
| [op_Inequality(ValueObject a, ValueObject b)](#op-Inequality-com.groupdocs.conversion.contracts.ValueObject-com.groupdocs.conversion.contracts.ValueObject-) | Ongelijkheidsoperator. |
### ValueObject() {#ValueObject--}
```
public ValueObject()
```


### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bepaalt of twee objectinstanties gelijk zijn.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | java.lang.Object | Het object om te vergelijken met het huidige object. |

**Returns:**
boolean -  true  als het opgegeven object gelijk is aan het huidige object; anders,  false .
### equals(ValueObject other) {#equals-com.groupdocs.conversion.contracts.ValueObject-}
```
public final boolean equals(ValueObject other)
```


Bepaalt of twee objectinstanties gelijk zijn.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| other | [ValueObject](../../com.groupdocs.conversion.contracts/valueobject) | Het object om te vergelijken met het huidige object. |

**Returns:**
boolean -  true  als het opgegeven object gelijk is aan het huidige object; anders,  false .
### hashCode() {#hashCode--}
```
public int hashCode()
```


Dient als de standaard hash-functie.

**Returns:**
int - Een hashcode voor het huidige object.
### op_Equality(ValueObject a, ValueObject b) {#op-Equality-com.groupdocs.conversion.contracts.ValueObject-com.groupdocs.conversion.contracts.ValueObject-}
```
public static boolean op_Equality(ValueObject a, ValueObject b)
```


Gelijkheidsoperator.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| a | [ValueObject](../../com.groupdocs.conversion.contracts/valueobject) | Het eerste object |
| b | [ValueObject](../../com.groupdocs.conversion.contracts/valueobject) | Het tweede object |

**Returns:**
boolean -  true  als objecten gelijk zijn
### op_Inequality(ValueObject a, ValueObject b) {#op-Inequality-com.groupdocs.conversion.contracts.ValueObject-com.groupdocs.conversion.contracts.ValueObject-}
```
public static boolean op_Inequality(ValueObject a, ValueObject b)
```


Ongelijkheidsoperator.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| a | [ValueObject](../../com.groupdocs.conversion.contracts/valueobject) | Het eerste object |
| b | [ValueObject](../../com.groupdocs.conversion.contracts/valueobject) | Het tweede object |

**Returns:**
boolean -  true  als objecten niet gelijk zijn
