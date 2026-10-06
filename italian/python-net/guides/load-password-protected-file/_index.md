---
title: "Carica file protetto da password"
linkTitle: "Load Password-Protected File"
second_title: "Riferimenti API di GroupDocs.Conversion per Python tramite .NET"
description: "Sblocca e converti documenti Word, Excel, PowerPoint e PDF protetti da password passando un'istanza di LoadOptions con l'attributo password al costruttore di Converter in GroupDocs.Conversion per Python via .NET."
type: docs
url: /it/python-net/guides/load-password-protected-file/
is_root: false
weight: 100
---


Con *GroupDocs.Conversion for Python via .NET* puoi caricare e convertire documenti protetti da password. Questa funzionalità è utile quando devi gestire documenti che richiedono autenticazione per accedere al loro contenuto.

Per caricare e convertire un documento protetto da password, segui i passaggi descritti nell'esempio di codice qui sotto:

{{< tabs \"code-example\">}}
{{< tab \"load_password_protected_file.py\" >}}
```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions
from groupdocs.conversion.options.load import WordProcessingLoadOptions

def load_password_protected_file():
    # Imposta il percorso del file
    file_path = "./password-protected.docx"
    
    # Istanzia le opzioni di caricamento e imposta la password
    wp_load_options = WordProcessingLoadOptions()
    wp_load_options.password = "12345"

    # Specifica lo stream del file sorgente e le opzioni di caricamento
    converter = Converter(file_path, wp_load_options)
    
    # Specificare la posizione del file di output e le opzioni di conversione
    output_path = "./password-protected.pdf"
    pdf_convert_options = PdfConvertOptions()
    pdf_convert_options.password = "67890"

    # Convertire e salvare nel percorso di output
    converter.convert(output_path, pdf_convert_options)

if __name__ == "__main__":
    load_password_protected_file()

```
{{< /tab >}}
{{< tab \"password-protected.docx\" >}}

`password-protected.docx` è il file di esempio usato in questo esempio. Fai clic [qui](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/loading-documents/load-password-protected-file/password-protected.docx) per scaricarlo.

{{< /tab >}}
{{< tab \"password-protected.pdf\" >}}
```text
Binary file (PDF, 234 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/loading-documents/load-password-protected-file/load_password_protected_file/password-protected.pdf)
{{< /tab >}}
{{< /tabs >}}

Nel caso in cui la password fornita sia errata, verrà generato un errore di runtime. L'errore previsto e il relativo messaggio sono i seguenti:

```bash
RuntimeError: Proxy error(CorruptOrDamagedFileException): Cannot convert. The file is corrupt or damaged. The document password is incorrect. ---> IncorrectPasswordException: The document password is incorrect.
```

### Explanation

1. **File Path Setup**: Il percorso del file per il documento protetto da password è specificato. In questo esempio, si assume che il documento si chiami `password-protected.docx`.

2. **Load Options**: Viene creata un'istanza di [`WordProcessingLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/), e viene impostata la password necessaria per aprire il documento.

3. **Converter Initialization**: Viene creata un'istanza di [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) utilizzando il percorso del file e le opzioni di caricamento che includono la password.

4. **Convert Options**: Viene creata un'istanza di [`PdfConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/) per il processo di conversione. È inoltre possibile impostare la password di output per il PDF risultante, se necessario.

4. **Conversion Execution**: Infine, il metodo `convert` viene chiamato sull'istanza [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) per convertire il documento protetto da password e salvarlo come PDF.

### Conclusion

Questo esempio dimostra come caricare e convertire in modo efficiente documenti protetti da password utilizzando l'API GroupDocs.Conversion per Python. Assicurati di sostituire le password e i percorsi dei file con i valori effettivi prima di eseguire il codice.
