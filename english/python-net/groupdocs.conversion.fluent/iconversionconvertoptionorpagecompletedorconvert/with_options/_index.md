---
title: with_options method
second_title: GroupDocs.Conversion for Python via .NET API References
description: "Sets convert options."
type: docs
url: /python-net/groupdocs.conversion.fluent/iconversionconvertoptionorpagecompletedorconvert/with_options/
is_root: false
weight: 1060
---


## with_options {#convert_options}

Sets convert options.

```python
def with_options(self, convert_options):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| convert_options | `ConvertOptions` | Convert options |

**Returns:** Interface to continue conversion building.

## with_options {#convert_options_provider}

Sets convert options.

```python
def with_options(self, convert_options_provider):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| convert_options_provider | `Func[ConvertContext, ConvertOptions]` | Convert options. The `ConvertContext` is passed to the provider. |

**Returns:** Interface to continue conversion building.

### See Also
* class [`IConversionConvertOptionOrPageCompletedOrConvert`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvertoptionorpagecompletedorconvert/)
