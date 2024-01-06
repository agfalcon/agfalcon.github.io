---
title: "MeetMeet"
property: "네이버 부스트 캠프 8기 프로젝트"
period: "2023/11/06 ~ 2023/12/15"
excerpt: "Android / Kotlin / Custom Calendar / Retrofit2 / MVVM / Hilt / Material3 / Room / DataStore  FCM / Jetpack navigation / Moshi / WorkManager / AlarmManger"
header:
  image: /assets/images/meetmeet.png
  teaser: assets/images/meetmeet.png
---
### 🔗 Link
Source

Project : <a href = "https://github.com/boostcampwm2023/and08-meetmeet">https://github.com/agfalcon/lbs_newrun</a>


### 📖 상세 내용

|달력|팔로우|일정초대|알림|피드|
|:---:|:---:|:---:|:---:|:---:|
|<img width="200" height="430" src="https://github.com/boostcampwm2023/and08-meetmeet/assets/97400357/8336fca3-03aa-47cf-ae59-268aef2d7302"/>|<img width="200" height="430"  src="https://github.com/boostcampwm2023/and08-meetmeet/assets/97400357/bf22c572-a0a5-4c6b-84d6-a28df9980d4d"/>|<img width="200" height="430" src="https://github.com/boostcampwm2023/and08-meetmeet/assets/97400357/92d685c7-8da5-4de4-bfe0-6b11260ac884"/>|<img width="200" height="430" src="https://github.com/boostcampwm2023/and08-meetmeet/assets/97400357/2892e3b0-33f5-4462-b9ff-3eb61fb84735"/>|<img width="200" height="430" src="https://github.com/boostcampwm2023/and08-meetmeet/assets/97400357/960fed3c-8a8e-4886-bc59-a3622a1e6b91"/>|


<div style="display: flex; width: 100%; border-radius: 3px; background: rgb(251, 236, 221); padding: 16px 16px 16px 12px;"><div><div class="notion-record-icon notranslate" style="display: flex; align-items: center; justify-content: center; height: 24px; width: 24px; border-radius: 0.25em; flex-shrink: 0;"><div style="display: flex; align-items: center; justify-content: center; height: 24px; width: 24px;"><div style="height: 16.8px; width: 16.8px; font-size: 16.8px; line-height: 1; margin-left: 0px; color: black;"><img class="notion-emoji" alt="🐷" aria-label="🐷" src="data:image/gif;base64,R0lGODlhAQABAIAAAP///wAAACH5BAEAAAAALAAAAAABAAEAAAICRAEAOw==" style="width: 100%; height: 100%; background: url(&quot;/images/emoji/twitter-emoji-spritesheet-64.d3a69865.png&quot;) 18.6441% 89.8305% / 6000% 6000%;"></div></div></div></div><div style="display: flex; flex-direction: column; min-width: 0px; margin-left: 8px; width: 100%;"><div spellcheck="true" placeholder="내용을 입력하세요" data-content-editable-leaf="true" contenteditable="false" style="max-width: 100%; width: 100%; white-space: pre-wrap; word-break: break-word; caret-color: rgb(55, 53, 47); padding-left: 2px; padding-right: 2px; font-size: 16px"><span style="font-weight:600" data-token-index="0" class="notion-enable-hover">네이버 부스트 캠프 웹·모바일 8기</span>에서 진행한 팀 프로젝트입니다. 애플리케이션 MeetMeet은 <span style="font-weight:600" data-token-index="2" class="notion-enable-hover">일정을 관리하고 일정에 초대하고 추억을 공유할 수 있는 소셜 기반 캘린더 앱</span>입니다. 팔로우를 통해 친구의 달력에 방문하고 친구의 일정에 참여할 수 있습니다. 함께 공유하는 일정에 대해 사진, 동영상을 담은 피드를 올려서 함께 추억을 공유할 수 있습니다.</div></div></div>



### 🛠️ 사용 기술 및 라이브러리

| 분류                    | Stack                                                      |
|:-----------------------:|:----------------------------------------------------------:|
| App Architechture       | Google Recommended app architecture                        |
| Design Pattern          | MVVM                                                       |
| DI                      | Hilt                                                       |
| UI                      | XML, Material3                                             |
| Local Storage           | Room, DataStore                                            |
| Network                 | Retrofit2, OkHttp3                                         |
| App publishing          | Firebase App distribution                                  |
| Image Loading           | Glide                                                      |
| Video Loading           | Media3, ExoPlayer                                          |
| Service                 | Kakao Login api, Firebase Cloud Messaging                  |
| navigation              | jetpack navigation                                         |
| serializer/deserializer | Moshi                                                      |
| Asynchronous            | Coroutines, Flow                                           |
| Background              | WorkManger, AlarmManager                                   |
| Notification            | NotificationManager                                        |
| Media                   | Download Manager, MediaStore, ContentResolver, PhotoPicker |

### 📱 담당한 기능(기획)
<p style="font-size:16px;">
- 프로젝트 주제 기획<br>
- 개발 프로세스<br>
- 코딩 컨벤션 규칙 정의<br>
- 프로젝트 백로그 정의<br>
</p>

### 📱 담당한 기능(Android)
<p style="font-size:16px;">
- Figma를 활용하여 앱 디자인<br>
- Custom 캘린더<br>
- 알림 기능(일정 알림, 초대, 팔로우)<br>
- 피드 자세히 보기 및 다운로드<br>
- 카카오 로그인<br>
- 일정 스토리 및 일정 멤버 관리 기능<br>
- 일정 수정, 삭제 기능<br>
</p>



### 💡 고민한 점
<p style="font-size:14px;">
- 개발 기간이 짧은 반면에 구현하고 싶은 기능이 많아서 기획 상에 많은 기능을 가지고 시작. 일관된 코드를 유지하되 좀 더 빠른 개발 속도가 필요함. 팀원들과 개발 프로세스를 개선하는 노력을 하면서 모닝 리뷰, 페어 프로그래밍을 진행하면서 개발 속도를 올릴 수 있었음.<br>
- 성과 : 안드로이드 팀 중 가장 많은 코드 작성. 백로그 닫히는 그래프가 유의미하게 상승 곡선을 보여줌.
- 소셜 기반 캘린더 앱이지만 오프라인에서 달력 기능을 제공하고 싶었음. 동기화에 대한 문제에 대해 많은 토의와 고민을 함. 다중 로그인을 지원하기 때문에 동기화가 매우 힘들었음. 일정을 보여주는 것 외에 수정, 삭제를 막고 추후에 Caldev 프로토콜 동기화 방법을 사용하기로 결정.
- 타임존이 다를 때 마다 일정이 모두 다른 시간으로 생성이 되는 문제가 있었음. 어떤 나라에서 일정을 생성하든 일관된 일정을 공유할 수 있어야 하여 앱에서 EpohMilli를 사용하여 일정을 관리하고 이를 타임존에 맞게 UI에 보여줄 수 있는 자체 Extension을 정의하여 관리.
- 오프라인에서 일정 알람을 제공할 경우 알람이 누락되는 경우가 다양하게 나타남. AlarmManager에서 2가지의 알람을 등록하여 주기적으로 알람을 동기화하여 새로 등록하는 알람과 시간에 맞게 알림을 제공하는 알람을 통해서 누락되는 알람이 없도록 구현.
</p>