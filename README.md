# ACSONE Odoo project template

This is a [copier](pypi.org/project/copier/) template for use in ACSONE Odoo projects.

⚠️ This project is meant for ACSONE internal use. Things may change without notice. ⚠️

## How to use this template

### Prerequisites

`pipx install copier`

### Initializing a new project

`copier copy https://github.com/acsone/acsone-odoo-project-template {project-root-dir}`

This will ask questions and create the `{project-root-dir}` directory and initialize the
project inside it.

### Updating an existing project

Inside the project root, run `copier -f update`, or `copier update` if you want to
change the answers to some questions.

## How to use the generated project

See the generated [README](src/README.md.jinja).
