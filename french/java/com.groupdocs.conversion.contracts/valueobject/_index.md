---
title: "ValueObject"
second_title: "Référence API GroupDocs.Conversion pour Java"
description: "Classe d'objet valeur abstraite."
type: docs
weight: 15
url: /fr/java/com.groupdocs.conversion.contracts/valueobject/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable, java.io.Serializable
```
public abstract class ValueObject implements System.IEquatable<ValueObject>, Serializable
```

Classe d'objet valeur abstraite.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [ValueObject()](#ValueObject--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [equals(Object obj)](#equals-java.lang.Object-) | Détermine si deux instances d'objet sont égales. |
|
|  | [equals(ValueObject other)](#equals-com.groupdocs.conversion.contracts.ValueObject-) | Détermine si deux instances d'objet sont égales. |
|
|  | [hashCode()](#hashCode--) | Servir de fonction de hachage par défaut. |
|
|  | [op_Equality(ValueObject a, ValueObject b)](#op-Equality-com.groupdocs.conversion.contracts.ValueObject-com.groupdocs.conversion.contracts.ValueObject-) | Opérateur d'égalité. |
|
|  | [op_Inequality(ValueObject a, ValueObject b)](#op-Inequality-com.groupdocs.conversion.contracts.ValueObject-com.groupdocs.conversion.contracts.ValueObject-) | Opérateur d'inégalité. |
|
### ValueObject() {#ValueObject--}
```
public ValueObject()
```


### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Détermine si deux instances d'objet sont égales.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | obj | java.lang.Object | L'objet à comparer avec l'objet actuel. |
|

**Returns:**
boolean -  true  si l'objet spécifié est égal à l'objet actuel ; sinon,  false .

### equals(ValueObject other) {#equals-com.groupdocs.conversion.contracts.ValueObject-}
```
public final boolean equals(ValueObject other)
```


Détermine si deux instances d'objet sont égales.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | other | [ValueObject](../../com.groupdocs.conversion.contracts/valueobject) | L'objet à comparer avec l'objet actuel. |
|

**Returns:**
boolean -  true  si l'objet spécifié est égal à l'objet actuel ; sinon,  false .

### hashCode() {#hashCode--}
```
public int hashCode()
```


Servir de fonction de hachage par défaut.


**Returns:**
int - Un code de hachage pour l'objet actuel.

### op_Equality(ValueObject a, ValueObject b) {#op-Equality-com.groupdocs.conversion.contracts.ValueObject-com.groupdocs.conversion.contracts.ValueObject-}
```
public static boolean op_Equality(ValueObject a, ValueObject b)
```


Opérateur d'égalité.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | a | [ValueObject](../../com.groupdocs.conversion.contracts/valueobject) | Le premier objet |
|
|  | b | [ValueObject](../../com.groupdocs.conversion.contracts/valueobject) | Le deuxième objet |
|

**Returns:**
boolean -  true  si les objets sont égaux

### op_Inequality(ValueObject a, ValueObject b) {#op-Inequality-com.groupdocs.conversion.contracts.ValueObject-com.groupdocs.conversion.contracts.ValueObject-}
```
public static boolean op_Inequality(ValueObject a, ValueObject b)
```


Opérateur d'inégalité.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | a | [ValueObject](../../com.groupdocs.conversion.contracts/valueobject) | Le premier objet |
|
|  | b | [ValueObject](../../com.groupdocs.conversion.contracts/valueobject) | Le deuxième objet |
|

**Returns:**
boolean -  true  si les objets ne sont pas égaux

