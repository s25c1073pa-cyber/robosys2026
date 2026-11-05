# plusコマンド

[![test](https://github.com/s25c1073pa-cyber/robosys2026/actions/workflows/test.yml/badge.svg)](https://github.com/s25c1073pa-cyber/robosys2026/actions/workflows/test.yml)

標準入力から読み込んだ数値を合計して、標準出力に表示するコマンドです。

## 使い方

数値を1行ずつ標準入力に渡します。

```bash
seq 5 | ./plus

```
実行結果: `15`

## 必要なソフトウェア

- Python 3
  - テスト済みバージョン: 3.10〜3.14

## テスト環境

- Ubuntu 24.04 LTS（GitHub Actions）

## ライセンス

- このソフトウェアパッケージは、3条項BSDライセンスの下、再頒布および使用が許可されます。
- Copyright 2026 Haruto Nakanou

## 出典

- このパッケージのコードは、下記のスライド（CC BY-SA 4.0 by Taro Suzuki）のものを、本人の許可を得て自分の著作としたものです。
- https://github.com/tarolab-cit/lectures/tree/main/robosys2026
