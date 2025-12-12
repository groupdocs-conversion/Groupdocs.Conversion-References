---
title: CsvLoadOptions class
second_title: GroupDocs.Conversion for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.conversion.options.load/csvloadoptions/
is_root: false
weight: 50
---

## CsvLoadOptions class

Options for loading Csv documents.



**Inheritance:** [`CsvLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions) → 
[`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions) → 
[`LoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/loadoptions) → 
[`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject)



The CsvLoadOptions type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/__init__/#) | Initializes new instance of [`CsvLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions) class. |


### Properties
| Property | Description |
| :- | :- |
| [format](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/format) | Input document file type. |
| [sheets](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/sheets) | Sheet name to convert |
| [sheet_indexes](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/sheet_indexes) | List of sheet indexes to convert.<br/>The indexes must be zero-based |
| [default_font](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/default_font) | Default font for spreadsheet document. The following font will be used if a font is missing. |
| [font_substitutes](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/font_substitutes) | Substitute specific fonts when converting spreadsheet document. |
| [show_grid_lines](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/show_grid_lines) | Show grid lines when converting Excel files. |
| [show_hidden_sheets](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/show_hidden_sheets) | Show hidden sheets when converting Excel files. |
| [one_page_per_sheet](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/one_page_per_sheet) | If OnePagePerSheet is true the content of the sheet will be converted to one page in the PDF document. Default value is true. |
| [optimize_pdf_size](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/optimize_pdf_size) | If True and converting to Pdf the conversion is optimized for better file size than print quality. |
| [convert_range](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/convert_range) | Convert specific range when converting to other than spreadsheet format. Example: "D1:F8". |
| [skip_empty_rows_and_columns](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/skip_empty_rows_and_columns) | Skips empty rows and columns when converting. Default is True. |
| [password](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/password) | Set password to unprotect protected document. |
| [hide_comments](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/hide_comments) | Hide comments. |
| [check_excel_restriction](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/check_excel_restriction) | Whether check restriction of excel file when user modify cells related objects. For example, excel does not allow inputting string value longer than 32K. When you input a value longer than 32K, if this property is true, you will get an Exception. If this property is false, we will accept your input string value as the cell's value so that later you can output the complete string value for other file formats such as CSV. However, if you have set such kind of value that is invalid for excel file format, you should not save the workbook as excel file format later. Otherwise there may be unexpected error for the generated excel file. |
| [culture_info](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/culture_info) | Get or set the system culture info at the time file is loaded, e.g. "en-US". |
| [all_columns_in_one_page_per_sheet](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/all_columns_in_one_page_per_sheet) | If AllColumnsInOnePagePerSheet is true, all column content of one sheet will output to only one page in result. The width of paper size of pagesetup will be invalid, and the other settings of pagesetup will still take effect. |
| [auto_fit_rows](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/auto_fit_rows) | Autofits all rows when converting |
| [columns_per_page](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/columns_per_page) | Split a worksheet into pages by columns. Default is 0, no pagination. |
| [rows_per_page](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/rows_per_page) | Split a worksheet into pages by rows. Default is 0, no pagination. |
| [convert_owner](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/convert_owner) | Implements [`IDocumentsContainerLoadOptions.convert_owner`](/conversion/python-net/groupdocs.conversion.contracts/idocumentscontainerloadoptions#convert_owner)<br/><br/>Default is true |
| [convert_owned](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/convert_owned) | Implements [`IDocumentsContainerLoadOptions.convert_owned`](/conversion/python-net/groupdocs.conversion.contracts/idocumentscontainerloadoptions#convert_owned)<br/><br/>Default is false |
| [depth](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/depth) | Implements [`IDocumentsContainerLoadOptions.depth`](/conversion/python-net/groupdocs.conversion.contracts/idocumentscontainerloadoptions#depth)<br/><br/>Default: 1 |
| [clear_built_in_document_properties](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/clear_built_in_document_properties) | Removes built-in metadata properties from the document. |
| [clear_custom_document_properties](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/clear_custom_document_properties) | Removes custom metadata properties from the document. |
| [separator](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/separator) | Delimiter of a Csv file. |
| [is_multi_encoded](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/is_multi_encoded) | True means the file contains several encodings. |
| [has_formula](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/has_formula) | Indicates whether text is formula if it starts with "=". |
| [convert_numeric_data](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/convert_numeric_data) | Indicates whether the string in the file is converted to numeric. Default is True. |
| [convert_date_time_data](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/convert_date_time_data) | Indicates whether the string in the file is converted to date. Default is True. |
| [encoding](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/encoding) | Encoding. Default is Encoding.Default. |


### Methods
| Method | Description |
| :- | :- |
| [equals](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/equals/#groupdocs.conversion.contracts.ValueObject) | Determines whether two object instances are equal. |
| [clone](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions/clone/#) | Clones current instance. |



### See Also
* module [`groupdocs.conversion.options.load`](..)
* class [`CsvLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/csvloadoptions)
* class [`LoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/loadoptions)
* class [`SpreadsheetLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/spreadsheetloadoptions)
* class [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject)
