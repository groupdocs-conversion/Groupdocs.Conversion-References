---
title: "クイックスタートガイド"
linkTitle: "Quick Start Guide"
second_title: "GroupDocs.Conversion for Python via .NET API リファレンス"
description: "仮想環境を設定し、groupdocs-conversion-net をインストールして、3 つの最小例（DOCX → PDF、PDF → ページごとの PNG、ZIP → 統合 PDF）を 5 分以内に実行します。"
type: docs
url: /ja/python-net/guides/quick-start-guide/
is_root: false
weight: 20
---


このガイドは、.NET 経由で GroupDocs.Conversion for Python をセットアップし使用開始する方法の概要を簡潔に示します。このライブラリにより、開発者は最小限の設定でさまざまなファイル形式（例：DOCX、PDF、PNG）間の変換が可能になります。

## Prerequisites

続行するには、以下が揃っていることを確認してください：

1. **Configured** 環境（[System Requirements]() トピックで説明されている通り）
2. **Optionally** すべての製品機能をテストするために、[Get a Temporary License](https://purchase.groupdocs.com/temporary-license/) を取得できます。

## Set Up Your Development Environment

ベストプラクティスとして、Python アプリケーションの依存関係を管理するために仮想環境を使用してください。仮想環境の詳細は、[Create and Use Virtual Environments](https://packaging.python.org/en/latest/guides/installing-using-pip-and-virtual-environments/#create-and-use-virtual-environments) のドキュメントトピックをご覧ください。

### Create and Activate a Virtual Environment

仮想環境を作成します：

{{< tabs \"example1\">}}
{{< tab \"Windows\" >}}
```ps
py -m venv .venv
```
{{< /tab >}}
{{< tab \"Linux\" >}}
```bash
python3 -m venv .venv
```
{{< /tab >}}
{{< tab \"macOS\" >}}
```bash
python3 -m venv .venv
```
{{< /tab >}}
{{< /tabs >}}

仮想環境を有効化します：

{{< tabs \"example2\">}}
{{< tab \"Windows\" >}}
```ps
.venv\Scripts\activate
```
{{< /tab >}}
{{< tab \"Linux\" >}}
```bash
source .venv/bin/activate
```
{{< /tab >}}
{{< tab \"macOS\" >}}
```bash
source .venv/bin/activate
```
{{< /tab >}}
{{< /tabs >}}

### Install `groupdocs-conversion-net` Package

仮想環境を有効化した後、ターミナルで以下のコマンドを実行してパッケージの最新バージョンをインストールしてください：

{{< tabs \"example3\">}}
{{< tab \"Windows\" >}}
```ps
py -m pip install groupdocs-conversion-net
```
{{< /tab >}}
{{< tab \"Linux\" >}}
```bash
python3 -m pip install groupdocs-conversion-net
```
{{< /tab >}}
{{< tab \"macOS\" >}}
```bash
python3 -m pip install groupdocs-conversion-net
```
{{< /tab >}}
{{< /tabs >}}

パッケージが正常にインストールされたことを確認してください。メッセージが表示されます。

```bash
Successfully installed groupdocs-conversion-net-*
```

## Example 1: Convert document

ライブラリをすぐにテストするために、DOCX ファイルを PDF に変換しましょう。また、作成するアプリを [here](https://docs.groupdocs.com/conversion/python-net/_sample_files/getting-started/quick-start-guide/convert_docx_to_pdf.zip) からダウンロードできます。

{{< tabs \"demo_app_convert_docx_to_pdf\">}}
{{< tab "convert_docx_to_pdf.py" >}}
```python
import os
from groupdocs.conversion import License, Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

def convert_docx_to_pdf():
    # ライセンスファイルの絶対パスを取得する
    license_path = os.path.abspath("./GroupDocs.Conversion.lic")

    if os.path.exists(license_path):
        # ライセンスを作成し、パスを設定する
        license = License()
        license.set_license(license_path)

    # DOCX ファイルを読み込む
    with Converter("./business-plan.docx") as converter:
        # 変換オプションを作成する
        pdf_convert_options = PdfConvertOptions()

        # DOCX を PDF に変換する
        converter.convert("./business-plan.pdf", pdf_convert_options)    

if __name__ == "__main__":
    convert_docx_to_pdf()
```
{{< /tab >}}
{{< tab "business-plan.docx" >}}

`business-plan.docx` はこの例で使用されるサンプルファイルです。ダウンロードするには [ここ](https://docs.groupdocs.com/conversion/python-net/_sample_files/getting-started/quick-start-guide/business-plan.docx) をクリックしてください。

{{< /tab >}}
{{< tab "business-plan.pdf" >}}
```text
Binary file (PDF, 283 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/getting-started/quick-start-guide/convert_docx_to_pdf/business-plan.pdf)
{{< /tab >}}
{{< /tabs >}}

フォルダー構造は以下のディレクトリ構成と同様になるはずです：

```Directory
📂 demo-app
 ├──convert_docx_to_pdf.py
 ├──business-plan.docx
 └──GroupDocs.Conversion.lic (Optionally)
```

### Run the App

{{< tabs "run-the-app">}}
{{< tab \"Windows\" >}}
```ps
py convert_docx_to_pdf.py
```
{{< /tab >}}
{{< tab \"Linux\" >}}
```bash
python3 convert_docx_to_pdf.py
```
{{< /tab >}}
{{< tab \"macOS\" >}}
```bash
python3 convert_docx_to_pdf.py
```
{{< /tab >}}
{{< /tabs >}}

アプリを実行した後、`deactivate` を実行するかシェルを閉じることで仮想環境を無効化できます。

### Explanation
- `Converter("./business-plan.docx")`: Initializes the converter with the DOCX file.
- `PdfConvertOptions()`: Specifies the output format as PDF.
- `converter.convert("./business-plan.pdf", pdf_convert_options)`: Converts the DOCX file to PDF and saves it as `business-plan.pdf`.

## Example 2: Convert document pages

この例では PDF ドキュメントのページを PNG に変換します。作成するアプリは [ここ](https://docs.groupdocs.com/conversion/python-net/_sample_files/getting-started/quick-start-guide/convert_pdf_pages_to_png.zip) からダウンロードできます。

{{< tabs "demo_app_convert_pdf_pages_to_png">}}
{{< tab "convert_pdf_pages_to_png.py" >}}
```python
import os
from groupdocs.conversion import License, Converter
from groupdocs.conversion.filetypes import ImageFileType
from groupdocs.conversion.options.convert import ImageConvertOptions

def convert_pdf_pages_to_png():
    # ライセンスファイルの絶対パスを取得する
    license_path = os.path.abspath("./GroupDocs.Conversion.lic")

    if os.path.exists(license_path):
        # ライセンスを作成し、パスを設定する
        license = License()
        license.set_license(license_path)

    output_folder = "./converted-pages"
    os.makedirs(output_folder, exist_ok=True)

    # PDF ドキュメントを読み込む
    with Converter("./annual-review.pdf") as converter:
        # ソースドキュメントの総ページ数を決定する
        pages_count = converter.get_document_info().pages_count

        # 変換オプションを作成し、ループ内で再利用する
        png_convert_options = ImageConvertOptions()
        png_convert_options.format = ImageFileType.PNG
        png_convert_options.pages_count = 1

        # 各ページを個別の PNG ファイルに変換する
        for page_number in range(1, pages_count + 1):
            png_convert_options.page_number = page_number
            output_file = os.path.join(output_folder, f"converted-page-{page_number}.png")
            converter.convert(output_file, png_convert_options)

if __name__ == "__main__":
    convert_pdf_pages_to_png()
```
{{< /tab >}}
{{< tab "annual-review.pdf" >}}

`annual-review.pdf` はこの例で使用されるサンプルファイルです。ダウンロードするには [ここ](https://docs.groupdocs.com/conversion/python-net/_sample_files/getting-started/quick-start-guide/annual-review.pdf) をクリックしてください。

{{< /tab >}}
{{< tab "convert-pdf-pages-to-png-outputs.zip" >}}
```text
converted-pages/converted-page-1.png (1148 KB)
converted-pages/converted-page-2.png (89 KB)
converted-pages/converted-page-3.png (83 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/getting-started/quick-start-guide/convert_pdf_pages_to_png/convert-pdf-pages-to-png-outputs.zip)
{{< /tab >}}
{{< /tabs >}}

フォルダー構造は以下のディレクトリ構成と同様になるはずです：

```Directory
📂 demo-app
 ├──annual-review.pdf
 ├──convert_pdf_pages_to_png.py
 └──GroupDocs.Conversion.lic (Optionally)
```

### Run the App

{{< tabs "run_the_app_convert_pdf_pages_to_png">}}
{{< tab \"Windows\" >}}
```ps
py convert_pdf_pages_to_png.py
```
{{< /tab >}}
{{< tab \"Linux\" >}}
```bash
python3 convert_pdf_pages_to_png.py
```
{{< /tab >}}
{{< tab \"macOS\" >}}
```bash
python3 convert_pdf_pages_to_png.py
```
{{< /tab >}}
{{< /tabs >}}

アプリを実行した後、`deactivate` を実行するかシェルを閉じることで仮想環境を無効化できます。

### Explanation
- `Converter("./annual-review.pdf")`: Initializes the converter with the PDF file.
- `converter.get_document_info().pages_count`: Retrieves the total number of pages in the source document.
- `ImageConvertOptions()` with `format = ImageFileType.PNG`: Specifies the output format as PNG image.
- The loop updates `png_convert_options.page_number` on each iteration (with `pages_count = 1`) and calls `converter.convert(...)` to write one PNG file per page into the `converted-pages` folder.

## Example 3: Convert files in archive

この例では ZIP アーカイブの内容を PDF に変換します。GroupDocs.Conversion はアーカイブを開き、内部のファイルを変換し、変換されたすべてのドキュメントを含む単一の統合 PDF を生成します。作成するアプリは [ここ](https://docs.groupdocs.com/conversion/python-net/_sample_files/getting-started/quick-start-guide/convert_files_in_archive.zip) からダウンロードできます。

{{< tabs "demo_app_convert_files_in_archive">}}
{{< tab "convert_files_in_archive.py" >}}
```python
import os
from groupdocs.conversion import License, Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

def convert_files_in_archive():
    # ライセンスファイルの絶対パスを取得する
    license_path = os.path.abspath("./GroupDocs.Conversion.lic")

    if os.path.exists(license_path):
        # ライセンスを作成し、パスを設定する
        license = License()
        license.set_license(license_path)

    # ZIP ファイルを読み込む
    with Converter("./compressed.zip") as converter:
        # 変換オプションを作成する
        pdf_convert_options = PdfConvertOptions()

        # アーカイブを抽出し、内容を変換して、統合 PDF として保存する
        converter.convert("./converted.pdf", pdf_convert_options)

if __name__ == "__main__":
    convert_files_in_archive()
```
{{< /tab >}}
{{< tab "compressed.zip" >}}

`compressed.zip` はこの例で使用されるサンプルファイルです。ダウンロードするには [ここ](https://docs.groupdocs.com/conversion/python-net/_sample_files/getting-started/quick-start-guide/compressed.zip) をクリックしてください。

{{< /tab >}}
{{< tab "converted.pdf" >}}
```text
Binary file (PDF, 283 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/getting-started/quick-start-guide/convert_files_in_archive/converted.pdf)
{{< /tab >}}
{{< /tabs >}}

フォルダー構造は以下のディレクトリ構成と同様になるはずです：

```Directory
📂 demo-app
 ├──compressed.zip
 ├──convert_files_in_archive.py
 └──GroupDocs.Conversion.lic (Optionally)
```

### Run the App

{{< tabs "run_the_app_convert_files_in_archive">}}
{{< tab \"Windows\" >}}
```ps
py convert_files_in_archive.py
```
{{< /tab >}}
{{< tab \"Linux\" >}}
```bash
python3 convert_files_in_archive.py
```
{{< /tab >}}
{{< tab \"macOS\" >}}
```bash
python3 convert_files_in_archive.py
```
{{< /tab >}}
{{< /tabs >}}

アプリを実行した後、`deactivate` を実行するかシェルを閉じることで仮想環境を無効化できます。

### Explanation
- `Converter("./compressed.zip")`: Initializes the converter with the ZIP file.
- `PdfConvertOptions()`: Specifies the output format as PDF.
- `converter.convert("./converted.pdf", pdf_convert_options)`: Extracts the archive, converts its contents, and writes a single consolidated PDF to `converted.pdf`.

## Next Steps

基本を完了したら、使用を拡張するための追加リソースを探しましょう：
- [Supported File Formats](): Review the full list of supported file types.
- [Licensing](): Check details on licensing and evaluation.
- [Technical Support](): Contact support for assistance if you encounter issues.
