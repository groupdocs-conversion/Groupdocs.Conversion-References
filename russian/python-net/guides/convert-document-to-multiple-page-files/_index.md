---
title: "Конвертировать документ в несколько файлов страниц"
linkTitle: "Convert Document To Multiple"
second_title: "GroupDocs.Conversion для Python через .NET справочник API"
description: "id: convert-document-to-multiple-page-files"
type: docs
url: /ru/python-net/guides/convert-document-to-multiple-page-files/
is_root: false
weight: 60
---


---
id: convert-document-to-multiple-page-files
url: conversion/python-net/developer-guide/converting-documents/convert-document-to-multiple-page-files
title: Конвертировать документ в несколько файлов страниц
linkTitle: Конвертировать в несколько файлов
weight: 3
description: "Отобразить каждую страницу многостраничного документа в отдельный выходной файл — перебрать page_number с pages_count=1 и вызвать Converter.convert() для создания одного PNG, PDF или изображения на страницу с помощью GroupDocs.Conversion для Python через .NET."
keywords: конвертировать в несколько файлов, вывод по страницам, page_number, pages_count, цикл страниц, конвертировать страницы презентаций, конвертировать страницы PDF в PNG, ImageConvertOptions, GroupDocs.Conversion, python
productName: GroupDocs.Conversion для Python через .NET
hideChildren: false
toc: true
---

Эта тема документации охватывает конвертацию одного многостраничного документа в отдельные файлы страниц. Ниже приведена диаграмма, иллюстрирующая процесс преобразования многостраничного файла в отдельные страницы:

flowchart LR
%% Nodes
A["Входной документ"]
B[\"Conversion\"]
C["Конвертированная страница 1"]
D["Конвертированная страница 2"]
E["Конвертированная страница N"]

%% Edge connections between nodes
A --> B --> C
B --> D
B --> E

Чтобы конвертировать документ в файлы по страницам, используйте метод `Converter.convert(file_path, convert_options)` вместе с атрибутами `page_number` и `pages_count` поддерживаемых классов [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/):

- **`page_number`**: One-based index of the first page to convert.
- **`pages_count`**: Number of consecutive pages to convert starting from `page_number`.

Чтобы создать один выходной файл на страницу, выполните цикл от `1` до `converter.get_document_info().pages_count`, обновляя `page_number` на каждой итерации и записывая в разный путь вывода. Установка `pages_count = 1` гарантирует, что каждый вызов генерирует одну страницу.

## Supported ConvertOptions Classes

Следующие классы [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/) предоставляют атрибуты `page_number` и `pages_count`, используемые в этой теме:

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

В следующем примере показано, как конвертировать каждый слайд PPTX-презентации в изображение PNG и сохранить полученные изображения в указанную папку.
 
Шаблон имени файла для выходных файлов: `converted-page-{page number}.{output file extension}`. В этом примере первый слайд будет сохранён как `converted-page-1.png`.

{{< tabs \"example-1\">}}
{{< tab \"convert_all_document_pages.py\" >}}
```python
import os
from groupdocs.conversion import Converter
from groupdocs.conversion.filetypes import ImageFileType
from groupdocs.conversion.options.convert import ImageConvertOptions

def convert_all_document_pages():
    output_folder = "./converted-pages"
    os.makedirs(output_folder, exist_ok=True)

    # Создайте экземпляр Converter с входным документом
    with Converter("./basic-presentation.pptx") as converter:
        # Определить общее количество страниц в исходном документе
        pages_count = converter.get_document_info().pages_count

        # Создайте параметры конвертации один раз и повторно используйте их внутри цикла
        png_convert_options = ImageConvertOptions()
        png_convert_options.format = ImageFileType.PNG
        png_convert_options.pages_count = 1

        # Конвертировать каждую страницу в отдельный PNG‑файл
        for page_number in range(1, pages_count + 1):
            png_convert_options.page_number = page_number
            output_file = os.path.join(output_folder, f"converted-page-{page_number}.png")
            converter.convert(output_file, png_convert_options)

if __name__ == "__main__":
    convert_all_document_pages()
```
{{< /tab >}}
{{< tab \"basic-presentation.pptx\" >}}

`basic-presentation.pptx` — это пример файла, используемый в этом примере. Нажмите [здесь](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/convert-document-to-multiple-page-files/basic-presentation.pptx), чтобы скачать его.

{{< /tab >}}
{{< tab \"convert-all-document-pages-outputs.zip\" >}}
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

Узнайте, как получить количество страниц документа в теме документации [Getting Document Information]().

В следующем примере показано, как конвертировать конкретный слайд PPTX-презентации и сохранить его как отдельный файл.

{{< tabs \"example-2\">}}
{{< tab "convert_specific_document_page_to_file.py" >}}
```python
from groupdocs.conversion import Converter
from groupdocs.conversion.filetypes import ImageFileType
from groupdocs.conversion.options.convert import ImageConvertOptions

def convert_specific_document_page_to_file():
    # Создайте экземпляр Converter с входным документом
    with Converter("./basic-presentation.pptx") as converter:
        # Создайте экземпляр параметров конвертации
        png_convert_options = ImageConvertOptions()
        # Определите формат вывода как PNG
        png_convert_options.format = ImageFileType.PNG

        # Укажите единственную страницу для конвертации
        png_convert_options.page_number = 3
        png_convert_options.pages_count = 1

        # Сохраните преобразованную страницу в файл
        converter.convert("./slide-3.png", png_convert_options)

if __name__ == "__main__":
    convert_specific_document_page_to_file()
```
{{< /tab >}}
{{< tab \"basic-presentation.pptx\" >}}

`basic-presentation.pptx` — это пример файла, используемый в этом примере. Нажмите [здесь](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/convert-document-to-multiple-page-files/basic-presentation.pptx), чтобы скачать его.

{{< /tab >}}
{{< tab "slide-3.png" >}}
```text
Binary file (PNG, 797 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/converting-documents/convert-document-to-multiple-page-files/convert_specific_document_page_to_file/slide-3.png)
{{< /tab >}}
{{< /tabs >}}

## Example 3: Convert a Specific Page and Load Output Into a Stream

Узнайте, как получить количество страниц документа в теме документации [Getting Document Information]().

Если вам нужна преобразованная страница в виде буфера в памяти (например, чтобы передать её другому API, не трогая файловую систему позже), сначала конвертируйте страницу в файл, а затем прочитайте её в объект `BytesIO`:

{{< tabs \"example-3\">}}
{{< tab "convert_specific_document_page_to_stream.py" >}}
```python
import io
from groupdocs.conversion import Converter
from groupdocs.conversion.filetypes import ImageFileType
from groupdocs.conversion.options.convert import ImageConvertOptions

def convert_specific_document_page_to_stream():
    page_number_to_convert = 5
    output_file = f"./slide-{page_number_to_convert}.png"

    # Создайте экземпляр Converter с входным документом
    with Converter("./basic-presentation.pptx") as converter:
        # Создайте экземпляр параметров конвертации
        png_convert_options = ImageConvertOptions()
        # Определите формат вывода как PNG
        png_convert_options.format = ImageFileType.PNG

        # Укажите единственную страницу для конвертации
        png_convert_options.page_number = page_number_to_convert
        png_convert_options.pages_count = 1

        # Конвертируйте и сохраните страницу в файл на диске
        converter.convert(output_file, png_convert_options)

    # Загрузите преобразованную страницу в поток в памяти для дальнейшего использования
    with open(output_file, "rb") as file_handle:
        page_stream = io.BytesIO(file_handle.read())

    # page_stream теперь содержит PNG‑байты и может быть передан любому потребителю
    print(f"Loaded {page_stream.getbuffer().nbytes} bytes into memory")

if __name__ == "__main__":
    convert_specific_document_page_to_stream()
```
{{< /tab >}}
{{< tab \"basic-presentation.pptx\" >}}

`basic-presentation.pptx` — это пример файла, используемый в этом примере. Нажмите [здесь](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/convert-document-to-multiple-page-files/basic-presentation.pptx), чтобы скачать его.

{{< /tab >}}
{{< tab "slide-5.png" >}}
```text
Binary file (PNG, 75 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/converting-documents/convert-document-to-multiple-page-files/convert_specific_document_page_to_stream/slide-5.png)
{{< /tab >}}
{{< /tabs >}}
