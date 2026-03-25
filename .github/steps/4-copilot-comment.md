<!--
  <<< Author notes: Step 4 >>>
  Start this step by acknowledging the previous step.
  Define terms and link to docs.github.com.
-->

## 4단계: 주석을 사용하여 Copilot으로 코드 생성하기

_Copilot 탭을 훌륭하게 활용하셨습니다!_ :partying_face:

이제 Copilot 빠른 탭 자동 제안뿐만 아니라 Copilot 허브를 활용하여 AI가 생성한 제안을 수락하는 방법을 익혔습니다.

이제 주석을 활용하여 Copilot 제안을 생성하는 방법을 알아봅시다!

### :keyboard: 활동: Codespace 리포지토리에 최신 코드 가져오기

> **참고**
> 다음 활동 전에 반드시 Pull을 수행해야 합니다.

1. VS Code 터미널을 사용하여 최신 코드를 가져옵니다:

   ```
   git pull
   ```

### :keyboard: 활동: 주석으로 Copilot 제안 코드 생성하기

1. Codespace 내 VS Code 탐색기 창에서 새 파일을 만듭니다. (위에서 Codespace를 닫았다면 다시 열거나 새 Codespace를 만드세요.)
2. 파일 이름을 `comments.js`로 지정합니다.
3. 파일에 다음 주석을 입력합니다:
   ```
   // Create web server
   ```
4. `enter`를 눌러 새 줄로 이동합니다.
5. Copilot이 코드 블록을 제안합니다.
6. 빨간 물결선 위에 마우스를 올리고 `...`을 선택합니다.

   > **참고**
   > Copilot 코드 블록 제안이나 빨간 물결선과 세 개의 점 `...`이 보이지 않으면, `control + enter`를 입력하여 GitHub Copilot 완성 패널을 불러올 수 있습니다.

7. **Open Completions Panel**을 클릭합니다. Copilot이 약 10가지 다른 코드 제안을 생성합니다. 다음과 같이 표시될 것입니다:
   ![Screen Shot 2023-04-25 at 3 59 42 PM](https://user-images.githubusercontent.com/26442605/234425509-74ea96e0-bbd6-417b-84c5-73546ac7b2cd.png)
8. 마음에 드는 솔루션을 찾아 **Accept Solution**을 클릭합니다.
9. `comments.js` 파일이 선택한 솔루션으로 업데이트됩니다.

### :keyboard: 활동: Codespace에서 리포지토리로 코드 푸시하기

1. VS Code 터미널을 사용하여 `comments.js` 파일을 리포지토리에 추가합니다:

   ```
   git add comments.js
   ```

2. 다음으로 VS Code 터미널에서 변경 사항을 리포지토리에 스테이지하고 커밋합니다:

   ```
   git commit -m "Copilot third commit"
   ```

3. 마지막으로 VS Code 터미널에서 코드를 리포지토리에 푸시합니다:

   ```
   git push
   ```

**약 60초 기다린 후 리포지토리 랜딩 페이지를 새로고침하여 다음 단계로 진행합니다.**
