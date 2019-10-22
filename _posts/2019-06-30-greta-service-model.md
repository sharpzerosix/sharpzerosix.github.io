---
layout: post
title:  "웹기반 종합 회계 시스템 greta 기획안"
date:   2019-06-30 19:00:00 +0900
categories: IT
author: 정지용
---
<img src="https://raw.githubusercontent.com/StopDragon/greta-service-model/master/logo/greta%20logo.png" width="200"><br>

## 1. Team Introduce
- TEAM NAME: idiot-brothers
- SERVICE NAME: [greta-github](https://github.com/greta-develop)
- MEMBERS:
    - [Jung Jiyong](https://github.com/StopDragon) (Creative Director and UX/UI Designer)
        - jiyong210@gmail.com
    - [Kim Mingeun](https://github.com/getsolaris) (Backend Developer)
        - mingeun.k.k@gmail.com
    - [Kim Yeongseo](https://github.com/kys6879) (Frontend Developer)
        - yskim@markany.com

## 2. Service Model
### 2.1. Planning the road
평소 계모임이나 학교 동아리, 학생회, 비영리 단체 등을 보면서 투명하지 못한 회계로 인해 내부 분열이나 횡령의 문제가 발생하고 있습니다. <br>
사람들은 나름 이러한 문제를 해결하기 위해 투명하게 엑셀이나 구글 시프트를 이용해서 장부를 작성하지만 이 또한 분식회계가 가능하기 때문에 조작이 불가능하면서도 투명한 장부를 작성할 수 있는 서비스를 만들게 되었습니다.
### 2.2. Service User
계모임 총무, 동아리, 학생회, 소규모 단체, 비영리 단체, 마을 등 장부 공개가 필요하고 투명하게 조직을 운영하고 싶은 사람들
### 2.3. Service Advantages
- 데이터 불가변성을 우선으로 raw파일은 수정이 불가능하기 때문에 고신뢰성
- 오송금, 오사용 등으로 인한 내용은 flow작성으로 대체 가능
- 일반 사용자들이 무료로 이용할 수 있음
- 모두가 언제나 장부를 조회할 수 있음
- AI 로보어드바이저가 매달 리포트를 작성해주어 자금 운용에 도움을 받을 수 있음
### 2.4. Service function
- 계좌 등록 (KB_API로 유효성 검사)
- KB_API를 이용하여 거래 내역 불러오기
- AI를 활용하여 거래 내역 자동 감사
- 영수증 첨부하기
- 익명으로 답글 남기기
- AI 로보어드바이저가 매달 리포트 작성하여 이메일 전송
- 데이터 자체 수정이 불가능함으로 flow형식으로 알아보기 쉽게 사유, 등 정정 가능
### 2.5. Competitiveness
- 시중에 나와있는 경리 프로그램들은 유료, 그리고 대기업, 중소기업을 타겟으로 함. 반면 greta는 무료, 누구나 영리적인 목적만 아니면 사용가능
- greta의 가장 큰 장점인 데이터 불가변성 때문에 타 프로그램과 달리 경리가 조작 불가능

## 3. Design
### 3.1. Prototype
![Prototype design1](https://raw.githubusercontent.com/StopDragon/greta-service-model/master/source/log_in_page.png)
<br>
![Prototype design2](https://raw.githubusercontent.com/StopDragon/greta-service-model/master/source/list.png)
<br>
![Prototype design3](https://raw.githubusercontent.com/StopDragon/greta-service-model/master/source/list%20menu.png)
<br>
![Prototype design4](https://raw.githubusercontent.com/StopDragon/greta-service-model/master/source/flow.png)

### 3.2. Color
![color_code](https://raw.githubusercontent.com/StopDragon/greta-service-model/master/source/color.png)
