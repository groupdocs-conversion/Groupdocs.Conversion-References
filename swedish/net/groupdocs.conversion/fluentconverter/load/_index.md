---
title: "Ladda"
second_title: "GroupDocs.Conversion för .NET API-referens"
description: "Konfigurera källdokument för konvertering"
type: docs
weight: 10
url: /sv/net/groupdocs.conversion/fluentconverter/load/
---
## Load(string) {#load_2}

Konfigurera källdokument för konvertering

```csharp
public static IConversionLoadOptionsOrSourceDocumentLoaded Load(string fileName)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fileName | String | Källdokument |

### Se även

* interface [IConversionLoadOptionsOrSourceDocumentLoaded](../../../groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded)
* class [FluentConverter](../../fluentconverter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Load(string[]) {#load_3}

Konfigurera uppsättning av källdokument

```csharp
public static IConversionLoadOptionsOrSourceDocumentLoaded Load(string[] fileName)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fileName | String[] | Array av källfiler. |

### Se även

* interface [IConversionLoadOptionsOrSourceDocumentLoaded](../../../groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded)
* class [FluentConverter](../../fluentconverter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Load(Func&lt;Stream&gt;) {#load_1}

Konfigurera källdokumentström

```csharp
public static IConversionLoadOptionsOrSourceDocumentLoaded Load(Func<Stream> documentStreamProvider)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| documentStreamProvider | Func`1 | Leverantör av källdokumentström |

### Se även

* interface [IConversionLoadOptionsOrSourceDocumentLoaded](../../../groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded)
* class [FluentConverter](../../fluentconverter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Load(Func&lt;Stream[]&gt;) {#load}

Konfigurera uppsättning av källdokumentströmmar

```csharp
public static IConversionLoadOptionsOrSourceDocumentLoaded Load(
    Func<Stream[]> documentStreamProvider)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| documentStreamProvider | Func`1 | Uppsättning av leverantör för strömmar av källdokument. |

### Se även

* interface [IConversionLoadOptionsOrSourceDocumentLoaded](../../../groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded)
* class [FluentConverter](../../fluentconverter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

<!-- FÅ INTE REDIGERA: genererad av xmldocmd för GroupDocs.conversion.dll -->
