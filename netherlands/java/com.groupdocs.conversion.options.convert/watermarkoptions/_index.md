---
title: "WatermarkOptions"
second_title: "GroupDocs.Conversion voor Java API-referentie"
description: "Opties voor het instellen van een watermerk op het geconverteerde document."
type: docs
weight: 44
url: /nl/java/com.groupdocs.conversion.options.convert/watermarkoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.lang.Cloneable, java.io.Serializable
```
public abstract class WatermarkOptions extends ValueObject implements Cloneable, Serializable
```

Opties voor het instellen van een watermerk op het geconverteerde document.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [WatermarkOptions()](#WatermarkOptions--) | Maak de WatermarkOptions-klasse aan en stel de watermerktekst in |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getWidth()](#getWidth--) | Watermark breedte |
|
|  | [setWidth(int value)](#setWidth-int-) | Watermark breedte |
|
|  | [getHeight()](#getHeight--) | Watermark hoogte |
|
|  | [setHeight(int value)](#setHeight-int-) | Watermark hoogte |
|
|  | [getTop()](#getTop--) | Watermark bovenpositie |
|
|  | [setTop(int value)](#setTop-int-) | Watermark bovenpositie |
|
|  | [getLeft()](#getLeft--) | Watermark linkerpositie |
|
|  | [setLeft(int value)](#setLeft-int-) | Watermark linkerpositie |
|
|  | [getRotationAngle()](#getRotationAngle--) | Watermark rotatiehoek |
|
|  | [setRotationAngle(int value)](#setRotationAngle-int-) | Watermark rotatiehoek |
|
|  | [getTransparency()](#getTransparency--) | Watermerktransparantie. |
|
|  | [setTransparency(double value)](#setTransparency-double-) | Watermerktransparantie. |
|
|  | [getBackground()](#getBackground--) | Geeft aan dat het watermerk als achtergrond is gestempeld. |
|
|  | [setBackground(boolean value)](#setBackground-boolean-) | Geeft aan dat het watermerk als achtergrond is gestempeld. |
|
| [isAutoAlign()](#isAutoAlign--) |  |
| [setAutoAlign(boolean autoAlign)](#setAutoAlign-boolean-) |  |
|  | [deepClone()](#deepClone--) | Kloon huidige instantie |
|
### WatermarkOptions() {#WatermarkOptions--}
```
public WatermarkOptions()
```


Maak de WatermarkOptions-klasse aan en stel de watermerktekst in


### getWidth() {#getWidth--}
```
public final int getWidth()
```


Watermark breedte


**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Watermark breedte


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Watermark hoogte


**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Watermark hoogte


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### getTop() {#getTop--}
```
public final int getTop()
```


Watermark bovenpositie


**Returns:**
int
### setTop(int value) {#setTop-int-}
```
public final void setTop(int value)
```


Watermark bovenpositie


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### getLeft() {#getLeft--}
```
public final int getLeft()
```


Watermark linkerpositie


**Returns:**
int
### setLeft(int value) {#setLeft-int-}
```
public final void setLeft(int value)
```


Watermark linkerpositie


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### getRotationAngle() {#getRotationAngle--}
```
public final int getRotationAngle()
```


Watermark rotatiehoek


**Returns:**
int
### setRotationAngle(int value) {#setRotationAngle-int-}
```
public final void setRotationAngle(int value)
```


Watermark rotatiehoek


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### getTransparency() {#getTransparency--}
```
public final double getTransparency()
```


Watermerktransparantie. Waarde tussen 0 en 1. Waarde 0 is volledig zichtbaar, waarde 1 is onzichtbaar.


**Returns:**
double
### setTransparency(double value) {#setTransparency-double-}
```
public final void setTransparency(double value)
```


Watermerktransparantie. Waarde tussen 0 en 1. Waarde 0 is volledig zichtbaar, waarde 1 is onzichtbaar.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double |  |

### getBackground() {#getBackground--}
```
public final boolean getBackground()
```


Geeft aan dat het watermerk als achtergrond is gestempeld. Als de waarde true is, wordt het watermerk onderaan geplaatst. Standaard is false en wordt het watermerk bovenaan geplaatst.


**Returns:**
boolean
### setBackground(boolean value) {#setBackground-boolean-}
```
public final void setBackground(boolean value)
```


Geeft aan dat het watermerk als achtergrond is gestempeld. Als de waarde true is, wordt het watermerk onderaan geplaatst. Standaard is false en wordt het watermerk bovenaan geplaatst.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean |  |

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| autoAlign | boolean |  |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Kloon huidige instantie


**Returns:**
java.lang.Object - instance

