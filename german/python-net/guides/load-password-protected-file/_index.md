---
title: "Passwortgeschützte Datei laden"
linkTitle: "Load Password-Protected File"
second_title: "GroupDocs.Conversion für Python über .NET API-Referenzen"
description: "Entsperren und konvertieren Sie passwortgeschützte Word-, Excel-, PowerPoint- und PDF-Dokumente, indem Sie eine LoadOptions‑Instanz mit dem Passwort‑Attribut an den Converter‑Konstruktor in GroupDocs.Conversion für Python via .NET übergeben."
type: docs
url: /de/python-net/guides/load-password-protected-file/
is_root: false
weight: 100
---


Mit *GroupDocs.Conversion for Python via .NET* können Sie Dokumente laden und konvertieren, die mit einem Passwort geschützt sind. Diese Funktion ist nützlich, wenn Sie Dokumente verarbeiten müssen, die eine Authentifizierung erfordern, um auf ihren Inhalt zuzugreifen.

Um ein passwortgeschütztes Dokument zu laden und zu konvertieren, folgen Sie den im nachstehenden Codebeispiel beschriebenen Schritten:

{{< tabs "code-example">}}
{{< tab \"load_password_protected_file.py\" >}}
```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions
from groupdocs.conversion.options.load import WordProcessingLoadOptions

def load_password_protected_file():
    # Dateipfad festlegen
    file_path = "./password-protected.docx"
    
    # Ladeoptionen instanziieren und Passwort festlegen
    wp_load_options = WordProcessingLoadOptions()
    wp_load_options.password = "12345"

    # Quelldateistream und Ladeoptionen angeben
    converter = Converter(file_path, wp_load_options)
    
    # Geben Sie den Speicherort der Ausgabedatei und die Konvertierungsoptionen an
    output_path = "./password-protected.pdf"
    pdf_convert_options = PdfConvertOptions()
    pdf_convert_options.password = "67890"

    # Konvertieren und im Ausgabepfad speichern
    converter.convert(output_path, pdf_convert_options)

if __name__ == "__main__":
    load_password_protected_file()

```
{{< /tab >}}
{{< tab \"password-protected.docx\" >}}

`password-protected.docx` ist eine Beispieldatei, die in diesem Beispiel verwendet wird. Klicken Sie [hier](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/loading-documents/load-password-protected-file/password-protected.docx) zum Herunterladen.

{{< /tab >}}
{{< tab \"password-protected.pdf\" >}}
```text
Binary file (PDF, 234 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/loading-documents/load-password-protected-file/load_password_protected_file/password-protected.pdf)
{{< /tab >}}
{{< /tabs >}}

Falls das angegebene Passwort falsch ist, wird ein Laufzeitfehler ausgelöst. Der erwartete Fehler und die Fehlermeldung sind wie folgt:

```bash
RuntimeError: Proxy error(CorruptOrDamagedFileException): Cannot convert. The file is corrupt or damaged. The document password is incorrect. ---> IncorrectPasswordException: The document password is incorrect.
```

### Explanation

1. **File Path Setup**: Der Dateipfad für das passwortgeschützte Dokument wird angegeben. In diesem Beispiel wird angenommen, dass das Dokument `password-protected.docx` heißt.

2. **Load Options**: Eine Instanz von [`WordProcessingLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/) wird erstellt, und das zum Öffnen des Dokuments erforderliche Passwort wird festgelegt.

3. **Converter Initialization**: Eine [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) Instanz wird unter Verwendung des Dateipfads und der Ladeoptionen, die das Passwort enthalten, erstellt.

4. **Convert Options**: Eine Instanz von [`PdfConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/) wird für den Konvertierungsprozess erstellt. Sie können bei Bedarf auch das Ausgabepasswort für das resultierende PDF festlegen.

4. **Conversion Execution**: Schließlich wird die Methode `convert` auf der [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) Instanz aufgerufen, um das passwortgeschützte Dokument zu konvertieren und als PDF zu speichern.

### Conclusion

Dieses Beispiel zeigt, wie passwortgeschützte Dokumente effizient mit der GroupDocs.Conversion für Python API geladen und konvertiert werden können. Stellen Sie sicher, dass Sie die Passwörter und Dateipfade vor der Ausführung des Codes durch Ihre tatsächlichen Werte ersetzen.
