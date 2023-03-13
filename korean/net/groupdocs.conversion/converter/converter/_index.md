---
title: Converter
second_title: .NET API 참조용 GroupDocs.Conversion
description: 의 새 인스턴스를 초기화합니다.Convertergroupdocs.conversion/converter 클래스.
type: docs
weight: 10
url: /ko/net/groupdocs.conversion/converter/converter/
---
## Converter(Func&lt;Stream&gt;) {#constructor_1}

의 새 인스턴스를 초기화합니다.[`Converter`](../../converter) 클래스.

```csharp
public Converter(Func<Stream> document)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| document | Func`1 | 읽을 수 있는 스트림을 반환하는 메서드입니다. |

### 예외

| 예외 | 상태 |
| --- | --- |
| ArgumentNullException | 언제 던져*document* null입니다. |

### 비고

**더 알아보기**

* FTP, Amazon S3 저장소, Windows Azure 또는 기타 타사 저장소에 저장된 문서를 로드하고 변환하는 방법에 대한 추가 정보: [다른 소스에서 문서 로드](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* 파일 형식에 따른 문서 로드 옵션에 대한 추가 정보: [다양한 문서 유형에 대한 로드 옵션](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### 또한보십시오

* class [Converter](../../converter)
* 네임스페이스 [GroupDocs.Conversion](../../converter)
* 집회 [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;ConverterSettings&gt;) {#constructor_2}

의 새 인스턴스를 초기화합니다.[`Converter`](../../converter) 클래스.

```csharp
public Converter(Func<Stream> document, Func<ConverterSettings> settings)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| document | Func`1 | 읽을 수 있는 스트림을 반환하는 메서드입니다. |
| settings | Func`1 | 변환기 설정. |

### 비고

**더 알아보기**

* FTP, Amazon S3 저장소, Windows Azure 또는 기타 타사 저장소에 저장된 문서를 로드하고 변환하는 방법에 대한 추가 정보: [다른 소스에서 문서 로드](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* 파일 형식에 따른 문서 로드 옵션에 대한 추가 정보: [다양한 문서 유형에 대한 로드 옵션](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### 또한보십시오

* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* 네임스페이스 [GroupDocs.Conversion](../../converter)
* 집회 [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;) {#constructor_3}

의 새 인스턴스를 초기화합니다.[`Converter`](../../converter) 클래스.

```csharp
public Converter(Func<Stream> document, Func<LoadOptions> loadOptions)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| document | Func`1 | 읽을 수 있는 스트림을 반환하는 메서드입니다. |
| loadOptions | Func`1 | 문서 로드 옵션을 반환하는 메서드입니다. |

### 비고

**더 알아보기**

* FTP, Amazon S3 저장소, Windows Azure 또는 기타 타사 저장소에 저장된 문서를 로드하고 변환하는 방법에 대한 추가 정보: [다른 소스에서 문서 로드](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* 파일 형식에 따른 문서 로드 옵션에 대한 추가 정보: [다양한 문서 유형에 대한 로드 옵션](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### 또한보십시오

* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [Converter](../../converter)
* 네임스페이스 [GroupDocs.Conversion](../../converter)
* 집회 [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;LoadOptions&gt;, Func&lt;ConverterSettings&gt;) {#constructor_4}

의 새 인스턴스를 초기화합니다.[`Converter`](../../converter) 클래스.

```csharp
public Converter(Func<Stream> document, Func<LoadOptions> loadOptions, 
    Func<ConverterSettings> settings)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| document | Func`1 | 읽을 수 있는 스트림을 반환하는 메서드입니다. |
| loadOptions | Func`1 | 문서 로드 옵션을 반환하는 메서드입니다. |
| settings | Func`1 | 변환기 설정. |

### 비고

**더 알아보기**

* FTP, Amazon S3 저장소, Windows Azure 또는 기타 타사 저장소에 저장된 문서를 로드하고 변환하는 방법에 대한 추가 정보: [다른 소스에서 문서 로드](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* 파일 형식에 따른 문서 로드 옵션에 대한 추가 정보: [다양한 문서 유형에 대한 로드 옵션](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### 또한보십시오

* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* 네임스페이스 [GroupDocs.Conversion](../../converter)
* 집회 [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;FileType, LoadOptions&gt;) {#constructor_5}

의 새 인스턴스를 초기화합니다.[`Converter`](../../converter) 클래스.

```csharp
public Converter(Func<Stream> document, Func<FileType, LoadOptions> loadOptions)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| document | Func`1 | 읽을 수 있는 스트림을 반환하는 메서드입니다. |
| loadOptions | Func`2 | 문서 로드 옵션을 반환하는 메서드. 소스 파일의 유형 |

### 비고

**더 알아보기**

* FTP, Amazon S3 저장소, Windows Azure 또는 기타 타사 저장소에 저장된 문서를 로드하고 변환하는 방법에 대한 추가 정보: [다른 소스에서 문서 로드](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* 파일 형식에 따른 문서 로드 옵션에 대한 추가 정보: [다양한 문서 유형에 대한 로드 옵션](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### 또한보십시오

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [Converter](../../converter)
* 네임스페이스 [GroupDocs.Conversion](../../converter)
* 집회 [GroupDocs.Conversion](../../../)

---

## Converter(Func&lt;Stream&gt;, Func&lt;FileType, LoadOptions&gt;, Func&lt;ConverterSettings&gt;) {#constructor_6}

의 새 인스턴스를 초기화합니다.[`Converter`](../../converter) 클래스.

```csharp
public Converter(Func<Stream> document, Func<FileType, LoadOptions> loadOptions, 
    Func<ConverterSettings> settings)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| document | Func`1 | 읽을 수 있는 스트림을 반환하는 메서드입니다. |
| loadOptions | Func`2 | 문서 로드 옵션을 반환하는 메서드. 소스 파일의 유형 |
| settings | Func`1 | 변환기 설정. |

### 비고

**더 알아보기**

* FTP, Amazon S3 저장소, Windows Azure 또는 기타 타사 저장소에 저장된 문서를 로드하고 변환하는 방법에 대한 추가 정보: [다른 소스에서 문서 로드](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* 파일 형식에 따른 문서 로드 옵션에 대한 추가 정보: [다양한 문서 유형에 대한 로드 옵션](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### 또한보십시오

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* 네임스페이스 [GroupDocs.Conversion](../../converter)
* 집회 [GroupDocs.Conversion](../../../)

---

## Converter(string) {#constructor_7}

의 새 인스턴스를 초기화합니다.[`Converter`](../../converter) 클래스.

```csharp
public Converter(string filePath)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| filePath | String | 소스 문서의 파일 경로입니다. |

### 비고

**더 알아보기**

* FTP, Amazon S3 저장소, Windows Azure 또는 기타 타사 저장소에 저장된 문서를 로드하고 변환하는 방법에 대한 추가 정보: [다른 소스에서 문서 로드](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* 파일 형식에 따른 문서 로드 옵션에 대한 추가 정보: [다양한 문서 유형에 대한 로드 옵션](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### 또한보십시오

* class [Converter](../../converter)
* 네임스페이스 [GroupDocs.Conversion](../../converter)
* 집회 [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;ConverterSettings&gt;) {#constructor_8}

의 새 인스턴스를 초기화합니다.[`Converter`](../../converter) 클래스.

```csharp
public Converter(string filePath, Func<ConverterSettings> settings)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| filePath | String | 소스 문서의 파일 경로입니다. |
| settings | Func`1 | 변환기 설정. |

### 비고

**더 알아보기**

* FTP, Amazon S3 저장소, Windows Azure 또는 기타 타사 저장소에 저장된 문서를 로드하고 변환하는 방법에 대한 추가 정보: [다른 소스에서 문서 로드](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* 파일 형식에 따른 문서 로드 옵션에 대한 추가 정보: [다양한 문서 유형에 대한 로드 옵션](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### 또한보십시오

* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* 네임스페이스 [GroupDocs.Conversion](../../converter)
* 집회 [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;LoadOptions&gt;) {#constructor_9}

의 새 인스턴스를 초기화합니다.[`Converter`](../../converter) 클래스.

```csharp
public Converter(string filePath, Func<LoadOptions> loadOptions)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| filePath | String | 소스 문서의 파일 경로입니다. |
| loadOptions | Func`1 | 문서 로드 옵션을 반환하는 메서드입니다. |

### 비고

**더 알아보기**

* FTP, Amazon S3 저장소, Windows Azure 또는 기타 타사 저장소에 저장된 문서를 로드하고 변환하는 방법에 대한 추가 정보: [다른 소스에서 문서 로드](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* 파일 형식에 따른 문서 로드 옵션에 대한 추가 정보: [다양한 문서 유형에 대한 로드 옵션](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### 또한보십시오

* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [Converter](../../converter)
* 네임스페이스 [GroupDocs.Conversion](../../converter)
* 집회 [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;LoadOptions&gt;, Func&lt;ConverterSettings&gt;) {#constructor_10}

의 새 인스턴스를 초기화합니다.[`Converter`](../../converter) 클래스.

```csharp
public Converter(string filePath, Func<LoadOptions> loadOptions, Func<ConverterSettings> settings)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| filePath | String | 소스 문서의 파일 경로입니다. |
| loadOptions | Func`1 | 문서 로드 옵션을 반환하는 메서드입니다. |
| settings | Func`1 | 변환기 설정. |

### 비고

**더 알아보기**

* FTP, Amazon S3 저장소, Windows Azure 또는 기타 타사 저장소에 저장된 문서를 로드하고 변환하는 방법에 대한 추가 정보: [다른 소스에서 문서 로드](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* 파일 형식에 따른 문서 로드 옵션에 대한 추가 정보: [다양한 문서 유형에 대한 로드 옵션](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### 또한보십시오

* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* 네임스페이스 [GroupDocs.Conversion](../../converter)
* 집회 [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;FileType, LoadOptions&gt;) {#constructor_11}

의 새 인스턴스를 초기화합니다.[`Converter`](../../converter) 클래스.

```csharp
public Converter(string filePath, Func<FileType, LoadOptions> loadOptions)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| filePath | String | 소스 문서의 파일 경로입니다. |
| loadOptions | Func`2 | 문서 로드 옵션을 반환하는 메서드. 소스 파일의 유형 |

### 비고

**더 알아보기**

* FTP, Amazon S3 저장소, Windows Azure 또는 기타 타사 저장소에 저장된 문서를 로드하고 변환하는 방법에 대한 추가 정보: [다른 소스에서 문서 로드](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* 파일 형식에 따른 문서 로드 옵션에 대한 추가 정보: [다양한 문서 유형에 대한 로드 옵션](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### 또한보십시오

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [Converter](../../converter)
* 네임스페이스 [GroupDocs.Conversion](../../converter)
* 집회 [GroupDocs.Conversion](../../../)

---

## Converter(string, Func&lt;FileType, LoadOptions&gt;, Func&lt;ConverterSettings&gt;) {#constructor_12}

의 새 인스턴스를 초기화합니다.[`Converter`](../../converter) 클래스.

```csharp
public Converter(string filePath, Func<FileType, LoadOptions> loadOptions, 
    Func<ConverterSettings> settings)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| filePath | String | 소스 문서의 파일 경로입니다. |
| loadOptions | Func`2 | 문서 로드 옵션을 반환하는 메서드. 소스 파일의 유형 |
| settings | Func`1 | 변환기 설정. |

### 비고

**더 알아보기**

* FTP, Amazon S3 저장소, Windows Azure 또는 기타 타사 저장소에 저장된 문서를 로드하고 변환하는 방법에 대한 추가 정보: [다른 소스에서 문서 로드](https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources)
* 파일 형식에 따른 문서 로드 옵션에 대한 추가 정보: [다양한 문서 유형에 대한 로드 옵션](https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types)

### 또한보십시오

* class [FileType](../../../groupdocs.conversion.filetypes/filetype)
* class [LoadOptions](../../../groupdocs.conversion.options.load/loadoptions)
* class [ConverterSettings](../../convertersettings)
* class [Converter](../../converter)
* 네임스페이스 [GroupDocs.Conversion](../../converter)
* 집회 [GroupDocs.Conversion](../../../)

---

## Converter() {#constructor}

의 새 인스턴스를 초기화합니다.[`Converter`](../../converter) 유창한 변환 설정을 위한 클래스.

```csharp
public Converter()
```

### 비고

샘플 유창한 변환 사용:

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

### 또한보십시오

* class [Converter](../../converter)
* 네임스페이스 [GroupDocs.Conversion](../../converter)
* 집회 [GroupDocs.Conversion](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
