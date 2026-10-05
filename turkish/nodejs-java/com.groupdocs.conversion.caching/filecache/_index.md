---
title: "FileCache"
second_title: "Node.js için GroupDocs.Conversion, Java üzerinden API Referansı"
description: "Dosya önbellekleme davranışı."
type: docs
weight: 10
url: /tr/nodejs-java/com.groupdocs.conversion.caching/filecache/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.conversion.caching.ICache](../../com.groupdocs.conversion.caching/icache)
```
public final class FileCache implements ICache
```

Dosya önbellekleme davranışı. Önbelleğin dosya sisteminde depolandığını ifade eder **Daha fazla bilgi**Önbellekleme ve dönüşüm sürecinin performansını önbelleğe alma ve optimize etme hakkında daha fazla bilgi: [Dönüştürme sonuçlarını önbelleğe alma][]


[Caching conversion results]: https://docs.groupdocs.com/display/conversionnet/Caching
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [FileCache(String cachePath)](#FileCache-java.lang.String-) | FileCache sınıfının yeni bir örneğini oluşturur |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [set(String key, Object value)](#set-java.lang.String-java.lang.Object-) | Önbelleğe bir giriş ekler. |
| [tryGetValue(String key)](#tryGetValue-java.lang.String-) | Bu anahtarla ilişkili giriş mevcutsa alır. |
| [getKeys(String filter)](#getKeys-java.lang.String-) | Filtreyle eşleşen tüm anahtarları döndürür. |
### FileCache(String cachePath) {#FileCache-java.lang.String-}
```
public FileCache(String cachePath)
```


FileCache sınıfının yeni bir örneğini oluşturur

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| cachePath | java.lang.String | Belge önbelleğinin depolanacağı göreli veya mutlak yol |

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
java.lang.Object - Anahtar bulunursa nesne, aksi takdirde null.
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
