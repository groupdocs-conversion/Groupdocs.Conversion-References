---
title: "ImageConvertOptions"
second_title: "GroupDocs.Conversion for .NET API 참조"
description: "이미지 파일 유형으로 변환하기 위한 옵션."
type: docs
weight: 1950
url: /ko/net/groupdocs.conversion.options.convert/imageconvertoptions/
---
## ImageConvertOptions class

이미지 파일 유형으로 변환하기 위한 옵션.

```csharp
public sealed class ImageConvertOptions : CommonConvertOptions<ImageFileType>, IUsePdfConvertOptions
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [ImageConvertOptions](imageconvertoptions)() | [`ImageConvertOptions`](../imageconvertoptions) 클래스의 새 인스턴스를 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [BackgroundColor](../../groupdocs.conversion.options.convert/imageconvertoptions/backgroundcolor) { get; set; } | 소스 형식에서 지원되는 경우 배경 색상을 설정합니다. |
| [Brightness](../../groupdocs.conversion.options.convert/imageconvertoptions/brightness) { get; set; } | 이미지 밝기를 조정합니다. |
| [CapResolutionToPageContent](../../groupdocs.conversion.options.convert/imageconvertoptions/capresolutiontopagecontent) { get; set; } | 설정하면, 페이지별 PDF 렌더링 해상도를 해당 페이지의 기본 래스터 해상도로 제한하여 페이지가 포함된 이미지보다 높은 DPI로 렌더링되지 않으며, 최종 출력에서 해당 페이지를 요청된 DPI로 다시 확대하는 대신 기본(작은) 픽셀 크기와 기본 DPI로 출력합니다. 이미지 중심(스캔) 페이지에만 적용되며, 텍스트나 벡터 내용이 있는 페이지는 절대 낮아지지 않고 요청된 DPI로 출력됩니다. 명시적인 출력 [`Width`](./width) 또는 [`Height`](./height)가 설정된 경우 이 옵션은 무시됩니다. 기본값은 `false`(제한 없음; 모든 페이지가 요청된 DPI로 렌더링 및 출력됩니다). |
| [Contrast](../../groupdocs.conversion.options.convert/imageconvertoptions/contrast) { get; set; } | 이미지 대비를 조정합니다. |
| [CropArea](../../groupdocs.conversion.options.convert/imageconvertoptions/croparea) { get; set; } | 변환 후 래스터 이미지 영역을 잘라냅니다. |
| [FlipMode](../../groupdocs.conversion.options.convert/imageconvertoptions/flipmode) { get; set; } | 이미지 플립 모드. |
| [Format](../../groupdocs.conversion.options.convert/convertoptions-1/format) { get; set; } | 입력 문서를 변환할 원하는 파일 형식입니다. |
| virtual [Format](../../groupdocs.conversion.options.convert/convertoptions/format) { get; set; } | 구현합니다 [`Format`](../iconvertoptions/format) |
| [Gamma](../../groupdocs.conversion.options.convert/imageconvertoptions/gamma) { get; set; } | 이미지 감마를 조정합니다. |
| [Grayscale](../../groupdocs.conversion.options.convert/imageconvertoptions/grayscale) { get; set; } | 그레이스케일 이미지로 변환할지 여부를 나타냅니다. |
| [Height](../../groupdocs.conversion.options.convert/imageconvertoptions/height) { get; set; } | 변환 후 원하는 이미지 높이. |
| [HorizontalResolution](../../groupdocs.conversion.options.convert/imageconvertoptions/horizontalresolution) { get; set; } | 변환 후 원하는 이미지 가로 해상도. 기본 해상도는 입력 파일의 해상도 또는 96 dpi입니다. |
| [JpegOptions](../../groupdocs.conversion.options.convert/imageconvertoptions/jpegoptions) { get; set; } | Jpeg 전용 변환 옵션. |
| [MinResolution](../../groupdocs.conversion.options.convert/imageconvertoptions/minresolution) { get; set; } | [`CapResolutionToPageContent`](./capresolutiontopagecontent)가 활성화된 경우 제한된 렌더 DPI에 적용되는 축별 하한값입니다. 제한된 DPI는 이 값 이하로 낮아지지 않습니다. 기본값은 `0`(하한 없음)입니다. |
| [PageNumber](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagenumber) { get; set; } | 구현합니다 [`PageNumber`](../ipagedconvertoptions/pagenumber) |
| [Pages](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pages) { get; set; } | 구현합니다 [`Pages`](../ipagerangedconvertoptions/pages) |
| [PagesCount](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagescount) { get; set; } | 구현합니다 [`PagesCount`](../ipagedconvertoptions/pagescount) |
| [PsdOptions](../../groupdocs.conversion.options.convert/imageconvertoptions/psdoptions) { get; set; } | Psd 전용 변환 옵션. |
| [RotateAngle](../../groupdocs.conversion.options.convert/imageconvertoptions/rotateangle) { get; set; } | 이미지 회전 각도. |
| [TiffOptions](../../groupdocs.conversion.options.convert/imageconvertoptions/tiffoptions) { get; set; } | Tiff 전용 변환 옵션. |
| [UsePdf](../../groupdocs.conversion.options.convert/imageconvertoptions/usepdf) { get; set; } | `true`이면 입력이 먼저 PDF로 변환되고 그 다음 원하는 형식으로 변환됩니다. |
| [VerticalResolution](../../groupdocs.conversion.options.convert/imageconvertoptions/verticalresolution) { get; set; } | 변환 후 원하는 이미지 세로 해상도. 기본 해상도는 입력 파일의 해상도 또는 96 dpi입니다. |
| [Watermark](../../groupdocs.conversion.options.convert/commonconvertoptions-1/watermark) { get; set; } | 구현합니다 [`Watermark`](../iwatermarkedconvertoptions/watermark) |
| [WebpOptions](../../groupdocs.conversion.options.convert/imageconvertoptions/webpoptions) { get; set; } | Webp 전용 변환 옵션. |
| [Width](../../groupdocs.conversion.options.convert/imageconvertoptions/width) { get; set; } | 변환 후 원하는 이미지 너비. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/convertoptions/clone)() | 현재 옵션 인스턴스를 복제합니다. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | 두 객체 인스턴스가 같은지 여부를 결정합니다. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | 두 객체 인스턴스가 같은지 여부를 결정합니다. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | 기본 해시 함수로 사용됩니다. |

### 또 보기

* class [CommonConvertOptions&lt;TFileType&gt;](../commonconvertoptions-1)
* class [ImageFileType](../../groupdocs.conversion.filetypes/imagefiletype)
* interface [IUsePdfConvertOptions](../iusepdfconvertoptions)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.conversion.dll -->
