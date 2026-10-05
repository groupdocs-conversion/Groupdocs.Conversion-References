---
title: "WatermarkOptions"
second_title: "Справочник API GroupDocs.Conversion для Node.js через Java"
description: "Параметры настройки водяного знака для конвертированного документа"
type: docs
weight: 44
url: /ru/nodejs-java/com.groupdocs.conversion.options.convert/watermarkoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.lang.Cloneable, java.io.Serializable
```
public abstract class WatermarkOptions extends ValueObject implements Cloneable, Serializable
```

Параметры настройки водяного знака для конвертированного документа
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [WatermarkOptions()](#WatermarkOptions--) | Создайте класс WatermarkOptions и задайте текст водяного знака |
## Методы

| Метод | Описание |
| --- | --- |
| [getWidth()](#getWidth--) | Ширина водяного знака |
| [setWidth(int value)](#setWidth-int-) | Ширина водяного знака |
| [getHeight()](#getHeight--) | Высота водяного знака |
| [setHeight(int value)](#setHeight-int-) | Высота водяного знака |
| [getTop()](#getTop--) | Позиция водяного знака по вертикали (верх) |
| [setTop(int value)](#setTop-int-) | Позиция водяного знака по вертикали (верх) |
| [getLeft()](#getLeft--) | Позиция водяного знака по горизонтали (лево) |
| [setLeft(int value)](#setLeft-int-) | Позиция водяного знака по горизонтали (лево) |
| [getRotationAngle()](#getRotationAngle--) | Угол поворота водяного знака |
| [setRotationAngle(int value)](#setRotationAngle-int-) | Угол поворота водяного знака |
| [getTransparency()](#getTransparency--) | Прозрачность водяного знака. |
| [setTransparency(double value)](#setTransparency-double-) | Прозрачность водяного знака. |
| [getBackground()](#getBackground--) | Указывает, что водяной знак наносится как фон. |
| [setBackground(boolean value)](#setBackground-boolean-) | Указывает, что водяной знак наносится как фон. |
| [isAutoAlign()](#isAutoAlign--) |  |
| [setAutoAlign(boolean autoAlign)](#setAutoAlign-boolean-) |  |
| [deepClone()](#deepClone--) | Клонировать текущий экземпляр |
### WatermarkOptions() {#WatermarkOptions--}
```
public WatermarkOptions()
```


Создайте класс WatermarkOptions и задайте текст водяного знака

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Ширина водяного знака

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Ширина водяного знака

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Высота водяного знака

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Высота водяного знака

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### getTop() {#getTop--}
```
public final int getTop()
```


Позиция водяного знака по вертикали (верх)

**Returns:**
int
### setTop(int value) {#setTop-int-}
```
public final void setTop(int value)
```


Позиция водяного знака по вертикали (верх)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### getLeft() {#getLeft--}
```
public final int getLeft()
```


Позиция водяного знака по горизонтали (лево)

**Returns:**
int
### setLeft(int value) {#setLeft-int-}
```
public final void setLeft(int value)
```


Позиция водяного знака по горизонтали (лево)

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### getRotationAngle() {#getRotationAngle--}
```
public final int getRotationAngle()
```


Угол поворота водяного знака

**Returns:**
int
### setRotationAngle(int value) {#setRotationAngle-int-}
```
public final void setRotationAngle(int value)
```


Угол поворота водяного знака

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### getTransparency() {#getTransparency--}
```
public final double getTransparency()
```


Прозрачность водяного знака. Значение от 0 до 1. Значение 0 — полностью видимый, значение 1 — невидимый.

**Returns:**
double
### setTransparency(double value) {#setTransparency-double-}
```
public final void setTransparency(double value)
```


Прозрачность водяного знака. Значение от 0 до 1. Значение 0 — полностью видимый, значение 1 — невидимый.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | double |  |

### getBackground() {#getBackground--}
```
public final boolean getBackground()
```


Указывает, что водяной знак наносится как фон. Если значение true, водяной знак размещается внизу. По умолчанию false, и водяной знак размещается сверху.

**Returns:**
boolean
### setBackground(boolean value) {#setBackground-boolean-}
```
public final void setBackground(boolean value)
```


Указывает, что водяной знак наносится как фон. Если значение true, водяной знак размещается внизу. По умолчанию false, и водяной знак размещается сверху.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

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
| Параметр | Тип | Описание |
| --- | --- | --- |
| autoAlign | boolean |  |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Клонировать текущий экземпляр

**Returns:**
java.lang.Object — экземпляр
