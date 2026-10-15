<p align="center">
  <img src="./logo.svg" width="88" height="88" alt="Modelith">
</p>

<p align="center">
  <b>テキストと図を同期して編集できる、オープンソースの SysML v2 モデリングエディタ</b><br>
  <sub>SysML v2 / KerML modeling editor with synchronized text and diagram editing</sub>
</p>

<p align="center">
  <a href="https://modelith.github.io/modelith/"><b>ブラウザで試す</b></a> &nbsp;|&nbsp;
  <a href="https://github.com/modelith/modelith">ソースコード</a> &nbsp;|&nbsp;
  <a href="https://github.com/modelith/modelith/tree/dev/docs">ドキュメント</a> &nbsp;|&nbsp;
  <a href="https://github.com/modelith/modelith/issues/new/choose">フィードバック</a>
</p>

<p align="center">
  <a href="https://github.com/modelith/modelith/releases"><img src="https://img.shields.io/github/v/release/modelith/modelith?include_prereleases&label=release" alt="release"></a>
  <a href="https://github.com/modelith/modelith/blob/main/LICENSE"><img src="https://img.shields.io/badge/license-AGPL--3.0%20%2B%20Plugin%20Exception-blue" alt="license"></a>
</p>

<br>

## Modelith とは

- **テキストが正本、図はその写し** — SysML v2 のテキストを書けば図が更新され、図を操作すればテキストが書き換わります。差分は Git でそのまま追えます。
- **インストール不要・サーバ不要** — ブラウザだけで動きます。モデルは手元のファイルとして保存され、外部に送信されません。
- **ひとつのコアをどこでも** — Rust のコアをブラウザ（WebAssembly）・CLI・サーバで共有します。
- **プラグインで拡張** — [plugin-sdk](https://github.com/modelith/plugin-sdk) の公開インタフェースだけを使うプラグインは、好きなライセンスで配布できます。

## リポジトリ

| リポジトリ | 内容 | ライセンス |
| --- | --- | --- |
| [modelith](https://github.com/modelith/modelith) | エディタ本体（Rust コア・Web アプリ・CLI） | AGPL-3.0 + [Plugin Exception](https://github.com/modelith/modelith/blob/main/PLUGIN-EXCEPTION.md) |
| [plugin-sdk](https://github.com/modelith/plugin-sdk) | プラグイン向けのインタフェース・型定義 | MIT |

## 開発状況

いまは **0.1.0 に向けた alpha 版**です。1 週間ごとに alpha を公開しながら、テストユーザーの声をもとに育てています。今後は CLI・MCP・LSP・プラグイン・サーバへと広げていく予定です（[ロードマップ](https://github.com/modelith/modelith/blob/dev/docs/explanation/architecture.md#ロードマップ)）。

## 参加する

- 使ってみた感想・「こんな図がほしい」は [Issues](https://github.com/modelith/modelith/issues/new/choose) へ。
- コードでの貢献は [CONTRIBUTING.md](https://github.com/modelith/modelith/blob/dev/CONTRIBUTING.md) をご覧ください。
- 設計の背景は [ADR](https://github.com/modelith/modelith/tree/dev/docs/adr) にまとめています。

<br>

<sub>SysML® and OMG® are registered trademarks, and KerML™ is a trademark, of Object Management Group, Inc. Modelith is an independent project and is not affiliated with or endorsed by OMG.</sub>
