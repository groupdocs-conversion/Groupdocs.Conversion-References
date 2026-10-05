---
title: "加载受密码保护的文件"
linkTitle: "Load Password-Protected File"
second_title: "适用于 Python 的 GroupDocs.Conversion via .NET API 参考"
description: "通过向 GroupDocs.Conversion for Python via .NET 中的 Converter 构造函数传递带有 password 属性的 LoadOptions 实例，解锁并转换受密码保护的 Word、Excel、PowerPoint 和 PDF 文档。"
type: docs
url: /zh/python-net/guides/load-password-protected-file/
is_root: false
weight: 100
---


使用 *GroupDocs.Conversion for Python via .NET*，您可以加载并转换受密码保护的文档。当您需要处理需要身份验证才能访问其内容的文档时，此功能非常有用。

要加载并转换受密码保护的文档，请按照下面代码示例中概述的步骤进行：

{{< tabs \"code-example\">}}
{{< tab \"load_password_protected_file.py\" >}}
```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions
from groupdocs.conversion.options.load import WordProcessingLoadOptions

def load_password_protected_file():
    # 设置文件路径
    file_path = "./password-protected.docx"
    
    # 实例化加载选项并设置密码
    wp_load_options = WordProcessingLoadOptions()
    wp_load_options.password = "12345"

    # 指定源文件流和加载选项
    converter = Converter(file_path, wp_load_options)
    
    # 指定输出文件位置和转换选项
    output_path = "./password-protected.pdf"
    pdf_convert_options = PdfConvertOptions()
    pdf_convert_options.password = "67890"

    # 转换并保存到输出路径
    converter.convert(output_path, pdf_convert_options)

if __name__ == "__main__":
    load_password_protected_file()

```
{{< /tab >}}
{{< tab \"password-protected.docx\" >}}

`password-protected.docx` 是本示例中使用的示例文件。点击 [here](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/loading-documents/load-password-protected-file/password-protected.docx) 下载。

{{< /tab >}}
{{< tab \"password-protected.pdf\" >}}
```text
Binary file (PDF, 234 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/loading-documents/load-password-protected-file/load_password_protected_file/password-protected.pdf)
{{< /tab >}}
{{< /tabs >}}

如果提供的密码不正确，将抛出运行时错误。预期的错误及错误信息如下：

```bash
RuntimeError: Proxy error(CorruptOrDamagedFileException): Cannot convert. The file is corrupt or damaged. The document password is incorrect. ---> IncorrectPasswordException: The document password is incorrect.
```

### Explanation

1. **File Path Setup**: 已指定受密码保护的文档的文件路径。在本示例中，假设文档名为 `password-protected.docx`。

2. **Load Options**: 已创建 [`WordProcessingLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/) 的实例，并设置打开文档所需的密码。

3. **Converter Initialization**: 使用文件路径和包含密码的加载选项创建了 [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) 实例。

4. **Convert Options**: 为转换过程创建了 [`PdfConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/) 的实例。如果需要，您还可以为生成的 PDF 设置输出密码。

4. **Conversion Execution**: 最后，在 [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) 实例上调用 `convert` 方法，将受密码保护的文档转换并保存为 PDF。

### Conclusion

本示例演示了如何使用 GroupDocs.Conversion for Python API 高效加载和转换受密码保护的文档。请在执行代码前将密码和文件路径替换为实际值。
