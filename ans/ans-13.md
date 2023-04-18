## 解答例（演習13）

contact.html

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
            <a class="menu-item" href="index.html">書籍一覧</a>
            <a class="menu-item" href="contact.html">お問い合わせ</a>
        </nav>
    </header>
    <main>
        <article>
            <section>
                <h1>お問い合わせ</h1>
                <p>必要事項をご入力の上、送信ボタンをクリックしてください。</p>
                <form>
                    <div>
                        <label for="name">お名前</label><br>
                        <input type="text" id="name" maxlength="30" placeholder="30文字以内" required>
                    </div>
                    <br>
                    <div>
                        <label for="tel">お電話番号</label><br>
                        <input type="tel" id="tel" maxlength="11" placeholder="11文字以内（ハイフン除く）">
                    </div>
                    <br>
                    <div>
                        <label for="email">メールアドレス</label><br>
                        <input type="mail" id="mail" maxlength="50" placeholder="50文字以内" required>
                    </div>
                    <br>
                    <div>
                        <label for="content">お問い合わせ内容</label><br>
                        <textarea id="content" rows="10" cols="50" maxlength="500" placeholder="500文字以内" required></textarea>
                    </div><br>
                    <input type="submit" id="btn-send" value="送信">
                </form>
            </section>
        </article>
    </main>
</body>
</html>
```