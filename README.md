# Alessandro Bombarda Portfolio

This is an [al-folio](https://github.com/alshedivat/al-folio) academic portfolio site.

## Local Build With Docker

```sh
docker compose run --rm jekyll bash -lc 'bundle exec jekyll build'
```

## Local Preview With Docker

```sh
docker compose up
```

Then open:

```text
http://localhost:8080
```

## Deploy

Push this folder as a GitHub repository and enable GitHub Pages. The included
`.github/workflows/deploy.yml` builds the site and deploys `_site` on pushes to
`main` or `master`.

Before publishing, adjust these in `_config.yml` if needed:

```yml
url: https://ale18v.github.io
baseurl: ""
```

For a project page such as `https://ale18v.github.io/al-folio-site`, set:

```yml
url: https://ale18v.github.io
baseurl: /al-folio-site
```
