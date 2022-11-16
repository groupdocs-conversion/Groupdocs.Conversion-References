---
title: OnConversionCompleted
second_title: GroupDocs.Conversion for .NET API 参考
description: 接收转换后的页面流仅当设置了SaveSaveDocumentStreamForFileType时才会触发
type: docs
weight: 10
url: /zh/net/groupdocs.conversion.fluent/iconversionbypagecompleted/onconversioncompleted/
---
## IConversionByPageCompleted.OnConversionCompleted method

接收转换后的页面流。仅当设置了“Save(SaveDocumentStreamForFileType)”时才会触发。

```csharp
public IConversionConvertOrCompress OnConversionCompleted(ConvertedPageStream convertedPageStream)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| convertedPageStream | ConvertedPageStream | 转换后的页面流提供程序 |

### 返回值

继续转换构建的界面

### 也可以看看

* interface [IConversionConvertOrCompress](../../iconversionconvertorcompress)
* delegate [ConvertedPageStream](../../../groupdocs.conversion.contracts/convertedpagestream)
* interface [IConversionByPageCompleted](../../iconversionbypagecompleted)
* 命名空间 [GroupDocs.Conversion.Fluent](../../iconversionbypagecompleted)
* 部件 [GroupDocs.Conversion](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->