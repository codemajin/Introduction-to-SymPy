# Introduction-to-SymPy

[SymPy](https://www.sympy.org/en/index.html)の学習記録をノートブックとして保存

![sympy_matrix](https://user-images.githubusercontent.com/20922926/139571306-0d0e35b8-2975-47ba-8261-2f66d5f1529e.png)

## 環境構築

`pip` を使用する場合は、

```shell
$ pip install numpy sympy mpmath
```

`conda`の場合は、[SymPy](https://www.sympy.org/en/index.html)を指定するだけで、関連するパッケージも同時にインストールされる。

```shell
$ conda install sympy
```

## ノートブック

- [SymPyの基本的な使い方](https://github.com/codemajin/Introduction-to-SymPy/blob/master/notebooks/01-BasicUsage.ipynb)
  + シンボル定義
  + 数式定義
  + 数式に値を代入
  + 数式の係数を取得
  + 分数の取り扱い方
  + 数列の取り扱い方
  + 連立方程式の解き方
- [微分・積分](https://github.com/codemajin/Introduction-to-SymPy/blob/master/notebooks/02-DifferentialAndIntegral.ipynb)
  + 極限の計算
  + 微分の計算
  + テーラー展開の計算
  + 不定積分、定積分の計算
  + 微分方程式の解き方
- [ベクトル・行列](https://github.com/codemajin/Introduction-to-SymPy/blob/master/notebooks/03-VectorAndMatrix.ipynb)
  + 行列の操作 (単位行列、対角行列、転置行列、逆行列、行列式、固有値、固有ベクトル)
  + ベクトルの操作 (内積、外積、直積、直交化)
- [コード生成](https://github.com/codemajin/Introduction-to-SymPy/blob/master/notebooks/04-CodeGeneration.ipynb)
  + C言語のコードを生成
- [メタプログラミング](https://github.com/codemajin/Introduction-to-SymPy/blob/master/notebooks/05-Metaprogramming.ipynb)
  + 論文に掲載されている数式を再現し、C言語のコードとして出力