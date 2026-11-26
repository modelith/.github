# Reporting security issues

English | [日本語](#日本語)

This policy covers every repository of the Modelith organization that has no `SECURITY.md` of its own
(for example plugin-sdk, plugin-registry, plugins and the manual site).
The editor itself has its own policy: [modelith/modelith SECURITY.md](https://github.com/modelith/modelith/blob/dev/SECURITY.md).

If you find a security issue, **do not open a public issue**. Please tell us privately in one of these ways.

- GitHub's private reporting: [Report a vulnerability](https://github.com/modelith/modelith/security/advisories/new)
  (you can report an issue in any Modelith repository there; say which repository it is about)
- Email: security@modelith-studio.org

Please include, as far as you know, what it allows (the impact) and the steps to reproduce.
Reports in English or Japanese are welcome.

## Examples

| Target | Examples |
| --- | --- |
| plugin-sdk (`modelith-plugin-protocol`, `modelith-plugin-sdk`) | A manifest or message that the types accept but should not, a published package that differs from the source |
| plugin-registry (<https://registry.modelith-studio.org/index.json>) | Changing someone else's entry or a published version, getting an entry into the index without the checks |
| The release workflows of any repository | Running code or getting a token from a pull request |

For issues in a third-party plugin, please contact the author of that plugin.

## How we respond

- We will acknowledge your report as soon as we can.
- Please keep the details private until it is fixed. After the fix is published, we will credit the report, and your name if you wish.

---

## 日本語

このページは、Modelith の組織のリポジトリのうち、自分の `SECURITY.md` を持たないもの（plugin-sdk・plugin-registry・plugins・マニュアルのサイトなど）に当てはまります。
エディタ本体には、本体の決まりがあります（[modelith/modelith の SECURITY.ja.md](https://github.com/modelith/modelith/blob/dev/SECURITY.ja.md)）。

セキュリティの問題を見つけたときは、**公開の Issue には書かずに**、次のどちらかでお知らせください。

- GitHub の非公開の報告：[Report a vulnerability](https://github.com/modelith/modelith/security/advisories/new)（どのリポジトリの問題でも、ここで受け付けます。どのリポジトリのことかを書いてください）
- メール：security@modelith-studio.org

何ができてしまうか（影響）と、再現する手順を、分かる範囲で書いてください。日本語でも英語でもかまいません。

ほかの人が作ったプラグインの問題は、そのプラグインの作者にお知らせください。
修正を公開するまでは、内容を公開しないでください。公開したあとに、報告への謝辞を（希望があれば名前も）載せます。
