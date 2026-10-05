---
title: "Klasse CadDocumentInfo"
second_title: "GroupDocs.Conversion für Python über .NET API-Referenzen"
description: "Enthält CAD-Dokument-Metadaten."
type: docs
url: /de/python-net/groupdocs.conversion.contracts/caddocumentinfo/
is_root: false
weight: 50
---


## CadDocumentInfo class

Enthält CAD-Dokument-Metadaten.

[`DocumentInfo.pages_count`](/conversion/python-net/groupdocs.conversion.contracts/documentinfo/pages_count/) counts the sheets the drawing offers under the load options it was read with.

Ohne explizite [`CadLoadOptions.layout_names`](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/layout_names/) sind diese Blätter der Modellraum, der immer plotbar und daher immer ein Blatt ist, plus jedes Papierraum‑Layout, dessen gespeicherte Seiteneinrichtung eine positive Breite und Höhe hat, eingeschränkt durch [`CadLoadOptions.layout_scope`](/conversion/python-net/groupdocs.conversion.options.load/cadloadoptions/layout_scope/). Explizite Layoutnamen gewinnen stattdessen eindeutig: Die Blätter sind dann die vom Zeichenobjekt mitgelieferten Namen, ordinal zugeordnet, wobei weder der Geltungsbereich noch die Seiteneinrichtung sie filtern.

Für ein DWF wird das veröffentlichte Seiten-Set gemeldet. Der Zähler unter eins ist null, gemeldet wenn der angeforderte Geltungsbereich kein Blatt einer Zeichnung findet, das eines anbietet: Die Metadaten beschreiben die Zeichnung weiterhin, und null bedeutet, dass der Geltungsbereich nichts auswählt, anstatt den Aufrufer, der nach dem Inhalt der Zeichnung fragt, fehlschlagen zu lassen. Eine Konvertierung mit denselben Ladeoptionen schlägt fehl.

Der Zähler entspricht daher nicht der Größe von [`CadDocumentInfo.layouts`](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/layouts/), die jede Plot‑Konfiguration auflistet, die die Zeichnung enthält, einschließlich jener, aus denen kein Blatt veröffentlicht werden kann, und er sagt nicht voraus, wie viele Seiten eine bestimmte Konvertierung erzeugt.

Der Typ CadDocumentInfo stellt die folgenden Mitglieder bereit:

### Methoden
| Methode | Beschreibung |
| :- | :- |
| [get](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/get/) |  |
| [get_file](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/get_file/) |  |
| [get_string](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/get_string/) |  |

### Eigenschaften
| Eigenschaft | Beschreibung |
| :- | :- |
| [creation_date](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/creation_date/) | Das Erstellungsdatum des Dokuments. |
| [format](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/format/) | Das Dokumentformat. |
| [height](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/height/) | Die Höhe des CAD-Dokuments. |
| [layers](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/layers/) | Die Ebenen im Dokument. |
| [layouts](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/layouts/) | Die Layouts im Dokument. |
| [pages_count](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/pages_count/) | Die Seitenanzahl des Dokuments. |
| [property_names](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/property_names/) | Die Aufzählung aller Eigenschaften, die für die aktuelle Dokumentinformation abgerufen werden können. |
| [size](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/size/) | Die Dokumentgröße in Bytes. |
| [width](/conversion/python-net/groupdocs.conversion.contracts/caddocumentinfo/width/) | Die Breite des CAD-Dokuments. |

### Siehe auch
* module [`groupdocs.conversion.contracts`](/conversion/python-net/groupdocs.conversion.contracts/)
