# ２つの数値の和を求めるプログラム sum.php を作成せよ。

## 実行例 {.unnumbered}

```bash
>php sum.php 1 2
>3
>php sum.php 3 5
>8
```
# 複数の数値の合計を求めるプログラム total.php を作成せよ。

## 実行例 {.unnumbered}

```bash
>php total.php 1 2
>3
>php total.php 2 3 4
>10
>php total.php 
>0
```
 
# 複数の数値の平均値を求めるプログラム average.php を作成せよ。

## 実行例 {.unnumbered}
```bash
>php average.php 1 2
>1.5
>php average.php 2 4 20
>13
```

# 生年月日を入力すると年齢を求めるプログラム age.php を作成せよ。

## 実行例 {.unnumbered}
```bash
>php age.php 2000/3/1
>あなたは 20 歳です
>php age.php 1980/3/1
>あなたは 39 歳です
```

# 入力した文字列をすべて連結した文字列を表示するプログラム concat.php を作成せよ。 

## 実行例 {.unnumbered}
```bash
>php concat.php abc edf  
>abcedf
>php concat.php i love php   
>ilovephp
```

# 入力した数値を小さい順にソートして表示するプログラム sort.php を作成せよ。

## 実行例 {.unnumbered}
```bash
>php sort.php 3 2 10 5 20 13 
>2 3 5 10 13 20
>php sort.php 100 50 30 20 10 
>10 20 30 50 100
```

# フルーツの名前を入力すると、その価格を返すプログラム、fruits.php を作成せよ。 

## フルーツは以下の通りとする。 {.unnumbered}
|フルーツ|価格|
|--|--|
|りんご|２００円|
|バナナ|１００円|
|みかん|１５０円|
|ぶどう|３００円|
|もも|４００円|

## 実行例 {.unnumbered}
```bash 
>php fruits.php りんご  
>200
>php fruits.php ぶどう
>300円
```

# 先の課題のフルーツのリストがある。フルーツの名前を複数入力すると、それらのフルーツの価格の平均値を求めるプログラム fruitsavg.php を作成せよ。

## 実行例 {.unnumbered}
```bash
>php fruits.php ぶどう みかん
>225円
>php fruits.php りんご ぶどう もも
>300円
```

# 先の課題のフルーツのリストがある。価格を入力するとその価格以上のフルーツのリストを出力するプログラム searchfruits.php を作成せよ。

## 実行例 {.unnumbered}
```bash
>php searchfruits.php 200  
>りんご、ぶどう、もも
>php searchfruits.php 400
>もも
>php searchfruits.php 500
>//ないので何も出力しない
```

# 以下のような、四則演算（足し算、引き算、掛け算、割り算）可能な計算プログラム calc.php を作成せよ。１つ目の入力値に、演算記号、２つ目と３つ目に数値を入力できること。演算記号は、「+」が足し算、「-」が引き算、「*」が掛け算、「/」が割り算を表すものとする。

## 実行例 {.unnumbered}
```bash
>php calc.php + 1 2
>3
>php calc.php - 3 1
>2
>php calc.php * 3 5
>15
>php calc.php / 4 2
>2
```
