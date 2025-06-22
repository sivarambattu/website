# Personal blog

- Instructions for generating content
    - https://docs.getpelican.com/en/latest/tips.html#publishing-a-project-site-to-github-pages-from-a-branch

- Using `gh-pages` for content hosting
```
uv run pelican content -o output -s pelicanconf.py

uv run ghp-import output -b gh-pages

git push origin gh-pages
```

- Followed [this](https://docs.getpelican.com/en/stable/tips.html#copy-static-files-to-the-root-of-your-site) to keep custom domain

- Using `src` branch for storing content

- To run locally
```
uv run pelican --autoreload --listen
```
