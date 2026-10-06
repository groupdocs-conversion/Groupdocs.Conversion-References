---
title: "Bestand laden van lokale schijf"
linkTitle: "Load From Local Disk"
second_title: "GroupDocs.Conversion for Python via .NET API-referenties"
description: "Instantieer de Converter-klasse met een absoluut of relatief bestandspad om een document dat op het lokale bestandssysteem is opgeslagen te converteren met GroupDocs.Conversion voor Python via .NET."
type: docs
url: /nl/python-net/guides/load-file-from-local-disk/
is_root: false
weight: 90
---


Om een bronbestand van uw lokale schijf te laden, kunt u de [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) klasseconstructor in GroupDocs.Conversion gebruiken. De API biedt verschillende overloads, waardoor flexibiliteit mogelijk is voor diverse instellingen en opties:

* `Converter(file_path)`
* `Converter(file_path, load_options)`
* `Converter(file_path, converter_settings)`
* `Converter(file_path, load_options, converter_settings)`

Elke constructor vereist de `filePath`-parameter, die het pad naar het bronbestand definieert. U kunt dit opgeven als een absoluut of relatief pad. Let op dat als het opgegeven bestandspad niet bestaat, er een uitzondering wordt opgegooid.

GroupDocs.Conversion zal alleen toegang krijgen tot het bestand wanneer een actie (bijv. conversie) wordt uitgevoerd met behulp van de [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) klasse‑instantie.

Het volgende Python‑voorbeeld toont het laden van een bestand van een lokale schijf en het converteren ervan naar PDF:

{{< tabs \"code-example\">}}
{{< tab \"convert_docx_to_pdf.py\" >}}
```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

def convert_docx_to_pdf():
    # Specificeer de locatie van het bronbestand
    converter = Converter("./business-plan.docx")
    
    # Specificeer de locatie van het uitvoerbestand en conversie‑opties
    output_path = "./business-plan.pdf"
    pdf_options = PdfConvertOptions()
    
    # Converteer en sla op naar het uitvoerpad
    converter.convert(output_path, pdf_options)

if __name__ == "__main__":
    convert_docx_to_pdf()
```
{{< /tab >}}
{{< tab \"business-plan.docx\" >}}

`business-plan.docx` is een voorbeeldbestand dat in dit voorbeeld wordt gebruikt. Klik [hier](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/loading-documents/load-file-from-local-disk/business-plan.docx) om het te downloaden.

{{< /tab >}}
{{< tab "business-plan.pdf" >}}
```text
Binary file (PDF, 283 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/loading-documents/load-file-from-local-disk/convert_docx_to_pdf/business-plan.pdf)
{{< /tab >}}
{{< /tabs >}}

GroupDocs.Conversion bepaalt het bestandstype aan de hand van de extensie. Als de bestandsextensie niet is ingesteld, zal GroupDocs.Conversion proberen het bestandstype automatisch te detecteren. Afhankelijk van het bestandstype en de grootte verbruikt automatische detectie van het bestandstype extra bronnen, zoals geheugen en CPU-tijd. Daarom raden we aan ervoor te zorgen dat een bestand de juiste extensie heeft of de constructor van de Converter‑klasse te gebruiken die laadopties accepteert.

### Explanation

- **Load Source File**: The [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) class is instantiated with the path to the source document ("business-plan.docx").
- **Conversion Options**: An instance of [`PdfConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/) is created to define the settings for PDF conversion.
- **Execute Conversion**: The `convert` method is used to convert the document and save it to the specified output path ("business-plan.pdf").

Raadpleeg de [GroupDocs.Conversion API Reference](https://reference.groupdocs.com/conversion/python-net/) voor meer details over het gebruik van laadopties en andere constructor‑overloads.
