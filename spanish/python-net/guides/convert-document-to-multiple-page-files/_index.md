---
title: "Convertir documento a archivos de varias páginas"
linkTitle: "Convert Document To Multiple"
second_title: "Referencias de API de GroupDocs.Conversion para Python a través de .NET"
description: "id: convert-document-to-multiple-page-files"
type: docs
url: /es/python-net/guides/convert-document-to-multiple-page-files/
is_root: false
weight: 60
---


---
id: convert-document-to-multiple-page-files
url: conversion/python-net/developer-guide/converting-documents/convert-document-to-multiple-page-files
title: Convertir un documento a archivos de varias páginas
linkTitle: Convertir a varios archivos
weight: 3
description: "Renderiza cada página de un documento multipágina en su propio archivo de salida — recorre page_number con pages_count=1 y Converter.convert() para producir un PNG, PDF o imagen por página con GroupDocs.Conversion for Python via .NET."
keywords: convertir a varios archivos, salida por página, page_number, pages_count, bucle de página, convertir páginas de presentación, convertir páginas PDF a PNG, ImageConvertOptions, GroupDocs.Conversion, python
productName: GroupDocs.Conversion for Python via .NET
hideChildren: false
toc: true
---

Este tema de documentación cubre la conversión de un único documento multipágina en archivos de página individuales. El siguiente diagrama ilustra el proceso de convertir un archivo multipágina en páginas separadas:

flowchart LR
%% Nodes
A["Documento de entrada"]
B["Conversion"]
C["Página convertida 1"]
D["Página convertida 2"]
E["Página convertida N"]

%% Conexiones de aristas entre nodos
A --> B --> C
B --> D
B --> E

Para convertir un documento en archivos por página, use el método `Converter.convert(file_path, convert_options)` junto con los atributos `page_number` y `pages_count` en las clases [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/) compatibles:

- **`page_number`**: One-based index of the first page to convert.
- **`pages_count`**: Number of consecutive pages to convert starting from `page_number`.

Para producir un archivo de salida por página, recorra desde `1` hasta `converter.get_document_info().pages_count`, actualizando `page_number` en cada iteración y escribiendo en una ruta de salida diferente. Establecer `pages_count = 1` garantiza que cada llamada genere una sola página.

## Supported ConvertOptions Classes

Las siguientes clases [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/) exponen los atributos `page_number` y `pages_count` utilizados en este tema:

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

El siguiente ejemplo muestra cómo convertir cada diapositiva de una presentación PPTX a una imagen PNG y guardar las imágenes de salida en una carpeta especificada.
 
La plantilla de nombre de archivo para los archivos de salida es `converted-page-{page number}.{output file extension}`. En este ejemplo, la primera diapositiva se guardará como `converted-page-1.png`.

{{< tabs "example-1">}}
{{< tab "convert_all_document_pages.py" >}}
```python
import os
from groupdocs.conversion import Converter
from groupdocs.conversion.filetypes import ImageFileType
from groupdocs.conversion.options.convert import ImageConvertOptions

def convert_all_document_pages():
    output_folder = "./converted-pages"
    os.makedirs(output_folder, exist_ok=True)

    # Instanciar el Convertidor con el documento de entrada
    with Converter("./basic-presentation.pptx") as converter:
        # Determinar el número total de páginas en el documento fuente
        pages_count = converter.get_document_info().pages_count

        # Instancie las opciones de conversión una vez y reutilícelas dentro del bucle
        png_convert_options = ImageConvertOptions()
        png_convert_options.format = ImageFileType.PNG
        png_convert_options.pages_count = 1

        # Convertir cada página a un archivo PNG separado
        for page_number in range(1, pages_count + 1):
            png_convert_options.page_number = page_number
            output_file = os.path.join(output_folder, f"converted-page-{page_number}.png")
            converter.convert(output_file, png_convert_options)

if __name__ == "__main__":
    convert_all_document_pages()
```
{{< /tab >}}
{{< tab "basic-presentation.pptx" >}}

`basic-presentation.pptx` es el archivo de ejemplo utilizado en este caso. Haga clic [aquí](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/convert-document-to-multiple-page-files/basic-presentation.pptx) para descargarlo.

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

Descubra cómo obtener el número de páginas del documento en el tema de documentación [Getting Document Information]().

El siguiente ejemplo muestra cómo convertir una diapositiva específica de una presentación PPTX y guardarla como un archivo separado.

{{< tabs "example-2">}}
{{< tab "convert_specific_document_page_to_file.py" >}}
```python
from groupdocs.conversion import Converter
from groupdocs.conversion.filetypes import ImageFileType
from groupdocs.conversion.options.convert import ImageConvertOptions

def convert_specific_document_page_to_file():
    # Instanciar el Convertidor con el documento de entrada
    with Converter("./basic-presentation.pptx") as converter:
        # Instanciar opciones de conversión
        png_convert_options = ImageConvertOptions()
        # Defina el formato de salida como PNG
        png_convert_options.format = ImageFileType.PNG

        # Especifique la página única a convertir
        png_convert_options.page_number = 3
        png_convert_options.pages_count = 1

        # Guarde la página convertida en un archivo
        converter.convert("./slide-3.png", png_convert_options)

if __name__ == "__main__":
    convert_specific_document_page_to_file()
```
{{< /tab >}}
{{< tab "basic-presentation.pptx" >}}

`basic-presentation.pptx` es el archivo de ejemplo utilizado en este caso. Haga clic [aquí](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/convert-document-to-multiple-page-files/basic-presentation.pptx) para descargarlo.

{{< /tab >}}
{{< tab "slide-3.png" >}}
```text
Binary file (PNG, 797 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/converting-documents/convert-document-to-multiple-page-files/convert_specific_document_page_to_file/slide-3.png)
{{< /tab >}}
{{< /tabs >}}

## Example 3: Convert a Specific Page and Load Output Into a Stream

Descubra cómo obtener el número de páginas del documento en el tema de documentación [Getting Document Information]().

Si necesita la página convertida como un búfer en memoria (p. ej., para enviarla a otra API sin tocar el sistema de archivos después), convierta la página a un archivo primero y luego léala en un objeto `BytesIO`:

{{< tabs \"example-3\">}}
{{< tab "convert_specific_document_page_to_stream.py" >}}
```python
import io
from groupdocs.conversion import Converter
from groupdocs.conversion.filetypes import ImageFileType
from groupdocs.conversion.options.convert import ImageConvertOptions

def convert_specific_document_page_to_stream():
    page_number_to_convert = 5
    output_file = f"./slide-{page_number_to_convert}.png"

    # Instanciar el Convertidor con el documento de entrada
    with Converter("./basic-presentation.pptx") as converter:
        # Instanciar opciones de conversión
        png_convert_options = ImageConvertOptions()
        # Defina el formato de salida como PNG
        png_convert_options.format = ImageFileType.PNG

        # Especifique la página única a convertir
        png_convert_options.page_number = page_number_to_convert
        png_convert_options.pages_count = 1

        # Convierta y guarde la página en un archivo en disco
        converter.convert(output_file, png_convert_options)

    # Cargue la página convertida en un flujo en memoria para uso posterior
    with open(output_file, "rb") as file_handle:
        page_stream = io.BytesIO(file_handle.read())

    # page_stream ahora contiene los bytes PNG y puede ser pasado a cualquier consumidor
    print(f"Loaded {page_stream.getbuffer().nbytes} bytes into memory")

if __name__ == "__main__":
    convert_specific_document_page_to_stream()
```
{{< /tab >}}
{{< tab "basic-presentation.pptx" >}}

`basic-presentation.pptx` es el archivo de ejemplo utilizado en este caso. Haga clic [aquí](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/convert-document-to-multiple-page-files/basic-presentation.pptx) para descargarlo.

{{< /tab >}}
{{< tab "slide-5.png" >}}
```text
Binary file (PNG, 75 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/converting-documents/convert-document-to-multiple-page-files/convert_specific_document_page_to_stream/slide-5.png)
{{< /tab >}}
{{< /tabs >}}
