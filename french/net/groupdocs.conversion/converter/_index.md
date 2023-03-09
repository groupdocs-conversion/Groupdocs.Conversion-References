---
title: Converter
second_title: Référence de l'API GroupDocs.Conversion pour .NET
description: Représente la classe principale qui contrôle le processus de conversion de document.
type: docs
weight: 730
url: /fr/net/groupdocs.conversion/converter/
---
## Converter class

Représente la classe principale qui contrôle le processus de conversion de document.

```csharp
public sealed class Converter : IConversionSettingsOrConversionFrom, IDisposable
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [Converter](converter#constructor)() | Initialise la nouvelle instance de[`Converter`](../converter) classe pour une configuration de conversion fluide. |
| [Converter](converter#constructor_1)(Func&lt;Stream&gt;) | Initialise la nouvelle instance de[`Converter`](../converter) classe. |
| [Converter](converter#constructor_7)(string) | Initialise la nouvelle instance de[`Converter`](../converter) classe. |
| [Converter](converter#constructor_2)(Func&lt;Stream&gt;, Func&lt;ConverterSettings&gt;) | Initialise la nouvelle instance de[`Converter`](../converter) classe. |
| [Converter](converter#constructor_5)(Func&lt;Stream&gt;, Func&lt;FileType, LoadOptions&gt;) | Initialise la nouvelle instance de[`Converter`](../converter) classe. |
| [Converter](converter#constructor_3)(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;) | Initialise la nouvelle instance de[`Converter`](../converter) classe. |
| [Converter](converter#constructor_8)(string, Func&lt;ConverterSettings&gt;) | Initialise la nouvelle instance de[`Converter`](../converter) classe. |
| [Converter](converter#constructor_11)(string, Func&lt;FileType, LoadOptions&gt;) | Initialise la nouvelle instance de[`Converter`](../converter) classe. |
| [Converter](converter#constructor_9)(string, Func&lt;LoadOptions&gt;) | Initialise la nouvelle instance de[`Converter`](../converter) classe. |
| [Converter](converter#constructor_6)(Func&lt;Stream&gt;, Func&lt;FileType, LoadOptions&gt;, Func&lt;ConverterSettings&gt;) | Initialise la nouvelle instance de[`Converter`](../converter) classe. |
| [Converter](converter#constructor_4)(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;, Func&lt;ConverterSettings&gt;) | Initialise la nouvelle instance de[`Converter`](../converter) classe. |
| [Converter](converter#constructor_12)(string, Func&lt;FileType, LoadOptions&gt;, Func&lt;ConverterSettings&gt;) | Initialise la nouvelle instance de[`Converter`](../converter) classe. |
| [Converter](converter#constructor_10)(string, Func&lt;LoadOptions&gt;, Func&lt;ConverterSettings&gt;) | Initialise la nouvelle instance de[`Converter`](../converter) classe. |

## Méthodes

| Nom | La description |
| --- | --- |
| [Convert](../../groupdocs.conversion/converter/convert#convert_4)(Func&lt;FileType, Stream&gt;, ConvertOptions) | Convertit le document source. Enregistre l'intégralité du document converti. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_7)(Func&lt;FileType, Stream&gt;, Func&lt;string, FileType, ConvertOptions&gt;) | Convertit le document source. Enregistre l'intégralité du document converti. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_12)(Func&lt;int, FileType, Stream&gt;, ConvertOptions) | Convertit le document source. Enregistre le document converti page par page. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_15)(Func&lt;int, FileType, Stream&gt;, Func&lt;string, FileType, ConvertOptions&gt;) | Convertit le document source. Enregistre le document converti page par page. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_8)(Func&lt;int, Stream&gt;, ConvertOptions) | Convertit le document source. Enregistre le document converti page par page. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_11)(Func&lt;int, Stream&gt;, Func&lt;string, FileType, ConvertOptions&gt;) | Convertit le document source. Enregistre le document converti page par page. |
| [Convert](../../groupdocs.conversion/converter/convert#convert)(Func&lt;Stream&gt;, ConvertOptions) | Convertit le document source. Enregistre l'intégralité du document converti. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_3)(Func&lt;Stream&gt;, Func&lt;string, FileType, ConvertOptions&gt;) | Convertit le document source. Enregistre l'intégralité du document converti. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_16)(string, ConvertOptions) | Convertit le document source. Enregistre l'intégralité du document converti. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_5)(Func&lt;FileType, Stream&gt;, Action&lt;Stream, string&gt;, ConvertOptions) | Convertit le document source. Enregistre l'intégralité du document converti. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_6)(Func&lt;FileType, Stream&gt;, Action&lt;Stream, string&gt;, Func&lt;string, FileType, ConvertOptions&gt;) | Convertit le document source. Enregistre l'intégralité du document converti. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_13)(Func&lt;int, FileType, Stream&gt;, Action&lt;int, Stream, string&gt;, ConvertOptions) | Convertit le document source. Enregistre le document converti page par page. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_14)(Func&lt;int, FileType, Stream&gt;, Action&lt;int, Stream, string&gt;, Func&lt;string, FileType, ConvertOptions&gt;) | Convertit le document source. Enregistre le document converti page par page. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_9)(Func&lt;int, Stream&gt;, Action&lt;int, Stream, string&gt;, ConvertOptions) | Convertit le document source. Enregistre le document converti page par page. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_10)(Func&lt;int, Stream&gt;, Action&lt;int, Stream, string&gt;, Func&lt;string, FileType, ConvertOptions&gt;) | Convertit le document source. Enregistre le document converti page par page. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_1)(Func&lt;Stream&gt;, Action&lt;Stream, string&gt;, ConvertOptions) | Convertit le document source. Enregistre l'intégralité du document converti. |
| [Convert](../../groupdocs.conversion/converter/convert#convert_2)(Func&lt;Stream&gt;, Action&lt;Stream, string&gt;, Func&lt;string, FileType, ConvertOptions&gt;) | Convertit le document source. Enregistre l'intégralité du document converti. |
| [Dispose](../../groupdocs.conversion/converter/dispose)() | Libère des ressources. |
| [GetDocumentInfo](../../groupdocs.conversion/converter/getdocumentinfo)() | Obtient les informations sur le document source - le nombre de pages et d'autres propriétés du document spécifiques au type de fichier. |
| [GetPossibleConversions](../../groupdocs.conversion/converter/getpossibleconversions)() | Obtient les conversions possibles pour le document source. |
| [Load](../../groupdocs.conversion/converter/load#load_1)(Func&lt;Stream&gt;) | Configurer le flux de documents source |
| [Load](../../groupdocs.conversion/converter/load#load)(Func&lt;Stream[]&gt;) | Configurer un ensemble de flux de documents source |
| [Load](../../groupdocs.conversion/converter/load#load_2)(string) | Configurer le document source pour la conversion |
| [Load](../../groupdocs.conversion/converter/load#load_3)(string[]) | Configurer un ensemble de documents source |
| [WithSettings](../../groupdocs.conversion/converter/withsettings)(Func&lt;ConverterSettings&gt;) | Configurer les paramètres de conversion |
| static [GetAllPossibleConversions](../../groupdocs.conversion/converter/getallpossibleconversions)() | Obtient toutes les conversions prises en charge |
| static [GetPossibleConversions](../../groupdocs.conversion/converter/getpossibleconversions)(string) | Obtient les conversions prises en charge pour l'extension de document fournie |

### Voir également

* interface [IConversionSettingsOrConversionFrom](../../groupdocs.conversion.fluent/iconversionsettingsorconversionfrom)
* espace de noms [GroupDocs.Conversion](../../groupdocs.conversion)
* Assemblée [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
