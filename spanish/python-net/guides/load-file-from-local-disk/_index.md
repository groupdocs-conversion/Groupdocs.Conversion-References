---
title: "Cargar archivo desde disco local"
linkTitle: "Load From Local Disk"
second_title: "Referencias de API de GroupDocs.Conversion para Python a través de .NET"
description: "Instanciar la clase Converter con una ruta de archivo absoluta o relativa para convertir un documento almacenado en el sistema de archivos local con GroupDocs.Conversion para Python a través de .NET."
type: docs
url: /es/python-net/guides/load-file-from-local-disk/
is_root: false
weight: 90
---


Para cargar un archivo fuente desde su disco local, puede usar el constructor de la clase [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) en GroupDocs.Conversion. La API ofrece varias sobrecargas, lo que permite flexibilidad para diversas configuraciones y opciones:

* `Converter(file_path)`
* `Converter(file_path, load_options)`
* `Converter(file_path, converter_settings)`
* `Converter(file_path, load_options, converter_settings)`

Cada constructor requiere el parámetro `filePath`, que define la ruta al archivo fuente. Puede especificarlo como una ruta absoluta o relativa. Tenga en cuenta que si la ruta de archivo especificada no existe, se lanzará una excepción.

GroupDocs.Conversion accederá al archivo solo cuando se realice una acción (p. ej., conversión) utilizando la instancia de la clase [`Converter`](/conversion/python-net/groupdocs.conversion/converter/).

El siguiente ejemplo en Python muestra cómo cargar un archivo desde un disco local y convertirlo a PDF:

{{< tabs "code-example">}}
{{< tab "convert_docx_to_pdf.py" >}}
```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

def convert_docx_to_pdf():
    # Especificar la ubicación del archivo fuente
    converter = Converter("./business-plan.docx")
    
    # Especificar la ubicación del archivo de salida y las opciones de conversión
    output_path = "./business-plan.pdf"
    pdf_options = PdfConvertOptions()
    
    # Convertir y guardar en la ruta de salida
    converter.convert(output_path, pdf_options)

if __name__ == "__main__":
    convert_docx_to_pdf()
```
{{< /tab >}}
{{< tab "business-plan.docx" >}}

`business-plan.docx` es un archivo de muestra utilizado en este ejemplo. Haga clic [aquí](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/loading-documents/load-file-from-local-disk/business-plan.docx) para descargarlo.

{{< /tab >}}
{{< tab "business-plan.pdf" >}}
```text
Binary file (PDF, 283 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/loading-documents/load-file-from-local-disk/convert_docx_to_pdf/business-plan.pdf)
{{< /tab >}}
{{< /tabs >}}

GroupDocs.Conversion determina el tipo de archivo por su extensión. Si la extensión del archivo no está establecida, GroupDocs.Conversion intentará detectar el tipo de archivo automáticamente. Dependiendo del tipo de archivo y su tamaño, la detección automática del tipo de archivo consume recursos adicionales, como memoria y tiempo de CPU. Por lo tanto, recomendamos asegurarse de que un archivo tenga la extensión correcta o usar el constructor de la clase Converter que acepta opciones de carga.

### Explanation

- **Load Source File**: The [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) class is instantiated with the path to the source document ("business-plan.docx").
- **Conversion Options**: An instance of [`PdfConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/) is created to define the settings for PDF conversion.
- **Execute Conversion**: The `convert` method is used to convert the document and save it to the specified output path ("business-plan.pdf").

Consulte la [Referencia de la API de GroupDocs.Conversion](https://reference.groupdocs.com/conversion/python-net/) para obtener más detalles sobre el uso de opciones de carga y otras sobrecargas de constructores.
