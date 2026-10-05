---
title: "Перечисление"
second_title: "Справочник API GroupDocs.Conversion для Node.js через Java"
description: "Обобщённый класс перечисления."
type: docs
weight: 11
url: /ru/nodejs-java/com.groupdocs.conversion.contracts/enumeration/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Comparable, java.io.Serializable, com.aspose.ms.System.IEquatable
```
public abstract class Enumeration implements Comparable, Serializable, System.IEquatable<Enumeration>
```

Обобщённый класс перечисления.

TKey :
## Методы

| Метод | Описание |
| --- | --- |
| [toString()](#toString--) | Возвращает строку, представляющую текущий объект. |
| [<T>getAll(Class<T> typeOfT)](#-T-getAll-java.lang.Class-T--) | Возвращает все значения перечисления. |
| [equals(Object obj)](#equals-java.lang.Object-) | Определяет, равны ли два экземпляра объекта. |
| [equals(Enumeration other)](#equals-com.groupdocs.conversion.contracts.Enumeration-) | Определяет, равны ли два экземпляра объекта. |
| [hashCode()](#hashCode--) | Служит функцией хеширования по умолчанию. |
| [<T>fromValue(Class<T> typeOfT, String value)](#-T-fromValue-java.lang.Class-T--java.lang.String-) | Возвращает объект по ключу. |
| [<T>fromDisplayName(Class<T> typeOfT, String displayName)](#-T-fromDisplayName-java.lang.Class-T--java.lang.String-) | Возвращает объект по отображаемому имени. |
| [compareTo(Object obj)](#compareTo-java.lang.Object-) | Сравнивает текущий объект с другим. |
| [op_Equality(Enumeration left, Enumeration right)](#op-Equality-com.groupdocs.conversion.contracts.Enumeration-com.groupdocs.conversion.contracts.Enumeration-) | Оператор равенства. |
| [op_Inequality(Enumeration left, Enumeration right)](#op-Inequality-com.groupdocs.conversion.contracts.Enumeration-com.groupdocs.conversion.contracts.Enumeration-) | Оператор неравенства. |
### toString() {#toString--}
```
public String toString()
```


Возвращает строку, представляющую текущий объект.

**Returns:**
java.lang.String - строковое представление
### <T>getAll(Class<T> typeOfT) {#-T-getAll-java.lang.Class-T--}
```
public static List <T>getAll(Class<T> typeOfT)
```


Возвращает все значения перечисления.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |

**Returns:**
java.util.List - перечисление элементов указанного типа

T : Перечислимый тип объекта.
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
### equals(Enumeration other) {#equals-com.groupdocs.conversion.contracts.Enumeration-}
```
public boolean equals(Enumeration other)
```


Определяет, равны ли два экземпляра объекта.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| other | [Enumeration](../../com.groupdocs.conversion.contracts/enumeration) | Объект для сравнения с текущим объектом. |

**Returns:**
boolean -  true  если указанный объект равен текущему объекту; иначе,  false .
### hashCode() {#hashCode--}
```
public int hashCode()
```


Служит функцией хеширования по умолчанию.

**Returns:**
int - Хеш-код текущего объекта.
### <T>fromValue(Class<T> typeOfT, String value) {#-T-fromValue-java.lang.Class-T--java.lang.String-}
```
public static T <T>fromValue(Class<T> typeOfT, String value)
```


Возвращает объект по ключу.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |
| значение | java.lang.String | Значение |

**Returns:**
T - Объект
### <T>fromDisplayName(Class<T> typeOfT, String displayName) {#-T-fromDisplayName-java.lang.Class-T--java.lang.String-}
```
public static T <T>fromDisplayName(Class<T> typeOfT, String displayName)
```


Возвращает объект по отображаемому имени.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |
| displayName | java.lang.String | Отображаемое имя |

**Returns:**
T - Объект
### compareTo(Object obj) {#compareTo-java.lang.Object-}
```
public final int compareTo(Object obj)
```


Сравнивает текущий объект с другим.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | java.lang.Object | Другой объект |

**Returns:**
int - ноль, если равны
### op_Equality(Enumeration left, Enumeration right) {#op-Equality-com.groupdocs.conversion.contracts.Enumeration-com.groupdocs.conversion.contracts.Enumeration-}
```
public static boolean op_Equality(Enumeration left, Enumeration right)
```


Оператор равенства.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| left | [Enumeration](../../com.groupdocs.conversion.contracts/enumeration) | Первый объект |
| right | [Enumeration](../../com.groupdocs.conversion.contracts/enumeration) | Второй объект |

**Returns:**
boolean -  true  если объекты равны
### op_Inequality(Enumeration left, Enumeration right) {#op-Inequality-com.groupdocs.conversion.contracts.Enumeration-com.groupdocs.conversion.contracts.Enumeration-}
```
public static boolean op_Inequality(Enumeration left, Enumeration right)
```


Оператор неравенства.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| left | [Enumeration](../../com.groupdocs.conversion.contracts/enumeration) | Первый объект |
| right | [Enumeration](../../com.groupdocs.conversion.contracts/enumeration) | Второй объект |

**Returns:**
boolean -  true  если объекты не равны
