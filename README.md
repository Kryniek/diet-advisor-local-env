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

# Install software
 - VNC Viewer
 - Python - https://wiki.python.org/moin/BeginnersGuide/Download
 - AWS CLI - https://docs.aws.amazon.com/cli/latest/userguide/install-windows.html (then configure it following this article https://docs.aws.amazon.com/cli/latest/userguide/cli-configure-quickstart.html)
# Add new submodule
```
git submodule add <REPOSITORY_URL>
```