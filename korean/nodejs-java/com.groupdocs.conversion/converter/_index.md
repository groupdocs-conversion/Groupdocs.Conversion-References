---
title: "Converter"
second_title: "Node.js용 GroupDocs.Conversion (Java 경유) API 레퍼런스"
description: "문서 변환 프로세스를 제어하는 ​​주요 클래스를 나타냅니다."
type: docs
weight: 10
url: /ko/nodejs-java/com.groupdocs.conversion/converter/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable
```
public class Converter implements Closeable
```

문서 변환 프로세스를 제어하는 ​​주요 클래스를 나타냅니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [Converter()](#Converter--) | 유창한 변환 설정을 위해  클래스의 새 인스턴스를 초기화합니다. |
| [Converter(Supplier<InputStream> document)](#Converter-java.util.function.Supplier-java.io.InputStream--) | [Converter](../../com.groupdocs.conversion/converter) 클래스의 새 인스턴스를 초기화합니다. |
| [Converter(Supplier<InputStream> document, ConverterSettingsProvider settings)](#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.ConverterSettingsProvider-) | [Converter](../../com.groupdocs.conversion/converter) 클래스의 새 인스턴스를 초기화합니다. |
| [Converter(Supplier<InputStream> document, LoadOptionsProvider loadOptions)](#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.LoadOptionsProvider-) | [Converter](../../com.groupdocs.conversion/converter) 클래스의 새 인스턴스를 초기화합니다. |
| [Converter(Supplier<InputStream> document, LoadOptionsProvider loadOptions, ConverterSettingsProvider settings)](#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.LoadOptionsProvider-com.groupdocs.conversion.contracts.ConverterSettingsProvider-) | [Converter](../../com.groupdocs.conversion/converter) 클래스의 새 인스턴스를 초기화합니다. |
| [Converter(Supplier<InputStream> document, LoadOptionsForFileTypeProvider loadOptions)](#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.LoadOptionsForFileTypeProvider-) |   클래스의 새 인스턴스를 초기화합니다. |
| [Converter(Supplier<InputStream> document, LoadOptionsForFileTypeProvider loadOptions, ConverterSettingsProvider settings)](#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.LoadOptionsForFileTypeProvider-com.groupdocs.conversion.contracts.ConverterSettingsProvider-) |   클래스의 새 인스턴스를 초기화합니다. |
| [Converter(String filePath)](#Converter-java.lang.String-) | [Converter](../../com.groupdocs.conversion/converter) 클래스의 새 인스턴스를 초기화합니다. |
| [Converter(String filePath, ConverterSettingsProvider settings)](#Converter-java.lang.String-com.groupdocs.conversion.contracts.ConverterSettingsProvider-) | [Converter](../../com.groupdocs.conversion/converter) 클래스의 새 인스턴스를 초기화합니다. |
| [Converter(String filePath, LoadOptionsProvider loadOptions)](#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsProvider-) | [Converter](../../com.groupdocs.conversion/converter) 클래스의 새 인스턴스를 초기화합니다. |
| [Converter(String filePath, LoadOptionsProvider loadOptions, ConverterSettingsProvider settings)](#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsProvider-com.groupdocs.conversion.contracts.ConverterSettingsProvider-) | [Converter](../../com.groupdocs.conversion/converter) 클래스의 새 인스턴스를 초기화합니다. |
| [Converter(String filePath, LoadOptionsForFileTypeProvider loadOptions)](#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsForFileTypeProvider-) |   클래스의 새 인스턴스를 초기화합니다. |
| [Converter(String filePath, LoadOptionsForFileTypeProvider loadOptions, ConverterSettingsProvider settings)](#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsForFileTypeProvider-com.groupdocs.conversion.contracts.ConverterSettingsProvider-) |   클래스의 새 인스턴스를 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [tweakPackageUtil(String vendor, String version, String specTitle)](#tweakPackageUtil-java.lang.String-java.lang.String-java.lang.String-) |  |
| [convert(SaveDocumentStream document, ConvertOptions convertOptions)](#convert-com.groupdocs.conversion.contracts.SaveDocumentStream-com.groupdocs.conversion.options.convert.ConvertOptions-) | 소스 문서를 변환합니다. |
| [convert(SaveDocumentStream document, ConvertedDocumentStream documentCompleted, ConvertOptions convertOptions)](#convert-com.groupdocs.conversion.contracts.SaveDocumentStream-com.groupdocs.conversion.contracts.ConvertedDocumentStream-com.groupdocs.conversion.options.convert.ConvertOptions-) | 소스 문서를 변환합니다. |
| [convert(SaveDocumentStream document, ConvertOptionsProvider convertOptionsProvider)](#convert-com.groupdocs.conversion.contracts.SaveDocumentStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-) | 소스 문서를 변환합니다. |
| [convert(SaveDocumentStream document, ConvertedDocumentStream documentCompleted, ConvertOptionsProvider convertOptionsProvider)](#convert-com.groupdocs.conversion.contracts.SaveDocumentStream-com.groupdocs.conversion.contracts.ConvertedDocumentStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-) | 소스 문서를 변환합니다. |
| [convert(SaveDocumentStreamForFileType document, ConvertOptions convertOptions)](#convert-com.groupdocs.conversion.contracts.SaveDocumentStreamForFileType-com.groupdocs.conversion.options.convert.ConvertOptions-) | 소스 문서를 변환합니다. |
| [convert(SaveDocumentStreamForFileType document, ConvertedDocumentStream documentCompleted, ConvertOptions convertOptions)](#convert-com.groupdocs.conversion.contracts.SaveDocumentStreamForFileType-com.groupdocs.conversion.contracts.ConvertedDocumentStream-com.groupdocs.conversion.options.convert.ConvertOptions-) | 소스 문서를 변환합니다. |
| [convert(SaveDocumentStreamForFileType document, ConvertOptionsProvider convertOptionsProvider)](#convert-com.groupdocs.conversion.contracts.SaveDocumentStreamForFileType-com.groupdocs.conversion.contracts.ConvertOptionsProvider-) | 소스 문서를 변환합니다. |
| [convert(SaveDocumentStreamForFileType document, ConvertedDocumentStream documentCompleted, ConvertOptionsProvider convertOptionsProvider)](#convert-com.groupdocs.conversion.contracts.SaveDocumentStreamForFileType-com.groupdocs.conversion.contracts.ConvertedDocumentStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-) | 소스 문서를 변환합니다. |
| [convert(String filePath, ConvertOptions convertOptions)](#convert-java.lang.String-com.groupdocs.conversion.options.convert.ConvertOptions-) | 소스 문서를 변환합니다. |
| [convert(SavePageStream document, ConvertOptions convertOptions)](#convert-com.groupdocs.conversion.contracts.SavePageStream-com.groupdocs.conversion.options.convert.ConvertOptions-) | 소스 문서를 변환합니다. |
| [convert(SavePageStream document, ConvertedPageStream documentCompleted, ConvertOptions convertOptions)](#convert-com.groupdocs.conversion.contracts.SavePageStream-com.groupdocs.conversion.contracts.ConvertedPageStream-com.groupdocs.conversion.options.convert.ConvertOptions-) | 소스 문서를 변환합니다. |
| [convert(SavePageStream document, ConvertOptionsProvider convertOptionsProvider)](#convert-com.groupdocs.conversion.contracts.SavePageStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-) | 소스 문서를 변환합니다. |
| [convert(SavePageStream document, ConvertedPageStream documentCompleted, ConvertOptionsProvider convertOptionsProvider)](#convert-com.groupdocs.conversion.contracts.SavePageStream-com.groupdocs.conversion.contracts.ConvertedPageStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-) | 소스 문서를 변환합니다. |
| [convert(SavePageStreamForFileType document, ConvertOptions convertOptions)](#convert-com.groupdocs.conversion.contracts.SavePageStreamForFileType-com.groupdocs.conversion.options.convert.ConvertOptions-) | 소스 문서를 변환합니다. |
| [convert(SavePageStreamForFileType document, ConvertedPageStream documentCompleted, ConvertOptions convertOptions)](#convert-com.groupdocs.conversion.contracts.SavePageStreamForFileType-com.groupdocs.conversion.contracts.ConvertedPageStream-com.groupdocs.conversion.options.convert.ConvertOptions-) | 소스 문서를 변환합니다. |
| [convert(SavePageStreamForFileType document, ConvertOptionsProvider convertOptionsProvider)](#convert-com.groupdocs.conversion.contracts.SavePageStreamForFileType-com.groupdocs.conversion.contracts.ConvertOptionsProvider-) | 소스 문서를 변환합니다. |
| [convert(SavePageStreamForFileType document, ConvertedPageStream documentCompleted, ConvertOptionsProvider convertOptionsProvider)](#convert-com.groupdocs.conversion.contracts.SavePageStreamForFileType-com.groupdocs.conversion.contracts.ConvertedPageStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-) | 소스 문서를 변환합니다. |
| [withSettings(ConverterSettingsProvider settingsProvider)](#withSettings-com.groupdocs.conversion.contracts.ConverterSettingsProvider-) |  |
| [load(String fileName)](#load-java.lang.String-) |  |
| [load(String[] fileNames)](#load-java.lang.String---) |  |
| [load(DocumentStreamProvider documentStreamProvider)](#load-com.groupdocs.conversion.contracts.DocumentStreamProvider-) |  |
| [load(DocumentStreamsProvider documentStreamProvider)](#load-com.groupdocs.conversion.contracts.DocumentStreamsProvider-) |  |
| [getDocumentInfo()](#getDocumentInfo--) | 소스 문서 정보를 가져옵니다 - 페이지 수 및 파일 유형에 특정한 기타 문서 속성. |
| [isDocumentPasswordProtected()](#isDocumentPasswordProtected--) | 소스 문서가 비밀번호로 보호되어 있는지 확인합니다. |
| [getPossibleConversions()](#getPossibleConversions--) | 소스 문서에 대한 가능한 변환을 가져옵니다. |
|  | [getAllPossibleConversions()](#getAllPossibleConversions--) | 지원되는 모든 변환을 가져옵니다 **자세히 보기**지원되는 변환에 대해 자세히 알아보려면: [지원되는 변환 전체 목록][]코드에서 사용 가능한 변환에 대해 자세히 알아보려면: [코드에서 지원되는 변환 가져오기][] |


[Full list of supported conversions]: https://docs.groupdocs.com/display/conversionnet/Supported+Document+Formats
[How to get supported conversions in code]: https://docs.groupdocs.com/display/conversionnet/Get+possible+conversions |
|  | [getPossibleConversions(String extension)](#getPossibleConversions-java.lang.String-) | 제공된 문서 확장자에 대한 지원되는 변환을 가져옵니다 Converter.GetPossibleConversions(".docx") Converter.GetPossibleConversions("docx")**자세히 보기**지원되는 변환에 대해 자세히 알아보려면: [지원되는 변환 전체 목록][]코드에서 사용 가능한 변환에 대해 자세히 알아보려면: [코드에서 지원되는 변환 가져오기][] |


[Full list of supported conversions]: https://docs.groupdocs.com/display/conversionnet/Supported+Document+Formats
[How to get supported conversions in code]: https://docs.groupdocs.com/display/conversionnet/Get+possible+conversions |
| [dispose()](#dispose--) | 리소스를 해제합니다. |
| [close()](#close--) |  |
### Converter() {#Converter--}
```
public Converter()
```


유창한 변환 설정을 위해  클래스의 새 인스턴스를 초기화합니다.  유창한 변환 사용 예시: `var converter = new Converter();` `converter .Load("") .ConvertTo("") .Convert();` `converter .WithSettings(() => new ConverterSettings()) .Load("").WithOptions(new PdfLoadOptions()) .ConvertTo("").WithOptions(new PdfConvertOptions()) .OnConversionCompleted(convertedDocumentStream => { }) .Convert();` `converter .Load("").WithOptions(new PdfLoadOptions()) .ConvertByPageTo((number => new FileStream("", FileMode.Create))).WithOptions(new PdfConvertOptions()) .OnConversionCompleted((number, stream) => {}) .Convert();` `converter.Load("").GetPossibleConversions(); converter.Load("").GetDocumentInfo(); converter.Load("").WithOptions(new PdfLoadOptions()).GetPossibleConversions(); converter.Load("").WithOptions(new PdfLoadOptions()).GetDocumentInfo();`

### Converter(Supplier<InputStream> document) {#Converter-java.util.function.Supplier-java.io.InputStream--}
```
public Converter(Supplier<InputStream> document)
```


[Converter](../../com.groupdocs.conversion/converter) 클래스의 새 인스턴스를 초기화합니다.

**Learn more**More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources][]More about document loading options dependent on file type: [Load options for different document types][]


[Loading document from different sources]: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
[Load options for different document types]: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 문서 | java.util.function.Supplier<java.io.InputStream> | 입력 스트림 공급자. |

### Converter(Supplier<InputStream> document, ConverterSettingsProvider settings) {#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.ConverterSettingsProvider-}
```
public Converter(Supplier<InputStream> document, ConverterSettingsProvider settings)
```


[Converter](../../com.groupdocs.conversion/converter) 클래스의 새 인스턴스를 초기화합니다.

**Learn more**More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources][]More about document loading options dependent on file type: [Load options for different document types][]


[Loading document from different sources]: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
[Load options for different document types]: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 문서 | java.util.function.Supplier<java.io.InputStream> | 입력 스트림 공급자입니다. |
| settings | [ConverterSettingsProvider](../../com.groupdocs.conversion.contracts/convertersettingsprovider) | Converter 설정 공급자. |

### Converter(Supplier<InputStream> document, LoadOptionsProvider loadOptions) {#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.LoadOptionsProvider-}
```
public Converter(Supplier<InputStream> document, LoadOptionsProvider loadOptions)
```


[Converter](../../com.groupdocs.conversion/converter) 클래스의 새 인스턴스를 초기화합니다.

**Learn more**More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources][]More about document loading options dependent on file type: [Load options for different document types][]


[Loading document from different sources]: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
[Load options for different document types]: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 문서 | java.util.function.Supplier<java.io.InputStream> | 입력 스트림 공급자입니다. |
| loadOptions | [LoadOptionsProvider](../../com.groupdocs.conversion.contracts/loadoptionsprovider) | 로드 옵션 공급자. |

### Converter(Supplier<InputStream> document, LoadOptionsProvider loadOptions, ConverterSettingsProvider settings) {#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.LoadOptionsProvider-com.groupdocs.conversion.contracts.ConverterSettingsProvider-}
```
public Converter(Supplier<InputStream> document, LoadOptionsProvider loadOptions, ConverterSettingsProvider settings)
```


[Converter](../../com.groupdocs.conversion/converter) 클래스의 새 인스턴스를 초기화합니다.

**Learn more**More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources][]More about document loading options dependent on file type: [Load options for different document types][]


[Loading document from different sources]: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
[Load options for different document types]: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 문서 | java.util.function.Supplier<java.io.InputStream> | 입력 스트림 공급자입니다. |
| loadOptions | [LoadOptionsProvider](../../com.groupdocs.conversion.contracts/loadoptionsprovider) | 문서 로드 옵션 공급자. |
| settings | [ConverterSettingsProvider](../../com.groupdocs.conversion.contracts/convertersettingsprovider) | Converter 설정 공급자. |

### Converter(Supplier<InputStream> document, LoadOptionsForFileTypeProvider loadOptions) {#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.LoadOptionsForFileTypeProvider-}
```
public Converter(Supplier<InputStream> document, LoadOptionsForFileTypeProvider loadOptions)
```


새 인스턴스를 초기화합니다. class.**Learn more**FTP, Amazon S3 Storage, Windows Azure 또는 기타 타사 스토리지에 저장된 문서를 로드하고 변환하는 방법에 대한 자세한 내용: [Loading document from different sources][]파일 유형에 따라 달라지는 문서 로드 옵션에 대한 자세한 내용: [Load options for different document types][]


[Loading document from different sources]: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
[Load options for different document types]: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 문서 | java.util.function.Supplier<java.io.InputStream> | 입력 스트림 공급자입니다. |
| loadOptions | [LoadOptionsForFileTypeProvider](../../com.groupdocs.conversion.contracts/loadoptionsforfiletypeprovider) | 문서 로드 옵션을 반환하는 함수. |

### Converter(Supplier<InputStream> document, LoadOptionsForFileTypeProvider loadOptions, ConverterSettingsProvider settings) {#Converter-java.util.function.Supplier-java.io.InputStream--com.groupdocs.conversion.contracts.LoadOptionsForFileTypeProvider-com.groupdocs.conversion.contracts.ConverterSettingsProvider-}
```
public Converter(Supplier<InputStream> document, LoadOptionsForFileTypeProvider loadOptions, ConverterSettingsProvider settings)
```


새 인스턴스를 초기화합니다. class.**Learn more**FTP, Amazon S3 Storage, Windows Azure 또는 기타 타사 스토리지에 저장된 문서를 로드하고 변환하는 방법에 대한 자세한 내용: [Loading document from different sources][]파일 유형에 따라 달라지는 문서 로드 옵션에 대한 자세한 내용: [Load options for different document types][]


[Loading document from different sources]: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
[Load options for different document types]: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 문서 | java.util.function.Supplier<java.io.InputStream> | 읽을 수 있는 스트림을 반환하는 공급자. |
| loadOptions | [LoadOptionsForFileTypeProvider](../../com.groupdocs.conversion.contracts/loadoptionsforfiletypeprovider) | 문서 로드 옵션을 반환하는 함수. |
| settings | [ConverterSettingsProvider](../../com.groupdocs.conversion.contracts/convertersettingsprovider) | Converter 설정 공급자. |

### Converter(String filePath) {#Converter-java.lang.String-}
```
public Converter(String filePath)
```


[Converter](../../com.groupdocs.conversion/converter) 클래스의 새 인스턴스를 초기화합니다.

**Learn more**More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources][]More about document loading options dependent on file type: [Load options for different document types][]


[Loading document from different sources]: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
[Load options for different document types]: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| filePath | java.lang.String | 소스 문서의 파일 경로. |

### Converter(String filePath, ConverterSettingsProvider settings) {#Converter-java.lang.String-com.groupdocs.conversion.contracts.ConverterSettingsProvider-}
```
public Converter(String filePath, ConverterSettingsProvider settings)
```


[Converter](../../com.groupdocs.conversion/converter) 클래스의 새 인스턴스를 초기화합니다.

**Learn more**More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources][]More about document loading options dependent on file type: [Load options for different document types][]


[Loading document from different sources]: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
[Load options for different document types]: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| filePath | java.lang.String | 소스 문서의 파일 경로. |
| settings | [ConverterSettingsProvider](../../com.groupdocs.conversion.contracts/convertersettingsprovider) | Converter 설정 공급자. |

### Converter(String filePath, LoadOptionsProvider loadOptions) {#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsProvider-}
```
public Converter(String filePath, LoadOptionsProvider loadOptions)
```


[Converter](../../com.groupdocs.conversion/converter) 클래스의 새 인스턴스를 초기화합니다.

**Learn more**More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources][]More about document loading options dependent on file type: [Load options for different document types][]


[Loading document from different sources]: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
[Load options for different document types]: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| filePath | java.lang.String | 소스 문서의 파일 경로. |
| loadOptions | [LoadOptionsProvider](../../com.groupdocs.conversion.contracts/loadoptionsprovider) | 로드 옵션 공급자. |

### Converter(String filePath, LoadOptionsProvider loadOptions, ConverterSettingsProvider settings) {#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsProvider-com.groupdocs.conversion.contracts.ConverterSettingsProvider-}
```
public Converter(String filePath, LoadOptionsProvider loadOptions, ConverterSettingsProvider settings)
```


[Converter](../../com.groupdocs.conversion/converter) 클래스의 새 인스턴스를 초기화합니다.

**Learn more**More about how to load and convert documents stored at FTP, Amazon S3 Storage, Windows Azure or any other third-party storage: [Loading document from different sources][]More about document loading options dependent on file type: [Load options for different document types][]


[Loading document from different sources]: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
[Load options for different document types]: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| filePath | java.lang.String | 소스 문서의 파일 경로. |
| loadOptions | [LoadOptionsProvider](../../com.groupdocs.conversion.contracts/loadoptionsprovider) | 문서 로드 옵션 공급자. |
| settings | [ConverterSettingsProvider](../../com.groupdocs.conversion.contracts/convertersettingsprovider) | Converter 설정 공급자. |

### Converter(String filePath, LoadOptionsForFileTypeProvider loadOptions) {#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsForFileTypeProvider-}
```
public Converter(String filePath, LoadOptionsForFileTypeProvider loadOptions)
```


새 인스턴스를 초기화합니다. class.**Learn more**FTP, Amazon S3 Storage, Windows Azure 또는 기타 타사 스토리지에 저장된 문서를 로드하고 변환하는 방법에 대한 자세한 내용: [Loading document from different sources][]파일 유형에 따라 달라지는 문서 로드 옵션에 대한 자세한 내용: [Load options for different document types][]


[Loading document from different sources]: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
[Load options for different document types]: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| filePath | java.lang.String | 소스 문서의 파일 경로. |
| loadOptions | [LoadOptionsForFileTypeProvider](../../com.groupdocs.conversion.contracts/loadoptionsforfiletypeprovider) | 문서 로드 옵션 함수. |

### Converter(String filePath, LoadOptionsForFileTypeProvider loadOptions, ConverterSettingsProvider settings) {#Converter-java.lang.String-com.groupdocs.conversion.contracts.LoadOptionsForFileTypeProvider-com.groupdocs.conversion.contracts.ConverterSettingsProvider-}
```
public Converter(String filePath, LoadOptionsForFileTypeProvider loadOptions, ConverterSettingsProvider settings)
```


새 인스턴스를 초기화합니다. class.**Learn more**FTP, Amazon S3 Storage, Windows Azure 또는 기타 타사 스토리지에 저장된 문서를 로드하고 변환하는 방법에 대한 자세한 내용: [Loading document from different sources][]파일 유형에 따라 달라지는 문서 로드 옵션에 대한 자세한 내용: [Load options for different document types][]


[Loading document from different sources]: https://docs.groupdocs.com/display/conversionnet/Loading+documents+from+different+sources
[Load options for different document types]: https://docs.groupdocs.com/display/conversionnet/Load+options+for+different+document+types

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| filePath | java.lang.String | 소스 문서의 파일 경로. |
| loadOptions | [LoadOptionsForFileTypeProvider](../../com.groupdocs.conversion.contracts/loadoptionsforfiletypeprovider) | 문서 로드 옵션 함수. |
| settings | [ConverterSettingsProvider](../../com.groupdocs.conversion.contracts/convertersettingsprovider) | Converter 설정 공급자. |

### tweakPackageUtil(String vendor, String version, String specTitle) {#tweakPackageUtil-java.lang.String-java.lang.String-java.lang.String-}
```
public static void tweakPackageUtil(String vendor, String version, String specTitle)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| vendor | java.lang.String |  |
| version | java.lang.String |  |
| specTitle | java.lang.String |  |

### convert(SaveDocumentStream document, ConvertOptions convertOptions) {#convert-com.groupdocs.conversion.contracts.SaveDocumentStream-com.groupdocs.conversion.options.convert.ConvertOptions-}
```
public final void convert(SaveDocumentStream document, ConvertOptions convertOptions)
```


소스 문서를 변환합니다. 전체 변환된 문서를 저장합니다.

**Learn more**More about document conversion basic scenarios: [How to convert document in 3 steps][]Conversion use cases, advanced settings and customizations: [Convert document with advanced settings][]


[How to convert document in 3 steps]: https://docs.groupdocs.com/display/conversionnet/Convert+document
[Convert document with advanced settings]: https://docs.groupdocs.com/display/conversionnet/Converting

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| document | [SaveDocumentStream](../../com.groupdocs.conversion.contracts/savedocumentstream) | 출력 스트림 공급자. |
| convertOptions | com.groupdocs.conversion.options.convert.ConvertOptions | 원하는 대상 파일 형식에 대한 변환 옵션. |

### convert(SaveDocumentStream document, ConvertedDocumentStream documentCompleted, ConvertOptions convertOptions) {#convert-com.groupdocs.conversion.contracts.SaveDocumentStream-com.groupdocs.conversion.contracts.ConvertedDocumentStream-com.groupdocs.conversion.options.convert.ConvertOptions-}
```
public void convert(SaveDocumentStream document, ConvertedDocumentStream documentCompleted, ConvertOptions convertOptions)
```


소스 문서를 변환합니다. 전체 변환된 문서를 저장합니다. **Learn more**문서 변환 기본 시나리오에 대한 자세한 내용: [How to convert document in 3 steps][]변환 사용 사례, 고급 설정 및 사용자 지정에 대한 자세한 내용: [Convert document with advanced settings][]


[How to convert document in 3 steps]: https://docs.groupdocs.com/display/conversionnet/Convert+document
[Convert document with advanced settings]: https://docs.groupdocs.com/display/conversionnet/Converting

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| document | [SaveDocumentStream](../../com.groupdocs.conversion.contracts/savedocumentstream) | 출력 스트림 공급자 |
| documentCompleted | [ConvertedDocumentStream](../../com.groupdocs.conversion.contracts/converteddocumentstream) | 변환된 문서 스트림을 수신하는 대리자. |
| convertOptions | com.groupdocs.conversion.options.convert.ConvertOptions | 원하는 대상 파일 형식에 대한 변환 옵션. |

### convert(SaveDocumentStream document, ConvertOptionsProvider convertOptionsProvider) {#convert-com.groupdocs.conversion.contracts.SaveDocumentStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-}
```
public void convert(SaveDocumentStream document, ConvertOptionsProvider convertOptionsProvider)
```


소스 문서를 변환합니다. 전체 변환된 문서를 저장합니다.**Learn more**문서 변환 기본 시나리오에 대한 자세한 내용: [How to convert document in 3 steps][]변환 사용 사례, 고급 설정 및 사용자 지정에 대한 자세한 내용: [Convert document with advanced settings][]


[How to convert document in 3 steps]: https://docs.groupdocs.com/display/conversionnet/Convert+document
[Convert document with advanced settings]: https://docs.groupdocs.com/display/conversionnet/Converting

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| document | [SaveDocumentStream](../../com.groupdocs.conversion.contracts/savedocumentstream) | 출력 스트림 공급자. |
| convertOptionsProvider | [ConvertOptionsProvider](../../com.groupdocs.conversion.contracts/convertoptionsprovider) | 변환 옵션 제공자. 각 변환마다 호출되어 원하는 대상 문서 유형에 대한 특정 변환 옵션을 제공합니다. |

### convert(SaveDocumentStream document, ConvertedDocumentStream documentCompleted, ConvertOptionsProvider convertOptionsProvider) {#convert-com.groupdocs.conversion.contracts.SaveDocumentStream-com.groupdocs.conversion.contracts.ConvertedDocumentStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-}
```
public void convert(SaveDocumentStream document, ConvertedDocumentStream documentCompleted, ConvertOptionsProvider convertOptionsProvider)
```


소스 문서를 변환합니다. 전체 변환된 문서를 저장합니다.**Learn more**문서 변환 기본 시나리오에 대한 자세한 내용: [How to convert document in 3 steps][]변환 사용 사례, 고급 설정 및 사용자 지정에 대한 자세한 내용: [Convert document with advanced settings][]


[How to convert document in 3 steps]: https://docs.groupdocs.com/display/conversionnet/Convert+document
[Convert document with advanced settings]: https://docs.groupdocs.com/display/conversionnet/Converting

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| document | [SaveDocumentStream](../../com.groupdocs.conversion.contracts/savedocumentstream) | 출력 스트림 공급자. |
| documentCompleted | [ConvertedDocumentStream](../../com.groupdocs.conversion.contracts/converteddocumentstream) | 변환된 문서 스트림을 수신하는 대리자. |
| convertOptionsProvider | [ConvertOptionsProvider](../../com.groupdocs.conversion.contracts/convertoptionsprovider) | 변환 옵션 제공자. 각 변환마다 호출되어 원하는 대상 문서 유형에 대한 특정 변환 옵션을 제공합니다. |

### convert(SaveDocumentStreamForFileType document, ConvertOptions convertOptions) {#convert-com.groupdocs.conversion.contracts.SaveDocumentStreamForFileType-com.groupdocs.conversion.options.convert.ConvertOptions-}
```
public void convert(SaveDocumentStreamForFileType document, ConvertOptions convertOptions)
```


소스 문서를 변환합니다. 전체 변환된 문서를 저장합니다.**Learn more**문서 변환 기본 시나리오에 대한 자세한 내용: [How to convert document in 3 steps][]변환 사용 사례, 고급 설정 및 사용자 지정에 대한 자세한 내용: [Convert document with advanced settings][]


[How to convert document in 3 steps]: https://docs.groupdocs.com/display/conversionnet/Convert+document
[Convert document with advanced settings]: https://docs.groupdocs.com/display/conversionnet/Converting

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| document | [SaveDocumentStreamForFileType](../../com.groupdocs.conversion.contracts/savedocumentstreamforfiletype) | 출력 스트림 함수. |
| convertOptions | com.groupdocs.conversion.options.convert.ConvertOptions | 원하는 대상 파일 형식에 대한 변환 옵션. |

### convert(SaveDocumentStreamForFileType document, ConvertedDocumentStream documentCompleted, ConvertOptions convertOptions) {#convert-com.groupdocs.conversion.contracts.SaveDocumentStreamForFileType-com.groupdocs.conversion.contracts.ConvertedDocumentStream-com.groupdocs.conversion.options.convert.ConvertOptions-}
```
public void convert(SaveDocumentStreamForFileType document, ConvertedDocumentStream documentCompleted, ConvertOptions convertOptions)
```


소스 문서를 변환합니다. 전체 변환된 문서를 저장합니다.**Learn more**문서 변환 기본 시나리오에 대한 자세한 내용: [How to convert document in 3 steps][]변환 사용 사례, 고급 설정 및 사용자 지정에 대한 자세한 내용: [Convert document with advanced settings][]


[How to convert document in 3 steps]: https://docs.groupdocs.com/display/conversionnet/Convert+document
[Convert document with advanced settings]: https://docs.groupdocs.com/display/conversionnet/Converting

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| document | [SaveDocumentStreamForFileType](../../com.groupdocs.conversion.contracts/savedocumentstreamforfiletype) | 출력 스트림 함수 |
| documentCompleted | [ConvertedDocumentStream](../../com.groupdocs.conversion.contracts/converteddocumentstream) | 변환된 문서 스트림을 받는 대리자 |
| convertOptions | com.groupdocs.conversion.options.convert.ConvertOptions | 원하는 대상 파일 유형에 대한 변환 옵션 |

### convert(SaveDocumentStreamForFileType document, ConvertOptionsProvider convertOptionsProvider) {#convert-com.groupdocs.conversion.contracts.SaveDocumentStreamForFileType-com.groupdocs.conversion.contracts.ConvertOptionsProvider-}
```
public void convert(SaveDocumentStreamForFileType document, ConvertOptionsProvider convertOptionsProvider)
```


소스 문서를 변환합니다. 전체 변환된 문서를 저장합니다.**Learn more**문서 변환 기본 시나리오에 대한 자세한 내용: [How to convert document in 3 steps][]변환 사용 사례, 고급 설정 및 사용자 지정에 대한 자세한 내용: [Convert document with advanced settings][]


[How to convert document in 3 steps]: https://docs.groupdocs.com/display/conversionnet/Convert+document
[Convert document with advanced settings]: https://docs.groupdocs.com/display/conversionnet/Converting

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| document | [SaveDocumentStreamForFileType](../../com.groupdocs.conversion.contracts/savedocumentstreamforfiletype) | 출력 스트림 함수. |
| convertOptionsProvider | [ConvertOptionsProvider](../../com.groupdocs.conversion.contracts/convertoptionsprovider) | 변환 옵션 제공자. 각 변환마다 호출되어 원하는 대상 문서 유형에 대한 특정 변환 옵션을 제공합니다. |

### convert(SaveDocumentStreamForFileType document, ConvertedDocumentStream documentCompleted, ConvertOptionsProvider convertOptionsProvider) {#convert-com.groupdocs.conversion.contracts.SaveDocumentStreamForFileType-com.groupdocs.conversion.contracts.ConvertedDocumentStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-}
```
public void convert(SaveDocumentStreamForFileType document, ConvertedDocumentStream documentCompleted, ConvertOptionsProvider convertOptionsProvider)
```


소스 문서를 변환합니다. 전체 변환된 문서를 저장합니다.**Learn more**문서 변환 기본 시나리오에 대한 자세한 내용: [How to convert document in 3 steps][]변환 사용 사례, 고급 설정 및 사용자 지정에 대한 자세한 내용: [Convert document with advanced settings][]


[How to convert document in 3 steps]: https://docs.groupdocs.com/display/conversionnet/Convert+document
[Convert document with advanced settings]: https://docs.groupdocs.com/display/conversionnet/Converting

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| document | [SaveDocumentStreamForFileType](../../com.groupdocs.conversion.contracts/savedocumentstreamforfiletype) | 출력 스트림 함수. |
| documentCompleted | [ConvertedDocumentStream](../../com.groupdocs.conversion.contracts/converteddocumentstream) | 변환된 문서 스트림을 수신하는 대리자. |
| convertOptionsProvider | [ConvertOptionsProvider](../../com.groupdocs.conversion.contracts/convertoptionsprovider) | 변환 옵션 제공자. 각 변환마다 호출되어 원하는 대상 문서 유형에 대한 특정 변환 옵션을 제공합니다. |

### convert(String filePath, ConvertOptions convertOptions) {#convert-java.lang.String-com.groupdocs.conversion.options.convert.ConvertOptions-}
```
public final void convert(String filePath, ConvertOptions convertOptions)
```


소스 문서를 변환합니다. 전체 변환된 문서를 저장합니다.

**Learn more**More about document conversion basic scenarios: [How to convert document in 3 steps][]Conversion use cases, advanced settings and customizations: [Convert document with advanced settings][]


[How to convert document in 3 steps]: https://docs.groupdocs.com/display/conversionnet/Convert+document
[Convert document with advanced settings]: https://docs.groupdocs.com/display/conversionnet/Converting

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| filePath | java.lang.String | 소스 문서의 파일 경로. |
| convertOptions | com.groupdocs.conversion.options.convert.ConvertOptions | 원하는 대상 파일 형식에 대한 변환 옵션. |

### convert(SavePageStream document, ConvertOptions convertOptions) {#convert-com.groupdocs.conversion.contracts.SavePageStream-com.groupdocs.conversion.options.convert.ConvertOptions-}
```
public final void convert(SavePageStream document, ConvertOptions convertOptions)
```


원본 문서를 변환합니다. 변환된 문서를 페이지별로 저장합니다.

**Learn more**More about document conversion basic scenarios: [How to convert document in 3 steps][]Conversion use cases, advanced settings and customizations: [Convert document with advanced settings][]


[How to convert document in 3 steps]: https://docs.groupdocs.com/display/conversionnet/Convert+document
[Convert document with advanced settings]: https://docs.groupdocs.com/display/conversionnet/Converting

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| document | [SavePageStream](../../com.groupdocs.conversion.contracts/savepagestream) | 페이지 출력 스트림 함수. |
| convertOptions | com.groupdocs.conversion.options.convert.ConvertOptions | 원하는 대상 파일 형식에 대한 변환 옵션. |

### convert(SavePageStream document, ConvertedPageStream documentCompleted, ConvertOptions convertOptions) {#convert-com.groupdocs.conversion.contracts.SavePageStream-com.groupdocs.conversion.contracts.ConvertedPageStream-com.groupdocs.conversion.options.convert.ConvertOptions-}
```
public void convert(SavePageStream document, ConvertedPageStream documentCompleted, ConvertOptions convertOptions)
```


원본 문서를 변환합니다. 변환된 문서를 페이지별로 저장합니다. **자세히 보기**문서 변환 기본 시나리오에 대해: [문서를 3단계로 변환하는 방법][]고급 설정 및 사용자 정의가 포함된 변환 사용 사례: [고급 설정으로 문서 변환][]


[How to convert document in 3 steps]: https://docs.groupdocs.com/display/conversionnet/Convert+document
[Convert document with advanced settings]: https://docs.groupdocs.com/display/conversionnet/Converting

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| document | [SavePageStream](../../com.groupdocs.conversion.contracts/savepagestream) | 출력 스트림 함수. |
| documentCompleted | [ConvertedPageStream](../../com.groupdocs.conversion.contracts/convertedpagestream) | 변환된 문서 페이지 스트림을 받는 대리자. |
| convertOptions | com.groupdocs.conversion.options.convert.ConvertOptions | 원하는 대상 파일 형식에 대한 변환 옵션. |

### convert(SavePageStream document, ConvertOptionsProvider convertOptionsProvider) {#convert-com.groupdocs.conversion.contracts.SavePageStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-}
```
public void convert(SavePageStream document, ConvertOptionsProvider convertOptionsProvider)
```


원본 문서를 변환합니다. 변환된 문서를 페이지별로 저장합니다.**자세히 보기**문서 변환 기본 시나리오에 대해: [문서를 3단계로 변환하는 방법][]고급 설정 및 사용자 정의가 포함된 변환 사용 사례: [고급 설정으로 문서 변환][]


[How to convert document in 3 steps]: https://docs.groupdocs.com/display/conversionnet/Convert+document
[Convert document with advanced settings]: https://docs.groupdocs.com/display/conversionnet/Converting

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| document | [SavePageStream](../../com.groupdocs.conversion.contracts/savepagestream) | 출력 스트림 함수. |
| convertOptionsProvider | [ConvertOptionsProvider](../../com.groupdocs.conversion.contracts/convertoptionsprovider) | 변환 옵션 제공자. 각 변환마다 호출되어 원하는 대상 문서 유형에 대한 특정 변환 옵션을 제공합니다. |

### convert(SavePageStream document, ConvertedPageStream documentCompleted, ConvertOptionsProvider convertOptionsProvider) {#convert-com.groupdocs.conversion.contracts.SavePageStream-com.groupdocs.conversion.contracts.ConvertedPageStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-}
```
public void convert(SavePageStream document, ConvertedPageStream documentCompleted, ConvertOptionsProvider convertOptionsProvider)
```


원본 문서를 변환합니다. 변환된 문서를 페이지별로 저장합니다.**자세히 보기**문서 변환 기본 시나리오에 대해: [문서를 3단계로 변환하는 방법][]고급 설정 및 사용자 정의가 포함된 변환 사용 사례: [고급 설정으로 문서 변환][]


[How to convert document in 3 steps]: https://docs.groupdocs.com/display/conversionnet/Convert+document
[Convert document with advanced settings]: https://docs.groupdocs.com/display/conversionnet/Converting

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| document | [SavePageStream](../../com.groupdocs.conversion.contracts/savepagestream) | 출력 스트림 함수. |
| documentCompleted | [ConvertedPageStream](../../com.groupdocs.conversion.contracts/convertedpagestream) | 변환된 문서 페이지 스트림을 받는 대리자. |
| convertOptionsProvider | [ConvertOptionsProvider](../../com.groupdocs.conversion.contracts/convertoptionsprovider) | 변환 옵션 제공자. 각 변환마다 호출되어 원하는 대상 문서 유형에 대한 특정 변환 옵션을 제공합니다. |

### convert(SavePageStreamForFileType document, ConvertOptions convertOptions) {#convert-com.groupdocs.conversion.contracts.SavePageStreamForFileType-com.groupdocs.conversion.options.convert.ConvertOptions-}
```
public void convert(SavePageStreamForFileType document, ConvertOptions convertOptions)
```


원본 문서를 변환합니다. 변환된 문서를 페이지별로 저장합니다.**자세히 보기**문서 변환 기본 시나리오에 대해: [문서를 3단계로 변환하는 방법][]고급 설정 및 사용자 정의가 포함된 변환 사용 사례: [고급 설정으로 문서 변환][]


[How to convert document in 3 steps]: https://docs.groupdocs.com/display/conversionnet/Convert+document
[Convert document with advanced settings]: https://docs.groupdocs.com/display/conversionnet/Converting

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| document | [SavePageStreamForFileType](../../com.groupdocs.conversion.contracts/savepagestreamforfiletype) | 출력 스트림 함수. |
| convertOptions | com.groupdocs.conversion.options.convert.ConvertOptions | 원하는 대상 파일 형식에 대한 변환 옵션. |

### convert(SavePageStreamForFileType document, ConvertedPageStream documentCompleted, ConvertOptions convertOptions) {#convert-com.groupdocs.conversion.contracts.SavePageStreamForFileType-com.groupdocs.conversion.contracts.ConvertedPageStream-com.groupdocs.conversion.options.convert.ConvertOptions-}
```
public void convert(SavePageStreamForFileType document, ConvertedPageStream documentCompleted, ConvertOptions convertOptions)
```


원본 문서를 변환합니다. 변환된 문서를 페이지별로 저장합니다.**자세히 보기**문서 변환 기본 시나리오에 대해: [문서를 3단계로 변환하는 방법][]고급 설정 및 사용자 정의가 포함된 변환 사용 사례: [고급 설정으로 문서 변환][]


[How to convert document in 3 steps]: https://docs.groupdocs.com/display/conversionnet/Convert+document
[Convert document with advanced settings]: https://docs.groupdocs.com/display/conversionnet/Converting

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| document | [SavePageStreamForFileType](../../com.groupdocs.conversion.contracts/savepagestreamforfiletype) | 출력 스트림 함수. |
| documentCompleted | [ConvertedPageStream](../../com.groupdocs.conversion.contracts/convertedpagestream) | 변환된 문서 페이지 스트림을 받는 대리자. |
| convertOptions | com.groupdocs.conversion.options.convert.ConvertOptions | 원하는 대상 파일 형식에 대한 변환 옵션. |

### convert(SavePageStreamForFileType document, ConvertOptionsProvider convertOptionsProvider) {#convert-com.groupdocs.conversion.contracts.SavePageStreamForFileType-com.groupdocs.conversion.contracts.ConvertOptionsProvider-}
```
public void convert(SavePageStreamForFileType document, ConvertOptionsProvider convertOptionsProvider)
```


원본 문서를 변환합니다. 변환된 문서를 페이지별로 저장합니다.**자세히 보기**문서 변환 기본 시나리오에 대해: [문서를 3단계로 변환하는 방법][]고급 설정 및 사용자 정의가 포함된 변환 사용 사례: [고급 설정으로 문서 변환][]


[How to convert document in 3 steps]: https://docs.groupdocs.com/display/conversionnet/Convert+document
[Convert document with advanced settings]: https://docs.groupdocs.com/display/conversionnet/Converting

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| document | [SavePageStreamForFileType](../../com.groupdocs.conversion.contracts/savepagestreamforfiletype) | 출력 스트림 함수. |
| convertOptionsProvider | [ConvertOptionsProvider](../../com.groupdocs.conversion.contracts/convertoptionsprovider) | 변환 옵션 제공자. 각 변환마다 호출되어 원하는 대상 문서 유형에 대한 특정 변환 옵션을 제공합니다. |

### convert(SavePageStreamForFileType document, ConvertedPageStream documentCompleted, ConvertOptionsProvider convertOptionsProvider) {#convert-com.groupdocs.conversion.contracts.SavePageStreamForFileType-com.groupdocs.conversion.contracts.ConvertedPageStream-com.groupdocs.conversion.contracts.ConvertOptionsProvider-}
```
public void convert(SavePageStreamForFileType document, ConvertedPageStream documentCompleted, ConvertOptionsProvider convertOptionsProvider)
```


원본 문서를 변환합니다. 변환된 문서를 페이지별로 저장합니다.**자세히 보기**문서 변환 기본 시나리오에 대해: [문서를 3단계로 변환하는 방법][]고급 설정 및 사용자 정의가 포함된 변환 사용 사례: [고급 설정으로 문서 변환][]


[How to convert document in 3 steps]: https://docs.groupdocs.com/display/conversionnet/Convert+document
[Convert document with advanced settings]: https://docs.groupdocs.com/display/conversionnet/Converting

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| document | [SavePageStreamForFileType](../../com.groupdocs.conversion.contracts/savepagestreamforfiletype) | 출력 스트림 함수. |
| documentCompleted | [ConvertedPageStream](../../com.groupdocs.conversion.contracts/convertedpagestream) | 변환된 문서 페이지 스트림을 받는 대리자. |
| convertOptionsProvider | [ConvertOptionsProvider](../../com.groupdocs.conversion.contracts/convertoptionsprovider) | 변환 옵션 제공자. 각 변환마다 호출되어 원하는 대상 문서 유형에 대한 특정 변환 옵션을 제공합니다. |

### withSettings(ConverterSettingsProvider settingsProvider) {#withSettings-com.groupdocs.conversion.contracts.ConverterSettingsProvider-}
```
public IConversionFrom withSettings(ConverterSettingsProvider settingsProvider)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| settingsProvider | [ConverterSettingsProvider](../../com.groupdocs.conversion.contracts/convertersettingsprovider) |  |

**Returns:**
[IConversionFrom](../../com.groupdocs.conversion.fluent/iconversionfrom)
### load(String fileName) {#load-java.lang.String-}
```
public IConversionLoadOptionsOrSourceDocumentLoaded load(String fileName)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fileName | java.lang.String |  |

**Returns:**
[IConversionLoadOptionsOrSourceDocumentLoaded](../../com.groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded)
### load(String[] fileNames) {#load-java.lang.String---}
```
public IConversionLoadOptionsOrSourceDocumentLoaded load(String[] fileNames)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fileNames | java.lang.String[] |  |

**Returns:**
[IConversionLoadOptionsOrSourceDocumentLoaded](../../com.groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded)
### load(DocumentStreamProvider documentStreamProvider) {#load-com.groupdocs.conversion.contracts.DocumentStreamProvider-}
```
public IConversionLoadOptionsOrSourceDocumentLoaded load(DocumentStreamProvider documentStreamProvider)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| documentStreamProvider | [DocumentStreamProvider](../../com.groupdocs.conversion.contracts/documentstreamprovider) |  |

**Returns:**
[IConversionLoadOptionsOrSourceDocumentLoaded](../../com.groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded)
### load(DocumentStreamsProvider documentStreamProvider) {#load-com.groupdocs.conversion.contracts.DocumentStreamsProvider-}
```
public IConversionLoadOptionsOrSourceDocumentLoaded load(DocumentStreamsProvider documentStreamProvider)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| documentStreamProvider | [DocumentStreamsProvider](../../com.groupdocs.conversion.contracts/documentstreamsprovider) |  |

**Returns:**
[IConversionLoadOptionsOrSourceDocumentLoaded](../../com.groupdocs.conversion.fluent/iconversionloadoptionsorsourcedocumentloaded)
### getDocumentInfo() {#getDocumentInfo--}
```
public final IDocumentInfo getDocumentInfo()
```


소스 문서 정보를 가져옵니다 - 페이지 수 및 파일 유형에 특정한 기타 문서 속성.

**Learn more**Learn more about converted document - file type, pages count, creation date and many other format specific properties: [How to get document info][]


[How to get document info]: https://docs.groupdocs.com/display/conversionnet/Get+document+info

**Returns:**
[IDocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/idocumentinfo) - document info
### isDocumentPasswordProtected() {#isDocumentPasswordProtected--}
```
public boolean isDocumentPasswordProtected()
```


소스 문서가 비밀번호로 보호되어 있는지 확인합니다.

**Returns:**
boolean - 문서가 비밀번호로 보호된 경우 true **자세히 보기**변환된 문서에 대한 자세한 정보 - 파일 유형, 페이지 수, 생성 날짜 및 기타 많은 형식별 속성: [문서가 비밀번호로 보호되는지 확인하는 방법][]


[How to check is the document password protected]: https://docs.groupdocs.com/display/conversionnet/Is+document+password+protected
### getPossibleConversions() {#getPossibleConversions--}
```
public final PossibleConversions getPossibleConversions()
```


소스 문서에 대한 가능한 변환을 가져옵니다.

**Learn more**Learn more about supported conversions: [Full list of supported conversions][]Learn more about available conversions: [How to get supported conversions in code][]


[Full list of supported conversions]: https://docs.groupdocs.com/display/conversionnet/Supported+Document+Formats
[How to get supported conversions in code]: https://docs.groupdocs.com/display/conversionnet/Get+possible+conversions

**Returns:**
[PossibleConversions](../../com.groupdocs.conversion.contracts/possibleconversions) - possible conversions
### getAllPossibleConversions() {#getAllPossibleConversions--}
```
public static List<PossibleConversions> getAllPossibleConversions()
```


지원되는 모든 변환을 가져옵니다 **자세히 보기**지원되는 변환에 대해 자세히 알아보려면: [지원되는 변환 전체 목록][]코드에서 사용 가능한 변환에 대해 자세히 알아보려면: [코드에서 지원되는 변환 가져오기][]


[Full list of supported conversions]: https://docs.groupdocs.com/display/conversionnet/Supported+Document+Formats
[How to get supported conversions in code]: https://docs.groupdocs.com/display/conversionnet/Get+possible+conversions

**Returns:**
java.util.List<com.groupdocs.conversion.contracts.PossibleConversions> - 지원되는 변환
### getPossibleConversions(String extension) {#getPossibleConversions-java.lang.String-}
```
public static PossibleConversions getPossibleConversions(String extension)
```


제공된 문서 확장자에 대한 지원되는 변환을 가져옵니다 Converter.GetPossibleConversions(".docx") Converter.GetPossibleConversions("docx")**자세히 보기**지원되는 변환에 대해 자세히 알아보려면: [지원되는 변환 전체 목록][]코드에서 사용 가능한 변환에 대해 자세히 알아보려면: [코드에서 지원되는 변환 가져오기][]


[Full list of supported conversions]: https://docs.groupdocs.com/display/conversionnet/Supported+Document+Formats
[How to get supported conversions in code]: https://docs.groupdocs.com/display/conversionnet/Get+possible+conversions

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 확장자 | java.lang.String | 문서 확장자 |

**Returns:**
[PossibleConversions](../../com.groupdocs.conversion.contracts/possibleconversions) - possible conversions
### dispose() {#dispose--}
```
public final void dispose()
```


리소스를 해제합니다.

### close() {#close--}
```
public void close()
```




