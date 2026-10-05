---
title: "TargetConversion"
second_title: "GroupDocs.Conversion för Node.js via Java API-referens"
description: "Representerar möjlig målkonvertering och en flagga som anger om den är primär eller sekundär"
type: docs
weight: 14
url: /sv/nodejs-java/com.groupdocs.conversion.contracts/targetconversion/
---
**Inheritance:**
java.lang.Object
```
public final class TargetConversion
```

Representerar möjlig målkonvertering och en flagga som anger om den är primär eller sekundär
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getFormat()](#getFormat--) | Måldokumentformat |
| [isPrimary()](#isPrimary--) | Är konverteringen primär |
| [getConvertOptions()](#getConvertOptions--) | Fördefinierade konverteringsalternativ som kan användas för att konvertera till aktuell typ |
### getFormat() {#getFormat--}
```
public FileType getFormat()
```


Måldokumentformat

**Returns:**
[FileType](../../com.groupdocs.conversion.filetypes/filetype) - Target document format
### isPrimary() {#isPrimary--}
```
public boolean isPrimary()
```


Är konverteringen primär

**Returns:**
boolesk - `true` om primär
### getConvertOptions() {#getConvertOptions--}
```
public ConvertOptions getConvertOptions()
```


Fördefinierade konverteringsalternativ som kan användas för att konvertera till aktuell typ

**Returns:**
[ConvertOptions](../../com.groupdocs.conversion.options.convert/convertoptions) - convert options
