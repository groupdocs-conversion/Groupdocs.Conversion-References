---
title: "MemoryCache"
second_title: "Node.js için GroupDocs.Conversion, Java üzerinden API Referansı"
description: "Bellek önbellekleme davranışı."
type: docs
weight: 11
url: /tr/nodejs-java/com.groupdocs.conversion.caching/memorycache/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.conversion.caching.ICache](../../com.groupdocs.conversion.caching/icache)
```
public class MemoryCache implements ICache
```

Bellek önbellekleme davranışı. Önbelleğin bellekte depolandığını ifade eder **Daha fazla bilgi**Önbellekleme ve dönüşüm sürecinin performansını önbelleğe alma ve optimize etme hakkında daha fazla bilgi: [Dönüştürme sonuçlarını önbelleğe alma][]


[Caching conversion results]: https://docs.groupdocs.com/display/conversionnet/Caching
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [MemoryCache()](#MemoryCache--) | MemoryCache sınıfının yeni bir örneğini oluşturur |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [set(String key, Object value)](#set-java.lang.String-java.lang.Object-) | Önbelleğe bir giriş ekler. |
| [tryGetValue(String key)](#tryGetValue-java.lang.String-) | Bu anahtarla ilişkili giriş mevcutsa alır. |
| [getKeys(String filter)](#getKeys-java.lang.String-) | Filtreyle eşleşen tüm anahtarları döndürür. |
### MemoryCache() {#MemoryCache--}
```
public MemoryCache()
```


MemoryCache sınıfının yeni bir örneğini oluşturur

### set(String key, Object value) {#set-java.lang.String-java.lang.Object-}
```
public void set(String key, Object value)
```


Önbelleğe bir giriş ekler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| anahtar | java.lang.String | Önbellek girişi için benzersiz bir tanımlayıcı. |
| değer | java.lang.Object | Eklenecek nesne. |

### tryGetValue(String key) {#tryGetValue-java.lang.String-}
```
public Object tryGetValue(String key)
```


Bu anahtarla ilişkili giriş mevcutsa alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| anahtar | java.lang.String | İstenen girişi tanımlayan bir anahtar. |

**Returns:**
java.lang.Object - Bulunan değer veya null.
### getKeys(String filter) {#getKeys-java.lang.String-}
```
public Iterable<String> getKeys(String filter)
```


Filtreyle eşleşen tüm anahtarları döndürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filtre | java.lang.String | Kullanılacak filtre. |

**Returns:**
java.lang.Iterable<java.lang.String> - Filtreyle eşleşen anahtarlar.
