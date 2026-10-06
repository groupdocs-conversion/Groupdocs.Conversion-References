---
title: "Documentinformatie ophalen"
linkTitle: "Getting Document Information"
second_title: "GroupDocs.Conversion for Python via .NET API-referenties"
description: "Lees formaat, aantal pagina's, auteur, afmetingen, inhoudsopgave en formatspecifieke metadata van PDF-, Word-, Excel-, PowerPoint-, CAD-, afbeelding-, projectbeheer- en e-maildocumenten zonder te converteren — met Converter.get_document_info() in GroupDocs.Conversion voor Python via .NET."
type: docs
url: /nl/python-net/guides/getting-document-info/
is_root: false
weight: 110
---


GroupDocs.Conversion voor Python via .NET biedt een standaardmethode om informatie over een document te verkrijgen. U kunt basisdocumentinformatie of gedetailleerde informatie ophalen zoals hieronder getoond voor verschillende formaten.

## Example 1: Get Basic Document Info

Om documentinformatie op te halen, gebruikt u de `Converter.get_document_info()`-methode. Deze retourneert een [`DocumentInfo`](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/) object met details die gemeenschappelijk zijn voor alle ondersteunde documenttypen, zoals formaat, aanmaakdatum, grootte en aantal pagina's.

{{< tabs "code-example-1">}}
{{< tab "get_document_info.py" >}}
```python
from groupdocs.conversion import Converter

def get_document_info():
    # Laad het document en haal informatie op
    with Converter("./lorem-ipsum.txt") as converter:
        info = converter.get_document_info()
    
        # Print basisdocumentinformatie
        print("Format:", info.format)
        print("Pages count:", info.pages_count)
        print("Creation date:", info.creation_date)
        print("Size, bytes:", info.size)

if __name__ == "__main__":
    get_document_info()
```
{{< /tab >}}

{{< tab "lorem-ipsum.txt" >}}

`lorem-ipsum.txt` is een voorbeeldbestand dat in dit voorbeeld wordt gebruikt. Klik [hier](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/get-document-info/lorem-ipsum.txt) om het te downloaden.

{{< /tab >}}
{{< tab "get-document-info.txt" >}}
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

{{< tabs "code-example-2">}}
{{< tab "get_pdf_document_info.py" >}}
```python
from groupdocs.conversion import Converter

def get_pdf_document_info():
    # Laad het document en haal informatie op
    with Converter("sample-with-toc.pdf") as converter:
        doc_info = converter.get_document_info()

        # Print PDF-documentinformatie
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
{{< tab "sample-with-toc.pdf" >}}

`sample-with-toc.pdf` is een voorbeeldbestand dat in dit voorbeeld wordt gebruikt. Klik [hier](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/get-document-info/sample-with-toc.pdf) om het te downloaden.

{{< /tab >}}
{{< tab "get-pdf-document-info.txt" >}}
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

U kunt vinden welke bestandstypen tot deze formaatfamilie behoren in de documentatiesectie [Word Processing]().

{{< tabs "code-example-3">}}
{{< tab "get_wp_document_info.py" >}}
```python
from groupdocs.conversion import Converter

def get_wp_document_info():
    # Laad het document en haal informatie op
    with Converter("./business-plan.doc") as converter:
        doc_info = converter.get_document_info()

        # Print DOC-documentinformatie
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
{{< tab \"business-plan.doc\" >}}

`business-plan.doc` is een voorbeeldbestand dat in dit voorbeeld wordt gebruikt. Klik [hier](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/get-document-info/business-plan.doc) om het te downloaden.

{{< /tab >}}
{{< tab \"get-wp-document-info.txt\" >}}
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

U kunt vinden welke bestandstypen tot deze formaatfamilie behoren in de [Project Management]() documentatiesectie.

{{< tabs \"code-example-4\">}}
{{< tab \"get_pm_document_info.py\" >}}
```python
from groupdocs.conversion import Converter

def get_pm_document_info():
    # Laad het document en haal informatie op
    with Converter("./weekly-plan.mpp") as converter:
        doc_info = converter.get_document_info()

        # Print MPP documentinformatie
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
{{< tab \"weekly-plan.mpp\" >}}

`weekly-plan.mpp` is een voorbeeldbestand dat in dit voorbeeld wordt gebruikt. Klik [hier](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/get-document-info/weekly-plan.mpp) om het te downloaden.

{{< /tab >}}
{{< tab \"get-pm-document-info.txt\" >}}
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

U kunt vinden welke bestandstypen tot deze formaatfamilie behoren in de [Image]() documentatiesectie.

{{< tabs \"code-example-5\">}}
{{< tab \"get_image_info.py\" >}}
```python
from groupdocs.conversion import Converter

def get_image_info():
    # Laad het document en haal informatie op
    with Converter("./infographic-elements.tiff") as converter:
        doc_info = converter.get_document_info()

        # Print TIFF documentinformatie
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
{{< tab \"infographic-elements.tiff\" >}}

`infographic-elements.tiff` is een voorbeeldbestand dat in dit voorbeeld wordt gebruikt. Klik [hier](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/get-document-info/infographic-elements.tiff) om het te downloaden.

{{< /tab >}}
{{< tab \"get-image-info.txt\" >}}
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

U kunt vinden welke bestandstypen tot deze formaatfamilie behoren in de [Presentation]() documentatiesectie.

{{< tabs \"code-example-6\">}}
{{< tab \"get_pres_document_info.py\" >}}
```python
from groupdocs.conversion import Converter

def get_pres_document_info():
    # Laad het document en haal informatie op
    with Converter("./presentation-template.pptx") as converter:
        doc_info = converter.get_document_info()

        # Print PPTX documentinformatie
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
{{< tab \"presentation-template.pptx\" >}}

`presentation-template.pptx` is een voorbeeldbestand dat in dit voorbeeld wordt gebruikt. Klik [hier](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/get-document-info/presentation-template.pptx) om het te downloaden.

{{< /tab >}}
{{< tab \"get-pres-document-info.txt\" >}}
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

U kunt vinden welke bestandstypen tot deze formaatfamilie behoren in de [Spreadsheets]() documentatiesectie.

{{< tabs "code-example-7">}}
{{< tab "get_sp_document_info.py" >}}
```python
from groupdocs.conversion import Converter

def get_sp_document_info():
    # Laad het document en haal informatie op
    with Converter("./cost-analysis.xlsx") as converter:
        doc_info = converter.get_document_info()

        # Print XLSX documentinformatie
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

`cost-analysis.xlsx` is een voorbeeldbestand dat in dit voorbeeld wordt gebruikt. Klik [hier](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/get-document-info/cost-analysis.xlsx) om het te downloaden.

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

U kunt vinden welke bestandstypen tot deze formaatfamilie behoren in de [CAD]() documentatiesectie.

{{< tabs "code-example-8">}}
{{< tab "get_cad_document_info.py" >}}
```python
from groupdocs.conversion import Converter

def get_cad_document_info():
    # Laad het document en haal informatie op
    with Converter("./blocks-and-tables.dwg") as converter:
        doc_info = converter.get_document_info()

        # Print DWG documentinformatie
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

`blocks-and-tables.dwg` is een voorbeeldbestand dat in dit voorbeeld wordt gebruikt. Klik [hier](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/get-document-info/blocks-and-tables.dwg) om het te downloaden.

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

U kunt vinden welke bestandstypen tot deze formaatfamilie behoren in de [Email]() documentatiesectie.

{{< tabs "code-example-9">}}
{{< tab "get_email_document_info.py" >}}
```python
from groupdocs.conversion import Converter

def get_email_document_info():
    # Laad het document en haal informatie op
    with Converter("./invitation.eml") as converter:
        doc_info = converter.get_document_info()

        # Print EML documentinformatie
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

`invitation.eml` is een voorbeeldbestand dat in dit voorbeeld wordt gebruikt. Klik [hier](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/get-document-info/invitation.eml) om het te downloaden.

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

Het DocumentInfo-object biedt een uitgebreide set metadata, die varieert afhankelijk van het documentformaat. U kunt de [API-referentie](https://reference.groupdocs.com/conversion/python-net/) raadplegen voor aanvullende formaat‑specifieke documentmetadata‑details.
