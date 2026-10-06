---
title: "ローカルディスクからファイルを読み込む"
linkTitle: "Load From Local Disk"
second_title: "GroupDocs.Conversion for Python via .NET API リファレンス"
description: "ローカルファイルシステムに保存されたドキュメントを .NET 経由の Python 用 GroupDocs.Conversion で変換するために、絶対パスまたは相対パスで Converter クラスをインスタンス化します。"
type: docs
url: /ja/python-net/guides/load-file-from-local-disk/
is_root: false
weight: 90
---


ローカルディスクからソースファイルを読み込むには、GroupDocs.Conversion の [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) クラスコンストラクタを使用できます。API は複数のオーバーロードを提供し、さまざまな設定やオプションに柔軟に対応します：

* `Converter(file_path)`
* `Converter(file_path, load_options)`
* `Converter(file_path, converter_settings)`
* `Converter(file_path, load_options, converter_settings)`

各コンストラクタは `filePath` パラメータが必要で、これはソースファイルへのパスを定義します。絶対パスまたは相対パスのいずれかで指定できます。指定されたファイルパスが存在しない場合、例外がスローされることに注意してください。

GroupDocs.Conversion は、[`Converter`](/conversion/python-net/groupdocs.conversion/converter/) クラスインスタンスを使用してアクション（例: 変換）を実行したときにのみファイルにアクセスします。

以下の Python の例は、ローカルディスクからファイルを読み込み、PDF に変換する方法を示しています：

{{< tabs "code-example">}}
{{< tab "convert_docx_to_pdf.py" >}}
```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

def convert_docx_to_pdf():
    # ソースファイルの場所を指定する
    converter = Converter("./business-plan.docx")
    
    # 出力ファイルの場所と変換オプションを指定する
    output_path = "./business-plan.pdf"
    pdf_options = PdfConvertOptions()
    
    # 変換して出力パスに保存する
    converter.convert(output_path, pdf_options)

if __name__ == "__main__":
    convert_docx_to_pdf()
```
{{< /tab >}}
{{< tab "business-plan.docx" >}}

`business-plan.docx` はこの例で使用されるサンプルファイルです。ダウンロードするには [こちら](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/loading-documents/load-file-from-local-disk/business-plan.docx) をクリックしてください。

{{< /tab >}}
{{< tab "business-plan.pdf" >}}
```text
Binary file (PDF, 283 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/loading-documents/load-file-from-local-disk/convert_docx_to_pdf/business-plan.pdf)
{{< /tab >}}
{{< /tabs >}}

GroupDocs.Conversion は拡張子によってファイルタイプを判定します。拡張子が設定されていない場合、GroupDocs.Conversion はファイルタイプを自動的に検出しようとします。ファイルタイプやサイズに応じて、自動ファイルタイプ検出はメモリや CPU 時間などの追加リソースを消費します。したがって、ファイルに正しい拡張子が付いていることを確認するか、ロードオプションを受け取る Converter クラスのコンストラクタを使用することを推奨します。

### Explanation

- **Load Source File**: The [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) class is instantiated with the path to the source document ("business-plan.docx").
- **Conversion Options**: An instance of [`PdfConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/) is created to define the settings for PDF conversion.
- **Execute Conversion**: The `convert` method is used to convert the document and save it to the specified output path ("business-plan.pdf").

ロードオプションやその他のコンストラクタのオーバーロードの詳細については、[GroupDocs.Conversion API Reference](https://reference.groupdocs.com/conversion/python-net/) を参照してください。
