---
title: "metode convert"
second_title: "Referensi API GroupDocs.Conversion untuk Python via .NET"
description: "Mengonversi dokumen sumber dan menyimpan seluruh dokumen yang telah dikonversi."
type: docs
url: /id/python-net/groupdocs.conversion/converter/convert/
is_root: false
weight: 1010
---


## convert {#target_stream_provider-convert_options}

Mengonversi dokumen sumber dan menyimpan seluruh dokumen yang telah dikonversi.

Pelajari lebih lanjut:
- More about document conversion basic scenarios: <https://docs.groupdocs.com/display/conversionnet/Convert+document>
- Conversion use cases, advanced settings and customizations: <https://docs.groupdocs.com/display/conversionnet/Converting>

```python
def convert(self, target_stream_provider, convert_options):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| target_stream_provider | `Func[SaveContext, io.RawIOBase]` | Callable yang menerima aliran dan menyimpan dokumen yang dikonversi ke dalamnya. |
| convert_options | `ConvertOptions` | Opsi konversi khusus untuk tipe file target yang diinginkan. |

### Contoh

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

def convert_document_to_pdf():
    # Buat instance Converter dengan dokumen input
    with Converter("./business-plan.docx") as converter:
        # Tentukan opsi konversi untuk output PDF
        pdf_options = PdfConvertOptions()
        # Konversi dokumen dan simpan sebagai PDF
        converter.convert("./business-plan.pdf", pdf_options)

if __name__ == "__main__":
    convert_document_to_pdf()
```

## convert {#convert_options-document_completed}

Mengonversi dokumen sumber dan menyimpan seluruh dokumen yang telah dikonversi.

Pelajari lebih lanjut:
- More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
- Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

```python
def convert(self, convert_options, document_completed):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| convert_options | `ConvertOptions` | Opsi konversi yang spesifik untuk tipe file target yang diinginkan. |
| document_completed | `Action[ConvertedContext]` | Delegasi yang menerima aliran dokumen yang telah dikonversi. Signature: `Action<ConvertedContext>`. Parameter `ConvertedContext` berisi aliran dokumen yang telah dikonversi dan metadata. |

### Contoh

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with open("input.docx", "rb") as stream:
    with Converter(stream) as converter:
        converter.convert("output.pdf", PdfConvertOptions())
```

## convert {#target_stream_provider-convert_options_provider}

Mengonversi dokumen sumber dan menyimpan seluruh dokumen yang telah dikonversi.

Pelajari lebih lanjut:
- More about document conversion basic scenarios: https://docs.groupdocs.com/display/conversionnet/Convert+document
- Conversion use cases, advanced settings and customizations: https://docs.groupdocs.com/display/conversionnet/Converting

```python
def convert(self, target_stream_provider, convert_options_provider):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| target_stream_provider | `Func[SaveContext, io.RawIOBase]` | `Callable[[SaveContext], io.RawIOBase]` yang menyediakan aliran untuk menyimpan dokumen yang telah dikonversi. |
| convert_options_provider | `Func[ConvertContext, ConvertOptions]` | `Callable[[ConvertContext], GroupDocs.Conversion.ConvertOptions]` yang menyediakan opsi konversi. |

**Returns:** None.

### Contoh

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

Mengonversi dokumen sumber dan menyimpan seluruh dokumen yang telah dikonversi.

Pelajari lebih lanjut

- More about document conversion basic scenarios: <https://docs.groupdocs.com/display/conversionnet/Convert+document>
- Conversion use cases, advanced settings and customizations: <https://docs.groupdocs.com/display/conversionnet/Converting>

```python
def convert(self, convert_options_provider, document_completed):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| convert_options_provider | `Func[ConvertContext, ConvertOptions]` | `Callable[[ConvertContext], GroupDocs.Conversion.ConvertOptions]` menyediakan opsi konversi. Parameter `ConvertContext` berisi informasi tentang operasi konversi. |
| document_completed | `Action[ConvertedContext]` | `Callable[[ConvertedContext], None]` menerima aliran dokumen yang telah dikonversi. Parameter `ConvertedContext` berisi aliran dokumen yang telah dikonversi dan metadata. |

**Returns:** None.

## convert {#file_path-convert_options}

Mengonversi dokumen sumber dan menyimpan seluruh dokumen yang telah dikonversi.

Pelajari lebih lanjut:
- More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
- Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

```python
def convert(self, file_path, convert_options):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| file_path | `str` | Jalur file ke dokumen sumber. |
| convert_options | `ConvertOptions` | Opsi konversi yang spesifik untuk tipe file target yang diinginkan. |

### Contoh

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with open("input.docx", "rb") as stream:
    with Converter(stream) as converter:
        converter.convert("output.pdf", PdfConvertOptions())
```

## convert {#target_stream_provider-convert_options_provider}

Mengonversi dokumen sumber dan menyimpan dokumen yang telah dikonversi halaman demi halaman.

Pelajari lebih lanjut

- More about document conversion basic scenarios: How to convert document in 3 steps (https://docs.groupdocs.com/display/conversionnet/Convert+document)
- Conversion use cases, advanced settings and customizations: Convert document with advanced settings (https://docs.groupdocs.com/display/conversionnet/Converting)

```python
def convert(self, target_stream_provider, convert_options_provider):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| target_stream_provider | `Func[SavePageContext, io.RawIOBase]` | `Callable[[SavePageContext], io.RawIOBase]` yang menyediakan aliran untuk menyimpan setiap halaman yang dikonversi. Parameter `SavePageContext` berisi nomor halaman dan informasi dokumen. |
| convert_options_provider | `Func[ConvertContext, ConvertOptions]` | `Callable[[ConvertContext], ConvertOptions]` yang menyediakan opsi konversi. Parameter `ConvertContext` berisi informasi tentang operasi konversi. |

**Returns:** None.

## convert {#target_stream_provider-convert_options}

Mengonversi dokumen sumber dan menyimpan dokumen yang telah dikonversi halaman demi halaman.

Pelajari lebih lanjut
- More about document conversion basic scenarios: <https://docs.groupdocs.com/display/conversionnet/Convert+document>
- Conversion use cases, advanced settings and customizations: <https://docs.groupdocs.com/display/conversionnet/Converting>

```python
def convert(self, target_stream_provider, convert_options):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| target_stream_provider | `Func[SavePageContext, io.RawIOBase]` | Callable yang menyediakan aliran untuk menyimpan setiap halaman yang dikonversi. Signature: `Func<SavePageContext, Stream>`. Parameter `SavePageContext` berisi nomor halaman dan informasi dokumen. |
| convert_options | `ConvertOptions` | Opsi konversi yang spesifik untuk tipe file target yang diinginkan. |

**Returns:** None.

### Contoh

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with open("input.docx", "rb") as stream:
    with Converter(stream) as converter:
        converter.convert("output.pdf", PdfConvertOptions())
```

## convert {#convert_options-document_completed}

Mengonversi dokumen sumber dan menyimpan dokumen yang telah dikonversi halaman demi halaman.

Pelajari lebih lanjut

- More about document conversion basic scenarios: <https://docs.groupdocs.com/display/conversionnet/Convert+document>
- Conversion use cases, advanced settings and customizations: <https://docs.groupdocs.com/display/conversionnet/Converting>

```python
def convert(self, convert_options, document_completed):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| convert_options | `ConvertOptions` | Opsi konversi yang spesifik untuk tipe file target yang diinginkan. |
| document_completed | `Action[ConvertedPageContext]` | Callable yang menerima setiap halaman yang dikonversi. Parameter `ConvertedPageContext` berisi nomor halaman, aliran, nama file sumber, dan tipe file target. |

### Contoh

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("./business-plan.docx") as converter:
    converter.convert("./business-plan.pdf", PdfConvertOptions())
```

## convert {#convert_options_provider-document_completed}

Mengonversi dokumen sumber dan menyimpan dokumen yang telah dikonversi halaman demi halaman.

Pelajari lebih lanjut

- More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
- Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

```python
def convert(self, convert_options_provider, document_completed):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| convert_options_provider | `Func[ConvertContext, ConvertOptions]` | Delegasi yang menyediakan opsi konversi. Parameter `ConvertContext` berisi informasi tentang operasi konversi. |
| document_completed | `Action[ConvertedPageContext]` | Delegasi yang menerima setiap halaman yang dikonversi. Parameter `ConvertedPageContext` berisi nomor halaman, aliran, nama file sumber, dan tipe file target. |

### Contoh

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with open("input.docx", "rb") as stream:
    with Converter(stream) as converter:
        converter.convert("output.pdf", PdfConvertOptions())
```

### Lihat Juga
* class [`Converter`](/conversion/python-net/groupdocs.conversion/converter/)
