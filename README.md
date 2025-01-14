# jlbellido.github.io

## About
This is the personal blog built with Hugo (https://gohugo.io/), a static site generator. The used theme is 
Blowfish(https://blowfish.page/).  

It is following the Jamstack https://jamstack.org/ approach.

## Local setup

```shell
# Once the project is clones locally, ensure we have downloaded every git submodule:
# Source: https://git-scm.com/book/en/v2/Git-Tools-Submodules

$ git submodule init
$ git submodule update

# Up the docker containers:
$ docker compose up

# Useful commands are available in: https://docker.hugomods.com/docs/development/docker-compose/
```

## How to upgrade

### Hugo

**Update Github workflow:** Go to .github/workflows/hugo.yml and define the new version like:
```yaml
jobs:
  # Build job
  build:
    runs-on: ubuntu-latest
    env:
      HUGO_VERSION: 0.144.2
```

**Note:** Locally the latest versions is always pulled.

### Blowfish
```shell
# Soruce: https://blowfish.page/docs/installation/#update-using-git

$ git submodule update --remote --merge
```

## Documentation links:

- Hugo official site: https://gohugo.io/
- Hugo Docker images: https://docker.hugomods.com
- Blowfish theme: https://blowfish.page/
