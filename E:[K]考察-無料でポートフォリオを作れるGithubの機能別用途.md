取れる手段が以下の通り考えられる

### Github Pages
一番簡単で分かりやすい方法だろう。
カスタマイズ性は高いが、プレビューがないため記事ページをいちいちpushしてbuildを待ってcache（ブラウザではなく、Githubホスティングサーバー）が更新されるまで待つ必要がある。
たとえば、curlでrawページを拾ってきて処理をするスクリプトを作っているイメージをしてもらえれば分かりやすいか。相当イラつくので、長期的な運用は難しい。

### 外部ホスティングサービス連携
Github Pagesと同様の問題がある。本番用に公開しているサーバーとして使うのは良いが、Github Pages同様に開発環境として適さない。
NetlifyやFirebaseなど色々なサービスがある。

Googleサイトスピード測定で調べたところ、日本からアクセスする場合はGithub Pagesより早い事が多い（かもしれない）

### Gist
Gistは表示されるファイルの順番を制御できないながら、公開設定を操作できるのが強み。
公開はそのままpublicだが、非公開は厳密にはprivateではなく、URLを知っていれば誰にでもアクセスができる。
秘匿性を上げるならGithubリポジトリで管理し、特定多数にアクセスできる情報はGistに置くのも一手だろう。

### Githubリポジトリ(アカウント名、アカウント名.github.ioなど)
上記２つと違って即時更新されるのと、マークダウンがそのまま使えるのは大きい。(Github PagesもTheme Chooserから指定すればjekyllとなり、マークダウンが使えるし、markdown-wasm等を使えばパースしてくれる）
ただし、レイアウトはGithubの仕様に沿うため、大々的に何かできるわけではない。

### Github Wiki
Wikiにプロフィールを書くという印象はなかなかないだろうが、一つのサイトとして見た場合にWikiシステムは優秀。
たとえば[登録したプロフィールをまとめただけのリポジトリ](https://github.com/shimajima-eiji/profile)などは、ソース管理をするよりWiki形式で管理する方が読みやすい。

### Github Project
この方法はポートフォリオを作成するという観点ではおすすめできない。Projectに紐づくのはIssueなので、専用のリポジトリを一つ作ることになる。
Beta版でページをテーブル/看板形式で見せられるので、うまく活用できれば面白い事ができそう。

---

### Github以外の方法
本旨とそれるが、当然考えるべき手段を比較してみよう。

#### WordPress(レンタルサーバー、VPSなど)
よく使われる方法。慣れないうちは覚える事が多くて大変だが、中長期的に考えると一番安定していると思われる。
比較的コストが掛かりやすい（無料でできなくはない）

#### ブログ
よく使われる方法。無料の場合は意図しない広告が差し込まれるのでポートフォリオにしては残念。
有料でもよいが、各社サービスの仕様に引きずられるので、エンジニアとしてはあまり嬉しくはない。

#### SNSアカウント(主にTwitter)
よく使われる方法。人となりを知るのには良いが、面倒くさいので見られない（評価されない）
情報を整理するのが苦手なので、何かしら方策を考えるべきだろう。

#### ポートフォリオサービス
最近は色々なポートフォリオサービスがあるが、どれも独自路線を突っ切っていて見るのが大変。
有名どころは[Linkedin](https://jp.linkedin.com/)だろうか。
