<!--
  <<< Author notes: Step 2 >>>
  Start this step by acknowledging the previous step.
  Define terms and link to docs.github.com.
-->

## 2단계: Javascript 파일에서 AI 코드 제안 확인하기!

_잘하셨습니다! :tada: Copilot이 설치된 devcontainer 파일을 사용하여 Codespace를 만들었습니다!_

GitHub Copilot은 다양한 언어와 프레임워크에 대한 제안을 제공하지만, Python, JavaScript, TypeScript, Ruby, Go, C# 및 C++에서 특히 잘 작동합니다. 다음 예제는 JavaScript로 되어 있지만, 다른 언어도 비슷하게 작동합니다.

Javascript를 활용하여 Copilot을 사용해 봅시다.

### :keyboard: 활동: Javascript 파일 추가하고 코드 작성 시작하기

1. Codespace 내 VS Code 탐색기 창에서 새 파일을 만듭니다.

> **참고**:
> 위에서 Codespace를 닫았다면 다시 열거나 새 Codespace를 만드세요.

2. 파일 이름을 `skills.js`로 지정합니다.
3. 새 파일이 다음과 같이 보이는지 확인합니다:
   ![Screen Shot 2023-03-09 at 9 21 34 AM](https://user-images.githubusercontent.com/26442605/224105906-d1beb531-b747-4c7a-85ba-a12526488422.png)
4. `skills.js` 파일에 다음 함수 헤더를 입력합니다.

   ```
   function calculateNumbers(var1, var2)
   ```

   GitHub Copilot이 회색 텍스트로 전체 함수 본문을 자동으로 제안합니다. 아래는 가장 일반적으로 볼 수 있는 예시이지만, 정확한 제안은 다를 수 있습니다.
   ![Screen Shot 2023-04-27 at 10 23 06 AM](https://user-images.githubusercontent.com/26442605/234941079-b4bf3e9d-fc70-4b20-b74c-0ee753ba344e.png)

5. `Tab`을 눌러 제안을 수락합니다.

### :keyboard: 활동: Codespace에서 리포지토리로 코드 푸시하기

1. VS Code 터미널을 사용하여 `skills.js` 파일을 리포지토리에 추가합니다:

   ```
   git add skills.js
   ```

2. 다음으로 VS Code 터미널에서 변경 사항을 리포지토리에 스테이지하고 커밋합니다:

   ```
   git commit -m "Copilot first commit"
   ```

3. 마지막으로 VS Code 터미널에서 코드를 리포지토리에 푸시합니다:

   ```
   git push
   ```

**약 60초 기다린 후 리포지토리 랜딩 페이지를 새로고침하여 다음 단계로 진행합니다.**
