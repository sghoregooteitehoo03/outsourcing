## 와이오코리아
<img src='https://github.com/sghoregooteitehoo03/outsourcing/blob/main/Syflora/image/logo.jpg' height="120" />

음식점 별 상품을 발주 및 발주 상태 조회/관리하는 앱 제작을 진행하였습니다.

## 작업 기간
### 2025/03/20 ~ 2025/04/08

## 기능
**[사용자]**
- 부여받은 코드를 통한 로그인

- 상품 발주 요청

- 지점별 발주 기록 확인



- 발주 현황에 따른 알림

- 지정된 요일마다 발주 요청 알림


**[관리자]**
- 모든 지점별 발주 기록 관리

- 점주, 직원의 정보 추가/삭제 관리

- 상품을 추가하고 관리하는 기능

- 공지사항 관리 기능

- 발주 요청에 따른 명세서 전송 및 발주 상태 관리

- 발주 명세서 다운/엑셀 변환

## 스크린샷
### [사용자] ###
![스크린샷](https://github.com/sghoregooteitehoo03/outsourcing/blob/main/Syflora/image/screenshot_1.png)  


### [관리자] ###
![스크린샷](https://github.com/sghoregooteitehoo03/outsourcing/blob/main/Syflora/image/screenshot_2.png)


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
