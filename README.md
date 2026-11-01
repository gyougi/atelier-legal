# atelier-legal

Public legal & support pages for the **Atelier** iOS app, served via GitHub Pages.

- `privacy.html` — Privacy Policy (JA / EN)
- `terms.html` — Terms of Use (JA / EN)
- `support.html` — Support & FAQ (JA / EN)
- `index.html` — Landing

Live: https://atelier-legal.glspace.co.jp/ (旧址 https://gyougi.github.io/atelier-legal/ 301→自定义域名)

Contact: contact@glspace.co.jp

## 連絡先はどこに書いてあるか

この站には生成スクリプトが無いので、住所は**頁の中に素で**在る。
`contact@glspace.co.jp` を変えるときは、次の全部を直すこと ──
一つ直し忘れても頁は普通に出るので、**字面でも検査でも分からない**。

- `privacy.html`（4 件）
- `support.html`（5 件）
- `terms.html`（4 件）
- `README.md`（上の Contact の行）

見落としを確かめる一行:

```bash
grep -rn 'glspace\.co\.jp' . --include='*.html' --include='*.md' | grep -v contact@
```
