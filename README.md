# git-archive-all action

![GitHub](https://img.shields.io/github/license/Jayrgo/git-archive-all-action?style=flat-square)

## Table of Contents

- [Inputs](#Inputs)
- [Usage](#Usage)
- [License](#License)

## Inputs
- **Required** `output`:
- **Optional** `args`: Arguments passed to git-archive-all. (Look at [Command line options](https://github.com/Kentzo/git-archive-all/blob/master/README.rst) for all arguments)

## Usage
```yaml
- uses: Jayrgo/git-archive-all-action@v1
  with:
    output: ''

    # Arguments passed to git-archive-all.
    # Default: 
    args: ''
```

# License

The scripts and documentation in this project are released under the [MIT License](LICENSE)
