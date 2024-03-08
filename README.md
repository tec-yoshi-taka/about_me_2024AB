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

## 色を増やしてみよう

```HTML
<li id="green"><i class="fas fa-fill-drip"></i></li>
<li id="yellow"><i class="fas fa-fill-drip"></i></li>
<li id="black"><i class="fas fa-fill-drip"></i></li>
```

---

## 線の色や太さを指定する

```javascript
//線の色
ctx.strokeStyle = "#ec5064";
//線の太さ
ctx.lineWidth = 2;
//線のボケ具合
ctx.shadowColor = "#ec5064";
```

---

## ペンの色と太さを変数に代入してみよう

```javascript
//ペンの色と太さを変数に代入してみよう
let penColor = "rgb(255,0,0)";
let penSize = 2;
```

---

## 線の色や太さを変更できるようにしよう

```javascript
//線の色
ctx.strokeStyle = penColor;
//線の太さ
ctx.lineWidth = penSize;
//線のボケ具合
ctx.shadowColor = penColor;
```

---

## クリックで色を変更してみよう

```javascript
//色を変更
colors.forEach((colorli) => {
  colorli.addEventListener("mousedown", (e) => {
    colors.forEach((clr) => {
      clr.classList.remove("active");
    });
    colorli.classList.add("active");
    style = window.getComputedStyle(e.target);
    penColor = style.getPropertyValue("color");
  });
});
```

---

## さらにペンを増やす（HTML）

```HTML
<!-- 好きなの色を増やそう -->
<li id="other"><i class="fas fa-fill-drip"></i></li>
```

## さらにペンを増やす（CSS）

```css
#color li#other {
  background-color: お好きな色;
}
#color li#other.active,
#color li#other:hover {
  color: お好きな色;
  background-color: #fff;
}
```

---
