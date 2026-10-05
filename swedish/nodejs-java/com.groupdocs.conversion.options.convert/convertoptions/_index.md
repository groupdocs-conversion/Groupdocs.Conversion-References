---
title: "ConvertOptions"
second_title: "GroupDocs.Conversion för Node.js via Java API-referens"
description: "Den allmänna konverteringsalternativklassen."
type: docs
weight: 12
url: /sv/nodejs-java/com.groupdocs.conversion.options.convert/convertoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.io.Serializable, [com.groupdocs.conversion.options.convert.IConvertOptions](../../com.groupdocs.conversion.options.convert/iconvertoptions), java.lang.Cloneable
```
public abstract class ConvertOptions<TFileType> extends ValueObject implements Serializable, IConvertOptions, Cloneable
```

Den allmänna konverteringsalternativklassen.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getFormat()](#getFormat--) | \\{@inheritDoc\\} |
| [setFormat(FileType value)](#setFormat-com.groupdocs.conversion.filetypes.FileType-) | Den önskade filtypen som inmatningsdokumentet ska konverteras till. |
| [deepClone()](#deepClone--) | Klonar aktuell alternativinstans. |
| [getFormat_ConvertOptions_New()](#getFormat-ConvertOptions-New--) | Den önskade filtypen som inmatningsdokumentet ska konverteras till. |
| [setFormat_ConvertOptions_New(TFileType value)](#setFormat-ConvertOptions-New-TFileType-) | Den önskade filtypen som inmatningsdokumentet ska konverteras till. |
### getFormat() {#getFormat--}
```
public FileType getFormat()
```


Hämtar den önskade filtypen som inmatningsdokumentet ska konverteras till.

**Returns:**
[FileType](../../com.groupdocs.conversion.filetypes/filetype)
### setFormat(FileType value) {#setFormat-com.groupdocs.conversion.filetypes.FileType-}
```
public void setFormat(FileType value)
```


Den önskade filtypen som inmatningsdokumentet ska konverteras till.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Klonar aktuell alternativinstans.

**Returns:**
java.lang.Object -
### getFormat_ConvertOptions_New() {#getFormat-ConvertOptions-New--}
```
public final TFileType getFormat_ConvertOptions_New()
```


Den önskade filtypen som inmatningsdokumentet ska konverteras till.

**Returns:**
TFileType
### setFormat_ConvertOptions_New(TFileType value) {#setFormat-ConvertOptions-New-TFileType-}
```
public final void setFormat_ConvertOptions_New(TFileType value)
```


Den önskade filtypen som inmatningsdokumentet ska konverteras till.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | TFileType |  |

