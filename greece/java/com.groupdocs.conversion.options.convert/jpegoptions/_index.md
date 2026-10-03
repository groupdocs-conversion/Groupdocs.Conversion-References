---
title: "JpegOptions"
second_title: "GroupDocs.Conversion για Java API Reference"
description: "Επιλογές για μετατροπή σε τύπο αρχείου Jpeg."
type: docs
weight: 20
url: /el/java/com.groupdocs.conversion.options.convert/jpegoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class JpegOptions extends ValueObject implements Serializable
```

Επιλογές για μετατροπή σε τύπο αρχείου Jpeg.

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [JpegOptions()](#JpegOptions--) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [JpegOptions](../../com.groupdocs.conversion.options.convert/jpegoptions). |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getQuality()](#getQuality--) | Επιθυμητή ποιότητα εικόνας. |
|
|  | [setQuality(int value)](#setQuality-int-) | Επιθυμητή ποιότητα εικόνας. |
|
|  | [getColorMode()](#getColorMode--) | Λειτουργία χρώματος Jpg. |
|
|  | [setColorMode(JpgColorModes value)](#setColorMode-com.groupdocs.conversion.options.convert.JpgColorModes-) | Λειτουργία χρώματος Jpg. |
|
|  | [getCompression()](#getCompression--) | Μέθοδος συμπίεσης Jpg. |
|
|  | [setCompression(JpgCompressionMethods value)](#setCompression-com.groupdocs.conversion.options.convert.JpgCompressionMethods-) | Μέθοδος συμπίεσης Jpg. |
|
### JpegOptions() {#JpegOptions--}
```
public JpegOptions()
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [JpegOptions](../../com.groupdocs.conversion.options.convert/jpegoptions).


### getQuality() {#getQuality--}
```
public final int getQuality()
```


Επιθυμητή ποιότητα εικόνας. Η τιμή πρέπει να είναι μεταξύ 0 και 100. Η προεπιλεγμένη τιμή είναι 100.


**Returns:**
int
### setQuality(int value) {#setQuality-int-}
```
public final void setQuality(int value)
```


Επιθυμητή ποιότητα εικόνας. Η τιμή πρέπει να είναι μεταξύ 0 και 100. Η προεπιλεγμένη τιμή είναι 100.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### getColorMode() {#getColorMode--}
```
public final JpgColorModes getColorMode()
```


Λειτουργία χρώματος Jpg.


**Returns:**
[JpgColorModes](../../com.groupdocs.conversion.options.convert/jpgcolormodes)
### setColorMode(JpgColorModes value) {#setColorMode-com.groupdocs.conversion.options.convert.JpgColorModes-}
```
public final void setColorMode(JpgColorModes value)
```


Λειτουργία χρώματος Jpg.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| value | [JpgColorModes](../../com.groupdocs.conversion.options.convert/jpgcolormodes) |  |

### getCompression() {#getCompression--}
```
public final JpgCompressionMethods getCompression()
```


Μέθοδος συμπίεσης Jpg.


**Returns:**
[JpgCompressionMethods](../../com.groupdocs.conversion.options.convert/jpgcompressionmethods)
### setCompression(JpgCompressionMethods value) {#setCompression-com.groupdocs.conversion.options.convert.JpgCompressionMethods-}
```
public final void setCompression(JpgCompressionMethods value)
```


Μέθοδος συμπίεσης Jpg.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| value | [JpgCompressionMethods](../../com.groupdocs.conversion.options.convert/jpgcompressionmethods) |  |

