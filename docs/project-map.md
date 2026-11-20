# 자료 지도

## 서비스
- 이름: 오늘옷 (가칭)
- 컨셉: 아침 기온 하나만 보고 입었다가 후회하지 않게, 오늘 하루 아침·낮·저녁에 맞춰 무엇을 입고 언제 벗고 무엇을 챙길지 알려주는 서비스.

## 파일 위치
| 자료 | 파일 |
|---|---|
| 서비스 기획서 | `brief.md` |
| 퍼소나 | `research/persona-kim-seoyeon.md` (주), `research/persona-lee-haeun.md` (보조), `research/persona-park-junho.md` (체감 보정 근거) |
| 인터뷰, 조사 | `research/interviews.md` |
| 메뉴 구조 | 없음 |
| 와이어프레임 | `wireframes/` (01~07, 1.2~1.4) |
| 그 밖의 기획 문서 | `index.html` (이전 기획 기준의 랜딩 페이지, 새 기획과 내용이 다름) |

## 핵심 기능 (기획서 그대로)
1. 시간대별 레이어링 타임라인
2. 일정별 날씨
3. 내 체감 보정
4. 바람·비 번역
5. 미세먼지
6. 알림

## 주요 사용 시나리오 (기획서 그대로)
1. 전날 밤에 내일 옷 정하기 (이하은): 밤 10시 알림을 누르고 내일 아침·낮·저녁 안내를 본 뒤, 옷을 꺼내 두고 아침엔 고민 없이 나간다.

## 화면 목록
메뉴 구조 문서가 없어서 와이어프레임과 기획서를 보고 만든 **초안**이에요.

| ID | 화면 이름 | 와이어프레임 파일 | 비고 |
|---|---|---|---|
| 1.0 | 오늘의 타임라인 (홈) | `wireframes/06-today-timeline.html` | |
| 1.1 | 저녁 체감 피드백 | `wireframes/07-feedback.html` | |
| 1.2 | 내일 미리보기 | `wireframes/1.2-tomorrow-preview.html` | `/flow` 에서 새로 생긴 화면. 1.0과 "오늘 / 내일" 전환으로 오감 |
| 1.3 | 내일 일정 바꾸기 | `wireframes/1.3-tomorrow-schedule-edit.html` | `/flow` 에서 새로 생긴 화면. 내일 미리보기(1.2)에서 들어감 |
| 1.4 | 오늘 일정 바꾸기 | `wireframes/1.4-today-schedule-edit.html` | `/flow` 에서 새로 생긴 화면. 오늘의 타임라인(1.0)에서 들어감 |
| 2.0 | 온보딩 | | 아래 네 화면의 묶음 |
| 2.1 | 동네 선택 | `wireframes/01-onboard-location.html` | |
| 2.2 | 평소 일정 | `wireframes/02-onboard-schedule.html` | |
| 2.3 | 추위 타는 정도 | `wireframes/03-onboard-sensitivity.html` | |
| 2.4 | 알림 시간 | `wireframes/04-onboard-notify.html` | |
| 3.0 | 알림 (웹 푸시) | `wireframes/05-notice.html` | 서비스 밖(폰 잠금 화면)에서 보이는 화면 |
| 4.0 | 설정 | 없음 | 홈에 설정 버튼은 있지만 기획서에 화면 설명이 없음 |

## 비어 있는 것
- 메뉴 구조 문서가 없다 (위 화면 목록은 초안)
- 설정 화면은 와이어프레임도, 기획서 설명도 없다
- `index.html` 랜딩 페이지는 이전 기획(20대 여성, 쇼핑 추천) 기준이다
