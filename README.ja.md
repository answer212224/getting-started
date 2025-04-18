# Docker 入門チュートリアル

[English](README.md) | [繁體中文](README.zh-TW.md) | [日本語](README.ja.md)

このチュートリアルは、コンテナの使用を開始するためのガイドとして書かれており、Docker Desktopで動作するように設計されています。詳細には触れませんが、以下のトピックをカバーしています：

- 最初のコンテナの実行
- コンテナのビルド
- コンテナについての学習
- コンテナの実行と削除
- データを永続化するためのボリュームの使用
- 開発をサポートするためのバインドマウントの使用
- 複数コンテナアプリケーションをサポートするためのコンテナネットワーキングの使用
- アプリケーションの定義と共有を簡略化するためのDocker Composeの使用
- ビルドを高速化し、プッシュ/プルサイズを減らすためのイメージレイヤーキャッシングの使用
- ビルド時と実行時の依存関係を分離するためのマルチステージビルドの使用

## 始め方

Docker Desktopをインストールした後、以下のコマンドでチュートリアルを実行できます：

```bash
docker run -d -p 80:80 docker/getting-started
```

起動したら、ブラウザで[http://localhost](http://localhost)を開いてください。

## 開発

このプロジェクトには`docker-compose.yml`ファイルがあり、mkdocsアプリケーションをローカルマシンで起動して、変更をすぐに確認することができます。

```bash
docker compose up
```

## 貢献

チュートリアルに誤字や他の問題を見つけた場合は、PRを作成して修正を提案してください！

チュートリアルの改善方法についてのアイデアがある場合や、新しいコンテンツの追加を提案したい場合は、作業を始める前に、まずIssueを開いてください。私たちは意見を歓迎しますが、チュートリアルは初心者向けに範囲を限定したいと考えています。そのため、より高度なリクエストについては拒否することがあり、あなたの作業が無駄にならないようにしたいと思います。まずは質問してください、私たちはあなたの考えを喜んでお聞きします！
