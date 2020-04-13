# 下のメニュー一覧が与えられている。以下の課題ではこのメニュー一覧を利用すること。

## メニュー一覧 {.unnumbered}
|メニュー名|カテゴリ|カロリー|
|---|---|---|
|ハンバーグ|洋食|300Kcal|
|スパゲティ|洋食|400Kcal|
|肉じゃが|和食|100Kcal|
|おにぎり|和食|300Kcal|
|チャーハン|中華|500Kcal|
|からあげ|中華|300Kcal|

## カロリーを指定すると、そのカロリー値に最も近いメニュー（複数の場合あり）を提案するプログラム```recommend_calorie.php```を作成せよ。

### 条件 {.unnumbered}
* 指定されたカロリーに最も近いメニュー（複数）返す関数```menusNearCalory```を```menus.php```ファイルに作成せよ。
* ```recommend_calorie.php```は```menus.php```を利用（インクルード）すること。

### 実行例 {.unnumbered}
```bash
>php recommend_calorie.php 100
肉じゃが
>php recommend_calorie.php 200
ハンバーグ スパゲティ
```

## 食べたいメニューのカテゴリを指定すると、そのカテゴリに属するメニュー（メニュー名とカロリー）の一覧とそれらのカロリー平均を出力するプログラム```recommend_category.php```を作成せよ。

### 条件 {.unnumbered}
* 指定されたカテゴリのメニュー一覧を返す関数```menusOfCategory```を```menus.php```ファイルに作成せよ。
* 整数配列の平均値を求める関数```average```を```arrayutil.php```ファイルに作成せよ。
* ```recommend_category.php```は```menus.php```と```arrayuti.php```を利用（インクルード）すること。

## 実行例 {.unnumbered}
```bash
>php recommend_category.php 洋食
ハンバーグ,300Kcal
スパゲティ,400Kcal
カロリー平均:350Kcal
>php recommend_category.php 中華
チャーハン,500Kcal
からあげ,300Kcal
カロリー平均:400Kcal
>php recommend_category.php インド料理
メニューはありません
```
