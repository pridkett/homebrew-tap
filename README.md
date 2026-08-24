# pridkett/homebrew-tap

Homebrew formulae for [Patrick Wagstrom](https://github.com/pridkett)'s tools.

```bash
brew install pridkett/tap/slidepack
```

`brew` expands `pridkett/tap` to this repository, so no explicit `brew tap` is
needed.

## Formulae

| Formula | What it is |
|---|---|
| [`slidepack`](https://github.com/pridkett/slidepack) | Packs a presentation directory into a single self-contained HTML file, and expands it back again. |

## How these are maintained

Formulae here are **generated, not hand-edited**. Each project's release
workflow renders its formula from a template in its own repository and pushes
the result here after a tagged release has been published and verified. Edits
made directly in this repository will be overwritten by the next release.

For `slidepack`, the template lives at
[`.github/homebrew/slidepack.rb.tmpl`](https://github.com/pridkett/slidepack/blob/main/.github/homebrew/slidepack.rb.tmpl)
and is rendered by
[`scripts/render-formula.sh`](https://github.com/pridkett/slidepack/blob/main/scripts/render-formula.sh).
