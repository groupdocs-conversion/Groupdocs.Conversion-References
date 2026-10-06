---
title: "get_hash_code 메서드"
second_title: "Python용 .NET을 통한 GroupDocs.Conversion API 참조"
description: "기본 해시 함수로 사용됩니다."
type: docs
url: /ko/python-net/groupdocs.conversion.contracts/valueobject/get_hash_code/
is_root: false
weight: 1040
---


## get_hash_code

기본 해시 함수로 사용됩니다.

배열, 리스트 및 사전 구성 요소는 내용에 따라 해시가 계산되며, 동등성 비교 방식과 일치합니다. 따라서 동등하게 비교되는 두 객체는 해시도 동일하게 계산되어 사전 키나 집합 멤버로 사용할 수 있습니다.

이는 다른 `System.Collections.IEnumerable`인 구성 요소에는 적용되지 않습니다: 이러한 구성 요소는 레퍼런스로 해시가 계산되며, 지연 이터레이터로 노출된 경우 매 접근 시 다른 값을 반환하므로 이를 포함하는 객체는 키로 전혀 사용할 수 없습니다. 중첩 컬렉션도 마찬가지로 재귀적으로가 아니라 레퍼런스로 비교 및 해시됩니다.

다른 결과는 값 객체가 노출하는 컬렉션을 변경하면(예: 페이지 리스트에 추가하거나 레이아웃 이름 배열에 쓰는 경우) 해당 객체의 해시가 변경되어 해시 컨테이너에 이미 저장된 인스턴스를 찾을 수 없게 된다는 점입니다. 값 객체는 키로 사용된 후에는 고정된 것으로 간주하십시오.

```python
def get_hash_code(self):
    ...
```

**Returns:** A hash code for the current object.

### 또 보기
* class [`ValueObject`](/conversion/python-net/groupdocs.conversion.contracts/valueobject/)
