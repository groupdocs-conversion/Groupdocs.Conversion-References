---
title: "Загрузить файл, защищённый паролем"
linkTitle: "Load Password-Protected File"
second_title: "GroupDocs.Conversion для Python через .NET справочник API"
description: "Разблокируйте и конвертируйте защищённые паролем документы Word, Excel, PowerPoint и PDF, передавая экземпляр LoadOptions с атрибутом password в конструктор Converter в GroupDocs.Conversion for Python via .NET."
type: docs
url: /ru/python-net/guides/load-password-protected-file/
is_root: false
weight: 100
---


С помощью *GroupDocs.Conversion for Python via .NET* вы можете загружать и конвертировать документы, защищённые паролем. Эта функция полезна, когда необходимо работать с документами, требующими аутентификации для доступа к их содержимому.

Чтобы загрузить и конвертировать документ, защищённый паролем, следуйте шагам, описанным в примере кода ниже:

{{< tabs \"code-example\">}}
{{< tab "load_password_protected_file.py" >}}
```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions
from groupdocs.conversion.options.load import WordProcessingLoadOptions

def load_password_protected_file():
    # Установите путь к файлу
    file_path = "./password-protected.docx"
    
    # Создайте экземпляр load options и задайте пароль
    wp_load_options = WordProcessingLoadOptions()
    wp_load_options.password = "12345"

    # Укажите поток исходного файла и параметры загрузки
    converter = Converter(file_path, wp_load_options)
    
    # Укажите расположение выходного файла и параметры конвертации
    output_path = "./password-protected.pdf"
    pdf_convert_options = PdfConvertOptions()
    pdf_convert_options.password = "67890"

    # Преобразуйте и сохраните в путь вывода
    converter.convert(output_path, pdf_convert_options)

if __name__ == "__main__":
    load_password_protected_file()

```
{{< /tab >}}
{{< tab "password-protected.docx" >}}

`password-protected.docx` — пример файла, используемый в этом примере. Нажмите [здесь](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/loading-documents/load-password-protected-file/password-protected.docx), чтобы скачать его.

{{< /tab >}}
{{< tab "password-protected.pdf" >}}
```text
Binary file (PDF, 234 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/loading-documents/load-password-protected-file/load_password_protected_file/password-protected.pdf)
{{< /tab >}}
{{< /tabs >}}

Если предоставленный пароль неверен, будет выброшена ошибка выполнения. Ожидаемая ошибка и сообщение об ошибке выглядят следующим образом:

```bash
RuntimeError: Proxy error(CorruptOrDamagedFileException): Cannot convert. The file is corrupt or damaged. The document password is incorrect. ---> IncorrectPasswordException: The document password is incorrect.
```

### Explanation

1. **File Path Setup**: Указывается путь к документу, защищённому паролем. В этом примере предполагается, что документ называется `password-protected.docx`.

2. **Load Options**: Создаётся экземпляр [`WordProcessingLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/), и задаётся пароль, необходимый для открытия документа.

3. **Converter Initialization**: Создаётся экземпляр [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) с использованием пути к файлу и параметров загрузки, включающих пароль.

4. **Convert Options**: Для процесса конвертации создаётся экземпляр [`PdfConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/). При необходимости можно также задать пароль вывода для получаемого PDF.

4. **Conversion Execution**: Наконец, вызывается метод `convert` у экземпляра [`Converter`](/conversion/python-net/groupdocs.conversion/converter/), чтобы конвертировать документ, защищённый паролем, и сохранить его как PDF.

### Conclusion

Этот пример демонстрирует, как эффективно загружать и конвертировать документы, защищённые паролем, с помощью API GroupDocs.Conversion для Python. Убедитесь, что перед выполнением кода заменили пароли и пути к файлам на фактические значения.
