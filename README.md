# Toolkit
A directory of Toolkits


## Building locally
The website is a set of static HTML pages that are automatically generated from the Jinja template file `template.html`. The static assets are in the `static` directory.

1. Clone the repo.
2. `pip install -r requirements.txt`
3. `python build.py` to generate the static site into the `site` directory.