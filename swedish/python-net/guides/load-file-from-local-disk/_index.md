---
title: "Läs in fil från lokal disk"
linkTitle: "Load From Local Disk"
second_title: "GroupDocs.Conversion for Python via .NET API-referenser"
description: "Instansiera Converter-klassen med en absolut eller relativ filsökväg för att konvertera ett dokument som lagras på det lokala filsystemet med GroupDocs.Conversion för Python via .NET."
type: docs
url: /sv/python-net/guides/load-file-from-local-disk/
is_root: false
weight: 90
---


För att läsa in en källfil från din lokala disk kan du använda [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) klasskonstruktorn i GroupDocs.Conversion. API:et erbjuder flera överlagringar, vilket ger flexibilitet för olika inställningar och alternativ:

* `Converter(file_path)`
* `Converter(file_path, load_options)`
* `Converter(file_path, converter_settings)`
* `Converter(file_path, load_options, converter_settings)`

Varje konstruktor kräver parametern `filePath`, som definierar sökvägen till källfilen. Du kan ange detta som en absolut eller relativ sökväg. Observera att om den angivna filsökvägen inte finns, kommer ett undantag att kastas.

GroupDocs.Conversion kommer endast att komma åt filen när en åtgärd (t.ex. konvertering) utförs med hjälp av [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) klassinstansen.

Följande Python‑exempel demonstrerar hur man läser in en fil från en lokal disk och konverterar den till PDF:

{{< tabs "code-example">}}
{{< tab "convert_docx_to_pdf.py" >}}
```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

def convert_docx_to_pdf():
    # Ange källfilens plats
    converter = Converter("./business-plan.docx")
    
    # Ange målfilens plats och konverteringsalternativ
    output_path = "./business-plan.pdf"
    pdf_options = PdfConvertOptions()
    
    # Konvertera och spara till målplatsen
    converter.convert(output_path, pdf_options)

if __name__ == "__main__":
    convert_docx_to_pdf()
```
{{< /tab >}}
{{< tab "business-plan.docx" >}}

`business-plan.docx` är exempelfilen som används i detta exempel. Klicka [här](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/loading-documents/load-file-from-local-disk/business-plan.docx) för att ladda ner den.

{{< /tab >}}
{{< tab "business-plan.pdf" >}}
```text
Binary file (PDF, 283 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/loading-documents/load-file-from-local-disk/convert_docx_to_pdf/business-plan.pdf)
{{< /tab >}}
{{< /tabs >}}

GroupDocs.Conversion bestämmer filtypen utifrån dess filändelse. Om filändelsen inte är angiven kommer GroupDocs.Conversion att försöka identifiera filtypen automatiskt. Beroende på filtyp och storlek förbrukar automatisk filtypdetektering ytterligare resurser, såsom minne och CPU‑tid. Därför rekommenderar vi att säkerställa att en fil har rätt filändelse eller att använda Converter‑klasskonstruktorn som accepterar laddningsalternativ.

### Explanation

- **Load Source File**: The [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) class is instantiated with the path to the source document ("business-plan.docx").
- **Conversion Options**: An instance of [`PdfConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/) is created to define the settings for PDF conversion.
- **Execute Conversion**: The `convert` method is used to convert the document and save it to the specified output path ("business-plan.pdf").

Se [GroupDocs.Conversion API‑referens](https://reference.groupdocs.com/conversion/python-net/) för mer information om hur du använder laddningsalternativ och andra konstruktoröverladdningar.
