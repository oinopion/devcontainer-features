# Dev Container Features

A collection of Development Containers Features.


## Features

Currently there's only one feature here: `mise`.

### `mise`

[Mise](https://mise.jdx.dev/) is a polyglot tool version manager. It replaces tools like asdf, nvm, pyenv, rbenv, etc.


```jsonc
{
    "image": "mcr.microsoft.com/devcontainers/base:ubuntu",
    "features": {
        "ghcr.io/oinopion/devcontainer-features/mise:0": {}
    }
}
```

```bash
$ mise use node@lts
mise node@20.15.0 ✓ installed

$ node --version
v20.15.0
```

## Repo and it's structure

This repo has been generated from the [feature-starter](https://github.com/devcontainers/feature-starter) template.
