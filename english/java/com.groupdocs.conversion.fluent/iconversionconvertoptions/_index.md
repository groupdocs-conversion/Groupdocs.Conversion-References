---
title: IConversionConvertOptions
second_title: GroupDocs.Conversion for Node.js via Java API Reference
description: Conversion convert options
type: docs
weight: 18
url: /nodejs-java/com.groupdocs.conversion.fluent/iconversionconvertoptions/
---```
public interface IConversionConvertOptions
```

Conversion convert options
## Methods

| Method | Description |
| --- | --- |
| [withOptions(ConvertOptions convertOptions)](#withOptions-com.groupdocs.conversion.options.convert.ConvertOptions-) | Set convert options |
| [withOptions(ConvertOptionsProvider convertOptionsProvider)](#withOptions-com.groupdocs.conversion.contracts.ConvertOptionsProvider-) | Set convert options |
### withOptions(ConvertOptions convertOptions) {#withOptions-com.groupdocs.conversion.options.convert.ConvertOptions-}
```
public abstract IConversionCompletedOrConvert withOptions(ConvertOptions convertOptions)
```


Set convert options

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| convertOptions | com.groupdocs.conversion.options.convert.ConvertOptions | Convert options |

**Returns:**
[IConversionCompletedOrConvert](../../com.groupdocs.conversion.fluent/iconversioncompletedorconvert) - Interface to continue conversion building
### withOptions(ConvertOptionsProvider convertOptionsProvider) {#withOptions-com.groupdocs.conversion.contracts.ConvertOptionsProvider-}
```
public abstract IConversionCompletedOrConvert withOptions(ConvertOptionsProvider convertOptionsProvider)
```


Set convert options

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| convertOptionsProvider | [ConvertOptionsProvider](../../com.groupdocs.conversion.contracts/convertoptionsprovider) | Convert options provider |

**Returns:**
[IConversionCompletedOrConvert](../../com.groupdocs.conversion.fluent/iconversioncompletedorconvert) - Interface to continue conversion building
