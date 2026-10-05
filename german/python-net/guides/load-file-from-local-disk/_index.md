---
title: "Datei vom lokalen Laufwerk laden"
linkTitle: "Load From Local Disk"
second_title: "GroupDocs.Conversion für Python über .NET API-Referenzen"
description: "Instanziieren Sie die Converter-Klasse mit einem absoluten oder relativen Dateipfad, um ein im lokalen Dateisystem gespeichertes Dokument mit GroupDocs.Conversion für Python über .NET zu konvertieren."
type: docs
url: /de/python-net/guides/load-file-from-local-disk/
is_root: false
weight: 90
---


Um eine Quelldatei von Ihrem lokalen Laufwerk zu laden, können Sie den Konstruktor der [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) Klasse in GroupDocs.Conversion verwenden. Die API bietet mehrere Überladungen, die Flexibilität für verschiedene Einstellungen und Optionen ermöglichen:

* `Converter(file_path)`
* `Converter(file_path, load_options)`
* `Converter(file_path, converter_settings)`
* `Converter(file_path, load_options, converter_settings)`

Jeder Konstruktor erfordert den Parameter `filePath`, der den Pfad zur Quelldatei definiert. Sie können diesen als absoluten oder relativen Pfad angeben. Beachten Sie, dass eine Ausnahme ausgelöst wird, wenn der angegebene Dateipfad nicht existiert.

GroupDocs.Conversion greift nur dann auf die Datei zu, wenn eine Aktion (z. B. Konvertierung) mit einer [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) Klasseninstanz ausgeführt wird.

Das folgende Python-Beispiel demonstriert das Laden einer Datei von einem lokalen Laufwerk und deren Konvertierung in PDF:

{{< tabs "code-example">}}
{{< tab "convert_docx_to_pdf.py" >}}
```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

def convert_docx_to_pdf():
    # Geben Sie den Speicherort der Quelldatei an
    converter = Converter("./business-plan.docx")
    
    # Geben Sie den Speicherort der Ausgabedatei und die Konvertierungsoptionen an
    output_path = "./business-plan.pdf"
    pdf_options = PdfConvertOptions()
    
    # Konvertieren und im Ausgabepfad speichern
    converter.convert(output_path, pdf_options)

if __name__ == "__main__":
    convert_docx_to_pdf()
```
{{< /tab >}}
{{< tab "business-plan.docx" >}}

`business-plan.docx` ist eine Beispieldatei, die in diesem Beispiel verwendet wird. Klicken Sie [hier](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/loading-documents/load-file-from-local-disk/business-plan.docx) zum Herunterladen.

{{< /tab >}}
{{< tab "business-plan.pdf" >}}
```text
Binary file (PDF, 283 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/loading-documents/load-file-from-local-disk/convert_docx_to_pdf/business-plan.pdf)
{{< /tab >}}
{{< /tabs >}}

GroupDocs.Conversion ermittelt den Dateityp anhand seiner Erweiterung. Ist die Dateierweiterung nicht gesetzt, versucht GroupDocs.Conversion den Dateityp automatisch zu erkennen. Je nach Dateityp und Größe verbraucht die automatische Dateityperkennung zusätzliche Ressourcen, wie Speicher und CPU‑Zeit. Daher empfehlen wir, sicherzustellen, dass eine Datei die korrekte Erweiterung hat, oder den Konstruktor der Converter‑Klasse zu verwenden, der Ladeoptionen akzeptiert.

### Explanation

- **Load Source File**: The [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) class is instantiated with the path to the source document ("business-plan.docx").
- **Conversion Options**: An instance of [`PdfConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/) is created to define the settings for PDF conversion.
- **Execute Conversion**: The `convert` method is used to convert the document and save it to the specified output path ("business-plan.pdf").

Weitere Details zur Verwendung von Ladeoptionen und anderen Konstruktorüberladungen finden Sie in der [GroupDocs.Conversion API Reference](https://reference.groupdocs.com/conversion/python-net/).
