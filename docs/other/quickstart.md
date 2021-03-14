# Quick start

ssm projectを試して見ようと思った方は以下の方法で試すことができます。

### 本体のダウンロード

### 最新の最低保障版を使う

[こちら](https://github.com/yupix/ssm/releases) から`pre-release`がついた物をダウンロードしてください。
この場合、動作の保障はできませんが、サポートは行わせていただきます。issuesを建てていただいた際は優先順位を上げ問題を修正します。

### 過去の成果物（完全保障版）を使う

> [!warning]
> 現在データベース周りの変更によりバージョン`latest1.0.0, pre1.0.1`からの引継ぎは行えません。
> またそれと同時にバグの修正は行いますが、機能の追加等は旧仕様には行いません。

[こちら](https://github.com/yupix/ssm/releases/latest) からダウンロードしてください。
動作の保障やバグの対応のみを行います。


### 不安定版（2種類）

> [!tip]
> 余程な理由がない限りは上記

```bash
# 最低限の動作が確認されている
git clone https://github.com/yupix/ssm.git

# 動作の確認は行われているが上記の物と比べると余り確認されていない
git clone -b testing https://github.com/yupix/ssm.git
```


```

```