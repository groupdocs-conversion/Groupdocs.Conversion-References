---
title: "PublisherFileType"
second_title: "Referencia de API de GroupDocs.Conversion for Java"
description: "Define documentos de Publisher."
type: docs
weight: 24
url: /es/java/com.groupdocs.conversion.filetypes/publisherfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class PublisherFileType extends FileType implements Serializable
```

Define documentos de Publisher.
Incluye los siguientes tipos:
[Pub](../../com.groupdocs.conversion.filetypes/publisherfiletype#Pub),
Aprende más sobre los formatos de fuentes [aquí](../https://wiki.fileformat.com/publisher).

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [PublisherFileType()](#PublisherFileType--) | Constructor de serialización |
|
## Campos

| Campo | Descripción |
| --- | --- |
|  | [Pub](#Pub) | Un archivo PUB es un formato de archivo de documento de Microsoft Publisher. |
|
## Métodos

| Método | Descripción |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getExcludedSourceTypes()](#getExcludedSourceTypes--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### PublisherFileType() {#PublisherFileType--}
```
public PublisherFileType()
```


Constructor de serialización


### Pub {#Pub}
```
public static final PublisherFileType Pub
```


Un archivo PUB es un formato de archivo de documento de Microsoft Publisher. Se usa para crear varios tipos de documentos de diseño como boletines, folletos, trípticos, postales, etc. Los archivos PUB pueden contener texto, imágenes raster y vectoriales. Aprende más sobre este formato de archivo [aquí](../https://docs.fileformat.com/publisher/pub/).


### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


Opciones de carga predeterminadas preparadas para el tipo de archivo de origen


**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)
### getExcludedSourceTypes() {#getExcludedSourceTypes--}
```
public static FileType[] getExcludedSourceTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
### getExcludedTargetTypes() {#getExcludedTargetTypes--}
```
public static FileType[] getExcludedTargetTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
