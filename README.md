# Continuous Integration example for Python

[![Python Package using Conda](https://github.com/dacb/codebase_github_actions/actions/workflows/python-package-conda.yml/badge.svg)](https://github.com/dacb/codebase_github_actions/actions/workflows/python-package-conda.yml)

[![Coverage Status](https://coveralls.io/repos/github/dacb/codebase_github_actions/badge.svg?branch=main)](https://coveralls.io/github/dacb/codebase_github_actions?branch=main)

To get started, click on "Actions" tab in the GitHub repository page.  This will open a page allowing you to select from default actions or to create your own.  We are developing a Python package and want to use `conda` (from Anaconda) for package management. Select 'Python Package using Anaconda' by GitHub Actions by clicking the 'Configure' button. This uses a template that will work for most Python packages.

After doing this, you will be taken to an editor in GitHub that will allow you to modify the default template from within the web page. 'Start Commit' will commit these files to your repository. To edit them in the future, you can `git pull` the repo and edit the files locally before `add`, `commit`, `push`.

Notice the file you are editing in your repo is located in `.github/workflows`.  YML (`.yml`) files in this directory in your repo contain instructions on how to build, test, and deploy your code.

The format for these workflow files is described [here](https://docs.github.com/en/actions/using-workflows/workflow-syntax-for-github-actions).

Everyone loves badges, especially Girl Scouts!  I do too!  Let's add the build bage to the README.md.  Click on your 'Action' that you want a badge for to open it's page.  Towards the right hand side is an ellipses. Clocking on it brings open a context menu where you can select 'Create status badge.'  Copying the code here or editing the default can give you code to put in your README.md that will show a build status badge.  See the top of this file for examples.
