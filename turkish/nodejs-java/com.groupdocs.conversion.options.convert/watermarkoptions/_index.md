---
title: "WatermarkOptions"
second_title: "Node.js için GroupDocs.Conversion, Java üzerinden API Referansı"
description: "Dönüştürülen belgeye filigran ayarları için seçenekler"
type: docs
weight: 44
url: /tr/nodejs-java/com.groupdocs.conversion.options.convert/watermarkoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.lang.Cloneable, java.io.Serializable
```
public abstract class WatermarkOptions extends ValueObject implements Cloneable, Serializable
```

Dönüştürülen belgeye filigran ayarları için seçenekler
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [WatermarkOptions()](#WatermarkOptions--) | WatermarkOptions sınıfını oluştur ve filigran metnini ayarla |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getWidth()](#getWidth--) | Filigran genişliği |
| [setWidth(int value)](#setWidth-int-) | Filigran genişliği |
| [getHeight()](#getHeight--) | Filigran yüksekliği |
| [setHeight(int value)](#setHeight-int-) | Filigran yüksekliği |
| [getTop()](#getTop--) | Filigran üst konumu |
| [setTop(int value)](#setTop-int-) | Filigran üst konumu |
| [getLeft()](#getLeft--) | Filigran sol konumu |
| [setLeft(int value)](#setLeft-int-) | Filigran sol konumu |
| [getRotationAngle()](#getRotationAngle--) | Filigran döndürme açısı |
| [setRotationAngle(int value)](#setRotationAngle-int-) | Filigran döndürme açısı |
| [getTransparency()](#getTransparency--) | Filigran şeffaflığı. |
| [setTransparency(double value)](#setTransparency-double-) | Filigran şeffaflığı. |
| [getBackground()](#getBackground--) | Filigranın arka plan olarak damgalandığını gösterir. |
| [setBackground(boolean value)](#setBackground-boolean-) | Filigranın arka plan olarak damgalandığını gösterir. |
| [isAutoAlign()](#isAutoAlign--) |  |
| [setAutoAlign(boolean autoAlign)](#setAutoAlign-boolean-) |  |
| [deepClone()](#deepClone--) | Mevcut örneği klonla |
### WatermarkOptions() {#WatermarkOptions--}
```
public WatermarkOptions()
```


WatermarkOptions sınıfını oluştur ve filigran metnini ayarla

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Filigran genişliği

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Filigran genişliği

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Filigran yüksekliği

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Filigran yüksekliği

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getTop() {#getTop--}
```
public final int getTop()
```


Filigran üst konumu

**Returns:**
int
### setTop(int value) {#setTop-int-}
```
public final void setTop(int value)
```


Filigran üst konumu

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getLeft() {#getLeft--}
```
public final int getLeft()
```


Filigran sol konumu

**Returns:**
int
### setLeft(int value) {#setLeft-int-}
```
public final void setLeft(int value)
```


Filigran sol konumu

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getRotationAngle() {#getRotationAngle--}
```
public final int getRotationAngle()
```


Filigran döndürme açısı

**Returns:**
int
### setRotationAngle(int value) {#setRotationAngle-int-}
```
public final void setRotationAngle(int value)
```


Filigran döndürme açısı

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getTransparency() {#getTransparency--}
```
public final double getTransparency()
```


Filigran şeffaflığı. Değer 0 ile 1 arasındadır. Değer 0 tamamen görünür, değer 1 ise görünmez.

**Returns:**
double
### setTransparency(double value) {#setTransparency-double-}
```
public final void setTransparency(double value)
```


Filigran şeffaflığı. Değer 0 ile 1 arasındadır. Değer 0 tamamen görünür, değer 1 ise görünmez.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double |  |

### getBackground() {#getBackground--}
```
public final boolean getBackground()
```


Filigranın arka plan olarak damgalandığını gösterir. Değer true ise, filigran altta yer alır. Varsayılan olarak false ve filigran üstte yer alır.

**Returns:**
boolean
### setBackground(boolean value) {#setBackground-boolean-}
```
public final void setBackground(boolean value)
```


Filigranın arka plan olarak damgalandığını gösterir. Değer true ise, filigran altta yer alır. Varsayılan olarak false ve filigran üstte yer alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| autoAlign | boolean |  |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Mevcut örneği klonla

**Returns:**
java.lang.Object - örnek
