# BREMONS

LFS管理されたファイルがいくつかあります．
ローカルに Git-LFS を入れていない場合，LFS管理されたファイル (`.gitattributes` に記載されている）は，実体ではなくポインタになってます．

必ずGit-LFSを入れて `git lfs install` してください．

- install してない状態で `git push` は特に厳禁です． 

そうしておけば，いつもの pull, push でなんら変わりません．

## Git-LFS のインストール

- windows: `winget install GitHub.GitLFS`
- mac: `brew install git-lfs`

## 最初のクローン

```
$ git clone https://github.com/SouseiPJ/BREMONS.git
$ cd BREMONS
$ git lfs install
$ git lfs pull
```

## 次回以降の pull, push

いつもと変わらず，pull & push
(勝手にLFS管理対象ファイルはLFSリポジトリにポインタされます)



