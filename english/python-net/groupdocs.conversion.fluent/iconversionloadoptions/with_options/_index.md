---
title: with_options method
second_title: GroupDocs.Conversion for Python via .NET API References
description: "Set load options."
type: docs
url: /python-net/groupdocs.conversion.fluent/iconversionloadoptions/with_options/
is_root: false
weight: 1010
---


## with_options {#load_options}

Set load options.

```python
def with_options(self, load_options):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| load_options | `LoadOptions` | Load options. |

## with_options {#load_options_provider}

Provides load options for the document currently being loaded.

```python
def with_options(self, load_options_provider):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| load_options_provider | `Func[LoadContext, LoadOptions]` | Load options provider. The provider receives the load options context. |

### See Also
* class [`IConversionLoadOptions`](/conversion/python-net/groupdocs.conversion.fluent/iconversionloadoptions/)
