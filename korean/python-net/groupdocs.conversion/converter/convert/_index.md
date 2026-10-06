---
title: "convert 메서드"
second_title: "Python용 .NET을 통한 GroupDocs.Conversion API 참조"
description: "소스 문서를 변환하고 전체 변환된 문서를 저장합니다."
type: docs
url: /ko/python-net/groupdocs.conversion/converter/convert/
is_root: false
weight: 1010
---


## convert {#target_stream_provider-convert_options}

소스 문서를 변환하고 전체 변환된 문서를 저장합니다.

자세히 알아보기:
- More about document conversion basic scenarios: <https://docs.groupdocs.com/display/conversionnet/Convert+document>
- Conversion use cases, advanced settings and customizations: <https://docs.groupdocs.com/display/conversionnet/Converting>

```python
def convert(self, target_stream_provider, convert_options):
    ...
```

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| target_stream_provider | `Func[SaveContext, io.RawIOBase]` | 스트림을 받아 변환된 문서를 해당 스트림에 저장하는 호출 가능 객체. |
| convert_options | `ConvertOptions` | 원하는 대상 파일 형식에 특정한 변환 옵션. |

### 예제

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

def convert_document_to_pdf():
    # 입력 문서로 Converter를 인스턴스화합니다.
    with Converter("./business-plan.docx") as converter:
        # PDF 출력에 대한 변환 옵션을 정의합니다
        pdf_options = PdfConvertOptions()
        # 문서를 변환하여 PDF로 저장
        converter.convert("./business-plan.pdf", pdf_options)

if __name__ == "__main__":
    convert_document_to_pdf()
```

## convert {#convert_options-document_completed}

소스 문서를 변환하고 전체 변환된 문서를 저장합니다.

자세히 알아보기:
- More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
- Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

```python
def convert(self, convert_options, document_completed):
    ...
```

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| convert_options | `ConvertOptions` | 원하는 대상 파일 형식에 특정한 변환 옵션입니다. |
| document_completed | `Action[ConvertedContext]` | 변환된 문서 스트림을 받는 대리자. 서명: `Action<ConvertedContext>`. `ConvertedContext` 매개변수에는 변환된 문서 스트림과 메타데이터가 포함됩니다. |

### 예제

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with open("input.docx", "rb") as stream:
    with Converter(stream) as converter:
        converter.convert("output.pdf", PdfConvertOptions())
```

## convert {#target_stream_provider-convert_options_provider}

소스 문서를 변환하고 전체 변환된 문서를 저장합니다.

자세히 알아보기:
- More about document conversion basic scenarios: https://docs.groupdocs.com/display/conversionnet/Convert+document
- Conversion use cases, advanced settings and customizations: https://docs.groupdocs.com/display/conversionnet/Converting

```python
def convert(self, target_stream_provider, convert_options_provider):
    ...
```

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| target_stream_provider | `Func[SaveContext, io.RawIOBase]` | Callable[[SaveContext], io.RawIOBase] 은 변환된 문서를 저장하기 위한 스트림을 제공합니다. |
| convert_options_provider | `Func[ConvertContext, ConvertOptions]` | Callable[[ConvertContext], GroupDocs.Conversion.ConvertOptions] 은 변환 옵션을 제공합니다. |

**Returns:** None.

### 예제

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with open("input.docx", "rb") as stream:
    with Converter(stream) as converter:
        converter.convert(
            lambda ctx: open("output.pdf", "wb"),
            lambda ctx: PdfConvertOptions(),
            cancellationToken=None
        )
```

## convert {#convert_options_provider-document_completed}

소스 문서를 변환하고 전체 변환된 문서를 저장합니다.

자세히 알아보기

- More about document conversion basic scenarios: <https://docs.groupdocs.com/display/conversionnet/Convert+document>
- Conversion use cases, advanced settings and customizations: <https://docs.groupdocs.com/display/conversionnet/Converting>

```python
def convert(self, convert_options_provider, document_completed):
    ...
```

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| convert_options_provider | `Func[ConvertContext, ConvertOptions]` | Callable[[ConvertContext], GroupDocs.Conversion.ConvertOptions] 은 변환 옵션을 제공합니다. `ConvertContext` 매개변수에는 변환 작업에 대한 정보가 포함됩니다. |
| document_completed | `Action[ConvertedContext]` | Callable[[ConvertedContext], None] 은 변환된 문서 스트림을 수신합니다. `ConvertedContext` 매개변수에는 변환된 문서 스트림과 메타데이터가 포함됩니다. |

**Returns:** None.

## convert {#file_path-convert_options}

소스 문서를 변환하고 전체 변환된 문서를 저장합니다.

자세히 알아보기:
- More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
- Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

```python
def convert(self, file_path, convert_options):
    ...
```

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| file_path | `str` | 소스 문서의 파일 경로입니다. |
| convert_options | `ConvertOptions` | 원하는 대상 파일 형식에 특정한 변환 옵션입니다. |

### 예제

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with open("input.docx", "rb") as stream:
    with Converter(stream) as converter:
        converter.convert("output.pdf", PdfConvertOptions())
```

## convert {#target_stream_provider-convert_options_provider}

소스 문서를 변환하고 변환된 문서를 페이지별로 저장합니다.

자세히 알아보기

- More about document conversion basic scenarios: How to convert document in 3 steps (https://docs.groupdocs.com/display/conversionnet/Convert+document)
- Conversion use cases, advanced settings and customizations: Convert document with advanced settings (https://docs.groupdocs.com/display/conversionnet/Converting)

```python
def convert(self, target_stream_provider, convert_options_provider):
    ...
```

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| target_stream_provider | `Func[SavePageContext, io.RawIOBase]` | Callable[[SavePageContext], io.RawIOBase] 은 각 변환된 페이지를 저장하기 위한 스트림을 제공합니다. `SavePageContext` 매개변수에는 페이지 번호와 문서 정보가 포함됩니다. |
| convert_options_provider | `Func[ConvertContext, ConvertOptions]` | Callable[[ConvertContext], ConvertOptions] 은 변환 옵션을 제공합니다. `ConvertContext` 매개변수에는 변환 작업에 대한 정보가 포함됩니다. |

**Returns:** None.

## convert {#target_stream_provider-convert_options}

소스 문서를 변환하고 변환된 문서를 페이지별로 저장합니다.

자세히 알아보기
- More about document conversion basic scenarios: <https://docs.groupdocs.com/display/conversionnet/Convert+document>
- Conversion use cases, advanced settings and customizations: <https://docs.groupdocs.com/display/conversionnet/Converting>

```python
def convert(self, target_stream_provider, convert_options):
    ...
```

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| target_stream_provider | `Func[SavePageContext, io.RawIOBase]` | Callable 은 각 변환된 페이지를 저장하기 위한 스트림을 제공합니다. 시그니처: `Func<SavePageContext, Stream>`. `SavePageContext` 매개변수에는 페이지 번호와 문서 정보가 포함됩니다. |
| convert_options | `ConvertOptions` | 원하는 대상 파일 형식에 특정한 변환 옵션입니다. |

**Returns:** None.

### 예제

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with open("input.docx", "rb") as stream:
    with Converter(stream) as converter:
        converter.convert("output.pdf", PdfConvertOptions())
```

## convert {#convert_options-document_completed}

소스 문서를 변환하고 변환된 문서를 페이지별로 저장합니다.

자세히 알아보기

- More about document conversion basic scenarios: <https://docs.groupdocs.com/display/conversionnet/Convert+document>
- Conversion use cases, advanced settings and customizations: <https://docs.groupdocs.com/display/conversionnet/Converting>

```python
def convert(self, convert_options, document_completed):
    ...
```

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| convert_options | `ConvertOptions` | 원하는 대상 파일 형식에 특정한 변환 옵션입니다. |
| document_completed | `Action[ConvertedPageContext]` | Callable 은 각 변환된 페이지를 수신합니다. `ConvertedPageContext` 매개변수에는 페이지 번호, 스트림, 소스 파일 이름 및 대상 파일 형식이 포함됩니다. |

### 예제

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("./business-plan.docx") as converter:
    converter.convert("./business-plan.pdf", PdfConvertOptions())
```

## convert {#convert_options_provider-document_completed}

소스 문서를 변환하고 변환된 문서를 페이지별로 저장합니다.

자세히 알아보기

- More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
- Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

```python
def convert(self, convert_options_provider, document_completed):
    ...
```

| 매개변수 | 유형 | 설명 |
| :- | :- | :- |
| convert_options_provider | `Func[ConvertContext, ConvertOptions]` | Delegate 은 변환 옵션을 제공합니다. `ConvertContext` 매개변수에는 변환 작업에 대한 정보가 포함됩니다. |
| document_completed | `Action[ConvertedPageContext]` | Delegate 은 각 변환된 페이지를 수신합니다. `ConvertedPageContext` 매개변수에는 페이지 번호, 스트림, 소스 파일 이름 및 대상 파일 형식이 포함됩니다. |

### 예제

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with open("input.docx", "rb") as stream:
    with Converter(stream) as converter:
        converter.convert("output.pdf", PdfConvertOptions())
```

### 또 보기
* class [`Converter`](/conversion/python-net/groupdocs.conversion/converter/)
