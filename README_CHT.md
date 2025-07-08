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
  <<< Author notes: Step 3 >>>
  Start this step by acknowledging the previous step.
  Define terms and link to docs.github.com.
-->
<!--
  <<< 作者註記：步驟 3 >>>
  從感謝上一步的操作開始這個步驟。
  定義專有名詞並連結到 docs.github.com。
-->

## 步驟 3：修復損壞的側邊欄

_做得好，成功找到了那個提交 :heart:_

感謝您找到那個提交！我們現在知道側邊欄確實是在那個提交中被加入的。讓我們再深入挖掘一下，看看是否有任何圍繞這個變更的規劃或對話，例如透過留言進行的討論。

如同我們已經看到的，議題和拉取請求中的對話可以參照其他工作，但它們所提供的上下文遠遠不止於相互連結。別忘了，Git 本身就是版本控制！舉例來說，您在上一步找到的那個提交，其實還連結了更多資訊，例如：

-   誰建立了這個提交。
-   還包含了哪些其他的變更。
-   這個提交是在何時建立的。
-   這個提交是哪個拉取請求的一部分。

拉取請求之所以重要，是因為它不僅讓我們知道一個提交是*何時*發生的，更讓我們了解*為何*要這麼做。追溯歷史並不是為了*指責*任何人，而是為了看到更完整的全貌。為什麼會做出這些決定？誰參與其中？每個提交的建置結果和測試報告是什麼？誰要求變更，又是誰核准了它們？

### 從提交中找到拉取請求

當您在 GitHub 上查看一個提交時，您可以看到許多資訊。在這個檢視畫面中，您也能找到建立該提交的拉取請求連結。我們將在下一步用到這個功能。

![一張在 GitHub 上查看提交的螢幕截圖，其中突顯了連向拉取請求的連結](https://user-images.githubusercontent.com/16547949/67341250-3edbb480-f4fd-11e9-805a-6bce5a8ba2d1.png)

### :keyboard: 動手做：修復損壞的側邊欄

1.  在 `main` 分支中，[編輯 `docs/_sidebar.md` 檔案](/docs/_sidebar.md)。
2.  將第 4 行的參照 `(doc-references__.md)` 中的拼寫錯誤更正為 `(doc-references.md)`。
3.  為這次的提交選擇或建立一個名為 `fix-sidebar` 的新分支，並發起一個拉取請求。
4.  確認 **base:** 選擇的是 **main**，而 **compare:** 選擇的是 **fix-sidebar**。
5.  在右側的 **Assignees** (指派對象) 區塊，將您自己指派給這個拉取請求。
6.  在拉取請求的留言中加入 `Closes #2`，來自動連結議題 #2。
7.  點擊 **Create pull request** (建立拉取請求)，並等待約 20 秒。
8.  合併這個拉取請求。
9.  刪除 `fix-sidebar` 分支。
10. 等待約 20 秒，然後重新整理這個頁面（也就是您正在閱讀說明的這個頁面）。[GitHub Actions](https://docs.github.com/en/actions) 將會自動將課程更新到下一個步驟。

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
