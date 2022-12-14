---
title: Load
second_title: Riferimento API GroupDocs.Conversion per .NET
description: Imposta il nome del file del documento di origine
type: docs
weight: 10
url: /it/net/groupdocs.conversion.fluent/iconversionfrom/load/
---
## Load(string) {#load_2}

Imposta il nome del file del documento di origine

```csharp
public IConversionLoadOptionsOrSourceDocumentLoaded Load(string fileName)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fileName | String | Documento di origine |

### Guarda anche

* interface [IConversionLoadOptionsOrSourceDocumentLoaded](../../iconversionloadoptionsorsourcedocumentloaded)
* interface [IConversionFrom](../../iconversionfrom)
* spazio dei nomi [GroupDocs.Conversion.Fluent](../../iconversionfrom)
* assemblea [GroupDocs.Conversion](../../../)

---

## Load(string[]) {#load_3}

Imposta l'array dei documenti di origine

```csharp
public IConversionLoadOptionsOrSourceDocumentLoaded Load(string[] fileName)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fileName | String[] | Insieme di documenti di origine |

### Guarda anche

* interface [IConversionLoadOptionsOrSourceDocumentLoaded](../../iconversionloadoptionsorsourcedocumentloaded)
* interface [IConversionFrom](../../iconversionfrom)
* spazio dei nomi [GroupDocs.Conversion.Fluent](../../iconversionfrom)
* assemblea [GroupDocs.Conversion](../../../)

---

## Load(Func&lt;Stream&gt;) {#load_1}

Imposta flusso di documenti di origine

```csharp
public IConversionLoadOptionsOrSourceDocumentLoaded Load(Func<Stream> documentStreamProvider)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| documentStreamProvider | Func`1 | Fornitore del flusso di documenti di origine |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [InvalidConverterSettingsException](../../../groupdocs.conversion.exceptions/invalidconvertersettingsexception) |  |

### Guarda anche

* interface [IConversionLoadOptionsOrSourceDocumentLoaded](../../iconversionloadoptionsorsourcedocumentloaded)
* interface [IConversionFrom](../../iconversionfrom)
* spazio dei nomi [GroupDocs.Conversion.Fluent](../../iconversionfrom)
* assemblea [GroupDocs.Conversion](../../../)

---

## Load(Func&lt;Stream[]&gt;) {#load}

Imposta flussi di documenti di origine array

```csharp
public IConversionLoadOptionsOrSourceDocumentLoaded Load(Func<Stream[]> documentStreamProvider)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| documentStreamProvider | Func`1 | Provider di flussi di documenti di origine |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| [InvalidConverterSettingsException](../../../groupdocs.conversion.exceptions/invalidconvertersettingsexception) |  |

### Guarda anche

* interface [IConversionLoadOptionsOrSourceDocumentLoaded](../../iconversionloadoptionsorsourcedocumentloaded)
* interface [IConversionFrom](../../iconversionfrom)
* spazio dei nomi [GroupDocs.Conversion.Fluent](../../iconversionfrom)
* assemblea [GroupDocs.Conversion](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
