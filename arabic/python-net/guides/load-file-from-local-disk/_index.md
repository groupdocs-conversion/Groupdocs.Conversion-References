---
title: "تحميل ملف من القرص المحلي"
linkTitle: "Load From Local Disk"
second_title: "مراجع API لـ GroupDocs.Conversion لـ Python عبر .NET"
description: "إنشاء كائن من فئة Converter باستخدام مسار ملف مطلق أو نسبي لتحويل مستند مخزن على نظام الملفات المحلي باستخدام GroupDocs.Conversion للبايثون عبر .NET."
type: docs
url: /ar/python-net/guides/load-file-from-local-disk/
is_root: false
weight: 90
---


لتحميل ملف مصدر من القرص المحلي، يمكنك استخدام مُنشئ الفئة [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) في GroupDocs.Conversion. توفر الواجهة البرمجية عدة إصدارات، مما يتيح مرونة للإعدادات والخيارات المتنوعة:

* `Converter(file_path)`
* `Converter(file_path, load_options)`
* `Converter(file_path, converter_settings)`
* `Converter(file_path, load_options, converter_settings)`

كل مُنشئ يتطلب المعامل `filePath`، الذي يحدد مسار ملف المصدر. يمكنك تحديده كمسار مطلق أو نسبي. لاحظ أنه إذا كان مسار الملف المحدد غير موجود، سيتم رفع استثناء.

ستقوم GroupDocs.Conversion بالوصول إلى الملف فقط عند تنفيذ إجراء (مثل التحويل) باستخدام كائن الفئة [`Converter`](/conversion/python-net/groupdocs.conversion/converter/).

يوضح المثال التالي بلغة Python كيفية تحميل ملف من قرص محلي وتحويله إلى PDF:

{{< tabs \"code-example\">}}
{{< tab \"convert_docx_to_pdf.py\" >}}
```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

def convert_docx_to_pdf():
    # حدد موقع ملف المصدر
    converter = Converter("./business-plan.docx")
    
    # حدد موقع ملف الإخراج وخيارات التحويل
    output_path = "./business-plan.pdf"
    pdf_options = PdfConvertOptions()
    
    # قم بالتحويل وحفظه إلى مسار الإخراج
    converter.convert(output_path, pdf_options)

if __name__ == "__main__":
    convert_docx_to_pdf()
```
{{< /tab >}}
{{< tab \"business-plan.docx\" >}}

`business-plan.docx` هو ملف عينة يُستخدم في هذا المثال. انقر على [هنا](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/loading-documents/load-file-from-local-disk/business-plan.docx) لتنزيله.

{{< /tab >}}
{{< tab \"business-plan.pdf\" >}}
```text
Binary file (PDF, 283 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/loading-documents/load-file-from-local-disk/convert_docx_to_pdf/business-plan.pdf)
{{< /tab >}}
{{< /tabs >}}

يحدد GroupDocs.Conversion نوع الملف بناءً على امتداده. إذا لم يتم تعيين امتداد الملف، سيحاول GroupDocs.Conversion اكتشاف نوع الملف تلقائيًا. اعتمادًا على نوع الملف وحجمه، يستهلك اكتشاف نوع الملف تلقائيًا موارد إضافية، مثل الذاكرة ووقت وحدة المعالجة المركزية. لذلك، نوصي بالتأكد من أن الملف يحتوي على الامتداد الصحيح أو باستخدام مُنشئ فئة Converter الذي يقبل خيارات التحميل.

### Explanation

- **Load Source File**: The [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) class is instantiated with the path to the source document ("business-plan.docx").
- **Conversion Options**: An instance of [`PdfConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/) is created to define the settings for PDF conversion.
- **Execute Conversion**: The `convert` method is used to convert the document and save it to the specified output path ("business-plan.pdf").

ارجع إلى [GroupDocs.Conversion API Reference](https://reference.groupdocs.com/conversion/python-net/) للحصول على مزيد من التفاصيل حول استخدام خيارات التحميل وغيرها من تجاوزات المُنشئ.
