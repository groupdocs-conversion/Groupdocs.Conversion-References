---
title: "تحويل الملفات داخل حاويات المستندات"
linkTitle: "Convert Archives and Containers"
second_title: "مراجع API لـ GroupDocs.Conversion لـ Python عبر .NET"
description: "افتح صيغ الحاويات مثل ZIP و RAR و 7Z و OST و PST وغيرها، حوّل محتوياتها، واكتب مستند إخراج موحد في استدعاء واحد لـ Converter.convert() باستخدام GroupDocs.Conversion للبايثون عبر .NET."
type: docs
url: /ar/python-net/guides/convert-files-within-document-containers/
is_root: false
weight: 70
---


يغطي هذا الموضوع كيفية تحويل الملفات المدمجة داخل حاويات المستندات، مثل الملفات المضغوطة أو المعبأة، إلى ملفات إخراج فردية. يوضح المخطط التالي عملية استخراج وتحويل الملفات داخل حاوية المستند:

flowchart LR
%% Nodes
A[\"حاوية المستند\"]
B[\"استخراج\"]
C[\"تحويل\"]
D[\"ملف محوّل 1\"]
E[\"ملف محوّل 2\"]
F[\"ملف محوّل N\"]

%% اتصالات الحواف بين العقد
A --> B --> C --> D
C --> E
C --> F

يتم تنفيذ عمليات الاستخراج والتحويل ضمن استدعاء واحد للطريقة `convert(file_path, convert_options)` في فئة [`Converter`](/conversion/python-net/groupdocs.conversion/converter/). تقوم GroupDocs.Conversion بفتح الحاوية، وتحويل الملفات التي تحتويها، وكتابة مستند إخراج موحد.

## Document Container File Types

أنواع الملفات التالية تُعتبر حاويات مستندات:

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

المثال التالي يوضح كيفية تحويل محتويات أرشيف ZIP إلى ملف PDF موحد واحد:

{{< tabs \"example-1\">}}
{{< tab \"convert_files_within_document_container.py\" >}}
```python
from groupdocs.conversion import Converter
from groupdocs.conversion.options.convert import PdfConvertOptions

def convert_files_within_document_container():
    # إنشاء كائن Converter باستخدام حاوية المستند المدخل
    with Converter("./compressed.zip") as converter:
        # إنشاء خيارات التحويل
        pdf_convert_options = PdfConvertOptions()

        # استخراج الأرشيف، تحويل الملفات المحتواة، وحفظ ملف PDF موحد
        converter.convert("./converted.pdf", pdf_convert_options)

if __name__ == "__main__":
    convert_files_within_document_container()
```
{{< /tab >}}
{{< tab \"compressed.zip\" >}}

`compressed.zip` هو ملف العينة المستخدم في هذا المثال. انقر [هنا](https://docs.groupdocs.com/conversion/python-net/_sample_files/developer-guide/converting-documents/convert-files-within-document-containers/compressed.zip) لتنزيله.

{{< /tab >}}
{{< tab \"converted.pdf\" >}}
```text
Binary file (PDF, 283 KB)
```
[Download full output](https://docs.groupdocs.com/conversion/python-net/_output_files/developer-guide/converting-documents/convert-files-within-document-containers/convert_files_within_document_container/converted.pdf)
{{< /tab >}}
{{< /tabs >}}
