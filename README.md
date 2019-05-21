name: inverse
layout: true
class: center, middle, inverse
---
# MonacaEasyStartApp
富士通クラウドテクノロジーズ株式会社

.right[<img src="readme-img/takano.png" alt="takano.png" width="150px">]

.footnote[
20190804
]

---
layout: true
class: center, middle, inverse_sub
---
## はじめに

---
layout: false
### 概要

自己紹介アプリを使ってみんなに自己紹介をしよう！


---
### 今日体験する内容
#### 「自己紹介アプリ」を作りましょう
hogehoge

1. 下書き
1. Monacaの準備
1. Monacaの練習
1. コーディング①（パーツの書き方）
1. コーディング②（アレンジの仕方）
1. TRY：レベルアップコーディング
  <!-- * mBaaSとは
  * mBaaSの準備
  * コーディング（イイねボタン）
  * コーディング（コメント欄） -->

---
layout: true
class: center, middle, inverse_sub
---
## 1. 下書き

---
layout: false
### 1. 下書き

ワークシートを使って作りたいWebページを下書きする


---
layout: true
class: center, middle, inverse_sub
---
## 2. Monacaの準備

---
layout: false
### 2. Monacaの準備

ブラウザの準備をする

* [Chrome](https://www.google.com/chrome/) 最新版

アカウントを作成する

* [Monaca](https://monaca.mobi/ja/signup) 利用登録（無料）

スマホがあれば、デバッガーもあると面白い

* [Monacaデバッガー](https://ja.monaca.io/debugger.html) 最新版

---
layout: false
### 2. Monacaの準備

プロジェクトを作る

.center[<img src="readme-img/Monaca01.png" alt="Monaca01.png" width="400px">]

---
### 2. Monacaの準備

最小限のテンプレート

.center[<img src="readme-img/Monaca02.png" alt="Monaca02.png" width="400px">]

---
### 2. Monacaの準備


.center[<img src="readme-img/Monaca03.png" alt="Monaca03.png" width="400px">]

---
### 2. Monacaの準備


.center[<img src="readme-img/Monaca04.png" alt="Monaca04.png" width="400px">]

---
### 2. Monacaの準備

右側

.center[<img src="readme-img/Monaca05.png" alt="Monaca05.png" width="400px">]

---
### 2. Monacaの準備

ここを触っていくよ

.center[<img src="readme-img/Monaca06.png" alt="Monaca06.png" width="700px">]

---
layout: true
class: center, middle, inverse_sub
---
## 3. Monacaの練習

---
layout: false
### 3. Monacaの練習

`<body>`と`</body>`の間に書かれた文字がプレビュー画面に出ているね

.center[<img src="readme-img/Monaca06.png" alt="Monaca06.png" width="700px">]

---
### 3. Monacaの練習

編集してみようか

.center[<img src="readme-img/Monaca07.png" alt="Monaca07.png" width="700px">]

---
### 3. Monacaの練習

ん？編集したけどプレビュー画面が変わらないって？

保存が必要だね。　Ctrl + S

---
### 3. Monacaの練習

変わったね

.center[<img src="readme-img/Monaca08.png" alt="Monaca08.png" width="700px">]

---
layout: true
class: center, middle, inverse_sub
---
## 4. コーディング①（パーツの書き方）

---
layout: false

### 4. コーディング①（パーツの書き方）

下書きを元に、`<body>`と`</body>`の間を編集して自己紹介アプリを作ってみよう

* 見出し（タイトル・サブタイトル）

```html
<h1>見出し1</h1>
<h2>見出し2</h2>
<h3>見出し3</h3>
・
・
・
```

.center[<img src="readme-img/Monaca09.png" alt="Monaca09.png" width="400px">]


---
### 4. コーディング①（パーツの書き方）

* 段落（自己紹介文）

```html
<p>段落1</p>
<p>段落2</p>
<p>段落3</p>
```

.center[<img src="readme-img/Monaca10.png" alt="Monaca10.png" width="400px">]

---
### 4. コーディング①（パーツの書き方）

見出しと段落を組み合わせて下書きの内容を画面の中に作ってみましょう

```html
<h1>私のホームページアプリ</h1>
<p>私の名前は○○　○○です。小学校○年生です。今学校では○○を勉強しています。</p>
<h2>私の好きなもの</h2>
<h3>食べ物</h3>
<p>ハンバーグ・餃子</p>
<h3>趣味</h3>
<p>サッカー・そろばん</p>
```

.center[<img src="readme-img/Monaca11.png" alt="Monaca11.png" width="400px">]

---
### 4. コーディング①（パーツの書き方）

画像を入れてみましょう（ちょっと難しくなるよ）

* 画像を用意しましょう
  * ファイル名は「img」にしましょう
* Monacaに画像をインポートしましょう

.center[<img src="readme-img/Monaca12.png" alt="Monaca12.png" width="200px">]

---
### 4. コーディング①（パーツの書き方）

.center[<img src="readme-img/Monaca13.png" alt="Monaca13.png" width="300px">]

---
### 4. コーディング①（パーツの書き方）

.center[<img src="readme-img/Monaca14.png" alt="Monaca14.png" width="300px">]

---
### 4. コーディング①（パーツの書き方）

.center[<img src="readme-img/Monaca15.png" alt="Monaca15.png" width="300px">]

---
### 4. コーディング①（パーツの書き方）

.center[<img src="readme-img/Monaca16.png" alt="Monaca16.png" width="300px">]

---
### 4. コーディング①（パーツの書き方）

* インポート出来ました

.center[<img src="readme-img/Monaca17.png" alt="Monaca17.png" width="300px">]

---
### 4. コーディング①（パーツの書き方）

* インポートした画像を表示しましょう
  * `src` : 画像のパスを指定します
  * `width` : 画像の横の長さを指定します
  * `height` : 画像の縦の長さを指定します

```html
<img src="/img/image.png" width="150" height="150">
```

.center[<img src="readme-img/Monaca18.png" alt="Monaca18.png" width="500px">]

---
### 4. コーディング①（パーツの書き方）

下書き通りに出来たかな？

.center[<img src="readme-img/Monaca19.png" alt="Monaca19.png" width="700px">]


---
layout: true
class: center, middle, inverse_sub
---
## 5. コーディング②（アレンジの仕方）

---
layout: false

### 5. コーディング②（アレンジの仕方）

せっかくなのでアレンジしてみましょう！

* 背景の色変更
 * `<body>`タグにちょっと追加
 * 下の例は背景が水色になる

```html
<body bgcolor="skyblue">
```

.center[<img src="readme-img/Monaca20.png" alt="Monaca20.png" width="500px">]


blue, pink, red などでもOKだけど、色コードで細かく設定もできるよ！



> 参考リンク
> [WEB色見本 原色大辞典 \- HTMLカラーコード](https://www.colordic.org/)


---
### 5. コーディング②（アレンジの仕方）
* 文字の色変更
  * 色を変えたい文字を`<font>`のタグで挟む
  * 下の例は「こんにちは」が赤で表示されます

```html
<font color="red">こんにちは</font>
```

.center[<img src="readme-img/Monaca21.png" alt="Monaca21.png" width="500px">]


---
### 5. コーディング②（アレンジの仕方）
一部だけ変えることもできるよ

```html
<h1>私の<font color="red">ホームページ</font>アプリ</h1>
```

.center[<img src="readme-img/Monaca22.png" alt="Monaca22.png" width="500px">]


---
### 5. コーディング②（アレンジの仕方）

* 文字の位置変更
 * `<p>`タグに`align="***"`追加します

```html
<p align="left">左揃え</p>
<p align="right">右揃え</p>
<p align="center">中央揃え</p>
```

.center[<img src="readme-img/Monaca23.png" alt="Monaca23.png" width="500px">]

---
### 5. コーディング②（アレンジの仕方）

* 画像の位置変更
 * 画像を以下で挟む


```HTML
<div align="center">画像</div>
```

.center[<img src="readme-img/Monaca24.png" alt="Monaca24.png" width="500px">]



---
layout: true
class: center, middle, inverse_sub
---
## TRY<br>レベルアップコーディング

---
layout: false

### TRY<br>レベルアップコーディング

mBaaS連携を入れたい

* mBaaSとは
* mBaaSの準備
* コーディング（イイねボタン）
* コーディング（コメント欄）


---
layout: true
class: center, middle, inverse_sub
---
## アプリを使って自己紹介しよう！

---
layout: false

### アプリを使って自己紹介しよう！

自己紹介タイム取れればな

---
layout: true
class: center, middle, inverse_sub
---
## まとめ

---
layout: false

### まとめ

おしまい
