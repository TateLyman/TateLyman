# Hey, I'm Tate

I build developer tools — CLI utilities, browser-based tools, and open source projects.

## Live Projects

**[DevTools.run](https://devtools-site-delta.vercel.app)** — 20 free browser-based developer tools. JSON formatter, JWT decoder, regex tester, QR generator, and more. No tracking, no accounts, 100% client-side.

**[Resume Builder](https://resume-builder-three-omega-84.vercel.app)** — Free resume builder with live preview, PDF export, and multiple templates.

## npm Packages

All zero dependencies, pure Node.js:

| Package | Description | Install |
|---------|-------------|---------|
| [jsonfix-cli](https://npmjs.com/package/jsonfix-cli) | Fix broken JSON (trailing commas, comments, single quotes) | `npm i -g jsonfix-cli` |
| [csvkit-cli](https://npmjs.com/package/csvkit-cli) | CSV swiss army knife (convert, filter, sort, stats) | `npm i -g csvkit-cli` |
| [portfind-cli](https://npmjs.com/package/portfind-cli) | Find/kill processes on ports | `npm i -g portfind-cli` |
| [envcheck-dev](https://npmjs.com/package/envcheck-dev) | Validate .env against .env.example | `npm i -g envcheck-dev` |
| [logpretty-cli](https://npmjs.com/package/logpretty-cli) | Pretty-print JSON logs (pino, winston, bunyan) | `npm i -g logpretty-cli` |
| [@tatelyman/gitquick-cli](https://npmjs.com/package/@tatelyman/gitquick-cli) | Git shortcuts for lazy devs | `npm i -g @tatelyman/gitquick-cli` |
| [@tatelyman/readme-gen](https://npmjs.com/package/@tatelyman/readme-gen) | Auto-generate README from package.json | `npm i -g @tatelyman/readme-gen` |

## GitHub Actions

**[PR Size Labeler](https://github.com/TateLyman/pr-size-labeler)** — Automatically label PRs by size (XS/S/M/L/XL) with color-coded labels.

```yaml
- uses: TateLyman/pr-size-labeler@v1
  with:
    github_token: ${{ secrets.GITHUB_TOKEN }}
```

## Support

If any of my tools save you time, tips are appreciated:

**SOL:** `NaTTUfDDQ8U1RBqb9q5rz6vJ22cWrrT5UAsXuxnb2Wr`

## Tech

TypeScript, Python, Node.js, Next.js, Solana, Security Research
