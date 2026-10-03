---
title: "SaveDocumentStream"
second_title: "GroupDocs.Conversion for Java API 레퍼런스"
description: "변환된 문서를 출력 스트림에 저장하는 대리자를 설명합니다."
type: docs
weight: 23
url: /ko/java/com.groupdocs.conversion.contracts/savedocumentstream/
---```
public interface SaveDocumentStream
```

Describes delegate for saving converted document into output stream.

## Methods

| Method | Description |
| --- | --- |
| [get()](#get--) | Saves converted document into output stream.
 |
### get() {#get--}
```
public abstract OutputStream get()
```


Saves converted document into output stream.


**Returns:**
java.io.OutputStream - Must return an output stream where the converted document will be saved

