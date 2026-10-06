---
title: "Загрузить файл с локального диска"
linkTitle: "Load From Local Disk"
second_title: "GroupDocs.Conversion для Python через .NET справочник API"
description: "Создайте экземпляр класса Converter, указав абсолютный или относительный путь к файлу, чтобы преобразовать документ, хранящийся в локальной файловой системе, с помощью GroupDocs.Conversion для Python через .NET."
type: docs
url: /ru/python-net/guides/load-file-from-local-disk/
is_root: false
weight: 90
---


Чтобы загрузить исходный файл с вашего локального диска, вы можете использовать конструктор класса [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) в GroupDocs.Conversion. API предоставляет несколько перегрузок, обеспечивая гибкость для различных настроек и параметров:

* `Converter(file_path)`
* `Converter(file_path, load_options)`
* `Converter(file_path, converter_settings)`
* `Converter(file_path, load_options, converter_settings)`

Каждый конструктор требует параметр `filePath`, который определяет путь к исходному файлу. Вы можете указать его как абсолютный, так и относительный путь. Обратите внимание, что если указанный путь к файлу не существует, будет выброшено исключение.

GroupDocs.Conversion получит доступ к файлу только когда будет выполнено действие (например, конвертация) с использованием экземпляра класса [`Converter`](/conversion/python-net/groupdocs.conversion/converter/).

В следующем примере на Python показано, как загрузить файл с локального диска и преобразовать его в PDF:

{{< tabs \"code-example\">}}
{{< tab \"convert_docx_to_pdf.py\" >}}
```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

def convert_docx_to_pdf():
    # Укажите расположение исходного файла
    converter = Converter("./business-plan.docx")
    
    # Укажите расположение выходного файла и параметры конвертации
    output_path = "./business-plan.pdf"
    pdf_options = PdfConvertOptions()
    
    # Преобразуйте и сохраните в путь вывода
    converter.convert(output_path, pdf_options)

if __name__ == "__main__":
    convert_docx_to_pdf()
```
{{< /tab >}}
{{< tab \"business-plan.docx\" >}}

`business-plan.docx` является примером файла, используемого в этом примере. Нажмите [здесь](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/loading-documents/load-file-from-local-disk/business-plan.docx), чтобы скачать его.

{{< /tab >}}
{{< tab \"business-plan.pdf\" >}}
```text
Binary file (PDF, 283 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/loading-documents/load-file-from-local-disk/convert_docx_to_pdf/business-plan.pdf)
{{< /tab >}}
{{< /tabs >}}

GroupDocs.Conversion определяет тип файла по его расширению. Если расширение файла не задано, GroupDocs.Conversion попытается автоматически определить тип файла. В зависимости от типа файла и его размера, автоматическое определение типа файла потребляет дополнительные ресурсы, такие как память и время процессора. Поэтому мы рекомендуем убедиться, что у файла правильное расширение или использовать конструктор класса Converter, принимающий параметры загрузки.

### Explanation

- **Load Source File**: The [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) class is instantiated with the path to the source document ("business-plan.docx").
- **Conversion Options**: An instance of [`PdfConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/) is created to define the settings for PDF conversion.
- **Execute Conversion**: The `convert` method is used to convert the document and save it to the specified output path ("business-plan.pdf").

Обратитесь к [GroupDocs.Conversion API Reference](https://reference.groupdocs.com/conversion/python-net/) для получения более подробной информации об использовании параметров загрузки и других перегрузок конструктора.
