---
title: PossibleConversions
second_title: GroupDocs.Conversion for Node.js via Java API Reference
description: 
type: docs

url: /nodejs-java/groupdocs.conversion/possibleconversions/
---

## PossibleConversions class
Represents a mapping what conversion pairs are supported for specific source file format
| [PossibleConversions](possibleconversions)([FileType](../filetype)) | Creates possible conversion list for specified source file format |

## Functions

| Name | Description |
| --- | --- |
| [add](add)([ConversionPair](../conversionpair)) | Add conversion pair |
| [forTarget](fortarget)([FileType](../filetype)) | Find conversion pair in current list for target file type |
| [getAll](getall)() | All target file types and primary/secondary flag |
| [getLoadOptions](getloadoptions)() | Predefined load options which could be used to convert from current type |
| [getPrimary](getprimary)() | Primary target file types |
| [getSecondary](getsecondary)() | Secondary target file types |
| [getSource](getsource)() | Source file formats |
| [getTargetConversion](gettargetconversion)([FileType](../filetype)) | Returns target conversion for specified target file type |
| [getTargetConversion](gettargetconversion)(String) |  |
