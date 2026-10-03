---
title: "PossibleConversions"
second_title: "GroupDocs.Conversion för Java API-referens"
description: "Representerar en mappning av vilka konverteringspar som stöds för ett specifikt källfilformat"
type: docs
weight: 13
url: /sv/java/com.groupdocs.conversion.contracts/possibleconversions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)
```
public final class PossibleConversions extends ValueObject
```

Representerar en mappning av vilka konverteringspar som stöds för ett specifikt källfilformat

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
|  | [PossibleConversions(FileType source)](#PossibleConversions-com.groupdocs.conversion.filetypes.FileType-) | Skapar en möjlig konverteringslista för angivet källfilformat |
|
## Fält

| Fält | Beskrivning |
| --- | --- |
| [NULL](#NULL) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getLoadOptions()](#getLoadOptions--) | Fördefinierade inläsningsalternativ som kan användas för att konvertera från aktuell typ |
|
|  | [getAll()](#getAll--) | Alla målfiltyper och primär/sekundär flagga |
|
|  | [getTargetConversion(FileType target)](#getTargetConversion-com.groupdocs.conversion.filetypes.FileType-) | Returnerar målkonvertering för angiven målfiltyp |
|
| [getTargetConversion(String extension)](#getTargetConversion-java.lang.String-) |  |
|  | [getPrimary()](#getPrimary--) | Primära målfiltyper |
|
|  | [getSecondary()](#getSecondary--) | Sekundära målfiltyper |
|
|  | [add(ConversionPair pair)](#add-com.groupdocs.conversion.contracts.ConversionPair-) | Lägg till konverteringspar |
|
|  | [forTarget(FileType target)](#forTarget-com.groupdocs.conversion.filetypes.FileType-) | Hitta konverteringspar i aktuell lista för målfiltyp |
|
|  | [getSource()](#getSource--) | Källfilformat |
|
### PossibleConversions(FileType source) {#PossibleConversions-com.groupdocs.conversion.filetypes.FileType-}
```
public PossibleConversions(FileType source)
```


Skapar en möjlig konverteringslista för angivet källfilformat


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | source | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | källfiltyp |
|

### NULL {#NULL}
```
public static final PossibleConversions NULL
```


### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


Fördefinierade inläsningsalternativ som kan användas för att konvertera från aktuell typ


**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions) - load options

### getAll() {#getAll--}
```
public Iterable<TargetConversion> getAll()
```


Alla målfiltyper och primär/sekundär flagga


**Returns:**
java.lang.Iterable<com.groupdocs.conversion.contracts.TargetConversion> - Iterable av [TargetConversion](../../com.groupdocs.conversion.contracts/targetconversion)

### getTargetConversion(FileType target) {#getTargetConversion-com.groupdocs.conversion.filetypes.FileType-}
```
public TargetConversion getTargetConversion(FileType target)
```


Returnerar målkonvertering för angiven målfiltyp


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | target | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | målfiltyp |
|

**Returns:**
[TargetConversion](../../com.groupdocs.conversion.contracts/targetconversion) - conversions

### getTargetConversion(String extension) {#getTargetConversion-java.lang.String-}
```
public TargetConversion getTargetConversion(String extension)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filändelse | java.lang.String |  |

**Returns:**
[TargetConversion](../../com.groupdocs.conversion.contracts/targetconversion)
### getPrimary() {#getPrimary--}
```
public Iterable<FileType> getPrimary()
```


Primära målfiltyper


**Returns:**
java.lang.Iterable<com.groupdocs.conversion.filetypes.FileType> - primära målfiltyper

### getSecondary() {#getSecondary--}
```
public Iterable<FileType> getSecondary()
```


Sekundära målfiltyper


**Returns:**
java.lang.Iterable<com.groupdocs.conversion.filetypes.FileType> - sekundära målfiltyper

### add(ConversionPair pair) {#add-com.groupdocs.conversion.contracts.ConversionPair-}
```
public void add(ConversionPair pair)
```


Lägg till konverteringspar


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | pair | [ConversionPair](../../com.groupdocs.conversion.contracts/conversionpair) | konverteringspar |
|

### forTarget(FileType target) {#forTarget-com.groupdocs.conversion.filetypes.FileType-}
```
public ConversionPair forTarget(FileType target)
```


Hitta konverteringspar i aktuell lista för målfiltyp


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | target | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | målfiltyp |
|

**Returns:**
[ConversionPair](../../com.groupdocs.conversion.contracts/conversionpair) - conversion pair

### getSource() {#getSource--}
```
public FileType getSource()
```


Källfilformat


**Returns:**
[FileType](../../com.groupdocs.conversion.filetypes/filetype) - file formats

