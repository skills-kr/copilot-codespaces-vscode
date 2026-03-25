<!--
  <<< Author notes: Step 3 >>>
  Start this step by acknowledging the previous step.
  Define terms and link to docs.github.com.
-->

## 3단계: 여러 제안이 있는 GitHub Copilot 탭 보기

_잘하셨습니다! JavaScript 파일에서 GitHub Copilot을 사용하여 AI 코드 제안을 활용했습니다 :sparkles:_

Copilot을 계속 사용하다 보면 GitHub Copilot이 제공하는 일부 제안을 원하지 않을 수 있습니다. GitHub Copilot은 새 탭에서 여러 제안을 보여줍니다.

### :keyboard: 활동: Codespace 리포지토리에 최신 코드 가져오기

> **참고**
> 다음 활동 전에 반드시 Pull을 수행해야 합니다.

1. VS Code 터미널을 사용하여 최신 코드를 가져옵니다:

   ```
   git pull
   ```

### :keyboard: 활동: 다른 Javascript 메서드 추가하고 모든 제안 보기

1. Codespace 내 VS Code 탐색기 창에서 새 파일을 만듭니다. 참고: 위에서 Codespace를 닫았다면 다시 열거나 새 Codespace를 만드세요.
2. 파일 이름을 `member.js`로 지정합니다.
3. `member.js` 파일에 다음 함수 헤더를 입력합니다.
   ```
   function skillsMember()
   ```
4. 입력을 멈추고 빨간 물결선 위에 마우스를 올린 후 `...`을 선택하여 Copilot 제안을 확인합니다.
5. **Open Completions Panel**을 클릭합니다. Copilot이 약 10가지 다른 코드 제안을 생성합니다. 다음과 같이 표시될 것입니다:
   ![Screen Shot 2023-04-27 at 10 06 55 AM](https://user-images.githubusercontent.com/26442605/234937592-d196bd5e-8ac2-4d9a-87f4-94e8a9b6a417.png)
6. 마음에 드는 솔루션을 찾아 **Accept Solution**을 클릭합니다.
7. `member.js` 파일이 선택한 솔루션으로 업데이트됩니다.

### :keyboard: 활동: Codespace에서 리포지토리로 코드 푸시하기

1. VS Code 터미널을 사용하여 `member.js` 파일을 리포지토리에 추가합니다:

   ```
   git add member.js
   ```

2. 다음으로 VS Code 터미널에서 변경 사항을 리포지토리에 스테이지하고 커밋합니다:

   ```
   git commit -m "Copilot second commit"
   ```

3. 마지막으로 VS Code 터미널에서 코드를 리포지토리에 푸시합니다:

   ```
   git push
   ```

**약 60초 기다린 후 리포지토리 랜딩 페이지를 새로고침하여 다음 단계로 진행합니다.**
