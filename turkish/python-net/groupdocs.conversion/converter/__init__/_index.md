---
title: "__init__ yapıcı"
second_title: "GroupDocs.Conversion for Python via .NET API Referansları"
description: "Converter'ın yeni bir örneğini başlatır."
type: docs
url: /tr/python-net/groupdocs.conversion/converter/__init__/
is_root: false
weight: 10
---


## __init__ {#source_stream_provider}

Converter'ın yeni bir örneğini başlatır.

- More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third‑party storage: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
- More about document loading options dependent on file type: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

```python
def __init__(self, source_stream_provider):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| source_stream_provider | `Func[io.RawIOBase]` | Okunabilir bir akış döndüren yöntem. |

| Kaldırır | Açıklama |
| :- | :- |
| `ValueError` | `source_stream_provider` None olduğunda fırlatılır. |

### Örnek

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with open("input.docx", "rb") as stream:
    with Converter(stream) as converter:
        converter.convert("output.pdf", PdfConvertOptions())
```

## __init__ {#source_stream_provider-settings}

Yeni bir [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) örneğini başlatır.

Daha fazla bilgi edinin

- More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third‑party storage: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
- More about document loading options dependent on file type: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

```python
def __init__(self, source_stream_provider, settings):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| source_stream_provider | `Func[io.RawIOBase]` | Okunabilir bir akış döndüren yöntem. |
| settings | `Func[ConverterSettings]` | Dönüştürücü ayarları. |

### Örnek

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("input.docx") as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

## __init__ {#source_stream_provider-load_options-settings}

Yeni bir [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) örneğini başlatır.

- More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third‑party storage: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
- More about document loading options dependent on file type: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

```python
def __init__(self, source_stream_provider, load_options, settings):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| source_stream_provider | `Func[io.RawIOBase]` | Okunabilir bir `io.RawIOBase` akışı döndüren çağrılabilir. |
| load_options | `Func[LoadContext, LoadOptions]` | Callable[[`LoadContext`], `GroupDocs.Conversion.LoadOptions`] belge için yükleme seçenekleri sağlayan bir çağrılabilir. `LoadContext` parametresi, yüklenen belge hakkında bilgi içerir. |
| settings | `Func[ConverterSettings]` | `ConverterSettings` dönüştürücü ayarlarını belirten. |

### Örnek

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with open("input.docx", "rb") as stream:
    with Converter(stream) as converter:
        converter.convert("output.pdf", PdfConvertOptions())
```

## __init__ {#source_stream_provider-load_options-settings-events}

Açık dönüşüm olaylarıyla yeni bir Converter'ı başlatır.

```python
def __init__(self, source_stream_provider, load_options, settings, events):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| source_stream_provider | `Func[io.RawIOBase]` | Okunabilir bir akış döndüren çağrılabilir. |
| load_options | `Func[LoadContext, LoadOptions]` | Belge için yükleme seçenekleri sağlayan çağrılabilir. |
| settings | `Func[ConverterSettings]` | Dönüştürücü ayarları. |
| events | `Func[ConversionEvents]` | Dönüştürücünün ömrü boyunca kaydedilen toplu `ConversionEvents` sağlayan çağrılabilir. |

## __init__ {#source_stream_provider-settings-events}

Açık dönüşüm olaylarıyla yeni bir Converter örneğini başlatır.

```python
def __init__(self, source_stream_provider, settings, events):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| source_stream_provider | `Func[io.RawIOBase]` | Okunabilir bir akış döndüren çağrılabilir. |
| settings | `Func[ConverterSettings]` | Dönüştürücü ayarları. |
| events | `Func[ConversionEvents]` | Dönüştürücünün ömrü boyunca kaydedilen toplu `ConversionEvents` sağlayan temsilci. |

### Örnek

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with open("input.docx", "rb") as stream:
    with Converter(stream) as converter:
        converter.convert("output.pdf", PdfConvertOptions())
```

## __init__ {#file_path}

Yeni bir Converter örneğini başlatır.

- More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third‑party storage: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
- More about document loading options dependent on file type: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

```python
def __init__(self, file_path):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| file_path | `str` | Kaynak belgenin dosya yolu. |

### Örnek

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("input.docx") as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

## __init__ {#file_path-settings}

Yeni bir [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) örneğini başlatır.

Daha fazla bilgi edinin

- More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third‑party storage: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
- More about document loading options dependent on file type: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

```python
def __init__(self, file_path, settings):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| file_path | `str` | Kaynak belgenin dosya yolu. |
| settings | `Func[ConverterSettings]` | Dönüştürücü ayarları. |

### Örnek

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("input.docx") as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

## __init__ {#file_path-load_options-settings}

Yeni bir [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) sınıfının örneğini başlatır.

Daha fazla bilgi edinin

- More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third‑party storage: <https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources>
- More about document loading options dependent on file type: <https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types>

```python
def __init__(self, file_path, load_options, settings):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| file_path | `str` | Kaynak belgenin dosya yolu. |
| load_options | `Func[LoadContext, LoadOptions]` | Belge için yükleme seçenekleri sağlayan temsilci. İmza: `Func<LoadContext, LoadOptions>`. `LoadContext` parametresi, yüklenen belge hakkında bilgi içerir. |
| settings | `Func[ConverterSettings]` | Dönüştürücü ayarları. |

### Örnek

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("input.docx") as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

## __init__ {#file_path-load_options-settings-events}

Açık dönüşüm olaylarıyla yeni bir Converter'ı başlatır.

```python
def __init__(self, file_path, load_options, settings, events):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| file_path | `str` | Kaynak belgenin dosya yolu. |
| load_options | `Func[LoadContext, LoadOptions]` | Belge için yükleme seçenekleri sağlayan temsilci. |
| settings | `Func[ConverterSettings]` | Dönüştürücü ayarları. |
| events | `Func[ConversionEvents]` | Dönüştürücünün ömrü boyunca kaydedilen toplu `ConversionEvents` sağlayan temsilci. |

### Örnek

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("input.docx") as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

## __init__ {#file_path-settings-events}

Açık dönüşüm olaylarıyla yeni bir Converter'ı başlatır.

```python
def __init__(self, file_path, settings, events):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| file_path | `str` | Kaynak belgenin dosya yolu. |
| settings | `Func[ConverterSettings]` | Dönüştürücü ayarları. |
| events | `Func[ConversionEvents]` | Dönüştürücünün ömrü boyunca kaydedilen toplu ConversionEvents sağlayan temsilci. |

### Örnek

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("input.docx") as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

### Ayrıca Bakınız
* class [`Converter`](/conversion/python-net/groupdocs.conversion/converter/)
