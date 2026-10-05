---
title: "Guide de démarrage rapide"
linkTitle: "Quick Start Guide"
second_title: "GroupDocs.Conversion for Python via .NET Références API"
description: "Configurez un environnement virtuel, installez groupdocs-conversion-net et exécutez trois exemples minimalistes — DOCX → PDF, PDF → PNG page par page, et ZIP → PDF consolidé — en moins de cinq minutes."
type: docs
url: /fr/python-net/guides/quick-start-guide/
is_root: false
weight: 20
---


Ce guide offre un aperçu rapide de la façon de configurer et de commencer à utiliser GroupDocs.Conversion pour Python via .NET. Cette bibliothèque permet aux développeurs de convertir entre différents formats de fichiers (par ex., DOCX, PDF, PNG) avec une configuration minimale.

## Prerequisites

Pour continuer, assurez‑vous d'avoir :

1. **Configured** l'environnement tel que décrit dans le sujet [System Requirements]().
2. **Optionally** vous pouvez [Get a Temporary License](https://purchase.groupdocs.com/temporary-license/) pour tester toutes les fonctionnalités du produit.

## Set Up Your Development Environment

Pour les meilleures pratiques, utilisez un environnement virtuel pour gérer les dépendances dans les applications Python. En savoir plus sur les environnements virtuels dans le sujet de documentation [Create and Use Virtual Environments](https://packaging.python.org/en/latest/guides/installing-using-pip-and-virtual-environments/#create-and-use-virtual-environments).

### Create and Activate a Virtual Environment

Créez un environnement virtuel :

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

Activez un environnement virtuel :

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

Après avoir activé l'environnement virtuel, exécutez la commande suivante dans votre terminal pour installer la dernière version du paquet :

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

Assurez‑vous que le paquet est installé avec succès. Vous devriez voir le message

```bash
Successfully installed groupdocs-conversion-net-*
```

## Example 1: Convert document

Pour tester rapidement la bibliothèque, convertissons un fichier DOCX en PDF. Vous pouvez également télécharger l'application que nous allons créer [ici](https://docs.groupdocs.com/conversion/python-net/_sample_files/getting-started/quick-start-guide/convert_docx_to_pdf.zip).

{{< tabs "demo_app_convert_docx_to_pdf">}}
{{< tab \"convert_docx_to_pdf.py\" >}}
```python
import os
from groupdocs.conversion import License, Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

def convert_docx_to_pdf():
    # Obtenir le chemin absolu du fichier de licence
    license_path = os.path.abspath("./GroupDocs.Conversion.lic")

    if os.path.exists(license_path):
        # Créer la licence et définir le chemin
        license = License()
        license.set_license(license_path)

    # Charger le fichier DOCX
    with Converter("./business-plan.docx") as converter:
        # Créer les options de conversion
        pdf_convert_options = PdfConvertOptions()

        # Convertir le DOCX en PDF
        converter.convert("./business-plan.pdf", pdf_convert_options)    

if __name__ == "__main__":
    convert_docx_to_pdf()
```
{{< /tab >}}
{{< tab \"business-plan.docx\" >}}

`business-plan.docx` est un fichier d'exemple utilisé dans cet exemple. Cliquez [ici](https://docs.groupdocs.com/conversion/python-net/_sample_files/getting-started/quick-start-guide/business-plan.docx) pour le télécharger.

{{< /tab >}}
{{< tab \"business-plan.pdf\" >}}
```text
Binary file (PDF, 283 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/getting-started/quick-start-guide/convert_docx_to_pdf/business-plan.pdf)
{{< /tab >}}
{{< /tabs >}}

Votre arborescence de dossiers devrait ressembler à la structure de répertoires suivante :

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

Après avoir exécuté l'application, vous pouvez désactiver l'environnement virtuel en exécutant `deactivate` ou en fermant votre shell.

### Explanation
- `Converter("./business-plan.docx")`: Initializes the converter with the DOCX file.
- `PdfConvertOptions()`: Specifies the output format as PDF.
- `converter.convert("./business-plan.pdf", pdf_convert_options)`: Converts the DOCX file to PDF and saves it as `business-plan.pdf`.

## Example 2: Convert document pages

Dans cet exemple, nous convertirons les pages d'un document PDF en PNG. Vous pouvez télécharger l'application que nous allons créer [ici](https://docs.groupdocs.com/conversion/python-net/_sample_files/getting-started/quick-start-guide/convert_pdf_pages_to_png.zip).

{{< tabs "demo_app_convert_pdf_pages_to_png">}}
{{< tab "convert_pdf_pages_to_png.py" >}}
```python
import os
from groupdocs.conversion import License, Converter
from groupdocs.conversion.filetypes import ImageFileType
from groupdocs.conversion.options.convert import ImageConvertOptions

def convert_pdf_pages_to_png():
    # Obtenir le chemin absolu du fichier de licence
    license_path = os.path.abspath("./GroupDocs.Conversion.lic")

    if os.path.exists(license_path):
        # Créer la licence et définir le chemin
        license = License()
        license.set_license(license_path)

    output_folder = "./converted-pages"
    os.makedirs(output_folder, exist_ok=True)

    # Charger le document PDF
    with Converter("./annual-review.pdf") as converter:
        # Déterminer le nombre total de pages dans le document source
        pages_count = converter.get_document_info().pages_count

        # Créer les options de conversion et les réutiliser dans la boucle
        png_convert_options = ImageConvertOptions()
        png_convert_options.format = ImageFileType.PNG
        png_convert_options.pages_count = 1

        # Convertir chaque page en un fichier PNG séparé
        for page_number in range(1, pages_count + 1):
            png_convert_options.page_number = page_number
            output_file = os.path.join(output_folder, f"converted-page-{page_number}.png")
            converter.convert(output_file, png_convert_options)

if __name__ == "__main__":
    convert_pdf_pages_to_png()
```
{{< /tab >}}
{{< tab "annual-review.pdf" >}}

`annual-review.pdf` est un fichier d'exemple utilisé dans cet exemple. Cliquez [ici](https://docs.groupdocs.com/conversion/python-net/_sample_files/getting-started/quick-start-guide/annual-review.pdf) pour le télécharger.

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

Votre arborescence de dossiers devrait ressembler à la structure de répertoires suivante :

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

Après avoir exécuté l'application, vous pouvez désactiver l'environnement virtuel en exécutant `deactivate` ou en fermant votre shell.

### Explanation
- `Converter("./annual-review.pdf")`: Initializes the converter with the PDF file.
- `converter.get_document_info().pages_count`: Retrieves the total number of pages in the source document.
- `ImageConvertOptions()` with `format = ImageFileType.PNG`: Specifies the output format as PNG image.
- The loop updates `png_convert_options.page_number` on each iteration (with `pages_count = 1`) and calls `converter.convert(...)` to write one PNG file per page into the `converted-pages` folder.

## Example 3: Convert files in archive

Dans cet exemple, nous convertirons le contenu d'une archive ZIP en PDF. GroupDocs.Conversion ouvre l'archive, convertit les fichiers qu'elle contient et produit un PDF consolidé unique contenant chaque document converti. Vous pouvez télécharger l'application que nous allons créer [ici](https://docs.groupdocs.com/conversion/python-net/_sample_files/getting-started/quick-start-guide/convert_files_in_archive.zip).

{{< tabs "demo_app_convert_files_in_archive">}}
{{< tab "convert_files_in_archive.py" >}}
```python
import os
from groupdocs.conversion import License, Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

def convert_files_in_archive():
    # Obtenir le chemin absolu du fichier de licence
    license_path = os.path.abspath("./GroupDocs.Conversion.lic")

    if os.path.exists(license_path):
        # Créer la licence et définir le chemin
        license = License()
        license.set_license(license_path)

    # Charger le fichier ZIP
    with Converter("./compressed.zip") as converter:
        # Créer les options de conversion
        pdf_convert_options = PdfConvertOptions()

        # Extrayez l'archive, convertissez son contenu et enregistrez un PDF consolidé
        converter.convert("./converted.pdf", pdf_convert_options)

if __name__ == "__main__":
    convert_files_in_archive()
```
{{< /tab >}}
{{< tab "compressed.zip" >}}

`compressed.zip` est un fichier d'exemple utilisé dans cet exemple. Cliquez [ici](https://docs.groupdocs.com/conversion/python-net/_sample_files/getting-started/quick-start-guide/compressed.zip) pour le télécharger.

{{< /tab >}}
{{< tab "converted.pdf" >}}
```text
Binary file (PDF, 283 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/getting-started/quick-start-guide/convert_files_in_archive/converted.pdf)
{{< /tab >}}
{{< /tabs >}}

Votre arborescence de dossiers devrait ressembler à la structure de répertoires suivante :

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

Après avoir exécuté l'application, vous pouvez désactiver l'environnement virtuel en exécutant `deactivate` ou en fermant votre shell.

### Explanation
- `Converter("./compressed.zip")`: Initializes the converter with the ZIP file.
- `PdfConvertOptions()`: Specifies the output format as PDF.
- `converter.convert("./converted.pdf", pdf_convert_options)`: Extracts the archive, converts its contents, and writes a single consolidated PDF to `converted.pdf`.

## Next Steps

Après avoir terminé les bases, explorez des ressources supplémentaires pour améliorer votre utilisation :
- [Supported File Formats](): Review the full list of supported file types.
- [Licensing](): Check details on licensing and evaluation.
- [Technical Support](): Contact support for assistance if you encounter issues.
