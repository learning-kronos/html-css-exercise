## 解答例（演習5）

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
</body>
</html>
```

<br>

css/style.css

```css
header {
    background-color: #CCCCCC;
}

.menu-container {
    display: flex;
    flex-direction: row; 
}

.menu-item {
    display: block;
    padding: 10px 20px;
    font-size: 15pt;
}
```