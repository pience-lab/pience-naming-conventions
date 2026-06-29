# Repository Naming Convention

이 문서는 우리 조직의 GitHub Repository 네이밍 규칙을 정의합니다. 모든 멤버는
새로운 리포지토리를 생성하기 전에 이 가이드를 반드시 따라야 합니다.

## 권장 패턴

```
{project/client}-{feature}-{type}

example)
lge-community-api
seah-keeper-app
seah-admin-web
seahsp-pda-app
anyma-admin-web
```

### 1 Project or Client

여러 프로젝트나 클라이언트가 있을 때 그룹핑을 위해 사용합니다.

| Project/Client | 용도                   | 예시                |
| -------------- | ---------------------- | ------------------- |
| `lge-`         | LG 클라이언트 프로젝트 | `lge-community-api` |
| `seah-`        | seah 앱 관련           | `seah-keeper-app`   |
| `seah-`        | seah admin 관련        | `seah-admin-web`    |
| `seahsp-`      | seahsp 앱 관련         | `seahsp-pda-app`    |
| `anyma-`       | anyma admin 관련       | `anyma-admin-web`   |

### 2 Feature (기능 영역)

리포지토리가 담당하는 비즈니스 기능이나 영역을 명시합니다.

예: `ai`, `admin`, `community`, `ecommerce`, `social`, `chat`

### 3 Type Suffix (코드의 종류)

리포지토리의 종류를 명시하는 가장 중요한 부분입니다.

| Suffix      | 용도                        | 예시                       |
| ----------- | --------------------------- | -------------------------- |
| `-monorepo` | 여러 종류를 포함하는 모노레포       | `community-monorepo`       |
| `-api`      | 백엔드 API 서버             | `payment-api`, `auth-api`  |
| `-web`      | 웹 프론트엔드               | `admin-web`, `landing-web` |
| `-socket`   | 웹 소켓                     | `chat-socket`              |
| `-app`      | 모바일 / 데스크톱 앱        | `tup-app`                  |
| `-sdk`      | 클라이언트 SDK / 라이브러리 | `pience-sdk`               |
| `-cli`      | 커맨드라인 도구             | `deploy-cli`               |
| `-lambda`   | serverless functions        | `image-lambda`             |
| `-lib`      | 공유 라이브러리             | `common-lib`               |
| `-infra`    | 인프라 / IaC (Terraform 등) | `aws-infra`                |
| `-docs`     | 문서                        | `api-docs`                 |
| `-config`   | 설정 파일 모음              | `eslint-config`            |
| `-mcp`      | MCP 서버                    | `notion-mcp`, `slack-mcp`  |
| `-bot`      | 봇 / 자동화                 | `slack-bot`                |
| `-action`   | GitHub Action               | `deploy-action`            |
| `-template` | 프로젝트 템플릿             | `nestjs-template`          |
| `-agent`    | AI Agent             | `ai-agent`          |
