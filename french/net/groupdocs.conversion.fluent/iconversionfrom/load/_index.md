---
title: "Charger"
second_title: "GroupDocs.Conversion pour .NET Référence d'API"
description: "Définir le nom de fichier du document source"
type: docs
weight: 10
url: /fr/net/groupdocs.conversion.fluent/iconversionfrom/load/
---
## Load(string) {#load_2}

Définir le nom de fichier du document source

```csharp
public IConversionLoadOptionsOrSourceDocumentLoaded Load(string fileName)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fileName | String | Document source |

### Voir aussi

* interface [IConversionLoadOptionsOrSourceDocumentLoaded](../../iconversionloadoptionsorsourcedocumentloaded)
* interface [IConversionFrom](../../iconversionfrom)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

---

## Load(string[]) {#load_3}

Définir le tableau des documents source

```csharp
public IConversionLoadOptionsOrSourceDocumentLoaded Load(string[] fileName)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fileName | String[] | Ensemble de documents source |

### Voir aussi

* interface [IConversionLoadOptionsOrSourceDocumentLoaded](../../iconversionloadoptionsorsourcedocumentloaded)
* interface [IConversionFrom](../../iconversionfrom)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

---

## Load(Func&lt;Stream&gt;) {#load_1}

Définir le flux du document source

```csharp
public IConversionLoadOptionsOrSourceDocumentLoaded Load(Func<Stream> documentStreamProvider)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| documentStreamProvider | Func`1 | Fournisseur de flux de document source |

### Exceptions

| exception | condition |
| --- | --- |
| [InvalidConverterSettingsException](../../../groupdocs.conversion.exceptions/invalidconvertersettingsexception) | Si la validation des paramètres du convertisseur échoue, cette exception sera levée |

### Voir aussi

* interface [IConversionLoadOptionsOrSourceDocumentLoaded](../../iconversionloadoptionsorsourcedocumentloaded)
* interface [IConversionFrom](../../iconversionfrom)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

---

## Load(Func&lt;Stream[]&gt;) {#load}

Définir le tableau des flux des documents source

```csharp
public IConversionLoadOptionsOrSourceDocumentLoaded Load(Func<Stream[]> documentStreamProvider)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| documentStreamProvider | Func`1 | Fournisseur de flux de documents source |

### Exceptions

| exception | condition |
| --- | --- |
| [InvalidConverterSettingsException](../../../groupdocs.conversion.exceptions/invalidconvertersettingsexception) | Si la validation des paramètres du convertisseur échoue, cette exception sera levée |

### Voir aussi

* interface [IConversionLoadOptionsOrSourceDocumentLoaded](../../iconversionloadoptionsorsourcedocumentloaded)
* interface [IConversionFrom](../../iconversionfrom)
* namespace [GroupDocs.Conversion.Fluent](../../../groupdocs.conversion.fluent)
* assembly [GroupDocs.Conversion](../../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.conversion.dll -->
