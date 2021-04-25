# Setup local environment
### Prepare repositories
- Clone this repository
- Init and update submodules
```
git submodule update --init --recursive --remote
git submodule foreach 'git checkout main; git pull --all'
```
### Run docker containers
- Export environment variable
```
export AWS_ACCESS_KEY_ID=<YOUR_AWS_ACCESS_KEY>
```
- Start docker
```
docker compose up -d
```
# Add new submodule
```
git submodule add <REPOSITORY_URL>
```