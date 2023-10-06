---
title: WordProcessingLoadOptions
second_title: GroupDocs.Conversion for Node.js via Java API Reference
description: 
type: docs

url: /nodejs-java/groupdocs.conversion/wordprocessingloadoptions/
---

## WordProcessingLoadOptions class

 Options for loading WordProcessing documents.
 
| [WordProcessingLoadOptions](wordprocessingloadoptions)() | Initializes new instance of WordProcessingLoadOptions class. |

## Functions

| Name | Description |
| --- | --- |
| [getAutoFontSubstitution](getautofontsubstitution)() | If AutoFontSubstitution is disabled, GroupDocs.Conversion uses the DefaultFont for the substitution of missing fonts. If AutoFontSubstitution is enabled, GroupDocs.Conversion evaluates all the related fields in FontInfo (Panose, Sig etc) for the missing font and finds the closest match among the available font sources. Note that font substitution mechanism will override the DefaultFont in cases when FontInfo for the missing font is available in the document. The default value is True. |
| [getBookmarkOptions](getbookmarkoptions)() | Bookmarks options |
| [getDefaultFont](getdefaultfont)() | Default font for Words document. The following font will be used if a font is missing. |
| [getFontSubstitutes](getfontsubstitutes)() | Substitute specific fonts when converting Words document. |
| [getFormat](getformat)() |  |
| [getHideComments](gethidecomments)() | Hide comments. |
| [getHideWordTrackedChanges](gethidewordtrackedchanges)() | Hide markup and track changes for Word documents. |
| [getPassword](getpassword)() | Set password to unprotect protected document. |
| [isEmbedTrueTypeFonts](isembedtruetypefonts)() | If EmbedTrueTypeFonts is true, GroupDocs.Conversion embed true type fonts in the output document. Default: false |
| [isKeepDateFieldOriginalValue](iskeepdatefieldoriginalvalue)() | Keep original value of date field. Default: false |
| [isPreserveFontFields](ispreservefontfields)() | Specifies whether to preserve Microsoft Word form fields as form fields in PDF or convert them to text. Default is false. |
| [isUpdateFields](isupdatefields)() | Update fields after loading. Default: false |
| [isUpdatePageLayout](isupdatepagelayout)() | Update page layout after loading. Default: false |
| [isUseTextShaper](isusetextshaper)() | Specifies whether to use a text shaper for better kerning display. Default is false. |
| [setAutoFontSubstitution](setautofontsubstitution)(boolean) | If AutoFontSubstitution is disabled, GroupDocs.Conversion uses the DefaultFont for the substitution of missing fonts. If AutoFontSubstitution is enabled, GroupDocs.Conversion evaluates all the related fields in FontInfo (Panose, Sig etc) for the missing font and finds the closest match among the available font sources. Note that font substitution mechanism will override the DefaultFont in cases when FontInfo for the missing font is available in the document. The default value is True. |
| [setBookmarkOptions](setbookmarkoptions)([WordProcessingBookmarksOptions](../wordprocessingbookmarksoptions)) | Bookmarks options |
| [setDefaultFont](setdefaultfont)(String) | Default font for Words document. The following font will be used if a font is missing. |
| [setEmbedTrueTypeFonts](setembedtruetypefonts)(boolean) |  |
| [setFontSubstitutes](setfontsubstitutes)(java.util.List<com.groupdocs.conversion.contracts. FontSubstitute>) | Substitute specific fonts when converting Words document. |
| [setHideComments](sethidecomments)(boolean) | Hide comments. |
| [setHideWordTrackedChanges](sethidewordtrackedchanges)(boolean) | Hide markup and track changes for Word documents. |
| [setKeepDateFieldOriginalValue](setkeepdatefieldoriginalvalue)(boolean) | Sets Keep original value of date field. |
| [setPassword](setpassword)(String) | Set password to unprotect protected document. |
| [setPreserveFontFields](setpreservefontfields)(boolean) | Sets preserveFontFields flag |
| [setUpdateFields](setupdatefields)(boolean) |  |
| [setUpdatePageLayout](setupdatepagelayout)(boolean) |  |
| [setUseTextShaper](setusetextshaper)(boolean) | Specifies whether to use a text shaper for better kerning display. Default is false. |
