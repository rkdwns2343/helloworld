# 오픈소스sw개론 과제
__top 명령어__
---
1. top 명령어란?

리눅스 시스템의 운용상황을 실시간으로 전반적인 상황을 모니터링하거나 프로세스를 관리할 수 있는 명령어이다.

-___아래 사진은 top명령어를 실행했을 때 사진이다.___-
<img src="https://user-images.githubusercontent.com/97230837/171996611-62ba43a0-4750-46fe-a795-a93a519e5bdc.png" width = "700" height="400">

2. 세부 정보 표시

- 위 사진에 노란색으로 표시된 곳이 세부 정보 이름이고 아래 나와있는 것이 세부 정보이다.

|세부 정보 이름|정보 내용|
|:---:|:---|
|PID|프로세스 ID(process ID)|
|USER|프로세스를 실행시킨 사용자의 ID|
|PRI|프로세스의 우선순위|
|NI|PR에 영향을 주는 nice라는 값입니다. 일의 nice value값이다. 마이너스를 가지는 nice value는 우선순위가 높음.|
|VIRT|가상 메모리의 사용량이다. 실행중인 코드,heap,stack과 같은 메모리,IO buffer메모리를 포함합니다.|
|RES|RAM에서 사용중인 메모리의 크기를 나타냅니다.|
|SHR|다른 프로세스와의 공유메모리(Shared Memory)를 나타냅니다.|
|S|프로세스의 현재 상태를 의미합니다. S(sleeping), R(running), W(swapped out process), Z(zombies)|
|%CPU|프로세스가 사용하는 CPU의 사용율을 나타냅니다.|
|%MEM|프로세스가 사용하는 메모리의 사용율 나타냅니다.|
|TIME+|프로세스가 시작된 이후 경가된 총 시간을 나타냅니다.|
|COMMAND|실행된 멸령어를 나타냅니다.|
