---
title: "CadDocumentInfo klasse"
second_title: "GroupDocs.Conversion for Python via .NET API-referenties"
description: "Bevat metadata van Cad-documenten."
type: docs
url: /nl/python-net/groupdocs.conversion.contracts/caddocumentinfo/
is_root: false
weight: 50
---


## CadDocumentInfo class

Bevat metadata van Cad-documenten.

[`DocumentInfo.pages_count`](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/pages_count/) counts the sheets the drawing offers under the load options it was read with.

Zonder expliciete [`CadLoadOptions.layout_names`](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/layout_names/) zijn die bladen modelruimte, die altijd plotbaar is en daarom altijd een blad is, plus elke papier-ruimte lay-out waarvan de opgeslagen pagina‑instelling een positieve breedte en hoogte heeft, beperkt door [`CadLoadOptions.layout_scope`](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/layout_scope/). Expliciete lay-outnamen winnen direct: de bladen zijn dan de opgegeven namen die de tekening bevat, ordinaal gematcht, zonder dat de scope of de pagina‑instelling ze filtert.

Voor een DWF wordt de gepubliceerde pagina‑set gerapporteerd. Het aantal onder één is nul, gerapporteerd wanneer de gevraagde scope geen blad van een tekening vindt die er één aanbiedt: de metadata beschrijft de tekening nog steeds, en nul geeft aan dat de scope niets selecteert in plaats van de aanroeper te laten falen die vroeg wat de tekening bevat. Een conversie onder diezelfde laadopties faalt.

Het aantal is daarom niet de grootte van [`CadDocumentInfo.layouts`](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/layouts/), die elke plotconfiguratie die de tekening bevat opsomt, inclusief die waarvan geen blad kan worden gepubliceerd, en het voorspelt niet hoeveel pagina's een specifieke conversie genereert.

Het CadDocumentInfo-type geeft de volgende leden weer:

### Methoden
| Methode | Beschrijving |
| :- | :- |
| [get](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/get/) |  |
| [get_file](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/get_file/) |  |
| [get_string](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/get_string/) |  |

### Eigenschappen
| Eigenschap | Beschrijving |
| :- | :- |
| [creation_date](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/creation_date/) | De aanmaakdatum van het document. |
| [format](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/format/) | Het documentformaat. |
| [height](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/height/) | De hoogte van het CAD‑document. |
| [layers](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/layers/) | De lagen in het document. |
| [layouts](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/layouts/) | De lay-outs in het document. |
| [pages_count](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/pages_count/) | Het aantal pagina's van het document. |
| [property_names](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/property_names/) | De enumeratie van alle eigenschappen die kunnen worden opgehaald voor de huidige documentinformatie. |
| [size](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/size/) | De documentgrootte in bytes. |
| [width](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/width/) | De breedte van het CAD‑document. |

### Zie ook
* module [`groupdocs.conversion.contracts`](/conversion/python-net/groupdocs.conversion.contracts/)
