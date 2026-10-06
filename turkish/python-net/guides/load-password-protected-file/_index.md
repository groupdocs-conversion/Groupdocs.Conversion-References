---
title: "Şifre Koruması Olan Dosyayı Yükle"
linkTitle: "Load Password-Protected File"
second_title: "GroupDocs.Conversion for Python via .NET API Referansları"
description: "GroupDocs.Conversion for Python via .NET içinde Converter yapıcısına şifre özelliğiyle bir LoadOptions örneği geçirerek şifre korumalı Word, Excel, PowerPoint ve PDF belgelerinin kilidini açın ve dönüştürün."
type: docs
url: /tr/python-net/guides/load-password-protected-file/
is_root: false
weight: 100
---


*GroupDocs.Conversion for Python via .NET* ile şifre korumalı belgeleri yükleyebilir ve dönüştürebilirsiniz. Bu özellik, içeriğine erişmek için kimlik doğrulama gerektiren belgelerle çalışmanız gerektiğinde faydalıdır.

Şifre korumalı bir belgeyi yüklemek ve dönüştürmek için, aşağıdaki kod örneğinde açıklanan adımları izleyin:

{{< tabs \"code-example\">}}
{{< tab "load_password_protected_file.py" >}}
```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions
from groupdocs.conversion.options.load import WordProcessingLoadOptions

def load_password_protected_file():
    # Dosya yolunu ayarla
    file_path = "./password-protected.docx"
    
    # Load options nesnesini oluşturun ve şifreyi ayarlayın
    wp_load_options = WordProcessingLoadOptions()
    wp_load_options.password = "12345"

    # Kaynak dosya akışını ve load options'ı belirtin
    converter = Converter(file_path, wp_load_options)
    
    # Çıktı dosya konumunu ve dönüştürme seçeneklerini belirtin
    output_path = "./password-protected.pdf"
    pdf_convert_options = PdfConvertOptions()
    pdf_convert_options.password = "67890"

    # Dönüştür ve çıktı yoluna kaydet
    converter.convert(output_path, pdf_convert_options)

if __name__ == "__main__":
    load_password_protected_file()

```
{{< /tab >}}
{{< tab "password-protected.docx" >}}

`password-protected.docx` bu örnekte kullanılan örnek dosyadır. İndirmek için [buraya](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/loading-documents/load-password-protected-file/password-protected.docx) tıklayın.

{{< /tab >}}
{{< tab "password-protected.pdf" >}}
```text
Binary file (PDF, 234 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/loading-documents/load-password-protected-file/load_password_protected_file/password-protected.pdf)
{{< /tab >}}
{{< /tabs >}}

Sağlanan şifre yanlış olduğunda, bir çalışma zamanı hatası fırlatılacaktır. Beklenen hata ve hata mesajı aşağıdaki gibidir:

```bash
RuntimeError: Proxy error(CorruptOrDamagedFileException): Cannot convert. The file is corrupt or damaged. The document password is incorrect. ---> IncorrectPasswordException: The document password is incorrect.
```

### Explanation

1. **File Path Setup**: Şifre korumalı belgenin dosya yolu belirtilir. Bu örnekte, belgenin `password-protected.docx` olarak adlandırıldığı varsayılır.

2. **Load Options**: [`WordProcessingLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/) sınıfının bir örneği oluşturulur ve belgeyi açmak için gereken şifre ayarlanır.

3. **Converter Initialization**: Dosya yolu ve şifreyi içeren yükleme seçenekleri kullanılarak bir [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) örneği oluşturulur.

4. **Convert Options**: Dönüştürme işlemi için bir [`PdfConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/) örneği oluşturulur. Gerekiyorsa, ortaya çıkan PDF için çıktı şifresi de ayarlanabilir.

4. **Conversion Execution**: Son olarak, şifre korumalı belgeyi dönüştürmek ve PDF olarak kaydetmek için [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) örneği üzerinde `convert` yöntemi çağrılır.

### Conclusion

Bu örnek, GroupDocs.Conversion for Python API'sını kullanarak şifre korumalı belgeleri verimli bir şekilde yükleme ve dönüştürme yöntemini gösterir. Kodu çalıştırmadan önce şifreleri ve dosya yollarını gerçek değerlerinizle değiştirdiğinizden emin olun.
