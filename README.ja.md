# PowerMTML Completions について

<<<<<<< HEAD
PowerMTML Completions は Sublime Text 2 で PowerCMS 及び Movable Type のテンプレートタグ（MTML）の入力補完を提供するパッケージです。  
=======
PowerMTML Completions は Sublime Text 2 で PowerCMS 及び Movable Type のテンプレートタグ（MTML）の入力補完を提供するパッケージです。
>>>>>>> refs/heads/develop
Movable Typeの標準タグを補完出来るようにするには「[MTML Completions ](https://github.com/bit-part/MTML-ST2)」のインストールが必要です。

## インストール

### Package Control を使ったインストール

_※あらかじめ Package Control をインストールしておく必要があります。_

Package Control を起動し「Add Repository」を選択し、リポジトリのURL「 https://github.com/bit-part/PowerMTML-ST2 」を入力します。

再度 Package Controlを起動し「Install Package」を選択し、「PowerMTML Completions」を選択します。

### Git を使ったインストール

_※あらかじめ Git をインストールしておく必要があります。_

Sublime Text 2 の Packages ディレクトリに移動し、git clone します。

```
cd /path/to/your/Sublime Text 2/Packages
git clone https://github.com/bit-part/PowerMTML-ST2
```

### zip ファイルによるインストール

zip ファイルをダウンロードし、Sublime Text 2 の Packages ディレクトリに展開します。

<<<<<<< HEAD
## 動作方法

HTMLとPHPの場合、「<」を入力した時点で自動で補完されます。  
拡張子を .mtml や .tmpl と設定している場合は、シンタックスモードをhtmlにすれば補完されます。

=======
## 設定

Preferences > Settings - User（command + ,）に以下の項目を設定するとこでテンプレートタグの書式等を変更できます。

### mtml_prefix

ここで設定した値がテンプレートタグの接頭辞になります。mtml_prefix を設定しない場合は mt: になります。

  設定無し => <mt:EntryTitle />
  "mtml_prefix": "MT:" => <MT:EntryTitle />
  "mtml_prefix": "MT"  => <MTEntryTitle />

### mtml_function_tag_type

ファンクションタグの書式を変更できます。設定できる値は dollar または none です。

  設定無し => <mt:EntryTitle />
  "mtml_function_tag_type": "dollar" => <$mt:EntryTitle$>
  "mtml_function_tag_type": "none" => <mt:EntryTitle>

## 動作方法

HTMLとPHPの場合、テンプレートタグについては「<」を入力した時点で自動で補完されます。  
拡張子を .mtml や .tmpl と設定している場合は、シンタックスモードをhtmlにすれば補完されます。

モディファイアについては、スペースに続けて数文字入力したあとに「Edit > Show Completions」（control + space）を実行すると補完されます。
なお、ショートカットキーがOSのショートカットキーと衝突している場合は、事前にどちらかを変更する必要があります。

>>>>>>> refs/heads/develop
## 表示サンプル

![表示サンプル](http://bit-part.github.com/data/img_powermtml-st2.png)

* [B]：Blockタグ
* [F]：Functionタグ
* [C]：Conditionalタグ

---

_Movable Type は Six Apart, Ltd. の登録商標です。_
_PowerCMS はアルファサード株式会社の登録商標です。_
