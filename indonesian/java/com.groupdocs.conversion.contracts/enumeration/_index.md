---
title: "Enumerasi"
second_title: "Referensi API GroupDocs.Conversion untuk Java"
description: "Kelas enumerasi generik."
type: docs
weight: 11
url: /id/java/com.groupdocs.conversion.contracts/enumeration/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Comparable, java.io.Serializable, com.aspose.ms.System.IEquatable
```
public abstract class Enumeration implements Comparable, Serializable, System.IEquatable<Enumeration>
```

Kelas enumerasi generik.


TKey
:

## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [toString()](#toString--) | Mengembalikan string yang mewakili objek saat ini. |
|
|  | [<T>getAll(Class<T> typeOfT)](#-T-getAll-java.lang.Class-T--) | Mengembalikan semua nilai enumerasi. |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Menentukan apakah dua instance objek sama. |
|
|  | [equals(Enumeration other)](#equals-com.groupdocs.conversion.contracts.Enumeration-) | Menentukan apakah dua instance objek sama. |
|
|  | [hashCode()](#hashCode--) | Berfungsi sebagai fungsi hash default. |
|
|  | [<T>fromValue(Class<T> typeOfT, String value)](#-T-fromValue-java.lang.Class-T--java.lang.String-) | Mengembalikan objek berdasarkan kunci. |
|
|  | [<T>fromDisplayName(Class<T> typeOfT, String displayName)](#-T-fromDisplayName-java.lang.Class-T--java.lang.String-) | Mengembalikan objek berdasarkan nama tampilan. |
|
|  | [compareTo(Object obj)](#compareTo-java.lang.Object-) | Membandingkan objek saat ini dengan yang lain. |
|
|  | [op_Equality(Enumeration left, Enumeration right)](#op-Equality-com.groupdocs.conversion.contracts.Enumeration-com.groupdocs.conversion.contracts.Enumeration-) | Operator kesetaraan. |
|
|  | [op_Inequality(Enumeration left, Enumeration right)](#op-Inequality-com.groupdocs.conversion.contracts.Enumeration-com.groupdocs.conversion.contracts.Enumeration-) | Operator ketidaksamaan. |
|
### toString() {#toString--}
```
public String toString()
```


Mengembalikan string yang mewakili objek saat ini.


**Returns:**
java.lang.String - representasi string

### <T>getAll(Class<T> typeOfT) {#-T-getAll-java.lang.Class-T--}
```
public static List <T>getAll(Class<T> typeOfT)
```


Mengembalikan semua nilai enumerasi.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |

**Returns:**
java.util.List - enumerasi dari tipe yang disediakan


T
: Tipe objek yang dienumerasi.

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

### equals(Enumeration other) {#equals-com.groupdocs.conversion.contracts.Enumeration-}
```
public boolean equals(Enumeration other)
```


Menentukan apakah dua instance objek sama.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | other | [Enumeration](../../com.groupdocs.conversion.contracts/enumeration) | Objek untuk dibandingkan dengan objek saat ini. |
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

### <T>fromValue(Class<T> typeOfT, String value) {#-T-fromValue-java.lang.Class-T--java.lang.String-}
```
public static T <T>fromValue(Class<T> typeOfT, String value)
```


Mengembalikan objek berdasarkan kunci.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |
|  | nilai | java.lang.String | Nilai |
|

**Returns:**
T - Objek

### <T>fromDisplayName(Class<T> typeOfT, String displayName) {#-T-fromDisplayName-java.lang.Class-T--java.lang.String-}
```
public static T <T>fromDisplayName(Class<T> typeOfT, String displayName)
```


Mengembalikan objek berdasarkan nama tampilan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |
|  | displayName | java.lang.String | Nama tampilan |
|

**Returns:**
T - Objek

### compareTo(Object obj) {#compareTo-java.lang.Object-}
```
public final int compareTo(Object obj)
```


Membandingkan objek saat ini dengan yang lain.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | obj | java.lang.Object | Objek lain |
|

**Returns:**
int - nol jika sama

### op_Equality(Enumeration left, Enumeration right) {#op-Equality-com.groupdocs.conversion.contracts.Enumeration-com.groupdocs.conversion.contracts.Enumeration-}
```
public static boolean op_Equality(Enumeration left, Enumeration right)
```


Operator kesetaraan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | left | [Enumeration](../../com.groupdocs.conversion.contracts/enumeration) | Objek pertama |
|
|  | right | [Enumeration](../../com.groupdocs.conversion.contracts/enumeration) | Objek kedua |
|

**Returns:**
boolean -  true  jika objek sama

### op_Inequality(Enumeration left, Enumeration right) {#op-Inequality-com.groupdocs.conversion.contracts.Enumeration-com.groupdocs.conversion.contracts.Enumeration-}
```
public static boolean op_Inequality(Enumeration left, Enumeration right)
```


Operator ketidaksamaan.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | left | [Enumeration](../../com.groupdocs.conversion.contracts/enumeration) | Objek pertama |
|
|  | right | [Enumeration](../../com.groupdocs.conversion.contracts/enumeration) | Objek kedua |
|

**Returns:**
boolean -  true  jika objek tidak sama

