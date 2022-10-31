---
title: Convert
second_title: GroupDocs.Conversion für .NET-API-Referenz
description: Konvertiert Quelldokument. Speichert das gesamte konvertierte Dokument.
type: docs
weight: 20
url: /de/net/groupdocs.conversion/converter/convert/
---
## Convert(SaveDocumentStream, ConvertOptions) {#convert_3}

Konvertiert Quelldokument. Speichert das gesamte konvertierte Dokument.

```csharp
public void Convert(SaveDocumentStream document, ConvertOptions convertOptions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| document | SaveDocumentStream | Der Delegat, der das konvertierte Dokument in einem Stream speichert. |
| convertOptions | ConvertOptions | Die Konvertierungsoptionen sind spezifisch für den gewünschten Zieldateityp. |

### Bemerkungen

**Mehr erfahren**

* Weitere Informationen zu den Basisszenarien der Dokumentenkonvertierung: [So konvertieren Sie ein Dokument in 3 Schritten](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion-Anwendungsfälle, erweiterte Einstellungen und Anpassungen: [Dokument mit erweiterten Einstellungen konvertieren](https://docs.groupdocs.com/display/conversionnet/Converting)

### Siehe auch

* delegate [SaveDocumentStream](../../../groupdocs.conversion.contracts/savedocumentstream)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namensraum [GroupDocs.Conversion](../../converter)
* Montage [GroupDocs.Conversion](../../../)

---

## Convert(SaveDocumentStream, ConvertedDocumentStream, ConvertOptions) {#convert_1}

Konvertiert Quelldokument. Speichert das gesamte konvertierte Dokument.

```csharp
public void Convert(SaveDocumentStream document, ConvertedDocumentStream documentCompleted, 
    ConvertOptions convertOptions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| document | SaveDocumentStream | Der Delegat, der das konvertierte Dokument in einem Stream speichert. |
| documentCompleted | ConvertedDocumentStream | Der Delegat, der den konvertierten Dokumentstream empfängt. |
| convertOptions | ConvertOptions | Die Konvertierungsoptionen sind spezifisch für den gewünschten Zieldateityp. |

### Bemerkungen

**Mehr erfahren**

* Weitere Informationen zu den Basisszenarien der Dokumentenkonvertierung: [So konvertieren Sie ein Dokument in 3 Schritten](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion-Anwendungsfälle, erweiterte Einstellungen und Anpassungen: [Dokument mit erweiterten Einstellungen konvertieren](https://docs.groupdocs.com/display/conversionnet/Converting)

### Siehe auch

* delegate [SaveDocumentStream](../../../groupdocs.conversion.contracts/savedocumentstream)
* delegate [ConvertedDocumentStream](../../../groupdocs.conversion.contracts/converteddocumentstream)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namensraum [GroupDocs.Conversion](../../converter)
* Montage [GroupDocs.Conversion](../../../)

---

## Convert(SaveDocumentStream, ConvertOptionsProvider) {#convert_2}

Konvertiert Quelldokument. Speichert das gesamte konvertierte Dokument.

```csharp
public void Convert(SaveDocumentStream document, ConvertOptionsProvider convertOptionsProvider)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| document | SaveDocumentStream | Der Delegat, der das konvertierte Dokument in einem Stream speichert. |
| convertOptionsProvider | ConvertOptionsProvider | Optionsanbieter konvertieren. Wird für jede Konvertierung aufgerufen, um spezifische Konvertierungsoptionen für den gewünschten Zieldokumenttyp bereitzustellen. |

### Bemerkungen

**Mehr erfahren**

* Weitere Informationen zu den Basisszenarien der Dokumentenkonvertierung: [So konvertieren Sie ein Dokument in 3 Schritten](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion-Anwendungsfälle, erweiterte Einstellungen und Anpassungen: [Dokument mit erweiterten Einstellungen konvertieren](https://docs.groupdocs.com/display/conversionnet/Converting)

### Siehe auch

* delegate [SaveDocumentStream](../../../groupdocs.conversion.contracts/savedocumentstream)
* delegate [ConvertOptionsProvider](../../../groupdocs.conversion.contracts/convertoptionsprovider)
* class [Converter](../../converter)
* namensraum [GroupDocs.Conversion](../../converter)
* Montage [GroupDocs.Conversion](../../../)

---

## Convert(SaveDocumentStream, ConvertedDocumentStream, ConvertOptionsProvider) {#convert}

Konvertiert Quelldokument. Speichert das gesamte konvertierte Dokument.

```csharp
public void Convert(SaveDocumentStream document, ConvertedDocumentStream documentCompleted, 
    ConvertOptionsProvider convertOptionsProvider)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| document | SaveDocumentStream | Der Delegat, der das konvertierte Dokument in einem Stream speichert. |
| documentCompleted | ConvertedDocumentStream | Der Delegat, der den konvertierten Dokumentstream empfängt. |
| convertOptionsProvider | ConvertOptionsProvider | Optionsanbieter konvertieren. Wird für jede Konvertierung aufgerufen, um spezifische Konvertierungsoptionen für den gewünschten Zieldokumenttyp bereitzustellen. |

### Bemerkungen

**Mehr erfahren**

* Weitere Informationen zu den Basisszenarien der Dokumentenkonvertierung: [So konvertieren Sie ein Dokument in 3 Schritten](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion-Anwendungsfälle, erweiterte Einstellungen und Anpassungen: [Dokument mit erweiterten Einstellungen konvertieren](https://docs.groupdocs.com/display/conversionnet/Converting)

### Siehe auch

* delegate [SaveDocumentStream](../../../groupdocs.conversion.contracts/savedocumentstream)
* delegate [ConvertedDocumentStream](../../../groupdocs.conversion.contracts/converteddocumentstream)
* delegate [ConvertOptionsProvider](../../../groupdocs.conversion.contracts/convertoptionsprovider)
* class [Converter](../../converter)
* namensraum [GroupDocs.Conversion](../../converter)
* Montage [GroupDocs.Conversion](../../../)

---

## Convert(SaveDocumentStreamForFileType, ConvertOptions) {#convert_7}

Konvertiert Quelldokument. Speichert das gesamte konvertierte Dokument.

```csharp
public void Convert(SaveDocumentStreamForFileType document, ConvertOptions convertOptions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| document | SaveDocumentStreamForFileType | Der Delegat, der das konvertierte Dokument in einem Stream speichert. |
| convertOptions | ConvertOptions | Die Konvertierungsoptionen sind spezifisch für den gewünschten Zieldateityp. |

### Bemerkungen

**Mehr erfahren**

* Weitere Informationen zu den Basisszenarien der Dokumentenkonvertierung: [So konvertieren Sie ein Dokument in 3 Schritten](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion-Anwendungsfälle, erweiterte Einstellungen und Anpassungen: [Dokument mit erweiterten Einstellungen konvertieren](https://docs.groupdocs.com/display/conversionnet/Converting)

### Siehe auch

* delegate [SaveDocumentStreamForFileType](../../../groupdocs.conversion.contracts/savedocumentstreamforfiletype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namensraum [GroupDocs.Conversion](../../converter)
* Montage [GroupDocs.Conversion](../../../)

---

## Convert(SaveDocumentStreamForFileType, ConvertedDocumentStream, ConvertOptions) {#convert_5}

Konvertiert Quelldokument. Speichert das gesamte konvertierte Dokument.

```csharp
public void Convert(SaveDocumentStreamForFileType document, 
    ConvertedDocumentStream documentCompleted, ConvertOptions convertOptions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| document | SaveDocumentStreamForFileType | Der Delegat, der das konvertierte Dokument in einem Stream speichert. |
| documentCompleted | ConvertedDocumentStream | Der Delegat, der den konvertierten Dokumentstream empfängt. |
| convertOptions | ConvertOptions | Die Konvertierungsoptionen sind spezifisch für den gewünschten Zieldateityp. |

### Bemerkungen

**Mehr erfahren**

* Weitere Informationen zu den Basisszenarien der Dokumentenkonvertierung: [So konvertieren Sie ein Dokument in 3 Schritten](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion-Anwendungsfälle, erweiterte Einstellungen und Anpassungen: [Dokument mit erweiterten Einstellungen konvertieren](https://docs.groupdocs.com/display/conversionnet/Converting)

### Siehe auch

* delegate [SaveDocumentStreamForFileType](../../../groupdocs.conversion.contracts/savedocumentstreamforfiletype)
* delegate [ConvertedDocumentStream](../../../groupdocs.conversion.contracts/converteddocumentstream)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namensraum [GroupDocs.Conversion](../../converter)
* Montage [GroupDocs.Conversion](../../../)

---

## Convert(SaveDocumentStreamForFileType, ConvertOptionsProvider) {#convert_6}

Konvertiert Quelldokument. Speichert das gesamte konvertierte Dokument.

```csharp
public void Convert(SaveDocumentStreamForFileType document, 
    ConvertOptionsProvider convertOptionsProvider)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| document | SaveDocumentStreamForFileType | Der Delegat, der das konvertierte Dokument in einem Stream speichert. |
| convertOptionsProvider | ConvertOptionsProvider | Optionsanbieter konvertieren. Wird für jede Konvertierung aufgerufen, um spezifische Konvertierungsoptionen für den gewünschten Zieldokumenttyp bereitzustellen. |

### Bemerkungen

**Mehr erfahren**

* Weitere Informationen zu den Basisszenarien der Dokumentenkonvertierung: [So konvertieren Sie ein Dokument in 3 Schritten](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion-Anwendungsfälle, erweiterte Einstellungen und Anpassungen: [Dokument mit erweiterten Einstellungen konvertieren](https://docs.groupdocs.com/display/conversionnet/Converting)

### Siehe auch

* delegate [SaveDocumentStreamForFileType](../../../groupdocs.conversion.contracts/savedocumentstreamforfiletype)
* delegate [ConvertOptionsProvider](../../../groupdocs.conversion.contracts/convertoptionsprovider)
* class [Converter](../../converter)
* namensraum [GroupDocs.Conversion](../../converter)
* Montage [GroupDocs.Conversion](../../../)

---

## Convert(SaveDocumentStreamForFileType, ConvertedDocumentStream, ConvertOptionsProvider) {#convert_4}

Konvertiert Quelldokument. Speichert das gesamte konvertierte Dokument.

```csharp
public void Convert(SaveDocumentStreamForFileType document, 
    ConvertedDocumentStream documentCompleted, ConvertOptionsProvider convertOptionsProvider)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| document | SaveDocumentStreamForFileType | Der Delegat, der das konvertierte Dokument in einem Stream speichert. |
| documentCompleted | ConvertedDocumentStream | Der Delegat, der den konvertierten Dokumentstream empfängt. |
| convertOptionsProvider | ConvertOptionsProvider | Optionsanbieter konvertieren. Wird für jede Konvertierung aufgerufen, um spezifische Konvertierungsoptionen für den gewünschten Zieldokumenttyp bereitzustellen. |

### Bemerkungen

**Mehr erfahren**

* Weitere Informationen zu den Basisszenarien der Dokumentenkonvertierung: [So konvertieren Sie ein Dokument in 3 Schritten](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion-Anwendungsfälle, erweiterte Einstellungen und Anpassungen: [Dokument mit erweiterten Einstellungen konvertieren](https://docs.groupdocs.com/display/conversionnet/Converting)

### Siehe auch

* delegate [SaveDocumentStreamForFileType](../../../groupdocs.conversion.contracts/savedocumentstreamforfiletype)
* delegate [ConvertedDocumentStream](../../../groupdocs.conversion.contracts/converteddocumentstream)
* delegate [ConvertOptionsProvider](../../../groupdocs.conversion.contracts/convertoptionsprovider)
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

**Mehr erfahren**

* Weitere Informationen zu den Basisszenarien der Dokumentenkonvertierung: [So konvertieren Sie ein Dokument in 3 Schritten](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion-Anwendungsfälle, erweiterte Einstellungen und Anpassungen: [Dokument mit erweiterten Einstellungen konvertieren](https://docs.groupdocs.com/display/conversionnet/Converting)

### Siehe auch

* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namensraum [GroupDocs.Conversion](../../converter)
* Montage [GroupDocs.Conversion](../../../)

---

## Convert(SavePageStream, ConvertOptions) {#convert_11}

Konvertiert Quelldokument. Speichert das konvertierte Dokument Seite für Seite.

```csharp
public void Convert(SavePageStream document, ConvertOptions convertOptions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| document | SavePageStream | Der Delegat, der das konvertierte Dokument in einem Stream speichert. |
| convertOptions | ConvertOptions | Die Konvertierungsoptionen sind spezifisch für den gewünschten Zieldateityp. |

### Bemerkungen

**Mehr erfahren**

* Weitere Informationen zu den Basisszenarien der Dokumentenkonvertierung: [So konvertieren Sie ein Dokument in 3 Schritten](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion-Anwendungsfälle, erweiterte Einstellungen und Anpassungen: [Dokument mit erweiterten Einstellungen konvertieren](https://docs.groupdocs.com/display/conversionnet/Converting)

### Siehe auch

* delegate [SavePageStream](../../../groupdocs.conversion.contracts/savepagestream)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namensraum [GroupDocs.Conversion](../../converter)
* Montage [GroupDocs.Conversion](../../../)

---

## Convert(SavePageStream, ConvertedPageStream, ConvertOptions) {#convert_9}

Konvertiert Quelldokument. Speichert das konvertierte Dokument Seite für Seite.

```csharp
public void Convert(SavePageStream document, ConvertedPageStream documentCompleted, 
    ConvertOptions convertOptions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| document | SavePageStream | Der Delegat, der die konvertierte Dokumentseite in einem Stream speichert. |
| documentCompleted | ConvertedPageStream | Der Delegat, der den konvertierten Dokumentseitenstream empfängt. |
| convertOptions | ConvertOptions | Die Konvertierungsoptionen sind spezifisch für den gewünschten Zieldateityp. |

### Bemerkungen

**Mehr erfahren**

* Weitere Informationen zu den Basisszenarien der Dokumentenkonvertierung: [So konvertieren Sie ein Dokument in 3 Schritten](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion-Anwendungsfälle, erweiterte Einstellungen und Anpassungen: [Dokument mit erweiterten Einstellungen konvertieren](https://docs.groupdocs.com/display/conversionnet/Converting)

### Siehe auch

* delegate [SavePageStream](../../../groupdocs.conversion.contracts/savepagestream)
* delegate [ConvertedPageStream](../../../groupdocs.conversion.contracts/convertedpagestream)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namensraum [GroupDocs.Conversion](../../converter)
* Montage [GroupDocs.Conversion](../../../)

---

## Convert(SavePageStream, ConvertOptionsProvider) {#convert_10}

Konvertiert Quelldokument. Speichert das konvertierte Dokument Seite für Seite.

```csharp
public void Convert(SavePageStream document, ConvertOptionsProvider convertOptionsProvider)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| document | SavePageStream | Der Delegat, der das konvertierte Dokument in einem Stream speichert. |
| convertOptionsProvider | ConvertOptionsProvider | Optionsanbieter konvertieren. Wird für jede Konvertierung aufgerufen, um spezifische Konvertierungsoptionen für den gewünschten Zieldokumenttyp bereitzustellen. |

### Bemerkungen

**Mehr erfahren**

* Weitere Informationen zu den Basisszenarien der Dokumentenkonvertierung: [So konvertieren Sie ein Dokument in 3 Schritten](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion-Anwendungsfälle, erweiterte Einstellungen und Anpassungen: [Dokument mit erweiterten Einstellungen konvertieren](https://docs.groupdocs.com/display/conversionnet/Converting)

### Siehe auch

* delegate [SavePageStream](../../../groupdocs.conversion.contracts/savepagestream)
* delegate [ConvertOptionsProvider](../../../groupdocs.conversion.contracts/convertoptionsprovider)
* class [Converter](../../converter)
* namensraum [GroupDocs.Conversion](../../converter)
* Montage [GroupDocs.Conversion](../../../)

---

## Convert(SavePageStream, ConvertedPageStream, ConvertOptionsProvider) {#convert_8}

Konvertiert Quelldokument. Speichert das konvertierte Dokument Seite für Seite.

```csharp
public void Convert(SavePageStream document, ConvertedPageStream documentCompleted, 
    ConvertOptionsProvider convertOptionsProvider)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| document | SavePageStream | Der Delegat, der die konvertierte Dokumentseite in einem Stream speichert. |
| documentCompleted | ConvertedPageStream | Der Delegat, der den konvertierten Dokumentseitenstream empfängt. |
| convertOptionsProvider | ConvertOptionsProvider | Optionsanbieter konvertieren. Wird für jede Konvertierung aufgerufen, um spezifische Konvertierungsoptionen für den gewünschten Zieldokumenttyp bereitzustellen. |

### Bemerkungen

**Mehr erfahren**

* Weitere Informationen zu den Basisszenarien der Dokumentenkonvertierung: [So konvertieren Sie ein Dokument in 3 Schritten](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion-Anwendungsfälle, erweiterte Einstellungen und Anpassungen: [Dokument mit erweiterten Einstellungen konvertieren](https://docs.groupdocs.com/display/conversionnet/Converting)

### Siehe auch

* delegate [SavePageStream](../../../groupdocs.conversion.contracts/savepagestream)
* delegate [ConvertedPageStream](../../../groupdocs.conversion.contracts/convertedpagestream)
* delegate [ConvertOptionsProvider](../../../groupdocs.conversion.contracts/convertoptionsprovider)
* class [Converter](../../converter)
* namensraum [GroupDocs.Conversion](../../converter)
* Montage [GroupDocs.Conversion](../../../)

---

## Convert(SavePageStreamForFileType, ConvertOptions) {#convert_15}

Konvertiert Quelldokument. Speichert das konvertierte Dokument Seite für Seite.

```csharp
public void Convert(SavePageStreamForFileType document, ConvertOptions convertOptions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| document | SavePageStreamForFileType | Der Delegat, der das konvertierte Dokument in einem Stream speichert. |
| convertOptions | ConvertOptions | Die Konvertierungsoptionen sind spezifisch für den gewünschten Zieldateityp. |

### Bemerkungen

**Mehr erfahren**

* Weitere Informationen zu den Basisszenarien der Dokumentenkonvertierung: [So konvertieren Sie ein Dokument in 3 Schritten](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion-Anwendungsfälle, erweiterte Einstellungen und Anpassungen: [Dokument mit erweiterten Einstellungen konvertieren](https://docs.groupdocs.com/display/conversionnet/Converting)

### Siehe auch

* delegate [SavePageStreamForFileType](../../../groupdocs.conversion.contracts/savepagestreamforfiletype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namensraum [GroupDocs.Conversion](../../converter)
* Montage [GroupDocs.Conversion](../../../)

---

## Convert(SavePageStreamForFileType, ConvertedPageStream, ConvertOptions) {#convert_13}

Konvertiert Quelldokument. Speichert das konvertierte Dokument Seite für Seite.

```csharp
public void Convert(SavePageStreamForFileType document, ConvertedPageStream documentCompleted, 
    ConvertOptions convertOptions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| document | SavePageStreamForFileType | Der Delegat, der die konvertierte Dokumentseite in einem Stream speichert. |
| documentCompleted | ConvertedPageStream | Der Delegat, der den konvertierten Dokumentseitenstream empfängt. |
| convertOptions | ConvertOptions | Die Konvertierungsoptionen sind spezifisch für den gewünschten Zieldateityp. |

### Bemerkungen

**Mehr erfahren**

* Weitere Informationen zu den Basisszenarien der Dokumentenkonvertierung: [So konvertieren Sie ein Dokument in 3 Schritten](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion-Anwendungsfälle, erweiterte Einstellungen und Anpassungen: [Dokument mit erweiterten Einstellungen konvertieren](https://docs.groupdocs.com/display/conversionnet/Converting)

### Siehe auch

* delegate [SavePageStreamForFileType](../../../groupdocs.conversion.contracts/savepagestreamforfiletype)
* delegate [ConvertedPageStream](../../../groupdocs.conversion.contracts/convertedpagestream)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namensraum [GroupDocs.Conversion](../../converter)
* Montage [GroupDocs.Conversion](../../../)

---

## Convert(SavePageStreamForFileType, ConvertOptionsProvider) {#convert_14}

Konvertiert Quelldokument. Speichert das konvertierte Dokument Seite für Seite.

```csharp
public void Convert(SavePageStreamForFileType document, 
    ConvertOptionsProvider convertOptionsProvider)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| document | SavePageStreamForFileType | Der Delegat, der das konvertierte Dokument in einem Stream speichert. |
| convertOptionsProvider | ConvertOptionsProvider | Optionsanbieter konvertieren. Wird für jede Konvertierung aufgerufen, um spezifische Konvertierungsoptionen für den gewünschten Zieldokumenttyp bereitzustellen. |

### Bemerkungen

**Mehr erfahren**

* Weitere Informationen zu den Basisszenarien der Dokumentenkonvertierung: [So konvertieren Sie ein Dokument in 3 Schritten](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion-Anwendungsfälle, erweiterte Einstellungen und Anpassungen: [Dokument mit erweiterten Einstellungen konvertieren](https://docs.groupdocs.com/display/conversionnet/Converting)

### Siehe auch

* delegate [SavePageStreamForFileType](../../../groupdocs.conversion.contracts/savepagestreamforfiletype)
* delegate [ConvertOptionsProvider](../../../groupdocs.conversion.contracts/convertoptionsprovider)
* class [Converter](../../converter)
* namensraum [GroupDocs.Conversion](../../converter)
* Montage [GroupDocs.Conversion](../../../)

---

## Convert(SavePageStreamForFileType, ConvertedPageStream, ConvertOptionsProvider) {#convert_12}

Konvertiert Quelldokument. Speichert das konvertierte Dokument Seite für Seite.

```csharp
public void Convert(SavePageStreamForFileType document, ConvertedPageStream documentCompleted, 
    ConvertOptionsProvider convertOptionsProvider)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| document | SavePageStreamForFileType | Der Delegat, der die konvertierte Dokumentseite in einem Stream speichert. |
| documentCompleted | ConvertedPageStream | Der Delegat, der den konvertierten Dokumentseitenstream empfängt. |
| convertOptionsProvider | ConvertOptionsProvider | Optionsanbieter konvertieren. Wird für jede Konvertierung aufgerufen, um spezifische Konvertierungsoptionen für den gewünschten Zieldokumenttyp bereitzustellen. |

### Bemerkungen

**Mehr erfahren**

* Weitere Informationen zu den Basisszenarien der Dokumentenkonvertierung: [So konvertieren Sie ein Dokument in 3 Schritten](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion-Anwendungsfälle, erweiterte Einstellungen und Anpassungen: [Dokument mit erweiterten Einstellungen konvertieren](https://docs.groupdocs.com/display/conversionnet/Converting)

### Siehe auch

* delegate [SavePageStreamForFileType](../../../groupdocs.conversion.contracts/savepagestreamforfiletype)
* delegate [ConvertedPageStream](../../../groupdocs.conversion.contracts/convertedpagestream)
* delegate [ConvertOptionsProvider](../../../groupdocs.conversion.contracts/convertoptionsprovider)
* class [Converter](../../converter)
* namensraum [GroupDocs.Conversion](../../converter)
* Montage [GroupDocs.Conversion](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
