---
title: "Charger le fichier depuis le disque local"
linkTitle: "Load From Local Disk"
second_title: "GroupDocs.Conversion for Python via .NET Références API"
description: "Instancier la classe Converter avec un chemin de fichier absolu ou relatif pour convertir un document stocké sur le système de fichiers local avec GroupDocs.Conversion pour Python via .NET."
type: docs
url: /fr/python-net/guides/load-file-from-local-disk/
is_root: false
weight: 90
---


Pour charger un fichier source depuis votre disque local, vous pouvez utiliser le constructeur de classe [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) dans GroupDocs.Conversion. L'API propose plusieurs surcharges, offrant une flexibilité pour divers paramètres et options :

* `Converter(file_path)`
* `Converter(file_path, load_options)`
* `Converter(file_path, converter_settings)`
* `Converter(file_path, load_options, converter_settings)`

Chaque constructeur nécessite le paramètre `filePath`, qui définit le chemin du fichier source. Vous pouvez le spécifier comme un chemin absolu ou relatif. Notez que si le chemin de fichier spécifié n'existe pas, une exception sera levée.

GroupDocs.Conversion n'accèdera au fichier que lorsqu'une action (par ex., une conversion) est effectuée en utilisant l'instance de classe [`Converter`](/conversion/python-net/groupdocs.conversion/converter/).

L'exemple Python suivant montre le chargement d'un fichier depuis un disque local et sa conversion en PDF :

{{< tabs \"code-example\">}}
{{< tab \"convert_docx_to_pdf.py\" >}}
```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

def convert_docx_to_pdf():
    # Spécifier l'emplacement du fichier source
    converter = Converter("./business-plan.docx")
    
    # Spécifier l'emplacement du fichier de sortie et les options de conversion
    output_path = "./business-plan.pdf"
    pdf_options = PdfConvertOptions()
    
    # Convertir et enregistrer vers le chemin de sortie
    converter.convert(output_path, pdf_options)

if __name__ == "__main__":
    convert_docx_to_pdf()
```
{{< /tab >}}
{{< tab \"business-plan.docx\" >}}

`business-plan.docx` est un fichier d'exemple utilisé dans cet exemple. Cliquez [ici](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/loading-documents/load-file-from-local-disk/business-plan.docx) pour le télécharger.

{{< /tab >}}
{{< tab \"business-plan.pdf\" >}}
```text
Binary file (PDF, 283 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/loading-documents/load-file-from-local-disk/convert_docx_to_pdf/business-plan.pdf)
{{< /tab >}}
{{< /tabs >}}

GroupDocs.Conversion détermine le type de fichier à partir de son extension. Si l'extension du fichier n'est pas définie, GroupDocs.Conversion tentera de détecter le type de fichier automatiquement. En fonction du type de fichier et de sa taille, la détection automatique du type de fichier consomme des ressources supplémentaires, telles que la mémoire et le temps CPU. Par conséquent, nous recommandons de vous assurer qu'un fichier possède la bonne extension ou d'utiliser le constructeur de la classe Converter qui accepte les options de chargement.

### Explanation

- **Load Source File**: The [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) class is instantiated with the path to the source document ("business-plan.docx").
- **Conversion Options**: An instance of [`PdfConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/) is created to define the settings for PDF conversion.
- **Execute Conversion**: The `convert` method is used to convert the document and save it to the specified output path ("business-plan.pdf").

Reportez-vous à la [GroupDocs.Conversion API Reference](https://reference.groupdocs.com/conversion/python-net/) pour plus de détails sur l'utilisation des options de chargement et d'autres surcharges de constructeur.
