---
title: "PresentationConvertOptions"
second_title: "Java için GroupDocs.Conversion API Referansı"
description: "Sunum dosya türüne dönüştürme seçeneklerini açıklar."
type: docs
weight: 33
url: /tr/java/com.groupdocs.conversion.options.convert/presentationconvertoptions/
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
|  | [PresentationConvertOptions()](#PresentationConvertOptions--) | Yeni bir [PresentationConvertOptions](../../com.groupdocs.conversion.options.convert/presentationconvertoptions) sınıfı örneği başlatır. |
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
### PresentationConvertOptions() {#PresentationConvertOptions--}
```
public PresentationConvertOptions()
```


Yeni bir [PresentationConvertOptions](../../com.groupdocs.conversion.options.convert/presentationconvertoptions) sınıfı örneği başlatır.


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
Varsayılan yakınlaştırma Microsoft Powerpoint 2010'a kadar desteklenir. Microsoft Powerpoint 2013'ten itibaren varsayılan yakınlaştırma belgeye ayarlanmamaktadır; bunun yerine son açılan belgenin yakınlaştırma faktörü kullanılıyor gibi görünmektedir.


**Returns:**
int
### setZoom(int value) {#setZoom-int-}
```
public final void setZoom(int value)
```


Yakınlaştırma seviyesini yüzde olarak belirtir. Varsayılan değer 100.
Varsayılan yakınlaştırma Microsoft Powerpoint 2010'a kadar desteklenir. Microsoft Powerpoint 2013'ten itibaren varsayılan yakınlaştırma belgeye ayarlanmamaktadır; bunun yerine son açılan belgenin yakınlaştırma faktörü kullanılıyor gibi görünmektedir.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

