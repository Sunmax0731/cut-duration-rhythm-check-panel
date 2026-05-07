# 要件定義

## 目的

カット尺・リズム確認パネル は、動画編集者、ショート動画制作者、レビュー担当者 が カットごとの尺、意図、テンポ、違和感メモをまとめ、レビュー時の確認を短縮する。

## Source

- PICKUP Rank: 49
- Domain / Idea No: WindowsApp / 14
- Repository: cut-duration-rhythm-check-panel
- created_idea: `D:/AI/WindowsApp/created_idea_014_cut-duration-rhythm-check-panel`
- ZIP: `D:/AI/WindowsApp/created_idea_014_cut-duration-rhythm-check-panel/idea_014_cut-duration-rhythm-check-panel.zip`
- README確認: 開始時点では正式 repo が存在しないため、README.md は存在しない。

## Functional Requirements

- R1: clipId、durationSec、rhythmIntent、reviewNote を必須項目として検査する。
- R2: 必須項目不足は fail として分類する。
- R3: `tempoRisk` が true の場合は warning として分類し、手動確認理由を返す。
- R4: 複数アイテムの mixed-batch を pass / warning / fail に集計する。
- R5: 結果を CLI と docs/release evidence で再利用できる形にする。

## Non Functional Requirements

- UTF-8 で Markdown / JSON / JS / HTML / Python を保存する。
- 外部通信を既定で行わず、サンプルとローカル入力だけで検証できる。
- 手動テスト未実施であることを release 前 docs に明記する。

