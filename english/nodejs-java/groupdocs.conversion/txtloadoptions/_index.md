---
title: TxtLoadOptions
second_title: GroupDocs.Conversion for Node.js via Java API Reference
description: 
type: docs

url: /nodejs-java/groupdocs.conversion/txtloadoptions/
---

## TxtLoadOptions class

 Options for loading Txt documents.
 
| [TxtLoadOptions](txtloadoptions)() | Initializes new instance of TxtLoadOptions class. |

## Functions

| Name | Description |
| --- | --- |
| [getDetectNumberingWithWhitespaces](getdetectnumberingwithwhitespaces)() | Allows to specify how numbered list items are recognized when plain text document is converted. The default value is true. If this option is set to false, lists recognition algorithm detects list paragraphs, when list numbers ends with either dot, right bracket or bullet symbols (such as "•", "*", "-" or "o"). If this option is set to true, whitespaces are also used as list number delimiters: list recognition algorithm for Arabic style numbering (1., 1.1.2.) uses both whitespaces and dot (".") symbols. |
| [getEncoding](getencoding)() | Gets or sets the encoding that will be used when loading Txt document. Can be null. Default is null. |
| [getFormat](getformat)() |  |
| [getLeadingSpacesOptions](getleadingspacesoptions)() | Gets or sets preferred option of a leading space handling. Default value is TxtLeadingSpacesOptions#ConvertToIndent. |
| [getTrailingSpacesOptions](gettrailingspacesoptions)() | Gets or sets preferred option of a trailing space handling. Default value is TxtTrailingSpacesOptions#Trim. |
| [setDetectNumberingWithWhitespaces](setdetectnumberingwithwhitespaces)(boolean) | Allows to specify how numbered list items are recognized when plain text document is converted. The default value is true. If this option is set to false, lists recognition algorithm detects list paragraphs, when list numbers ends with either dot, right bracket or bullet symbols (such as "•", "*", "-" or "o"). If this option is set to true, whitespaces are also used as list number delimiters: list recognition algorithm for Arabic style numbering (1., 1.1.2.) uses both whitespaces and dot (".") symbols. |
| [setEncoding](setencoding)(Charset) | Gets or sets the encoding that will be used when loading Txt document. Can be null. Default is null. |
| [setLeadingSpacesOptions](setleadingspacesoptions)([TxtLeadingSpacesOptions](../txtleadingspacesoptions)) | Gets or sets preferred option of a leading space handling. Default value is TxtLeadingSpacesOptions#ConvertToIndent. |
| [setTrailingSpacesOptions](settrailingspacesoptions)([TxtTrailingSpacesOptions](../txttrailingspacesoptions)) | Gets or sets preferred option of a trailing space handling. Default value is TxtTrailingSpacesOptions#Trim. |
