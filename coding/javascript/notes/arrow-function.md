# アロー関数

## 概要
従来の関数式を簡潔に書ける構文。

## 特徴
- `=>` を使用
- 短く書ける
- thisの扱いが通常関数と異なる

## 使用例

```javascript
const func = (str) => {
  return str;
};

const func2 = str => str;

const add = (num1, num2) => num1 + num2;
```

