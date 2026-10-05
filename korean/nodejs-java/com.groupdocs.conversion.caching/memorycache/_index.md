---
title: "MemoryCache"
second_title: "Node.js용 GroupDocs.Conversion (Java 경유) API 레퍼런스"
description: "메모리 캐싱 동작."
type: docs
weight: 11
url: /ko/nodejs-java/com.groupdocs.conversion.caching/memorycache/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.conversion.caching.ICache](../../com.groupdocs.conversion.caching/icache)
```
public class MemoryCache implements ICache
```

메모리 캐싱 동작. 캐시가 메모리에 저장된다는 의미입니다. **자세히 알아보기**캐싱 및 변환 프로세스 성능 최적화에 대한 자세한 내용: [캐싱 변환 결과][]


[Caching conversion results]: https://docs.groupdocs.com/display/conversionnet/Caching
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [MemoryCache()](#MemoryCache--) | MemoryCache 클래스의 새 인스턴스를 생성합니다 |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [set(String key, Object value)](#set-java.lang.String-java.lang.Object-) | 캐시 항목을 캐시에 삽입합니다. |
| [tryGetValue(String key)](#tryGetValue-java.lang.String-) | 해당 키와 연결된 항목이 있으면 가져옵니다. |
| [getKeys(String filter)](#getKeys-java.lang.String-) | 필터와 일치하는 모든 키를 반환합니다. |
### MemoryCache() {#MemoryCache--}
```
public MemoryCache()
```


MemoryCache 클래스의 새 인스턴스를 생성합니다

### set(String key, Object value) {#set-java.lang.String-java.lang.Object-}
```
public void set(String key, Object value)
```


캐시 항목을 캐시에 삽입합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 키 | java.lang.String | 캐시 항목에 대한 고유 식별자입니다. |
| 값 | java.lang.Object | 삽입할 객체입니다. |

### tryGetValue(String key) {#tryGetValue-java.lang.String-}
```
public Object tryGetValue(String key)
```


해당 키와 연결된 항목이 있으면 가져옵니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 키 | java.lang.String | 요청된 항목을 식별하는 키입니다. |

**Returns:**
java.lang.Object - 찾은 값 또는 null.
### getKeys(String filter) {#getKeys-java.lang.String-}
```
public Iterable<String> getKeys(String filter)
```


필터와 일치하는 모든 키를 반환합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 필터 | java.lang.String | 사용할 필터입니다. |

**Returns:**
java.lang.Iterable<java.lang.String> - 필터와 일치하는 키.
