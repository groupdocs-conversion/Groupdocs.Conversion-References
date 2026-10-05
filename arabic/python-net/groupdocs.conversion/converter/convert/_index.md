---
title: "طريقة التحويل."
second_title: "مراجع API لـ GroupDocs.Conversion لـ Python عبر .NET"
description: "يقوم بتحويل المستند المصدر ويحفظ المستند المُحوَّل بالكامل."
type: docs
url: /ar/python-net/groupdocs.conversion/converter/convert/
is_root: false
weight: 1010
---


## convert {#target_stream_provider-convert_options}

يقوم بتحويل المستند المصدر ويحفظ المستند المُحوَّل بالكامل.

المزيد من المعلومات:
- More about document conversion basic scenarios: <https://docs.groupdocs.com/display/conversionnet/Convert+document>
- Conversion use cases, advanced settings and customizations: <https://docs.groupdocs.com/display/conversionnet/Converting>

```python
def convert(self, target_stream_provider, convert_options):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| target_stream_provider | `Func[SaveContext, io.RawIOBase]` | قابل للاستدعاء يستقبل تدفقًا ويحفظ المستند المحول فيه. |
| convert_options | `ConvertOptions` | خيارات التحويل الخاصة بنوع الملف الهدف المطلوب. |

### مثال

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

def convert_document_to_pdf():
    # إنشاء كائن Converter باستخدام المستند الإدخالي
    with Converter("./business-plan.docx") as converter:
        # حدد خيارات التحويل لإخراج PDF
        pdf_options = PdfConvertOptions()
        # حوّل المستند واحفظه كملف PDF
        converter.convert("./business-plan.pdf", pdf_options)

if __name__ == "__main__":
    convert_document_to_pdf()
```

## convert {#convert_options-document_completed}

يقوم بتحويل المستند المصدر ويحفظ المستند المُحوَّل بالكامل.

المزيد من المعلومات:
- More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
- Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

```python
def convert(self, convert_options, document_completed):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| convert_options | `ConvertOptions` | خيارات التحويل الخاصة بنوع الملف الهدف المطلوب. |
| document_completed | `Action[ConvertedContext]` | المندوب الذي يستقبل تدفق المستند المحول. التوقيع: `Action<ConvertedContext>`. يحتوي معامل `ConvertedContext` على تدفق المستند المحول والبيانات الوصفية. |

### مثال

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with open("input.docx", "rb") as stream:
    with Converter(stream) as converter:
        converter.convert("output.pdf", PdfConvertOptions())
```

## convert {#target_stream_provider-convert_options_provider}

يقوم بتحويل المستند المصدر ويحفظ المستند المُحوَّل بالكامل.

المزيد من المعلومات:
- More about document conversion basic scenarios: https://docs.groupdocs.com/display/conversionnet/Convert+document
- Conversion use cases, advanced settings and customizations: https://docs.groupdocs.com/display/conversionnet/Converting

```python
def convert(self, target_stream_provider, convert_options_provider):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| target_stream_provider | `Func[SaveContext, io.RawIOBase]` | `Callable[[SaveContext], io.RawIOBase]` الذي يوفر التدفق لحفظ المستند المحول. |
| convert_options_provider | `Func[ConvertContext, ConvertOptions]` | `Callable[[ConvertContext], GroupDocs.Conversion.ConvertOptions]` الذي يوفر خيارات التحويل. |

**Returns:** None.

### مثال

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

يقوم بتحويل المستند المصدر ويحفظ المستند المُحوَّل بالكامل.

اعرف المزيد

- More about document conversion basic scenarios: <https://docs.groupdocs.com/display/conversionnet/Convert+document>
- Conversion use cases, advanced settings and customizations: <https://docs.groupdocs.com/display/conversionnet/Converting>

```python
def convert(self, convert_options_provider, document_completed):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| convert_options_provider | `Func[ConvertContext, ConvertOptions]` | `Callable[[ConvertContext], GroupDocs.Conversion.ConvertOptions]` يوفر خيارات التحويل. يحتوي معامل `ConvertContext` على معلومات حول عملية التحويل. |
| document_completed | `Action[ConvertedContext]` | `Callable[[ConvertedContext], None]` يستقبل تدفق المستند المحول. يحتوي معامل `ConvertedContext` على تدفق المستند المحول والبيانات الوصفية. |

**Returns:** None.

## convert {#file_path-convert_options}

يقوم بتحويل المستند المصدر ويحفظ المستند المُحوَّل بالكامل.

المزيد من المعلومات:
- More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
- Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

```python
def convert(self, file_path, convert_options):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| file_path | `str` | مسار الملف للمستند المصدر. |
| convert_options | `ConvertOptions` | خيارات التحويل الخاصة بنوع الملف الهدف المطلوب. |

### مثال

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with open("input.docx", "rb") as stream:
    with Converter(stream) as converter:
        converter.convert("output.pdf", PdfConvertOptions())
```

## convert {#target_stream_provider-convert_options_provider}

يقوم بتحويل المستند المصدر ويحفظ المستند المُحوَّل صفحةً بصفحة.

اعرف المزيد

- More about document conversion basic scenarios: How to convert document in 3 steps (https://docs.groupdocs.com/display/conversionnet/Convert+document)
- Conversion use cases, advanced settings and customizations: Convert document with advanced settings (https://docs.groupdocs.com/display/conversionnet/Converting)

```python
def convert(self, target_stream_provider, convert_options_provider):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| target_stream_provider | `Func[SavePageContext, io.RawIOBase]` | `Callable[[SavePageContext], io.RawIOBase]` الذي يوفر تدفقًا لحفظ كل صفحة محولة. يحتوي معامل `SavePageContext` على رقم الصفحة ومعلومات المستند. |
| convert_options_provider | `Func[ConvertContext, ConvertOptions]` | `Callable[[ConvertContext], ConvertOptions]` الذي يوفر خيارات التحويل. يحتوي معامل `ConvertContext` على معلومات حول عملية التحويل. |

**Returns:** None.

## convert {#target_stream_provider-convert_options}

يقوم بتحويل المستند المصدر ويحفظ المستند المُحوَّل صفحةً بصفحة.

اعرف المزيد
- More about document conversion basic scenarios: <https://docs.groupdocs.com/display/conversionnet/Convert+document>
- Conversion use cases, advanced settings and customizations: <https://docs.groupdocs.com/display/conversionnet/Converting>

```python
def convert(self, target_stream_provider, convert_options):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| target_stream_provider | `Func[SavePageContext, io.RawIOBase]` | Callable الذي يوفر تدفقًا لحفظ كل صفحة محولة. التوقيع: `Func<SavePageContext, Stream>`. يحتوي معامل `SavePageContext` على رقم الصفحة ومعلومات المستند. |
| convert_options | `ConvertOptions` | خيارات التحويل الخاصة بنوع الملف الهدف المطلوب. |

**Returns:** None.

### مثال

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with open("input.docx", "rb") as stream:
    with Converter(stream) as converter:
        converter.convert("output.pdf", PdfConvertOptions())
```

## convert {#convert_options-document_completed}

يقوم بتحويل المستند المصدر ويحفظ المستند المُحوَّل صفحةً بصفحة.

اعرف المزيد

- More about document conversion basic scenarios: <https://docs.groupdocs.com/display/conversionnet/Convert+document>
- Conversion use cases, advanced settings and customizations: <https://docs.groupdocs.com/display/conversionnet/Converting>

```python
def convert(self, convert_options, document_completed):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| convert_options | `ConvertOptions` | خيارات التحويل الخاصة بنوع الملف الهدف المطلوب. |
| document_completed | `Action[ConvertedPageContext]` | Callable الذي يستقبل كل صفحة محولة. يحتوي معامل `ConvertedPageContext` على رقم الصفحة، التدفق، اسم ملف المصدر، ونوع الملف الهدف. |

### مثال

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with Converter("./business-plan.docx") as converter:
    converter.convert("./business-plan.pdf", PdfConvertOptions())
```

## convert {#convert_options_provider-document_completed}

يقوم بتحويل المستند المصدر ويحفظ المستند المُحوَّل صفحةً بصفحة.

اعرف المزيد

- More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
- Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

```python
def convert(self, convert_options_provider, document_completed):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| convert_options_provider | `Func[ConvertContext, ConvertOptions]` | المندوب الذي يوفر خيارات التحويل. يحتوي معامل `ConvertContext` على معلومات حول عملية التحويل. |
| document_completed | `Action[ConvertedPageContext]` | المندوب الذي يستقبل كل صفحة محولة. يحتوي معامل `ConvertedPageContext` على رقم الصفحة، التدفق، اسم ملف المصدر، ونوع الملف الهدف. |

### مثال

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

with open("input.docx", "rb") as stream:
    with Converter(stream) as converter:
        converter.convert("output.pdf", PdfConvertOptions())
```

### انظر أيضًا
* class [`Converter`](/conversion/python-net/groupdocs.conversion/converter/)
