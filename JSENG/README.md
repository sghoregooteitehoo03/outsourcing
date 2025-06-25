## JS ENG
<img src='https://github.com/sghoregooteitehoo03/outsourcing/blob/main/Syflora/image/logo.jpg' height="120" />

업무내역 작성/관리 및 엑셀 변환 앱 제작을 진행하였습니다.

## 작업 기간
### 2024/12/02 ~ 2024/12/22

## 기능
- 지정된 형식에 맞게 업무내역 작성

- 작성된 업무내역 수정/삭제 관리

- 업무내역 엑셀로 변환


## 스크린샷
![스크린샷](https://github.com/sghoregooteitehoo03/outsourcing/blob/main/Syflora/image/screenshot_1.png)  


## 아키텍쳐 및 라이브러리
- 아키텍처
   - MVVM 패턴: (View - ViewModel - Model)
   - [App Architecture 패턴](https://developer.android.com/topic/architecture/intro): (UI Layer - Domain Layer - Data Layer)
     
- Jetpack
  - ViewModel: UI의 상태값을 관리하며 UI의 이벤트들을 처리합니다.
  - Navigation: 화면 구성 및 화면전환에 관련된 다양한 기능을 제공합니다.
  - Compose: 기존의 XML레이아웃을 이용하지 않고, Kotlin 코드를 통해 UI 화면을 제작합니다.
  - [Hilt](https://dagger.dev/hilt/): 의존성 주입을 통해 보일러플레이트 코드를 줄여줍니다.

- Firebase
  - Firestore: Firebase에서 제공하는 NoSql 기반의 클라우드 데이터베이스를 이용할 수 있는 기능을 제공합니다.
  - Firebase Storage: 이미지/동영상을 저장 관리하도록 도와주는 저장소 입니다.

- Coil: 네트워크로부터 이미지를 로드합니다.

- [poi](https://github.com/apache/poi): 엑셀 파일을 쉽게 읽고 작성할 수 있습니다.
