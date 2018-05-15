# Change Log

## [awscli-1.15.20](https://github.com/sahsu/docker-aws-cli/tree/awscli-1.15.20) (2018-05-15)
[Full Changelog](https://github.com/sahsu/docker-aws-cli/compare/aws-cli-1.15.20...awscli-1.15.20)

## [aws-cli-1.15.20](https://github.com/sahsu/docker-aws-cli/tree/aws-cli-1.15.20) (2018-05-15)
[Full Changelog](https://github.com/sahsu/docker-aws-cli/compare/enbale-auto-diary-check...aws-cli-1.15.20)

## [enbale-auto-diary-check](https://github.com/sahsu/docker-aws-cli/tree/enbale-auto-diary-check) (2018-05-15)
[Full Changelog](https://github.com/sahsu/docker-aws-cli/compare/1.9.4...enbale-auto-diary-check)

## [1.9.4](https://github.com/sahsu/docker-aws-cli/tree/1.9.4) (2015-10-26)


# Intro
1. sahsu/docker-aws-cli is now support automatic upgrade, check diary. 
1. just a clone version of https://github.com/anigeo/docker-awscli

```
docker run -it --rm -v `pwd`:/root -v ~/.aws:/root/.aws -v /tmp/:/tmp/ -e i=$i -e ET=$ET -e AWSACCOUNT=$AWSACCOUNT -e AWS_ACCESS_KEY_ID=$AWS_ACCESS_KEY_ID -e AWS_SECRET_ACCESS_KEY=$AWS_SECRET_ACCESS_KEY -e AWS_DEFAULT_REGION=$AWS_DEFAULT_REGION sahsu/docker-awscli $*
```

1. if you using ZSH, you can use this as FUNCTION:
```
function aws () { d run -it --rm -v `pwd`:/root -v ~/.aws:/root/.aws -v /tmp/:/tmp/ -e i=$i -e ET=$ET -e "AWS_ACCESS_KEY_ID=$AWS_ACCESS_KEY_ID" -e "AWS_SECRET_ACCESS_KEY=$AWS_SECRET_ACCESS_KEY" -e "AWS_DEFAULT_REGION=$AWS_DEFAULT_REGION" sahsu/docker-aws-cli $* }
```
2. and use like `aws --version` to check latest version.
3. I hope you like and sahsu/docker-aws-cli, if you don't mind, can you help star docker hub & github link? Thanks!
