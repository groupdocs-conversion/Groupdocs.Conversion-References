---
title: "WatermarkOptions"
second_title: "GroupDocs.Conversion för Java API-referens"
description: "Alternativ för inställning av vattenstämpel till det konverterade dokumentet"
type: docs
weight: 44
url: /sv/java/com.groupdocs.conversion.options.convert/watermarkoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.lang.Cloneable, java.io.Serializable
```
public abstract class WatermarkOptions extends ValueObject implements Cloneable, Serializable
```

Alternativ för inställning av vattenstämpel till det konverterade dokumentet

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
|  | [WatermarkOptions()](#WatermarkOptions--) | Skapa WatermarkOptions-klassen och ange vattenstämpeltext |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getWidth()](#getWidth--) | Vattenstämpelbredd |
|
|  | [setWidth(int value)](#setWidth-int-) | Vattenstämpelbredd |
|
|  | [getHeight()](#getHeight--) | Vattenstämpelhöjd |
|
|  | [setHeight(int value)](#setHeight-int-) | Vattenstämpelhöjd |
|
|  | [getTop()](#getTop--) | Vattenstämpelns övre position |
|
|  | [setTop(int value)](#setTop-int-) | Vattenstämpelns övre position |
|
|  | [getLeft()](#getLeft--) | Vattenstämpelns vänstra position |
|
|  | [setLeft(int value)](#setLeft-int-) | Vattenstämpelns vänstra position |
|
|  | [getRotationAngle()](#getRotationAngle--) | Vattenstämpelns rotationsvinkel |
|
|  | [setRotationAngle(int value)](#setRotationAngle-int-) | Vattenstämpelns rotationsvinkel |
|
|  | [getTransparency()](#getTransparency--) | Vattenstämpelns transparens. |
|
|  | [setTransparency(double value)](#setTransparency-double-) | Vattenstämpelns transparens. |
|
|  | [getBackground()](#getBackground--) | Indikerar att vattenstämpeln är stämplad som bakgrund. |
|
|  | [setBackground(boolean value)](#setBackground-boolean-) | Indikerar att vattenstämpeln är stämplad som bakgrund. |
|
| [isAutoAlign()](#isAutoAlign--) |  |
| [setAutoAlign(boolean autoAlign)](#setAutoAlign-boolean-) |  |
|  | [deepClone()](#deepClone--) | Klona aktuell instans |
|
### WatermarkOptions() {#WatermarkOptions--}
```
public WatermarkOptions()
```


Skapa WatermarkOptions-klassen och ange vattenstämpeltext


### getWidth() {#getWidth--}
```
public final int getWidth()
```


Vattenstämpelbredd


**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Vattenstämpelbredd


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Vattenstämpelhöjd


**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Vattenstämpelhöjd


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getTop() {#getTop--}
```
public final int getTop()
```


Vattenstämpelns övre position


**Returns:**
int
### setTop(int value) {#setTop-int-}
```
public final void setTop(int value)
```


Vattenstämpelns övre position


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getLeft() {#getLeft--}
```
public final int getLeft()
```


Vattenstämpelns vänstra position


**Returns:**
int
### setLeft(int value) {#setLeft-int-}
```
public final void setLeft(int value)
```


Vattenstämpelns vänstra position


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getRotationAngle() {#getRotationAngle--}
```
public final int getRotationAngle()
```


Vattenstämpelns rotationsvinkel


**Returns:**
int
### setRotationAngle(int value) {#setRotationAngle-int-}
```
public final void setRotationAngle(int value)
```


Vattenstämpelns rotationsvinkel


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getTransparency() {#getTransparency--}
```
public final double getTransparency()
```


Vattenstämpelns transparens. Värde mellan 0 och 1. Värde 0 är helt synligt, värde 1 är osynligt.


**Returns:**
double
### setTransparency(double value) {#setTransparency-double-}
```
public final void setTransparency(double value)
```


Vattenstämpelns transparens. Värde mellan 0 och 1. Värde 0 är helt synligt, värde 1 är osynligt.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double |  |

### getBackground() {#getBackground--}
```
public final boolean getBackground()
```


Indikerar att vattenstämpeln är stämplad som bakgrund. Om värdet är sant läggs vattenstämpeln längst ner. Som standard är falskt och vattenstämpeln läggs överst.


**Returns:**
boolean
### setBackground(boolean value) {#setBackground-boolean-}
```
public final void setBackground(boolean value)
```


Indikerar att vattenstämpeln är stämplad som bakgrund. Om värdet är sant läggs vattenstämpeln längst ner. Som standard är falskt och vattenstämpeln läggs överst.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| autoAlign | boolean |  |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Klona aktuell instans


**Returns:**
java.lang.Object - instans

