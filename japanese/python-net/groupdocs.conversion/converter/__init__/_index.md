---
title: "__init__ コンストラクタ"
second_title: "GroupDocs.Conversion for Python via .NET API リファレンス"
description: "Converter の新しいインスタンスを初期化します。"
type: docs
url: /ja/python-net/groupdocs.conversion/converter/__init__/
is_root: false
weight: 10
---


## __init__ {#source_stream_provider}

Converter の新しいインスタンスを初期化します。

- More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third‑party storage: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
- More about document loading options dependent on file type: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

```python
def __init__(self, source_stream_provider):
    ...
```

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| source_stream_provider | `Func[io.RawIOBase]` | 読み取り可能なストリームを返すメソッドです。 |

| 例外を発生させます | 説明 |
| :- | :- |
| `ValueError` | `source_stream_provider` が None のときに発生します。 |

### 例

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with open("input.docx", "rb") as stream:
    with Converter(stream) as converter:
        converter.convert("output.pdf", PdfConvertOptions())
```

## __init__ {#source_stream_provider-settings}

新しい [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) インスタンスを初期化します。

詳細を見る

- More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third‑party storage: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
- More about document loading options dependent on file type: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

```python
def __init__(self, source_stream_provider, settings):
    ...
```

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| source_stream_provider | `Func[io.RawIOBase]` | 読み取り可能なストリームを返すメソッドです。 |
| settings | `Func[ConverterSettings]` | Converter の設定です。 |

### 例

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("input.docx") as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

## __init__ {#source_stream_provider-load_options-settings}

新しい [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) インスタンスを初期化します。

- More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third‑party storage: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
- More about document loading options dependent on file type: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

```python
def __init__(self, source_stream_provider, load_options, settings):
    ...
```

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| source_stream_provider | `Func[io.RawIOBase]` | 読み取り可能な `io.RawIOBase` ストリームを返す Callable。 |
| load_options | `Func[LoadContext, LoadOptions]` | ドキュメントのロードオプションを提供する Callable[[`LoadContext`], `GroupDocs.Conversion.LoadOptions`]。`LoadContext` パラメータには、ロード中のドキュメントに関する情報が含まれます。 |
| settings | `Func[ConverterSettings]` | `ConverterSettings` がコンバータ設定を指定します。 |

### 例

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with open("input.docx", "rb") as stream:
    with Converter(stream) as converter:
        converter.convert("output.pdf", PdfConvertOptions())
```

## __init__ {#source_stream_provider-load_options-settings-events}

明示的な変換イベントを使用して新しい Converter を初期化します。

```python
def __init__(self, source_stream_provider, load_options, settings, events):
    ...
```

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| source_stream_provider | `Func[io.RawIOBase]` | 読み取り可能なストリームを返す Callable。 |
| load_options | `Func[LoadContext, LoadOptions]` | ドキュメントのロードオプションを提供する Callable。 |
| settings | `Func[ConverterSettings]` | コンバータ設定。 |
| events | `Func[ConversionEvents]` | コンバータのライフタイムで登録された集約 `ConversionEvents` を提供する Callable。 |

## __init__ {#source_stream_provider-settings-events}

明示的な変換イベントを使用して新しい Converter インスタンスを初期化します。

```python
def __init__(self, source_stream_provider, settings, events):
    ...
```

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| source_stream_provider | `Func[io.RawIOBase]` | 読み取り可能なストリームを返す Callable。 |
| settings | `Func[ConverterSettings]` | コンバータ設定。 |
| events | `Func[ConversionEvents]` | コンバータのライフタイムで登録された集約 `ConversionEvents` を提供する Delegate。 |

### 例

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with open("input.docx", "rb") as stream:
    with Converter(stream) as converter:
        converter.convert("output.pdf", PdfConvertOptions())
```

## __init__ {#file_path}

新しい Converter インスタンスを初期化します。

- More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third‑party storage: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
- More about document loading options dependent on file type: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

```python
def __init__(self, file_path):
    ...
```

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| file_path | `str` | ソースドキュメントへのファイルパスです。 |

### 例

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("input.docx") as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

## __init__ {#file_path-settings}

新しい [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) インスタンスを初期化します。

詳細を見る

- More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third‑party storage: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
- More about document loading options dependent on file type: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

```python
def __init__(self, file_path, settings):
    ...
```

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| file_path | `str` | ソースドキュメントへのファイルパスです。 |
| settings | `Func[ConverterSettings]` | Converter の設定です。 |

### 例

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("input.docx") as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

## __init__ {#file_path-load_options-settings}

新しい [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) クラスのインスタンスを初期化します。

詳細を見る

- More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third‑party storage: <https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources>
- More about document loading options dependent on file type: <https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types>

```python
def __init__(self, file_path, load_options, settings):
    ...
```

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| file_path | `str` | ソースドキュメントへのファイルパスです。 |
| load_options | `Func[LoadContext, LoadOptions]` | ドキュメントのロードオプションを提供する Delegate。シグネチャ: `Func<LoadContext, LoadOptions>`。`LoadContext` パラメータには、ロード中のドキュメントに関する情報が含まれます。 |
| settings | `Func[ConverterSettings]` | Converter の設定です。 |

### 例

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("input.docx") as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

## __init__ {#file_path-load_options-settings-events}

明示的な変換イベントを使用して新しい Converter を初期化します。

```python
def __init__(self, file_path, load_options, settings, events):
    ...
```

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| file_path | `str` | ソースドキュメントへのファイルパスです。 |
| load_options | `Func[LoadContext, LoadOptions]` | ドキュメントのロードオプションを提供する Delegate。 |
| settings | `Func[ConverterSettings]` | Converter の設定です。 |
| events | `Func[ConversionEvents]` | コンバータのライフタイムで登録された集約 `ConversionEvents` を提供する Delegate。 |

### 例

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("input.docx") as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

## __init__ {#file_path-settings-events}

明示的な変換イベントを使用して新しい Converter を初期化します。

```python
def __init__(self, file_path, settings, events):
    ...
```

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| file_path | `str` | ソースドキュメントへのファイルパスです。 |
| settings | `Func[ConverterSettings]` | Converter の設定です。 |
| events | `Func[ConversionEvents]` | コンバータのライフタイムで登録された集約 ConversionEvents を提供する Delegate。 |

### 例

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("input.docx") as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

### 関連項目
* class [`Converter`](/conversion/python-net/groupdocs.conversion/converter/)
