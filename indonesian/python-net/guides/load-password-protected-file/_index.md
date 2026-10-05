---
title: "Muat File yang Dilindungi Kata Sandi"
linkTitle: "Load Password-Protected File"
second_title: "Referensi API GroupDocs.Conversion untuk Python via .NET"
description: "Buka kunci dan konversi dokumen Word, Excel, PowerPoint, dan PDF yang dilindungi kata sandi dengan memberikan instance LoadOptions yang memiliki atribut password ke konstruktor Converter di GroupDocs.Conversion untuk Python via .NET."
type: docs
url: /id/python-net/guides/load-password-protected-file/
is_root: false
weight: 100
---


Dengan *GroupDocs.Conversion for Python via .NET* Anda dapat memuat dan mengonversi dokumen yang dilindungi dengan kata sandi. Fitur ini berguna ketika Anda perlu menangani dokumen yang memerlukan otentikasi untuk mengakses isinya.

Untuk memuat dan mengonversi dokumen yang dilindungi kata sandi, ikuti langkah-langkah yang dijelaskan dalam contoh kode di bawah ini:

{{< tabs \"code-example\">}}
{{< tab \"load_password_protected_file.py\" >}}
```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions
from groupdocs.conversion.options.load import WordProcessingLoadOptions

def load_password_protected_file():
    # Atur jalur file
    file_path = "./password-protected.docx"
    
    # Instansiasi opsi muat dan atur kata sandi
    wp_load_options = WordProcessingLoadOptions()
    wp_load_options.password = "12345"

    # Tentukan aliran file sumber dan opsi muat
    converter = Converter(file_path, wp_load_options)
    
    # Tentukan lokasi file output dan opsi konversi
    output_path = "./password-protected.pdf"
    pdf_convert_options = PdfConvertOptions()
    pdf_convert_options.password = "67890"

    # Konversi dan simpan ke jalur output
    converter.convert(output_path, pdf_convert_options)

if __name__ == "__main__":
    load_password_protected_file()

```
{{< /tab >}}
{{< tab \"password-protected.docx\" >}}

`password-protected.docx` adalah file contoh yang digunakan dalam contoh ini. Klik [di sini](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/loading-documents/load-password-protected-file/password-protected.docx) untuk mengunduhnya.

{{< /tab >}}
{{< tab \"password-protected.pdf\" >}}
```text
Binary file (PDF, 234 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/loading-documents/load-password-protected-file/load_password_protected_file/password-protected.pdf)
{{< /tab >}}
{{< /tabs >}}

Jika kata sandi yang diberikan tidak benar, kesalahan runtime akan dilemparkan. Kesalahan yang diharapkan dan pesan kesalahannya adalah sebagai berikut:

```bash
RuntimeError: Proxy error(CorruptOrDamagedFileException): Cannot convert. The file is corrupt or damaged. The document password is incorrect. ---> IncorrectPasswordException: The document password is incorrect.
```

### Explanation

1. **File Path Setup**: Jalur file untuk dokumen yang dilindungi kata sandi ditentukan. Dalam contoh ini, diasumsikan bahwa dokumen tersebut bernama `password-protected.docx`.

2. **Load Options**: Sebuah instance dari [`WordProcessingLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/) dibuat, dan kata sandi yang diperlukan untuk membuka dokumen diatur.

3. **Converter Initialization**: Sebuah instance [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) dibuat menggunakan jalur file dan opsi muat yang mencakup kata sandi.

4. **Convert Options**: Sebuah instance dari [`PdfConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/) dibuat untuk proses konversi. Anda juga dapat mengatur kata sandi output untuk PDF yang dihasilkan jika diperlukan.

4. **Conversion Execution**: Akhirnya, metode `convert` dipanggil pada instance [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) untuk mengonversi dokumen yang dilindungi kata sandi dan menyimpannya sebagai PDF.

### Conclusion

Contoh ini menunjukkan cara memuat dan mengonversi dokumen yang dilindungi kata sandi secara efisien menggunakan API GroupDocs.Conversion untuk Python. Pastikan untuk mengganti kata sandi dan jalur file dengan nilai sebenarnya sebelum mengeksekusi kode.
