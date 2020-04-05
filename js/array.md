# 与えられた整数の配列から偶数のみを抽出関数```evensOf```を作成せよ。

## 実行例
```javascript
let result1 = evensOf([1,2,3,4]);
let result2 = average([1,3,5,7]);
let result3 = average([]);

console.log(result1); //[2,4]と表示される
console.log(result2); //[]と表示される
````

# 与えられた整数の配列のすべての要素の合計値を求める関数```total```を作成せよ。

## 実行例
```javascript
let result1 = total([1,2]);
let result2 = total([3,5,7]);
let result3 = total([]);

console.log(result1); //3と表示される
console.log(result2); //15と表示される
console.log(result3); //0と表示される
```

# 与えられた整数の配列の全ての要素を２倍にした新しいリストを生成する関数```doubles```を作成せよ。

## 実行例
```javascript
let result1 = doubles([1,2,3]);
let result2 = doubles([]);

console.log(result1); //[2,4,6]と表示される
console.log(result2); //[]と表示される
````

# サイズ```n```と要素```e```を受け取り、大きさ```n```の全て要素が```e```の配列を生成する```makeArray```を作成せよ。

## 実行例
```javascript
let result1 = makeArray(3, “hoge”);
let result2 = makeArray(0, "hoge");
let result3 = makeArray(2, 100);

console.log(result1); //[hoge,hoge,hoge]と表示される
console.log(result2); //[]と表示される
console.log(result3); //[100,100]と表示される
```

# 配列と値を受け取り、配列の中にその値が１つでも含まれる場合は```true```を返す関数```sameOne```を作成せよ。

## 実行例
```javascript
let result1 = sameOne([1,2,3], 3);
let result2 = sameOne([1,2,3], 5);
let result3 = sameOne(["apple","orange","grape"], "grape");
let result4 = sameOne([1,2,3], "3");

console.log(result1); //trueと表示される
console.log(result2); //falseと表示される
console.log(result3); //trueと表示される
console.log(result4); //falseと表示される。文字列３と数値３は異なることに注意。
```

# 配列と値を受け取り、配列のすべての要素がその値と等しい場合に```true```を返す関数```sameAll```を作成せよ。

## 実行例
```javascript
let result1 = sameAll([1,2,3], 3);
let result2 = sameAll([3,3,3], 3);
let result3 = sameAll(["apple","orange","grape"], "grape");
let result4 = sameAll([3,3,3], "3");

console.log(result1); //falseと表示される
console.log(result2); //trueと表示される
console.log(result3); //falseと表示される
console.log(result4); //falseと表示される。文字列３と数値３は異なることに注意。
```

# 配列の配列を受け取り、各要素の配列を連結して新しい配列を返す関数 ```flatten``` を作成せよ。

## 実行例
```javascript
let result1 = flatten([[1],[2,3],[4,5,6]]);
let result2 = flatten([["a"],[1,2],["b", "c"]]);
let result3 = flatten([]);
let result4 = flatten([[1],[],[2,3]]);

console.log(result1); //1,2,3,4,5,6と表示される
console.log(result2); //a,1,2,b,cと表示される
console.log(result3); //何も表示されない（空配列）
console.log(result4); //1,2,3と表示される。
```

# ２つの整数配列を受け取り、対応する要素の和を要素とする新しい配列を返す関数 ```sumArray```を作成せよ。ただし、配列の大きさが異なる場合は、小さい配列の大きさとなること。

## 実行例
```javascript
let result1 = sumArray([1,2,3], [3,4,5]);
let result2 = sumArray([],[3,4,5]);
let result3 = sumArray([1,2,3],[]);
let result4 = sumArray([1,2,3],[3,4]);
let result5 = sumArray([],[]);

console.log(result1); //4,6,8と表示される
console.log(result2); //3,4,5と表示される
console.log(result3); //1,2,3と表示される
console.log(result4); //4,6と表示される。
console.log(result5); //何も表示されない（空配列）
```

# 整数の配列を受け取り、すべての要素の積を求めるメソッド ```productArray```を作成せよ。

## 実行例
```javascript
let result1 = productArray([1,2,3]);
let result2 = productArray([3,4,5]);
let result3 = productArray([0,3,5]);
let result4 = productArray([]);

console.log(result1); //6と表示される
console.log(result2); //60と表示される
console.log(result3); //0と表示される
console.log(result4); //何も表示されない（空配列）
```

# 整数の階乗を求める関数 ```factorial```を作成せよ。ただし、上記で作成した```product```を利用せよ。

## ヒント
* 整数```n```の階乗とは、```1```から```n```までのすべての積、つまり ```1 * 2 * ... * n``` のことである。
* ただし、```0```の階乗は```1```とする。

## 実行例
```javascript
let result1 = factorial(1);
let result2 = factorial(2);
let result3 = factorial(3);
let result4 = factorial(4);

console.log(result1); //1と表示される
console.log(result2); //2と表示される
console.log(result3); //6と表示される
console.log(result4); //24と表示される
```

# 注文金額の配列```orderAmouns```と金額```amount```を受け取り、注文額が金額```amount```以上の平均を求める関数 ```averageAmount``` を作成せよ。

## 実行例
```javascript
let result1 = averageAmount([3000, 2000, 5000], 3000);
let result2 = averageAmount([3000, 2000, 5000], 6000);
let result3 = averageAmount([3000, 2000, 5000], 2000);
let result4 = averageAmount([], 3000);

console.log(result1); //4000と表示される。3000+5000/2
console.log(result2); //0と表示される
console.log(result3); //3333.333...と表示される
console.log(result4); //0と表示される
```


 
