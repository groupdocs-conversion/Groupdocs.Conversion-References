---
title: SavePageStreamForFileType
second_title: GroupDocs.Conversion لمرجع .NET API
description: يصف المفوض لحفظ صفحة المستند المحولة في التدفق.
type: docs
weight: 500
url: /ar/net/groupdocs.conversion.contracts/savepagestreamforfiletype/
---
## SavePageStreamForFileType delegate

يصف المفوض لحفظ صفحة المستند المحولة في التدفق.

```csharp
public delegate Stream SavePageStreamForFileType(int pageNumber, FileType fileType);
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| pageNumber | Int32 | رقم الصفحة المحولة |
| fileType | FileType | نوع الوثيقة المحولة |

### قيمة الإرجاع

يجب إرجاع دفق حيث سيتم حفظ صفحة المستند المحولة

### أنظر أيضا

* class [FileType](../../groupdocs.conversion.filetypes/filetype)
* مساحة الاسم [GroupDocs.Conversion.Contracts](../../groupdocs.conversion.contracts)
* المجسم [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
