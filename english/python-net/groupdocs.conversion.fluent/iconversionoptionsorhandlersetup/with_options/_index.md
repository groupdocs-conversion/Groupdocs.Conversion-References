---
title: with_options method
second_title: GroupDocs.Conversion for Python via .NET API References
description: "Sets conversion options for the conversion process."
type: docs
url: /python-net/groupdocs.conversion.fluent/iconversionoptionsorhandlersetup/with_options/
is_root: false
weight: 1080
---


## with_options {#convert_options}

Sets conversion options for the conversion process.

```python
def with_options(self, convert_options):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| convert_options | `ConvertOptions` | Conversion options. |

**Returns:** Handler setup interface to continue conversion building.

## with_options {#options_provider}

Sets conversion options using a provider function.

```python
def with_options(self, options_provider):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| options_provider | `Func[ConvertContext, ConvertOptions]` | A function that provides conversion options based on the conversion context. |

**Returns:** Handler setup interface to continue conversion building.

### See Also
* class [`IConversionOptionsOrHandlerSetup`](/conversion/python-net/groupdocs.conversion.fluent/iconversionoptionsorhandlersetup/)
