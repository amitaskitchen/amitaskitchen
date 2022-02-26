# amitaskitchen

Website at: https://amitaskitchen.github.io

## Setup

1. Setup git repo for github pages: from https://pages.github.com
    1. `amitaskitchen` github org is owned by account `ajay610@gmail.com`
1. Use homebrew to setup `ruby` and `jekyll`: https://jekyllrb.com/docs/installation/macos/
1. Setup `jekyll-admin`: https://jekyll.github.io/jekyll-admin/
1. Setup custom URL: https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site

## Create site
```bash
git clone ...repo...
cd ...repo...
mkdir tmp
cd tmp
jekyll new amitas-kitchen
cd amitas-kitchen
cp -rav * ../..
cd ../..
bundle exec jekyll serve
```

## Run local

```bash
bundle install
bundle exec jekyll serve
```

This launches websites at: http://127.0.0.1:4000/
