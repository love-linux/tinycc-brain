# tinycc-brain

TinyCC（TCC - Tiny C Compiler）を、SHARP の電子辞書 Brain
（Windows CE）で動くように改造したもののソースコードです。

## もとのプロジェクト

- TinyCC は Fabrice Bellard と貢献者による C コンパイラです。
- 本家: https://bellard.org/tcc/
- このリポジトリは本家のソースコードをもとに、Brain / Windows CE 向けの
  改造を加えたものです。改造部分も含め、各ファイルの著作権表示を
  そのまま残しています。

## ライセンス

- GNU Lesser General Public License（LGPL）version 2.1 以降の条件で
  配布します。全文は同梱の `COPYING` を参照してください。
- brain AI 本体のソースコードは公開していません。このリポジトリは
  同梱している C コンパイラ（TinyCC）のソースコードだけを公開するものです。
