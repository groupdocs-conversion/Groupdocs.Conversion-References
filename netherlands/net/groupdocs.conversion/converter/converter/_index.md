---
title: "Converter"
second_title: "GroupDocs.Conversion voor .NET API-referentie"
description: "Initialiseert een nieuwe instantie van de Convertergroupdocs.conversion/converter‑klasse."
type: docs
weight: 10
url: /nl/net/groupdocs.conversion/converter/converter/
---
## Converter(Func&lt;Stream&gt;) {#constructor}

Initialiseert een nieuwe instantie van de [`Converter`](../../converter)‑klasse.

```csharp
public Converter(Func<Stream> sourceStreamProvider)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourceStreamProvider | Func`1 | De methode die een leesbare stream retourneert. |

### Uitzonderingen

| uitzondering | conditie |
| --- | --- |
| ArgumentNullException | Wordt gegooid wanneer *sourceStreamProvider* null is. |

### Opmerkingen

**Learn more**

* More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* More about document loading options dependent on file type: [Load options for different document types](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Zie ook

* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;ConverterSettings&gt;) {#constructor_1}

Initialiseert een nieuwe instantie van de [`Converter`](../../converter)‑klasse.

```csharp
public Converter(Func<Stream> sourceStreamProvider, Func<ConverterSettings> settings)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourceStreamProvider | Func`1 | De methode die een leesbare stream retourneert. |
| settings | Func`1 | De Converter‑instellingen. |

### Opmerkingen

**Learn more**

* More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* More about document loading options dependent on file type: [Load options for different document types](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Zie ook

* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;LoadContext, LoadOptions&gt;, Func&lt;ConverterSettings&gt;) {#constructor_3}

Initialiseert een nieuwe instantie van de [`Converter`](../../converter)‑klasse.

```csharp
public Converter(Func<Stream> sourceStreamProvider, Func<LoadContext, LoadOptions> loadOptions, 
    Func<ConverterSettings> settings = null)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourceStreamProvider | Func`1 | De methode die een leesbare stream retourneert. |
| loadOptions | Func`2 | Delegate die laadopties voor het document levert. Handtekening: `Func<LoadContext, LoadOptions>`. De [`LoadContext`](../../loadcontext) parameter bevat informatie over het te laden document. |
| settings | Func`1 | De Converter‑instellingen. |

### Opmerkingen

**Learn more**

* More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* More about document loading options dependent on file type: [Load options for different document types](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Zie ook

* class [LoadContext](../../loadcontext)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;LoadContext, LoadOptions&gt;, Func&lt;ConverterSettings&gt;, Func&lt;ConversionEvents&gt;) {#constructor_4}

Initialiseert een nieuwe instantie van de [`Converter`](../../converter) klasse met expliciete conversiegebeurtenissen.

```csharp
public Converter(Func<Stream> sourceStreamProvider, Func<LoadContext, LoadOptions> loadOptions, 
    Func<ConverterSettings> settings, Func<ConversionEvents> events)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourceStreamProvider | Func`1 | De methode die een leesbare stream retourneert. |
| loadOptions | Func`2 | Delegate die laadopties voor het document levert. |
| settings | Func`1 | De Converter‑instellingen. |
| events | Func`1 | Delegate die geaggregeerde [`ConversionEvents`](../../conversionevents) levert die geregistreerd zijn voor de levensduur van de converter. |

### Zie ook

* class [LoadContext](../../loadcontext)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [ConverterSettings](../../convertersettings)
* class [ConversionEvents](../../conversionevents)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;ConverterSettings&gt;, Func&lt;ConversionEvents&gt;) {#constructor_2}

Initialiseert een nieuwe instantie van de [`Converter`](../../converter) klasse met expliciete conversiegebeurtenissen.

```csharp
public Converter(Func<Stream> sourceStreamProvider, Func<ConverterSettings> settings, 
    Func<ConversionEvents> events)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourceStreamProvider | Func`1 | De methode die een leesbare stream retourneert. |
| settings | Func`1 | De Converter‑instellingen. |
| events | Func`1 | Delegate die geaggregeerde [`ConversionEvents`](../../conversionevents) levert die geregistreerd zijn voor de levensduur van de converter. |

### Zie ook

* class [ConverterSettings](../../convertersettings)
* class [ConversionEvents](../../conversionevents)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(string) {#constructor_5}

Initialiseert een nieuwe instantie van de [`Converter`](../../converter)‑klasse.

```csharp
public Converter(string filePath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filePath | String | Het bestandspad naar het brondocument. |

### Opmerkingen

**Learn more**

* More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* More about document loading options dependent on file type: [Load options for different document types](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Zie ook

* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;ConverterSettings&gt;) {#constructor_6}

Initialiseert een nieuwe instantie van de [`Converter`](../../converter)‑klasse.

```csharp
public Converter(string filePath, Func<ConverterSettings> settings)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filePath | String | Het bestandspad naar het brondocument. |
| settings | Func`1 | De Converter‑instellingen. |

### Opmerkingen

**Learn more**

* More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* More about document loading options dependent on file type: [Load options for different document types](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Zie ook

* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;LoadContext, LoadOptions&gt;, Func&lt;ConverterSettings&gt;) {#constructor_8}

Initialiseert een nieuwe instantie van de [`Converter`](../../converter)‑klasse.

```csharp
public Converter(string filePath, Func<LoadContext, LoadOptions> loadOptions, 
    Func<ConverterSettings> settings = null)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filePath | String | Het bestandspad naar het brondocument. |
| loadOptions | Func`2 | Delegate die laadopties voor het document levert. Handtekening: `Func<LoadContext, LoadOptions>`. De [`LoadContext`](../../loadcontext) parameter bevat informatie over het te laden document. |
| settings | Func`1 | De Converter‑instellingen. |

### Opmerkingen

**Learn more**

* More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* More about document loading options dependent on file type: [Load options for different document types](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Zie ook

* class [LoadContext](../../loadcontext)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;LoadContext, LoadOptions&gt;, Func&lt;ConverterSettings&gt;, Func&lt;ConversionEvents&gt;) {#constructor_9}

Initialiseert een nieuwe instantie van de [`Converter`](../../converter) klasse met expliciete conversiegebeurtenissen.

```csharp
public Converter(string filePath, Func<LoadContext, LoadOptions> loadOptions, 
    Func<ConverterSettings> settings, Func<ConversionEvents> events)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filePath | String | Het bestandspad naar het brondocument. |
| loadOptions | Func`2 | Delegate die laadopties voor het document levert. |
| settings | Func`1 | De Converter‑instellingen. |
| events | Func`1 | Delegate die geaggregeerde [`ConversionEvents`](../../conversionevents) levert die geregistreerd zijn voor de levensduur van de converter. |

### Zie ook

* class [LoadContext](../../loadcontext)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [ConverterSettings](../../convertersettings)
* class [ConversionEvents](../../conversionevents)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;ConverterSettings&gt;, Func&lt;ConversionEvents&gt;) {#constructor_7}

Initialiseert een nieuwe instantie van de [`Converter`](../../converter) klasse met expliciete conversiegebeurtenissen.

```csharp
public Converter(string filePath, Func<ConverterSettings> settings, Func<ConversionEvents> events)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filePath | String | Het bestandspad naar het brondocument. |
| settings | Func`1 | De Converter‑instellingen. |
| events | Func`1 | Delegate die geaggregeerde [`ConversionEvents`](../../conversionevents) levert die geregistreerd zijn voor de levensduur van de converter. |

### Zie ook

* class [ConverterSettings](../../convertersettings)
* class [ConversionEvents](../../conversionevents)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.conversion.dll -->
