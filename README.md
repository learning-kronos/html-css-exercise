# HTML/CSS演習

本演習問題用のフォルダ（以下、演習フォルダ）を作成して各演習を進めてください。

<br>

演習を進めながら書籍一覧ページとお問い合わせページを作成していきます。以下のようなファイルの構成で作成します。

<img src="./img/file-composition.png" width="400">

<br><br>

index.html（書籍一覧ページ）とcontact.html（お問い合わせページ）は以下の構成で作成します。

<img src="./img/page-composition.png">

<br><br>

## 1 書籍一覧（index.html）

### 演習1（画像の表示）

演習フォルダにimgフォルダを作成し、以下の画像をkronos-books-logo.pngというファイル名で保存します。<br>演習フォルダ直下にindex.htmlを作成し、保存した画像をheader部に表示します。画像は相対パスで指定してください。

<img src="./img/kronos-books-logo.png" alt="黒ノ巣屋書店">

<br><br>

[解答例](ans/ans-01.md)

<br><br>

### 演習2（背景色の指定）

CSS（スタイルシート）でheaderタグの背景色を「#CCCCCC」に変更します。

<img src="./img/ex-02.png" width="600">

<br><br>

[解答例](ans/ans-02.md)

<br><br>

### 演習3（メニューリンクの追加）

タイトルの下に「書籍一覧」リンクと「お問い合わせ」リンクを追加します。リンクはnavタグ内に配置します。

<img src="./img/ex-03.png" width="600">

<br><br>

[解答例](ans/ans-03.md)

<br><br>

### 演習4（メニューリンクのブロック化と装飾）

メニューリンクのクラス名を「menu-item」とし、以下のスタイルシートを適用します。

- ブロック化（ display: block; ）
- 内部余白 - 上下：10px、左右：20px
- フォントサイズ - 1rem

<img src="./img/ex-04.png" width="600">

<br><br>

[解答例](ans/ans-04.md)

<br><br>

### 演習5（メニューリンクの整列）

メニューリンクを左から横並びに配置します。

<img src="./img/ex-05.png" width="600">

<br><br>

[解答例](ans/ans-05.md)

<br><br>

### 演習6（メニューリンクの追加装飾）

メニューリンクを青文字にし、文字の下線を非表示にします。

<img src="./img/ex-06.png" width="600">

<br><br>

[解答例](ans/ans-06.md)

<br><br>

### 演習7（メニューリンクのマウスオーバー）

メニューリンクにマウスオーバーした時に文字色と背景色を以下のようにします。

- 文字色 - 白
- 背景色 - R:0、G:0、B:170

<img src="./img/ex-07.png" width="600">

<br><br>

[解答例](ans/ans-07.md)

<br><br>

### 演習8（書籍一覧の表示）

sectionタグ内に次のような書籍一覧表を追加します。表のボーダーも表示しますが、後の演習でCSSによるボーダーに変更します。また、mainタグに対して外部余白として上下左右に「20px」を指定します。

<img src="./img/ex-08.png" width="600">

<br><br>

[解答例](ans/ans-08.md)

<br><br>

### 演習9（書籍一覧のボーダー）

書籍一覧表のボーダーをCSSで表現します。また、表の項目の背景色を変更します。

- ボーダー - 線の太さ：1px、線の色：黒、線の形式：1本線
- 項目の背景色 - R:142、G:184、B:255

<img src="./img/ex-09.png" width="600">

<br><br>

[解答例](ans/ans-09.md)

<br><br>

### 演習10（ページ全体の余白除去）

ページ全体の周りにある余白を消去します。

> Chromeの開発者ツールを使って、どこに余白ができているのか確認してみてください。

<img src="./img/ex-10.png" width="700">

<br><br>

[解答例](ans/ans-10.md)

<br><br>

## 2 お問い合わせフォーム（contact.html）

### 演習11（お問い合わせフォームの作成）

次のようなお問い合わせフォームを作成します。

<img src="./img/ex-11_1.png" width="600">

| 項目 | タグ | type属性 | 概要 |
|:--------|:---:|:---:|:----|
| お名前 | input | text | ID: name<br>最大入力文字数: 30<br>プレースホルダー: "30文字以内"<br>入力必須 |
| お電話番号 | input | tel |ID: tel<br>最大入力文字数: 11<br>プレースホルダー: "11文字以内（ハイフン除く）" |
| メールアドレス | input | email |ID: mail<br>最大入力文字数: 50<br>プレースホルダー: "50文字以内"<br>入力必須 |
| お問い合わせ内容 | textarea | - | ID: content<br>縦幅: 10<br>横幅: 50<br>最大入力文字数: 500<br>プレースホルダー: "500文字以内"<br>入力必須 |
| 送信 | input | submit | ID: btn-send |

※上記項目をformタグ内に配置してください。

<br>

必須項目が未入力の状態で、送信ボタンをクリックすると、入力を促すメッセージが表示されることを確認しましょう。

<img src="./img/ex-11_2.png" width="600">

<br><br>

[解答例](ans/ans-11.md)

<br><br>

### 演習12（必須バッチの追加）

必須項目のラベルの横に必須バッチを追加します。

<img src="./img/ex-12.png" width="500">

<br><br>

[解答例](ans/ans-12.md)

<br><br>

### 演習13（画像のリンク化）

黒ノ巣屋書店のロゴ（画像）をクリックすると、書籍一覧（index.html）を表示します。

<img src="./img/ex-13.png" width="700">

<br><br>

[解答例](ans/ans-13.md)

<br><br>

ここまでで一通りページは完成です。お疲れ様でした。

<br><br>

### 追加課題（デザインの調整）

お問い合わせ画面を次のように整形にしてみましょう。

<img src="./img/ex-14.png" width="700">

<br><br>

[解答例](ans/ans-App.md)