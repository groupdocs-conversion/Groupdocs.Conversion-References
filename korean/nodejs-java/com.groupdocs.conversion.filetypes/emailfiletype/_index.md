---
title: "EmailFileType"
second_title: "Node.js용 GroupDocs.Conversion (Java 경유) API 레퍼런스"
description: "이메일 파일 형식은 이메일 애플리케이션에서 이메일 메시지, 첨부 파일, 폴더, 주소록 등을 포함한 다양한 데이터를 저장하는 데 사용됩니다."
type: docs
weight: 15
url: /ko/nodejs-java/com.groupdocs.conversion.filetypes/emailfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class EmailFileType extends FileType implements Serializable
```

이메일 파일 형식은 이메일 애플리케이션에서 이메일 메시지, 첨부 파일, 폴더, 주소록 등을 포함한 다양한 데이터를 저장하는 데 사용됩니다. 다음 파일 유형을 포함합니다: [Eml](../../com.groupdocs.conversion.filetypes/emailfiletype\\#Eml), [Emlx](../../com.groupdocs.conversion.filetypes/emailfiletype\\#Emlx), [Msg](../../com.groupdocs.conversion.filetypes/emailfiletype\\#Msg), [Vcf](../../com.groupdocs.conversion.filetypes/emailfiletype\\#Vcf). [Pst](../../com.groupdocs.conversion.filetypes/emailfiletype\\#Pst). [Ost](../../com.groupdocs.conversion.filetypes/emailfiletype\\#Ost). [Olm](../../com.groupdocs.conversion.filetypes/emailfiletype\\#Olm). 이메일 형식에 대해 자세히 알아보려면 [here][].


[here]: https://wiki.fileformat.com/email
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [EmailFileType()](#EmailFileType--) | 직렬화 생성자 |
## 필드

| 필드 | 설명 |
| --- | --- |
| [Msg](#Msg) | MSG는 Microsoft Outlook 및 Exchange에서 이메일 메시지, 연락처, 약속 또는 기타 작업을 저장하는 데 사용되는 파일 형식입니다. |
| [Eml](#Eml) | EML 파일 형식은 Outlook 및 기타 관련 애플리케이션을 사용하여 저장된 이메일 메시지를 나타냅니다. |
| [Emlx](#Emlx) | EMLX 파일 형식은 Apple에 의해 구현 및 개발되었습니다. |
| [Vcf](#Vcf) | VCF(Virtual Card Format) 또는 vCard는 연락처 정보를 저장하기 위한 디지털 파일 형식입니다. |
| [Mbox](#Mbox) | MBox 파일 형식은 전자 메일 메시지 모음을 저장하는 컨테이너를 나타내는 일반적인 용어입니다. |
| [Pst](#Pst) | .PST 확장자를 가진 파일은 Outlook 개인 저장 파일(또는 Personal Storage Table)로, 다양한 사용자 정보를 저장합니다. |
| [Ost](#Ost) | OST 또는 Offline Storage Files는 Microsoft Outlook을 사용해 Exchange Server에 등록한 후 로컬 컴퓨터에서 오프라인 모드로 사용자의 메일함 데이터를 나타냅니다. |
| [Olm](#Olm) | .olm 확장자를 가진 파일은 Mac 운영 체제용 Microsoft Outlook 파일입니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
### EmailFileType() {#EmailFileType--}
```
public EmailFileType()
```


직렬화 생성자

### Msg {#Msg}
```
public static final EmailFileType Msg
```


MSG는 Microsoft Outlook 및 Exchange에서 이메일 메시지, 연락처, 약속 또는 기타 작업을 저장하는 데 사용되는 파일 형식입니다. 이 파일 형식에 대해 자세히 알아보려면 [here][].


[here]: https://wiki.fileformat.com/email/msg

### Eml {#Eml}
```
public static final EmailFileType Eml
```


EML 파일 형식은 Outlook 및 기타 관련 애플리케이션을 사용해 저장된 이메일 메시지를 나타냅니다. 거의 모든 이메일 클라이언트가 RFC-822 인터넷 메시지 형식 표준을 준수하기 때문에 이 형식을 지원합니다. 이 파일 형식에 대해 자세히 알아보려면 [here][].


[here]: https://wiki.fileformat.com/email/eml

### Emlx {#Emlx}
```
public static final EmailFileType Emlx
```


EMLX 파일 형식은 Apple에서 구현 및 개발되었습니다. Apple Mail 애플리케이션은 이메일을 내보낼 때 EMLX 파일 형식을 사용합니다. 이 파일 형식에 대해 자세히 알아보려면 [here][].


[here]: https://wiki.fileformat.com/email/emlx

### Vcf {#Vcf}
```
public static final EmailFileType Vcf
```


VCF(Virtual Card Format) 또는 vCard는 연락처 정보를 저장하는 디지털 파일 형식입니다. 이 형식은 인기 있는 정보 교환 애플리케이션 간 데이터 교환에 널리 사용됩니다. 이 파일 형식에 대해 자세히 알아보려면 [here][].


[here]: https://wiki.fileformat.com/email/vcf

### Mbox {#Mbox}
```
public static final EmailFileType Mbox
```


MBox 파일 형식은 전자 메일 메시지 모음을 저장하는 컨테이너를 나타내는 일반적인 용어입니다. 메시지는 첨부 파일과 함께 컨테이너 내부에 저장됩니다. 이 파일 형식에 대해 자세히 알아보려면 [here][].


[here]: https://docs.fileformat.com/email/mbox/

### Pst {#Pst}
```
public static final EmailFileType Pst
```


.PST 확장자를 가진 파일은 Outlook 개인 저장 파일(또는 Personal Storage Table)로, 다양한 사용자 정보를 저장합니다. 이 파일 형식에 대해 자세히 알아보려면 [here][].


[here]: https://wiki.fileformat.com/email/pst

### Ost {#Ost}
```
public static final EmailFileType Ost
```


OST 또는 Offline Storage Files는 Microsoft Outlook을 사용해 Exchange Server에 등록한 후 로컬 컴퓨터에서 오프라인 모드로 사용자의 메일함 데이터를 나타냅니다. 이 파일 형식에 대해 자세히 알아보려면 [here][].


[here]: https://wiki.fileformat.com/email/ost

### Olm {#Olm}
```
public static final EmailFileType Olm
```


.olm 확장자를 가진 파일은 Mac 운영 체제용 Microsoft Outlook 파일입니다. OLM 파일은 이메일 메시지, 저널, 캘린더 데이터 및 기타 유형의 애플리케이션 데이터를 저장합니다. 이는 Windows 운영 체제용 Outlook에서 사용하는 PST 파일과 유사합니다. 그러나 Mac용 Outlook에서 만든 OLM 파일은 Outlook for Windows에서 열 수 없습니다. 이 파일 형식에 대해 자세히 알아보려면 [here][].


[here]: https://wiki.fileformat.com/email/olm

### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


소스 파일 유형에 대한 기본 로드 옵션을 준비했습니다.

**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)
### getConvertOptions() {#getConvertOptions--}
```
public ConvertOptions getConvertOptions()
```


파일 유형에 대한 기본 변환 옵션을 준비했습니다.

**Returns:**
[ConvertOptions](../../com.groupdocs.conversion.options.convert/convertoptions)
