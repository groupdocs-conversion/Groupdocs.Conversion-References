---
title: "ドキュメントを別の形式に変換する"
linkTitle: "Convert to Another Format"
second_title: "GroupDocs.Conversion for Python via .NET API リファレンス"
description: "単一のドキュメントをある形式から別の形式へ変換します。必要に応じて、ConvertOptions の pages / page_number / pages_count 属性を使用して特定のページやページ範囲を選択できます（GroupDocs.Conversion for Python via .NET）。"
type: docs
url: /ja/python-net/guides/convert-document-to-another-format/
is_root: false
weight: 40
---


このドキュメントトピックは、単一のドキュメントを別の形式に変換することを扱い、出力として1つのドキュメントのみが生成されます。以下の図は、ファイルをある形式から別の形式へ変換するプロセスを示しています：

flowchart LR
%% Nodes
A[\"Input Document (e.g. DOCX)\"]
B[\"Conversion\"]
C[\"Converted Document (e.g. PDF)\"]

%% Edge connections between nodes
A --> B --> C

ドキュメントを変換して保存するには、以下の [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) クラスメソッドを使用してください：

- **`convert(file_path, convert_options)`**: Converts a document to a specified single output format and saves it to a file, such as converting a DOCX to PDF.
- **`convert(stream, convert_options)`**: Converts the document and writes it to a provided stream instead of a file path.

## Convert a Complete Document 

以下の [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/) クラスのリストを使用して、ドキュメントを特定の単一出力形式に変換できます：

- **PdfConvertOptions** – Options for converting to [PDF]() format.
- **WordProcessingConvertOptions** – Options for converting to [Word Processing]() formats.
- **SpreadsheetConvertOptions** – Options for converting to [Spreadsheet]() formats.
- **PresentationConvertOptions** – Options for converting to [Presentation]() formats.
- **ImageConvertOptions** – Options for converting to [Image]() formats (e.g., PNG, JPEG).
- **WebConvertOptions** – Options for converting to [Web]() formats (e.g., HTML).
- **PageDescriptionLanguageConvertOptions** – Options for converting to [Page Description Language]() formats (e.g., PostScript).
- **EBookConvertOptions** – Options for converting to [EBook]() formats (e.g., EPUB, MOBI).
- **EmailConvertOptions** – Options for converting to [Email]() formats (e.g., EML, MSG).
- **DiagramConvertOptions** – Options for converting to [Diagram]() formats (e.g., VSDX).
- **CadConvertOptions** – Options for converting to [CAD]() formats (e.g., DWG).
- **ThreeDConvertOptions** – Options for converting to [3D]() formats.
- **ProjectManagementConvertOptions** – Options for converting to [Project Management]() formats (e.g., MPP).
- **GisConvertOptions** – Options for converting to [GIS]() formats.
- **FontConvertOptions** – Options for converting to [Font]() formats (e.g., TTF, OTF).
- **FinanceConvertOptions** – Options for converting to [Finance]() formats (e.g., XBRL).
- **CompressionConvertOptions** – Options for converting to [Compression]() formats (e.g., ZIP).
- **NoConvertOptions** – A special option class that instructs the converter to copy the source document without any modifications.

### Example 1: Convert a Document to Another Format

以下の例は、DOCX ファイルを PDF に変換する方法を示しています：

{{< tabs "example-1">}}
{{< tab "convert_document_to_another_format.py" >}}
```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

def convert_document_to_another_format():
    # 入力ドキュメントで Converter をインスタンス化します 
    with Converter("./business-plan.docx") as converter:
        # 出力形式を定義するために ConvertOptions をインスタンス化します
        pdf_convert_options = PdfConvertOptions()
        
        # 入力ドキュメントを PDF に変換します
        converter.convert("./business-plan.pdf", pdf_convert_options)    

if __name__ == "__main__":
    convert_document_to_another_format()
```
{{< /tab >}}
{{< tab "business-plan.docx" >}}

`business-plan.docx` はこの例で使用されるサンプルファイルです。ダウンロードするには [here](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/convert-document-to-another-format/business-plan.docx) をクリックしてください。

{{< /tab >}}
{{< tab "business-plan.pdf" >}}
```text
Binary file (PDF, 283 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/converting-documents/convert-document-to-another-format/convert_document_to_another_format/business-plan.pdf)
{{< /tab >}}
{{< /tabs >}}

### Example 2: Specify Output Format

デフォルトでは、各 [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/) クラスはそれぞれ固有のデフォルトターゲット形式を持ちます。例えば、[WordProcessingConvertOptions](https://reference.groupdocs.com/conversion/python-net/groupdocs.conversion.options.convert/wordprocessingconvertoptions/) のデフォルト出力形式は [DOCX](https://reference.groupdocs.com/conversion/python-net/groupdocs.conversion.filetypes/wordprocessingfiletype/docx/) です。

フォーマットファミリー内で別の出力形式を設定するには、`format` プロパティを使用します。以下の例は、`DOCX` ファイルを変換する際にターゲット形式を `TXT` と指定する方法を示しています：

{{< tabs "example-2">}}
{{< tab "specify_output_format.py" >}}
```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import WordProcessingConvertOptions
from groupdocs.conversion.filetypes import WordProcessingFileType

def specify_output_format():
    # 入力ドキュメントで Converter をインスタンス化します 
    with Converter("./business-plan.docx") as converter:
        # 出力形式を定義するために ConvertOptions をインスタンス化します。デフォルトでは DOCX です
        word_convert_options = WordProcessingConvertOptions()
        # フォーマットファミリ内の出力形式を DOCX から TXT に変更します
        word_convert_options.format = WordProcessingFileType.TXT
        
        # 入力ドキュメントを TXT に変換します
        converter.convert("./business-plan.txt", word_convert_options)    

if __name__ == "__main__":
    specify_output_format()
```
{{< /tab >}}
{{< tab "business-plan.docx" >}}

`business-plan.docx` はこの例で使用されるサンプルファイルです。ダウンロードするには [here](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/convert-document-to-another-format/business-plan.docx) をクリックしてください。

{{< /tab >}}
{{< tab "business-plan.txt" >}}
```text
﻿HOME BASED

PROFESSIONAL SERVICES

Business Plan

[TRUNCATED]
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/converting-documents/convert-document-to-another-format/specify_output_format/business-plan.txt)
{{< /tab >}}
{{< /tabs >}}

## Specify Document Pages to Convert

ドキュメントページ数の取得方法を確認するには、[Getting Document Information]() ドキュメントトピックをご覧ください。

特定のドキュメントページを変換するには、以下の [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/) クラスを使用できます。このクラスは `pages`、`page_number`、`pages_count` 属性を提供します。これらのオプションを使用して、個々のページまたはページ範囲を指定して変換できます。

- **PdfConvertOptions** – Options for converting to [PDF]() format.
- **ImageConvertOptions** – Options for converting to [Image]() formats (e.g., PNG, JPEG).
- **WordProcessingConvertOptions** – Options for converting to [Word Processing]() formats.
- **SpreadsheetConvertOptions** – Options for converting to [Spreadsheet]() formats.
- **PresentationConvertOptions** – Options for converting to [Presentation]() formats.
- **WebConvertOptions** – Options for converting to [Web]() formats (e.g., HTML).
- **EBookConvertOptions** – Options for converting to [EBook]() formats (e.g., EPUB, MOBI).
- **DiagramConvertOptions** – Options for converting to [Diagram]() formats (e.g., VSDX).
- **PageDescriptionLanguageConvertOptions** – Options for converting to [Page Description Language]() formats (e.g., PostScript).
- **CadConvertOptions** – Options for converting to [CAD]() formats (e.g., DWG).
- **ThreeDConvertOptions** – Options for converting to [3D]() formats.
- **FinanceConvertOptions** – Options for converting to [Finance]() formats (e.g., XBRL).

### Example 1: Convert Specific Document Pages to Another Format

以下の例のように、変換したいドキュメントページを指定できます。

{{< tabs \"example-3\">}}
{{< tab \"convert_specific_document_pages.py\" >}}
```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

def convert_specific_document_pages():
    # 入力ドキュメントで Converter をインスタンス化します 
    with Converter("./business-plan.docx") as converter:
        # 出力形式を定義するために ConvertOptions をインスタンス化します
        pdf_convert_options = PdfConvertOptions()
        # 変換するドキュメントページを指定してください
        pdf_convert_options.pages = [1, 3, 5]

        # 入力ドキュメントの指定されたページを PDF に変換します
        converter.convert("./pages-1-3-5.pdf", pdf_convert_options)    

if __name__ == "__main__":
    convert_specific_document_pages()
```
{{< /tab >}}
{{< tab "business-plan.docx" >}}

`business-plan.docx` はこの例で使用されるサンプルファイルです。ダウンロードするには [here](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/convert-document-to-another-format/business-plan.docx) をクリックしてください。

{{< /tab >}}
{{< tab \"pages-1-3-5.pdf\" >}}
```text
Binary file (PDF, 156 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/converting-documents/convert-document-to-another-format/convert_specific_document_pages/pages-1-3-5.pdf)
{{< /tab >}}
{{< /tabs >}}

### Example 2: Convert N Consecutive Pages

代替として、以下の例のように連続するページ数を指定して変換することもできます。

{{< tabs \"example-4\">}}
{{< tab \"convert_consecutive_document_pages.py\" >}}
```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

def convert_consecutive_document_pages():
    # 入力ドキュメントで Converter をインスタンス化します 
    with Converter("./business-plan.docx") as converter:
        # 出力形式を定義するために ConvertOptions をインスタンス化します
        pdf_convert_options = PdfConvertOptions()
        # 変換する開始ページとページ数を指定してください
        pdf_convert_options.page_number = 1
        pdf_convert_options.pages_count = 5

        # ドキュメント内の指定されたページ範囲を PDF に変換します
        converter.convert("./pages-1-through-5.pdf", pdf_convert_options)    

if __name__ == "__main__":
    convert_consecutive_document_pages()
```
{{< /tab >}}
{{< tab "business-plan.docx" >}}

`business-plan.docx` はこの例で使用されるサンプルファイルです。ダウンロードするには [here](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/convert-document-to-another-format/business-plan.docx) をクリックしてください。

{{< /tab >}}
{{< tab \"pages-1-through-5.pdf\" >}}
```text
Binary file (PDF, 216 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/converting-documents/convert-document-to-another-format/convert_consecutive_document_pages/pages-1-through-5.pdf)
{{< /tab >}}
{{< /tabs >}}
