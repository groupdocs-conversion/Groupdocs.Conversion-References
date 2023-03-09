---
title: Converter
second_title: Référence de l'API GroupDocs.Conversion pour .NET
description: Initialise la nouvelle instance deConvertergroupdocs.conversion/converter classe.
type: docs
weight: 10
url: /fr/net/groupdocs.conversion/converter/converter/
---
## Converter(Func&lt;Stream&gt;) {#constructor_1}

Initialise la nouvelle instance de[`Converter`](../../converter) classe.

```csharp
public Converter(Func<Stream> document)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| document | Func`1 | La méthode qui renvoie un flux lisible. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Jeté quand*document* est nul. |

### Remarques

**Apprendre encore plus**

* En savoir plus sur le chargement et la conversion de documents stockés sur FTP, Amazon S3 Storage, Windows Azure ou tout autre stockage tiers : [Chargement d'un document à partir de différentes sources](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* En savoir plus sur les options de chargement de document en fonction du type de fichier : [Options de chargement pour différents types de documents](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Voir également

* class [Converter](../../converter)
* espace de noms [GroupDocs.Conversion](../../converter)
* Assemblée [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;ConverterSettings&gt;) {#constructor_2}

Initialise la nouvelle instance de[`Converter`](../../converter) classe.

```csharp
public Converter(Func<Stream> document, Func<ConverterSettings> settings)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| document | Func`1 | La méthode qui renvoie un flux lisible. |
| settings | Func`1 | Les paramètres du convertisseur. |

### Remarques

**Apprendre encore plus**

* En savoir plus sur le chargement et la conversion de documents stockés sur FTP, Amazon S3 Storage, Windows Azure ou tout autre stockage tiers : [Chargement d'un document à partir de différentes sources](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* En savoir plus sur les options de chargement de document en fonction du type de fichier : [Options de chargement pour différents types de documents](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Voir également

* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* espace de noms [GroupDocs.Conversion](../../converter)
* Assemblée [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;) {#constructor_3}

Initialise la nouvelle instance de[`Converter`](../../converter) classe.

```csharp
public Converter(Func<Stream> document, Func<LoadOptions> loadOptions)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| document | Func`1 | La méthode qui renvoie un flux lisible. |
| loadOptions | Func`1 | Les méthodes qui renvoient les options de chargement de document. |

### Remarques

**Apprendre encore plus**

* En savoir plus sur le chargement et la conversion de documents stockés sur FTP, Amazon S3 Storage, Windows Azure ou tout autre stockage tiers : [Chargement d'un document à partir de différentes sources](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* En savoir plus sur les options de chargement de document en fonction du type de fichier : [Options de chargement pour différents types de documents](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Voir également

* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [Converter](../../converter)
* espace de noms [GroupDocs.Conversion](../../converter)
* Assemblée [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;, Func&lt;ConverterSettings&gt;) {#constructor_4}

Initialise la nouvelle instance de[`Converter`](../../converter) classe.

```csharp
public Converter(Func<Stream> document, Func<LoadOptions> loadOptions, 
    Func<ConverterSettings> settings)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| document | Func`1 | La méthode qui renvoie un flux lisible. |
| loadOptions | Func`1 | Les méthodes qui renvoient les options de chargement de document. |
| settings | Func`1 | Les paramètres du convertisseur. |

### Remarques

**Apprendre encore plus**

* En savoir plus sur le chargement et la conversion de documents stockés sur FTP, Amazon S3 Storage, Windows Azure ou tout autre stockage tiers : [Chargement d'un document à partir de différentes sources](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* En savoir plus sur les options de chargement de document en fonction du type de fichier : [Options de chargement pour différents types de documents](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Voir également

* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* espace de noms [GroupDocs.Conversion](../../converter)
* Assemblée [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;FileType, LoadOptions&gt;) {#constructor_5}

Initialise la nouvelle instance de[`Converter`](../../converter) classe.

```csharp
public Converter(Func<Stream> document, Func<FileType, LoadOptions> loadOptions)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| document | Func`1 | La méthode qui renvoie un flux lisible. |
| loadOptions | Func`2 | Les méthodes qui renvoient les options de chargement de document. Le type du fichier source |

### Remarques

**Apprendre encore plus**

* En savoir plus sur le chargement et la conversion de documents stockés sur FTP, Amazon S3 Storage, Windows Azure ou tout autre stockage tiers : [Chargement d'un document à partir de différentes sources](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* En savoir plus sur les options de chargement de document en fonction du type de fichier : [Options de chargement pour différents types de documents](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Voir également

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [Converter](../../converter)
* espace de noms [GroupDocs.Conversion](../../converter)
* Assemblée [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;FileType, LoadOptions&gt;, Func&lt;ConverterSettings&gt;) {#constructor_6}

Initialise la nouvelle instance de[`Converter`](../../converter) classe.

```csharp
public Converter(Func<Stream> document, Func<FileType, LoadOptions> loadOptions, 
    Func<ConverterSettings> settings)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| document | Func`1 | La méthode qui renvoie un flux lisible. |
| loadOptions | Func`2 | Les méthodes qui renvoient les options de chargement de document. Le type du fichier source |
| settings | Func`1 | Les paramètres du convertisseur. |

### Remarques

**Apprendre encore plus**

* En savoir plus sur le chargement et la conversion de documents stockés sur FTP, Amazon S3 Storage, Windows Azure ou tout autre stockage tiers : [Chargement d'un document à partir de différentes sources](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* En savoir plus sur les options de chargement de document en fonction du type de fichier : [Options de chargement pour différents types de documents](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Voir également

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* espace de noms [GroupDocs.Conversion](../../converter)
* Assemblée [GroupDocs.Conversion](../../../)

---

## Converter(string) {#constructor_7}

Initialise la nouvelle instance de[`Converter`](../../converter) classe.

```csharp
public Converter(string filePath)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| filePath | String | Le chemin du fichier vers le document source. |

### Remarques

**Apprendre encore plus**

* En savoir plus sur le chargement et la conversion de documents stockés sur FTP, Amazon S3 Storage, Windows Azure ou tout autre stockage tiers : [Chargement d'un document à partir de différentes sources](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* En savoir plus sur les options de chargement de document en fonction du type de fichier : [Options de chargement pour différents types de documents](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Voir également

* class [Converter](../../converter)
* espace de noms [GroupDocs.Conversion](../../converter)
* Assemblée [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;ConverterSettings&gt;) {#constructor_8}

Initialise la nouvelle instance de[`Converter`](../../converter) classe.

```csharp
public Converter(string filePath, Func<ConverterSettings> settings)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| filePath | String | Le chemin du fichier vers le document source. |
| settings | Func`1 | Les paramètres du convertisseur. |

### Remarques

**Apprendre encore plus**

* En savoir plus sur le chargement et la conversion de documents stockés sur FTP, Amazon S3 Storage, Windows Azure ou tout autre stockage tiers : [Chargement d'un document à partir de différentes sources](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* En savoir plus sur les options de chargement de document en fonction du type de fichier : [Options de chargement pour différents types de documents](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Voir également

* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* espace de noms [GroupDocs.Conversion](../../converter)
* Assemblée [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;LoadOptions&gt;) {#constructor_9}

Initialise la nouvelle instance de[`Converter`](../../converter) classe.

```csharp
public Converter(string filePath, Func<LoadOptions> loadOptions)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| filePath | String | Le chemin du fichier vers le document source. |
| loadOptions | Func`1 | Les méthodes qui renvoient les options de chargement de document. |

### Remarques

**Apprendre encore plus**

* En savoir plus sur le chargement et la conversion de documents stockés sur FTP, Amazon S3 Storage, Windows Azure ou tout autre stockage tiers : [Chargement d'un document à partir de différentes sources](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* En savoir plus sur les options de chargement de document en fonction du type de fichier : [Options de chargement pour différents types de documents](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Voir également

* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [Converter](../../converter)
* espace de noms [GroupDocs.Conversion](../../converter)
* Assemblée [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;LoadOptions&gt;, Func&lt;ConverterSettings&gt;) {#constructor_10}

Initialise la nouvelle instance de[`Converter`](../../converter) classe.

```csharp
public Converter(string filePath, Func<LoadOptions> loadOptions, Func<ConverterSettings> settings)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| filePath | String | Le chemin du fichier vers le document source. |
| loadOptions | Func`1 | Les méthodes qui renvoient les options de chargement de document. |
| settings | Func`1 | Les paramètres du convertisseur. |

### Remarques

**Apprendre encore plus**

* En savoir plus sur le chargement et la conversion de documents stockés sur FTP, Amazon S3 Storage, Windows Azure ou tout autre stockage tiers : [Chargement d'un document à partir de différentes sources](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* En savoir plus sur les options de chargement de document en fonction du type de fichier : [Options de chargement pour différents types de documents](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Voir également

* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* espace de noms [GroupDocs.Conversion](../../converter)
* Assemblée [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;FileType, LoadOptions&gt;) {#constructor_11}

Initialise la nouvelle instance de[`Converter`](../../converter) classe.

```csharp
public Converter(string filePath, Func<FileType, LoadOptions> loadOptions)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| filePath | String | Le chemin du fichier vers le document source. |
| loadOptions | Func`2 | Les méthodes qui renvoient les options de chargement de document. Le type du fichier source |

### Remarques

**Apprendre encore plus**

* En savoir plus sur le chargement et la conversion de documents stockés sur FTP, Amazon S3 Storage, Windows Azure ou tout autre stockage tiers : [Chargement d'un document à partir de différentes sources](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* En savoir plus sur les options de chargement de document en fonction du type de fichier : [Options de chargement pour différents types de documents](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Voir également

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [Converter](../../converter)
* espace de noms [GroupDocs.Conversion](../../converter)
* Assemblée [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;FileType, LoadOptions&gt;, Func&lt;ConverterSettings&gt;) {#constructor_12}

Initialise la nouvelle instance de[`Converter`](../../converter) classe.

```csharp
public Converter(string filePath, Func<FileType, LoadOptions> loadOptions, 
    Func<ConverterSettings> settings)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| filePath | String | Le chemin du fichier vers le document source. |
| loadOptions | Func`2 | Les méthodes qui renvoient les options de chargement de document. Le type du fichier source |
| settings | Func`1 | Les paramètres du convertisseur. |

### Remarques

**Apprendre encore plus**

* En savoir plus sur le chargement et la conversion de documents stockés sur FTP, Amazon S3 Storage, Windows Azure ou tout autre stockage tiers : [Chargement d'un document à partir de différentes sources](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* En savoir plus sur les options de chargement de document en fonction du type de fichier : [Options de chargement pour différents types de documents](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Voir également

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* espace de noms [GroupDocs.Conversion](../../converter)
* Assemblée [GroupDocs.Conversion](../../../)

---

## Converter() {#constructor}

Initialise la nouvelle instance de[`Converter`](../../converter) classe pour une configuration de conversion fluide.

```csharp
public Converter()
```

### Remarques

Exemple d'utilisation de la conversion fluide :

```csharp
var converter = new Converter();
```

```csharp
converter
    .Load("")
    .ConvertTo("")
    .Convert();
```

```csharp
converter
    .WithSettings(() => new ConverterSettings())
    .Load("").WithOptions(new PdfLoadOptions())
    .ConvertTo("").WithOptions(new PdfConvertOptions())
    .OnConversionCompleted(convertedDocumentStream => { })
    .Convert();
```

```csharp
converter
    .Load("").WithOptions(new PdfLoadOptions())
    .ConvertByPageTo((number => new FileStream("", FileMode.Create))).WithOptions(new PdfConvertOptions())
    .OnConversionCompleted((number, stream) => {})
    .Convert();
```

```csharp
converter.Load("").GetPossibleConversions();
converter.Load("").GetDocumentInfo();
converter.Load("").WithOptions(new PdfLoadOptions()).GetPossibleConversions();
converter.Load("").WithOptions(new PdfLoadOptions()).GetDocumentInfo();
```

### Voir également

* class [Converter](../../converter)
* espace de noms [GroupDocs.Conversion](../../converter)
* Assemblée [GroupDocs.Conversion](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
