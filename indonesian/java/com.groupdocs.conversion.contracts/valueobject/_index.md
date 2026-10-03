---
title: "ValueObject"
second_title: "Referensi API GroupDocs.Conversion untuk Java"
description: "Kelas objek nilai abstrak."
type: docs
weight: 15
url: /id/java/com.groupdocs.conversion.contracts/valueobject/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable, java.io.Serializable
```
public abstract class ValueObject implements System.IEquatable<ValueObject>, Serializable
```

Kelas objek nilai abstrak.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [ValueObject()](#ValueObject--) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [equals(Object obj)](#equals-java.lang.Object-) | Menentukan apakah dua instance objek sama. |
|
|  | [equals(ValueObject other)](#equals-com.groupdocs.conversion.contracts.ValueObject-) | Menentukan apakah dua instance objek sama. |
|
|  | [hashCode()](#hashCode--) | Berfungsi sebagai fungsi hash default. |
|
|  | [op_Equality(ValueObject a, ValueObject b)](#op-Equality-com.groupdocs.conversion.contracts.ValueObject-com.groupdocs.conversion.contracts.ValueObject-) | Operator kesetaraan. |
|
|  | [op_Inequality(ValueObject a, ValueObject b)](#op-Inequality-com.groupdocs.conversion.contracts.ValueObject-com.groupdocs.conversion.contracts.ValueObject-) | Operator ketidaksamaan. |
|
### ValueObject() {#ValueObject--}
```
public ValueObject()
```


### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Menentukan apakah dua instance objek sama.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | obj | java.lang.Object | Objek untuk dibandingkan dengan objek saat ini. |
|

**Returns:**
boolean -  true  jika objek yang ditentukan sama dengan objek saat ini; sebaliknya,  false .

### equals(ValueObject other) {#equals-com.groupdocs.conversion.contracts.ValueObject-}
```
public final boolean equals(ValueObject other)
```


Menentukan apakah dua instance objek sama.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | other | [ValueObject](../../com.groupdocs.conversion.contracts/valueobject) | Objek untuk dibandingkan dengan objek saat ini. |
|

**Returns:**
boolean -  true  jika objek yang ditentukan sama dengan objek saat ini; sebaliknya,  false .

### hashCode() {#hashCode--}
```
public int hashCode()
```


Berfungsi sebagai fungsi hash default.


**Returns:**
int - Kode hash untuk objek saat ini.

### op_Equality(ValueObject a, ValueObject b) {#op-Equality-com.groupdocs.conversion.contracts.ValueObject-com.groupdocs.conversion.contracts.ValueObject-}
```
public static boolean op_Equality(ValueObject a, ValueObject b)
```


Operator kesetaraan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | a | [ValueObject](../../com.groupdocs.conversion.contracts/valueobject) | Objek pertama |
|
|  | b | [ValueObject](../../com.groupdocs.conversion.contracts/valueobject) | Objek kedua |
|

**Returns:**
boolean -  true  jika objek sama

### op_Inequality(ValueObject a, ValueObject b) {#op-Inequality-com.groupdocs.conversion.contracts.ValueObject-com.groupdocs.conversion.contracts.ValueObject-}
```
public static boolean op_Inequality(ValueObject a, ValueObject b)
```


Operator ketidaksamaan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | a | [ValueObject](../../com.groupdocs.conversion.contracts/valueobject) | Objek pertama |
|
|  | b | [ValueObject](../../com.groupdocs.conversion.contracts/valueobject) | Objek kedua |
|

**Returns:**
boolean -  true  jika objek tidak sama

