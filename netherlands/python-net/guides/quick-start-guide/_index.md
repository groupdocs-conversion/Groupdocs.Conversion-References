---
title: "Snelstartgids"
linkTitle: "Quick Start Guide"
second_title: "GroupDocs.Conversion for Python via .NET API-referenties"
description: "Installeer een virtuele omgeving, installeer groupdocs-conversion-net, en voer drie minimale voorbeelden uit — DOCX → PDF, PDF → per-pagina PNG, en ZIP → geconsolideerde PDF — in minder dan vijf minuten."
type: docs
url: /nl/python-net/guides/quick-start-guide/
is_root: false
weight: 20
---


Deze gids biedt een snel overzicht van hoe u GroupDocs.Conversion for Python via .NET kunt installeren en gebruiken. Deze bibliotheek stelt ontwikkelaars in staat om tussen verschillende bestandsformaten te converteren (bijv. DOCX, PDF, PNG) met minimale configuratie.

## Prerequisites

Om verder te gaan, zorg ervoor dat u het volgende heeft:

1. **Configured** omgeving zoals beschreven in het onderwerp [System Requirements]().
2. **Optionally** kunt u een [Ontvang een tijdelijke licentie](https://purchase.groupdocs.com/temporary-license/) verkrijgen om alle productfuncties te testen.

## Set Up Your Development Environment

Voor de beste praktijken, gebruik een virtuele omgeving om afhankelijkheden in Python‑toepassingen te beheren. Lees meer over virtuele omgevingen in het documentatie‑onderwerp [Maak en gebruik virtuele omgevingen](https://packaging.python.org/en/latest/guides/installing-using-pip-and-virtual-environments/#create-and-use-virtual-environments).

### Create and Activate a Virtual Environment

Maak een virtuele omgeving:

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

Activeer een virtuele omgeving:

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

Na het activeren van de virtuele omgeving, voer de volgende opdracht uit in uw terminal om de nieuwste versie van het pakket te installeren:

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

Zorg ervoor dat het pakket succesvol is geïnstalleerd. U zou het bericht moeten zien

```bash
Successfully installed groupdocs-conversion-net-*
```

## Example 1: Convert document

Om de bibliotheek snel te testen, laten we een DOCX‑bestand naar PDF converteren. U kunt ook de app die we gaan bouwen downloaden [hier](https://docs.groupdocs.com/conversion/python-net/_sample_files/getting-started/quick-start-guide/convert_docx_to_pdf.zip).

{{< tabs "demo_app_convert_docx_to_pdf">}}
{{< tab \"convert_docx_to_pdf.py\" >}}
```python
import os
from groupdocs.conversion import License, Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

def convert_docx_to_pdf():
    # Haal het absolute pad van het licentiebestand op
    license_path = os.path.abspath("./GroupDocs.Conversion.lic")

    if os.path.exists(license_path):
        # Maak een licentie aan en stel het pad in
        license = License()
        license.set_license(license_path)

    # Laad DOCX-bestand
    with Converter("./business-plan.docx") as converter:
        # Maak conversie‑opties aan
        pdf_convert_options = PdfConvertOptions()

        # Converteer DOCX naar PDF
        converter.convert("./business-plan.pdf", pdf_convert_options)    

if __name__ == "__main__":
    convert_docx_to_pdf()
```
{{< /tab >}}
{{< tab \"business-plan.docx\" >}}

`business-plan.docx` is een voorbeeldbestand dat in dit voorbeeld wordt gebruikt. Klik [hier](https://docs.groupdocs.com/conversion/python-net/_sample_files/getting-started/quick-start-guide/business-plan.docx) om het te downloaden.

{{< /tab >}}
{{< tab "business-plan.pdf" >}}
```text
Binary file (PDF, 283 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/getting-started/quick-start-guide/convert_docx_to_pdf/business-plan.pdf)
{{< /tab >}}
{{< /tabs >}}

Uw mapstructuur zou er ongeveer als volgt uit moeten zien:

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

Na het uitvoeren van de app kunt u de virtuele omgeving deactiveren door `deactivate` uit te voeren of uw shell te sluiten.

### Explanation
- `Converter("./business-plan.docx")`: Initializes the converter with the DOCX file.
- `PdfConvertOptions()`: Specifies the output format as PDF.
- `converter.convert("./business-plan.pdf", pdf_convert_options)`: Converts the DOCX file to PDF and saves it as `business-plan.pdf`.

## Example 2: Convert document pages

In dit voorbeeld zullen we PDF‑documentpagina's naar PNG converteren. U kunt de app die we gaan bouwen [hier](https://docs.groupdocs.com/conversion/python-net/_sample_files/getting-started/quick-start-guide/convert_pdf_pages_to_png.zip) downloaden.

{{< tabs "demo_app_convert_pdf_pages_to_png">}}
{{< tab "convert_pdf_pages_to_png.py" >}}
```python
import os
from groupdocs.conversion import License, Converter
from groupdocs.conversion.filetypes import ImageFileType
from groupdocs.conversion.options.convert import ImageConvertOptions

def convert_pdf_pages_to_png():
    # Haal het absolute pad van het licentiebestand op
    license_path = os.path.abspath("./GroupDocs.Conversion.lic")

    if os.path.exists(license_path):
        # Maak een licentie aan en stel het pad in
        license = License()
        license.set_license(license_path)

    output_folder = "./converted-pages"
    os.makedirs(output_folder, exist_ok=True)

    # Laad PDF‑document
    with Converter("./annual-review.pdf") as converter:
        # Bepaal het totale aantal pagina's in het bron‑document
        pages_count = converter.get_document_info().pages_count

        # Maak conversie‑opties aan en hergebruik ze binnen de lus
        png_convert_options = ImageConvertOptions()
        png_convert_options.format = ImageFileType.PNG
        png_convert_options.pages_count = 1

        # Converteer elke pagina naar een afzonderlijk PNG‑bestand
        for page_number in range(1, pages_count + 1):
            png_convert_options.page_number = page_number
            output_file = os.path.join(output_folder, f"converted-page-{page_number}.png")
            converter.convert(output_file, png_convert_options)

if __name__ == "__main__":
    convert_pdf_pages_to_png()
```
{{< /tab >}}
{{< tab "annual-review.pdf" >}}

`annual-review.pdf` is een voorbeeldbestand dat in dit voorbeeld wordt gebruikt. Klik [hier](https://docs.groupdocs.com/conversion/python-net/_sample_files/getting-started/quick-start-guide/annual-review.pdf) om het te downloaden.

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

Uw mapstructuur zou er ongeveer als volgt uit moeten zien:

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

Na het uitvoeren van de app kunt u de virtuele omgeving deactiveren door `deactivate` uit te voeren of uw shell te sluiten.

### Explanation
- `Converter("./annual-review.pdf")`: Initializes the converter with the PDF file.
- `converter.get_document_info().pages_count`: Retrieves the total number of pages in the source document.
- `ImageConvertOptions()` with `format = ImageFileType.PNG`: Specifies the output format as PNG image.
- The loop updates `png_convert_options.page_number` on each iteration (with `pages_count = 1`) and calls `converter.convert(...)` to write one PNG file per page into the `converted-pages` folder.

## Example 3: Convert files in archive

In dit voorbeeld zullen we de inhoud van een ZIP‑archief naar PDF converteren. GroupDocs.Conversion opent het archief, converteert de bestanden erin en maakt één geconsolideerde PDF die elk geconverteerd document bevat. U kunt de app die we gaan bouwen [hier](https://docs.groupdocs.com/conversion/python-net/_sample_files/getting-started/quick-start-guide/convert_files_in_archive.zip) downloaden.

{{< tabs "demo_app_convert_files_in_archive">}}
{{< tab "convert_files_in_archive.py" >}}
```python
import os
from groupdocs.conversion import License, Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

def convert_files_in_archive():
    # Haal het absolute pad van het licentiebestand op
    license_path = os.path.abspath("./GroupDocs.Conversion.lic")

    if os.path.exists(license_path):
        # Maak een licentie aan en stel het pad in
        license = License()
        license.set_license(license_path)

    # Laad ZIP‑bestand
    with Converter("./compressed.zip") as converter:
        # Maak conversie‑opties aan
        pdf_convert_options = PdfConvertOptions()

        # Extraheer het archief, converteer de inhoud en sla een geconsolideerde PDF op
        converter.convert("./converted.pdf", pdf_convert_options)

if __name__ == "__main__":
    convert_files_in_archive()
```
{{< /tab >}}
{{< tab "compressed.zip" >}}

`compressed.zip` is een voorbeeldbestand dat in dit voorbeeld wordt gebruikt. Klik [hier](https://docs.groupdocs.com/conversion/python-net/_sample_files/getting-started/quick-start-guide/compressed.zip) om het te downloaden.

{{< /tab >}}
{{< tab "converted.pdf" >}}
```text
Binary file (PDF, 283 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/getting-started/quick-start-guide/convert_files_in_archive/converted.pdf)
{{< /tab >}}
{{< /tabs >}}

Uw mapstructuur zou er ongeveer als volgt uit moeten zien:

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

Na het uitvoeren van de app kunt u de virtuele omgeving deactiveren door `deactivate` uit te voeren of uw shell te sluiten.

### Explanation
- `Converter("./compressed.zip")`: Initializes the converter with the ZIP file.
- `PdfConvertOptions()`: Specifies the output format as PDF.
- `converter.convert("./converted.pdf", pdf_convert_options)`: Extracts the archive, converts its contents, and writes a single consolidated PDF to `converted.pdf`.

## Next Steps

Na het voltooien van de basis, verken extra bronnen om uw gebruik te verbeteren:
- [Supported File Formats](): Review the full list of supported file types.
- [Licensing](): Check details on licensing and evaluation.
- [Technical Support](): Contact support for assistance if you encounter issues.
