# recipe-runner
An automated method for testing large AutoPkg recipe repositories.

```
usage: recipe-runner [-h] [--skip SKIP] search_path

Tests the AutoPkg recipes at the specified path and compiles a status report
for your reference.

positional arguments:
  search_path  Path to search recursively for AutoPkg recipes.

optional arguments:
  -h, --help   show this help message and exit
  --skip SKIP  Recipe type (e.g. download, pkg, munki) to skip.
```

