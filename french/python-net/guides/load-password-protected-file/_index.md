---
title: "Charger un fichier protégé par mot de passe"
linkTitle: "Load Password-Protected File"
second_title: "GroupDocs.Conversion for Python via .NET Références API"
description: "Déverrouillez et convertissez les documents Word, Excel, PowerPoint et PDF protégés par mot de passe en passant une instance de LoadOptions avec l'attribut password au constructeur de Converter dans GroupDocs.Conversion pour Python via .NET."
type: docs
url: /fr/python-net/guides/load-password-protected-file/
is_root: false
weight: 100
---


Avec *GroupDocs.Conversion for Python via .NET*, vous pouvez charger et convertir des documents protégés par un mot de passe. Cette fonctionnalité est utile lorsque vous devez gérer des documents qui nécessitent une authentification pour accéder à leur contenu.

Pour charger et convertir un document protégé par mot de passe, suivez les étapes décrites dans l'exemple de code ci‑dessous :

{{< tabs \"code-example\">}}
{{< tab "load_password_protected_file.py" >}}
```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions
from groupdocs.conversion.options.load import WordProcessingLoadOptions

def load_password_protected_file():
    # Définir le chemin du fichier
    file_path = "./password-protected.docx"
    
    # Instancier les options de chargement et définir le mot de passe
    wp_load_options = WordProcessingLoadOptions()
    wp_load_options.password = "12345"

    # Spécifier le flux du fichier source et les options de chargement
    converter = Converter(file_path, wp_load_options)
    
    # Spécifier l'emplacement du fichier de sortie et les options de conversion
    output_path = "./password-protected.pdf"
    pdf_convert_options = PdfConvertOptions()
    pdf_convert_options.password = "67890"

    # Convertir et enregistrer vers le chemin de sortie
    converter.convert(output_path, pdf_convert_options)

if __name__ == "__main__":
    load_password_protected_file()

```
{{< /tab >}}
{{< tab "password-protected.docx" >}}

`password-protected.docx` est le fichier d'exemple utilisé dans cet exemple. Cliquez [ici](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/loading-documents/load-password-protected-file/password-protected.docx) pour le télécharger.

{{< /tab >}}
{{< tab "password-protected.pdf" >}}
```text
Binary file (PDF, 234 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/loading-documents/load-password-protected-file/load_password_protected_file/password-protected.pdf)
{{< /tab >}}
{{< /tabs >}}

Dans le cas où le mot de passe fourni est incorrect, une erreur d'exécution sera levée. L'erreur attendue et le message d'erreur sont les suivants :

```bash
RuntimeError: Proxy error(CorruptOrDamagedFileException): Cannot convert. The file is corrupt or damaged. The document password is incorrect. ---> IncorrectPasswordException: The document password is incorrect.
```

### Explanation

1. **File Path Setup** : Le chemin d'accès au document protégé par mot de passe est spécifié. Dans cet exemple, il suppose que le document s'appelle `password-protected.docx`.

2. **Load Options** : Une instance de [`WordProcessingLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/) est créée, et le mot de passe requis pour ouvrir le document est défini.

3. **Converter Initialization** : Une instance de [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) est créée en utilisant le chemin d'accès et les options de chargement qui incluent le mot de passe.

4. **Convert Options** : Une instance de [`PdfConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/) est créée pour le processus de conversion. Vous pouvez également définir le mot de passe de sortie pour le PDF résultant si nécessaire.

4. **Conversion Execution** : Enfin, la méthode `convert` est appelée sur l'instance [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) pour convertir le document protégé par mot de passe et l'enregistrer en PDF.

### Conclusion

Cet exemple montre comment charger et convertir efficacement des documents protégés par mot de passe en utilisant l'API GroupDocs.Conversion pour Python. Assurez‑vous de remplacer les mots de passe et les chemins d'accès par vos valeurs réelles avant d'exécuter le code.
