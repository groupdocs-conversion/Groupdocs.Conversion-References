---
title: "ConversionEvents Klasse"
second_title: "GroupDocs.Conversion für Python über .NET API-Referenzen"
description: "Aggregiert Ereignis‑Handler des Konvertierungslebenszyklus."
type: docs
url: /de/python-net/groupdocs.conversion/conversionevents/
is_root: false
weight: 20
---


## ConversionEvents class

Aggregiert Ereignis‑Handler des Konvertierungslebenszyklus.

Übergeben Sie eine Instanz an den Konstruktor von [`Converter`](/conversion/python-net/groupdocs.conversion/converter/) im Parameter `events` oder an die Fluent-Methode `WithEvents`.

Bevorzugen Sie dies gegenüber den einzelnen Handler-Eigenschaften von [`ConverterSettings`](/conversion/python-net/groupdocs.conversion/convertersettings/), die veraltet sind.

Der ConversionEvents-Typ stellt die folgenden Mitglieder bereit:

### Konstruktoren
| Konstruktor | Beschreibung |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion/conversionevents/__init__/) |  |

### Eigenschaften
| Eigenschaft | Beschreibung |
| :- | :- |
| [on_compression_completed](/conversion/python-net/groupdocs.conversion/conversionevents/on_compression_completed/) | Das Ereignis, das ausgelöst wird, wenn die Kompression der Konvertierungsausgabe abgeschlossen ist. Wird nur in Builds aufgerufen, die die Kompressionspipeline (LIB_ZIP) enthalten. |
| [on_conversion_completed](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_completed/) | Das Ereignis, das einmal ausgelöst wird, wenn der Konvertierungslauf beendet ist, unabhängig von Erfolg oder Misserfolg. |
| [on_conversion_progress](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_progress/) | Der Konvertierungsfortschritt als Prozentsatz (0–100), periodisch ausgelöst. |
| [on_conversion_started](/conversion/python-net/groupdocs.conversion/conversionevents/on_conversion_started/) | Das Ereignis, das einmal zu Beginn des Konvertierungslaufs ausgelöst wird, bevor ein Dokument verarbeitet wird. |
| [on_document_converted](/conversion/python-net/groupdocs.conversion/conversionevents/on_document_converted/) | Das Ereignis wird einmal pro Gesamtdokumentkonvertierung ausgelöst, die erfolgreich abgeschlossen wird. |
| [on_document_failed](/conversion/python-net/groupdocs.conversion/conversionevents/on_document_failed/) | Das Ereignis wird einmal pro Gesamtdokumentkonvertierung ausgelöst, die fehlschlägt. |
| [on_font_substituted](/conversion/python-net/groupdocs.conversion/conversionevents/on_font_substituted/) | Das Ereignis wird ausgelöst, wenn eine im Quell‑Dokument referenzierte Schriftart nicht verfügbar ist und ersetzt wird (entweder durch eine vom Kunden bereitgestellte [`FontSubstitute`](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitute/) Regel, durch die konfigurierte Standardschriftart oder durch den internen Fallback der Konvertierungspipeline). |
| [on_page_converted](/conversion/python-net/groupdocs.conversion/conversionevents/on_page_converted/) | Das Ereignis wird einmal pro Seite ausgelöst, wenn eine Seitenkonvertierung erfolgreich abgeschlossen wird. |
| [on_page_failed](/conversion/python-net/groupdocs.conversion/conversionevents/on_page_failed/) | Das Ereignis wird einmal pro Seite ausgelöst, wenn eine Seitenkonvertierung fehlschlägt. |

### Siehe auch
* module [`groupdocs.conversion`](/conversion/python-net/groupdocs.conversion/)
