---
title: "[Algorithm] 02. 배열 & (연결)리스트"
date: 2018-01-21 16:57:47
categories:
- TIL
- Algorithm
tags:
- python
- til
- algorithm
---

###### 2018. 01. 21

## 배열 & (연결)리스트

**[배열 vs (연결)리스트]**

- 메모리 저장 방식
  - 배열 크기만큼 메모리에 저장
  - 임의의 장소에 저장, 다음 원소의 주소를 앞 원소에 저장
- 장점
  - 빠른 속도
  - 원소 추가, 삽입, 삭제 용이
- 자료 접근 방식
  - 임의/순차 접근
  - 순차 접근


- 연산 실행 시간 (읽기/삽입/삭제)
  - 배열: O(1) / O(n) / O(n)
  - (연결)리스트: O(n) / O(1) / O(1)