---
title: "Convertir le document en plusieurs fichiers de pages"
linkTitle: "Convert Document To Multiple"
second_title: "GroupDocs.Conversion for Python via .NET Références API"
description: "id: convert-document-to-multiple-page-files"
type: docs
url: /fr/python-net/guides/convert-document-to-multiple-page-files/
is_root: false
weight: 60
---


---
id: convert-document-to-multiple-page-files
url: conversion/python-net/developer-guide/converting-documents/convert-document-to-multiple-page-files
title: Convertir un document en plusieurs fichiers de pages
linkTitle: Convertir en plusieurs fichiers
weight: 3
description: "Rendre chaque page d'un document multipage dans son propre fichier de sortie — boucler page_number avec pages_count=1 et Converter.convert() pour produire un PNG, PDF ou image par page avec GroupDocs.Conversion pour Python via .NET."
keywords: convertir en plusieurs fichiers, sortie par page, page_number, pages_count, boucle de pages, convertir les pages de présentation, convertir les pages PDF en PNG, ImageConvertOptions, GroupDocs.Conversion, python
productName: GroupDocs.Conversion pour Python via .NET
hideChildren: false
toc: true
---

Ce sujet de documentation couvre la conversion d'un document multipage unique en fichiers de pages individuels. Le diagramme suivant illustre le processus de conversion d'un fichier multipage en pages séparées :

flowchart LR
%% Nodes
A["Document d'entrée"]
B[\"Conversion\"]
C["Page convertie 1"]
D["Page convertie 2"]
E["Page convertie N"]

%% Edge connections between nodes
A --> B --> C
B --> D
B --> E

Pour convertir un document en fichiers par page, utilisez la méthode `Converter.convert(file_path, convert_options)` ainsi que les attributs `page_number` et `pages_count` sur les classes [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/) prises en charge :

- **`page_number`**: One-based index of the first page to convert.
- **`pages_count`**: Number of consecutive pages to convert starting from `page_number`.

Pour produire un fichier de sortie par page, bouclez de `1` à `converter.get_document_info().pages_count`, en mettant à jour `page_number` à chaque itération et en écrivant vers un chemin de sortie différent. Définir `pages_count = 1` garantit que chaque appel génère une seule page.

## Supported ConvertOptions Classes

Les classes [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/) suivantes exposent les attributs `page_number` et `pages_count` utilisés dans ce sujet :

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

L'exemple suivant montre comment convertir chaque diapositive d'une présentation PPTX en image PNG et enregistrer les images de sortie dans un dossier spécifié.
 
Le modèle de nom de fichier pour les fichiers de sortie est `converted-page-{page number}.{output file extension}`. Dans cet exemple, la première diapositive sera enregistrée sous `converted-page-1.png`.

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

    # Instanciez le Convertisseur avec le document d'entrée
    with Converter("./basic-presentation.pptx") as converter:
        # Déterminer le nombre total de pages dans le document source
        pages_count = converter.get_document_info().pages_count

        # Instanciez les options de conversion une fois et réutilisez-les à l'intérieur de la boucle
        png_convert_options = ImageConvertOptions()
        png_convert_options.format = ImageFileType.PNG
        png_convert_options.pages_count = 1

        # Convertir chaque page en un fichier PNG séparé
        for page_number in range(1, pages_count + 1):
            png_convert_options.page_number = page_number
            output_file = os.path.join(output_folder, f"converted-page-{page_number}.png")
            converter.convert(output_file, png_convert_options)

if __name__ == "__main__":
    convert_all_document_pages()
```
{{< /tab >}}
{{< tab "basic-presentation.pptx" >}}

`basic-presentation.pptx` est le fichier d'exemple utilisé dans cet exemple. Cliquez [ici](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/convert-document-to-multiple-page-files/basic-presentation.pptx) pour le télécharger.

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

Découvrez comment obtenir le nombre de pages du document dans le sujet de documentation [Getting Document Information]().

L'exemple suivant montre comment convertir une diapositive spécifique d'une présentation PPTX et l'enregistrer en tant que fichier distinct.

{{< tabs \"example-2\">}}
{{< tab "convert_specific_document_page_to_file.py" >}}
```python
from groupdocs.conversion import Converter
from groupdocs.conversion.filetypes import ImageFileType
from groupdocs.conversion.options.convert import ImageConvertOptions

def convert_specific_document_page_to_file():
    # Instanciez le Convertisseur avec le document d'entrée
    with Converter("./basic-presentation.pptx") as converter:
        # Instanciez les options de conversion
        png_convert_options = ImageConvertOptions()
        # Définissez le format de sortie comme PNG
        png_convert_options.format = ImageFileType.PNG

        # Spécifiez la page unique à convertir
        png_convert_options.page_number = 3
        png_convert_options.pages_count = 1

        # Enregistrez la page convertie dans un fichier
        converter.convert("./slide-3.png", png_convert_options)

if __name__ == "__main__":
    convert_specific_document_page_to_file()
```
{{< /tab >}}
{{< tab "basic-presentation.pptx" >}}

`basic-presentation.pptx` est le fichier d'exemple utilisé dans cet exemple. Cliquez [ici](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/convert-document-to-multiple-page-files/basic-presentation.pptx) pour le télécharger.

{{< /tab >}}
{{< tab "slide-3.png" >}}
```text
Binary file (PNG, 797 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/converting-documents/convert-document-to-multiple-page-files/convert_specific_document_page_to_file/slide-3.png)
{{< /tab >}}
{{< /tabs >}}

## Example 3: Convert a Specific Page and Load Output Into a Stream

Découvrez comment obtenir le nombre de pages du document dans le sujet de documentation [Getting Document Information]().

Si vous avez besoin de la page convertie sous forme de tampon en mémoire (par exemple, pour la transmettre à une autre API sans toucher au système de fichiers par la suite), convertissez d'abord la page en fichier puis lisez‑la dans un objet `BytesIO` :

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

    # Instanciez le Convertisseur avec le document d'entrée
    with Converter("./basic-presentation.pptx") as converter:
        # Instanciez les options de conversion
        png_convert_options = ImageConvertOptions()
        # Définissez le format de sortie comme PNG
        png_convert_options.format = ImageFileType.PNG

        # Spécifiez la page unique à convertir
        png_convert_options.page_number = page_number_to_convert
        png_convert_options.pages_count = 1

        # Convertissez et enregistrez la page dans un fichier sur le disque
        converter.convert(output_file, png_convert_options)

    # Chargez la page convertie dans un flux en mémoire pour une utilisation en aval
    with open(output_file, "rb") as file_handle:
        page_stream = io.BytesIO(file_handle.read())

    # page_stream contient maintenant les octets PNG et peut être transmis à n'importe quel consommateur
    print(f"Loaded {page_stream.getbuffer().nbytes} bytes into memory")

if __name__ == "__main__":
    convert_specific_document_page_to_stream()
```
{{< /tab >}}
{{< tab "basic-presentation.pptx" >}}

`basic-presentation.pptx` est le fichier d'exemple utilisé dans cet exemple. Cliquez [ici](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/convert-document-to-multiple-page-files/basic-presentation.pptx) pour le télécharger.

{{< /tab >}}
{{< tab "slide-5.png" >}}
```text
Binary file (PNG, 75 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/converting-documents/convert-document-to-multiple-page-files/convert_specific_document_page_to_stream/slide-5.png)
{{< /tab >}}
{{< /tabs >}}
