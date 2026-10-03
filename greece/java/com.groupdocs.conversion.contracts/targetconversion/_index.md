---
title: "TargetConversion"
second_title: "GroupDocs.Conversion για Java API Reference"
description: "Αντιπροσωπεύει τη δυνατότητα μετατροπής προορισμού και μια σημαία που υποδεικνύει αν είναι κύρια ή δευτερεύουσα."
type: docs
weight: 14
url: /el/java/com.groupdocs.conversion.contracts/targetconversion/
---
**Inheritance:**
java.lang.Object
```
public final class TargetConversion
```

Αντιπροσωπεύει τη δυνατότητα μετατροπής προορισμού και μια σημαία που υποδεικνύει αν είναι κύρια ή δευτερεύουσα.

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getFormat()](#getFormat--) | Μορφή εγγράφου προορισμού |
|
|  | [isPrimary()](#isPrimary--) | Είναι η μετατροπή κύρια |
|
|  | [getConvertOptions()](#getConvertOptions--) | Προκαθορισμένες επιλογές μετατροπής που μπορούν να χρησιμοποιηθούν για μετατροπή στον τρέχον τύπο |
|
### getFormat() {#getFormat--}
```
public FileType getFormat()
```


Μορφή εγγράφου προορισμού


**Returns:**
[FileType](../../com.groupdocs.conversion.filetypes/filetype) - Target document format

### isPrimary() {#isPrimary--}
```
public boolean isPrimary()
```


Είναι η μετατροπή κύρια


**Returns:**
boolean - `true` εάν είναι κύριο

### getConvertOptions() {#getConvertOptions--}
```
public ConvertOptions getConvertOptions()
```


Προκαθορισμένες επιλογές μετατροπής που μπορούν να χρησιμοποιηθούν για μετατροπή στον τρέχον τύπο


**Returns:**
[ConvertOptions](../../com.groupdocs.conversion.options.convert/convertoptions) - convert options

