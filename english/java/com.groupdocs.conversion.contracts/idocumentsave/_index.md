---
title: IDocumentSave
second_title: GroupDocs.Conversion for Java API Reference
description: 
type: docs
weight: 28
url: /java/com.groupdocs.conversion.contracts/idocumentsave/
---```
public interface IDocumentSave
```
## Methods

| Method | Description |
| --- | --- |
| [save(SaveDocumentStreamForFileType streamFactory, Consumer<System.IO.Stream> documentCompleted, ConvertOptions convertOptions)](#save-com.groupdocs.conversion.contracts.SaveDocumentStreamForFileType-java.util.function.Consumer-com.aspose.ms.System.IO.Stream--com.groupdocs.conversion.options.convert.ConvertOptions-) |  |
| [save(SavePageStreamForFileType streamFactory, BiConsumer<Integer,System.IO.Stream> documentCompleted, ConvertOptions convertOptions)](#save-com.groupdocs.conversion.contracts.SavePageStreamForFileType-java.util.function.BiConsumer-java.lang.Integer-com.aspose.ms.System.IO.Stream--com.groupdocs.conversion.options.convert.ConvertOptions-) |  |
### save(SaveDocumentStreamForFileType streamFactory, Consumer<System.IO.Stream> documentCompleted, ConvertOptions convertOptions) {#save-com.groupdocs.conversion.contracts.SaveDocumentStreamForFileType-java.util.function.Consumer-com.aspose.ms.System.IO.Stream--com.groupdocs.conversion.options.convert.ConvertOptions-}
```
public abstract void save(SaveDocumentStreamForFileType streamFactory, Consumer<System.IO.Stream> documentCompleted, ConvertOptions convertOptions)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| streamFactory | [SaveDocumentStreamForFileType](../../com.groupdocs.conversion.contracts/savedocumentstreamforfiletype) |  |
| documentCompleted | java.util.function.Consumer<com.aspose.ms.System.IO.Stream> |  |
| convertOptions | com.groupdocs.conversion.options.convert.ConvertOptions |  |

### save(SavePageStreamForFileType streamFactory, BiConsumer<Integer,System.IO.Stream> documentCompleted, ConvertOptions convertOptions) {#save-com.groupdocs.conversion.contracts.SavePageStreamForFileType-java.util.function.BiConsumer-java.lang.Integer-com.aspose.ms.System.IO.Stream--com.groupdocs.conversion.options.convert.ConvertOptions-}
```
public abstract void save(SavePageStreamForFileType streamFactory, BiConsumer<Integer,System.IO.Stream> documentCompleted, ConvertOptions convertOptions)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| streamFactory | [SavePageStreamForFileType](../../com.groupdocs.conversion.contracts/savepagestreamforfiletype) |  |
| documentCompleted | java.util.function.BiConsumer<java.lang.Integer,com.aspose.ms.System.IO.Stream> |  |
| convertOptions | com.groupdocs.conversion.options.convert.ConvertOptions |  |

