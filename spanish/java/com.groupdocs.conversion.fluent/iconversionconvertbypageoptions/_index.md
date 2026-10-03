---
title: "IConversionConvertByPageOptions"
second_title: "Referencia de API de GroupDocs.Conversion for Java"
description: "Opciones de conversión"
type: docs
weight: 17
url: /es/java/com.groupdocs.conversion.fluent/iconversionconvertbypageoptions/
---```
public interface IConversionConvertByPageOptions
```

Conversion convert options

## Methods

| Method | Description |
| --- | --- |
| [withOptions(ConvertOptions convertOptions)](#withOptions-com.groupdocs.conversion.options.convert.ConvertOptions-) | Set convert options
 |
| [withOptions(ConvertOptionsProvider convertOptionsProvider)](#withOptions-com.groupdocs.conversion.contracts.ConvertOptionsProvider-) | Set convert options
 |
### withOptions(ConvertOptions convertOptions) {#withOptions-com.groupdocs.conversion.options.convert.ConvertOptions-}
```
public abstract IConversionByPageCompletedOrConvert withOptions(ConvertOptions convertOptions)
```


Set convert options


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| convertOptions | com.groupdocs.conversion.options.convert.ConvertOptions | Convert options
 |

**Returns:**
[IConversionByPageCompletedOrConvert](../../com.groupdocs.conversion.fluent/iconversionbypagecompletedorconvert) - Interface to continue conversion building

### withOptions(ConvertOptionsProvider convertOptionsProvider) {#withOptions-com.groupdocs.conversion.contracts.ConvertOptionsProvider-}
```
public abstract IConversionByPageCompletedOrConvert withOptions(ConvertOptionsProvider convertOptionsProvider)
```


Set convert options


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| convertOptionsProvider | [ConvertOptionsProvider](../../com.groupdocs.conversion.contracts/convertoptionsprovider) | Convert options provider
 |

**Returns:**
[IConversionByPageCompletedOrConvert](../../com.groupdocs.conversion.fluent/iconversionbypagecompletedorconvert) - Interface to continue conversion building

