<!--
  <<< Author notes: Step 1 >>>
  Choose 3-5 steps for your course.
  The first step is always the hardest, so pick something easy!
  Link to docs.github.com for further explanations.
  Encourage users to open new tabs for steps!
-->

## 1단계: Codespace에서 VS Code로 Copilot 활용하기

_"GitHub Copilot과 VS Code를 사용한 AI 기반 코드 제안으로 개발하기"에 오신 것을 환영합니다! :wave:_

GitHub Copilot은 더 빠르고 적은 노력으로 코드를 작성할 수 있도록 도와주는 AI 페어 프로그래머입니다. 주석과 코드에서 컨텍스트를 파악하여 개별 줄과 전체 함수를 즉시 제안합니다. GitHub Copilot은 OpenAI가 만든 생성형 사전 훈련 언어 모델인 OpenAI Codex로 구동됩니다.

**Copilot은 VS Code, Visual Studio, JetBrains IDE, Neovim 등 다양한 코드 에디터에서 작동합니다.**

또한 GitHub Copilot은 공개 리포지토리에 있는 모든 언어로 훈련되었습니다. 각 언어에 대해 받는 제안의 품질은 해당 언어의 훈련 데이터 양과 다양성에 따라 달라질 수 있습니다.

Codespace에서 Copilot을 사용하면 GitHub의 [협업 코딩](https://github.com/features#features-collaboration) 도구 모음을 얼마나 쉽게 시작할 수 있는지 보여줍니다.

> **참고**
> 이 실습은 GitHub Codespace 활용에 초점을 맞추고 있습니다. 이 실습을 진행하기 전에 GitHub 스킬 [Codespaces](https://github.com/skills-kr/code-with-codespaces)를 완료하는 것을 권장합니다.

### :keyboard: 활동: Codespace에서 Copilot 활성화하기

**다음 활동을 진행하는 동안 이 지침을 참고할 수 있도록 다른 브라우저 탭을 여는 것을 권장합니다.**

리포지토리에서 Codespace를 열기 전에, 개발 컨테이너를 만들고 Codespace에서 사용하거나 설치할 특정 확장 프로그램 또는 구성을 정의할 수 있습니다. 개발 컨테이너를 만들고 확장 프로그램 목록에 Copilot을 추가해 봅시다.

1. 리포지토리의 **Code** 탭으로 돌아가서 **Add file** 드롭다운 버튼을 클릭한 다음 `Create new file`을 클릭합니다.
1. 빈 텍스트 필드에 다음을 입력하거나 붙여넣어 파일 이름을 지정합니다.
   ```
   .devcontainer/devcontainer.json
   ```
1. 새 **.devcontainer/devcontainer.json** 파일 본문에 다음 내용을 추가합니다:
   ```
   {
       // Name this configuration
       "name": "Codespace for Skills!",
       "customizations": {
           "vscode": {
               "extensions": [
                   "GitHub.copilot"
               ]
           }
       }
   }
   ```
1. **Commit directly to the `main` branch** 옵션을 선택하고 **Commit new file** 버튼을 클릭합니다.
1. 화면 왼쪽 상단의 **Code** 탭을 클릭하여 리포지토리 홈페이지로 돌아갑니다.
1. 페이지 중앙에 있는 **Code** 버튼을 클릭합니다.
1. 팝업 상자에서 **Codespaces** 탭을 클릭합니다.
1. **Create codespace on main** 버튼을 클릭합니다.

   **Codespace가 시작될 때까지 약 2분 정도 기다립니다.**

1. Codespace가 실행 중인지 확인합니다. 브라우저에 VS Code 웹 기반 에디터와 아래와 같은 터미널이 표시되어야 합니다:
   ![Screen Shot 2023-03-09 at 9 09 07 AM](https://user-images.githubusercontent.com/26442605/224102962-d0222578-3f10-4566-856d-8d59f28fcf2e.png)
1. `copilot` 확장 프로그램이 VS Code 확장 프로그램 목록에 표시되어야 합니다. 확장 프로그램 사이드바 탭을 클릭합니다. 다음과 같이 표시되어야 합니다:
   ![Screen Shot 2023-03-09 at 9 04 13 AM](https://user-images.githubusercontent.com/26442605/224102514-7d6d2f51-f435-401d-a529-7bae3ae3e511.png)

**약 60초 기다린 후 리포지토리 랜딩 페이지를 새로고침하여 다음 단계로 진행합니다.**
