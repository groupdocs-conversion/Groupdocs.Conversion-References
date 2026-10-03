---
title: "WatermarkOptions"
second_title: "Referensi API GroupDocs.Conversion untuk Java"
description: "Opsi untuk mengatur watermark pada dokumen yang dikonversi"
type: docs
weight: 44
url: /id/java/com.groupdocs.conversion.options.convert/watermarkoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.lang.Cloneable, java.io.Serializable
```
public abstract class WatermarkOptions extends ValueObject implements Cloneable, Serializable
```

Opsi untuk mengatur watermark pada dokumen yang dikonversi

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
|  | [WatermarkOptions()](#WatermarkOptions--) | Buat kelas WatermarkOptions dan atur teks watermark |
|
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getWidth()](#getWidth--) | Lebar watermark |
|
|  | [setWidth(int value)](#setWidth-int-) | Lebar watermark |
|
|  | [getHeight()](#getHeight--) | Tinggi watermark |
|
|  | [setHeight(int value)](#setHeight-int-) | Tinggi watermark |
|
|  | [getTop()](#getTop--) | Posisi atas watermark |
|
|  | [setTop(int value)](#setTop-int-) | Posisi atas watermark |
|
|  | [getLeft()](#getLeft--) | Posisi kiri watermark |
|
|  | [setLeft(int value)](#setLeft-int-) | Posisi kiri watermark |
|
|  | [getRotationAngle()](#getRotationAngle--) | Sudut rotasi watermark |
|
|  | [setRotationAngle(int value)](#setRotationAngle-int-) | Sudut rotasi watermark |
|
|  | [getTransparency()](#getTransparency--) | Transparansi watermark. |
|
|  | [setTransparency(double value)](#setTransparency-double-) | Transparansi watermark. |
|
|  | [getBackground()](#getBackground--) | Menunjukkan bahwa watermark ditempatkan sebagai latar belakang. |
|
|  | [setBackground(boolean value)](#setBackground-boolean-) | Menunjukkan bahwa watermark ditempatkan sebagai latar belakang. |
|
| [isAutoAlign()](#isAutoAlign--) |  |
| [setAutoAlign(boolean autoAlign)](#setAutoAlign-boolean-) |  |
|  | [deepClone()](#deepClone--) | Kloning instance saat ini |
|
### WatermarkOptions() {#WatermarkOptions--}
```
public WatermarkOptions()
```


Buat kelas WatermarkOptions dan atur teks watermark


### getWidth() {#getWidth--}
```
public final int getWidth()
```


Lebar watermark


**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Lebar watermark


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Tinggi watermark


**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Tinggi watermark


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### getTop() {#getTop--}
```
public final int getTop()
```


Posisi atas watermark


**Returns:**
int
### setTop(int value) {#setTop-int-}
```
public final void setTop(int value)
```


Posisi atas watermark


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### getLeft() {#getLeft--}
```
public final int getLeft()
```


Posisi kiri watermark


**Returns:**
int
### setLeft(int value) {#setLeft-int-}
```
public final void setLeft(int value)
```


Posisi kiri watermark


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### getRotationAngle() {#getRotationAngle--}
```
public final int getRotationAngle()
```


Sudut rotasi watermark


**Returns:**
int
### setRotationAngle(int value) {#setRotationAngle-int-}
```
public final void setRotationAngle(int value)
```


Sudut rotasi watermark


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | int |  |

### getTransparency() {#getTransparency--}
```
public final double getTransparency()
```


Transparansi watermark. Nilai antara 0 dan 1. Nilai 0 sepenuhnya terlihat, nilai 1 tidak terlihat.


**Returns:**
double
### setTransparency(double value) {#setTransparency-double-}
```
public final void setTransparency(double value)
```


Transparansi watermark. Nilai antara 0 dan 1. Nilai 0 sepenuhnya terlihat, nilai 1 tidak terlihat.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | double |  |

### getBackground() {#getBackground--}
```
public final boolean getBackground()
```


Menunjukkan bahwa watermark ditempatkan sebagai latar belakang. Jika nilai true, watermark diletakkan di bagian bawah. Secara default false dan watermark diletakkan di atas.


**Returns:**
boolean
### setBackground(boolean value) {#setBackground-boolean-}
```
public final void setBackground(boolean value)
```


Menunjukkan bahwa watermark ditempatkan sebagai latar belakang. Jika nilai true, watermark diletakkan di bagian bawah. Secara default false dan watermark diletakkan di atas.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | boolean |  |

### isAutoAlign() {#isAutoAlign--}
```
public boolean isAutoAlign()
```




**Returns:**
boolean
### setAutoAlign(boolean autoAlign) {#setAutoAlign-boolean-}
```
public void setAutoAlign(boolean autoAlign)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| autoAlign | boolean |  |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Kloning instance saat ini


**Returns:**
java.lang.Object - instance

