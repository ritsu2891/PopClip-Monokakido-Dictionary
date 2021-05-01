# PopClip-Monokakido-Dictionary

![Usage](https://cdn.rpaka.dev/useimage/popclip-monokakido/usage_fix.gif)

選択した文字を[物書堂の「辞書」アプリ](https://www.monokakido.jp/ja/dictionaries/app/)で検索するための[PopClip](https://pilotmoon.com/popclip/)の拡張です。

# 使い方

## インストール
このリポジトリの Release から `Monokakido-Dictionary.popclipextz` をダウンロードしてダブルクリックでインストールできます。

普通は必要ないと思いますが、以下の方法で `popclipextz` ファイルを作成できます。

1. 本リポジトリをクローンする
2. 本リポジトリのルートディレクトリで `build.sh` を実行する

```bash
$ zsh build.sh
```

## 単語の検索
PopClipを起動して単語を選択すると、新たに物書堂の辞書アプリのアイコン（ <img style="height: 1em;" src="https://cdn.rpaka.dev/useimage/popclip-monokakido/Dictionary.png" /> ）が追加されているのでそれをクリックすると物書堂の辞書アプリで検索結果が表示されます。