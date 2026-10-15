<p align="center">
  <img src="https://raw.githubusercontent.com/modelith/.github/main/profile/logo.svg" width="88" height="88" alt="Modelith">
</p>

<p align="center">
  <b>テキストと図を同期して編集できる、オープンソースの SysML v2 モデリングエディタ</b><br>
  <sub>SysML v2 / KerML modeling editor with synchronized text and diagram editing</sub>
</p>

<p align="center">
  <a href="https://modelith.github.io/modelith/"><b>ブラウザで試す</b></a> &nbsp;|&nbsp;
  <a href="https://github.com/modelith/modelith">ソースコード</a> &nbsp;|&nbsp;
  <a href="https://github.com/modelith/modelith/issues/new/choose">フィードバック</a>
</p>

<p align="center">
  <a href="https://github.com/modelith/modelith/releases"><img src="https://img.shields.io/github/v/release/modelith/modelith?include_prereleases&label=release" alt="release"></a>
  <a href="https://github.com/modelith/modelith/blob/main/LICENSE"><img src="https://img.shields.io/badge/license-AGPL--3.0%20%2B%20Plugin%20Exception-blue" alt="license"></a>
</p>

<br>

## Modelith とは

システムエンジニア・学生・研究者のための、SysML v2 のモデリングエディタです。テキストで書いたモデルがすぐ図になり、図で動かした内容はテキストに書き戻されます。

<p align="center">
  <a href="https://modelith.github.io/modelith/">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/modelith/.github/main/profile/screenshot-dark.png">
      <img src="https://raw.githubusercontent.com/modelith/.github/main/profile/screenshot.png" width="800" alt="Modelith の画面。左にファイル、中央にトレーサビリティの図、右に SysML v2 のテキスト">
    </picture>
  </a>
</p>

- **書いても、描いても、同じモデル**<br>
  テキストを打てば図に反映し、図で要素や関係を足せばテキストが書き換わります。

- **目的に合わせた 7 つのビュー**<br>
  トレーサビリティ・構造・制御ループ・内部ブロック図・振る舞い・シーケンスなど、同じモデルを見たい切り口で表示できます。SVG や draw.io 形式への書き出しにも対応しています。

- **要求の抜けに気づける**<br>
  利用者要求から方式設計・検証までのつながりをたどり、導出・充足・検証の抜けを件数と箇所で示します。

- **ブラウザを開くだけ**<br>
  インストールもアカウントも不要です。手元のフォルダを VS Code のように開いて、編集・保存できます。

- **モデルは手元から出ない**<br>
  モデルを外部に送信せず、アクセス解析も使いません。モデルはただのテキストファイルなので、Git で差分を追えます。

## リポジトリ

| リポジトリ | 内容 | ライセンス |
| --- | --- | --- |
| [modelith](https://github.com/modelith/modelith) | エディタ本体（Rust コア・Web アプリ・CLI） | AGPL-3.0 + [Plugin Exception](https://github.com/modelith/modelith/blob/main/PLUGIN-EXCEPTION.md) |
| [plugin-sdk](https://github.com/modelith/plugin-sdk) | プラグイン向けのインタフェース・型定義 | MIT |

## 開発状況

いまは **0.1.0 に向けた alpha 版**です。1 週間ごとに alpha を公開しながら、テストユーザーの声をもとに育てています。今後は CLI・MCP・LSP・プラグイン・サーバへと広げていく予定です。

## 参加する

- 使ってみた感想・「こんな図がほしい」は [Issues](https://github.com/modelith/modelith/issues/new/choose) へ。
- コードで貢献したい方は、[modelith リポジトリ](https://github.com/modelith/modelith)をご覧ください。

<br>

<sub>SysML® and OMG® are registered trademarks, and KerML™ is a trademark, of Object Management Group, Inc. Modelith is an independent project and is not affiliated with or endorsed by OMG.</sub>
