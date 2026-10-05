---
title: "تحميل ملف محمي بكلمة مرور"
linkTitle: "Load Password-Protected File"
second_title: "مراجع API لـ GroupDocs.Conversion لـ Python عبر .NET"
description: "قم بإلغاء القفل وتحويل مستندات Word وExcel وPowerPoint وPDF المحمية بكلمة مرور عن طريق تمرير كائن LoadOptions مع خاصية password إلى مُنشئ Converter في GroupDocs.Conversion for Python via .NET."
type: docs
url: /ar/python-net/guides/load-password-protected-file/
is_root: false
weight: 100
---


مع *GroupDocs.Conversion for Python via .NET* يمكنك تحميل وتحويل المستندات المحمية بكلمة مرور. هذه الميزة مفيدة عندما تحتاج إلى التعامل مع المستندات التي تتطلب مصادقة للوصول إلى محتوياتها.

لتحميل وتحويل مستند محمي بكلمة مرور، اتبع الخطوات الموضحة في مثال الشيفرة أدناه:

{{< tabs \"code-example\">}}
{{< tab "load_password_protected_file.py" >}}
```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions
from groupdocs.conversion.options.load import WordProcessingLoadOptions

def load_password_protected_file():
    # حدد مسار الملف
    file_path = "./password-protected.docx"
    
    # إنشاء كائن خيارات التحميل وتعيين كلمة المرور
    wp_load_options = WordProcessingLoadOptions()
    wp_load_options.password = "12345"

    # حدد تدفق ملف المصدر وخيارات التحميل
    converter = Converter(file_path, wp_load_options)
    
    # حدد موقع ملف الإخراج وخيارات التحويل
    output_path = "./password-protected.pdf"
    pdf_convert_options = PdfConvertOptions()
    pdf_convert_options.password = "67890"

    # قم بالتحويل وحفظه إلى مسار الإخراج
    converter.convert(output_path, pdf_convert_options)

if __name__ == "__main__":
    load_password_protected_file()

```
{{< /tab >}}
{{< tab "password-protected.docx" >}}

`password-protected.docx` هو ملف عينة يُستخدم في هذا المثال. انقر [هنا](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/loading-documents/load-password-protected-file/password-protected.docx) لتنزيله.

{{< /tab >}}
{{< tab "password-protected.pdf" >}}
```text
Binary file (PDF, 234 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/loading-documents/load-password-protected-file/load_password_protected_file/password-protected.pdf)
{{< /tab >}}
{{< /tabs >}}

في حال كانت كلمة المرور المقدمة غير صحيحة، سيتم إلقاء خطأ في وقت التشغيل. الخطأ المتوقع ورسالة الخطأ كما يلي:

```bash
RuntimeError: Proxy error(CorruptOrDamagedFileException): Cannot convert. The file is corrupt or damaged. The document password is incorrect. ---> IncorrectPasswordException: The document password is incorrect.
```

### Explanation

1. **File Path Setup**: تم تحديد مسار الملف للمستند المحمي بكلمة مرور. في هذا المثال، يُفترض أن المستند اسمه `password-protected.docx`.

2. **Load Options**: تم إنشاء نسخة من [`WordProcessingLoadOptions`](/conversion/python-net/groupdocs.conversion.options.load/wordprocessingloadoptions/)، وتم تعيين كلمة المرور المطلوبة لفتح المستند.

3. **Converter Initialization**: تم إنشاء نسخة من [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) باستخدام مسار الملف وخيارات التحميل التي تتضمن كلمة المرور.

4. **Convert Options**: تم إنشاء نسخة من [`PdfConvertOptions`](/conversion/python-net/groupdocs.conversion.options.convert/pdfconvertoptions/) لعملية التحويل. يمكنك أيضًا تعيين كلمة مرور الإخراج للملف PDF الناتج إذا لزم الأمر.

4. **Conversion Execution**: أخيرًا، يتم استدعاء طريقة `convert` على نسخة [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) لتحويل المستند المحمي بكلمة مرور وحفظه كملف PDF.

### Conclusion

يوضح هذا المثال كيفية تحميل وتحويل المستندات المحمية بكلمة مرور بكفاءة باستخدام واجهة برمجة تطبيقات GroupDocs.Conversion للبايثون. تأكد من استبدال كلمات المرور ومسارات الملفات بالقيم الفعلية قبل تنفيذ الشيفرة.
