---
title: IConversionTo
second_title: GroupDocs.Conversion for Node.js via Java API Reference
description: Set how converted document to be stored
type: docs
weight: 28
url: /nodejs-java/com.groupdocs.conversion.fluent/iconversionto/
---```
public interface IConversionTo
```

Set how converted document to be stored
## Methods

| Method | Description |
| --- | --- |
| [convertTo(String fileName)](#convertTo-java.lang.String-) | Save converted document as file |
| [convertTo(SaveDocumentStream convertedStreamProvider)](#convertTo-com.groupdocs.conversion.contracts.SaveDocumentStream-) | Save converted document as stream |
| [convertByPageTo(SavePageStream convertedPageProvider)](#convertByPageTo-com.groupdocs.conversion.contracts.SavePageStream-) | Save converted page as stream |
| [convertTo(SaveDocumentStreamForFileType convertedStreamProvider)](#convertTo-com.groupdocs.conversion.contracts.SaveDocumentStreamForFileType-) | Save converted document as stream by type |
| [convertByPageTo(SavePageStreamForFileType convertedStreamProvider)](#convertByPageTo-com.groupdocs.conversion.contracts.SavePageStreamForFileType-) | Save converted page as stream by type |
### convertTo(String fileName) {#convertTo-java.lang.String-}
```
public abstract IConversionConvertOptionOrCompletedOrConvert convertTo(String fileName)
```


Save converted document as file

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | Converted document |

**Returns:**
[IConversionConvertOptionOrCompletedOrConvert](../../com.groupdocs.conversion.fluent/iconversionconvertoptionorcompletedorconvert) - Interface to continue conversion building
### convertTo(SaveDocumentStream convertedStreamProvider) {#convertTo-com.groupdocs.conversion.contracts.SaveDocumentStream-}
```
public abstract IConversionConvertOptionOrCompletedOrConvert convertTo(SaveDocumentStream convertedStreamProvider)
```


Save converted document as stream

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| convertedStreamProvider | [SaveDocumentStream](../../com.groupdocs.conversion.contracts/savedocumentstream) | Converted document stream provider |

**Returns:**
[IConversionConvertOptionOrCompletedOrConvert](../../com.groupdocs.conversion.fluent/iconversionconvertoptionorcompletedorconvert) - Interface to continue conversion building
### convertByPageTo(SavePageStream convertedPageProvider) {#convertByPageTo-com.groupdocs.conversion.contracts.SavePageStream-}
```
public abstract IConversionConvertOptionOrPageCompletedOrConvert convertByPageTo(SavePageStream convertedPageProvider)
```


Save converted page as stream

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| convertedPageProvider | [SavePageStream](../../com.groupdocs.conversion.contracts/savepagestream) | Converted document page stream provider |

**Returns:**
[IConversionConvertOptionOrPageCompletedOrConvert](../../com.groupdocs.conversion.fluent/iconversionconvertoptionorpagecompletedorconvert) - Interface to continue conversion building
### convertTo(SaveDocumentStreamForFileType convertedStreamProvider) {#convertTo-com.groupdocs.conversion.contracts.SaveDocumentStreamForFileType-}
```
public abstract IConversionConvertOptionOrCompletedOrConvert convertTo(SaveDocumentStreamForFileType convertedStreamProvider)
```


Save converted document as stream by type

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| convertedStreamProvider | [SaveDocumentStreamForFileType](../../com.groupdocs.conversion.contracts/savedocumentstreamforfiletype) | Converted document stream provider |

**Returns:**
[IConversionConvertOptionOrCompletedOrConvert](../../com.groupdocs.conversion.fluent/iconversionconvertoptionorcompletedorconvert) - Interface to continue conversion building
### convertByPageTo(SavePageStreamForFileType convertedStreamProvider) {#convertByPageTo-com.groupdocs.conversion.contracts.SavePageStreamForFileType-}
```
public abstract IConversionConvertOptionOrPageCompletedOrConvert convertByPageTo(SavePageStreamForFileType convertedStreamProvider)
```


Save converted page as stream by type

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| convertedStreamProvider | [SavePageStreamForFileType](../../com.groupdocs.conversion.contracts/savepagestreamforfiletype) | Converted document page stream provider |

**Returns:**
[IConversionConvertOptionOrPageCompletedOrConvert](../../com.groupdocs.conversion.fluent/iconversionconvertoptionorpagecompletedorconvert) - Interface to continue conversion building
