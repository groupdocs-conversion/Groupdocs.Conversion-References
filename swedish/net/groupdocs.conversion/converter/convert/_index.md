---
title: Convert
second_title: GroupDocs.Conversion for .NET API Referens
description: Konverterar källdokument. Sparar hela det konverterade dokumentet.
type: docs
weight: 20
url: /sv/net/groupdocs.conversion/converter/convert/
---
## Convert(Func&lt;Stream&gt;, ConvertOptions) {#convert}

Konverterar källdokument. Sparar hela det konverterade dokumentet.

```csharp
public void Convert(Func<Stream> document, ConvertOptions convertOptions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| document | Func`1 | Ombudet som sparar konverterat dokument till en ström. |
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

## Convert(Func&lt;Stream&gt;, Action&lt;Stream, string&gt;, ConvertOptions) {#convert_1}

Konverterar källdokument. Sparar hela det konverterade dokumentet.

```csharp
public void Convert(Func<Stream> document, Action<Stream, string> documentCompleted, 
    ConvertOptions convertOptions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| document | Func`1 | Ombudet som sparar konverterat dokument till en ström. |
| documentCompleted | Action`2 | Delegaten som tar emot konverterad dokumentström. FilinnehållsströmmenNamnet på filen |
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

## Convert(Func&lt;Stream&gt;, Func&lt;string, FileType, ConvertOptions&gt;) {#convert_3}

Konverterar källdokument. Sparar hela det konverterade dokumentet.

```csharp
public void Convert(Func<Stream> document, 
    Func<string, FileType, ConvertOptions> convertOptionsProvider)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| document | Func`1 | Ombudet som sparar konverterat dokument till en ström. |
| convertOptionsProvider | Func`3 | Konvertera alternativleverantör. Kommer att anropas för varje konvertering för att tillhandahålla specifika konverteringsalternativ till önskad måldokumenttyp. Namnet på filenTypen av fil |

### Anmärkningar

**Läs mer**

* Mer om grundläggande scenarier för dokumentkonvertering: [Hur man konverterar dokument i 3 steg](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Användningsfall för konvertering, avancerade inställningar och anpassningar: [Konvertera dokument med avancerade inställningar](https://docs.groupdocs.com/display/conversionnet/Converting)

### Se även

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namnutrymme [GroupDocs.Conversion](../../converter)
* hopsättning [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;Stream&gt;, Action&lt;Stream, string&gt;, Func&lt;string, FileType, ConvertOptions&gt;) {#convert_2}

Konverterar källdokument. Sparar hela det konverterade dokumentet.

```csharp
public void Convert(Func<Stream> document, Action<Stream, string> documentCompleted, 
    Func<string, FileType, ConvertOptions> convertOptionsProvider)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| document | Func`1 | Ombudet som sparar konverterat dokument till en ström. |
| documentCompleted | Action`2 | Delegaten som tar emot konverterad dokumentström. FilinnehållsströmmenNamnet på filen |
| convertOptionsProvider | Func`3 | Konvertera alternativleverantör. Kommer att anropas för varje konvertering för att tillhandahålla specifika konverteringsalternativ till önskad måldokumenttyp. Namnet på filenTypen av fil |

### Anmärkningar

**Läs mer**

* Mer om grundläggande scenarier för dokumentkonvertering: [Hur man konverterar dokument i 3 steg](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Användningsfall för konvertering, avancerade inställningar och anpassningar: [Konvertera dokument med avancerade inställningar](https://docs.groupdocs.com/display/conversionnet/Converting)

### Se även

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namnutrymme [GroupDocs.Conversion](../../converter)
* hopsättning [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;FileType, Stream&gt;, ConvertOptions) {#convert_4}

Konverterar källdokument. Sparar hela det konverterade dokumentet.

```csharp
public void Convert(Func<FileType, Stream> document, ConvertOptions convertOptions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| document | Func`2 | Ombudet som sparar konverterat dokument till en ström. Typen av källfil |
| convertOptions | ConvertOptions | Konverteringsalternativen specifika för önskad målfiltyp. |

### Anmärkningar

**Läs mer**

* Mer om grundläggande scenarier för dokumentkonvertering: [Hur man konverterar dokument i 3 steg](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Användningsfall för konvertering, avancerade inställningar och anpassningar: [Konvertera dokument med avancerade inställningar](https://docs.groupdocs.com/display/conversionnet/Converting)

### Se även

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namnutrymme [GroupDocs.Conversion](../../converter)
* hopsättning [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;FileType, Stream&gt;, Action&lt;Stream, string&gt;, ConvertOptions) {#convert_5}

Konverterar källdokument. Sparar hela det konverterade dokumentet.

```csharp
public void Convert(Func<FileType, Stream> document, Action<Stream, string> documentCompleted, 
    ConvertOptions convertOptions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| document | Func`2 | Ombudet som sparar konverterat dokument till en ström. Typen av källfil |
| documentCompleted | Action`2 | Delegaten som tar emot konverterad dokumentström. FilinnehållsströmmenNamnet på filen |
| convertOptions | ConvertOptions | Konverteringsalternativen specifika för önskad målfiltyp. |

### Anmärkningar

**Läs mer**

* Mer om grundläggande scenarier för dokumentkonvertering: [Hur man konverterar dokument i 3 steg](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Användningsfall för konvertering, avancerade inställningar och anpassningar: [Konvertera dokument med avancerade inställningar](https://docs.groupdocs.com/display/conversionnet/Converting)

### Se även

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namnutrymme [GroupDocs.Conversion](../../converter)
* hopsättning [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;FileType, Stream&gt;, Func&lt;string, FileType, ConvertOptions&gt;) {#convert_7}

Konverterar källdokument. Sparar hela det konverterade dokumentet.

```csharp
public void Convert(Func<FileType, Stream> document, 
    Func<string, FileType, ConvertOptions> convertOptionsProvider)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| document | Func`2 | Ombudet som sparar konverterat dokument till en ström. Typen av källfil |
| convertOptionsProvider | Func`3 | Konvertera alternativleverantör. Kommer att anropas för varje konvertering för att tillhandahålla specifika konverteringsalternativ till önskad måldokumenttyp. Namnet på filenTypen av fil |

### Anmärkningar

**Läs mer**

* Mer om grundläggande scenarier för dokumentkonvertering: [Hur man konverterar dokument i 3 steg](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Användningsfall för konvertering, avancerade inställningar och anpassningar: [Konvertera dokument med avancerade inställningar](https://docs.groupdocs.com/display/conversionnet/Converting)

### Se även

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namnutrymme [GroupDocs.Conversion](../../converter)
* hopsättning [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;FileType, Stream&gt;, Action&lt;Stream, string&gt;, Func&lt;string, FileType, ConvertOptions&gt;) {#convert_6}

Konverterar källdokument. Sparar hela det konverterade dokumentet.

```csharp
public void Convert(Func<FileType, Stream> document, Action<Stream, string> documentCompleted, 
    Func<string, FileType, ConvertOptions> convertOptionsProvider)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| document | Func`2 | Ombudet som sparar konverterat dokument till en ström. Typen av källfil |
| documentCompleted | Action`2 | Delegaten som tar emot konverterad dokumentström. FilinnehållsströmmenNamnet på filen |
| convertOptionsProvider | Func`3 | Konvertera alternativleverantör. Kommer att anropas för varje konvertering för att tillhandahålla specifika konverteringsalternativ till önskad måldokumenttyp. Namnet på filenTypen av fil |

### Anmärkningar

**Läs mer**

* Mer om grundläggande scenarier för dokumentkonvertering: [Hur man konverterar dokument i 3 steg](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Användningsfall för konvertering, avancerade inställningar och anpassningar: [Konvertera dokument med avancerade inställningar](https://docs.groupdocs.com/display/conversionnet/Converting)

### Se även

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
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

## Convert(Func&lt;int, Stream&gt;, ConvertOptions) {#convert_8}

Konverterar källdokument. Sparar det konverterade dokumentet sida för sida.

```csharp
public void Convert(Func<int, Stream> document, ConvertOptions convertOptions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| document | Func`2 | Ombudet som sparar konverterat dokument till en ström. Sidonummer |
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

## Convert(Func&lt;int, Stream&gt;, Action&lt;int, Stream, string&gt;, ConvertOptions) {#convert_9}

Konverterar källdokument. Sparar det konverterade dokumentet sida för sida.

```csharp
public void Convert(Func<int, Stream> document, Action<int, Stream, string> documentCompleted, 
    ConvertOptions convertOptions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| document | Func`2 | Ombudet som sparar den konverterade dokumentsidan till en ström. Sidonummer |
| documentCompleted | Action`3 | Delegaten som tar emot konverterad dokumentsidaström. SidonummerFilinnehållsströmmenNamnet på filen |
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

## Convert(Func&lt;int, Stream&gt;, Func&lt;string, FileType, ConvertOptions&gt;) {#convert_11}

Konverterar källdokument. Sparar det konverterade dokumentet sida för sida.

```csharp
public void Convert(Func<int, Stream> document, 
    Func<string, FileType, ConvertOptions> convertOptionsProvider)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| document | Func`2 | Ombudet som sparar konverterat dokument till en ström. Sidonummer |
| convertOptionsProvider | Func`3 | Konvertera alternativleverantör. Kommer att anropas för varje konvertering för att tillhandahålla specifika konverteringsalternativ till önskad måldokumenttyp. Namnet på filenTypen av fil |

### Anmärkningar

**Läs mer**

* Mer om grundläggande scenarier för dokumentkonvertering: [Hur man konverterar dokument i 3 steg](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Användningsfall för konvertering, avancerade inställningar och anpassningar: [Konvertera dokument med avancerade inställningar](https://docs.groupdocs.com/display/conversionnet/Converting)

### Se även

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namnutrymme [GroupDocs.Conversion](../../converter)
* hopsättning [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;int, Stream&gt;, Action&lt;int, Stream, string&gt;, Func&lt;string, FileType, ConvertOptions&gt;) {#convert_10}

Konverterar källdokument. Sparar det konverterade dokumentet sida för sida.

```csharp
public void Convert(Func<int, Stream> document, Action<int, Stream, string> documentCompleted, 
    Func<string, FileType, ConvertOptions> convertOptionsProvider)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| document | Func`2 | Ombudet som sparar den konverterade dokumentsidan till en ström. Sidonummer |
| documentCompleted | Action`3 | Delegaten som tar emot konverterad dokumentsidaström. SidonummerFilinnehållsströmmenNamnet på filen |
| convertOptionsProvider | Func`3 | Konvertera alternativleverantör. Kommer att anropas för varje konvertering för att tillhandahålla specifika konverteringsalternativ till önskad måldokumenttyp. Namnet på filenTypen av fil |

### Anmärkningar

**Läs mer**

* Mer om grundläggande scenarier för dokumentkonvertering: [Hur man konverterar dokument i 3 steg](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Användningsfall för konvertering, avancerade inställningar och anpassningar: [Konvertera dokument med avancerade inställningar](https://docs.groupdocs.com/display/conversionnet/Converting)

### Se även

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namnutrymme [GroupDocs.Conversion](../../converter)
* hopsättning [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;int, FileType, Stream&gt;, ConvertOptions) {#convert_12}

Konverterar källdokument. Sparar det konverterade dokumentet sida för sida.

```csharp
public void Convert(Func<int, FileType, Stream> document, ConvertOptions convertOptions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| document | Func`3 | Ombudet som sparar konverterat dokument till en ström. Sidonummer |
| convertOptions | ConvertOptions | Konverteringsalternativen specifika för önskad målfiltyp. |

### Anmärkningar

**Läs mer**

* Mer om grundläggande scenarier för dokumentkonvertering: [Hur man konverterar dokument i 3 steg](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Användningsfall för konvertering, avancerade inställningar och anpassningar: [Konvertera dokument med avancerade inställningar](https://docs.groupdocs.com/display/conversionnet/Converting)

### Se även

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namnutrymme [GroupDocs.Conversion](../../converter)
* hopsättning [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;int, FileType, Stream&gt;, Action&lt;int, Stream, string&gt;, ConvertOptions) {#convert_13}

Konverterar källdokument. Sparar det konverterade dokumentet sida för sida.

```csharp
public void Convert(Func<int, FileType, Stream> document, 
    Action<int, Stream, string> documentCompleted, ConvertOptions convertOptions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| document | Func`3 | Ombudet som sparar den konverterade dokumentsidan till en ström. SidonummerFiltyp |
| documentCompleted | Action`3 | Delegaten som tar emot konverterad dokumentsidaström. SidonummerFilinnehållsströmmenNamnet på filen |
| convertOptions | ConvertOptions | Konverteringsalternativen specifika för önskad målfiltyp. |

### Anmärkningar

**Läs mer**

* Mer om grundläggande scenarier för dokumentkonvertering: [Hur man konverterar dokument i 3 steg](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Användningsfall för konvertering, avancerade inställningar och anpassningar: [Konvertera dokument med avancerade inställningar](https://docs.groupdocs.com/display/conversionnet/Converting)

### Se även

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namnutrymme [GroupDocs.Conversion](../../converter)
* hopsättning [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;int, FileType, Stream&gt;, Func&lt;string, FileType, ConvertOptions&gt;) {#convert_15}

Konverterar källdokument. Sparar det konverterade dokumentet sida för sida.

```csharp
public void Convert(Func<int, FileType, Stream> document, 
    Func<string, FileType, ConvertOptions> convertOptionsProvider)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| document | Func`3 | Ombudet som sparar konverterat dokument till en ström. SidonummerFiltyp |
| convertOptionsProvider | Func`3 | Konvertera alternativleverantör. Kommer att anropas för varje konvertering för att tillhandahålla specifika konverteringsalternativ till önskad måldokumenttyp. Namnet på filenTypen av fil |

### Anmärkningar

**Läs mer**

* Mer om grundläggande scenarier för dokumentkonvertering: [Hur man konverterar dokument i 3 steg](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Användningsfall för konvertering, avancerade inställningar och anpassningar: [Konvertera dokument med avancerade inställningar](https://docs.groupdocs.com/display/conversionnet/Converting)

### Se även

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namnutrymme [GroupDocs.Conversion](../../converter)
* hopsättning [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;int, FileType, Stream&gt;, Action&lt;int, Stream, string&gt;, Func&lt;string, FileType, ConvertOptions&gt;) {#convert_14}

Konverterar källdokument. Sparar det konverterade dokumentet sida för sida.

```csharp
public void Convert(Func<int, FileType, Stream> document, 
    Action<int, Stream, string> documentCompleted, 
    Func<string, FileType, ConvertOptions> convertOptionsProvider)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| document | Func`3 | Ombudet som sparar den konverterade dokumentsidan till en ström. SidonummerFiltyp |
| documentCompleted | Action`3 | Delegaten som tar emot konverterad dokumentsidaström. SidonummerFilinnehållsströmmenNamnet på filen |
| convertOptionsProvider | Func`3 | Konvertera alternativleverantör. Kommer att anropas för varje konvertering för att tillhandahålla specifika konverteringsalternativ till önskad måldokumenttyp. Namnet på filenTypen av fil |

### Anmärkningar

**Läs mer**

* Mer om grundläggande scenarier för dokumentkonvertering: [Hur man konverterar dokument i 3 steg](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Användningsfall för konvertering, avancerade inställningar och anpassningar: [Konvertera dokument med avancerade inställningar](https://docs.groupdocs.com/display/conversionnet/Converting)

### Se även

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namnutrymme [GroupDocs.Conversion](../../converter)
* hopsättning [GroupDocs.Conversion](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
