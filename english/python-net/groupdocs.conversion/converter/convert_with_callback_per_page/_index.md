---
title: convert_with_callback_per_page method
second_title: GroupDocs.Conversion for Python via .NET API References
description: 
type: docs
url: /conversion/python-net/groupdocs.conversion/converter/convert_with_callback_per_page/
is_root: false
weight: 1050
---


## convert_with_callback_per_page {#convert_options-callback}

Converts the source document and saves the converted document page by page.

Learn more

- More about document conversion basic scenarios: https://docs.groupdocs.com/display/conversionnet/Convert+document
- Conversion use cases, advanced settings and customizations: https://docs.groupdocs.com/display/conversionnet/Converting

```python
def convert_with_callback_per_page(self, convert_options, callback):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| convert_options | `ConvertOptions` | GroupDocs.Conversion.ConvertOptions – The convert options specific to desired target file type. |
| callback | `System.Action`1[[GroupDocs.Conversion.ConvertedPageContext, GroupDocs.Conversion, Version=26.3.0.0, Culture=neutral, PublicKeyToken=716fcc553a201e56]]` |  |

### See Also
* class [`Converter`](/conversion/python-net/groupdocs.conversion/converter/)
