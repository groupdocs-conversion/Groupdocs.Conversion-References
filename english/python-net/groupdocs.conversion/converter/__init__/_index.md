---
title: __init__ constructor
second_title: GroupDocs.Conversion for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.conversion/converter/__init__/
is_root: false
weight: 10
---


## __init__ {#file_path}

Initializes a new instance of [`Converter`](/conversion/python-net/groupdocs.conversion/converter/).

Learn more

- More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third‑party storage: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
- More about document loading options dependent on file type: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

```python
def __init__(self, file_path):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | `str` | The file path to the source document. |

## __init__ {#source_stream_provider}

Initializes new instance of Converter class.

Learn more

- More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
- More about document loading options dependent on file type: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

```python
def __init__(self, source_stream_provider):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| source_stream_provider | `System.Func`1[[System.IO.Stream, System.Private.CoreLib, Version=10.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]]` | The method that returns readable stream. |

| Raises | Description |
| :- | :- |
| `ValueError` | Raised when `source_stream_provider` is None. |

## __init__ {#source_stream_provider-settings}

Initializes a new instance of [`Converter`](/conversion/python-net/groupdocs.conversion/converter/).

Learn more

- More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third‑party storage: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
- More about document loading options dependent on file type: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

```python
def __init__(self, source_stream_provider, settings):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| source_stream_provider | `System.Func`1[[System.IO.Stream, System.Private.CoreLib, Version=10.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]]` | The method that returns readable stream. |
| settings | `System.Func`1[[GroupDocs.Conversion.ConverterSettings, GroupDocs.Conversion, Version=26.3.0.0, Culture=neutral, PublicKeyToken=716fcc553a201e56]]` | The Converter settings. |

## __init__ {#file_path-settings}

Initializes a new instance of [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) class.

Learn more

- More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
- More about document loading options dependent on file type: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

```python
def __init__(self, file_path, settings):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | `str` | The file path to the source document. |
| settings | `System.Func`1[[GroupDocs.Conversion.ConverterSettings, GroupDocs.Conversion, Version=26.3.0.0, Culture=neutral, PublicKeyToken=716fcc553a201e56]]` | The Converter settings. |

## __init__ {#source_stream_provider-load_options-settings}

Initializes new instance of Converter class.

Learn more

- More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
- More about document loading options dependent on file type: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

```python
def __init__(self, source_stream_provider, load_options, settings):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| source_stream_provider | `System.Func`1[[System.IO.Stream, System.Private.CoreLib, Version=10.0.0.0, Culture=neutral, PublicKeyToken=7cec85d7bea7798e]]` | The method that returns readable stream. |
| load_options | `System.Func`2[[GroupDocs.Conversion.LoadContext, GroupDocs.Conversion, Version=26.3.0.0, Culture=neutral, PublicKeyToken=716fcc553a201e56],[GroupDocs.Conversion.Options.Load.LoadOptions, GroupDocs.Conversion, Version=26.3.0.0, Culture=neutral, PublicKeyToken=716fcc553a201e56]]` | Delegate that provides load options for the document. Signature: `Func<LoadContext, LoadOptions>`. The `LoadContext` parameter contains information about the document being loaded. |
| settings | `System.Func`1[[GroupDocs.Conversion.ConverterSettings, GroupDocs.Conversion, Version=26.3.0.0, Culture=neutral, PublicKeyToken=716fcc553a201e56]]` | The Converter settings. |

## __init__ {#file_path-load_options-settings}

Initializes a new instance of [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) class.

Learn more

- More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third‑party storage: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
- More about document loading options dependent on file type: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

```python
def __init__(self, file_path, load_options, settings):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | `str` | The file path to the source document. |
| load_options | `System.Func`2[[GroupDocs.Conversion.LoadContext, GroupDocs.Conversion, Version=26.3.0.0, Culture=neutral, PublicKeyToken=716fcc553a201e56],[GroupDocs.Conversion.Options.Load.LoadOptions, GroupDocs.Conversion, Version=26.3.0.0, Culture=neutral, PublicKeyToken=716fcc553a201e56]]` | Delegate that provides load options for the document. Signature: `Func<LoadContext, LoadOptions>`. The `LoadContext` parameter contains information about the document being loaded. |
| settings | `System.Func`1[[GroupDocs.Conversion.ConverterSettings, GroupDocs.Conversion, Version=26.3.0.0, Culture=neutral, PublicKeyToken=716fcc553a201e56]]` | The Converter settings. |

### See Also
* class [`Converter`](/conversion/python-net/groupdocs.conversion/converter/)
