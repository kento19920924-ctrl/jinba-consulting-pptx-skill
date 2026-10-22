---
name: consulting-pptx-skill
description: スライド設計規約 slide-rules.md を核に、経営会議品質のスライドを作るスキル。作成前に規約を読み、HTMLパーツ集（基本30＋追加35の65型）から該当パーツをコピーして組み、規約の範囲で型に囚われず調整し、check_deck.py の機械チェック FAIL 0 で仕上げる。型カタログはレイアウトの発想帳であり、合わせる対象ではない。既存の PowerPoint 資料を渡され、そこへ差し込むページを PPTX で求められたときだけ、その資料のマスターの上に直接組む（slide-rules §8.7）。トリガー例:「コンサル品質のスライドを作って」「規約に沿ったデッキで」「型カタログから選んで」「この pptx に足すページを同じ書式で」。
---

# コンサル型スライド作成スキル（プロジェクト用の入口）

このファイルは、リポジトリをプロジェクトスキルとして認識させるための入口だけを持つ。指示の本体はリポジトリ直下の `SKILL.md` にある。

1. 最初にリポジトリ直下の `SKILL.md`（このファイルから見て `../../../SKILL.md`）を全文読み、その手順に従う。
2. `SKILL.md` に出てくる `references/`・`templates/`・`scripts/`・`assets/`・`local/`・`tests/`・`examples/` などのパスは、すべて**リポジトリ直下からの相対パス**として扱う（`.claude/skills/consulting-pptx-skill/` からではない）。コマンドはリポジトリ直下で実行する。
3. Chrome・Chromium のパスと playwright の場所は `.claude/settings.json` の環境変数 `CHROME_PATH`・`PLAYWRIGHT_MODULE_DIR` で渡している。`SKILL.md` にある macOS の Chrome のパス（`/Applications/Google Chrome.app/...`）は、この環境では `$CHROME_PATH` に読み替える。
