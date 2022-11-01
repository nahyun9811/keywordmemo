## 키워드 정리



## WPF 란?


## 윈도우 프레젠테이션 파운데이션 (Windows Presentation Foundation)
윈도우 기반 응용프로그램에서 사용자 인터페이스를 표시하기 위한 목적으로 
마이크로소프트에서 만든 그래픽 서브시스템이다. 과거 아발론(Avalon)이라는 코드명으로 불렸으며 최초에 닷넷 프레임워크 3.0의 일부분으로 발표되었으며, 
기존의 그래픽 장치 인터페이스 대신 DirectX를 사용한다. 
WPF는 응용프로그램 개발을 위한 일관성 있는 프로그래밍 모델을 제공하며 사용자 인터페이스와 비즈니스 로직을 분리해준다. 
XUL이나 SVG와 같은 XML 기반 객체 모델과 유사하다.

WPF는 다양한 인터페이스 요소들을 정의하고 연결하기 위해 XML 기반의 언어인 XAML을 채용하였다. 
WPF 응용프로그램은 데스크탑에서 단독으로 실행될 수도 있고 웹사이트에 내장된 객체로 서비스될 수도 있다. 
WPF는 2D/3D 렌더링, 고정 및 가변 문서, 타이포그래피, 벡터 그래픽스, 실시간 애니메이션, 프리렌더링 미디어와 같은 여러 가지 보편적인 사용자 인터페이스들을 통합하는 것을 목적으로 한다. 
이러한 요소들은 다양한 이벤트, 사용자 인터랙션, 그리고 데이터 바인딩에 기반하여 연결 및 처리될 수 있다.

WPF 런타임 라이브러리는 윈도우 비스타 및 윈도우 서버 2008부터 모든 버전의 마이크로소프트 윈도우에 기본적으로 포함되어 있다. 
윈도우 XP SP2/SP3 및 윈도우 서버 2003 사용자는 필요한 라이브러리를 선택적으로 설치할 수 있다.

마이크로소프트 실버라이트는 어도비 플래시와 유사한 내장 웹 컨트롤들을 제공하며 이는 대부분 WPF의 일부분에 해당한다. 3D 실시간 렌더링은 실버라이트 5 버전부터 제공되었다.

## XAML
## 확장 응용 프로그램 마크업 언어(Extensible Application Markup Language)
XAML([zæ:mɛl])로 발음)은 마이크로소프트사가 구조값과 객체를 초기화하는 데 사용하려고 만든 선언형 XML 기반 언어이다. 마이크로소프트사의 Open Specification Promise를 통해 사용할 수 있다.[3] XAML은 원래 윈도우 프레젠테이션 파운데이션의 코드 이름이기도 했던 Avalon에서 따와서 "eXtension Avalon Markup Language"를 대표하는 말이었다.[4]

## 레이아웃(Layout)' 이란 

'배치'라는 뜻으로, HTML 태그로 감싸진 각 정보 요소를 화면상의 어느 위치에 어떻게 자리잡을지를 결정하는 것을 말합니다.



## 1. Canvas

모눈종이.
Canvas의 자식 요소는 크기가 조정되지 않고 지정된 좌표에 배치된다.

Canvas 크기가 달라져도 안의 요소의 크기는 변하지 않는다.

굉장히 자유도가 높은 컨트롤이다.

![Canvas](https://user-images.githubusercontent.com/116422740/198871088-2dcde0ce-59ed-4d63-a719-79befdea4025.JPG)

![Canvas2](https://user-images.githubusercontent.com/116422740/198871091-9cb71d6f-e011-4926-9bdd-c951715f7cfd.JPG)

## 2. DockPanel

Dock 속성을 사용하여 자식이 생긴 순서대로 위치를 정한다.

같은 코드라도 순서를 바꾸면 위치가 달라질 수 있다.

![DockPanel](https://user-images.githubusercontent.com/116422740/198871245-7975c0f3-57ae-410e-a574-1846b3344033.JPG)

![DockPanel2](https://user-images.githubusercontent.com/116422740/198871250-651921cf-5ecf-44f0-beef-d3a6afbc457b.JPG)

버튼 순서를 변경해봤다.

![DockPanel3](https://user-images.githubusercontent.com/116422740/198871373-d93c5548-53df-4147-8a79-b9b42d33de02.JPG)

![DockPanel4](https://user-images.githubusercontent.com/116422740/198871379-a1816183-96c7-4f38-8c58-f10466a674e5.JPG)


## 3. Grid

표 형식의 패널. 가장 많이 사용되는 레이아웃이다.

열과 행을 정의하고 공간의 비율에 따라 배분할 수 있다.

![Grid](https://user-images.githubusercontent.com/116422740/198871445-e7dc3fd4-83e7-4b19-923b-41fb91392580.JPG)

![Grid2](https://user-images.githubusercontent.com/116422740/198871451-86da750e-0cf7-4e70-bed8-e556c9b2456b.JPG)

## 4. StackPanel

자식 요소를 행이나 열로 간단하게 나열할 때 사용하는 컨트롤.

Orientation 속성을 사용해서 나열할 방향을 정할 수 있다.

![StackPanel](https://user-images.githubusercontent.com/116422740/198871629-c50afd41-59a7-4615-a813-62565f3c2d76.JPG)

![StackPanel2](https://user-images.githubusercontent.com/116422740/198871632-01d5bebd-dbbf-4921-b04c-6762f6ba3b49.JPG)

![StackPanel3](https://user-images.githubusercontent.com/116422740/198871639-b15ca922-1afc-4c76-afbd-272fee914e87.JPG)

![StackPanel4](https://user-images.githubusercontent.com/116422740/198871648-c390a91d-c6a8-4cd4-8230-5668e079b4bb.JPG)

## 5. WrapPanel

자식 요소들의 크기가 작을 때는 StackPanel과 같은 역할을 하지만,

자식 요소들의 크기가 WrapPanel크기를 넘어가면 다음 줄에 배치한다.

![WrapPanel](https://user-images.githubusercontent.com/116422740/198871795-79576e29-f09e-4c2a-a25d-dc6161621a5b.JPG)

![WrapPanel2](https://user-images.githubusercontent.com/116422740/198871802-2b416f93-1253-4c8a-bd52-5f087e7bb74e.JPG)

![WrapPanel3](https://user-images.githubusercontent.com/116422740/198871806-885c7625-9768-40ab-a174-14e131ae0511.JPG)

![WrapPanel4](https://user-images.githubusercontent.com/116422740/198871809-6f4e2da8-53e8-47a7-8c09-ea913060b3ba.JPG)



