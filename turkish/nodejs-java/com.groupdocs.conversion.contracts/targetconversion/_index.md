---
title: "TargetConversion"
second_title: "Node.js için GroupDocs.Conversion, Java üzerinden API Referansı"
description: "Olası hedef dönüşümü ve bunun birincil mi ikincil mi olduğunu belirten bir bayrağı temsil eder"
type: docs
weight: 14
url: /tr/nodejs-java/com.groupdocs.conversion.contracts/targetconversion/
---
**Inheritance:**
java.lang.Object
```
public final class TargetConversion
```

Olası hedef dönüşümü ve bunun birincil mi ikincil mi olduğunu belirten bir bayrağı temsil eder
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getFormat()](#getFormat--) | Hedef belge biçimi |
| [isPrimary()](#isPrimary--) | Dönüşüm birincil mi |
| [getConvertOptions()](#getConvertOptions--) | Mevcut türe dönüştürmek için kullanılabilecek önceden tanımlı dönüştürme seçenekleri |
### getFormat() {#getFormat--}
```
public FileType getFormat()
```


Hedef belge biçimi

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


Mevcut türe dönüştürmek için kullanılabilecek önceden tanımlı dönüştürme seçenekleri

**Returns:**
[ConvertOptions](../../com.groupdocs.conversion.options.convert/convertoptions) - convert options
