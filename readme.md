# DevOps CD/CI

This is an example of CD/CI environment with docker compose, it's based on jenkins-gitlab-artifactory tools.

## Installation

After clone this repository you need to create the directories to bind mounts:

```
mkdir artifactory
chmod 777 artifactory/

mkdir gitlab
mkdir gitlab/config
mkdir gitlab/logs
mkdir gitlab/data

mkdir gitlab
mkdir gitlab/config
mkdir gitlab/logs
mkdir gitlab/data

mkdir jenkins
mkdir jenkins/data
mkdir jenkins/home
```

Now you can run docker-compose:

```bash
docker-compose up
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.
