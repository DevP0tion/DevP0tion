# 플러그인 마켓플레이스

AI 사용하면서 개인적으로 필요하다 싶은 기능들을 만들어봤어요.

## 설치

### Claude Code

```
/plugin marketplace add DevP0tion/DevP0tion
/plugin install <플러그인명>@devp0tion
```

### Codex CLI (ChatGPT)

Codex는 Claude Code 호환 플러그인 체계를 쓰므로 명령이 같습니다. 현재 Codex 지원 플러그인은 `nunchi-codex`입니다.

```
/plugin marketplace add DevP0tion/DevP0tion
/plugin install nunchi-codex@devp0tion
```

설치 후 `/hooks`에서 nunchi의 hook을 검토하고 신뢰(trust)해야 동작합니다 — Codex는 플러그인에 번들된 hook을 자동으로 신뢰하지 않습니다.

## 플러그인

| 플러그인 | 설명 |
|--------|------|
| `xlmcp` | Claude가 Excel 파일을 직접 읽고 고치고 자동화합니다 — 데이터 입력부터 보고서 작성까지. 대용량 파일도 빠르게 처리합니다. Windows 전용. |
| `team-report` | "아키텍처 리뷰", "컬러 테마 분석" 같은 요청을 받아, 요구사항에 맞게 구성된 AI 전문가 팀이 반응형 HTML 보고서로 작성합니다. 제안마다 수락/보류/거절을 고르면 다음 보고서가 그 선택을 학습합니다. |
| `nunchi` | 프로젝트마다 "적당히"가 어느 정도인지 Claude에게 가르칩니다. 과했던 것과 부족했던 것을 기억해 다음 세션부터 자동 반영합니다. Bun 필요. |
| `nunchi-codex` | `nunchi`의 Codex CLI(ChatGPT)용 빌드. 같은 프로젝트를 Claude Code와 Codex로 번갈아 작업해도 학습이 하나로 쌓입니다. Bun 필요. |

