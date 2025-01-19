# rusty-book-manager-template

書籍『Rust による Web アプリケーション開発』の実装

- Dockerfile: Docker 向けの設定が書かれています。
- compose.yaml: docker compose を立ち上げるために必要です。
- Makefile.toml: cargo-make の設定のために必要です。
- rust-toolchain.toml: 書籍と Rust のバージョンをそろえるために必要です。
- .github: GitHub Actions の設定ファイルが主に含まれています。
- infra: AWS 上にリソースを構築し、デプロイやリリースを一通り体験したい場合に必要です。セットアップの方法については、[README](./infra/README.md)に記載しています。
- frontend: rust-book-manager の UI を立ち上げたい場合に必要です。立ち上げる方法は、[README](./frontend/README.md)に記載しています。
