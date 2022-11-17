---
title: Convert
second_title: GroupDocs.Conversion for .NET API Referens
description: Konverterar källdokument. Sparar hela det konverterade dokumentet.
type: docs
weight: 20
url: /sv/net/groupdocs.conversion/converter/convert/
---
## Convert(SaveDocumentStream, ConvertOptions) {#convert_3}

Konverterar källdokument. Sparar hela det konverterade dokumentet.

```csharp
public void Convert(SaveDocumentStream document, ConvertOptions convertOptions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| document | SaveDocumentStream | Ombudet som sparar konverterat dokument till en ström. |
| convertOptions | ConvertOptions | Konverteringsalternativen specifika för önskad målfiltyp. |

### Anmärkningar

**Läs mer**

* Mer om grundläggande scenarier för dokumentkonvertering: [Hur man konverterar dokument i 3 steg](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Användningsfall för konvertering, avancerade inställningar och anpassningar: [Konvertera dokument med avancerade inställningar](https://docs.groupdocs.com/display/conversionnet/Converting)

### Se även

* delegate [SaveDocumentStream](../../../groupdocs.conversion.contracts/savedocumentstream)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namnutrymme [GroupDocs.Conversion](../../converter)
* hopsättning [GroupDocs.Conversion](../../../)

---

## Convert(SaveDocumentStream, ConvertedDocumentStream, ConvertOptions) {#convert_1}

Konverterar källdokument. Sparar hela det konverterade dokumentet.

```csharp
public void Convert(SaveDocumentStream document, ConvertedDocumentStream documentCompleted, 
    ConvertOptions convertOptions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| document | SaveDocumentStream | Ombudet som sparar konverterat dokument till en ström. |
| documentCompleted | ConvertedDocumentStream | Delegaten som tar emot konverterad dokumentström. |
| convertOptions | ConvertOptions | Konverteringsalternativen specifika för önskad målfiltyp. |

### Anmärkningar

**Läs mer**

* Mer om grundläggande scenarier för dokumentkonvertering: [Hur man konverterar dokument i 3 steg](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Användningsfall för konvertering, avancerade inställningar och anpassningar: [Konvertera dokument med avancerade inställningar](https://docs.groupdocs.com/display/conversionnet/Converting)

### Se även

* delegate [SaveDocumentStream](../../../groupdocs.conversion.contracts/savedocumentstream)
* delegate [ConvertedDocumentStream](../../../groupdocs.conversion.contracts/converteddocumentstream)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namnutrymme [GroupDocs.Conversion](../../converter)
* hopsättning [GroupDocs.Conversion](../../../)

---

## Convert(SaveDocumentStream, ConvertOptionsProvider) {#convert_2}

Konverterar källdokument. Sparar hela det konverterade dokumentet.

```csharp
public void Convert(SaveDocumentStream document, ConvertOptionsProvider convertOptionsProvider)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| document | SaveDocumentStream | Ombudet som sparar konverterat dokument till en ström. |
| convertOptionsProvider | ConvertOptionsProvider | Konvertera alternativleverantör. Kommer att anropas för varje konvertering för att ge specifika konverteringsalternativ till önskad måldokumenttyp. |

### Anmärkningar

**Läs mer**

* Mer om grundläggande scenarier för dokumentkonvertering: [Hur man konverterar dokument i 3 steg](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Användningsfall för konvertering, avancerade inställningar och anpassningar: [Konvertera dokument med avancerade inställningar](https://docs.groupdocs.com/display/conversionnet/Converting)

### Se även

* delegate [SaveDocumentStream](../../../groupdocs.conversion.contracts/savedocumentstream)
* delegate [ConvertOptionsProvider](../../../groupdocs.conversion.contracts/convertoptionsprovider)
* class [Converter](../../converter)
* namnutrymme [GroupDocs.Conversion](../../converter)
* hopsättning [GroupDocs.Conversion](../../../)

---

## Convert(SaveDocumentStream, ConvertedDocumentStream, ConvertOptionsProvider) {#convert}

Konverterar källdokument. Sparar hela det konverterade dokumentet.

```csharp
public void Convert(SaveDocumentStream document, ConvertedDocumentStream documentCompleted, 
    ConvertOptionsProvider convertOptionsProvider)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| document | SaveDocumentStream | Ombudet som sparar konverterat dokument till en ström. |
| documentCompleted | ConvertedDocumentStream | Delegaten som tar emot konverterad dokumentström. |
| convertOptionsProvider | ConvertOptionsProvider | Konvertera alternativleverantör. Kommer att anropas för varje konvertering för att ge specifika konverteringsalternativ till önskad måldokumenttyp. |

### Anmärkningar

**Läs mer**

* Mer om grundläggande scenarier för dokumentkonvertering: [Hur man konverterar dokument i 3 steg](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Användningsfall för konvertering, avancerade inställningar och anpassningar: [Konvertera dokument med avancerade inställningar](https://docs.groupdocs.com/display/conversionnet/Converting)

### Se även

* delegate [SaveDocumentStream](../../../groupdocs.conversion.contracts/savedocumentstream)
* delegate [ConvertedDocumentStream](../../../groupdocs.conversion.contracts/converteddocumentstream)
* delegate [ConvertOptionsProvider](../../../groupdocs.conversion.contracts/convertoptionsprovider)
* class [Converter](../../converter)
* namnutrymme [GroupDocs.Conversion](../../converter)
* hopsättning [GroupDocs.Conversion](../../../)

---

## Convert(SaveDocumentStreamForFileType, ConvertOptions) {#convert_7}

Konverterar källdokument. Sparar hela det konverterade dokumentet.

```csharp
public void Convert(SaveDocumentStreamForFileType document, ConvertOptions convertOptions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| document | SaveDocumentStreamForFileType | Ombudet som sparar konverterat dokument till en ström. |
| convertOptions | ConvertOptions | Konverteringsalternativen specifika för önskad målfiltyp. |

### Anmärkningar

**Läs mer**

* Mer om grundläggande scenarier för dokumentkonvertering: [Hur man konverterar dokument i 3 steg](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Användningsfall för konvertering, avancerade inställningar och anpassningar: [Konvertera dokument med avancerade inställningar](https://docs.groupdocs.com/display/conversionnet/Converting)

### Se även

* delegate [SaveDocumentStreamForFileType](../../../groupdocs.conversion.contracts/savedocumentstreamforfiletype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namnutrymme [GroupDocs.Conversion](../../converter)
* hopsättning [GroupDocs.Conversion](../../../)

---

## Convert(SaveDocumentStreamForFileType, ConvertedDocumentStream, ConvertOptions) {#convert_5}

Konverterar källdokument. Sparar hela det konverterade dokumentet.

```csharp
public void Convert(SaveDocumentStreamForFileType document, 
    ConvertedDocumentStream documentCompleted, ConvertOptions convertOptions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| document | SaveDocumentStreamForFileType | Ombudet som sparar konverterat dokument till en ström. |
| documentCompleted | ConvertedDocumentStream | Delegaten som tar emot konverterad dokumentström. |
| convertOptions | ConvertOptions | Konverteringsalternativen specifika för önskad målfiltyp. |

### Anmärkningar

**Läs mer**

* Mer om grundläggande scenarier för dokumentkonvertering: [Hur man konverterar dokument i 3 steg](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Användningsfall för konvertering, avancerade inställningar och anpassningar: [Konvertera dokument med avancerade inställningar](https://docs.groupdocs.com/display/conversionnet/Converting)

### Se även

* delegate [SaveDocumentStreamForFileType](../../../groupdocs.conversion.contracts/savedocumentstreamforfiletype)
* delegate [ConvertedDocumentStream](../../../groupdocs.conversion.contracts/converteddocumentstream)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namnutrymme [GroupDocs.Conversion](../../converter)
* hopsättning [GroupDocs.Conversion](../../../)

---

## Convert(SaveDocumentStreamForFileType, ConvertOptionsProvider) {#convert_6}

Konverterar källdokument. Sparar hela det konverterade dokumentet.

```csharp
public void Convert(SaveDocumentStreamForFileType document, 
    ConvertOptionsProvider convertOptionsProvider)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| document | SaveDocumentStreamForFileType | Ombudet som sparar konverterat dokument till en ström. |
| convertOptionsProvider | ConvertOptionsProvider | Konvertera alternativleverantör. Kommer att anropas för varje konvertering för att ge specifika konverteringsalternativ till önskad måldokumenttyp. |

### Anmärkningar

**Läs mer**

* Mer om grundläggande scenarier för dokumentkonvertering: [Hur man konverterar dokument i 3 steg](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Användningsfall för konvertering, avancerade inställningar och anpassningar: [Konvertera dokument med avancerade inställningar](https://docs.groupdocs.com/display/conversionnet/Converting)

### Se även

* delegate [SaveDocumentStreamForFileType](../../../groupdocs.conversion.contracts/savedocumentstreamforfiletype)
* delegate [ConvertOptionsProvider](../../../groupdocs.conversion.contracts/convertoptionsprovider)
* class [Converter](../../converter)
* namnutrymme [GroupDocs.Conversion](../../converter)
* hopsättning [GroupDocs.Conversion](../../../)

---

## Convert(SaveDocumentStreamForFileType, ConvertedDocumentStream, ConvertOptionsProvider) {#convert_4}

Konverterar källdokument. Sparar hela det konverterade dokumentet.

```csharp
public void Convert(SaveDocumentStreamForFileType document, 
    ConvertedDocumentStream documentCompleted, ConvertOptionsProvider convertOptionsProvider)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| document | SaveDocumentStreamForFileType | Ombudet som sparar konverterat dokument till en ström. |
| documentCompleted | ConvertedDocumentStream | Delegaten som tar emot konverterad dokumentström. |
| convertOptionsProvider | ConvertOptionsProvider | Konvertera alternativleverantör. Kommer att anropas för varje konvertering för att ge specifika konverteringsalternativ till önskad måldokumenttyp. |

### Anmärkningar

**Läs mer**

* Mer om grundläggande scenarier för dokumentkonvertering: [Hur man konverterar dokument i 3 steg](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Användningsfall för konvertering, avancerade inställningar och anpassningar: [Konvertera dokument med avancerade inställningar](https://docs.groupdocs.com/display/conversionnet/Converting)

### Se även

* delegate [SaveDocumentStreamForFileType](../../../groupdocs.conversion.contracts/savedocumentstreamforfiletype)
* delegate [ConvertedDocumentStream](../../../groupdocs.conversion.contracts/converteddocumentstream)
* delegate [ConvertOptionsProvider](../../../groupdocs.conversion.contracts/convertoptionsprovider)
* class [Converter](../../converter)
* namnutrymme [GroupDocs.Conversion](../../converter)
* hopsättning [GroupDocs.Conversion](../../../)

---

## Convert(string, ConvertOptions) {#convert_16}

Konverterar källdokument. Sparar hela det konverterade dokumentet.

```csharp
public void Convert(string filePath, ConvertOptions convertOptions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | String | Filsökvägen till källdokumentet. |
| convertOptions | ConvertOptions | Konverteringsalternativen specifika för önskad målfiltyp. |

### Anmärkningar

**Läs mer**

* Mer om grundläggande scenarier för dokumentkonvertering: [Hur man konverterar dokument i 3 steg](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Användningsfall för konvertering, avancerade inställningar och anpassningar: [Konvertera dokument med avancerade inställningar](https://docs.groupdocs.com/display/conversionnet/Converting)

### Se även

* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namnutrymme [GroupDocs.Conversion](../../converter)
* hopsättning [GroupDocs.Conversion](../../../)

---

## Convert(SavePageStream, ConvertOptions) {#convert_11}

Konverterar källdokument. Sparar det konverterade dokumentet sida för sida.

```csharp
public void Convert(SavePageStream document, ConvertOptions convertOptions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| document | SavePageStream | Ombudet som sparar konverterat dokument till en ström. |
| convertOptions | ConvertOptions | Konverteringsalternativen specifika för önskad målfiltyp. |

### Anmärkningar

**Läs mer**

* Mer om grundläggande scenarier för dokumentkonvertering: [Hur man konverterar dokument i 3 steg](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Användningsfall för konvertering, avancerade inställningar och anpassningar: [Konvertera dokument med avancerade inställningar](https://docs.groupdocs.com/display/conversionnet/Converting)

### Se även

* delegate [SavePageStream](../../../groupdocs.conversion.contracts/savepagestream)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namnutrymme [GroupDocs.Conversion](../../converter)
* hopsättning [GroupDocs.Conversion](../../../)

---

## Convert(SavePageStream, ConvertedPageStream, ConvertOptions) {#convert_9}

Konverterar källdokument. Sparar det konverterade dokumentet sida för sida.

```csharp
public void Convert(SavePageStream document, ConvertedPageStream documentCompleted, 
    ConvertOptions convertOptions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| document | SavePageStream | Ombudet som sparar den konverterade dokumentsidan till en ström. |
| documentCompleted | ConvertedPageStream | Delegaten som tar emot konverterad dokumentsidaström. |
| convertOptions | ConvertOptions | Konverteringsalternativen specifika för önskad målfiltyp. |

### Anmärkningar

**Läs mer**

* Mer om grundläggande scenarier för dokumentkonvertering: [Hur man konverterar dokument i 3 steg](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Användningsfall för konvertering, avancerade inställningar och anpassningar: [Konvertera dokument med avancerade inställningar](https://docs.groupdocs.com/display/conversionnet/Converting)

### Se även

* delegate [SavePageStream](../../../groupdocs.conversion.contracts/savepagestream)
* delegate [ConvertedPageStream](../../../groupdocs.conversion.contracts/convertedpagestream)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namnutrymme [GroupDocs.Conversion](../../converter)
* hopsättning [GroupDocs.Conversion](../../../)

---

## Convert(SavePageStream, ConvertOptionsProvider) {#convert_10}

Konverterar källdokument. Sparar det konverterade dokumentet sida för sida.

```csharp
public void Convert(SavePageStream document, ConvertOptionsProvider convertOptionsProvider)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| document | SavePageStream | Ombudet som sparar konverterat dokument till en ström. |
| convertOptionsProvider | ConvertOptionsProvider | Konvertera alternativleverantör. Kommer att anropas för varje konvertering för att ge specifika konverteringsalternativ till önskad måldokumenttyp. |

### Anmärkningar

**Läs mer**

* Mer om grundläggande scenarier för dokumentkonvertering: [Hur man konverterar dokument i 3 steg](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Användningsfall för konvertering, avancerade inställningar och anpassningar: [Konvertera dokument med avancerade inställningar](https://docs.groupdocs.com/display/conversionnet/Converting)

### Se även

* delegate [SavePageStream](../../../groupdocs.conversion.contracts/savepagestream)
* delegate [ConvertOptionsProvider](../../../groupdocs.conversion.contracts/convertoptionsprovider)
* class [Converter](../../converter)
* namnutrymme [GroupDocs.Conversion](../../converter)
* hopsättning [GroupDocs.Conversion](../../../)

---

## Convert(SavePageStream, ConvertedPageStream, ConvertOptionsProvider) {#convert_8}

Konverterar källdokument. Sparar det konverterade dokumentet sida för sida.

```csharp
public void Convert(SavePageStream document, ConvertedPageStream documentCompleted, 
    ConvertOptionsProvider convertOptionsProvider)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| document | SavePageStream | Ombudet som sparar den konverterade dokumentsidan till en ström. |
| documentCompleted | ConvertedPageStream | Delegaten som tar emot konverterad dokumentsidaström. |
| convertOptionsProvider | ConvertOptionsProvider | Konvertera alternativleverantör. Kommer att anropas för varje konvertering för att ge specifika konverteringsalternativ till önskad måldokumenttyp. |

### Anmärkningar

**Läs mer**

* Mer om grundläggande scenarier för dokumentkonvertering: [Hur man konverterar dokument i 3 steg](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Användningsfall för konvertering, avancerade inställningar och anpassningar: [Konvertera dokument med avancerade inställningar](https://docs.groupdocs.com/display/conversionnet/Converting)

### Se även

* delegate [SavePageStream](../../../groupdocs.conversion.contracts/savepagestream)
* delegate [ConvertedPageStream](../../../groupdocs.conversion.contracts/convertedpagestream)
* delegate [ConvertOptionsProvider](../../../groupdocs.conversion.contracts/convertoptionsprovider)
* class [Converter](../../converter)
* namnutrymme [GroupDocs.Conversion](../../converter)
* hopsättning [GroupDocs.Conversion](../../../)

---

## Convert(SavePageStreamForFileType, ConvertOptions) {#convert_15}

Konverterar källdokument. Sparar det konverterade dokumentet sida för sida.

```csharp
public void Convert(SavePageStreamForFileType document, ConvertOptions convertOptions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| document | SavePageStreamForFileType | Ombudet som sparar konverterat dokument till en ström. |
| convertOptions | ConvertOptions | Konverteringsalternativen specifika för önskad målfiltyp. |

### Anmärkningar

**Läs mer**

* Mer om grundläggande scenarier för dokumentkonvertering: [Hur man konverterar dokument i 3 steg](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Användningsfall för konvertering, avancerade inställningar och anpassningar: [Konvertera dokument med avancerade inställningar](https://docs.groupdocs.com/display/conversionnet/Converting)

### Se även

* delegate [SavePageStreamForFileType](../../../groupdocs.conversion.contracts/savepagestreamforfiletype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namnutrymme [GroupDocs.Conversion](../../converter)
* hopsättning [GroupDocs.Conversion](../../../)

---

## Convert(SavePageStreamForFileType, ConvertedPageStream, ConvertOptions) {#convert_13}

Konverterar källdokument. Sparar det konverterade dokumentet sida för sida.

```csharp
public void Convert(SavePageStreamForFileType document, ConvertedPageStream documentCompleted, 
    ConvertOptions convertOptions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| document | SavePageStreamForFileType | Ombudet som sparar den konverterade dokumentsidan till en ström. |
| documentCompleted | ConvertedPageStream | Delegaten som tar emot konverterad dokumentsidaström. |
| convertOptions | ConvertOptions | Konverteringsalternativen specifika för önskad målfiltyp. |

### Anmärkningar

**Läs mer**

* Mer om grundläggande scenarier för dokumentkonvertering: [Hur man konverterar dokument i 3 steg](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Användningsfall för konvertering, avancerade inställningar och anpassningar: [Konvertera dokument med avancerade inställningar](https://docs.groupdocs.com/display/conversionnet/Converting)

### Se även

* delegate [SavePageStreamForFileType](../../../groupdocs.conversion.contracts/savepagestreamforfiletype)
* delegate [ConvertedPageStream](../../../groupdocs.conversion.contracts/convertedpagestream)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namnutrymme [GroupDocs.Conversion](../../converter)
* hopsättning [GroupDocs.Conversion](../../../)

---

## Convert(SavePageStreamForFileType, ConvertOptionsProvider) {#convert_14}

Konverterar källdokument. Sparar det konverterade dokumentet sida för sida.

```csharp
public void Convert(SavePageStreamForFileType document, 
    ConvertOptionsProvider convertOptionsProvider)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| document | SavePageStreamForFileType | Ombudet som sparar konverterat dokument till en ström. |
| convertOptionsProvider | ConvertOptionsProvider | Konvertera alternativleverantör. Kommer att anropas för varje konvertering för att ge specifika konverteringsalternativ till önskad måldokumenttyp. |

### Anmärkningar

**Läs mer**

* Mer om grundläggande scenarier för dokumentkonvertering: [Hur man konverterar dokument i 3 steg](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Användningsfall för konvertering, avancerade inställningar och anpassningar: [Konvertera dokument med avancerade inställningar](https://docs.groupdocs.com/display/conversionnet/Converting)

### Se även

* delegate [SavePageStreamForFileType](../../../groupdocs.conversion.contracts/savepagestreamforfiletype)
* delegate [ConvertOptionsProvider](../../../groupdocs.conversion.contracts/convertoptionsprovider)
* class [Converter](../../converter)
* namnutrymme [GroupDocs.Conversion](../../converter)
* hopsättning [GroupDocs.Conversion](../../../)

---

## Convert(SavePageStreamForFileType, ConvertedPageStream, ConvertOptionsProvider) {#convert_12}

Konverterar källdokument. Sparar det konverterade dokumentet sida för sida.

```csharp
public void Convert(SavePageStreamForFileType document, ConvertedPageStream documentCompleted, 
    ConvertOptionsProvider convertOptionsProvider)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| document | SavePageStreamForFileType | Ombudet som sparar den konverterade dokumentsidan till en ström. |
| documentCompleted | ConvertedPageStream | Delegaten som tar emot konverterad dokumentsidaström. |
| convertOptionsProvider | ConvertOptionsProvider | Konvertera alternativleverantör. Kommer att anropas för varje konvertering för att ge specifika konverteringsalternativ till önskad måldokumenttyp. |

### Anmärkningar

**Läs mer**

* Mer om grundläggande scenarier för dokumentkonvertering: [Hur man konverterar dokument i 3 steg](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Användningsfall för konvertering, avancerade inställningar och anpassningar: [Konvertera dokument med avancerade inställningar](https://docs.groupdocs.com/display/conversionnet/Converting)

### Se även

* delegate [SavePageStreamForFileType](../../../groupdocs.conversion.contracts/savepagestreamforfiletype)
* delegate [ConvertedPageStream](../../../groupdocs.conversion.contracts/convertedpagestream)
* delegate [ConvertOptionsProvider](../../../groupdocs.conversion.contracts/convertoptionsprovider)
* class [Converter](../../converter)
* namnutrymme [GroupDocs.Conversion](../../converter)
* hopsättning [GroupDocs.Conversion](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
