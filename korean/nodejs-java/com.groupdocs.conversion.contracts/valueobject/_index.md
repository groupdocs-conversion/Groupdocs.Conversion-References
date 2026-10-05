---
title: "ValueObject"
second_title: "Node.js용 GroupDocs.Conversion (Java 경유) API 레퍼런스"
description: "추상 값 객체 클래스."
type: docs
weight: 15
url: /ko/nodejs-java/com.groupdocs.conversion.contracts/valueobject/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable, java.io.Serializable
```
public abstract class ValueObject implements System.IEquatable<ValueObject>, Serializable
```

추상 값 객체 클래스.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [ValueObject()](#ValueObject--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | 두 객체 인스턴스가 같은지 여부를 판단합니다. |
| [equals(ValueObject other)](#equals-com.groupdocs.conversion.contracts.ValueObject-) | 두 객체 인스턴스가 같은지 여부를 판단합니다. |
| [hashCode()](#hashCode--) | 기본 해시 함수로 사용됩니다. |
| [op_Equality(ValueObject a, ValueObject b)](#op-Equality-com.groupdocs.conversion.contracts.ValueObject-com.groupdocs.conversion.contracts.ValueObject-) | 동등 연산자. |
| [op_Inequality(ValueObject a, ValueObject b)](#op-Inequality-com.groupdocs.conversion.contracts.ValueObject-com.groupdocs.conversion.contracts.ValueObject-) | 부등 연산자. |
### ValueObject() {#ValueObject--}
```
public ValueObject()
```


### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


두 객체 인스턴스가 같은지 여부를 판단합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| obj | java.lang.Object | 현재 객체와 비교할 객체. |

**Returns:**
boolean - 지정된 객체가 현재 객체와 같으면 true; 그렇지 않으면 false.
### equals(ValueObject other) {#equals-com.groupdocs.conversion.contracts.ValueObject-}
```
public final boolean equals(ValueObject other)
```


두 객체 인스턴스가 같은지 여부를 판단합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| other | [ValueObject](../../com.groupdocs.conversion.contracts/valueobject) | 현재 객체와 비교할 객체. |

**Returns:**
boolean - 지정된 객체가 현재 객체와 같으면 true; 그렇지 않으면 false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


기본 해시 함수로 사용됩니다.

**Returns:**
int - 현재 객체에 대한 해시 코드.
### op_Equality(ValueObject a, ValueObject b) {#op-Equality-com.groupdocs.conversion.contracts.ValueObject-com.groupdocs.conversion.contracts.ValueObject-}
```
public static boolean op_Equality(ValueObject a, ValueObject b)
```


동등 연산자.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| a | [ValueObject](../../com.groupdocs.conversion.contracts/valueobject) | 첫 번째 객체 |
| b | [ValueObject](../../com.groupdocs.conversion.contracts/valueobject) | 두 번째 객체 |

**Returns:**
boolean -  객체가 같으면 true
### op_Inequality(ValueObject a, ValueObject b) {#op-Inequality-com.groupdocs.conversion.contracts.ValueObject-com.groupdocs.conversion.contracts.ValueObject-}
```
public static boolean op_Inequality(ValueObject a, ValueObject b)
```


부등 연산자.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| a | [ValueObject](../../com.groupdocs.conversion.contracts/valueobject) | 첫 번째 객체 |
| b | [ValueObject](../../com.groupdocs.conversion.contracts/valueobject) | 두 번째 객체 |

**Returns:**
boolean -  객체가 다르면 true
