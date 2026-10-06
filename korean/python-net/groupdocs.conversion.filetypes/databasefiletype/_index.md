---
title: "DatabaseFileType 클래스"
second_title: "Python용 .NET을 통한 GroupDocs.Conversion API 참조"
description: "데이터베이스 문서를 정의합니다."
type: docs
url: /ko/python-net/groupdocs.conversion.filetypes/databasefiletype/
is_root: false
weight: 40
---


## DatabaseFileType class

데이터베이스 문서를 정의합니다. 다음 파일 형식이 포함됩니다.

- [`DatabaseFileType.nsf`](/conversion/python-net/groupdocs.conversion.filetypes/databasefiletype/nsf/)
- [`DatabaseFileType.log`](/conversion/python-net/groupdocs.conversion.filetypes/databasefiletype/log/)
- [`DatabaseFileType.sql`](/conversion/python-net/groupdocs.conversion.filetypes/databasefiletype/sql/)

DatabaseFileType 유형은 다음 멤버를 노출합니다:

### 생성자
| 생성자 | 설명 |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.filetypes/databasefiletype/__init__/) | 직렬화를 위해 새로운 DatabaseFileType을 초기화합니다. |

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
| [NSF](/conversion/python-net/groupdocs.conversion.filetypes/databasefiletype/nsf/) | .nsf (Notes Storage Facility) 확장자를 가진 파일은 이전에 Lotus Notes로 알려졌던 IBM Notes 소프트웨어에서 사용하는 데이터베이스 파일 형식입니다. 이메일, 약속, 문서, 양식 및 뷰와 같은 다양한 종류의 객체를 저장하기 위한 스키마를 정의합니다. 여기에서 이 파일 형식에 대해 자세히 알아보세요. |
| [LOG](/conversion/python-net/groupdocs.conversion.filetypes/databasefiletype/log/) | .log 확장자를 가진 파일은 타임스탬프가 포함된 일반 텍스트 목록을 담고 있습니다. 일반적으로 소프트웨어나 운영 체제가 특정 활동 상세 정보를 기록하여 개발자나 사용자가 특정 기간에 무슨 일이 있었는지 추적할 수 있도록 합니다. 여기에서 이 파일 형식에 대해 자세히 알아보세요. |
| [SQL](/conversion/python-net/groupdocs.conversion.filetypes/databasefiletype/sql/) | .sql 확장자를 가진 파일은 관계형 데이터베이스와 작업하기 위한 코드를 포함한 Structured Query Language (SQL) 파일입니다. 데이터베이스에 대한 CRUD (Create, Read, Update, Delete) 작업을 수행하는 SQL 문을 작성하는 데 사용됩니다. 여기에서 이 파일 형식에 대해 자세히 알아보세요. |
| [UNKNOWN](/conversion/python-net/groupdocs.conversion.filetypes/filetype/unknown/) | 알 수 없는 파일 유형 ([`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)에서 상속됨) |

### 또 보기
* module [`groupdocs.conversion.filetypes`](/conversion/python-net/groupdocs.conversion.filetypes/)
