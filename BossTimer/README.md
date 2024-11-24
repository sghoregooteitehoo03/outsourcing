## BossTimer
![그래픽 이미지]()

RPG 게임의 몬스터가 재생성 되는 시간을 설정하고 알림으로 알려주는 앱 입니다.

## 작업 기간
### 2024/08/21 ~ 2024/08/25

## 기능
- 침착맨님의 다양한 유튜브 채널과 그동안 출연한 모든 영상들을 간편하게 찾아볼 수 있습니다.  

- 침착맨님의 현재 방송 여부뿐만 아니라, 배도라지 크루 멤버들의 트위치 방송도 함께 확인하고 손쉽게 시청하실 수 있습니다.

- 이말년 작가로 활동하던 시기에 네이버에서 연재된 웹툰을 한데 모아 쉽게 즐길 수 있습니다.

- 침착맨님의 팬카페의 다양한 게시글을 카테고리별로 편리하게 탐색하며, 침하하와 함께 즐겨보세요.

- 침착맨님의 다양한 굿즈에 대한 정보를 확인하고, 마음에 드는 굿즈를 찾아보세요.

- 유튜브 영상을 시청하다가 이어보고 싶은 부분이나 특별한 순간이 있다면, 해당 앱으로 손쉽게 공유하고 북마크를 만들어 콘텐츠를 더욱 편리하게 즐겨보세요.

## 스크린샷
![스크린샷]()

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
