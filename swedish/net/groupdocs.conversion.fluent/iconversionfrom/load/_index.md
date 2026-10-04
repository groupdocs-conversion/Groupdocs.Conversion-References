---
title: "Ladda"
second_title: "GroupDocs.Conversion för .NET API-referens"
description: "Ange filnamn för källdokument"
type: docs
weight: 10
url: /sv/net/groupdocs.conversion.fluent/iconversionfrom/load/
---
## Load(string) {#load_2}

Ange filnamn för källdokument

```csharp
public IConversionLoadOptionsOrSourceDocumentLoaded Load(string fileName)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fileName | String | Källdokument |

### Se även

* interface [IConversionLoadOptionsOrSourceDocumentLoaded](../../iconversionloadoptionsorsourcedocumentloaded)
* interface [IConversionFrom](../../iconversionfrom)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

---

## Load(string[]) {#load_3}

Ange array med källdokument

```csharp
public IConversionLoadOptionsOrSourceDocumentLoaded Load(string[] fileName)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fileName | String[] | Uppsättning av källdokument |

### Se även

* interface [IConversionLoadOptionsOrSourceDocumentLoaded](../../iconversionloadoptionsorsourcedocumentloaded)
* interface [IConversionFrom](../../iconversionfrom)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

---

## Load(Func&lt;Stream&gt;) {#load_1}

Ange källdokumentström

```csharp
public IConversionLoadOptionsOrSourceDocumentLoaded Load(Func<Stream> documentStreamProvider)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| documentStreamProvider | Func`1 | Leverantör av källdokumentström |

### Undantag

| undantag | villkor |
| --- | --- |
| [InvalidConverterSettingsException](../../../groupdocs.conversion.exceptions/invalidconvertersettingsexception) | Om validering av konverterarinställningarna misslyckas kastas detta undantag. |

### Se även

* interface [IConversionLoadOptionsOrSourceDocumentLoaded](../../iconversionloadoptionsorsourcedocumentloaded)
* interface [IConversionFrom](../../iconversionfrom)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

---

## Load(Func&lt;Stream[]&gt;) {#load}

Ange array med strömmar för källdokument

```csharp
public IConversionLoadOptionsOrSourceDocumentLoaded Load(Func<Stream[]> documentStreamProvider)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| documentStreamProvider | Func`1 | Leverantör av källdokumentströmmar |

### Undantag

| undantag | villkor |
| --- | --- |
| [InvalidConverterSettingsException](../../../groupdocs.conversion.exceptions/invalidconvertersettingsexception) | Om validering av konverterarinställningarna misslyckas kastas detta undantag. |

### Se även

* interface [IConversionLoadOptionsOrSourceDocumentLoaded](../../iconversionloadoptionsorsourcedocumentloaded)
* interface [IConversionFrom](../../iconversionfrom)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- FÅ INTE REDIGERA: genererad av xmldocmd för GroupDocs.conversion.dll -->
