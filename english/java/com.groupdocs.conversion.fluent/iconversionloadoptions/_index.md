---
title: IConversionLoadOptions
second_title: GroupDocs.Conversion for Java API Reference
description: Conversion load options
type: docs
weight: 23
url: /java/com.groupdocs.conversion.fluent/iconversionloadoptions/
---```
public interface IConversionLoadOptions
```

Conversion load options
## Methods

| Method | Description |
| --- | --- |
| [withOptions(LoadOptions loadOptions)](#withOptions-com.groupdocs.conversion.options.load.LoadOptions-) | Provide load options for the document currently being loading |
| [withOptions(LoadOptionsProvider loadOptionsProvider)](#withOptions-com.groupdocs.conversion.contracts.LoadOptionsProvider-) | Provide load options for the document currently being loading |
| [withOptions(LoadOptionsForFileTypeProvider loadOptionsProvider)](#withOptions-com.groupdocs.conversion.contracts.LoadOptionsForFileTypeProvider-) | Provide load options for the document currently being loading |
| [withOptions(LoadOptionsForNameFileTypeStreamProvider loadOptionsProvider)](#withOptions-com.groupdocs.conversion.contracts.LoadOptionsForNameFileTypeStreamProvider-) | Provide load options for the document currently being loading Load options provider The name of the loaded file The type of the loaded file The content of the loaded file |
### withOptions(LoadOptions loadOptions) {#withOptions-com.groupdocs.conversion.options.load.LoadOptions-}
```
public abstract IConversionSourceDocumentLoaded withOptions(LoadOptions loadOptions)
```


Provide load options for the document currently being loading

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| loadOptions | [LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions) | Load options |

**Returns:**
[IConversionSourceDocumentLoaded](../../com.groupdocs.conversion.fluent/iconversionsourcedocumentloaded)
### withOptions(LoadOptionsProvider loadOptionsProvider) {#withOptions-com.groupdocs.conversion.contracts.LoadOptionsProvider-}
```
public abstract IConversionSourceDocumentLoaded withOptions(LoadOptionsProvider loadOptionsProvider)
```


Provide load options for the document currently being loading

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| loadOptionsProvider | [LoadOptionsProvider](../../com.groupdocs.conversion.contracts/loadoptionsprovider) | Load options provider |

**Returns:**
[IConversionSourceDocumentLoaded](../../com.groupdocs.conversion.fluent/iconversionsourcedocumentloaded)
### withOptions(LoadOptionsForFileTypeProvider loadOptionsProvider) {#withOptions-com.groupdocs.conversion.contracts.LoadOptionsForFileTypeProvider-}
```
public abstract IConversionSourceDocumentLoaded withOptions(LoadOptionsForFileTypeProvider loadOptionsProvider)
```


Provide load options for the document currently being loading

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| loadOptionsProvider | [LoadOptionsForFileTypeProvider](../../com.groupdocs.conversion.contracts/loadoptionsforfiletypeprovider) | Load options provider |

**Returns:**
[IConversionSourceDocumentLoaded](../../com.groupdocs.conversion.fluent/iconversionsourcedocumentloaded)
### withOptions(LoadOptionsForNameFileTypeStreamProvider loadOptionsProvider) {#withOptions-com.groupdocs.conversion.contracts.LoadOptionsForNameFileTypeStreamProvider-}
```
public abstract IConversionSourceDocumentLoaded withOptions(LoadOptionsForNameFileTypeStreamProvider loadOptionsProvider)
```


Provide load options for the document currently being loading Load options provider The name of the loaded file The type of the loaded file The content of the loaded file

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| loadOptionsProvider | [LoadOptionsForNameFileTypeStreamProvider](../../com.groupdocs.conversion.contracts/loadoptionsfornamefiletypestreamprovider) |  |

**Returns:**
[IConversionSourceDocumentLoaded](../../com.groupdocs.conversion.fluent/iconversionsourcedocumentloaded)
