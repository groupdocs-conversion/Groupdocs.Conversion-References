---
title: "load 메서드"
second_title: "Python용 .NET을 통한 GroupDocs.Conversion API 참조"
description: "변환을 위해 원본 문서를 구성합니다."
type: docs
url: /ko/python-net/groupdocs.conversion/fluentconverter/load/
is_root: false
weight: 1010
---


## load {#file_name}

변환을 위해 원본 문서를 구성합니다.

```python
def load(cls, file_name):
    ...
```

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| file_name | `str` | 소스 문서. |

## load {#file_name}

원본 문서 집합을 구성합니다.

```python
def load(cls, file_name):
    ...
```

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| file_name | `list[str]` | 소스 파일 배열. |

## load {#document_stream_provider}

원본 문서 스트림을 구성합니다.

```python
def load(cls, document_stream_provider):
    ...
```

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| document_stream_provider | `Func[io.RawIOBase]` | 소스 문서 스트림 제공자. |

## load {#document_stream_provider}

원본 문서 스트림 집합을 구성합니다.

```python
def load(cls, document_stream_provider):
    ...
```

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| document_stream_provider | `Func[list[io.RawIOBase]]` | 소스 문서 스트림 공급자의 집합. |

### 또 보기
* class [`FluentConverter`](/conversion/python-net/groupdocs.conversion/fluentconverter/)
