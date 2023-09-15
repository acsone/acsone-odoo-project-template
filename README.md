# ACSONE Odoo project template

This is a [copier](https://pypi.org/project/copier/) template for use in ACSONE Odoo projects.

The aim of this template is to organize an Odoo project as a regular Python project,
using modern Python standards and good practices.

⚠️ This project is meant for ACSONE internal use. Things may change without notice. Feel
free to draw inspiration. Feedback is welcome in
[discussions](https://github.com/acsone/acsone-odoo-project-template/discussions). ⚠️

## How to use this template

### Prerequisites

`pipx install copier`

### Initializing a new project

`copier copy git+https://github.com/acsone/acsone-odoo-project-template {project-root-dir}`

This will ask questions and create the `{project-root-dir}` directory and initialize the
project inside it.

### Updating an existing project

Inside the project root, run `pipx run copier update  -f`, or `pipx run copier update` if you want to
change the answers to some questions.

## How to use the generated project

See the generated [README](src/README.md.jinja).
