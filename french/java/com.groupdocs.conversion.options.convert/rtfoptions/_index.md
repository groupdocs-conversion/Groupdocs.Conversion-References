---
title: "RtfOptions"
second_title: "Référence API GroupDocs.Conversion pour Java"
description: "Options de conversion vers le type de fichier RTF."
type: docs
weight: 39
url: /fr/java/com.groupdocs.conversion.options.convert/rtfoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class RtfOptions extends ValueObject implements Serializable
```

Options de conversion vers le type de fichier RTF.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [RtfOptions()](#RtfOptions--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getExportImagesForOldReaders()](#getExportImagesForOldReaders--) | Spécifie si les mots‑clés pour "old readers" sont écrits dans le RTF ou non. |
|
|  | [setExportImagesForOldReaders(boolean value)](#setExportImagesForOldReaders-boolean-) | Spécifie si les mots‑clés pour "old readers" sont écrits dans le RTF ou non. |
|
### RtfOptions() {#RtfOptions--}
```
public RtfOptions()
```


### getExportImagesForOldReaders() {#getExportImagesForOldReaders--}
```
public final boolean getExportImagesForOldReaders()
```


Spécifie si les mots‑clés pour "old readers" sont écrits dans le RTF ou non.
Cela peut affecter de manière significative la taille du document RTF. La valeur par défaut est False.


**Returns:**
booléen
### setExportImagesForOldReaders(boolean value) {#setExportImagesForOldReaders-boolean-}
```
public final void setExportImagesForOldReaders(boolean value)
```


Spécifie si les mots‑clés pour "old readers" sont écrits dans le RTF ou non.
Cela peut affecter de manière significative la taille du document RTF. La valeur par défaut est False.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

