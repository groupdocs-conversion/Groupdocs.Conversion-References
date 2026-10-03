---
title: "IDocument"
second_title: "Java के लिए GroupDocs.Conversion API संदर्भ"
description: "दस्तावेज़ों के लिए इंटरफ़ेस"
type: docs
weight: 22
url: /hi/java/com.groupdocs.conversion.contracts/idocument/
---
**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, [com.groupdocs.conversion.contracts.IDocumentSave](../../com.groupdocs.conversion.contracts/idocumentsave)
```
public interface IDocument extends System.IDisposable, IDocumentSave
```

दस्तावेज़ों के लिए इंटरफ़ेस

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getFormat()](#getFormat--) |  |
| [getContentStream()](#getContentStream--) |  |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getInfo()](#getInfo--) |  |
| [getSize()](#getSize--) |  |
| [getPagesCount()](#getPagesCount--) |  |
| [ensureLoaded()](#ensureLoaded--) |  |
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
### ensureLoaded() {#ensureLoaded--}
```
public abstract void ensureLoaded()
```




