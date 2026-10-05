---
title: "PresentationConvertOptions"
second_title: "Node.js için GroupDocs.Conversion, Java üzerinden API Referansı"
description: "Sunum dosya türüne dönüştürme seçeneklerini açıklar."
type: docs
weight: 33
url: /tr/nodejs-java/com.groupdocs.conversion.options.convert/presentationconvertoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), com.groupdocs.conversion.options.convert.ConvertOptions, com.groupdocs.conversion.options.convert.CommonConvertOptions

**All Implemented Interfaces:**
java.io.Serializable
```
public class PresentationConvertOptions extends CommonConvertOptions<PresentationFileType> implements Serializable
```

Sunum dosya türüne dönüştürme seçeneklerini açıklar.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [PresentationConvertOptions()](#PresentationConvertOptions--) | Yeni bir [PresentationConvertOptions](../../com.groupdocs.conversion.options.convert/presentationconvertoptions) sınıfı örneği başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getPassword()](#getPassword--) | Bu özelliği, dönüştürülen belgeyi bir şifreyle korumak istiyorsanız ayarlayın. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Bu özelliği, dönüştürülen belgeyi bir şifreyle korumak istiyorsanız ayarlayın. |
| [getZoom()](#getZoom--) | Yakınlaştırma seviyesini yüzde olarak belirtir. |
| [setZoom(int value)](#setZoom-int-) | Yakınlaştırma seviyesini yüzde olarak belirtir. |
### PresentationConvertOptions() {#PresentationConvertOptions--}
```
public PresentationConvertOptions()
```


Yeni bir [PresentationConvertOptions](../../com.groupdocs.conversion.options.convert/presentationconvertoptions) sınıfı örneği başlatır.

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


Yakınlaştırma seviyesini yüzde olarak belirtir. Varsayılan değer 100'dür. Varsayılan yakınlaştırma, Microsoft Powerpoint 2010'a kadar desteklenir. Microsoft Powerpoint 2013'ten itibaren varsayılan yakınlaştırma belgeye artık ayarlanmamaktadır; bunun yerine açılan son belgenin yakınlaştırma faktörü kullanılıyor gibi görünür.

**Returns:**
int
### setZoom(int value) {#setZoom-int-}
```
public final void setZoom(int value)
```


Yakınlaştırma seviyesini yüzde olarak belirtir. Varsayılan değer 100'dür. Varsayılan yakınlaştırma, Microsoft Powerpoint 2010'a kadar desteklenir. Microsoft Powerpoint 2013'ten itibaren varsayılan yakınlaştırma belgeye artık ayarlanmamaktadır; bunun yerine açılan son belgenin yakınlaştırma faktörü kullanılıyor gibi görünür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

