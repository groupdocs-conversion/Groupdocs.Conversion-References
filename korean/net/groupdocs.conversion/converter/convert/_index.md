---
title: "Convert"
second_title: "GroupDocs.Conversion for .NET API 참조"
description: "소스 문서를 변환합니다. 변환된 전체 문서를 저장합니다."
type: docs
weight: 20
url: /ko/net/groupdocs.conversion/converter/convert/
---
## Convert(Func&lt;SaveContext, Stream&gt;, ConvertOptions, CancellationToken) {#convert_4}

소스 문서를 변환합니다. 변환된 전체 문서를 저장합니다.

```csharp
public void Convert(Func<SaveContext, Stream> targetStreamProvider, ConvertOptions convertOptions, 
    CancellationToken cancellationToken = default)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| targetStreamProvider | Func`2 | 변환된 문서를 스트림에 저장하는 대리자입니다. |
| convertOptions | ConvertOptions | 원하는 대상 파일 형식에 특정한 변환 옵션입니다. |
| cancellationToken | CancellationToken | 취소 토큰입니다. |

### 비고

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### 또 보기

* class [SaveContext](../../savecontext)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(ConvertOptions, Action&lt;ConvertedContext&gt;, CancellationToken) {#convert}

소스 문서를 변환합니다. 변환된 전체 문서를 저장합니다.

```csharp
public void Convert(ConvertOptions convertOptions, Action<ConvertedContext> documentCompleted, 
    CancellationToken cancellationToken = default)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| convertOptions | ConvertOptions | 원하는 대상 파일 형식에 특정한 변환 옵션입니다. |
| documentCompleted | Action`1 | 변환된 문서 스트림을 받는 대리자. 서명: `Action<ConvertedContext>`. [`ConvertedContext`](../../convertedcontext) 매개변수에는 변환된 문서 스트림과 메타데이터가 포함됩니다. |
| cancellationToken | CancellationToken | 취소 토큰입니다. |

### 비고

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### 또 보기

* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [ConvertedContext](../../convertedcontext)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;SaveContext, Stream&gt;, Func&lt;ConvertContext, ConvertOptions&gt;, CancellationToken) {#convert_5}

소스 문서를 변환합니다. 변환된 전체 문서를 저장합니다.

```csharp
public void Convert(Func<SaveContext, Stream> targetStreamProvider, 
    Func<ConvertContext, ConvertOptions> convertOptionsProvider, 
    CancellationToken cancellationToken = default)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| targetStreamProvider | Func`2 | 변환된 문서를 저장하기 위한 스트림을 제공하는 대리자. 서명: `Func<SaveContext, Stream>`. [`SaveContext`](../../savecontext) 매개변수에는 저장 작업에 대한 정보가 포함됩니다. |
| convertOptionsProvider | Func`2 | 변환 옵션을 제공하는 대리자. 서명: `Func<ConvertContext, ConvertOptions>`. [`ConvertContext`](../../convertcontext) 매개변수에는 변환 작업에 대한 정보가 포함됩니다. |
| cancellationToken | CancellationToken | 취소 토큰입니다. |

### 비고

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### 또 보기

* class [SaveContext](../../savecontext)
* class [ConvertContext](../../convertcontext)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;ConvertContext, ConvertOptions&gt;, Action&lt;ConvertedContext&gt;, CancellationToken) {#convert_2}

소스 문서를 변환합니다. 변환된 전체 문서를 저장합니다.

```csharp
public void Convert(Func<ConvertContext, ConvertOptions> convertOptionsProvider, 
    Action<ConvertedContext> documentCompleted, CancellationToken cancellationToken = default)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| convertOptionsProvider | Func`2 | 변환 옵션을 제공하는 대리자. 서명: `Func<ConvertContext, ConvertOptions>`. [`ConvertContext`](../../convertcontext) 매개변수에는 변환 작업에 대한 정보가 포함됩니다. |
| documentCompleted | Action`1 | 변환된 문서 스트림을 받는 대리자. 서명: `Action<ConvertedContext>`. [`ConvertedContext`](../../convertedcontext) 매개변수에는 변환된 문서 스트림과 메타데이터가 포함됩니다. |
| cancellationToken | CancellationToken | 취소 토큰입니다. |

### 비고

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### 또 보기

* class [ConvertContext](../../convertcontext)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [ConvertedContext](../../convertedcontext)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(string, ConvertOptions, CancellationToken) {#convert_8}

소스 문서를 변환합니다. 변환된 전체 문서를 저장합니다.

```csharp
public void Convert(string filePath, ConvertOptions convertOptions, 
    CancellationToken cancellationToken = default)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| filePath | String | 소스 문서의 파일 경로. |
| convertOptions | ConvertOptions | 원하는 대상 파일 형식에 특정한 변환 옵션입니다. |
| cancellationToken | CancellationToken | 취소 토큰입니다. |

### 비고

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### 또 보기

* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;SavePageContext, Stream&gt;, Func&lt;ConvertContext, ConvertOptions&gt;, CancellationToken) {#convert_7}

소스 문서를 변환합니다. 변환된 문서를 페이지별로 저장합니다.

```csharp
public void Convert(Func<SavePageContext, Stream> targetStreamProvider, 
    Func<ConvertContext, ConvertOptions> convertOptionsProvider, 
    CancellationToken cancellationToken = default)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| targetStreamProvider | Func`2 | 각 변환된 페이지를 저장하기 위한 스트림을 제공하는 대리자. 서명: `Func<SavePageContext, Stream>`. [`SavePageContext`](../../savepagecontext) 매개변수에는 페이지 번호와 문서 정보가 포함됩니다. |
| convertOptionsProvider | Func`2 | 변환 옵션을 제공하는 대리자. 서명: `Func<ConvertContext, ConvertOptions>`. [`ConvertContext`](../../convertcontext) 매개변수에는 변환 작업에 대한 정보가 포함됩니다. |
| cancellationToken | CancellationToken | 취소 토큰입니다. |

### 비고

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### 또 보기

* class [SavePageContext](../../savepagecontext)
* class [ConvertContext](../../convertcontext)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;SavePageContext, Stream&gt;, ConvertOptions, CancellationToken) {#convert_6}

소스 문서를 변환합니다. 변환된 문서를 페이지별로 저장합니다.

```csharp
public void Convert(Func<SavePageContext, Stream> targetStreamProvider, 
    ConvertOptions convertOptions, CancellationToken cancellationToken = default)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| targetStreamProvider | Func`2 | 각 변환된 페이지를 저장하기 위한 스트림을 제공하는 대리자. 서명: `Func<SavePageContext, Stream>`. [`SavePageContext`](../../savepagecontext) 매개변수에는 페이지 번호와 문서 정보가 포함됩니다. |
| convertOptions | ConvertOptions | 원하는 대상 파일 형식에 특정한 변환 옵션입니다. |
| cancellationToken | CancellationToken | 취소 토큰입니다. |

### 비고

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### 또 보기

* class [SavePageContext](../../savepagecontext)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(ConvertOptions, Action&lt;ConvertedPageContext&gt;, CancellationToken) {#convert_1}

소스 문서를 변환합니다. 변환된 문서를 페이지별로 저장합니다.

```csharp
public void Convert(ConvertOptions convertOptions, Action<ConvertedPageContext> documentCompleted, 
    CancellationToken cancellationToken = default)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| documentCompleted | ConvertOptions | 각 변환된 페이지를 받는 대리자. 서명: `Action<ConvertedPageContext>`. [`ConvertedPageContext`](../../convertedpagecontext) 매개변수에는 페이지 번호, 스트림, 소스 파일 이름 및 대상 파일 형식이 포함됩니다. |
| convertOptions | Action`1 | 원하는 대상 파일 형식에 특정한 변환 옵션입니다. |
| cancellationToken | CancellationToken | 취소 토큰입니다. |

### 비고

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### 또 보기

* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [ConvertedPageContext](../../convertedpagecontext)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Convert(Func&lt;ConvertContext, ConvertOptions&gt;, Action&lt;ConvertedPageContext&gt;, CancellationToken) {#convert_3}

소스 문서를 변환합니다. 변환된 문서를 페이지별로 저장합니다.

```csharp
public void Convert(Func<ConvertContext, ConvertOptions> convertOptionsProvider, 
    Action<ConvertedPageContext> documentCompleted, CancellationToken cancellationToken = default)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| convertOptionsProvider | Func`2 | 변환 옵션을 제공하는 대리자. 서명: `Func<ConvertContext, ConvertOptions>`. [`ConvertContext`](../../convertcontext) 매개변수에는 변환 작업에 대한 정보가 포함됩니다. |
| documentCompleted | Action`1 | 각 변환된 페이지를 받는 대리자. 서명: `Action<ConvertedPageContext>`. [`ConvertedPageContext`](../../convertedpagecontext) 매개변수에는 페이지 번호, 스트림, 소스 파일 이름 및 대상 파일 형식이 포함됩니다. |
| cancellationToken | CancellationToken | 취소 토큰입니다. |

### 비고

**Learn more**

* More about document conversion basic scenarios: [How to convert document in 3 steps](https://docs.groupdocs.com/display/conversionnet/Convert+document)
* Conversion use cases, advanced settings and customizations: [Convert document with advanced settings](https://docs.groupdocs.com/display/conversionnet/Converting)

### 또 보기

* class [ConvertContext](../../convertcontext)
* class [ConvertOptions](../../../groupdocs.conversion.options.convert/convertoptions)
* class [ConvertedPageContext](../../convertedpagecontext)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.conversion.dll -->
