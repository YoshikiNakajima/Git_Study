# Git_Study
お勉強するよお
# Outline

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->

- [1回目](#1%E5%9B%9E%E7%9B%AE)
  - [導入（Gitのssh接続）](#%E5%B0%8E%E5%85%A5git%E3%81%AEssh%E6%8E%A5%E7%B6%9A)
  - [Gitのいろいろ](#git%E3%81%AE%E3%81%84%E3%82%8D%E3%81%84%E3%82%8D)
  - [Hello World](#hello-world)
  - [Apple pie](#apple-pie)
- [2回目（今日だよおお）](#2%E5%9B%9E%E7%9B%AE%E4%BB%8A%E6%97%A5%E3%81%A0%E3%82%88%E3%81%8A%E3%81%8A)
  - [bbb](#bbb)
    - [ccc](#ccc)
    - [aaaa](#aaaa)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

# 1回目
## 導入（Gitのssh接続）
ホームディレクトリに鍵を入れるフォルダを(なければ)作成し移動する。
```
mkdir .ssh
cd .ssh
```
鍵を生成する。
```
ssh-keygen
```
鍵が生成されてることを確認し`ls`、公開鍵`id_rsa.pub`の中身をコピー
```
.ssh$ ls
id_rsa		id_rsa.pub	known_hosts
```
https://github.com/settings/ssh
公開鍵を上URLからGitHubにアップする。
ページ内`Add SSH key`から`title`に公開鍵名、`key`に公開鍵の中身を入れる。

## Gitのいろいろ
ローカルリポジトリ(PC)をリモートリポジトリ(Git)から更新
```
git pull
```

リモートリポジトリ(Git)をローカルリポジトリ(PC)から更新
```
git add .
git commit -m [comment]
git push
```
`git add .`ディレクトリ内の全てをステージングエリアへ更新¥n
`git commit -m [comment]`更新をリポジトリに保存 [comment]に詳細を記述
`git push`リモートリポジトリを更新

## Hello World
- 1111
- 2222
- 3333

  * 4444
  * 5555

```.c
#include <stdio.h>

main()
{
  printf("Hello World\n");
}
```

## Apple pie
- 1111
  - 2222

- 3333
  * 4444

```.c
#include <stdio.h>

main()
{
  printf("apple pie\n");
}
```

# 2回目（今日だよおお）

## bbb
### ccc

### aaaa
