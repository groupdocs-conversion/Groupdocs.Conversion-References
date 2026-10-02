---
title: "تعداد"
second_title: "مرجع API لـ GroupDocs.Conversion للـ Java"
description: "فئة تعداد عامة."
type: docs
weight: 11
url: /ar/java/com.groupdocs.conversion.contracts/enumeration/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Comparable, java.io.Serializable, com.aspose.ms.System.IEquatable
```
public abstract class Enumeration implements Comparable, Serializable, System.IEquatable<Enumeration>
```

فئة تعداد عامة.


TKey
:

## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [toString()](#toString--) | يرجع سلسلة تمثل الكائن الحالي. |
|
|  | [<T>getAll(Class<T> typeOfT)](#-T-getAll-java.lang.Class-T--) | إرجاع جميع قيم التعداد. |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | يحدد ما إذا كانت مثيلتين من الكائن متساويتين. |
|
|  | [equals(Enumeration other)](#equals-com.groupdocs.conversion.contracts.Enumeration-) | يحدد ما إذا كانت مثيلتين من الكائن متساويتين. |
|
|  | [hashCode()](#hashCode--) | يعمل كدالة تجزئة افتراضية. |
|
|  | [<T>fromValue(Class<T> typeOfT, String value)](#-T-fromValue-java.lang.Class-T--java.lang.String-) | يرجع الكائن حسب المفتاح. |
|
|  | [<T>fromDisplayName(Class<T> typeOfT, String displayName)](#-T-fromDisplayName-java.lang.Class-T--java.lang.String-) | يرجع الكائن حسب اسم العرض. |
|
|  | [compareTo(Object obj)](#compareTo-java.lang.Object-) | يقارن الكائن الحالي بآخر. |
|
|  | [op_Equality(Enumeration left, Enumeration right)](#op-Equality-com.groupdocs.conversion.contracts.Enumeration-com.groupdocs.conversion.contracts.Enumeration-) | عامل المساواة. |
|
|  | [op_Inequality(Enumeration left, Enumeration right)](#op-Inequality-com.groupdocs.conversion.contracts.Enumeration-com.groupdocs.conversion.contracts.Enumeration-) | عامل عدم المساواة. |
|
### toString() {#toString--}
```
public String toString()
```


يرجع سلسلة تمثل الكائن الحالي.


**Returns:**
java.lang.String - تمثيل السلسلة

### <T>getAll(Class<T> typeOfT) {#-T-getAll-java.lang.Class-T--}
```
public static List <T>getAll(Class<T> typeOfT)
```


إرجاع جميع قيم التعداد.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |

**Returns:**
java.util.List - قابل للتعداد من النوع المقدم


T
: نوع كائن مُعدَّد

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


يحدد ما إذا كانت مثيلتين من الكائن متساويتين.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | obj | java.lang.Object | الكائن للمقارنة مع الكائن الحالي. |
|

**Returns:**
boolean -  true  إذا كان الكائن المحدد مساويًا للكائن الحالي؛ وإلا،  false .

### equals(Enumeration other) {#equals-com.groupdocs.conversion.contracts.Enumeration-}
```
public boolean equals(Enumeration other)
```


يحدد ما إذا كانت مثيلتين من الكائن متساويتين.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | other | [Enumeration](../../com.groupdocs.conversion.contracts/enumeration) | الكائن للمقارنة مع الكائن الحالي. |
|

**Returns:**
boolean -  true  إذا كان الكائن المحدد مساويًا للكائن الحالي؛ وإلا،  false .

### hashCode() {#hashCode--}
```
public int hashCode()
```


يعمل كدالة تجزئة افتراضية.


**Returns:**
int - رمز تجزئة للكائن الحالي.

### <T>fromValue(Class<T> typeOfT, String value) {#-T-fromValue-java.lang.Class-T--java.lang.String-}
```
public static T <T>fromValue(Class<T> typeOfT, String value)
```


يرجع الكائن حسب المفتاح.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |
|  | القيمة | java.lang.String | القيمة |
|

**Returns:**
T - الكائن

### <T>fromDisplayName(Class<T> typeOfT, String displayName) {#-T-fromDisplayName-java.lang.Class-T--java.lang.String-}
```
public static T <T>fromDisplayName(Class<T> typeOfT, String displayName)
```


يرجع الكائن حسب اسم العرض.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |
|  | displayName | java.lang.String | اسم العرض |
|

**Returns:**
T - الكائن

### compareTo(Object obj) {#compareTo-java.lang.Object-}
```
public final int compareTo(Object obj)
```


يقارن الكائن الحالي بآخر.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | obj | java.lang.Object | الكائن الآخر |
|

**Returns:**
int - صفر إذا كان متساويًا

### op_Equality(Enumeration left, Enumeration right) {#op-Equality-com.groupdocs.conversion.contracts.Enumeration-com.groupdocs.conversion.contracts.Enumeration-}
```
public static boolean op_Equality(Enumeration left, Enumeration right)
```


عامل المساواة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | left | [Enumeration](../../com.groupdocs.conversion.contracts/enumeration) | الكائن الأول |
|
|  | right | [Enumeration](../../com.groupdocs.conversion.contracts/enumeration) | الكائن الثاني |
|

**Returns:**
boolean -  true  إذا كانت الكائنات متساوية

### op_Inequality(Enumeration left, Enumeration right) {#op-Inequality-com.groupdocs.conversion.contracts.Enumeration-com.groupdocs.conversion.contracts.Enumeration-}
```
public static boolean op_Inequality(Enumeration left, Enumeration right)
```


عامل عدم المساواة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | left | [Enumeration](../../com.groupdocs.conversion.contracts/enumeration) | الكائن الأول |
|
|  | right | [Enumeration](../../com.groupdocs.conversion.contracts/enumeration) | الكائن الثاني |
|

**Returns:**
boolean -  true  إذا كانت الكائنات غير متساوية

