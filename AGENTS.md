# Bear Metal - Hugo Commands Reference

## Local Development (Hugo v0.165.x)

```bash
hugo                             # Build production static site into public/
hugo --minify                    # Minified build for production deploy
hugo server                      # Start dev server at http://localhost:1313 (watch mode, hot reload)
hugo server -D                   # Watch mode + include draft/pending-future posts
```

## Testing Checklist

- [ ] Run `hugo server` and verify site loads at `http://localhost:1313`
- [ ] Check that all page content renders correctly with ananke theme
- [ ] Preview drafts with `hugo server -D` but don't commit draft posts
- [ ] Run `hugo` to generate production output in `public/` and verify it looks correct before pushing to main

## Adding Authors to Posts

Add `author` under `[params]` in frontmatter to display author name on each post:

```yaml
+++
date = 'YYYY-MM-DDTHH:MM:SS-07:00'
title = 'Post Title'
slug = 'post-slug'

[params]
  author = 'Brandon Abear'
+++
```
