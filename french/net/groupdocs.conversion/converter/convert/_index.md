---
title: Convert
second_title: Référence de l'API GroupDocs.Conversion pour .NET
description: Convertit le document source. Enregistre lintégralité du document converti.
type: docs
weight: 20
url: /fr/net/groupdocs.conversion/converter/convert/
---
## Convert(Func&lt;Stream&gt;, ConvertOptions) {#convert}

Convertit le document source. Enregistre l'intégralité du document converti.

```csharp
public void Convert(Func<Stream> document, ConvertOptions convertOptions)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| document | Func`1 | Délégué qui enregistre le document converti dans un flux. |
| convertOptions | ConvertOptions | Les options de conversion spécifiques au type de fichier cible souhaité. |

### Remarques

**Apprendre encore plus**

* En savoir plus sur les scénarios de base de conversion de documents : [Comment convertir un document en 3 étapes](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Cas d'utilisation de la conversion, paramètres avancés et personnalisations : [Convertir un document avec des paramètres avancés](https://docs.groupdocs.com/display/conversionnet/Converting)

### Voir également

* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* espace de noms [GroupDocs.Conversion](../../converter)
* Assemblée [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;Stream&gt;, Action&lt;Stream, string&gt;, ConvertOptions) {#convert_1}

Convertit le document source. Enregistre l'intégralité du document converti.

```csharp
public void Convert(Func<Stream> document, Action<Stream, string> documentCompleted, 
    ConvertOptions convertOptions)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| document | Func`1 | Délégué qui enregistre le document converti dans un flux. |
| documentCompleted | Action`2 | Le délégué qui reçoit le flux de documents converti. Le flux de contenu du fichierLe nom du fichier |
| convertOptions | ConvertOptions | Les options de conversion spécifiques au type de fichier cible souhaité. |

### Remarques

**Apprendre encore plus**

* En savoir plus sur les scénarios de base de conversion de documents : [Comment convertir un document en 3 étapes](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Cas d'utilisation de la conversion, paramètres avancés et personnalisations : [Convertir un document avec des paramètres avancés](https://docs.groupdocs.com/display/conversionnet/Converting)

### Voir également

* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* espace de noms [GroupDocs.Conversion](../../converter)
* Assemblée [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;Stream&gt;, Func&lt;string, FileType, ConvertOptions&gt;) {#convert_3}

Convertit le document source. Enregistre l'intégralité du document converti.

```csharp
public void Convert(Func<Stream> document, 
    Func<string, FileType, ConvertOptions> convertOptionsProvider)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| document | Func`1 | Délégué qui enregistre le document converti dans un flux. |
| convertOptionsProvider | Func`3 | Convertir le fournisseur d'options. Sera appelé pour chaque conversion afin de fournir des options de conversion spécifiques au type de document cible souhaité. Le nom du fichierLe type de fichier |

### Remarques

**Apprendre encore plus**

* En savoir plus sur les scénarios de base de conversion de documents : [Comment convertir un document en 3 étapes](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Cas d'utilisation de la conversion, paramètres avancés et personnalisations : [Convertir un document avec des paramètres avancés](https://docs.groupdocs.com/display/conversionnet/Converting)

### Voir également

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* espace de noms [GroupDocs.Conversion](../../converter)
* Assemblée [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;Stream&gt;, Action&lt;Stream, string&gt;, Func&lt;string, FileType, ConvertOptions&gt;) {#convert_2}

Convertit le document source. Enregistre l'intégralité du document converti.

```csharp
public void Convert(Func<Stream> document, Action<Stream, string> documentCompleted, 
    Func<string, FileType, ConvertOptions> convertOptionsProvider)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| document | Func`1 | Délégué qui enregistre le document converti dans un flux. |
| documentCompleted | Action`2 | Le délégué qui reçoit le flux de documents converti. Le flux de contenu du fichierLe nom du fichier |
| convertOptionsProvider | Func`3 | Convertir le fournisseur d'options. Sera appelé pour chaque conversion afin de fournir des options de conversion spécifiques au type de document cible souhaité. Le nom du fichierLe type de fichier |

### Remarques

**Apprendre encore plus**

* En savoir plus sur les scénarios de base de conversion de documents : [Comment convertir un document en 3 étapes](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Cas d'utilisation de la conversion, paramètres avancés et personnalisations : [Convertir un document avec des paramètres avancés](https://docs.groupdocs.com/display/conversionnet/Converting)

### Voir également

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* espace de noms [GroupDocs.Conversion](../../converter)
* Assemblée [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;FileType, Stream&gt;, ConvertOptions) {#convert_4}

Convertit le document source. Enregistre l'intégralité du document converti.

```csharp
public void Convert(Func<FileType, Stream> document, ConvertOptions convertOptions)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| document | Func`2 | Le délégué qui enregistre le document converti dans un flux. Le type du fichier source |
| convertOptions | ConvertOptions | Les options de conversion spécifiques au type de fichier cible souhaité. |

### Remarques

**Apprendre encore plus**

* En savoir plus sur les scénarios de base de conversion de documents : [Comment convertir un document en 3 étapes](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Cas d'utilisation de la conversion, paramètres avancés et personnalisations : [Convertir un document avec des paramètres avancés](https://docs.groupdocs.com/display/conversionnet/Converting)

### Voir également

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* espace de noms [GroupDocs.Conversion](../../converter)
* Assemblée [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;FileType, Stream&gt;, Action&lt;Stream, string&gt;, ConvertOptions) {#convert_5}

Convertit le document source. Enregistre l'intégralité du document converti.

```csharp
public void Convert(Func<FileType, Stream> document, Action<Stream, string> documentCompleted, 
    ConvertOptions convertOptions)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| document | Func`2 | Le délégué qui enregistre le document converti dans un flux. Le type du fichier source |
| documentCompleted | Action`2 | Le délégué qui reçoit le flux de documents converti. Le flux de contenu du fichierLe nom du fichier |
| convertOptions | ConvertOptions | Les options de conversion spécifiques au type de fichier cible souhaité. |

### Remarques

**Apprendre encore plus**

* En savoir plus sur les scénarios de base de conversion de documents : [Comment convertir un document en 3 étapes](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Cas d'utilisation de la conversion, paramètres avancés et personnalisations : [Convertir un document avec des paramètres avancés](https://docs.groupdocs.com/display/conversionnet/Converting)

### Voir également

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* espace de noms [GroupDocs.Conversion](../../converter)
* Assemblée [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;FileType, Stream&gt;, Func&lt;string, FileType, ConvertOptions&gt;) {#convert_7}

Convertit le document source. Enregistre l'intégralité du document converti.

```csharp
public void Convert(Func<FileType, Stream> document, 
    Func<string, FileType, ConvertOptions> convertOptionsProvider)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| document | Func`2 | Le délégué qui enregistre le document converti dans un flux. Le type du fichier source |
| convertOptionsProvider | Func`3 | Convertir le fournisseur d'options. Sera appelé pour chaque conversion afin de fournir des options de conversion spécifiques au type de document cible souhaité. Le nom du fichierLe type de fichier |

### Remarques

**Apprendre encore plus**

* En savoir plus sur les scénarios de base de conversion de documents : [Comment convertir un document en 3 étapes](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Cas d'utilisation de la conversion, paramètres avancés et personnalisations : [Convertir un document avec des paramètres avancés](https://docs.groupdocs.com/display/conversionnet/Converting)

### Voir également

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* espace de noms [GroupDocs.Conversion](../../converter)
* Assemblée [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;FileType, Stream&gt;, Action&lt;Stream, string&gt;, Func&lt;string, FileType, ConvertOptions&gt;) {#convert_6}

Convertit le document source. Enregistre l'intégralité du document converti.

```csharp
public void Convert(Func<FileType, Stream> document, Action<Stream, string> documentCompleted, 
    Func<string, FileType, ConvertOptions> convertOptionsProvider)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| document | Func`2 | Le délégué qui enregistre le document converti dans un flux. Le type du fichier source |
| documentCompleted | Action`2 | Le délégué qui reçoit le flux de documents converti. Le flux de contenu du fichierLe nom du fichier |
| convertOptionsProvider | Func`3 | Convertir le fournisseur d'options. Sera appelé pour chaque conversion afin de fournir des options de conversion spécifiques au type de document cible souhaité. Le nom du fichierLe type de fichier |

### Remarques

**Apprendre encore plus**

* En savoir plus sur les scénarios de base de conversion de documents : [Comment convertir un document en 3 étapes](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Cas d'utilisation de la conversion, paramètres avancés et personnalisations : [Convertir un document avec des paramètres avancés](https://docs.groupdocs.com/display/conversionnet/Converting)

### Voir également

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* espace de noms [GroupDocs.Conversion](../../converter)
* Assemblée [GroupDocs.Conversion](../../../)

---

## Convert(string, ConvertOptions) {#convert_16}

Convertit le document source. Enregistre l'intégralité du document converti.

```csharp
public void Convert(string filePath, ConvertOptions convertOptions)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| filePath | String | Le chemin du fichier vers le document source. |
| convertOptions | ConvertOptions | Les options de conversion spécifiques au type de fichier cible souhaité. |

### Remarques

**Apprendre encore plus**

* En savoir plus sur les scénarios de base de conversion de documents : [Comment convertir un document en 3 étapes](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Cas d'utilisation de la conversion, paramètres avancés et personnalisations : [Convertir un document avec des paramètres avancés](https://docs.groupdocs.com/display/conversionnet/Converting)

### Voir également

* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* espace de noms [GroupDocs.Conversion](../../converter)
* Assemblée [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;int, Stream&gt;, ConvertOptions) {#convert_8}

Convertit le document source. Enregistre le document converti page par page.

```csharp
public void Convert(Func<int, Stream> document, ConvertOptions convertOptions)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| document | Func`2 | Le délégué qui enregistre le document converti dans un flux. Numéro de page |
| convertOptions | ConvertOptions | Les options de conversion spécifiques au type de fichier cible souhaité. |

### Remarques

**Apprendre encore plus**

* En savoir plus sur les scénarios de base de conversion de documents : [Comment convertir un document en 3 étapes](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Cas d'utilisation de la conversion, paramètres avancés et personnalisations : [Convertir un document avec des paramètres avancés](https://docs.groupdocs.com/display/conversionnet/Converting)

### Voir également

* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* espace de noms [GroupDocs.Conversion](../../converter)
* Assemblée [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;int, Stream&gt;, Action&lt;int, Stream, string&gt;, ConvertOptions) {#convert_9}

Convertit le document source. Enregistre le document converti page par page.

```csharp
public void Convert(Func<int, Stream> document, Action<int, Stream, string> documentCompleted, 
    ConvertOptions convertOptions)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| document | Func`2 | Le délégué qui enregistre la page de document convertie dans un flux. Numéro de page |
| documentCompleted | Action`3 | Le délégué qui reçoit le flux de page de document converti. Numéro de pageLe flux de contenu du fichierLe nom du fichier |
| convertOptions | ConvertOptions | Les options de conversion spécifiques au type de fichier cible souhaité. |

### Remarques

**Apprendre encore plus**

* En savoir plus sur les scénarios de base de conversion de documents : [Comment convertir un document en 3 étapes](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Cas d'utilisation de la conversion, paramètres avancés et personnalisations : [Convertir un document avec des paramètres avancés](https://docs.groupdocs.com/display/conversionnet/Converting)

### Voir également

* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* espace de noms [GroupDocs.Conversion](../../converter)
* Assemblée [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;int, Stream&gt;, Func&lt;string, FileType, ConvertOptions&gt;) {#convert_11}

Convertit le document source. Enregistre le document converti page par page.

```csharp
public void Convert(Func<int, Stream> document, 
    Func<string, FileType, ConvertOptions> convertOptionsProvider)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| document | Func`2 | Le délégué qui enregistre le document converti dans un flux. Numéro de page |
| convertOptionsProvider | Func`3 | Convertir le fournisseur d'options. Sera appelé pour chaque conversion afin de fournir des options de conversion spécifiques au type de document cible souhaité. Le nom du fichierLe type de fichier |

### Remarques

**Apprendre encore plus**

* En savoir plus sur les scénarios de base de conversion de documents : [Comment convertir un document en 3 étapes](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Cas d'utilisation de la conversion, paramètres avancés et personnalisations : [Convertir un document avec des paramètres avancés](https://docs.groupdocs.com/display/conversionnet/Converting)

### Voir également

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* espace de noms [GroupDocs.Conversion](../../converter)
* Assemblée [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;int, Stream&gt;, Action&lt;int, Stream, string&gt;, Func&lt;string, FileType, ConvertOptions&gt;) {#convert_10}

Convertit le document source. Enregistre le document converti page par page.

```csharp
public void Convert(Func<int, Stream> document, Action<int, Stream, string> documentCompleted, 
    Func<string, FileType, ConvertOptions> convertOptionsProvider)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| document | Func`2 | Le délégué qui enregistre la page de document convertie dans un flux. Numéro de page |
| documentCompleted | Action`3 | Le délégué qui reçoit le flux de page de document converti. Numéro de pageLe flux de contenu du fichierLe nom du fichier |
| convertOptionsProvider | Func`3 | Convertir le fournisseur d'options. Sera appelé pour chaque conversion afin de fournir des options de conversion spécifiques au type de document cible souhaité. Le nom du fichierLe type de fichier |

### Remarques

**Apprendre encore plus**

* En savoir plus sur les scénarios de base de conversion de documents : [Comment convertir un document en 3 étapes](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Cas d'utilisation de la conversion, paramètres avancés et personnalisations : [Convertir un document avec des paramètres avancés](https://docs.groupdocs.com/display/conversionnet/Converting)

### Voir également

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* espace de noms [GroupDocs.Conversion](../../converter)
* Assemblée [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;int, FileType, Stream&gt;, ConvertOptions) {#convert_12}

Convertit le document source. Enregistre le document converti page par page.

```csharp
public void Convert(Func<int, FileType, Stream> document, ConvertOptions convertOptions)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| document | Func`3 | Le délégué qui enregistre le document converti dans un flux. Numéro de page |
| convertOptions | ConvertOptions | Les options de conversion spécifiques au type de fichier cible souhaité. |

### Remarques

**Apprendre encore plus**

* En savoir plus sur les scénarios de base de conversion de documents : [Comment convertir un document en 3 étapes](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Cas d'utilisation de la conversion, paramètres avancés et personnalisations : [Convertir un document avec des paramètres avancés](https://docs.groupdocs.com/display/conversionnet/Converting)

### Voir également

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* espace de noms [GroupDocs.Conversion](../../converter)
* Assemblée [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;int, FileType, Stream&gt;, Action&lt;int, Stream, string&gt;, ConvertOptions) {#convert_13}

Convertit le document source. Enregistre le document converti page par page.

```csharp
public void Convert(Func<int, FileType, Stream> document, 
    Action<int, Stream, string> documentCompleted, ConvertOptions convertOptions)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| document | Func`3 | Le délégué qui enregistre la page de document convertie dans un flux. Numéro de pageType de fichier |
| documentCompleted | Action`3 | Le délégué qui reçoit le flux de page de document converti. Numéro de pageLe flux de contenu du fichierLe nom du fichier |
| convertOptions | ConvertOptions | Les options de conversion spécifiques au type de fichier cible souhaité. |

### Remarques

**Apprendre encore plus**

* En savoir plus sur les scénarios de base de conversion de documents : [Comment convertir un document en 3 étapes](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Cas d'utilisation de la conversion, paramètres avancés et personnalisations : [Convertir un document avec des paramètres avancés](https://docs.groupdocs.com/display/conversionnet/Converting)

### Voir également

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* espace de noms [GroupDocs.Conversion](../../converter)
* Assemblée [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;int, FileType, Stream&gt;, Func&lt;string, FileType, ConvertOptions&gt;) {#convert_15}

Convertit le document source. Enregistre le document converti page par page.

```csharp
public void Convert(Func<int, FileType, Stream> document, 
    Func<string, FileType, ConvertOptions> convertOptionsProvider)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| document | Func`3 | Le délégué qui enregistre le document converti dans un flux. Numéro de pageType de fichier |
| convertOptionsProvider | Func`3 | Convertir le fournisseur d'options. Sera appelé pour chaque conversion afin de fournir des options de conversion spécifiques au type de document cible souhaité. Le nom du fichierLe type de fichier |

### Remarques

**Apprendre encore plus**

* En savoir plus sur les scénarios de base de conversion de documents : [Comment convertir un document en 3 étapes](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Cas d'utilisation de la conversion, paramètres avancés et personnalisations : [Convertir un document avec des paramètres avancés](https://docs.groupdocs.com/display/conversionnet/Converting)

### Voir également

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* espace de noms [GroupDocs.Conversion](../../converter)
* Assemblée [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;int, FileType, Stream&gt;, Action&lt;int, Stream, string&gt;, Func&lt;string, FileType, ConvertOptions&gt;) {#convert_14}

Convertit le document source. Enregistre le document converti page par page.

```csharp
public void Convert(Func<int, FileType, Stream> document, 
    Action<int, Stream, string> documentCompleted, 
    Func<string, FileType, ConvertOptions> convertOptionsProvider)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| document | Func`3 | Le délégué qui enregistre la page de document convertie dans un flux. Numéro de pageType de fichier |
| documentCompleted | Action`3 | Le délégué qui reçoit le flux de page de document converti. Numéro de pageLe flux de contenu du fichierLe nom du fichier |
| convertOptionsProvider | Func`3 | Convertir le fournisseur d'options. Sera appelé pour chaque conversion afin de fournir des options de conversion spécifiques au type de document cible souhaité. Le nom du fichierLe type de fichier |

### Remarques

**Apprendre encore plus**

* En savoir plus sur les scénarios de base de conversion de documents : [Comment convertir un document en 3 étapes](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Cas d'utilisation de la conversion, paramètres avancés et personnalisations : [Convertir un document avec des paramètres avancés](https://docs.groupdocs.com/display/conversionnet/Converting)

### Voir également

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* espace de noms [GroupDocs.Conversion](../../converter)
* Assemblée [GroupDocs.Conversion](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
