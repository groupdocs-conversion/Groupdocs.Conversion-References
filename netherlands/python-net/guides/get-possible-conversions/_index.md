---
title: "Mogelijke conversies ophalen"
linkTitle: "Get Possible Conversions"
second_title: "GroupDocs.Conversion for Python via .NET API-referenties"
description: "Vraag GroupDocs.Conversion voor Python via .NET op naar de reeks doelformaten die een gegeven bron ondersteunt — bibliotheek‑breed, per extensie, of voor het momenteel geladen document — via get_all_possible_conversions, get_possible_conversions_by_extension en get_possible_conversions."
type: docs
url: /nl/python-net/guides/get-possible-conversions/
is_root: false
weight: 50
---


GroupDocs.Conversion biedt verschillende methoden om mogelijke conversies op te halen:

- **`Converter.get_all_possible_conversions()`**: Retrieves all available primary and secondary conversions for every supported file type.
- **`Converter.get_possible_conversions_by_extension(extension: str)`**: Retrieves possible conversions for a specific file extension, e.g., `"docx"`.
- **`converter.get_possible_conversions()`**: Retrieves possible conversions for the currently loaded file.

### Types of Conversions
* **Primary Conversion**: A direct conversion from one format to another, providing higher quality and better performance.
* **Secondary Conversion**: An indirect conversion that requires the source file to be first converted to an intermediate format before reaching the final format.

## Example 1: Get All Possible Conversions

Het volgende voorbeeld laat zien hoe alle primaire en secundaire conversies voor elk ondersteund bestandstype kunnen worden opgehaald en weergegeven.

{{< tabs \"example-1\">}}
{{< tab "get_all_possible_conversions.py" >}}
```python
from groupdocs.conversion import Converter

# GroupDocs.Conversion ondersteunt meer dan 150 bronformaten; druk de eerste N af
# om de console‑output leesbaar te houden. Verhoog of verwijder de limiet om te zien
# elk bronformaat.
SAMPLE_LIMIT = 3

def get_all_possible_conversions():
    # Haal alle mogelijke conversies op voor elk ondersteund bronformaat
    all_possible_conversions = list(Converter.get_all_possible_conversions())

    print(f"Total supported source formats: {len(all_possible_conversions)}")
    print(f"Showing the first {SAMPLE_LIMIT} as a sample.")
    print()

    for possible_conversion in all_possible_conversions[:SAMPLE_LIMIT]:
        # Verzamel primaire / secundaire doel‑extensies voor deze bron
        primary_conversions = [c.format.extension for c in possible_conversion.all if c.is_primary]
        secondary_conversions = [c.format.extension for c in possible_conversion.all if not c.is_primary]

        # Druk het bronformaat en de bijbehorende doel‑extensies af
        print(f"Source format: {possible_conversion.source.description}")
        print(f"  Primary target formats  ({len(primary_conversions)}): {primary_conversions}")
        print(f"  Secondary target formats ({len(secondary_conversions)}): {secondary_conversions}")
        print()

if __name__ == "__main__":
    get_all_possible_conversions()
```
{{< /tab >}}
{{< tab "get-all-possible-conversions.txt" >}}
```text
Total supported source formats: 208
Showing the first 3 as a sample.

Source format: MP3 Audio File (mp3)
  Primary target formats  (9): ['mp3', 'aac', 'aiff', 'flac', 'm4a', 'wma', 'ac3', 'ogg', 'wav']
  Secondary target formats (0): []

Source format: Advanced Audio Coding File (aac)
  Primary target formats  (9): ['mp3', 'aac', 'aiff', 'flac', 'm4a', 'wma', 'ac3', 'ogg', 'wav']
  Secondary target formats (0): []
[TRUNCATED]
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/converting-documents/get-possible-conversions/get_all_possible_conversions/get-all-possible-conversions.txt)
{{< /tab >}}
{{< /tabs >}}

## Example 2: Get Possible Conversions by File Extension

Het volgende voorbeeld toont hoe mogelijke conversies voor de "docx" extensie op te halen en weer te geven, die overeenkomt met een Microsoft Word Open XML-document.

{{< tabs "example-2">}}
{{< tab "get_all_possible_conversions_by_file_extension.py" >}}
```python
from groupdocs.conversion import Converter

def get_all_possible_conversions_by_file_extension():
    # Alle mogelijke conversies ophalen voor een specifieke extensie
    possible_conversion = Converter.get_possible_conversions_by_extension("docx")

    # Primaire conversies filteren (gebruik .extension voor een schone string)
    primary_conversions = [conversion.format.extension for conversion in possible_conversion.all if conversion.is_primary]
    # Secundaire conversies filteren
    secondary_conversions = [conversion.format.extension for conversion in possible_conversion.all if not conversion.is_primary]

    # Print het bronformaat en de bijbehorende conversies
    print(f" **Source format**: {possible_conversion.source.description}")
    print(f"  - **Primary conversions**: {primary_conversions}")
    print(f"  - **Secondary conversions**: {secondary_conversions}")
    print()

if __name__ == "__main__":
    get_all_possible_conversions_by_file_extension()
```
{{< /tab >}}
{{< tab "get-all-possible-conversions-by-file-extension.txt" >}}
```text
**Source format**: Microsoft Word Open XML Document (docx)
  - **Primary conversions**: ['epub', 'mobi', 'azw3', 'tiff', 'tif', 'jpg', 'jpeg', 'png', 'gif', 'bmp', 'ico', 'psd', 'wmf', 'emf', 'dcm', 'dicom', 'webp', 'jp2', 'j2k', 'emz', 'wmz', 'tga', 'psb', 'jfif', 'eps', 'xps', 'tex', 'ps', 'pcl', 'svg', 'svgz', 'pdf', 'ppt', 'pps', 'pptx', 'ppsx', 'odp', 'otp', 'potx', 'pot', 'potm', 'pptm', 'ppsm', 'fodp', 'htm', 'html', 'mhtml', 'mht', 'doc', 'docm', 'docx', 'dot', 'dotm', 'dotx', 'rtf', 'od
[TRUNCATED]
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/converting-documents/get-possible-conversions/get_all_possible_conversions_by_file_extension/get-all-possible-conversions-by-file-extension.txt)
{{< /tab >}}
{{< /tabs >}}

## Example 3: Get Possible Conversions for Current File

Het volgende voorbeeld toont hoe mogelijke conversies voor een bestand dat wordt doorgegeven aan de [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) class constructor op te halen en weer te geven.

{{< tabs "example-3">}}
{{< tab "get_all_possible_conversions_for_current_file.py" >}}
```python
from groupdocs.conversion import Converter

def get_all_possible_conversions_for_current_file():
    with Converter("./cost-analysis.xlsx") as converter:
        # Mogelijke conversies ophalen voor het geladen document
        possible_conversion = converter.get_possible_conversions()

        # Primaire conversies filteren (gebruik .extension voor een schone string)
        primary_conversions = [conversion.format.extension for conversion in possible_conversion.all if conversion.is_primary]
        # Secundaire conversies filteren
        secondary_conversions = [conversion.format.extension for conversion in possible_conversion.all if not conversion.is_primary]

        # Print het bronformaat en de bijbehorende conversies
        print(f" **Source format**: {possible_conversion.source.description}")
        print(f"  - **Primary conversions**: {primary_conversions}")
        print(f"  - **Secondary conversions**: {secondary_conversions}")
        print()

if __name__ == "__main__":
    get_all_possible_conversions_for_current_file()
```
{{< /tab >}}
{{< tab "get-all-possible-conversions-current-file.txt" >}}
```text
**Source format**: Microsoft Excel Open XML Spreadsheet (xlsx)
  - **Primary conversions**: ['epub', 'mobi', 'azw3', 'eps', 'xps', 'tex', 'ps', 'pcl', 'pdf', 'xls', 'xlsx', 'xlsm', 'xlsb', 'ods', 'xltx', 'xlt', 'xltm', 'tsv', 'xlam', 'csv', 'fods', 'dif', 'sxc', 'fopcs', 'htm', 'html', 'mhtml', 'mht', 'json', 'xml']
  - **Secondary conversions**: ['tiff', 'tif', 'jpg', 'jpeg', 'png', 'gif', 'bmp', 'ico', 'psd', 'wmf', 'emf', 'dcm', 'dicom', 'webp', 'jp2', 'j2k', 'emz', 'wmz', 'tga', 'psb', 'jfif
[TRUNCATED]
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/converting-documents/get-possible-conversions/get_all_possible_conversions_for_current_file/get-all-possible-conversions-current-file.txt)
{{< /tab >}}
{{< /tabs >}}
