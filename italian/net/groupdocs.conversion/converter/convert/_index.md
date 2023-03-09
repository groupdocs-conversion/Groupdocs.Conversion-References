---
title: Convert
second_title: Riferimento API GroupDocs.Conversion per .NET
description: Converte il documento di origine. Salva lintero documento convertito.
type: docs
weight: 20
url: /it/net/groupdocs.conversion/converter/convert/
---
## Convert(Func&lt;Stream&gt;, ConvertOptions) {#convert}

Converte il documento di origine. Salva l'intero documento convertito.

```csharp
public void Convert(Func<Stream> document, ConvertOptions convertOptions)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| document | Func`1 | Delegato che salva il documento convertito in un flusso. |
| convertOptions | ConvertOptions | Le opzioni di conversione specifiche per il tipo di file di destinazione desiderato. |

### Osservazioni

**Saperne di più**

* Ulteriori informazioni sugli scenari di base della conversione dei documenti: [Come convertire un documento in 3 passaggi](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Casi d'uso di conversione, impostazioni avanzate e personalizzazioni: [Converti documento con impostazioni avanzate](https://docs.groupdocs.com/display/conversionnet/Converting)

### Guarda anche

* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* spazio dei nomi [GroupDocs.Conversion](../../converter)
* assemblea [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;Stream&gt;, Action&lt;Stream, string&gt;, ConvertOptions) {#convert_1}

Converte il documento di origine. Salva l'intero documento convertito.

```csharp
public void Convert(Func<Stream> document, Action<Stream, string> documentCompleted, 
    ConvertOptions convertOptions)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| document | Func`1 | Delegato che salva il documento convertito in un flusso. |
| documentCompleted | Action`2 | Il delegato che riceve il flusso di documenti convertito. Il flusso di contenuto del fileIl nome del file |
| convertOptions | ConvertOptions | Le opzioni di conversione specifiche per il tipo di file di destinazione desiderato. |

### Osservazioni

**Saperne di più**

* Ulteriori informazioni sugli scenari di base della conversione dei documenti: [Come convertire un documento in 3 passaggi](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Casi d'uso di conversione, impostazioni avanzate e personalizzazioni: [Converti documento con impostazioni avanzate](https://docs.groupdocs.com/display/conversionnet/Converting)

### Guarda anche

* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* spazio dei nomi [GroupDocs.Conversion](../../converter)
* assemblea [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;Stream&gt;, Func&lt;string, FileType, ConvertOptions&gt;) {#convert_3}

Converte il documento di origine. Salva l'intero documento convertito.

```csharp
public void Convert(Func<Stream> document, 
    Func<string, FileType, ConvertOptions> convertOptionsProvider)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| document | Func`1 | Delegato che salva il documento convertito in un flusso. |
| convertOptionsProvider | Func`3 | Converti fornitore di opzioni. Verrà richiamato per ogni conversione per fornire opzioni di conversione specifiche al tipo di documento di destinazione desiderato. Il nome del fileIl tipo di file |

### Osservazioni

**Saperne di più**

* Ulteriori informazioni sugli scenari di base della conversione dei documenti: [Come convertire un documento in 3 passaggi](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Casi d'uso di conversione, impostazioni avanzate e personalizzazioni: [Converti documento con impostazioni avanzate](https://docs.groupdocs.com/display/conversionnet/Converting)

### Guarda anche

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* spazio dei nomi [GroupDocs.Conversion](../../converter)
* assemblea [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;Stream&gt;, Action&lt;Stream, string&gt;, Func&lt;string, FileType, ConvertOptions&gt;) {#convert_2}

Converte il documento di origine. Salva l'intero documento convertito.

```csharp
public void Convert(Func<Stream> document, Action<Stream, string> documentCompleted, 
    Func<string, FileType, ConvertOptions> convertOptionsProvider)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| document | Func`1 | Delegato che salva il documento convertito in un flusso. |
| documentCompleted | Action`2 | Il delegato che riceve il flusso di documenti convertito. Il flusso di contenuto del fileIl nome del file |
| convertOptionsProvider | Func`3 | Converti fornitore di opzioni. Verrà richiamato per ogni conversione per fornire opzioni di conversione specifiche al tipo di documento di destinazione desiderato. Il nome del fileIl tipo di file |

### Osservazioni

**Saperne di più**

* Ulteriori informazioni sugli scenari di base della conversione dei documenti: [Come convertire un documento in 3 passaggi](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Casi d'uso di conversione, impostazioni avanzate e personalizzazioni: [Converti documento con impostazioni avanzate](https://docs.groupdocs.com/display/conversionnet/Converting)

### Guarda anche

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* spazio dei nomi [GroupDocs.Conversion](../../converter)
* assemblea [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;FileType, Stream&gt;, ConvertOptions) {#convert_4}

Converte il documento di origine. Salva l'intero documento convertito.

```csharp
public void Convert(Func<FileType, Stream> document, ConvertOptions convertOptions)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| document | Func`2 | Il delegato che salva il documento convertito in un flusso. Il tipo di file di origine |
| convertOptions | ConvertOptions | Le opzioni di conversione specifiche per il tipo di file di destinazione desiderato. |

### Osservazioni

**Saperne di più**

* Ulteriori informazioni sugli scenari di base della conversione dei documenti: [Come convertire un documento in 3 passaggi](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Casi d'uso di conversione, impostazioni avanzate e personalizzazioni: [Converti documento con impostazioni avanzate](https://docs.groupdocs.com/display/conversionnet/Converting)

### Guarda anche

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* spazio dei nomi [GroupDocs.Conversion](../../converter)
* assemblea [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;FileType, Stream&gt;, Action&lt;Stream, string&gt;, ConvertOptions) {#convert_5}

Converte il documento di origine. Salva l'intero documento convertito.

```csharp
public void Convert(Func<FileType, Stream> document, Action<Stream, string> documentCompleted, 
    ConvertOptions convertOptions)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| document | Func`2 | Il delegato che salva il documento convertito in un flusso. Il tipo di file di origine |
| documentCompleted | Action`2 | Il delegato che riceve il flusso di documenti convertito. Il flusso di contenuto del fileIl nome del file |
| convertOptions | ConvertOptions | Le opzioni di conversione specifiche per il tipo di file di destinazione desiderato. |

### Osservazioni

**Saperne di più**

* Ulteriori informazioni sugli scenari di base della conversione dei documenti: [Come convertire un documento in 3 passaggi](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Casi d'uso di conversione, impostazioni avanzate e personalizzazioni: [Converti documento con impostazioni avanzate](https://docs.groupdocs.com/display/conversionnet/Converting)

### Guarda anche

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* spazio dei nomi [GroupDocs.Conversion](../../converter)
* assemblea [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;FileType, Stream&gt;, Func&lt;string, FileType, ConvertOptions&gt;) {#convert_7}

Converte il documento di origine. Salva l'intero documento convertito.

```csharp
public void Convert(Func<FileType, Stream> document, 
    Func<string, FileType, ConvertOptions> convertOptionsProvider)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| document | Func`2 | Il delegato che salva il documento convertito in un flusso. Il tipo di file di origine |
| convertOptionsProvider | Func`3 | Converti fornitore di opzioni. Verrà richiamato per ogni conversione per fornire opzioni di conversione specifiche al tipo di documento di destinazione desiderato. Il nome del fileIl tipo di file |

### Osservazioni

**Saperne di più**

* Ulteriori informazioni sugli scenari di base della conversione dei documenti: [Come convertire un documento in 3 passaggi](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Casi d'uso di conversione, impostazioni avanzate e personalizzazioni: [Converti documento con impostazioni avanzate](https://docs.groupdocs.com/display/conversionnet/Converting)

### Guarda anche

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* spazio dei nomi [GroupDocs.Conversion](../../converter)
* assemblea [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;FileType, Stream&gt;, Action&lt;Stream, string&gt;, Func&lt;string, FileType, ConvertOptions&gt;) {#convert_6}

Converte il documento di origine. Salva l'intero documento convertito.

```csharp
public void Convert(Func<FileType, Stream> document, Action<Stream, string> documentCompleted, 
    Func<string, FileType, ConvertOptions> convertOptionsProvider)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| document | Func`2 | Il delegato che salva il documento convertito in un flusso. Il tipo di file di origine |
| documentCompleted | Action`2 | Il delegato che riceve il flusso di documenti convertito. Il flusso di contenuto del fileIl nome del file |
| convertOptionsProvider | Func`3 | Converti fornitore di opzioni. Verrà richiamato per ogni conversione per fornire opzioni di conversione specifiche al tipo di documento di destinazione desiderato. Il nome del fileIl tipo di file |

### Osservazioni

**Saperne di più**

* Ulteriori informazioni sugli scenari di base della conversione dei documenti: [Come convertire un documento in 3 passaggi](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Casi d'uso di conversione, impostazioni avanzate e personalizzazioni: [Converti documento con impostazioni avanzate](https://docs.groupdocs.com/display/conversionnet/Converting)

### Guarda anche

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* spazio dei nomi [GroupDocs.Conversion](../../converter)
* assemblea [GroupDocs.Conversion](../../../)

---

## Convert(string, ConvertOptions) {#convert_16}

Converte il documento di origine. Salva l'intero documento convertito.

```csharp
public void Convert(string filePath, ConvertOptions convertOptions)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePath | String | Il percorso del file al documento di origine. |
| convertOptions | ConvertOptions | Le opzioni di conversione specifiche per il tipo di file di destinazione desiderato. |

### Osservazioni

**Saperne di più**

* Ulteriori informazioni sugli scenari di base della conversione dei documenti: [Come convertire un documento in 3 passaggi](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Casi d'uso di conversione, impostazioni avanzate e personalizzazioni: [Converti documento con impostazioni avanzate](https://docs.groupdocs.com/display/conversionnet/Converting)

### Guarda anche

* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* spazio dei nomi [GroupDocs.Conversion](../../converter)
* assemblea [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;int, Stream&gt;, ConvertOptions) {#convert_8}

Converte il documento di origine. Salva il documento convertito pagina per pagina.

```csharp
public void Convert(Func<int, Stream> document, ConvertOptions convertOptions)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| document | Func`2 | Il delegato che salva il documento convertito in un flusso. Numero di pagina |
| convertOptions | ConvertOptions | Le opzioni di conversione specifiche per il tipo di file di destinazione desiderato. |

### Osservazioni

**Saperne di più**

* Ulteriori informazioni sugli scenari di base della conversione dei documenti: [Come convertire un documento in 3 passaggi](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Casi d'uso di conversione, impostazioni avanzate e personalizzazioni: [Converti documento con impostazioni avanzate](https://docs.groupdocs.com/display/conversionnet/Converting)

### Guarda anche

* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* spazio dei nomi [GroupDocs.Conversion](../../converter)
* assemblea [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;int, Stream&gt;, Action&lt;int, Stream, string&gt;, ConvertOptions) {#convert_9}

Converte il documento di origine. Salva il documento convertito pagina per pagina.

```csharp
public void Convert(Func<int, Stream> document, Action<int, Stream, string> documentCompleted, 
    ConvertOptions convertOptions)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| document | Func`2 | Il delegato che salva la pagina del documento convertito in un flusso. Numero di pagina |
| documentCompleted | Action`3 | Il delegato che riceve lo stream della pagina del documento convertito. Numero di paginaIl flusso di contenuto del fileIl nome del file |
| convertOptions | ConvertOptions | Le opzioni di conversione specifiche per il tipo di file di destinazione desiderato. |

### Osservazioni

**Saperne di più**

* Ulteriori informazioni sugli scenari di base della conversione dei documenti: [Come convertire un documento in 3 passaggi](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Casi d'uso di conversione, impostazioni avanzate e personalizzazioni: [Converti documento con impostazioni avanzate](https://docs.groupdocs.com/display/conversionnet/Converting)

### Guarda anche

* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* spazio dei nomi [GroupDocs.Conversion](../../converter)
* assemblea [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;int, Stream&gt;, Func&lt;string, FileType, ConvertOptions&gt;) {#convert_11}

Converte il documento di origine. Salva il documento convertito pagina per pagina.

```csharp
public void Convert(Func<int, Stream> document, 
    Func<string, FileType, ConvertOptions> convertOptionsProvider)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| document | Func`2 | Il delegato che salva il documento convertito in un flusso. Numero di pagina |
| convertOptionsProvider | Func`3 | Converti fornitore di opzioni. Verrà richiamato per ogni conversione per fornire opzioni di conversione specifiche al tipo di documento di destinazione desiderato. Il nome del fileIl tipo di file |

### Osservazioni

**Saperne di più**

* Ulteriori informazioni sugli scenari di base della conversione dei documenti: [Come convertire un documento in 3 passaggi](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Casi d'uso di conversione, impostazioni avanzate e personalizzazioni: [Converti documento con impostazioni avanzate](https://docs.groupdocs.com/display/conversionnet/Converting)

### Guarda anche

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* spazio dei nomi [GroupDocs.Conversion](../../converter)
* assemblea [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;int, Stream&gt;, Action&lt;int, Stream, string&gt;, Func&lt;string, FileType, ConvertOptions&gt;) {#convert_10}

Converte il documento di origine. Salva il documento convertito pagina per pagina.

```csharp
public void Convert(Func<int, Stream> document, Action<int, Stream, string> documentCompleted, 
    Func<string, FileType, ConvertOptions> convertOptionsProvider)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| document | Func`2 | Il delegato che salva la pagina del documento convertito in un flusso. Numero di pagina |
| documentCompleted | Action`3 | Il delegato che riceve lo stream della pagina del documento convertito. Numero di paginaIl flusso di contenuto del fileIl nome del file |
| convertOptionsProvider | Func`3 | Converti fornitore di opzioni. Verrà richiamato per ogni conversione per fornire opzioni di conversione specifiche al tipo di documento di destinazione desiderato. Il nome del fileIl tipo di file |

### Osservazioni

**Saperne di più**

* Ulteriori informazioni sugli scenari di base della conversione dei documenti: [Come convertire un documento in 3 passaggi](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Casi d'uso di conversione, impostazioni avanzate e personalizzazioni: [Converti documento con impostazioni avanzate](https://docs.groupdocs.com/display/conversionnet/Converting)

### Guarda anche

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* spazio dei nomi [GroupDocs.Conversion](../../converter)
* assemblea [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;int, FileType, Stream&gt;, ConvertOptions) {#convert_12}

Converte il documento di origine. Salva il documento convertito pagina per pagina.

```csharp
public void Convert(Func<int, FileType, Stream> document, ConvertOptions convertOptions)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| document | Func`3 | Il delegato che salva il documento convertito in un flusso. Numero di pagina |
| convertOptions | ConvertOptions | Le opzioni di conversione specifiche per il tipo di file di destinazione desiderato. |

### Osservazioni

**Saperne di più**

* Ulteriori informazioni sugli scenari di base della conversione dei documenti: [Come convertire un documento in 3 passaggi](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Casi d'uso di conversione, impostazioni avanzate e personalizzazioni: [Converti documento con impostazioni avanzate](https://docs.groupdocs.com/display/conversionnet/Converting)

### Guarda anche

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* spazio dei nomi [GroupDocs.Conversion](../../converter)
* assemblea [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;int, FileType, Stream&gt;, Action&lt;int, Stream, string&gt;, ConvertOptions) {#convert_13}

Converte il documento di origine. Salva il documento convertito pagina per pagina.

```csharp
public void Convert(Func<int, FileType, Stream> document, 
    Action<int, Stream, string> documentCompleted, ConvertOptions convertOptions)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| document | Func`3 | Il delegato che salva la pagina del documento convertito in un flusso. Numero di paginaTipo di file |
| documentCompleted | Action`3 | Il delegato che riceve lo stream della pagina del documento convertito. Numero di paginaIl flusso di contenuto del fileIl nome del file |
| convertOptions | ConvertOptions | Le opzioni di conversione specifiche per il tipo di file di destinazione desiderato. |

### Osservazioni

**Saperne di più**

* Ulteriori informazioni sugli scenari di base della conversione dei documenti: [Come convertire un documento in 3 passaggi](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Casi d'uso di conversione, impostazioni avanzate e personalizzazioni: [Converti documento con impostazioni avanzate](https://docs.groupdocs.com/display/conversionnet/Converting)

### Guarda anche

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* spazio dei nomi [GroupDocs.Conversion](../../converter)
* assemblea [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;int, FileType, Stream&gt;, Func&lt;string, FileType, ConvertOptions&gt;) {#convert_15}

Converte il documento di origine. Salva il documento convertito pagina per pagina.

```csharp
public void Convert(Func<int, FileType, Stream> document, 
    Func<string, FileType, ConvertOptions> convertOptionsProvider)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| document | Func`3 | Il delegato che salva il documento convertito in un flusso. Numero di paginaTipo di file |
| convertOptionsProvider | Func`3 | Converti fornitore di opzioni. Verrà richiamato per ogni conversione per fornire opzioni di conversione specifiche al tipo di documento di destinazione desiderato. Il nome del fileIl tipo di file |

### Osservazioni

**Saperne di più**

* Ulteriori informazioni sugli scenari di base della conversione dei documenti: [Come convertire un documento in 3 passaggi](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Casi d'uso di conversione, impostazioni avanzate e personalizzazioni: [Converti documento con impostazioni avanzate](https://docs.groupdocs.com/display/conversionnet/Converting)

### Guarda anche

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* spazio dei nomi [GroupDocs.Conversion](../../converter)
* assemblea [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;int, FileType, Stream&gt;, Action&lt;int, Stream, string&gt;, Func&lt;string, FileType, ConvertOptions&gt;) {#convert_14}

Converte il documento di origine. Salva il documento convertito pagina per pagina.

```csharp
public void Convert(Func<int, FileType, Stream> document, 
    Action<int, Stream, string> documentCompleted, 
    Func<string, FileType, ConvertOptions> convertOptionsProvider)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| document | Func`3 | Il delegato che salva la pagina del documento convertito in un flusso. Numero di paginaTipo di file |
| documentCompleted | Action`3 | Il delegato che riceve lo stream della pagina del documento convertito. Numero di paginaIl flusso di contenuto del fileIl nome del file |
| convertOptionsProvider | Func`3 | Converti fornitore di opzioni. Verrà richiamato per ogni conversione per fornire opzioni di conversione specifiche al tipo di documento di destinazione desiderato. Il nome del fileIl tipo di file |

### Osservazioni

**Saperne di più**

* Ulteriori informazioni sugli scenari di base della conversione dei documenti: [Come convertire un documento in 3 passaggi](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Casi d'uso di conversione, impostazioni avanzate e personalizzazioni: [Converti documento con impostazioni avanzate](https://docs.groupdocs.com/display/conversionnet/Converting)

### Guarda anche

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* spazio dei nomi [GroupDocs.Conversion](../../converter)
* assemblea [GroupDocs.Conversion](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
