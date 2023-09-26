---
layout: post
title: MalShorts - MalMacro_AutoExec_bat
subtitle: MalShorts
categories: Shorts
tags: [Shorts]
sidebar: []
---
### MalShorts : MalMacro_AutoExec_bat

### **멀웨어 정보**

SHA-256 : b4ccbe294a120cc87808328da43fe6cd3539704f61bdd73c83356552ba8a13f3

Feature : #macro #AutoExec_bat



### 주요 행위 및 분석가 한줄평

- 주요 행위
    - 엑셀 파일 열람 시 VBA매크로 자동 실행
    - 매크로를 통해 bat 파일 실행
        - `C:\Windows\Tasks\j.bat`
- 분석가 한줄평
    - 악성 bat파일이 자동 실행되도록 유도하는 매크로가 저장된 문서 파일



### **MARS Defender에서 추출한 위협 포인트**

![image-20230926-005806.png](/assets/images/MalShorts-MalMacro_AutoExec_bat/image-20230926-005806.png){:style="border:1px solid #eaeaea; border-radius: 7px; padding: 0px;" }


### **MARS Defender 탐지 내역**

![image-20230926-020313.png](/assets/images/MalShorts-MalMacro_AutoExec_bat/image-20230926-020313.png){:style="border:1px solid #eaeaea; border-radius: 7px; padding: 0px;" }


#### [MARSDefender 탐지 보고서(Link)](https://marsdefender.seculetter.com/?hash=b4ccbe294a120cc87808328da43fe6cd3539704f61bdd73c83356552ba8a13f3)