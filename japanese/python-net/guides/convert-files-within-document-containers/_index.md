---
title: "ドキュメントコンテナ内のファイルを変換する"
linkTitle: "Convert Archives and Containers"
second_title: "GroupDocs.Conversion for Python via .NET API リファレンス"
description: "ZIP、RAR、7Z、OST、PST などのコンテナ形式を開き、その内容を変換し、.NET 経由の Python 用 GroupDocs.Conversion の単一の Converter.convert() 呼び出しで統合された出力ドキュメントを書き込みます。"
type: docs
url: /ja/python-net/guides/convert-files-within-document-containers/
is_root: false
weight: 70
---


このトピックでは、圧縮ファイルやパッケージ化されたファイルなど、ドキュメントコンテナに埋め込まれたファイルを個別の出力ファイルに変換する方法について説明します。以下の図は、ドキュメントコンテナ内のファイルを抽出し変換するプロセスを示しています。

flowchart LR
%% Nodes
A[\"ドキュメントコンテナ\"]
B[\"抽出\"]
C[\"変換\"]
D[\"変換されたファイル 1\"]
E[\"変換されたファイル 2\"]
F[\"変換されたファイル N\"]

%% Edge connections between nodes
A --> B --> C --> D
C --> E
C → F

抽出および変換プロセスは、[`Converter`](/conversion/python-net/groupdocs.conversion/converter/) クラスの `convert(file_path, convert_options)` メソッドを 1 回呼び出すだけで実行されます。GroupDocs.Conversion はコンテナを開き、内部のファイルを変換し、統合された出力ドキュメントを書き込みます。

## Document Container File Types

次のファイルタイプはドキュメント コンテナとみなされます:

### Email and Outlook

- **EML** - Email Message File.
- **EMLX** - Apple Mail Email File.
- **MSG** - Microsoft Outlook Message File.
- **OST** - Outlook Offline Data File.
- **PST** - Outlook Personal Information Store File.

### PDF

- **PDF** - PDF files that contain embedded resources.

### Word Processing

- **DOC** - The older Microsoft Word binary format.
- **DOCX** - The modern Word format.
- **DOT and DOTX** - Word template files.
- **RTF** - Rich Text Format.

### Compression

- **7Z** - 7-Zip Compressed File.
- **BZ2** - Bzip2 Compressed File.
- **CAB** - Windows Cabinet File.
- **CPIO** - CPIO Compressed File.
- **GZ** - Gnu Zipped Archive.
- **GZIP** - Gzip Compressed File.
- **LZ** - Lzip Compressed File.
- **LZMA** - LZMA Compressed File.
- **RAR** - RAR Compressed Archive.
- **TAR** - Consolidated Unix File Archive.
- **XZ** - Xz Compressed File.
- **Z** - Unix Compressed File.
- **ZIP** - ZIP Compressed File.

## Example: Convert Files Within Document Container

次の例は、ZIP アーカイブの内容を単一の統合 PDF に変換する方法を示しています:

{{< tabs "example-1">}}
{{< tab "convert_files_within_document_container.py" >}}
```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

def convert_files_within_document_container():
    # 入力ドキュメント コンテナで Converter をインスタンス化する
    with Converter("./compressed.zip") as converter:
        # 変換オプションをインスタンス化する
        pdf_convert_options = PdfConvertOptions()

        # アーカイブを抽出し、含まれるファイルを変換して、統合 PDF として保存する
        converter.convert("./converted.pdf", pdf_convert_options)

if __name__ == "__main__":
    convert_files_within_document_container()
```
{{< /tab >}}
{{< tab "compressed.zip" >}}

`compressed.zip` はこの例で使用されるサンプル ファイルです。ダウンロードするには [here](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/convert-files-within-document-containers/compressed.zip) をクリックしてください。

{{< /tab >}}
{{< tab "converted.pdf" >}}
```text
Binary file (PDF, 283 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/converting-documents/convert-files-within-document-containers/convert_files_within_document_container/converted.pdf)
{{< /tab >}}
{{< /tabs >}}
