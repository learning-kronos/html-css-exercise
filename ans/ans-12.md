## 解答例（演習5）

index.html

```html
(中略)

    <main>
        <article>
            <section>
                <h1>お問い合わせ</h1>
                <p>必要事項をご入力の上、送信ボタンをクリックしてください。</p>
                <form>
                    <div>
                        <label for="name">お名前&ensp;<span class="required-label">必須</span></label><br>
                        <input type="text" id="name" maxlength="30" placeholder="30文字以内" required>
                    </div>
                    <br>
                    <div>
                        <label for="tel">お電話番号</label><br>
                        <input type="tel" id="tel" maxlength="11" placeholder="11文字以内（ハイフン除く）">
                    </div>
                    <br>
                    <div>
                        <label for="email">メールアドレス&ensp;<span class="required-label">必須</span></label><br>
                        <input type="mail" id="mail" maxlength="50" placeholder="50文字以内" required>
                    </div>
                    <br>
                    <div>
                        <label for="content">お問い合わせ内容&ensp;<span class="required-label">必須</span></label><br>
                        <textarea id="content" rows="10" cols="50" maxlength="500" placeholder="500文字以内" required></textarea>
                    </div><br>
                    <input type="submit" id="btn-send" value="送信">
                </form>
            </section>
        </article>
    </main>

(中略)
```

<br>

css/style.css

```css
（中略）

.required-label {
    background-color: #BB0000;
    color: #FFFFFF;
    font-size: 0.625rem;
    padding: 0px 3px;
}
```