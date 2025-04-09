# Cookiecutter template for Python projects

This template includes everything you need to start a new Python project:

- [devbox](https://www.jetify.com/devbox)
- [direnv](https://direnv.net/)
- [taskfile](https://taskfile.dev/)
- [Python](https://www.python.org/)
- [uv](https://docs.astral.sh/uv/)
- [Black](https://github.com/psf/black)
- [Prettier](https://prettier.io/)
- [SQLFluff](https://sqlfluff.com/)
- [pre-commit](https://pre-commit.com/)
- [nbstripout](https://github.com/kynan/nbstripout)
- [devcontainer](https://code.visualstudio.com/docs/devcontainers/containers)

## Future additions

- build + test github workflows
- [dependency bot support](https://docs.astral.sh/uv/guides/integration/dependency-bots/) (renovate/dependabot)

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
