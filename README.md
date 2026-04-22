# PROMPTER STUDIO

Concert Cueing Prompter System — コンサート演出家向け、舞台モニター用プロンプター。

## 機能

- 複数セットリスト管理（localStorage永続化）
- 歌詞ページ / MCページ / INTRO / OUTRO / 間奏 / NEXT SONG
- メンバー管理（色・立ち位置・グループ分け）
- ビジュアル立ち位置表示（-4〜+4スケール、衝突回避つき）
- CUE（演出指示）・コード譜・立ち位置ブロック
- 外部ディスプレイ出力（16:9、BroadcastChannel同期）
- ページごとのオーバーレイ編集（テキスト・図形・矢印）
- ページごとの歌詞オーバーライド（改行・色変更）
- カラム幅リサイズ・レイアウトカスタマイズ

## 公開URL

https://nomura0913-hu.github.io/prompter-studio/

## ローカル実行

```bash
# どのWebサーバーでもOK
python3 -m http.server 8080
# または
npx serve
```

ブラウザで http://localhost:8080 を開く。
