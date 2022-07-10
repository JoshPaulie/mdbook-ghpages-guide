# Book Config (book.toml)

Add the two specified lines to your `book.toml`

```toml
[book]
authors = ["..."]
language = "en"
multilingual = false
src = "src"
title = "..."

# Add these two lines 👇
[build]
build-dir = "docs"
```

If you've built your book, you'll need to delete the default `/book` directory & rebuild.

`mdbook build`