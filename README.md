# CSSアニメーションまとめ

CSS の `transition` と `animation` の動きを、実際に触って確かめられる学習用ページです。
各カードの「VIEW CSS」を押すと、その動きのコードを見ることができます。JavaScript は使っていません。

**デモ：** https://huruuuuuugi.github.io/coding-matome/

## 内容

### transition（状態が変わるときの動き）

1. ボタン
2. テキストリンクの下線
3. カードのホバー（画像のズーム＋オーバーレイ）
4. グローバルナビ＆ドロップダウン
5. フォームのフォーカス演出
6. トグルスイッチ
7. アコーディオン

### animation（時間に沿って自動で動く）

1. ローディング表現 4種
2. スケルトンスクリーン（読み込み中の骨組み）
3. 登場演出（フェードイン＋時間差）：`animation-timeline: view()` を使い、スクロール量に合わせて表示

## ファイル構成

```
.
├── index.html
├── css/
│   └── style.css
└── images/
```

## 対応ブラウザ

最新の Chrome / Edge / Safari で確認しています。
スクロール連動の登場演出（`animation-timeline: view()`）に対応していないブラウザでは、画像が最初から表示されます。
