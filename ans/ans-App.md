## 解答例（追加演習）

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
                    <hr>
                    <div class="input-group">
                        <label for="name">お名前&ensp;<span class="required-label">必須</span></label>
                        <input type="text" id="name" maxlength="30" placeholder="30文字以内" required>
                    </div>
                    <hr>
                    <div class="input-group">
                        <label for="tel">お電話番号</label>
                        <input type="tel" id="tel" maxlength="11" placeholder="11文字以内（ハイフン除く）">
                    </div>
                    <hr>
                    <div class="input-group">
                        <label for="mail">メールアドレス&ensp;<span class="required-label">必須</span></label>
                        <div>
                            <input type="email" id="mail1" class="mail" maxlength="50" placeholder="50文字以内" required>
                            <div class="check-div">（確認用）</div>
                            <input type="email" id="mail2" class="mail" maxlength="50" placeholder="50文字以内" required>
                        </div>
                    </div>
                    <hr>
                    <div class="input-group">
                        <label for="content">お問い合わせ内容&ensp;<span class="required-label">必須</span></label>
                        <textarea id="content" rows="10" cols="50" maxlength="500" placeholder="500文字以内" required></textarea>
                    </div>
                    <div class="text-center">
                        <input type="submit" id="btn-send" class="btn-primary" value="送信">
                    </div>
                </form>
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

.input-group {
    display: flex;
    flex-direction: row;
    margin: 20px;
}

.input-group label {
    width: 180px;
}

.input-group input, .input-group textarea, .input-group div {
    flex-grow: 1;
}

.mail {
    width: 100%;
    box-sizing: border-box;
}

.check-div {
    margin-top: 5px;
    font-size: 0.875rem;
}

.btn-primary {
    background-color: #0066FF;
    color: #FFFFFF;
    border-radius: 5px;
    padding: 5px 15px;
    border: none;
}

.text-center {
    text-align: center;
}
```