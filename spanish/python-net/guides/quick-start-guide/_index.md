---
title: "Guía de inicio rápido"
linkTitle: "Quick Start Guide"
second_title: "Referencias de API de GroupDocs.Conversion para Python a través de .NET"
description: "Configure un entorno virtual, instale groupdocs-conversion-net y ejecute tres ejemplos mínimos — DOCX → PDF, PDF → PNG por página y ZIP → PDF consolidado — en menos de cinco minutos."
type: docs
url: /es/python-net/guides/quick-start-guide/
is_root: false
weight: 20
---


Esta guía ofrece una visión rápida de cómo configurar y comenzar a usar GroupDocs.Conversion para Python a través de .NET. Esta biblioteca permite a los desarrolladores convertir entre varios formatos de archivo (p. ej., DOCX, PDF, PNG) con una configuración mínima.

## Prerequisites

Para continuar, asegúrese de que tiene:

1. Entorno **Configured** según lo descrito en el tema [System Requirements]().
2. **Optionally** puede [Obtener una licencia temporal](https://purchase.groupdocs.com/temporary-license/) para probar todas las funciones del producto.

## Set Up Your Development Environment

Para seguir las mejores prácticas, use un entorno virtual para gestionar dependencias en aplicaciones Python. Obtenga más información sobre entornos virtuales en el tema de documentación [Create and Use Virtual Environments](https://packaging.python.org/en/latest/guides/installing-using-pip-and-virtual-environments/#create-and-use-virtual-environments).

### Create and Activate a Virtual Environment

Cree un entorno virtual:

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

Active un entorno virtual:

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

Después de activar el entorno virtual, ejecute el siguiente comando en su terminal para instalar la última versión del paquete:

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

Asegúrese de que el paquete se haya instalado correctamente. Debería ver el mensaje

```bash
Successfully installed groupdocs-conversion-net-*
```

## Example 1: Convert document

Para probar rápidamente la biblioteca, convierta un archivo DOCX a PDF. También puede descargar la aplicación que vamos a crear [aquí](https://docs.groupdocs.com/conversion/python-net/_sample_files/getting-started/quick-start-guide/convert_docx_to_pdf.zip).

{{< tabs "demo_app_convert_docx_to_pdf">}}
{{< tab "convert_docx_to_pdf.py" >}}
```python
import os
from groupdocs.conversion import License, Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

def convert_docx_to_pdf():
    # Obtener la ruta absoluta del archivo de licencia
    license_path = os.path.abspath("./GroupDocs.Conversion.lic")

    if os.path.exists(license_path):
        # Crear la licencia y establecer la ruta
        license = License()
        license.set_license(license_path)

    # Cargar el archivo DOCX
    with Converter("./business-plan.docx") as converter:
        # Crear opciones de conversión
        pdf_convert_options = PdfConvertOptions()

        # Convertir DOCX a PDF
        converter.convert("./business-plan.pdf", pdf_convert_options)    

if __name__ == "__main__":
    convert_docx_to_pdf()
```
{{< /tab >}}
{{< tab "business-plan.docx" >}}

`business-plan.docx` es un archivo de muestra utilizado en este ejemplo. Haz clic [aquí](https://docs.groupdocs.com/conversion/python-net/_sample_files/getting-started/quick-start-guide/business-plan.docx) para descargarlo.

{{< /tab >}}
{{< tab "business-plan.pdf" >}}
```text
Binary file (PDF, 283 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/getting-started/quick-start-guide/convert_docx_to_pdf/business-plan.pdf)
{{< /tab >}}
{{< /tabs >}}

Tu árbol de carpetas debería verse similar a la siguiente estructura de directorios:

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

Después de ejecutar la aplicación, puedes desactivar el entorno virtual ejecutando `deactivate` o cerrando tu terminal.

### Explanation
- `Converter("./business-plan.docx")`: Initializes the converter with the DOCX file.
- `PdfConvertOptions()`: Specifies the output format as PDF.
- `converter.convert("./business-plan.pdf", pdf_convert_options)`: Converts the DOCX file to PDF and saves it as `business-plan.pdf`.

## Example 2: Convert document pages

En este ejemplo convertiremos las páginas del documento PDF a PNG. Puedes descargar la aplicación que vamos a crear [aquí](https://docs.groupdocs.com/conversion/python-net/_sample_files/getting-started/quick-start-guide/convert_pdf_pages_to_png.zip).

{{< tabs "demo_app_convert_pdf_pages_to_png">}}
{{< tab "convert_pdf_pages_to_png.py" >}}
```python
import os
from groupdocs.conversion import License, Converter
from groupdocs.conversion.filetypes import ImageFileType
from groupdocs.conversion.options.convert import ImageConvertOptions

def convert_pdf_pages_to_png():
    # Obtener la ruta absoluta del archivo de licencia
    license_path = os.path.abspath("./GroupDocs.Conversion.lic")

    if os.path.exists(license_path):
        # Crear la licencia y establecer la ruta
        license = License()
        license.set_license(license_path)

    output_folder = "./converted-pages"
    os.makedirs(output_folder, exist_ok=True)

    # Cargar documento PDF
    with Converter("./annual-review.pdf") as converter:
        # Determinar el número total de páginas en el documento fuente
        pages_count = converter.get_document_info().pages_count

        # Crear opciones de conversión y reutilizarlas dentro del bucle
        png_convert_options = ImageConvertOptions()
        png_convert_options.format = ImageFileType.PNG
        png_convert_options.pages_count = 1

        # Convertir cada página a un archivo PNG separado
        for page_number in range(1, pages_count + 1):
            png_convert_options.page_number = page_number
            output_file = os.path.join(output_folder, f"converted-page-{page_number}.png")
            converter.convert(output_file, png_convert_options)

if __name__ == "__main__":
    convert_pdf_pages_to_png()
```
{{< /tab >}}
{{< tab "annual-review.pdf" >}}

`annual-review.pdf` es un archivo de muestra utilizado en este ejemplo. Haz clic [aquí](https://docs.groupdocs.com/conversion/python-net/_sample_files/getting-started/quick-start-guide/annual-review.pdf) para descargarlo.

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

Tu árbol de carpetas debería verse similar a la siguiente estructura de directorios:

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

Después de ejecutar la aplicación, puedes desactivar el entorno virtual ejecutando `deactivate` o cerrando tu terminal.

### Explanation
- `Converter("./annual-review.pdf")`: Initializes the converter with the PDF file.
- `converter.get_document_info().pages_count`: Retrieves the total number of pages in the source document.
- `ImageConvertOptions()` with `format = ImageFileType.PNG`: Specifies the output format as PNG image.
- The loop updates `png_convert_options.page_number` on each iteration (with `pages_count = 1`) and calls `converter.convert(...)` to write one PNG file per page into the `converted-pages` folder.

## Example 3: Convert files in archive

En este ejemplo convertiremos el contenido de un archivo ZIP a PDF. GroupDocs.Conversion abre el archivo, convierte los archivos internos y produce un único PDF consolidado que contiene todos los documentos convertidos. Puedes descargar la aplicación que vamos a crear [aquí](https://docs.groupdocs.com/conversion/python-net/_sample_files/getting-started/quick-start-guide/convert_files_in_archive.zip).

{{< tabs "demo_app_convert_files_in_archive">}}
{{< tab "convert_files_in_archive.py" >}}
```python
import os
from groupdocs.conversion import License, Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

def convert_files_in_archive():
    # Obtener la ruta absoluta del archivo de licencia
    license_path = os.path.abspath("./GroupDocs.Conversion.lic")

    if os.path.exists(license_path):
        # Crear la licencia y establecer la ruta
        license = License()
        license.set_license(license_path)

    # Cargar archivo ZIP
    with Converter("./compressed.zip") as converter:
        # Crear opciones de conversión
        pdf_convert_options = PdfConvertOptions()

        # Extrae el archivo, convierte su contenido y guarda un PDF consolidado
        converter.convert("./converted.pdf", pdf_convert_options)

if __name__ == "__main__":
    convert_files_in_archive()
```
{{< /tab >}}
{{< tab "compressed.zip" >}}

`compressed.zip` es un archivo de ejemplo utilizado en este caso. Haz clic [aquí](https://docs.groupdocs.com/conversion/python-net/_sample_files/getting-started/quick-start-guide/compressed.zip) para descargarlo.

{{< /tab >}}
{{< tab "converted.pdf" >}}
```text
Binary file (PDF, 283 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/getting-started/quick-start-guide/convert_files_in_archive/converted.pdf)
{{< /tab >}}
{{< /tabs >}}

Tu árbol de carpetas debería verse similar a la siguiente estructura de directorios:

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

Después de ejecutar la aplicación, puedes desactivar el entorno virtual ejecutando `deactivate` o cerrando tu terminal.

### Explanation
- `Converter("./compressed.zip")`: Initializes the converter with the ZIP file.
- `PdfConvertOptions()`: Specifies the output format as PDF.
- `converter.convert("./converted.pdf", pdf_convert_options)`: Extracts the archive, converts its contents, and writes a single consolidated PDF to `converted.pdf`.

## Next Steps

Después de completar lo básico, explora recursos adicionales para mejorar tu uso:
- [Supported File Formats](): Review the full list of supported file types.
- [Licensing](): Check details on licensing and evaluation.
- [Technical Support](): Contact support for assistance if you encounter issues.
