---
title: "Schnellstart-Anleitung"
linkTitle: "Quick Start Guide"
second_title: "GroupDocs.Conversion für Python über .NET API-Referenzen"
description: "Richten Sie eine virtuelle Umgebung ein, installieren Sie groupdocs-conversion-net und führen Sie drei minimale Beispiele aus — DOCX → PDF, PDF → PNG pro Seite und ZIP → konsolidiertes PDF — in weniger als fünf Minuten."
type: docs
url: /de/python-net/guides/quick-start-guide/
is_root: false
weight: 20
---


Dieser Leitfaden bietet einen kurzen Überblick darüber, wie Sie GroupDocs.Conversion für Python über .NET einrichten und nutzen können. Diese Bibliothek ermöglicht Entwicklern, zwischen verschiedenen Dateiformaten (z. B. DOCX, PDF, PNG) mit minimaler Konfiguration zu konvertieren.

## Prerequisites

Um fortzufahren, stellen Sie sicher, dass Sie Folgendes haben:

1. **Configured** Umgebung wie im Thema [System Requirements]() beschrieben.
2. **Optionally** können Sie [Get a Temporary License](https://purchase.groupdocs.com/temporary-license/) erhalten, um alle Produktfunktionen zu testen.

## Set Up Your Development Environment

Für bewährte Vorgehensweisen verwenden Sie eine virtuelle Umgebung, um Abhängigkeiten in Python-Anwendungen zu verwalten. Erfahren Sie mehr über virtuelle Umgebungen im Thema [Create and Use Virtual Environments](https://packaging.python.org/en/latest/guides/installing-using-pip-and-virtual-environments/#create-and-use-virtual-environments) der Dokumentation.

### Create and Activate a Virtual Environment

Erstellen Sie eine virtuelle Umgebung:

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

Aktivieren Sie eine virtuelle Umgebung:

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

Nachdem Sie die virtuelle Umgebung aktiviert haben, führen Sie den folgenden Befehl in Ihrem Terminal aus, um die neueste Version des Pakets zu installieren:

{{< tabs "example3">}}
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

Stellen Sie sicher, dass das Paket erfolgreich installiert wurde. Sie sollten die Meldung sehen.

```bash
Successfully installed groupdocs-conversion-net-*
```

## Example 1: Convert document

Um die Bibliothek schnell zu testen, konvertieren wir eine DOCX-Datei in PDF. Sie können die Anwendung, die wir erstellen werden, auch [hier](https://docs.groupdocs.com/conversion/python-net/_sample_files/getting-started/quick-start-guide/convert_docx_to_pdf.zip) herunterladen.

{{< tabs "demo_app_convert_docx_to_pdf">}}
{{< tab "convert_docx_to_pdf.py" >}}
```python
import os
from groupdocs.conversion import License, Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

def convert_docx_to_pdf():
    # Abrufen des absoluten Pfads der Lizenzdatei
    license_path = os.path.abspath("./GroupDocs.Conversion.lic")

    if os.path.exists(license_path):
        # Lizenz erstellen und den Pfad festlegen
        license = License()
        license.set_license(license_path)

    # DOCX-Datei laden
    with Converter("./business-plan.docx") as converter:
        # Konvertierungsoptionen erstellen
        pdf_convert_options = PdfConvertOptions()

        # DOCX in PDF konvertieren
        converter.convert("./business-plan.pdf", pdf_convert_options)    

if __name__ == "__main__":
    convert_docx_to_pdf()
```
{{< /tab >}}
{{< tab "business-plan.docx" >}}

`business-plan.docx` ist die in diesem Beispiel verwendete Beispieldatei. Klicken Sie [hier](https://docs.groupdocs.com/conversion/python-net/_sample_files/getting-started/quick-start-guide/business-plan.docx), um sie herunterzuladen.

{{< /tab >}}
{{< tab "business-plan.pdf" >}}
```text
Binary file (PDF, 283 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/getting-started/quick-start-guide/convert_docx_to_pdf/business-plan.pdf)
{{< /tab >}}
{{< /tabs >}}

Ihr Ordnerbaum sollte einer ähnlichen Verzeichnisstruktur wie folgt aussehen:

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

Nach dem Ausführen der Anwendung können Sie die virtuelle Umgebung deaktivieren, indem Sie `deactivate` ausführen oder Ihre Shell schließen.

### Explanation
- `Converter("./business-plan.docx")`: Initializes the converter with the DOCX file.
- `PdfConvertOptions()`: Specifies the output format as PDF.
- `converter.convert("./business-plan.pdf", pdf_convert_options)`: Converts the DOCX file to PDF and saves it as `business-plan.pdf`.

## Example 2: Convert document pages

In diesem Beispiel konvertieren wir PDF-Dokumentseiten in PNG. Sie können die Anwendung, die wir erstellen werden, [hier](https://docs.groupdocs.com/conversion/python-net/_sample_files/getting-started/quick-start-guide/convert_pdf_pages_to_png.zip) herunterladen.

{{< tabs "demo_app_convert_pdf_pages_to_png">}}
{{< tab "convert_pdf_pages_to_png.py" >}}
```python
import os
from groupdocs.conversion import License, Converter
from groupdocs.conversion.filetypes import ImageFileType
from groupdocs.conversion.options.convert import ImageConvertOptions

def convert_pdf_pages_to_png():
    # Abrufen des absoluten Pfads der Lizenzdatei
    license_path = os.path.abspath("./GroupDocs.Conversion.lic")

    if os.path.exists(license_path):
        # Lizenz erstellen und den Pfad festlegen
        license = License()
        license.set_license(license_path)

    output_folder = "./converted-pages"
    os.makedirs(output_folder, exist_ok=True)

    # PDF-Dokument laden
    with Converter("./annual-review.pdf") as converter:
        # Ermitteln Sie die Gesamtzahl der Seiten im Quell-Dokument
        pages_count = converter.get_document_info().pages_count

        # Konvertierungsoptionen erstellen und sie innerhalb der Schleife wiederverwenden
        png_convert_options = ImageConvertOptions()
        png_convert_options.format = ImageFileType.PNG
        png_convert_options.pages_count = 1

        # Jede Seite in eine separate PNG-Datei konvertieren
        for page_number in range(1, pages_count + 1):
            png_convert_options.page_number = page_number
            output_file = os.path.join(output_folder, f"converted-page-{page_number}.png")
            converter.convert(output_file, png_convert_options)

if __name__ == "__main__":
    convert_pdf_pages_to_png()
```
{{< /tab >}}
{{< tab "annual-review.pdf" >}}

`annual-review.pdf` ist die in diesem Beispiel verwendete Beispieldatei. Klicken Sie [hier](https://docs.groupdocs.com/conversion/python-net/_sample_files/getting-started/quick-start-guide/annual-review.pdf), um sie herunterzuladen.

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

Ihr Ordnerbaum sollte einer ähnlichen Verzeichnisstruktur wie folgt aussehen:

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

Nach dem Ausführen der Anwendung können Sie die virtuelle Umgebung deaktivieren, indem Sie `deactivate` ausführen oder Ihre Shell schließen.

### Explanation
- `Converter("./annual-review.pdf")`: Initializes the converter with the PDF file.
- `converter.get_document_info().pages_count`: Retrieves the total number of pages in the source document.
- `ImageConvertOptions()` with `format = ImageFileType.PNG`: Specifies the output format as PNG image.
- The loop updates `png_convert_options.page_number` on each iteration (with `pages_count = 1`) and calls `converter.convert(...)` to write one PNG file per page into the `converted-pages` folder.

## Example 3: Convert files in archive

In diesem Beispiel konvertieren wir den Inhalt eines ZIP-Archivs in PDF. GroupDocs.Conversion öffnet das Archiv, konvertiert die darin enthaltenen Dateien und erzeugt ein einzelnes konsolidiertes PDF, das jedes konvertierte Dokument enthält. Sie können die Anwendung, die wir erstellen werden, [hier](https://docs.groupdocs.com/conversion/python-net/_sample_files/getting-started/quick-start-guide/convert_files_in_archive.zip) herunterladen.

{{< tabs "demo_app_convert_files_in_archive">}}
{{< tab "convert_files_in_archive.py" >}}
```python
import os
from groupdocs.conversion import License, Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

def convert_files_in_archive():
    # Abrufen des absoluten Pfads der Lizenzdatei
    license_path = os.path.abspath("./GroupDocs.Conversion.lic")

    if os.path.exists(license_path):
        # Lizenz erstellen und den Pfad festlegen
        license = License()
        license.set_license(license_path)

    # ZIP-Datei laden
    with Converter("./compressed.zip") as converter:
        # Konvertierungsoptionen erstellen
        pdf_convert_options = PdfConvertOptions()

        # Entpacken Sie das Archiv, konvertieren Sie dessen Inhalt und speichern Sie ein konsolidiertes PDF
        converter.convert("./converted.pdf", pdf_convert_options)

if __name__ == "__main__":
    convert_files_in_archive()
```
{{< /tab >}}
{{< tab "compressed.zip" >}}

`compressed.zip` ist die in diesem Beispiel verwendete Beispieldatei. Klicken Sie [hier](https://docs.groupdocs.com/conversion/python-net/_sample_files/getting-started/quick-start-guide/compressed.zip) zum Herunterladen.

{{< /tab >}}
{{< tab "converted.pdf" >}}
```text
Binary file (PDF, 283 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/getting-started/quick-start-guide/convert_files_in_archive/converted.pdf)
{{< /tab >}}
{{< /tabs >}}

Ihr Ordnerbaum sollte einer ähnlichen Verzeichnisstruktur wie folgt aussehen:

```Directory
📂 demo-app
 ├──compressed.zip
 ├──convert_files_in_archive.py
 └──GroupDocs.Conversion.lic (Optionally)
```

### Run the App

{{< tabs "run_the_app_convert_files_in_archive">}}
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

Nach dem Ausführen der Anwendung können Sie die virtuelle Umgebung deaktivieren, indem Sie `deactivate` ausführen oder Ihre Shell schließen.

### Explanation
- `Converter("./compressed.zip")`: Initializes the converter with the ZIP file.
- `PdfConvertOptions()`: Specifies the output format as PDF.
- `converter.convert("./converted.pdf", pdf_convert_options)`: Extracts the archive, converts its contents, and writes a single consolidated PDF to `converted.pdf`.

## Next Steps

Nachdem Sie die Grundlagen abgeschlossen haben, erkunden Sie zusätzliche Ressourcen, um Ihre Nutzung zu verbessern:
- [Supported File Formats](): Review the full list of supported file types.
- [Licensing](): Check details on licensing and evaluation.
- [Technical Support](): Contact support for assistance if you encounter issues.
