---
title: "WordProcessingLoadOptions"
second_title: "GroupDocs.Conversion for .NET API 참조"
description: "WordProcessing 문서를 로드하기 위한 옵션."
type: docs
weight: 2950
url: /ko/net/groupdocs.conversion.options.load/wordprocessingloadoptions/
---
## WordProcessingLoadOptions class

WordProcessing 문서를 로드하기 위한 옵션.

```csharp
public class WordProcessingLoadOptions : LoadOptions, IDocumentsContainerLoadOptions, 
    IFontSubstituteLoadOptions, IFontTransformationLoadOptions, IMetadataLoadOptions, 
    IPageMarginOptions, IPageNumberingLoadOptions, IPageSizeOptions, IResourceLoadingOptions
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [WordProcessingLoadOptions](wordprocessingloadoptions)() | `[`WordProcessingLoadOptions`](../wordprocessingloadoptions)` 클래스의 새 인스턴스를 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [AutoDetectRtlDirection](../../groupdocs.conversion.options.load/wordprocessingloadoptions/autodetectrtldirection) { get; set; } | true(기본값)인 경우, 텍스트가 주로 오른쪽에서 왼쪽으로 표시되는 단락 및 실행은 변환 전에 bidi 플래그가 복구됩니다. 이는 Microsoft Word와 LibreOffice가 적용하는 휴리스틱과 일치하며, &lt;w:bidi/&gt; 없이 OOXML을 생성하고 실행에 &lt;w:rtl w:val=\"0\"/&gt;를 포함하는 RTL 스크립트만 있는 경우(특히 Google Docs) 생성된 아랍어/히브리어 문서의 렌더링을 수정합니다. false로 설정하면 소스 마크업의 엄격한 OOXML 해석을 유지합니다. |
| [BookmarkOptions](../../groupdocs.conversion.options.load/wordprocessingloadoptions/bookmarkoptions) { get; set; } | 북마크 옵션 |
| [ClearBuiltInDocumentProperties](../../groupdocs.conversion.options.load/wordprocessingloadoptions/clearbuiltindocumentproperties) { get; set; } | 문서에서 기본 메타데이터 속성을 제거합니다. |
| [ClearCustomDocumentProperties](../../groupdocs.conversion.options.load/wordprocessingloadoptions/clearcustomdocumentproperties) { get; set; } | 문서에서 사용자 정의 메타데이터 속성을 제거합니다. |
| [CommentDisplayMode](../../groupdocs.conversion.options.load/wordprocessingloadoptions/commentdisplaymode) { get; set; } | 출력 문서에서 주석이 표시되는 방식을 지정합니다. 기본값은 ShowInBalloons입니다. |
| [ConvertOwned](../../groupdocs.conversion.options.load/wordprocessingloadoptions/convertowned) { get; set; } | `[`ConvertOwned`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowned)`을 구현합니다. 기본값은 false입니다. |
| [ConvertOwner](../../groupdocs.conversion.options.load/wordprocessingloadoptions/convertowner) { get; set; } | `[`ConvertOwner`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowner)`을 구현합니다. 기본값은 true입니다. |
| [DefaultFont](../../groupdocs.conversion.options.load/wordprocessingloadoptions/defaultfont) { get; set; } | WordProcessing 문서의 기본 글꼴을 설정합니다. |
| [Depth](../../groupdocs.conversion.options.load/wordprocessingloadoptions/depth) { get; set; } | `[`Depth`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/depth)`을 구현합니다. 기본값: 1 |
| [EmbedTrueTypeFonts](../../groupdocs.conversion.options.load/wordprocessingloadoptions/embedtruetypefonts) { get; set; } | EmbedTrueTypeFonts가 true이면 GroupDocs.Conversion이 출력 문서에 TrueType 글꼴을 삽입합니다. 기본값: true |
| [FontConfigSubstitutionEnabled](../../groupdocs.conversion.options.load/wordprocessingloadoptions/fontconfigsubstitutionenabled) { get; set; } | 시스템의 FontConfig을 기반으로 누락된 글꼴을 자동으로 대체합니다. 기본값: false. |
| [FontInfoSubstitutionEnabled](../../groupdocs.conversion.options.load/wordprocessingloadoptions/fontinfosubstitutionenabled) { get; set; } | 문서의 FontInfo를 기반으로 누락된 글꼴을 자동으로 대체합니다. 기본값: false. |
| [FontNameSubstitutionEnabled](../../groupdocs.conversion.options.load/wordprocessingloadoptions/fontnamesubstitutionenabled) { get; set; } | 글꼴 이름을 기반으로 누락된 글꼴을 자동으로 대체합니다. 기본값: false. |
| [FontSubstitutes](../../groupdocs.conversion.options.load/wordprocessingloadoptions/fontsubstitutes) { get; set; } | WordsProcessing 문서를 변환할 때 특정 글꼴을 대체합니다. |
| [FontTransformations](../../groupdocs.conversion.options.load/wordprocessingloadoptions/fonttransformations) { get; set; } | 문서 로드와 글꼴 대체가 완료된 후 기존 글꼴을 변환합니다. 글꼴 변환은 성공적으로 로드된 글꼴을 포함하여 문서의 모든 글꼴을 수정할 수 있습니다. |
| [Format](../../groupdocs.conversion.options.load/wordprocessingloadoptions/format) { get; set; } | 입력 문서 파일 유형입니다. 형식이 설정될 때까지 `null`이며, `null`인지 테스트하고, 절대 [`Unknown`](../../groupdocs.conversion.filetypes/filetype/unknown)와 비교하지 마십시오. 이 값은 절대 일치하지 않습니다. |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | 입력 문서 파일 유형. |
| [HideWordTrackedChanges](../../groupdocs.conversion.options.load/wordprocessingloadoptions/hidewordtrackedchanges) { get; set; } | Word 문서의 마크업을 숨기고 변경 내용을 추적합니다. |
| [HyphenationOptions](../../groupdocs.conversion.options.load/wordprocessingloadoptions/hyphenationoptions) { get; set; } | WordProcessing 문서에 대한 하이픈 옵션을 설정합니다. |
| [KeepDateFieldOriginalValue](../../groupdocs.conversion.options.load/wordprocessingloadoptions/keepdatefieldoriginalvalue) { get; set; } | 날짜 필드의 원래 값을 유지합니다. 기본값: false |
| [MarginSettings](../../groupdocs.conversion.options.load/wordprocessingloadoptions/marginsettings) { get; set; } | 페이지 여백 설정 |
| [PageNumbering](../../groupdocs.conversion.options.load/wordprocessingloadoptions/pagenumbering) { get; set; } | 변환된 문서에서 페이지 번호 매기기 생성을 활성화하거나 비활성화합니다. 기본값: false |
| [Password](../../groupdocs.conversion.options.load/wordprocessingloadoptions/password) { get; set; } | 보호된 문서의 보호를 해제하기 위해 비밀번호를 설정합니다. |
| [PreserveDocumentStructure](../../groupdocs.conversion.options.load/wordprocessingloadoptions/preservedocumentstructure) { get; set; } | PDF로 변환할 때 문서 구조를 보존할지 여부를 결정합니다(기본값은 false). |
| [PreserveFormFields](../../groupdocs.conversion.options.load/wordprocessingloadoptions/preserveformfields) { get; set; } | Microsoft Word 양식 필드를 PDF에서 양식 필드로 보존할지, 텍스트로 변환할지 지정합니다. 기본값은 false입니다. |
| [ShowFullCommenterName](../../groupdocs.conversion.options.load/wordprocessingloadoptions/showfullcommentername) { get; set; } | 댓글에 전체 댓글자 이름을 표시합니다. 기본값은 false입니다. |
| [SizeSettings](../../groupdocs.conversion.options.load/wordprocessingloadoptions/sizesettings) { get; set; } | 페이지 크기 설정 |
| [SkipExternalResources](../../groupdocs.conversion.options.load/wordprocessingloadoptions/skipexternalresources) { get; set; } | 구현 [`SkipExternalResources`](../iresourceloadingoptions/skipexternalresources) |
| [UpdateFields](../../groupdocs.conversion.options.load/wordprocessingloadoptions/updatefields) { get; set; } | 로드 후 필드를 업데이트합니다. 기본값: false |
| [UpdatePageLayout](../../groupdocs.conversion.options.load/wordprocessingloadoptions/updatepagelayout) { get; set; } | 로드 후 페이지 레이아웃을 업데이트합니다. 기본값: false |
| [UseTextShaper](../../groupdocs.conversion.options.load/wordprocessingloadoptions/usetextshaper) { get; set; } | 텍스트 셰이퍼를 사용하여 더 나은 커닝 표시를 할지 여부를 지정합니다. 기본값은 false입니다. |
| [WhitelistedResources](../../groupdocs.conversion.options.load/wordprocessingloadoptions/whitelistedresources) { get; set; } | 구현 [`WhitelistedResources`](../iresourceloadingoptions/whitelistedresources) |

## 메서드

| 이름 | 설명 |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | 두 객체 인스턴스가 같은지 여부를 결정합니다. |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | 두 객체 인스턴스가 같은지 여부를 결정합니다. |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | 기본 해시 함수로 사용됩니다. |

### 비고

**Font Processing Pipeline:**

**Phase 1 - Font Substitution (during document loading):**

• FontSubstitutes, DefaultFont 및 시스템 대체를 사용하여 누락되거나 사용할 수 없는 글꼴을 처리합니다

• 처리 순서: FontName → FontConfig → FontSubstitutes → FontInfo → DefaultFont

**Phase 2 - Font Replacement (after document loading):**

• 로드된 문서의 기존 글꼴을 FontReplacements를 사용하여 수정합니다

• 모든 글꼴 대체가 완료된 후 적용됩니다

### 또 보기

* class [LoadOptions](../loadoptions)
* interface [IDocumentsContainerLoadOptions](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions)
* interface [IFontSubstituteLoadOptions](../ifontsubstituteloadoptions)
* interface [IFontTransformationLoadOptions](../ifonttransformationloadoptions)
* interface [IMetadataLoadOptions](../imetadataloadoptions)
* interface [IPageMarginOptions](../../groupdocs.conversion.options/ipagemarginoptions)
* interface [IPageNumberingLoadOptions](../ipagenumberingloadoptions)
* interface [IPageSizeOptions](../../groupdocs.conversion.options/ipagesizeoptions)
* interface [IResourceLoadingOptions](../iresourceloadingoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.conversion.dll -->
