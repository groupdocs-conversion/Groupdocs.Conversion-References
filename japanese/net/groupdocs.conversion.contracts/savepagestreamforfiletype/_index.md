---
title: SavePageStreamForFileType
second_title: GroupDocs.Conversion for .NET API リファレンス
description: 変換されたドキュメント ページをストリームに保存するためのデリゲートを記述します
type: docs
weight: 500
url: /ja/net/groupdocs.conversion.contracts/savepagestreamforfiletype/
---
## SavePageStreamForFileType delegate

変換されたドキュメント ページをストリームに保存するためのデリゲートを記述します。

```csharp
public delegate Stream SavePageStreamForFileType(int pageNumber, FileType fileType);
```

| パラメータ | タイプ | 説明 |
| --- | --- | --- |
| pageNumber | Int32 | 変換後のページ番号 |
| fileType | FileType | 変換されたドキュメントの種類 |

### 戻り値

変換されたドキュメント ページが保存されるストリームを返す必要があります

### 関連項目

* class [FileType](../../groupdocs.conversion.filetypes/filetype)
* 名前空間 [GroupDocs.Conversion.Contracts](../../groupdocs.conversion.contracts)
* 組み立て [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->