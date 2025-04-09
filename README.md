# Cookiecutter template for Python projects

This template includes everything you need to start a new Python project:

- devbox
- direnv
- taskfile
- python
- uv
- black
- prettier
- sqlfluff
- pre-commit
- nbstripout
- devcontainer

## Future additions

- github workflows
- dependabot
- renovate?

## Requirements

- [cookiecutter](https://www.cookiecutter.io/)

## Usage
  
- To use the template from a local directory, run:

```sh
cookiecutter <location-of-current-dir>/cookiecutter-template-python/
```

- To use the template remotely, run:

```sh
cookiecutter gh:legomb/cookiecutter-template-python
```

This will prompt some questions:

- `new_directory_name`: Name of the directory to be created based on this template
- `project_name`: Name of the project
