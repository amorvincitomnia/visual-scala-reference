---
name: curried
---

# `curried`

@include [signatures/curried.md]

`curried` は、元の関数の1つ目のパラメーターを処理して残りの引数を取る関数を作成します。続いてその関数は、元の関数の2つ目のパラメーターを処理して残りの引数を取る関数を作成します。…というのが、すべてのパラメーターがなくなるまで続き、最終的な結果が計算されます。

@include [figure.html source="../images/curried.svg" desc="関数 curried の図"]
