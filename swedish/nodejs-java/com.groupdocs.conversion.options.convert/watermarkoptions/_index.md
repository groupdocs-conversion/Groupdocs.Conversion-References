---
title: "WatermarkOptions"
second_title: "GroupDocs.Conversion för Node.js via Java API-referens"
description: "Alternativ för inställning av vattenstämpel till det konverterade dokumentet"
type: docs
weight: 44
url: /sv/nodejs-java/com.groupdocs.conversion.options.convert/watermarkoptions/
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
| [WatermarkOptions()](#WatermarkOptions--) | Skapa WatermarkOptions-klass och ange vattenmärkningstext |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getWidth()](#getWidth--) | Vattenmärkningens bredd |
| [setWidth(int value)](#setWidth-int-) | Vattenmärkningens bredd |
| [getHeight()](#getHeight--) | Vattenmärkningens höjd |
| [setHeight(int value)](#setHeight-int-) | Vattenmärkningens höjd |
| [getTop()](#getTop--) | Vattenmärkningens övre position |
| [setTop(int value)](#setTop-int-) | Vattenmärkningens övre position |
| [getLeft()](#getLeft--) | Vattenmärkningens vänstra position |
| [setLeft(int value)](#setLeft-int-) | Vattenmärkningens vänstra position |
| [getRotationAngle()](#getRotationAngle--) | Vattenmärkningens rotationsvinkel |
| [setRotationAngle(int value)](#setRotationAngle-int-) | Vattenmärkningens rotationsvinkel |
| [getTransparency()](#getTransparency--) | Vattenmärkningens transparens. |
| [setTransparency(double value)](#setTransparency-double-) | Vattenmärkningens transparens. |
| [getBackground()](#getBackground--) | Indikerar att vattenmärket är stämplat som bakgrund. |
| [setBackground(boolean value)](#setBackground-boolean-) | Indikerar att vattenmärket är stämplat som bakgrund. |
| [isAutoAlign()](#isAutoAlign--) |  |
| [setAutoAlign(boolean autoAlign)](#setAutoAlign-boolean-) |  |
| [deepClone()](#deepClone--) | Klona aktuell instans |
### WatermarkOptions() {#WatermarkOptions--}
```
public WatermarkOptions()
```


Skapa WatermarkOptions-klass och ange vattenmärkningstext

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Vattenmärkningens bredd

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Vattenmärkningens bredd

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Vattenmärkningens höjd

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Vattenmärkningens höjd

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getTop() {#getTop--}
```
public final int getTop()
```


Vattenmärkningens övre position

**Returns:**
int
### setTop(int value) {#setTop-int-}
```
public final void setTop(int value)
```


Vattenmärkningens övre position

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getLeft() {#getLeft--}
```
public final int getLeft()
```


Vattenmärkningens vänstra position

**Returns:**
int
### setLeft(int value) {#setLeft-int-}
```
public final void setLeft(int value)
```


Vattenmärkningens vänstra position

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getRotationAngle() {#getRotationAngle--}
```
public final int getRotationAngle()
```


Vattenmärkningens rotationsvinkel

**Returns:**
int
### setRotationAngle(int value) {#setRotationAngle-int-}
```
public final void setRotationAngle(int value)
```


Vattenmärkningens rotationsvinkel

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getTransparency() {#getTransparency--}
```
public final double getTransparency()
```


Vattenmärkningens transparens. Värde mellan 0 och 1. Värde 0 är fullt synligt, värde 1 är osynligt.

**Returns:**
double
### setTransparency(double value) {#setTransparency-double-}
```
public final void setTransparency(double value)
```


Vattenmärkningens transparens. Värde mellan 0 och 1. Värde 0 är fullt synligt, värde 1 är osynligt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | double |  |

### getBackground() {#getBackground--}
```
public final boolean getBackground()
```


Indikerar att vattenmärket är stämplat som bakgrund. Om värdet är true placeras vattenmärket längst ner. Som standard är false och vattenmärket placeras överst.

**Returns:**
boolean
### setBackground(boolean value) {#setBackground-boolean-}
```
public final void setBackground(boolean value)
```


Indikerar att vattenmärket är stämplat som bakgrund. Om värdet är true placeras vattenmärket längst ner. Som standard är false och vattenmärket placeras överst.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

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
