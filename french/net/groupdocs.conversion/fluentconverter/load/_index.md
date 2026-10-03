---
title: "Charger"
second_title: "GroupDocs.Conversion pour .NET Référence d'API"
description: "Configurer le document source pour la conversion"
type: docs
weight: 10
url: /fr/net/groupdocs.conversion/fluentconverter/load/
---
## Load(string) {#load_2}

Configurer le document source pour la conversion

```csharp
public static IConversionLoadOptionsOrSourceDocumentLoaded Load(string fileName)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fileName | String | Document source |

### Voir aussi

* interface [IConversionLoadOptionsOrSourceDocumentLoaded](../../../groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded)
* class [FluentConverter](../../fluentconverter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Load(string[]) {#load_3}

Configurer l'ensemble des documents source

```csharp
public static IConversionLoadOptionsOrSourceDocumentLoaded Load(string[] fileName)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fileName | String[] | Tableau de fichiers source |

### Voir aussi

* interface [IConversionLoadOptionsOrSourceDocumentLoaded](../../../groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded)
* class [FluentConverter](../../fluentconverter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Load(Func&lt;Stream&gt;) {#load_1}

Configurer le flux du document source

```csharp
public static IConversionLoadOptionsOrSourceDocumentLoaded Load(Func<Stream> documentStreamProvider)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| documentStreamProvider | Func`1 | Fournisseur de flux de document source |

### Voir aussi

* interface [IConversionLoadOptionsOrSourceDocumentLoaded](../../../groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded)
* class [FluentConverter](../../fluentconverter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Load(Func&lt;Stream[]&gt;) {#load}

Configurer l'ensemble des flux de documents source

```csharp
public static IConversionLoadOptionsOrSourceDocumentLoaded Load(
    Func<Stream[]> documentStreamProvider)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| documentStreamProvider | Func`1 | Fournisseur d'ensemble de flux de documents source |

### Voir aussi

* interface [IConversionLoadOptionsOrSourceDocumentLoaded](../../../groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded)
* class [FluentConverter](../../fluentconverter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.conversion.dll -->
