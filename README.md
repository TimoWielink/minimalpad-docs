# MinimalPad documentation

The source for [docs.minimalmacropad.com](https://docs.minimalmacropad.com/), built with Mintlify.

## Local development

Install the [Mintlify CLI](https://www.npmjs.com/package/mint), then start the preview from this directory:

```sh
npm i -g mint
mint dev
```

View your local preview at `http://localhost:3000`.

## Structure

- `docs.json` controls branding, navigation, and global site settings.
- Content is grouped by customer task: getting started, connecting, Studio, firmware, and troubleshooting.
- `sources/` contains reference material captured from the product website and is not published in the documentation navigation.
