---
title: "ConvertOptionsProvider"
second_title: "Java के लिए GroupDocs.Conversion API संदर्भ"
description: "विशिष्ट स्रोत दस्तावेज़ के लिए रूपांतरण विकल्प प्रदान करने वाले डेलीगेट का वर्णन करता है।"
type: docs
weight: 16
url: /hi/java/com.groupdocs.conversion.contracts/convertoptionsprovider/
---```
public interface ConvertOptionsProvider
```

Describes delegate to provide convert options for specific source document. The delegate will be called before each conversion and provide a chance to provide specific convert options for desired target conversion. The decision could be made based on provided source file name and source file type.

## Methods

| Method | Description |
| --- | --- |
| [invoke(String sourceDocumentName, FileType sourceType)](#invoke-java.lang.String-com.groupdocs.conversion.filetypes.FileType-) | Provides convert options for specific source document.
 |
### invoke(String sourceDocumentName, FileType sourceType) {#invoke-java.lang.String-com.groupdocs.conversion.filetypes.FileType-}
```
public abstract ConvertOptions invoke(String sourceDocumentName, FileType sourceType)
```


Provides convert options for specific source document.


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceDocumentName | java.lang.String | Source file name
 |
| sourceType | [FileType](../../com.groupdocs.conversion.filetypes/filetype) | Source file type
 |

**Returns:**
[ConvertOptions](../../com.groupdocs.conversion.options.convert/convertoptions) - Must return ConvertOptions to be used for conversion of FileType sourceType\< document

