# SYNAPSE — 프로젝트 페이지

이기종 멀티로봇을 위한 End-to-End 원격조작·플릿 관제 플랫폼 **SYNAPSE**의 소개 사이트입니다.
KETI 지능로보틱스연구센터 · STAR TEAM.

🔗 **사이트:** https://keti-synapse.github.io/

## 구성
| 페이지 | 내용 |
|---|---|
| `index.html` | 플랫폼 개요 · 아키텍처 · 컴포넌트 · 통신 · 미션 |
| `synapse.html` | 공통 표준 레이어 (메시지·Enum·자료구조·미션 모델) |
| `tom.html` · `and.html` · `gerri.html` | 온-로봇 측 (물리 HW · 네트워크 데몬 · 제어 SW + COCKPIT) |
| `nexus.html` | 플릿 관제 서버 |
| `demo.html` | 체험해보기 — nexus_ui 통합 관제 콘솔 재현(사이트 오버뷰 · 플릿 RTS · 1:1 콕핏 · 플릿 미션, 백엔드 없는 시뮬레이션) |
| `style.css` | 공통 스타일 (논문 페이지 톤) |

## 배포
순수 정적 HTML/CSS — 빌드 없음. GitHub Pages(main 브랜치 루트)에서 그대로 서빙됩니다.
로컬 미리보기: `python3 -m http.server 8000`

---
🤖 Generated with [Claude Code](https://claude.com/claude-code)
