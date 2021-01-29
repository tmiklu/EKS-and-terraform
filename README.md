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

## Login to AWS 

```bash
# create access keys in aws 
aws configure 

AWS Access Key ID [None]: XXXXXX 
AWS Secret Access Key [None]: XXXXXX 
Default region name [None]: <your-choice> 
Default output format [None]: json 
```

