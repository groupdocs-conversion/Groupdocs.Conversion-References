---
title: Converter
second_title: GroupDocs.Conversion voor .NET API-referentie
description: Initialiseert nieuw exemplaar vanConvertergroupdocs.conversion/converter klasse.
type: docs
weight: 10
url: /nl/net/groupdocs.conversion/converter/converter/
---
## Converter(Func&lt;Stream&gt;) {#constructor_1}

Initialiseert nieuw exemplaar van[`Converter`](../../converter) klasse.

```csharp
public Converter(Func<Stream> document)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| document | Func`1 | De methode die een leesbare stream retourneert. |

### Uitzonderingen

| uitzondering | voorwaarde |
| --- | --- |
| ArgumentNullException | Wanneer gegooid*document* is niets. |

### Opmerkingen

**Kom meer te weten**

* Meer informatie over het laden en converteren van documenten die zijn opgeslagen op FTP, Amazon S3 Storage, Windows Azure of andere opslag van derden: [Document laden uit verschillende bronnen](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* Meer over opties voor het laden van documenten, afhankelijk van het bestandstype: [Laadopties voor verschillende documenttypes](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Zie ook

* class [Converter](../../converter)
* naamruimte [GroupDocs.Conversion](../../converter)
* montage [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;ConverterSettings&gt;) {#constructor_2}

Initialiseert nieuw exemplaar van[`Converter`](../../converter) klasse.

```csharp
public Converter(Func<Stream> document, Func<ConverterSettings> settings)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| document | Func`1 | De methode die een leesbare stream retourneert. |
| settings | Func`1 | De Converter-instellingen. |

### Opmerkingen

**Kom meer te weten**

* Meer informatie over het laden en converteren van documenten die zijn opgeslagen op FTP, Amazon S3 Storage, Windows Azure of andere opslag van derden: [Document laden uit verschillende bronnen](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* Meer over opties voor het laden van documenten, afhankelijk van het bestandstype: [Laadopties voor verschillende documenttypes](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Zie ook

* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* naamruimte [GroupDocs.Conversion](../../converter)
* montage [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;) {#constructor_3}

Initialiseert nieuw exemplaar van[`Converter`](../../converter) klasse.

```csharp
public Converter(Func<Stream> document, Func<LoadOptions> loadOptions)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| document | Func`1 | De methode die een leesbare stream retourneert. |
| loadOptions | Func`1 | De methoden die opties voor het laden van documenten retourneren. |

### Opmerkingen

**Kom meer te weten**

* Meer informatie over het laden en converteren van documenten die zijn opgeslagen op FTP, Amazon S3 Storage, Windows Azure of andere opslag van derden: [Document laden uit verschillende bronnen](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* Meer over opties voor het laden van documenten, afhankelijk van het bestandstype: [Laadopties voor verschillende documenttypes](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Zie ook

* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [Converter](../../converter)
* naamruimte [GroupDocs.Conversion](../../converter)
* montage [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;, Func&lt;ConverterSettings&gt;) {#constructor_4}

Initialiseert nieuw exemplaar van[`Converter`](../../converter) klasse.

```csharp
public Converter(Func<Stream> document, Func<LoadOptions> loadOptions, 
    Func<ConverterSettings> settings)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| document | Func`1 | De methode die een leesbare stream retourneert. |
| loadOptions | Func`1 | De methoden die opties voor het laden van documenten retourneren. |
| settings | Func`1 | De Converter-instellingen. |

### Opmerkingen

**Kom meer te weten**

* Meer informatie over het laden en converteren van documenten die zijn opgeslagen op FTP, Amazon S3 Storage, Windows Azure of andere opslag van derden: [Document laden uit verschillende bronnen](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* Meer over opties voor het laden van documenten, afhankelijk van het bestandstype: [Laadopties voor verschillende documenttypes](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Zie ook

* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* naamruimte [GroupDocs.Conversion](../../converter)
* montage [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;FileType, LoadOptions&gt;) {#constructor_5}

Initialiseert nieuw exemplaar van[`Converter`](../../converter) klasse.

```csharp
public Converter(Func<Stream> document, Func<FileType, LoadOptions> loadOptions)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| document | Func`1 | De methode die een leesbare stream retourneert. |
| loadOptions | Func`2 | De methoden die laadopties voor documenten retourneren. Het type van het bronbestand |

### Opmerkingen

**Kom meer te weten**

* Meer informatie over het laden en converteren van documenten die zijn opgeslagen op FTP, Amazon S3 Storage, Windows Azure of andere opslag van derden: [Document laden uit verschillende bronnen](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* Meer over opties voor het laden van documenten, afhankelijk van het bestandstype: [Laadopties voor verschillende documenttypes](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Zie ook

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [Converter](../../converter)
* naamruimte [GroupDocs.Conversion](../../converter)
* montage [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;FileType, LoadOptions&gt;, Func&lt;ConverterSettings&gt;) {#constructor_6}

Initialiseert nieuw exemplaar van[`Converter`](../../converter) klasse.

```csharp
public Converter(Func<Stream> document, Func<FileType, LoadOptions> loadOptions, 
    Func<ConverterSettings> settings)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| document | Func`1 | De methode die een leesbare stream retourneert. |
| loadOptions | Func`2 | De methoden die laadopties voor documenten retourneren. Het type van het bronbestand |
| settings | Func`1 | De Converter-instellingen. |

### Opmerkingen

**Kom meer te weten**

* Meer informatie over het laden en converteren van documenten die zijn opgeslagen op FTP, Amazon S3 Storage, Windows Azure of andere opslag van derden: [Document laden uit verschillende bronnen](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* Meer over opties voor het laden van documenten, afhankelijk van het bestandstype: [Laadopties voor verschillende documenttypes](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Zie ook

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* naamruimte [GroupDocs.Conversion](../../converter)
* montage [GroupDocs.Conversion](../../../)

---

## Converter(string) {#constructor_7}

Initialiseert nieuw exemplaar van[`Converter`](../../converter) klasse.

```csharp
public Converter(string filePath)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filePath | String | Het bestandspad naar het brondocument. |

### Opmerkingen

**Kom meer te weten**

* Meer informatie over het laden en converteren van documenten die zijn opgeslagen op FTP, Amazon S3 Storage, Windows Azure of andere opslag van derden: [Document laden uit verschillende bronnen](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* Meer over opties voor het laden van documenten, afhankelijk van het bestandstype: [Laadopties voor verschillende documenttypes](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Zie ook

* class [Converter](../../converter)
* naamruimte [GroupDocs.Conversion](../../converter)
* montage [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;ConverterSettings&gt;) {#constructor_8}

Initialiseert nieuw exemplaar van[`Converter`](../../converter) klasse.

```csharp
public Converter(string filePath, Func<ConverterSettings> settings)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filePath | String | Het bestandspad naar het brondocument. |
| settings | Func`1 | De Converter-instellingen. |

### Opmerkingen

**Kom meer te weten**

* Meer informatie over het laden en converteren van documenten die zijn opgeslagen op FTP, Amazon S3 Storage, Windows Azure of andere opslag van derden: [Document laden uit verschillende bronnen](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* Meer over opties voor het laden van documenten, afhankelijk van het bestandstype: [Laadopties voor verschillende documenttypes](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Zie ook

* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* naamruimte [GroupDocs.Conversion](../../converter)
* montage [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;LoadOptions&gt;) {#constructor_9}

Initialiseert nieuw exemplaar van[`Converter`](../../converter) klasse.

```csharp
public Converter(string filePath, Func<LoadOptions> loadOptions)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filePath | String | Het bestandspad naar het brondocument. |
| loadOptions | Func`1 | De methoden die opties voor het laden van documenten retourneren. |

### Opmerkingen

**Kom meer te weten**

* Meer informatie over het laden en converteren van documenten die zijn opgeslagen op FTP, Amazon S3 Storage, Windows Azure of andere opslag van derden: [Document laden uit verschillende bronnen](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* Meer over opties voor het laden van documenten, afhankelijk van het bestandstype: [Laadopties voor verschillende documenttypes](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Zie ook

* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [Converter](../../converter)
* naamruimte [GroupDocs.Conversion](../../converter)
* montage [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;LoadOptions&gt;, Func&lt;ConverterSettings&gt;) {#constructor_10}

Initialiseert nieuw exemplaar van[`Converter`](../../converter) klasse.

```csharp
public Converter(string filePath, Func<LoadOptions> loadOptions, Func<ConverterSettings> settings)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filePath | String | Het bestandspad naar het brondocument. |
| loadOptions | Func`1 | De methoden die opties voor het laden van documenten retourneren. |
| settings | Func`1 | De Converter-instellingen. |

### Opmerkingen

**Kom meer te weten**

* Meer informatie over het laden en converteren van documenten die zijn opgeslagen op FTP, Amazon S3 Storage, Windows Azure of andere opslag van derden: [Document laden uit verschillende bronnen](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* Meer over opties voor het laden van documenten, afhankelijk van het bestandstype: [Laadopties voor verschillende documenttypes](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Zie ook

* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* naamruimte [GroupDocs.Conversion](../../converter)
* montage [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;FileType, LoadOptions&gt;) {#constructor_11}

Initialiseert nieuw exemplaar van[`Converter`](../../converter) klasse.

```csharp
public Converter(string filePath, Func<FileType, LoadOptions> loadOptions)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filePath | String | Het bestandspad naar het brondocument. |
| loadOptions | Func`2 | De methoden die laadopties voor documenten retourneren. Het type van het bronbestand |

### Opmerkingen

**Kom meer te weten**

* Meer informatie over het laden en converteren van documenten die zijn opgeslagen op FTP, Amazon S3 Storage, Windows Azure of andere opslag van derden: [Document laden uit verschillende bronnen](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* Meer over opties voor het laden van documenten, afhankelijk van het bestandstype: [Laadopties voor verschillende documenttypes](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Zie ook

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [Converter](../../converter)
* naamruimte [GroupDocs.Conversion](../../converter)
* montage [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;FileType, LoadOptions&gt;, Func&lt;ConverterSettings&gt;) {#constructor_12}

Initialiseert nieuw exemplaar van[`Converter`](../../converter) klasse.

```csharp
public Converter(string filePath, Func<FileType, LoadOptions> loadOptions, 
    Func<ConverterSettings> settings)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filePath | String | Het bestandspad naar het brondocument. |
| loadOptions | Func`2 | De methoden die laadopties voor documenten retourneren. Het type van het bronbestand |
| settings | Func`1 | De Converter-instellingen. |

### Opmerkingen

**Kom meer te weten**

* Meer informatie over het laden en converteren van documenten die zijn opgeslagen op FTP, Amazon S3 Storage, Windows Azure of andere opslag van derden: [Document laden uit verschillende bronnen](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* Meer over opties voor het laden van documenten, afhankelijk van het bestandstype: [Laadopties voor verschillende documenttypes](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Zie ook

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* naamruimte [GroupDocs.Conversion](../../converter)
* montage [GroupDocs.Conversion](../../../)

---

## Converter() {#constructor}

Initialiseert nieuw exemplaar van[`Converter`](../../converter) klasse voor vloeiende conversie-instellingen.

```csharp
public Converter()
```

### Opmerkingen

Voorbeeld van vloeiend conversiegebruik:

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

### Zie ook

* class [Converter](../../converter)
* naamruimte [GroupDocs.Conversion](../../converter)
* montage [GroupDocs.Conversion](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
