---
title: "test01投稿"
date: "2022-02-22"
thumbnail: "/images/thumbnail01.jpg"
---

# 条件を分岐させるためのIF文の使い方とは？
## 条件分岐って何？
条件分岐とは、指定した条件で処理を分ける方法
 
***
- 請求書の締め月が上期だった場合は、〇〇を使って計算する
- 部署コードがA0001の場合は開発部、B0001の場合はWEBマーケティング部
- 処理月が2014年4未満だった場合は消費税5%、それ以外は8%で計算
***
## IF文の基礎的な使い方
### 条件が1つのみ
```vb
IF 条件 Then
    '条件に一致したときの処理をここにかく
End if
```