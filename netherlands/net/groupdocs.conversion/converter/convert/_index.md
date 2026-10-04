---
title: "Convert"
second_title: "GroupDocs.Conversion voor .NET API-referentie"
description: "Converteert brondocument. Slaat het volledige geconverteerde document op."
type: docs
weight: 20
url: /nl/net/groupdocs.conversion/converter/convert/
---
## Convert(Func&lt;SaveContext, Stream&gt;, ConvertOptions, CancellationToken) {#convert_4}

Converteert brondocument. Slaat het volledige geconverteerde document op.

```csharp
public void Convert(Func<SaveContext, Stream> targetStreamProvider, ConvertOptions convertOptions, 
    CancellationToken cancellationToken = default)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| targetStreamProvider | Func`2 | De delegate die het geconverteerde document opslaat naar een stream. |
| convertOptions | ConvertOptions | De conversie‑opties specifiek voor het gewenste doelformaat. |
| cancellationToken | CancellationToken | Het annulerings‑token. |

### Opmerkingen

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### Zie ook

* class [SaveContext](../../savecontext)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(ConvertOptions, Action&lt;ConvertedContext&gt;, CancellationToken) {#convert}

Converteert brondocument. Slaat het volledige geconverteerde document op.

```csharp
public void Convert(ConvertOptions convertOptions, Action<ConvertedContext> documentCompleted, 
    CancellationToken cancellationToken = default)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| convertOptions | ConvertOptions | De conversie‑opties specifiek voor het gewenste doelformaat. |
| documentCompleted | Action`1 | Delegate die de geconverteerde documentstream ontvangt. Handtekening: `Action<ConvertedContext>`. De [`ConvertedContext`](../../convertedcontext) parameter bevat de geconverteerde documentstream en metadata. |
| cancellationToken | CancellationToken | Het annulerings‑token. |

### Opmerkingen

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### Zie ook

* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [ConvertedContext](../../convertedcontext)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;SaveContext, Stream&gt;, Func&lt;ConvertContext, ConvertOptions&gt;, CancellationToken) {#convert_5}

Converteert brondocument. Slaat het volledige geconverteerde document op.

```csharp
public void Convert(Func<SaveContext, Stream> targetStreamProvider, 
    Func<ConvertContext, ConvertOptions> convertOptionsProvider, 
    CancellationToken cancellationToken = default)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| targetStreamProvider | Func`2 | Delegate die de stream levert om het geconverteerde document op te slaan. Handtekening: `Func<SaveContext, Stream>`. De [`SaveContext`](../../savecontext) parameter bevat informatie over de opslagbewerking. |
| convertOptionsProvider | Func`2 | Delegate die conversie‑opties levert. Handtekening: `Func<ConvertContext, ConvertOptions>`. De [`ConvertContext`](../../convertcontext) parameter bevat informatie over de conversie‑bewerking. |
| cancellationToken | CancellationToken | Het annulerings‑token. |

### Opmerkingen

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### Zie ook

* class [SaveContext](../../savecontext)
* class [ConvertContext](../../convertcontext)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;ConvertContext, ConvertOptions&gt;, Action&lt;ConvertedContext&gt;, CancellationToken) {#convert_2}

Converteert brondocument. Slaat het volledige geconverteerde document op.

```csharp
public void Convert(Func<ConvertContext, ConvertOptions> convertOptionsProvider, 
    Action<ConvertedContext> documentCompleted, CancellationToken cancellationToken = default)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| convertOptionsProvider | Func`2 | Delegate die conversie‑opties levert. Handtekening: `Func<ConvertContext, ConvertOptions>`. De [`ConvertContext`](../../convertcontext) parameter bevat informatie over de conversie‑bewerking. |
| documentCompleted | Action`1 | Delegate die de geconverteerde documentstream ontvangt. Handtekening: `Action<ConvertedContext>`. De [`ConvertedContext`](../../convertedcontext) parameter bevat de geconverteerde documentstream en metadata. |
| cancellationToken | CancellationToken | Het annulerings‑token. |

### Opmerkingen

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### Zie ook

* class [ConvertContext](../../convertcontext)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [ConvertedContext](../../convertedcontext)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(string, ConvertOptions, CancellationToken) {#convert_8}

Converteert brondocument. Slaat het volledige geconverteerde document op.

```csharp
public void Convert(string filePath, ConvertOptions convertOptions, 
    CancellationToken cancellationToken = default)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filePath | String | Het bestandspad naar het brondocument. |
| convertOptions | ConvertOptions | De conversie‑opties specifiek voor het gewenste doelformaat. |
| cancellationToken | CancellationToken | Het annulerings‑token. |

### Opmerkingen

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### Zie ook

* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;SavePageContext, Stream&gt;, Func&lt;ConvertContext, ConvertOptions&gt;, CancellationToken) {#convert_7}

Converteert brondocument. Slaat het geconverteerde document pagina voor pagina op.

```csharp
public void Convert(Func<SavePageContext, Stream> targetStreamProvider, 
    Func<ConvertContext, ConvertOptions> convertOptionsProvider, 
    CancellationToken cancellationToken = default)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| targetStreamProvider | Func`2 | Delegate die een stream levert om elke geconverteerde pagina op te slaan. Handtekening: `Func<SavePageContext, Stream>`. De [`SavePageContext`](../../savepagecontext) parameter bevat paginanummer en documentinformatie. |
| convertOptionsProvider | Func`2 | Delegate die conversie‑opties levert. Handtekening: `Func<ConvertContext, ConvertOptions>`. De [`ConvertContext`](../../convertcontext) parameter bevat informatie over de conversie‑bewerking. |
| cancellationToken | CancellationToken | Het annulerings‑token. |

### Opmerkingen

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### Zie ook

* class [SavePageContext](../../savepagecontext)
* class [ConvertContext](../../convertcontext)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;SavePageContext, Stream&gt;, ConvertOptions, CancellationToken) {#convert_6}

Converteert brondocument. Slaat het geconverteerde document pagina voor pagina op.

```csharp
public void Convert(Func<SavePageContext, Stream> targetStreamProvider, 
    ConvertOptions convertOptions, CancellationToken cancellationToken = default)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| targetStreamProvider | Func`2 | Delegate die een stream levert om elke geconverteerde pagina op te slaan. Handtekening: `Func<SavePageContext, Stream>`. De [`SavePageContext`](../../savepagecontext) parameter bevat paginanummer en documentinformatie. |
| convertOptions | ConvertOptions | De conversie‑opties specifiek voor het gewenste doelformaat. |
| cancellationToken | CancellationToken | Het annulerings‑token. |

### Opmerkingen

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### Zie ook

* class [SavePageContext](../../savepagecontext)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(ConvertOptions, Action&lt;ConvertedPageContext&gt;, CancellationToken) {#convert_1}

Converteert brondocument. Slaat het geconverteerde document pagina voor pagina op.

```csharp
public void Convert(ConvertOptions convertOptions, Action<ConvertedPageContext> documentCompleted, 
    CancellationToken cancellationToken = default)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| documentCompleted | ConvertOptions | Delegate die elke geconverteerde pagina ontvangt. Handtekening: `Action<ConvertedPageContext>`. De [`ConvertedPageContext`](../../convertedpagecontext) parameter bevat paginanummer, stream, bronbestandsnaam en doelformaat. |
| convertOptions | Action`1 | De conversie‑opties specifiek voor het gewenste doelformaat. |
| cancellationToken | CancellationToken | Het annulerings‑token. |

### Opmerkingen

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### Zie ook

* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [ConvertedPageContext](../../convertedpagecontext)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;ConvertContext, ConvertOptions&gt;, Action&lt;ConvertedPageContext&gt;, CancellationToken) {#convert_3}

Converteert brondocument. Slaat het geconverteerde document pagina voor pagina op.

```csharp
public void Convert(Func<ConvertContext, ConvertOptions> convertOptionsProvider, 
    Action<ConvertedPageContext> documentCompleted, CancellationToken cancellationToken = default)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| convertOptionsProvider | Func`2 | Delegate die conversie‑opties levert. Handtekening: `Func<ConvertContext, ConvertOptions>`. De [`ConvertContext`](../../convertcontext) parameter bevat informatie over de conversie‑bewerking. |
| documentCompleted | Action`1 | Delegate die elke geconverteerde pagina ontvangt. Handtekening: `Action<ConvertedPageContext>`. De [`ConvertedPageContext`](../../convertedpagecontext) parameter bevat paginanummer, stream, bronbestandsnaam en doelformaat. |
| cancellationToken | CancellationToken | Het annulerings‑token. |

### Opmerkingen

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### Zie ook

* class [ConvertContext](../../convertcontext)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [ConvertedPageContext](../../convertedpagecontext)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.conversion.dll -->
