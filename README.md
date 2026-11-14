# packwiz
どな鯖のpackwiz


## MODの導入方法

- [packwiz-installer-bootstrap](https://github.com/packwiz/packwiz-installer-bootstrap)を起動構成のフォルダに置く
    - 右側のReleasesから最新バージョンを取ってこれるお

```bash
# サーバー
java -jar packwiz-installer-bootstrap.jar --no-gui --side server https://raw.githubusercontent.com/donabeya/packwiz/refs/heads/feature/3.0/pack.toml

# クライアント
java -jar packwiz-installer-bootstrap.jar --side client https://raw.githubusercontent.com/donabeya/packwiz/refs/heads/feature/3.0/pack.toml

```

- `java -jar packwiz-installer-bootstrap.jar https://raw.githubusercontent.com/donabeya/packwiz/refs/heads/main/pack.toml`
    - 一度`mods`フォルダを削除するといい
