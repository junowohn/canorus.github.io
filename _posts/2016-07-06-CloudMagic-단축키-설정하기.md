---
layout: post
title: CloudMagic 단축키 설정하기
---

![](/Resources/2016-07-06/CloudMagic.png)



2015년이 지나가고 2016년이 시작되던 무렵, Spark의 맥용 버전을 기다리다가 MagicCloud Email을 접했습니다. 막 iPad 용 Spark의 베타버전이 공개되던 무렵이었고 맥용 버전의 공개도 기대되던 시점이었죠. 일주일 간 iPhone과 iPad에서 Spark와 비교해보고 주저없이 CloudMagic을 선택했습니다. 지금까지도 이 선택을 후회하지 않습니다. 무엇보다도 OSX과 iOS에서 같은 앱을 쓴다는 것은 동기화에서 어마어마한 장점을 가져오니까요.



다만 OSX용에서 한 가지 문제점에 봉착했는데 바로 키보드 단축키가 간간이 작동하지 않는다는 것이었습니다. 원칙적으로 Shift+u를 누르면 읽음/읽지 않음 상태로 전환해주어야 하는데 이게 안정적으로 작동하지 않았다는 것이죠.



약 반 년을(!) 미루다가 어제 저녁에 지원팀에 메일을 보냈습니다. 새벽 2시까지 메일을 주고 받다가 문제의 원인을 찾았습니다. *입력기가 한글 상태로 놓였을 때에는 단축키가 작동하지 않는다*는 것이었지요.



지원팀에 단축키를 입력기와 상관없이 작동하도록 해달라 라는 요청을 하였고 긍정적으로 검토하겠다 라는 답변을 받았습니다. 그 때까지 목마른 사람이 우물을 판다고 임시로 단축키를 설정해서 쓰기로 하였습니다.



1. 설정.app -> 키보드 -> 단축키 -> App 단축키로 가서 선택 상자 아래 쪽의 + 버튼을 눌러줍니다.  
![](/Resources/2016-07-06/keyboard.png)

2. 응용프로그램에서 CloudMagic Email을 선택합니다.  
![](/Resources/2016-07-06/selectapp.png)

3. 메뉴 제목에는 `읽음/읽지 않음 표시`라고 입력하고 키보드 단축키에는 본인이 원하는 단축키를 지정합니다. 저는 cmd + shift + r 로 지정했습니다.  
![](/Resources/2016-07-06/kor.png)

   - 언어가 영문 상위이신 분은 `Mark as Read / Unread`로 입력하시면 됩니다![](/Resources/2016-07-06/eng.png)
   - 영문이든 한글이든 대소문자, 띄어쓰기까지 완전히 준수하셔야 합니다. 특히 영문 R과 U가 대문자인 것과 `/` 좌우에 띄어쓰기가 있다는 점을 유념해주세요.
   - CloudMagic에서 읽음/읽지 않음 표시의 기본 단축키는 Shift + u 입니다만 시스템 단축키에서 지정할 때에는 Shift만 사용하는 것은 허용되지 않는 것 같습니다. cmd나 ctrl 또는 option을 넣어서 단축키를 지정해주세요.

   ​