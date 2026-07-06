# devp0tion — Claude Code 플러그인 마켓플레이스

[DevP0tion](https://github.com/DevP0tion)이 배포하는 Claude Code 플러그인을 한곳에 모은 마켓플레이스입니다.

## 설치

```
/plugin marketplace add DevP0tion/DevP0tion
/plugin install <플러그인명>@devp0tion
```

## 플러그인

| 플러그인 | 설명 |
|--------|------|
| `xlmcp` | Excel 자동화 MCP 서버 (49개 도구). 세션 풀링, 가상 클립보드, 청크 병렬 I/O. Windows 전용. |
| `team-report` | Accept/Defer/Reject 결정 카드와 피드백 루프를 갖춘 인터랙티브 HTML 리포트를 생성하는 멀티 에이전트 팀 분석. |

각 플러그인의 소스는 개별 저장소에 있으며, 통합 관리를 위해 [`plugins/`](plugins/) 아래에 git submodule로 미러링되어 있습니다. 설치는 항상 원본 저장소에서 직접 받아오므로 submodule을 초기화할 필요가 없습니다.
