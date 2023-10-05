# data-science-project-template

[![Release](https://img.shields.io/github/v/release/LishuaiJing3/data-science-project-template)](https://img.shields.io/github/v/release/LishuaiJing3/data-science-project-template)
[![Build status](https://img.shields.io/github/actions/workflow/status/LishuaiJing3/data-science-project-template/main.yml?branch=main)](https://github.com/LishuaiJing3/data-science-project-template/actions/workflows/main.yml?query=branch%3Amain)
[![codecov](https://codecov.io/gh/LishuaiJing3/data-science-project-template/branch/main/graph/badge.svg)](https://codecov.io/gh/LishuaiJing3/data-science-project-template)
[![Commit activity](https://img.shields.io/github/commit-activity/m/LishuaiJing3/data-science-project-template)](https://img.shields.io/github/commit-activity/m/LishuaiJing3/data-science-project-template)
[![License](https://img.shields.io/github/license/LishuaiJing3/data-science-project-template)](https://img.shields.io/github/license/LishuaiJing3/data-science-project-template)

This is a template repository for Python projects that use Poetry for their dependency management.

- **Github repository**: <https://github.com/LishuaiJing3/data-science-project-template/>
- **Documentation** <https://LishuaiJing3.github.io/data-science-project-template/>

## Getting started with your project

First, create a repository on GitHub with the same name as this project, and then run the following commands:

``` bash
git init -b main
git add .
git commit -m "init commit"
git remote add origin git@github.com:LishuaiJing3/data-science-project-template.git
git push -u origin main
```

Finally, install the environment and the pre-commit hooks with 

```bash
make install
```

You are now ready to start development on your project! The CI/CD
pipeline will be triggered when you open a pull request, merge to main,
or when you create a new release.

To finalize the set-up for publishing to PyPi or Artifactory, see
[here](https://fpgmaas.github.io/cookiecutter-poetry/features/publishing/#set-up-for-pypi).
For activating the automatic documentation with MkDocs, see
[here](https://fpgmaas.github.io/cookiecutter-poetry/features/mkdocs/#enabling-the-documentation-on-github).
To enable the code coverage reports, see [here](https://fpgmaas.github.io/cookiecutter-poetry/features/codecov/).

## Releasing a new version



---

Repository initiated with [fpgmaas/cookiecutter-poetry](https://github.com/fpgmaas/cookiecutter-poetry).

## start project in dev container in VS code
- F1 or ctl + shift + p, search Dev Containers: clone repository in named volumns. 
- If you have github, type in the address for your github repo. If you use azure devops, type the repo name correspondingly.  
- create a new volumn-> you can come up your own name as you wish (e.g. ds-template)
- then write the target folder name. for example the data science project name that you use
- If you do not have a dev container config file defined, you can choose to use a template vs code provide, for example python with poetry or just pythpon. Then you can install other dependencies that you wish to have. 
- then the build process will start. 
