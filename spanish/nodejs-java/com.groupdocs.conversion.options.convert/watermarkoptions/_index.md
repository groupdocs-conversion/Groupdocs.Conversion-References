---
title: "WatermarkOptions"
second_title: "Referencia de API de GroupDocs.Conversion para Node.js vía Java"
description: "Opciones para configurar la marca de agua en el documento convertido"
type: docs
weight: 44
url: /es/nodejs-java/com.groupdocs.conversion.options.convert/watermarkoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.lang.Cloneable, java.io.Serializable
```
public abstract class WatermarkOptions extends ValueObject implements Cloneable, Serializable
```

Opciones para configurar la marca de agua en el documento convertido
## Constructores

| Constructor | Descripción |
| --- | --- |
| [WatermarkOptions()](#WatermarkOptions--) | Crear la clase WatermarkOptions y establecer el texto de la marca de agua |
## Métodos

| Método | Descripción |
| --- | --- |
| [getWidth()](#getWidth--) | Ancho de la marca de agua |
| [setWidth(int value)](#setWidth-int-) | Ancho de la marca de agua |
| [getHeight()](#getHeight--) | Altura de la marca de agua |
| [setHeight(int value)](#setHeight-int-) | Altura de la marca de agua |
| [getTop()](#getTop--) | Posición superior de la marca de agua |
| [setTop(int value)](#setTop-int-) | Posición superior de la marca de agua |
| [getLeft()](#getLeft--) | Posición izquierda de la marca de agua |
| [setLeft(int value)](#setLeft-int-) | Posición izquierda de la marca de agua |
| [getRotationAngle()](#getRotationAngle--) | Ángulo de rotación de la marca de agua |
| [setRotationAngle(int value)](#setRotationAngle-int-) | Ángulo de rotación de la marca de agua |
| [getTransparency()](#getTransparency--) | Transparencia de la marca de agua. |
| [setTransparency(double value)](#setTransparency-double-) | Transparencia de la marca de agua. |
| [getBackground()](#getBackground--) | Indica que la marca de agua se sella como fondo. |
| [setBackground(boolean value)](#setBackground-boolean-) | Indica que la marca de agua se sella como fondo. |
| [isAutoAlign()](#isAutoAlign--) |  |
| [setAutoAlign(boolean autoAlign)](#setAutoAlign-boolean-) |  |
| [deepClone()](#deepClone--) | Clonar la instancia actual |
### WatermarkOptions() {#WatermarkOptions--}
```
public WatermarkOptions()
```


Crear la clase WatermarkOptions y establecer el texto de la marca de agua

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Ancho de la marca de agua

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Ancho de la marca de agua

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Altura de la marca de agua

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Altura de la marca de agua

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getTop() {#getTop--}
```
public final int getTop()
```


Posición superior de la marca de agua

**Returns:**
int
### setTop(int value) {#setTop-int-}
```
public final void setTop(int value)
```


Posición superior de la marca de agua

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getLeft() {#getLeft--}
```
public final int getLeft()
```


Posición izquierda de la marca de agua

**Returns:**
int
### setLeft(int value) {#setLeft-int-}
```
public final void setLeft(int value)
```


Posición izquierda de la marca de agua

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getRotationAngle() {#getRotationAngle--}
```
public final int getRotationAngle()
```


Ángulo de rotación de la marca de agua

**Returns:**
int
### setRotationAngle(int value) {#setRotationAngle-int-}
```
public final void setRotationAngle(int value)
```


Ángulo de rotación de la marca de agua

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getTransparency() {#getTransparency--}
```
public final double getTransparency()
```


Transparencia de la marca de agua. Valor entre 0 y 1. El valor 0 es totalmente visible, el valor 1 es invisible.

**Returns:**
double
### setTransparency(double value) {#setTransparency-double-}
```
public final void setTransparency(double value)
```


Transparencia de la marca de agua. Valor entre 0 y 1. El valor 0 es totalmente visible, el valor 1 es invisible.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double |  |

### getBackground() {#getBackground--}
```
public final boolean getBackground()
```


Indica que la marca de agua se sella como fondo. Si el valor es true, la marca de agua se coloca en la parte inferior. Por defecto es false y la marca de agua se coloca en la parte superior.

**Returns:**
boolean
### setBackground(boolean value) {#setBackground-boolean-}
```
public final void setBackground(boolean value)
```


Indica que la marca de agua se sella como fondo. Si el valor es true, la marca de agua se coloca en la parte inferior. Por defecto es false y la marca de agua se coloca en la parte superior.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| autoAlign | boolean |  |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Clonar la instancia actual

**Returns:**
java.lang.Object - instancia
