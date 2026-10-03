---
title: "Converter"
second_title: "GroupDocs.Conversion pour .NET Référence d'API"
description: "Initialise une nouvelle instance de la classe Convertergroupdocs.conversion/converter."
type: docs
weight: 10
url: /fr/net/groupdocs.conversion/converter/converter/
---
## Converter(Func&lt;Stream&gt;) {#constructor}

Initialise une nouvelle instance de la classe [`Converter`](../../converter).

```csharp
public Converter(Func<Stream> sourceStreamProvider)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| sourceStreamProvider | Func`1 | La méthode qui renvoie un flux lisible. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Lancée lorsque *sourceStreamProvider* est nul. |

### Remarques

**Learn more**

* More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* More about document loading options dependent on file type: [Load options for different document types](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Voir aussi

* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;ConverterSettings&gt;) {#constructor_1}

Initialise une nouvelle instance de la classe [`Converter`](../../converter).

```csharp
public Converter(Func<Stream> sourceStreamProvider, Func<ConverterSettings> settings)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| sourceStreamProvider | Func`1 | La méthode qui renvoie un flux lisible. |
| settings | Func`1 | Les paramètres du Convertisseur. |

### Remarques

**Learn more**

* More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* More about document loading options dependent on file type: [Load options for different document types](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Voir aussi

* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;LoadContext, LoadOptions&gt;, Func&lt;ConverterSettings&gt;) {#constructor_3}

Initialise une nouvelle instance de la classe [`Converter`](../../converter).

```csharp
public Converter(Func<Stream> sourceStreamProvider, Func<LoadContext, LoadOptions> loadOptions, 
    Func<ConverterSettings> settings = null)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| sourceStreamProvider | Func`1 | La méthode qui renvoie un flux lisible. |
| loadOptions | Func`2 | Délégué qui fournit les options de chargement pour le document. Signature : `Func<LoadContext, LoadOptions>`. Le paramètre [`LoadContext`](../../loadcontext) contient des informations sur le document en cours de chargement. |
| settings | Func`1 | Les paramètres du Convertisseur. |

### Remarques

**Learn more**

* More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* More about document loading options dependent on file type: [Load options for different document types](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Voir aussi

* class [LoadContext](../../loadcontext)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;LoadContext, LoadOptions&gt;, Func&lt;ConverterSettings&gt;, Func&lt;ConversionEvents&gt;) {#constructor_4}

Initialise une nouvelle instance de la classe [`Converter`](../../converter) avec des événements de conversion explicites.

```csharp
public Converter(Func<Stream> sourceStreamProvider, Func<LoadContext, LoadOptions> loadOptions, 
    Func<ConverterSettings> settings, Func<ConversionEvents> events)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| sourceStreamProvider | Func`1 | La méthode qui renvoie un flux lisible. |
| loadOptions | Func`2 | Délégué qui fournit les options de chargement pour le document. |
| settings | Func`1 | Les paramètres du Convertisseur. |
| events | Func`1 | Délégué qui fournit les [`ConversionEvents`](../../conversionevents) agrégés enregistrés pendant la durée de vie du convertisseur. |

### Voir aussi

* class [LoadContext](../../loadcontext)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [ConverterSettings](../../convertersettings)
* class [ConversionEvents](../../conversionevents)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;ConverterSettings&gt;, Func&lt;ConversionEvents&gt;) {#constructor_2}

Initialise une nouvelle instance de la classe [`Converter`](../../converter) avec des événements de conversion explicites.

```csharp
public Converter(Func<Stream> sourceStreamProvider, Func<ConverterSettings> settings, 
    Func<ConversionEvents> events)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| sourceStreamProvider | Func`1 | La méthode qui renvoie un flux lisible. |
| settings | Func`1 | Les paramètres du Convertisseur. |
| events | Func`1 | Délégué qui fournit les [`ConversionEvents`](../../conversionevents) agrégés enregistrés pendant la durée de vie du convertisseur. |

### Voir aussi

* class [ConverterSettings](../../convertersettings)
* class [ConversionEvents](../../conversionevents)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(string) {#constructor_5}

Initialise une nouvelle instance de la classe [`Converter`](../../converter).

```csharp
public Converter(string filePath)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| filePath | String | Le chemin d'accès du fichier source. |

### Remarques

**Learn more**

* More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* More about document loading options dependent on file type: [Load options for different document types](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Voir aussi

* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;ConverterSettings&gt;) {#constructor_6}

Initialise une nouvelle instance de la classe [`Converter`](../../converter).

```csharp
public Converter(string filePath, Func<ConverterSettings> settings)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| filePath | String | Le chemin d'accès du fichier source. |
| settings | Func`1 | Les paramètres du Convertisseur. |

### Remarques

**Learn more**

* More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* More about document loading options dependent on file type: [Load options for different document types](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Voir aussi

* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;LoadContext, LoadOptions&gt;, Func&lt;ConverterSettings&gt;) {#constructor_8}

Initialise une nouvelle instance de la classe [`Converter`](../../converter).

```csharp
public Converter(string filePath, Func<LoadContext, LoadOptions> loadOptions, 
    Func<ConverterSettings> settings = null)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| filePath | String | Le chemin d'accès du fichier source. |
| loadOptions | Func`2 | Délégué qui fournit les options de chargement pour le document. Signature : `Func<LoadContext, LoadOptions>`. Le paramètre [`LoadContext`](../../loadcontext) contient des informations sur le document en cours de chargement. |
| settings | Func`1 | Les paramètres du Convertisseur. |

### Remarques

**Learn more**

* More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* More about document loading options dependent on file type: [Load options for different document types](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Voir aussi

* class [LoadContext](../../loadcontext)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;LoadContext, LoadOptions&gt;, Func&lt;ConverterSettings&gt;, Func&lt;ConversionEvents&gt;) {#constructor_9}

Initialise une nouvelle instance de la classe [`Converter`](../../converter) avec des événements de conversion explicites.

```csharp
public Converter(string filePath, Func<LoadContext, LoadOptions> loadOptions, 
    Func<ConverterSettings> settings, Func<ConversionEvents> events)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| filePath | String | Le chemin d'accès du fichier source. |
| loadOptions | Func`2 | Délégué qui fournit les options de chargement pour le document. |
| settings | Func`1 | Les paramètres du Convertisseur. |
| events | Func`1 | Délégué qui fournit les [`ConversionEvents`](../../conversionevents) agrégés enregistrés pendant la durée de vie du convertisseur. |

### Voir aussi

* class [LoadContext](../../loadcontext)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [ConverterSettings](../../convertersettings)
* class [ConversionEvents](../../conversionevents)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;ConverterSettings&gt;, Func&lt;ConversionEvents&gt;) {#constructor_7}

Initialise une nouvelle instance de la classe [`Converter`](../../converter) avec des événements de conversion explicites.

```csharp
public Converter(string filePath, Func<ConverterSettings> settings, Func<ConversionEvents> events)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| filePath | String | Le chemin d'accès du fichier source. |
| settings | Func`1 | Les paramètres du Convertisseur. |
| events | Func`1 | Délégué qui fournit les [`ConversionEvents`](../../conversionevents) agrégés enregistrés pendant la durée de vie du convertisseur. |

### Voir aussi

* class [ConverterSettings](../../convertersettings)
* class [ConversionEvents](../../conversionevents)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.conversion.dll -->
