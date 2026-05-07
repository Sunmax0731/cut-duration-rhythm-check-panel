# カット尺・リズム確認パネル

cut-duration-rhythm-check-panel は 動画編集者、ショート動画制作者、レビュー担当者 向けの closed alpha プロダクトです。カットごとの尺、意図、テンポ、違和感メモをまとめ、レビュー時の確認を短縮する。

## Source

- PICKUP Rank: 49
- Domain / Idea No: WindowsApp / 14
- Repository: cut-duration-rhythm-check-panel
- 主な公開先: GitHub Release / BOOTH
- created_idea: `D:/AI/WindowsApp/created_idea_014_cut-duration-rhythm-check-panel`
- 同梱ZIP: `D:/AI/WindowsApp/created_idea_014_cut-duration-rhythm-check-panel/idea_014_cut-duration-rhythm-check-panel.zip`
- 開始時 README: 存在しない


## Alpha Scope

- 代表シナリオ4件の自動検証
- 必須項目不足、警告、混在バッチの分類
- ui/ のホスト連携シェル
- QCDS、security/privacy、traceability、release checklist、manual test docs
- docs ZIP: `dist/cut-duration-rhythm-check-panel-docs.zip`

## Commands

```powershell
npm test
node src/cli/index.js samples/representative-suite.json
npm run build:docs
```

手動テストは Codex 側では未実施です。手順は `docs/manual-test.md` と `docs/strict-manual-test-addendum.md` にあります。

