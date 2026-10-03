---
title: "TargetConversion"
second_title: "Référence API GroupDocs.Conversion pour Java"
description: "Représente la conversion cible possible et un indicateur indiquant si elle est principale ou secondaire"
type: docs
weight: 14
url: /fr/java/com.groupdocs.conversion.contracts/targetconversion/
---
**Inheritance:**
java.lang.Object
```
public final class TargetConversion
```

Représente la conversion cible possible et un indicateur indiquant si elle est principale ou secondaire

## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getFormat()](#getFormat--) | format de document cible |
|
|  | [isPrimary()](#isPrimary--) | La conversion est-elle principale |
|
|  | [getConvertOptions()](#getConvertOptions--) | Options de conversion prédéfinies pouvant être utilisées pour convertir vers le type actuel |
|
### getFormat() {#getFormat--}
```
public FileType getFormat()
```


format de document cible


**Returns:**
[FileType](../../com.groupdocs.conversion.filetypes/filetype) - Target document format

### isPrimary() {#isPrimary--}
```
public boolean isPrimary()
```


La conversion est-elle principale


**Returns:**
booléen - `true` si principal

### getConvertOptions() {#getConvertOptions--}
```
public ConvertOptions getConvertOptions()
```


Options de conversion prédéfinies pouvant être utilisées pour convertir vers le type actuel


**Returns:**
[ConvertOptions](../../com.groupdocs.conversion.options.convert/convertoptions) - convert options

