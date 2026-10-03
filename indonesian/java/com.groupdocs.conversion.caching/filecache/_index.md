---
title: "FileCache"
second_title: "Referensi API GroupDocs.Conversion untuk Java"
description: "Perilaku caching file."
type: docs
weight: 10
url: /id/java/com.groupdocs.conversion.caching/filecache/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.conversion.caching.ICache](../../com.groupdocs.conversion.caching/icache)
```
public final class FileCache implements ICache
```

Perilaku caching file. Artinya cache disimpan pada sistem file **Learn more** Lebih lanjut tentang caching dan mengoptimalkan kinerja proses konversi: [Caching conversion results](../https://docs.groupdocs.com/display/conversionnet/Caching)

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [FileCache(String cachePath)](#FileCache-java.lang.String-) | Membuat instance baru dari kelas FileCache |
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
### FileCache(String cachePath) {#FileCache-java.lang.String-}
```
public FileCache(String cachePath)
```


Membuat instance baru dari kelas FileCache


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | cachePath | java.lang.String | Jalur relatif atau absolut tempat cache dokumen akan disimpan |
|

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
java.lang.Object - Objek jika kunci ditemukan atau null.

### getKeys(String filter) {#getKeys-java.lang.String-}
```
public Iterable<String> getKeys(String filter)
```


Mengembalikan semua kunci yang cocok dengan filter.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | filter | java.lang.String | Filter yang akan digunakan. |
|

**Returns:**
java.lang.Iterable<java.lang.String> - Kunci yang cocok dengan filter.

