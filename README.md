# zivue-landing

Static landing page for Zivue.

Deployed at:

```text
https://zivue.github.io/zivue-landing/
```

## Structure

```text
docs/
  index.html
  favicon.svg
  robots.txt
  sitemap.xml
  assets/
    css/style.css
    images/
```

The site is plain HTML and CSS. There is no build step and no JavaScript framework.

## Local Preview

Serve the `docs/` directory with any static file server, for example:

```sh
python3 -m http.server 8080 --directory docs
```

Then open:

```text
http://localhost:8080
```

## Assets

CSS lives in `docs/assets/css/style.css`.

Images and social preview assets live in `docs/assets/images/`.

GitHub Pages serves `docs/` as the site root, so `docs/assets/css/style.css` is available publicly as:

```text
https://zivue.github.io/zivue-landing/assets/css/style.css
```
