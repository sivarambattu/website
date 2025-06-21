# A personal blog

## Instructions for generating content
- https://docs.getpelican.com/en/latest/tips.html#publishing-a-project-site-to-github-pages-from-a-branch

```
uv run pelican content -o output -s pelicanconf.py

uv run ghp-import output -b gh-pages

git push origin gh-pages
```