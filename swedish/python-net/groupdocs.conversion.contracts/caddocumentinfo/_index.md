---
title: "CadDocumentInfo-klass"
second_title: "GroupDocs.Conversion for Python via .NET API-referenser"
description: "Innehåller CAD-dokumentmetadata."
type: docs
url: /sv/python-net/groupdocs.conversion.contracts/caddocumentinfo/
is_root: false
weight: 50
---


## CadDocumentInfo class

Innehåller CAD-dokumentmetadata.

[`DocumentInfo.pages_count`](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/pages_count/) counts the sheets the drawing offers under the load options it was read with.

Utan explicit [`CadLoadOptions.layout_names`](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/layout_names/) är dessa blad modellutrymme, vilket alltid kan plottas och därför alltid är ett blad, samt varje pappersutrymmeslayout vars lagrade sidinställning har en positiv bredd och höjd, begränsad av [`CadLoadOptions.layout_scope`](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/layout_scope/). Explicita layoutnamn vinner helt och hållet istället: bladen blir då de angivna namn som ritningen innehåller, matchade ordinalt, utan att vare sig omfattningen eller sidinställningen filtrerar dem.

För en DWF rapporteras den publicerade siduppsättningen. Det tal under ett är noll, rapporterat när den begärda omfattningen inte matchar något blad i en ritning som erbjuder ett: metadata beskriver fortfarande ritningen, och noll betyder att omfattningen inte väljer något snarare än att misslyckas för den som frågade vad ritningen innehåller. En konvertering med samma inläsningsalternativ misslyckas.

Antalet är därför inte storleken på [`CadDocumentInfo.layouts`](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/layouts/), som listar varje plotkonfiguration som ritningen innehåller, inklusive de som inget blad kan publiceras från, och det förutsäger inte hur många sidor en viss konvertering genererar.

Typen CadDocumentInfo exponerar följande medlemmar:

### Metoder
| Metod | Beskrivning |
| :- | :- |
| [get](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/get/) |  |
| [get_file](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/get_file/) |  |
| [get_string](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/get_string/) |  |

### Egenskaper
| Egenskap | Beskrivning |
| :- | :- |
| [creation_date](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/creation_date/) | Dokumentets skapandedatum. |
| [format](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/format/) | Dokumentformatet. |
| [height](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/height/) | Höjden på CAD-dokumentet. |
| [layers](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/layers/) | Lagerna i dokumentet. |
| [layouts](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/layouts/) | Layouterna i dokumentet. |
| [pages_count](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/pages_count/) | Antalet sidor i dokumentet. |
| [property_names](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/property_names/) | Den uppräkningsbara samlingen av alla egenskaper som kan hämtas för den aktuella dokumentinformationen. |
| [size](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/size/) | Dokumentets storlek i byte. |
| [width](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/width/) | Bredden på CAD-dokumentet. |

### Se även
* module [`groupdocs.conversion.contracts`](/conversion/python-net/groupdocs.conversion.contracts/)
