---
title: "Bestandstype"
second_title: "GroupDocs.Conversion for Node.js via Java API-referentie"
description: "Basis‑klasse voor bestandstype"
type: docs
weight: 16
url: /nl/nodejs-java/com.groupdocs.conversion.filetypes/filetype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration)
```
public class FileType extends Enumeration
```

Basis‑klasse voor bestandstype
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [FileType()](#FileType--) | Serialisatieconstructor |
## Velden

| Veld | Beschrijving |
| --- | --- |
| [Unknown](#Unknown) | Onbekend bestandstype |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | Het bestandsformaat |
| [getExtension()](#getExtension--) | De bestandsextensie |
| [getFamily()](#getFamily--) | De bestandsfamilie |
| [getDescription()](#getDescription--) | Beschrijving van het bestandstype |
| [fromFilename(String fileName)](#fromFilename-java.lang.String-) | Retourneert FileType voor opgegeven bestandsnaam |
| [fromExtension(String fileExtension)](#fromExtension-java.lang.String-) | Haalt FileType op voor opgegeven bestandsextensie |
| [fromStream(InputStream inputStream)](#fromStream-java.io.InputStream-) | Retourneert FileType voor opgegeven documentstroom |
| [<T>getAllTypes(Class<T> typeOfT)](#-T-getAllTypes-java.lang.Class-T--) | Geeft alle enumeratiewaarden terug. |
| [<T>getAllTypes(Class<T> typeOfT, FileType[] excluded)](#-T-getAllTypes-java.lang.Class-T--com.groupdocs.conversion.filetypes.FileType---) |  |
| [<T>getAllTypes(Class<T> typeOfT, FileType[][] excluded)](#-T-getAllTypes-java.lang.Class-T--com.groupdocs.conversion.filetypes.FileType--...-) |  |
| [toString()](#toString--) | Stringrepresentatie |
| [getLoadOptions()](#getLoadOptions--) | Voorbereide standaard laadopties voor het bronbestandstype |
| [getConvertOptions()](#getConvertOptions--) | Voorbereide standaard conversie‑opties voor het bestandstype |
| [isObsolete()](#isObsolete--) |  |
| [equals(Enumeration other)](#equals-com.groupdocs.conversion.contracts.Enumeration-) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [hashCode()](#hashCode--) |  |
### FileType() {#FileType--}
```
public FileType()
```


Serialisatieconstructor

### Unknown {#Unknown}
```
public static final FileType Unknown
```


Onbekend bestandstype

### getFileFormat() {#getFileFormat--}
```
public final String getFileFormat()
```


Het bestandsformaat

**Returns:**
java.lang.String
### getExtension() {#getExtension--}
```
public final String getExtension()
```


De bestandsextensie

**Returns:**
java.lang.String
### getFamily() {#getFamily--}
```
public String getFamily()
```


De bestandsfamilie

**Returns:**
java.lang.String - De bestandsfamilie
### getDescription() {#getDescription--}
```
public final String getDescription()
```


Beschrijving van het bestandstype

**Returns:**
java.lang.String - beschrijving
### fromFilename(String fileName) {#fromFilename-java.lang.String-}
```
public static FileType fromFilename(String fileName)
```


Retourneert FileType voor opgegeven bestandsnaam

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fileName | java.lang.String | De bestandsnaam |

**Returns:**
[FileType](../../com.groupdocs.conversion.filetypes/filetype) - The file type of specified file name
### fromExtension(String fileExtension) {#fromExtension-java.lang.String-}
```
public static FileType fromExtension(String fileExtension)
```


Haalt FileType op voor opgegeven bestandsextensie

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fileExtension | java.lang.String | bestandsextensie |

**Returns:**
[FileType](../../com.groupdocs.conversion.filetypes/filetype) - file type
### fromStream(InputStream inputStream) {#fromStream-java.io.InputStream-}
```
public static FileType fromStream(InputStream inputStream)
```


Retourneert FileType voor opgegeven documentstroom

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| inputStream | java.io.InputStream | TStream die zal worden onderzocht |

**Returns:**
[FileType](../../com.groupdocs.conversion.filetypes/filetype) - The file type of provided stream
### <T>getAllTypes(Class<T> typeOfT) {#-T-getAllTypes-java.lang.Class-T--}
```
public static List<FileType> <T>getAllTypes(Class<T> typeOfT)
```


Geeft alle enumeratiewaarden terug.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |

**Returns:**
java.util.List<com.groupdocs.conversion.filetypes.FileType> - Opsomming van bestandstypen

T : Genummerd objecttype.
### <T>getAllTypes(Class<T> typeOfT, FileType[] excluded) {#-T-getAllTypes-java.lang.Class-T--com.groupdocs.conversion.filetypes.FileType---}
```
public static List<FileType> <T>getAllTypes(Class<T> typeOfT, FileType[] excluded)
```




**Parameters:**
| Parameter | Type | Beschrijving |
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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |
| excluded | [FileType\[\]](../../com.groupdocs.conversion.filetypes/filetype) |  |

**Returns:**
java.util.List<com.groupdocs.conversion.filetypes.FileType>
### toString() {#toString--}
```
public String toString()
```


Stringrepresentatie

**Returns:**
java.lang.String - Stringrepresentatie van bestandstype
### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


Voorbereide standaard laadopties voor het bronbestandstype

**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions) - NULL if there is not file type specific load options
### getConvertOptions() {#getConvertOptions--}
```
public ConvertOptions getConvertOptions()
```


Voorbereide standaard conversie‑opties voor het bestandstype

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


Bepaalt of twee objectinstanties gelijk zijn.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| other | [Enumeration](../../com.groupdocs.conversion.contracts/enumeration) |  |

**Returns:**
boolean
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bepaalt of twee objectinstanties gelijk zijn.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public int hashCode()
```


Dient als de standaard hash-functie.

**Returns:**
int
