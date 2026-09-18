---
title: with_options method
second_title: GroupDocs.Conversion for Python via .NET API References
description: "Set convert options."
type: docs
url: /python-net/groupdocs.conversion.fluent/iconversionbypageoptionsorhandlersetup/with_options/
is_root: false
weight: 1080
---


## with_options {#convert_options}

Set convert options.

```python
def with_options(self, convert_options):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| convert_options | `ConvertOptions` | Convert options |

**Returns:** Interface to continue conversion building

## with_options {#convert_options_provider}

Set convert options.

```python
def with_options(self, convert_options_provider):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| convert_options_provider | `Func[ConvertContext, ConvertOptions]` | Convert options. The `ConvertContext`. |

**Returns:** Interface to continue conversion building.

### See Also
* class [`IConversionByPageOptionsOrHandlerSetup`](/conversion/python-net/groupdocs.conversion.fluent/iconversionbypageoptionsorhandlersetup/)
