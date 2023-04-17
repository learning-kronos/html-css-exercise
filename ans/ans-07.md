## 解答例（演習7）

css/style.css

```css
header {
    background-color:#CCCCCC;
}

.menu-container {
    display: flex;
    flex-direction: row; 
}

.menu-item {
    display: block;
    padding: 10px 20px;
    font-size: 15pt;
    color: #0000FF;
    text-decoration-line: none;
}

.menu-item:hover {
    background-color: #0000AA;
    color: white;
}
```