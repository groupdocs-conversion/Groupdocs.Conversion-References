---
title: "Carica file dal disco locale"
linkTitle: "Load From Local Disk"
second_title: "Riferimenti API di GroupDocs.Conversion per Python tramite .NET"
description: "Istanziare la classe Converter con un percorso file assoluto o relativo per convertire un documento memorizzato sul file system locale con GroupDocs.Conversion per Python tramite .NET."
type: docs
url: /it/python-net/guides/load-file-from-local-disk/
is_root: false
weight: 90
---


Per caricare un file sorgente dal disco locale, è possibile utilizzare il costruttore della classe [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) in GroupDocs.Conversion. L'API offre diverse sovraccarichi, consentendo flessibilità per varie impostazioni e opzioni:

* `Converter(file_path)`
* `Converter(file_path, load_options)`
* `Converter(file_path, converter_settings)`
* `Converter(file_path, load_options, converter_settings)`

Ogni costruttore richiede il parametro `filePath`, che definisce il percorso del file sorgente. È possibile specificarlo come percorso assoluto o relativo. Nota che se il percorso file specificato non esiste, verrà sollevata un'eccezione.

GroupDocs.Conversion accederà al file solo quando viene eseguita un'azione (ad es., conversione) utilizzando l'istanza della classe [`Converter`](/conversion/python-net/groupdocs.conversion/converter/).

Il seguente esempio Python dimostra come caricare un file da un disco locale e convertirlo in PDF:

{{< tabs \"code-example\">}}
{{< tab \"convert_docx_to_pdf.py\" >}}
```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

def convert_docx_to_pdf():
    # Specificare la posizione del file sorgente
    converter = Converter("./business-plan.docx")
    
    # Specificare la posizione del file di output e le opzioni di conversione
    output_path = "./business-plan.pdf"
    pdf_options = PdfConvertOptions()
    
    # Convertire e salvare nel percorso di output
    converter.convert(output_path, pdf_options)

if __name__ == "__main__":
    convert_docx_to_pdf()
```
{{< /tab >}}
{{< tab \"business-plan.docx\" >}}

`business-plan.docx` è il file di esempio utilizzato in questo esempio. Fai clic [qui](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/loading-documents/load-file-from-local-disk/business-plan.docx) per scaricarlo.

{{< /tab >}}
{{< tab "business-plan.pdf" >}}
```text
Binary file (PDF, 283 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/loading-documents/load-file-from-local-disk/convert_docx_to_pdf/business-plan.pdf)
{{< /tab >}}
{{< /tabs >}}

GroupDocs.Conversion determina il tipo di file dalla sua estensione. Se l'estensione del file non è impostata, GroupDocs.Conversion cercherà di rilevare automaticamente il tipo di file. A seconda del tipo di file e delle dimensioni, il rilevamento automatico del tipo di file consuma risorse aggiuntive, come memoria e tempo CPU. Pertanto, consigliamo di assicurarsi che un file abbia l'estensione corretta o di utilizzare il costruttore della classe Converter che accetta le opzioni di caricamento.

### Explanation

- **Load Source File**: The [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) class is instantiated with the path to the source document ("business-plan.docx").
- **Conversion Options**: An instance of [`PdfConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/) is created to define the settings for PDF conversion.
- **Execute Conversion**: The `convert` method is used to convert the document and save it to the specified output path ("business-plan.pdf").

Consulta la [GroupDocs.Conversion API Reference](https://reference.groupdocs.com/conversion/python-net/) per ulteriori dettagli sull'utilizzo delle opzioni di caricamento e di altri overload del costruttore.
