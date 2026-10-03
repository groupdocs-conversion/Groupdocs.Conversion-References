---
title: "WatermarkOptions"
second_title: "GroupDocs.Conversion für Java API-Referenz"
description: "Optionen für das Festlegen eines Wasserzeichens für das konvertierte Dokument"
type: docs
weight: 44
url: /de/java/com.groupdocs.conversion.options.convert/watermarkoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.lang.Cloneable, java.io.Serializable
```
public abstract class WatermarkOptions extends ValueObject implements Cloneable, Serializable
```

Optionen für das Festlegen eines Wasserzeichens für das konvertierte Dokument

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [WatermarkOptions()](#WatermarkOptions--) | Erstellen Sie die Klasse WatermarkOptions und setzen Sie den Wasserzeichen‑Text. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getWidth()](#getWidth--) | Wasserzeichenbreite |
|
|  | [setWidth(int value)](#setWidth-int-) | Wasserzeichenbreite |
|
|  | [getHeight()](#getHeight--) | Wasserzeichenhöhe |
|
|  | [setHeight(int value)](#setHeight-int-) | Wasserzeichenhöhe |
|
|  | [getTop()](#getTop--) | Obere Position des Wasserzeichens |
|
|  | [setTop(int value)](#setTop-int-) | Obere Position des Wasserzeichens |
|
|  | [getLeft()](#getLeft--) | Linke Position des Wasserzeichens |
|
|  | [setLeft(int value)](#setLeft-int-) | Linke Position des Wasserzeichens |
|
|  | [getRotationAngle()](#getRotationAngle--) | Drehwinkel des Wasserzeichens |
|
|  | [setRotationAngle(int value)](#setRotationAngle-int-) | Drehwinkel des Wasserzeichens |
|
|  | [getTransparency()](#getTransparency--) | Transparenz des Wasserzeichens. |
|
|  | [setTransparency(double value)](#setTransparency-double-) | Transparenz des Wasserzeichens. |
|
|  | [getBackground()](#getBackground--) | Gibt an, dass das Wasserzeichen als Hintergrund gestempelt wird. |
|
|  | [setBackground(boolean value)](#setBackground-boolean-) | Gibt an, dass das Wasserzeichen als Hintergrund gestempelt wird. |
|
| [isAutoAlign()](#isAutoAlign--) |  |
| [setAutoAlign(boolean autoAlign)](#setAutoAlign-boolean-) |  |
|  | [deepClone()](#deepClone--) | Aktuelle Instanz klonen |
|
### WatermarkOptions() {#WatermarkOptions--}
```
public WatermarkOptions()
```


Erstellen Sie die Klasse WatermarkOptions und setzen Sie den Wasserzeichen‑Text.


### getWidth() {#getWidth--}
```
public final int getWidth()
```


Wasserzeichenbreite


**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Wasserzeichenbreite


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Wasserzeichenhöhe


**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Wasserzeichenhöhe


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getTop() {#getTop--}
```
public final int getTop()
```


Obere Position des Wasserzeichens


**Returns:**
int
### setTop(int value) {#setTop-int-}
```
public final void setTop(int value)
```


Obere Position des Wasserzeichens


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getLeft() {#getLeft--}
```
public final int getLeft()
```


Linke Position des Wasserzeichens


**Returns:**
int
### setLeft(int value) {#setLeft-int-}
```
public final void setLeft(int value)
```


Linke Position des Wasserzeichens


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getRotationAngle() {#getRotationAngle--}
```
public final int getRotationAngle()
```


Drehwinkel des Wasserzeichens


**Returns:**
int
### setRotationAngle(int value) {#setRotationAngle-int-}
```
public final void setRotationAngle(int value)
```


Drehwinkel des Wasserzeichens


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getTransparency() {#getTransparency--}
```
public final double getTransparency()
```


Transparenz des Wasserzeichens. Wert zwischen 0 und 1. Wert 0 ist vollständig sichtbar, Wert 1 ist unsichtbar.


**Returns:**
double
### setTransparency(double value) {#setTransparency-double-}
```
public final void setTransparency(double value)
```


Transparenz des Wasserzeichens. Wert zwischen 0 und 1. Wert 0 ist vollständig sichtbar, Wert 1 ist unsichtbar.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | double |  |

### getBackground() {#getBackground--}
```
public final boolean getBackground()
```


Gibt an, dass das Wasserzeichen als Hintergrund gestempelt wird. Wenn der Wert true ist, wird das Wasserzeichen unten platziert. Standardmäßig ist false und das Wasserzeichen wird oben platziert.


**Returns:**
boolean
### setBackground(boolean value) {#setBackground-boolean-}
```
public final void setBackground(boolean value)
```


Gibt an, dass das Wasserzeichen als Hintergrund gestempelt wird. Wenn der Wert true ist, wird das Wasserzeichen unten platziert. Standardmäßig ist false und das Wasserzeichen wird oben platziert.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| autoAlign | boolean |  |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Aktuelle Instanz klonen


**Returns:**
java.lang.Object - Instanz

