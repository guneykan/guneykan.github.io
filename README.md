# guneykan.github.io

Personal research website for Guneykan Ozgul.

The site is built with Jekyll, but its layouts and visual system are custom to this repository. It does not use a packaged or remote theme.

## Local development

```sh
bundle install
bundle exec jekyll serve
```

The homepage at `/` combines the biography and publications. Edit the biography in `home.md` and the paper list in `_data/publications.yml`. The existing `/home/` and `/papers/` URLs remain available. Page structure is in `_layouts/`, shared page content is in `_includes/`, and the visual styles are in `_sass/_style.scss`. The website does not require JavaScript.
