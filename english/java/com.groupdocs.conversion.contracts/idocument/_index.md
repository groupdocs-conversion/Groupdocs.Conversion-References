---
title: IDocument
second_title: GroupDocs.Conversion for Java API Reference
description: Interface for documents
type: docs
weight: 27
url: /java/com.groupdocs.conversion.contracts/idocument/
---
**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, [com.groupdocs.conversion.contracts.IDocumentSave](../../com.groupdocs.conversion.contracts/idocumentsave)
```
public interface IDocument extends System.IDisposable, IDocumentSave
```

Interface for documents
## Methods

| Method | Description |
| --- | --- |
| [getFormat()](#getFormat--) |  |
| [getContentStream()](#getContentStream--) |  |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getInfo()](#getInfo--) |  |
| [getSize()](#getSize--) |  |
| [getPagesCount()](#getPagesCount--) |  |
### getFormat() {#getFormat--}
```
public abstract FileType getFormat()
```




**Returns:**
[FileType](../../com.groupdocs.conversion.filetypes/filetype)
### getContentStream() {#getContentStream--}
```
public abstract System.IO.MemoryStream getContentStream()
```




**Returns:**
com.aspose.ms.System.IO.MemoryStream
### getLoadOptions() {#getLoadOptions--}
```
public abstract LoadOptions getLoadOptions()
```




**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)
### getInfo() {#getInfo--}
```
public abstract IDocumentInfo getInfo()
```




**Returns:**
[IDocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/idocumentinfo)
### getSize() {#getSize--}
```
public abstract long getSize()
```




**Returns:**
long
### getPagesCount() {#getPagesCount--}
```
public abstract int getPagesCount()
```




**Returns:**
int
