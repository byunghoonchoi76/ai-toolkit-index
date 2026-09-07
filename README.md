# 🧰 AI 툴킷 인덱스

그동안 모아둔 깃허브·사이트·노션 링크 **70개**를 전부 확인해 “무엇을 하는지 / 어떻게 쓰는지”로 정리하고 **10개 카테고리**로 분류한 개인 참고 서고입니다.

전체 내용은 검색·필터가 되는 한 장짜리 웹페이지 [`index.html`](index.html)에 담겨 있습니다. 카드마다 **무엇 · 핵심 기능 · 설치/사용 명령어 · 원본 링크**가 들어 있고, 상단 검색창과 카테고리 필터로 원하는 도구를 바로 찾을 수 있습니다.

> 🔎 **바로 보기:** GitHub Pages를 켜면 `https://<사용자명>.github.io/ai-toolkit-index/` 에서 열립니다. (설정법은 맨 아래 참고)

---

## 📚 카테고리

| 카테고리 | 개수 | 대표 |
|---|---:|---|
| 스킬 · 개발 방법론 | 8 | superpowers · agent-skills · ponytail · Task Observer |
| 컨텍스트 · 메모리 · 라우팅 인프라 | 6 | OmniRoute · claude-mem · Headroom · LangGraph |
| 코드 · 문서 이해/생성 | 4 | RepoBrain · OpenWiki · drawDB · PDF Inspector |
| 프롬프트 · 글쓰기(한글) | 3 | prompt-master · im-not-ai · claw-hwp |
| 연구 · 논문 도구 | 7 | open-science · PaperBanana · PixelNeRF · StoryScope |
| 미디어 · 하드웨어 앱 | 3 | muscriptor · Parabolic · Tinkered AI |
| 학습 · 실습(핸즈온) | 3 | cwc-workshops · a2ui · Vertex AI Pipelines |
| AI 학습 · 시각화 · 실험 | 15 | TensorFlow Playground · Transformer Explainer · Explainpaper |
| 가이드 · 아티클(블로그) | 7 | StoryScope 해설 · 바이브코딩 3도구 · ELI5 |
| 노션 자료 · 프롬프트 | 14 | AI 발표자료 프롬프트 · PubMed 자동요약 · hwpx 스킬 |

## ⭐ 관심사 연관 (논문 · 발표 · HWP · 자동화)

- **PaperBanana** — 방법론 텍스트 → 논문급 다이어그램·통계 플롯 (NeurIPS/IEEE 스타일)
- **open-science** — 로컬 우선 AI 연구 워크벤치 (Python/R 실행 + 결과물 출처 추적)
- **PixelNeRF** — 소수 시점 이미지 → 3D 복원 (100줄 구현 예제)
- **Explainpaper** — 논문 어려운 부분을 하이라이트하면 AI가 즉시 설명
- **Transformer Explainer** — 브라우저에서 GPT-2를 돌려 트랜스포머 전 과정 시각화
- **claw-hwp / hwpx 스킬** — Claude가 HWP/HWPX를 직접 읽고 편집 (학위논문 작업)
- **AI 발표자료 제작 프롬프트** — 원본 자료 → PPTX + 발표대본 DOCX 자동 생성

## ⚠️ 주의

일부 노션 링크(예: `Claude × PubMed × Notion`, `Aixploria`)는 **원본 URL에 개인 접근 토큰이 포함**돼 있었습니다. 이 저장소에 실린 링크는 가능한 한 토큰을 제거한 주소이지만, 링크를 외부에 공유할 때는 토큰 노출에 유의하세요.

일부 항목은 **상태가 바뀌었습니다** — Distill(2021년 이후 신규 발행 중단), Google AI Experiments(→ Google Labs 통합), Lobe(개발 종료), Playground AI(이미지 생성 → 디자인 스튜디오로 전환). 각 항목 카드에 표시해 두었습니다.

---

## 🚀 GitHub Pages로 웹페이지 띄우기

1. GitHub에서 이 저장소 페이지로 이동
2. **Settings → Pages**
3. **Source** 를 `Deploy from a branch` 로 선택
4. **Branch** 를 `main` / 폴더 `/ (root)` 로 지정하고 **Save**
5. 잠시 후 `https://<사용자명>.github.io/ai-toolkit-index/` 에서 `index.html`이 열립니다

> ℹ️ **비공개(Private) 저장소 참고:** GitHub Pages를 **비공개 저장소**에서 쓰려면 GitHub Pro/Team/Enterprise 플랜이 필요합니다. 무료 플랜이라면 저장소를 **Public** 으로 바꿔야 Pages가 동작합니다. (웹 호스팅 없이 파일만 보관하려면 이 단계는 건너뛰고 저장소에서 `index.html`을 내려받아 여세요.)

---

*확인 방법: GitHub·웹은 페이지 원문 파싱, 공개 노션은 브라우저 렌더링으로 읽음. 설치 명령은 각 저장소 README 기준이며 버전은 바뀔 수 있습니다.*
