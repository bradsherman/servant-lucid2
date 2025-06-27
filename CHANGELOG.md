# 0.9.0.7 (unreleased)

- Support for GHC 9.12 (lucid >=2.11.20250303, servant >=0.20.3.0)

# 0.9

- Also accept content type without character set i.e `text/html`

# 0.8.1

- Support `servant-0.14`
- Add `Lucid.Servant` with `safeHref_` function and its variants.

# 0.8

- Only single `MimeRender HTML a` instance. `lucid-2.9.8` has `ToHtml (HtmlT m a)` instance.
