## 解答例（演習8）

index.html

```html
<!DOCTYPE html>
<html lang="jp">
<head>
    <meta charset="UTF-8">
    <title>黒ノ巣屋書店</title>
    <link rel="stylesheet" type="text/css" href="css/style.css">
</head>
<body>
    <header>
        <img src="./img/kronos-books-logo.png">
        <nav class="menu-container">
            <a class="menu-item" href="./index.html">書籍一覧</a>
            <a class="menu-item" href="./contact.html">お問い合わせ</a>
        </nav>
    </header>
    <main>
        <article>
            <section>
                <h1>書籍一覧</h1>
                <table border="1">
                    <tr>
                        <th>#</th>
                        <th>カテゴリー</th>
                        <th>書籍名</th>
                        <th>著者</th>
                        <th>発行年</th>
                    </tr>
                    <tr>
                        <td>1</td>
                        <td>ITベーシック</td>
                        <td>IT基礎・コンピュータ基礎</td>
                        <td>山田　太郎</td>
                        <td>2023/03/12</td>
                    </tr>
                    <tr>
                        <td>2</td>
                        <td>ITベーシック</td>
                        <td>アルゴリズム</td>
                        <td>佐藤　華子</td>
                        <td>2023/03/15</td>
                    </tr>
                    <tr>
                        <td>3</td>
                        <td>Webテクノロジー</td>
                        <td>HTML/CSS</td>
                        <td>小林　一郎</td>
                        <td>2022/12/24</td>
                    </tr>
                    <tr>
                        <td>4</td>
                        <td>Webテクノロジー</td>
                        <td>JavaScript</td>
                        <td>鈴木　次郎</td>
                        <td>2022/11/11</td>
                    </tr>
                </table>
            </section>
        </article>
    </main>
</body>
</html>
```

<br>

css/style.css

```css
（中略）

main {
    margin: 20px;
}
```