# polygo review demo

A small app's worth of translations, used to watch [polygo](https://github.com/Na5co/polygo)
review a pull request.

`.github/workflows/i18n.yml` runs `polygo check` on every pull request with
`review: "true"`, so findings arrive as inline comments on the diff — and where the repair
is mechanical (a translator translated the placeholder *name*), as a suggested change you
commit with one click.

Open a pull request that edits a file in `locales/` and see for yourself.
