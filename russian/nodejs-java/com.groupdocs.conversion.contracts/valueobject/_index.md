---
title: "ValueObject"
second_title: "Справочник API GroupDocs.Conversion для Node.js через Java"
description: "Абстрактный класс объект-значения."
type: docs
weight: 15
url: /ru/nodejs-java/com.groupdocs.conversion.contracts/valueobject/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable, java.io.Serializable
```
public abstract class ValueObject implements System.IEquatable<ValueObject>, Serializable
```

Абстрактный класс объект-значения.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [ValueObject()](#ValueObject--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Определяет, равны ли два экземпляра объекта. |
| [equals(ValueObject other)](#equals-com.groupdocs.conversion.contracts.ValueObject-) | Определяет, равны ли два экземпляра объекта. |
| [hashCode()](#hashCode--) | Служит функцией хеширования по умолчанию. |
| [op_Equality(ValueObject a, ValueObject b)](#op-Equality-com.groupdocs.conversion.contracts.ValueObject-com.groupdocs.conversion.contracts.ValueObject-) | Оператор равенства. |
| [op_Inequality(ValueObject a, ValueObject b)](#op-Inequality-com.groupdocs.conversion.contracts.ValueObject-com.groupdocs.conversion.contracts.ValueObject-) | Оператор неравенства. |
### ValueObject() {#ValueObject--}
```
public ValueObject()
```


### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Определяет, равны ли два экземпляра объекта.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | java.lang.Object | Объект для сравнения с текущим объектом. |

**Returns:**
boolean -  true  если указанный объект равен текущему объекту; иначе,  false .
### equals(ValueObject other) {#equals-com.groupdocs.conversion.contracts.ValueObject-}
```
public final boolean equals(ValueObject other)
```


Определяет, равны ли два экземпляра объекта.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| other | [ValueObject](../../com.groupdocs.conversion.contracts/valueobject) | Объект для сравнения с текущим объектом. |

**Returns:**
boolean -  true  если указанный объект равен текущему объекту; иначе,  false .
### hashCode() {#hashCode--}
```
public int hashCode()
```


Служит функцией хеширования по умолчанию.

**Returns:**
int - Хеш-код текущего объекта.
### op_Equality(ValueObject a, ValueObject b) {#op-Equality-com.groupdocs.conversion.contracts.ValueObject-com.groupdocs.conversion.contracts.ValueObject-}
```
public static boolean op_Equality(ValueObject a, ValueObject b)
```


Оператор равенства.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| a | [ValueObject](../../com.groupdocs.conversion.contracts/valueobject) | Первый объект |
| b | [ValueObject](../../com.groupdocs.conversion.contracts/valueobject) | Второй объект |

**Returns:**
boolean -  true  если объекты равны
### op_Inequality(ValueObject a, ValueObject b) {#op-Inequality-com.groupdocs.conversion.contracts.ValueObject-com.groupdocs.conversion.contracts.ValueObject-}
```
public static boolean op_Inequality(ValueObject a, ValueObject b)
```


Оператор неравенства.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| a | [ValueObject](../../com.groupdocs.conversion.contracts/valueobject) | Первый объект |
| b | [ValueObject](../../com.groupdocs.conversion.contracts/valueobject) | Второй объект |

**Returns:**
boolean -  true  если объекты не равны
