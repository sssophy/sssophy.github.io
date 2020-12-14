---
title: "OMG sample page"
date: 2020-12-14 16:52:28 +0900
categories: jekyll update
---
<제외 룰셋>
1. Remove usage of generic wildcard type
2. Remove this useless assignment to local variable
3. 주석 제거

<처리 보류>
1. Cognitive Complexity of methods should not be too high
-> 메서드 내 코드 복잡성이 너무 높은 경우 탐지

2. Source files should not have any duplicated blocks
-> 소스 코드가 Duplicated 되었다는 탐지

3. String literals should not be duplicated
-> 문자열 리터럴이 반복표현 되는 경우 탐지