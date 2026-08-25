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
  <<< Author notes: Course start >>>
  Include start button, a note about Actions minutes,
  and tell the learner why they should take the course.
-->

## ようこそ

履歴が長く積み重なったリポジトリで作業したことはありますか。関連する Issue や pull request を過去にさかのぼって探したり、ある変更を誰がコミットしたのかを突き止めたりした経験があるなら、作業場所をたどれることの大切さが分かるはずです。

- **対象**: 開発者、GitHub ユーザー、Git を使い始めた人、学生、管理者、チーム
- **学ぶこと**:
  - 関連する Issue と pull request を見つける。
  - 履歴を検索して背景を知る。
  - GitHub の中でつながりを作り、ほかの人が情報を見つけやすくする。
- **作るもの**: 既存のコミット、重複した Issue、直すべき内容の不具合を含むリポジトリ
- **前提**: 受講前に、GitHub Docs の [GitHub Quickstart](https://docs.github.com/en/get-started/quickstart) と GitHub Skills の [Introduction to GitHub](https://github.com/skills/introduction-to-github) に目を通しておくと理解しやすくなります。
- **所要時間**: 15 分以内で完了します。

コースで行うこと:

1. 重複した Issue を整理する。
2. 履歴からコミットを見つける。
3. 壊れたサイドバーを直す。

### コースの始め方

<!-- For start course, run in JavaScript:
'https://github.com/new?' + new URLSearchParams({
  template_owner: 'mamezou',
  template_name: 'skills-ja-connect-the-dots',
  owner: '@me',
  name: 'skills-connect-the-dots',
  description: 'My clone repository',
  visibility: 'public',
}).toString()
-->

[![start-course](https://user-images.githubusercontent.com/1221423/235727646-4a590299-ffe5-480d-8cd5-8194ea184546.svg)](https://github.com/new?template_owner=mamezou&template_name=skills-ja-connect-the-dots&owner=%40me&name=skills-connect-the-dots&description=My+clone+repository&visibility=public)

1. **Start course** を右クリックして、リンクを新しいタブで開きます。
2. 開いたタブでは、入力欄のほとんどが自動で埋まります。
   - Owner には、リポジトリを置く個人アカウントまたは Organization を選びます。
   - private リポジトリは [Actions の実行時間を消費する](https://docs.github.com/en/billing/managing-billing-for-github-actions/about-billing-for-github-actions)ため、public リポジトリを推奨します。
   - 下までスクロールし、フォーム下部の **Create repository** ボタンをクリックします。
3. 新しいリポジトリが作られたら 20 秒ほど待ち、ページを再読み込みします。新しいリポジトリの README に出る手順に従って進めてください。

<footer>

<!--
  <<< Author notes: Footer >>>
  Add a link to get support, GitHub status page, code of conduct, license link.
-->

---

困ったとき: 講師に知らせてください &bull; [GitHub のステータスページを確認する](https://www.githubstatus.com/)

&copy; 2023 GitHub &bull; [Code of Conduct](https://www.contributor-covenant.org/version/2/1/code_of_conduct/code_of_conduct.md) &bull; [MIT License](https://gh.io/mit)

</footer>
