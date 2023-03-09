---
title: Convert
second_title: GroupDocs.Conversion für .NET-API-Referenz
description: Konvertiert Quelldokument. Speichert das gesamte konvertierte Dokument.
type: docs
weight: 20
url: /de/net/groupdocs.conversion/converter/convert/
---
## Convert(Func&lt;Stream&gt;, ConvertOptions) {#convert}

Konvertiert Quelldokument. Speichert das gesamte konvertierte Dokument.

```csharp
public void Convert(Func<Stream> document, ConvertOptions convertOptions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| document | Func`1 | Der Delegat, der das konvertierte Dokument in einem Stream speichert. |
| convertOptions | ConvertOptions | Die Konvertierungsoptionen sind spezifisch für den gewünschten Zieldateityp. |

### Bemerkungen

**Erfahren Sie mehr**

* Weitere Informationen zu den Basisszenarien der Dokumentenkonvertierung: [So konvertieren Sie ein Dokument in 3 Schritten](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion-Anwendungsfälle, erweiterte Einstellungen und Anpassungen: [Dokument mit erweiterten Einstellungen konvertieren](https://docs.groupdocs.com/display/conversionnet/Converting)

### Siehe auch

* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namensraum [GroupDocs.Conversion](../../converter)
* Montage [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;Stream&gt;, Action&lt;Stream, string&gt;, ConvertOptions) {#convert_1}

Konvertiert Quelldokument. Speichert das gesamte konvertierte Dokument.

```csharp
public void Convert(Func<Stream> document, Action<Stream, string> documentCompleted, 
    ConvertOptions convertOptions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| document | Func`1 | Der Delegat, der das konvertierte Dokument in einem Stream speichert. |
| documentCompleted | Action`2 | Der Delegat, der den konvertierten Dokumentstream empfängt. Der DateiinhaltsstromDer Name der Datei |
| convertOptions | ConvertOptions | Die Konvertierungsoptionen sind spezifisch für den gewünschten Zieldateityp. |

### Bemerkungen

**Erfahren Sie mehr**

* Weitere Informationen zu den Basisszenarien der Dokumentenkonvertierung: [So konvertieren Sie ein Dokument in 3 Schritten](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion-Anwendungsfälle, erweiterte Einstellungen und Anpassungen: [Dokument mit erweiterten Einstellungen konvertieren](https://docs.groupdocs.com/display/conversionnet/Converting)

### Siehe auch

* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namensraum [GroupDocs.Conversion](../../converter)
* Montage [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;Stream&gt;, Func&lt;string, FileType, ConvertOptions&gt;) {#convert_3}

Konvertiert Quelldokument. Speichert das gesamte konvertierte Dokument.

```csharp
public void Convert(Func<Stream> document, 
    Func<string, FileType, ConvertOptions> convertOptionsProvider)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| document | Func`1 | Der Delegat, der das konvertierte Dokument in einem Stream speichert. |
| convertOptionsProvider | Func`3 | Optionsanbieter konvertieren. Wird für jede Konvertierung aufgerufen, um spezifische Konvertierungsoptionen für den gewünschten Zieldokumenttyp bereitzustellen. Der Name der DateiDer Typ der Datei |

### Bemerkungen

**Erfahren Sie mehr**

* Weitere Informationen zu den Basisszenarien der Dokumentenkonvertierung: [So konvertieren Sie ein Dokument in 3 Schritten](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion-Anwendungsfälle, erweiterte Einstellungen und Anpassungen: [Dokument mit erweiterten Einstellungen konvertieren](https://docs.groupdocs.com/display/conversionnet/Converting)

### Siehe auch

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namensraum [GroupDocs.Conversion](../../converter)
* Montage [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;Stream&gt;, Action&lt;Stream, string&gt;, Func&lt;string, FileType, ConvertOptions&gt;) {#convert_2}

Konvertiert Quelldokument. Speichert das gesamte konvertierte Dokument.

```csharp
public void Convert(Func<Stream> document, Action<Stream, string> documentCompleted, 
    Func<string, FileType, ConvertOptions> convertOptionsProvider)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| document | Func`1 | Der Delegat, der das konvertierte Dokument in einem Stream speichert. |
| documentCompleted | Action`2 | Der Delegat, der den konvertierten Dokumentstream empfängt. Der DateiinhaltsstromDer Name der Datei |
| convertOptionsProvider | Func`3 | Optionsanbieter konvertieren. Wird für jede Konvertierung aufgerufen, um spezifische Konvertierungsoptionen für den gewünschten Zieldokumenttyp bereitzustellen. Der Name der DateiDer Typ der Datei |

### Bemerkungen

**Erfahren Sie mehr**

* Weitere Informationen zu den Basisszenarien der Dokumentenkonvertierung: [So konvertieren Sie ein Dokument in 3 Schritten](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion-Anwendungsfälle, erweiterte Einstellungen und Anpassungen: [Dokument mit erweiterten Einstellungen konvertieren](https://docs.groupdocs.com/display/conversionnet/Converting)

### Siehe auch

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namensraum [GroupDocs.Conversion](../../converter)
* Montage [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;FileType, Stream&gt;, ConvertOptions) {#convert_4}

Konvertiert Quelldokument. Speichert das gesamte konvertierte Dokument.

```csharp
public void Convert(Func<FileType, Stream> document, ConvertOptions convertOptions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| document | Func`2 | Der Delegat, der das konvertierte Dokument in einem Stream speichert. Der Typ der Quelldatei |
| convertOptions | ConvertOptions | Die Konvertierungsoptionen sind spezifisch für den gewünschten Zieldateityp. |

### Bemerkungen

**Erfahren Sie mehr**

* Weitere Informationen zu den Basisszenarien der Dokumentenkonvertierung: [So konvertieren Sie ein Dokument in 3 Schritten](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion-Anwendungsfälle, erweiterte Einstellungen und Anpassungen: [Dokument mit erweiterten Einstellungen konvertieren](https://docs.groupdocs.com/display/conversionnet/Converting)

### Siehe auch

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namensraum [GroupDocs.Conversion](../../converter)
* Montage [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;FileType, Stream&gt;, Action&lt;Stream, string&gt;, ConvertOptions) {#convert_5}

Konvertiert Quelldokument. Speichert das gesamte konvertierte Dokument.

```csharp
public void Convert(Func<FileType, Stream> document, Action<Stream, string> documentCompleted, 
    ConvertOptions convertOptions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| document | Func`2 | Der Delegat, der das konvertierte Dokument in einem Stream speichert. Der Typ der Quelldatei |
| documentCompleted | Action`2 | Der Delegat, der den konvertierten Dokumentstream empfängt. Der DateiinhaltsstromDer Name der Datei |
| convertOptions | ConvertOptions | Die Konvertierungsoptionen sind spezifisch für den gewünschten Zieldateityp. |

### Bemerkungen

**Erfahren Sie mehr**

* Weitere Informationen zu den Basisszenarien der Dokumentenkonvertierung: [So konvertieren Sie ein Dokument in 3 Schritten](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion-Anwendungsfälle, erweiterte Einstellungen und Anpassungen: [Dokument mit erweiterten Einstellungen konvertieren](https://docs.groupdocs.com/display/conversionnet/Converting)

### Siehe auch

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namensraum [GroupDocs.Conversion](../../converter)
* Montage [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;FileType, Stream&gt;, Func&lt;string, FileType, ConvertOptions&gt;) {#convert_7}

Konvertiert Quelldokument. Speichert das gesamte konvertierte Dokument.

```csharp
public void Convert(Func<FileType, Stream> document, 
    Func<string, FileType, ConvertOptions> convertOptionsProvider)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| document | Func`2 | Der Delegat, der das konvertierte Dokument in einem Stream speichert. Der Typ der Quelldatei |
| convertOptionsProvider | Func`3 | Optionsanbieter konvertieren. Wird für jede Konvertierung aufgerufen, um spezifische Konvertierungsoptionen für den gewünschten Zieldokumenttyp bereitzustellen. Der Name der DateiDer Typ der Datei |

### Bemerkungen

**Erfahren Sie mehr**

* Weitere Informationen zu den Basisszenarien der Dokumentenkonvertierung: [So konvertieren Sie ein Dokument in 3 Schritten](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion-Anwendungsfälle, erweiterte Einstellungen und Anpassungen: [Dokument mit erweiterten Einstellungen konvertieren](https://docs.groupdocs.com/display/conversionnet/Converting)

### Siehe auch

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namensraum [GroupDocs.Conversion](../../converter)
* Montage [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;FileType, Stream&gt;, Action&lt;Stream, string&gt;, Func&lt;string, FileType, ConvertOptions&gt;) {#convert_6}

Konvertiert Quelldokument. Speichert das gesamte konvertierte Dokument.

```csharp
public void Convert(Func<FileType, Stream> document, Action<Stream, string> documentCompleted, 
    Func<string, FileType, ConvertOptions> convertOptionsProvider)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| document | Func`2 | Der Delegat, der das konvertierte Dokument in einem Stream speichert. Der Typ der Quelldatei |
| documentCompleted | Action`2 | Der Delegat, der den konvertierten Dokumentstream empfängt. Der DateiinhaltsstromDer Name der Datei |
| convertOptionsProvider | Func`3 | Optionsanbieter konvertieren. Wird für jede Konvertierung aufgerufen, um spezifische Konvertierungsoptionen für den gewünschten Zieldokumenttyp bereitzustellen. Der Name der DateiDer Typ der Datei |

### Bemerkungen

**Erfahren Sie mehr**

* Weitere Informationen zu den Basisszenarien der Dokumentenkonvertierung: [So konvertieren Sie ein Dokument in 3 Schritten](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion-Anwendungsfälle, erweiterte Einstellungen und Anpassungen: [Dokument mit erweiterten Einstellungen konvertieren](https://docs.groupdocs.com/display/conversionnet/Converting)

### Siehe auch

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namensraum [GroupDocs.Conversion](../../converter)
* Montage [GroupDocs.Conversion](../../../)

---

## Convert(string, ConvertOptions) {#convert_16}

Konvertiert Quelldokument. Speichert das gesamte konvertierte Dokument.

```csharp
public void Convert(string filePath, ConvertOptions convertOptions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | String | Der Dateipfad zum Quelldokument. |
| convertOptions | ConvertOptions | Die Konvertierungsoptionen sind spezifisch für den gewünschten Zieldateityp. |

### Bemerkungen

**Erfahren Sie mehr**

* Weitere Informationen zu den Basisszenarien der Dokumentenkonvertierung: [So konvertieren Sie ein Dokument in 3 Schritten](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion-Anwendungsfälle, erweiterte Einstellungen und Anpassungen: [Dokument mit erweiterten Einstellungen konvertieren](https://docs.groupdocs.com/display/conversionnet/Converting)

### Siehe auch

* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namensraum [GroupDocs.Conversion](../../converter)
* Montage [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;int, Stream&gt;, ConvertOptions) {#convert_8}

Konvertiert Quelldokument. Speichert das konvertierte Dokument Seite für Seite.

```csharp
public void Convert(Func<int, Stream> document, ConvertOptions convertOptions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| document | Func`2 | Der Delegat, der das konvertierte Dokument in einem Stream speichert. Seitennummer |
| convertOptions | ConvertOptions | Die Konvertierungsoptionen sind spezifisch für den gewünschten Zieldateityp. |

### Bemerkungen

**Erfahren Sie mehr**

* Weitere Informationen zu den Basisszenarien der Dokumentenkonvertierung: [So konvertieren Sie ein Dokument in 3 Schritten](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion-Anwendungsfälle, erweiterte Einstellungen und Anpassungen: [Dokument mit erweiterten Einstellungen konvertieren](https://docs.groupdocs.com/display/conversionnet/Converting)

### Siehe auch

* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namensraum [GroupDocs.Conversion](../../converter)
* Montage [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;int, Stream&gt;, Action&lt;int, Stream, string&gt;, ConvertOptions) {#convert_9}

Konvertiert Quelldokument. Speichert das konvertierte Dokument Seite für Seite.

```csharp
public void Convert(Func<int, Stream> document, Action<int, Stream, string> documentCompleted, 
    ConvertOptions convertOptions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| document | Func`2 | Der Delegat, der die konvertierte Dokumentseite in einem Stream speichert. Seitennummer |
| documentCompleted | Action`3 | Der Delegat, der den konvertierten Dokumentseitenstream empfängt. SeitennummerDer DateiinhaltsstromDer Name der Datei |
| convertOptions | ConvertOptions | Die Konvertierungsoptionen sind spezifisch für den gewünschten Zieldateityp. |

### Bemerkungen

**Erfahren Sie mehr**

* Weitere Informationen zu den Basisszenarien der Dokumentenkonvertierung: [So konvertieren Sie ein Dokument in 3 Schritten](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion-Anwendungsfälle, erweiterte Einstellungen und Anpassungen: [Dokument mit erweiterten Einstellungen konvertieren](https://docs.groupdocs.com/display/conversionnet/Converting)

### Siehe auch

* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namensraum [GroupDocs.Conversion](../../converter)
* Montage [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;int, Stream&gt;, Func&lt;string, FileType, ConvertOptions&gt;) {#convert_11}

Konvertiert Quelldokument. Speichert das konvertierte Dokument Seite für Seite.

```csharp
public void Convert(Func<int, Stream> document, 
    Func<string, FileType, ConvertOptions> convertOptionsProvider)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| document | Func`2 | Der Delegat, der das konvertierte Dokument in einem Stream speichert. Seitennummer |
| convertOptionsProvider | Func`3 | Optionsanbieter konvertieren. Wird für jede Konvertierung aufgerufen, um spezifische Konvertierungsoptionen für den gewünschten Zieldokumenttyp bereitzustellen. Der Name der DateiDer Typ der Datei |

### Bemerkungen

**Erfahren Sie mehr**

* Weitere Informationen zu den Basisszenarien der Dokumentenkonvertierung: [So konvertieren Sie ein Dokument in 3 Schritten](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion-Anwendungsfälle, erweiterte Einstellungen und Anpassungen: [Dokument mit erweiterten Einstellungen konvertieren](https://docs.groupdocs.com/display/conversionnet/Converting)

### Siehe auch

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namensraum [GroupDocs.Conversion](../../converter)
* Montage [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;int, Stream&gt;, Action&lt;int, Stream, string&gt;, Func&lt;string, FileType, ConvertOptions&gt;) {#convert_10}

Konvertiert Quelldokument. Speichert das konvertierte Dokument Seite für Seite.

```csharp
public void Convert(Func<int, Stream> document, Action<int, Stream, string> documentCompleted, 
    Func<string, FileType, ConvertOptions> convertOptionsProvider)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| document | Func`2 | Der Delegat, der die konvertierte Dokumentseite in einem Stream speichert. Seitennummer |
| documentCompleted | Action`3 | Der Delegat, der den konvertierten Dokumentseitenstream empfängt. SeitennummerDer DateiinhaltsstromDer Name der Datei |
| convertOptionsProvider | Func`3 | Optionsanbieter konvertieren. Wird für jede Konvertierung aufgerufen, um spezifische Konvertierungsoptionen für den gewünschten Zieldokumenttyp bereitzustellen. Der Name der DateiDer Typ der Datei |

### Bemerkungen

**Erfahren Sie mehr**

* Weitere Informationen zu den Basisszenarien der Dokumentenkonvertierung: [So konvertieren Sie ein Dokument in 3 Schritten](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion-Anwendungsfälle, erweiterte Einstellungen und Anpassungen: [Dokument mit erweiterten Einstellungen konvertieren](https://docs.groupdocs.com/display/conversionnet/Converting)

### Siehe auch

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namensraum [GroupDocs.Conversion](../../converter)
* Montage [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;int, FileType, Stream&gt;, ConvertOptions) {#convert_12}

Konvertiert Quelldokument. Speichert das konvertierte Dokument Seite für Seite.

```csharp
public void Convert(Func<int, FileType, Stream> document, ConvertOptions convertOptions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| document | Func`3 | Der Delegat, der das konvertierte Dokument in einem Stream speichert. Seitennummer |
| convertOptions | ConvertOptions | Die Konvertierungsoptionen sind spezifisch für den gewünschten Zieldateityp. |

### Bemerkungen

**Erfahren Sie mehr**

* Weitere Informationen zu den Basisszenarien der Dokumentenkonvertierung: [So konvertieren Sie ein Dokument in 3 Schritten](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion-Anwendungsfälle, erweiterte Einstellungen und Anpassungen: [Dokument mit erweiterten Einstellungen konvertieren](https://docs.groupdocs.com/display/conversionnet/Converting)

### Siehe auch

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namensraum [GroupDocs.Conversion](../../converter)
* Montage [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;int, FileType, Stream&gt;, Action&lt;int, Stream, string&gt;, ConvertOptions) {#convert_13}

Konvertiert Quelldokument. Speichert das konvertierte Dokument Seite für Seite.

```csharp
public void Convert(Func<int, FileType, Stream> document, 
    Action<int, Stream, string> documentCompleted, ConvertOptions convertOptions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| document | Func`3 | Der Delegat, der die konvertierte Dokumentseite in einem Stream speichert. SeitennummerDateityp |
| documentCompleted | Action`3 | Der Delegat, der den konvertierten Dokumentseitenstream empfängt. SeitennummerDer DateiinhaltsstromDer Name der Datei |
| convertOptions | ConvertOptions | Die Konvertierungsoptionen sind spezifisch für den gewünschten Zieldateityp. |

### Bemerkungen

**Erfahren Sie mehr**

* Weitere Informationen zu den Basisszenarien der Dokumentenkonvertierung: [So konvertieren Sie ein Dokument in 3 Schritten](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion-Anwendungsfälle, erweiterte Einstellungen und Anpassungen: [Dokument mit erweiterten Einstellungen konvertieren](https://docs.groupdocs.com/display/conversionnet/Converting)

### Siehe auch

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namensraum [GroupDocs.Conversion](../../converter)
* Montage [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;int, FileType, Stream&gt;, Func&lt;string, FileType, ConvertOptions&gt;) {#convert_15}

Konvertiert Quelldokument. Speichert das konvertierte Dokument Seite für Seite.

```csharp
public void Convert(Func<int, FileType, Stream> document, 
    Func<string, FileType, ConvertOptions> convertOptionsProvider)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| document | Func`3 | Der Delegat, der das konvertierte Dokument in einem Stream speichert. SeitennummerDateityp |
| convertOptionsProvider | Func`3 | Optionsanbieter konvertieren. Wird für jede Konvertierung aufgerufen, um spezifische Konvertierungsoptionen für den gewünschten Zieldokumenttyp bereitzustellen. Der Name der DateiDer Typ der Datei |

### Bemerkungen

**Erfahren Sie mehr**

* Weitere Informationen zu den Basisszenarien der Dokumentenkonvertierung: [So konvertieren Sie ein Dokument in 3 Schritten](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion-Anwendungsfälle, erweiterte Einstellungen und Anpassungen: [Dokument mit erweiterten Einstellungen konvertieren](https://docs.groupdocs.com/display/conversionnet/Converting)

### Siehe auch

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namensraum [GroupDocs.Conversion](../../converter)
* Montage [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;int, FileType, Stream&gt;, Action&lt;int, Stream, string&gt;, Func&lt;string, FileType, ConvertOptions&gt;) {#convert_14}

Konvertiert Quelldokument. Speichert das konvertierte Dokument Seite für Seite.

```csharp
public void Convert(Func<int, FileType, Stream> document, 
    Action<int, Stream, string> documentCompleted, 
    Func<string, FileType, ConvertOptions> convertOptionsProvider)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| document | Func`3 | Der Delegat, der die konvertierte Dokumentseite in einem Stream speichert. SeitennummerDateityp |
| documentCompleted | Action`3 | Der Delegat, der den konvertierten Dokumentseitenstream empfängt. SeitennummerDer DateiinhaltsstromDer Name der Datei |
| convertOptionsProvider | Func`3 | Optionsanbieter konvertieren. Wird für jede Konvertierung aufgerufen, um spezifische Konvertierungsoptionen für den gewünschten Zieldokumenttyp bereitzustellen. Der Name der DateiDer Typ der Datei |

### Bemerkungen

**Erfahren Sie mehr**

* Weitere Informationen zu den Basisszenarien der Dokumentenkonvertierung: [So konvertieren Sie ein Dokument in 3 Schritten](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion-Anwendungsfälle, erweiterte Einstellungen und Anpassungen: [Dokument mit erweiterten Einstellungen konvertieren](https://docs.groupdocs.com/display/conversionnet/Converting)

### Siehe auch

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namensraum [GroupDocs.Conversion](../../converter)
* Montage [GroupDocs.Conversion](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
