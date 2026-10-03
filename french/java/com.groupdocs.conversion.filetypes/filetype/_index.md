---
title: "FileType"
second_title: "Référence API GroupDocs.Conversion pour Java"
description: "Classe de base du type de fichier"
type: docs
weight: 16
url: /fr/java/com.groupdocs.conversion.filetypes/filetype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration)
```
public class FileType extends Enumeration
```

Classe de base du type de fichier

## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [FileType()](#FileType--) | Constructeur de sérialisation |
|
## Champs

| Champ | Description |
| --- | --- |
|  | [Unknown](#Unknown) | Type de fichier inconnu |
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getFileFormat()](#getFileFormat--) | Le format de fichier |
|
|  | [getExtension()](#getExtension--) | L'extension de fichier |
|
|  | [getFamily()](#getFamily--) | La famille de fichiers |
|
|  | [getDescription()](#getDescription--) | Description du type de fichier |
|
|  | [fromFilename(String fileName)](#fromFilename-java.lang.String-) | Renvoie FileType pour le fileName spécifié |
|
|  | [fromExtension(String fileExtension)](#fromExtension-java.lang.String-) | Obtient FileType pour le fileExtension fourni |
|
|  | [fromStream(InputStream inputStream)](#fromStream-java.io.InputStream-) | Renvoie FileType pour le flux de document fourni |
|
|  | [<T>getAllTypes(Class<T> typeOfT)](#-T-getAllTypes-java.lang.Class-T--) | Renvoie toutes les valeurs d'énumération. |
|
| [<T>getAllTypes(Class<T> typeOfT, FileType[] excluded)](#-T-getAllTypes-java.lang.Class-T--com.groupdocs.conversion.filetypes.FileType---) |  |
| [<T>getAllTypes(Class<T> typeOfT, FileType[][] excluded)](#-T-getAllTypes-java.lang.Class-T--com.groupdocs.conversion.filetypes.FileType--...-) |  |
|  | [toString()](#toString--) | Représentation sous forme de chaîne |
|
|  | [getLoadOptions()](#getLoadOptions--) | Options de chargement par défaut préparées pour le type de fichier source |
|
|  | [getConvertOptions()](#getConvertOptions--) | Options de conversion par défaut préparées pour le type de fichier |
|
| [isObsolete()](#isObsolete--) |  |
| [equals(Enumeration other)](#equals-com.groupdocs.conversion.contracts.Enumeration-) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [hashCode()](#hashCode--) |  |
### FileType() {#FileType--}
```
public FileType()
```


Constructeur de sérialisation


### Unknown {#Unknown}
```
public static final FileType Unknown
```


Type de fichier inconnu


### getFileFormat() {#getFileFormat--}
```
public final String getFileFormat()
```


Le format de fichier


**Returns:**
java.lang.String
### getExtension() {#getExtension--}
```
public final String getExtension()
```


L'extension de fichier


**Returns:**
java.lang.String
### getFamily() {#getFamily--}
```
public String getFamily()
```


La famille de fichiers


**Returns:**
java.lang.String - La famille de fichiers

### getDescription() {#getDescription--}
```
public final String getDescription()
```


Description du type de fichier


**Returns:**
java.lang.String - description

### fromFilename(String fileName) {#fromFilename-java.lang.String-}
```
public static FileType fromFilename(String fileName)
```


Renvoie FileType pour le fileName spécifié


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | fileName | java.lang.String | Le nom du fichier |
|

**Returns:**
[FileType](../../com.groupdocs.conversion.filetypes/filetype) - The file type of specified file name

### fromExtension(String fileExtension) {#fromExtension-java.lang.String-}
```
public static FileType fromExtension(String fileExtension)
```


Obtient FileType pour le fileExtension fourni


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | fileExtension | java.lang.String | extension de fichier |
|

**Returns:**
[FileType](../../com.groupdocs.conversion.filetypes/filetype) - file type

### fromStream(InputStream inputStream) {#fromStream-java.io.InputStream-}
```
public static FileType fromStream(InputStream inputStream)
```


Renvoie FileType pour le flux de document fourni


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | inputStream | java.io.InputStream | TStream qui sera sondé |
|

**Returns:**
[FileType](../../com.groupdocs.conversion.filetypes/filetype) - The file type of provided stream

### <T>getAllTypes(Class<T> typeOfT) {#-T-getAllTypes-java.lang.Class-T--}
```
public static List<FileType> <T>getAllTypes(Class<T> typeOfT)
```


Renvoie toutes les valeurs d'énumération.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |

**Returns:**
java.util.List<com.groupdocs.conversion.filetypes.FileType> - Énumérable des types de fichiers


T
: Type d'objet énuméré.

### <T>getAllTypes(Class<T> typeOfT, FileType[] excluded) {#-T-getAllTypes-java.lang.Class-T--com.groupdocs.conversion.filetypes.FileType---}
```
public static List<FileType> <T>getAllTypes(Class<T> typeOfT, FileType[] excluded)
```




**Parameters:**
| Paramètre | Type | Description |
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
| Paramètre | Type | Description |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |
| excluded | [FileType\[\]](../../com.groupdocs.conversion.filetypes/filetype) |  |

**Returns:**
java.util.List<com.groupdocs.conversion.filetypes.FileType>
### toString() {#toString--}
```
public String toString()
```


Représentation sous forme de chaîne


**Returns:**
java.lang.String - Représentation sous forme de chaîne du type de fichier

### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


Options de chargement par défaut préparées pour le type de fichier source


**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions) - NULL if there is not file type specific load options

### getConvertOptions() {#getConvertOptions--}
```
public ConvertOptions getConvertOptions()
```


Options de conversion par défaut préparées pour le type de fichier


**Returns:**
[ConvertOptions](../../com.groupdocs.conversion.options.convert/convertoptions) - NULL if the conversion to the type not supported

### isObsolete() {#isObsolete--}
```
public boolean isObsolete()
```




**Returns:**
booléen
### equals(Enumeration other) {#equals-com.groupdocs.conversion.contracts.Enumeration-}
```
public boolean equals(Enumeration other)
```


Détermine si deux instances d'objet sont égales.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| other | [Enumeration](../../com.groupdocs.conversion.contracts/enumeration) |  |

**Returns:**
booléen
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Détermine si deux instances d'objet sont égales.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
booléen
### hashCode() {#hashCode--}
```
public int hashCode()
```


Servir de fonction de hachage par défaut.


**Returns:**
int
