---
title: "TargetConversion"
second_title: "GroupDocs.Conversion für Java API-Referenz"
description: "Stellt mögliche Zielkonvertierung dar und ein Flag, ob es primär oder sekundär ist."
type: docs
weight: 14
url: /de/java/com.groupdocs.conversion.contracts/targetconversion/
---
**Inheritance:**
java.lang.Object
```
public final class TargetConversion
```

Stellt mögliche Zielkonvertierung dar und ein Flag, ob es primär oder sekundär ist.

## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getFormat()](#getFormat--) | Zieldokumentformat |
|
|  | [isPrimary()](#isPrimary--) | Ist die Konvertierung primär |
|
|  | [getConvertOptions()](#getConvertOptions--) | Vordefinierte Konvertierungsoptionen, die verwendet werden können, um zum aktuellen Typ zu konvertieren |
|
### getFormat() {#getFormat--}
```
public FileType getFormat()
```


Zieldokumentformat


**Returns:**
[FileType](../../com.groupdocs.conversion.filetypes/filetype) - Target document format

### isPrimary() {#isPrimary--}
```
public boolean isPrimary()
```


Ist die Konvertierung primär


**Returns:**
boolean - `true` wenn primär

### getConvertOptions() {#getConvertOptions--}
```
public ConvertOptions getConvertOptions()
```


Vordefinierte Konvertierungsoptionen, die verwendet werden können, um zum aktuellen Typ zu konvertieren


**Returns:**
[ConvertOptions](../../com.groupdocs.conversion.options.convert/convertoptions) - convert options

