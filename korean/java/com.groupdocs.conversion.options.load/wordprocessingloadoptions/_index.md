---
title: "WordProcessingLoadOptions"
second_title: "GroupDocs.Conversion for Java API 레퍼런스"
description: "WordProcessing 문서를 로드하기 위한 옵션."
type: docs
weight: 40
url: /ko/java/com.groupdocs.conversion.options.load/wordprocessingloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.io.Serializable, [com.groupdocs.conversion.options.load.IResourceLoadingOptions](../../com.groupdocs.conversion.options.load/iresourceloadingoptions), [com.groupdocs.conversion.options.load.IPageNumberingLoadOptions](../../com.groupdocs.conversion.options.load/ipagenumberingloadoptions), [com.groupdocs.conversion.contracts.IDocumentsContainerLoadOptions](../../com.groupdocs.conversion.contracts/idocumentscontainerloadoptions)
```
public class WordProcessingLoadOptions extends LoadOptions implements Serializable, IResourceLoadingOptions, IPageNumberingLoadOptions, IDocumentsContainerLoadOptions
```

WordProcessing 문서를 로드하기 위한 옵션.

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [WordProcessingLoadOptions()](#WordProcessingLoadOptions--) | [WordProcessingLoadOptions](../../com.groupdocs.conversion.options.load/wordprocessingloadoptions) 클래스의 새 인스턴스를 초기화합니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getFormat()](#getFormat--) |  |
|  | [getDefaultFont()](#getDefaultFont--) | Words 문서의 기본 글꼴. |
|
|  | [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | Words 문서의 기본 글꼴. |
|
|  | [getAutoFontSubstitution()](#getAutoFontSubstitution--) | AutoFontSubstitution이 비활성화된 경우, GroupDocs.Conversion은 누락된 글꼴을 대체하기 위해 DefaultFont을 사용합니다. |
|
|  | [setAutoFontSubstitution(boolean value)](#setAutoFontSubstitution-boolean-) | AutoFontSubstitution이 비활성화된 경우, GroupDocs.Conversion은 누락된 글꼴을 대체하기 위해 DefaultFont을 사용합니다. |
|
|  | [getFontSubstitutes()](#getFontSubstitutes--) | Words 문서를 변환할 때 특정 글꼴을 대체합니다. |
|
|  | [isEmbedTrueTypeFonts()](#isEmbedTrueTypeFonts--) | EmbedTrueTypeFonts가 true인 경우, GroupDocs.Conversion은 출력 문서에 TrueType 글꼴을 삽입합니다. |
|
| [setEmbedTrueTypeFonts(boolean embedTrueTypeFonts)](#setEmbedTrueTypeFonts-boolean-) |  |
|  | [isUpdatePageLayout()](#isUpdatePageLayout--) | 로드 후 페이지 레이아웃을 업데이트합니다. |
|
| [setUpdatePageLayout(boolean updatePageLayout)](#setUpdatePageLayout-boolean-) |  |
|  | [isUpdateFields()](#isUpdateFields--) | 로드 후 필드를 업데이트합니다. |
|
| [setUpdateFields(boolean updateFields)](#setUpdateFields-boolean-) |  |
|  | [isKeepDateFieldOriginalValue()](#isKeepDateFieldOriginalValue--) | 날짜 필드의 원래 값을 유지합니다. |
|
|  | [setKeepDateFieldOriginalValue(boolean keepDateFieldOriginalValue)](#setKeepDateFieldOriginalValue-boolean-) | 날짜 필드의 원래 값을 유지하도록 설정합니다. |
|
|  | [setFontSubstitutes(List<FontSubstitute> value)](#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--) | Words 문서를 변환할 때 특정 글꼴을 대체합니다. |
|
|  | [getPassword()](#getPassword--) | 보호된 문서의 보호를 해제하기 위해 비밀번호를 설정합니다. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | 보호된 문서의 보호를 해제하기 위해 비밀번호를 설정합니다. |
|
|  | [getHideWordTrackedChanges()](#getHideWordTrackedChanges--) | Word 문서에 대한 마크업 및 변경 내용 추적을 숨깁니다. |
|
|  | [setHideWordTrackedChanges(boolean value)](#setHideWordTrackedChanges-boolean-) | Word 문서에 대한 마크업 및 변경 내용 추적을 숨깁니다. |
|
|  | [setHideComments(boolean value)](#setHideComments-boolean-) | 주석을 숨깁니다. |
|
|  | [getBookmarkOptions()](#getBookmarkOptions--) | 북마크 옵션 |
|
|  | [setBookmarkOptions(WordProcessingBookmarksOptions value)](#setBookmarkOptions-com.groupdocs.conversion.options.load.WordProcessingBookmarksOptions-) | 북마크 옵션 |
|
|  | [isPreserveFontFields()](#isPreserveFontFields--) | Microsoft Word 양식 필드를 PDF에서 양식 필드로 보존할지 텍스트로 변환할지 지정합니다. |
|
|  | [setPreserveFontFields(boolean preserveFontFields)](#setPreserveFontFields-boolean-) | preserveFontFields 플래그를 설정합니다. |
|
|  | [isUseTextShaper()](#isUseTextShaper--) | 보다 나은 커닝 표시를 위해 텍스트 셰이퍼 사용 여부를 지정합니다. |
|
|  | [setUseTextShaper(boolean isUseTextShaper)](#setUseTextShaper-boolean-) | 보다 나은 커닝 표시를 위해 텍스트 셰이퍼 사용 여부를 지정합니다. |
|
|  | [isPreserveDocumentStructure()](#isPreserveDocumentStructure--) | PDF로 변환할 때 문서 구조를 보존할지 여부를 결정합니다(기본값은 false). |
|
| [setPreserveDocumentStructure(boolean preserveDocumentStructure)](#setPreserveDocumentStructure-boolean-) |  |
|  | [getSkipExternalResources()](#getSkipExternalResources--) | {@inheritDoc} |
|
|  | [setSkipExternalResources(boolean skip)](#setSkipExternalResources-boolean-) | {@inheritDoc} |
|
|  | [getWhitelistedResources()](#getWhitelistedResources--) | {@inheritDoc} |
|
|  | [setWhitelistedResources(List<String> whiteList)](#setWhitelistedResources-java.util.List-java.lang.String--) | {@inheritDoc} |
|
|  | [getCommentDisplayMode()](#getCommentDisplayMode--) | 출력 문서에서 주석을 표시하는 방식을 지정합니다. |
|
| [setCommentDisplayMode(WordProcessingCommentDisplay commentDisplayMode)](#setCommentDisplayMode-com.groupdocs.conversion.options.load.WordProcessingCommentDisplay-) |  |
|  | [getShowFullCommenterName()](#getShowFullCommenterName--) | 주석에 전체 댓글 작성자 이름을 표시합니다. |
|
| [setShowFullCommenterName(boolean showFullCommenterName)](#setShowFullCommenterName-boolean-) |  |
|  | [isPageNumbering()](#isPageNumbering--) | 변환된 문서에서 페이지 번호 생성을 활성화하거나 비활성화합니다. |
|
| [setPageNumbering(boolean isPageNumbering)](#setPageNumbering-boolean-) |  |
|  | [getHyphenationOptions()](#getHyphenationOptions--) | WordProcessing 문서에 대한 하이픈 옵션을 가져옵니다. |
|
|  | [setHyphenationOptions(HyphenationOptions hyphenationOptions)](#setHyphenationOptions-com.groupdocs.conversion.options.load.HyphenationOptions-) | WordProcessing 문서에 대한 하이픈 옵션을 설정합니다. |
|
|  | [isInterruptThreadIfImageExceptionThrown()](#isInterruptThreadIfImageExceptionThrown--) | InterruptThreadIfImageExceptionThrown 플래그를 가져옵니다 기본값: false. true인 경우 이미지 처리 스레드에서 예외가 발생하면 메인 변환 스레드를 중단합니다. |
|
|  | [setInterruptThreadIfImageExceptionThrown(boolean interruptThreadIfImageExceptionThrown)](#setInterruptThreadIfImageExceptionThrown-boolean-) | InterruptThreadIfImageExceptionThrown 플래그를 설정합니다. |
|
|  | [isAutoDetectRtlDirection()](#isAutoDetectRtlDirection--) | 활성화된 경우(기본값), 텍스트가 주로 오른쪽에서 왼쪽(RTL)인 단락 및 실행은 변환 전에 bidi 플래그가 복구됩니다. |
|
|  | [setAutoDetectRtlDirection(boolean autoDetectRtlDirection)](#setAutoDetectRtlDirection-boolean-) | autoDetectRtlDirection을 설정합니다. |
|
| [isConvertOwner()](#isConvertOwner--) |  |
| [setConvertOwner(boolean convertOwner)](#setConvertOwner-boolean-) |  |
| [isConvertOwned()](#isConvertOwned--) |  |
| [setConvertOwned(boolean convertOwned)](#setConvertOwned-boolean-) |  |
| [getDepth()](#getDepth--) |  |
| [setDepth(int depth)](#setDepth-int-) |  |
### WordProcessingLoadOptions() {#WordProcessingLoadOptions--}
```
public WordProcessingLoadOptions()
```


[WordProcessingLoadOptions](../../com.groupdocs.conversion.options.load/wordprocessingloadoptions) 클래스의 새 인스턴스를 초기화합니다.


### getFormat() {#getFormat--}
```
public final WordProcessingFileType getFormat()
```


입력 문서 파일 유형


**Returns:**
[WordProcessingFileType](../../com.groupdocs.conversion.filetypes/wordprocessingfiletype)
### getDefaultFont() {#getDefaultFont--}
```
public final String getDefaultFont()
```


Words 문서의 기본 글꼴입니다. 글꼴이 없을 경우 다음 글꼴이 사용됩니다.


**Returns:**
java.lang.String
### setDefaultFont(String value) {#setDefaultFont-java.lang.String-}
```
public final void setDefaultFont(String value)
```


Words 문서의 기본 글꼴입니다. 글꼴이 없을 경우 다음 글꼴이 사용됩니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### getAutoFontSubstitution() {#getAutoFontSubstitution--}
```
public final boolean getAutoFontSubstitution()
```


AutoFontSubstitution이 비활성화된 경우, GroupDocs.Conversion은 누락된 글꼴 대체를 위해 DefaultFont을 사용합니다. AutoFontSubstitution이 활성화된 경우,
GroupDocs.Conversion은 누락된 글꼴에 대해 FontInfo(Panose, Sig 등)의 모든 관련 필드를 평가하고 사용 가능한 글꼴 소스 중에서 가장 근접한 일치를 찾습니다.
글꼴 대체 메커니즘은 문서에 누락된 글꼴에 대한 FontInfo가 있는 경우 DefaultFont를 대체합니다. 기본값은 True입니다.


**Returns:**
불리언
### setAutoFontSubstitution(boolean value) {#setAutoFontSubstitution-boolean-}
```
public final void setAutoFontSubstitution(boolean value)
```


AutoFontSubstitution이 비활성화된 경우, GroupDocs.Conversion은 누락된 글꼴 대체를 위해 DefaultFont을 사용합니다. AutoFontSubstitution이 활성화된 경우,
GroupDocs.Conversion은 누락된 글꼴에 대해 FontInfo(Panose, Sig 등)의 모든 관련 필드를 평가하고 사용 가능한 글꼴 소스 중에서 가장 근접한 일치를 찾습니다.
글꼴 대체 메커니즘은 문서에 누락된 글꼴에 대한 FontInfo가 있는 경우 DefaultFont를 대체합니다. 기본값은 True입니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | 불리언 |  |

### getFontSubstitutes() {#getFontSubstitutes--}
```
public final List<FontSubstitute> getFontSubstitutes()
```


Words 문서를 변환할 때 특정 글꼴을 대체합니다.


**Returns:**
java.util.List<com.groupdocs.conversion.contracts.FontSubstitute>
### isEmbedTrueTypeFonts() {#isEmbedTrueTypeFonts--}
```
public boolean isEmbedTrueTypeFonts()
```


EmbedTrueTypeFonts가 true이면 GroupDocs.Conversion은 출력 문서에 TrueType 글꼴을 삽입합니다. 기본값: false


**Returns:**
불리언
### setEmbedTrueTypeFonts(boolean embedTrueTypeFonts) {#setEmbedTrueTypeFonts-boolean-}
```
public void setEmbedTrueTypeFonts(boolean embedTrueTypeFonts)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| embedTrueTypeFonts | 불리언 |  |

### isUpdatePageLayout() {#isUpdatePageLayout--}
```
public boolean isUpdatePageLayout()
```


로드 후 페이지 레이아웃을 업데이트합니다. 기본값: false


**Returns:**
불리언
### setUpdatePageLayout(boolean updatePageLayout) {#setUpdatePageLayout-boolean-}
```
public void setUpdatePageLayout(boolean updatePageLayout)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| updatePageLayout | 불리언 |  |

### isUpdateFields() {#isUpdateFields--}
```
public boolean isUpdateFields()
```


로드 후 필드를 업데이트합니다. 기본값: false


**Returns:**
불리언
### setUpdateFields(boolean updateFields) {#setUpdateFields-boolean-}
```
public void setUpdateFields(boolean updateFields)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| updateFields | 불리언 |  |

### isKeepDateFieldOriginalValue() {#isKeepDateFieldOriginalValue--}
```
public boolean isKeepDateFieldOriginalValue()
```


날짜 필드의 원래 값을 유지합니다. 기본값: false


**Returns:**
불리언
### setKeepDateFieldOriginalValue(boolean keepDateFieldOriginalValue) {#setKeepDateFieldOriginalValue-boolean-}
```
public void setKeepDateFieldOriginalValue(boolean keepDateFieldOriginalValue)
```


날짜 필드의 원래 값을 유지하도록 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| keepDateFieldOriginalValue | 불리언 |  |

### setFontSubstitutes(List<FontSubstitute> value) {#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--}
```
public final void setFontSubstitutes(List<FontSubstitute> value)
```


Words 문서를 변환할 때 특정 글꼴을 대체합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | java.util.List<com.groupdocs.conversion.contracts.FontSubstitute> |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


보호된 문서의 보호를 해제하기 위해 비밀번호를 설정합니다.


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


보호된 문서의 보호를 해제하기 위해 비밀번호를 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### getHideWordTrackedChanges() {#getHideWordTrackedChanges--}
```
public final boolean getHideWordTrackedChanges()
```


Word 문서에 대한 마크업 및 변경 내용 추적을 숨깁니다.


**Returns:**
불리언
### setHideWordTrackedChanges(boolean value) {#setHideWordTrackedChanges-boolean-}
```
public final void setHideWordTrackedChanges(boolean value)
```


Word 문서에 대한 마크업 및 변경 내용 추적을 숨깁니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | 불리언 |  |

### setHideComments(boolean value) {#setHideComments-boolean-}
```
public final void setHideComments(boolean value)
```


주석을 숨깁니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | 불리언 |  |

### getBookmarkOptions() {#getBookmarkOptions--}
```
public final WordProcessingBookmarksOptions getBookmarkOptions()
```


북마크 옵션


**Returns:**
[WordProcessingBookmarksOptions](../../com.groupdocs.conversion.options.load/wordprocessingbookmarksoptions)
### setBookmarkOptions(WordProcessingBookmarksOptions value) {#setBookmarkOptions-com.groupdocs.conversion.options.load.WordProcessingBookmarksOptions-}
```
public final void setBookmarkOptions(WordProcessingBookmarksOptions value)
```


북마크 옵션


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [WordProcessingBookmarksOptions](../../com.groupdocs.conversion.options.load/wordprocessingbookmarksoptions) |  |

### isPreserveFontFields() {#isPreserveFontFields--}
```
public boolean isPreserveFontFields()
```


Microsoft Word 양식 필드를 PDF에서 양식 필드로 보존할지 텍스트로 변환할지 지정합니다. 기본값은 false입니다.


**Returns:**
boolean - preserveFontFields 플래그

### setPreserveFontFields(boolean preserveFontFields) {#setPreserveFontFields-boolean-}
```
public void setPreserveFontFields(boolean preserveFontFields)
```


preserveFontFields 플래그를 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | preserveFontFields | 불리언 | Microsoft Word 양식 필드를 PDF에서 양식 필드로 보존하거나 텍스트로 변환합니다 |
|

### isUseTextShaper() {#isUseTextShaper--}
```
public boolean isUseTextShaper()
```


텍스트 셰이퍼를 사용하여 커닝 표시를 개선할지 여부를 지정합니다. 기본값은 false입니다.


**Returns:**
불리언
### setUseTextShaper(boolean isUseTextShaper) {#setUseTextShaper-boolean-}
```
public void setUseTextShaper(boolean isUseTextShaper)
```


텍스트 셰이퍼를 사용하여 커닝 표시를 개선할지 여부를 지정합니다. 기본값은 false입니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | isUseTextShaper | 불리언 | isUseTextShaper 플래그 |
|

### isPreserveDocumentStructure() {#isPreserveDocumentStructure--}
```
public boolean isPreserveDocumentStructure()
```


PDF로 변환할 때 문서 구조를 보존할지 여부를 결정합니다(기본값은 false). 문서 구조를 내보내면 특히 큰 문서의 경우 메모리 사용량이 크게 증가한다는 점에 유의하십시오.


**Returns:**
불리언
### setPreserveDocumentStructure(boolean preserveDocumentStructure) {#setPreserveDocumentStructure-boolean-}
```
public void setPreserveDocumentStructure(boolean preserveDocumentStructure)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| preserveDocumentStructure | 불리언 |  |

### getSkipExternalResources() {#getSkipExternalResources--}
```
public boolean getSkipExternalResources()
```


true인 경우 모든 외부 리소스는 로드되지 않으며, 해당 리소스는 ...에 있는 리소스를 제외합니다


**Returns:**
불리언
### setSkipExternalResources(boolean skip) {#setSkipExternalResources-boolean-}
```
public void setSkipExternalResources(boolean skip)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| skip | 불리언 |  |

### getWhitelistedResources() {#getWhitelistedResources--}
```
public List<String> getWhitelistedResources()
```


항상 로드되는 외부 리소스


**Returns:**
java.util.List<java.lang.String>
### setWhitelistedResources(List<String> whiteList) {#setWhitelistedResources-java.util.List-java.lang.String--}
```
public void setWhitelistedResources(List<String> whiteList)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| whiteList | java.util.List<java.lang.String> |  |

### getCommentDisplayMode() {#getCommentDisplayMode--}
```
public WordProcessingCommentDisplay getCommentDisplayMode()
```


출력 문서에서 주석이 표시되는 방식을 지정합니다. 기본값은 ShowInBalloons입니다.


**Returns:**
[WordProcessingCommentDisplay](../../com.groupdocs.conversion.options.load/wordprocessingcommentdisplay)
### setCommentDisplayMode(WordProcessingCommentDisplay commentDisplayMode) {#setCommentDisplayMode-com.groupdocs.conversion.options.load.WordProcessingCommentDisplay-}
```
public void setCommentDisplayMode(WordProcessingCommentDisplay commentDisplayMode)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| commentDisplayMode | [WordProcessingCommentDisplay](../../com.groupdocs.conversion.options.load/wordprocessingcommentdisplay) |  |

### getShowFullCommenterName() {#getShowFullCommenterName--}
```
public boolean getShowFullCommenterName()
```


주석에 전체 댓글 작성자 이름을 표시합니다. 기본값은 false입니다.


**Returns:**
불리언
### setShowFullCommenterName(boolean showFullCommenterName) {#setShowFullCommenterName-boolean-}
```
public void setShowFullCommenterName(boolean showFullCommenterName)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| showFullCommenterName | 불리언 |  |

### isPageNumbering() {#isPageNumbering--}
```
public boolean isPageNumbering()
```


변환된 문서에서 페이지 번호 생성을 활성화하거나 비활성화합니다. 기본값: false


**Returns:**
불리언
### setPageNumbering(boolean isPageNumbering) {#setPageNumbering-boolean-}
```
public void setPageNumbering(boolean isPageNumbering)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| isPageNumbering | 불리언 |  |

### getHyphenationOptions() {#getHyphenationOptions--}
```
public HyphenationOptions getHyphenationOptions()
```


WordProcessing 문서에 대한 하이픈 옵션을 가져옵니다.


**Returns:**
[HyphenationOptions](../../com.groupdocs.conversion.options.load/hyphenationoptions)
### setHyphenationOptions(HyphenationOptions hyphenationOptions) {#setHyphenationOptions-com.groupdocs.conversion.options.load.HyphenationOptions-}
```
public void setHyphenationOptions(HyphenationOptions hyphenationOptions)
```


WordProcessing 문서에 대한 하이픈 옵션을 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| hyphenationOptions | [HyphenationOptions](../../com.groupdocs.conversion.options.load/hyphenationoptions) |  |

### isInterruptThreadIfImageExceptionThrown() {#isInterruptThreadIfImageExceptionThrown--}
```
public boolean isInterruptThreadIfImageExceptionThrown()
```


InterruptThreadIfImageExceptionThrown 플래그를 가져옵니다 기본값: false. true인 경우 이미지 처리 스레드에서 예외가 발생하면 메인 변환 스레드를 중단합니다.


**Returns:**
불리언
### setInterruptThreadIfImageExceptionThrown(boolean interruptThreadIfImageExceptionThrown) {#setInterruptThreadIfImageExceptionThrown-boolean-}
```
public void setInterruptThreadIfImageExceptionThrown(boolean interruptThreadIfImageExceptionThrown)
```


InterruptThreadIfImageExceptionThrown 플래그를 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| interruptThreadIfImageExceptionThrown | 불리언 |  |

### isAutoDetectRtlDirection() {#isAutoDetectRtlDirection--}
```
public boolean isAutoDetectRtlDirection()
```


활성화된 경우(기본값), 텍스트가 주로 오른쪽에서 왼쪽(RTL)인 단락 및 실행은 변환 전에 bidi 플래그가 복구됩니다.


이것은 Microsoft Word와 LibreOffice에 적용된 휴리스틱과 일치합니다 그리고
생성기가 만든 아랍어/히브리어 문서의 렌더링을 수정합니다
(특히 Google Docs)에서 OOXML을 없이 내보내는 경우


그리고

오직 RTL 스크립트만 포함하는 실행에서.


설정값을
false
엄격한 OOXML 해석을 유지하기 위해
소스 마크업.


**Returns:**
불리언
### setAutoDetectRtlDirection(boolean autoDetectRtlDirection) {#setAutoDetectRtlDirection-boolean-}
```
public void setAutoDetectRtlDirection(boolean autoDetectRtlDirection)
```


autoDetectRtlDirection을 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | autoDetectRtlDirection | 불리언 | autoDetectRtlDirection |
|

### isConvertOwner() {#isConvertOwner--}
```
public boolean isConvertOwner()
```


문서 컨테이너 자체를 변환해야 하는지 제어하는 옵션을 가져옵니다


**Returns:**
불리언
### setConvertOwner(boolean convertOwner) {#setConvertOwner-boolean-}
```
public void setConvertOwner(boolean convertOwner)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| convertOwner | 불리언 |  |

### isConvertOwned() {#isConvertOwned--}
```
public boolean isConvertOwned()
```


문서 컨테이너 내 소유된 문서를 변환해야 하는지 제어하는 옵션


**Returns:**
불리언
### setConvertOwned(boolean convertOwned) {#setConvertOwned-boolean-}
```
public void setConvertOwned(boolean convertOwned)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| convertOwned | 불리언 |  |

### getDepth() {#getDepth--}
```
public int getDepth()
```


변환을 수행할 깊이 수준의 수를 제어하는 옵션


**Returns:**
int
### setDepth(int depth) {#setDepth-int-}
```
public void setDepth(int depth)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| depth | int |  |

