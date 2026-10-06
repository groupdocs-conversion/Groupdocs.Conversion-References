---
title: "Läs in lösenordsskyddad fil"
linkTitle: "Load Password-Protected File"
second_title: "GroupDocs.Conversion for Python via .NET API-referenser"
description: "Lås upp och konvertera lösenordsskyddade Word-, Excel-, PowerPoint- och PDF‑dokument genom att skicka en LoadOptions‑instans med lösenordsattributet till Converter‑konstruktorn i GroupDocs.Conversion för Python via .NET."
type: docs
url: /sv/python-net/guides/load-password-protected-file/
is_root: false
weight: 100
---


Med *GroupDocs.Conversion for Python via .NET* kan du läsa in och konvertera dokument som är skyddade med ett lösenord. Denna funktion är användbar när du behöver hantera dokument som kräver autentisering för att komma åt deras innehåll.

För att läsa in och konvertera ett lösenordsskyddat dokument, följ stegen som beskrivs i kodexemplet nedan:

{{< tabs "code-example">}}
{{< tab \"load_password_protected_file.py\" >}}
```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions
from groupdocs.conversion.options.load import WordProcessingLoadOptions

def load_password_protected_file():
    # Ange filsökväg
    file_path = "./password-protected.docx"
    
    # Instansiera load‑alternativ och ange lösenord
    wp_load_options = WordProcessingLoadOptions()
    wp_load_options.password = "12345"

    # Specificera källfilström och load‑alternativ
    converter = Converter(file_path, wp_load_options)
    
    # Ange målfilens plats och konverteringsalternativ
    output_path = "./password-protected.pdf"
    pdf_convert_options = PdfConvertOptions()
    pdf_convert_options.password = "67890"

    # Konvertera och spara till målplatsen
    converter.convert(output_path, pdf_convert_options)

if __name__ == "__main__":
    load_password_protected_file()

```
{{< /tab >}}
{{< tab \"password-protected.docx\" >}}

`password-protected.docx` är en exempelfil som används i detta exempel. Klicka [här](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/loading-documents/load-password-protected-file/password-protected.docx) för att ladda ner den.

{{< /tab >}}
{{< tab \"password-protected.pdf\" >}}
```text
Binary file (PDF, 234 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/loading-documents/load-password-protected-file/load_password_protected_file/password-protected.pdf)
{{< /tab >}}
{{< /tabs >}}

Om det angivna lösenordet är felaktigt kommer ett körfel att kastas. Det förväntade felet och felmeddelandet är som följer:

```bash
RuntimeError: Proxy error(CorruptOrDamagedFileException): Cannot convert. The file is corrupt or damaged. The document password is incorrect. ---> IncorrectPasswordException: The document password is incorrect.
```

### Explanation

1. **File Path Setup**: Filsökvägen för det lösenordsskyddade dokumentet specificeras. I detta exempel antas dokumentet heta `password-protected.docx`.

2. **Load Options**: En instans av [`WordProcessingLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/) skapas, och lösenordet som krävs för att öppna dokumentet anges.

3. **Converter Initialization**: En [`Converter`](/conversion/python-net/groupdocs.conversion/converter/)‑instans skapas med hjälp av filsökvägen och load‑alternativen som inkluderar lösenordet.

4. **Convert Options**: En instans av [`PdfConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/) skapas för konverteringsprocessen. Du kan också ange ett utdata‑lösenord för den resulterande PDF‑filen om så krävs.

4. **Conversion Execution**: Slutligen anropas `convert`-metoden på [`Converter`](/conversion/python-net/groupdocs.conversion/converter/)‑instansen för att konvertera det lösenordsskyddade dokumentet och spara det som en PDF.

### Conclusion

Detta exempel visar hur man effektivt laddar och konverterar lösenordsskyddade dokument med GroupDocs.Conversion för Python‑API. Se till att ersätta lösenorden och filsökvägarna med dina faktiska värden innan du kör koden.
