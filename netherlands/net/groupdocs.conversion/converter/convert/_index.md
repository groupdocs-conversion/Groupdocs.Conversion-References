---
title: Convert
second_title: GroupDocs.Conversion voor .NET API-referentie
description: Converteert brondocument. Slaat het hele geconverteerde document op.
type: docs
weight: 20
url: /nl/net/groupdocs.conversion/converter/convert/
---
## Convert(Func&lt;Stream&gt;, ConvertOptions) {#convert}

Converteert brondocument. Slaat het hele geconverteerde document op.

```csharp
public void Convert(Func<Stream> document, ConvertOptions convertOptions)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| document | Func`1 | De gemachtigde die het geconverteerde document opslaat in een stroom. |
| convertOptions | ConvertOptions | De conversieopties die specifiek zijn voor het gewenste doelbestandstype. |

### Opmerkingen

**Kom meer te weten**

* Meer over basisscenario's voor documentconversie: [Documenten converteren in 3 stappen](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Gebruiksscenario's voor conversie, geavanceerde instellingen en aanpassingen: [Document converteren met geavanceerde instellingen](https://docs.groupdocs.com/display/conversionnet/Converting)

### Zie ook

* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* naamruimte [GroupDocs.Conversion](../../converter)
* montage [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;Stream&gt;, Action&lt;Stream, string&gt;, ConvertOptions) {#convert_1}

Converteert brondocument. Slaat het hele geconverteerde document op.

```csharp
public void Convert(Func<Stream> document, Action<Stream, string> documentCompleted, 
    ConvertOptions convertOptions)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| document | Func`1 | De gemachtigde die het geconverteerde document opslaat in een stroom. |
| documentCompleted | Action`2 | De gemachtigde die de geconverteerde documentstroom ontvangt. De inhoudsstroom van het bestandDe naam van het bestand |
| convertOptions | ConvertOptions | De conversieopties die specifiek zijn voor het gewenste doelbestandstype. |

### Opmerkingen

**Kom meer te weten**

* Meer over basisscenario's voor documentconversie: [Documenten converteren in 3 stappen](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Gebruiksscenario's voor conversie, geavanceerde instellingen en aanpassingen: [Document converteren met geavanceerde instellingen](https://docs.groupdocs.com/display/conversionnet/Converting)

### Zie ook

* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* naamruimte [GroupDocs.Conversion](../../converter)
* montage [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;Stream&gt;, Func&lt;string, FileType, ConvertOptions&gt;) {#convert_3}

Converteert brondocument. Slaat het hele geconverteerde document op.

```csharp
public void Convert(Func<Stream> document, 
    Func<string, FileType, ConvertOptions> convertOptionsProvider)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| document | Func`1 | De gemachtigde die het geconverteerde document opslaat in een stroom. |
| convertOptionsProvider | Func`3 | Converteer opties provider. Wordt voor elke conversie aangeroepen om specifieke conversieopties te bieden voor het gewenste doeldocumenttype. De naam van het bestandHet type van het bestand |

### Opmerkingen

**Kom meer te weten**

* Meer over basisscenario's voor documentconversie: [Documenten converteren in 3 stappen](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Gebruiksscenario's voor conversie, geavanceerde instellingen en aanpassingen: [Document converteren met geavanceerde instellingen](https://docs.groupdocs.com/display/conversionnet/Converting)

### Zie ook

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* naamruimte [GroupDocs.Conversion](../../converter)
* montage [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;Stream&gt;, Action&lt;Stream, string&gt;, Func&lt;string, FileType, ConvertOptions&gt;) {#convert_2}

Converteert brondocument. Slaat het hele geconverteerde document op.

```csharp
public void Convert(Func<Stream> document, Action<Stream, string> documentCompleted, 
    Func<string, FileType, ConvertOptions> convertOptionsProvider)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| document | Func`1 | De gemachtigde die het geconverteerde document opslaat in een stroom. |
| documentCompleted | Action`2 | De gemachtigde die de geconverteerde documentstroom ontvangt. De inhoudsstroom van het bestandDe naam van het bestand |
| convertOptionsProvider | Func`3 | Converteer opties provider. Wordt voor elke conversie aangeroepen om specifieke conversieopties te bieden voor het gewenste doeldocumenttype. De naam van het bestandHet type van het bestand |

### Opmerkingen

**Kom meer te weten**

* Meer over basisscenario's voor documentconversie: [Documenten converteren in 3 stappen](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Gebruiksscenario's voor conversie, geavanceerde instellingen en aanpassingen: [Document converteren met geavanceerde instellingen](https://docs.groupdocs.com/display/conversionnet/Converting)

### Zie ook

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* naamruimte [GroupDocs.Conversion](../../converter)
* montage [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;FileType, Stream&gt;, ConvertOptions) {#convert_4}

Converteert brondocument. Slaat het hele geconverteerde document op.

```csharp
public void Convert(Func<FileType, Stream> document, ConvertOptions convertOptions)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| document | Func`2 | De gemachtigde die het geconverteerde document opslaat in een stream. Het type van het bronbestand |
| convertOptions | ConvertOptions | De conversieopties die specifiek zijn voor het gewenste doelbestandstype. |

### Opmerkingen

**Kom meer te weten**

* Meer over basisscenario's voor documentconversie: [Documenten converteren in 3 stappen](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Gebruiksscenario's voor conversie, geavanceerde instellingen en aanpassingen: [Document converteren met geavanceerde instellingen](https://docs.groupdocs.com/display/conversionnet/Converting)

### Zie ook

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* naamruimte [GroupDocs.Conversion](../../converter)
* montage [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;FileType, Stream&gt;, Action&lt;Stream, string&gt;, ConvertOptions) {#convert_5}

Converteert brondocument. Slaat het hele geconverteerde document op.

```csharp
public void Convert(Func<FileType, Stream> document, Action<Stream, string> documentCompleted, 
    ConvertOptions convertOptions)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| document | Func`2 | De gemachtigde die het geconverteerde document opslaat in een stream. Het type van het bronbestand |
| documentCompleted | Action`2 | De gemachtigde die de geconverteerde documentstroom ontvangt. De inhoudsstroom van het bestandDe naam van het bestand |
| convertOptions | ConvertOptions | De conversieopties die specifiek zijn voor het gewenste doelbestandstype. |

### Opmerkingen

**Kom meer te weten**

* Meer over basisscenario's voor documentconversie: [Documenten converteren in 3 stappen](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Gebruiksscenario's voor conversie, geavanceerde instellingen en aanpassingen: [Document converteren met geavanceerde instellingen](https://docs.groupdocs.com/display/conversionnet/Converting)

### Zie ook

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* naamruimte [GroupDocs.Conversion](../../converter)
* montage [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;FileType, Stream&gt;, Func&lt;string, FileType, ConvertOptions&gt;) {#convert_7}

Converteert brondocument. Slaat het hele geconverteerde document op.

```csharp
public void Convert(Func<FileType, Stream> document, 
    Func<string, FileType, ConvertOptions> convertOptionsProvider)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| document | Func`2 | De gemachtigde die het geconverteerde document opslaat in een stream. Het type van het bronbestand |
| convertOptionsProvider | Func`3 | Converteer opties provider. Wordt voor elke conversie aangeroepen om specifieke conversieopties te bieden voor het gewenste doeldocumenttype. De naam van het bestandHet type van het bestand |

### Opmerkingen

**Kom meer te weten**

* Meer over basisscenario's voor documentconversie: [Documenten converteren in 3 stappen](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Gebruiksscenario's voor conversie, geavanceerde instellingen en aanpassingen: [Document converteren met geavanceerde instellingen](https://docs.groupdocs.com/display/conversionnet/Converting)

### Zie ook

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* naamruimte [GroupDocs.Conversion](../../converter)
* montage [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;FileType, Stream&gt;, Action&lt;Stream, string&gt;, Func&lt;string, FileType, ConvertOptions&gt;) {#convert_6}

Converteert brondocument. Slaat het hele geconverteerde document op.

```csharp
public void Convert(Func<FileType, Stream> document, Action<Stream, string> documentCompleted, 
    Func<string, FileType, ConvertOptions> convertOptionsProvider)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| document | Func`2 | De gemachtigde die het geconverteerde document opslaat in een stream. Het type van het bronbestand |
| documentCompleted | Action`2 | De gemachtigde die de geconverteerde documentstroom ontvangt. De inhoudsstroom van het bestandDe naam van het bestand |
| convertOptionsProvider | Func`3 | Converteer opties provider. Wordt voor elke conversie aangeroepen om specifieke conversieopties te bieden voor het gewenste doeldocumenttype. De naam van het bestandHet type van het bestand |

### Opmerkingen

**Kom meer te weten**

* Meer over basisscenario's voor documentconversie: [Documenten converteren in 3 stappen](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Gebruiksscenario's voor conversie, geavanceerde instellingen en aanpassingen: [Document converteren met geavanceerde instellingen](https://docs.groupdocs.com/display/conversionnet/Converting)

### Zie ook

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* naamruimte [GroupDocs.Conversion](../../converter)
* montage [GroupDocs.Conversion](../../../)

---

## Convert(string, ConvertOptions) {#convert_16}

Converteert brondocument. Slaat het hele geconverteerde document op.

```csharp
public void Convert(string filePath, ConvertOptions convertOptions)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| filePath | String | Het bestandspad naar het brondocument. |
| convertOptions | ConvertOptions | De conversieopties die specifiek zijn voor het gewenste doelbestandstype. |

### Opmerkingen

**Kom meer te weten**

* Meer over basisscenario's voor documentconversie: [Documenten converteren in 3 stappen](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Gebruiksscenario's voor conversie, geavanceerde instellingen en aanpassingen: [Document converteren met geavanceerde instellingen](https://docs.groupdocs.com/display/conversionnet/Converting)

### Zie ook

* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* naamruimte [GroupDocs.Conversion](../../converter)
* montage [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;int, Stream&gt;, ConvertOptions) {#convert_8}

Converteert brondocument. Slaat het geconverteerde document pagina voor pagina op.

```csharp
public void Convert(Func<int, Stream> document, ConvertOptions convertOptions)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| document | Func`2 | De gemachtigde die het geconverteerde document opslaat in een stream. Paginanummer |
| convertOptions | ConvertOptions | De conversieopties die specifiek zijn voor het gewenste doelbestandstype. |

### Opmerkingen

**Kom meer te weten**

* Meer over basisscenario's voor documentconversie: [Documenten converteren in 3 stappen](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Gebruiksscenario's voor conversie, geavanceerde instellingen en aanpassingen: [Document converteren met geavanceerde instellingen](https://docs.groupdocs.com/display/conversionnet/Converting)

### Zie ook

* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* naamruimte [GroupDocs.Conversion](../../converter)
* montage [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;int, Stream&gt;, Action&lt;int, Stream, string&gt;, ConvertOptions) {#convert_9}

Converteert brondocument. Slaat het geconverteerde document pagina voor pagina op.

```csharp
public void Convert(Func<int, Stream> document, Action<int, Stream, string> documentCompleted, 
    ConvertOptions convertOptions)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| document | Func`2 | De gemachtigde die de geconverteerde documentpagina opslaat in een stream. Paginanummer |
| documentCompleted | Action`3 | De gemachtigde die de geconverteerde documentpaginastream ontvangt. PaginanummerDe inhoudsstroom van het bestandDe naam van het bestand |
| convertOptions | ConvertOptions | De conversieopties die specifiek zijn voor het gewenste doelbestandstype. |

### Opmerkingen

**Kom meer te weten**

* Meer over basisscenario's voor documentconversie: [Documenten converteren in 3 stappen](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Gebruiksscenario's voor conversie, geavanceerde instellingen en aanpassingen: [Document converteren met geavanceerde instellingen](https://docs.groupdocs.com/display/conversionnet/Converting)

### Zie ook

* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* naamruimte [GroupDocs.Conversion](../../converter)
* montage [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;int, Stream&gt;, Func&lt;string, FileType, ConvertOptions&gt;) {#convert_11}

Converteert brondocument. Slaat het geconverteerde document pagina voor pagina op.

```csharp
public void Convert(Func<int, Stream> document, 
    Func<string, FileType, ConvertOptions> convertOptionsProvider)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| document | Func`2 | De gemachtigde die het geconverteerde document opslaat in een stream. Paginanummer |
| convertOptionsProvider | Func`3 | Converteer opties provider. Wordt voor elke conversie aangeroepen om specifieke conversieopties te bieden voor het gewenste doeldocumenttype. De naam van het bestandHet type van het bestand |

### Opmerkingen

**Kom meer te weten**

* Meer over basisscenario's voor documentconversie: [Documenten converteren in 3 stappen](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Gebruiksscenario's voor conversie, geavanceerde instellingen en aanpassingen: [Document converteren met geavanceerde instellingen](https://docs.groupdocs.com/display/conversionnet/Converting)

### Zie ook

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* naamruimte [GroupDocs.Conversion](../../converter)
* montage [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;int, Stream&gt;, Action&lt;int, Stream, string&gt;, Func&lt;string, FileType, ConvertOptions&gt;) {#convert_10}

Converteert brondocument. Slaat het geconverteerde document pagina voor pagina op.

```csharp
public void Convert(Func<int, Stream> document, Action<int, Stream, string> documentCompleted, 
    Func<string, FileType, ConvertOptions> convertOptionsProvider)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| document | Func`2 | De gemachtigde die de geconverteerde documentpagina opslaat in een stream. Paginanummer |
| documentCompleted | Action`3 | De gemachtigde die de geconverteerde documentpaginastream ontvangt. PaginanummerDe inhoudsstroom van het bestandDe naam van het bestand |
| convertOptionsProvider | Func`3 | Converteer opties provider. Wordt voor elke conversie aangeroepen om specifieke conversieopties te bieden voor het gewenste doeldocumenttype. De naam van het bestandHet type van het bestand |

### Opmerkingen

**Kom meer te weten**

* Meer over basisscenario's voor documentconversie: [Documenten converteren in 3 stappen](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Gebruiksscenario's voor conversie, geavanceerde instellingen en aanpassingen: [Document converteren met geavanceerde instellingen](https://docs.groupdocs.com/display/conversionnet/Converting)

### Zie ook

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* naamruimte [GroupDocs.Conversion](../../converter)
* montage [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;int, FileType, Stream&gt;, ConvertOptions) {#convert_12}

Converteert brondocument. Slaat het geconverteerde document pagina voor pagina op.

```csharp
public void Convert(Func<int, FileType, Stream> document, ConvertOptions convertOptions)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| document | Func`3 | De gemachtigde die het geconverteerde document opslaat in een stream. Paginanummer |
| convertOptions | ConvertOptions | De conversieopties die specifiek zijn voor het gewenste doelbestandstype. |

### Opmerkingen

**Kom meer te weten**

* Meer over basisscenario's voor documentconversie: [Documenten converteren in 3 stappen](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Gebruiksscenario's voor conversie, geavanceerde instellingen en aanpassingen: [Document converteren met geavanceerde instellingen](https://docs.groupdocs.com/display/conversionnet/Converting)

### Zie ook

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* naamruimte [GroupDocs.Conversion](../../converter)
* montage [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;int, FileType, Stream&gt;, Action&lt;int, Stream, string&gt;, ConvertOptions) {#convert_13}

Converteert brondocument. Slaat het geconverteerde document pagina voor pagina op.

```csharp
public void Convert(Func<int, FileType, Stream> document, 
    Action<int, Stream, string> documentCompleted, ConvertOptions convertOptions)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| document | Func`3 | De gemachtigde die de geconverteerde documentpagina opslaat in een stream. PaginanummerBestandstype |
| documentCompleted | Action`3 | De gemachtigde die de geconverteerde documentpaginastream ontvangt. PaginanummerDe inhoudsstroom van het bestandDe naam van het bestand |
| convertOptions | ConvertOptions | De conversieopties die specifiek zijn voor het gewenste doelbestandstype. |

### Opmerkingen

**Kom meer te weten**

* Meer over basisscenario's voor documentconversie: [Documenten converteren in 3 stappen](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Gebruiksscenario's voor conversie, geavanceerde instellingen en aanpassingen: [Document converteren met geavanceerde instellingen](https://docs.groupdocs.com/display/conversionnet/Converting)

### Zie ook

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* naamruimte [GroupDocs.Conversion](../../converter)
* montage [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;int, FileType, Stream&gt;, Func&lt;string, FileType, ConvertOptions&gt;) {#convert_15}

Converteert brondocument. Slaat het geconverteerde document pagina voor pagina op.

```csharp
public void Convert(Func<int, FileType, Stream> document, 
    Func<string, FileType, ConvertOptions> convertOptionsProvider)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| document | Func`3 | De gemachtigde die het geconverteerde document opslaat in een stream. PaginanummerBestandstype |
| convertOptionsProvider | Func`3 | Converteer opties provider. Wordt voor elke conversie aangeroepen om specifieke conversieopties te bieden voor het gewenste doeldocumenttype. De naam van het bestandHet type van het bestand |

### Opmerkingen

**Kom meer te weten**

* Meer over basisscenario's voor documentconversie: [Documenten converteren in 3 stappen](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Gebruiksscenario's voor conversie, geavanceerde instellingen en aanpassingen: [Document converteren met geavanceerde instellingen](https://docs.groupdocs.com/display/conversionnet/Converting)

### Zie ook

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* naamruimte [GroupDocs.Conversion](../../converter)
* montage [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;int, FileType, Stream&gt;, Action&lt;int, Stream, string&gt;, Func&lt;string, FileType, ConvertOptions&gt;) {#convert_14}

Converteert brondocument. Slaat het geconverteerde document pagina voor pagina op.

```csharp
public void Convert(Func<int, FileType, Stream> document, 
    Action<int, Stream, string> documentCompleted, 
    Func<string, FileType, ConvertOptions> convertOptionsProvider)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| document | Func`3 | De gemachtigde die de geconverteerde documentpagina opslaat in een stream. PaginanummerBestandstype |
| documentCompleted | Action`3 | De gemachtigde die de geconverteerde documentpaginastream ontvangt. PaginanummerDe inhoudsstroom van het bestandDe naam van het bestand |
| convertOptionsProvider | Func`3 | Converteer opties provider. Wordt voor elke conversie aangeroepen om specifieke conversieopties te bieden voor het gewenste doeldocumenttype. De naam van het bestandHet type van het bestand |

### Opmerkingen

**Kom meer te weten**

* Meer over basisscenario's voor documentconversie: [Documenten converteren in 3 stappen](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Gebruiksscenario's voor conversie, geavanceerde instellingen en aanpassingen: [Document converteren met geavanceerde instellingen](https://docs.groupdocs.com/display/conversionnet/Converting)

### Zie ook

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* naamruimte [GroupDocs.Conversion](../../converter)
* montage [GroupDocs.Conversion](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
