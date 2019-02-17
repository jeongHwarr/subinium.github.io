---
title : \[ML with Python\] 3장 비지도 학습과 데이터 전처리 - 비지도 학습의 도전 과제
category :
  - ML
tag :
  - python
  - deep-learning
  - AI
  - machine learning
  - 머신러닝
  - 비지도 학습
  - 데이터 전처리
  - 입문
  - subinium
  - 소스코드

sidebar:
  nav: sidebar-MLwithPython

use_math : true

header:
  teaser : /assets/images/category/ml.jpg
  overlay_color: "#AF3D8A"

---

3.2 비지도 학습의 도전 과제

본 문서는 [파이썬 라이브러리를 활용한 머신러닝] 책을 기반으로 하고 있으며, subinium(본인)이 정리하고 추가한 내용입니다. 생략된 부분과 추가된 부분이 있으니 추가/수정하면 좋을 것 같은 부분은 댓글로 이야기해주시면 감사하겠습니다.

---

비지도 학습에서 가장 어려운 일은 알고리즘이 뭔가 유용한 것을 학습했는지 평가하는 것입니다.
비지도 학습은 보통 레이블이 없는 데이터에 적용하기 때문에 무엇이 올바른 출력인지 모릅니다.
그렇기에 결과를 확인하기 전까지는 알고리즘이 유의미한 작업을 했는가에 대해는 알 수 없다는 것입니다.

이런 이유로 비지도 학습 알고리즘은 데이터 과학자가 데이터를 더 잘 이해하고 싶을 때 탐색적 분석 단계에서 많이 사용합니다.
지도 학습의 전처리 단계에서도 사용합니다. 비지도 학습 결과로 새롭게 표현된 데이터를 사용해 학습하면 지도 학습의 정확도가 좋아지기도 하며 메모리와 시간을 절약할 수 있습니다.

다음 절에서는 가볍게 전처리에 관해서 다루고 비지도 알고리즘을 본격적으로 보도록 하겠습니다.