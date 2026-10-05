---
title: "WordProcessingLoadOptions"
second_title: "Node.js용 GroupDocs.Conversion (Java 경유) API 레퍼런스"
description: "WordProcessing 문서를 로드하기 위한 옵션."
type: docs
weight: 44
url: /ko/nodejs-java/com.groupdocs.conversion.options.load/wordprocessingloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.io.Serializable, [com.groupdocs.conversion.options.load.IResourceLoadingOptions](../../com.groupdocs.conversion.options.load/iresourceloadingoptions)
```
public class WordProcessingLoadOptions extends LoadOptions implements Serializable, IResourceLoadingOptions
```

WordProcessing 문서를 로드하기 위한 옵션.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [WordProcessingLoadOptions()](#WordProcessingLoadOptions--) | [WordProcessingLoadOptions](../../com.groupdocs.conversion.options.load/wordprocessingloadoptions) 클래스의 새 인스턴스를 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getFormat()](#getFormat--) |  |
| [getDefaultFont()](#getDefaultFont--) | Words 문서의 기본 글꼴. |
| [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | Words 문서의 기본 글꼴. |
| [getAutoFontSubstitution()](#getAutoFontSubstitution--) | AutoFontSubstitution이 비활성화된 경우, GroupDocs.Conversion은 누락된 글꼴 대체를 위해 DefaultFont을 사용합니다. |
| [setAutoFontSubstitution(boolean value)](#setAutoFontSubstitution-boolean-) | AutoFontSubstitution이 비활성화된 경우, GroupDocs.Conversion은 누락된 글꼴 대체를 위해 DefaultFont을 사용합니다. |
| [getFontSubstitutes()](#getFontSubstitutes--) | Words 문서를 변환할 때 특정 글꼴을 대체합니다. |
| [isEmbedTrueTypeFonts()](#isEmbedTrueTypeFonts--) | EmbedTrueTypeFonts가 true인 경우, GroupDocs.Conversion은 출력 문서에 TrueType 글꼴을 삽입합니다. |
| [setEmbedTrueTypeFonts(boolean embedTrueTypeFonts)](#setEmbedTrueTypeFonts-boolean-) |  |
| [isUpdatePageLayout()](#isUpdatePageLayout--) | 로드 후 페이지 레이아웃을 업데이트합니다. |
| [setUpdatePageLayout(boolean updatePageLayout)](#setUpdatePageLayout-boolean-) |  |
| [isUpdateFields()](#isUpdateFields--) | 로드 후 필드를 업데이트합니다. |
| [setUpdateFields(boolean updateFields)](#setUpdateFields-boolean-) |  |
| [isKeepDateFieldOriginalValue()](#isKeepDateFieldOriginalValue--) | 날짜 필드의 원래 값을 유지합니다. |
| [setKeepDateFieldOriginalValue(boolean keepDateFieldOriginalValue)](#setKeepDateFieldOriginalValue-boolean-) | 날짜 필드의 원래 값을 유지하도록 설정합니다. |
| [setFontSubstitutes(List<FontSubstitute> value)](#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--) | Words 문서를 변환할 때 특정 글꼴을 대체합니다. |
| [getPassword()](#getPassword--) | 보호된 문서의 보호를 해제하기 위해 비밀번호를 설정합니다. |
| [setPassword(String value)](#setPassword-java.lang.String-) | 보호된 문서의 보호를 해제하기 위해 비밀번호를 설정합니다. |
| [getHideWordTrackedChanges()](#getHideWordTrackedChanges--) | Word 문서의 마크업 및 변경 추적을 숨깁니다. |
| [setHideWordTrackedChanges(boolean value)](#setHideWordTrackedChanges-boolean-) | Word 문서의 마크업 및 변경 추적을 숨깁니다. |
| [setHideComments(boolean value)](#setHideComments-boolean-) | 주석을 숨깁니다. |
| [getBookmarkOptions()](#getBookmarkOptions--) | 북마크 옵션 |
| [setBookmarkOptions(WordProcessingBookmarksOptions value)](#setBookmarkOptions-com.groupdocs.conversion.options.load.WordProcessingBookmarksOptions-) | 북마크 옵션 |
| [isPreserveFontFields()](#isPreserveFontFields--) | Microsoft Word 양식 필드를 PDF에서 양식 필드로 유지할지 텍스트로 변환할지를 지정합니다. |
| [setPreserveFontFields(boolean preserveFontFields)](#setPreserveFontFields-boolean-) | preserveFontFields 플래그를 설정합니다. |
| [isUseTextShaper()](#isUseTextShaper--) | 더 나은 커닝 표시를 위해 텍스트 셰이퍼 사용 여부를 지정합니다. |
| [setUseTextShaper(boolean isUseTextShaper)](#setUseTextShaper-boolean-) | 더 나은 커닝 표시를 위해 텍스트 셰이퍼 사용 여부를 지정합니다. |
| [isPreserveDocumentStructure()](#isPreserveDocumentStructure--) | PDF로 변환할 때 문서 구조를 유지할지 여부를 결정합니다(기본값은 false). |
| [setPreserveDocumentStructure(boolean preserveDocumentStructure)](#setPreserveDocumentStructure-boolean-) |  |
| [getSkipExternalResources()](#getSkipExternalResources--) | \{@inheritDoc\} |
| [setSkipExternalResources(boolean skip)](#setSkipExternalResources-boolean-) | \{@inheritDoc\} |
| [getWhitelistedResources()](#getWhitelistedResources--) | \{@inheritDoc\} |
| [setWhitelistedResources(List<String> whiteList)](#setWhitelistedResources-java.util.List-java.lang.String--) | \{@inheritDoc\} |
| [getCommentDisplayMode()](#getCommentDisplayMode--) | 출력 문서에서 주석이 표시되는 방식을 지정합니다. |
| [setCommentDisplayMode(WordProcessingCommentDisplay commentDisplayMode)](#setCommentDisplayMode-com.groupdocs.conversion.options.load.WordProcessingCommentDisplay-) |  |
| [getShowFullCommenterName()](#getShowFullCommenterName--) | 주석에 전체 댓글 작성자 이름을 표시합니다. |
| [setShowFullCommenterName(boolean showFullCommenterName)](#setShowFullCommenterName-boolean-) |  |
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


Words 문서의 기본 글꼴입니다. 글꼴이 누락된 경우 다음 글꼴이 사용됩니다.

**Returns:**
java.lang.String
### setDefaultFont(String value) {#setDefaultFont-java.lang.String-}
```
public final void setDefaultFont(String value)
```


Words 문서의 기본 글꼴입니다. 글꼴이 누락된 경우 다음 글꼴이 사용됩니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### getAutoFontSubstitution() {#getAutoFontSubstitution--}
```
public final boolean getAutoFontSubstitution()
```


AutoFontSubstitution이 비활성화된 경우, GroupDocs.Conversion은 누락된 글꼴 대체를 위해 DefaultFont을 사용합니다. AutoFontSubstitution이 활성화된 경우, GroupDocs.Conversion은 누락된 글꼴에 대한 FontInfo(Panose, Sig 등)의 모든 관련 필드를 평가하고 사용 가능한 글꼴 소스 중에서 가장 근접한 일치를 찾습니다. 글꼴 대체 메커니즘은 문서에 누락된 글꼴에 대한 FontInfo가 존재하는 경우 DefaultFont을 대체한다는 점에 유의하십시오. 기본값은 True입니다.

**Returns:**
boolean
### setAutoFontSubstitution(boolean value) {#setAutoFontSubstitution-boolean-}
```
public final void setAutoFontSubstitution(boolean value)
```


AutoFontSubstitution이 비활성화된 경우, GroupDocs.Conversion은 누락된 글꼴 대체를 위해 DefaultFont을 사용합니다. AutoFontSubstitution이 활성화된 경우, GroupDocs.Conversion은 누락된 글꼴에 대한 FontInfo(Panose, Sig 등)의 모든 관련 필드를 평가하고 사용 가능한 글꼴 소스 중에서 가장 근접한 일치를 찾습니다. 글꼴 대체 메커니즘은 문서에 누락된 글꼴에 대한 FontInfo가 존재하는 경우 DefaultFont을 대체한다는 점에 유의하십시오. 기본값은 True입니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

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


EmbedTrueTypeFonts가 true인 경우, GroupDocs.Conversion은 출력 문서에 TrueType 글꼴을 삽입합니다. 기본값: false

**Returns:**
boolean
### setEmbedTrueTypeFonts(boolean embedTrueTypeFonts) {#setEmbedTrueTypeFonts-boolean-}
```
public void setEmbedTrueTypeFonts(boolean embedTrueTypeFonts)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| embedTrueTypeFonts | boolean |  |

### isUpdatePageLayout() {#isUpdatePageLayout--}
```
public boolean isUpdatePageLayout()
```


로드 후 페이지 레이아웃을 업데이트합니다. 기본값: false

**Returns:**
boolean
### setUpdatePageLayout(boolean updatePageLayout) {#setUpdatePageLayout-boolean-}
```
public void setUpdatePageLayout(boolean updatePageLayout)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| updatePageLayout | boolean |  |

### isUpdateFields() {#isUpdateFields--}
```
public boolean isUpdateFields()
```


로드 후 필드를 업데이트합니다. 기본값: false

**Returns:**
boolean
### setUpdateFields(boolean updateFields) {#setUpdateFields-boolean-}
```
public void setUpdateFields(boolean updateFields)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| updateFields | boolean |  |

### isKeepDateFieldOriginalValue() {#isKeepDateFieldOriginalValue--}
```
public boolean isKeepDateFieldOriginalValue()
```


날짜 필드의 원래 값을 유지합니다. 기본값: false

**Returns:**
boolean
### setKeepDateFieldOriginalValue(boolean keepDateFieldOriginalValue) {#setKeepDateFieldOriginalValue-boolean-}
```
public void setKeepDateFieldOriginalValue(boolean keepDateFieldOriginalValue)
```


날짜 필드의 원래 값을 유지하도록 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| keepDateFieldOriginalValue | boolean |  |

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


Word 문서의 마크업 및 변경 추적을 숨깁니다.

**Returns:**
boolean
### setHideWordTrackedChanges(boolean value) {#setHideWordTrackedChanges-boolean-}
```
public final void setHideWordTrackedChanges(boolean value)
```


Word 문서의 마크업 및 변경 추적을 숨깁니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### setHideComments(boolean value) {#setHideComments-boolean-}
```
public final void setHideComments(boolean value)
```


주석을 숨깁니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

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
불리언 - preserveFontFields 플래그
### setPreserveFontFields(boolean preserveFontFields) {#setPreserveFontFields-boolean-}
```
public void setPreserveFontFields(boolean preserveFontFields)
```


preserveFontFields 플래그를 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| preserveFontFields | boolean | Microsoft Word 양식 필드를 PDF에서 양식 필드로 보존하거나 텍스트로 변환합니다 |

### isUseTextShaper() {#isUseTextShaper--}
```
public boolean isUseTextShaper()
```


더 나은 커닝 표시를 위해 텍스트 셰이퍼를 사용할지 여부를 지정합니다. 기본값은 false입니다.

**Returns:**
boolean
### setUseTextShaper(boolean isUseTextShaper) {#setUseTextShaper-boolean-}
```
public void setUseTextShaper(boolean isUseTextShaper)
```


더 나은 커닝 표시를 위해 텍스트 셰이퍼를 사용할지 여부를 지정합니다. 기본값은 false입니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| isUseTextShaper | boolean | isUseTextShaper 플래그 |

### isPreserveDocumentStructure() {#isPreserveDocumentStructure--}
```
public boolean isPreserveDocumentStructure()
```


PDF로 변환할 때 문서 구조를 보존할지 여부를 결정합니다(기본값은 false). 문서 구조를 내보내면 특히 큰 문서의 경우 메모리 사용량이 크게 증가한다는 점에 유의하십시오.

**Returns:**
boolean
### setPreserveDocumentStructure(boolean preserveDocumentStructure) {#setPreserveDocumentStructure-boolean-}
```
public void setPreserveDocumentStructure(boolean preserveDocumentStructure)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| preserveDocumentStructure | boolean |  |

### getSkipExternalResources() {#getSkipExternalResources--}
```
public boolean getSkipExternalResources()
```


true인 경우 모든 외부 리소스는 로드되지 않으며, 다음에 있는 리소스는 예외입니다.

**Returns:**
boolean
### setSkipExternalResources(boolean skip) {#setSkipExternalResources-boolean-}
```
public void setSkipExternalResources(boolean skip)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| skip | boolean |  |

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
boolean
### setShowFullCommenterName(boolean showFullCommenterName) {#setShowFullCommenterName-boolean-}
```
public void setShowFullCommenterName(boolean showFullCommenterName)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| showFullCommenterName | boolean |  |

