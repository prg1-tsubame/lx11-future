# Usage:

`run {future, rec, promise, add, add_zip, add_promise, fib}`

引数の説明

- **future**: Future の計算終了を待って結果を得る例 (`Await.result(f, t)`)
- **rec**: 再帰版 Fibonacci の計算例
- **promise**: Promise を介して結果を得る例 (`p success ...`)
- **add**: Future を合成する例 (`for { v1 <- f1; v2 <- f2 } yield (...)`)
- **add_zip**: Future を合成する例 (`f1.zip(f2)`)
- **add_promise**: Promise を利用して Future を合成する例
- **fib**: 再帰版と並列版の Fibonacci を比較
