## 안전보건관리체계
<img src='https://github.com/sghoregooteitehoo03/outsourcing/blob/main/%EC%A2%8B%EC%9D%80%EA%B8%80%EC%93%B0%EA%B8%B0/image/logo2.png' height="120" />

사용자들에게 다양한 좋은 글귀, 동영상, 문서양식 등을 공유하는 앱을 제작하였습니다.

## 다운로드
<a href='https://play.google.com/store/apps/details?id=com.sg.sharearticle'><img alt='다운로드하기 Google Play' src='https://play.google.com/intl/en_us/badges/static/images/badges/ko_badge_web_generic.png' height="80"/></a>

## 작업 기간
### 2025/01/09 ~ 2025/01/31

## 기능
**[사용자]**
- 구글, 카카오 로그인 기능

- 게시글 공유 및 이미지 저장 기능

- 댓글, 좋아요 소셜 기능

- 지역별 날씨 확인 기능

- 게시글 업로드 알림 기능


**[관리자]**
- 게시글 작성/수정/삭제 관리 기능

- 게시글 알림 설정 기능


## 스크린샷
### [사용자] ###
![스크린샷](https://github.com/sghoregooteitehoo03/outsourcing/blob/main/Syflora/image/screenshot_1.png)  


### [관리자] ###
![스크린샷](https://github.com/sghoregooteitehoo03/outsourcing/blob/main/Syflora/image/screenshot_2.png)


## 아키텍쳐 및 라이브러리
- 아키텍처
   - MVVM 패턴: (View - ViewModel(UI State, UI Event) - Model)
   - [App Architecture 패턴](https://developer.android.com/topic/architecture/intro): (UI Layer - Domain Layer - Data Layer)
     
- Jetpack
  - ViewModel: UI의 상태값을 관리하며 UI의 이벤트들을 처리합니다.
  - Paging: 로컬 데이터베이스나 네트워크에서 가져온 데이터를 페이징하여 데이터를 처리합니다.
  - Room: SQL 기능을 이용하여 앱 내 데이터베이스를 이용합니다.
  - Navigation: 화면 구성 및 화면전환에 관련된 다양한 기능을 제공합니다.
  - Compose: 기존의 XML레이아웃을 이용하지 않고, Kotlin 코드를 통해 UI 화면을 제작합니다.
  - [Hilt](https://dagger.dev/hilt/): 의존성 주입을 통해 보일러플레이트 코드를 줄여줍니다.
  - Splash: Splash 화면을 구현합니다.

- Firebase
  - Firestore: Firebase에서 제공하는 NoSql 기반의 클라우드 데이터베이스를 이용할 수 있는 기능을 제공합니다.
  - Firebase Storage: 이미지/동영상을 저장 관리하도록 도와주는 저장소 입니다.
  - Firebase Cloud Messaging: 메시지를 안정적으로 무료 전송할 수 있는 크로스 플랫폼 메시징 솔루션입니다.
  - Firebase Functions: 사용자의 요청에 따른 백엔드 동작을 수행합니다.
  - Firebase Authentication: 앱에서 사용자 인증 시 필요한 백엔드 서비스와 사용하기 쉬운 SDK, 기성 UI 라이브러리를 제공합니다.

- [Coil](https://github.com/coil-kt/coil), [Picasso](https://github.com/square/picasso): 네트워크로부터 이미지를 로드합니다.

- [Retrofit](https://github.com/square/retrofit): Android 및 Java를 위한 HTTP 클라이언트입니다.

- [Kakao](https://developers.kakao.com/):
   - 카카오톡 공유: 사용자가 카카오톡 친구에게 카카오톡 메시지를 보내는 기능을 제공합니다.
   - 카카오톡 로그인: 카카오계정을 통한 빠르고 간편한 사용자 로그인 기능입니다.

- Custom Views
  - [compose-shimmer](https://github.com/valentinilk/compose-shimmer): Jetpack Compose에 shimmer 효과를 제공합니다.
  - [android-youtube-player](https://github.com/PierfrancescoSoffritti/android-youtube-player): Android용 Youtube Player View입니다.
  - [Zoomable](https://github.com/usuiat/Zoomable): 이미지 확대/축소 효과를 제공합니다.
