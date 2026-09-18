---
title: FontSubstitutionContext class
second_title: GroupDocs.Conversion for Python via .NET API References
description: "Describes a single font substitution that occurred while loading or rendering a source document."
type: docs
url: /python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/
is_root: false
weight: 190
---


## FontSubstitutionContext class

Describes a single font substitution that occurred while loading or rendering a source document.

Instances are passed to [`ConversionEvents.on_font_substituted`](/conversion/python-net/groupdocs.conversion/conversionevents/on_font_substituted/).

The FontSubstitutionContext type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/__init__/#source_file_name-original_font_name-substitute_font_name-reason) | Initializes a new FontSubstitutionContext. |

### Properties
| Property | Description |
| :- | :- |
| [original_font_name](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/original_font_name/) | The name of the font referenced by the source document but unavailable to the conversion pipeline. |
| [reason](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/reason/) | The substitution message exactly as reported by the conversion pipeline, verbatim and unparsed. |
| [source_file_name](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/source_file_name/) | The file name of the source document being converted. When the source was provided as a stream that is not a `io.RawIOBase`, this contains a generated identifier rather than a real file name. |
| [substitute_font_name](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/substitute_font_name/) | The name of the font used as a substitute. May be None for documents whose engine reports the substitution only as descriptive text — in that case read [`FontSubstitutionContext.reason`](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/reason/). |

### See Also
* module [`groupdocs.conversion.contracts`](/conversion/python-net/groupdocs.conversion.contracts/)
