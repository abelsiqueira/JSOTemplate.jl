# JSO Template.jl

This is a template/skeleton for JSO packages.
It should be used for new packages and to update the configuration of packages.

## How to install

1. Install [copier](https://copier.readthedocs.io).

2. Run copier with this template

```bash
copier copy https://github.com/JuliaSmoothOptimizers/{{ PackageName }}.jl PackageName.jl
```

### Things to manually change

- Project.toml: name and uuid
- LICENSE.md: Check if MPL-v2 is the correct choice
