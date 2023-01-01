# Website using just-the-docs-template

## Custom implementation of protected pages

Created new layout `protected.html` that lets you password protect specific pages. HTML needs to be run through https://robinmoisson.github.io/staticrypt/ - > salt and encrypted_msg should be added to .md file as params

Replace head tags from local: 

```
<link rel="shortcut icon" href="/just-the-docs-template/favicon.ico" type="image/x-icon">
<link rel="stylesheet" href="/just-the-docs-template/assets/css/just-the-docs-default.css">
<script src="/just-the-docs-template/assets/js/vendor/lunr.min.js"></script> <script src="/just-the-docs-template/assets/js/just-the-docs.js"></script> 
<link rel="canonical" href="https://domantax.github.io/just-the-docs-template/just-the-docs-template/en/" />
<meta property="og:url" content="https://domantax.github.io/just-the-docs-template/just-the-docs-template/en/" />
<script type="application/ld+json"> {"@context":"https://schema.org","@type":"WebPage","description":"Super website","headline":"Welcome","url":"https://domantax.github.io/just-the-docs-template/just-the-docs-template/en/"}</script>
```


## Building and previewing your site locally

Assuming [Jekyll] and [Bundler] are installed on your computer:

1.  Change your working directory to the root directory of your site.

2.  Run `bundle install`.

3.  Run `bundle exec jekyll serve` to build your site and preview it at `localhost:4000`.

    The built site is stored in the directory `_site`.
