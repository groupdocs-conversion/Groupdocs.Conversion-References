---
title: "ドキュメントを複数ページのファイルに変換"
linkTitle: "Convert Document To Multiple"
second_title: "GroupDocs.Conversion for Python via .NET API リファレンス"
description: "id: convert-document-to-multiple-page-files"
type: docs
url: /ja/python-net/guides/convert-document-to-multiple-page-files/
is_root: false
weight: 60
---


---
id: convert-document-to-multiple-page-files
url: conversion/python-net/developer-guide/converting-documents/convert-document-to-multiple-page-files
title: ドキュメントを複数ページのファイルに変換
linkTitle: 複数ファイルに変換
weight: 3
description: "マルチページ文書の各ページを個別の出力ファイルにレンダリングします — page_number をループし、pages_count=1 と Converter.convert() を使用して、GroupDocs.Conversion for Python via .NET でページごとに PNG、PDF、または画像を生成します。"
keywords: 複数ファイルへの変換, ページ単位の出力, page_number, pages_count, ページループ, プレゼンテーションページの変換, PDFページをPNGに変換, ImageConvertOptions, GroupDocs.Conversion, python
productName: GroupDocs.Conversion for Python via .NET
hideChildren: false
toc: true
---

このドキュメントトピックは、単一のマルチページ文書を個別のページファイルに変換する方法をカバーしています。以下の図は、マルチページファイルを別々のページに変換するプロセスを示しています：

flowchart LR
%% Nodes
A[\"入力文書\"]
B[\"Conversion\"]
C[\"変換ページ 1\"]
D[\"変換ページ 2\"]
E[\"変換ページ N\"]

%% Edge connections between nodes
A --> B --> C
B --> D
B --> E

ドキュメントをページ単位のファイルに変換するには、サポートされている [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/) クラスの `page_number` と `pages_count` 属性と共に、`Converter.convert(file_path, convert_options)` メソッドを使用します：

- **`page_number`**: One-based index of the first page to convert.
- **`pages_count`**: Number of consecutive pages to convert starting from `page_number`.

ページごとに1つの出力ファイルを生成するには、`1` から `converter.get_document_info().pages_count` までループし、各イテレーションで `page_number` を更新して別々の出力パスに書き込みます。`pages_count = 1` を設定すると、各呼び出しで単一ページが出力されます。

## Supported ConvertOptions Classes

以下の [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/) クラスは、このトピックで使用される `page_number` と `pages_count` 属性を公開しています：

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

## Example 1: Convert All Pages of a Document and Save Output to a Folder

以下の例は、PPTX プレゼンテーションの各スライドを PNG 画像に変換し、出力画像を指定フォルダーに保存する方法を示しています。
 
出力ファイルのファイル名テンプレートは `converted-page-{page number}.{output file extension}` です。この例では、最初のスライドは `converted-page-1.png` として保存されます。

{{< tabs "example-1">}}
{{< tab \"convert_all_document_pages.py\" >}}
```python
import os
from groupdocs.conversion import Converter
from groupdocs.conversion.filetypes import ImageFileType
from groupdocs.conversion.options.convert import ImageConvertOptions

def convert_all_document_pages():
    output_folder = "./converted-pages"
    os.makedirs(output_folder, exist_ok=True)

    # 入力ドキュメントで Converter をインスタンス化します
    with Converter("./basic-presentation.pptx") as converter:
        # ソースドキュメントの総ページ数を決定する
        pages_count = converter.get_document_info().pages_count

        # 変換オプションを一度インスタンス化し、ループ内で再利用します
        png_convert_options = ImageConvertOptions()
        png_convert_options.format = ImageFileType.PNG
        png_convert_options.pages_count = 1

        # 各ページを個別の PNG ファイルに変換する
        for page_number in range(1, pages_count + 1):
            png_convert_options.page_number = page_number
            output_file = os.path.join(output_folder, f"converted-page-{page_number}.png")
            converter.convert(output_file, png_convert_options)

if __name__ == "__main__":
    convert_all_document_pages()
```
{{< /tab >}}
{{< tab \"basic-presentation.pptx\" >}}

`basic-presentation.pptx` はこの例で使用されるサンプルファイルです。ダウンロードするには [here](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/convert-document-to-multiple-page-files/basic-presentation.pptx) をクリックしてください。

{{< /tab >}}
{{< tab \"convert-all-document-pages-outputs.zip\" >}}
```text
converted-pages/converted-page-1.png (26 KB)
converted-pages/converted-page-10.png (81 KB)
converted-pages/converted-page-11.png (67 KB)
converted-pages/converted-page-12.png (70 KB)
converted-pages/converted-page-13.png (36 KB)
converted-pages/converted-page-2.png (34 KB)
converted-pages/converted-page-3.png (797 KB)
converted-pages/converted-page-4.png (1262 KB)
converted-pages/converted-page-5.png (75 KB)
converted-pages/converted-page-6.png (33 KB)
[TRUNCATED] (13 files total)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/converting-documents/convert-document-to-multiple-page-files/convert_all_document_pages/convert-all-document-pages-outputs.zip)
{{< /tab >}}
{{< /tabs >}}

## Example 2: Convert a Specific Page and Save Output to a File

ドキュメントページ数の取得方法を確認するには、[Getting Document Information]() ドキュメントトピックをご覧ください。

以下の例は、PPTX プレゼンテーションの特定のスライドを変換し、別ファイルとして保存する方法を示しています。

{{< tabs "example-2">}}
{{< tab \"convert_specific_document_page_to_file.py\" >}}
```python
from groupdocs.conversion import Converter
from groupdocs.conversion.filetypes import ImageFileType
from groupdocs.conversion.options.convert import ImageConvertOptions

def convert_specific_document_page_to_file():
    # 入力ドキュメントで Converter をインスタンス化します
    with Converter("./basic-presentation.pptx") as converter:
        # 変換オプションをインスタンス化する
        png_convert_options = ImageConvertOptions()
        # 出力形式を PNG に設定します
        png_convert_options.format = ImageFileType.PNG

        # 変換する単一ページを指定してください
        png_convert_options.page_number = 3
        png_convert_options.pages_count = 1

        # 変換されたページをファイルに保存します
        converter.convert("./slide-3.png", png_convert_options)

if __name__ == "__main__":
    convert_specific_document_page_to_file()
```
{{< /tab >}}
{{< tab \"basic-presentation.pptx\" >}}

`basic-presentation.pptx` はこの例で使用されるサンプルファイルです。ダウンロードするには [here](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/convert-document-to-multiple-page-files/basic-presentation.pptx) をクリックしてください。

{{< /tab >}}
{{< tab \"slide-3.png\" >}}
```text
Binary file (PNG, 797 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/converting-documents/convert-document-to-multiple-page-files/convert_specific_document_page_to_file/slide-3.png)
{{< /tab >}}
{{< /tabs >}}

## Example 3: Convert a Specific Page and Load Output Into a Stream

ドキュメントページ数の取得方法を確認するには、[Getting Document Information]() ドキュメントトピックをご覧ください。

変換されたページをメモリ内バッファとして必要な場合（例：ファイルシステムに触れずに別の API に転送する場合）、まずページをファイルに変換し、次に `BytesIO` オブジェクトに読み込みます：

{{< tabs \"example-3\">}}
{{< tab \"convert_specific_document_page_to_stream.py\" >}}
```python
import io
from groupdocs.conversion import Converter
from groupdocs.conversion.filetypes import ImageFileType
from groupdocs.conversion.options.convert import ImageConvertOptions

def convert_specific_document_page_to_stream():
    page_number_to_convert = 5
    output_file = f"./slide-{page_number_to_convert}.png"

    # 入力ドキュメントで Converter をインスタンス化します
    with Converter("./basic-presentation.pptx") as converter:
        # 変換オプションをインスタンス化する
        png_convert_options = ImageConvertOptions()
        # 出力形式を PNG に設定します
        png_convert_options.format = ImageFileType.PNG

        # 変換する単一ページを指定してください
        png_convert_options.page_number = page_number_to_convert
        png_convert_options.pages_count = 1

        # ページを変換し、ディスク上のファイルに保存します
        converter.convert(output_file, png_convert_options)

    # 変換されたページをメモリ内ストリームにロードし、下流で使用できるようにします
    with open(output_file, "rb") as file_handle:
        page_stream = io.BytesIO(file_handle.read())

    # page_stream は現在 PNG バイトデータを保持しており、任意のコンシューマに渡すことができます
    print(f"Loaded {page_stream.getbuffer().nbytes} bytes into memory")

if __name__ == "__main__":
    convert_specific_document_page_to_stream()
```
{{< /tab >}}
{{< tab \"basic-presentation.pptx\" >}}

`basic-presentation.pptx` はこの例で使用されるサンプルファイルです。ダウンロードするには [here](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/convert-document-to-multiple-page-files/basic-presentation.pptx) をクリックしてください。

{{< /tab >}}
{{< tab \"slide-5.png\" >}}
```text
Binary file (PNG, 75 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/converting-documents/convert-document-to-multiple-page-files/convert_specific_document_page_to_stream/slide-5.png)
{{< /tab >}}
{{< /tabs >}}
