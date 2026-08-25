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
  <<< Author notes: Step 2 >>>
  Start this step by acknowledging the previous step.
  Define terms and link to docs.github.com.
-->

## Step 2: 履歴からコミットを見つける

_重複の指摘をありがとうございます :wave:_

バージョン管理の重要な点のひとつは、過去をさかのぼって見られることです。`git blame` を使ってコミットの背景をたどると、コードについて人を _blame_（責める）する以上のことができます。なぜコミットが行われたのかという経緯が見えます。関連する pull request はどれか。誰が pull request を承認したか。マージ前にどんなテストが実行されたか。

履歴を調べる分かりやすい理由は、履歴を知るためです。Issue と pull request があれば、最低限の情報だけでなく、より完全な経緯が分かります。

### `git blame` とは

`git blame` は、ファイルの各行を最後に変更したリビジョンと作者を表示する Git の機能です。誰がいつコミットしたか、さらになぜコミットしたかまで調べられます。ファイルへの変更を誰が入れたのか分からないときは、`git blame` で確認できます。`git blame` という名前は責任追及のように聞こえますが、判断の背景を理解するために使えます。

### SHA（Secure Hash Algorithm）とは

SHA は特定のオブジェクトへの参照です。演習ではコミットへの参照を指します。GitHub では、特定のコミットを開くと、どんな変更が入ったか、誰が入れたか、pull request の一部だったかを確認できます。

### :keyboard: やること: 履歴からコミットを見つける

1. 自分のリポジトリの Code タブを開きます。
   - _ヒント: リポジトリは別のタブで開いているかもしれません_
2. `docs` をクリックして `/docs` ディレクトリに入ります。
3. `_sidebar.md` をクリックしてファイルを表示します。
4. ファイルの上部にある **Blame** をクリックし、直近のリビジョンの詳細を見ます。
5. コミットメッセージ `add sidebar to documentation` をクリックして、コミットの詳細を表示します。
6. SHA の先頭 7 文字をコピーします（`commit` の後ろに並ぶ 40 文字の 16 進数の、最初の 7 文字です）。
7. 手順 6 の SHA をコメント本文にして Issue #2 にコメントし、"Comment" ボタンをクリックします。
8. 20 秒ほど待ってから、手順を読んでいるページ（README）を再読み込みします。[GitHub Actions](https://docs.github.com/en/actions) が自動で次の Step に更新します。

<footer>

<!--
  <<< Author notes: Footer >>>
  Add a link to get support, GitHub status page, code of conduct, license link.
-->

---

困ったとき: 講師に知らせてください &bull; [GitHub のステータスページを確認する](https://www.githubstatus.com/)

&copy; 2023 GitHub &bull; [Code of Conduct](https://www.contributor-covenant.org/version/2/1/code_of_conduct/code_of_conduct.md) &bull; [MIT License](https://gh.io/mit)

</footer>
