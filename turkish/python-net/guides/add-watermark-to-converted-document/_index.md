---
title: "Dönüştürülmüş Belgeye Filigran Ekle"
linkTitle: "Add a Watermark"
second_title: "GroupDocs.Conversion for Python via .NET API Referansları"
description: "GroupDocs.Conversion for Python via .NET ile dönüştürülmüş bir belgenin her sayfasına metin filigranı damgalayın — renk, boyut, konum, dönüş, şeffaflık ve ön plan ya da arka plan yerleşimini WatermarkTextOptions aracılığıyla kontrol edin."
type: docs
url: /tr/python-net/guides/add-watermark-to-converted-document/
is_root: false
weight: 80
---


Bu konu, GroupDocs.Conversion for Python via .NET kullanarak dönüştürme işlemi sırasında nasıl filigran ekleneceğini açıklar. Filigran, bir belge başka bir formata dönüştürülürken uygulanabilir, içeriği korumaya ve tanımlanabilir olmasını sağlamaya yardımcı olur.

Filigranlamayı etkinleştirmek için uygun [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/) sınıflarında `watermark` özniteliğini kullanabilirsiniz. Aşağıda, dönüştürme sırasında filigranı yapılandırmanıza izin veren desteklenen [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/) sınıfları listelenmiştir:

Gelişmiş filigranlama özellikleri mi arıyorsunuz? GroupDocs.Conversion temel filigranlama sunarken, geliştirilmiş özelliklere sahip kapsamlı bir çözüm için [GroupDocs.Watermark](https://products.groupdocs.com/watermark/) adresini inceleyebilirsiniz.

## Supported ConvertOptions Classes

Aşağıdaki [`ConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/convertoptions/) sınıfları `watermark` özniteliğini sağlar.

- **PdfConvertOptions** – Options for converting to [PDF]() format.
- **WordProcessingConvertOptions** – Options for converting to [Word Processing]() formats.
- **SpreadsheetConvertOptions** – Options for converting to [Spreadsheet]() formats.
- **PresentationConvertOptions** – Options for converting to [Presentation]() formats.
- **ImageConvertOptions** – Options for converting to [Image]() formats (e.g., PNG, JPEG).
- **WebConvertOptions** – Options for converting to [Web]() formats (e.g., HTML).
- **PageDescriptionLanguageConvertOptions** – Options for converting to [Page Description Language]() formats (e.g., PostScript).
- **EBookConvertOptions** – Options for converting to [EBook]() formats (e.g., EPUB, MOBI).
- **DiagramConvertOptions** – Options for converting to [Diagram]() formats (e.g., VSDX).

## WatermarkTextOptions Class Attributes

Bu [`WatermarkTextOptions`](/conversion/python-net/groupdocs.conversion.options.convert/watermarktextoptions/) sınıfı, filigranın görünümünü yapılandırmak için kullanılır. Filigran eklemek için aşağıdaki seçenekler yapılandırılabilir:

- **text**: The text to be used for the watermark.
- **font**: The font name used for the watermark text.
- **color**: The color of the watermark text.
- **width**: The width of the watermark.
- **height**: The height of the watermark.
- **top**: The top position of the watermark.
- **left**: The left position of the watermark.
- **rotation_angle**: The rotation angle of the watermark.
- **transparency**: The transparency level of the watermark.
- **background**: Specifies whether the watermark is stamped as a background. If set to `True`, the watermark is placed at the bottom. By default, it is `False`, and the watermark is placed on top of the content.

## Example: Add a Watermark to Converted Document

Aşağıdaki örnek, DOCX belgesini PDF'ye dönüştürmeyi ve bir filigran eklemeyi gösterir:

{{< tabs \"example-1\">}}
{{< tab \"add_watermark_to_converted_document.py\" >}}
```python
from groupdocs.pydrawing import Color
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions, WatermarkTextOptions

def add_watermark_to_converted_document():
    # Girdi belgesiyle Converter'ı örnekleyin 
    with Converter("./professional-services.docx") as converter:
        # Filigran seçeneklerini ayarlayın
        watermark = WatermarkTextOptions("DRAFT")
        watermark.color = Color.from_argb(128, 211, 211, 211) # lite gray
        watermark.top = 10
        watermark.left = 10
        watermark.width = 300
        watermark.height = 300
        watermark.background = True

        # Dönüştürme seçeneklerini ayarlayın
        options = PdfConvertOptions()
        options.pages_count = 1
        options.watermark = watermark
        
        # Dönüştürmeyi gerçekleştirin
        converter.convert("./professional-services.pdf", options)    

if __name__ == "__main__":
    add_watermark_to_converted_document()
```
{{< /tab >}}
{{< tab \"professional-services.docx\" >}}

`professional-services.docx` bu örnekte kullanılan örnek dosyadır. İndirmek için [buraya](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/add-watermark-to-converted-document/professional-services.docx) tıklayın.

{{< /tab >}}
{{< tab \"professional-services.pdf\" >}}
```text
Binary file (PDF, 363 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/converting-documents/add-watermark-to-converted-document/add_watermark_to_converted_document/professional-services.pdf)
{{< /tab >}}
{{< /tabs >}}
