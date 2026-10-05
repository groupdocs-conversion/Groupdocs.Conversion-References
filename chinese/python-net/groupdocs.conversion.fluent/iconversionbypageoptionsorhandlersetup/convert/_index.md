---
title: "convert 方法"
second_title: "适用于 Python 的 GroupDocs.Conversion via .NET API 参考"
description: "执行转换链。"
type: docs
url: /zh/python-net/groupdocs.conversion.fluent/iconversionbypageoptionsorhandlersetup/convert/
is_root: false
weight: 1030
---


## convert

执行转换链。

```python
def convert(self):
    ...
```

### 示例

```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

def convert_document():
    # 打开源文档
    with Converter("./business-plan.docx") as converter:
        # 为 PDF 输出定义转换选项
        pdf_options = PdfConvertOptions()
        # 执行转换并保存结果
        converter.convert("./business-plan.pdf", pdf_options)

if __name__ == "__main__":
    convert_document()
```

### 另见
* class [`IConversionByPageOptionsOrHandlerSetup`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypageoptionsorhandlersetup/)
