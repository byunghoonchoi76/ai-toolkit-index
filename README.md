# 🧰 AI 툴킷 인덱스

그동안 모아둔 깃허브·사이트·노션 링크 **144개**를 전부 확인해 “무엇을 하는지 / 어떻게 쓰는지”로 정리하고 **13개 카테고리**로 분류한 개인 참고 서고입니다.

전체 내용은 검색·필터가 되는 한 장짜리 웹페이지 [`index.html`](index.html)에 담겨 있습니다. 카드마다 **무엇 · 핵심 기능 · 설치/사용 명령어 · 원본 링크**가 들어 있고, 상단 검색창과 카테고리 필터로 원하는 도구를 바로 찾을 수 있습니다.

> 🔎 **바로 보기:** GitHub Pages를 켜면 `https://<사용자명>.github.io/ai-toolkit-index/` 에서 열립니다. (설정법은 맨 아래 참고)

---

## 📚 카테고리

| 카테고리 | 개수 | 대표 |
|---|---:|---|
| 스킬 · 개발 방법론 | 15 | superpowers · agent-skills · ponytail · spec-kit · replica-skill · scientific-agents |
| 컨텍스트 · 메모리 · 라우팅 인프라 | 10 | OmniRoute · claude-mem · Headroom · LangGraph · Graft · mobile-mcp · 9router |
| 코드 · 문서 이해/생성 | 5 | RepoBrain · OpenWiki · drawDB · PDF Inspector · opendataloader-pdf |
| 개발 도구 · 유틸리티 | 21 | Paseo · superset · REA · PentAGI · Filee · windirstat · react-three-fiber |
| 프롬프트 · 글쓰기(한글) | 5 | prompt-master · im-not-ai · claw-hwp · kordoc · humanizer |
| 연구 · 논문 도구 | 11 | open-science · PaperBanana · Paper2Agent · OpenResearch · dr-claw |
| 3D · 비전 · 생성 모델 | 15 | TRELLIS.2 · GenIA · LightGlue · GVHMR · Sana · FoundYou · modly |
| 미디어 · 하드웨어 앱 | 10 | God's Eye View · Voicebox · Upscayl · MiniMax-Music3 · muscriptor |
| 학습 · 실습(핸즈온) | 4 | cwc-workshops · a2ui · Vertex AI Pipelines · DeepTutor |
| AI 학습 · 시각화 · 실험 | 15 | TensorFlow Playground · Transformer Explainer · Explainpaper |
| 가이드 · 아티클(블로그) | 10 | StoryScope 해설 · 바이브코딩 3도구 · Claude YouTube Skill · 낭만빌더 |
| 디자인 · UI 레퍼런스 | 6 | Framer · Mobbin · 60fps.design · ui-skills · M3E Canvas |
| 노션 자료 · 프롬프트 | 17 | AI 발표자료 프롬프트 · PubMed 자동요약 · 비싼 사이트 효과 4가지 |

## ⭐ 관심사 연관 (위성 정찰·ISR · 3D · 논문 · 발표 · HWP)

- **God's Eye View** — 실시간 지구 전역 지리정보(ISR) 3D 시각화 (항공기·선박·위성·CCTV) — **국방 초소형/군집 위성 정찰 관심사에 직결**
- **TRELLIS.2 · GenIA** — 이미지→3D 생성 / 입력 정렬 테스트타임 3D 재구성 (학위논문 3D 작업)
- **LightGlue** — 광속 희소 로컬 피처 매칭 (위성/멀티뷰 정합 파이프라인)
- **FoundYou** — 개인화 객체 분할+검색 통합 모델 (정찰·객체 재식별)
- **Upscayl** — Real-ESRGAN AI 이미지 업스케일러 (위성 SR 작업 참고용)
- **claw-hwp · kordoc · Filee** — HWP/HWPX를 읽고 편집·변환 (학위논문 작업)
- **PaperBanana / Paper2Agent** — 논문 그림 자동 생성 / 논문을 대화형 에이전트로 변환

## ⚠️ 주의

- 일부 노션 링크(예: `Claude × PubMed × Notion`, `Aixploria`)는 **원본 URL에 개인 접근 토큰이 포함**돼 있었습니다. 저장소에 실린 링크는 가능한 한 토큰을 제거한 주소이지만, 외부 공유 시 유의하세요.
- **상태가 바뀐 항목:** Distill(발행 중단), Google AI Experiments(→ Google Labs), Lobe(개발 종료), Playground AI(디자인 스튜디오), Flowise(저장소 아카이브), PaperGym(README 미비). 각 카드에 표시했습니다.
- **REA · replica-skill · PentAGI**는 리버스 엔지니어링 / 앱 클론 / 자율 침투 테스트 도구로, **소유했거나 명시적으로 평가 권한을 받은 시스템·소프트웨어**의 합법적 연구·상호운용·보안 테스트 목적에 한정됩니다.
- 대부분의 3D·비전·생성 모델(GenIA·schift-ocr 포함)은 **NVIDIA GPU·CUDA 환경**이 필요합니다.

---

## 🚀 GitHub Pages로 웹페이지 띄우기

1. GitHub에서 이 저장소 페이지로 이동 → **Settings → Pages**
2. **Source** `Deploy from a branch` → **Branch** `main` / `/ (root)` → **Save**
3. 잠시 후 `https://<사용자명>.github.io/ai-toolkit-index/` 에서 `index.html`이 열립니다

> ℹ️ **비공개(Private) 저장소 참고:** GitHub Pages를 비공개 저장소에서 쓰려면 GitHub Pro/Team/Enterprise 플랜이 필요합니다. 무료 플랜이면 저장소를 **Public** 으로 바꿔야 Pages가 동작합니다.

---

*확인 방법: GitHub·웹은 페이지 원문 파싱, 공개 노션은 브라우저 렌더링으로 읽음. 설치 명령은 각 저장소 README 기준이며 버전은 바뀔 수 있습니다.*
