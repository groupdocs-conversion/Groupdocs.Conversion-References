---
title: "加载"
second_title: "GroupDocs.Conversion for .NET API 参考"
description: "配置用于转换的源文档"
type: docs
weight: 10
url: /zh/net/groupdocs.conversion/fluentconverter/load/
---
## Load(string) {#load_2}

配置用于转换的源文档

```csharp
public static IConversionLoadOptionsOrSourceDocumentLoaded Load(string fileName)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileName | String | 源文档 |

### 另见

* interface [IConversionLoadOptionsOrSourceDocumentLoaded](../../../groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded)
* class [FluentConverter](../../fluentconverter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Load(string[]) {#load_3}

配置一组源文档

```csharp
public static IConversionLoadOptionsOrSourceDocumentLoaded Load(string[] fileName)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileName | String[] | 源文件数组 |

### 另见

* interface [IConversionLoadOptionsOrSourceDocumentLoaded](../../../groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded)
* class [FluentConverter](../../fluentconverter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Load(Func&lt;Stream&gt;) {#load_1}

配置源文档流

```csharp
public static IConversionLoadOptionsOrSourceDocumentLoaded Load(Func<Stream> documentStreamProvider)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| documentStreamProvider | Func`1 | 源文档流提供程序 |

### 另见

* interface [IConversionLoadOptionsOrSourceDocumentLoaded](../../../groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded)
* class [FluentConverter](../../fluentconverter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Load(Func&lt;Stream[]&gt;) {#load}

配置一组源文档流

```csharp
public static IConversionLoadOptionsOrSourceDocumentLoaded Load(
    Func<Stream[]> documentStreamProvider)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| documentStreamProvider | Func`1 | 源文档流提供程序集合 |

### 另见

* interface [IConversionLoadOptionsOrSourceDocumentLoaded](../../../groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded)
* class [FluentConverter](../../fluentconverter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

<!-- 请勿编辑：由 xmldocmd 为 GroupDocs.conversion.dll 生成 -->
