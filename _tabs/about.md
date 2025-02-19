---
# the default layout is 'page'
icon: fas fa-info-circle
order: 1
---
> 안녕하세요. 끊임없이 실험하며 성장하는 개발자, Lawon562입니다.

## 소개

- 강사로 시작해 비전공자와 원활하게 소통할 수 있는 개발자입니다.
> 비전공자와 소통하며 개발 개념을 쉽게 전달하는 능력을 바탕으로, 프로젝트 관계자와 원활하게 협력해 시스템을 개선합니다.

- 모바일 게임 개발과 다양한 SDK 기능 연동 및 관리를 담당하고 있습니다.
> AOS/iOS 빌드 관리, Game Analytics와 Firebase SDK를 활용한 데이터 분석 및 지표 개선 경험이 있습니다.
> 제작한 기능을 플러그인으로 패키징하여 여러 프로젝트에 재사용할 수 있도록 최적화했습니다.

- 품질이 높고 유지보수하기 쉬운 프로그램을 만드는 것에 관심이 많습니다.
> 프로젝트 관계자들과 적극적으로 소통하며, 코드 품질과 사용자 경험 개선을 주도하고 있습니다.

---

## 기술 스택
- **C#**
  - 객체지향 프로그래밍 원칙을 이해하고 활용할 수 있습니다.
  - Unity에서 인터페이스 및 컴포넌트 기반 구조를 활용하여 개발할 수 있습니다.
  - 효율적인 코드 구조와 재사용성을 고려한 설계를 할 수 있습니다.
- **Unity** 
  - Profiler를 통해 성능 최적화가 가능합니다.
  > 오브젝트 활성화 과정을 최적화해 60ms까지 나타나던 성능 스파이크를 8ms로 줄여 해결한 경험이 있습니다.
  - 이벤트 시스템 및 커스텀 인터페이스를 활용한 유연한 기능 구현이 가능합니다.
  - 게임 오브젝트의 상태 관리, 애니메이션, UI 상호작용을 효과적으로 제어할 수 있습니다.
- **Git**
  - Git Bash 및 CLI(Command Line Interface)를 활용하여 프로젝트를 효율적으로 관리할 수 있습니다.
  - GitHub, GitLab을 이용한 협업 경험이 있으며, PR 및 코드 리뷰 프로세스를 진행할 수 있습니다.
- **AWS**
  - AWS EC2와 Elastic IP Address를 활용하여 웹/앱 데이터 서버를 구축하고, 9개월간 운영했었습니다.
  > 고화질 사진의 빠른 로딩(0.1초 내)을 구현하여 사용자 경험을 개선했습니다.


---

## 진행했던 프로젝트

![Desktop View](/assets/img/profile/awesome_park_idle_game.png)
{: width="256" height="256" .normal}
### Awesome Park : Idle Game
  **테마 파크를 주제로 방치형 아케이드 게임 개발**
  ( [**플레이 스토어**](https://play.google.com/store/apps/details?id=com.Albus.AwesomePark) | 
  [**앱 스토어**](https://apps.apple.com/kr/app/awesome-park-idle-game/id6482050793) )  
  **역할**: 전체적인 게임 시스템 개발과 서브 기획  
  * Android / iOS 앱 릴리즈 및 지속적인 업데이트 관리  
  * 데이터 분석 SDK 연동 및 사용자 데이터를 기반으로 한 개선 작업 진행  
  > Firebase와 Game Analytics를 활용해 유저 이탈 구간을 분석하고, 재기획 및 구현, 개선을 통해 이탈률을 **22%**에서 **약 8.5%**로 줄였습니다.  
  **(약 63% 개선)**
  * 다양한 코어 루프 및 서브 루프 테스트를 통해 유저 경험 개선  
  > 스테이지 후반부에서 굿즈샵과 굿즈 관리 시스템을 도입해 해당 구간의 이탈률을 **14%**에서 **8%**로 줄임.  
  **(약 43% 개선)**
  * 프로젝트 관계자 일정 조율, 리소스 요청/적용 및 확인
    
---

### Dimension Archer
  **MR 환경에서 벽을 부수고 몰려오는 적들을 막는 캐주얼 로그라이크 아처 게임 개발.**  
  **역할**: 전체 시스템 개발과 서브 기획
  * Quest 3의 "First Encounter"를 참고하여 게임 기획 및 시스템 설계
  * Scene Load Manager를 구현하여 시점을 세분화(로딩 전, 로딩 중, 게임 진입, 업그레이드 선택 등)
  * MR 환경에서 사용자 동작을 난이도에 반영하여 몰입감을 강화
  > Easy mode: 활시위만 당겨도 자동 장전  
  > Normal mode: 화살통에서 화살을 꺼내 활시위에 장전  
  > Hard mode: 장전 각도가 맞지 않으면 화살이 정상적으로 발사되지 않으며, 데미지가 감소  
  * MR 어플리케이션 개발 과정을 팀과 공유하고 문서화하여 이후 MR 프로젝트 협업의 기본 템플릿 생성
  
---

### MR Home
  **XR 기기에서 표시되는 기본 홈 환경 앱 제작**  
  **역할**: 전체 시스템 개발
  * 서랍 UI와 문 개방 등 다양한 상호작용 시스템을 구현하여 몰입감 있는 환경 제공
  * 미팅 룸, 미디어 콘텐츠 감상 공간 등 다양한 가상 환경을 제작하여 사용자 경험을 확장
    
---

### 기타 프로젝트 경험
  - 광고 설정 및 SDK 핸들러 구현을 통해 수익 모델을 개선하고 사용자 이슈를 해결했습니다.
  > 특정 광고 SDK의 **사운드 뮤트 현상 문제를 해결**하여 오디오 초기화 시 발생하던 **스파이크(평균 120ms) 제거**
  > Bright SDK 핸들러 생성: iOS에서만 동작하는 Bright Data SDK를 제어하는 핸들러를 작성하여 여러 프로젝트에 적용
  - 사내 다른 프로젝트 개발 지원(**Water Park Boys**, **Roller Disco!**)
