---
title: "Snabbstartsguide"
linkTitle: "Quick Start Guide"
second_title: "GroupDocs.Conversion for Python via .NET API-referenser"
description: "Skapa en virtuell miljö, installera groupdocs-conversion-net och kör tre minimala exempel — DOCX → PDF, PDF → per‑sida PNG och ZIP → sammanslagen PDF — på mindre än fem minuter."
type: docs
url: /sv/python-net/guides/quick-start-guide/
is_root: false
weight: 20
---


Denna guide ger en snabb översikt över hur du ställer in och börjar använda GroupDocs.Conversion för Python via .NET. Detta bibliotek låter utvecklare konvertera mellan olika filformat (t.ex. DOCX, PDF, PNG) med minimal konfiguration.

## Prerequisites

För att fortsätta, se till att du har:

1. **Configured** miljö enligt beskrivningen i ämnet [System Requirements]().
2. **Optionally** kan du [Skaffa en tillfällig licens](https://purchase.groupdocs.com/temporary-license/) för att testa alla produktfunktioner.

## Set Up Your Development Environment

För bästa praxis, använd en virtuell miljö för att hantera beroenden i Python‑applikationer. Läs mer om virtuella miljöer i dokumentationsämnet [Skapa och använd virtuella miljöer](https://packaging.python.org/en/latest/guides/installing-using-pip-and-virtual-environments/#create-and-use-virtual-environments).

### Create and Activate a Virtual Environment

Skapa en virtuell miljö:

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

Aktivera en virtuell miljö:

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

Efter att ha aktiverat den virtuella miljön, kör följande kommando i din terminal för att installera den senaste versionen av paketet:

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

Säkerställ att paketet har installerats framgångsrikt. Du bör se meddelandet

```bash
Successfully installed groupdocs-conversion-net-*
```

## Example 1: Convert document

För att snabbt testa biblioteket, låt oss konvertera en DOCX‑fil till PDF. Du kan också ladda ner appen som vi ska bygga [här](https://docs.groupdocs.com/conversion/python-net/_sample_files/getting-started/quick-start-guide/convert_docx_to_pdf.zip).

{{< tabs \"demo_app_convert_docx_to_pdf\">}}
{{< tab "convert_docx_to_pdf.py" >}}
```python
import os
from groupdocs.conversion import License, Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

def convert_docx_to_pdf():
    # Hämta licensfilens absoluta sökväg
    license_path = os.path.abspath("./GroupDocs.Conversion.lic")

    if os.path.exists(license_path):
        # Skapa licens och ange sökvägen
        license = License()
        license.set_license(license_path)

    # Läs in DOCX‑fil
    with Converter("./business-plan.docx") as converter:
        # Skapa konverteringsalternativ
        pdf_convert_options = PdfConvertOptions()

        # Konvertera DOCX till PDF
        converter.convert("./business-plan.pdf", pdf_convert_options)    

if __name__ == "__main__":
    convert_docx_to_pdf()
```
{{< /tab >}}
{{< tab "business-plan.docx" >}}

`business-plan.docx` är en exempelfil som används i detta exempel. Klicka [här](https://docs.groupdocs.com/conversion/python-net/_sample_files/getting-started/quick-start-guide/business-plan.docx) för att ladda ner den.

{{< /tab >}}
{{< tab "business-plan.pdf" >}}
```text
Binary file (PDF, 283 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/getting-started/quick-start-guide/convert_docx_to_pdf/business-plan.pdf)
{{< /tab >}}
{{< /tabs >}}

Din mappstruktur bör se liknande ut som följande katalogstruktur:

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

Efter att du har kört appen kan du inaktivera den virtuella miljön genom att köra `deactivate` eller stänga ditt skal.

### Explanation
- `Converter("./business-plan.docx")`: Initializes the converter with the DOCX file.
- `PdfConvertOptions()`: Specifies the output format as PDF.
- `converter.convert("./business-plan.pdf", pdf_convert_options)`: Converts the DOCX file to PDF and saves it as `business-plan.pdf`.

## Example 2: Convert document pages

I det här exemplet kommer vi att konvertera PDF-dokumentsidor till PNG. Du kan ladda ner appen som vi ska bygga [här](https://docs.groupdocs.com/conversion/python-net/_sample_files/getting-started/quick-start-guide/convert_pdf_pages_to_png.zip).

{{< tabs "demo_app_convert_pdf_pages_to_png">}}
{{< tab "convert_pdf_pages_to_png.py" >}}
```python
import os
from groupdocs.conversion import License, Converter
from groupdocs.conversion.filetypes import ImageFileType
from groupdocs.conversion.options.convert import ImageConvertOptions

def convert_pdf_pages_to_png():
    # Hämta licensfilens absoluta sökväg
    license_path = os.path.abspath("./GroupDocs.Conversion.lic")

    if os.path.exists(license_path):
        # Skapa licens och ange sökvägen
        license = License()
        license.set_license(license_path)

    output_folder = "./converted-pages"
    os.makedirs(output_folder, exist_ok=True)

    # Läs in PDF-dokument
    with Converter("./annual-review.pdf") as converter:
        # Bestäm det totala antalet sidor i källdokumentet
        pages_count = converter.get_document_info().pages_count

        # Skapa konverteringsalternativ och återanvänd dem i loopen
        png_convert_options = ImageConvertOptions()
        png_convert_options.format = ImageFileType.PNG
        png_convert_options.pages_count = 1

        # Konvertera varje sida till en separat PNG-fil
        for page_number in range(1, pages_count + 1):
            png_convert_options.page_number = page_number
            output_file = os.path.join(output_folder, f"converted-page-{page_number}.png")
            converter.convert(output_file, png_convert_options)

if __name__ == "__main__":
    convert_pdf_pages_to_png()
```
{{< /tab >}}
{{< tab "annual-review.pdf" >}}

`annual-review.pdf` är en exempelfil som används i detta exempel. Klicka [här](https://docs.groupdocs.com/conversion/python-net/_sample_files/getting-started/quick-start-guide/annual-review.pdf) för att ladda ner den.

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

Din mappstruktur bör se liknande ut som följande katalogstruktur:

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

Efter att du har kört appen kan du inaktivera den virtuella miljön genom att köra `deactivate` eller stänga ditt skal.

### Explanation
- `Converter("./annual-review.pdf")`: Initializes the converter with the PDF file.
- `converter.get_document_info().pages_count`: Retrieves the total number of pages in the source document.
- `ImageConvertOptions()` with `format = ImageFileType.PNG`: Specifies the output format as PNG image.
- The loop updates `png_convert_options.page_number` on each iteration (with `pages_count = 1`) and calls `converter.convert(...)` to write one PNG file per page into the `converted-pages` folder.

## Example 3: Convert files in archive

I det här exemplet kommer vi att konvertera innehållet i ett ZIP-arkiv till PDF. GroupDocs.Conversion öppnar arkivet, konverterar filerna inuti och skapar en enda samlad PDF som innehåller alla konverterade dokument. Du kan ladda ner appen som vi ska bygga [här](https://docs.groupdocs.com/conversion/python-net/_sample_files/getting-started/quick-start-guide/convert_files_in_archive.zip).

{{< tabs "demo_app_convert_files_in_archive">}}
{{< tab "convert_files_in_archive.py" >}}
```python
import os
from groupdocs.conversion import License, Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

def convert_files_in_archive():
    # Hämta licensfilens absoluta sökväg
    license_path = os.path.abspath("./GroupDocs.Conversion.lic")

    if os.path.exists(license_path):
        # Skapa licens och ange sökvägen
        license = License()
        license.set_license(license_path)

    # Läs in ZIP-fil
    with Converter("./compressed.zip") as converter:
        # Skapa konverteringsalternativ
        pdf_convert_options = PdfConvertOptions()

        # Extrahera arkivet, konvertera dess innehåll och spara en samlad PDF
        converter.convert("./converted.pdf", pdf_convert_options)

if __name__ == "__main__":
    convert_files_in_archive()
```
{{< /tab >}}
{{< tab \"compressed.zip\" >}}

`compressed.zip` är en exempelfil som används i detta exempel. Klicka [här](https://docs.groupdocs.com/conversion/python-net/_sample_files/getting-started/quick-start-guide/compressed.zip) för att ladda ner den.

{{< /tab >}}
{{< tab \"converted.pdf\" >}}
```text
Binary file (PDF, 283 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/getting-started/quick-start-guide/convert_files_in_archive/converted.pdf)
{{< /tab >}}
{{< /tabs >}}

Din mappstruktur bör se liknande ut som följande katalogstruktur:

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

Efter att du har kört appen kan du inaktivera den virtuella miljön genom att köra `deactivate` eller stänga ditt skal.

### Explanation
- `Converter("./compressed.zip")`: Initializes the converter with the ZIP file.
- `PdfConvertOptions()`: Specifies the output format as PDF.
- `converter.convert("./converted.pdf", pdf_convert_options)`: Extracts the archive, converts its contents, and writes a single consolidated PDF to `converted.pdf`.

## Next Steps

Efter att du har slutfört grunderna, utforska ytterligare resurser för att förbättra din användning:
- [Supported File Formats](): Review the full list of supported file types.
- [Licensing](): Check details on licensing and evaluation.
- [Technical Support](): Contact support for assistance if you encounter issues.
