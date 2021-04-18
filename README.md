# Setup local environment

- Clone this repository
- Init and update submodules
```
git submodule update --init --recursive --remote
git submodule foreach 'git checkout main; git pull --all'
```
- Start docker
```
docker-compose up -d
```