---
title: "Obtener conversiones posibles"
linkTitle: "Get Possible Conversions"
second_title: "Referencias de API de GroupDocs.Conversion para Python a través de .NET"
description: "Consulte GroupDocs.Conversion para Python a través de .NET el conjunto de formatos de destino que admite una fuente dada — a nivel de biblioteca, por extensión o para el documento cargado actualmente — mediante get_all_possible_conversions, get_possible_conversions_by_extension y get_possible_conversions."
type: docs
url: /es/python-net/guides/get-possible-conversions/
is_root: false
weight: 50
---


GroupDocs.Conversion ofrece varios métodos para obtener conversiones posibles:

- **`Converter.get_all_possible_conversions()`**: Retrieves all available primary and secondary conversions for every supported file type.
- **`Converter.get_possible_conversions_by_extension(extension: str)`**: Retrieves possible conversions for a specific file extension, e.g., `"docx"`.
- **`converter.get_possible_conversions()`**: Retrieves possible conversions for the currently loaded file.

### Types of Conversions
* **Primary Conversion**: A direct conversion from one format to another, providing higher quality and better performance.
* **Secondary Conversion**: An indirect conversion that requires the source file to be first converted to an intermediate format before reaching the final format.

## Example 1: Get All Possible Conversions

El siguiente ejemplo muestra cómo obtener y mostrar todas las conversiones primarias y secundarias para cada tipo de archivo compatible.

{{< tabs "example-1">}}
{{< tab "get_all_possible_conversions.py" >}}
```python
from groupdocs.conversion import Converter

# GroupDocs.Conversion admite más de 150 formatos de origen; imprima los primeros N
# para mantener la salida de consola legible. Aumente o elimine el límite para ver
# cada formato de origen.
SAMPLE_LIMIT = 3

def get_all_possible_conversions():
    # Obtener todas las conversiones posibles para cada formato de origen compatible
    all_possible_conversions = list(Converter.get_all_possible_conversions())

    print(f"Total supported source formats: {len(all_possible_conversions)}")
    print(f"Showing the first {SAMPLE_LIMIT} as a sample.")
    print()

    for possible_conversion in all_possible_conversions[:SAMPLE_LIMIT]:
        # Recopilar extensiones de destino primarias / secundarias para esta fuente
        primary_conversions = [c.format.extension for c in possible_conversion.all if c.is_primary]
        secondary_conversions = [c.format.extension for c in possible_conversion.all if not c.is_primary]

        # Imprimir el formato de origen y sus extensiones de destino
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

El siguiente ejemplo muestra cómo obtener y mostrar conversiones posibles para la extensión \"docx\", que corresponde a un documento Microsoft Word Open XML.

{{< tabs "example-2">}}
{{< tab \"get_all_possible_conversions_by_file_extension.py\" >}}
```python
from groupdocs.conversion import Converter

def get_all_possible_conversions_by_file_extension():
    # Obtener todas las conversiones posibles para una extensión específica
    possible_conversion = Converter.get_possible_conversions_by_extension("docx")

    # Filtrar conversiones primarias (use .extension para una cadena limpia)
    primary_conversions = [conversion.format.extension for conversion in possible_conversion.all if conversion.is_primary]
    # Filtrar conversiones secundarias
    secondary_conversions = [conversion.format.extension for conversion in possible_conversion.all if not conversion.is_primary]

    # Imprimir el formato de origen y sus conversiones
    print(f" **Source format**: {possible_conversion.source.description}")
    print(f"  - **Primary conversions**: {primary_conversions}")
    print(f"  - **Secondary conversions**: {secondary_conversions}")
    print()

if __name__ == "__main__":
    get_all_possible_conversions_by_file_extension()
```
{{< /tab >}}
{{< tab \"get-all-possible-conversions-by-file-extension.txt\" >}}
```text
**Source format**: Microsoft Word Open XML Document (docx)
  - **Primary conversions**: ['epub', 'mobi', 'azw3', 'tiff', 'tif', 'jpg', 'jpeg', 'png', 'gif', 'bmp', 'ico', 'psd', 'wmf', 'emf', 'dcm', 'dicom', 'webp', 'jp2', 'j2k', 'emz', 'wmz', 'tga', 'psb', 'jfif', 'eps', 'xps', 'tex', 'ps', 'pcl', 'svg', 'svgz', 'pdf', 'ppt', 'pps', 'pptx', 'ppsx', 'odp', 'otp', 'potx', 'pot', 'potm', 'pptm', 'ppsm', 'fodp', 'htm', 'html', 'mhtml', 'mht', 'doc', 'docm', 'docx', 'dot', 'dotm', 'dotx', 'rtf', 'od
[TRUNCATED]
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/converting-documents/get-possible-conversions/get_all_possible_conversions_by_file_extension/get-all-possible-conversions-by-file-extension.txt)
{{< /tab >}}
{{< /tabs >}}

## Example 3: Get Possible Conversions for Current File

El siguiente ejemplo muestra cómo obtener y mostrar conversiones posibles para un archivo pasado al constructor de la clase [`Converter`](/conversion/python-net/groupdocs.conversion/converter/).

{{< tabs \"example-3\">}}
{{< tab \"get_all_possible_conversions_for_current_file.py\" >}}
```python
from groupdocs.conversion import Converter

def get_all_possible_conversions_for_current_file():
    with Converter("./cost-analysis.xlsx") as converter:
        # Obtener conversiones posibles para el documento cargado
        possible_conversion = converter.get_possible_conversions()

        # Filtrar conversiones primarias (use .extension para una cadena limpia)
        primary_conversions = [conversion.format.extension for conversion in possible_conversion.all if conversion.is_primary]
        # Filtrar conversiones secundarias
        secondary_conversions = [conversion.format.extension for conversion in possible_conversion.all if not conversion.is_primary]

        # Imprimir el formato de origen y sus conversiones
        print(f" **Source format**: {possible_conversion.source.description}")
        print(f"  - **Primary conversions**: {primary_conversions}")
        print(f"  - **Secondary conversions**: {secondary_conversions}")
        print()

if __name__ == "__main__":
    get_all_possible_conversions_for_current_file()
```
{{< /tab >}}
{{< tab \"get-all-possible-conversions-current-file.txt\" >}}
```text
**Source format**: Microsoft Excel Open XML Spreadsheet (xlsx)
  - **Primary conversions**: ['epub', 'mobi', 'azw3', 'eps', 'xps', 'tex', 'ps', 'pcl', 'pdf', 'xls', 'xlsx', 'xlsm', 'xlsb', 'ods', 'xltx', 'xlt', 'xltm', 'tsv', 'xlam', 'csv', 'fods', 'dif', 'sxc', 'fopcs', 'htm', 'html', 'mhtml', 'mht', 'json', 'xml']
  - **Secondary conversions**: ['tiff', 'tif', 'jpg', 'jpeg', 'png', 'gif', 'bmp', 'ico', 'psd', 'wmf', 'emf', 'dcm', 'dicom', 'webp', 'jp2', 'j2k', 'emz', 'wmz', 'tga', 'psb', 'jfif
[TRUNCATED]
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/converting-documents/get-possible-conversions/get_all_possible_conversions_for_current_file/get-all-possible-conversions-current-file.txt)
{{< /tab >}}
{{< /tabs >}}
