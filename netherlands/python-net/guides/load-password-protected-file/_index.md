---
title: "Bestand met wachtwoordbeveiliging laden"
linkTitle: "Load Password-Protected File"
second_title: "GroupDocs.Conversion for Python via .NET API-referenties"
description: "Ontgrendel en converteer met wachtwoord beveiligde Word-, Excel-, PowerPoint- en PDF‑documenten door een LoadOptions‑instantie met het wachtwoord‑attribuut door te geven aan de Converter‑constructor in GroupDocs.Conversion voor Python via .NET."
type: docs
url: /nl/python-net/guides/load-password-protected-file/
is_root: false
weight: 100
---


Met *GroupDocs.Conversion for Python via .NET* kun je documenten die met een wachtwoord zijn beveiligd laden en converteren. Deze functie is handig wanneer je documenten moet verwerken die authenticatie vereisen om toegang te krijgen tot hun inhoud.

Om een met wachtwoord beveiligd document te laden en te converteren, volg je de stappen die in het code‑voorbeeld hieronder worden beschreven:

{{< tabs \"code-example\">}}
{{< tab "load_password_protected_file.py" >}}
```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions
from groupdocs.conversion.options.load import WordProcessingLoadOptions

def load_password_protected_file():
    # Stel bestands‑pad in
    file_path = "./password-protected.docx"
    
    # Instantieer laadopties en stel wachtwoord in
    wp_load_options = WordProcessingLoadOptions()
    wp_load_options.password = "12345"

    # Geef bron‑bestand‑stream en laadopties op
    converter = Converter(file_path, wp_load_options)
    
    # Specificeer de locatie van het uitvoerbestand en conversie‑opties
    output_path = "./password-protected.pdf"
    pdf_convert_options = PdfConvertOptions()
    pdf_convert_options.password = "67890"

    # Converteer en sla op naar het uitvoerpad
    converter.convert(output_path, pdf_convert_options)

if __name__ == "__main__":
    load_password_protected_file()

```
{{< /tab >}}
{{< tab "password-protected.docx" >}}

`password-protected.docx` is een voorbeeldbestand dat in dit voorbeeld wordt gebruikt. Klik [hier](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/loading-documents/load-password-protected-file/password-protected.docx) om het te downloaden.

{{< /tab >}}
{{< tab "password-protected.pdf" >}}
```text
Binary file (PDF, 234 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/loading-documents/load-password-protected-file/load_password_protected_file/password-protected.pdf)
{{< /tab >}}
{{< /tabs >}}

Als het opgegeven wachtwoord onjuist is, wordt er een runtime‑fout gegooid. De verwachte fout en foutmelding zijn als volgt:

```bash
RuntimeError: Proxy error(CorruptOrDamagedFileException): Cannot convert. The file is corrupt or damaged. The document password is incorrect. ---> IncorrectPasswordException: The document password is incorrect.
```

### Explanation

1. **File Path Setup**: Het bestandspad voor het wachtwoord‑beveiligde document wordt gespecificeerd. In dit voorbeeld wordt aangenomen dat het document `password-protected.docx` heet.

2. **Load Options**: Er wordt een instantie van [`WordProcessingLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/) gemaakt, en het wachtwoord dat nodig is om het document te openen, wordt ingesteld.

3. **Converter Initialization**: Er wordt een [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) instantie aangemaakt met behulp van het bestandspad en de laadopties die het wachtwoord bevatten.

4. **Convert Options**: Er wordt een instantie van [`PdfConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/) aangemaakt voor het conversieproces. U kunt ook het uitvoerwachtwoord voor de resulterende PDF instellen indien nodig.

4. **Conversion Execution**: Ten slotte wordt de `convert`‑methode aangeroepen op de [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) instantie om het wachtwoord‑beveiligde document te converteren en op te slaan als PDF.

### Conclusion

Dit voorbeeld laat zien hoe u efficiënt wachtwoord‑beveiligde documenten kunt laden en converteren met de GroupDocs.Conversion for Python API. Zorg ervoor dat u de wachtwoorden en bestandspaden vervangt door uw werkelijke waarden voordat u de code uitvoert.
