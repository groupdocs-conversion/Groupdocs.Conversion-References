---
title: "ValueObject"
second_title: "Java için GroupDocs.Conversion API Referansı"
description: "Soyut değer nesnesi sınıfı."
type: docs
weight: 15
url: /tr/java/com.groupdocs.conversion.contracts/valueobject/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable, java.io.Serializable
```
public abstract class ValueObject implements System.IEquatable<ValueObject>, Serializable
```

Soyut değer nesnesi sınıfı.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [ValueObject()](#ValueObject--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [equals(Object obj)](#equals-java.lang.Object-) | İki nesne örneğinin eşit olup olmadığını belirler. |
|
|  | [equals(ValueObject other)](#equals-com.groupdocs.conversion.contracts.ValueObject-) | İki nesne örneğinin eşit olup olmadığını belirler. |
|
|  | [hashCode()](#hashCode--) | Varsayılan karma işlevi olarak hizmet verir. |
|
|  | [op_Equality(ValueObject a, ValueObject b)](#op-Equality-com.groupdocs.conversion.contracts.ValueObject-com.groupdocs.conversion.contracts.ValueObject-) | Eşitlik operatörü. |
|
|  | [op_Inequality(ValueObject a, ValueObject b)](#op-Inequality-com.groupdocs.conversion.contracts.ValueObject-com.groupdocs.conversion.contracts.ValueObject-) | Eşitsizlik operatörü. |
|
### ValueObject() {#ValueObject--}
```
public ValueObject()
```


### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


İki nesne örneğinin eşit olup olmadığını belirler.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | obj | java.lang.Object | Geçerli nesneyle karşılaştırılacak nesne. |
|

**Returns:**
boolean -  true  eğer belirtilen nesne mevcut nesneye eşitse; aksi takdirde,  false .

### equals(ValueObject other) {#equals-com.groupdocs.conversion.contracts.ValueObject-}
```
public final boolean equals(ValueObject other)
```


İki nesne örneğinin eşit olup olmadığını belirler.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | other | [ValueObject](../../com.groupdocs.conversion.contracts/valueobject) | Geçerli nesneyle karşılaştırılacak nesne. |
|

**Returns:**
boolean -  true  eğer belirtilen nesne mevcut nesneye eşitse; aksi takdirde,  false .

### hashCode() {#hashCode--}
```
public int hashCode()
```


Varsayılan karma işlevi olarak hizmet verir.


**Returns:**
int - Mevcut nesne için bir karma kodu.

### op_Equality(ValueObject a, ValueObject b) {#op-Equality-com.groupdocs.conversion.contracts.ValueObject-com.groupdocs.conversion.contracts.ValueObject-}
```
public static boolean op_Equality(ValueObject a, ValueObject b)
```


Eşitlik operatörü.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | a | [ValueObject](../../com.groupdocs.conversion.contracts/valueobject) | İlk nesne |
|
|  | b | [ValueObject](../../com.groupdocs.conversion.contracts/valueobject) | İkinci nesne |
|

**Returns:**
boolean -  true  eğer nesneler eşitse

### op_Inequality(ValueObject a, ValueObject b) {#op-Inequality-com.groupdocs.conversion.contracts.ValueObject-com.groupdocs.conversion.contracts.ValueObject-}
```
public static boolean op_Inequality(ValueObject a, ValueObject b)
```


Eşitsizlik operatörü.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | a | [ValueObject](../../com.groupdocs.conversion.contracts/valueobject) | İlk nesne |
|
|  | b | [ValueObject](../../com.groupdocs.conversion.contracts/valueobject) | İkinci nesne |
|

**Returns:**
boolean -  true  eğer nesneler eşit değilse

