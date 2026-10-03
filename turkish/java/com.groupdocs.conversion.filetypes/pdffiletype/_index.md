---
title: "PdfFileType"
second_title: "Java için GroupDocs.Conversion API Referansı"
description: "Pdf belgelerini tanımlar."
type: docs
weight: 21
url: /tr/java/com.groupdocs.conversion.filetypes/pdffiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class PdfFileType extends FileType implements Serializable
```

Pdf belgelerini tanımlar. Aşağıdaki dosya türlerini içerir:
[Pdf](../../com.groupdocs.conversion.filetypes/pdffiletype#Pdf),

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
|  | [PdfFileType()](#PdfFileType--) | Serileştirme yapıcısı |
|
## Alanlar

| Alan | Açıklama |
| --- | --- |
|  | [Pdf](#Pdf) | Portable Document Format (PDF), 1990'larda Adobe tarafından oluşturulan bir belge türüdür. |
|
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedSourceTypes()](#getExcludedSourceTypes--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### PdfFileType() {#PdfFileType--}
```
public PdfFileType()
```


Serileştirme yapıcısı


### Pdf {#Pdf}
```
public static final PdfFileType Pdf
```


Portable Document Format (PDF), 1990'larda Adobe tarafından oluşturulan bir belge türüdür. Bu dosya biçiminin amacı, belgelerin ve diğer referans materyallerin, uygulama yazılımı, donanım ve İşletim Sistemi bağımsız bir formatta temsil edilmesi için bir standart getirmekti.
Bu dosya biçimi hakkında daha fazla bilgi edinin [burada](../https://wiki.fileformat.com/view/pdf).


### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


Kaynak dosya türü için varsayılan yükleme seçenekleri hazırlandı


**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)
### getConvertOptions() {#getConvertOptions--}
```
public ConvertOptions getConvertOptions()
```


Dosya türü için varsayılan dönüştürme seçenekleri hazırlandı


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
