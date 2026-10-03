---
title: "Énumération"
second_title: "Référence API GroupDocs.Conversion pour Java"
description: "Classe d'énumération générique."
type: docs
weight: 11
url: /fr/java/com.groupdocs.conversion.contracts/enumeration/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Comparable, java.io.Serializable, com.aspose.ms.System.IEquatable
```
public abstract class Enumeration implements Comparable, Serializable, System.IEquatable<Enumeration>
```

Classe d'énumération générique.


TKey
:

## Méthodes

| Méthode | Description |
| --- | --- |
|  | [toString()](#toString--) | Renvoie une chaîne qui représente l'objet actuel. |
|
|  | [<T>getAll(Class<T> typeOfT)](#-T-getAll-java.lang.Class-T--) | Renvoie toutes les valeurs d'énumération. |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Détermine si deux instances d'objet sont égales. |
|
|  | [equals(Enumeration other)](#equals-com.groupdocs.conversion.contracts.Enumeration-) | Détermine si deux instances d'objet sont égales. |
|
|  | [hashCode()](#hashCode--) | Servir de fonction de hachage par défaut. |
|
|  | [<T>fromValue(Class<T> typeOfT, String value)](#-T-fromValue-java.lang.Class-T--java.lang.String-) | Renvoie l'objet par clé. |
|
|  | [<T>fromDisplayName(Class<T> typeOfT, String displayName)](#-T-fromDisplayName-java.lang.Class-T--java.lang.String-) | Renvoie l'objet par nom d'affichage. |
|
|  | [compareTo(Object obj)](#compareTo-java.lang.Object-) | Compare l'objet actuel à un autre. |
|
|  | [op_Equality(Enumeration left, Enumeration right)](#op-Equality-com.groupdocs.conversion.contracts.Enumeration-com.groupdocs.conversion.contracts.Enumeration-) | Opérateur d'égalité. |
|
|  | [op_Inequality(Enumeration left, Enumeration right)](#op-Inequality-com.groupdocs.conversion.contracts.Enumeration-com.groupdocs.conversion.contracts.Enumeration-) | Opérateur d'inégalité. |
|
### toString() {#toString--}
```
public String toString()
```


Renvoie une chaîne qui représente l'objet actuel.


**Returns:**
java.lang.String - représentation sous forme de chaîne

### <T>getAll(Class<T> typeOfT) {#-T-getAll-java.lang.Class-T--}
```
public static List <T>getAll(Class<T> typeOfT)
```


Renvoie toutes les valeurs d'énumération.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |

**Returns:**
java.util.List - énumérable du type fourni


T
: Type d'objet énuméré.

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

### equals(Enumeration other) {#equals-com.groupdocs.conversion.contracts.Enumeration-}
```
public boolean equals(Enumeration other)
```


Détermine si deux instances d'objet sont égales.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | other | [Enumeration](../../com.groupdocs.conversion.contracts/enumeration) | L'objet à comparer avec l'objet actuel. |
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

### <T>fromValue(Class<T> typeOfT, String value) {#-T-fromValue-java.lang.Class-T--java.lang.String-}
```
public static T <T>fromValue(Class<T> typeOfT, String value)
```


Renvoie l'objet par clé.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |
|  | valeur | java.lang.String | La valeur |
|

**Returns:**
T - L'objet

### <T>fromDisplayName(Class<T> typeOfT, String displayName) {#-T-fromDisplayName-java.lang.Class-T--java.lang.String-}
```
public static T <T>fromDisplayName(Class<T> typeOfT, String displayName)
```


Renvoie l'objet par nom d'affichage.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |
|  | displayName | java.lang.String | Le nom d'affichage |
|

**Returns:**
T - L'objet

### compareTo(Object obj) {#compareTo-java.lang.Object-}
```
public final int compareTo(Object obj)
```


Compare l'objet actuel à un autre.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | obj | java.lang.Object | L'autre objet |
|

**Returns:**
int - zéro si égal

### op_Equality(Enumeration left, Enumeration right) {#op-Equality-com.groupdocs.conversion.contracts.Enumeration-com.groupdocs.conversion.contracts.Enumeration-}
```
public static boolean op_Equality(Enumeration left, Enumeration right)
```


Opérateur d'égalité.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | left | [Enumeration](../../com.groupdocs.conversion.contracts/enumeration) | Le premier objet |
|
|  | right | [Enumeration](../../com.groupdocs.conversion.contracts/enumeration) | Le deuxième objet |
|

**Returns:**
boolean -  true  si les objets sont égaux

### op_Inequality(Enumeration left, Enumeration right) {#op-Inequality-com.groupdocs.conversion.contracts.Enumeration-com.groupdocs.conversion.contracts.Enumeration-}
```
public static boolean op_Inequality(Enumeration left, Enumeration right)
```


Opérateur d'inégalité.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | left | [Enumeration](../../com.groupdocs.conversion.contracts/enumeration) | Le premier objet |
|
|  | right | [Enumeration](../../com.groupdocs.conversion.contracts/enumeration) | Le deuxième objet |
|

**Returns:**
boolean -  true  si les objets ne sont pas égaux

