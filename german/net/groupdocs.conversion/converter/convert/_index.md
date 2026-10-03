---
title: "Convert"
second_title: "GroupDocs.Conversion für .NET API-Referenz"
description: "Konvertiert das Quelldokument. Speichert das gesamte konvertierte Dokument."
type: docs
weight: 20
url: /de/net/groupdocs.conversion/converter/convert/
---
## Convert(Func&lt;SaveContext, Stream&gt;, ConvertOptions, CancellationToken) {#convert_4}

Konvertiert das Quelldokument. Speichert das gesamte konvertierte Dokument.

```csharp
public void Convert(Func<SaveContext, Stream> targetStreamProvider, ConvertOptions convertOptions, 
    CancellationToken cancellationToken = default)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| targetStreamProvider | Func`2 | Der Delegat, der das konvertierte Dokument in einen Stream speichert. |
| convertOptions | ConvertOptions | Die Konvertierungsoptionen, die für den gewünschten Zieldateityp spezifisch sind. |
| cancellationToken | CancellationToken | Das Abbruch-Token. |

### Hinweise

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### Siehe auch

* class [SaveContext](../../savecontext)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(ConvertOptions, Action&lt;ConvertedContext&gt;, CancellationToken) {#convert}

Konvertiert das Quelldokument. Speichert das gesamte konvertierte Dokument.

```csharp
public void Convert(ConvertOptions convertOptions, Action<ConvertedContext> documentCompleted, 
    CancellationToken cancellationToken = default)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| convertOptions | ConvertOptions | Die Konvertierungsoptionen, die für den gewünschten Zieldateityp spezifisch sind. |
| documentCompleted | Action`1 | Delegat, der den konvertierten Dokumenten-Stream empfängt. Signatur: `Action<ConvertedContext>`. Der [`ConvertedContext`](../../convertedcontext)-Parameter enthält den konvertierten Dokumenten-Stream und Metadaten. |
| cancellationToken | CancellationToken | Das Abbruch-Token. |

### Hinweise

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### Siehe auch

* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [ConvertedContext](../../convertedcontext)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;SaveContext, Stream&gt;, Func&lt;ConvertContext, ConvertOptions&gt;, CancellationToken) {#convert_5}

Konvertiert das Quelldokument. Speichert das gesamte konvertierte Dokument.

```csharp
public void Convert(Func<SaveContext, Stream> targetStreamProvider, 
    Func<ConvertContext, ConvertOptions> convertOptionsProvider, 
    CancellationToken cancellationToken = default)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| targetStreamProvider | Func`2 | Delegat, der den Stream zum Speichern des konvertierten Dokuments bereitstellt. Signature: `Func<SaveContext, Stream>`. Der Parameter [`SaveContext`](../../savecontext) enthält Informationen über den Speichervorgang. |
| convertOptionsProvider | Func`2 | Delegat, der Konvertierungsoptionen bereitstellt. Signature: `Func<ConvertContext, ConvertOptions>`. Der Parameter [`ConvertContext`](../../convertcontext) enthält Informationen über den Konvertierungsvorgang. |
| cancellationToken | CancellationToken | Das Abbruch-Token. |

### Hinweise

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### Siehe auch

* class [SaveContext](../../savecontext)
* class [ConvertContext](../../convertcontext)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;ConvertContext, ConvertOptions&gt;, Action&lt;ConvertedContext&gt;, CancellationToken) {#convert_2}

Konvertiert das Quelldokument. Speichert das gesamte konvertierte Dokument.

```csharp
public void Convert(Func<ConvertContext, ConvertOptions> convertOptionsProvider, 
    Action<ConvertedContext> documentCompleted, CancellationToken cancellationToken = default)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| convertOptionsProvider | Func`2 | Delegat, der Konvertierungsoptionen bereitstellt. Signature: `Func<ConvertContext, ConvertOptions>`. Der Parameter [`ConvertContext`](../../convertcontext) enthält Informationen über den Konvertierungsvorgang. |
| documentCompleted | Action`1 | Delegat, der den konvertierten Dokumenten-Stream empfängt. Signatur: `Action<ConvertedContext>`. Der [`ConvertedContext`](../../convertedcontext)-Parameter enthält den konvertierten Dokumenten-Stream und Metadaten. |
| cancellationToken | CancellationToken | Das Abbruch-Token. |

### Hinweise

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### Siehe auch

* class [ConvertContext](../../convertcontext)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [ConvertedContext](../../convertedcontext)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(string, ConvertOptions, CancellationToken) {#convert_8}

Konvertiert das Quelldokument. Speichert das gesamte konvertierte Dokument.

```csharp
public void Convert(string filePath, ConvertOptions convertOptions, 
    CancellationToken cancellationToken = default)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | String | Der Dateipfad zur Quelldatei. |
| convertOptions | ConvertOptions | Die Konvertierungsoptionen, die für den gewünschten Zieldateityp spezifisch sind. |
| cancellationToken | CancellationToken | Das Abbruch-Token. |

### Hinweise

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### Siehe auch

* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;SavePageContext, Stream&gt;, Func&lt;ConvertContext, ConvertOptions&gt;, CancellationToken) {#convert_7}

Konvertiert das Quelldokument. Speichert das konvertierte Dokument seitenweise.

```csharp
public void Convert(Func<SavePageContext, Stream> targetStreamProvider, 
    Func<ConvertContext, ConvertOptions> convertOptionsProvider, 
    CancellationToken cancellationToken = default)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| targetStreamProvider | Func`2 | Delegat, der einen Stream zum Speichern jeder konvertierten Seite bereitstellt. Signature: `Func<SavePageContext, Stream>`. Der Parameter [`SavePageContext`](../../savepagecontext) enthält Seitenzahl und Dokumentinformationen. |
| convertOptionsProvider | Func`2 | Delegat, der Konvertierungsoptionen bereitstellt. Signature: `Func<ConvertContext, ConvertOptions>`. Der Parameter [`ConvertContext`](../../convertcontext) enthält Informationen über den Konvertierungsvorgang. |
| cancellationToken | CancellationToken | Das Abbruch-Token. |

### Hinweise

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### Siehe auch

* class [SavePageContext](../../savepagecontext)
* class [ConvertContext](../../convertcontext)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;SavePageContext, Stream&gt;, ConvertOptions, CancellationToken) {#convert_6}

Konvertiert das Quelldokument. Speichert das konvertierte Dokument seitenweise.

```csharp
public void Convert(Func<SavePageContext, Stream> targetStreamProvider, 
    ConvertOptions convertOptions, CancellationToken cancellationToken = default)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| targetStreamProvider | Func`2 | Delegat, der einen Stream zum Speichern jeder konvertierten Seite bereitstellt. Signature: `Func<SavePageContext, Stream>`. Der Parameter [`SavePageContext`](../../savepagecontext) enthält Seitenzahl und Dokumentinformationen. |
| convertOptions | ConvertOptions | Die Konvertierungsoptionen, die für den gewünschten Zieldateityp spezifisch sind. |
| cancellationToken | CancellationToken | Das Abbruch-Token. |

### Hinweise

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### Siehe auch

* class [SavePageContext](../../savepagecontext)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(ConvertOptions, Action&lt;ConvertedPageContext&gt;, CancellationToken) {#convert_1}

Konvertiert das Quelldokument. Speichert das konvertierte Dokument seitenweise.

```csharp
public void Convert(ConvertOptions convertOptions, Action<ConvertedPageContext> documentCompleted, 
    CancellationToken cancellationToken = default)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| documentCompleted | ConvertOptions | Delegat, der jede konvertierte Seite empfängt. Signature: `Action<ConvertedPageContext>`. Der Parameter [`ConvertedPageContext`](../../convertedpagecontext) enthält Seitenzahl, Stream, Quelldateinamen und Zieldateityp. |
| convertOptions | Action`1 | Die Konvertierungsoptionen, die für den gewünschten Zieldateityp spezifisch sind. |
| cancellationToken | CancellationToken | Das Abbruch-Token. |

### Hinweise

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### Siehe auch

* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [ConvertedPageContext](../../convertedpagecontext)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;ConvertContext, ConvertOptions&gt;, Action&lt;ConvertedPageContext&gt;, CancellationToken) {#convert_3}

Konvertiert das Quelldokument. Speichert das konvertierte Dokument seitenweise.

```csharp
public void Convert(Func<ConvertContext, ConvertOptions> convertOptionsProvider, 
    Action<ConvertedPageContext> documentCompleted, CancellationToken cancellationToken = default)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| convertOptionsProvider | Func`2 | Delegat, der Konvertierungsoptionen bereitstellt. Signature: `Func<ConvertContext, ConvertOptions>`. Der Parameter [`ConvertContext`](../../convertcontext) enthält Informationen über den Konvertierungsvorgang. |
| documentCompleted | Action`1 | Delegat, der jede konvertierte Seite empfängt. Signature: `Action<ConvertedPageContext>`. Der Parameter [`ConvertedPageContext`](../../convertedpagecontext) enthält Seitenzahl, Stream, Quelldateinamen und Zieldateityp. |
| cancellationToken | CancellationToken | Das Abbruch-Token. |

### Hinweise

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### Siehe auch

* class [ConvertContext](../../convertcontext)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [ConvertedPageContext](../../convertedpagecontext)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.conversion.dll -->
