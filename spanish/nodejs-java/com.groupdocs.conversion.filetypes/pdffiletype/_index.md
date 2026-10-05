---
title: "PdfFileType"
second_title: "Referencia de API de GroupDocs.Conversion para Node.js vía Java"
description: "Define documentos PDF."
type: docs
weight: 21
url: /es/nodejs-java/com.groupdocs.conversion.filetypes/pdffiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class PdfFileType extends FileType implements Serializable
```

Define documentos Pdf. Incluye los siguientes tipos de archivo: [Pdf](../../com.groupdocs.conversion.filetypes/pdffiletype\#Pdf),
## Constructores

| Constructor | Descripción |
| --- | --- |
| [PdfFileType()](#PdfFileType--) | Constructor de serialización |
## Campos

| Campo | Descripción |
| --- | --- |
| [Pdf](#Pdf) | Portable Document Format (PDF) es un tipo de documento creado por Adobe en la década de 1990. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedSourceTypes()](#getExcludedSourceTypes--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### PdfFileType() {#PdfFileType--}
```
public PdfFileType()
```


Constructor de serialización

### Pdf {#Pdf}
```
public static final PdfFileType Pdf
```


Portable Document Format (PDF) es un tipo de documento creado por Adobe en la década de 1990. El propósito de este formato de archivo era introducir un estándar para la representación de documentos y otro material de referencia en un formato independiente del software de aplicación, hardware y del sistema operativo. Obtén más información sobre este formato de archivo [aquí][].


[here]: https://wiki.fileformat.com/view/pdf

### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


Opciones de carga predeterminadas preparadas para el tipo de archivo de origen

**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)
### getConvertOptions() {#getConvertOptions--}
```
public ConvertOptions getConvertOptions()
```


Opciones de conversión predeterminadas preparadas para el tipo de archivo

**Returns:**
[ConvertOptions](../../com.groupdocs.conversion.options.convert/convertoptions)
### getExcludedSourceTypes() {#getExcludedSourceTypes--}
```
public static final FileType[] getExcludedSourceTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
### getExcludedTargetTypes() {#getExcludedTargetTypes--}
```
public static final FileType[] getExcludedTargetTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
