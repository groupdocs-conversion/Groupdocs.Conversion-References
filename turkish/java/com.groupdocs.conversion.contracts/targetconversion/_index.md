---
title: "TargetConversion"
second_title: "Java için GroupDocs.Conversion API Referansı"
description: "Olası hedef dönüşüm ve bunun birincil mi ikincil mi olduğunu gösteren bir bayrağı temsil eder"
type: docs
weight: 14
url: /tr/java/com.groupdocs.conversion.contracts/targetconversion/
---
**Inheritance:**
java.lang.Object
```
public final class TargetConversion
```

Olası hedef dönüşüm ve bunun birincil mi ikincil mi olduğunu gösteren bir bayrağı temsil eder

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getFormat()](#getFormat--) | Hedef belge formatı |
|
|  | [isPrimary()](#isPrimary--) | Dönüşüm birincil mi |
|
|  | [getConvertOptions()](#getConvertOptions--) | Mevcut türe dönüştürmek için kullanılabilecek önceden tanımlanmış dönüştürme seçenekleri |
|
### getFormat() {#getFormat--}
```
public FileType getFormat()
```


Hedef belge formatı


**Returns:**
[FileType](../../com.groupdocs.conversion.filetypes/filetype) - Target document format

### isPrimary() {#isPrimary--}
```
public boolean isPrimary()
```


Dönüşüm birincil mi


**Returns:**
boolean - birincil ise `true`

### getConvertOptions() {#getConvertOptions--}
```
public ConvertOptions getConvertOptions()
```


Mevcut türe dönüştürmek için kullanılabilecek önceden tanımlanmış dönüştürme seçenekleri


**Returns:**
[ConvertOptions](../../com.groupdocs.conversion.options.convert/convertoptions) - convert options

