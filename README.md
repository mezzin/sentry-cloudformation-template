# Sentry Cloudformation Template

This is a Cloudformation template for [Sentry](https://github.com/getsentry/sentry). 

[![Launch Stack](https://s3.amazonaws.com/cloudformation-examples/cloudformation-launch-stack.png)](https://us-east-1.console.aws.amazon.com/cloudformation/home?region=us-east-1#/stacks/create/review?templateURL=https://static-mezzin.s3.amazonaws.com/cloudformation/sentry-aws.template&stackName=Sentry)

## Included

 * Latest sentry
 * Supervisord
 * Nginx
 * PostgreSQL

## Parameters
  * SentryUserName 
  * SentryPassword
  * SentryEmail
  * DBUsername
  * DBName
  * DBPassword
  * KeyName
  * InstanceType
  * `SENTRY_KEY` was rendom genearted.
  
## Configurations
 
   * /home/ubuntu/.sentry/sentry.conf.py 
   
