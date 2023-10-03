# fn-pylint-action

A GitHub Action to run `pylint`

This action executes [Pylint](https://pylint.pycqa.org/en/latest) on the
codebase and reports a summary in the action log and annotations on
source lines of a PR.

It is assumed that `pylint` is already installed in the environment.

## Inputs

## `pylint-args`

**Required** The arguments to pass to `pylint`, as if on a command line.

## Example usage
```yaml
uses: TheFoundryVisionmongers/fn-pylint-action@v1
with:
  pylint-args: "--ignore=C,I,R --rcfile=pyproject.toml my_project tests"
```

## License

This project is licence under the [Apache 2.0 license](LICENSE), and
contains dependencies licence as per [dist/licenses.txt](dist/licenses.txt).
