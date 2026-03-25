<header>

<!--
  <<< Author notes: Course header >>>
  Read <https://skills.github.com/quickstart> for more information about how to build courses using this template.
  Include a 1280×640 image, course name in sentence case, and a concise description in emphasis.
  In your repository settings: enable template repository, add your 1280×640 social image, auto delete head branches.
  Next to "About", add description & tags; disable releases, packages, & environments.
  Add your open source license, GitHub uses the MIT license.
-->

# GitHub Copilot으로 코딩하기

_GitHub Copilot은 VS Code와 Codespaces에서 자동완성 스타일의 제안을 통해 코딩을 도와줍니다._

</header>

<!--
  <<< Author notes: Course start >>>
  Include start button, a note about Actions minutes,
  and tell the learner why they should take the course.
-->

## 환영합니다

GitHub Copilot은 자동완성 스타일의 제안을 제공하여 코딩을 도와줍니다. GitHub Copilot이 어떻게 작동하는지, 그리고 사용 시 고려해야 할 사항을 배울 수 있습니다. GitHub Copilot은 편집 중인 파일과 관련 파일의 컨텍스트를 분석하여 텍스트 에디터 내에서 제안을 제공합니다. GitHub Copilot은 OpenAI가 만든 새로운 AI 시스템인 OpenAI Codex로 구동됩니다.

- **대상**: 개발자, DevOps 엔지니어, 소프트웨어 개발 관리자, 테스터.
- **학습 내용**: Codespace에 Copilot 설치, 코드 제안 수락, 주석으로부터 제안 수락하는 방법.
- **만들 것**: Copilot AI의 코드 및 주석 제안으로 생성된 코드를 포함하는 Javascript 파일.
- **사전 요구사항**:
  - [GitHub 계정](https://github.com/login) - 사용 가능한 Codespaces 시간이 있어야 합니다.
  - [GitHub Copilot](https://github.com/github-copilot/signup) - 학습 목적이라면 사용량 제한이 있는 **Copilot Free** 옵션으로 충분합니다.
- **소요 시간**: 이 과정은 1시간 이내에 완료할 수 있습니다.

### 이 과정을 시작하는 방법

<!-- For start course, run in JavaScript:
'https://github.com/new?' + new URLSearchParams({
  template_owner: 'skills-kr',
  template_name: 'copilot-codespaces-vscode',
  owner: '@me',
  name: 'skills-copilot-codespaces-vscode',
  description: '실습: GitHub Copilot으로 코딩하기',
  visibility: 'public',
}).toString()
-->

[![start-course](https://user-images.githubusercontent.com/1221423/235727646-4a590299-ffe5-480d-8cd5-8194ea184546.svg)](https://github.com/new?template_owner=skills-kr&template_name=copilot-codespaces-vscode&owner=%40me&name=skills-copilot-codespaces-vscode&description=%EC%8B%A4%EC%8A%B5%3A+GitHub+Copilot%EC%9C%BC%EB%A1%9C+%EC%BD%94%EB%94%A9%ED%95%98%EA%B8%B0&visibility=public)

1. **실습 시작** 버튼을 우클릭하고 새 탭에서 링크를 엽니다.
2. 새 탭에서 대부분의 입력란이 자동으로 채워집니다.
   - 소유자(owner)는 개인 계정 또는 저장소를 호스팅할 조직을 선택합니다.
   - 프라이빗 리포지토리는 [Actions 시간을 사용](https://docs.github.com/en/billing/managing-billing-for-github-actions/about-billing-for-github-actions)하므로 퍼블릭 리포지토리를 만드는 것을 권장합니다.
   - 아래로 스크롤하여 양식 하단의 **Create repository** 버튼을 클릭합니다.
3. 새 리포지토리가 생성된 후 약 20초 기다린 다음 페이지를 새로고침합니다. 새 리포지토리의 README에 있는 단계별 지침을 따르세요.

<footer>

<!--
  <<< Author notes: Footer >>>
  Add a link to get support, GitHub status page, code of conduct, license link.
-->

---

도움 받기: [토론 게시판에 글 올리기](https://github.com/orgs/skills/discussions/categories/code-with-copilot) &bull; [GitHub 상태 페이지 확인](https://www.githubstatus.com/)

> **참고**: 이 실습은 [skills/copilot-codespaces-vscode](https://github.com/skills/copilot-codespaces-vscode)를 기반으로 한글화하고, [🏆 GitHub Skills Workshop Dashboard](https://github-skills.studydev.com)와 연계되어 있습니다.

&copy; 2023 GitHub &bull; [행동 강령](https://www.contributor-covenant.org/version/2/1/code_of_conduct/code_of_conduct.md) &bull; [MIT 라이선스](https://gh.io/mit)

</footer>
