---
title: "EmailFileType 클래스"
second_title: "Python용 .NET을 통한 GroupDocs.Conversion API 참조"
description: "이메일 애플리케이션이 메시지, 첨부 파일, 폴더, 주소록 및 기타 데이터를 저장하는 데 사용하는 이메일 파일 형식을 정의합니다."
type: docs
url: /ko/python-net/groupdocs.conversion.filetypes/emailfiletype/
is_root: false
weight: 70
---


## EmailFileType class

이메일 애플리케이션이 메시지, 첨부 파일, 폴더, 주소록 및 기타 데이터를 저장하는 데 사용하는 이메일 파일 형식을 정의합니다.

다음 파일 유형을 포함합니다:
- [`EmailFileType.eml`](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/eml/)
- [`EmailFileType.emlx`](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/emlx/)
- [`EmailFileType.msg`](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/msg/)
- [`EmailFileType.vcf`](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/vcf/)
- [`EmailFileType.mbox`](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/mbox/)
- [`EmailFileType.pst`](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/pst/)
- [`EmailFileType.ost`](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/ost/)
- [`EmailFileType.olm`](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/olm/)

https://wiki.fileformat.com/email에서 이메일 형식에 대해 자세히 알아보세요.

EmailFileType 유형은 다음 멤버를 노출합니다:

### 생성자
| 생성자 | 설명 |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/__init__/) | 직렬화를 위해 새로운 EmailFileType을 초기화합니다. |

### 메서드
| 메서드 | 설명 |
| :- | :- |
| [compare_to](/conversion/python-net/groupdocs.conversion.contracts/enumeration/compare_to/) | 현재 객체를 다른 객체와 비교합니다. ([`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)에서 상속됨) |
| [compare_to_object](/conversion/python-net/groupdocs.conversion.contracts/enumeration/compare_to_object/) | ([`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)에서 상속됨) |
| [equals](/conversion/python-net/groupdocs.conversion.filetypes/filetype/equals/) | [`Enumeration.equals`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/equals/)에 정의된 동등성 비교를 구현합니다. (`[`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)에서 상속됨) |
| [equals_enumeration](/conversion/python-net/groupdocs.conversion.filetypes/filetype/equals_enumeration/) | (`[`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)에서 상속됨) |
| [equals_object](/conversion/python-net/groupdocs.conversion.contracts/enumeration/equals_object/) | ([`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)에서 상속됨) |
| [from_display_name](/conversion/python-net/groupdocs.conversion.contracts/enumeration/from_display_name/) | ([`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)에서 상속됨) |
| [from_extension](/conversion/python-net/groupdocs.conversion.filetypes/filetype/from_extension/) | 제공된 파일 확장자에 대한 FileType을 가져옵니다. (상속됨: [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [from_filename](/conversion/python-net/groupdocs.conversion.filetypes/filetype/from_filename/) | 지정된 file_name에 대한 FileType을 반환합니다. (상속됨: [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [from_stream](/conversion/python-net/groupdocs.conversion.filetypes/filetype/from_stream/) | 제공된 문서 스트림에 대한 FileType을 반환합니다. (상속됨: [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [from_value](/conversion/python-net/groupdocs.conversion.contracts/enumeration/from_value/) | ([`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)에서 상속됨) |
| [get_all](/conversion/python-net/groupdocs.conversion.filetypes/filetype/get_all/) | (`[`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)에서 상속됨) |
| [get_hash_code](/conversion/python-net/groupdocs.conversion.contracts/enumeration/get_hash_code/) | 기본 해시 함수를 제공합니다. ([`Enumeration`](/conversion/python-net/groupdocs.conversion.contracts/enumeration/)에서 상속됨) |
| [to_string](/conversion/python-net/groupdocs.conversion.filetypes/filetype/to_string/) | 파일 유형의 문자열 표현입니다. (상속됨: [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |

### 속성들
| 속성 | 설명 |
| :- | :- |
| [description](/conversion/python-net/groupdocs.conversion.filetypes/filetype/description/) | 파일 유형 설명입니다. (상속됨: [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [extension](/conversion/python-net/groupdocs.conversion.filetypes/filetype/extension/) | 파일 확장자입니다. (상속됨: [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [family](/conversion/python-net/groupdocs.conversion.filetypes/filetype/family/) | 파일 패밀리입니다. (상속됨: [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |
| [file_format](/conversion/python-net/groupdocs.conversion.filetypes/filetype/file_format/) | 파일 형식입니다. (상속됨: [`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)) |

### 필드
| 필드 | 설명 |
| :- | :- |
| [MSG](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/msg/) | MSG는 Microsoft Outlook 및 Exchange에서 이메일 메시지, 연락처, 약속 또는 기타 작업을 저장하는 데 사용되는 파일 형식입니다. 여기에서 이 파일 형식에 대해 자세히 알아보세요. |
| [EML](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/eml/) | EML 파일 형식은 Outlook 및 기타 관련 애플리케이션을 사용해 저장된 이메일 메시지를 나타냅니다. 거의 모든 이메일 클라이언트가 RFC-822 인터넷 메시지 형식 표준을 준수하기 때문에 이 파일 형식을 지원합니다. 여기에서 이 파일 형식에 대해 자세히 알아보세요. |
| [EMLX](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/emlx/) | EMLX 파일 형식은 Apple에서 구현 및 개발되었습니다. Apple Mail 애플리케이션은 이메일을 내보낼 때 EMLX 파일 형식을 사용합니다. 여기에서 이 파일 형식에 대해 자세히 알아보세요. |
| [VCF](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/vcf/) | VCF(가상 카드 형식) 또는 vCard는 연락처 정보를 저장하는 디지털 파일 형식입니다. 이 형식은 인기 있는 정보 교환 애플리케이션 간 데이터 교환에 널리 사용됩니다. 여기에서 이 파일 형식에 대해 자세히 알아보세요. |
| [MBOX](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/mbox/) | MBox 파일 형식은 전자 메일 메시지 컬렉션을 담는 컨테이너를 나타내는 일반적인 용어입니다. 메시지는 첨부 파일과 함께 컨테이너 내부에 저장됩니다. 여기에서 이 파일 형식에 대해 자세히 알아보세요. |
| [PST](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/pst/) | .PST 확장자를 가진 파일은 Outlook 개인 저장 파일(또는 Personal Storage Table)로, 다양한 사용자 정보를 저장합니다. 여기에서 이 파일 형식에 대해 자세히 알아보세요. |
| [OST](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/ost/) | OST 또는 오프라인 저장 파일은 Microsoft Outlook을 사용해 Exchange Server에 등록한 후 로컬 컴퓨터에서 오프라인 모드로 사용자의 사서함 데이터를 나타냅니다. 여기에서 이 파일 형식에 대해 자세히 알아보세요. |
| [OLM](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/olm/) | .olm 확장자를 가진 파일은 Mac 운영 체제용 Microsoft Outlook 파일입니다. OLM 파일은 이메일 메시지, 저널, 캘린더 데이터 및 기타 애플리케이션 데이터를 저장합니다. 이는 Windows 운영 체제용 Outlook에서 사용하는 PST 파일과 유사합니다. 그러나 Mac용 Outlook에서 만든 OLM 파일은 Windows용 Outlook에서 열 수 없습니다. 여기에서 이 파일 형식에 대해 자세히 알아보세요. |
| [ICS](/conversion/python-net/groupdocs.conversion.filetypes/emailfiletype/ics/) | ICS(iCalendar) 파일 형식은 이벤트, 할 일, 자유/점유 상태 데이터와 같은 일정 및 스케줄링 정보를 나타내고 교환하는 데 사용됩니다. 여기에서 이 파일 형식에 대해 자세히 알아보세요. |
| [UNKNOWN](/conversion/python-net/groupdocs.conversion.filetypes/filetype/unknown/) | 알 수 없는 파일 유형 ([`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)에서 상속됨) |

### 또 보기
* module [`groupdocs.conversion.filetypes`](/conversion/python-net/groupdocs.conversion.filetypes/)
