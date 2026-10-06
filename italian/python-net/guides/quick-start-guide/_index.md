---
title: "Guida Rapida all'Avvio"
linkTitle: "Quick Start Guide"
second_title: "Riferimenti API di GroupDocs.Conversion per Python tramite .NET"
description: "Configura un ambiente virtuale, installa groupdocs-conversion-net e esegui tre esempi minimi — DOCX → PDF, PDF → PNG per pagina e ZIP → PDF consolidato — in meno di cinque minuti."
type: docs
url: /it/python-net/guides/quick-start-guide/
is_root: false
weight: 20
---


Questa guida offre una panoramica rapida su come configurare e iniziare a utilizzare GroupDocs.Conversion per Python tramite .NET. Questa libreria consente agli sviluppatori di convertire tra vari formati di file (ad es., DOCX, PDF, PNG) con una configurazione minima.

## Prerequisites

Per procedere, assicurati di avere:

1. **Configured** ambiente come descritto nella sezione [System Requirements]().
2. **Optionally** puoi [Get a Temporary License](https://purchase.groupdocs.com/temporary-license/) per testare tutte le funzionalità del prodotto.

## Set Up Your Development Environment

Per le migliori pratiche, utilizza un ambiente virtuale per gestire le dipendenze nelle applicazioni Python. Scopri di più sugli ambienti virtuali nella sezione documentazione [Create and Use Virtual Environments](https://packaging.python.org/en/latest/guides/installing-using-pip-and-virtual-environments/#create-and-use-virtual-environments).

### Create and Activate a Virtual Environment

Crea un ambiente virtuale:

{{< tabs "example1">}}
{{< tab "Windows" >}}
```ps
py -m venv .venv
```
{{< /tab >}}
{{< tab "Linux" >}}
```bash
python3 -m venv .venv
```
{{< /tab >}}
{{< tab "macOS" >}}
```bash
python3 -m venv .venv
```
{{< /tab >}}
{{< /tabs >}}

Attiva un ambiente virtuale:

{{< tabs "example2">}}
{{< tab "Windows" >}}
```ps
.venv\Scripts\activate
```
{{< /tab >}}
{{< tab "Linux" >}}
```bash
source .venv/bin/activate
```
{{< /tab >}}
{{< tab "macOS" >}}
```bash
source .venv/bin/activate
```
{{< /tab >}}
{{< /tabs >}}

### Install `groupdocs-conversion-net` Package

Dopo aver attivato l'ambiente virtuale, esegui il seguente comando nel tuo terminale per installare l'ultima versione del pacchetto:

{{< tabs "example3">}}
{{< tab "Windows" >}}
```ps
py -m pip install groupdocs-conversion-net
```
{{< /tab >}}
{{< tab "Linux" >}}
```bash
python3 -m pip install groupdocs-conversion-net
```
{{< /tab >}}
{{< tab "macOS" >}}
```bash
python3 -m pip install groupdocs-conversion-net
```
{{< /tab >}}
{{< /tabs >}}

Assicurati che il pacchetto sia installato correttamente. Dovresti vedere il messaggio

```bash
Successfully installed groupdocs-conversion-net-*
```

## Example 1: Convert document

Per testare rapidamente la libreria, convertiamo un file DOCX in PDF. Puoi anche scaricare l'app che costruiremo [qui](https://docs.groupdocs.com/conversion/python-net/_sample_files/getting-started/quick-start-guide/convert_docx_to_pdf.zip).

{{< tabs "demo_app_convert_docx_to_pdf">}}
{{< tab \"convert_docx_to_pdf.py\" >}}
```python
import os
from groupdocs.conversion import License, Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

def convert_docx_to_pdf():
    # Ottieni il percorso assoluto del file di licenza
    license_path = os.path.abspath("./GroupDocs.Conversion.lic")

    if os.path.exists(license_path):
        # Crea la licenza e imposta il percorso
        license = License()
        license.set_license(license_path)

    # Carica il file DOCX
    with Converter("./business-plan.docx") as converter:
        # Crea le opzioni di conversione
        pdf_convert_options = PdfConvertOptions()

        # Converti DOCX in PDF
        converter.convert("./business-plan.pdf", pdf_convert_options)    

if __name__ == "__main__":
    convert_docx_to_pdf()
```
{{< /tab >}}
{{< tab \"business-plan.docx\" >}}

`business-plan.docx` è il file di esempio utilizzato in questo esempio. Fai clic [qui](https://docs.groupdocs.com/conversion/python-net/_sample_files/getting-started/quick-start-guide/business-plan.docx) per scaricarlo.

{{< /tab >}}
{{< tab "business-plan.pdf" >}}
```text
Binary file (PDF, 283 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/getting-started/quick-start-guide/convert_docx_to_pdf/business-plan.pdf)
{{< /tab >}}
{{< /tabs >}}

L'albero delle cartelle dovrebbe apparire simile alla seguente struttura di directory:

```Directory
📂 demo-app
 ├──convert_docx_to_pdf.py
 ├──business-plan.docx
 └──GroupDocs.Conversion.lic (Optionally)
```

### Run the App

{{< tabs "run-the-app">}}
{{< tab "Windows" >}}
```ps
py convert_docx_to_pdf.py
```
{{< /tab >}}
{{< tab "Linux" >}}
```bash
python3 convert_docx_to_pdf.py
```
{{< /tab >}}
{{< tab "macOS" >}}
```bash
python3 convert_docx_to_pdf.py
```
{{< /tab >}}
{{< /tabs >}}

Dopo aver eseguito l'app puoi disattivare l'ambiente virtuale eseguendo `deactivate` o chiudendo il terminale.

### Explanation
- `Converter("./business-plan.docx")`: Initializes the converter with the DOCX file.
- `PdfConvertOptions()`: Specifies the output format as PDF.
- `converter.convert("./business-plan.pdf", pdf_convert_options)`: Converts the DOCX file to PDF and saves it as `business-plan.pdf`.

## Example 2: Convert document pages

In questo esempio convertiremo le pagine del documento PDF in PNG. Puoi scaricare l'app che costruiremo [qui](https://docs.groupdocs.com/conversion/python-net/_sample_files/getting-started/quick-start-guide/convert_pdf_pages_to_png.zip).

{{< tabs "demo_app_convert_pdf_pages_to_png">}}
{{< tab "convert_pdf_pages_to_png.py" >}}
```python
import os
from groupdocs.conversion import License, Converter
from groupdocs.conversion.filetypes import ImageFileType
from groupdocs.conversion.options.convert import ImageConvertOptions

def convert_pdf_pages_to_png():
    # Ottieni il percorso assoluto del file di licenza
    license_path = os.path.abspath("./GroupDocs.Conversion.lic")

    if os.path.exists(license_path):
        # Crea la licenza e imposta il percorso
        license = License()
        license.set_license(license_path)

    output_folder = "./converted-pages"
    os.makedirs(output_folder, exist_ok=True)

    # Carica il documento PDF
    with Converter("./annual-review.pdf") as converter:
        # Determina il numero totale di pagine nel documento di origine
        pages_count = converter.get_document_info().pages_count

        # Crea le opzioni di conversione e riutilizzale all'interno del ciclo
        png_convert_options = ImageConvertOptions()
        png_convert_options.format = ImageFileType.PNG
        png_convert_options.pages_count = 1

        # Converti ogni pagina in un file PNG separato
        for page_number in range(1, pages_count + 1):
            png_convert_options.page_number = page_number
            output_file = os.path.join(output_folder, f"converted-page-{page_number}.png")
            converter.convert(output_file, png_convert_options)

if __name__ == "__main__":
    convert_pdf_pages_to_png()
```
{{< /tab >}}
{{< tab "annual-review.pdf" >}}

`annual-review.pdf` è il file di esempio usato in questo esempio. Fai clic [qui](https://docs.groupdocs.com/conversion/python-net/_sample_files/getting-started/quick-start-guide/annual-review.pdf) per scaricarlo.

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

L'albero delle cartelle dovrebbe apparire simile alla seguente struttura di directory:

```Directory
📂 demo-app
 ├──annual-review.pdf
 ├──convert_pdf_pages_to_png.py
 └──GroupDocs.Conversion.lic (Optionally)
```

### Run the App

{{< tabs "run_the_app_convert_pdf_pages_to_png">}}
{{< tab "Windows" >}}
```ps
py convert_pdf_pages_to_png.py
```
{{< /tab >}}
{{< tab "Linux" >}}
```bash
python3 convert_pdf_pages_to_png.py
```
{{< /tab >}}
{{< tab "macOS" >}}
```bash
python3 convert_pdf_pages_to_png.py
```
{{< /tab >}}
{{< /tabs >}}

Dopo aver eseguito l'app puoi disattivare l'ambiente virtuale eseguendo `deactivate` o chiudendo il terminale.

### Explanation
- `Converter("./annual-review.pdf")`: Initializes the converter with the PDF file.
- `converter.get_document_info().pages_count`: Retrieves the total number of pages in the source document.
- `ImageConvertOptions()` with `format = ImageFileType.PNG`: Specifies the output format as PNG image.
- The loop updates `png_convert_options.page_number` on each iteration (with `pages_count = 1`) and calls `converter.convert(...)` to write one PNG file per page into the `converted-pages` folder.

## Example 3: Convert files in archive

In questo esempio convertiremo il contenuto di un archivio ZIP in PDF. GroupDocs.Conversion apre l'archivio, converte i file al suo interno e produce un unico PDF consolidato che contiene tutti i documenti convertiti. Puoi scaricare l'app che costruiremo [qui](https://docs.groupdocs.com/conversion/python-net/_sample_files/getting-started/quick-start-guide/convert_files_in_archive.zip).

{{< tabs "demo_app_convert_files_in_archive">}}
{{< tab "convert_files_in_archive.py" >}}
```python
import os
from groupdocs.conversion import License, Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

def convert_files_in_archive():
    # Ottieni il percorso assoluto del file di licenza
    license_path = os.path.abspath("./GroupDocs.Conversion.lic")

    if os.path.exists(license_path):
        # Crea la licenza e imposta il percorso
        license = License()
        license.set_license(license_path)

    # Carica il file ZIP
    with Converter("./compressed.zip") as converter:
        # Crea le opzioni di conversione
        pdf_convert_options = PdfConvertOptions()

        # Estrai l'archivio, converti il suo contenuto e salva un PDF consolidato
        converter.convert("./converted.pdf", pdf_convert_options)

if __name__ == "__main__":
    convert_files_in_archive()
```
{{< /tab >}}
{{< tab \"compressed.zip\" >}}

`compressed.zip` è il file di esempio utilizzato in questo esempio. Fai clic [qui](https://docs.groupdocs.com/conversion/python-net/_sample_files/getting-started/quick-start-guide/compressed.zip) per scaricarlo.

{{< /tab >}}
{{< tab \"converted.pdf\" >}}
```text
Binary file (PDF, 283 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/getting-started/quick-start-guide/convert_files_in_archive/converted.pdf)
{{< /tab >}}
{{< /tabs >}}

L'albero delle cartelle dovrebbe apparire simile alla seguente struttura di directory:

```Directory
📂 demo-app
 ├──compressed.zip
 ├──convert_files_in_archive.py
 └──GroupDocs.Conversion.lic (Optionally)
```

### Run the App

{{< tabs \"run_the_app_convert_files_in_archive\">}}
{{< tab "Windows" >}}
```ps
py convert_files_in_archive.py
```
{{< /tab >}}
{{< tab "Linux" >}}
```bash
python3 convert_files_in_archive.py
```
{{< /tab >}}
{{< tab "macOS" >}}
```bash
python3 convert_files_in_archive.py
```
{{< /tab >}}
{{< /tabs >}}

Dopo aver eseguito l'app puoi disattivare l'ambiente virtuale eseguendo `deactivate` o chiudendo il terminale.

### Explanation
- `Converter("./compressed.zip")`: Initializes the converter with the ZIP file.
- `PdfConvertOptions()`: Specifies the output format as PDF.
- `converter.convert("./converted.pdf", pdf_convert_options)`: Extracts the archive, converts its contents, and writes a single consolidated PDF to `converted.pdf`.

## Next Steps

Dopo aver completato le basi, esplora risorse aggiuntive per migliorare il tuo utilizzo:
- [Supported File Formats](): Review the full list of supported file types.
- [Licensing](): Check details on licensing and evaluation.
- [Technical Support](): Contact support for assistance if you encounter issues.
