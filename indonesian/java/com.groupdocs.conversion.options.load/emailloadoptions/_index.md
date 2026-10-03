---
title: "EmailLoadOptions"
second_title: "Referensi API GroupDocs.Conversion untuk Java"
description: "Opsi untuk memuat dokumen Email."
type: docs
weight: 18
url: /id/java/com.groupdocs.conversion.options.load/emailloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
[com.groupdocs.conversion.contracts.IDocumentsContainerLoadOptions](../../com.groupdocs.conversion.contracts/idocumentscontainerloadoptions), java.lang.Cloneable, java.io.Serializable
```
public final class EmailLoadOptions extends LoadOptions implements IDocumentsContainerLoadOptions, Cloneable, Serializable
```

Opsi untuk memuat dokumen Email.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [EmailLoadOptions()](#EmailLoadOptions--) | Menginisialisasi instance baru dari kelas [EmailLoadOptions](../../com.groupdocs.conversion.options.load/emailloadoptions). |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getFormat()](#getFormat--) |  |
|  | [getDisplayHeader()](#getDisplayHeader--) | Opsi untuk menampilkan atau menyembunyikan header email. |
|
|  | [setDisplayHeader(boolean value)](#setDisplayHeader-boolean-) | Opsi untuk menampilkan atau menyembunyikan header email. |
|
|  | [getDisplayFromEmailAddress()](#getDisplayFromEmailAddress--) | Opsi untuk menampilkan atau menyembunyikan alamat email "from". |
|
|  | [setDisplayFromEmailAddress(boolean value)](#setDisplayFromEmailAddress-boolean-) | Opsi untuk menampilkan atau menyembunyikan alamat email "from". |
|
|  | [getDisplayToEmailAddress()](#getDisplayToEmailAddress--) | Opsi untuk menampilkan atau menyembunyikan alamat email "to". |
|
|  | [setDisplayToEmailAddress(boolean value)](#setDisplayToEmailAddress-boolean-) | Opsi untuk menampilkan atau menyembunyikan alamat email "to". |
|
|  | [getDisplayCcEmailAddress()](#getDisplayCcEmailAddress--) | Opsi untuk menampilkan atau menyembunyikan alamat email "Cc". |
|
|  | [setDisplayCcEmailAddress(boolean value)](#setDisplayCcEmailAddress-boolean-) | Opsi untuk menampilkan atau menyembunyikan alamat email "Cc". |
|
|  | [getDisplayBccEmailAddress()](#getDisplayBccEmailAddress--) | Opsi untuk menampilkan atau menyembunyikan alamat email "Bcc". |
|
|  | [setDisplayBccEmailAddress(boolean value)](#setDisplayBccEmailAddress-boolean-) | Opsi untuk menampilkan atau menyembunyikan alamat email "Bcc". |
|
|  | [getTimeZoneOffset()](#getTimeZoneOffset--) | Mendapatkan atau mengatur offset Waktu Universal Terkoordinasi (UTC) untuk tanggal pesan. |
|
| [getTimeZoneOffsetInternal()](#getTimeZoneOffsetInternal--) |  |
|  | [getResourceLoadingTimeout()](#getResourceLoadingTimeout--) | Batas waktu untuk memuat sumber daya eksternal |
|
|  | [setResourceLoadingTimeout(System.TimeSpan resourceLoadingTimeout)](#setResourceLoadingTimeout-com.aspose.ms.System.TimeSpan-) | Batas waktu untuk memuat sumber daya eksternal (setter) |
|
|  | [setTimeZoneOffset(Double value)](#setTimeZoneOffset-java.lang.Double-) | Mendapatkan atau mengatur offset Waktu Universal Terkoordinasi (UTC) untuk tanggal pesan. |
|
|  | [deepClone()](#deepClone--) | Menggandakan instance saat ini. |
|
|  | [getFieldTextMap()](#getFieldTextMap--) | Mendapatkan pemetaan antara pesan email dan representasi teks bidang |
|
|  | [setFieldTextMap(Map<EmailField,String> fieldTextMap)](#setFieldTextMap-java.util.Map-com.groupdocs.conversion.options.load.EmailField-java.lang.String--) | Mengatur pemetaan antara pesan email dan representasi teks bidang |
|
|  | [isPreserveOriginalDate()](#isPreserveOriginalDate--) | Mendefinisikan apakah perlu mempertahankan string header tanggal asli dalam pesan email saat menyimpan atau tidak (Nilai default adalah true) |
|
|  | [setPreserveOriginalDate(boolean preserveOriginalDate)](#setPreserveOriginalDate-boolean-) | Mendefinisikan apakah perlu mempertahankan string header tanggal asli dalam pesan email saat menyimpan atau tidak |
|
| [isConvertOwner()](#isConvertOwner--) |  |
| [setConvertOwner(boolean convertOwner)](#setConvertOwner-boolean-) |  |
| [isConvertOwned()](#isConvertOwned--) |  |
| [setConvertOwned(boolean convertOwned)](#setConvertOwned-boolean-) |  |
| [getDepth()](#getDepth--) |  |
| [setDepth(int depth)](#setDepth-int-) |  |
|  | [isDisplayAttachments()](#isDisplayAttachments--) | Mendapatkan opsi untuk menampilkan atau menyembunyikan lampiran di header. |
|
|  | [setDisplayAttachments(boolean displayAttachments)](#setDisplayAttachments-boolean-) | Mengatur opsi untuk menampilkan atau menyembunyikan lampiran di header. |
|
|  | [isDisplaySubject()](#isDisplaySubject--) | Mendapatkan opsi untuk menampilkan atau menyembunyikan subjek di header. |
|
|  | [setDisplaySubject(boolean displaySubject)](#setDisplaySubject-boolean-) | Mengatur opsi untuk menampilkan atau menyembunyikan subjek di header |
|
|  | [isDisplaySent()](#isDisplaySent--) | Mendapatkan opsi untuk menampilkan atau menyembunyikan tanggal/waktu terkirim di header. |
|
|  | [setDisplaySent(boolean displaySent)](#setDisplaySent-boolean-) | Mengatur opsi untuk menampilkan atau menyembunyikan tanggal/waktu terkirim di header. |
|
|  | [isSkipExternalResources()](#isSkipExternalResources--) | Lewati pemuatan sumber daya http jika true |
|
| [setSkipExternalResources(boolean skipExternalResources)](#setSkipExternalResources-boolean-) |  |
### EmailLoadOptions() {#EmailLoadOptions--}
```
public EmailLoadOptions()
```


Menginisialisasi instance baru dari kelas [EmailLoadOptions](../../com.groupdocs.conversion.options.load/emailloadoptions).


### getFormat() {#getFormat--}
```
public final EmailFileType getFormat()
```


Jenis berkas dokumen input


**Returns:**
[EmailFileType](../../com.groupdocs.conversion.filetypes/emailfiletype)
### getDisplayHeader() {#getDisplayHeader--}
```
public final boolean getDisplayHeader()
```


Opsi untuk menampilkan atau menyembunyikan header email. Default: true.


**Returns:**
boolean
### setDisplayHeader(boolean value) {#setDisplayHeader-boolean-}
```
public final void setDisplayHeader(boolean value)
```


Opsi untuk menampilkan atau menyembunyikan header email. Default: true.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### getDisplayFromEmailAddress() {#getDisplayFromEmailAddress--}
```
public final boolean getDisplayFromEmailAddress()
```


Opsi untuk menampilkan atau menyembunyikan alamat email "from". Default: true.


**Returns:**
boolean
### setDisplayFromEmailAddress(boolean value) {#setDisplayFromEmailAddress-boolean-}
```
public final void setDisplayFromEmailAddress(boolean value)
```


Opsi untuk menampilkan atau menyembunyikan alamat email "from". Default: true.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### getDisplayToEmailAddress() {#getDisplayToEmailAddress--}
```
public final boolean getDisplayToEmailAddress()
```


Opsi untuk menampilkan atau menyembunyikan alamat email "to". Default: true.


**Returns:**
boolean
### setDisplayToEmailAddress(boolean value) {#setDisplayToEmailAddress-boolean-}
```
public final void setDisplayToEmailAddress(boolean value)
```


Opsi untuk menampilkan atau menyembunyikan alamat email "to". Default: true.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### getDisplayCcEmailAddress() {#getDisplayCcEmailAddress--}
```
public final boolean getDisplayCcEmailAddress()
```


Opsi untuk menampilkan atau menyembunyikan alamat email "Cc". Default: false.


**Returns:**
boolean
### setDisplayCcEmailAddress(boolean value) {#setDisplayCcEmailAddress-boolean-}
```
public final void setDisplayCcEmailAddress(boolean value)
```


Opsi untuk menampilkan atau menyembunyikan alamat email "Cc". Default: false.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### getDisplayBccEmailAddress() {#getDisplayBccEmailAddress--}
```
public final boolean getDisplayBccEmailAddress()
```


Opsi untuk menampilkan atau menyembunyikan alamat email "Bcc". Default: false.


**Returns:**
boolean
### setDisplayBccEmailAddress(boolean value) {#setDisplayBccEmailAddress-boolean-}
```
public final void setDisplayBccEmailAddress(boolean value)
```


Opsi untuk menampilkan atau menyembunyikan alamat email "Bcc". Default: false.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### getTimeZoneOffset() {#getTimeZoneOffset--}
```
public final Double getTimeZoneOffset()
```


Mendapatkan atau mengatur offset Waktu Universal Terkoordinasi (UTC) untuk tanggal pesan. Properti ini mendefinisikan perbedaan zona waktu antara waktu lokal dan UTC.


**Returns:**
java.lang.Double
### getTimeZoneOffsetInternal() {#getTimeZoneOffsetInternal--}
```
public System.TimeSpan getTimeZoneOffsetInternal()
```




**Returns:**
com.aspose.ms.System.TimeSpan
### getResourceLoadingTimeout() {#getResourceLoadingTimeout--}
```
public System.TimeSpan getResourceLoadingTimeout()
```


Batas waktu untuk memuat sumber daya eksternal


**Returns:**
com.aspose.ms.System.TimeSpan
### setResourceLoadingTimeout(System.TimeSpan resourceLoadingTimeout) {#setResourceLoadingTimeout-com.aspose.ms.System.TimeSpan-}
```
public void setResourceLoadingTimeout(System.TimeSpan resourceLoadingTimeout)
```


Batas waktu untuk memuat sumber daya eksternal (setter)


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| resourceLoadingTimeout | com.aspose.ms.System.TimeSpan |  |

### setTimeZoneOffset(Double value) {#setTimeZoneOffset-java.lang.Double-}
```
public final void setTimeZoneOffset(Double value)
```


Mendapatkan atau mengatur offset Waktu Universal Terkoordinasi (UTC) untuk tanggal pesan. Properti ini mendefinisikan perbedaan zona waktu antara waktu lokal dan UTC.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.Double |  |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Menggandakan instance saat ini.


**Returns:**
java.lang.Object -
### getFieldTextMap() {#getFieldTextMap--}
```
public Map<EmailField,String> getFieldTextMap()
```


Mendapatkan pemetaan antara pesan email dan representasi teks bidang


**Returns:**
java.util.Map<com.groupdocs.conversion.options.load.EmailField,java.lang.String> - pemetaan

### setFieldTextMap(Map<EmailField,String> fieldTextMap) {#setFieldTextMap-java.util.Map-com.groupdocs.conversion.options.load.EmailField-java.lang.String--}
```
public void setFieldTextMap(Map<EmailField,String> fieldTextMap)
```


Mengatur pemetaan antara pesan email dan representasi teks bidang


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | fieldTextMap | java.util.Map<com.groupdocs.conversion.options.load.EmailField,java.lang.String> | pemetaan |
|

### isPreserveOriginalDate() {#isPreserveOriginalDate--}
```
public boolean isPreserveOriginalDate()
```


Mendefinisikan apakah perlu mempertahankan string header tanggal asli dalam pesan email saat menyimpan atau tidak (Nilai default adalah true)


**Returns:**
boolean - pertahankan tanggal asli jika true

### setPreserveOriginalDate(boolean preserveOriginalDate) {#setPreserveOriginalDate-boolean-}
```
public void setPreserveOriginalDate(boolean preserveOriginalDate)
```


Mendefinisikan apakah perlu mempertahankan string header tanggal asli dalam pesan email saat menyimpan atau tidak


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | preserveOriginalDate | boolean | pertahankan tanggal asli |
|

### isConvertOwner() {#isConvertOwner--}
```
public boolean isConvertOwner()
```


Mendapatkan opsi untuk mengontrol apakah kontainer dokumen itu sendiri harus dikonversi


**Returns:**
boolean
### setConvertOwner(boolean convertOwner) {#setConvertOwner-boolean-}
```
public void setConvertOwner(boolean convertOwner)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| convertOwner | boolean |  |

### isConvertOwned() {#isConvertOwned--}
```
public boolean isConvertOwned()
```


Opsi untuk mengontrol apakah dokumen yang dimiliki dalam kontainer dokumen harus dikonversi


**Returns:**
boolean
### setConvertOwned(boolean convertOwned) {#setConvertOwned-boolean-}
```
public void setConvertOwned(boolean convertOwned)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| convertOwned | boolean |  |

### getDepth() {#getDepth--}
```
public int getDepth()
```


Opsi untuk mengontrol berapa banyak tingkat kedalaman untuk melakukan konversi


**Returns:**
int
### setDepth(int depth) {#setDepth-int-}
```
public void setDepth(int depth)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| depth | int |  |

### isDisplayAttachments() {#isDisplayAttachments--}
```
public boolean isDisplayAttachments()
```


Mendapatkan opsi untuk menampilkan atau menyembunyikan lampiran di header. Default: true.


**Returns:**
boolean
### setDisplayAttachments(boolean displayAttachments) {#setDisplayAttachments-boolean-}
```
public void setDisplayAttachments(boolean displayAttachments)
```


Mengatur opsi untuk menampilkan atau menyembunyikan lampiran di header.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| displayAttachments | boolean |  |

### isDisplaySubject() {#isDisplaySubject--}
```
public boolean isDisplaySubject()
```


Mendapatkan opsi untuk menampilkan atau menyembunyikan subjek di header. Default: true.


**Returns:**
boolean
### setDisplaySubject(boolean displaySubject) {#setDisplaySubject-boolean-}
```
public void setDisplaySubject(boolean displaySubject)
```


Mengatur opsi untuk menampilkan atau menyembunyikan subjek di header


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| displaySubject | boolean |  |

### isDisplaySent() {#isDisplaySent--}
```
public boolean isDisplaySent()
```


Mendapatkan opsi untuk menampilkan atau menyembunyikan tanggal/waktu terkirim di header. Default: true.


**Returns:**
boolean
### setDisplaySent(boolean displaySent) {#setDisplaySent-boolean-}
```
public void setDisplaySent(boolean displaySent)
```


Mengatur opsi untuk menampilkan atau menyembunyikan tanggal/waktu terkirim di header.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| displaySent | boolean |  |

### isSkipExternalResources() {#isSkipExternalResources--}
```
public boolean isSkipExternalResources()
```


Lewati pemuatan sumber daya http jika true


**Returns:**
boolean
### setSkipExternalResources(boolean skipExternalResources) {#setSkipExternalResources-boolean-}
```
public void setSkipExternalResources(boolean skipExternalResources)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| skipExternalResources | boolean |  |

