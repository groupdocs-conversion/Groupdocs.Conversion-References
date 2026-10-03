---
title: "加载"
second_title: "GroupDocs.Conversion for .NET API 参考"
description: "设置源文档文件名"
type: docs
weight: 10
url: /zh/net/groupdocs.conversion.fluent/iconversionfrom/load/
---
## Load(string) {#load_2}

设置源文档文件名

```csharp
public IConversionLoadOptionsOrSourceDocumentLoaded Load(string fileName)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileName | String | 源文档 |

### 另见

* interface [IConversionLoadOptionsOrSourceDocumentLoaded](../../iconversionloadoptionsorsourcedocumentloaded)
* interface [IConversionFrom](../../iconversionfrom)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

---

## Load(string[]) {#load_3}

设置源文档数组

```csharp
public IConversionLoadOptionsOrSourceDocumentLoaded Load(string[] fileName)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileName | String[] | 源文档集合 |

### 另见

* interface [IConversionLoadOptionsOrSourceDocumentLoaded](../../iconversionloadoptionsorsourcedocumentloaded)
* interface [IConversionFrom](../../iconversionfrom)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

---

## Load(Func&lt;Stream&gt;) {#load_1}

设置源文档流

```csharp
public IConversionLoadOptionsOrSourceDocumentLoaded Load(Func<Stream> documentStreamProvider)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| documentStreamProvider | Func`1 | 源文档流提供程序 |

### 异常

| 异常 | 条件 |
| --- | --- |
| [InvalidConverterSettingsException](../../../groupdocs.conversion.exceptions/invalidconvertersettingsexception) | 如果转换器设置的验证失败，将抛出此异常 |

### 另见

* interface [IConversionLoadOptionsOrSourceDocumentLoaded](../../iconversionloadoptionsorsourcedocumentloaded)
* interface [IConversionFrom](../../iconversionfrom)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

---

## Load(Func&lt;Stream[]&gt;) {#load}

设置源文档流数组

```csharp
public IConversionLoadOptionsOrSourceDocumentLoaded Load(Func<Stream[]> documentStreamProvider)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| documentStreamProvider | Func`1 | 源文档流提供程序 |

### 异常

| 异常 | 条件 |
| --- | --- |
| [InvalidConverterSettingsException](../../../groupdocs.conversion.exceptions/invalidconvertersettingsexception) | 如果转换器设置的验证失败，将抛出此异常 |

### 另见

* interface [IConversionLoadOptionsOrSourceDocumentLoaded](../../iconversionloadoptionsorsourcedocumentloaded)
* interface [IConversionFrom](../../iconversionfrom)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- 请勿编辑：由 xmldocmd 为 GroupDocs.conversion.dll 生成 -->
