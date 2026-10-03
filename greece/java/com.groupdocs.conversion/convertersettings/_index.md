---
title: "ConverterSettings"
second_title: "GroupDocs.Conversion για Java API Reference"
description: "Ορίζει ρυθμίσεις για την προσαρμογή της συμπεριφοράς."
type: docs
weight: 11
url: /el/java/com.groupdocs.conversion/convertersettings/
---
**Inheritance:**
java.lang.Object
```
public final class ConverterSettings
```

Ορίζει ρυθμίσεις για την προσαρμογή της συμπεριφοράς του [Converter](../../com.groupdocs.conversion/converter).

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [ConverterSettings()](#ConverterSettings--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getCache()](#getCache--) | Η υλοποίηση της προσωρινής μνήμης που χρησιμοποιείται για την αποθήκευση των αποτελεσμάτων μετατροπής. |
|
|  | [setCache(ICache value)](#setCache-com.groupdocs.conversion.caching.ICache-) | Η υλοποίηση της προσωρινής μνήμης που χρησιμοποιείται για την αποθήκευση των αποτελεσμάτων μετατροπής. |
|
|  | [getLogger()](#getLogger--) | Η υλοποίηση του καταγραφέα που χρησιμοποιείται για την καταγραφή της διαδικασίας μετατροπής. |
|
|  | [setLogger(ILogger value)](#setLogger-com.groupdocs.conversion.logging.ILogger-) | Η υλοποίηση του καταγραφέα που χρησιμοποιείται για την καταγραφή της διαδικασίας μετατροπής. |
|
|  | [getListener()](#getListener--) | Αποκτά την υλοποίηση του ακροατή μετατροπέα που χρησιμοποιείται για την παρακολούθηση της κατάστασης και της προόδου της μετατροπής |
|
|  | [setListener(IConverterListener listener)](#setListener-com.groupdocs.conversion.reporting.IConverterListener-) | Ορίζει την υλοποίηση του ακροατή μετατροπέα που χρησιμοποιείται για την παρακολούθηση της κατάστασης και της προόδου της μετατροπής |
|
|  | [getFontDirectories()](#getFontDirectories--) | Οι διαδρομές των προσαρμοσμένων καταλόγων γραμματοσειρών |
|
| [getFontDirectoriesInternal()](#getFontDirectoriesInternal--) |  |
|  | [setFontDirectories(List<String> value)](#setFontDirectories-java.util.List-java.lang.String--) | Οι διαδρομές των προσαρμοσμένων καταλόγων γραμματοσειρών |
|
| [listConverterSettings()](#listConverterSettings--) |  |
|  | [getTempFolder()](#getTempFolder--) | Φάκελος προσωρινής αποθήκευσης που χρησιμοποιείται για τη μετατροπή |
|
|  | [setTempFolder(String tempFolder)](#setTempFolder-java.lang.String-) | Ορίζει φάκελο προσωρινής αποθήκευσης που χρησιμοποιείται για τη μετατροπή |
|
### ConverterSettings() {#ConverterSettings--}
```
public ConverterSettings()
```


### getCache() {#getCache--}
```
public final ICache getCache()
```


Η υλοποίηση της προσωρινής μνήμης που χρησιμοποιείται για την αποθήκευση των αποτελεσμάτων μετατροπής.


**Returns:**
[ICache](../../com.groupdocs.conversion.caching/icache)
### setCache(ICache value) {#setCache-com.groupdocs.conversion.caching.ICache-}
```
public final void setCache(ICache value)
```


Η υλοποίηση της προσωρινής μνήμης που χρησιμοποιείται για την αποθήκευση των αποτελεσμάτων μετατροπής.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| value | [ICache](../../com.groupdocs.conversion.caching/icache) |  |

### getLogger() {#getLogger--}
```
public final ILogger getLogger()
```


Η υλοποίηση του καταγραφέα που χρησιμοποιείται για την καταγραφή της διαδικασίας μετατροπής.


**Returns:**
[ILogger](../../com.groupdocs.conversion.logging/ilogger)
### setLogger(ILogger value) {#setLogger-com.groupdocs.conversion.logging.ILogger-}
```
public final void setLogger(ILogger value)
```


Η υλοποίηση του καταγραφέα που χρησιμοποιείται για την καταγραφή της διαδικασίας μετατροπής.


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| value | [ILogger](../../com.groupdocs.conversion.logging/ilogger) |  |

### getListener() {#getListener--}
```
public IConverterListener getListener()
```


Αποκτά την υλοποίηση του ακροατή μετατροπέα που χρησιμοποιείται για την παρακολούθηση της κατάστασης και της προόδου της μετατροπής


**Returns:**
[IConverterListener](../../com.groupdocs.conversion.reporting/iconverterlistener) - The converter listener

### setListener(IConverterListener listener) {#setListener-com.groupdocs.conversion.reporting.IConverterListener-}
```
public void setListener(IConverterListener listener)
```


Ορίζει την υλοποίηση του ακροατή μετατροπέα που χρησιμοποιείται για την παρακολούθηση της κατάστασης και της προόδου της μετατροπής


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
|  | listener | [IConverterListener](../../com.groupdocs.conversion.reporting/iconverterlistener) | Ο ακροατής μετατροπέα |
|

### getFontDirectories() {#getFontDirectories--}
```
public final List<String> getFontDirectories()
```


Οι διαδρομές των προσαρμοσμένων καταλόγων γραμματοσειρών


**Returns:**
java.util.List<java.lang.String>
### getFontDirectoriesInternal() {#getFontDirectoriesInternal--}
```
public List<String> getFontDirectoriesInternal()
```




**Returns:**
java.util.List<java.lang.String>
### setFontDirectories(List<String> value) {#setFontDirectories-java.util.List-java.lang.String--}
```
public void setFontDirectories(List<String> value)
```


Οι διαδρομές των προσαρμοσμένων καταλόγων γραμματοσειρών


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| τιμή | java.util.List<java.lang.String> |  |

### listConverterSettings() {#listConverterSettings--}
```
public List<String> listConverterSettings()
```




**Returns:**
java.util.List<java.lang.String>
### getTempFolder() {#getTempFolder--}
```
public String getTempFolder()
```


Φάκελος προσωρινής αποθήκευσης που χρησιμοποιείται για τη μετατροπή


**Returns:**
java.lang.String
### setTempFolder(String tempFolder) {#setTempFolder-java.lang.String-}
```
public void setTempFolder(String tempFolder)
```


Ορίζει φάκελο προσωρινής αποθήκευσης που χρησιμοποιείται για τη μετατροπή


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| tempFolder | java.lang.String |  |

