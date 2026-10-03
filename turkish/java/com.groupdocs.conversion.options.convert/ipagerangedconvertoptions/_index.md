---
title: "IPageRangedConvertOptions"
second_title: "Java için GroupDocs.Conversion API Referansı"
description: "Belirli sayfa listesinin dönüştürülmesini destekleyen dönüştürme seçeneklerini temsil eder"
type: docs
weight: 52
url: /tr/java/com.groupdocs.conversion.options.convert/ipagerangedconvertoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.conversion.options.convert.IConvertOptions](../../com.groupdocs.conversion.options.convert/iconvertoptions)
```
public interface IPageRangedConvertOptions extends IConvertOptions
```

Belirli sayfa listesinin dönüştürülmesini destekleyen dönüştürme seçeneklerini temsil eder

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getPages()](#getPages--) | Dönüştürülecek sayfa indekslerinin listesini alır. |
|
|  | [setPages(List<Integer> pages)](#setPages-java.util.List-java.lang.Integer--) | Dönüştürülecek sayfa indekslerinin listesini ayarlar. |
|
### getPages() {#getPages--}
```
public abstract List<Integer> getPages()
```


Dönüştürülecek sayfa indekslerinin listesini alır. Belirli sayfaları dönüştürmek için belirtilmelidir.


**Returns:**
java.util.List<java.lang.Integer> - Dönüştürülecek sayfa indekslerinin listesi. Belirli sayfaları dönüştürmek için belirtilmelidir.

### setPages(List<Integer> pages) {#setPages-java.util.List-java.lang.Integer--}
```
public abstract void setPages(List<Integer> pages)
```


Dönüştürülecek sayfa indekslerinin listesini ayarlar. Belirli sayfaları dönüştürmek için belirtilmelidir.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | pages | java.util.List<java.lang.Integer> | Dönüştürülecek sayfa indekslerinin listesi. Belirli sayfaları dönüştürmek için belirtilmelidir. |
|

