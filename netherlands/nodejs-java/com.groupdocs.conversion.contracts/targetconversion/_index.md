---
title: "TargetConversion"
second_title: "GroupDocs.Conversion for Node.js via Java API-referentie"
description: "Stelt mogelijke doelconversie voor en een vlag of deze primair of secundair is"
type: docs
weight: 14
url: /nl/nodejs-java/com.groupdocs.conversion.contracts/targetconversion/
---
**Inheritance:**
java.lang.Object
```
public final class TargetConversion
```

Stelt mogelijke doelconversie voor en een vlag of deze primair of secundair is
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getFormat()](#getFormat--) | Doelformaat van document |
| [isPrimary()](#isPrimary--) | Is de conversie primair |
| [getConvertOptions()](#getConvertOptions--) | Vooraf gedefinieerde conversie-opties die kunnen worden gebruikt om naar het huidige type te converteren |
### getFormat() {#getFormat--}
```
public FileType getFormat()
```


Doelformaat van document

**Returns:**
[FileType](../../com.groupdocs.conversion.filetypes/filetype) - Target document format
### isPrimary() {#isPrimary--}
```
public boolean isPrimary()
```


Is de conversie primair

**Returns:**
boolean - `true` als primair
### getConvertOptions() {#getConvertOptions--}
```
public ConvertOptions getConvertOptions()
```


Vooraf gedefinieerde conversie-opties die kunnen worden gebruikt om naar het huidige type te converteren

**Returns:**
[ConvertOptions](../../com.groupdocs.conversion.options.convert/convertoptions) - convert options
