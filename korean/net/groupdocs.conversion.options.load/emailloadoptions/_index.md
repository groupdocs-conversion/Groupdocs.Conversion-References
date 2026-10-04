---
title: "EmailLoadOptions"
second_title: "GroupDocs.Conversion for .NET API 참조"
description: "이메일 문서를 로드하기 위한 옵션."
type: docs
weight: 2500
url: /ko/net/groupdocs.conversion.options.load/emailloadoptions/
---
## EmailLoadOptions class

이메일 문서를 로드하기 위한 옵션.

```csharp
public sealed class EmailLoadOptions : LoadOptions, ICustomCssStyleOptions, 
    IDocumentsContainerLoadOptions, IFontSubstituteLoadOptions, IPageLayoutOptions, 
    IPageMarginOptions, IPageOrientationOptions, IPageSizeOptions, IResourceLoadingOptions
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [EmailLoadOptions](emailloadoptions)() | 새 인스턴스를 초기화합니다 [`EmailLoadOptions`](../emailloadoptions) 클래스. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [AttachmentIcons](../../groupdocs.conversion.options.load/emailloadoptions/attachmenticons) { get; set; } | 첨부 아이콘 목록을 가져오거나 설정합니다. 목록은 다양한 파일 유형에 대한 특정 아이콘을 제공하도록 사용자 정의할 수 있습니다. 기본적으로 일반 파일 유형 아이콘을 포함합니다. |
| [ConvertOwned](../../groupdocs.conversion.options.load/emailloadoptions/convertowned) { get; set; } | 구현합니다 [`ConvertOwned`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowned) 기본값은 true입니다. |
| [ConvertOwner](../../groupdocs.conversion.options.load/emailloadoptions/convertowner) { get; set; } | `[`ConvertOwner`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowner)`을 구현합니다. 기본값은 true입니다. |
| [CustomCssStyle](../../groupdocs.conversion.options.load/emailloadoptions/customcssstyle) { get; set; } | 구현합니다 [`CustomCssStyle`](../icustomcssstyleoptions/customcssstyle) |
| [DefaultFont](../../groupdocs.conversion.options.load/emailloadoptions/defaultfont) { get; set; } | 이메일 문서의 기본 폰트입니다. 폰트가 없을 경우 다음 폰트가 사용됩니다. |
| [Depth](../../groupdocs.conversion.options.load/emailloadoptions/depth) { get; set; } | `[`Depth`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/depth)`을 구현합니다. 기본값: 1 |
| [DisplayAttachments](../../groupdocs.conversion.options.load/emailloadoptions/displayattachments) { get; set; } | 헤더에 첨부 파일을 표시하거나 숨기는 옵션입니다. 기본값: true. |
| [DisplayBccEmailAddress](../../groupdocs.conversion.options.load/emailloadoptions/displaybccemailaddress) { get; set; } | 헤더에 \"Bcc\" 이메일 주소를 표시하거나 숨기는 옵션입니다. 기본값: false. |
| [DisplayCcEmailAddress](../../groupdocs.conversion.options.load/emailloadoptions/displayccemailaddress) { get; set; } | 헤더에 \"Cc\" 이메일 주소를 표시하거나 숨기는 옵션입니다. 기본값: false. |
| [DisplayEmailAddresses](../../groupdocs.conversion.options.load/emailloadoptions/displayemailaddresses) { get; set; } | 이메일 주소를 이름과 함께 표시할지 여부를 제어하는 옵션입니다. 예: \"John Doe &lt;john.doe@sample.com&gt;\" 또는 단순히 \"John Doe.\" 기본값: true. |
| [DisplayFromEmailAddress](../../groupdocs.conversion.options.load/emailloadoptions/displayfromemailaddress) { get; set; } | 헤더에 \"from\" 이메일 주소를 표시하거나 숨기는 옵션입니다. 기본값: true. |
| [DisplayHeader](../../groupdocs.conversion.options.load/emailloadoptions/displayheader) { get; set; } | 이메일 헤더를 표시하거나 숨기는 옵션입니다. 기본값: true. |
| [DisplaySent](../../groupdocs.conversion.options.load/emailloadoptions/displaysent) { get; set; } | 헤더에 전송 날짜/시간을 표시하거나 숨기는 옵션입니다. 기본값: true. |
| [DisplaySubject](../../groupdocs.conversion.options.load/emailloadoptions/displaysubject) { get; set; } | 헤더에 제목을 표시하거나 숨기는 옵션입니다. 기본값: true. |
| [DisplayToEmailAddress](../../groupdocs.conversion.options.load/emailloadoptions/displaytoemailaddress) { get; set; } | 헤더에 \"to\" 이메일 주소를 표시하거나 숨기는 옵션입니다. 기본값: true. |
| [FieldTextMap](../../groupdocs.conversion.options.load/emailloadoptions/fieldtextmap) { get; set; } | 이메일 메시지 [`EmailField`](../emailfield)와 필드 텍스트 표현 사이의 매핑 |
| [FontSubstitutes](../../groupdocs.conversion.options.load/emailloadoptions/fontsubstitutes) { get; set; } | 폰트 대체 목록. |
| [Format](../../groupdocs.conversion.options.load/emailloadoptions/format) { get; set; } | 입력 문서 파일 유형입니다. 형식이 설정될 때까지 `null`이며, `null`인지 테스트하고, 절대 [`Unknown`](../../groupdocs.conversion.filetypes/filetype/unknown)와 비교하지 마십시오. 이 값은 절대 일치하지 않습니다. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | 입력 문서 파일 유형. |
| [MarginSettings](../../groupdocs.conversion.options.load/emailloadoptions/marginsettings) { get; set; } | 페이지 여백 설정 |
| [OrientationSettings](../../groupdocs.conversion.options.load/emailloadoptions/orientationsettings) { get; set; } | 페이지 방향 설정 |
| [PageLayoutOptions](../../groupdocs.conversion.options.load/emailloadoptions/pagelayoutoptions) { get; set; } | 구현합니다 [`PageLayoutOptions`](../ipagelayoutoptions/pagelayoutoptions) |
| [PreserveOriginalDate](../../groupdocs.conversion.options.load/emailloadoptions/preserveoriginaldate) { get; set; } | 메일 메시지를 저장할 때 원본 날짜 헤더 문자열을 유지할지 여부를 정의합니다 (기본값은 true입니다). |
| [ResourceLoadingTimeout](../../groupdocs.conversion.options.load/emailloadoptions/resourceloadingtimeout) { get; set; } | 외부 리소스를 로드하는 시간 제한 |
| [SizeSettings](../../groupdocs.conversion.options.load/emailloadoptions/sizesettings) { get; set; } | 페이지 크기 설정 |
| [SkipExternalResources](../../groupdocs.conversion.options.load/emailloadoptions/skipexternalresources) { get; set; } | 구현 [`SkipExternalResources`](../iresourceloadingoptions/skipexternalresources) |
| [TimeZoneOffset](../../groupdocs.conversion.options.load/emailloadoptions/timezoneoffset) { get; set; } | 메시지 날짜에 대한 협정 세계시(UTC) 오프셋을 가져오거나 설정합니다. 이 속성은 로컬 시간과 UTC 사이의 시간대 차이를 정의합니다. |
| [UseDefaultAttachmentIcons](../../groupdocs.conversion.options.load/emailloadoptions/usedefaultattachmenticons) { get; set; } | 기본 첨부 아이콘을 사용할지 여부를 가져오거나 설정합니다. 기본값: true. |
| [WhitelistedResources](../../groupdocs.conversion.options.load/emailloadoptions/whitelistedresources) { get; set; } | 구현 [`WhitelistedResources`](../iresourceloadingoptions/whitelistedresources) |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.load/emailloadoptions/clone)() | 현재 인스턴스를 복제합니다. |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | 두 객체 인스턴스가 같은지 여부를 결정합니다. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | 두 객체 인스턴스가 같은지 여부를 결정합니다. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | 기본 해시 함수로 사용됩니다. |

### 또 보기

* class [LoadOptions](../loadoptions)
* interface [ICustomCssStyleOptions](../icustomcssstyleoptions)
* interface [IDocumentsContainerLoadOptions](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions)
* interface [IFontSubstituteLoadOptions](../ifontsubstituteloadoptions)
* interface [IPageLayoutOptions](../ipagelayoutoptions)
* interface [IPageMarginOptions](../../groupdocs.conversion.options/ipagemarginoptions)
* interface [IPageOrientationOptions](../../groupdocs.conversion.options/ipageorientationoptions)
* interface [IPageSizeOptions](../../groupdocs.conversion.options/ipagesizeoptions)
* interface [IResourceLoadingOptions](../iresourceloadingoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.conversion.dll -->
