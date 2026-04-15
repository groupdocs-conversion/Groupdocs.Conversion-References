---
title: FontTransformation class
second_title: GroupDocs.Conversion for Python via .NET API References
description: 
type: docs
url: /conversion/python-net/groupdocs.conversion.contracts/fonttransformation/
is_root: false
weight: 190
---


## FontTransformation class

Describes font transformation configuration including font attributes.

Font transformations are applied after document loading and font substitution.

The FontTransformation type exposes the following members:

### Methods
| Method | Description |
| :- | :- |
| [create](/conversion/python-net/groupdocs.conversion.contracts/fonttransformation/create/#original_font-replacement_font) | Creates a font transformation with exact font matching (size and style must match). |
| [create_by_name](/conversion/python-net/groupdocs.conversion.contracts/fonttransformation/create_by_name/#original_font_name-replacement_font_name) | Creates a font transformation by name only, matching any size and style. |
| [create_flexible](/conversion/python-net/groupdocs.conversion.contracts/fonttransformation/create_flexible/#original_font-replacement_font-match_any_size-match_any_style) | Creates a font transformation with flexible matching options. |

### Properties
| Property | Description |
| :- | :- |
| [match_any_size](/conversion/python-net/groupdocs.conversion.contracts/fonttransformation/match_any_size/) | The property determines whether any font size for the original font name is matched (true) or the exact font size specified in OriginalFont is matched (false). |
| [match_any_style](/conversion/python-net/groupdocs.conversion.contracts/fonttransformation/match_any_style/) | The property indicates whether any font style (bold, italic, underline) for the original font is matched when true, or the exact font style specified in `OriginalFont` when false. |
| [original_font](/conversion/python-net/groupdocs.conversion.contracts/fonttransformation/original_font/) | The original font specification to match and replace. |
| [replacement_font](/conversion/python-net/groupdocs.conversion.contracts/fonttransformation/replacement_font/) | The replacement font specification. |

### See Also
* module [`groupdocs.conversion.contracts`](/conversion/python-net/groupdocs.conversion.contracts/)
