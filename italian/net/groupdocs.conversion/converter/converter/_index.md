---
title: "Converter"
second_title: "Riferimento API di GroupDocs.Conversion per .NET"
description: "Inizializza una nuova istanza della classe Convertergroupdocs.conversion/converter."
type: docs
weight: 10
url: /it/net/groupdocs.conversion/converter/converter/
---
## Converter(Func&lt;Stream&gt;) {#constructor}

Inizializza una nuova istanza della classe [`Converter`](../../converter).

```csharp
public Converter(Func<Stream> sourceStreamProvider)
```

| Parameter | Type | Descrizione |
| --- | --- | --- |
| sourceStreamProvider | Func`1 | Il metodo che restituisce un flusso leggibile. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | Generato quando *sourceStreamProvider* è nullo. |

### Osservazioni

**Learn more**

* More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* More about document loading options dependent on file type: [Load options for different document types](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### IConversionConvertOptions

* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;ConverterSettings&gt;) {#constructor_1}

Inizializza una nuova istanza della classe [`Converter`](../../converter).

```csharp
public Converter(Func<Stream> sourceStreamProvider, Func<ConverterSettings> settings)
```

| Parameter | Type | Descrizione |
| --- | --- | --- |
| sourceStreamProvider | Func`1 | Il metodo che restituisce un flusso leggibile. |
| settings | Func`1 | Le impostazioni del Converter. |

### Osservazioni

**Learn more**

* More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* More about document loading options dependent on file type: [Load options for different document types](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### IConversionConvertOptions

* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;LoadContext, LoadOptions&gt;, Func&lt;ConverterSettings&gt;) {#constructor_3}

Inizializza una nuova istanza della classe [`Converter`](../../converter).

```csharp
public Converter(Func<Stream> sourceStreamProvider, Func<LoadContext, LoadOptions> loadOptions, 
    Func<ConverterSettings> settings = null)
```

| Parameter | Type | Descrizione |
| --- | --- | --- |
| sourceStreamProvider | Func`1 | Il metodo che restituisce un flusso leggibile. |
| loadOptions | Func`2 | Delegato che fornisce le opzioni di caricamento per il documento. Firma: `Func<LoadContext, LoadOptions>`. Il parametro [`LoadContext`](../../loadcontext) contiene informazioni sul documento caricato. |
| settings | Func`1 | Le impostazioni del Converter. |

### Osservazioni

**Learn more**

* More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* More about document loading options dependent on file type: [Load options for different document types](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### IConversionConvertOptions

* class [LoadContext](../../loadcontext)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;LoadContext, LoadOptions&gt;, Func&lt;ConverterSettings&gt;, Func&lt;ConversionEvents&gt;) {#constructor_4}

Inizializza una nuova istanza della classe [`Converter`](../../converter) con eventi di conversione espliciti.

```csharp
public Converter(Func<Stream> sourceStreamProvider, Func<LoadContext, LoadOptions> loadOptions, 
    Func<ConverterSettings> settings, Func<ConversionEvents> events)
```

| Parameter | Type | Descrizione |
| --- | --- | --- |
| sourceStreamProvider | Func`1 | Il metodo che restituisce un flusso leggibile. |
| loadOptions | Func`2 | Delegato che fornisce le opzioni di caricamento per il documento. |
| settings | Func`1 | Le impostazioni del Converter. |
| events | Func`1 | Delegato che fornisce gli [`ConversionEvents`](../../conversionevents) aggregati registrati per la durata del convertitore. |

### IConversionConvertOptions

* class [LoadContext](../../loadcontext)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [ConverterSettings](../../convertersettings)
* class [ConversionEvents](../../conversionevents)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;ConverterSettings&gt;, Func&lt;ConversionEvents&gt;) {#constructor_2}

Inizializza una nuova istanza della classe [`Converter`](../../converter) con eventi di conversione espliciti.

```csharp
public Converter(Func<Stream> sourceStreamProvider, Func<ConverterSettings> settings, 
    Func<ConversionEvents> events)
```

| Parameter | Type | Descrizione |
| --- | --- | --- |
| sourceStreamProvider | Func`1 | Il metodo che restituisce un flusso leggibile. |
| settings | Func`1 | Le impostazioni del Converter. |
| events | Func`1 | Delegato che fornisce gli [`ConversionEvents`](../../conversionevents) aggregati registrati per la durata del convertitore. |

### IConversionConvertOptions

* class [ConverterSettings](../../convertersettings)
* class [ConversionEvents](../../conversionevents)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(string) {#constructor_5}

Inizializza una nuova istanza della classe [`Converter`](../../converter).

```csharp
public Converter(string filePath)
```

| Parameter | Type | Descrizione |
| --- | --- | --- |
| filePath | String | Il percorso del file del documento di origine. |

### Osservazioni

**Learn more**

* More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* More about document loading options dependent on file type: [Load options for different document types](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### IConversionConvertOptions

* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;ConverterSettings&gt;) {#constructor_6}

Inizializza una nuova istanza della classe [`Converter`](../../converter).

```csharp
public Converter(string filePath, Func<ConverterSettings> settings)
```

| Parameter | Type | Descrizione |
| --- | --- | --- |
| filePath | String | Il percorso del file del documento di origine. |
| settings | Func`1 | Le impostazioni del Converter. |

### Osservazioni

**Learn more**

* More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* More about document loading options dependent on file type: [Load options for different document types](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### IConversionConvertOptions

* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;LoadContext, LoadOptions&gt;, Func&lt;ConverterSettings&gt;) {#constructor_8}

Inizializza una nuova istanza della classe [`Converter`](../../converter).

```csharp
public Converter(string filePath, Func<LoadContext, LoadOptions> loadOptions, 
    Func<ConverterSettings> settings = null)
```

| Parameter | Type | Descrizione |
| --- | --- | --- |
| filePath | String | Il percorso del file del documento di origine. |
| loadOptions | Func`2 | Delegato che fornisce le opzioni di caricamento per il documento. Firma: `Func<LoadContext, LoadOptions>`. Il parametro [`LoadContext`](../../loadcontext) contiene informazioni sul documento caricato. |
| settings | Func`1 | Le impostazioni del Converter. |

### Osservazioni

**Learn more**

* More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* More about document loading options dependent on file type: [Load options for different document types](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### IConversionConvertOptions

* class [LoadContext](../../loadcontext)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;LoadContext, LoadOptions&gt;, Func&lt;ConverterSettings&gt;, Func&lt;ConversionEvents&gt;) {#constructor_9}

Inizializza una nuova istanza della classe [`Converter`](../../converter) con eventi di conversione espliciti.

```csharp
public Converter(string filePath, Func<LoadContext, LoadOptions> loadOptions, 
    Func<ConverterSettings> settings, Func<ConversionEvents> events)
```

| Parameter | Type | Descrizione |
| --- | --- | --- |
| filePath | String | Il percorso del file del documento di origine. |
| loadOptions | Func`2 | Delegato che fornisce le opzioni di caricamento per il documento. |
| settings | Func`1 | Le impostazioni del Converter. |
| events | Func`1 | Delegato che fornisce gli [`ConversionEvents`](../../conversionevents) aggregati registrati per la durata del convertitore. |

### IConversionConvertOptions

* class [LoadContext](../../loadcontext)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [ConverterSettings](../../convertersettings)
* class [ConversionEvents](../../conversionevents)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;ConverterSettings&gt;, Func&lt;ConversionEvents&gt;) {#constructor_7}

Inizializza una nuova istanza della classe [`Converter`](../../converter) con eventi di conversione espliciti.

```csharp
public Converter(string filePath, Func<ConverterSettings> settings, Func<ConversionEvents> events)
```

| Parameter | Type | Descrizione |
| --- | --- | --- |
| filePath | String | Il percorso del file del documento di origine. |
| settings | Func`1 | Le impostazioni del Converter. |
| events | Func`1 | Delegato che fornisce gli [`ConversionEvents`](../../conversionevents) aggregati registrati per la durata del convertitore. |

### IConversionConvertOptions

* class [ConverterSettings](../../convertersettings)
* class [ConversionEvents](../../conversionevents)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.conversion.dll -->
