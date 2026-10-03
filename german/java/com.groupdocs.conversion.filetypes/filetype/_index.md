---
title: "FileType"
second_title: "GroupDocs.Conversion für Java API-Referenz"
description: "Dateityp-Basisklasse"
type: docs
weight: 16
url: /de/java/com.groupdocs.conversion.filetypes/filetype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration)
```
public class FileType extends Enumeration
```

Dateityp-Basisklasse

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [FileType()](#FileType--) | Serialisierungskonstruktor |
|
## Felder

| Feld | Beschreibung |
| --- | --- |
|  | [Unknown](#Unknown) | Unbekannter Dateityp |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getFileFormat()](#getFileFormat--) | Das Dateiformat |
|
|  | [getExtension()](#getExtension--) | Die Dateierweiterung |
|
|  | [getFamily()](#getFamily--) | Die Dateifamilie |
|
|  | [getDescription()](#getDescription--) | Beschreibung des Dateityps |
|
|  | [fromFilename(String fileName)](#fromFilename-java.lang.String-) | Gibt FileType für angegebenen Dateinamen zurück |
|
|  | [fromExtension(String fileExtension)](#fromExtension-java.lang.String-) | Ermittelt FileType für angegebene Dateierweiterung |
|
|  | [fromStream(InputStream inputStream)](#fromStream-java.io.InputStream-) | Gibt FileType für bereitgestellten Dokumenten-Stream zurück |
|
|  | [<T>getAllTypes(Class<T> typeOfT)](#-T-getAllTypes-java.lang.Class-T--) | Gibt alle Enumerationswerte zurück. |
|
| [<T>getAllTypes(Class<T> typeOfT, FileType[] excluded)](#-T-getAllTypes-java.lang.Class-T--com.groupdocs.conversion.filetypes.FileType---) |  |
| [<T>getAllTypes(Class<T> typeOfT, FileType[][] excluded)](#-T-getAllTypes-java.lang.Class-T--com.groupdocs.conversion.filetypes.FileType--...-) |  |
|  | [toString()](#toString--) | String-Darstellung |
|
|  | [getLoadOptions()](#getLoadOptions--) | Standard‑Ladeoptionen für den Quelldateityp vorbereitet |
|
|  | [getConvertOptions()](#getConvertOptions--) | Standard‑Konvertierungsoptionen für den Dateityp vorbereitet |
|
| [isObsolete()](#isObsolete--) |  |
| [equals(Enumeration other)](#equals-com.groupdocs.conversion.contracts.Enumeration-) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [hashCode()](#hashCode--) |  |
### FileType() {#FileType--}
```
public FileType()
```


Serialisierungskonstruktor


### Unknown {#Unknown}
```
public static final FileType Unknown
```


Unbekannter Dateityp


### getFileFormat() {#getFileFormat--}
```
public final String getFileFormat()
```


Das Dateiformat


**Returns:**
java.lang.String
### getExtension() {#getExtension--}
```
public final String getExtension()
```


Die Dateierweiterung


**Returns:**
java.lang.String
### getFamily() {#getFamily--}
```
public String getFamily()
```


Die Dateifamilie


**Returns:**
java.lang.String - Die Dateifamilie

### getDescription() {#getDescription--}
```
public final String getDescription()
```


Beschreibung des Dateityps


**Returns:**
java.lang.String - Beschreibung

### fromFilename(String fileName) {#fromFilename-java.lang.String-}
```
public static FileType fromFilename(String fileName)
```


Gibt FileType für angegebenen Dateinamen zurück


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | fileName | java.lang.String | Der Dateiname |
|

**Returns:**
[FileType](../../com.groupdocs.conversion.filetypes/filetype) - The file type of specified file name

### fromExtension(String fileExtension) {#fromExtension-java.lang.String-}
```
public static FileType fromExtension(String fileExtension)
```


Ermittelt FileType für angegebene Dateierweiterung


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | fileExtension | java.lang.String | Dateierweiterung |
|

**Returns:**
[FileType](../../com.groupdocs.conversion.filetypes/filetype) - file type

### fromStream(InputStream inputStream) {#fromStream-java.io.InputStream-}
```
public static FileType fromStream(InputStream inputStream)
```


Gibt FileType für bereitgestellten Dokumenten-Stream zurück


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | inputStream | java.io.InputStream | TStream, das abgefragt wird |
|

**Returns:**
[FileType](../../com.groupdocs.conversion.filetypes/filetype) - The file type of provided stream

### <T>getAllTypes(Class<T> typeOfT) {#-T-getAllTypes-java.lang.Class-T--}
```
public static List<FileType> <T>getAllTypes(Class<T> typeOfT)
```


Gibt alle Enumerationswerte zurück.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |

**Returns:**
java.util.List<com.groupdocs.conversion.filetypes.FileType> - Aufzählung von Dateitypen


T
: Aufgezählter Objekttyp.

### <T>getAllTypes(Class<T> typeOfT, FileType[] excluded) {#-T-getAllTypes-java.lang.Class-T--com.groupdocs.conversion.filetypes.FileType---}
```
public static List<FileType> <T>getAllTypes(Class<T> typeOfT, FileType[] excluded)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |
| excluded | [FileType\[\]](../../com.groupdocs.conversion.filetypes/filetype) |  |

**Returns:**
java.util.List<com.groupdocs.conversion.filetypes.FileType>
### <T>getAllTypes(Class<T> typeOfT, FileType[][] excluded) {#-T-getAllTypes-java.lang.Class-T--com.groupdocs.conversion.filetypes.FileType--...-}
```
public static List<FileType> <T>getAllTypes(Class<T> typeOfT, FileType[][] excluded)
```




**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |
| excluded | [FileType\[\]](../../com.groupdocs.conversion.filetypes/filetype) |  |

**Returns:**
java.util.List<com.groupdocs.conversion.filetypes.FileType>
### toString() {#toString--}
```
public String toString()
```


String-Darstellung


**Returns:**
java.lang.String - Zeichenkettenrepräsentation des Dateityps

### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


Standard‑Ladeoptionen für den Quelldateityp vorbereitet


**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions) - NULL if there is not file type specific load options

### getConvertOptions() {#getConvertOptions--}
```
public ConvertOptions getConvertOptions()
```


Standard‑Konvertierungsoptionen für den Dateityp vorbereitet


**Returns:**
[ConvertOptions](../../com.groupdocs.conversion.options.convert/convertoptions) - NULL if the conversion to the type not supported

### isObsolete() {#isObsolete--}
```
public boolean isObsolete()
```




**Returns:**
boolean
### equals(Enumeration other) {#equals-com.groupdocs.conversion.contracts.Enumeration-}
```
public boolean equals(Enumeration other)
```


Bestimmt, ob zwei Objektinstanzen gleich sind.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| other | [Enumeration](../../com.groupdocs.conversion.contracts/enumeration) |  |

**Returns:**
boolean
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bestimmt, ob zwei Objektinstanzen gleich sind.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public int hashCode()
```


Dient als Standard-Hashfunktion.


**Returns:**
int
