# docker-create-react-app

A simple shell script to initialize a [create-react-app](https://github.com/facebookincubator/create-react-app) project with docker (no other dependencies needed!).

## Prerequisites
* [Install docker](https://github.com/docker/docker-install)
    * ```curl -fsSL get.docker.com -o get-docker.sh```
    * ```sh get-docker.sh```

## Installation
* Local installation
    * ```curl "https://raw.githubusercontent.com/mikebars/docker-create-react-app/develop/docker-create-react-app" -o docker-create-react-app```

* Global installation
    * ```mkdir -p $HOME/.docker-create-react-app/bin```
    * ```curl "https://raw.githubusercontent.com/mikebars/docker-create-react-app/develop/docker-create-react-app" -o $HOME/.docker-create-react-app/bin/docker-create-react-app```
    * ```chmod +x $HOME/.docker-create-react-app/bin/docker-create-react-app```
    * ```echo 'export DOCKER_CREATE_REACT_APP_PATH="$HOME/.docker-create-react-app"' >> $HOME/.zshrc```
        * (if using bash, replace `.zshrc` with `.bashrc`)
    * ```echo 'export PATH="$DOCKER_CREATE_REACT_APP_PATH/bin:$PATH"' >> $HOME/.zshrc```
        * (if using bash, replace `.zshrc` with `.bashrc`)

## Usage
* If installed locally:
    * ```sh docker-create-react-app <PROJECT_NAME>```
* If installed globally:
    * ```docker-create-react-app <PROJECT_NAME>```
