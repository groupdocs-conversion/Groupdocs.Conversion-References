---
title: "Carica"
second_title: "Riferimento API di GroupDocs.Conversion per .NET"
description: "Imposta il nome file del documento sorgente"
type: docs
weight: 10
url: /it/net/groupdocs.conversion.fluent/iconversionfrom/load/
---
## Load(string) {#load_2}

Imposta il nome file del documento sorgente

```csharp
public IConversionLoadOptionsOrSourceDocumentLoaded Load(string fileName)
```

| Parameter | Type | Descrizione |
| --- | --- | --- |
| fileName | String | Documento sorgente |

### IConversionConvertOptions

* interface [IConversionLoadOptionsOrSourceDocumentLoaded](../../iconversionloadoptionsorsourcedocumentloaded)
* interface [IConversionFrom](../../iconversionfrom)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

---

## Load(string[]) {#load_3}

Imposta l'array di documenti sorgente

```csharp
public IConversionLoadOptionsOrSourceDocumentLoaded Load(string[] fileName)
```

| Parameter | Type | Descrizione |
| --- | --- | --- |
| fileName | String[] | Insieme di documenti sorgente |

### IConversionConvertOptions

* interface [IConversionLoadOptionsOrSourceDocumentLoaded](../../iconversionloadoptionsorsourcedocumentloaded)
* interface [IConversionFrom](../../iconversionfrom)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

---

## Load(Func&lt;Stream&gt;) {#load_1}

Imposta lo stream del documento sorgente

```csharp
public IConversionLoadOptionsOrSourceDocumentLoaded Load(Func<Stream> documentStreamProvider)
```

| Parameter | Type | Descrizione |
| --- | --- | --- |
| documentStreamProvider | Func`1 | Provider di stream del documento sorgente |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [InvalidConverterSettingsException](../../../groupdocs.conversion.exceptions/invalidconvertersettingsexception) | Se la convalida delle impostazioni del convertitore fallisce, verrà sollevata questa eccezione. |

### IConversionConvertOptions

* interface [IConversionLoadOptionsOrSourceDocumentLoaded](../../iconversionloadoptionsorsourcedocumentloaded)
* interface [IConversionFrom](../../iconversionfrom)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

---

## Load(Func&lt;Stream[]&gt;) {#load}

Imposta l'array di stream dei documenti sorgente

```csharp
public IConversionLoadOptionsOrSourceDocumentLoaded Load(Func<Stream[]> documentStreamProvider)
```

| Parameter | Type | Descrizione |
| --- | --- | --- |
| documentStreamProvider | Func`1 | Provider di flussi di documenti sorgente |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [InvalidConverterSettingsException](../../../groupdocs.conversion.exceptions/invalidconvertersettingsexception) | Se la convalida delle impostazioni del convertitore fallisce, verrà sollevata questa eccezione. |

### IConversionConvertOptions

* interface [IConversionLoadOptionsOrSourceDocumentLoaded](../../iconversionloadoptionsorsourcedocumentloaded)
* interface [IConversionFrom](../../iconversionfrom)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.conversion.dll -->
