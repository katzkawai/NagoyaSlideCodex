# Nagoya Slide Deck

このリポジトリには、名古屋でのスライド資料を以下の2種類の形式で収録しています。

- **Reveal.js版**: `nagoya.html`
- **Impress.js版**: `nagoya-impress.html`

## 概要

- **Reveal.js版**は、16:9アスペクト比、余白（マージン）の調整、自動フォントスケーリングを有効にした構成です。
- **Impress.js版**は、座標ベースのダイナミックなアニメーション表示が可能です。

## 必要環境

- モダンなウェブブラウザ（Chrome, Firefox, Safari, Edge など）
- （オプション）ローカルHTTPサーバー（Python 3）

## 使い方

### 1. HTTPサーバー経由で開く（推奨）

```bash
python3 -m http.server 8000
```

ブラウザで以下のURLにアクセスしてください。

- Reveal.js版: http://localhost:8000/nagoya.html
- Impress.js版: http://localhost:8000/nagoya-impress.html

### 2. ファイルを直接開く

`nagoya.html` または `nagoya-impress.html` をブラウザで直接開くこともできます。  
※ ブラウザのセキュリティ制限により正しく動作しない場合があります。

## Impress.js版での操作

| 操作                   | キー                              |
| ---------------------- | --------------------------------- |
| 次のステップへ         | → / ↓ / PageDown / Space          |
| 前のステップへ         | ← / ↑ / PageUp / Backspace        |
| 概要モードへ (Overview) | ESC / O                           |
| 概要モード解除         | ESC または任意のスライドをクリック |
| 全画面切替             | F                                 |
| リセット (最初に戻す)   | R                                 |
| 印刷用スナップショット | P                                 |

---

本リポジトリの内容を活用し、効果的なプレゼンテーションを行ってください。