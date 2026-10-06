---
title: "convert yöntemi"
second_title: "GroupDocs.Conversion for Python via .NET API Referansları"
description: "Kaynak belgeyi dönüştürür ve dönüştürülmüş belgenin tamamını kaydeder."
type: docs
url: /tr/python-net/groupdocs.conversion/converter/convert/
is_root: false
weight: 1010
---


## convert {#target_stream_provider-convert_options}

Kaynak belgeyi dönüştürür ve dönüştürülmüş belgenin tamamını kaydeder.

Daha fazla bilgi edinin:
- More about document conversion basic scenarios: <https://docs.groupdocs.com/display/conversionnet/Convert+document>
- Conversion use cases, advanced settings and customizations: <https://docs.groupdocs.com/display/conversionnet/Converting>

```python
def convert(self, target_stream_provider, convert_options):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| target_stream_provider | `Func[SaveContext, io.RawIOBase]` | Bir stream alan ve dönüştürülmüş belgeyi ona kaydeden çağrılabilir. |
| convert_options | `ConvertOptions` | İstenen hedef dosya türüne özgü dönüştürme seçenekleri. |

### Örnek

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

def convert_document_to_pdf():
    # Dönüştürücüyü giriş belgesiyle örnekleyin
    with Converter("./business-plan.docx") as converter:
        # PDF çıktısı için dönüşüm seçeneklerini tanımla
        pdf_options = PdfConvertOptions()
        # Belgeyi dönüştür ve PDF olarak kaydet
        converter.convert("./business-plan.pdf", pdf_options)

if __name__ == "__main__":
    convert_document_to_pdf()
```

## convert {#convert_options-document_completed}

Kaynak belgeyi dönüştürür ve dönüştürülmüş belgenin bütününü kaydeder.

Daha fazla bilgi edinin:
- More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
- Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

```python
def convert(self, convert_options, document_completed):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| convert_options | `ConvertOptions` | İstenen hedef dosya türüne özgü dönüştürme seçenekleri. |
| document_completed | `Action[ConvertedContext]` | Dönüştürülmüş belge akışını alan delege. İmza: `Action<ConvertedContext>`. `ConvertedContext` parametresi dönüştürülmüş belge akışını ve meta verileri içerir. |

### Örnek

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with open("input.docx", "rb") as stream:
    with Converter(stream) as converter:
        converter.convert("output.pdf", PdfConvertOptions())
```

## convert {#target_stream_provider-convert_options_provider}

Kaynak belgeyi dönüştürür ve dönüştürülmüş belgenin bütününü kaydeder.

Daha fazla bilgi edinin:
- More about document conversion basic scenarios: https://docs.groupdocs.com/display/conversionnet/Convert+document
- Conversion use cases, advanced settings and customizations: https://docs.groupdocs.com/display/conversionnet/Converting

```python
def convert(self, target_stream_provider, convert_options_provider):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| target_stream_provider | `Func[SaveContext, io.RawIOBase]` | Dönüştürülmüş belgeyi kaydetmek için akışı sağlayan `Callable[[SaveContext], io.RawIOBase]`. |
| convert_options_provider | `Func[ConvertContext, ConvertOptions]` | `Callable[[ConvertContext], GroupDocs.Conversion.ConvertOptions]` dönüştürme seçeneklerini sağlar. |

**Returns:** None.

### Örnek

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

Kaynak belgeyi dönüştürür ve dönüştürülmüş belgenin bütününü kaydeder.

Daha fazla bilgi edinin

- More about document conversion basic scenarios: <https://docs.groupdocs.com/display/conversionnet/Convert+document>
- Conversion use cases, advanced settings and customizations: <https://docs.groupdocs.com/display/conversionnet/Converting>

```python
def convert(self, convert_options_provider, document_completed):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| convert_options_provider | `Func[ConvertContext, ConvertOptions]` | `Callable[[ConvertContext], GroupDocs.Conversion.ConvertOptions]` dönüştürme seçeneklerini sağlar. `ConvertContext` parametresi dönüşüm işlemi hakkında bilgi içerir. |
| document_completed | `Action[ConvertedContext]` | `Callable[[ConvertedContext], None]` dönüştürülmüş belge akışını alır. `ConvertedContext` parametresi dönüştürülmüş belge akışını ve meta verileri içerir. |

**Returns:** None.

## convert {#file_path-convert_options}

Kaynak belgeyi dönüştürür ve dönüştürülmüş belgenin bütününü kaydeder.

Daha fazla bilgi edinin:
- More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
- Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

```python
def convert(self, file_path, convert_options):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| file_path | `str` | Kaynak belgenin dosya yolu. |
| convert_options | `ConvertOptions` | İstenen hedef dosya türüne özgü dönüştürme seçenekleri. |

### Örnek

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with open("input.docx", "rb") as stream:
    with Converter(stream) as converter:
        converter.convert("output.pdf", PdfConvertOptions())
```

## convert {#target_stream_provider-convert_options_provider}

Kaynak belgeyi dönüştürür ve dönüştürülmüş belgeyi sayfa sayfa kaydeder.

Daha fazla bilgi edinin

- More about document conversion basic scenarios: How to convert document in 3 steps (https://docs.groupdocs.com/display/conversionnet/Convert+document)
- Conversion use cases, advanced settings and customizations: Convert document with advanced settings (https://docs.groupdocs.com/display/conversionnet/Converting)

```python
def convert(self, target_stream_provider, convert_options_provider):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| target_stream_provider | `Func[SavePageContext, io.RawIOBase]` | `Callable[[SavePageContext], io.RawIOBase]` her dönüştürülmüş sayfayı kaydetmek için bir akış sağlar. `SavePageContext` parametresi sayfa numarasını ve belge bilgilerini içerir. |
| convert_options_provider | `Func[ConvertContext, ConvertOptions]` | `Callable[[ConvertContext], ConvertOptions]` dönüştürme seçeneklerini sağlar. `ConvertContext` parametresi dönüşüm işlemi hakkında bilgi içerir. |

**Returns:** None.

## convert {#target_stream_provider-convert_options}

Kaynak belgeyi dönüştürür ve dönüştürülmüş belgeyi sayfa sayfa kaydeder.

Daha fazla bilgi edinin
- More about document conversion basic scenarios: <https://docs.groupdocs.com/display/conversionnet/Convert+document>
- Conversion use cases, advanced settings and customizations: <https://docs.groupdocs.com/display/conversionnet/Converting>

```python
def convert(self, target_stream_provider, convert_options):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| target_stream_provider | `Func[SavePageContext, io.RawIOBase]` | Her dönüştürülmüş sayfayı kaydetmek için bir akış sağlayan delege. İmza: `Func<SavePageContext, Stream>`. `SavePageContext` parametresi sayfa numarasını ve belge bilgilerini içerir. |
| convert_options | `ConvertOptions` | İstenen hedef dosya türüne özgü dönüştürme seçenekleri. |

**Returns:** None.

### Örnek

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with open("input.docx", "rb") as stream:
    with Converter(stream) as converter:
        converter.convert("output.pdf", PdfConvertOptions())
```

## convert {#convert_options-document_completed}

Kaynak belgeyi dönüştürür ve dönüştürülmüş belgeyi sayfa sayfa kaydeder.

Daha fazla bilgi edinin

- More about document conversion basic scenarios: <https://docs.groupdocs.com/display/conversionnet/Convert+document>
- Conversion use cases, advanced settings and customizations: <https://docs.groupdocs.com/display/conversionnet/Converting>

```python
def convert(self, convert_options, document_completed):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| convert_options | `ConvertOptions` | İstenen hedef dosya türüne özgü dönüştürme seçenekleri. |
| document_completed | `Action[ConvertedPageContext]` | Her dönüştürülmüş sayfayı alan delege. `ConvertedPageContext` parametresi sayfa numarasını, akışı, kaynak dosya adını ve hedef dosya türünü içerir. |

### Örnek

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("./business-plan.docx") as converter:
    converter.convert("./business-plan.pdf", PdfConvertOptions())
```

## convert {#convert_options_provider-document_completed}

Kaynak belgeyi dönüştürür ve dönüştürülmüş belgeyi sayfa sayfa kaydeder.

Daha fazla bilgi edinin

- More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
- Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

```python
def convert(self, convert_options_provider, document_completed):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| convert_options_provider | `Func[ConvertContext, ConvertOptions]` | Dönüştürme seçeneklerini sağlayan delege. `ConvertContext` parametresi dönüşüm işlemi hakkında bilgi içerir. |
| document_completed | `Action[ConvertedPageContext]` | Her dönüştürülmüş sayfayı alan delege. `ConvertedPageContext` parametresi sayfa numarasını, akışı, kaynak dosya adını ve hedef dosya türünü içerir. |

### Örnek

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with open("input.docx", "rb") as stream:
    with Converter(stream) as converter:
        converter.convert("output.pdf", PdfConvertOptions())
```

### Ayrıca Bakınız
* class [`Converter`](/conversion/python-net/groupdocs.conversion/converter/)
