---
title: "Laden"
second_title: "GroupDocs.Conversion voor .NET API-referentie"
description: "Stel bestandsnaam van brondocument in"
type: docs
weight: 10
url: /nl/net/groupdocs.conversion.fluent/iconversionfrom/load/
---
## Load(string) {#load_2}

Stel bestandsnaam van brondocument in

```csharp
public IConversionLoadOptionsOrSourceDocumentLoaded Load(string fileName)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fileName | String | Brondocument |

### Zie ook

* interface [IConversionLoadOptionsOrSourceDocumentLoaded](../../iconversionloadoptionsorsourcedocumentloaded)
* interface [IConversionFrom](../../iconversionfrom)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

---

## Load(string[]) {#load_3}

Stel array met brondocumenten in

```csharp
public IConversionLoadOptionsOrSourceDocumentLoaded Load(string[] fileName)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fileName | String[] | Set van brondocumenten |

### Zie ook

* interface [IConversionLoadOptionsOrSourceDocumentLoaded](../../iconversionloadoptionsorsourcedocumentloaded)
* interface [IConversionFrom](../../iconversionfrom)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

---

## Load(Func&lt;Stream&gt;) {#load_1}

Stel brondocumentstroom in

```csharp
public IConversionLoadOptionsOrSourceDocumentLoaded Load(Func<Stream> documentStreamProvider)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| documentStreamProvider | Func`1 | Provider voor brondocumentstroom |

### Uitzonderingen

| uitzondering | conditie |
| --- | --- |
| [InvalidConverterSettingsException](../../../groupdocs.conversion.exceptions/invalidconvertersettingsexception) | Als de validatie van converterinstellingen mislukt, wordt deze uitzondering gegooid |

### Zie ook

* interface [IConversionLoadOptionsOrSourceDocumentLoaded](../../iconversionloadoptionsorsourcedocumentloaded)
* interface [IConversionFrom](../../iconversionfrom)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

---

## Load(Func&lt;Stream[]&gt;) {#load}

Stel array met stromen van brondocumenten in

```csharp
public IConversionLoadOptionsOrSourceDocumentLoaded Load(Func<Stream[]> documentStreamProvider)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| documentStreamProvider | Func`1 | Provider voor brondocumentstreams |

### Uitzonderingen

| uitzondering | conditie |
| --- | --- |
| [InvalidConverterSettingsException](../../../groupdocs.conversion.exceptions/invalidconvertersettingsexception) | Als de validatie van converterinstellingen mislukt, wordt deze uitzondering gegooid |

### Zie ook

* interface [IConversionLoadOptionsOrSourceDocumentLoaded](../../iconversionloadoptionsorsourcedocumentloaded)
* interface [IConversionFrom](../../iconversionfrom)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.conversion.dll -->
