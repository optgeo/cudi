# cudi
kid-c template

# 使い方
このテンプレートは、UNVT のコマンドラインツールを使います。

Raspberry Pi OS では [equinox](https://github.com/unvt/equinox) で UNVT を導入できます。

Docker 上では [nanban](https://github.com/unvt/nanban) で UNVT を導入できます。

## 導入
```
git clone git@github.com:optgeo/cudi
cd cudi
```

## スタイル構築
```
vi layers/voxel.yml
rake style
```

## 自ホストでホスト
```
rake host
```

## GitHub Pages でホスト
main ブランチの doc ディレクトリをホストするように GitHub Pages を設定してください。

