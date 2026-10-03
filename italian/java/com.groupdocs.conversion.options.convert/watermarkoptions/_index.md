---
title: "WatermarkOptions"
second_title: "Riferimento API di GroupDocs.Conversion per Java"
description: "Opzioni per impostare la filigrana al documento convertito"
type: docs
weight: 44
url: /it/java/com.groupdocs.conversion.options.convert/watermarkoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.lang.Cloneable, java.io.Serializable
```
public abstract class WatermarkOptions extends ValueObject implements Cloneable, Serializable
```

Opzioni per impostare la filigrana al documento convertito

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [WatermarkOptions()](#WatermarkOptions--) | Crea la classe WatermarkOptions e imposta il testo della filigrana |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getWidth()](#getWidth--) | Larghezza filigrana |
|
|  | [setWidth(int value)](#setWidth-int-) | Larghezza filigrana |
|
|  | [getHeight()](#getHeight--) | Altezza filigrana |
|
|  | [setHeight(int value)](#setHeight-int-) | Altezza filigrana |
|
|  | [getTop()](#getTop--) | Posizione superiore della filigrana |
|
|  | [setTop(int value)](#setTop-int-) | Posizione superiore della filigrana |
|
|  | [getLeft()](#getLeft--) | Posizione sinistra della filigrana |
|
|  | [setLeft(int value)](#setLeft-int-) | Posizione sinistra della filigrana |
|
|  | [getRotationAngle()](#getRotationAngle--) | Angolo di rotazione della filigrana |
|
|  | [setRotationAngle(int value)](#setRotationAngle-int-) | Angolo di rotazione della filigrana |
|
|  | [getTransparency()](#getTransparency--) | Trasparenza della filigrana. |
|
|  | [setTransparency(double value)](#setTransparency-double-) | Trasparenza della filigrana. |
|
|  | [getBackground()](#getBackground--) | Indica che la filigrana è applicata come sfondo. |
|
|  | [setBackground(boolean value)](#setBackground-boolean-) | Indica che la filigrana è applicata come sfondo. |
|
| [isAutoAlign()](#isAutoAlign--) |  |
| [setAutoAlign(boolean autoAlign)](#setAutoAlign-boolean-) |  |
|  | [deepClone()](#deepClone--) | Clona l'istanza corrente |
|
### WatermarkOptions() {#WatermarkOptions--}
```
public WatermarkOptions()
```


Crea la classe WatermarkOptions e imposta il testo della filigrana


### getWidth() {#getWidth--}
```
public final int getWidth()
```


Larghezza filigrana


**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Larghezza filigrana


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Altezza filigrana


**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Altezza filigrana


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getTop() {#getTop--}
```
public final int getTop()
```


Posizione superiore della filigrana


**Returns:**
int
### setTop(int value) {#setTop-int-}
```
public final void setTop(int value)
```


Posizione superiore della filigrana


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getLeft() {#getLeft--}
```
public final int getLeft()
```


Posizione sinistra della filigrana


**Returns:**
int
### setLeft(int value) {#setLeft-int-}
```
public final void setLeft(int value)
```


Posizione sinistra della filigrana


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getRotationAngle() {#getRotationAngle--}
```
public final int getRotationAngle()
```


Angolo di rotazione della filigrana


**Returns:**
int
### setRotationAngle(int value) {#setRotationAngle-int-}
```
public final void setRotationAngle(int value)
```


Angolo di rotazione della filigrana


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getTransparency() {#getTransparency--}
```
public final double getTransparency()
```


Trasparenza della filigrana. Valore compreso tra 0 e 1. Il valore 0 è completamente visibile, il valore 1 è invisibile.


**Returns:**
double
### setTransparency(double value) {#setTransparency-double-}
```
public final void setTransparency(double value)
```


Trasparenza della filigrana. Valore compreso tra 0 e 1. Il valore 0 è completamente visibile, il valore 1 è invisibile.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double |  |

### getBackground() {#getBackground--}
```
public final boolean getBackground()
```


Indica che la filigrana è applicata come sfondo. Se il valore è true, la filigrana è posizionata in basso. Per impostazione predefinita è false e la filigrana è posizionata in alto.


**Returns:**
booleano
### setBackground(boolean value) {#setBackground-boolean-}
```
public final void setBackground(boolean value)
```


Indica che la filigrana è applicata come sfondo. Se il valore è true, la filigrana è posizionata in basso. Per impostazione predefinita è false e la filigrana è posizionata in alto.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | booleano |  |

### isAutoAlign() {#isAutoAlign--}
```
public boolean isAutoAlign()
```




**Returns:**
booleano
### setAutoAlign(boolean autoAlign) {#setAutoAlign-boolean-}
```
public void setAutoAlign(boolean autoAlign)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| autoAlign | booleano |  |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Clona l'istanza corrente


**Returns:**
java.lang.Object - istanza

