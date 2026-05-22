# Path of Exile 2 — The Runes of Aldur (0.5.0) 日本語要約

Path of Exile 2 バージョン 0.5.0「Return of the Ancients / アルダーのルーン リーグ」公式パッチノートの**非公式・個人用日本語要約**です。

## 内容

全 25 セクションを 9 ソース HTML にまとめています:

| # | ソース | 内容 |
|---|---|---|
| 01 | リーグ概要 | レムナント、ヴェリシウム・ルーンフォージング、海洋探索、チャレンジ |
| 02 | エンドゲーム改修「神性の起源」 | 要塞・先人の塔・神性のアービター・アトラスの導師 |
| 03 | 既存リーグメカニクス更新 | Delirium / Breach / Ritual / Vaal / Abyss / Expedition / Other |
| 04 | キャンペーン ＆ プレイヤー | 新Ascendancy 2種、リネージサポート 21種、ユニーク 42種 |
| 05 | アセンダンシー ＆ パッシブツリー | 6 Ascendancy 変更 + パッシブツリー 300+ ノード拡張 |
| 06 | スキル ＆ サポート変更 | 36 スキル + 26 サポート個別変更 |
| 07 | ユニーク ＆ アイテム変更 | 29 ユニーク変更 + 8 カテゴリのアイテム変更 |
| 08 | モンスター/クエスト/UI/MTX | エンドゲーム周辺の調整 |
| 09 | バグ修正 | 127 項目を 7 カテゴリで整理 |

## 特徴

- **完全日本語化**: 固有名詞は [poe2db.tw/jp](https://poe2db.tw/jp/) で確認した正式日本語訳を採用
- **暫定訳**: poe2db 未収録の用語（特に新規ジェム類）は文脈から自然な暫定訳を当て、ホバーで原語を表示
- **用語辞書**: [`assets/glossary.json`](assets/glossary.json) に 760+ 語の英日対応表
- **SVG 図解**: 主要メカニクス（Remnant スロット、Runeforging フロー、海洋探索階層、要塞導線、導師ノード）
- **PoE2 世界観のダークテーマ**: 単一の `style.css` で統一

## 構成

```
├── index.html              ← ハブ (ソース一覧)
├── sources/                ← 9 ソース HTML
│   ├── 01_league-overview.html
│   ├── 02_endgame-overhaul.html
│   ├── ...
│   └── 09_bug-fixes.html
└── assets/
    ├── style.css           ← 共通スタイル
    └── glossary.json       ← 用語辞書 (760+ 語)
```

## 表示方法

- ローカル: `index.html` をブラウザで開く
- GitHub Pages 等で公開する場合: ルート直下を公開すれば、相対パスで動作

## 用語の確からしさについて

- `status: "verified"` — poe2db.tw/jp で日本語訳を直接確認したもの
- `status: "provisional"` — 当ドキュメント独自の暫定訳。公式日本語名が判明次第更新予定

## 出典・著作権

- **原典**: [Path of Exile 2: Patch Notes 0.5.0 (公式フォーラム)](https://www.pathofexile.com/forum/view-thread/3932540)
- **ゲーム内容・原文の権利**: © Grinding Gear Games
- **本日本語要約**: ファンによる非公式翻訳。GGG とは無関係です。

本ドキュメントの翻訳・要約部分は学習・調査目的の二次的著作物です。商業利用は想定しておらず、公式情報を保証するものでもありません。正確な情報は必ず公式ソースを参照してください。

## ライセンス

本リポジトリの **HTML / CSS / JSON コードおよび翻訳文** は MIT License 相当で自由に再利用可能です。
ただし上記の通り、PoE2 のゲーム内容・固有名詞・設定の権利は Grinding Gear Games に帰属します。
