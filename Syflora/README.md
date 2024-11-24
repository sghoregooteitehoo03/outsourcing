## Syflora
![앱 로고]()

관리자가 관리하는 꽃을 미리 사전주문 및 구매 하는 앱 제작을 진행하였습니다.

## 작업 기간
### 2024/09/07 ~ 2024/09/25

## 기능
**[사용자]**
- 부여받은 코드를 통한 로그인 기능  

- 상품 사전주문 및 구매 요청 기능

- 주문 현황에 따른 알림 기능


**[관리자]**
- 사전 주문에 따라 상품에 대한 정보를 전송하는 기능

- 고객이 구매확정한 상품에 대해 구매거절/입금확인 기능

- 관리자의 정보를 관리하는 기능

- 고객 정보를 추가/수정 관리하는 기능

- 상품을 추가하고 관리하는 기능

## 스크린샷
![스크린샷]()

## 아키텍쳐 및 라이브러리
- 아키텍처
   - MVVM 패턴: (View - ViewModel - Model)
   - [App Architecture 패턴](https://developer.android.com/topic/architecture/intro): (UI Layer - Domain Layer - Data Layer)
     
- Jetpack
  - ViewModel: UI의 상태값을 관리하며 UI의 이벤트들을 처리합니다.
  - Paging3: 로컬 데이터베이스나 네트워크에서 가져온 데이터를 페이징하여 데이터를 처리합니다.
  - Room: SQL 기능을 이용하여 앱 내 데이터베이스를 이용합니다.
  - Navigation: 화면 구성 및 화면전환에 관련된 다양한 기능을 제공합니다.
  - Compose: 기존의 XML레이아웃을 이용하지 않고, Kotlin 코드를 통해 UI 화면을 제작합니다.
  - [Hilt](https://dagger.dev/hilt/): 의존성 주입을 통해 보일러플레이트 코드를 줄여줍니다.

- Firebase
  - Firestore: Firebase에서 제공하는 NoSql 기반의 클라우드 데이터베이스를 이용할 수 있는 기능을 제공합니다.
  - Firebase Storage: 이미지/동영상을 저장 관리하도록 도와주는 저장소 입니다.
  - Firebase Cloud Messaging: 메시지를 안정적으로 무료 전송할 수 있는 크로스 플랫폼 메시징 솔루션입니다.
  - Firebase Functions: 사용자의 요청에 따른 백엔드 동작을 수행합니다.

- Coil: 네트워크로부터 이미지를 로드합니다.

- [ffmpeg-kti](https://github.com/arthenica/ffmpeg-kit): 비디오, 오디오 및 기타 멀티미디어 파일과 스트림을 처리하기 위한 라이브러리와 프로그램 모음 입니다.
