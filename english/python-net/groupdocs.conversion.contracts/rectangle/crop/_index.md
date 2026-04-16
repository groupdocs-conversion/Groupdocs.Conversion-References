---
title: crop method
second_title: GroupDocs.Conversion for Python via .NET API References
description: 
type: docs
url: /python-net/groupdocs.conversion.contracts/rectangle/crop/
is_root: false
weight: 1010
---


## crop {#crop_left-crop_top-crop_right-crop_bottom}

Creates a cropped version of the current rectangle by removing specified margins.

```python
def crop(self, crop_left, crop_top, crop_right, crop_bottom):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| crop_left | `int` | The number of pixels to remove from the left side. |
| crop_top | `int` | The number of pixels to remove from the top side. |
| crop_right | `int` | The number of pixels to remove from the right side. |
| crop_bottom | `int` | The number of pixels to remove from the bottom side. |

**Returns:** A new cropped rectangle.

### See Also
* class [`Rectangle`](/conversion/python-net/groupdocs.conversion.contracts/rectangle/)
