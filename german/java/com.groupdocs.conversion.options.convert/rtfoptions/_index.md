---
title: "RtfOptions"
second_title: "GroupDocs.Conversion für Java API-Referenz"
description: "Optionen für die Konvertierung zum RTF-Dateityp."
type: docs
weight: 39
url: /de/java/com.groupdocs.conversion.options.convert/rtfoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class RtfOptions extends ValueObject implements Serializable
```

Optionen für die Konvertierung zum RTF-Dateityp.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [RtfOptions()](#RtfOptions--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getExportImagesForOldReaders()](#getExportImagesForOldReaders--) | Gibt an, ob die Schlüsselwörter für "alte Leser" in RTF geschrieben werden oder nicht. |
|
|  | [setExportImagesForOldReaders(boolean value)](#setExportImagesForOldReaders-boolean-) | Gibt an, ob die Schlüsselwörter für "alte Leser" in RTF geschrieben werden oder nicht. |
|
### RtfOptions() {#RtfOptions--}
```
public RtfOptions()
```


### getExportImagesForOldReaders() {#getExportImagesForOldReaders--}
```
public final boolean getExportImagesForOldReaders()
```


Gibt an, ob die Schlüsselwörter für "alte Leser" in RTF geschrieben werden oder nicht.
Dies kann die Größe des RTF-Dokuments erheblich beeinflussen. Standard ist False.


**Returns:**
boolean
### setExportImagesForOldReaders(boolean value) {#setExportImagesForOldReaders-boolean-}
```
public final void setExportImagesForOldReaders(boolean value)
```


Gibt an, ob die Schlüsselwörter für "alte Leser" in RTF geschrieben werden oder nicht.
Dies kann die Größe des RTF-Dokuments erheblich beeinflussen. Standard ist False.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

