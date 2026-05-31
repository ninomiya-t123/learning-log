# SOLID原則

## 概要
SOLID原則とは、オブジェクト指向設計における5つの基本原則をまとめた頭文字
保守しやすく、拡張しやすいソフトウェア設計を目的としている

## 一覧
- S : Single Responsibility Principle
- O : Open/Closed Principle
- L : Liskov Substitution Principle
- I : Interface Segregation Principle
- D : Dependency Inversion Principle

---

# S - 単一責任の原則

## 正式名称
Single Responsibility Principle

## 概要
クラスの責任を明確にするための原則

## 意味
- 1つのクラスが複数の理由で変更されるべきではない
- クラスは1つの「軸」で変化するように設計する

## メリット
- 責務が明確になる
- コードの保守性が上がる
- 可読性が向上する
- 要件変更に柔軟に対応できる

---

# O - 開放/閉鎖の原則

## 正式名称
Open/Closed Principle

## 概要
ソフトウェアの実装は、拡張に対して開かれ、修正に対して閉じられているべきという原則

## 意味
- 既存コードを変更せず、新しい機能を追加できる設計を目指す
- 変更に強く、拡張しやすい設計を実現する

## メリット
- バグ発生リスクの低減
- 保守性の向上
- 再利用性の向上
- 機能追加の柔軟性確保
