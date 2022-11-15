---
title: Converter
second_title: GroupDocs.Conversion for .NET API Referens
description: Initierar ny instans avConvertergroupdocs.conversion/converter class.
type: docs
weight: 10
url: /sv/net/groupdocs.conversion/converter/converter/
---
## Converter(Func&lt;Stream&gt;) {#constructor_1}

Initierar ny instans av[`Converter`](../../converter) class.

```csharp
public Converter(Func<Stream> document)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| document | Func`1 | Metoden som returnerar läsbar ström. |

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentNullException | Kastas när*document* är inget. |

### Anmärkningar

**Läs mer**

* Mer om hur du laddar och konverterar dokument lagrade på FTP, Amazon S3 Storage, Windows Azure eller annan tredjepartslagring: [Laddar dokument från olika källor](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* Mer om alternativ för dokumentladdning beroende på filtyp: [Ladda alternativ för olika dokumenttyper](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Se även

* class [Converter](../../converter)
* namnutrymme [GroupDocs.Conversion](../../converter)
* hopsättning [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;ConverterSettings&gt;) {#constructor_2}

Initierar ny instans av[`Converter`](../../converter) class.

```csharp
public Converter(Func<Stream> document, Func<ConverterSettings> settings)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| document | Func`1 | Metoden som returnerar läsbar ström. |
| settings | Func`1 | Konverterinställningarna. |

### Anmärkningar

**Läs mer**

* Mer om hur du laddar och konverterar dokument lagrade på FTP, Amazon S3 Storage, Windows Azure eller annan tredjepartslagring: [Laddar dokument från olika källor](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* Mer om alternativ för dokumentladdning beroende på filtyp: [Ladda alternativ för olika dokumenttyper](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Se även

* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* namnutrymme [GroupDocs.Conversion](../../converter)
* hopsättning [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;) {#constructor_3}

Initierar ny instans av[`Converter`](../../converter) class.

```csharp
public Converter(Func<Stream> document, Func<LoadOptions> loadOptions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| document | Func`1 | Metoden som returnerar läsbar ström. |
| loadOptions | Func`1 | Metoderna som returnerar alternativ för dokumentladdning. |

### Anmärkningar

**Läs mer**

* Mer om hur du laddar och konverterar dokument lagrade på FTP, Amazon S3 Storage, Windows Azure eller annan tredjepartslagring: [Laddar dokument från olika källor](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* Mer om alternativ för dokumentladdning beroende på filtyp: [Ladda alternativ för olika dokumenttyper](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Se även

* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [Converter](../../converter)
* namnutrymme [GroupDocs.Conversion](../../converter)
* hopsättning [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;, Func&lt;ConverterSettings&gt;) {#constructor_4}

Initierar ny instans av[`Converter`](../../converter) class.

```csharp
public Converter(Func<Stream> document, Func<LoadOptions> loadOptions, 
    Func<ConverterSettings> settings)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| document | Func`1 | Metoden som returnerar läsbar ström. |
| loadOptions | Func`1 | Metoderna som returnerar alternativ för dokumentladdning. |
| settings | Func`1 | Konverterinställningarna. |

### Anmärkningar

**Läs mer**

* Mer om hur du laddar och konverterar dokument lagrade på FTP, Amazon S3 Storage, Windows Azure eller annan tredjepartslagring: [Laddar dokument från olika källor](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* Mer om alternativ för dokumentladdning beroende på filtyp: [Ladda alternativ för olika dokumenttyper](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Se även

* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* namnutrymme [GroupDocs.Conversion](../../converter)
* hopsättning [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;FileType, LoadOptions&gt;) {#constructor_5}

Initierar ny instans av[`Converter`](../../converter) class.

```csharp
public Converter(Func<Stream> document, Func<FileType, LoadOptions> loadOptions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| document | Func`1 | Metoden som returnerar läsbar ström. |
| loadOptions | Func`2 | Metoderna som returnerar alternativ för dokumentladdning. |

### Anmärkningar

**Läs mer**

* Mer om hur du laddar och konverterar dokument lagrade på FTP, Amazon S3 Storage, Windows Azure eller annan tredjepartslagring: [Laddar dokument från olika källor](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* Mer om alternativ för dokumentladdning beroende på filtyp: [Ladda alternativ för olika dokumenttyper](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Se även

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [Converter](../../converter)
* namnutrymme [GroupDocs.Conversion](../../converter)
* hopsättning [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;FileType, LoadOptions&gt;, Func&lt;ConverterSettings&gt;) {#constructor_6}

Initierar ny instans av[`Converter`](../../converter) class.

```csharp
public Converter(Func<Stream> document, Func<FileType, LoadOptions> loadOptions, 
    Func<ConverterSettings> settings)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| document | Func`1 | Metoden som returnerar läsbar ström. |
| loadOptions | Func`2 | Metoderna som returnerar alternativ för dokumentladdning. |
| settings | Func`1 | Konverterinställningarna. |

### Anmärkningar

**Läs mer**

* Mer om hur du laddar och konverterar dokument lagrade på FTP, Amazon S3 Storage, Windows Azure eller annan tredjepartslagring: [Laddar dokument från olika källor](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* Mer om alternativ för dokumentladdning beroende på filtyp: [Ladda alternativ för olika dokumenttyper](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Se även

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* namnutrymme [GroupDocs.Conversion](../../converter)
* hopsättning [GroupDocs.Conversion](../../../)

---

## Converter(string) {#constructor_7}

Initierar ny instans av[`Converter`](../../converter) class.

```csharp
public Converter(string filePath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | String | Filsökvägen till källdokumentet. |

### Anmärkningar

**Läs mer**

* Mer om hur du laddar och konverterar dokument lagrade på FTP, Amazon S3 Storage, Windows Azure eller annan tredjepartslagring: [Laddar dokument från olika källor](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* Mer om alternativ för dokumentladdning beroende på filtyp: [Ladda alternativ för olika dokumenttyper](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Se även

* class [Converter](../../converter)
* namnutrymme [GroupDocs.Conversion](../../converter)
* hopsättning [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;ConverterSettings&gt;) {#constructor_8}

Initierar ny instans av[`Converter`](../../converter) class.

```csharp
public Converter(string filePath, Func<ConverterSettings> settings)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | String | Filsökvägen till källdokumentet. |
| settings | Func`1 | Konverterinställningarna. |

### Anmärkningar

**Läs mer**

* Mer om hur du laddar och konverterar dokument lagrade på FTP, Amazon S3 Storage, Windows Azure eller annan tredjepartslagring: [Laddar dokument från olika källor](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* Mer om alternativ för dokumentladdning beroende på filtyp: [Ladda alternativ för olika dokumenttyper](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Se även

* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* namnutrymme [GroupDocs.Conversion](../../converter)
* hopsättning [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;LoadOptions&gt;) {#constructor_9}

Initierar ny instans av[`Converter`](../../converter) class.

```csharp
public Converter(string filePath, Func<LoadOptions> loadOptions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | String | Filsökvägen till källdokumentet. |
| loadOptions | Func`1 | Metoderna som returnerar alternativ för dokumentladdning. |

### Anmärkningar

**Läs mer**

* Mer om hur du laddar och konverterar dokument lagrade på FTP, Amazon S3 Storage, Windows Azure eller annan tredjepartslagring: [Laddar dokument från olika källor](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* Mer om alternativ för dokumentladdning beroende på filtyp: [Ladda alternativ för olika dokumenttyper](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Se även

* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [Converter](../../converter)
* namnutrymme [GroupDocs.Conversion](../../converter)
* hopsättning [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;LoadOptions&gt;, Func&lt;ConverterSettings&gt;) {#constructor_10}

Initierar ny instans av[`Converter`](../../converter) class.

```csharp
public Converter(string filePath, Func<LoadOptions> loadOptions, Func<ConverterSettings> settings)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | String | Filsökvägen till källdokumentet. |
| loadOptions | Func`1 | Metoderna som returnerar alternativ för dokumentladdning. |
| settings | Func`1 | Konverterinställningarna. |

### Anmärkningar

**Läs mer**

* Mer om hur du laddar och konverterar dokument lagrade på FTP, Amazon S3 Storage, Windows Azure eller annan tredjepartslagring: [Laddar dokument från olika källor](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* Mer om alternativ för dokumentladdning beroende på filtyp: [Ladda alternativ för olika dokumenttyper](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Se även

* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* namnutrymme [GroupDocs.Conversion](../../converter)
* hopsättning [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;FileType, LoadOptions&gt;) {#constructor_11}

Initierar ny instans av[`Converter`](../../converter) class.

```csharp
public Converter(string filePath, Func<FileType, LoadOptions> loadOptions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | String | Filsökvägen till källdokumentet. |
| loadOptions | Func`2 | Metoderna som returnerar alternativ för dokumentladdning. |

### Anmärkningar

**Läs mer**

* Mer om hur du laddar och konverterar dokument lagrade på FTP, Amazon S3 Storage, Windows Azure eller annan tredjepartslagring: [Laddar dokument från olika källor](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* Mer om alternativ för dokumentladdning beroende på filtyp: [Ladda alternativ för olika dokumenttyper](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Se även

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [Converter](../../converter)
* namnutrymme [GroupDocs.Conversion](../../converter)
* hopsättning [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;FileType, LoadOptions&gt;, Func&lt;ConverterSettings&gt;) {#constructor_12}

Initierar ny instans av[`Converter`](../../converter) class.

```csharp
public Converter(string filePath, Func<FileType, LoadOptions> loadOptions, 
    Func<ConverterSettings> settings)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | String | Filsökvägen till källdokumentet. |
| loadOptions | Func`2 | Metoderna som returnerar alternativ för dokumentladdning. |
| settings | Func`1 | Konverterinställningarna. |

### Anmärkningar

**Läs mer**

* Mer om hur du laddar och konverterar dokument lagrade på FTP, Amazon S3 Storage, Windows Azure eller annan tredjepartslagring: [Laddar dokument från olika källor](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* Mer om alternativ för dokumentladdning beroende på filtyp: [Ladda alternativ för olika dokumenttyper](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Se även

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* namnutrymme [GroupDocs.Conversion](../../converter)
* hopsättning [GroupDocs.Conversion](../../../)

---

## Converter() {#constructor}

Initierar ny instans av[`Converter`](../../converter) klass för flytande konverteringsinställningar.

```csharp
public Converter()
```

### Anmärkningar

Exempel på flytande konverteringsanvändning:

```csharp
var converter = new Converter();
```

```csharp
converter
    .Load("")
    .ConvertTo("")
    .Convert();
```

```csharp
converter
    .WithSettings(() => new ConverterSettings())
    .Load("").WithOptions(new PdfLoadOptions())
    .ConvertTo("").WithOptions(new PdfConvertOptions())
    .OnConversionCompleted(convertedDocumentStream => { })
    .Convert();
```

```csharp
converter
    .Load("").WithOptions(new PdfLoadOptions())
    .ConvertByPageTo((number => new FileStream("", FileMode.Create))).WithOptions(new PdfConvertOptions())
    .OnConversionCompleted((number, stream) => {})
    .Convert();
```

```csharp
converter.Load("").GetPossibleConversions();
converter.Load("").GetDocumentInfo();
converter.Load("").WithOptions(new PdfLoadOptions()).GetPossibleConversions();
converter.Load("").WithOptions(new PdfLoadOptions()).GetDocumentInfo();
```

### Se även

* class [Converter](../../converter)
* namnutrymme [GroupDocs.Conversion](../../converter)
* hopsättning [GroupDocs.Conversion](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
