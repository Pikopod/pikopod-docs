# pikopod documentation

The source of [docs.pikopod.com](https://docs.pikopod.com). Mintlify format: `docs.json` holds the navigation, theme and logo; every page is an `.mdx` file.

## Preview locally

```bash
npm install
npx mint dev
```

Opens on `http://localhost:3000` and reloads on every save.

## Check before pushing

```bash
npx mint validate
npx mint broken-links
```

## Deploy

Connect this repository to Mintlify, add `docs.pikopod.com` as the custom domain, and every push to `main` deploys.

## Conventions

- Every command and every block of output must come from running the real binary. Nothing is hand-written prose pretending to be output.
- Say only what works. No deprecated flags, no internal quirks, no hedging.
- The fictional provider is `examplepay`. Never name a real provider or another product.
- Put `{...}` and `<...>` inside backticks or code blocks; MDX treats them as expressions and tags otherwise.
