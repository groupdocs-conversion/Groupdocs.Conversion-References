---
title: "Filtyp"
second_title: "GroupDocs.Conversion för Node.js via Java API-referens"
description: "Bas-klass för filtyp"
type: docs
weight: 16
url: /sv/nodejs-java/com.groupdocs.conversion.filetypes/filetype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration)
```
public class FileType extends Enumeration
```

Bas-klass för filtyp
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [FileType()](#FileType--) | Serialiseringskonstruktor |
## Fält

| Fält | Beskrivning |
| --- | --- |
| [Unknown](#Unknown) | Okänd filtyp |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | Filformatet |
| [getExtension()](#getExtension--) | Filändelsen |
| [getFamily()](#getFamily--) | Filfamiljen |
| [getDescription()](#getDescription--) | Beskrivning av filtypen |
| [fromFilename(String fileName)](#fromFilename-java.lang.String-) | Returnerar FileType för angivet fileName |
| [fromExtension(String fileExtension)](#fromExtension-java.lang.String-) | Hämtar FileType för angiven fileExtension |
| [fromStream(InputStream inputStream)](#fromStream-java.io.InputStream-) | Returnerar FileType för angiven dokumentström |
| [<T>getAllTypes(Class<T> typeOfT)](#-T-getAllTypes-java.lang.Class-T--) | Returnerar alla enumerationsvärden. |
| [<T>getAllTypes(Class<T> typeOfT, FileType[] excluded)](#-T-getAllTypes-java.lang.Class-T--com.groupdocs.conversion.filetypes.FileType---) |  |
| [<T>getAllTypes(Class<T> typeOfT, FileType[][] excluded)](#-T-getAllTypes-java.lang.Class-T--com.groupdocs.conversion.filetypes.FileType--...-) |  |
| [toString()](#toString--) | Strängrepresentation |
| [getLoadOptions()](#getLoadOptions--) | Förberedda standardalternativ för inläsning för källfiltypen |
| [getConvertOptions()](#getConvertOptions--) | Förberedda standardalternativ för konvertering för filtypen |
| [isObsolete()](#isObsolete--) |  |
| [equals(Enumeration other)](#equals-com.groupdocs.conversion.contracts.Enumeration-) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [hashCode()](#hashCode--) |  |
### FileType() {#FileType--}
```
public FileType()
```


Serialiseringskonstruktor

### Unknown {#Unknown}
```
public static final FileType Unknown
```


Okänd filtyp

### getFileFormat() {#getFileFormat--}
```
public final String getFileFormat()
```


Filformatet

**Returns:**
java.lang.String
### getExtension() {#getExtension--}
```
public final String getExtension()
```


Filändelsen

**Returns:**
java.lang.String
### getFamily() {#getFamily--}
```
public String getFamily()
```


Filfamiljen

**Returns:**
java.lang.String - Filfamiljen
### getDescription() {#getDescription--}
```
public final String getDescription()
```


Beskrivning av filtypen

**Returns:**
java.lang.String - beskrivning
### fromFilename(String fileName) {#fromFilename-java.lang.String-}
```
public static FileType fromFilename(String fileName)
```


Returnerar FileType för angivet fileName

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fileName | java.lang.String | Filnamnet |

**Returns:**
[FileType](../../com.groupdocs.conversion.filetypes/filetype) - The file type of specified file name
### fromExtension(String fileExtension) {#fromExtension-java.lang.String-}
```
public static FileType fromExtension(String fileExtension)
```


Hämtar FileType för angiven fileExtension

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fileExtension | java.lang.String | filändelse |

**Returns:**
[FileType](../../com.groupdocs.conversion.filetypes/filetype) - file type
### fromStream(InputStream inputStream) {#fromStream-java.io.InputStream-}
```
public static FileType fromStream(InputStream inputStream)
```


Returnerar FileType för angiven dokumentström

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputStream | java.io.InputStream | TStream som kommer att undersökas |

**Returns:**
[FileType](../../com.groupdocs.conversion.filetypes/filetype) - The file type of provided stream
### <T>getAllTypes(Class<T> typeOfT) {#-T-getAllTypes-java.lang.Class-T--}
```
public static List<FileType> <T>getAllTypes(Class<T> typeOfT)
```


Returnerar alla enumerationsvärden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |

**Returns:**
java.util.List<com.groupdocs.conversion.filetypes.FileType> - Uppsättning av filtyper

T : Enumererad objekttyp.
### <T>getAllTypes(Class<T> typeOfT, FileType[] excluded) {#-T-getAllTypes-java.lang.Class-T--com.groupdocs.conversion.filetypes.FileType---}
```
public static List<FileType> <T>getAllTypes(Class<T> typeOfT, FileType[] excluded)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |
| excluded | [FileType\[\]](../../com.groupdocs.conversion.filetypes/filetype) |  |

**Returns:**
java.util.List<com.groupdocs.conversion.filetypes.FileType>
### toString() {#toString--}
```
public String toString()
```


Strängrepresentation

**Returns:**
java.lang.String - Strängrepresentation av filtyp
### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


Förberedda standardalternativ för inläsning för källfiltypen

**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions) - NULL if there is not file type specific load options
### getConvertOptions() {#getConvertOptions--}
```
public ConvertOptions getConvertOptions()
```


Förberedda standardalternativ för konvertering för filtypen

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


Bestämmer om två objektinstanser är lika.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| other | [Enumeration](../../com.groupdocs.conversion.contracts/enumeration) |  |

**Returns:**
boolean
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bestämmer om två objektinstanser är lika.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public int hashCode()
```


Fungerar som standardhashfunktion.

**Returns:**
int
