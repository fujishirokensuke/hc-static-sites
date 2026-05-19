# OPS_LOG — hc-static-sites

## 2026-05-19 — repo新規作成 + GitHub Pages有効化（初回）

**何を**
- GitHub repo `fujishirokensuke/hc-static-sites` を **public** で新規作成
- GitHub Pages を `main` ブランチ / `/`（root）で有効化（HTTPS強制）
- `csb/index.html` に Healing Connections の standalone HTML（17MB、画像インライン版）を配置

**なぜ**
- 健介の手元（`~/Desktop/CSB/Healing Connections - standalone.html`）にあった成果物を、筧さん（HC関係者）が手軽にリンクで見られるようにするため
- CLAUDE.md の方針「HC内部資料で外部公開OKなものは hc-static-sites（public）+ GitHub Pages」に従う
- デスクトップは消える運用なので、SSoT を GitHub に移した

**結果**
- ✅ push成功（commit `215ca07`）
- ✅ Pages build `built` を確認
- ✅ `https://fujishirokensuke.github.io/hc-static-sites/csb/` が HTTP 200 で配信中

**公開URL**
- https://fujishirokensuke.github.io/hc-static-sites/csb/

**メモ**
- 中身は公開OKと健介に確認済み（公開LP相当の内容）
- 17MB単一HTMLだがGitHub Pagesの100MB/file制限内
- 将来別資料を追加する場合は `<slug>/index.html` 形式で追加し、README.md の表を更新する
