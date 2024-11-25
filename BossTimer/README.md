## BossTimer
<img src='https://github.com/sghoregooteitehoo03/outsourcing/blob/main/BossTimer/image/icon.png' height="120" />

RPG 게임의 몬스터가 재생성 되는 시간을 설정하고 알림으로 알려주는 앱 제작을 진행하였습니다.

## 작업 기간
### 2024/08/21 ~ 2024/08/25

## 기능
- 몬스터의 재생성 되는 시간을 추가하고 관리합니다.  

- 몬스터의 재생성 되는 시간을 설정한 시간에 따라 주기적으로 업데이트 합니다.

- 몬스터를 그룹으로 묶어 관리할 수 있습니다.

- 기존에 있던 타이머 사이트에서 데이터를 가져와 목록에 표시합니다.

- 몬스터 재생성 시간 5분 전 사용자의 기기로 알림을 보내줍니다.  

- 몬스터 재생성 알림을 카카오톡 메시지를 통해 다른 사람들에게 공유합니다.  

- 사용자가 알림 메시지 내용을 설정하고 수정합니다.  

## 스크린샷
![스크린샷](https://github.com/sghoregooteitehoo03/outsourcing/blob/main/BossTimer/image/screenshot.png)

## 아키텍쳐 및 라이브러리
- 아키텍처
   - MVVM 패턴: (View - ViewModel - Model)
   - [App Architecture 패턴](https://developer.android.com/topic/architecture/intro): (UI Layer - Domain Layer - Data Layer)
     
- Jetpack
  - DataStore: 키-값 형태로 데이터를 저장할 수 있는 데이터 저장 솔루션입니다.
  - ViewModel: UI의 상태값을 관리하며 UI의 이벤트들을 처리합니다.
  - Navigation: 화면 구성 및 화면전환에 관련된 다양한 기능을 제공합니다.
  - Compose: 기존의 XML레이아웃을 이용하지 않고, Kotlin 코드를 통해 UI 화면을 제작합니다.
  - [Hilt](https://dagger.dev/hilt/): 의존성 주입을 통해 보일러플레이트 코드를 줄여줍니다.

- Firebase
  - Firestore: Firebase에서 제공하는 NoSql 기반의 클라우드 데이터베이스를 이용할 수 있는 기능을 제공합니다.
  - Firebase Cloud Messaging: 메시지를 안정적으로 무료 전송할 수 있는 크로스 플랫폼 메시징 솔루션입니다.

- [Jsoup](https://jsoup.org/): HTML 및 XML 작업을 간단하게 만드는 라이브러리로 데이터 파싱, 추출 등의 다양한 기능을 이용할 수 있습니다.

- [KakaoTalk](https://developers.kakao.com/):
   - 카카오톡 공유: 사용자가 카카오톡 친구에게 카카오톡 메시지를 보내는 기능을 제공합니다.

## API/Service
### [Kakao API](https://developers.kakao.com/)
### [Google Cloud Scheduler](https://cloud.google.com/scheduler/docs)
### [Cloud Run Functions](https://cloud.google.com/functions)
