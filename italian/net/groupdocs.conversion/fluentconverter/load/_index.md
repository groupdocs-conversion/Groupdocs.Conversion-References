---
title: "Carica"
second_title: "Riferimento API di GroupDocs.Conversion per .NET"
description: "Configura il documento sorgente per la conversione"
type: docs
weight: 10
url: /it/net/groupdocs.conversion/fluentconverter/load/
---
## Load(string) {#load_2}

Configura il documento sorgente per la conversione

```csharp
public static IConversionLoadOptionsOrSourceDocumentLoaded Load(string fileName)
```

| Parameter | Type | Descrizione |
| --- | --- | --- |
| fileName | String | Documento sorgente |

### IConversionConvertOptions

* interface [IConversionLoadOptionsOrSourceDocumentLoaded](../../../groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded)
* class [FluentConverter](../../fluentconverter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Load(string[]) {#load_3}

Configura l'insieme di documenti sorgente

```csharp
public static IConversionLoadOptionsOrSourceDocumentLoaded Load(string[] fileName)
```

| Parameter | Type | Descrizione |
| --- | --- | --- |
| fileName | String[] | Array di file sorgente |

### IConversionConvertOptions

* interface [IConversionLoadOptionsOrSourceDocumentLoaded](../../../groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded)
* class [FluentConverter](../../fluentconverter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Load(Func&lt;Stream&gt;) {#load_1}

Configura lo stream del documento sorgente

```csharp
public static IConversionLoadOptionsOrSourceDocumentLoaded Load(Func<Stream> documentStreamProvider)
```

| Parameter | Type | Descrizione |
| --- | --- | --- |
| documentStreamProvider | Func`1 | Provider di stream del documento sorgente |

### IConversionConvertOptions

* interface [IConversionLoadOptionsOrSourceDocumentLoaded](../../../groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded)
* class [FluentConverter](../../fluentconverter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Load(Func&lt;Stream[]&gt;) {#load}

Configura l'insieme di stream dei documenti sorgente

```csharp
public static IConversionLoadOptionsOrSourceDocumentLoaded Load(
    Func<Stream[]> documentStreamProvider)
```

| Parameter | Type | Descrizione |
| --- | --- | --- |
| documentStreamProvider | Func`1 | Provider di flussi di documenti sorgente |

### IConversionConvertOptions

* interface [IConversionLoadOptionsOrSourceDocumentLoaded](../../../groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded)
* class [FluentConverter](../../fluentconverter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.conversion.dll -->
