---
title: "SpreadsheetConvertOptions"
second_title: "Node.js için GroupDocs.Conversion, Java üzerinden API Referansı"
description: "Elektronik tablo dosya türüne dönüştürme seçenekleri."
type: docs
weight: 40
url: /tr/nodejs-java/com.groupdocs.conversion.options.convert/spreadsheetconvertoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), com.groupdocs.conversion.options.convert.ConvertOptions, com.groupdocs.conversion.options.convert.CommonConvertOptions

**All Implemented Interfaces:**
java.io.Serializable
```
public class SpreadsheetConvertOptions extends CommonConvertOptions<SpreadsheetFileType> implements Serializable
```

Elektronik tablo dosya türüne dönüştürme seçenekleri.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [SpreadsheetConvertOptions()](#SpreadsheetConvertOptions--) | Yeni bir [SpreadsheetConvertOptions](../../com.groupdocs.conversion.options.convert/spreadsheetconvertoptions) sınıfı örneği başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getPassword()](#getPassword--) | Bu özelliği, dönüştürülen belgeyi bir şifreyle korumak istiyorsanız ayarlayın. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Bu özelliği, dönüştürülen belgeyi bir şifreyle korumak istiyorsanız ayarlayın. |
| [getZoom()](#getZoom--) | Yakınlaştırma seviyesini yüzde olarak belirtir. |
| [setZoom(int value)](#setZoom-int-) | Yakınlaştırma seviyesini yüzde olarak belirtir. |
### SpreadsheetConvertOptions() {#SpreadsheetConvertOptions--}
```
public SpreadsheetConvertOptions()
```


Yeni bir [SpreadsheetConvertOptions](../../com.groupdocs.conversion.options.convert/spreadsheetconvertoptions) sınıfı örneği başlatır.

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Bu özelliği, dönüştürülen belgeyi bir şifreyle korumak istiyorsanız ayarlayın.

**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Bu özelliği, dönüştürülen belgeyi bir şifreyle korumak istiyorsanız ayarlayın.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getZoom() {#getZoom--}
```
public final int getZoom()
```


Yakınlaştırma seviyesini yüzde olarak belirtir. Varsayılan değer 100'dür.

**Returns:**
int
### setZoom(int value) {#setZoom-int-}
```
public final void setZoom(int value)
```


Yakınlaştırma seviyesini yüzde olarak belirtir. Varsayılan değer 100'dür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

