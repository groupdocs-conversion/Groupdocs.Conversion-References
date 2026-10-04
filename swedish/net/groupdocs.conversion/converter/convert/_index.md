---
title: "Konvertera"
second_title: "GroupDocs.Conversion för .NET API-referens"
description: "Konverterar källdokumentet. Sparar hela det konverterade dokumentet."
type: docs
weight: 20
url: /sv/net/groupdocs.conversion/converter/convert/
---
## Convert(Func&lt;SaveContext, Stream&gt;, ConvertOptions, CancellationToken) {#convert_4}

Konverterar källdokumentet. Sparar hela det konverterade dokumentet.

```csharp
public void Convert(Func<SaveContext, Stream> targetStreamProvider, ConvertOptions convertOptions, 
    CancellationToken cancellationToken = default)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| targetStreamProvider | Func`2 | Delegaten som sparar det konverterade dokumentet till en ström. |
| convertOptions | ConvertOptions | Konverteringsalternativen som är specifika för önskad målfiltyp. |
| cancellationToken | CancellationToken | Avbokningstokenen. |

### Anmärkningar

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### Se även

* class [SaveContext](../../savecontext)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(ConvertOptions, Action&lt;ConvertedContext&gt;, CancellationToken) {#convert}

Konverterar källdokumentet. Sparar hela det konverterade dokumentet.

```csharp
public void Convert(ConvertOptions convertOptions, Action<ConvertedContext> documentCompleted, 
    CancellationToken cancellationToken = default)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| convertOptions | ConvertOptions | Konverteringsalternativen som är specifika för önskad målfiltyp. |
| documentCompleted | Action`1 | Delegat som tar emot den konverterade dokumentströmmen. Signatur: `Action<ConvertedContext>`. Parametern [`ConvertedContext`](../../convertedcontext) innehåller den konverterade dokumentströmmen och metadata. |
| cancellationToken | CancellationToken | Avbokningstokenen. |

### Anmärkningar

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### Se även

* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [ConvertedContext](../../convertedcontext)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;SaveContext, Stream&gt;, Func&lt;ConvertContext, ConvertOptions&gt;, CancellationToken) {#convert_5}

Konverterar källdokumentet. Sparar hela det konverterade dokumentet.

```csharp
public void Convert(Func<SaveContext, Stream> targetStreamProvider, 
    Func<ConvertContext, ConvertOptions> convertOptionsProvider, 
    CancellationToken cancellationToken = default)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| targetStreamProvider | Func`2 | Delegat som tillhandahåller strömmen för att spara det konverterade dokumentet. Signatur: `Func<SaveContext, Stream>`. Parametern [`SaveContext`](../../savecontext) innehåller information om sparningsoperationen. |
| convertOptionsProvider | Func`2 | Delegat som tillhandahåller konverteringsalternativ. Signatur: `Func<ConvertContext, ConvertOptions>`. Parametern [`ConvertContext`](../../convertcontext) innehåller information om konverteringsoperationen. |
| cancellationToken | CancellationToken | Avbokningstokenen. |

### Anmärkningar

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### Se även

* class [SaveContext](../../savecontext)
* class [ConvertContext](../../convertcontext)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;ConvertContext, ConvertOptions&gt;, Action&lt;ConvertedContext&gt;, CancellationToken) {#convert_2}

Konverterar källdokumentet. Sparar hela det konverterade dokumentet.

```csharp
public void Convert(Func<ConvertContext, ConvertOptions> convertOptionsProvider, 
    Action<ConvertedContext> documentCompleted, CancellationToken cancellationToken = default)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| convertOptionsProvider | Func`2 | Delegat som tillhandahåller konverteringsalternativ. Signatur: `Func<ConvertContext, ConvertOptions>`. Parametern [`ConvertContext`](../../convertcontext) innehåller information om konverteringsoperationen. |
| documentCompleted | Action`1 | Delegat som tar emot den konverterade dokumentströmmen. Signatur: `Action<ConvertedContext>`. Parametern [`ConvertedContext`](../../convertedcontext) innehåller den konverterade dokumentströmmen och metadata. |
| cancellationToken | CancellationToken | Avbokningstokenen. |

### Anmärkningar

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### Se även

* class [ConvertContext](../../convertcontext)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [ConvertedContext](../../convertedcontext)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(string, ConvertOptions, CancellationToken) {#convert_8}

Konverterar källdokumentet. Sparar hela det konverterade dokumentet.

```csharp
public void Convert(string filePath, ConvertOptions convertOptions, 
    CancellationToken cancellationToken = default)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | String | Filvägen till källdokumentet. |
| convertOptions | ConvertOptions | Konverteringsalternativen som är specifika för önskad målfiltyp. |
| cancellationToken | CancellationToken | Avbokningstokenen. |

### Anmärkningar

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### Se även

* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;SavePageContext, Stream&gt;, Func&lt;ConvertContext, ConvertOptions&gt;, CancellationToken) {#convert_7}

Konverterar källdokumentet. Sparar det konverterade dokumentet sida för sida.

```csharp
public void Convert(Func<SavePageContext, Stream> targetStreamProvider, 
    Func<ConvertContext, ConvertOptions> convertOptionsProvider, 
    CancellationToken cancellationToken = default)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| targetStreamProvider | Func`2 | Delegat som tillhandahåller en ström för att spara varje konverterad sida. Signatur: `Func<SavePageContext, Stream>`. Parametern [`SavePageContext`](../../savepagecontext) innehåller sidnummer och dokumentinformation. |
| convertOptionsProvider | Func`2 | Delegat som tillhandahåller konverteringsalternativ. Signatur: `Func<ConvertContext, ConvertOptions>`. Parametern [`ConvertContext`](../../convertcontext) innehåller information om konverteringsoperationen. |
| cancellationToken | CancellationToken | Avbokningstokenen. |

### Anmärkningar

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### Se även

* class [SavePageContext](../../savepagecontext)
* class [ConvertContext](../../convertcontext)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;SavePageContext, Stream&gt;, ConvertOptions, CancellationToken) {#convert_6}

Konverterar källdokumentet. Sparar det konverterade dokumentet sida för sida.

```csharp
public void Convert(Func<SavePageContext, Stream> targetStreamProvider, 
    ConvertOptions convertOptions, CancellationToken cancellationToken = default)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| targetStreamProvider | Func`2 | Delegat som tillhandahåller en ström för att spara varje konverterad sida. Signatur: `Func<SavePageContext, Stream>`. Parametern [`SavePageContext`](../../savepagecontext) innehåller sidnummer och dokumentinformation. |
| convertOptions | ConvertOptions | Konverteringsalternativen som är specifika för önskad målfiltyp. |
| cancellationToken | CancellationToken | Avbokningstokenen. |

### Anmärkningar

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### Se även

* class [SavePageContext](../../savepagecontext)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(ConvertOptions, Action&lt;ConvertedPageContext&gt;, CancellationToken) {#convert_1}

Konverterar källdokumentet. Sparar det konverterade dokumentet sida för sida.

```csharp
public void Convert(ConvertOptions convertOptions, Action<ConvertedPageContext> documentCompleted, 
    CancellationToken cancellationToken = default)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| documentCompleted | ConvertOptions | Delegat som tar emot varje konverterad sida. Signatur: `Action<ConvertedPageContext>`. Parametern [`ConvertedPageContext`](../../convertedpagecontext) innehåller sidnummer, ström, källfilnamn och målfiltyp. |
| convertOptions | Action`1 | Konverteringsalternativen som är specifika för önskad målfiltyp. |
| cancellationToken | CancellationToken | Avbokningstokenen. |

### Anmärkningar

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### Se även

* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [ConvertedPageContext](../../convertedpagecontext)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;ConvertContext, ConvertOptions&gt;, Action&lt;ConvertedPageContext&gt;, CancellationToken) {#convert_3}

Konverterar källdokumentet. Sparar det konverterade dokumentet sida för sida.

```csharp
public void Convert(Func<ConvertContext, ConvertOptions> convertOptionsProvider, 
    Action<ConvertedPageContext> documentCompleted, CancellationToken cancellationToken = default)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| convertOptionsProvider | Func`2 | Delegat som tillhandahåller konverteringsalternativ. Signatur: `Func<ConvertContext, ConvertOptions>`. Parametern [`ConvertContext`](../../convertcontext) innehåller information om konverteringsoperationen. |
| documentCompleted | Action`1 | Delegat som tar emot varje konverterad sida. Signatur: `Action<ConvertedPageContext>`. Parametern [`ConvertedPageContext`](../../convertedpagecontext) innehåller sidnummer, ström, källfilnamn och målfiltyp. |
| cancellationToken | CancellationToken | Avbokningstokenen. |

### Anmärkningar

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### Se även

* class [ConvertContext](../../convertcontext)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [ConvertedPageContext](../../convertedpagecontext)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

<!-- FÅ INTE REDIGERA: genererad av xmldocmd för GroupDocs.conversion.dll -->
