---
title: "Convert"
second_title: "GroupDocs.Conversion pour .NET Référence d'API"
description: "Convertit le document source. Enregistre le document converti complet."
type: docs
weight: 20
url: /fr/net/groupdocs.conversion/converter/convert/
---
## Convert(Func&lt;SaveContext, Stream&gt;, ConvertOptions, CancellationToken) {#convert_4}

Convertit le document source. Enregistre le document converti complet.

```csharp
public void Convert(Func<SaveContext, Stream> targetStreamProvider, ConvertOptions convertOptions, 
    CancellationToken cancellationToken = default)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| targetStreamProvider | Func`2 | Le délégué qui enregistre le document converti dans un flux. |
| convertOptions | ConvertOptions | Les options de conversion spécifiques au type de fichier cible souhaité. |
| cancellationToken | CancellationToken | Le jeton d'annulation. |

### Remarques

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### Voir aussi

* class [SaveContext](../../savecontext)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(ConvertOptions, Action&lt;ConvertedContext&gt;, CancellationToken) {#convert}

Convertit le document source. Enregistre le document converti complet.

```csharp
public void Convert(ConvertOptions convertOptions, Action<ConvertedContext> documentCompleted, 
    CancellationToken cancellationToken = default)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| convertOptions | ConvertOptions | Les options de conversion spécifiques au type de fichier cible souhaité. |
| documentCompleted | Action`1 | Délégué qui reçoit le flux du document converti. Signature : `Action<ConvertedContext>`. Le paramètre [`ConvertedContext`](../../convertedcontext) contient le flux du document converti et les métadonnées. |
| cancellationToken | CancellationToken | Le jeton d'annulation. |

### Remarques

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### Voir aussi

* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [ConvertedContext](../../convertedcontext)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;SaveContext, Stream&gt;, Func&lt;ConvertContext, ConvertOptions&gt;, CancellationToken) {#convert_5}

Convertit le document source. Enregistre le document converti complet.

```csharp
public void Convert(Func<SaveContext, Stream> targetStreamProvider, 
    Func<ConvertContext, ConvertOptions> convertOptionsProvider, 
    CancellationToken cancellationToken = default)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| targetStreamProvider | Func`2 | Délégué qui fournit le flux pour enregistrer le document converti. Signature : `Func<SaveContext, Stream>`. Le paramètre [`SaveContext`](../../savecontext) contient des informations sur l'opération d'enregistrement. |
| convertOptionsProvider | Func`2 | Délégué qui fournit les options de conversion. Signature : `Func<ConvertContext, ConvertOptions>`. Le paramètre [`ConvertContext`](../../convertcontext) contient des informations sur l'opération de conversion. |
| cancellationToken | CancellationToken | Le jeton d'annulation. |

### Remarques

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### Voir aussi

* class [SaveContext](../../savecontext)
* class [ConvertContext](../../convertcontext)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;ConvertContext, ConvertOptions&gt;, Action&lt;ConvertedContext&gt;, CancellationToken) {#convert_2}

Convertit le document source. Enregistre le document converti complet.

```csharp
public void Convert(Func<ConvertContext, ConvertOptions> convertOptionsProvider, 
    Action<ConvertedContext> documentCompleted, CancellationToken cancellationToken = default)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| convertOptionsProvider | Func`2 | Délégué qui fournit les options de conversion. Signature : `Func<ConvertContext, ConvertOptions>`. Le paramètre [`ConvertContext`](../../convertcontext) contient des informations sur l'opération de conversion. |
| documentCompleted | Action`1 | Délégué qui reçoit le flux du document converti. Signature : `Action<ConvertedContext>`. Le paramètre [`ConvertedContext`](../../convertedcontext) contient le flux du document converti et les métadonnées. |
| cancellationToken | CancellationToken | Le jeton d'annulation. |

### Remarques

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### Voir aussi

* class [ConvertContext](../../convertcontext)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [ConvertedContext](../../convertedcontext)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(string, ConvertOptions, CancellationToken) {#convert_8}

Convertit le document source. Enregistre le document converti complet.

```csharp
public void Convert(string filePath, ConvertOptions convertOptions, 
    CancellationToken cancellationToken = default)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| filePath | String | Le chemin d'accès du fichier source. |
| convertOptions | ConvertOptions | Les options de conversion spécifiques au type de fichier cible souhaité. |
| cancellationToken | CancellationToken | Le jeton d'annulation. |

### Remarques

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### Voir aussi

* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;SavePageContext, Stream&gt;, Func&lt;ConvertContext, ConvertOptions&gt;, CancellationToken) {#convert_7}

Convertit le document source. Enregistre le document converti page par page.

```csharp
public void Convert(Func<SavePageContext, Stream> targetStreamProvider, 
    Func<ConvertContext, ConvertOptions> convertOptionsProvider, 
    CancellationToken cancellationToken = default)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| targetStreamProvider | Func`2 | Délégué qui fournit un flux pour enregistrer chaque page convertie. Signature : `Func<SavePageContext, Stream>`. Le paramètre [`SavePageContext`](../../savepagecontext) contient le numéro de page et les informations du document. |
| convertOptionsProvider | Func`2 | Délégué qui fournit les options de conversion. Signature : `Func<ConvertContext, ConvertOptions>`. Le paramètre [`ConvertContext`](../../convertcontext) contient des informations sur l'opération de conversion. |
| cancellationToken | CancellationToken | Le jeton d'annulation. |

### Remarques

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### Voir aussi

* class [SavePageContext](../../savepagecontext)
* class [ConvertContext](../../convertcontext)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;SavePageContext, Stream&gt;, ConvertOptions, CancellationToken) {#convert_6}

Convertit le document source. Enregistre le document converti page par page.

```csharp
public void Convert(Func<SavePageContext, Stream> targetStreamProvider, 
    ConvertOptions convertOptions, CancellationToken cancellationToken = default)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| targetStreamProvider | Func`2 | Délégué qui fournit un flux pour enregistrer chaque page convertie. Signature : `Func<SavePageContext, Stream>`. Le paramètre [`SavePageContext`](../../savepagecontext) contient le numéro de page et les informations du document. |
| convertOptions | ConvertOptions | Les options de conversion spécifiques au type de fichier cible souhaité. |
| cancellationToken | CancellationToken | Le jeton d'annulation. |

### Remarques

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### Voir aussi

* class [SavePageContext](../../savepagecontext)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(ConvertOptions, Action&lt;ConvertedPageContext&gt;, CancellationToken) {#convert_1}

Convertit le document source. Enregistre le document converti page par page.

```csharp
public void Convert(ConvertOptions convertOptions, Action<ConvertedPageContext> documentCompleted, 
    CancellationToken cancellationToken = default)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| documentCompleted | ConvertOptions | Délégué qui reçoit chaque page convertie. Signature : `Action<ConvertedPageContext>`. Le paramètre [`ConvertedPageContext`](../../convertedpagecontext) contient le numéro de page, le flux, le nom du fichier source et le type de fichier cible. |
| convertOptions | Action`1 | Les options de conversion spécifiques au type de fichier cible souhaité. |
| cancellationToken | CancellationToken | Le jeton d'annulation. |

### Remarques

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### Voir aussi

* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [ConvertedPageContext](../../convertedpagecontext)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;ConvertContext, ConvertOptions&gt;, Action&lt;ConvertedPageContext&gt;, CancellationToken) {#convert_3}

Convertit le document source. Enregistre le document converti page par page.

```csharp
public void Convert(Func<ConvertContext, ConvertOptions> convertOptionsProvider, 
    Action<ConvertedPageContext> documentCompleted, CancellationToken cancellationToken = default)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| convertOptionsProvider | Func`2 | Délégué qui fournit les options de conversion. Signature : `Func<ConvertContext, ConvertOptions>`. Le paramètre [`ConvertContext`](../../convertcontext) contient des informations sur l'opération de conversion. |
| documentCompleted | Action`1 | Délégué qui reçoit chaque page convertie. Signature : `Action<ConvertedPageContext>`. Le paramètre [`ConvertedPageContext`](../../convertedpagecontext) contient le numéro de page, le flux, le nom du fichier source et le type de fichier cible. |
| cancellationToken | CancellationToken | Le jeton d'annulation. |

### Remarques

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### Voir aussi

* class [ConvertContext](../../convertcontext)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [ConvertedPageContext](../../convertedpagecontext)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.conversion.dll -->
