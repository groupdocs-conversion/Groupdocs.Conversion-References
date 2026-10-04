---
title: "Converter"
second_title: "GroupDocs.Conversion för .NET API-referens"
description: "Initierar en ny instans av klassen Convertergroupdocs.conversion/converter."
type: docs
weight: 10
url: /sv/net/groupdocs.conversion/converter/converter/
---
## Converter(Func&lt;Stream&gt;) {#constructor}

Initierar en ny instans av klassen [`Converter`](../../converter).

```csharp
public Converter(Func<Stream> sourceStreamProvider)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourceStreamProvider | Func`1 | Metoden som returnerar en läsbar ström. |

### Undantag

| undantag | villkor |
| --- | --- |
| ArgumentNullException | Kastas när *sourceStreamProvider* är null. |

### Anmärkningar

**Learn more**

* More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* More about document loading options dependent on file type: [Load options for different document types](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Se även

* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;ConverterSettings&gt;) {#constructor_1}

Initierar en ny instans av klassen [`Converter`](../../converter).

```csharp
public Converter(Func<Stream> sourceStreamProvider, Func<ConverterSettings> settings)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourceStreamProvider | Func`1 | Metoden som returnerar en läsbar ström. |
| settings | Func`1 | Inställningarna för Converter. |

### Anmärkningar

**Learn more**

* More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* More about document loading options dependent on file type: [Load options for different document types](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Se även

* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;LoadContext, LoadOptions&gt;, Func&lt;ConverterSettings&gt;) {#constructor_3}

Initierar en ny instans av klassen [`Converter`](../../converter).

```csharp
public Converter(Func<Stream> sourceStreamProvider, Func<LoadContext, LoadOptions> loadOptions, 
    Func<ConverterSettings> settings = null)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourceStreamProvider | Func`1 | Metoden som returnerar en läsbar ström. |
| loadOptions | Func`2 | Delegat som tillhandahåller laddningsalternativ för dokumentet. Signatur: `Func<LoadContext, LoadOptions>`. Parametern [`LoadContext`](../../loadcontext) innehåller information om dokumentet som laddas. |
| settings | Func`1 | Inställningarna för Converter. |

### Anmärkningar

**Learn more**

* More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* More about document loading options dependent on file type: [Load options for different document types](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Se även

* class [LoadContext](../../loadcontext)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;LoadContext, LoadOptions&gt;, Func&lt;ConverterSettings&gt;, Func&lt;ConversionEvents&gt;) {#constructor_4}

Initierar en ny instans av klassen [`Converter`](../../converter) med explicita konverteringsevenemang.

```csharp
public Converter(Func<Stream> sourceStreamProvider, Func<LoadContext, LoadOptions> loadOptions, 
    Func<ConverterSettings> settings, Func<ConversionEvents> events)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourceStreamProvider | Func`1 | Metoden som returnerar en läsbar ström. |
| loadOptions | Func`2 | Delegat som tillhandahåller laddningsalternativ för dokumentet. |
| settings | Func`1 | Inställningarna för Converter. |
| events | Func`1 | Delegat som tillhandahåller aggregerade [`ConversionEvents`](../../conversionevents) registrerade för konverterarens livstid. |

### Se även

* class [LoadContext](../../loadcontext)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [ConverterSettings](../../convertersettings)
* class [ConversionEvents](../../conversionevents)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;ConverterSettings&gt;, Func&lt;ConversionEvents&gt;) {#constructor_2}

Initierar en ny instans av klassen [`Converter`](../../converter) med explicita konverteringsevenemang.

```csharp
public Converter(Func<Stream> sourceStreamProvider, Func<ConverterSettings> settings, 
    Func<ConversionEvents> events)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourceStreamProvider | Func`1 | Metoden som returnerar en läsbar ström. |
| settings | Func`1 | Inställningarna för Converter. |
| events | Func`1 | Delegat som tillhandahåller aggregerade [`ConversionEvents`](../../conversionevents) registrerade för konverterarens livstid. |

### Se även

* class [ConverterSettings](../../convertersettings)
* class [ConversionEvents](../../conversionevents)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(string) {#constructor_5}

Initierar en ny instans av klassen [`Converter`](../../converter).

```csharp
public Converter(string filePath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | String | Filvägen till källdokumentet. |

### Anmärkningar

**Learn more**

* More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* More about document loading options dependent on file type: [Load options for different document types](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Se även

* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;ConverterSettings&gt;) {#constructor_6}

Initierar en ny instans av klassen [`Converter`](../../converter).

```csharp
public Converter(string filePath, Func<ConverterSettings> settings)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | String | Filvägen till källdokumentet. |
| settings | Func`1 | Inställningarna för Converter. |

### Anmärkningar

**Learn more**

* More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* More about document loading options dependent on file type: [Load options for different document types](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Se även

* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;LoadContext, LoadOptions&gt;, Func&lt;ConverterSettings&gt;) {#constructor_8}

Initierar en ny instans av klassen [`Converter`](../../converter).

```csharp
public Converter(string filePath, Func<LoadContext, LoadOptions> loadOptions, 
    Func<ConverterSettings> settings = null)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | String | Filvägen till källdokumentet. |
| loadOptions | Func`2 | Delegat som tillhandahåller laddningsalternativ för dokumentet. Signatur: `Func<LoadContext, LoadOptions>`. Parametern [`LoadContext`](../../loadcontext) innehåller information om dokumentet som laddas. |
| settings | Func`1 | Inställningarna för Converter. |

### Anmärkningar

**Learn more**

* More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* More about document loading options dependent on file type: [Load options for different document types](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Se även

* class [LoadContext](../../loadcontext)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;LoadContext, LoadOptions&gt;, Func&lt;ConverterSettings&gt;, Func&lt;ConversionEvents&gt;) {#constructor_9}

Initierar en ny instans av klassen [`Converter`](../../converter) med explicita konverteringsevenemang.

```csharp
public Converter(string filePath, Func<LoadContext, LoadOptions> loadOptions, 
    Func<ConverterSettings> settings, Func<ConversionEvents> events)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | String | Filvägen till källdokumentet. |
| loadOptions | Func`2 | Delegat som tillhandahåller laddningsalternativ för dokumentet. |
| settings | Func`1 | Inställningarna för Converter. |
| events | Func`1 | Delegat som tillhandahåller aggregerade [`ConversionEvents`](../../conversionevents) registrerade för konverterarens livstid. |

### Se även

* class [LoadContext](../../loadcontext)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [ConverterSettings](../../convertersettings)
* class [ConversionEvents](../../conversionevents)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;ConverterSettings&gt;, Func&lt;ConversionEvents&gt;) {#constructor_7}

Initierar en ny instans av klassen [`Converter`](../../converter) med explicita konverteringsevenemang.

```csharp
public Converter(string filePath, Func<ConverterSettings> settings, Func<ConversionEvents> events)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | String | Filvägen till källdokumentet. |
| settings | Func`1 | Inställningarna för Converter. |
| events | Func`1 | Delegat som tillhandahåller aggregerade [`ConversionEvents`](../../conversionevents) registrerade för konverterarens livstid. |

### Se även

* class [ConverterSettings](../../convertersettings)
* class [ConversionEvents](../../conversionevents)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

<!-- FÅ INTE REDIGERA: genererad av xmldocmd för GroupDocs.conversion.dll -->
