---
title: "convert メソッド"
second_title: "GroupDocs.Conversion for Python via .NET API リファレンス"
description: "ソースドキュメントを変換し、変換されたドキュメント全体を保存します。"
type: docs
url: /ja/python-net/groupdocs.conversion/converter/convert/
is_root: false
weight: 1010
---


## convert {#target_stream_provider-convert_options}

ソースドキュメントを変換し、変換されたドキュメント全体を保存します。

詳しく見る:
- More about document conversion basic scenarios: <https://docs.groupdocs.com/display/conversionnet/Convert+document>
- Conversion use cases, advanced settings and customizations: <https://docs.groupdocs.com/display/conversionnet/Converting>

```python
def convert(self, target_stream_provider, convert_options):
    ...
```

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| target_stream_provider | `Func[SaveContext, io.RawIOBase]` | ストリームを受け取り、変換されたドキュメントをそれに保存する Callable。 |
| convert_options | `ConvertOptions` | 目的のターゲットファイルタイプに固有の変換オプション。 |

### 例

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

def convert_document_to_pdf():
    # 入力ドキュメントで Converter をインスタンス化します
    with Converter("./business-plan.docx") as converter:
        # PDF 出力の変換オプションを定義する
        pdf_options = PdfConvertOptions()
        # ドキュメントを変換して PDF として保存する
        converter.convert("./business-plan.pdf", pdf_options)

if __name__ == "__main__":
    convert_document_to_pdf()
```

## convert {#convert_options-document_completed}

ソースドキュメントを変換し、変換されたドキュメント全体を保存します。

詳しく見る:
- More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
- Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

```python
def convert(self, convert_options, document_completed):
    ...
```

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| convert_options | `ConvertOptions` | 目的のターゲットファイルタイプに固有の変換オプションです。 |
| document_completed | `Action[ConvertedContext]` | 変換されたドキュメントストリームを受け取る Delegate。シグネチャ: `Action<ConvertedContext>`。`ConvertedContext` パラメータには変換されたドキュメントストリームとメタデータが含まれます。 |

### 例

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with open("input.docx", "rb") as stream:
    with Converter(stream) as converter:
        converter.convert("output.pdf", PdfConvertOptions())
```

## convert {#target_stream_provider-convert_options_provider}

ソースドキュメントを変換し、変換されたドキュメント全体を保存します。

詳しく見る:
- More about document conversion basic scenarios: https://docs.groupdocs.com/display/conversionnet/Convert+document
- Conversion use cases, advanced settings and customizations: https://docs.groupdocs.com/display/conversionnet/Converting

```python
def convert(self, target_stream_provider, convert_options_provider):
    ...
```

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| target_stream_provider | `Func[SaveContext, io.RawIOBase]` | Callable[[SaveContext], io.RawIOBase] は変換されたドキュメントを保存するためのストリームを提供します。 |
| convert_options_provider | `Func[ConvertContext, ConvertOptions]` | Callable[[ConvertContext], GroupDocs.Conversion.ConvertOptions] は変換オプションを提供します。 |

**Returns:** None.

### 例

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

ソースドキュメントを変換し、変換されたドキュメント全体を保存します。

詳細を見る

- More about document conversion basic scenarios: <https://docs.groupdocs.com/display/conversionnet/Convert+document>
- Conversion use cases, advanced settings and customizations: <https://docs.groupdocs.com/display/conversionnet/Converting>

```python
def convert(self, convert_options_provider, document_completed):
    ...
```

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| convert_options_provider | `Func[ConvertContext, ConvertOptions]` | Callable[[ConvertContext], GroupDocs.Conversion.ConvertOptions] は変換オプションを提供します。`ConvertContext` パラメーターには変換操作に関する情報が含まれます。 |
| document_completed | `Action[ConvertedContext]` | Callable[[ConvertedContext], None] は変換されたドキュメントのストリームを受け取ります。`ConvertedContext` パラメーターには変換されたドキュメントのストリームとメタデータが含まれます。 |

**Returns:** None.

## convert {#file_path-convert_options}

ソースドキュメントを変換し、変換されたドキュメント全体を保存します。

詳しく見る:
- More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
- Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

```python
def convert(self, file_path, convert_options):
    ...
```

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| file_path | `str` | ソースドキュメントへのファイルパスです。 |
| convert_options | `ConvertOptions` | 目的のターゲットファイルタイプに固有の変換オプションです。 |

### 例

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with open("input.docx", "rb") as stream:
    with Converter(stream) as converter:
        converter.convert("output.pdf", PdfConvertOptions())
```

## convert {#target_stream_provider-convert_options_provider}

ソースドキュメントを変換し、変換されたドキュメントをページ単位で保存します。

詳細を見る

- More about document conversion basic scenarios: How to convert document in 3 steps (https://docs.groupdocs.com/display/conversionnet/Convert+document)
- Conversion use cases, advanced settings and customizations: Convert document with advanced settings (https://docs.groupdocs.com/display/conversionnet/Converting)

```python
def convert(self, target_stream_provider, convert_options_provider):
    ...
```

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| target_stream_provider | `Func[SavePageContext, io.RawIOBase]` | Callable[[SavePageContext], io.RawIOBase] は各変換ページを保存するためのストリームを提供します。`SavePageContext` パラメーターにはページ番号とドキュメント情報が含まれます。 |
| convert_options_provider | `Func[ConvertContext, ConvertOptions]` | Callable[[ConvertContext], ConvertOptions] は変換オプションを提供します。`ConvertContext` パラメーターには変換操作に関する情報が含まれます。 |

**Returns:** None.

## convert {#target_stream_provider-convert_options}

ソースドキュメントを変換し、変換されたドキュメントをページ単位で保存します。

詳細を見る
- More about document conversion basic scenarios: <https://docs.groupdocs.com/display/conversionnet/Convert+document>
- Conversion use cases, advanced settings and customizations: <https://docs.groupdocs.com/display/conversionnet/Converting>

```python
def convert(self, target_stream_provider, convert_options):
    ...
```

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| target_stream_provider | `Func[SavePageContext, io.RawIOBase]` | Callable は各変換ページを保存するためのストリームを提供します。シグネチャ: `Func<SavePageContext, Stream>`。`SavePageContext` パラメーターにはページ番号とドキュメント情報が含まれます。 |
| convert_options | `ConvertOptions` | 目的のターゲットファイルタイプに固有の変換オプションです。 |

**Returns:** None.

### 例

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with open("input.docx", "rb") as stream:
    with Converter(stream) as converter:
        converter.convert("output.pdf", PdfConvertOptions())
```

## convert {#convert_options-document_completed}

ソースドキュメントを変換し、変換されたドキュメントをページ単位で保存します。

詳細を見る

- More about document conversion basic scenarios: <https://docs.groupdocs.com/display/conversionnet/Convert+document>
- Conversion use cases, advanced settings and customizations: <https://docs.groupdocs.com/display/conversionnet/Converting>

```python
def convert(self, convert_options, document_completed):
    ...
```

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| convert_options | `ConvertOptions` | 目的のターゲットファイルタイプに固有の変換オプションです。 |
| document_completed | `Action[ConvertedPageContext]` | Callable は各変換ページを受け取ります。`ConvertedPageContext` パラメーターにはページ番号、ストリーム、ソースファイル名、ターゲットファイルタイプが含まれます。 |

### 例

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("./business-plan.docx") as converter:
    converter.convert("./business-plan.pdf", PdfConvertOptions())
```

## convert {#convert_options_provider-document_completed}

ソースドキュメントを変換し、変換されたドキュメントをページ単位で保存します。

詳細を見る

- More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
- Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

```python
def convert(self, convert_options_provider, document_completed):
    ...
```

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| convert_options_provider | `Func[ConvertContext, ConvertOptions]` | Delegate は変換オプションを提供します。`ConvertContext` パラメーターには変換操作に関する情報が含まれます。 |
| document_completed | `Action[ConvertedPageContext]` | Delegate は各変換ページを受け取ります。`ConvertedPageContext` パラメーターにはページ番号、ストリーム、ソースファイル名、ターゲットファイルタイプが含まれます。 |

### 例

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with open("input.docx", "rb") as stream:
    with Converter(stream) as converter:
        converter.convert("output.pdf", PdfConvertOptions())
```

### 関連項目
* class [`Converter`](/conversion/python-net/groupdocs.conversion/converter/)
