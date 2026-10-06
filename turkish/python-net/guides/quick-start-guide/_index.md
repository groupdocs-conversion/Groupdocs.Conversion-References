---
title: "Hızlı Başlangıç Kılavuzu"
linkTitle: "Quick Start Guide"
second_title: "GroupDocs.Conversion for Python via .NET API Referansları"
description: "Bir sanal ortam kurun, groupdocs-conversion-net'i yükleyin ve beş dakikadan kısa sürede üç temel örneği çalıştırın — DOCX → PDF, PDF → sayfa başına PNG ve ZIP → birleştirilmiş PDF."
type: docs
url: /tr/python-net/guides/quick-start-guide/
is_root: false
weight: 20
---


Bu kılavuz, .NET üzerinden GroupDocs.Conversion for Python'ı nasıl kurup kullanmaya başlayacağınız hakkında hızlı bir genel bakış sunar. Bu kütüphane, geliştiricilerin çeşitli dosya formatları (ör. DOCX, PDF, PNG) arasında minimum yapılandırma ile dönüştürme yapmasını sağlar.

## Prerequisites

Devam etmek için, şunların olduğundan emin olun:

1. **Configured** ortam, [System Requirements]() konusunda açıklandığı gibi.
2. **Optionally** tüm ürün özelliklerini test etmek için [Geçici Lisans Al](https://purchase.groupdocs.com/temporary-license/) alabilirsiniz.

## Set Up Your Development Environment

En iyi uygulamalar için, Python uygulamalarında bağımlılıkları yönetmek amacıyla bir sanal ortam kullanın. Sanal ortam hakkında daha fazla bilgi için [Create and Use Virtual Environments](https://packaging.python.org/en/latest/guides/installing-using-pip-and-virtual-environments/#create-and-use-virtual-environments) dokümantasyon konusuna bakın.

### Create and Activate a Virtual Environment

Bir sanal ortam oluşturun:

{{< tabs "example1">}}
{{< tab "Windows" >}}
```ps
py -m venv .venv
```
{{< /tab >}}
{{< tab "Linux" >}}
```bash
python3 -m venv .venv
```
{{< /tab >}}
{{< tab "macOS" >}}
```bash
python3 -m venv .venv
```
{{< /tab >}}
{{< /tabs >}}

Sanal ortamı etkinleştirin:

{{< tabs "example2">}}
{{< tab "Windows" >}}
```ps
.venv\Scripts\activate
```
{{< /tab >}}
{{< tab "Linux" >}}
```bash
source .venv/bin/activate
```
{{< /tab >}}
{{< tab "macOS" >}}
```bash
source .venv/bin/activate
```
{{< /tab >}}
{{< /tabs >}}

### Install `groupdocs-conversion-net` Package

Sanal ortamı etkinleştirdikten sonra, paketinin en son sürümünü yüklemek için terminalinizde aşağıdaki komutu çalıştırın:

{{< tabs "example3">}}
{{< tab "Windows" >}}
```ps
py -m pip install groupdocs-conversion-net
```
{{< /tab >}}
{{< tab "Linux" >}}
```bash
python3 -m pip install groupdocs-conversion-net
```
{{< /tab >}}
{{< tab "macOS" >}}
```bash
python3 -m pip install groupdocs-conversion-net
```
{{< /tab >}}
{{< /tabs >}}

Paketin başarılı bir şekilde yüklendiğinden emin olun. Aşağıdaki mesajı görmelisiniz

```bash
Successfully installed groupdocs-conversion-net-*
```

## Example 1: Convert document

Kütüphaneyi hızlıca test etmek için bir DOCX dosyasını PDF'ye dönüştürelim. Ayrıca oluşturacağımız uygulamayı [buradan](https://docs.groupdocs.com/conversion/python-net/_sample_files/getting-started/quick-start-guide/convert_docx_to_pdf.zip) indirebilirsiniz.

{{< tabs \"demo_app_convert_docx_to_pdf\">}}
{{< tab \"convert_docx_to_pdf.py\" >}}
```python
import os
from groupdocs.conversion import License, Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

def convert_docx_to_pdf():
    # Lisans dosyasının mutlak yolunu alın
    license_path = os.path.abspath("./GroupDocs.Conversion.lic")

    if os.path.exists(license_path):
        # Lisans oluşturun ve yolu ayarlayın
        license = License()
        license.set_license(license_path)

    # DOCX dosyasını yükleyin
    with Converter("./business-plan.docx") as converter:
        # Dönüştürme seçeneklerini oluşturun
        pdf_convert_options = PdfConvertOptions()

        # DOCX'i PDF'e dönüştürün
        converter.convert("./business-plan.pdf", pdf_convert_options)    

if __name__ == "__main__":
    convert_docx_to_pdf()
```
{{< /tab >}}
{{< tab \"business-plan.docx\" >}}

`business-plan.docx` bu örnekte kullanılan örnek dosyadır. İndirmek için [buraya](https://docs.groupdocs.com/conversion/python-net/_sample_files/getting-started/quick-start-guide/business-plan.docx) tıklayın.

{{< /tab >}}
{{< tab "business-plan.pdf" >}}
```text
Binary file (PDF, 283 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/getting-started/quick-start-guide/convert_docx_to_pdf/business-plan.pdf)
{{< /tab >}}
{{< /tabs >}}

Klasör ağacınız aşağıdaki dizin yapısına benzer olmalıdır:

```Directory
📂 demo-app
 ├──convert_docx_to_pdf.py
 ├──business-plan.docx
 └──GroupDocs.Conversion.lic (Optionally)
```

### Run the App

{{< tabs \"run-the-app\">}}
{{< tab "Windows" >}}
```ps
py convert_docx_to_pdf.py
```
{{< /tab >}}
{{< tab "Linux" >}}
```bash
python3 convert_docx_to_pdf.py
```
{{< /tab >}}
{{< tab "macOS" >}}
```bash
python3 convert_docx_to_pdf.py
```
{{< /tab >}}
{{< /tabs >}}

Uygulamayı çalıştırdıktan sonra `deactivate` komutunu çalıştırarak veya kabuğunuzu kapatarak sanal ortamı devre dışı bırakabilirsiniz.

### Explanation
- `Converter("./business-plan.docx")`: Initializes the converter with the DOCX file.
- `PdfConvertOptions()`: Specifies the output format as PDF.
- `converter.convert("./business-plan.pdf", pdf_convert_options)`: Converts the DOCX file to PDF and saves it as `business-plan.pdf`.

## Example 2: Convert document pages

Bu örnekte PDF belge sayfalarını PNG'ye dönüştüreceğiz. Oluşturacağımız uygulamayı [buradan](https://docs.groupdocs.com/conversion/python-net/_sample_files/getting-started/quick-start-guide/convert_pdf_pages_to_png.zip) indirebilirsiniz.

{{< tabs \"demo_app_convert_pdf_pages_to_png\">}}
{{< tab \"convert_pdf_pages_to_png.py\" >}}
```python
import os
from groupdocs.conversion import License, Converter
from groupdocs.conversion.filetypes import ImageFileType
from groupdocs.conversion.options.convert import ImageConvertOptions

def convert_pdf_pages_to_png():
    # Lisans dosyasının mutlak yolunu alın
    license_path = os.path.abspath("./GroupDocs.Conversion.lic")

    if os.path.exists(license_path):
        # Lisans oluşturun ve yolu ayarlayın
        license = License()
        license.set_license(license_path)

    output_folder = "./converted-pages"
    os.makedirs(output_folder, exist_ok=True)

    # PDF belgesini yükleyin
    with Converter("./annual-review.pdf") as converter:
        # Kaynak belgedeki toplam sayfa sayısını belirleyin
        pages_count = converter.get_document_info().pages_count

        # Dönüştürme seçeneklerini oluşturun ve döngü içinde yeniden kullanın
        png_convert_options = ImageConvertOptions()
        png_convert_options.format = ImageFileType.PNG
        png_convert_options.pages_count = 1

        # Her sayfayı ayrı bir PNG dosyasına dönüştürün
        for page_number in range(1, pages_count + 1):
            png_convert_options.page_number = page_number
            output_file = os.path.join(output_folder, f"converted-page-{page_number}.png")
            converter.convert(output_file, png_convert_options)

if __name__ == "__main__":
    convert_pdf_pages_to_png()
```
{{< /tab >}}
{{< tab \"annual-review.pdf\" >}}

`annual-review.pdf` bu örnekte kullanılan örnek dosyadır. İndirmek için [buraya](https://docs.groupdocs.com/conversion/python-net/_sample_files/getting-started/quick-start-guide/annual-review.pdf) tıklayın.

{{< /tab >}}
{{< tab \"convert-pdf-pages-to-png-outputs.zip\" >}}
```text
converted-pages/converted-page-1.png (1148 KB)
converted-pages/converted-page-2.png (89 KB)
converted-pages/converted-page-3.png (83 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/getting-started/quick-start-guide/convert_pdf_pages_to_png/convert-pdf-pages-to-png-outputs.zip)
{{< /tab >}}
{{< /tabs >}}

Klasör ağacınız aşağıdaki dizin yapısına benzer olmalıdır:

```Directory
📂 demo-app
 ├──annual-review.pdf
 ├──convert_pdf_pages_to_png.py
 └──GroupDocs.Conversion.lic (Optionally)
```

### Run the App

{{< tabs \"run_the_app_convert_pdf_pages_to_png\">}}
{{< tab "Windows" >}}
```ps
py convert_pdf_pages_to_png.py
```
{{< /tab >}}
{{< tab "Linux" >}}
```bash
python3 convert_pdf_pages_to_png.py
```
{{< /tab >}}
{{< tab "macOS" >}}
```bash
python3 convert_pdf_pages_to_png.py
```
{{< /tab >}}
{{< /tabs >}}

Uygulamayı çalıştırdıktan sonra `deactivate` komutunu çalıştırarak veya kabuğunuzu kapatarak sanal ortamı devre dışı bırakabilirsiniz.

### Explanation
- `Converter("./annual-review.pdf")`: Initializes the converter with the PDF file.
- `converter.get_document_info().pages_count`: Retrieves the total number of pages in the source document.
- `ImageConvertOptions()` with `format = ImageFileType.PNG`: Specifies the output format as PNG image.
- The loop updates `png_convert_options.page_number` on each iteration (with `pages_count = 1`) and calls `converter.convert(...)` to write one PNG file per page into the `converted-pages` folder.

## Example 3: Convert files in archive

Bu örnekte bir ZIP arşivinin içeriğini PDF'e dönüştüreceğiz. GroupDocs.Conversion arşivi açar, içindeki dosyaları dönüştürür ve tüm dönüştürülmüş belgeleri içeren tek bir birleşik PDF üretir. Oluşturacağımız uygulamayı [buradan](https://docs.groupdocs.com/conversion/python-net/_sample_files/getting-started/quick-start-guide/convert_files_in_archive.zip) indirebilirsiniz.

{{< tabs \"demo_app_convert_files_in_archive\">}}
{{< tab \"convert_files_in_archive.py\" >}}
```python
import os
from groupdocs.conversion import License, Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

def convert_files_in_archive():
    # Lisans dosyasının mutlak yolunu alın
    license_path = os.path.abspath("./GroupDocs.Conversion.lic")

    if os.path.exists(license_path):
        # Lisans oluşturun ve yolu ayarlayın
        license = License()
        license.set_license(license_path)

    # ZIP dosyasını yükleyin
    with Converter("./compressed.zip") as converter:
        # Dönüştürme seçeneklerini oluşturun
        pdf_convert_options = PdfConvertOptions()

        # Arşivi çıkarın, içeriğini dönüştürün ve birleştirilmiş bir PDF olarak kaydedin
        converter.convert("./converted.pdf", pdf_convert_options)

if __name__ == "__main__":
    convert_files_in_archive()
```
{{< /tab >}}
{{< tab "compressed.zip" >}}

`compressed.zip` bu örnekte kullanılan örnek dosyadır. İndirmek için [buraya](https://docs.groupdocs.com/conversion/python-net/_sample_files/getting-started/quick-start-guide/compressed.zip) tıklayın.

{{< /tab >}}
{{< tab "converted.pdf" >}}
```text
Binary file (PDF, 283 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/getting-started/quick-start-guide/convert_files_in_archive/converted.pdf)
{{< /tab >}}
{{< /tabs >}}

Klasör ağacınız aşağıdaki dizin yapısına benzer olmalıdır:

```Directory
📂 demo-app
 ├──compressed.zip
 ├──convert_files_in_archive.py
 └──GroupDocs.Conversion.lic (Optionally)
```

### Run the App

{{< tabs \"run_the_app_convert_files_in_archive\">}}
{{< tab "Windows" >}}
```ps
py convert_files_in_archive.py
```
{{< /tab >}}
{{< tab "Linux" >}}
```bash
python3 convert_files_in_archive.py
```
{{< /tab >}}
{{< tab "macOS" >}}
```bash
python3 convert_files_in_archive.py
```
{{< /tab >}}
{{< /tabs >}}

Uygulamayı çalıştırdıktan sonra `deactivate` komutunu çalıştırarak veya kabuğunuzu kapatarak sanal ortamı devre dışı bırakabilirsiniz.

### Explanation
- `Converter("./compressed.zip")`: Initializes the converter with the ZIP file.
- `PdfConvertOptions()`: Specifies the output format as PDF.
- `converter.convert("./converted.pdf", pdf_convert_options)`: Extracts the archive, converts its contents, and writes a single consolidated PDF to `converted.pdf`.

## Next Steps

Temel konuları tamamladıktan sonra, kullanımınızı geliştirmek için ek kaynakları keşfedin:
- [Supported File Formats](): Review the full list of supported file types.
- [Licensing](): Check details on licensing and evaluation.
- [Technical Support](): Contact support for assistance if you encounter issues.
