---
title: "ConvertOptions"
second_title: "GroupDocs.Conversion για Java API Reference"
description: "Η γενική κλάση επιλογών μετατροπής."
type: docs
weight: 12
url: /el/java/com.groupdocs.conversion.options.convert/convertoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.io.Serializable, [com.groupdocs.conversion.options.convert.IConvertOptions](../../com.groupdocs.conversion.options.convert/iconvertoptions), java.lang.Cloneable
```
public abstract class ConvertOptions<TFileType> extends ValueObject implements Serializable, IConvertOptions, Cloneable
```

Η γενική κλάση επιλογών μετατροπής.

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getFormat()](#getFormat--) | {@inheritDoc} |
|
|  | [setFormat(FileType value)](#setFormat-com.groupdocs.conversion.filetypes.FileType-) | Ο επιθυμητός τύπος αρχείου στο οποίο πρέπει να μετατραπεί το εισαγόμενο έγγραφο. |
|
|  | [deepClone()](#deepClone--) | Δημιουργεί αντίγραφο της τρέχουσας παρουσίας επιλογών. |
|
|  | [getFormat_ConvertOptions_New()](#getFormat-ConvertOptions-New--) | Ο επιθυμητός τύπος αρχείου στο οποίο πρέπει να μετατραπεί το εισαγόμενο έγγραφο. |
|
|  | [setFormat_ConvertOptions_New(TFileType value)](#setFormat-ConvertOptions-New-TFileType-) | Ο επιθυμητός τύπος αρχείου στο οποίο πρέπει να μετατραπεί το εισαγόμενο έγγραφο. |
|
### getFormat() {#getFormat--}
```
public FileType getFormat()
```


Λαμβάνει τον επιθυμητό τύπο αρχείου στον οποίο πρέπει να μετατραπεί το εισαγόμενο έγγραφο.


**Returns:**
[FileType](../../com.groupdocs.conversion.filetypes/filetype)
### setFormat(FileType value) {#setFormat-com.groupdocs.conversion.filetypes.FileType-}
```
public void setFormat(FileType value)
```


Ο επιθυμητός τύπος αρχείου στο οποίο πρέπει να μετατραπεί το εισαγόμενο έγγραφο.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Δημιουργεί αντίγραφο της τρέχουσας παρουσίας επιλογών.


**Returns:**
java.lang.Object -
### getFormat_ConvertOptions_New() {#getFormat-ConvertOptions-New--}
```
public final TFileType getFormat_ConvertOptions_New()
```


Ο επιθυμητός τύπος αρχείου στο οποίο πρέπει να μετατραπεί το εισαγόμενο έγγραφο.


**Returns:**
TFileType
### setFormat_ConvertOptions_New(TFileType value) {#setFormat-ConvertOptions-New-TFileType-}
```
public final void setFormat_ConvertOptions_New(TFileType value)
```


Ο επιθυμητός τύπος αρχείου στο οποίο πρέπει να μετατραπεί το εισαγόμενο έγγραφο.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | TFileType |  |

