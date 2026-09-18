---
title: with_options method
second_title: GroupDocs.Conversion for Python via .NET API References
description: "Sets convert options."
type: docs
url: /python-net/groupdocs.conversion.fluent/iconversionconvertbypageoptions/with_options/
is_root: false
weight: 1010
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

Set convert options.

```python
def with_options(self, convert_options_provider):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| convert_options_provider | `Func[ConvertContext, ConvertOptions]` | Convert options. The callable receives a `ConvertContext`. |

**Returns:** Interface to continue conversion building.

### See Also
* class [`IConversionConvertByPageOptions`](/conversion/python-net/groupdocs.conversion.fluent/iconversionconvertbypageoptions/)
