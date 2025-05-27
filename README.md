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
