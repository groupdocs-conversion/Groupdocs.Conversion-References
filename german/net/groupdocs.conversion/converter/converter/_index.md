---
title: "Converter"
second_title: "GroupDocs.Conversion für .NET API-Referenz"
description: "Initialisiert eine neue Instanz der Klasse Convertergroupdocs.conversion/converter."
type: docs
weight: 10
url: /de/net/groupdocs.conversion/converter/converter/
---
## Converter(Func&lt;Stream&gt;) {#constructor}

Initialisiert eine neue Instanz der Klasse [`Converter`](../../converter).

```csharp
public Converter(Func<Stream> sourceStreamProvider)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourceStreamProvider | Func`1 | Die Methode, die einen lesbaren Stream zurückgibt. |

### Ausnahmen

| exception | condition |
| --- | --- |
| ArgumentNullException | Wird ausgelöst, wenn *sourceStreamProvider* null ist. |

### Hinweise

**Learn more**

* More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* More about document loading options dependent on file type: [Load options for different document types](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Siehe auch

* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;ConverterSettings&gt;) {#constructor_1}

Initialisiert eine neue Instanz der Klasse [`Converter`](../../converter).

```csharp
public Converter(Func<Stream> sourceStreamProvider, Func<ConverterSettings> settings)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourceStreamProvider | Func`1 | Die Methode, die einen lesbaren Stream zurückgibt. |
| settings | Func`1 | Die Converter-Einstellungen. |

### Hinweise

**Learn more**

* More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* More about document loading options dependent on file type: [Load options for different document types](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Siehe auch

* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;LoadContext, LoadOptions&gt;, Func&lt;ConverterSettings&gt;) {#constructor_3}

Initialisiert eine neue Instanz der Klasse [`Converter`](../../converter).

```csharp
public Converter(Func<Stream> sourceStreamProvider, Func<LoadContext, LoadOptions> loadOptions, 
    Func<ConverterSettings> settings = null)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourceStreamProvider | Func`1 | Die Methode, die einen lesbaren Stream zurückgibt. |
| loadOptions | Func`2 | Delegat, der Ladeoptionen für das Dokument bereitstellt. Signature: `Func<LoadContext, LoadOptions>`. Der Parameter [`LoadContext`](../../loadcontext) enthält Informationen über das zu ladende Dokument. |
| settings | Func`1 | Die Converter-Einstellungen. |

### Hinweise

**Learn more**

* More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* More about document loading options dependent on file type: [Load options for different document types](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Siehe auch

* class [LoadContext](../../loadcontext)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;LoadContext, LoadOptions&gt;, Func&lt;ConverterSettings&gt;, Func&lt;ConversionEvents&gt;) {#constructor_4}

Initialisiert eine neue Instanz der Klasse [`Converter`](../../converter) mit expliziten Konvertierungsereignissen.

```csharp
public Converter(Func<Stream> sourceStreamProvider, Func<LoadContext, LoadOptions> loadOptions, 
    Func<ConverterSettings> settings, Func<ConversionEvents> events)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourceStreamProvider | Func`1 | Die Methode, die einen lesbaren Stream zurückgibt. |
| loadOptions | Func`2 | Delegat, der Ladeoptionen für das Dokument bereitstellt. |
| settings | Func`1 | Die Converter-Einstellungen. |
| events | Func`1 | Delegat, der aggregierte [`ConversionEvents`](../../conversionevents) bereitstellt, die für die Lebensdauer des Converters registriert sind. |

### Siehe auch

* class [LoadContext](../../loadcontext)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [ConverterSettings](../../convertersettings)
* class [ConversionEvents](../../conversionevents)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;ConverterSettings&gt;, Func&lt;ConversionEvents&gt;) {#constructor_2}

Initialisiert eine neue Instanz der Klasse [`Converter`](../../converter) mit expliziten Konvertierungsereignissen.

```csharp
public Converter(Func<Stream> sourceStreamProvider, Func<ConverterSettings> settings, 
    Func<ConversionEvents> events)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourceStreamProvider | Func`1 | Die Methode, die einen lesbaren Stream zurückgibt. |
| settings | Func`1 | Die Converter-Einstellungen. |
| events | Func`1 | Delegat, der aggregierte [`ConversionEvents`](../../conversionevents) bereitstellt, die für die Lebensdauer des Converters registriert sind. |

### Siehe auch

* class [ConverterSettings](../../convertersettings)
* class [ConversionEvents](../../conversionevents)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(string) {#constructor_5}

Initialisiert eine neue Instanz der Klasse [`Converter`](../../converter).

```csharp
public Converter(string filePath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | String | Der Dateipfad zur Quelldatei. |

### Hinweise

**Learn more**

* More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* More about document loading options dependent on file type: [Load options for different document types](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Siehe auch

* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;ConverterSettings&gt;) {#constructor_6}

Initialisiert eine neue Instanz der Klasse [`Converter`](../../converter).

```csharp
public Converter(string filePath, Func<ConverterSettings> settings)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | String | Der Dateipfad zur Quelldatei. |
| settings | Func`1 | Die Converter-Einstellungen. |

### Hinweise

**Learn more**

* More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* More about document loading options dependent on file type: [Load options for different document types](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Siehe auch

* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;LoadContext, LoadOptions&gt;, Func&lt;ConverterSettings&gt;) {#constructor_8}

Initialisiert eine neue Instanz der Klasse [`Converter`](../../converter).

```csharp
public Converter(string filePath, Func<LoadContext, LoadOptions> loadOptions, 
    Func<ConverterSettings> settings = null)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | String | Der Dateipfad zur Quelldatei. |
| loadOptions | Func`2 | Delegat, der Ladeoptionen für das Dokument bereitstellt. Signature: `Func<LoadContext, LoadOptions>`. Der Parameter [`LoadContext`](../../loadcontext) enthält Informationen über das zu ladende Dokument. |
| settings | Func`1 | Die Converter-Einstellungen. |

### Hinweise

**Learn more**

* More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* More about document loading options dependent on file type: [Load options for different document types](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Siehe auch

* class [LoadContext](../../loadcontext)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;LoadContext, LoadOptions&gt;, Func&lt;ConverterSettings&gt;, Func&lt;ConversionEvents&gt;) {#constructor_9}

Initialisiert eine neue Instanz der Klasse [`Converter`](../../converter) mit expliziten Konvertierungsereignissen.

```csharp
public Converter(string filePath, Func<LoadContext, LoadOptions> loadOptions, 
    Func<ConverterSettings> settings, Func<ConversionEvents> events)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | String | Der Dateipfad zur Quelldatei. |
| loadOptions | Func`2 | Delegat, der Ladeoptionen für das Dokument bereitstellt. |
| settings | Func`1 | Die Converter-Einstellungen. |
| events | Func`1 | Delegat, der aggregierte [`ConversionEvents`](../../conversionevents) bereitstellt, die für die Lebensdauer des Converters registriert sind. |

### Siehe auch

* class [LoadContext](../../loadcontext)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [ConverterSettings](../../convertersettings)
* class [ConversionEvents](../../conversionevents)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;ConverterSettings&gt;, Func&lt;ConversionEvents&gt;) {#constructor_7}

Initialisiert eine neue Instanz der Klasse [`Converter`](../../converter) mit expliziten Konvertierungsereignissen.

```csharp
public Converter(string filePath, Func<ConverterSettings> settings, Func<ConversionEvents> events)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | String | Der Dateipfad zur Quelldatei. |
| settings | Func`1 | Die Converter-Einstellungen. |
| events | Func`1 | Delegat, der aggregierte [`ConversionEvents`](../../conversionevents) bereitstellt, die für die Lebensdauer des Converters registriert sind. |

### Siehe auch

* class [ConverterSettings](../../convertersettings)
* class [ConversionEvents](../../conversionevents)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.conversion.dll -->
