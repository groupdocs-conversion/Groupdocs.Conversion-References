---
title: "パスワード保護されたファイルを読み込む"
linkTitle: "Load Password-Protected File"
second_title: "GroupDocs.Conversion for Python via .NET API リファレンス"
description: "パスワードで保護された Word、Excel、PowerPoint、PDF ドキュメントを、LoadOptions インスタンスの password 属性を指定して GroupDocs.Conversion for Python via .NET の Converter コンストラクタに渡すことで、ロック解除および変換します。"
type: docs
url: /ja/python-net/guides/load-password-protected-file/
is_root: false
weight: 100
---


*GroupDocs.Conversion for Python via .NET* を使用すると、パスワードで保護されたドキュメントを読み込み、変換できます。この機能は、内容にアクセスするために認証が必要なドキュメントを扱う必要がある場合に便利です。

パスワード保護されたドキュメントを読み込み、変換するには、以下のコード例に示された手順に従ってください：

{{< tabs "code-example">}}
{{< tab "load_password_protected_file.py" >}}
```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions
from groupdocs.conversion.options.load import WordProcessingLoadOptions

def load_password_protected_file():
    # ファイルパスを設定する
    file_path = "./password-protected.docx"
    
    # LoadOptions をインスタンス化し、パスワードを設定する
    wp_load_options = WordProcessingLoadOptions()
    wp_load_options.password = "12345"

    # ソースファイルストリームと LoadOptions を指定する
    converter = Converter(file_path, wp_load_options)
    
    # 出力ファイルの場所と変換オプションを指定する
    output_path = "./password-protected.pdf"
    pdf_convert_options = PdfConvertOptions()
    pdf_convert_options.password = "67890"

    # 変換して出力パスに保存する
    converter.convert(output_path, pdf_convert_options)

if __name__ == "__main__":
    load_password_protected_file()

```
{{< /tab >}}
{{< tab "password-protected.docx" >}}

`password-protected.docx` はこの例で使用されるサンプルファイルです。ダウンロードするには [here](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/loading-documents/load-password-protected-file/password-protected.docx) をクリックしてください。

{{< /tab >}}
{{< tab "password-protected.pdf" >}}
```text
Binary file (PDF, 234 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/loading-documents/load-password-protected-file/load_password_protected_file/password-protected.pdf)
{{< /tab >}}
{{< /tabs >}}

提供されたパスワードが正しくない場合、ランタイムエラーがスローされます。期待されるエラーとエラーメッセージは以下の通りです：

```bash
RuntimeError: Proxy error(CorruptOrDamagedFileException): Cannot convert. The file is corrupt or damaged. The document password is incorrect. ---> IncorrectPasswordException: The document password is incorrect.
```

### Explanation

1. **File Path Setup**: パスワード保護されたドキュメントのファイルパスが指定されています。この例では、ドキュメントの名前が `password-protected.docx` であると想定しています。

2. **Load Options**: [`WordProcessingLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/) のインスタンスが作成され、ドキュメントを開くために必要なパスワードが設定されます。

3. **Converter Initialization**: ファイルパスとパスワードを含むロードオプションを使用して、[`Converter`](/conversion/python-net/groupdocs.conversion/converter/) のインスタンスが作成されます。

4. **Convert Options**: 変換プロセスのために [`PdfConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/) のインスタンスが作成されます。必要に応じて、生成される PDF の出力パスワードを設定することもできます。

4. **Conversion Execution**: 最後に、[`Converter`](/conversion/python-net/groupdocs.conversion/converter/) インスタンス上で `convert` メソッドを呼び出し、パスワード保護されたドキュメントを変換して PDF として保存します。

### Conclusion

この例は、GroupDocs.Conversion for Python API を使用してパスワード保護されたドキュメントを効率的にロードおよび変換する方法を示しています。コードを実行する前に、パスワードとファイルパスを実際の値に置き換えてください。
