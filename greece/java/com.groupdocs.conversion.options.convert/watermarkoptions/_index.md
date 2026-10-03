---
title: "WatermarkOptions"
second_title: "GroupDocs.Conversion για Java API Reference"
description: "Επιλογές για ρύθμιση υδατογραφήματος στο μετατρεπόμενο έγγραφο"
type: docs
weight: 44
url: /el/java/com.groupdocs.conversion.options.convert/watermarkoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.lang.Cloneable, java.io.Serializable
```
public abstract class WatermarkOptions extends ValueObject implements Cloneable, Serializable
```

Επιλογές για ρύθμιση υδατογραφήματος στο μετατρεπόμενο έγγραφο

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [WatermarkOptions()](#WatermarkOptions--) | Δημιουργήστε την κλάση WatermarkOptions και ορίστε το κείμενο υδατογραφήματος |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getWidth()](#getWidth--) | Πλάτος υδατογραφήματος |
|
|  | [setWidth(int value)](#setWidth-int-) | Πλάτος υδατογραφήματος |
|
|  | [getHeight()](#getHeight--) | Ύψος υδατογραφήματος |
|
|  | [setHeight(int value)](#setHeight-int-) | Ύψος υδατογραφήματος |
|
|  | [getTop()](#getTop--) | Θέση κορυφής υδατογραφήματος |
|
|  | [setTop(int value)](#setTop-int-) | Θέση κορυφής υδατογραφήματος |
|
|  | [getLeft()](#getLeft--) | Θέση αριστερά υδατογραφήματος |
|
|  | [setLeft(int value)](#setLeft-int-) | Θέση αριστερά υδατογραφήματος |
|
|  | [getRotationAngle()](#getRotationAngle--) | Γωνία περιστροφής υδατογραφήματος |
|
|  | [setRotationAngle(int value)](#setRotationAngle-int-) | Γωνία περιστροφής υδατογραφήματος |
|
|  | [getTransparency()](#getTransparency--) | Διαφάνεια υδατογραφήματος. |
|
|  | [setTransparency(double value)](#setTransparency-double-) | Διαφάνεια υδατογραφήματος. |
|
|  | [getBackground()](#getBackground--) | Δηλώνει ότι το υδατογράφημα είναι σφραγισμένο ως φόντο. |
|
|  | [setBackground(boolean value)](#setBackground-boolean-) | Δηλώνει ότι το υδατογράφημα είναι σφραγισμένο ως φόντο. |
|
| [isAutoAlign()](#isAutoAlign--) |  |
| [setAutoAlign(boolean autoAlign)](#setAutoAlign-boolean-) |  |
|  | [deepClone()](#deepClone--) | Κλωνοποίηση τρέχουσας παρουσίας |
|
### WatermarkOptions() {#WatermarkOptions--}
```
public WatermarkOptions()
```


Δημιουργήστε την κλάση WatermarkOptions και ορίστε το κείμενο υδατογραφήματος


### getWidth() {#getWidth--}
```
public final int getWidth()
```


Πλάτος υδατογραφήματος


**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Πλάτος υδατογραφήματος


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Ύψος υδατογραφήματος


**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Ύψος υδατογραφήματος


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### getTop() {#getTop--}
```
public final int getTop()
```


Θέση κορυφής υδατογραφήματος


**Returns:**
int
### setTop(int value) {#setTop-int-}
```
public final void setTop(int value)
```


Θέση κορυφής υδατογραφήματος


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### getLeft() {#getLeft--}
```
public final int getLeft()
```


Θέση αριστερά υδατογραφήματος


**Returns:**
int
### setLeft(int value) {#setLeft-int-}
```
public final void setLeft(int value)
```


Θέση αριστερά υδατογραφήματος


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### getRotationAngle() {#getRotationAngle--}
```
public final int getRotationAngle()
```


Γωνία περιστροφής υδατογραφήματος


**Returns:**
int
### setRotationAngle(int value) {#setRotationAngle-int-}
```
public final void setRotationAngle(int value)
```


Γωνία περιστροφής υδατογραφήματος


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### getTransparency() {#getTransparency--}
```
public final double getTransparency()
```


Διαφάνεια υδατογραφήματος. Τιμή μεταξύ 0 και 1. Η τιμή 0 είναι πλήρως ορατή, η τιμή 1 είναι αόρατη.


**Returns:**
double
### setTransparency(double value) {#setTransparency-double-}
```
public final void setTransparency(double value)
```


Διαφάνεια υδατογραφήματος. Τιμή μεταξύ 0 και 1. Η τιμή 0 είναι πλήρως ορατή, η τιμή 1 είναι αόρατη.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | double |  |

### getBackground() {#getBackground--}
```
public final boolean getBackground()
```


Δηλώνει ότι το υδατογράφημα είναι σφραγισμένο ως φόντο. Εάν η τιμή είναι true, το υδατογράφημα τοποθετείται στο κάτω μέρος. Από προεπιλογή είναι false και το υδατογράφημα τοποθετείται στην κορυφή.


**Returns:**
boolean
### setBackground(boolean value) {#setBackground-boolean-}
```
public final void setBackground(boolean value)
```


Δηλώνει ότι το υδατογράφημα είναι σφραγισμένο ως φόντο. Εάν η τιμή είναι true, το υδατογράφημα τοποθετείται στο κάτω μέρος. Από προεπιλογή είναι false και το υδατογράφημα τοποθετείται στην κορυφή.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

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
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| autoAlign | boolean |  |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Κλωνοποίηση τρέχουσας παρουσίας


**Returns:**
java.lang.Object - παράδειγμα

