---
title: "FileCache"
second_title: "Node.js용 GroupDocs.Conversion (Java 경유) API 레퍼런스"
description: "파일 캐싱 동작."
type: docs
weight: 10
url: /ko/nodejs-java/com.groupdocs.conversion.caching/filecache/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.conversion.caching.ICache](../../com.groupdocs.conversion.caching/icache)
```
public final class FileCache implements ICache
```

파일 캐싱 동작. 캐시가 파일 시스템에 저장됨을 의미합니다 **자세히 알아보기** 캐시 및 변환 프로세스 성능 최적화에 대한 자세한 내용: [변환 결과 캐시][]


[Caching conversion results]: https://docs.groupdocs.com/display/conversionnet/Caching
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [FileCache(String cachePath)](#FileCache-java.lang.String-) | FileCache 클래스의 새 인스턴스를 생성합니다 |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [set(String key, Object value)](#set-java.lang.String-java.lang.Object-) | 캐시 항목을 캐시에 삽입합니다. |
| [tryGetValue(String key)](#tryGetValue-java.lang.String-) | 해당 키와 연결된 항목이 있으면 가져옵니다. |
| [getKeys(String filter)](#getKeys-java.lang.String-) | 필터와 일치하는 모든 키를 반환합니다. |
### FileCache(String cachePath) {#FileCache-java.lang.String-}
```
public FileCache(String cachePath)
```


FileCache 클래스의 새 인스턴스를 생성합니다

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| cachePath | java.lang.String | 문서 캐시가 저장될 상대 경로나 절대 경로 |

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
java.lang.Object - 키가 발견되면 객체, 그렇지 않으면 null.
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
