---
title: TsvLoadOptions class
second_title: GroupDocs.Conversion for Python via .NET API References
description: 
type: docs
weight: 450
url: /python-net/groupdocs.conversion.options.load/tsvloadoptions/
is_root: false
---

## TsvLoadOptions class

Options for loading Tsv documents.



**Inheritance:** [`TsvLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/tsvloadoptions) → 
[`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions) → 
[`LoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/loadoptions) → 
[`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject)



The TsvLoadOptions type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.options.load/tsvloadoptions/__init__/#) | Initializes new instance of [`TsvLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/tsvloadoptions) class. |


### Properties
| Property | Description |
| :- | :- |
| [format](/conversion/python-net/groupdocs.conversion.options.load/tsvloadoptions/format) | Input document file type. |
| [sheets](/conversion/python-net/groupdocs.conversion.options.load/tsvloadoptions/sheets) | Sheet name to convert |
| [sheet_indexes](/conversion/python-net/groupdocs.conversion.options.load/tsvloadoptions/sheet_indexes) | List of sheet indexes to convert.<br/>The indexes must be zero-based |
| [default_font](/conversion/python-net/groupdocs.conversion.options.load/tsvloadoptions/default_font) | Default font for spreadsheet document. The following font will be used if a font is missing. |
| [font_substitutes](/conversion/python-net/groupdocs.conversion.options.load/tsvloadoptions/font_substitutes) | Substitute specific fonts when converting spreadsheet document. |
| [show_grid_lines](/conversion/python-net/groupdocs.conversion.options.load/tsvloadoptions/show_grid_lines) | Show grid lines when converting Excel files. |
| [show_hidden_sheets](/conversion/python-net/groupdocs.conversion.options.load/tsvloadoptions/show_hidden_sheets) | Show hidden sheets when converting Excel files. |
| [one_page_per_sheet](/conversion/python-net/groupdocs.conversion.options.load/tsvloadoptions/one_page_per_sheet) | If OnePagePerSheet is true the content of the sheet will be converted to one page in the PDF document. Default value is true. |
| [optimize_pdf_size](/conversion/python-net/groupdocs.conversion.options.load/tsvloadoptions/optimize_pdf_size) | If True and converting to Pdf the conversion is optimized for better file size than print quality. |
| [convert_range](/conversion/python-net/groupdocs.conversion.options.load/tsvloadoptions/convert_range) | Convert specific range when converting to other than spreadsheet format. Example: "D1:F8". |
| [skip_empty_rows_and_columns](/conversion/python-net/groupdocs.conversion.options.load/tsvloadoptions/skip_empty_rows_and_columns) | Skips empty rows and columns when converting. Default is True. |
| [password](/conversion/python-net/groupdocs.conversion.options.load/tsvloadoptions/password) | Set password to unprotect protected document. |
| [hide_comments](/conversion/python-net/groupdocs.conversion.options.load/tsvloadoptions/hide_comments) | Hide comments. |
| [check_excel_restriction](/conversion/python-net/groupdocs.conversion.options.load/tsvloadoptions/check_excel_restriction) | Whether check restriction of excel file when user modify cells related objects. For example, excel does not allow inputting string value longer than 32K. When you input a value longer than 32K, if this property is true, you will get an Exception. If this property is false, we will accept your input string value as the cell's value so that later you can output the complete string value for other file formats such as CSV. However, if you have set such kind of value that is invalid for excel file format, you should not save the workbook as excel file format later. Otherwise there may be unexpected error for the generated excel file. |
| [culture_info](/conversion/python-net/groupdocs.conversion.options.load/tsvloadoptions/culture_info) | Get or set the system culture info at the time file is loaded, e.g. "en-US". |
| [all_columns_in_one_page_per_sheet](/conversion/python-net/groupdocs.conversion.options.load/tsvloadoptions/all_columns_in_one_page_per_sheet) | If AllColumnsInOnePagePerSheet is true, all column content of one sheet will output to only one page in result. The width of paper size of pagesetup will be invalid, and the other settings of pagesetup will still take effect. |
| [auto_fit_rows](/conversion/python-net/groupdocs.conversion.options.load/tsvloadoptions/auto_fit_rows) | Autofits all rows when converting |
| [columns_per_page](/conversion/python-net/groupdocs.conversion.options.load/tsvloadoptions/columns_per_page) | Split a worksheet into pages by columns. Default is 0, no pagination. |
| [rows_per_page](/conversion/python-net/groupdocs.conversion.options.load/tsvloadoptions/rows_per_page) | Split a worksheet into pages by rows. Default is 0, no pagination. |
| [convert_owner](/conversion/python-net/groupdocs.conversion.options.load/tsvloadoptions/convert_owner) | Implements [`IDocumentsContainerLoadOptions.convert_owner`](/conversion/python-net/groupdocs.conversion.contracts/idocumentscontainerloadoptions#convert_owner)<br/><br/>Default is true |
| [convert_owned](/conversion/python-net/groupdocs.conversion.options.load/tsvloadoptions/convert_owned) | Implements [`IDocumentsContainerLoadOptions.convert_owned`](/conversion/python-net/groupdocs.conversion.contracts/idocumentscontainerloadoptions#convert_owned)<br/><br/>Default is false |
| [depth](/conversion/python-net/groupdocs.conversion.options.load/tsvloadoptions/depth) | Implements [`IDocumentsContainerLoadOptions.depth`](/conversion/python-net/groupdocs.conversion.contracts/idocumentscontainerloadoptions#depth)<br/><br/>Default: 1 |
| [clear_built_in_document_properties](/conversion/python-net/groupdocs.conversion.options.load/tsvloadoptions/clear_built_in_document_properties) | Removes built-in metadata properties from the document. |
| [clear_custom_document_properties](/conversion/python-net/groupdocs.conversion.options.load/tsvloadoptions/clear_custom_document_properties) | Removes custom metadata properties from the document. |


### Methods
| Method | Description |
| :- | :- |
| [equals](/conversion/python-net/groupdocs.conversion.options.load/tsvloadoptions/equals/#groupdocs.conversion.contracts.ValueObject) | Determines whether two object instances are equal. |
| [clone](/conversion/python-net/groupdocs.conversion.options.load/tsvloadoptions/clone/#) | Clones current instance. |



### See Also
* module [`groupdocs.conversion.options.load`](..)
* class [`LoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/loadoptions)
* class [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions)
* class [`TsvLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/tsvloadoptions)
* class [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject)
