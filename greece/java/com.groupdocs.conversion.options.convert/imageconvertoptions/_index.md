---
title: "ImageConvertOptions"
second_title: "GroupDocs.Conversion για Java API Reference"
description: "Επιλογές για μετατροπή σε τύπο αρχείου Image."
type: docs
weight: 18
url: /el/java/com.groupdocs.conversion.options.convert/imageconvertoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), com.groupdocs.conversion.options.convert.ConvertOptions, com.groupdocs.conversion.options.convert.CommonConvertOptions

**All Implemented Interfaces:**
java.io.Serializable
```
public final class ImageConvertOptions extends CommonConvertOptions<ImageFileType> implements Serializable
```

Επιλογές για μετατροπή σε τύπο αρχείου Image.

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [ImageConvertOptions()](#ImageConvertOptions--) | Αρχικοποιεί μια νέα παρουσία της κλάσης [ImageConvertOptions](../../com.groupdocs.conversion.options.convert/imageconvertoptions). |
|
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| [DEFAULT_DPI](#DEFAULT-DPI) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getWidth()](#getWidth--) | Επιθυμητό πλάτος εικόνας μετά τη μετατροπή. |
|
|  | [setWidth(int value)](#setWidth-int-) | Επιθυμητό πλάτος εικόνας μετά τη μετατροπή. |
|
|  | [getHeight()](#getHeight--) | Επιθυμητό ύψος εικόνας μετά τη μετατροπή. |
|
|  | [setHeight(int value)](#setHeight-int-) | Επιθυμητό ύψος εικόνας μετά τη μετατροπή. |
|
|  | [getUsePdf()](#getUsePdf--) | Αν |
true
, η είσοδος πρώτα μετατρέπεται σε PDF και μετά στο επιθυμητό μορφότυπο.
|
|  | [setUsePdf(boolean value)](#setUsePdf-boolean-) | Αν |
true
, η είσοδος πρώτα μετατρέπεται σε PDF και μετά στο επιθυμητό μορφότυπο.
|
|  | [getHorizontalResolution()](#getHorizontalResolution--) | Επιθυμητή οριζόντια ανάλυση εικόνας μετά τη μετατροπή. |
|
|  | [setHorizontalResolution(int value)](#setHorizontalResolution-int-) | Επιθυμητή οριζόντια ανάλυση εικόνας μετά τη μετατροπή. |
|
|  | [getVerticalResolution()](#getVerticalResolution--) | Επιθυμητή κάθετη ανάλυση εικόνας μετά τη μετατροπή. |
|
|  | [setVerticalResolution(int value)](#setVerticalResolution-int-) | Επιθυμητή κάθετη ανάλυση εικόνας μετά τη μετατροπή. |
|
|  | [getTiffOptions()](#getTiffOptions--) | Ειδικές επιλογές μετατροπής για Tiff. |
|
|  | [setTiffOptions(TiffOptions value)](#setTiffOptions-com.groupdocs.conversion.options.convert.TiffOptions-) | Ειδικές επιλογές μετατροπής για Tiff. |
|
|  | [getPsdOptions()](#getPsdOptions--) | Ειδικές επιλογές μετατροπής για Psd. |
|
|  | [setPsdOptions(PsdOptions value)](#setPsdOptions-com.groupdocs.conversion.options.convert.PsdOptions-) | Ειδικές επιλογές μετατροπής για Psd. |
|
|  | [getWebpOptions()](#getWebpOptions--) | Ειδικές επιλογές μετατροπής για Webp. |
|
|  | [setWebpOptions(WebpOptions value)](#setWebpOptions-com.groupdocs.conversion.options.convert.WebpOptions-) | Ειδικές επιλογές μετατροπής για Webp. |
|
|  | [getGrayscale()](#getGrayscale--) | Δείχνει αν θα μετατραπεί σε εικόνα σε κλίμακα του γκρι. |
|
|  | [setGrayscale(boolean value)](#setGrayscale-boolean-) | Δείχνει αν θα μετατραπεί σε εικόνα σε κλίμακα του γκρι. |
|
|  | [getRotateAngle()](#getRotateAngle--) | Γωνία περιστροφής εικόνας. |
|
|  | [setRotateAngle(int value)](#setRotateAngle-int-) | Γωνία περιστροφής εικόνας. |
|
|  | [getJpegOptions()](#getJpegOptions--) | Ειδικές επιλογές μετατροπής για Jpeg. |
|
|  | [setJpegOptions(JpegOptions value)](#setJpegOptions-com.groupdocs.conversion.options.convert.JpegOptions-) | Ειδικές επιλογές μετατροπής για Jpeg. |
|
|  | [getFlipMode()](#getFlipMode--) | Λειτουργία αναστροφής εικόνας. |
|
|  | [setFlipMode(ImageFlipModes value)](#setFlipMode-com.groupdocs.conversion.options.convert.ImageFlipModes-) | Λειτουργία αναστροφής εικόνας. |
|
|  | [getBrightness()](#getBrightness--) | Ρυθμίζει τη φωτεινότητα της εικόνας. |
|
|  | [setBrightness(int value)](#setBrightness-int-) | Ρυθμίζει τη φωτεινότητα της εικόνας. |
|
|  | [getContrast()](#getContrast--) | Ρυθμίζει την αντίθεση της εικόνας. |
|
|  | [setContrast(int value)](#setContrast-int-) | Ρυθμίζει την αντίθεση της εικόνας. |
|
|  | [getGamma()](#getGamma--) | Ρυθμίζει το γάμμα της εικόνας. |
|
|  | [setGamma(float value)](#setGamma-float-) | Ρυθμίζει το γάμμα της εικόνας. |
|
|  | [getBackgroundColor()](#getBackgroundColor--) | Λαμβάνει το χρώμα φόντου |
|
|  | [setBackgroundColor(System.Drawing.Color backgroundColor)](#setBackgroundColor-com.aspose.ms.System.Drawing.Color-) | Ορίζει το χρώμα φόντου όπου υποστηρίζεται από τη μορφή προέλευσης |
|
### ImageConvertOptions() {#ImageConvertOptions--}
```
public ImageConvertOptions()
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [ImageConvertOptions](../../com.groupdocs.conversion.options.convert/imageconvertoptions).


### DEFAULT_DPI {#DEFAULT-DPI}
```
public static final int DEFAULT_DPI
```


### getWidth() {#getWidth--}
```
public final int getWidth()
```


Επιθυμητό πλάτος εικόνας μετά τη μετατροπή.


**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Επιθυμητό πλάτος εικόνας μετά τη μετατροπή.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Επιθυμητό ύψος εικόνας μετά τη μετατροπή.


**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Επιθυμητό ύψος εικόνας μετά τη μετατροπή.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### getUsePdf() {#getUsePdf--}
```
public final boolean getUsePdf()
```


Αν
true
, η είσοδος πρώτα μετατρέπεται σε PDF και μετά στο επιθυμητό μορφότυπο.


**Returns:**
boolean
### setUsePdf(boolean value) {#setUsePdf-boolean-}
```
public final void setUsePdf(boolean value)
```


Αν
true
, η είσοδος πρώτα μετατρέπεται σε PDF και μετά στο επιθυμητό μορφότυπο.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### getHorizontalResolution() {#getHorizontalResolution--}
```
public final int getHorizontalResolution()
```


Επιθυμητή οριζόντια ανάλυση εικόνας μετά τη μετατροπή. Η προεπιλεγμένη ανάλυση είναι η ανάλυση του αρχείου εισόδου ή 96 dpi.


**Returns:**
int
### setHorizontalResolution(int value) {#setHorizontalResolution-int-}
```
public final void setHorizontalResolution(int value)
```


Επιθυμητή οριζόντια ανάλυση εικόνας μετά τη μετατροπή. Η προεπιλεγμένη ανάλυση είναι η ανάλυση του αρχείου εισόδου ή 96 dpi.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### getVerticalResolution() {#getVerticalResolution--}
```
public final int getVerticalResolution()
```


Επιθυμητή κάθετη ανάλυση εικόνας μετά τη μετατροπή. Η προεπιλεγμένη ανάλυση είναι η ανάλυση του αρχείου εισόδου ή 96 dpi.


**Returns:**
int
### setVerticalResolution(int value) {#setVerticalResolution-int-}
```
public final void setVerticalResolution(int value)
```


Επιθυμητή κάθετη ανάλυση εικόνας μετά τη μετατροπή. Η προεπιλεγμένη ανάλυση είναι η ανάλυση του αρχείου εισόδου ή 96 dpi.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### getTiffOptions() {#getTiffOptions--}
```
public final TiffOptions getTiffOptions()
```


Ειδικές επιλογές μετατροπής για Tiff.


**Returns:**
[TiffOptions](../../com.groupdocs.conversion.options.convert/tiffoptions)
### setTiffOptions(TiffOptions value) {#setTiffOptions-com.groupdocs.conversion.options.convert.TiffOptions-}
```
public final void setTiffOptions(TiffOptions value)
```


Ειδικές επιλογές μετατροπής για Tiff.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| value | [TiffOptions](../../com.groupdocs.conversion.options.convert/tiffoptions) |  |

### getPsdOptions() {#getPsdOptions--}
```
public final PsdOptions getPsdOptions()
```


Ειδικές επιλογές μετατροπής για Psd.


**Returns:**
[PsdOptions](../../com.groupdocs.conversion.options.convert/psdoptions)
### setPsdOptions(PsdOptions value) {#setPsdOptions-com.groupdocs.conversion.options.convert.PsdOptions-}
```
public final void setPsdOptions(PsdOptions value)
```


Ειδικές επιλογές μετατροπής για Psd.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| value | [PsdOptions](../../com.groupdocs.conversion.options.convert/psdoptions) |  |

### getWebpOptions() {#getWebpOptions--}
```
public final WebpOptions getWebpOptions()
```


Ειδικές επιλογές μετατροπής για Webp.


**Returns:**
[WebpOptions](../../com.groupdocs.conversion.options.convert/webpoptions)
### setWebpOptions(WebpOptions value) {#setWebpOptions-com.groupdocs.conversion.options.convert.WebpOptions-}
```
public final void setWebpOptions(WebpOptions value)
```


Ειδικές επιλογές μετατροπής για Webp.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| value | [WebpOptions](../../com.groupdocs.conversion.options.convert/webpoptions) |  |

### getGrayscale() {#getGrayscale--}
```
public final boolean getGrayscale()
```


Δείχνει αν θα μετατραπεί σε εικόνα σε κλίμακα του γκρι.


**Returns:**
boolean
### setGrayscale(boolean value) {#setGrayscale-boolean-}
```
public final void setGrayscale(boolean value)
```


Δείχνει αν θα μετατραπεί σε εικόνα σε κλίμακα του γκρι.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean |  |

### getRotateAngle() {#getRotateAngle--}
```
public final int getRotateAngle()
```


Γωνία περιστροφής εικόνας.


**Returns:**
int
### setRotateAngle(int value) {#setRotateAngle-int-}
```
public final void setRotateAngle(int value)
```


Γωνία περιστροφής εικόνας.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### getJpegOptions() {#getJpegOptions--}
```
public final JpegOptions getJpegOptions()
```


Ειδικές επιλογές μετατροπής για Jpeg.


**Returns:**
[JpegOptions](../../com.groupdocs.conversion.options.convert/jpegoptions)
### setJpegOptions(JpegOptions value) {#setJpegOptions-com.groupdocs.conversion.options.convert.JpegOptions-}
```
public final void setJpegOptions(JpegOptions value)
```


Ειδικές επιλογές μετατροπής για Jpeg.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| value | [JpegOptions](../../com.groupdocs.conversion.options.convert/jpegoptions) |  |

### getFlipMode() {#getFlipMode--}
```
public final ImageFlipModes getFlipMode()
```


Λειτουργία αναστροφής εικόνας.


**Returns:**
[ImageFlipModes](../../com.groupdocs.conversion.options.convert/imageflipmodes)
### setFlipMode(ImageFlipModes value) {#setFlipMode-com.groupdocs.conversion.options.convert.ImageFlipModes-}
```
public final void setFlipMode(ImageFlipModes value)
```


Λειτουργία αναστροφής εικόνας.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| value | [ImageFlipModes](../../com.groupdocs.conversion.options.convert/imageflipmodes) |  |

### getBrightness() {#getBrightness--}
```
public final int getBrightness()
```


Ρυθμίζει τη φωτεινότητα της εικόνας.


**Returns:**
int
### setBrightness(int value) {#setBrightness-int-}
```
public final void setBrightness(int value)
```


Ρυθμίζει τη φωτεινότητα της εικόνας.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### getContrast() {#getContrast--}
```
public final int getContrast()
```


Ρυθμίζει την αντίθεση της εικόνας.


**Returns:**
int
### setContrast(int value) {#setContrast-int-}
```
public final void setContrast(int value)
```


Ρυθμίζει την αντίθεση της εικόνας.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | int |  |

### getGamma() {#getGamma--}
```
public final float getGamma()
```


Ρυθμίζει το γάμμα της εικόνας.


**Returns:**
float
### setGamma(float value) {#setGamma-float-}
```
public final void setGamma(float value)
```


Ρυθμίζει το γάμμα της εικόνας.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | float |  |

### getBackgroundColor() {#getBackgroundColor--}
```
public System.Drawing.Color getBackgroundColor()
```


Λαμβάνει το χρώμα φόντου


**Returns:**
com.aspose.ms.System.Drawing.Color - χρώμα φόντου

### setBackgroundColor(System.Drawing.Color backgroundColor) {#setBackgroundColor-com.aspose.ms.System.Drawing.Color-}
```
public void setBackgroundColor(System.Drawing.Color backgroundColor)
```


Ορίζει το χρώμα φόντου όπου υποστηρίζεται από τη μορφή προέλευσης


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
|  | backgroundColor | com.aspose.ms.System.Drawing.Color | χρώμα φόντου |
|

