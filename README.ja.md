# PowerMTML-ST2 について

Sublime Text 2 PowerMTML Package は Sublime Text 2 で PowerCMS 及び Movable Type のテンプレートタグ（MTML）の入力補完を提供するパッケージです。  
Movable Typeの標準タグを補完出来るようにするには「[MTML-ST2](https://github.com/bit-part/MTML-ST2)」のインストールが必要です。

## インストール

### Package Control を使ったインストール

_※あらかじめ Package Control をインストールしておく必要があります。_

Package Control を起動し「Add Repository」を選択し、リポジトリのURL「 https://github.com/bit-part/PowerMTML-ST2 」を入力します。

再度 Package Controlを起動し「Install Package」を選択し、「PowerMTML-ST2」を選択します。

### Git を使ったインストール

_※あらかじめ Git をインストールしておく必要があります。_

Sublime Text 2 の Packages ディレクトリに移動し、git clone します。

```
cd /path/to/your/Sublime Text 2/Packages
git clone https://github.com/bit-part/PowerMTML-ST2
```

### zip ファイルによるインストール

zip ファイルをダウンロードし、Sublime Text 2 の Packages ディレクトリに展開します。

## 動作方法

HTMLとPHPの場合、「<」を入力した時点で自動で補完されます。  
拡張子を .mtml や .tmpl と設定している場合は、シンタックスモードをhtmlにすれば補完されます。

## 表示サンプル

![表示サンプル](http://bit-part.github.com/data/img_powermtml-st2.png)

* [B]：Blockタグ
* [F]：Functionタグ
* [C]：Conditionalタグ

---

_Movable Type は Six Apart, Ltd. の登録商標です。_
_PowerCMS はアルファサード株式会社の登録商標です。_