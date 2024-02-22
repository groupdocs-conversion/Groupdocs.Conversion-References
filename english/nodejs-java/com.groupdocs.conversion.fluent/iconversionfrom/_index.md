---
title: IConversionFrom
second_title: GroupDocs.Conversion for Node.js via Java API Reference
description: Setup source for conversion
type: docs
weight: 19
url: /nodejs-java/com.groupdocs.conversion.fluent/iconversionfrom/
---```
public interface IConversionFrom
```

Setup source for conversion
## Methods

| Method | Description |
| --- | --- |
| [load(String fileName)](#load-java.lang.String-) | Set source document fileName |
| [load(String[] fileName)](#load-java.lang.String---) | Set source documents array |
| [load(DocumentStreamProvider documentStreamProvider)](#load-com.groupdocs.conversion.contracts.DocumentStreamProvider-) | Set source document stream |
| [load(DocumentStreamsProvider documentStreamProvider)](#load-com.groupdocs.conversion.contracts.DocumentStreamsProvider-) | Set source documents streams array |
### load(String fileName) {#load-java.lang.String-}
```
public abstract IConversionLoadOptionsOrSourceDocumentLoaded load(String fileName)
```


Set source document fileName

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | Source document |

**Returns:**
[IConversionLoadOptionsOrSourceDocumentLoaded](../../com.groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded)
### load(String[] fileName) {#load-java.lang.String---}
```
public abstract IConversionLoadOptionsOrSourceDocumentLoaded load(String[] fileName)
```


Set source documents array

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String[] | Set of source documents |

**Returns:**
[IConversionLoadOptionsOrSourceDocumentLoaded](../../com.groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded)
### load(DocumentStreamProvider documentStreamProvider) {#load-com.groupdocs.conversion.contracts.DocumentStreamProvider-}
```
public abstract IConversionLoadOptionsOrSourceDocumentLoaded load(DocumentStreamProvider documentStreamProvider)
```


Set source document stream

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| documentStreamProvider | [DocumentStreamProvider](../../com.groupdocs.conversion.contracts/documentstreamprovider) | Source document stream provider |

**Returns:**
[IConversionLoadOptionsOrSourceDocumentLoaded](../../com.groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded)
### load(DocumentStreamsProvider documentStreamProvider) {#load-com.groupdocs.conversion.contracts.DocumentStreamsProvider-}
```
public abstract IConversionLoadOptionsOrSourceDocumentLoaded load(DocumentStreamsProvider documentStreamProvider)
```


Set source documents streams array

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| documentStreamProvider | [DocumentStreamsProvider](../../com.groupdocs.conversion.contracts/documentstreamsprovider) | Source document streams provider |

**Returns:**
[IConversionLoadOptionsOrSourceDocumentLoaded](../../com.groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded)
