# terraform-qa

This action will apply [pre-commit-terraform](https://github.com/antonbabenko/pre-commit-terraform) and [pre-commit-hooks](https://github.com/pre-commit/pre-commit-hooks).

It will also apply the linting rules and commit them in the same branch where the action is executed. When only existing files are linted, or documentation is generated, the workflow will appear as green.
