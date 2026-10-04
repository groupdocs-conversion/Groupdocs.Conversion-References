---
title: "Convert"
second_title: "Riferimento API di GroupDocs.Conversion per .NET"
description: "Converte il documento di origine. Salva l'intero documento convertito."
type: docs
weight: 20
url: /it/net/groupdocs.conversion/converter/convert/
---
## Convert(Func&lt;SaveContext, Stream&gt;, ConvertOptions, CancellationToken) {#convert_4}

Converte il documento di origine. Salva l'intero documento convertito.

```csharp
public void Convert(Func<SaveContext, Stream> targetStreamProvider, ConvertOptions convertOptions, 
    CancellationToken cancellationToken = default)
```

| Parameter | Type | Descrizione |
| --- | --- | --- |
| targetStreamProvider | Func`2 | Il delegato che salva il documento convertito in un flusso. |
| convertOptions | ConvertOptions | Le opzioni di conversione specifiche per il tipo di file di destinazione desiderato. |
| cancellationToken | CancellationToken | Il token di cancellazione. |

### Osservazioni

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### IConversionConvertOptions

* class [SaveContext](../../savecontext)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(ConvertOptions, Action&lt;ConvertedContext&gt;, CancellationToken) {#convert}

Converte il documento di origine. Salva l'intero documento convertito.

```csharp
public void Convert(ConvertOptions convertOptions, Action<ConvertedContext> documentCompleted, 
    CancellationToken cancellationToken = default)
```

| Parameter | Type | Descrizione |
| --- | --- | --- |
| convertOptions | ConvertOptions | Le opzioni di conversione specifiche per il tipo di file di destinazione desiderato. |
| documentCompleted | Action`1 | Delegato che riceve il flusso del documento convertito. Firma: `Action<ConvertedContext>`. Il parametro [`ConvertedContext`](../../convertedcontext) contiene il flusso del documento convertito e i metadati. |
| cancellationToken | CancellationToken | Il token di cancellazione. |

### Osservazioni

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### IConversionConvertOptions

* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [ConvertedContext](../../convertedcontext)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;SaveContext, Stream&gt;, Func&lt;ConvertContext, ConvertOptions&gt;, CancellationToken) {#convert_5}

Converte il documento di origine. Salva l'intero documento convertito.

```csharp
public void Convert(Func<SaveContext, Stream> targetStreamProvider, 
    Func<ConvertContext, ConvertOptions> convertOptionsProvider, 
    CancellationToken cancellationToken = default)
```

| Parameter | Type | Descrizione |
| --- | --- | --- |
| targetStreamProvider | Func`2 | Delegato che fornisce il flusso per salvare il documento convertito. Firma: `Func<SaveContext, Stream>`. Il parametro [`SaveContext`](../../savecontext) contiene informazioni sull'operazione di salvataggio. |
| convertOptionsProvider | Func`2 | Delegato che fornisce le opzioni di conversione. Firma: `Func<ConvertContext, ConvertOptions>`. Il parametro [`ConvertContext`](../../convertcontext) contiene informazioni sull'operazione di conversione. |
| cancellationToken | CancellationToken | Il token di cancellazione. |

### Osservazioni

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### IConversionConvertOptions

* class [SaveContext](../../savecontext)
* class [ConvertContext](../../convertcontext)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;ConvertContext, ConvertOptions&gt;, Action&lt;ConvertedContext&gt;, CancellationToken) {#convert_2}

Converte il documento di origine. Salva l'intero documento convertito.

```csharp
public void Convert(Func<ConvertContext, ConvertOptions> convertOptionsProvider, 
    Action<ConvertedContext> documentCompleted, CancellationToken cancellationToken = default)
```

| Parameter | Type | Descrizione |
| --- | --- | --- |
| convertOptionsProvider | Func`2 | Delegato che fornisce le opzioni di conversione. Firma: `Func<ConvertContext, ConvertOptions>`. Il parametro [`ConvertContext`](../../convertcontext) contiene informazioni sull'operazione di conversione. |
| documentCompleted | Action`1 | Delegato che riceve il flusso del documento convertito. Firma: `Action<ConvertedContext>`. Il parametro [`ConvertedContext`](../../convertedcontext) contiene il flusso del documento convertito e i metadati. |
| cancellationToken | CancellationToken | Il token di cancellazione. |

### Osservazioni

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### IConversionConvertOptions

* class [ConvertContext](../../convertcontext)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [ConvertedContext](../../convertedcontext)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(string, ConvertOptions, CancellationToken) {#convert_8}

Converte il documento di origine. Salva l'intero documento convertito.

```csharp
public void Convert(string filePath, ConvertOptions convertOptions, 
    CancellationToken cancellationToken = default)
```

| Parameter | Type | Descrizione |
| --- | --- | --- |
| filePath | String | Il percorso del file del documento di origine. |
| convertOptions | ConvertOptions | Le opzioni di conversione specifiche per il tipo di file di destinazione desiderato. |
| cancellationToken | CancellationToken | Il token di cancellazione. |

### Osservazioni

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### IConversionConvertOptions

* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;SavePageContext, Stream&gt;, Func&lt;ConvertContext, ConvertOptions&gt;, CancellationToken) {#convert_7}

Converte il documento di origine. Salva il documento convertito pagina per pagina.

```csharp
public void Convert(Func<SavePageContext, Stream> targetStreamProvider, 
    Func<ConvertContext, ConvertOptions> convertOptionsProvider, 
    CancellationToken cancellationToken = default)
```

| Parameter | Type | Descrizione |
| --- | --- | --- |
| targetStreamProvider | Func`2 | Delegato che fornisce un flusso per salvare ogni pagina convertita. Firma: `Func<SavePageContext, Stream>`. Il parametro [`SavePageContext`](../../savepagecontext) contiene il numero di pagina e le informazioni del documento. |
| convertOptionsProvider | Func`2 | Delegato che fornisce le opzioni di conversione. Firma: `Func<ConvertContext, ConvertOptions>`. Il parametro [`ConvertContext`](../../convertcontext) contiene informazioni sull'operazione di conversione. |
| cancellationToken | CancellationToken | Il token di cancellazione. |

### Osservazioni

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### IConversionConvertOptions

* class [SavePageContext](../../savepagecontext)
* class [ConvertContext](../../convertcontext)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;SavePageContext, Stream&gt;, ConvertOptions, CancellationToken) {#convert_6}

Converte il documento di origine. Salva il documento convertito pagina per pagina.

```csharp
public void Convert(Func<SavePageContext, Stream> targetStreamProvider, 
    ConvertOptions convertOptions, CancellationToken cancellationToken = default)
```

| Parameter | Type | Descrizione |
| --- | --- | --- |
| targetStreamProvider | Func`2 | Delegato che fornisce un flusso per salvare ogni pagina convertita. Firma: `Func<SavePageContext, Stream>`. Il parametro [`SavePageContext`](../../savepagecontext) contiene il numero di pagina e le informazioni del documento. |
| convertOptions | ConvertOptions | Le opzioni di conversione specifiche per il tipo di file di destinazione desiderato. |
| cancellationToken | CancellationToken | Il token di cancellazione. |

### Osservazioni

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### IConversionConvertOptions

* class [SavePageContext](../../savepagecontext)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(ConvertOptions, Action&lt;ConvertedPageContext&gt;, CancellationToken) {#convert_1}

Converte il documento di origine. Salva il documento convertito pagina per pagina.

```csharp
public void Convert(ConvertOptions convertOptions, Action<ConvertedPageContext> documentCompleted, 
    CancellationToken cancellationToken = default)
```

| Parameter | Type | Descrizione |
| --- | --- | --- |
| documentCompleted | ConvertOptions | Delegato che riceve ogni pagina convertita. Firma: `Action<ConvertedPageContext>`. Il parametro [`ConvertedPageContext`](../../convertedpagecontext) contiene il numero di pagina, il flusso, il nome del file di origine e il tipo di file di destinazione. |
| convertOptions | Action`1 | Le opzioni di conversione specifiche per il tipo di file di destinazione desiderato. |
| cancellationToken | CancellationToken | Il token di cancellazione. |

### Osservazioni

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### IConversionConvertOptions

* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [ConvertedPageContext](../../convertedpagecontext)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;ConvertContext, ConvertOptions&gt;, Action&lt;ConvertedPageContext&gt;, CancellationToken) {#convert_3}

Converte il documento di origine. Salva il documento convertito pagina per pagina.

```csharp
public void Convert(Func<ConvertContext, ConvertOptions> convertOptionsProvider, 
    Action<ConvertedPageContext> documentCompleted, CancellationToken cancellationToken = default)
```

| Parameter | Type | Descrizione |
| --- | --- | --- |
| convertOptionsProvider | Func`2 | Delegato che fornisce le opzioni di conversione. Firma: `Func<ConvertContext, ConvertOptions>`. Il parametro [`ConvertContext`](../../convertcontext) contiene informazioni sull'operazione di conversione. |
| documentCompleted | Action`1 | Delegato che riceve ogni pagina convertita. Firma: `Action<ConvertedPageContext>`. Il parametro [`ConvertedPageContext`](../../convertedpagecontext) contiene il numero di pagina, il flusso, il nome del file di origine e il tipo di file di destinazione. |
| cancellationToken | CancellationToken | Il token di cancellazione. |

### Osservazioni

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### IConversionConvertOptions

* class [ConvertContext](../../convertcontext)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [ConvertedPageContext](../../convertedpagecontext)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.conversion.dll -->
