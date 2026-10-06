---
title: "Belgeyi Çoklu Sayfa Dosyalarına Dönüştür"
linkTitle: "Convert Document To Multiple"
second_title: "GroupDocs.Conversion for Python via .NET API Referansları"
description: "id: convert-document-to-multiple-page-files"
type: docs
url: /tr/python-net/guides/convert-document-to-multiple-page-files/
is_root: false
weight: 60
---


---
id: convert-document-to-multiple-page-files
url: conversion/python-net/developer-guide/converting-documents/convert-document-to-multiple-page-files
title: Belgeyi Çoklu Sayfa Dosyalarına Dönüştür
linkTitle: Birden Çok Dosyaya Dönüştür
weight: 3
description: "Çok sayfalı bir belgenin her sayfasını kendi çıktı dosyasına dönüştürün — page_number'ı pages_count=1 ile döngüye alın ve Converter.convert() kullanarak GroupDocs.Conversion for Python via .NET ile her sayfa için bir PNG, PDF veya görüntü üretin."
keywords: çoklu dosyalara dönüştür, sayfa başı çıktı, page_number, pages_count, sayfa döngüsü, sunum sayfalarını dönüştür, PDF sayfalarını PNG'ye dönüştür, ImageConvertOptions, GroupDocs.Conversion, python
productName: GroupDocs.Conversion for Python via .NET
hideChildren: false
toc: true
---

Bu dokümantasyon konusu, tek bir çok sayfalı belgenin ayrı sayfa dosyalarına dönüştürülmesini kapsar. Aşağıdaki diyagram, çok sayfalı bir dosyanın ayrı sayfalara dönüştürülme sürecini göstermektedir:

flowchart LR
%% Nodes
A["Girdi Belgesi"]
B["Conversion"]
C["Dönüştürülmüş Sayfa 1"]
D["Dönüştürülmüş Sayfa 2"]
E["Dönüştürülmüş Sayfa N"]

%% Düğümler arasındaki kenar bağlantıları
A --> B --> C
B --> D
B --> E

Bir belgeyi sayfa başı dosyalara dönüştürmek için, desteklenen [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/) sınıflarındaki `page_number` ve `pages_count` öznitelikleriyle birlikte `Converter.convert(file_path, convert_options)` metodunu kullanın:

- **`page_number`**: One-based index of the first page to convert.
- **`pages_count`**: Number of consecutive pages to convert starting from `page_number`.

Her sayfa için bir çıktı dosyası üretmek amacıyla, `converter.get_document_info().pages_count` değerine kadar `1`'den başlayarak döngü oluşturun, her yinelemede `page_number` değerini güncelleyip farklı bir çıktı yoluna yazın. `pages_count = 1` ayarı, her çağrının tek bir sayfa üretmesini sağlar.

## Supported ConvertOptions Classes

Bu konuda kullanılan `page_number` ve `pages_count` özniteliklerini ortaya çıkaran aşağıdaki [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/) sınıfları:

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

## Example 1: Convert All Pages of a Document and Save Output to a Folder

Aşağıdaki örnek, bir PPTX sunumundaki her slaytı PNG görüntüsüne dönüştürmeyi ve çıktı görüntülerini belirli bir klasöre kaydetmeyi göstermektedir.
 
Çıktı dosyalarının dosya adı şablonu `converted-page-{page number}.{output file extension}` şeklindedir. Bu örnekte, ilk slayt `converted-page-1.png` olarak kaydedilecektir.

{{< tabs \"example-1\">}}
{{< tab "convert_all_document_pages.py" >}}
```python
import os
from groupdocs.conversion import Converter
from groupdocs.conversion.filetypes import ImageFileType
from groupdocs.conversion.options.convert import ImageConvertOptions

def convert_all_document_pages():
    output_folder = "./converted-pages"
    os.makedirs(output_folder, exist_ok=True)

    # Dönüştürücüyü giriş belgesiyle örnekleyin
    with Converter("./basic-presentation.pptx") as converter:
        # Kaynak belgedeki toplam sayfa sayısını belirleyin
        pages_count = converter.get_document_info().pages_count

        # Dönüştürme seçeneklerini bir kez oluşturun ve döngü içinde tekrar kullanın
        png_convert_options = ImageConvertOptions()
        png_convert_options.format = ImageFileType.PNG
        png_convert_options.pages_count = 1

        # Her sayfayı ayrı bir PNG dosyasına dönüştürün
        for page_number in range(1, pages_count + 1):
            png_convert_options.page_number = page_number
            output_file = os.path.join(output_folder, f"converted-page-{page_number}.png")
            converter.convert(output_file, png_convert_options)

if __name__ == "__main__":
    convert_all_document_pages()
```
{{< /tab >}}
{{< tab "basic-presentation.pptx" >}}

`basic-presentation.pptx` bu örnekte kullanılan örnek dosyadır. İndirmek için [buraya](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/convert-document-to-multiple-page-files/basic-presentation.pptx) tıklayın.

{{< /tab >}}
{{< tab "convert-all-document-pages-outputs.zip" >}}
```text
converted-pages/converted-page-1.png (26 KB)
converted-pages/converted-page-10.png (81 KB)
converted-pages/converted-page-11.png (67 KB)
converted-pages/converted-page-12.png (70 KB)
converted-pages/converted-page-13.png (36 KB)
converted-pages/converted-page-2.png (34 KB)
converted-pages/converted-page-3.png (797 KB)
converted-pages/converted-page-4.png (1262 KB)
converted-pages/converted-page-5.png (75 KB)
converted-pages/converted-page-6.png (33 KB)
[TRUNCATED] (13 files total)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/converting-documents/convert-document-to-multiple-page-files/convert_all_document_pages/convert-all-document-pages-outputs.zip)
{{< /tab >}}
{{< /tabs >}}

## Example 2: Convert a Specific Page and Save Output to a File

Belge sayfalarının sayısını nasıl alacağınızı [Getting Document Information]() belgeleri konusunda öğrenin.

Aşağıdaki örnek, bir PPTX sunumundaki belirli bir slaytı nasıl dönüştürüp ayrı bir dosya olarak kaydedebileceğinizi gösterir.

{{< tabs "example-2">}}
{{< tab "convert_specific_document_page_to_file.py" >}}
```python
from groupdocs.conversion import Converter
from groupdocs.conversion.filetypes import ImageFileType
from groupdocs.conversion.options.convert import ImageConvertOptions

def convert_specific_document_page_to_file():
    # Dönüştürücüyü giriş belgesiyle örnekleyin
    with Converter("./basic-presentation.pptx") as converter:
        # Dönüştürme seçeneklerini örnekleyin
        png_convert_options = ImageConvertOptions()
        # Çıktı formatını PNG olarak tanımlayın
        png_convert_options.format = ImageFileType.PNG

        # Dönüştürülecek tek sayfayı belirtin
        png_convert_options.page_number = 3
        png_convert_options.pages_count = 1

        # Dönüştürülen sayfayı bir dosyaya kaydedin
        converter.convert("./slide-3.png", png_convert_options)

if __name__ == "__main__":
    convert_specific_document_page_to_file()
```
{{< /tab >}}
{{< tab "basic-presentation.pptx" >}}

`basic-presentation.pptx` bu örnekte kullanılan örnek dosyadır. İndirmek için [buraya](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/convert-document-to-multiple-page-files/basic-presentation.pptx) tıklayın.

{{< /tab >}}
{{< tab "slide-3.png" >}}
```text
Binary file (PNG, 797 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/converting-documents/convert-document-to-multiple-page-files/convert_specific_document_page_to_file/slide-3.png)
{{< /tab >}}
{{< /tabs >}}

## Example 3: Convert a Specific Page and Load Output Into a Stream

Belge sayfalarının sayısını nasıl alacağınızı [Getting Document Information]() belgeleri konusunda öğrenin.

Dönüştürülen sayfayı bellek içi bir tampon olarak (örneğin, dosya sistemine dokunmadan başka bir API'ye iletmek için) ihtiyacınız varsa, önce sayfayı bir dosyaya dönüştürün ve ardından bir `BytesIO` nesnesine okuyun:

{{< tabs "example-3">}}
{{< tab "convert_specific_document_page_to_stream.py" >}}
```python
import io
from groupdocs.conversion import Converter
from groupdocs.conversion.filetypes import ImageFileType
from groupdocs.conversion.options.convert import ImageConvertOptions

def convert_specific_document_page_to_stream():
    page_number_to_convert = 5
    output_file = f"./slide-{page_number_to_convert}.png"

    # Dönüştürücüyü giriş belgesiyle örnekleyin
    with Converter("./basic-presentation.pptx") as converter:
        # Dönüştürme seçeneklerini örnekleyin
        png_convert_options = ImageConvertOptions()
        # Çıktı formatını PNG olarak tanımlayın
        png_convert_options.format = ImageFileType.PNG

        # Dönüştürülecek tek sayfayı belirtin
        png_convert_options.page_number = page_number_to_convert
        png_convert_options.pages_count = 1

        # Sayfayı dönüştürün ve diskte bir dosyaya kaydedin
        converter.convert(output_file, png_convert_options)

    # Dönüştürülen sayfayı aşağı akışta kullanım için bellek içi bir akışa yükleyin
    with open(output_file, "rb") as file_handle:
        page_stream = io.BytesIO(file_handle.read())

    # page_stream artık PNG baytlarını tutuyor ve herhangi bir tüketiciye aktarılabilir
    print(f"Loaded {page_stream.getbuffer().nbytes} bytes into memory")

if __name__ == "__main__":
    convert_specific_document_page_to_stream()
```
{{< /tab >}}
{{< tab "basic-presentation.pptx" >}}

`basic-presentation.pptx` bu örnekte kullanılan örnek dosyadır. İndirmek için [buraya](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/convert-document-to-multiple-page-files/basic-presentation.pptx) tıklayın.

{{< /tab >}}
{{< tab "slide-5.png" >}}
```text
Binary file (PNG, 75 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/converting-documents/convert-document-to-multiple-page-files/convert_specific_document_page_to_stream/slide-5.png)
{{< /tab >}}
{{< /tabs >}}
