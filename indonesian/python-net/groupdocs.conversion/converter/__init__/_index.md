---
title: "konstruktor __init__"
second_title: "Referensi API GroupDocs.Conversion untuk Python via .NET"
description: "Menginisialisasi sebuah instance baru dari Converter."
type: docs
url: /id/python-net/groupdocs.conversion/converter/__init__/
is_root: false
weight: 10
---


## __init__ {#source_stream_provider}

Menginisialisasi sebuah instance baru dari Converter.

- More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third‑party storage: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
- More about document loading options dependent on file type: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

```python
def __init__(self, source_stream_provider):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| source_stream_provider | `Func[io.RawIOBase]` | Metode yang mengembalikan aliran yang dapat dibaca. |

| Menaikkan | Deskripsi |
| :- | :- |
| `ValueError` | Dilempar ketika `source_stream_provider` bernilai None. |

### Contoh

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with open("input.docx", "rb") as stream:
    with Converter(stream) as converter:
        converter.convert("output.pdf", PdfConvertOptions())
```

## __init__ {#source_stream_provider-settings}

Menginisialisasi sebuah instance baru [`Converter`](/conversion/python-net/groupdocs.conversion/converter/).

Pelajari lebih lanjut

- More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third‑party storage: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
- More about document loading options dependent on file type: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

```python
def __init__(self, source_stream_provider, settings):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| source_stream_provider | `Func[io.RawIOBase]` | Metode yang mengembalikan aliran yang dapat dibaca. |
| settings | `Func[ConverterSettings]` | Pengaturan Converter. |

### Contoh

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("input.docx") as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

## __init__ {#source_stream_provider-load_options-settings}

Menginisialisasi sebuah instance baru [`Converter`](/conversion/python-net/groupdocs.conversion/converter/).

- More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third‑party storage: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
- More about document loading options dependent on file type: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

```python
def __init__(self, source_stream_provider, load_options, settings):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| source_stream_provider | `Func[io.RawIOBase]` | Callable yang mengembalikan stream `io.RawIOBase` yang dapat dibaca. |
| load_options | `Func[LoadContext, LoadOptions]` | Callable[[`LoadContext`], `GroupDocs.Conversion.LoadOptions`] yang menyediakan opsi pemuatan untuk dokumen. Parameter `LoadContext` berisi informasi tentang dokumen yang sedang dimuat. |
| settings | `Func[ConverterSettings]` | `ConverterSettings` yang menentukan pengaturan konverter. |

### Contoh

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with open("input.docx", "rb") as stream:
    with Converter(stream) as converter:
        converter.convert("output.pdf", PdfConvertOptions())
```

## __init__ {#source_stream_provider-load_options-settings-events}

Menginisialisasi Converter baru dengan peristiwa konversi eksplisit.

```python
def __init__(self, source_stream_provider, load_options, settings, events):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| source_stream_provider | `Func[io.RawIOBase]` | Callable yang mengembalikan stream yang dapat dibaca. |
| load_options | `Func[LoadContext, LoadOptions]` | Callable yang menyediakan opsi pemuatan untuk dokumen. |
| settings | `Func[ConverterSettings]` | Pengaturan konverter. |
| events | `Func[ConversionEvents]` | Callable yang menyediakan `ConversionEvents` teragregasi yang terdaftar selama masa hidup konverter. |

## __init__ {#source_stream_provider-settings-events}

Menginisialisasi sebuah instance Converter baru dengan peristiwa konversi eksplisit.

```python
def __init__(self, source_stream_provider, settings, events):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| source_stream_provider | `Func[io.RawIOBase]` | Callable yang mengembalikan stream yang dapat dibaca. |
| settings | `Func[ConverterSettings]` | Pengaturan konverter. |
| events | `Func[ConversionEvents]` | Delegate yang menyediakan `ConversionEvents` teragregasi yang terdaftar selama masa hidup konverter. |

### Contoh

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with open("input.docx", "rb") as stream:
    with Converter(stream) as converter:
        converter.convert("output.pdf", PdfConvertOptions())
```

## __init__ {#file_path}

Menginisialisasi sebuah instance Converter baru.

- More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third‑party storage: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
- More about document loading options dependent on file type: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

```python
def __init__(self, file_path):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| file_path | `str` | Jalur file ke dokumen sumber. |

### Contoh

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("input.docx") as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

## __init__ {#file_path-settings}

Menginisialisasi sebuah instance baru [`Converter`](/conversion/python-net/groupdocs.conversion/converter/).

Pelajari lebih lanjut

- More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third‑party storage: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
- More about document loading options dependent on file type: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

```python
def __init__(self, file_path, settings):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| file_path | `str` | Jalur file ke dokumen sumber. |
| settings | `Func[ConverterSettings]` | Pengaturan Converter. |

### Contoh

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("input.docx") as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

## __init__ {#file_path-load_options-settings}

Menginisialisasi instance baru kelas [`Converter`](/conversion/python-net/groupdocs.conversion/converter/).

Pelajari lebih lanjut

- More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third‑party storage: <https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources>
- More about document loading options dependent on file type: <https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types>

```python
def __init__(self, file_path, load_options, settings):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| file_path | `str` | Jalur file ke dokumen sumber. |
| load_options | `Func[LoadContext, LoadOptions]` | Delegate yang menyediakan opsi pemuatan untuk dokumen. Tanda tangan: `Func<LoadContext, LoadOptions>`. Parameter `LoadContext` berisi informasi tentang dokumen yang sedang dimuat. |
| settings | `Func[ConverterSettings]` | Pengaturan Converter. |

### Contoh

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("input.docx") as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

## __init__ {#file_path-load_options-settings-events}

Menginisialisasi Converter baru dengan peristiwa konversi eksplisit.

```python
def __init__(self, file_path, load_options, settings, events):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| file_path | `str` | Jalur file ke dokumen sumber. |
| load_options | `Func[LoadContext, LoadOptions]` | Delegate yang menyediakan opsi pemuatan untuk dokumen. |
| settings | `Func[ConverterSettings]` | Pengaturan Converter. |
| events | `Func[ConversionEvents]` | Delegate yang menyediakan `ConversionEvents` teragregasi yang terdaftar selama masa hidup konverter. |

### Contoh

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("input.docx") as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

## __init__ {#file_path-settings-events}

Menginisialisasi Converter baru dengan peristiwa konversi eksplisit.

```python
def __init__(self, file_path, settings, events):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| file_path | `str` | Jalur file ke dokumen sumber. |
| settings | `Func[ConverterSettings]` | Pengaturan Converter. |
| events | `Func[ConversionEvents]` | Delegate yang menyediakan ConversionEvents teragregasi yang terdaftar selama masa hidup konverter. |

### Contoh

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("input.docx") as converter:
    converter.convert("output.pdf", PdfConvertOptions())
```

### Lihat Juga
* class [`Converter`](/conversion/python-net/groupdocs.conversion/converter/)
