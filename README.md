# 🌸 idea-garden

A personal space to collect, nurture, and turn app ideas into real projects.

**ひらめきを記録し、少しずつ育てて、いつかアプリにするための場所です。**

## 🌱 まずはアイデアを残す

**[新しいアプリアイデアを記録する](https://github.com/iwasaki-hub/idea-garden-/issues/new?template=app-idea.yml)**

1. 思いついたら GitHub Issues のフォームを開く
2. タイトルと「アイデアの概要」を書いて投稿する（まずはこれだけで OK）
3. あとから課題・機能・参考リンクを追記してアイデアを育てる
4. 具体化したら [詳細テンプレート](templates/app-idea.md) を使って `ideas/` に整理する
5. 開発を始めたら、新しいアプリのリポジトリを作り、相互にリンクする

投稿済みのアイデアは **[Issues 一覧](https://github.com/iwasaki-hub/idea-garden-/issues)** から振り返れます。

## 🌿 アイデアの成長ステージ

| ステージ | 状態 |
| --- | --- |
| 🌱 Seed | 思いついたことを記録 |
| 🌿 Exploring | 課題や可能性を検討 |
| 🪴 Planned | 実装したい内容が明確 |
| 🚀 Building | 開発中 |
| 🌸 Shipped | アプリを公開済み |

無理に順番どおり進める必要はありません。小さなメモから始めます。

## 📁 リポジトリ構成

```text
idea-garden/
├── README.md                       # このガイド
├── ideas/
│   └── README.md                   # 詳細化したアイデアの一覧・運用ルール
├── templates/
│   └── app-idea.md                 # アイデア詳細記録用テンプレート
└── .github/
    └── ISSUE_TEMPLATE/
        └── app-idea.yml            # スマホでも入力しやすい Issue フォーム
```

## ✨ 運用の考え方

- **記録のハードルを低くする**：最初から完成度を求めない
- **1アイデア = 1 Issue**：思考の変化もコメントで残す
- **詳しくなるほど整理する**：必要に応じて `ideas/<idea-slug>.md` を作る
- **開発リポジトリは分ける**：この場所をアイデアの原点として残す

> **公開リポジトリです。** 個人情報、APIキー、未公開の秘密情報などは書かないでください。
