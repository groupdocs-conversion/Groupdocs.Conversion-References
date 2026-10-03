---
title: "CadLoadOptions"
second_title: "GroupDocs.Conversion για Java API Reference"
description: "Επιλογές φόρτωσης εγγράφων CAD."
type: docs
weight: 12
url: /el/java/com.groupdocs.conversion.options.load/cadloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class CadLoadOptions extends LoadOptions implements Serializable
```

Επιλογές φόρτωσης εγγράφων CAD.

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [CadLoadOptions()](#CadLoadOptions--) | Αρχικοποιεί νέα παρουσία της κλάσης [CadLoadOptions](../../com.groupdocs.conversion.options.load/cadloadoptions). |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getFormat()](#getFormat--) |  |
|  | [getLayoutNames()](#getLayoutNames--) | Καθορίζει ποια διατάξεις CAD θα μετατραπούν |
|
|  | [setLayoutNames(String[] value)](#setLayoutNames-java.lang.String---) | Καθορίζει ποια διατάξεις CAD θα μετατραπούν |
|
|  | [getDrawType()](#getDrawType--) | Λαμβάνει τον τύπο του σχεδίου. |
|
|  | [setDrawType(CadDrawTypeMode drawType)](#setDrawType-com.groupdocs.conversion.options.load.CadDrawTypeMode-) | Ορίζει τον τύπο του σχεδίου. |
|
|  | [getBackgroundColor()](#getBackgroundColor--) | Λαμβάνει ένα χρώμα φόντου. |
|
|  | [setBackgroundColor(System.Drawing.Color backgroundColor)](#setBackgroundColor-com.aspose.ms.System.Drawing.Color-) | Ορίζει ένα χρώμα φόντου. |
|
| [getFontDirectories()](#getFontDirectories--) |  |
| [setFontDirectories(List<String> fontDirectories)](#setFontDirectories-java.util.List-java.lang.String--) |  |
|  | [getCtbSources()](#getCtbSources--) | Λαμβάνει τις πηγές CTB. |
|
|  | [setCtbSources(Map<String,InputStream> ctbSources)](#setCtbSources-java.util.Map-java.lang.String-java.io.InputStream--) | Ορίζει τις πηγές CTB. |
|
|  | [getDrawColor()](#getDrawColor--) | Λαμβάνει το χρώμα προσκηνίου. |
|
|  | [setDrawColor(System.Drawing.Color drawColor)](#setDrawColor-com.aspose.ms.System.Drawing.Color-) | Ορίζει το χρώμα προσκηνίου. |
|
### CadLoadOptions() {#CadLoadOptions--}
```
public CadLoadOptions()
```


Αρχικοποιεί νέα παρουσία της κλάσης [CadLoadOptions](../../com.groupdocs.conversion.options.load/cadloadoptions).


### getFormat() {#getFormat--}
```
public CadFileType getFormat()
```


Τύπος αρχείου εισαγόμενου εγγράφου


**Returns:**
[CadFileType](../../com.groupdocs.conversion.filetypes/cadfiletype)
### getLayoutNames() {#getLayoutNames--}
```
public final String[] getLayoutNames()
```


Καθορίζει ποια διατάξεις CAD θα μετατραπούν


**Returns:**
java.lang.String[]
### setLayoutNames(String[] value) {#setLayoutNames-java.lang.String---}
```
public final void setLayoutNames(String[] value)
```


Καθορίζει ποια διατάξεις CAD θα μετατραπούν


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String[] |  |

### getDrawType() {#getDrawType--}
```
public CadDrawTypeMode getDrawType()
```


Λαμβάνει τον τύπο του σχεδίου.


**Returns:**
[CadDrawTypeMode](../../com.groupdocs.conversion.options.load/caddrawtypemode)
### setDrawType(CadDrawTypeMode drawType) {#setDrawType-com.groupdocs.conversion.options.load.CadDrawTypeMode-}
```
public void setDrawType(CadDrawTypeMode drawType)
```


Ορίζει τον τύπο του σχεδίου.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| drawType | [CadDrawTypeMode](../../com.groupdocs.conversion.options.load/caddrawtypemode) |  |

### getBackgroundColor() {#getBackgroundColor--}
```
public System.Drawing.Color getBackgroundColor()
```


Λαμβάνει ένα χρώμα φόντου.


**Returns:**
com.aspose.ms.System.Drawing.Color
### setBackgroundColor(System.Drawing.Color backgroundColor) {#setBackgroundColor-com.aspose.ms.System.Drawing.Color-}
```
public void setBackgroundColor(System.Drawing.Color backgroundColor)
```


Ορίζει ένα χρώμα φόντου.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| backgroundColor | com.aspose.ms.System.Drawing.Color |  |

### getFontDirectories() {#getFontDirectories--}
```
public List<String> getFontDirectories()
```




**Returns:**
java.util.List<java.lang.String>
### setFontDirectories(List<String> fontDirectories) {#setFontDirectories-java.util.List-java.lang.String--}
```
public void setFontDirectories(List<String> fontDirectories)
```




**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| fontDirectories | java.util.List<java.lang.String> |  |

### getCtbSources() {#getCtbSources--}
```
public Map<String,InputStream> getCtbSources()
```


Λαμβάνει τις πηγές CTB.


**Returns:**
java.util.Map<java.lang.String,java.io.InputStream>
### setCtbSources(Map<String,InputStream> ctbSources) {#setCtbSources-java.util.Map-java.lang.String-java.io.InputStream--}
```
public void setCtbSources(Map<String,InputStream> ctbSources)
```


Ορίζει τις πηγές CTB.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| ctbSources | java.util.Map<java.lang.String,java.io.InputStream> |  |

### getDrawColor() {#getDrawColor--}
```
public System.Drawing.Color getDrawColor()
```


Λαμβάνει το χρώμα προσκηνίου.


**Returns:**
com.aspose.ms.System.Drawing.Color
### setDrawColor(System.Drawing.Color drawColor) {#setDrawColor-com.aspose.ms.System.Drawing.Color-}
```
public void setDrawColor(System.Drawing.Color drawColor)
```


Ορίζει το χρώμα προσκηνίου.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| drawColor | com.aspose.ms.System.Drawing.Color |  |

