# EXP — 2024 ExP makE Summer Game Jam

> '길건너 친구들 (Crossy Road)' 의 축소 버전 컨셉으로, 다리·차량·캐릭터를 조합한 캐주얼 액션 게임. 홍익대학교 게임 개발 동아리 **ExP makE** 의 2024 여름 게임잼에 팀으로 참여하여 **단 24 시간 안에 완성** 했습니다.

---

## Game Overview

- **장르** — 캐주얼 액션 (Crossy Road 류)
- **개발 기간** — 24 시간 (2024 ExP makE 서머 게임잼)
- **플랫폼** — PC (Unity)
- **팀** — 홍익대학교 게임 개발 동아리 ExP makE

## My Role — 개발 담당

- 게임 코어 시스템 구현 (다리·차량·캐릭터 컨트롤러)
- ScriptableObject 기반 데이터 구조 설계 (`CurveSO`, `VariableSO`, `SkinSO`)
- URP 2D 렌더링 파이프라인 셋업
- 게임 UI (시작·일시정지·설정·홈) 구현

## Tech Stack

| 항목 | 사용 기술 |
|---|---|
| Engine | Unity 2022.3 LTS |
| Renderer | URP (Universal Render Pipeline) 2D |
| Language | C# |
| Data | ScriptableObject (CurveSO / VariableSO / SkinSO / IntVariableSO) |
| Tool | Git / GitHub |

## Implemented Systems

### 다리·차량·캐릭터 컨트롤러
- 다양한 차량 (자동차·배 등) 과 스킨 시스템 구현
- 캐릭터가 다리 위를 이동하며 차량을 통과시키는 코어 루프

### ScriptableObject 기반 데이터 구조
- `CurveSO` — 움직임 커브 데이터
- `VariableSO` / `IntVariableSO` — 게임 변수 (점수·난이도·스테이지)
- `SkinSO` — 캐릭터·차량 스킨 데이터
- 데이터를 코드와 분리하여 빠른 밸런싱 + 팀원 간 작업 충돌 최소화

### URP 2D 렌더링 + 게임 UI
- URP 2D 라이팅 + Pixel Perfect Camera
- 게임 UI (Start / Pause / Setting / Home) + 스킨 선택 화면

## Collaboration Insights

시간이 24 시간으로 극도로 제한된 환경에서, **기획 단계의 의견 충돌이 가장 큰 위험 요소** 였습니다. 개발 담당으로서 두 가지 원칙을 제안해 갈등을 정리했습니다.

1. **MVP 우선 정의** — '하루 안에 반드시 작동해야 하는 최소 기능' 을 먼저 합의한 뒤, 시간이 남으면 깊이를 추가하는 방식
2. **코드 영역 단위 역할 분리** — 동시 작업 시 머지 충돌 최소화 + 각자 자기 영역의 완성도 책임

결과적으로 **정시에 게임을 완성하여 출품** 할 수 있었습니다.

이 경험은 이후 1 인 인디 게임 'Sneakheaven' 개발 시의 마일스톤 분할 원칙, 그리고 현재 운영하는 'Game Factory' 양산 파이프라인의 '1 기능 = 1 Play = 1 커밋' 리듬으로 이어졌습니다.

---

## Developer

**윤현상 (Hyunsang Yoon)** — Game Designer

- itch.io: [nestward](https://nestward.itch.io)
- GitHub: [@fivefar](https://github.com/fivefar)
- Email: fivefar@gmail.com
