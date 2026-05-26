# selfcore-frame

**AI와 함께 나를 정의하고, 웹사이트 표현까지 완성하는 Claude 실행 저장소**
*by 이태원쌤*

---

## 이 저장소는 무엇인가

강사·코치·컨설턴트가 Claude Project에 연결해서
셀프코어 프레임 전체를 AI와 함께 완성하는 저장소다.

사람이 읽는 문서가 아니라 **Claude가 읽고 실행하는 저장소**다.
사용자는 "시작"이라고 입력하면 된다. Claude가 나머지를 주도한다.

---

## 완성되면 무엇이 생기나

**셀프코어** (STEP 1~4)
- 미션 선언문 (XYZ)
- Why / How / What (골든 서클)
- 핵심 차별점

**웹사이트 표현 세트** (STEP 5~7)
- Role — 나를 설명하는 직함 3개
- Identity — 방문자 관점의 한 문장 정의
- Slogan — 행동 방침 한 줄
- Message — 방문자에게 건네는 첫 마디

**Brizy Story** (셀프코어 완성 후)
- 모바일 명함 / 교육 랜딩페이지 / 서비스 소개 / 포트폴리오
- 용도별 가이드에 따라 콘텐츠 설계 → 템플릿 선정 → 슬라이드 가이드 생성

---

## 사용 방법

1. Claude Project를 만든다
2. 이 저장소를 Project에 연결한다
3. 새 채팅에서 "시작"이라고 입력한다
4. Claude의 안내에 따라 답변만 하면 된다

저장소가 업데이트되면 새 채팅에서 "CLAUDE.md 업데이트해줘"라고 입력하면 된다.

---

## 저장소 구조

```
selfcore-frame/
│
├── CLAUDE.md                   ← Claude용 저장소 전체 안내
├── README.md                   ← 사람용 안내 (GitHub 페이지)
│
├── 1_process/                  ← Claude가 각 단계에서 참조하는 행동 지침
│   ├── step1-xyz.md        ★  STEP 1 — XYZ 인터뷰 진행 방식
│   ├── step2-mission.md       STEP 2 — 미션 선언문 생성 방식
│   ├── step3-golden-circle.md STEP 3 — Why/How/What 인터뷰 방식
│   ├── step3a-why-unclear.md  STEP 3 분기 — Why가 흐릿할 때
│   ├── step4-summary.md       STEP 4 — 셀프코어 정리 및 출력
│   ├── step5-role.md          STEP 5 — Role 도출
│   ├── step6-expression.md    STEP 6 — Identity/Slogan/Message 및 서브카피 생성
│   └── step7-check.md         STEP 7 — 일관성 검증
│
├── 2_templates/                ← 결과물 출력 형식
│   ├── selfcore-output.md     STEP 4 결과물 형식
│   ├── expression-output.md   STEP 7 결과물 형식
│   └── profile-base-template.md  기초자료 정리 템플릿 (초기화 시 Claude가 참조)
│
├── 3_examples/                 ← 완성 예시 (사용자에게 제시할 때 참조)
│   └── example-leetaewon.md   이태원쌤 셀프코어 전체 예시
│
└── 4_brizy/
    ├── brizy-story-guide.md        Brizy Story 활용 방안 및 용도별 추천
    ├── brizy-story-templates.md    템플릿 전체 분석 (58개 슬라이드 구조)
    ├── guide-mobile-card.md        모바일 명함 제작 가이드 (절차 + 템플릿 선정)
    ├── guide-edu-landing.md        교육 랜딩페이지·커리큘럼 소개 제작 가이드
    ├── guide-service-intro.md      서비스 소개 제작 가이드
    └── guide-portfolio.md          포트폴리오 제작 가이드
```

---

## 전체 흐름

```
STEP 1  XYZ 질문         → 소재 수집 (X·Y·Z 하나씩)
STEP 2  미션 선언문       → 초안 3가지 → 선택·확정
STEP 3  골든 서클 질문    → Why·How·What 하나씩
STEP 4  셀프코어 정리     → 전체 출력 + 연결 점검      ← 셀프코어 완성
STEP 5  Role 도출        → 직함 3개 세트 → 선택·확정
STEP 6  표현 세트 생성    → Identity·Slogan·Message
STEP 7  일관성 점검       → 4요소 점검 + 완료          ← 표현 세트 완성

Brizy  템플릿 추천        → 셀프코어 기반 템플릿 선택 + 슬라이드 가이드
```

STEP 4까지 완성하면 셀프코어, STEP 7까지 완성하면 웹사이트 표현 세트가 나온다.
Brizy Story는 셀프코어 완성 후 언제든 Claude에게 요청하면 된다.

---

## 문의

이태원쌤 — leetaewon.com

*selfcore-frame | by 이태원쌤 | 2026-05-26*