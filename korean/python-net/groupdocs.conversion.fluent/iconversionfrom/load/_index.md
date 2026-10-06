---
title: "load 메서드"
second_title: "Python용 .NET을 통한 GroupDocs.Conversion API 참조"
description: "소스 문서 파일 이름을 설정합니다."
type: docs
url: /ko/python-net/groupdocs.conversion.fluent/iconversionfrom/load/
is_root: false
weight: 1010
---


## load {#file_name}

소스 문서 파일 이름을 설정합니다.

```python
def load(self, file_name):
    ...
```

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| file_name | `str` | 소스 문서. |

## load {#file_name}

소스 문서 배열을 설정합니다.

```python
def load(self, file_name):
    ...
```

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| file_name | `list[str]` | 소스 문서 집합. |

## load {#document_stream_provider}

소스 문서 스트림을 설정합니다.

```python
def load(self, document_stream_provider):
    ...
```

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| document_stream_provider | `Func[io.RawIOBase]` | 소스 문서 스트림 제공자. |

| 예외 발생. | 설명 |
| :- | :- |
| `InvalidConverterSettingsException` | 변환기 설정 검증에 실패하면. |

## load {#document_stream_provider}

소스 문서 스트림 제공자를 설정합니다.

```python
def load(self, document_stream_provider):
    ...
```

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| document_stream_provider | `Func[list[io.RawIOBase]]` | 소스 문서 스트림 제공자. |

| 예외 발생. | 설명 |
| :- | :- |
| `InvalidConverterSettingsException` | 변환기 설정 검증에 실패하면. |

### 또 보기
* class [`IConversionFrom`](/conversion/python-net/groupdocs.conversion.fluent/iconversionfrom/)
