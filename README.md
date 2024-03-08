# 自己紹介ページを作ってみよう

![完成をQRで確認しよう](./images/QR.png)

## 完成のリンク

[完成へのリンク](https://tec-yoshi-taka.github.io/js-paint-finish/)
<br><br>

---

---

## 自分の名前を書いてみよう

### 漢字

```HTML
<title>〇〇〇〇の自己紹介ページ</title>
```

```HTML
<h1>〇〇〇〇の自己紹介ページ</h1>
```

```HTML
<p class="txet">〇〇〇〇</p>
```

### ローマ字

```HTML
<small>Copyright &copy; 2024 〇〇〇〇 All Rights Reserved.</small>
```

---

## 学校を選んだ理由、希望職種

```HTML
<h3>東京電子専門学校を選んだ理由</h3>
<p class="txet">
  理由を書いてください。理由を書いてください。<br>
  理由を書いてください。
</p>
```

```HTML
<h3>将来就きたい職種</h3>
<p class="txet">
  希望職種を書いてください。<br>
  その理由も書きてください。
</p>
```

---

## 趣味

```HTML
<h3>趣味</h3>
<ul class="txet">
  <li>趣味①を書きてください。</li>
  <li>趣味②を書きてください。</li>
  <li>趣味③を書きてください。</li>
</ul>
```

---

## 背景色・文字色

### 見出し１

```css
h1 {
  /* 見出し１の文字色を変更 */
  color: #fff;
  font-size: 40px;
  font-weight: bold;
  text-shadow: 1px 1px 4px #aaaaaa;
}
```

### 見出し２

```css
h2 {
  /* 見出し２の背景色を変更 */
  background-color: #8d6212;
  /* 見出し２の文字色を変更 */
  color: #fff;
  text-align: center;
  font-weight: bold;
  font-size: 24px;
  letter-spacing: 2px;
  margin: 0 0 20px 0;
  padding: 10px 0 10px 0;
  border-radius: 10px;
}
```

---

## 背景画像

```css
body {
  /* 背景画像の変更 */
  background: url(../images/bg07.png);
  line-height: 1.5;
}
```

---
