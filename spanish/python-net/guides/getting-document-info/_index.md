---
title: "Obtener información del documento"
linkTitle: "Getting Document Information"
second_title: "Referencias de API de GroupDocs.Conversion para Python a través de .NET"
description: "Lee el formato, número de páginas, autor, dimensiones, tabla de contenido y metadatos específicos del formato de documentos PDF, Word, Excel, PowerPoint, CAD, imagen, gestión de proyectos y correo electrónico sin convertir, usando Converter.get_document_info() en GroupDocs.Conversion para Python a través de .NET."
type: docs
url: /es/python-net/guides/getting-document-info/
is_root: false
weight: 110
---


GroupDocs.Conversion para Python a través de .NET proporciona un método estándar para obtener información sobre un documento. Puedes obtener información básica del documento o detallada como se muestra a continuación para varios formatos.

## Example 1: Get Basic Document Info

Para obtener información del documento, usa el método `Converter.get_document_info()`. Devuelve un objeto [`DocumentInfo`](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/) que contiene detalles comunes a todos los tipos de documento compatibles, como formato, fecha de creación, tamaño y número de páginas.

{{< tabs \"code-example-1\">}}
{{< tab \"get_document_info.py\" >}}
```python
from groupdocs.conversion import Converter

def get_document_info():
    # Carga el documento y recupera la información
    with Converter("./lorem-ipsum.txt") as converter:
        info = converter.get_document_info()
    
        # Imprime la información básica del documento
        print("Format:", info.format)
        print("Pages count:", info.pages_count)
        print("Creation date:", info.creation_date)
        print("Size, bytes:", info.size)

if __name__ == "__main__":
    get_document_info()
```
{{< /tab >}}

{{< tab \"lorem-ipsum.txt\" >}}

`lorem-ipsum.txt` es un archivo de ejemplo utilizado en este caso. Haz clic [aquí](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/get-document-info/lorem-ipsum.txt) para descargarlo.

{{< /tab >}}
{{< tab \"get-document-info.txt\" >}}
```text
Format: txt
Pages count: 3
Creation date: 0001-01-01T00:00:00.0000000
Size, bytes: 7794
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/getting-document-info/get_document_info/get-document-info.txt)
{{< /tab >}}
{{< /tabs >}}

## Example 2: Get PDF Document Info

{{< tabs \"code-example-2\">}}
{{< tab \"get_pdf_document_info.py\" >}}
```python
from groupdocs.conversion import Converter

def get_pdf_document_info():
    # Carga el documento y recupera la información
    with Converter("sample-with-toc.pdf") as converter:
        doc_info = converter.get_document_info()

        # Imprime la información del documento PDF
        print("Author:", doc_info.author)
        print("Creation Date:", doc_info.creation_date)
        print("Title:", doc_info.title)
        print("Version:", doc_info.version)
        print("Pages Count:", doc_info.pages_count)
        print("Width:", doc_info.width)
        print("Height:", doc_info.height)
        print("Is Landscaped:", doc_info.is_landscape)
        print("Is Password-Protected:", doc_info.is_password_protected)
        print("Table of contents:")
        for toc_item in doc_info.table_of_contents:
            print(f" Page {toc_item.page}: Title: {toc_item.title}")

if __name__ == "__main__":
    get_pdf_document_info()
```
{{< /tab >}}
{{< tab \"sample-with-toc.pdf\" >}}

`sample-with-toc.pdf` es un archivo de ejemplo utilizado en este caso. Haz clic [aquí](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/get-document-info/sample-with-toc.pdf) para descargarlo.

{{< /tab >}}
{{< tab \"get-pdf-document-info.txt\" >}}
```text
Author: None
Creation Date: 2020-08-12T16:41:29.0000000
Title: None
Version: 1.7
Pages Count: 5
Width: 612
Height: 792
Is Landscaped: False
Is Password-Protected: False
Table of contents:
[TRUNCATED]
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/getting-document-info/get_pdf_document_info/get-pdf-document-info.txt)
{{< /tab >}}
{{< /tabs >}}

## Example 3: Get Word Processing Document Info

Puedes encontrar qué tipos de archivo pertenecen a esta familia de formatos en la sección de documentación [Word Processing]().

{{< tabs \"code-example-3\">}}
{{< tab \"get_wp_document_info.py\" >}}
```python
from groupdocs.conversion import Converter

def get_wp_document_info():
    # Carga el documento y recupera la información
    with Converter("./business-plan.doc") as converter:
        doc_info = converter.get_document_info()

        # Imprime la información del documento DOC
        print("Author:", doc_info.author)
        print("Creation Date:", doc_info.creation_date)
        print("Format:", doc_info.format)
        print("Is Password Protected:", doc_info.is_password_protected)
        print("Lines:", doc_info.lines)
        print("Pages Count:", doc_info.pages_count)
        print("Size, bytes:", doc_info.size)
        print("Title:", doc_info.title)
        print("Words:", doc_info.words)
        print("Table of contents:")
        for toc_item in doc_info.table_of_contents:
            print(f" Page {toc_item.page}: Title: {toc_item.title}")

if __name__ == "__main__":
    get_wp_document_info()
```
{{< /tab >}}
{{< tab "business-plan.doc" >}}

`business-plan.doc` es un archivo de muestra utilizado en este ejemplo. Haga clic [aquí](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/get-document-info/business-plan.doc) para descargarlo.

{{< /tab >}}
{{< tab "get-wp-document-info.txt" >}}
```text
Author: GroupDocs
Creation Date: 2024-11-03T10:05:00.0000000Z
Format: doc
Is Password Protected: False
Lines: 180
Pages Count: 19
Size, bytes: 414208
Title: 
Words: 3789
Table of contents:
[TRUNCATED]
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/getting-document-info/get_wp_document_info/get-wp-document-info.txt)
{{< /tab >}}
{{< /tabs >}}

## Example 4: Get Project Management Document Info

Puede encontrar qué tipos de archivo pertenecen a esta familia de formatos en la sección de documentación de [Project Management]().

{{< tabs "code-example-4">}}
{{< tab "get_pm_document_info.py" >}}
```python
from groupdocs.conversion import Converter

def get_pm_document_info():
    # Carga el documento y recupera la información
    with Converter("./weekly-plan.mpp") as converter:
        doc_info = converter.get_document_info()

        # Imprimir información del documento MPP
        print("Creation Date:", doc_info.creation_date)
        print("Start Date:", doc_info.start_date)
        print("End Date:", doc_info.end_date)
        print("Format:", doc_info.format)
        print("Size, bytes:", doc_info.size)
        print("Tasks Count:", doc_info.tasks_count)

if __name__ == "__main__":
    get_pm_document_info()
```
{{< /tab >}}
{{< tab "weekly-plan.mpp" >}}

`weekly-plan.mpp` es un archivo de muestra utilizado en este ejemplo. Haga clic [aquí](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/get-document-info/weekly-plan.mpp) para descargarlo.

{{< /tab >}}
{{< tab "get-pm-document-info.txt" >}}
```text
Creation Date: 2026-04-15T20:19:14.5231130Z
Start Date: 2017-10-06T09:00:00.0000000Z
End Date: 2017-10-14T18:00:00.0000000Z
Format: mpp
Size, bytes: 236544
Tasks Count: 5
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/getting-document-info/get_pm_document_info/get-pm-document-info.txt)
{{< /tab >}}
{{< /tabs >}}

## Example 5: Get Image Info

Puede encontrar qué tipos de archivo pertenecen a esta familia de formatos en la sección de documentación de [Image]().

{{< tabs "code-example-5">}}
{{< tab "get_image_info.py" >}}
```python
from groupdocs.conversion import Converter

def get_image_info():
    # Carga el documento y recupera la información
    with Converter("./infographic-elements.tiff") as converter:
        doc_info = converter.get_document_info()

        # Imprimir información del documento TIFF
        print("Bits per Pixel:", doc_info.bits_per_pixel)
        print("Creation Date:", doc_info.creation_date)
        print("Format:", doc_info.format)
        print("Height:", doc_info.height)
        print("Width:", doc_info.width)
        print("Size, bytes:", doc_info.size)

if __name__ == "__main__":
    get_image_info()
```
{{< /tab >}}
{{< tab "infographic-elements.tiff" >}}

`infographic-elements.tiff` es un archivo de muestra utilizado en este ejemplo. Haga clic [aquí](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/get-document-info/infographic-elements.tiff) para descargarlo.

{{< /tab >}}
{{< tab "get-image-info.txt" >}}
```text
Bits per Pixel: 32
Creation Date: 2026-04-15T20:19:15.4324761Z
Format: tiff
Height: 2000
Width: 1500
Size, bytes: 1734560
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/getting-document-info/get_image_info/get-image-info.txt)
{{< /tab >}}
{{< /tabs >}}

## Example 6: Get Presentation Document Info

Puede encontrar qué tipos de archivo pertenecen a esta familia de formatos en la sección de documentación de [Presentation]().

{{< tabs "code-example-6">}}
{{< tab "get_pres_document_info.py" >}}
```python
from groupdocs.conversion import Converter

def get_pres_document_info():
    # Carga el documento y recupera la información
    with Converter("./presentation-template.pptx") as converter:
        doc_info = converter.get_document_info()

        # Imprimir información del documento PPTX
        print("Author:", doc_info.author)
        print("Creation Date:", doc_info.creation_date)
        print("Format:", doc_info.format)
        print("Is Password Protected:", doc_info.is_password_protected)
        print("Pages Count:", doc_info.pages_count)
        print("Size, bytes:", doc_info.size)
        print("Title:", doc_info.title)

if __name__ == "__main__":
    get_pres_document_info()
```
{{< /tab >}}
{{< tab "presentation-template.pptx" >}}

`presentation-template.pptx` es un archivo de muestra utilizado en este ejemplo. Haga clic [aquí](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/get-document-info/presentation-template.pptx) para descargarlo.

{{< /tab >}}
{{< tab "get-pres-document-info.txt" >}}
```text
Author: GroupDocs
Creation Date: 2023-03-04T14:58:10.0000000Z
Format: pptx
Is Password Protected: False
Pages Count: 3
Size, bytes: 35210
Title: TEST
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/getting-document-info/get_pres_document_info/get-pres-document-info.txt)
{{< /tab >}}
{{< /tabs >}}

## Example 7: Get Spreadsheet Document Info

Puede encontrar qué tipos de archivo pertenecen a esta familia de formatos en la sección de documentación de [Spreadsheets]().

{{< tabs "code-example-7">}}
{{< tab "get_sp_document_info.py" >}}
```python
from groupdocs.conversion import Converter

def get_sp_document_info():
    # Carga el documento y recupera la información
    with Converter("./cost-analysis.xlsx") as converter:
        doc_info = converter.get_document_info()

        # Imprimir información del documento XLSX
        print("Author:", doc_info.author)
        print("Creation Date:", doc_info.creation_date)
        print("Format:", doc_info.format)
        print("Is Password Protected:", doc_info.is_password_protected)
        print("Pages Count:", doc_info.pages_count)
        print("Size, bytes:", doc_info.size)
        print("Title:", doc_info.title)
        print("Worksheets Count:", doc_info.worksheets_count)

if __name__ == "__main__":
    get_sp_document_info()
```
{{< /tab >}}
{{< tab "cost-analysis.xlsx" >}}

`cost-analysis.xlsx` es un archivo de muestra utilizado en este ejemplo. Haga clic [aquí](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/get-document-info/cost-analysis.xlsx) para descargarlo.

{{< /tab >}}
{{< tab "get-sp-document-info.txt" >}}
```text
Author: GroupDocs
Creation Date: 2023-02-23T18:52:46.0000000+02:00
Format: xlsx
Is Password Protected: False
Pages Count: 0
Size, bytes: 78940
Title: Cost Analysis
Worksheets Count: 1
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/getting-document-info/get_sp_document_info/get-sp-document-info.txt)
{{< /tab >}}
{{< /tabs >}}

## Example 8: Get CAD Drawing Info

Puede encontrar qué tipos de archivo pertenecen a esta familia de formatos en la sección de documentación de [CAD]().

{{< tabs "code-example-8">}}
{{< tab "get_cad_document_info.py" >}}
```python
from groupdocs.conversion import Converter

def get_cad_document_info():
    # Carga el documento y recupera la información
    with Converter("./blocks-and-tables.dwg") as converter:
        doc_info = converter.get_document_info()

        # Imprimir información del documento DWG
        print("Creation Date:", doc_info.creation_date)
        print("Format:", doc_info.format)
        print("Height:", doc_info.height)
        print("Width:", doc_info.width)
        print("Size, bytes:", doc_info.size)
        
        print("Layouts:")
        for layout in doc_info.layouts:
            print(" Layout:", layout)
        
        print("Layers:")
        for layer in doc_info.layers:
            print(" Layer:", layer)

if __name__ == "__main__":
    get_cad_document_info()
```
{{< /tab >}}
{{< tab "blocks-and-tables.dwg" >}}

`blocks-and-tables.dwg` es un archivo de muestra utilizado en este ejemplo. Haga clic [aquí](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/get-document-info/blocks-and-tables.dwg) para descargarlo.

{{< /tab >}}
{{< tab "get-cad-document-info.txt" >}}
```text
Creation Date: 2026-04-15T20:19:18.9521534Z
Format: dwg
Height: 16
Width: 26
Size, bytes: 258848
Layouts:
 Layout: Model
 Layout: ISO A1
Layers:
 Layer: Text
[TRUNCATED]
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/getting-document-info/get_cad_document_info/get-cad-document-info.txt)
{{< /tab >}}
{{< /tabs >}}

## Example 9: Get Email Message Info

Puede encontrar qué tipos de archivo pertenecen a esta familia de formatos en la sección de documentación de [Email]().

{{< tabs "code-example-9">}}
{{< tab "get_email_document_info.py" >}}
```python
from groupdocs.conversion import Converter

def get_email_document_info():
    # Carga el documento y recupera la información
    with Converter("./invitation.eml") as converter:
        doc_info = converter.get_document_info()

        # Imprimir información del documento EML
        print("Creation Date:", doc_info.creation_date)
        print("Format:", doc_info.format)
        print("Is Encrypted:", doc_info.is_encrypted)
        print("Is Body in HTML:", doc_info.is_html)
        print("Is Signed:", doc_info.is_signed)
        print("Size:", doc_info.size)
        print("Attachments Count:", doc_info.attachments_count)

        for attachment_name in doc_info.attachments_names:
            print("Attachment Name:", attachment_name)

if __name__ == "__main__":
    get_email_document_info()
```
{{< /tab >}}
{{< tab "invitation.eml" >}}

`invitation.eml` es un archivo de muestra utilizado en este ejemplo. Haga clic [aquí](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/get-document-info/invitation.eml) para descargarlo.

{{< /tab >}}
{{< tab "get-email-document-info.txt" >}}
```text
Creation Date: 2017-04-25T11:28:29.0000000Z
Format: eml
Is Encrypted: False
Is Body in HTML: True
Is Signed: False
Size: 91948
Attachments Count: 1
Attachment Name: bg_pattern.gif
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/getting-document-info/get_email_document_info/get-email-document-info.txt)
{{< /tab >}}
{{< /tabs >}}

El objeto DocumentInfo proporciona un conjunto extenso de metadatos, que varía según el formato del documento. Puede consultar la [referencia de API](https://reference.groupdocs.com/conversion/python-net/) para obtener detalles adicionales de metadatos de documentos específicos de cada formato.
