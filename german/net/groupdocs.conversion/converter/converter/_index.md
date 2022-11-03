---
title: Converter
second_title: GroupDocs.Conversion für .NET-API-Referenz
description: Initialisiert eine neue Instanz vonConvertergroupdocs.conversion/converter Klasse.
type: docs
weight: 10
url: /de/net/groupdocs.conversion/converter/converter/
---
## Converter(Func&lt;Stream&gt;) {#constructor_1}

Initialisiert eine neue Instanz von[`Converter`](../../converter) Klasse.

```csharp
public Converter(Func<Stream> document)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| document | Func`1 | Die Methode, die einen lesbaren Stream zurückgibt. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | Wann geworfen*document* ist Null. |

### Bemerkungen

**Mehr erfahren**

* Weitere Informationen zum Laden und Konvertieren von Dokumenten, die auf FTP, Amazon S3-Speicher, Windows Azure oder einem anderen Speicher von Drittanbietern gespeichert sind: [Laden von Dokumenten aus verschiedenen Quellen](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* Weitere Informationen zu Optionen zum Laden von Dokumenten in Abhängigkeit vom Dateityp: [Ladeoptionen für verschiedene Dokumenttypen](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Siehe auch

* class [Converter](../../converter)
* namensraum [GroupDocs.Conversion](../../converter)
* Montage [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;ConverterSettings&gt;) {#constructor_2}

Initialisiert eine neue Instanz von[`Converter`](../../converter) Klasse.

```csharp
public Converter(Func<Stream> document, Func<ConverterSettings> settings)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| document | Func`1 | Die Methode, die einen lesbaren Stream zurückgibt. |
| settings | Func`1 | Die Konverter-Einstellungen. |

### Bemerkungen

**Mehr erfahren**

* Weitere Informationen zum Laden und Konvertieren von Dokumenten, die auf FTP, Amazon S3-Speicher, Windows Azure oder einem anderen Speicher von Drittanbietern gespeichert sind: [Laden von Dokumenten aus verschiedenen Quellen](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* Weitere Informationen zu Optionen zum Laden von Dokumenten in Abhängigkeit vom Dateityp: [Ladeoptionen für verschiedene Dokumenttypen](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Siehe auch

* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* namensraum [GroupDocs.Conversion](../../converter)
* Montage [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;) {#constructor_3}

Initialisiert eine neue Instanz von[`Converter`](../../converter) Klasse.

```csharp
public Converter(Func<Stream> document, Func<LoadOptions> loadOptions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| document | Func`1 | Die Methode, die einen lesbaren Stream zurückgibt. |
| loadOptions | Func`1 | Die Methoden, die Dokumentladeoptionen zurückgeben. |

### Bemerkungen

**Mehr erfahren**

* Weitere Informationen zum Laden und Konvertieren von Dokumenten, die auf FTP, Amazon S3-Speicher, Windows Azure oder einem anderen Speicher von Drittanbietern gespeichert sind: [Laden von Dokumenten aus verschiedenen Quellen](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* Weitere Informationen zu Optionen zum Laden von Dokumenten in Abhängigkeit vom Dateityp: [Ladeoptionen für verschiedene Dokumenttypen](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Siehe auch

* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [Converter](../../converter)
* namensraum [GroupDocs.Conversion](../../converter)
* Montage [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;, Func&lt;ConverterSettings&gt;) {#constructor_4}

Initialisiert eine neue Instanz von[`Converter`](../../converter) Klasse.

```csharp
public Converter(Func<Stream> document, Func<LoadOptions> loadOptions, 
    Func<ConverterSettings> settings)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| document | Func`1 | Die Methode, die einen lesbaren Stream zurückgibt. |
| loadOptions | Func`1 | Die Methoden, die Dokumentladeoptionen zurückgeben. |
| settings | Func`1 | Die Konverter-Einstellungen. |

### Bemerkungen

**Mehr erfahren**

* Weitere Informationen zum Laden und Konvertieren von Dokumenten, die auf FTP, Amazon S3-Speicher, Windows Azure oder einem anderen Speicher von Drittanbietern gespeichert sind: [Laden von Dokumenten aus verschiedenen Quellen](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* Weitere Informationen zu Optionen zum Laden von Dokumenten in Abhängigkeit vom Dateityp: [Ladeoptionen für verschiedene Dokumenttypen](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Siehe auch

* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* namensraum [GroupDocs.Conversion](../../converter)
* Montage [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;FileType, LoadOptions&gt;) {#constructor_5}

Initialisiert eine neue Instanz von[`Converter`](../../converter) Klasse.

```csharp
public Converter(Func<Stream> document, Func<FileType, LoadOptions> loadOptions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| document | Func`1 | Die Methode, die einen lesbaren Stream zurückgibt. |
| loadOptions | Func`2 | Die Methoden, die Dokumentladeoptionen zurückgeben. |

### Bemerkungen

**Mehr erfahren**

* Weitere Informationen zum Laden und Konvertieren von Dokumenten, die auf FTP, Amazon S3-Speicher, Windows Azure oder einem anderen Speicher von Drittanbietern gespeichert sind: [Laden von Dokumenten aus verschiedenen Quellen](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* Weitere Informationen zu Optionen zum Laden von Dokumenten in Abhängigkeit vom Dateityp: [Ladeoptionen für verschiedene Dokumenttypen](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Siehe auch

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [Converter](../../converter)
* namensraum [GroupDocs.Conversion](../../converter)
* Montage [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;FileType, LoadOptions&gt;, Func&lt;ConverterSettings&gt;) {#constructor_6}

Initialisiert eine neue Instanz von[`Converter`](../../converter) Klasse.

```csharp
public Converter(Func<Stream> document, Func<FileType, LoadOptions> loadOptions, 
    Func<ConverterSettings> settings)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| document | Func`1 | Die Methode, die einen lesbaren Stream zurückgibt. |
| loadOptions | Func`2 | Die Methoden, die Dokumentladeoptionen zurückgeben. |
| settings | Func`1 | Die Konverter-Einstellungen. |

### Bemerkungen

**Mehr erfahren**

* Weitere Informationen zum Laden und Konvertieren von Dokumenten, die auf FTP, Amazon S3-Speicher, Windows Azure oder einem anderen Speicher von Drittanbietern gespeichert sind: [Laden von Dokumenten aus verschiedenen Quellen](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* Weitere Informationen zu Optionen zum Laden von Dokumenten in Abhängigkeit vom Dateityp: [Ladeoptionen für verschiedene Dokumenttypen](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Siehe auch

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* namensraum [GroupDocs.Conversion](../../converter)
* Montage [GroupDocs.Conversion](../../../)

---

## Converter(string) {#constructor_7}

Initialisiert eine neue Instanz von[`Converter`](../../converter) Klasse.

```csharp
public Converter(string filePath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | String | Der Dateipfad zum Quelldokument. |

### Bemerkungen

**Mehr erfahren**

* Weitere Informationen zum Laden und Konvertieren von Dokumenten, die auf FTP, Amazon S3-Speicher, Windows Azure oder einem anderen Speicher von Drittanbietern gespeichert sind: [Laden von Dokumenten aus verschiedenen Quellen](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* Weitere Informationen zu Optionen zum Laden von Dokumenten in Abhängigkeit vom Dateityp: [Ladeoptionen für verschiedene Dokumenttypen](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Siehe auch

* class [Converter](../../converter)
* namensraum [GroupDocs.Conversion](../../converter)
* Montage [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;ConverterSettings&gt;) {#constructor_8}

Initialisiert eine neue Instanz von[`Converter`](../../converter) Klasse.

```csharp
public Converter(string filePath, Func<ConverterSettings> settings)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | String | Der Dateipfad zum Quelldokument. |
| settings | Func`1 | Die Konverter-Einstellungen. |

### Bemerkungen

**Mehr erfahren**

* Weitere Informationen zum Laden und Konvertieren von Dokumenten, die auf FTP, Amazon S3-Speicher, Windows Azure oder einem anderen Speicher von Drittanbietern gespeichert sind: [Laden von Dokumenten aus verschiedenen Quellen](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* Weitere Informationen zu Optionen zum Laden von Dokumenten in Abhängigkeit vom Dateityp: [Ladeoptionen für verschiedene Dokumenttypen](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Siehe auch

* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* namensraum [GroupDocs.Conversion](../../converter)
* Montage [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;LoadOptions&gt;) {#constructor_9}

Initialisiert eine neue Instanz von[`Converter`](../../converter) Klasse.

```csharp
public Converter(string filePath, Func<LoadOptions> loadOptions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | String | Der Dateipfad zum Quelldokument. |
| loadOptions | Func`1 | Die Methoden, die Dokumentladeoptionen zurückgeben. |

### Bemerkungen

**Mehr erfahren**

* Weitere Informationen zum Laden und Konvertieren von Dokumenten, die auf FTP, Amazon S3-Speicher, Windows Azure oder einem anderen Speicher von Drittanbietern gespeichert sind: [Laden von Dokumenten aus verschiedenen Quellen](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* Weitere Informationen zu Optionen zum Laden von Dokumenten in Abhängigkeit vom Dateityp: [Ladeoptionen für verschiedene Dokumenttypen](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Siehe auch

* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [Converter](../../converter)
* namensraum [GroupDocs.Conversion](../../converter)
* Montage [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;LoadOptions&gt;, Func&lt;ConverterSettings&gt;) {#constructor_10}

Initialisiert eine neue Instanz von[`Converter`](../../converter) Klasse.

```csharp
public Converter(string filePath, Func<LoadOptions> loadOptions, Func<ConverterSettings> settings)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | String | Der Dateipfad zum Quelldokument. |
| loadOptions | Func`1 | Die Methoden, die Dokumentladeoptionen zurückgeben. |
| settings | Func`1 | Die Konverter-Einstellungen. |

### Bemerkungen

**Mehr erfahren**

* Weitere Informationen zum Laden und Konvertieren von Dokumenten, die auf FTP, Amazon S3-Speicher, Windows Azure oder einem anderen Speicher von Drittanbietern gespeichert sind: [Laden von Dokumenten aus verschiedenen Quellen](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* Weitere Informationen zu Optionen zum Laden von Dokumenten in Abhängigkeit vom Dateityp: [Ladeoptionen für verschiedene Dokumenttypen](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Siehe auch

* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* namensraum [GroupDocs.Conversion](../../converter)
* Montage [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;FileType, LoadOptions&gt;) {#constructor_11}

Initialisiert eine neue Instanz von[`Converter`](../../converter) Klasse.

```csharp
public Converter(string filePath, Func<FileType, LoadOptions> loadOptions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | String | Der Dateipfad zum Quelldokument. |
| loadOptions | Func`2 | Die Methoden, die Dokumentladeoptionen zurückgeben. |

### Bemerkungen

**Mehr erfahren**

* Weitere Informationen zum Laden und Konvertieren von Dokumenten, die auf FTP, Amazon S3-Speicher, Windows Azure oder einem anderen Speicher von Drittanbietern gespeichert sind: [Laden von Dokumenten aus verschiedenen Quellen](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* Weitere Informationen zu Optionen zum Laden von Dokumenten in Abhängigkeit vom Dateityp: [Ladeoptionen für verschiedene Dokumenttypen](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Siehe auch

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [Converter](../../converter)
* namensraum [GroupDocs.Conversion](../../converter)
* Montage [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;FileType, LoadOptions&gt;, Func&lt;ConverterSettings&gt;) {#constructor_12}

Initialisiert eine neue Instanz von[`Converter`](../../converter) Klasse.

```csharp
public Converter(string filePath, Func<FileType, LoadOptions> loadOptions, 
    Func<ConverterSettings> settings)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | String | Der Dateipfad zum Quelldokument. |
| loadOptions | Func`2 | Die Methoden, die Dokumentladeoptionen zurückgeben. |
| settings | Func`1 | Die Konverter-Einstellungen. |

### Bemerkungen

**Mehr erfahren**

* Weitere Informationen zum Laden und Konvertieren von Dokumenten, die auf FTP, Amazon S3-Speicher, Windows Azure oder einem anderen Speicher von Drittanbietern gespeichert sind: [Laden von Dokumenten aus verschiedenen Quellen](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* Weitere Informationen zu Optionen zum Laden von Dokumenten in Abhängigkeit vom Dateityp: [Ladeoptionen für verschiedene Dokumenttypen](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Siehe auch

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* namensraum [GroupDocs.Conversion](../../converter)
* Montage [GroupDocs.Conversion](../../../)

---

## Converter() {#constructor}

Initialisiert eine neue Instanz von[`Converter`](../../converter) Klasse für die Einrichtung der fließenden Konvertierung.

```csharp
public Converter()
```

### Bemerkungen

Beispiel für die Verwendung von Fluent Conversions:

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

### Siehe auch

* class [Converter](../../converter)
* namensraum [GroupDocs.Conversion](../../converter)
* Montage [GroupDocs.Conversion](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
