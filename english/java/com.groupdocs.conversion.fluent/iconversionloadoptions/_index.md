---
title: IConversionLoadOptions
second_title: GroupDocs.Conversion for Java API Reference
description: Conversion load options
type: docs
weight: 22
url: /java/com.groupdocs.conversion.fluent/iconversionloadoptions/
---```
public interface IConversionLoadOptions
```

Conversion load options
## Methods

| Method | Description |
| --- | --- |
| [withOptions(LoadOptions loadOptions)](#withOptions-com.groupdocs.conversion.options.load.LoadOptions-) | Set load options |
| [withOptions(LoadOptionsProvider loadOptionsProvider)](#withOptions-com.groupdocs.conversion.contracts.LoadOptionsProvider-) | Set load options |
| [withOptions(LoadOptionsForFileTypeProvider loadOptionsProvider)](#withOptions-com.groupdocs.conversion.contracts.LoadOptionsForFileTypeProvider-) | Set load options for specified file type |
### withOptions(LoadOptions loadOptions) {#withOptions-com.groupdocs.conversion.options.load.LoadOptions-}
```
public abstract IConversionSourceDocumentLoaded withOptions(LoadOptions loadOptions)
```


Set load options

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


Set load options

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


Set load options for specified file type

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| loadOptionsProvider | [LoadOptionsForFileTypeProvider](../../com.groupdocs.conversion.contracts/loadoptionsforfiletypeprovider) | Load options provider |

**Returns:**
[IConversionSourceDocumentLoaded](../../com.groupdocs.conversion.fluent/iconversionsourcedocumentloaded)
