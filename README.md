# rancher-compose-tools

Simple volume container that will contains rancher-compose and a few utilitary scripts to make jenkins pipelines easier.

## First time usage

```
docker run -i -v $HOME/.rancher:/root/.rancher/ adopteunops/rancher-cli:latest --url http://YOUR_RANCHER_MASTER_URL config
```
