---
title: "Converter"
second_title: "GroupDocs.Conversion for .NET API 참조"
description: "Convertergroupdocs.conversion/converter 클래스의 새 인스턴스를 초기화합니다."
type: docs
weight: 10
url: /ko/net/groupdocs.conversion/converter/converter/
---
## Converter(Func&lt;Stream&gt;) {#constructor}

[`Converter`](../../converter) 클래스의 새 인스턴스를 초기화합니다.

```csharp
public Converter(Func<Stream> sourceStreamProvider)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| sourceStreamProvider | Func`1 | 읽을 수 있는 스트림을 반환하는 메서드. |

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentNullException | *sourceStreamProvider*가 null인 경우 발생합니다. |

### 비고

**Learn more**

* More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* More about document loading options dependent on file type: [Load options for different document types](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### 또 보기

* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;ConverterSettings&gt;) {#constructor_1}

[`Converter`](../../converter) 클래스의 새 인스턴스를 초기화합니다.

```csharp
public Converter(Func<Stream> sourceStreamProvider, Func<ConverterSettings> settings)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| sourceStreamProvider | Func`1 | 읽을 수 있는 스트림을 반환하는 메서드. |
| settings | Func`1 | Converter 설정. |

### 비고

**Learn more**

* More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* More about document loading options dependent on file type: [Load options for different document types](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### 또 보기

* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;LoadContext, LoadOptions&gt;, Func&lt;ConverterSettings&gt;) {#constructor_3}

[`Converter`](../../converter) 클래스의 새 인스턴스를 초기화합니다.

```csharp
public Converter(Func<Stream> sourceStreamProvider, Func<LoadContext, LoadOptions> loadOptions, 
    Func<ConverterSettings> settings = null)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| sourceStreamProvider | Func`1 | 읽을 수 있는 스트림을 반환하는 메서드. |
| loadOptions | Func`2 | 문서에 대한 로드 옵션을 제공하는 대리자. 서명: `Func<LoadContext, LoadOptions>`. [`LoadContext`](../../loadcontext) 매개변수에는 로드되는 문서에 대한 정보가 포함됩니다. |
| settings | Func`1 | Converter 설정. |

### 비고

**Learn more**

* More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* More about document loading options dependent on file type: [Load options for different document types](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### 또 보기

* class [LoadContext](../../loadcontext)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;LoadContext, LoadOptions&gt;, Func&lt;ConverterSettings&gt;, Func&lt;ConversionEvents&gt;) {#constructor_4}

명시적 변환 이벤트와 함께 [`Converter`](../../converter) 클래스의 새 인스턴스를 초기화합니다.

```csharp
public Converter(Func<Stream> sourceStreamProvider, Func<LoadContext, LoadOptions> loadOptions, 
    Func<ConverterSettings> settings, Func<ConversionEvents> events)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| sourceStreamProvider | Func`1 | 읽을 수 있는 스트림을 반환하는 메서드. |
| loadOptions | Func`2 | 문서에 대한 로드 옵션을 제공하는 대리자. |
| settings | Func`1 | Converter 설정. |
| events | Func`1 | 컨버터 수명 동안 등록된 집계된 [`ConversionEvents`](../../conversionevents)를 제공하는 대리자. |

### 또 보기

* class [LoadContext](../../loadcontext)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [ConverterSettings](../../convertersettings)
* class [ConversionEvents](../../conversionevents)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;ConverterSettings&gt;, Func&lt;ConversionEvents&gt;) {#constructor_2}

명시적 변환 이벤트와 함께 [`Converter`](../../converter) 클래스의 새 인스턴스를 초기화합니다.

```csharp
public Converter(Func<Stream> sourceStreamProvider, Func<ConverterSettings> settings, 
    Func<ConversionEvents> events)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| sourceStreamProvider | Func`1 | 읽을 수 있는 스트림을 반환하는 메서드. |
| settings | Func`1 | Converter 설정. |
| events | Func`1 | 컨버터 수명 동안 등록된 집계된 [`ConversionEvents`](../../conversionevents)를 제공하는 대리자. |

### 또 보기

* class [ConverterSettings](../../convertersettings)
* class [ConversionEvents](../../conversionevents)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(string) {#constructor_5}

[`Converter`](../../converter) 클래스의 새 인스턴스를 초기화합니다.

```csharp
public Converter(string filePath)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| filePath | String | 소스 문서의 파일 경로. |

### 비고

**Learn more**

* More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* More about document loading options dependent on file type: [Load options for different document types](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### 또 보기

* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;ConverterSettings&gt;) {#constructor_6}

[`Converter`](../../converter) 클래스의 새 인스턴스를 초기화합니다.

```csharp
public Converter(string filePath, Func<ConverterSettings> settings)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| filePath | String | 소스 문서의 파일 경로. |
| settings | Func`1 | Converter 설정. |

### 비고

**Learn more**

* More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* More about document loading options dependent on file type: [Load options for different document types](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### 또 보기

* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;LoadContext, LoadOptions&gt;, Func&lt;ConverterSettings&gt;) {#constructor_8}

[`Converter`](../../converter) 클래스의 새 인스턴스를 초기화합니다.

```csharp
public Converter(string filePath, Func<LoadContext, LoadOptions> loadOptions, 
    Func<ConverterSettings> settings = null)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| filePath | String | 소스 문서의 파일 경로. |
| loadOptions | Func`2 | 문서에 대한 로드 옵션을 제공하는 대리자. 서명: `Func<LoadContext, LoadOptions>`. [`LoadContext`](../../loadcontext) 매개변수에는 로드되는 문서에 대한 정보가 포함됩니다. |
| settings | Func`1 | Converter 설정. |

### 비고

**Learn more**

* More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* More about document loading options dependent on file type: [Load options for different document types](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### 또 보기

* class [LoadContext](../../loadcontext)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;LoadContext, LoadOptions&gt;, Func&lt;ConverterSettings&gt;, Func&lt;ConversionEvents&gt;) {#constructor_9}

명시적 변환 이벤트와 함께 [`Converter`](../../converter) 클래스의 새 인스턴스를 초기화합니다.

```csharp
public Converter(string filePath, Func<LoadContext, LoadOptions> loadOptions, 
    Func<ConverterSettings> settings, Func<ConversionEvents> events)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| filePath | String | 소스 문서의 파일 경로. |
| loadOptions | Func`2 | 문서에 대한 로드 옵션을 제공하는 대리자. |
| settings | Func`1 | Converter 설정. |
| events | Func`1 | 컨버터 수명 동안 등록된 집계된 [`ConversionEvents`](../../conversionevents)를 제공하는 대리자. |

### 또 보기

* class [LoadContext](../../loadcontext)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [ConverterSettings](../../convertersettings)
* class [ConversionEvents](../../conversionevents)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;ConverterSettings&gt;, Func&lt;ConversionEvents&gt;) {#constructor_7}

명시적 변환 이벤트와 함께 [`Converter`](../../converter) 클래스의 새 인스턴스를 초기화합니다.

```csharp
public Converter(string filePath, Func<ConverterSettings> settings, Func<ConversionEvents> events)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| filePath | String | 소스 문서의 파일 경로. |
| settings | Func`1 | Converter 설정. |
| events | Func`1 | 컨버터 수명 동안 등록된 집계된 [`ConversionEvents`](../../conversionevents)를 제공하는 대리자. |

### 또 보기

* class [ConverterSettings](../../convertersettings)
* class [ConversionEvents](../../conversionevents)
* class [Converter](../../converter)
* namespace [GroupDocs.Conversion](../../../groupdocs.conversion)
* assembly [GroupDocs.Conversion](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.conversion.dll -->
