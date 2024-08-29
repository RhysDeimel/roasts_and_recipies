# Roasts and Recipes
Home for all the recipes I've tried, and liked enough to keep. Figured it's worth having a self-hosted page,
rather than relying on external sources, because sometimes they disappear.

## Getting started
This is a [MkDocs](https://www.mkdocs.org/) site using [Material for MKDocs](https://squidfunk.github.io/mkdocs-material/)
dressed up as a blog. I wanted something simple, and low touch, because I'd much rather be cooking and doing better
things with my life, than maintaining a temperamental website.

### Overview
- Site-wide config can be found in `mkdocs.yml`
- Recipes are written as Markdown files in `docs/recipes`.
  These require front matter to be rendered correctly.
  See existing recipes for examples.
- Site template overrides are located in `overrides`


### Installing the project
```bash
virtualenv -p python3.11 venv
source venv/bin/activate
pip install -r requirements.txt
```

### Running the project
```
mkdocs serve
```

### Testing the project
```bash
pyspelling --config .pyspelling.yml
```


## TODO
- see if I can make the homepage a dynamically chosen random recipe
- have a random recipe / roulette feature
- create a helper function to automatically convert ingredients into tags (for better search)
