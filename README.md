# study_rust

Rustのお勉強

## 参考

- [Rust入門ガイド (sapporo.rs)](https://qiita.com/tatsuya6502/items/f13582103a65aa24e5b9)
- [Rust IDE に化ける VSCode](https://tech-blog.optim.co.jp/entry/2019/07/18/173000)
- [プログラミング言語Rust](https://doc.rust-jp.rs/the-rust-programming-language-ja/1.6/book/)

## 導入

インストール
```shell
$ curl https://sh.rustup.rs -sSf | sh
$ export PATH=$HOME/.cargo/bin:$PATH
$ rustc --version
```
アンインストール
```shell
$ rustup self uninstall
```

## 実行

```shell
$ rustc main.rs
$ ./main
```

## Cargo

> CargoはRustのビルドシステムであり、パッケージマネージャであり、RustaceanはCargoをRustプロジェクトの管理にも使います。

インストールされてるか確認
```shell
$ cargo --version
```