<header>

<!--
  <<< Author notes: Course header >>>
  Include a 1280x640 image, course title in sentence case, and a concise description in emphasis.
  In your repository settings: enable template repository, add your 1280x640 social image, auto delete head branches.
  Add your open source license, GitHub uses MIT license.
-->
<!--
  <<< 作者註記：課程標頭 >>>
  包含一張 1280x640 的圖片、一個句子式大小寫的課程標題，以及一段以強調樣式呈現的簡潔描述。
  在您的儲存庫設定中：啟用樣板儲存庫、新增您的 1280x640 社群圖片、自動刪除 head 分支。
  新增您的開源授權條款，GitHub 使用的是 MIT 授權條款。
-->

# 在 GitHub 儲存庫中串起關聯

_在瀏覽您的儲存庫時的實用技巧。_

</header>

<!--
  <<< Author notes: Step 2 >>>
  Start this step by acknowledging the previous step.
  Define terms and link to docs.github.com.
-->
<!--
  <<< 作者註記：步驟 2 >>>
  從感謝上一步的操作開始這個步驟。
  定義專有名詞並連結到 docs.github.com。
-->

## 步驟 2：在歷史紀錄中尋找一個提交 (commit)

_感謝您加上重複議題的註記 :wave:_

版本控制的一個重要部分，就是能夠回顧過去。透過使用 `git blame`，並找出某個提交背後的故事，我們能做到的不只是「指責」某人寫了某段程式碼。我們更能看到一個提交之所以被建立的前因後果。它關聯的拉取請求是什麼？是誰核准了那個拉取請求？在它被合併之前，有哪些測試在這個提交上運行過？

在歷史紀錄中尋找資訊最直接的理由，就是為了了解歷史。透過議題和拉取請求，我們能看到一個更完整的故事，而不僅僅是最低限度的資訊。

### `git blame` 是什麼？

`git blame` 是 Git 的一個功能，它能顯示一個檔案中的每一行，最後是由哪個修訂版本 (revision) 和哪位作者所修改的。像是誰、在何時、甚至為何做了某個提交這樣的資訊，都可以透過這個功能找到。如果您不確定是誰對檔案做了某些變更，您就可以用 `git blame` 來查明。雖然 `git blame` 這個詞聽起來有點像在追究責任，但它其實常被用來理解決策背後的脈絡。

### 什麼是 SHA (安全雜湊演算法)？

SHA (Secure Hash Algorithm) 是一個指向特定物件的參照。在我們這裡的例子中，它指向一個提交 (commit)。在 GitHub 上，您可以查看一個特定的提交，來了解它引入了哪些變更、由誰提交，以及它是否是某個拉取請求的一部分。

### :keyboard: 動手做：在歷史紀錄中尋找提交

1.  前往您的儲存庫的 **Code** (程式碼) 索引標籤。
    -   *小提示：您先前可能已經在新分頁中建立了您的儲存庫。*
2.  點擊 `docs` 進入 `/docs` 目錄。
3.  點擊 `_sidebar.md` 來檢視這個檔案。
4.  在檔案檢視頁面的頂端，點擊 **Blame** 按鈕，來查看最新修訂版本的詳細資訊。
5.  點擊提交訊息 `add sidebar to documentation`，來查看該提交的詳細內容。
6.  複製 **SHA** 的前七個字元 (也就是在 `commit` 後面那串 40 個字元的十六進位字串中的前 7 個字元)。
7.  前往議題 #2，將您在步驟 6 複製的 SHA 作為留言內容貼上，然後點擊「Comment」按鈕。
8.  等待約 20 秒，然後重新整理這個頁面（也就是您正在閱讀說明的這個頁面）。[GitHub Actions](https://docs.github.com/en/actions) 將會自動將課程更新到下一個步驟。

<footer>

<!--
  <<< Author notes: Footer >>>
  Add a link to get support, GitHub status page, code of conduct, license link.
-->
<!--
  <<< 作者註記：頁尾 >>>
  新增一個取得支援的連結、GitHub 狀態頁面、行為準則、授權條款連結。
-->

---

尋求協助：[在我們的論壇中發文](https://github.com/orgs/skills/discussions/categories/connect-the-dots) • [查看 GitHub 狀態頁面](https://www.githubstatus.com/)

© 2023 GitHub • [行為準則](https://www.contributor-covenant.org/version/2/1/code_of_conduct/code_of_conduct.md) • [MIT 授權條款](https://gh.io/mit)

</footer>
