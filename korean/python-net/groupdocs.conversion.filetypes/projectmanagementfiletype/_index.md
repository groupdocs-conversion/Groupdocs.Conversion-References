---
title: "ProjectManagementFileType 클래스"
second_title: "Python용 .NET을 통한 GroupDocs.Conversion API 참조"
description: "Microsoft Project, Primavera P6 등과 같은 프로젝트 관리 소프트웨어에 의해 생성되는 프로젝트 파일 형식을 정의합니다."
type: docs
url: /ko/python-net/groupdocs.conversion.filetypes/projectmanagementfiletype/
is_root: false
weight: 170
---


## ProjectManagementFileType class

Microsoft Project, Primavera P6 등과 같은 프로젝트 관리 소프트웨어에 의해 생성되는 프로젝트 파일 형식을 정의합니다.

프로젝트 파일은 작업, 리소스 및 일정 관리를 통해 제품 또는 서비스 형태의 측정 가능한 결과물을 얻기 위한 컬렉션입니다. 프로젝트 관리 문서. 다음 파일 유형을 포함합니다: [`ProjectManagementFileType.mpp`](/conversion/python-net/groupdocs.conversion.filetypes/projectmanagementfiletype/mpp/), [`ProjectManagementFileType.mpt`](/conversion/python-net/groupdocs.conversion.filetypes/projectmanagementfiletype/mpt/), [`ProjectManagementFileType.mpx`](/conversion/python-net/groupdocs.conversion.filetypes/projectmanagementfiletype/mpx/). 프로젝트 관리 형식에 대해 자세히 알아보려면 여기에서 확인하세요: https://wiki.fileformat.com/project-management.

ProjectManagementFileType 유형은 다음 멤버를 노출합니다:

### 생성자
| 생성자 | 설명 |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.filetypes/projectmanagementfiletype/__init__/) | 직렬화를 위해 ProjectManagementFileType을 초기화합니다. |

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
| [MPT](/conversion/python-net/groupdocs.conversion.filetypes/projectmanagementfiletype/mpt/) | Microsoft Project 템플릿 파일은 .MPP 파일을 만들기 위한 기본 정보와 구조, 문서 설정을 포함합니다. 이 파일 형식에 대해 자세히 알아보려면 여기에서 확인하세요. |
| [MPP](/conversion/python-net/groupdocs.conversion.filetypes/projectmanagementfiletype/mpp/) | MPP는 프로젝트 관리와 관련된 정보를 통합적으로 저장하는 Microsoft Project 데이터 파일입니다. 이 파일 형식에 대해 자세히 알아보려면 여기에서 확인하세요. |
| [MPX](/conversion/python-net/groupdocs.conversion.filetypes/projectmanagementfiletype/mpx/) | Microsoft Exchange 파일 형식은 Microsoft Project(MSP)와 Primavera Project Planner, Sciforma, Timerline Precision Estimating과 같이 MPX 파일 형식을 지원하는 다른 애플리케이션 간에 프로젝트 정보를 전송하기 위한 ASCII 파일 형식입니다. 이 파일 형식에 대해 자세히 알아보려면 여기에서 확인하세요. |
| [XER](/conversion/python-net/groupdocs.conversion.filetypes/projectmanagementfiletype/xer/) | XER 파일 형식은 Primavera P6 프로젝트 계획 및 관리 애플리케이션에서 사용하는 독점적인 프로젝트 파일 형식입니다. 이 파일 형식에 대해 자세히 알아보려면 여기에서 확인하세요. |
| [UNKNOWN](/conversion/python-net/groupdocs.conversion.filetypes/filetype/unknown/) | 알 수 없는 파일 유형 ([`FileType`](/conversion/python-net/groupdocs.conversion.filetypes/filetype/)에서 상속됨) |

### 또 보기
* module [`groupdocs.conversion.filetypes`](/conversion/python-net/groupdocs.conversion.filetypes/)
