---
title: "MemoryCache"
second_title: "Referensi API GroupDocs.Conversion untuk Java"
description: "Perilaku caching memori."
type: docs
weight: 11
url: /id/java/com.groupdocs.conversion.caching/memorycache/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.conversion.caching.ICache](../../com.groupdocs.conversion.caching/icache)
```
public class MemoryCache implements ICache
```

Perilaku caching memori. Artinya cache disimpan di memori **Learn more** Lebih lanjut tentang caching dan mengoptimalkan kinerja proses konversi: [Caching conversion results](../https://docs.groupdocs.com/display/conversionnet/Caching)

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [MemoryCache()](#MemoryCache--) | Membuat instance baru dari kelas MemoryCache |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [set(String key, Object value)](#set-java.lang.String-java.lang.Object-) | Menyisipkan entri cache ke dalam cache. |
|
|  | [tryGetValue(String key)](#tryGetValue-java.lang.String-) | Mendapatkan entri yang terkait dengan kunci ini jika ada. |
|
|  | [getKeys(String filter)](#getKeys-java.lang.String-) | Mengembalikan semua kunci yang cocok dengan filter. |
|
### MemoryCache() {#MemoryCache--}
```
public MemoryCache()
```


Membuat instance baru dari kelas MemoryCache


### set(String key, Object value) {#set-java.lang.String-java.lang.Object-}
```
public void set(String key, Object value)
```


Menyisipkan entri cache ke dalam cache.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | kunci | java.lang.String | Pengidentifikasi unik untuk entri cache. |
|
|  | nilai | java.lang.Object | Objek yang akan disisipkan. |
|

### tryGetValue(String key) {#tryGetValue-java.lang.String-}
```
public Object tryGetValue(String key)
```


Mendapatkan entri yang terkait dengan kunci ini jika ada.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | kunci | java.lang.String | Kunci yang mengidentifikasi entri yang diminta. |
|

**Returns:**
java.lang.Object - Nilai yang ditemukan atau null.

### getKeys(String filter) {#getKeys-java.lang.String-}
```
public Iterable<String> getKeys(String filter)
```


Mengembalikan semua kunci yang cocok dengan filter.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | filter | java.lang.String | filter yang akan digunakan. |
|

**Returns:**
java.lang.Iterable<java.lang.String> - Kunci yang cocok dengan filter.

