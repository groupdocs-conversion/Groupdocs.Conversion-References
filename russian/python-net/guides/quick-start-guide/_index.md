---
title: "Руководство по быстрому старту"
linkTitle: "Quick Start Guide"
second_title: "GroupDocs.Conversion для Python через .NET справочник API"
description: "Создайте виртуальное окружение, установите groupdocs-conversion-net и выполните три минимальных примера — DOCX → PDF, PDF → PNG по страницам и ZIP → объединённый PDF — менее чем за пять минут."
type: docs
url: /ru/python-net/guides/quick-start-guide/
is_root: false
weight: 20
---


Это руководство даёт краткий обзор того, как настроить и начать использовать GroupDocs.Conversion для Python через .NET. Эта библиотека позволяет разработчикам конвертировать между различными форматами файлов (например, DOCX, PDF, PNG) с минимальной конфигурацией.

## Prerequisites

Чтобы продолжить, убедитесь, что у вас есть:

1. **Configured** окружение, как описано в теме [System Requirements]().
2. **Optionally** вы можете [Получить временную лицензию](https://purchase.groupdocs.com/temporary-license/) для тестирования всех функций продукта.

## Set Up Your Development Environment

Для лучших практик используйте виртуальное окружение для управления зависимостями в приложениях Python. Узнайте больше о виртуальном окружении в теме документации [Создание и использование виртуальных окружений](https://packaging.python.org/en/latest/guides/installing-using-pip-and-virtual-environments/#create-and-use-virtual-environments).

### Create and Activate a Virtual Environment

Создайте виртуальное окружение:

{{< tabs \"example1\">}}
{{< tab \"Windows\" >}}
```ps
py -m venv .venv
```
{{< /tab >}}
{{< tab \"Linux\" >}}
```bash
python3 -m venv .venv
```
{{< /tab >}}
{{< tab \"macOS\" >}}
```bash
python3 -m venv .venv
```
{{< /tab >}}
{{< /tabs >}}

Активируйте виртуальное окружение:

{{< tabs \"example2\">}}
{{< tab \"Windows\" >}}
```ps
.venv\Scripts\activate
```
{{< /tab >}}
{{< tab \"Linux\" >}}
```bash
source .venv/bin/activate
```
{{< /tab >}}
{{< tab \"macOS\" >}}
```bash
source .venv/bin/activate
```
{{< /tab >}}
{{< /tabs >}}

### Install `groupdocs-conversion-net` Package

После активации виртуального окружения выполните следующую команду в терминале, чтобы установить последнюю версию пакета:

{{< tabs \"example3\">}}
{{< tab \"Windows\" >}}
```ps
py -m pip install groupdocs-conversion-net
```
{{< /tab >}}
{{< tab \"Linux\" >}}
```bash
python3 -m pip install groupdocs-conversion-net
```
{{< /tab >}}
{{< tab \"macOS\" >}}
```bash
python3 -m pip install groupdocs-conversion-net
```
{{< /tab >}}
{{< /tabs >}}

Убедитесь, что пакет установлен успешно. Вы должны увидеть сообщение

```bash
Successfully installed groupdocs-conversion-net-*
```

## Example 1: Convert document

Чтобы быстро протестировать библиотеку, давайте конвертируем файл DOCX в PDF. Вы также можете скачать приложение, которое мы собираемся создать, [здесь](https://docs.groupdocs.com/conversion/python-net/_sample_files/getting-started/quick-start-guide/convert_docx_to_pdf.zip).

{{< tabs "demo_app_convert_docx_to_pdf">}}
{{< tab \"convert_docx_to_pdf.py\" >}}
```python
import os
from groupdocs.conversion import License, Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

def convert_docx_to_pdf():
    # Получить абсолютный путь к файлу лицензии
    license_path = os.path.abspath("./GroupDocs.Conversion.lic")

    if os.path.exists(license_path):
        # Создать лицензию и задать путь
        license = License()
        license.set_license(license_path)

    # Загрузить файл DOCX
    with Converter("./business-plan.docx") as converter:
        # Создать параметры конвертации
        pdf_convert_options = PdfConvertOptions()

        # Конвертировать DOCX в PDF
        converter.convert("./business-plan.pdf", pdf_convert_options)    

if __name__ == "__main__":
    convert_docx_to_pdf()
```
{{< /tab >}}
{{< tab \"business-plan.docx\" >}}

`business-plan.docx` является примером файла, используемого в этом примере. Нажмите [здесь](https://docs.groupdocs.com/conversion/python-net/_sample_files/getting-started/quick-start-guide/business-plan.docx), чтобы загрузить его.

{{< /tab >}}
{{< tab \"business-plan.pdf\" >}}
```text
Binary file (PDF, 283 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/getting-started/quick-start-guide/convert_docx_to_pdf/business-plan.pdf)
{{< /tab >}}
{{< /tabs >}}

Ваша структура папок должна выглядеть примерно так:

```Directory
📂 demo-app
 ├──convert_docx_to_pdf.py
 ├──business-plan.docx
 └──GroupDocs.Conversion.lic (Optionally)
```

### Run the App

{{< tabs "run-the-app">}}
{{< tab \"Windows\" >}}
```ps
py convert_docx_to_pdf.py
```
{{< /tab >}}
{{< tab \"Linux\" >}}
```bash
python3 convert_docx_to_pdf.py
```
{{< /tab >}}
{{< tab \"macOS\" >}}
```bash
python3 convert_docx_to_pdf.py
```
{{< /tab >}}
{{< /tabs >}}

После запуска приложения вы можете деактивировать виртуальное окружение, выполнив `deactivate`, или закрыв оболочку.

### Explanation
- `Converter("./business-plan.docx")`: Initializes the converter with the DOCX file.
- `PdfConvertOptions()`: Specifies the output format as PDF.
- `converter.convert("./business-plan.pdf", pdf_convert_options)`: Converts the DOCX file to PDF and saves it as `business-plan.pdf`.

## Example 2: Convert document pages

В этом примере мы преобразуем страницы PDF‑документа в PNG. Вы можете скачать приложение, которое мы собираемся создать, [здесь](https://docs.groupdocs.com/conversion/python-net/_sample_files/getting-started/quick-start-guide/convert_pdf_pages_to_png.zip).

{{< tabs "demo_app_convert_pdf_pages_to_png">}}
{{< tab "convert_pdf_pages_to_png.py" >}}
```python
import os
from groupdocs.conversion import License, Converter
from groupdocs.conversion.filetypes import ImageFileType
from groupdocs.conversion.options.convert import ImageConvertOptions

def convert_pdf_pages_to_png():
    # Получить абсолютный путь к файлу лицензии
    license_path = os.path.abspath("./GroupDocs.Conversion.lic")

    if os.path.exists(license_path):
        # Создать лицензию и задать путь
        license = License()
        license.set_license(license_path)

    output_folder = "./converted-pages"
    os.makedirs(output_folder, exist_ok=True)

    # Загрузить PDF‑документ
    with Converter("./annual-review.pdf") as converter:
        # Определить общее количество страниц в исходном документе
        pages_count = converter.get_document_info().pages_count

        # Создать параметры конвертации и повторно использовать их внутри цикла
        png_convert_options = ImageConvertOptions()
        png_convert_options.format = ImageFileType.PNG
        png_convert_options.pages_count = 1

        # Конвертировать каждую страницу в отдельный PNG‑файл
        for page_number in range(1, pages_count + 1):
            png_convert_options.page_number = page_number
            output_file = os.path.join(output_folder, f"converted-page-{page_number}.png")
            converter.convert(output_file, png_convert_options)

if __name__ == "__main__":
    convert_pdf_pages_to_png()
```
{{< /tab >}}
{{< tab "annual-review.pdf" >}}

`annual-review.pdf` является примером файла, используемого в этом примере. Нажмите [здесь](https://docs.groupdocs.com/conversion/python-net/_sample_files/getting-started/quick-start-guide/annual-review.pdf), чтобы загрузить его.

{{< /tab >}}
{{< tab "convert-pdf-pages-to-png-outputs.zip" >}}
```text
converted-pages/converted-page-1.png (1148 KB)
converted-pages/converted-page-2.png (89 KB)
converted-pages/converted-page-3.png (83 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/getting-started/quick-start-guide/convert_pdf_pages_to_png/convert-pdf-pages-to-png-outputs.zip)
{{< /tab >}}
{{< /tabs >}}

Ваша структура папок должна выглядеть примерно так:

```Directory
📂 demo-app
 ├──annual-review.pdf
 ├──convert_pdf_pages_to_png.py
 └──GroupDocs.Conversion.lic (Optionally)
```

### Run the App

{{< tabs "run_the_app_convert_pdf_pages_to_png">}}
{{< tab \"Windows\" >}}
```ps
py convert_pdf_pages_to_png.py
```
{{< /tab >}}
{{< tab \"Linux\" >}}
```bash
python3 convert_pdf_pages_to_png.py
```
{{< /tab >}}
{{< tab \"macOS\" >}}
```bash
python3 convert_pdf_pages_to_png.py
```
{{< /tab >}}
{{< /tabs >}}

После запуска приложения вы можете деактивировать виртуальное окружение, выполнив `deactivate`, или закрыв оболочку.

### Explanation
- `Converter("./annual-review.pdf")`: Initializes the converter with the PDF file.
- `converter.get_document_info().pages_count`: Retrieves the total number of pages in the source document.
- `ImageConvertOptions()` with `format = ImageFileType.PNG`: Specifies the output format as PNG image.
- The loop updates `png_convert_options.page_number` on each iteration (with `pages_count = 1`) and calls `converter.convert(...)` to write one PNG file per page into the `converted-pages` folder.

## Example 3: Convert files in archive

В этом примере мы конвертируем содержимое ZIP‑архива в PDF. GroupDocs.Conversion открывает архив, конвертирует вложенные файлы и создает единый объединённый PDF, содержащий каждый преобразованный документ. Вы можете скачать приложение, которое мы собираемся создать, [здесь](https://docs.groupdocs.com/conversion/python-net/_sample_files/getting-started/quick-start-guide/convert_files_in_archive.zip).

{{< tabs "demo_app_convert_files_in_archive">}}
{{< tab "convert_files_in_archive.py" >}}
```python
import os
from groupdocs.conversion import License, Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

def convert_files_in_archive():
    # Получить абсолютный путь к файлу лицензии
    license_path = os.path.abspath("./GroupDocs.Conversion.lic")

    if os.path.exists(license_path):
        # Создать лицензию и задать путь
        license = License()
        license.set_license(license_path)

    # Загрузить ZIP‑файл
    with Converter("./compressed.zip") as converter:
        # Создать параметры конвертации
        pdf_convert_options = PdfConvertOptions()

        # Извлеките архив, преобразуйте его содержимое и сохраните объединённый PDF
        converter.convert("./converted.pdf", pdf_convert_options)

if __name__ == "__main__":
    convert_files_in_archive()
```
{{< /tab >}}
{{< tab \"compressed.zip\" >}}

`compressed.zip` — пример файла, используемый в этом примере. Нажмите [здесь](https://docs.groupdocs.com/conversion/python-net/_sample_files/getting-started/quick-start-guide/compressed.zip), чтобы скачать его.

{{< /tab >}}
{{< tab \"converted.pdf\" >}}
```text
Binary file (PDF, 283 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/getting-started/quick-start-guide/convert_files_in_archive/converted.pdf)
{{< /tab >}}
{{< /tabs >}}

Ваша структура папок должна выглядеть примерно так:

```Directory
📂 demo-app
 ├──compressed.zip
 ├──convert_files_in_archive.py
 └──GroupDocs.Conversion.lic (Optionally)
```

### Run the App

{{< tabs \"run_the_app_convert_files_in_archive\">}}
{{< tab \"Windows\" >}}
```ps
py convert_files_in_archive.py
```
{{< /tab >}}
{{< tab \"Linux\" >}}
```bash
python3 convert_files_in_archive.py
```
{{< /tab >}}
{{< tab \"macOS\" >}}
```bash
python3 convert_files_in_archive.py
```
{{< /tab >}}
{{< /tabs >}}

После запуска приложения вы можете деактивировать виртуальное окружение, выполнив `deactivate`, или закрыв оболочку.

### Explanation
- `Converter("./compressed.zip")`: Initializes the converter with the ZIP file.
- `PdfConvertOptions()`: Specifies the output format as PDF.
- `converter.convert("./converted.pdf", pdf_convert_options)`: Extracts the archive, converts its contents, and writes a single consolidated PDF to `converted.pdf`.

## Next Steps

После освоения основ изучите дополнительные ресурсы, чтобы расширить возможности использования:
- [Supported File Formats](): Review the full list of supported file types.
- [Licensing](): Check details on licensing and evaluation.
- [Technical Support](): Contact support for assistance if you encounter issues.
