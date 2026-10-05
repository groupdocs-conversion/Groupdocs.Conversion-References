---
title: "열거형"
second_title: "Node.js용 GroupDocs.Conversion (Java 경유) API 레퍼런스"
description: "일반 열거형 클래스."
type: docs
weight: 11
url: /ko/nodejs-java/com.groupdocs.conversion.contracts/enumeration/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Comparable, java.io.Serializable, com.aspose.ms.System.IEquatable
```
public abstract class Enumeration implements Comparable, Serializable, System.IEquatable<Enumeration>
```

일반 열거형 클래스.

TKey :
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [toString()](#toString--) | 현재 객체를 나타내는 문자열을 반환합니다. |
| [<T>getAll(Class<T> typeOfT)](#-T-getAll-java.lang.Class-T--) | 모든 열거값을 반환합니다. |
| [equals(Object obj)](#equals-java.lang.Object-) | 두 객체 인스턴스가 같은지 여부를 판단합니다. |
| [equals(Enumeration other)](#equals-com.groupdocs.conversion.contracts.Enumeration-) | 두 객체 인스턴스가 같은지 여부를 판단합니다. |
| [hashCode()](#hashCode--) | 기본 해시 함수로 사용됩니다. |
| [<T>fromValue(Class<T> typeOfT, String value)](#-T-fromValue-java.lang.Class-T--java.lang.String-) | 키로 객체를 반환합니다. |
| [<T>fromDisplayName(Class<T> typeOfT, String displayName)](#-T-fromDisplayName-java.lang.Class-T--java.lang.String-) | 표시 이름으로 객체를 반환합니다. |
| [compareTo(Object obj)](#compareTo-java.lang.Object-) | 현재 객체를 다른 객체와 비교합니다. |
| [op_Equality(Enumeration left, Enumeration right)](#op-Equality-com.groupdocs.conversion.contracts.Enumeration-com.groupdocs.conversion.contracts.Enumeration-) | 동등 연산자. |
| [op_Inequality(Enumeration left, Enumeration right)](#op-Inequality-com.groupdocs.conversion.contracts.Enumeration-com.groupdocs.conversion.contracts.Enumeration-) | 부등 연산자. |
### toString() {#toString--}
```
public String toString()
```


현재 객체를 나타내는 문자열을 반환합니다.

**Returns:**
java.lang.String - 문자열 표현
### <T>getAll(Class<T> typeOfT) {#-T-getAll-java.lang.Class-T--}
```
public static List <T>getAll(Class<T> typeOfT)
```


모든 열거값을 반환합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |

**Returns:**
java.util.List - 제공된 유형의 열거형

T : 열거된 객체 유형.
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
### equals(Enumeration other) {#equals-com.groupdocs.conversion.contracts.Enumeration-}
```
public boolean equals(Enumeration other)
```


두 객체 인스턴스가 같은지 여부를 판단합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| other | [Enumeration](../../com.groupdocs.conversion.contracts/enumeration) | 현재 객체와 비교할 객체. |

**Returns:**
boolean - 지정된 객체가 현재 객체와 같으면 true; 그렇지 않으면 false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


기본 해시 함수로 사용됩니다.

**Returns:**
int - 현재 객체에 대한 해시 코드.
### <T>fromValue(Class<T> typeOfT, String value) {#-T-fromValue-java.lang.Class-T--java.lang.String-}
```
public static T <T>fromValue(Class<T> typeOfT, String value)
```


키로 객체를 반환합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |
| 값 | java.lang.String | 값 |

**Returns:**
T - 객체
### <T>fromDisplayName(Class<T> typeOfT, String displayName) {#-T-fromDisplayName-java.lang.Class-T--java.lang.String-}
```
public static T <T>fromDisplayName(Class<T> typeOfT, String displayName)
```


표시 이름으로 객체를 반환합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |
| displayName | java.lang.String | 표시 이름 |

**Returns:**
T - 객체
### compareTo(Object obj) {#compareTo-java.lang.Object-}
```
public final int compareTo(Object obj)
```


현재 객체를 다른 객체와 비교합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| obj | java.lang.Object | 다른 객체 |

**Returns:**
int - 같으면 0
### op_Equality(Enumeration left, Enumeration right) {#op-Equality-com.groupdocs.conversion.contracts.Enumeration-com.groupdocs.conversion.contracts.Enumeration-}
```
public static boolean op_Equality(Enumeration left, Enumeration right)
```


동등 연산자.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| left | [Enumeration](../../com.groupdocs.conversion.contracts/enumeration) | 첫 번째 객체 |
| right | [Enumeration](../../com.groupdocs.conversion.contracts/enumeration) | 두 번째 객체 |

**Returns:**
boolean -  객체가 같으면 true
### op_Inequality(Enumeration left, Enumeration right) {#op-Inequality-com.groupdocs.conversion.contracts.Enumeration-com.groupdocs.conversion.contracts.Enumeration-}
```
public static boolean op_Inequality(Enumeration left, Enumeration right)
```


부등 연산자.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| left | [Enumeration](../../com.groupdocs.conversion.contracts/enumeration) | 첫 번째 객체 |
| right | [Enumeration](../../com.groupdocs.conversion.contracts/enumeration) | 두 번째 객체 |

**Returns:**
boolean -  객체가 다르면 true
