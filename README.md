# Project Template for DDF projects

This is the [cookiecutter](https://cookiecutter.readthedocs.io/en/latest/readme.html) template
for DDF projects.

## Project Structure

```
.
├── README.md
├── datapackage.json
├── ddf--concepts.csv
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

install [ddf_utils](https://github.com/semio/ddf_utils), and just run `ddf new`
in the command line prompt. The program will prompt for project informations and
create the project for you.

Alternativly, you can install
[cookiecutter](https://github.com/cookiecutter/cookiecutter) and run
following command to create project with this template.

``` shell
$ cookiecutter https://github.com/Gapminder/ddf_project_template
```
