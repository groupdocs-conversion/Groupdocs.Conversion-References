---
title: "Convertir des fichiers à l’intérieur des conteneurs de documents"
linkTitle: "Convert Archives and Containers"
second_title: "GroupDocs.Conversion for Python via .NET Références API"
description: "Ouvrez les formats de conteneurs ZIP, RAR, 7Z, OST, PST et autres, convertissez leur contenu, et écrivez un document de sortie consolidé en un seul appel Converter.convert() avec GroupDocs.Conversion pour Python via .NET."
type: docs
url: /fr/python-net/guides/convert-files-within-document-containers/
is_root: false
weight: 70
---


Ce sujet explique comment convertir les fichiers intégrés dans des conteneurs de documents, tels que les fichiers compressés ou empaquetés, en fichiers de sortie individuels. Le diagramme suivant illustre le processus d’extraction et de conversion des fichiers au sein d’un conteneur de documents :

flowchart LR
%% Nodes
A["Conteneur de document"]
B["Extraction"]
C["Conversion"]
D["Fichier converti 1"]
E["Fichier converti 2"]
F["Fichier converti N"]

%% Edge connections between nodes
A --> B --> C --> D
C --> E
C --> F

Les processus d'extraction et de conversion sont exécutés en un seul appel à la méthode `convert(file_path, convert_options)` de la classe [`Converter`](/conversion/python-net/groupdocs.conversion/converter/). GroupDocs.Conversion ouvre le conteneur, convertit les fichiers qu'il contient et écrit un document de sortie consolidé.

## Document Container File Types

Les types de fichiers suivants sont considérés comme des conteneurs de documents :

### Email and Outlook

- **EML** - Email Message File.
- **EMLX** - Apple Mail Email File.
- **MSG** - Microsoft Outlook Message File.
- **OST** - Outlook Offline Data File.
- **PST** - Outlook Personal Information Store File.

### PDF

- **PDF** - PDF files that contain embedded resources.

### Word Processing

- **DOC** - The older Microsoft Word binary format.
- **DOCX** - The modern Word format.
- **DOT and DOTX** - Word template files.
- **RTF** - Rich Text Format.

### Compression

- **7Z** - 7-Zip Compressed File.
- **BZ2** - Bzip2 Compressed File.
- **CAB** - Windows Cabinet File.
- **CPIO** - CPIO Compressed File.
- **GZ** - Gnu Zipped Archive.
- **GZIP** - Gzip Compressed File.
- **LZ** - Lzip Compressed File.
- **LZMA** - LZMA Compressed File.
- **RAR** - RAR Compressed Archive.
- **TAR** - Consolidated Unix File Archive.
- **XZ** - Xz Compressed File.
- **Z** - Unix Compressed File.
- **ZIP** - ZIP Compressed File.

## Example: Convert Files Within Document Container

L'exemple suivant montre comment convertir le contenu d'une archive ZIP en un seul PDF consolidé :

{{< tabs \"example-1\">}}
{{< tab "convert_files_within_document_container.py" >}}
```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

def convert_files_within_document_container():
    # Instanciez le Converter avec le conteneur de document d'entrée
    with Converter("./compressed.zip") as converter:
        # Instanciez les options de conversion
        pdf_convert_options = PdfConvertOptions()

        # Extrayez l'archive, convertissez les fichiers qu'elle contient et enregistrez un PDF consolidé
        converter.convert("./converted.pdf", pdf_convert_options)

if __name__ == "__main__":
    convert_files_within_document_container()
```
{{< /tab >}}
{{< tab "compressed.zip" >}}

`compressed.zip` est le fichier d'exemple utilisé dans cet exemple. Cliquez [ici](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/convert-files-within-document-containers/compressed.zip) pour le télécharger.

{{< /tab >}}
{{< tab "converted.pdf" >}}
```text
Binary file (PDF, 283 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/converting-documents/convert-files-within-document-containers/convert_files_within_document_container/converted.pdf)
{{< /tab >}}
{{< /tabs >}}
