# Project Template for DDF projects

This is the [cookiecutter](https://cookiecutter.readthedocs.io/en/latest/readme.html) template
for DDF projects.

## Project Structure

```
.
├── README.md
└── etl
    ├── notebooks
    ├── recipes
    │   ├── _template.yaml
    │   └── translation_dictionaries
    ├── requirements.txt
    ├── scripts
    │   └── etl.py
    └── source
```

## Usage

install [ddf_utils](https://github.com/semio/ddf_utils), and just run `ddfnew.py`
in the command line prompt. The program will prompt for project informations and
create the project for you.

