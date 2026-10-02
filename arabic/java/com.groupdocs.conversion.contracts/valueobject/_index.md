---
title: "ValueObject"
second_title: "مرجع API لـ GroupDocs.Conversion للـ Java"
description: "فئة كائن قيمة مجردة."
type: docs
weight: 15
url: /ar/java/com.groupdocs.conversion.contracts/valueobject/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable, java.io.Serializable
```
public abstract class ValueObject implements System.IEquatable<ValueObject>, Serializable
```

فئة كائن قيمة مجردة.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [ValueObject()](#ValueObject--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [equals(Object obj)](#equals-java.lang.Object-) | يحدد ما إذا كانت مثيلتين من الكائن متساويتين. |
|
|  | [equals(ValueObject other)](#equals-com.groupdocs.conversion.contracts.ValueObject-) | يحدد ما إذا كانت مثيلتين من الكائن متساويتين. |
|
|  | [hashCode()](#hashCode--) | يعمل كدالة تجزئة افتراضية. |
|
|  | [op_Equality(ValueObject a, ValueObject b)](#op-Equality-com.groupdocs.conversion.contracts.ValueObject-com.groupdocs.conversion.contracts.ValueObject-) | عامل المساواة. |
|
|  | [op_Inequality(ValueObject a, ValueObject b)](#op-Inequality-com.groupdocs.conversion.contracts.ValueObject-com.groupdocs.conversion.contracts.ValueObject-) | عامل عدم المساواة. |
|
### ValueObject() {#ValueObject--}
```
public ValueObject()
```


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

### equals(ValueObject other) {#equals-com.groupdocs.conversion.contracts.ValueObject-}
```
public final boolean equals(ValueObject other)
```


يحدد ما إذا كانت مثيلتين من الكائن متساويتين.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | other | [ValueObject](../../com.groupdocs.conversion.contracts/valueobject) | الكائن للمقارنة مع الكائن الحالي. |
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

### op_Equality(ValueObject a, ValueObject b) {#op-Equality-com.groupdocs.conversion.contracts.ValueObject-com.groupdocs.conversion.contracts.ValueObject-}
```
public static boolean op_Equality(ValueObject a, ValueObject b)
```


عامل المساواة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | a | [ValueObject](../../com.groupdocs.conversion.contracts/valueobject) | الكائن الأول |
|
|  | b | [ValueObject](../../com.groupdocs.conversion.contracts/valueobject) | الكائن الثاني |
|

**Returns:**
boolean -  true  إذا كانت الكائنات متساوية

### op_Inequality(ValueObject a, ValueObject b) {#op-Inequality-com.groupdocs.conversion.contracts.ValueObject-com.groupdocs.conversion.contracts.ValueObject-}
```
public static boolean op_Inequality(ValueObject a, ValueObject b)
```


عامل عدم المساواة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | a | [ValueObject](../../com.groupdocs.conversion.contracts/valueobject) | الكائن الأول |
|
|  | b | [ValueObject](../../com.groupdocs.conversion.contracts/valueobject) | الكائن الثاني |
|

**Returns:**
boolean -  true  إذا كانت الكائنات غير متساوية

