---
title: PdfRecognitionMode class
second_title: GroupDocs.Conversion for Python via .NET API References
description: 
type: docs
weight: 400
url: /python-net/groupdocs.conversion.options.convert/pdfrecognitionmode/
is_root: false
---

## PdfRecognitionMode class

Allows to control how a PDF document is converted into a word processing document.



**Inheritance:** [`PdfRecognitionMode`](/conversion/python-net/groupdocs.conversion.options.convert/pdfrecognitionmode) → 
[`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration)



The PdfRecognitionMode type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.options.convert/pdfrecognitionmode/__init__/#) | Serialization constructor |


### Properties
| Property | Description |
| :- | :- |
| [TEXTBOX](/conversion/python-net/groupdocs.conversion.options.convert/pdfrecognitionmode/textbox) | This mode is fast and good for maximally preserving original look of the PDF<br/>file, but editability of the resulting document could be limited.<br/>Every visually grouped block of text int the original PDF file is converted into<br/>a textbox in the resulting document. This achieves maximal resemblance of the<br/>output document to the original PDF file. The output document will look good,<br/>but it will consist entirely of textboxes and it could makes further editing<br/>of the document in Microsoft Word quite hard.<br/>This is the default mode. |
| [FLOW](/conversion/python-net/groupdocs.conversion.options.convert/pdfrecognitionmode/flow) | Full recognition mode, the engine performs grouping and multi-level analysis<br/>to restore the original document author's intent and produce a maximally editable<br/>document. The downside is that the output document might look different from<br/>the original PDF file. |


### Methods
| Method | Description |
| :- | :- |
| [equals](/conversion/python-net/groupdocs.conversion.options.convert/pdfrecognitionmode/equals/#groupdocs.conversion.contracts.Enumeration) | Determines whether two object instances are equal. |
| [compare_to](/conversion/python-net/groupdocs.conversion.options.convert/pdfrecognitionmode/compare_to/#any) | Compares current object to other. |



### See Also
* module [`groupdocs.conversion.options.convert`](..)
* class [`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration)
* class [`PdfRecognitionMode`](/conversion/python-net/groupdocs.conversion.options.convert/pdfrecognitionmode)
