---
title: Converter
second_title: Riferimento API GroupDocs.Conversion per .NET
description: Inizializza la nuova istanza diConvertergroupdocs.conversion/converter classe.
type: docs
weight: 10
url: /it/net/groupdocs.conversion/converter/converter/
---
## Converter(Func&lt;Stream&gt;) {#constructor_1}

Inizializza la nuova istanza di[`Converter`](../../converter) classe.

```csharp
public Converter(Func<Stream> document)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| document | Func`1 | Il metodo che restituisce un flusso leggibile. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | Lanciato quando*document* è zero. |

### Osservazioni

**Scopri di più**

* Ulteriori informazioni su come caricare e convertire documenti archiviati su FTP, Amazon S3 Storage, Windows Azure o qualsiasi altro storage di terze parti: [Caricamento di documenti da diverse fonti](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* Ulteriori informazioni sulle opzioni di caricamento dei documenti in base al tipo di file: [Carica le opzioni per diversi tipi di documenti](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Guarda anche

* class [Converter](../../converter)
* spazio dei nomi [GroupDocs.Conversion](../../converter)
* assemblea [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;ConverterSettings&gt;) {#constructor_2}

Inizializza la nuova istanza di[`Converter`](../../converter) classe.

```csharp
public Converter(Func<Stream> document, Func<ConverterSettings> settings)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| document | Func`1 | Il metodo che restituisce un flusso leggibile. |
| settings | Func`1 | Le impostazioni del convertitore. |

### Osservazioni

**Scopri di più**

* Ulteriori informazioni su come caricare e convertire documenti archiviati su FTP, Amazon S3 Storage, Windows Azure o qualsiasi altro storage di terze parti: [Caricamento di documenti da diverse fonti](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* Ulteriori informazioni sulle opzioni di caricamento dei documenti in base al tipo di file: [Carica le opzioni per diversi tipi di documenti](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Guarda anche

* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* spazio dei nomi [GroupDocs.Conversion](../../converter)
* assemblea [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;) {#constructor_3}

Inizializza la nuova istanza di[`Converter`](../../converter) classe.

```csharp
public Converter(Func<Stream> document, Func<LoadOptions> loadOptions)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| document | Func`1 | Il metodo che restituisce un flusso leggibile. |
| loadOptions | Func`1 | I metodi che restituiscono le opzioni di caricamento del documento. |

### Osservazioni

**Scopri di più**

* Ulteriori informazioni su come caricare e convertire documenti archiviati su FTP, Amazon S3 Storage, Windows Azure o qualsiasi altro storage di terze parti: [Caricamento di documenti da diverse fonti](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* Ulteriori informazioni sulle opzioni di caricamento dei documenti in base al tipo di file: [Carica le opzioni per diversi tipi di documenti](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Guarda anche

* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [Converter](../../converter)
* spazio dei nomi [GroupDocs.Conversion](../../converter)
* assemblea [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;, Func&lt;ConverterSettings&gt;) {#constructor_4}

Inizializza la nuova istanza di[`Converter`](../../converter) classe.

```csharp
public Converter(Func<Stream> document, Func<LoadOptions> loadOptions, 
    Func<ConverterSettings> settings)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| document | Func`1 | Il metodo che restituisce un flusso leggibile. |
| loadOptions | Func`1 | I metodi che restituiscono le opzioni di caricamento del documento. |
| settings | Func`1 | Le impostazioni del convertitore. |

### Osservazioni

**Scopri di più**

* Ulteriori informazioni su come caricare e convertire documenti archiviati su FTP, Amazon S3 Storage, Windows Azure o qualsiasi altro storage di terze parti: [Caricamento di documenti da diverse fonti](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* Ulteriori informazioni sulle opzioni di caricamento dei documenti in base al tipo di file: [Carica le opzioni per diversi tipi di documenti](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Guarda anche

* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* spazio dei nomi [GroupDocs.Conversion](../../converter)
* assemblea [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;FileType, LoadOptions&gt;) {#constructor_5}

Inizializza la nuova istanza di[`Converter`](../../converter) classe.

```csharp
public Converter(Func<Stream> document, Func<FileType, LoadOptions> loadOptions)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| document | Func`1 | Il metodo che restituisce un flusso leggibile. |
| loadOptions | Func`2 | I metodi che restituiscono le opzioni di caricamento del documento. |

### Osservazioni

**Scopri di più**

* Ulteriori informazioni su come caricare e convertire documenti archiviati su FTP, Amazon S3 Storage, Windows Azure o qualsiasi altro storage di terze parti: [Caricamento di documenti da diverse fonti](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* Ulteriori informazioni sulle opzioni di caricamento dei documenti in base al tipo di file: [Carica le opzioni per diversi tipi di documenti](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Guarda anche

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [Converter](../../converter)
* spazio dei nomi [GroupDocs.Conversion](../../converter)
* assemblea [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;FileType, LoadOptions&gt;, Func&lt;ConverterSettings&gt;) {#constructor_6}

Inizializza la nuova istanza di[`Converter`](../../converter) classe.

```csharp
public Converter(Func<Stream> document, Func<FileType, LoadOptions> loadOptions, 
    Func<ConverterSettings> settings)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| document | Func`1 | Il metodo che restituisce un flusso leggibile. |
| loadOptions | Func`2 | I metodi che restituiscono le opzioni di caricamento del documento. |
| settings | Func`1 | Le impostazioni del convertitore. |

### Osservazioni

**Scopri di più**

* Ulteriori informazioni su come caricare e convertire documenti archiviati su FTP, Amazon S3 Storage, Windows Azure o qualsiasi altro storage di terze parti: [Caricamento di documenti da diverse fonti](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* Ulteriori informazioni sulle opzioni di caricamento dei documenti in base al tipo di file: [Carica le opzioni per diversi tipi di documenti](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Guarda anche

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* spazio dei nomi [GroupDocs.Conversion](../../converter)
* assemblea [GroupDocs.Conversion](../../../)

---

## Converter(string) {#constructor_7}

Inizializza la nuova istanza di[`Converter`](../../converter) classe.

```csharp
public Converter(string filePath)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePath | String | Il percorso del file del documento di origine. |

### Osservazioni

**Scopri di più**

* Ulteriori informazioni su come caricare e convertire documenti archiviati su FTP, Amazon S3 Storage, Windows Azure o qualsiasi altro storage di terze parti: [Caricamento di documenti da diverse fonti](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* Ulteriori informazioni sulle opzioni di caricamento dei documenti in base al tipo di file: [Carica le opzioni per diversi tipi di documenti](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Guarda anche

* class [Converter](../../converter)
* spazio dei nomi [GroupDocs.Conversion](../../converter)
* assemblea [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;ConverterSettings&gt;) {#constructor_8}

Inizializza la nuova istanza di[`Converter`](../../converter) classe.

```csharp
public Converter(string filePath, Func<ConverterSettings> settings)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePath | String | Il percorso del file del documento di origine. |
| settings | Func`1 | Le impostazioni del convertitore. |

### Osservazioni

**Scopri di più**

* Ulteriori informazioni su come caricare e convertire documenti archiviati su FTP, Amazon S3 Storage, Windows Azure o qualsiasi altro storage di terze parti: [Caricamento di documenti da diverse fonti](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* Ulteriori informazioni sulle opzioni di caricamento dei documenti in base al tipo di file: [Carica le opzioni per diversi tipi di documenti](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Guarda anche

* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* spazio dei nomi [GroupDocs.Conversion](../../converter)
* assemblea [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;LoadOptions&gt;) {#constructor_9}

Inizializza la nuova istanza di[`Converter`](../../converter) classe.

```csharp
public Converter(string filePath, Func<LoadOptions> loadOptions)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePath | String | Il percorso del file del documento di origine. |
| loadOptions | Func`1 | I metodi che restituiscono le opzioni di caricamento del documento. |

### Osservazioni

**Scopri di più**

* Ulteriori informazioni su come caricare e convertire documenti archiviati su FTP, Amazon S3 Storage, Windows Azure o qualsiasi altro storage di terze parti: [Caricamento di documenti da diverse fonti](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* Ulteriori informazioni sulle opzioni di caricamento dei documenti in base al tipo di file: [Carica le opzioni per diversi tipi di documenti](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Guarda anche

* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [Converter](../../converter)
* spazio dei nomi [GroupDocs.Conversion](../../converter)
* assemblea [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;LoadOptions&gt;, Func&lt;ConverterSettings&gt;) {#constructor_10}

Inizializza la nuova istanza di[`Converter`](../../converter) classe.

```csharp
public Converter(string filePath, Func<LoadOptions> loadOptions, Func<ConverterSettings> settings)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePath | String | Il percorso del file del documento di origine. |
| loadOptions | Func`1 | I metodi che restituiscono le opzioni di caricamento del documento. |
| settings | Func`1 | Le impostazioni del convertitore. |

### Osservazioni

**Scopri di più**

* Ulteriori informazioni su come caricare e convertire documenti archiviati su FTP, Amazon S3 Storage, Windows Azure o qualsiasi altro storage di terze parti: [Caricamento di documenti da diverse fonti](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* Ulteriori informazioni sulle opzioni di caricamento dei documenti in base al tipo di file: [Carica le opzioni per diversi tipi di documenti](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Guarda anche

* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* spazio dei nomi [GroupDocs.Conversion](../../converter)
* assemblea [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;FileType, LoadOptions&gt;) {#constructor_11}

Inizializza la nuova istanza di[`Converter`](../../converter) classe.

```csharp
public Converter(string filePath, Func<FileType, LoadOptions> loadOptions)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePath | String | Il percorso del file del documento di origine. |
| loadOptions | Func`2 | I metodi che restituiscono le opzioni di caricamento del documento. |

### Osservazioni

**Scopri di più**

* Ulteriori informazioni su come caricare e convertire documenti archiviati su FTP, Amazon S3 Storage, Windows Azure o qualsiasi altro storage di terze parti: [Caricamento di documenti da diverse fonti](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* Ulteriori informazioni sulle opzioni di caricamento dei documenti in base al tipo di file: [Carica le opzioni per diversi tipi di documenti](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Guarda anche

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [Converter](../../converter)
* spazio dei nomi [GroupDocs.Conversion](../../converter)
* assemblea [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;FileType, LoadOptions&gt;, Func&lt;ConverterSettings&gt;) {#constructor_12}

Inizializza la nuova istanza di[`Converter`](../../converter) classe.

```csharp
public Converter(string filePath, Func<FileType, LoadOptions> loadOptions, 
    Func<ConverterSettings> settings)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePath | String | Il percorso del file del documento di origine. |
| loadOptions | Func`2 | I metodi che restituiscono le opzioni di caricamento del documento. |
| settings | Func`1 | Le impostazioni del convertitore. |

### Osservazioni

**Scopri di più**

* Ulteriori informazioni su come caricare e convertire documenti archiviati su FTP, Amazon S3 Storage, Windows Azure o qualsiasi altro storage di terze parti: [Caricamento di documenti da diverse fonti](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* Ulteriori informazioni sulle opzioni di caricamento dei documenti in base al tipo di file: [Carica le opzioni per diversi tipi di documenti](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### Guarda anche

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* spazio dei nomi [GroupDocs.Conversion](../../converter)
* assemblea [GroupDocs.Conversion](../../../)

---

## Converter() {#constructor}

Inizializza la nuova istanza di[`Converter`](../../converter) classe per l'impostazione della conversione fluente.

```csharp
public Converter()
```

### Osservazioni

Esempio di utilizzo della conversione fluente:

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

### Guarda anche

* class [Converter](../../converter)
* spazio dei nomi [GroupDocs.Conversion](../../converter)
* assemblea [GroupDocs.Conversion](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
