# 分割代入

## 概要
配列やオブジェクトから値を取り出して変数へ代入する構文。

## オブジェクト例

```javascript
const dogProfile = {
  name: "Mile",
  age: 5
};

const { name, age } = dogProfile;
```

## 配列例

```javascript
const dogNames = ["Mile", "Taro", "Hanako"];

const [dog1, dog2, dog3] = dogNames;
```

## メリット
コードが短くなる
可読性向上
