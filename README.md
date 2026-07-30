# zivue-landing

Static landing page for Zivue.

## Structure

```text
public/
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

Serve the `public/` directory with any static file server, for example:

```sh
python3 -m http.server 8080 --directory public
```

Then open:

```text
http://localhost:8080
```

## Assets

CSS lives in `public/assets/css/style.css`.

Images and social preview assets live in `public/assets/images/`.
