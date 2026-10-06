---
title: "Yerel Diskten Dosya Yükle"
linkTitle: "Load From Local Disk"
second_title: "GroupDocs.Conversion for Python via .NET API Referansları"
description: "Yerel dosya sisteminde depolanan bir belgeyi .NET üzerinden Python için GroupDocs.Conversion ile dönüştürmek üzere, mutlak veya göreli bir dosya yolu ile Converter sınıfını örnekleyin."
type: docs
url: /tr/python-net/guides/load-file-from-local-disk/
is_root: false
weight: 90
---


Yerel diskten bir kaynak dosya yüklemek için, GroupDocs.Conversion içindeki [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) sınıf yapıcısını kullanabilirsiniz. API, çeşitli ayarlar ve seçenekler için esneklik sağlayan birkaç aşırı yükleme sunar:

* `Converter(file_path)`
* `Converter(file_path, load_options)`
* `Converter(file_path, converter_settings)`
* `Converter(file_path, load_options, converter_settings)`

Her bir yapıcı, kaynak dosyanın yolunu tanımlayan `filePath` parametresini gerektirir. Bunu mutlak veya göreli bir yol olarak belirtebilirsiniz. Belirtilen dosya yolu mevcut değilse bir istisna oluşacağını unutmayın.

GroupDocs.Conversion, yalnızca bir eylem (ör. dönüştürme) [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) sınıf örneği kullanılarak gerçekleştirildiğinde dosyaya erişecektir.

Aşağıdaki Python örneği, yerel bir diskten dosya yüklemeyi ve PDF'ye dönüştürmeyi gösterir:

{{< tabs \"code-example\">}}
{{< tab \"convert_docx_to_pdf.py\" >}}
```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

def convert_docx_to_pdf():
    # Kaynak dosya konumunu belirtin
    converter = Converter("./business-plan.docx")
    
    # Çıktı dosya konumunu ve dönüştürme seçeneklerini belirtin
    output_path = "./business-plan.pdf"
    pdf_options = PdfConvertOptions()
    
    # Dönüştür ve çıktı yoluna kaydet
    converter.convert(output_path, pdf_options)

if __name__ == "__main__":
    convert_docx_to_pdf()
```
{{< /tab >}}
{{< tab \"business-plan.docx\" >}}

`business-plan.docx` bu örnekte kullanılan örnek dosyadır. İndirmek için [buraya](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/loading-documents/load-file-from-local-disk/business-plan.docx) tıklayın.

{{< /tab >}}
{{< tab "business-plan.pdf" >}}
```text
Binary file (PDF, 283 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/loading-documents/load-file-from-local-disk/convert_docx_to_pdf/business-plan.pdf)
{{< /tab >}}
{{< /tabs >}}

GroupDocs.Conversion dosya tipini uzantısına göre belirler. Dosya uzantısı ayarlanmamışsa, GroupDocs.Conversion dosya tipini otomatik olarak tespit etmeye çalışır. Dosya tipi ve boyutuna bağlı olarak, otomatik dosya tipi tespiti ek kaynaklar tüketir; örneğin bellek ve CPU süresi. Bu nedenle, bir dosyanın doğru uzantıya sahip olduğundan emin olmanızı veya yükleme seçeneklerini kabul eden Converter sınıfı yapıcısını kullanmanızı öneririz.

### Explanation

- **Load Source File**: The [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) class is instantiated with the path to the source document ("business-plan.docx").
- **Conversion Options**: An instance of [`PdfConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/) is created to define the settings for PDF conversion.
- **Execute Conversion**: The `convert` method is used to convert the document and save it to the specified output path ("business-plan.pdf").

Yükleme seçeneklerini ve diğer yapıcı aşırı yüklemelerini kullanma hakkında daha fazla ayrıntı için [GroupDocs.Conversion API Reference](https://reference.groupdocs.com/conversion/python-net/) adresine bakın.
