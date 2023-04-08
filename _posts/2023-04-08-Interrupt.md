---
layout: post
title: "Interrupt"
date: 2023-04-08 23:00:00 +0900
categories: 인터럽트
tag: [인터럽트, 프로세서]
---
### [Interrupt(인터럽트)](https://en.wikipedia.org/wiki/Interrupt)
: 장치에 예외상황이 발생하여 처리가 필요한 경우 <br>
: 마이크로프로세서에게 알려 처리할 수 있도록 하는 것<br>
> [1] 동기 인터럽트, 비동기 인터럽트<br>
> [2] 외부 인터럽트, 내부 인터럽트
> [3] 하드웨어 인터럽트, 소프트웨어 인터럽트<br>

#### Typr of Interrupt
> [1] I/O Interrupt <br>
> : 입출력 종료, 입출력 오류로 인한 CPU기능 요구<br>
> [2] External Interrupt <br>
> : 오퍼레이터 및 타이머에 뜻으로 의도록으로 프로그램이 중단되는 것<br>
> [3] Restart Interrupt <br>
> : 오퍼레이터 및 다른 프로세서에 뜻으로 재시작명령이 도착했을 때 실행하는 것<br>
> [4] Program Check Interrupt <br>
> : 보호된 기억공간에 다가감 or 불법적인 명령수행 의 문제발생시 불려지는 것<br>
> [5] Machine check Interrupt <br>
> : 하드웨어구조로 말리암아 일어난다.<br>
> [6] Supervisor Interrupt <br>
> : 사용자가 SVC명령을 불러냈거나 입출력,기억장치할당따위를 맡는 경우<br>
