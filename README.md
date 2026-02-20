# tamura-jspsych-demos

心理言語学の授業（関西大学外国語学部・3・4年次「心理言語学研究」）で扱う実験デモ集です。jsPsych を用いてブラウザ上で動作する形で実装しています。

**デモサイト（体験用）**
- https://tamura-jspsych-demo.netlify.app/

**紹介記事**
- https://tam07pb915.com/2026/01/26/jspsych-psycholinguistics-experiment-demos/

## 目的と位置づけ

本リポジトリは教育目的での利用を主目的としています。授業内で完結できるように，研究用実験ほどの厳密性は必ずしも担保していません。例えば，原著研究の手続きに近い形で再現しているものもあれば，「効果」自体を体験しやすくするために手続きを簡略化・変更しているものもあります。

## 個人情報・データ保存について

本デモは，参加者の反応データをサーバー上に保存しません。個人情報の収集も行いません。結果画面を閉じる，またはリロードすると表示内容は失われ，復元できません。

## デモ一覧

- Word superiority effect demo（word-superiority-effect-demo.html）
- Masked priming demo（masked-priming-demo.html）
- Masked morphological priming demo（masked-priming_morphological-demo.html）
- Semantic priming demo（semantic-priming-demo.html）
- Self-paced reading demo（spr-demo.html / spr-demo_jp.html）
- Time metaphors demo（time-metaphors.html）
- Color demo（color-demo.html）

注：各デモの説明はデモサイトの各ページに記載しています。

### ローカル環境での実行について

本リポジトリには jsPsych 本体および必要なファイルがすべて含まれているため，リポジトリをダウンロードすれば追加のインストールなしで実行できます。

多くの場合，HTMLファイル（例：`index.html`）をブラウザで直接開くことでも動作します。

ただし，ブラウザのセキュリティ制限（ローカルファイルアクセス制限）により，一部の環境では正しく動作しないことがあります。そのため，確実に動作させる方法として，簡易ローカルサーバーを使用する方法を推奨します。

#### 推奨方法（Pythonを使用）

```bash
cd public
python -m http.server 8000
```

その後，ブラウザで以下にアクセスしてください。

```
http://localhost:8000
```

この方法は，ブラウザの制限を回避し，Netlify環境と同じ条件で動作確認ができるため，最も確実です。


## フィードバック・要望

現状，Issue によるフィードバック受付を想定しています（今後運用方針を整備します）。「こういうデモがあると授業で助かる」といった提案がある場合は，扱っている原著論文の情報も合わせて共有してください。対応は保証できませんが，可能な範囲で検討します。

## ライセンス

MIT License（詳細は LICENSE を参照）。

## 引用（Citation）

授業資料や発表資料等で参照したい場合は，以下の形式を目安にしてください。

Tamura, Y. (2026). tamura-jspsych-demos: Psycholinguistics experiment demos built with jsPsych (Version 0.1). GitHub repository.
