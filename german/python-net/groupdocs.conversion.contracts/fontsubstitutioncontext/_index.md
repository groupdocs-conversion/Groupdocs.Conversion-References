---
title: "FontSubstitutionContext Klasse"
second_title: "GroupDocs.Conversion für Python über .NET API-Referenzen"
description: "Beschreibt eine einzelne Schriftart-Substitution, die beim Laden oder Rendern eines Quelldokuments auftrat."
type: docs
url: /de/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/
is_root: false
weight: 190
---


## FontSubstitutionContext class

Beschreibt eine einzelne Schriftart-Substitution, die beim Laden oder Rendern eines Quelldokuments auftrat.

Instanzen werden an [`ConversionEvents.on_font_substituted`](/conversion/python-net/groupdocs.conversion/conversionevents/on_font_substituted/) übergeben.

Der FontSubstitutionContext Typ stellt die folgenden Mitglieder bereit:

### Konstruktoren
| Konstruktor | Beschreibung |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/__init__/#source_file_name-original_font_name-substitute_font_name-reason) | Initialisiert einen neuen FontSubstitutionContext. |

### Eigenschaften
| Eigenschaft | Beschreibung |
| :- | :- |
| [original_font_name](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/original_font_name/) | Der Name der Schriftart, die im Quelldokument referenziert wird, aber für die Konvertierungspipeline nicht verfügbar ist. |
| [reason](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/reason/) | Die Ersetzungsmeldung exakt wie von der Konvertierungspipeline gemeldet, wortwörtlich und ungeparst. |
| [source_file_name](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/source_file_name/) | Der Dateiname des zu konvertierenden Quelldokuments. Wenn die Quelle als Stream bereitgestellt wurde, der kein `io.RawIOBase` ist, enthält dieses Feld eine generierte Kennung anstelle eines echten Dateinamens. |
| [substitute_font_name](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/substitute_font_name/) | Der Name der als Ersatz verwendeten Schriftart. Kann None sein für Dokumente, deren Engine die Ersetzung nur als beschreibenden Text meldet — in diesem Fall lesen Sie [`FontSubstitutionContext.reason`](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/reason/). |

### Siehe auch
* module [`groupdocs.conversion.contracts`](/conversion/python-net/groupdocs.conversion.contracts/)
