---
title: "WatermarkOptions"
second_title: "Référence API GroupDocs.Conversion pour Java"
description: "Options pour configurer le filigrane du document converti."
type: docs
weight: 44
url: /fr/java/com.groupdocs.conversion.options.convert/watermarkoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.lang.Cloneable, java.io.Serializable
```
public abstract class WatermarkOptions extends ValueObject implements Cloneable, Serializable
```

Options pour configurer le filigrane du document converti.

## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [WatermarkOptions()](#WatermarkOptions--) | Créer la classe WatermarkOptions et définir le texte du filigrane |
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getWidth()](#getWidth--) | Largeur du filigrane |
|
|  | [setWidth(int value)](#setWidth-int-) | Largeur du filigrane |
|
|  | [getHeight()](#getHeight--) | Hauteur du filigrane |
|
|  | [setHeight(int value)](#setHeight-int-) | Hauteur du filigrane |
|
|  | [getTop()](#getTop--) | Position supérieure du filigrane |
|
|  | [setTop(int value)](#setTop-int-) | Position supérieure du filigrane |
|
|  | [getLeft()](#getLeft--) | Position gauche du filigrane |
|
|  | [setLeft(int value)](#setLeft-int-) | Position gauche du filigrane |
|
|  | [getRotationAngle()](#getRotationAngle--) | Angle de rotation du filigrane |
|
|  | [setRotationAngle(int value)](#setRotationAngle-int-) | Angle de rotation du filigrane |
|
|  | [getTransparency()](#getTransparency--) | Transparence du filigrane. |
|
|  | [setTransparency(double value)](#setTransparency-double-) | Transparence du filigrane. |
|
|  | [getBackground()](#getBackground--) | Indique que le filigrane est appliqué en tant qu'arrière-plan. |
|
|  | [setBackground(boolean value)](#setBackground-boolean-) | Indique que le filigrane est appliqué en tant qu'arrière-plan. |
|
| [isAutoAlign()](#isAutoAlign--) |  |
| [setAutoAlign(boolean autoAlign)](#setAutoAlign-boolean-) |  |
|  | [deepClone()](#deepClone--) | Cloner l'instance actuelle |
|
### WatermarkOptions() {#WatermarkOptions--}
```
public WatermarkOptions()
```


Créer la classe WatermarkOptions et définir le texte du filigrane


### getWidth() {#getWidth--}
```
public final int getWidth()
```


Largeur du filigrane


**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Largeur du filigrane


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Hauteur du filigrane


**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Hauteur du filigrane


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getTop() {#getTop--}
```
public final int getTop()
```


Position supérieure du filigrane


**Returns:**
int
### setTop(int value) {#setTop-int-}
```
public final void setTop(int value)
```


Position supérieure du filigrane


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getLeft() {#getLeft--}
```
public final int getLeft()
```


Position gauche du filigrane


**Returns:**
int
### setLeft(int value) {#setLeft-int-}
```
public final void setLeft(int value)
```


Position gauche du filigrane


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getRotationAngle() {#getRotationAngle--}
```
public final int getRotationAngle()
```


Angle de rotation du filigrane


**Returns:**
int
### setRotationAngle(int value) {#setRotationAngle-int-}
```
public final void setRotationAngle(int value)
```


Angle de rotation du filigrane


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getTransparency() {#getTransparency--}
```
public final double getTransparency()
```


Transparence du filigrane. Valeur comprise entre 0 et 1. La valeur 0 est entièrement visible, la valeur 1 est invisible.


**Returns:**
double
### setTransparency(double value) {#setTransparency-double-}
```
public final void setTransparency(double value)
```


Transparence du filigrane. Valeur comprise entre 0 et 1. La valeur 0 est entièrement visible, la valeur 1 est invisible.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double |  |

### getBackground() {#getBackground--}
```
public final boolean getBackground()
```


Indique que le filigrane est appliqué en tant qu'arrière-plan. Si la valeur est vraie, le filigrane est placé en bas. Par défaut, c'est faux et le filigrane est placé en haut.


**Returns:**
booléen
### setBackground(boolean value) {#setBackground-boolean-}
```
public final void setBackground(boolean value)
```


Indique que le filigrane est appliqué en tant qu'arrière-plan. Si la valeur est vraie, le filigrane est placé en bas. Par défaut, c'est faux et le filigrane est placé en haut.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### isAutoAlign() {#isAutoAlign--}
```
public boolean isAutoAlign()
```




**Returns:**
booléen
### setAutoAlign(boolean autoAlign) {#setAutoAlign-boolean-}
```
public void setAutoAlign(boolean autoAlign)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| autoAlign | booléen |  |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Cloner l'instance actuelle


**Returns:**
java.lang.Object - instance

