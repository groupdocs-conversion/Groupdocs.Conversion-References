---
title: "SpreadsheetConvertOptions"
second_title: "Java için GroupDocs.Conversion API Referansı"
description: "Elektronik tablo dosya türüne dönüştürme seçenekleri."
type: docs
weight: 40
url: /tr/java/com.groupdocs.conversion.options.convert/spreadsheetconvertoptions/
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
|  | [SpreadsheetConvertOptions()](#SpreadsheetConvertOptions--) | Yeni bir [SpreadsheetConvertOptions](../../com.groupdocs.conversion.options.convert/spreadsheetconvertoptions) sınıfı örneği başlatır. |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getPassword()](#getPassword--) | Dönüştürülen belgeyi bir şifre ile korumak istiyorsanız bu özelliği ayarlayın. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Dönüştürülen belgeyi bir şifre ile korumak istiyorsanız bu özelliği ayarlayın. |
|
|  | [getZoom()](#getZoom--) | Yakınlaştırma seviyesini yüzde olarak belirtir. |
|
|  | [setZoom(int value)](#setZoom-int-) | Yakınlaştırma seviyesini yüzde olarak belirtir. |
|
|  | [getSeparator()](#getSeparator--) | Ayırıcıyı, ayrılmış formatlara dönüştürürken kullanılacak şekilde belirtir. |
|
| [setSeparator(char separator)](#setSeparator-char-) |  |
| [setFormat(FileType value)](#setFormat-com.groupdocs.conversion.filetypes.FileType-) |  |
### SpreadsheetConvertOptions() {#SpreadsheetConvertOptions--}
```
public SpreadsheetConvertOptions()
```


Yeni bir [SpreadsheetConvertOptions](../../com.groupdocs.conversion.options.convert/spreadsheetconvertoptions) sınıfı örneği başlatır.


### getPassword() {#getPassword--}
```
public final String getPassword()
```


Dönüştürülen belgeyi bir şifre ile korumak istiyorsanız bu özelliği ayarlayın.


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Dönüştürülen belgeyi bir şifre ile korumak istiyorsanız bu özelliği ayarlayın.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getZoom() {#getZoom--}
```
public final int getZoom()
```


Yakınlaştırma seviyesini yüzde olarak belirtir. Varsayılan değer 100.


**Returns:**
int
### setZoom(int value) {#setZoom-int-}
```
public final void setZoom(int value)
```


Yakınlaştırma seviyesini yüzde olarak belirtir. Varsayılan değer 100.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getSeparator() {#getSeparator--}
```
public char getSeparator()
```


Ayırıcıyı, ayrılmış formatlara dönüştürürken kullanılacak şekilde belirtir.


**Returns:**
char
### setSeparator(char separator) {#setSeparator-char-}
```
public void setSeparator(char separator)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ayırıcı | char |  |

### setFormat(FileType value) {#setFormat-com.groupdocs.conversion.filetypes.FileType-}
```
public void setFormat(FileType value)
```


Girdi belgesinin dönüştürülmesi gereken istenen dosya türü.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |

