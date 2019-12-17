# test-No.1

## 基本情報

- プロジェクト：.NET Core コンソールアプリケーション
- フレームワーク：.NET Core 3.1

## 概要

VisualStudioで作成したプロジェクトにDockerサポートを追加。VS上でDockerfileを作成。
これをDcokerHubに公開して他のホストマシン上で稼働させることを想定したトライ。

## 実施内容

- VS上でDockerfileを作成（Dockerサポート機能の有効化）
- このDockerfileを用いてホストマシン上でpowershellからコンテナを起動
	- 作成イメージ：**testimage**

## 結果

コンテナが正常に稼働することを確認した。