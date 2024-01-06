---
title: "New Run"
property: "팀 프로젝트"
period: "2023/03/2 ~ 2023/06/12"
excerpt: "Android / Kotlin / Google Maps API / Retrofit2 / Flask / Stable Diffusion / GitHub / Notion / Postman"
header:
  image: /assets/images/newrun.png
  teaser: assets/images/newrun.png

---
### 🔗 Link

Source

Project : <a href = "https://github.com/agfalcon/lbs_newrun">https://github.com/agfalcon/lbs_newrun</a>



### 📖 상세 내용

<p align ="center">

<img src="\images\NewRun\EMB000023b46724.png" alt="앱 아키텍처" style="zoom: 100%;" />

<img src="\images\NewRun\EMB000023b46704.bmp" alt="앱 예제" style="zoom: 30%;" />  	<img src="\images\NewRun\EMB000023b46707.bmp" alt="앱 예제" style="zoom: 30%;" /> 	 <img src="\images\NewRun\EMB000023b4670a.bmp" alt="앱 예제" style="zoom: 30%;" />  	<img src="\images\NewRun\EMB000023b4670d.bmp" alt="앱 예제" style="zoom: 30%;" />   	<img src="\images\NewRun\EMB000023b46710.bmp" alt="앱 예제" style="zoom:30%;" />  	<img src="\images\NewRun\EMB000023b46713.bmp" alt="앱 예제" style="zoom: 30%;" />  	<img src="\images\NewRun\EMB000023b46716.bmp" alt="앱 예제" style="zoom: 30%;" />  	

</p>

<div style="display: flex; width: 100%; border-radius: 3px; background: rgb(251, 236, 221); padding: 16px 16px 16px 12px;"><div><div class="notion-record-icon notranslate" style="display: flex; align-items: center; justify-content: center; height: 24px; width: 24px; border-radius: 0.25em; flex-shrink: 0;"><div style="display: flex; align-items: center; justify-content: center; height: 24px; width: 24px;"><div style="height: 16.8px; width: 16.8px; font-size: 16.8px; line-height: 1; margin-left: 0px; color: black;"><img class="notion-emoji" alt="🐷" aria-label="🐷" src="data:image/gif;base64,R0lGODlhAQABAIAAAP///wAAACH5BAEAAAAALAAAAAABAAEAAAICRAEAOw==" style="width: 100%; height: 100%; background: url(&quot;/images/emoji/twitter-emoji-spritesheet-64.d3a69865.png&quot;) 18.6441% 89.8305% / 6000% 6000%;"></div></div></div></div><div style="display: flex; flex-direction: column; min-width: 0px; margin-left: 8px; width: 100%;"><div spellcheck="true" placeholder="내용을 입력하세요" data-content-editable-leaf="true" contenteditable="false" style="max-width: 100%; width: 100%; white-space: pre-wrap; word-break: break-word; caret-color: rgb(55, 53, 47); padding-left: 2px; padding-right: 2px; font-size: 16px"><span style="font-weight:600" data-token-index="0" class="notion-enable-hover">팀 프로젝트</span>로 진행된 프로젝트입니다. 달리기 애플리케이션 New run은 <span style="font-weight:600" data-token-index="2" class="notion-enable-hover">달리기를 진행하고 보상으로 달린 경로와 사용자가 원하는 키워드를 통해 이미지를 보상으로 주는 앱</span>입니다. 청소년들의 운동 부족 문제가 OECD 국가 중 가장 심각하여 가장 간단한 운동인 달리기와 예측하지 못한 보상에 흥미를 느끼는 가변 보상 효과를 접목하여 아이디어를 고안해냈습니다. 최신 기술인 Stable Diffusion에 이미지를 조건으로 주기 위해 Control Net 모델을 사용하였으며, 사용자는 여러 가지 기능을 통해 재밌게 달리기를 할 수 있습니다.</div></div></div>



### 🛠️ 사용 기술 및 라이브러리
<p style="font-size:16px;">
- Kotlin, Android<br>
- Google Maps<br>
- Retrofit2<br>
- kizitonwose<br>
- Firebase, Kakao SDK, Naver oauth<br>
- Figma, Postman, GitHub<br>
- Flask<br>
- Stable Diffusion & Control Net<br>
</p>


### 📱 담당한 기능(Android)
<p style="font-size:16px;">
- Figma를 활용하여 앱 디자인<br>
- 홈 화면 기능<br>
- 달리기 기능<br>
- Custom Calendar를 활용한 기록 기능<br>
- 전체 API 통신<br>
- 전체 아키텍처 설계<br>
</p>

### 📱 담당한 기능(Stable Diffusion API)
<p style="font-size:16px;">
- Control Net WEBUI 오픈소스를 API로 쓸 수 있게 변경<br>
- Flask Server를 통한 이미지 생성 API 기능
</p>

### 그 외
<p style="font-size:16px;">
- 데이터베이스 스키마 설계
</p>



### 💡 고민한 점
<p style="font-size:14px;">
- 달리기 기능에서 백그라운드에서 지속적으로 gps 정보를 받아서 연산 처리가 필요하여 Service를 도입. Background Service의 생명주기에 대해 이해하였고, command에 따라 service의 동작을 제어하는 것을 경험함.<br>
- Service에서 연산 처리한 데이터를 액티비티에서 활용할 필요가 있었음. 4대 컴포넌트 중 하나인 Broadcase Receiver의 동작에 대해 이해하고 이를 통해 서비스에서 다양한 액티비티와 통신할 수 있도록 구현.<br>
- 달리기 데이터에 대한 처리를 위해 서버 담당자와 많은 고민을 함. 경로 데이터에 대한 처리를 DB에서 제공하는 공간 데이터 활용 및 안드로이드에서는 경로 좌표를 제공받지 않고 경로 이미지로 받아서 처리할 수 있도록 구현<br>
- Stable Diffusion 모델이 너무 커서 클라우드 서버에 넣을 수 없는 문제 발생. Stable Diffusion 구동 웹 서버를 통해 이미지를 생성할 수 있도록 하고 이를 flask 서버에서 요청하고 앱으로 전달할 수 있도록 구현.<br>
</p>