---
title: "GetDocumentInfo"
second_title: "GroupDocs.Conversion for .NET API 参考"
description: "获取源文档信息、页数以及特定文件类型的其他文档属性。"
type: docs
weight: 40
url: /zh/net/groupdocs.conversion/converter/getdocumentinfo/
---
## GetDocumentInfo() {#getdocumentinfo}

获取源文档信息——页面计数以及特定文件类型的其他文档属性。

```csharp
public IDocumentInfo GetDocumentInfo()
```

### 返回值

文档信息作为 [`IDocumentInfo`](../../../groupdocs.conversion.contracts/idocumentinfo)。

### 备注

**Learn more**

* Learn more about converted document - file type, pages count, creation date and many other format specific properties: [How to get document info](https://docs.groupdocs.com/display/conversionnet/Get+document+info)

### 另见

* interface [IDocumentInfo](../../../groupdocs.conversion.contracts/idocumentinfo)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## GetDocumentInfo&lt;T&gt;() {#getdocumentinfo_1}

获取源文档信息——页面计数以及特定文件类型的其他文档属性。

```csharp
public T GetDocumentInfo<T>()
    where T : IDocumentInfo
```

| 参数 | 描述 |
| --- | --- |
| T | 特定的文档信息类型。 |

### 返回值

文档信息作为指定的类型 T。

### 备注

**Learn more**

* Learn more about converted document - file type, pages count, creation date and many other format specific properties: [How to get document info](https://docs.groupdocs.com/display/conversionnet/Get+document+info)

### 另见

* interface [IDocumentInfo](../../../groupdocs.conversion.contracts/idocumentinfo)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

<!-- 请勿编辑：由 xmldocmd 为 GroupDocs.conversion.dll 生成 -->
