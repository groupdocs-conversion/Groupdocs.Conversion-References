---
title: Converter
second_title: GroupDocs.Conversion für .NET-API-Referenz
description: Stellt die Hauptklasse dar die den Dokumentenkonvertierungsprozess steuert.
type: docs
weight: 730
url: /de/net/groupdocs.conversion/converter/
---
## Converter class

Stellt die Hauptklasse dar, die den Dokumentenkonvertierungsprozess steuert.

```csharp
public sealed class Converter : IConversionSettingsOrConversionFrom, IDisposable
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [Converter](converter#constructor)() | Initialisiert eine neue Instanz von[`Converter`](../converter) Klasse für die Einrichtung der fließenden Konvertierung. |
| [Converter](converter#constructor_1)(Func&lt;Stream&gt;) | Initialisiert eine neue Instanz von[`Converter`](../converter) Klasse. |
| [Converter](converter#constructor_7)(string) | Initialisiert eine neue Instanz von[`Converter`](../converter) Klasse. |
| [Converter](converter#constructor_2)(Func&lt;Stream&gt;, Func&lt;ConverterSettings&gt;) | Initialisiert eine neue Instanz von[`Converter`](../converter) Klasse. |
| [Converter](converter#constructor_5)(Func&lt;Stream&gt;, Func&lt;FileType, LoadOptions&gt;) | Initialisiert eine neue Instanz von[`Converter`](../converter) Klasse. |
| [Converter](converter#constructor_3)(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;) | Initialisiert eine neue Instanz von[`Converter`](../converter) Klasse. |
| [Converter](converter#constructor_8)(string, Func&lt;ConverterSettings&gt;) | Initialisiert eine neue Instanz von[`Converter`](../converter) Klasse. |
| [Converter](converter#constructor_11)(string, Func&lt;FileType, LoadOptions&gt;) | Initialisiert eine neue Instanz von[`Converter`](../converter) Klasse. |
| [Converter](converter#constructor_9)(string, Func&lt;LoadOptions&gt;) | Initialisiert eine neue Instanz von[`Converter`](../converter) Klasse. |
| [Converter](converter#constructor_6)(Func&lt;Stream&gt;, Func&lt;FileType, LoadOptions&gt;, Func&lt;ConverterSettings&gt;) | Initialisiert eine neue Instanz von[`Converter`](../converter) Klasse. |
| [Converter](converter#constructor_4)(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;, Func&lt;ConverterSettings&gt;) | Initialisiert eine neue Instanz von[`Converter`](../converter) Klasse. |
| [Converter](converter#constructor_12)(string, Func&lt;FileType, LoadOptions&gt;, Func&lt;ConverterSettings&gt;) | Initialisiert eine neue Instanz von[`Converter`](../converter) Klasse. |
| [Converter](converter#constructor_10)(string, Func&lt;LoadOptions&gt;, Func&lt;ConverterSettings&gt;) | Initialisiert eine neue Instanz von[`Converter`](../converter) Klasse. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Convert](../../groupdocs.conversion/converter/convert#convert_4)(Func&lt;FileType, Stream&gt;, ConvertOptions) | Konvertiert Quelldokument. Speichert das gesamte konvertierte Dokument. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_7)(Func&lt;FileType, Stream&gt;, Func&lt;string, FileType, ConvertOptions&gt;) | Konvertiert Quelldokument. Speichert das gesamte konvertierte Dokument. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_12)(Func&lt;int, FileType, Stream&gt;, ConvertOptions) | Konvertiert Quelldokument. Speichert das konvertierte Dokument Seite für Seite. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_15)(Func&lt;int, FileType, Stream&gt;, Func&lt;string, FileType, ConvertOptions&gt;) | Konvertiert Quelldokument. Speichert das konvertierte Dokument Seite für Seite. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_8)(Func&lt;int, Stream&gt;, ConvertOptions) | Konvertiert Quelldokument. Speichert das konvertierte Dokument Seite für Seite. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_11)(Func&lt;int, Stream&gt;, Func&lt;string, FileType, ConvertOptions&gt;) | Konvertiert Quelldokument. Speichert das konvertierte Dokument Seite für Seite. |
| [Convert](../../groupdocs.conversion/converter/convert#convert)(Func&lt;Stream&gt;, ConvertOptions) | Konvertiert Quelldokument. Speichert das gesamte konvertierte Dokument. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_3)(Func&lt;Stream&gt;, Func&lt;string, FileType, ConvertOptions&gt;) | Konvertiert Quelldokument. Speichert das gesamte konvertierte Dokument. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_16)(string, ConvertOptions) | Konvertiert Quelldokument. Speichert das gesamte konvertierte Dokument. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_5)(Func&lt;FileType, Stream&gt;, Action&lt;Stream, string&gt;, ConvertOptions) | Konvertiert Quelldokument. Speichert das gesamte konvertierte Dokument. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_6)(Func&lt;FileType, Stream&gt;, Action&lt;Stream, string&gt;, Func&lt;string, FileType, ConvertOptions&gt;) | Konvertiert Quelldokument. Speichert das gesamte konvertierte Dokument. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_13)(Func&lt;int, FileType, Stream&gt;, Action&lt;int, Stream, string&gt;, ConvertOptions) | Konvertiert Quelldokument. Speichert das konvertierte Dokument Seite für Seite. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_14)(Func&lt;int, FileType, Stream&gt;, Action&lt;int, Stream, string&gt;, Func&lt;string, FileType, ConvertOptions&gt;) | Konvertiert Quelldokument. Speichert das konvertierte Dokument Seite für Seite. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_9)(Func&lt;int, Stream&gt;, Action&lt;int, Stream, string&gt;, ConvertOptions) | Konvertiert Quelldokument. Speichert das konvertierte Dokument Seite für Seite. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_10)(Func&lt;int, Stream&gt;, Action&lt;int, Stream, string&gt;, Func&lt;string, FileType, ConvertOptions&gt;) | Konvertiert Quelldokument. Speichert das konvertierte Dokument Seite für Seite. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_1)(Func&lt;Stream&gt;, Action&lt;Stream, string&gt;, ConvertOptions) | Konvertiert Quelldokument. Speichert das gesamte konvertierte Dokument. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_2)(Func&lt;Stream&gt;, Action&lt;Stream, string&gt;, Func&lt;string, FileType, ConvertOptions&gt;) | Konvertiert Quelldokument. Speichert das gesamte konvertierte Dokument. |
| [Dispose](../../groupdocs.conversion/converter/dispose)() | Gibt Ressourcen frei. |
| [GetDocumentInfo](../../groupdocs.conversion/converter/getdocumentinfo)() | Ruft Quelldokumentinformationen ab – Seitenzahl und andere Dokumenteigenschaften, die für den Dateityp spezifisch sind. |
| [GetPossibleConversions](../../groupdocs.conversion/converter/getpossibleconversions)() | Ruft mögliche Konvertierungen für das Quelldokument ab. |
| [Load](../../groupdocs.conversion/converter/load#load_1)(Func&lt;Stream&gt;) | Quelldokument stream konfigurieren |
| [Load](../../groupdocs.conversion/converter/load#load)(Func&lt;Stream[]&gt;) | Satz von Quelldokumenten konfigurieren streams |
| [Load](../../groupdocs.conversion/converter/load#load_2)(string) | Quelldokument für Konvertierung konfigurieren |
| [Load](../../groupdocs.conversion/converter/load#load_3)(string[]) | Satz von Quelldokumenten konfigurieren |
| [WithSettings](../../groupdocs.conversion/converter/withsettings)(Func&lt;ConverterSettings&gt;) | Konvertierungseinstellungen konfigurieren |
| static [GetAllPossibleConversions](../../groupdocs.conversion/converter/getallpossibleconversions)() | Ruft alle unterstützten Konvertierungen ab |
| static [GetPossibleConversions](../../groupdocs.conversion/converter/getpossibleconversions)(string) | Ruft unterstützte Konvertierungen für die bereitgestellte Dokumenterweiterung ab |

### Siehe auch

* interface [IConversionSettingsOrConversionFrom](../../groupdocs.conversion.fluent/iconversionsettingsorconversionfrom)
* namensraum [GroupDocs.Conversion](../../groupdocs.conversion)
* Montage [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
