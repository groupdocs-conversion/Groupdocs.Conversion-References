---
title: "Metered 클래스"
second_title: "Python용 .NET을 통한 GroupDocs.Conversion API 참조"
description: "계량(사용량 기반) 라이선스를 관리합니다."
type: docs
url: /ko/python-net/groupdocs.conversion/metered/
is_root: false
weight: 210
---


## Metered class

계량(사용량 기반) 라이선스를 관리합니다.

Metered 라이선스는 실제 사용량에 따라 청구됩니다 (보통 페이지 또는
문서가 처리됩니다). 공개/비공개 키 쌍을 한 번 설정합니다
애플리케이션 시작 시; 래퍼가 사용량을 GroupDocs에 보고합니다
백그라운드에서 라이선스 서버에

Metered 형식은 다음 멤버를 노출합니다:

### 메서드
| 메서드 | 설명 |
| :- | :- |
| [get_consumption_credit](/conversion/python-net/groupdocs.conversion/metered/get_consumption_credit/) | 현재 키에 대한 남은 메터링 크레딧을 반환합니다. |
| [get_consumption_quantity](/conversion/python-net/groupdocs.conversion/metered/get_consumption_quantity/) | 지금까지 사용된 총 메터링 양을 반환합니다. |
| [set_metered_key](/conversion/python-net/groupdocs.conversion/metered/set_metered_key/#public_key-private_key) | 주어진 공개/비공개 키 쌍으로 메터링 청구를 활성화합니다. |

### 또 보기
* module [`groupdocs.conversion`](/conversion/python-net/groupdocs.conversion/)
