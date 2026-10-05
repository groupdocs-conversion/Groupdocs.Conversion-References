---
title: "Sıralama"
second_title: "Node.js için GroupDocs.Conversion, Java üzerinden API Referansı"
description: "Genel enum sınıfı."
type: docs
weight: 11
url: /tr/nodejs-java/com.groupdocs.conversion.contracts/enumeration/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Comparable, java.io.Serializable, com.aspose.ms.System.IEquatable
```
public abstract class Enumeration implements Comparable, Serializable, System.IEquatable<Enumeration>
```

Genel enum sınıfı.

TKey :
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [toString()](#toString--) | Geçerli nesneyi temsil eden bir dize döndürür. |
| [<T>getAll(Class<T> typeOfT)](#-T-getAll-java.lang.Class-T--) | Tüm enum değerlerini döndürür. |
| [equals(Object obj)](#equals-java.lang.Object-) | İki nesne örneğinin eşit olup olmadığını belirler. |
| [equals(Enumeration other)](#equals-com.groupdocs.conversion.contracts.Enumeration-) | İki nesne örneğinin eşit olup olmadığını belirler. |
| [hashCode()](#hashCode--) | Varsayılan hash işlevi olarak hizmet verir. |
| [<T>fromValue(Class<T> typeOfT, String value)](#-T-fromValue-java.lang.Class-T--java.lang.String-) | Anahtara göre nesneyi döndürür. |
| [<T>fromDisplayName(Class<T> typeOfT, String displayName)](#-T-fromDisplayName-java.lang.Class-T--java.lang.String-) | Görünen ada göre nesneyi döndürür. |
| [compareTo(Object obj)](#compareTo-java.lang.Object-) | Geçerli nesneyi diğerine karşılaştırır. |
| [op_Equality(Enumeration left, Enumeration right)](#op-Equality-com.groupdocs.conversion.contracts.Enumeration-com.groupdocs.conversion.contracts.Enumeration-) | Eşitlik operatörü. |
| [op_Inequality(Enumeration left, Enumeration right)](#op-Inequality-com.groupdocs.conversion.contracts.Enumeration-com.groupdocs.conversion.contracts.Enumeration-) | Eşitsizlik operatörü. |
### toString() {#toString--}
```
public String toString()
```


Geçerli nesneyi temsil eden bir dize döndürür.

**Returns:**
java.lang.String - Dize temsili
### <T>getAll(Class<T> typeOfT) {#-T-getAll-java.lang.Class-T--}
```
public static List <T>getAll(Class<T> typeOfT)
```


Tüm enum değerlerini döndürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |

**Returns:**
java.util.List - Sağlanan tipin enumerable'ı

T : Numaralandırılmış nesne türü.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


İki nesne örneğinin eşit olup olmadığını belirler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | java.lang.Object | Geçerli nesneyle karşılaştırılacak nesne. |

**Returns:**
boolean -  true  eğer belirtilen nesne geçerli nesneye eşitse; aksi takdirde,  false .
### equals(Enumeration other) {#equals-com.groupdocs.conversion.contracts.Enumeration-}
```
public boolean equals(Enumeration other)
```


İki nesne örneğinin eşit olup olmadığını belirler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| other | [Enumeration](../../com.groupdocs.conversion.contracts/enumeration) | Geçerli nesneyle karşılaştırılacak nesne. |

**Returns:**
boolean -  true  eğer belirtilen nesne geçerli nesneye eşitse; aksi takdirde,  false .
### hashCode() {#hashCode--}
```
public int hashCode()
```


Varsayılan hash işlevi olarak hizmet verir.

**Returns:**
int - Geçerli nesne için bir karma kodu.
### <T>fromValue(Class<T> typeOfT, String value) {#-T-fromValue-java.lang.Class-T--java.lang.String-}
```
public static T <T>fromValue(Class<T> typeOfT, String value)
```


Anahtara göre nesneyi döndürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |
| değer | java.lang.String | Değer |

**Returns:**
T - Nesne
### <T>fromDisplayName(Class<T> typeOfT, String displayName) {#-T-fromDisplayName-java.lang.Class-T--java.lang.String-}
```
public static T <T>fromDisplayName(Class<T> typeOfT, String displayName)
```


Görünen ada göre nesneyi döndürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |
| displayName | java.lang.String | Görünen ad |

**Returns:**
T - Nesne
### compareTo(Object obj) {#compareTo-java.lang.Object-}
```
public final int compareTo(Object obj)
```


Geçerli nesneyi diğerine karşılaştırır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | java.lang.Object | Diğer nesne |

**Returns:**
int - eşitse sıfır
### op_Equality(Enumeration left, Enumeration right) {#op-Equality-com.groupdocs.conversion.contracts.Enumeration-com.groupdocs.conversion.contracts.Enumeration-}
```
public static boolean op_Equality(Enumeration left, Enumeration right)
```


Eşitlik operatörü.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| left | [Enumeration](../../com.groupdocs.conversion.contracts/enumeration) | İlk nesne |
| right | [Enumeration](../../com.groupdocs.conversion.contracts/enumeration) | İkinci nesne |

**Returns:**
boolean -  true  eğer nesneler eşitse
### op_Inequality(Enumeration left, Enumeration right) {#op-Inequality-com.groupdocs.conversion.contracts.Enumeration-com.groupdocs.conversion.contracts.Enumeration-}
```
public static boolean op_Inequality(Enumeration left, Enumeration right)
```


Eşitsizlik operatörü.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| left | [Enumeration](../../com.groupdocs.conversion.contracts/enumeration) | İlk nesne |
| right | [Enumeration](../../com.groupdocs.conversion.contracts/enumeration) | İkinci nesne |

**Returns:**
boolean -  true  eğer nesneler eşit değilse
