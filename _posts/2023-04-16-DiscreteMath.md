---
layout: post
title: "Discrete Math"
date: 2023-04-16 21:00:00 +0900
categories: Math
tag: [Discrete Math]
---
### Discrete Math

1. 이산수학의 개요
2. 논리와 명제
3. 집합과 디지털 수
4. 증명
5. Relations and Representation
6. 행렬과 행렬식
7. 함수
8. 그래프
9. 트리
10. 순열, 이산확률, 재귀적관계
11. 계싼모델
12. 수열과 급수

#### 이산수학을 공부하는 이유
[1] 컴퓨터 과학에 필수적인 이론적 기반 제공<br>
[2] 문제 해결 능력 향상<br>
[3] 컴퓨터 시스템 설계와 분석에 활용<br>
[4] 현실 세계의 문제를 수학적으로 모델링하는 능력 향상<br>

##### 소셜 네트워크 분석, 암호학, 문제해결방법
#### __이산수학__ 이란

인간이 사회속에서 살아가면서 인터넷은 빠져나갈 수 없게 되었다.<br>
따라서 인간은 실수를 하거나 오점을 줄이기 위해서 기계를 사용한다.<br>
기계를 사용하면서 오류 및 에러가 등장할 경우 인간은 실망을 해버린다.<br>
컴퓨터상의 네트워크를 분석하거나 보호받을 데이터를 민감하게 반응해야한다.<br>
따라서 이산수학을 공부할 경우 문제점을 정리하여 보호받을 분야를 정의<br>
            할 수 있기 때문에 '문제해결능력'을얻을 수 있습니다.<br>
            
---
1. __이산수학의 개요__

#### 이산수학(Discrete Mathematics)이란?
-> 연속적이 아닌 "불연속" 객체를 다루는 수학의 한 분야.<br>

ex1><br> 
[1]미적분학은 "연속적인 대상"을 다룬다.<br>
[2]이산수학은 "연속적인 대상"을 다루지 않는다.<br>
ex2><br> 
정수, 컴퓨터 프로그램의 각 단계, 로또복권에 당첨이 될 경우<br>
> // 컴퓨터 과학에서 필요로 하는 "수학적 토대"를 제공한다.

#### __본 강좌의 목표__
[1] 수리적 추론 : 수학적 주장 및 논증에 대래 읽고, 이해하고, 구성하는 능력<br>
[2] 이산구조 : 집합, 순열, 관계, 그래프, 트리 등등..<br>
[3] 알고리즘적 사고 : 문제에 대한 아이디어를 지정하고 메모리시간분석 및 디버깅<br>
[4] 응용 및 모델링 : 새로운 모델을 개발할 수 있는 능력을 기르는 것이 중요하다.<br>

#### __인공지능과 이산수학__
[1] 논리적 분석과 적절한 정보의 검색 - 명제와 논리<br>
[2] 정보의 판단 - 그래프, 트리, 집합론<br>
[3] 정보의 연관성 = 행렬과 행렬식<br>
[4] 복잡한 문제의 시스템화 - 오토마타<br>
[5] 문제 해결 - 알고리즘을 이용한 문제 해결<br>


---


2. __논리와 명제(Logic & Propositions)__

#### __논리란?__ -> 올바른 추론에 대한 연구
[1] 알고리즘의 설계나 증명 - [2] 디지털 논리회로의 설계 - [3] 논리 프로그램 분야<br>
[4] 관계형 데이터베이스 이론 - [5] 오토마타와 계산 이론 - [6] 인공지능<br>

#### __논리의 종류__
1. 형식논리 <br>
-> 형식기호사용, 연역적추론, 추론규칙이 유효한지를 탐구<br>
-> "명재 논리[True or false 판별]"와 "술어논리[구조로부터 '주어'가 가능한 {한정기호}]"로 구분<br>
2. 비형식논리 -> 자연언어, 귀납적추론, 맥락을 고려하여 내용형식과 이어지는여부<br>


#### __명제란?__ -> true OR false을 판정할 수 있는 평서문
[1] 명제는 명문 소문자 등으로 표기한다.<br>
[2] True OR false의 값을 가질때, 진리값(truth value)이라고 한다.<br>
[3] 2가지의 진리 값만을 가지는 것은 "이진 논리" or "불논리"라고 한다.<br>


#### 논리 연산
1. 단순명제 -> 하나의 문자이나 식으로 구성된 명제
2. 복합명제(합성명제) -> 단순명제 + 논리연산자로 연결된 명제

#### 논리연산자이란? __ 우선순위 순서
> NOT,(¬ or ~ ) AND(∧), OR(∨), XOR(⊕), IMPLY(->), IFF(if and only if: <->)

#### 진리값(truth value) -> 단순명제의 진리값과 논리연산자의 특성에 따라 정해진다.
#### 진리 표(truth table) -> 단순명제들의 진리값과 논리연산 결과를 표로 나타낸 것

---

4. __증명(Proofs)__

#### 컴퓨터 과학에서 증명 기술의 중요성
[1] 컴퓨터 프로그램이 올바른지 확인<br>
[2] 운영체제의 보안 유지<br>
[3] 인공 지능에서의 추론방법<br>
[4] 시스템 사양이 일관성이 있음을 증명<br>

#### 증명관련 용어
1. 정리 : 정리가 참으로 증명된 명제
2. 공리 : 증명하고자 하는 정리의 가정 or 증명이 불필요한 명재
3. 추론 규칙 : 논리적인 논증을 사용하여, 결론으로 이끌어가는 과정
4. 보조정리 : 다른 정리를 증명하는 데 사용하는 간단한 정리
5. 따른 정리 : 어떤 정리가 증명되면, 자연스럽게 증명되는 정리
6. 가설 : 증명되지는 않았지만, 참으로 믿어지는 명제
7. 이론 : 주어진 공리로부터 증명이 가능한 모든 정리의 집합

#### 증명 방법론
[1] 증명의 단계적 접근 방법 <br>
-> 1. 아이디어 스케치 단계 : 문제 해걀하기 위한 개략적인 아이디어 스케치<br>
-> 2. 구체적인 방법론 제시 단계 : 블록다이어그램(block diagram)등으로 표현함<br>
-> 3. 엄밀한 입븡이나 증명의 단계 : 객관적인 증명 방법을 공감할 수 있게 증명함.<br>

[2] 여러 가지 증명 방법<br>
1. 연역법 : 사실과 공리들로 추론하여 새로운 사실을 도출하는 것<br>
2. 귀납법 : 관찰과 실험에 기반한 가설을 귀남 추론을 통해 일반적인 규칙을 입증<br>

[3] 프로그램 입증<br>
1. 제어 구조(control structure)에서 4가지의 문장 구조를 입증
-> 순서도, 조건문, 반복문, 무조건적 이동문<br>





















