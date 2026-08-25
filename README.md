<header>

<!--
  <<< Author notes: Course header >>>
  Include a 1280x640 image, course title in sentence case, and a concise description in emphasis.
  In your repository settings: enable template repository, add your 1280x640 social image, auto delete head branches.
  Add your open source license, GitHub uses MIT license.
-->

# Connect the dots in a GitHub repository（日本語版）

_リポジトリの中をたどるときに役立つコツ。_

> このリポジトリは GitHub Skills「[Connect the dots](https://github.com/skills/connect-the-dots)」（MIT License）の日本語版です。
> 演習の進め方と自動チェックの仕組みは原本と同じで、README に表示される手順の本文だけを日本語にしています。

</header>

<!--
  <<< Author notes: Step 1 >>>
  Choose 3-5 steps for your course.
  The first step is always the hardest, so pick something easy!
  Link to docs.github.com for further explanations.
  Encourage users to open new tabs for steps!
-->

## Step 1: 重複した Issue を整理する

_コースへようこそ :tada:_

GitHub には、GitHub 上の別の情報を参照するための特別な機能があります。たとえば、別の Issue や pull request を番号で参照すると、番号がリンクになります。同時に、リンク先の Issue や pull request の側にも相互参照（cross-reference）が作られます。双方向の参照によって、GitHub 上の情報どうしの関係を追えます。

![Issue から PR へのリンクと、PR 側に作られた相互参照のスクリーンショット](https://user-images.githubusercontent.com/6351798/172456846-2daec570-08b0-4ffa-a7cb-41acc50b836e.png)

複数のメンバーで共同作業をしていると、Issue が重複することがあります。上の例では、新しい Issue `#8346` が以前の Issue `#8249` の重複です。相互参照の機能があるので、重複をたどり、適切なタイミングで Issue をクローズできます。

### 参照を作る

別の Issue へリンクすると、GitHub の中に参照が自動で作られます。完全な URL を書く必要すらありません。コメントの中に `#5` と入力すれば、Issue または pull request の 5 番へのリンクになります。

クロスリンクを作りたいときは、`#` 記号を入力した直後に Issue や pull request のタイトルを打ち始めてください。GitHub が正しいリンク先の候補を提案します。さらに詳しくは [Autolinked References and URLs](https://docs.github.com/en/articles/autolinked-references-and-urls) の記事を参照してください。

### :keyboard: やること: クロスリンクされた Issue を見つけてクローズする

1. Issue #1（Welcome）を開きます。
2. コメントに "Duplicate of #2" と入力し、Issue #1 をクローズします。
3. 20 秒ほど待ってから、手順を読んでいるページ（README）を再読み込みします。[GitHub Actions](https://docs.github.com/en/actions) が自動で次の Step に更新します。

<footer>

<!--
  <<< Author notes: Footer >>>
  Add a link to get support, GitHub status page, code of conduct, license link.
-->

---

困ったとき: 講師に知らせてください &bull; [GitHub のステータスページを確認する](https://www.githubstatus.com/)

&copy; 2023 GitHub &bull; [Code of Conduct](https://www.contributor-covenant.org/version/2/1/code_of_conduct/code_of_conduct.md) &bull; [MIT License](https://gh.io/mit)

</footer>
