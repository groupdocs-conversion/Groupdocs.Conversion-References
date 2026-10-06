---
title: "Bir Belgeyi Başka Bir Formata Dönüştür"
linkTitle: "Convert to Another Format"
second_title: "GroupDocs.Conversion for Python via .NET API Referansları"
description: "GroupDocs.Conversion for Python via .NET ile ConvertOptions üzerindeki pages / page_number / pages_count özniteliklerini kullanarak, tek bir belgeyi bir formattan diğerine dönüştürün; isteğe bağlı olarak belirli sayfaları veya bir sayfa aralığını seçebilirsiniz."
type: docs
url: /tr/python-net/guides/convert-document-to-another-format/
is_root: false
weight: 40
---


Bu dokümantasyon konusu, tek bir belgenin başka bir formata dönüştürülmesini kapsar; çıktıda yalnızca bir belge üretilir. Aşağıdaki diyagram, bir dosyanın bir formattan diğerine dönüştürülme sürecini göstermektedir:

flowchart LR
%% Nodes
A["Input Document (e.g. DOCX)"]
B["Conversion"]
C["Converted Document (e.g. PDF)"]

%% Düğümler arasındaki kenar bağlantıları
A --> B --> C

Bir belgeyi dönüştürmek ve kaydetmek için aşağıdaki [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) sınıfı yöntemlerini kullanın:

- **`convert(file_path, convert_options)`**: Converts a document to a specified single output format and saves it to a file, such as converting a DOCX to PDF.
- **`convert(stream, convert_options)`**: Converts the document and writes it to a provided stream instead of a file path.

## Convert a Complete Document 

Aşağıdaki [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/) sınıfları listesi, bir belgeyi belirli tek bir çıktı formatına dönüştürmek için kullanılabilir:

- **PdfConvertOptions** – Options for converting to [PDF]() format.
- **WordProcessingConvertOptions** – Options for converting to [Word Processing]() formats.
- **SpreadsheetConvertOptions** – Options for converting to [Spreadsheet]() formats.
- **PresentationConvertOptions** – Options for converting to [Presentation]() formats.
- **ImageConvertOptions** – Options for converting to [Image]() formats (e.g., PNG, JPEG).
- **WebConvertOptions** – Options for converting to [Web]() formats (e.g., HTML).
- **PageDescriptionLanguageConvertOptions** – Options for converting to [Page Description Language]() formats (e.g., PostScript).
- **EBookConvertOptions** – Options for converting to [EBook]() formats (e.g., EPUB, MOBI).
- **EmailConvertOptions** – Options for converting to [Email]() formats (e.g., EML, MSG).
- **DiagramConvertOptions** – Options for converting to [Diagram]() formats (e.g., VSDX).
- **CadConvertOptions** – Options for converting to [CAD]() formats (e.g., DWG).
- **ThreeDConvertOptions** – Options for converting to [3D]() formats.
- **ProjectManagementConvertOptions** – Options for converting to [Project Management]() formats (e.g., MPP).
- **GisConvertOptions** – Options for converting to [GIS]() formats.
- **FontConvertOptions** – Options for converting to [Font]() formats (e.g., TTF, OTF).
- **FinanceConvertOptions** – Options for converting to [Finance]() formats (e.g., XBRL).
- **CompressionConvertOptions** – Options for converting to [Compression]() formats (e.g., ZIP).
- **NoConvertOptions** – A special option class that instructs the converter to copy the source document without any modifications.

### Example 1: Convert a Document to Another Format

Aşağıdaki örnek, bir DOCX dosyasını PDF'ye nasıl dönüştüreceğinizi gösterir:

{{< tabs \"example-1\">}}
{{< tab "convert_document_to_another_format.py" >}}
```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

def convert_document_to_another_format():
    # Girdi belgesiyle Converter'ı örnekleyin 
    with Converter("./business-plan.docx") as converter:
        # Çıktı formatını tanımlamak için dönüştürme seçeneklerini örnekleyin
        pdf_convert_options = PdfConvertOptions()
        
        # Girdi belgesini PDF'ye dönüştür
        converter.convert("./business-plan.pdf", pdf_convert_options)    

if __name__ == "__main__":
    convert_document_to_another_format()
```
{{< /tab >}}
{{< tab \"business-plan.docx\" >}}

`business-plan.docx` bu örnekte kullanılan örnek dosyadır. İndirmek için [buraya](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/convert-document-to-another-format/business-plan.docx) tıklayın.

{{< /tab >}}
{{< tab "business-plan.pdf" >}}
```text
Binary file (PDF, 283 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/converting-documents/convert-document-to-another-format/convert_document_to_another_format/business-plan.pdf)
{{< /tab >}}
{{< /tabs >}}

### Example 2: Specify Output Format

Varsayılan olarak, her bir [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/) sınıfının kendi varsayılan hedef formatı vardır. Örneğin, [WordProcessingConvertOptions](https://reference.groupdocs.com/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/) için varsayılan çıktı formatı [DOCX](https://reference.groupdocs.com/conversion/python-net/groupdocs.conversion.filetypes/wordprocessingfiletype/docx/)'dir.

Format ailesi içinde farklı bir çıktı formatı ayarlamak için `format` özelliğini kullanın. Aşağıdaki örnek, bir `DOCX` dosyasını dönüştürürken hedef formatı `TXT` olarak nasıl belirleyeceğinizi gösterir:

{{< tabs "example-2">}}
{{< tab "specify_output_format.py" >}}
```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import WordProcessingConvertOptions
from groupdocs.conversion.filetypes import WordProcessingFileType

def specify_output_format():
    # Girdi belgesiyle Converter'ı örnekleyin 
    with Converter("./business-plan.docx") as converter:
        # Çıktı formatını tanımlamak için dönüştürme seçeneklerini örnekleyin, varsayılan olarak DOCX'tir
        word_convert_options = WordProcessingConvertOptions()
        # Format ailesi içinde çıktı formatını DOCX'ten TXT'ye değiştirin
        word_convert_options.format = WordProcessingFileType.TXT
        
        # Giriş belgesini TXT'ye dönüştürün
        converter.convert("./business-plan.txt", word_convert_options)    

if __name__ == "__main__":
    specify_output_format()
```
{{< /tab >}}
{{< tab \"business-plan.docx\" >}}

`business-plan.docx` bu örnekte kullanılan örnek dosyadır. İndirmek için [buraya](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/convert-document-to-another-format/business-plan.docx) tıklayın.

{{< /tab >}}
{{< tab "business-plan.txt" >}}
```text
﻿HOME BASED

PROFESSIONAL SERVICES

Business Plan

[TRUNCATED]
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/converting-documents/convert-document-to-another-format/specify_output_format/business-plan.txt)
{{< /tab >}}
{{< /tabs >}}

## Specify Document Pages to Convert

Belge sayfalarının sayısını nasıl alacağınızı [Getting Document Information]() belgeleri konusunda öğrenin.

Belirli belge sayfalarını dönüştürmek için aşağıdaki [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/) sınıflarını kullanabilirsiniz; bu sınıflar `pages`, `page_number` ve `pages_count` özniteliklerini sağlar. Bu seçenekler, dönüştürmek istediğiniz tek tek sayfaları veya bir sayfa aralığını belirtmenize olanak tanır.

- **PdfConvertOptions** – Options for converting to [PDF]() format.
- **ImageConvertOptions** – Options for converting to [Image]() formats (e.g., PNG, JPEG).
- **WordProcessingConvertOptions** – Options for converting to [Word Processing]() formats.
- **SpreadsheetConvertOptions** – Options for converting to [Spreadsheet]() formats.
- **PresentationConvertOptions** – Options for converting to [Presentation]() formats.
- **WebConvertOptions** – Options for converting to [Web]() formats (e.g., HTML).
- **EBookConvertOptions** – Options for converting to [EBook]() formats (e.g., EPUB, MOBI).
- **DiagramConvertOptions** – Options for converting to [Diagram]() formats (e.g., VSDX).
- **PageDescriptionLanguageConvertOptions** – Options for converting to [Page Description Language]() formats (e.g., PostScript).
- **CadConvertOptions** – Options for converting to [CAD]() formats (e.g., DWG).
- **ThreeDConvertOptions** – Options for converting to [3D]() formats.
- **FinanceConvertOptions** – Options for converting to [Finance]() formats (e.g., XBRL).

### Example 1: Convert Specific Document Pages to Another Format

Aşağıdaki örnekte gösterildiği gibi, dönüştürmek istediğiniz belge sayfalarını belirtebilirsiniz:

{{< tabs "example-3">}}
{{< tab "convert_specific_document_pages.py" >}}
```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

def convert_specific_document_pages():
    # Girdi belgesiyle Converter'ı örnekleyin 
    with Converter("./business-plan.docx") as converter:
        # Çıktı formatını tanımlamak için dönüştürme seçeneklerini örnekleyin
        pdf_convert_options = PdfConvertOptions()
        # Dönüştürülecek belge sayfalarını belirtin
        pdf_convert_options.pages = [1, 3, 5]

        # Girdi belgesinin belirtilen sayfalarını PDF'e dönüştürün
        converter.convert("./pages-1-3-5.pdf", pdf_convert_options)    

if __name__ == "__main__":
    convert_specific_document_pages()
```
{{< /tab >}}
{{< tab \"business-plan.docx\" >}}

`business-plan.docx` bu örnekte kullanılan örnek dosyadır. İndirmek için [buraya](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/convert-document-to-another-format/business-plan.docx) tıklayın.

{{< /tab >}}
{{< tab "pages-1-3-5.pdf" >}}
```text
Binary file (PDF, 156 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/converting-documents/convert-document-to-another-format/convert_specific_document_pages/pages-1-3-5.pdf)
{{< /tab >}}
{{< /tabs >}}

### Example 2: Convert N Consecutive Pages

Alternatif olarak, aşağıdaki örnekte gösterildiği gibi, dönüştürmek için ardışık sayfa sayısını belirtebilirsiniz:

{{< tabs "example-4">}}
{{< tab "convert_consecutive_document_pages.py" >}}
```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

def convert_consecutive_document_pages():
    # Girdi belgesiyle Converter'ı örnekleyin 
    with Converter("./business-plan.docx") as converter:
        # Çıktı formatını tanımlamak için dönüştürme seçeneklerini örnekleyin
        pdf_convert_options = PdfConvertOptions()
        # Dönüştürülecek başlangıç sayfasını ve sayfa sayısını belirtin
        pdf_convert_options.page_number = 1
        pdf_convert_options.pages_count = 5

        # Belgedeki belirtilen sayfa aralığını PDF'e dönüştürün
        converter.convert("./pages-1-through-5.pdf", pdf_convert_options)    

if __name__ == "__main__":
    convert_consecutive_document_pages()
```
{{< /tab >}}
{{< tab \"business-plan.docx\" >}}

`business-plan.docx` bu örnekte kullanılan örnek dosyadır. İndirmek için [buraya](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/convert-document-to-another-format/business-plan.docx) tıklayın.

{{< /tab >}}
{{< tab "pages-1-through-5.pdf" >}}
```text
Binary file (PDF, 216 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/converting-documents/convert-document-to-another-format/convert_consecutive_document_pages/pages-1-through-5.pdf)
{{< /tab >}}
{{< /tabs >}}
