---
title: "__init__ 생성자"
second_title: "Python용 .NET을 통한 GroupDocs.Conversion API 참조"
description: "새 Converter 인스턴스를 초기화합니다."
type: docs
url: /ko/python-net/groupdocs.conversion/converter/__init__/
is_root: false
weight: 10
---


## __init__ {#source_stream_provider}

새 Converter 인스턴스를 초기화합니다.

- More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third‑party storage: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
- More about document loading options dependent on file type: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

```python
def __init__(self, source_stream_provider):
    ...
```

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| source_stream_provider | `Func[io.RawIOBase]` | 읽을 수 있는 스트림을 반환하는 메서드입니다. |

| 예외 발생. | 설명 |
| :- | :- |
| `ValueError` | `source_stream_provider` 가 None 일 때 발생합니다. |

### 예제

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with open("input.docx", "rb") as stream:
    with Converter(stream) as converter:
        converter.convert("output.pdf", PdfConvertOptions())
```

## __init__ {#source_stream_provider-settings}

새 [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) 인스턴스를 초기화합니다.

자세히 알아보기

- More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third‑party storage: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
- More about document loading options dependent on file type: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

```python
def __init__(self, source_stream_provider, settings):
    ...
```

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| source_stream_provider | `Func[io.RawIOBase]` | 읽을 수 있는 스트림을 반환하는 메서드입니다. |
| settings | `Func[ConverterSettings]` | Converter 설정입니다. |

### 예제

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("input.docx") as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

## __init__ {#source_stream_provider-load_options-settings}

새 [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) 인스턴스를 초기화합니다.

- More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third‑party storage: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
- More about document loading options dependent on file type: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

```python
def __init__(self, source_stream_provider, load_options, settings):
    ...
```

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| source_stream_provider | `Func[io.RawIOBase]` | 읽을 수 있는 `io.RawIOBase` 스트림을 반환하는 Callable. |
| load_options | `Func[LoadContext, LoadOptions]` | 문서에 대한 로드 옵션을 제공하는 Callable[[`LoadContext`], `GroupDocs.Conversion.LoadOptions`]. `LoadContext` 매개변수에는 로드 중인 문서에 대한 정보가 포함됩니다. |
| settings | `Func[ConverterSettings]` | 컨버터 설정을 지정하는 `ConverterSettings`. |

### 예제

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with open("input.docx", "rb") as stream:
    with Converter(stream) as converter:
        converter.convert("output.pdf", PdfConvertOptions())
```

## __init__ {#source_stream_provider-load_options-settings-events}

명시적 변환 이벤트가 있는 새 Converter를 초기화합니다.

```python
def __init__(self, source_stream_provider, load_options, settings, events):
    ...
```

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| source_stream_provider | `Func[io.RawIOBase]` | 읽을 수 있는 스트림을 반환하는 Callable. |
| load_options | `Func[LoadContext, LoadOptions]` | 문서에 대한 로드 옵션을 제공하는 Callable. |
| settings | `Func[ConverterSettings]` | 컨버터 설정. |
| events | `Func[ConversionEvents]` | 컨버터 수명 동안 등록된 집계된 `ConversionEvents`를 제공하는 Callable. |

## __init__ {#source_stream_provider-settings-events}

명시적 변환 이벤트가 있는 새 Converter 인스턴스를 초기화합니다.

```python
def __init__(self, source_stream_provider, settings, events):
    ...
```

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| source_stream_provider | `Func[io.RawIOBase]` | 읽을 수 있는 스트림을 반환하는 Callable. |
| settings | `Func[ConverterSettings]` | 컨버터 설정. |
| events | `Func[ConversionEvents]` | 컨버터 수명 동안 등록된 집계된 `ConversionEvents`를 제공하는 Delegate. |

### 예제

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with open("input.docx", "rb") as stream:
    with Converter(stream) as converter:
        converter.convert("output.pdf", PdfConvertOptions())
```

## __init__ {#file_path}

새 Converter 인스턴스를 초기화합니다.

- More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third‑party storage: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
- More about document loading options dependent on file type: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

```python
def __init__(self, file_path):
    ...
```

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| file_path | `str` | 소스 문서의 파일 경로입니다. |

### 예제

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("input.docx") as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

## __init__ {#file_path-settings}

새 [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) 인스턴스를 초기화합니다.

자세히 알아보기

- More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third‑party storage: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
- More about document loading options dependent on file type: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

```python
def __init__(self, file_path, settings):
    ...
```

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| file_path | `str` | 소스 문서의 파일 경로입니다. |
| settings | `Func[ConverterSettings]` | Converter 설정입니다. |

### 예제

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("input.docx") as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

## __init__ {#file_path-load_options-settings}

새 [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) 클래스 인스턴스를 초기화합니다.

자세히 알아보기

- More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third‑party storage: <https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources>
- More about document loading options dependent on file type: <https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types>

```python
def __init__(self, file_path, load_options, settings):
    ...
```

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| file_path | `str` | 소스 문서의 파일 경로입니다. |
| load_options | `Func[LoadContext, LoadOptions]` | 문서에 대한 로드 옵션을 제공하는 Delegate. 서명: `Func<LoadContext, LoadOptions>`. `LoadContext` 매개변수에는 로드 중인 문서에 대한 정보가 포함됩니다. |
| settings | `Func[ConverterSettings]` | Converter 설정입니다. |

### 예제

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("input.docx") as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

## __init__ {#file_path-load_options-settings-events}

명시적 변환 이벤트가 있는 새 Converter를 초기화합니다.

```python
def __init__(self, file_path, load_options, settings, events):
    ...
```

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| file_path | `str` | 소스 문서의 파일 경로입니다. |
| load_options | `Func[LoadContext, LoadOptions]` | 문서에 대한 로드 옵션을 제공하는 Delegate. |
| settings | `Func[ConverterSettings]` | Converter 설정입니다. |
| events | `Func[ConversionEvents]` | 컨버터 수명 동안 등록된 집계된 `ConversionEvents`를 제공하는 Delegate. |

### 예제

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("input.docx") as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

## __init__ {#file_path-settings-events}

명시적 변환 이벤트가 있는 새 Converter를 초기화합니다.

```python
def __init__(self, file_path, settings, events):
    ...
```

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| file_path | `str` | 소스 문서의 파일 경로입니다. |
| settings | `Func[ConverterSettings]` | Converter 설정입니다. |
| events | `Func[ConversionEvents]` | 컨버터 수명 동안 등록된 집계된 ConversionEvents를 제공하는 Delegate. |

### 예제

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("input.docx") as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

### 또 보기
* class [`Converter`](/conversion/python-net/groupdocs.conversion/converter/)
