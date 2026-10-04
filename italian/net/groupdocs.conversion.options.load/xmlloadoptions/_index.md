---
title: "XmlLoadOptions"
second_title: "Riferimento API di GroupDocs.Conversion per .NET"
description: "Opzioni per il caricamento di documenti XML."
type: docs
weight: 2960
url: /it/net/groupdocs.conversion.options.load/xmlloadoptions/
---
## XmlLoadOptions class

Opzioni per il caricamento di documenti XML.

```csharp
public sealed class XmlLoadOptions : WebLoadOptions
```

## Costruttori

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [XmlLoadOptions](xmlloadoptions)() | Inizializza una nuova istanza della classe [`XmlLoadOptions`](../xmlloadoptions). |

## Proprietà

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| [BasePath](../../groupdocs.conversion.options.load/webloadoptions/basepath) { get; set; } | Il percorso/base URL per l'HTML |
| [ConfigureHeaders](../../groupdocs.conversion.options.load/webloadoptions/configureheaders) { get; set; } | Azione per la configurazione delle intestazioni della richiesta. Il primo parametro dell'azione è l'Uri. |
| [CredentialsProvider](../../groupdocs.conversion.options.load/webloadoptions/credentialsprovider) { get; set; } | Fornitore di credenziali per l'Uri. |
| [CustomCssStyle](../../groupdocs.conversion.options.load/webloadoptions/customcssstyle) { get; set; } | Implementa [`CustomCssStyle`](../icustomcssstyleoptions/customcssstyle) |
| [Encoding](../../groupdocs.conversion.options.load/webloadoptions/encoding) { get; set; } | Ottiene o imposta la codifica da utilizzare durante il caricamento del documento web. Se la proprietà è null, la codifica verrà determinata dall'attributo del set di caratteri del documento. |
| [Format](../../groupdocs.conversion.options.load/xmlloadoptions/format) { get; } | Tipo di file del documento di input. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | Tipo di file del documento di input. |
| [HtmlRenderingMode](../../groupdocs.conversion.options.load/webloadoptions/htmlrenderingmode) { get; set; } | Controlla come viene renderizzato il contenuto HTML. Predefinito: AbsolutePositioning |
| [MarginSettings](../../groupdocs.conversion.options.load/webloadoptions/marginsettings) { get; set; } | Impostazioni dei margini di pagina |
| [OrientationSettings](../../groupdocs.conversion.options.load/webloadoptions/orientationsettings) { get; set; } | Impostazioni dell'orientamento della pagina |
| [PageLayoutOptions](../../groupdocs.conversion.options.load/webloadoptions/pagelayoutoptions) { get; set; } | Specifica le opzioni di layout della pagina durante il caricamento dei documenti web. |
| [PageNumbering](../../groupdocs.conversion.options.load/webloadoptions/pagenumbering) { get; set; } | Abilita o disabilita la generazione della numerazione di pagina nel documento convertito. Predefinito: false |
| [ResourceLoadingTimeout](../../groupdocs.conversion.options.load/webloadoptions/resourceloadingtimeout) { get; set; } | Timeout per il caricamento delle risorse esterne |
| [SizeSettings](../../groupdocs.conversion.options.load/webloadoptions/sizesettings) { get; set; } | Impostazioni delle dimensioni della pagina |
| [SkipExternalResources](../../groupdocs.conversion.options.load/webloadoptions/skipexternalresources) { get; set; } | Implementa [`SkipExternalResources`](../iresourceloadingoptions/skipexternalresources) |
| [UseAsDataSource](../../groupdocs.conversion.options.load/xmlloadoptions/useasdatasource) { get; set; } | Utilizza documento Xml come origine dati |
| [UsePdf](../../groupdocs.conversion.options.load/webloadoptions/usepdf) { get; set; } | Utilizza pdf per la conversione. Predefinito: false |
| [WhitelistedResources](../../groupdocs.conversion.options.load/webloadoptions/whitelistedresources) { get; set; } | Implementa [`WhitelistedResources`](../iresourceloadingoptions/whitelistedresources) |
| [XslFoFactory](../../groupdocs.conversion.options.load/xmlloadoptions/xslfofactory) { get; set; } | Flusso di documento XSL-FO per convertire XML usando il file di markup XSL-FO. |
| [XsltFactory](../../groupdocs.conversion.options.load/xmlloadoptions/xsltfactory) { get; set; } | Flusso di documento XSLT per convertire XML eseguendo la trasformazione XSL in HTML. |
| [Zoom](../../groupdocs.conversion.options.load/webloadoptions/zoom) { get; set; } | Specifica il livello di zoom come percentuale. Il livello di zoom viene applicato al tag &lt;body&gt; del documento prima della conversione, scalando l'aspetto visivo del documento. Un valore del 100% rappresenta la dimensione originale. Il valore predefinito è 100. |

## Vedi anche

| IConversionByPageCompletedOrConvert | Descrizione |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | Determina se due istanze di oggetti sono uguali. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | Determina se due istanze di oggetti sono uguali. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | Funziona come funzione hash predefinita. |

### IConversionConvertOptions

* class [WebLoadOptions](../webloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- NON MODIFICARE: generato da xmldocmd per GroupDocs.conversion.dll -->
