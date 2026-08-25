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
  <<< Author notes: Step 3 >>>
  Start this step by acknowledging the previous step.
  Define terms and link to docs.github.com.
-->

## Step 3: 壊れたサイドバーを直す

_コミットを見つけられましたね :heart:_

サイドバーが確かに追加されたこと、`add sidebar to documentation` のコミットで行われたことが分かりました。もう少し掘り下げて、変更をめぐる計画や会話がコメントとして残っていないか調べましょう。

すでに見たとおり、Issue や pull request での会話は別の作業を参照できますが、得られる文脈はクロスリンクだけにとどまりません。Git はバージョン管理です。たとえば、前の Step で見つけたコミットには、次のような情報がひも付いています。

- 誰がコミットをしたか。
- ほかにどんな変更が含まれていたか。
- いつコミットされたか。
- どの pull request の一部だったか。

pull request が重要なのは、コミットがいつ行われたかを超えた情報が分かるからです。_なぜ_ コミットが行われたかを知ることができます。履歴を調べるのは誰かを _責める_ ためではなく、全体像を見るためです。なぜ判断がされたのか。誰が関わったのか。各コミットのビルド結果とテスト結果はどうだったのか。誰が変更を要求し、誰が承認したのか。

### コミットから pull request を見つける

GitHub でコミットを表示すると、多くの情報が見られます。コミットの画面から、コミットが作られた pull request へのリンクもたどれます。次の Step で使います。

![GitHub のコミット画面で、pull request へのリンクを示したスクリーンショット](https://user-images.githubusercontent.com/16547949/67341250-3edbb480-f4fd-11e9-805a-6bce5a8ba2d1.png)

### :keyboard: やること: 壊れたサイドバーを直す

1. main ブランチで [`docs/_sidebar.md` ファイルを編集](/docs/_sidebar.md)します。
2. 4 行目にある参照 `(doc-references__.md)` のつづりを `(doc-references.md)` に直します。
3. コミット用に新しいブランチ `fix-sidebar` を選択または作成し、pull request を開始します。
4. **base:** に **main**、**compare:** に **fix-sidebar** が選ばれていることを確認します。
5. 右側の **Assignees** で、自分を pull request の担当者に割り当てます。
6. pull request のコメントに 'Closes #2' と入力し、Issue #2 を自動リンクします。
7. **Create pull request** をクリックし、20 秒ほど待ちます。
8. pull request をマージします。
9. ブランチ 'fix-sidebar' を削除します。
10. 20 秒ほど待ってから、手順を読んでいるページ（README）を再読み込みします。[GitHub Actions](https://docs.github.com/en/actions) が自動で次の Step に更新します。

<footer>

<!--
  <<< Author notes: Footer >>>
  Add a link to get support, GitHub status page, code of conduct, license link.
-->

---

困ったとき: 講師に知らせてください &bull; [GitHub のステータスページを確認する](https://www.githubstatus.com/)

&copy; 2023 GitHub &bull; [Code of Conduct](https://www.contributor-covenant.org/version/2/1/code_of_conduct/code_of_conduct.md) &bull; [MIT License](https://gh.io/mit)

</footer>
