---
title: "FontSubstitutionContext 클래스"
second_title: "Python용 .NET을 통한 GroupDocs.Conversion API 참조"
description: "소스 문서를 로드하거나 렌더링하는 동안 발생한 단일 폰트 대체를 설명합니다."
type: docs
url: /ko/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/
is_root: false
weight: 190
---


## FontSubstitutionContext class

소스 문서를 로드하거나 렌더링하는 동안 발생한 단일 폰트 대체를 설명합니다.

인스턴스는 [`ConversionEvents.on_font_substituted`](/conversion/python-net/groupdocs.conversion/conversionevents/on_font_substituted/)에 전달됩니다.

FontSubstitutionContext 형식은 다음 멤버를 노출합니다:

### 생성자
| 생성자 | 설명 |
| :- | :- |
| [__init__](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/__init__/#source_file_name-original_font_name-substitute_font_name-reason) | 새 FontSubstitutionContext를 초기화합니다. |

### 속성들
| 속성 | 설명 |
| :- | :- |
| [original_font_name](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/original_font_name/) | 소스 문서에서 참조되었지만 변환 파이프라인에서 사용할 수 없는 글꼴 이름. |
| [reason](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/reason/) | 변환 파이프라인에서 보고된 그대로의 치환 메시지이며, 그대로이며 구문 분석되지 않았습니다. |
| [source_file_name](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/source_file_name/) | 변환 중인 소스 문서의 파일 이름입니다. 소스가 `io.RawIOBase`가 아닌 스트림으로 제공된 경우, 실제 파일 이름 대신 생성된 식별자가 포함됩니다. |
| [substitute_font_name](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/substitute_font_name/) | 대체 글꼴로 사용되는 글꼴 이름입니다. 엔진이 대체를 설명 텍스트로만 보고하는 문서의 경우 None일 수 있으며, 이 경우 [`FontSubstitutionContext.reason`](/conversion/python-net/groupdocs.conversion.contracts/fontsubstitutioncontext/reason/)을 읽으세요. |

### 또 보기
* module [`groupdocs.conversion.contracts`](/conversion/python-net/groupdocs.conversion.contracts/)
