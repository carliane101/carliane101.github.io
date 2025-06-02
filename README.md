# SeaJay Env site build instructions

#### Locally

```shell
hugo --minify --destination public/repo-name
cd public
python3 -m http.server
```

#### GitHub

There is a github action that should build into the gh-pages branch.

#### TODO

- Add instructions on configuring GitHub Pages to use this setup.
- Remove toc from reports (other pages?)
- Remove the automatic header on pages (a header from the markdown will be used instead)
- Hover link text color should change
