# docker-aws-cli

# Intro
1. just a clone version of https://github.com/anigeo/docker-awscli but i do maint a script for auto rebuild everything awscli released new version.

```
docker run -it --rm -v `pwd`:/root -v ~/.aws:/root/.aws -v /tmp/:/tmp/ -e i=$i -e ET=$ET -e AWSACCOUNT=$AWSACCOUNT -e AWS_ACCESS_KEY_ID=$AWS_ACCESS_KEY_ID -e AWS_SECRET_ACCESS_KEY=$AWS_SECRET_ACCESS_KEY -e AWS_DEFAULT_REGION=$AWS_DEFAULT_REGION sahsu/docker-awscli $*
```
