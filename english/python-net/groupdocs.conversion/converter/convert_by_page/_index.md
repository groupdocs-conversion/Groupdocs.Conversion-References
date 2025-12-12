---
title: convert_by_page method
second_title: GroupDocs.Conversion for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.conversion/converter/convert_by_page/
is_root: false
weight: 30
---

## convert_by_page {#System.String-groupdocs.conversion.options.convert.ConvertOptions}

Converts source document. Saves the converted document page by page.



```python
def convert_by_page(self, output_folder, convert_options):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| output_folder | System.String | Output folder to save converted pages. File name template is converted-page-{0}.ext. |
| convert_options | groupdocs.conversion.options.convert.ConvertOptions | The convert options specific to desired target file type. |


## convert_by_page {#System.String-int-groupdocs.conversion.options.convert.ConvertOptions}

Converts source document. Saves the converted document page to a stream



```python
def convert_by_page(self, file_path, page_number, convert_options):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| file_path | System.String | Output file path. |
| page_number | int | Page number to convert. |
| convert_options | groupdocs.conversion.options.convert.ConvertOptions | The convert options specific to desired target file type. |


## convert_by_page {#io.RawIOBase-int-groupdocs.conversion.options.convert.ConvertOptions}

Converts source document. Saves the converted document page to a stream



```python
def convert_by_page(self, page_stream, page_number, convert_options):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| page_stream | io.RawIOBase | Output page stream. |
| page_number | int | Page number to convert. |
| convert_options | groupdocs.conversion.options.convert.ConvertOptions | The convert options specific to desired target file type. |



### See Also
* module [`groupdocs.conversion`](../../)
* class [`Converter`](/conversion/python-net/groupdocs.conversion/converter)
