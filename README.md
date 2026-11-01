<div align="center">
  <img src="./assets/header.svg" width="100%" alt="YJ Game Client Developer — 게임의 입력과 흐름을 시스템으로 연결하다." />
</div>

<p align="center">
  <strong>이유정 | Game Client Developer</strong><br/>
  Unity 2D 프로젝트와 Unreal Engine 팀 프로젝트에서 게임플레이 흐름, 인터랙션, 사용자 입력과 데이터 연동을 구현했습니다.
</p>

<p align="center">
  <a href="https://github.com/YjLee221/Pencil2Diamond">Pencil2Diamond GitHub</a>
  &nbsp;·&nbsp;
  <a href="https://youtu.be/p8ovjJP-HN0">Taxi Driver 시연</a>
  &nbsp;·&nbsp;
  <a href="https://www.youtube.com/watch?v=fnKinP_DIwg">Magic School 시연</a>
</p>

## Selected Projects

### 01 · Pencil2Diamond — Unity / C#

<a href="https://github.com/YjLee221/Pencil2Diamond"><img src="./assets/pencil2diamond.svg" width="100%" alt="Pencil2Diamond: Unity 6 C# 모바일 2D 개인 프로젝트, 개발 중. 작업 흐름을 표현한 일러스트"/></a>

**개인 프로젝트 · 개발 중 · Android 목표**

연필 깎기 → 흑연 추출 → 온도 조절 프레스 → 다이아몬드 획득·판매로 이어지는 2D 제작 게임입니다. 튜토리얼 명령·이벤트 처리, 공방 작업 UI, 연필 상점의 목록·구매 흐름을 구현하고 있습니다.

**핵심 구현:** TSV 데이터 기반 튜토리얼 · C# 이벤트 기반 단계 전환 · ScriptableObject 데이터 · 공통 수량 선택 UI · 상점 ViewData

**현재 범위:** 튜토리얼의 제작·판매 흐름과 메인 공방·상점 기본 기능을 연결했습니다. 반복 제작·자원 소비·보상 통합, 저장/불러오기, Android 빌드 검증은 개발 중입니다.

[소스 코드](https://github.com/YjLee221/Pencil2Diamond/tree/develop) · [구현 현황 README](https://github.com/YjLee221/Pencil2Diamond/blob/develop/README.md) · [이슈 및 개발 기록](https://github.com/YjLee221/Pencil2Diamond/issues)

### Unreal Engine 5 · Team Projects

<table>
  <tr>
    <td width="50%" valign="top">
      <a href="https://youtu.be/p8ovjJP-HN0"><img src="./assets/taxi-driver.svg" width="100%" alt="Taxi Driver in Paris: Unreal Engine 5, C++ 기반 2인 팀 프로젝트, 팀장. 시스템 흐름 일러스트"/></a>
      <br/><strong>Taxi Driver in Paris</strong><br/>
      <sub>2인 팀 · 팀장 · C++ / Blueprint</sub>
      <p>플레이어·AI 차량의 공통 베이스 구조, Chaos Vehicle 주행 및 Spline 경로 추종, 주행 HUD를 구현했습니다.</p>
      <a href="https://youtu.be/p8ovjJP-HN0">시연 영상</a>
    </td>
    <td width="50%" valign="top">
      <a href="https://www.youtube.com/watch?v=fnKinP_DIwg"><img src="./assets/magic-school.svg" width="100%" alt="Magic School: Unreal Engine 5, Blueprint 기반 2인 팀 프로젝트, 팀원. 상호작용 구조 일러스트"/></a>
      <br/><strong>Magic School</strong><br/>
      <sub>2인 팀 · 팀원 · Blueprint / Niagara</sub>
      <p>시선 기반 대상 감지, 인터페이스를 통한 오브젝트 상호작용, 서랍 기믹과 시각 효과를 작업했습니다.</p>
      <a href="https://www.youtube.com/watch?v=fnKinP_DIwg">시연 영상</a>
    </td>
  </tr>
</table>

## Implementation Highlights

| 영역 | 구현 내용 | 코드 근거 |
|:---|:---|:---|
| Tutorial Flow | 대화 명령, 미니게임 완료 이벤트, 성공·실패에 따른 단계 전환 | [TutorialFlowController.cs](https://github.com/YjLee221/Pencil2Diamond/blob/develop/Assets/Script/Flow/TutorialFlowController.cs) |
| Press Interaction | 드래그 각도를 온도로 변환하고 허용 오차로 결과 판정 | [SettingTemperature.cs](https://github.com/YjLee221/Pencil2Diamond/blob/develop/Assets/Script/Tool/SettingTemperature.cs) |
| Shop / Inventory | 구매 수량·잔액 확인, 인벤토리 수량 변경, 화면 표시 데이터 | [MainMarketController.cs](https://github.com/YjLee221/Pencil2Diamond/blob/develop/Assets/Script/Flow/MainMarketController.cs) |

## Tech Stack

| 분류 | 기술 |
|:---|:---|
| **Game Engine** | Unity 6 (2D), Unreal Engine 5 |
| **Programming** | C#, C++, Blueprint |
| **Gameplay / UI** | Unity uGUI, TextMeshPro, C# events, ScriptableObject, Unreal Chaos Vehicles, Niagara |
| **Workflow** | Git, GitHub, 기능 브랜치·PR·이슈 기반 개발 기록 |

---

<sub>실제 구현 여부와 검증 상태는 각 프로젝트 설명에서 구분했습니다. 위 프로젝트 커버는 게임 플레이 화면이 아닌 설명용 시스템 일러스트입니다.</sub>
