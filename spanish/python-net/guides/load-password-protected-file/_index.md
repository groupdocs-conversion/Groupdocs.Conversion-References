---
title: "Cargar archivo protegido con contraseña"
linkTitle: "Load Password-Protected File"
second_title: "Referencias de API de GroupDocs.Conversion para Python a través de .NET"
description: "Desbloquee y convierta documentos de Word, Excel, PowerPoint y PDF protegidos con contraseña pasando una instancia de LoadOptions con el atributo de contraseña al constructor de Converter en GroupDocs.Conversion for Python via .NET."
type: docs
url: /es/python-net/guides/load-password-protected-file/
is_root: false
weight: 100
---


Con *GroupDocs.Conversion for Python via .NET* puedes cargar y convertir documentos que están protegidos con una contraseña. Esta función es útil cuando necesitas manejar documentos que requieren autenticación para acceder a su contenido.

Para cargar y convertir un documento protegido con contraseña, sigue los pasos descritos en el ejemplo de código a continuación:

{{< tabs "code-example">}}
{{< tab \"load_password_protected_file.py\" >}}
```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions
from groupdocs.conversion.options.load import WordProcessingLoadOptions

def load_password_protected_file():
    # Establecer ruta del archivo
    file_path = "./password-protected.docx"
    
    # Instanciar opciones de carga y establecer la contraseña
    wp_load_options = WordProcessingLoadOptions()
    wp_load_options.password = "12345"

    # Especificar flujo de archivo fuente y opciones de carga
    converter = Converter(file_path, wp_load_options)
    
    # Especificar la ubicación del archivo de salida y las opciones de conversión
    output_path = "./password-protected.pdf"
    pdf_convert_options = PdfConvertOptions()
    pdf_convert_options.password = "67890"

    # Convertir y guardar en la ruta de salida
    converter.convert(output_path, pdf_convert_options)

if __name__ == "__main__":
    load_password_protected_file()

```
{{< /tab >}}
{{< tab \"password-protected.docx\" >}}

`password-protected.docx` es un archivo de ejemplo utilizado en este caso. Haz clic [aquí](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/loading-documents/load-password-protected-file/password-protected.docx) para descargarlo.

{{< /tab >}}
{{< tab \"password-protected.pdf\" >}}
```text
Binary file (PDF, 234 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/loading-documents/load-password-protected-file/load_password_protected_file/password-protected.pdf)
{{< /tab >}}
{{< /tabs >}}

En caso de que la contraseña proporcionada sea incorrecta, se lanzará un error en tiempo de ejecución. El error esperado y el mensaje de error son los siguientes:

```bash
RuntimeError: Proxy error(CorruptOrDamagedFileException): Cannot convert. The file is corrupt or damaged. The document password is incorrect. ---> IncorrectPasswordException: The document password is incorrect.
```

### Explanation

1. **File Path Setup**: Se especifica la ruta del archivo para el documento protegido con contraseña. En este ejemplo, se asume que el documento se llama `password-protected.docx`.

2. **Load Options**: Se crea una instancia de [`WordProcessingLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/), y se establece la contraseña necesaria para abrir el documento.

3. **Converter Initialization**: Se crea una instancia de [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) utilizando la ruta del archivo y las opciones de carga que incluyen la contraseña.

4. **Convert Options**: Se crea una instancia de [`PdfConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/) para el proceso de conversión. También puede establecer la contraseña de salida para el PDF resultante si es necesario.

4. **Conversion Execution**: Finalmente, se llama al método `convert` en la instancia de [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) para convertir el documento protegido con contraseña y guardarlo como PDF.

### Conclusion

Este ejemplo muestra cómo cargar y convertir de manera eficiente documentos protegidos con contraseña utilizando la API de GroupDocs.Conversion para Python. Asegúrese de reemplazar las contraseñas y rutas de archivo con sus valores reales antes de ejecutar el código.
