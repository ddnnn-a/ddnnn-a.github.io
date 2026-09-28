# ddnnn-a.github.io

SidePin の配布サイトを `14firm-dev/sidepin-dist` に移転したあとも、旧 URL
`https://ddnnn-a.github.io/sidepin/` を生かし続けるためのミラーです。

- `sidepin/appcast.xml` … 既存ユーザーの自動更新（Sparkle）が参照するフィード。**リリースのたびに `14firm-dev/sidepin-dist` の appcast.xml と同期すること**
- `sidepin/index.html` … ランディングページ。外部に出回っている旧リンク用

**このリポジトリを消すと既存ユーザーに自動更新が届かなくなります。**
また `github.com/ddnnn-a/sidepin` という名前のリポジトリを新たに作ると、
リリース資産へのリダイレクト（`github.com/ddnnn-a/sidepin/releases/...` → `14firm-dev/sidepin-dist`）が壊れるので作らないこと。
