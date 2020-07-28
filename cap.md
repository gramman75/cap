# SAP Cloud Application Model
## 1. 소개

엔터프라이즈급 애플리케이션 개발을 위한 프레임웍

![overview](/image/overview.png)
가장 중요한 요소는 CDS로 모델링과 서비스 정의 언어이다. Entity와 서비스 Controller의 역할이라고 보면 된다.

### CDS를 이용하여 도메인설계에 집중.


![overview](/image/core-concepts.png)

위 그림에서 보면 맨 좌측의 역할을 CDS가 담당한다. Java개발로 보면 Entity, Controller/Service뿐만 아니라 UI를 위한 기본 마크업까지도 담당한다. 
맨 좌측은 Event Handlers는 Service영역에서 확장이 필요할 때 java나 nodejs로 해당 부분을 custom하게 개발하여 코드를 넣을 수 있다.

##### Core Data Services(CDS)
