---
title: "Convertir archivos dentro de contenedores de documentos"
linkTitle: "Convert Archives and Containers"
second_title: "Referencias de API de GroupDocs.Conversion para Python a través de .NET"
description: "Abra formatos de contenedor ZIP, RAR, 7Z, OST, PST y otros, convierta su contenido y genere un documento de salida consolidado en una única llamada a Converter.convert() con GroupDocs.Conversion para Python a través de .NET."
type: docs
url: /es/python-net/guides/convert-files-within-document-containers/
is_root: false
weight: 70
---


Este tema cubre cómo convertir archivos incrustados dentro de contenedores de documentos, como archivos comprimidos o empaquetados, en archivos de salida individuales. El siguiente diagrama ilustra el proceso de extracción y conversión de archivos dentro de un contenedor de documentos:

flowchart LR
%% Nodes
A[\"Contenedor de Documentos\"]
B[\"Extracción\"]
C[\"Conversión\"]
D[\"Archivo Convertido 1\"]
E[\"Archivo Convertido 2\"]
F[\"Archivo Convertido N\"]

%% Conexiones de aristas entre nodos
A --> B --> C --> D
C --> E
C --> F

Los procesos de extracción y conversión se realizan dentro de una única llamada al método `convert(file_path, convert_options)` de la clase [`Converter`](/conversion/python-net/groupdocs.conversion/converter/). GroupDocs.Conversion abre el contenedor, convierte los archivos que contiene y escribe un documento de salida consolidado.

## Document Container File Types

Los siguientes tipos de archivo se consideran contenedores de documentos:

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

El siguiente ejemplo muestra cómo convertir el contenido de un archivo ZIP en un único PDF consolidado:

{{< tabs "example-1">}}
{{< tab "convert_files_within_document_container.py" >}}
```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

def convert_files_within_document_container():
    # Instanciar Converter con el contenedor de documento de entrada
    with Converter("./compressed.zip") as converter:
        # Instanciar opciones de conversión
        pdf_convert_options = PdfConvertOptions()

        # Extraer el archivo, convertir los archivos contenidos y guardar un PDF consolidado
        converter.convert("./converted.pdf", pdf_convert_options)

if __name__ == "__main__":
    convert_files_within_document_container()
```
{{< /tab >}}
{{< tab "compressed.zip" >}}

`compressed.zip` es el archivo de muestra utilizado en este ejemplo. Haga clic [aquí](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/convert-files-within-document-containers/compressed.zip) para descargarlo.

{{< /tab >}}
{{< tab "converted.pdf" >}}
```text
Binary file (PDF, 283 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/converting-documents/convert-files-within-document-containers/convert_files_within_document_container/converted.pdf)
{{< /tab >}}
{{< /tabs >}}
