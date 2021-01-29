# EKS-and-terraform 

## Amazon CLI 

You can get the Amazon CLI on [Docker-HUB](https://hub.docker.com/r/amazon/aws-cli)

```bash
docker run -it --rm -v ${pwd}:/work -w /work --entrypoint /bin/sh amazon/aws-cli:latest
``` 
Install handy tools 

```bash
yum install -y jq gzip tar git unzip wget
``` 
